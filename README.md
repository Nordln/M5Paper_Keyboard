# M5Paper_Keyboard
M5Paper_Keyboard�́AM5Paper�œ����V���A��I/F�̃L�[�{�[�h�ł��B<br>
BLE�L�[�{�[�h�ɂ��Ή����܂����B<br><br>
����́AM5Paper_FactoryTest�̃L�[�{�[�h�̏����𔲂��o���ĉ����������̂ł��B<br>
�x�[�X�ɂ����I���W�i���͂�����B<br>
M5Paper_FactoryTest <https://github.com/m5stack/M5Paper_FactoryTest><br>

![�摜1](images/image1.png)<br><br>

### �K�v�ȕ� ###
* [M5Paper](http://www.m5stack.com/ "Title")<br>
* Arduino IDE (1.8.13�œ���m�F�����܂����B)<br>
* [Arduino core for the ESP32](https://github.com/espressif/arduino-esp32 "Title")
* [M5Paper Library](https://github.com/m5stack/M5EPD "Title")
* [NimBLE-Arduino Library](https://github.com/h2zero/NimBLE-Arduino "Title") (BLE�L�[�{�[�h�Ƃ��Ďg���ꍇ�j
* [ESP32 NimBLE Keyboard library](https://github.com/wakwak-koba/ESP32-NimBLE-Keyboard "Title") (BLE�L�[�{�[�h�Ƃ��Ďg���ꍇ�j
<br>

���C�u������Arduino IDE��[�X�P�b�` | ���C�u�������C���N���[�h |���C�u�������Ǘ�...] ����C���X�g�[������ƊȒP�ł��B

### �V���A���|�[�g�̎d�l ###
* M5Paper��PORT C���g�p���܂��B�ݒ�͈ȉ��̒ʂ�B<br>
    // Serial2.begin(unsigned long baud, uint32_t config, int8_t rxPin, int8_t txPin, bool invert)<br>
    Serial2.begin(115200, SERIAL_8N1, 19, 18);

### �⑫ ###
* �d����؂�ꍇ�́AM5Paper�̗����́hBATTERY OFF�h�{�^�����g�p���Ă��������B<br>
* "Fn"�L�[�͖��g�p�ł��̂ŋ@�\�g�����Ɏg�p���Ă��������B<br><br>

---

M5Paper_Keyboard�̓���m�F�p��M5Stack�v���O����(M5Stack_Serial2_test)��p�ӂ��Ă���܂��B<br>

![�摜2](images/image2.png)<br><br>

### �K�v�ȕ� ###
* [M5Stack](http://www.m5stack.com/ "Title") (Fire�œ���m�F�����܂����B)<br>
* Arduino IDE (1.8.13�œ���m�F�����܂����B)<br>
* [Arduino core for the ESP32](https://github.com/espressif/arduino-esp32 "Title")<br>
* [M5Stack Library](https://github.com/m5stack/M5Stack "Title")
* [LovyanGFX���C�u����](https://github.com/lovyan03/LovyanGFX "Title")

���C�u������Arduino IDE��[�X�P�b�` | ���C�u�������C���N���[�h |���C�u�������Ǘ�...] ����C���X�g�[������ƊȒP�ł��B

### �V���A���|�[�g�̎d�l ###
* M5Stack��PORT C���g�p���܂��B�ݒ�͈ȉ��̒ʂ�B<br>
    // Serial2.begin(unsigned long baud, uint32_t config, int8_t rxPin, int8_t txPin, bool invert)<br>
    Serial2.begin(115200, SERIAL_8N1, 16, 17);<br><br>
���ӁFM5Stack Fire���g�p����ꍇ��PSRAM�𖳌��ɂ���K�v������܂��B<br><br>
![�摜3](images/image3.png)<br><br>

---

### �N���X�P�[�u���̍��� ###
* M5StackSerial2_test��M5Stack��M5Paper_Keyboard��ڑ�����ɂ̓N���X�P�[�u�����K�v�ł��B<br>
�Ԃ̃P�[�u��(�d���j�𔲂��A���Ɖ��F�̃P�[�u�����N���X�����܂��B<br><br>
![�摜4](images/image4.png)<br><br>
* �R�l�N�^�̒܂̕������������Ŏ����グ�Ă��΃P�[�u���͊ȒP�ɔ����܂��B <br><br>
![�摜5](images/image5.png)<br><br>
<br>

---

### BLE�L�[�{�[�h�Ƃ��Ďg���ꍇ ###

* "keyboard_config.h"��"#define USE_BLE_KEYBOARD"�̃R�����g���O���ăr���h���܂��B<br><br>
![�摜6](images/image6.png)<br><br>
* "M5Paper-Keyboard"�ƃy�A�����O���܂��B
* ���p/�S�p�̐؂�ւ����@(�m�F��������)<br>
iPhone11(iOS14) �F [Ctrl] + [Space]<br>
Android(FIRE HD 8) �F [Shift] + [Space]<br>
Windows 10 �F [Alt] + [`]<br>
<br><br>

