# RoboMaster SDK Cheat Sheet (полный, ориентирован на управление роботами)

> Просканировано Python-файлов: **285**, в cheat sheet включены контрольные модули/примеры: **230**.

## Инициализация, подключение и завершение

- `examples.05_vision.01_marker:MarkerInfo.__init__` — описание отсутствует
- `examples.05_vision.02_line:PointInfo.__init__` — описание отсутствует
- `examples.05_vision.03_person:PersonInfo.__init__` — описание отсутствует
- `examples.05_vision.04_robot:RobotInfo.__init__` — описание отсутствует
- `examples.05_vision.05_gesture:GestureInfo.__init__` — описание отсутствует
- `examples.15_multi_robot.multi_ep.03_six_ep_demo:ep_arm_initial_pos` — ep_arm 初始云台位置
- `examples.15_multi_robot.multi_ep.03_six_ep_demo:ep_gimbal_initial_pos` — ep_gimbal 初始云台位置
- `examples.plaintext_sample_code.RoboMasterEP.connection.network.robot_connection:RobotConnection.__init__` — описание отсутствует
- `examples.plaintext_sample_code.RoboMasterEP.connection.network.robot_connection:RobotConnection.close` — Close the connection
- `examples.plaintext_sample_code.RoboMasterEP.connection.network.robot_connection:RobotConnection.start_audio_recv` — описание отсутствует
- `examples.plaintext_sample_code.RoboMasterEP.connection.network.robot_connection:RobotConnection.start_video_recv` — описание отсутствует
- `examples.plaintext_sample_code.RoboMasterEP.connection.network.robot_connection:RobotConnection.stop_audio_recv` — описание отсутствует
- `examples.plaintext_sample_code.RoboMasterEP.connection.network.robot_connection:RobotConnection.stop_video_recv` — описание отсутствует
- `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.tests.conftest:Capture.__init__` — описание отсутствует
- `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.tests.conftest:Output.__init__` — описание отсутствует
- `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.tests.conftest:SanitizedString.__init__` — описание отсутствует
- `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.tests.test_class:test_brace_initialization` — Tests that simple POD classes can be constructed using C++11 brace initialization
- `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.tests.test_embed.test_interpreter:DerivedWidget.__init__` — описание отсутствует
- `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.tests.test_factory_constructors:test_init_factory_alias` — Tests py::init_factory() wrapper with value conversions and alias types
- `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.tests.test_factory_constructors:test_init_factory_basic` — Tests py::init_factory() wrapper around various ways of returning the object
- `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.tests.test_factory_constructors:test_init_factory_casting` — Tests py::init_factory() wrapper with various upcasting and downcasting returns
- `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.tests.test_factory_constructors:test_init_factory_dual` — Tests init factory functions with dual main/alias factory functions
- `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.tests.test_factory_constructors:test_init_factory_signature` — описание отсутствует
- `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.tests.test_numpy_array:test_initializer_list` — описание отсутствует
- `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.tests.test_sequences_and_iterators:allclose` — описание отсутствует
- `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.tests.test_sequences_and_iterators:isclose` — Like math.isclose() from Python 3.5
- `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.tests.test_virtual_functions:test_alias_delay_initialization1` — `A` only initializes its trampoline class when we inherit from it
- `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.tests.test_virtual_functions:test_alias_delay_initialization2` — `A2`, unlike the above, is configured to always initialize the alias
- `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.tools.mkdoc:ExtractionThread.__init__` — описание отсутствует
- `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.tests.conftest:Capture.__init__` — описание отсутствует
- `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.tests.conftest:Output.__init__` — описание отсутствует
- `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.tests.conftest:SanitizedString.__init__` — описание отсутствует
- `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.tests.test_class:test_brace_initialization` — Tests that simple POD classes can be constructed using C++11 brace initialization
- `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.tests.test_embed.test_interpreter:DerivedWidget.__init__` — описание отсутствует
- `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.tests.test_factory_constructors:test_init_factory_alias` — Tests py::init_factory() wrapper with value conversions and alias types
- `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.tests.test_factory_constructors:test_init_factory_basic` — Tests py::init_factory() wrapper around various ways of returning the object
- `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.tests.test_factory_constructors:test_init_factory_casting` — Tests py::init_factory() wrapper with various upcasting and downcasting returns
- `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.tests.test_factory_constructors:test_init_factory_dual` — Tests init factory functions with dual main/alias factory functions
- `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.tests.test_factory_constructors:test_init_factory_signature` — описание отсутствует
- `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.tests.test_numpy_array:test_initializer_list` — описание отсутствует
- `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.tests.test_sequences_and_iterators:allclose` — описание отсутствует
- `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.tests.test_sequences_and_iterators:isclose` — Like math.isclose() from Python 3.5
- `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.tests.test_virtual_functions:test_alias_delay_initialization1` — `A` only initializes its trampoline class when we inherit from it
- `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.tests.test_virtual_functions:test_alias_delay_initialization2` — `A2`, unlike the above, is configured to always initialize the alias
- `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.tools.mkdoc:ExtractionThread.__init__` — описание отсутствует
- `examples.plaintext_sample_code.RoboMasterEP.stream.python_stream_liveview.liveview:RobotLiveview.__init__` — описание отсутствует
- `examples.plaintext_sample_code.RoboMasterEP.stream.python_stream_liveview.liveview:RobotLiveview.close` — описание отсутствует
- `src.multi_robomaster.multi_group:RMGroup.__init__` — описание отсутствует
- `src.multi_robomaster.multi_group:RobotGroupBase.__init__` — описание отсутствует
- `src.multi_robomaster.multi_group:RobotGroupBase.initialize` — описание отсутствует
- `src.multi_robomaster.multi_group:SingleDroneInGroup.__init__` — описание отсутствует
- `src.multi_robomaster.multi_group:SingleDroneInGroup.close` — описание отсутствует
- `src.multi_robomaster.multi_group:TelloGroup.__init__` — описание отсутствует
- `src.multi_robomaster.multi_group:TelloGroup.init` — описание отсутствует
- `src.multi_robomaster.multi_module:MultiAction.__init__` — описание отсутствует
- `src.multi_robomaster.multi_module:MultiModule.__init__` — описание отсутствует
- `src.multi_robomaster.multi_module:MultiRmModule.__init__` — описание отсутствует
- `src.multi_robomaster.multi_module:MultiRmModule.close` — gripper
- `src.multi_robomaster.multi_module:TelloAction.__init__` — описание отсутствует
- `src.multi_robomaster.multi_module:TelloDispatcher.__init__` — описание отсутствует
- `src.multi_robomaster.multi_robot:MultiDrone.__init__` — описание отсутствует
- `src.multi_robomaster.multi_robot:MultiDrone.close` — описание отсутствует
- `src.multi_robomaster.multi_robot:MultiDrone.initialize` — описание отсутствует
- `src.multi_robomaster.multi_robot:MultiEP.__init__` — описание отсутствует
- `src.multi_robomaster.multi_robot:MultiEP.initialize` — scan all robots and init its
- `src.multi_robomaster.multi_robot:MultiRobotBase.__init__` — описание отсутствует
- `src.multi_robomaster.multi_robot:MultiRobotBase.close` — описание отсутствует
- `src.multi_robomaster.multi_robot:MultiRobotBase.initialize` — scan all robots and init its
- `src.multi_robomaster.tool:TelloClient.__init__` — описание отсутствует
- `src.multi_robomaster.tool:TelloClient.close` — описание отсутствует
- `src.multi_robomaster.tool:TelloClient.start` — описание отсутствует
- `src.multi_robomaster.tool:TelloConnection.__init__` — описание отсутствует
- `src.multi_robomaster.tool:TelloConnection.close` — описание отсутствует
- `src.multi_robomaster.tool:TelloConnection.pre_close` — описание отсутствует
- `src.multi_robomaster.tool:TelloConnection.start` — описание отсутствует
- `src.multi_robomaster.tool:TelloProtocol.__init__` — описание отсутствует
- `src.multi_robomaster.tool:TelloProtocol.init` — описание отсутствует
- `src.multi_robomaster.tool:TelloStatus.__init__` — описание отсутствует
- `src.multi_robomaster.tool:TelloThread.__init__` — описание отсутствует
- `src.robomaster.action:Action.__init__` — описание отсутствует
- `src.robomaster.action:ActionDispatcher.__init__` — описание отсутствует
- `src.robomaster.action:ActionDispatcher.initialize` — описание отсутствует
- `src.robomaster.action:TextAction.__init__` — описание отсутствует
- `src.robomaster.action:_AutoRegisterAction.__init__` — описание отсутствует
- `src.robomaster.ai_module:AiModule.__init__` — описание отсутствует
- `src.robomaster.ai_module:AiModule.init_ai_module` — описание отсутствует
- `src.robomaster.ai_module:AiModuleEvent.__init__` — описание отсутствует
- `src.robomaster.ai_module:TelloAI.__init__` — описание отсутствует
- `src.robomaster.ai_module:TelloAIInfoSubject.__init__` — описание отсутствует
- `src.robomaster.armor:Armor.__init__` — описание отсутствует
- `src.robomaster.armor:ArmorHitEvent.__init__` — описание отсутствует
- `src.robomaster.armor:IrHitEvent.__init__` — описание отсутствует
- `src.robomaster.battery:Battery.__init__` — описание отсутствует
- `src.robomaster.battery:BatterySubject.__init__` — описание отсутствует
- `src.robomaster.battery:TelloBatInfoSubject.__init__` — описание отсутствует
- `src.robomaster.battery:TelloBattery.__init__` — описание отсутствует
- `src.robomaster.blaster:Blaster.__init__` — описание отсутствует
- `src.robomaster.camera:Camera.__init__` — описание отсутствует
- `src.robomaster.camera:Camera.start_video_stream` — описание отсутствует
- `src.robomaster.camera:Camera.stop_video_stream` — описание отсутствует
- `src.robomaster.camera:EPCamera.__init__` — описание отсутствует
- `src.robomaster.camera:EPCamera.start_audio_stream` — 开启音频流
- `src.robomaster.camera:EPCamera.start_video_stream` — 开启视频流
- `src.robomaster.camera:EPCamera.stop` — 停止
- `src.robomaster.camera:EPCamera.stop_audio_stream` — 停止音频流
- `src.robomaster.camera:EPCamera.stop_video_stream` — 停止视频流
- `src.robomaster.camera:TelloCamera.__init__` — описание отсутствует
- `src.robomaster.camera:TelloCamera.start_video_stream` — 开启视频流
- `src.robomaster.camera:TelloCamera.stop` — описание отсутствует
- `src.robomaster.camera:TelloCamera.stop_video_stream` — описание отсутствует
- `src.robomaster.chassis:AttiInfoSubject.__init__` — описание отсутствует
- `src.robomaster.chassis:Chassis.__init__` — описание отсутствует
- `src.robomaster.chassis:Chassis._auto_stop_timer` — описание отсутствует
- `src.robomaster.chassis:Chassis.stop` — описание отсутствует
- `src.robomaster.chassis:ChassisModeSubject.__init__` — описание отсутствует
- `src.robomaster.chassis:ChassisMoveAction.__init__` — описание отсутствует
- `src.robomaster.chassis:EscSubject.__init__` — описание отсутствует
- `src.robomaster.chassis:ImuSubject.__init__` — описание отсутствует
- `src.robomaster.chassis:PositionSubject.__init__` — описание отсутствует
- `src.robomaster.chassis:SaStatusSubject.__init__` — описание отсутствует
- `src.robomaster.chassis:SbusSubject.__init__` — описание отсутствует
- `src.robomaster.chassis:VelocitySubject.__init__` — описание отсутствует
- `src.robomaster.client:Client.__init__` — описание отсутствует
- `src.robomaster.client:Client.initialize` — описание отсутствует
- `src.robomaster.client:Client.start` — описание отсутствует
- `src.robomaster.client:Client.stop` — описание отсутствует
- `src.robomaster.client:EventIdentify.__init__` — описание отсутствует
- `src.robomaster.client:MsgHandler.__init__` — описание отсутствует
- `src.robomaster.client:TextClient.__init__` — описание отсутствует
- `src.robomaster.client:TextClient.initialize` — описание отсутствует
- `src.robomaster.client:TextClient.start` — описание отсутствует
- `src.robomaster.client:TextClient.stop` — описание отсутствует
- `src.robomaster.config:Config.__init__` — описание отсутствует
- `src.robomaster.conn:BaseConnection.__init__` — описание отсутствует
- `src.robomaster.conn:BaseConnection.close` — описание отсутствует
- `src.robomaster.conn:Connection.__init__` — описание отсутствует
- `src.robomaster.conn:ConnectionHelper.__init__` — описание отсутствует
- `src.robomaster.conn:ConnectionHelper.wait_for_connection` — описание отсутствует
- `src.robomaster.conn:FtpConnection.__init__` — описание отсутствует
- `src.robomaster.conn:FtpConnection.connect` — описание отсутствует
- `src.robomaster.conn:FtpConnection.stop` — описание отсутствует
- `src.robomaster.conn:SdkConnection.__init__` — описание отсутствует
- `src.robomaster.conn:SdkConnection.request_connection` — описание отсутствует
- `src.robomaster.conn:StreamConnection.__init__` — описание отсутствует
- `src.robomaster.conn:StreamConnection.connect` — описание отсутствует
- `src.robomaster.conn:StreamConnection.disconnect` — описание отсутствует
- `src.robomaster.dds:Subject.__init__` — описание отсутствует
- `src.robomaster.dds:Subscriber.__init__` — описание отсутствует
- `src.robomaster.dds:Subscriber.start` — описание отсутствует
- `src.robomaster.dds:Subscriber.stop` — описание отсутствует
- `src.robomaster.dds:TelloSubscriber.__init__` — описание отсутствует
- `src.robomaster.dds:TelloSubscriber.start` — описание отсутствует
- `src.robomaster.dds:TelloSubscriber.stop` — описание отсутствует
- `src.robomaster.dds:_AutoRegisterSubject.__init__` — описание отсутствует
- `src.robomaster.event:Dispatcher.__init__` — описание отсутствует
- `src.robomaster.flight:Flight.__init__` — описание отсутствует
- `src.robomaster.flight:Flight.stop` — 停止rc运动并悬停，任何时候都可以
- `src.robomaster.flight:FlightAction.__init__` — описание отсутствует
- `src.robomaster.flight:TelloAttiInfoSubject.__init__` — описание отсутствует
- `src.robomaster.flight:TelloImuInfoSubject.__init__` — описание отсутствует
- `src.robomaster.gimbal:Gimbal.__init__` — описание отсутствует
- `src.robomaster.gimbal:GimbalMoveAction.__init__` — описание отсутствует
- `src.robomaster.gimbal:GimbalPosSubject.__init__` — описание отсутствует
- `src.robomaster.gimbal:GimbalRecenterAction.__init__` — описание отсутствует
- `src.robomaster.gripper:Gripper.__init__` — описание отсутствует
- `src.robomaster.gripper:Gripper.close` — 控制机械爪关闭
- `src.robomaster.gripper:GripperSubject.__init__` — описание отсутствует
- `src.robomaster.led:Led.__init__` — описание отсутствует
- `src.robomaster.led:TelloLed.__init__` — описание отсутствует
- `src.robomaster.media:LiveView.__init__` — описание отсутствует
- `src.robomaster.media:LiveView.start_audio_stream` — описание отсутствует
- `src.robomaster.media:LiveView.start_video_stream` — описание отсутствует
- `src.robomaster.media:LiveView.stop` — описание отсутствует
- `src.robomaster.media:LiveView.stop_audio_stream` — описание отсутствует
- `src.robomaster.media:LiveView.stop_video_stream` — описание отсутствует
- `src.robomaster.module:Module.__init__` — описание отсутствует
- `src.robomaster.module:Module.start` — описание отсутствует
- `src.robomaster.module:Module.stop` — описание отсутствует
- `src.robomaster.module:_AutoRegisterModule.__init__` — описание отсутствует
- `src.robomaster.protocol:Msg.__init__` — описание отсутствует
- `src.robomaster.protocol:MsgBase.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoAddSubMsg.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoAiModuleEvent.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoArmorHitEvent.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoBlasterFire.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoBlasterSetLed.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoChassisPwmFreq.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoChassisPwmPercent.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoChassisSerialMsgSend.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoChassisSerialSet.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoChassisSetWorkMode.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoChassisSpeedMode.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoChassisStickOverlay.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoChassisWheelSpeed.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoData.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoDelMsg.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoFcSubInfoReq.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoGameMsgEvent.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoGetProductVersion.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoGetRobotMode.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoGetSn.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoGetVersion.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoGetZoom.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoGimbalActionPush.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoGimbalCtrl.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoGimbalCtrlSpeed.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoGimbalRecenter.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoGimbalRotate.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoGimbalSetWorkMode.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoGripperCtrl.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoIrHitEvent.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoPlaySound.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoPositionMove.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoPositionPush.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoPushPeriodMsg.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoRoboticAiInit.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoRoboticArmGetPostion.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoRoboticArmMove.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoRoboticArmMoveCtrl.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoRoboticArmMovePush.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoSdkHeartBeat.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoSensorGetData.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoServoControl.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoServoCtrlPush.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoServoCtrlSet.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoServoGetAngle.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoServoModeSet.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoSetArmorParam.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoSetRobotMode.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoSetSdkConnection.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoSetSdkMode.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoSetSystemLed.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoSetWheelSpeed.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoSetWhiteBalance.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoSetZoom.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoSoundPush.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoStreamCtrl.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoSubNodeReset.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoSubscribeAddNode.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoTakePhoto.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoUwbModuleEvent.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoVisionDetectEnable.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoVisionDetectInfo.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoVisionDetectStatus.__init__` — описание отсутствует
- `src.robomaster.protocol:ProtoVisionSetColor.__init__` — описание отсутствует
- `src.robomaster.protocol:STAConnInfo.__init__` — описание отсутствует
- `src.robomaster.protocol:TelloDdsProto.__init__` — описание отсутствует
- `src.robomaster.protocol:TextMsg.__init__` — описание отсутствует
- `src.robomaster.protocol:TextProtoData.__init__` — описание отсутствует
- `src.robomaster.protocol:TextProtoDrone.__init__` — описание отсутствует
- `src.robomaster.protocol:TextProtoDronePush.__init__` — описание отсутствует
- `src.robomaster.protocol:_AutoRegisterProto.__init__` — описание отсутствует
- `src.robomaster.robot:Drone.__init__` — описание отсутствует
- `src.robomaster.robot:Drone.close` — 停止drone对象
- `src.robomaster.robot:Drone.initialize` — описание отсутствует
- `src.robomaster.robot:Drone.search_stop` — описание отсутствует
- `src.robomaster.robot:Drone.start` — описание отсутствует
- `src.robomaster.robot:Robot.__init__` — описание отсутствует
- `src.robomaster.robot:Robot._start_heart_beat_timer` — описание отсутствует
- `src.robomaster.robot:Robot._stop_heart_beat_timer` — описание отсутствует
- `src.robomaster.robot:Robot._wait_for_connection` — описание отсутствует
- `src.robomaster.robot:Robot.close` — описание отсутствует
- `src.robomaster.robot:Robot.initialize` — 初始化机器人
- `src.robomaster.robot:Robot.is_initialized` — описание отсутствует
- `src.robomaster.robot:RobotBase.__init__` — описание отсутствует
- `src.robomaster.robot:RobotPlaySoundAction.__init__` — описание отсутствует
- `src.robomaster.robot:TelloDroneInfoSubject.__init__` — описание отсутствует
- `src.robomaster.robot:TelloStatusSubject.__init__` — описание отсутствует
- `src.robomaster.robot:TelloTempInfoSubject.__init__` — описание отсутствует
- `src.robomaster.robot:TelloTofInfoSubject.__init__` — описание отсутствует
- `src.robomaster.robotic_arm:ArmSubject.__init__` — описание отсутствует
- `src.robomaster.robotic_arm:RoboticArm.__init__` — описание отсутствует
- `src.robomaster.robotic_arm:RoboticArmMoveAction.__init__` — описание отсутствует
- `src.robomaster.sensor:AdapterSubject.__init__` — описание отсутствует
- `src.robomaster.sensor:DistanceSensor.__init__` — описание отсутствует
- `src.robomaster.sensor:SensorAdaptor.__init__` — описание отсутствует
- `src.robomaster.sensor:TelloDistanceSensor.__init__` — описание отсутствует
- `src.robomaster.sensor:TofSubject.__init__` — описание отсутствует
- `src.robomaster.servo:Servo.__init__` — описание отсутствует
- `src.robomaster.servo:ServoSetAngleAction.__init__` — описание отсутствует
- `src.robomaster.servo:ServoSubject.__init__` — описание отсутствует
- `src.robomaster.uart:Uart.__init__` — описание отсутствует
- `src.robomaster.uart:Uart.start` — описание отсутствует
- `src.robomaster.uart:Uart.stop` — описание отсутствует
- `src.robomaster.util:UnitChecker.__init__` — описание отсутствует
- `src.robomaster.util:UnitChecker.start` — описание отсутствует
- `src.robomaster.vision:Vision.__init__` — описание отсутствует
- `src.robomaster.vision:VisionPushEvent.__init__` — описание отсутствует

## Модуль `examples.00_general.01_sdk_version` (`examples/00_general/01_sdk_version.py`)


## Модуль `examples.01_robot.00_logger` (`examples/01_robot/00_logger.py`)


## Модуль `examples.01_robot.01_get_version` (`examples/01_robot/01_get_version.py`)


## Модуль `examples.01_robot.02_get_sn` (`examples/01_robot/02_get_sn.py`)


## Модуль `examples.01_robot.03_play_audio` (`examples/01_robot/03_play_audio.py`)


## Модуль `examples.01_robot.03_play_sound` (`examples/01_robot/03_play_sound.py`)


## Модуль `examples.01_robot.04_ap_conn` (`examples/01_robot/04_ap_conn.py`)


## Модуль `examples.01_robot.05_sta_conn` (`examples/01_robot/05_sta_conn.py`)


## Модуль `examples.01_robot.05_sta_conn_helper` (`examples/01_robot/05_sta_conn_helper.py`)


## Модуль `examples.01_robot.05_sta_conn_sn` (`examples/01_robot/05_sta_conn_sn.py`)


## Модуль `examples.01_robot.06_rndis_conn` (`examples/01_robot/06_rndis_conn.py`)


## Модуль `examples.01_robot.07_tcp_protocol` (`examples/01_robot/07_tcp_protocol.py`)


## Модуль `examples.01_robot.08_udp_protocol` (`examples/01_robot/08_udp_protocol.py`)


## Модуль `examples.01_robot.09_set_mode` (`examples/01_robot/09_set_mode.py`)


## Модуль `examples.02_chassis.01_move` (`examples/02_chassis/01_move.py`)


## Модуль `examples.02_chassis.02_wheel` (`examples/02_chassis/02_wheel.py`)


## Модуль `examples.02_chassis.03_speed` (`examples/02_chassis/03_speed.py`)


## Модуль `examples.02_chassis.04_sub_attitude` (`examples/02_chassis/04_sub_attitude.py`)

### Функции

#### `sub_attitude_info_handler`
- **Сигнатура:** `sub_attitude_info_handler(attitude_info)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** print, format
- **Аргументы:**
  - `attitude_info`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `attitude_info`.
- **Пример:** `sub_attitude_info_handler(...)`


## Модуль `examples.02_chassis.05_sub_position` (`examples/02_chassis/05_sub_position.py`)

### Функции

#### `sub_position_handler`
- **Сигнатура:** `sub_position_handler(position_info)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** print, format
- **Аргументы:**
  - `position_info`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `position_info`.
- **Пример:** `sub_position_handler(...)`


## Модуль `examples.02_chassis.06_sub_imu` (`examples/02_chassis/06_sub_imu.py`)

### Функции

#### `sub_imu_info_handler`
- **Сигнатура:** `sub_imu_info_handler(imu_info)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** print, format
- **Аргументы:**
  - `imu_info`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `imu_info`.
- **Пример:** `sub_imu_info_handler(...)`


## Модуль `examples.02_chassis.07_sub_status` (`examples/02_chassis/07_sub_status.py`)

### Функции

#### `sub_status_info_handler`
- **Сигнатура:** `sub_status_info_handler(status_info)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** print, format
- **Аргументы:**
  - `status_info`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `status_info`.
- **Пример:** `sub_status_info_handler(...)`


## Модуль `examples.02_chassis.08_sub_esc` (`examples/02_chassis/08_sub_esc.py`)

### Функции

#### `sub_esc_info_handler`
- **Сигнатура:** `sub_esc_info_handler(esc_info)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** print, format
- **Аргументы:**
  - `esc_info`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `esc_info`.
- **Пример:** `sub_esc_info_handler(...)`


## Модуль `examples.02_chassis.09_sub_all` (`examples/02_chassis/09_sub_all.py`)

### Функции

#### `sub_info_handler`
- **Сигнатура:** `sub_info_handler(sub_info)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** print, format
- **Аргументы:**
  - `sub_info`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `sub_info`.
- **Пример:** `sub_info_handler(...)`


## Модуль `examples.02_chassis.10_serial` (`examples/02_chassis/10_serial.py`)


## Модуль `examples.02_chassis.11_pwm` (`examples/02_chassis/11_pwm.py`)


## Модуль `examples.03_gimbal.01_move` (`examples/03_gimbal/01_move.py`)


## Модуль `examples.03_gimbal.02_speed` (`examples/03_gimbal/02_speed.py`)


## Модуль `examples.03_gimbal.03_control` (`examples/03_gimbal/03_control.py`)


## Модуль `examples.03_gimbal.04_recenter` (`examples/03_gimbal/04_recenter.py`)


## Модуль `examples.03_gimbal.05_sub_angle` (`examples/03_gimbal/05_sub_angle.py`)

### Функции

#### `sub_data_handler`
- **Сигнатура:** `sub_data_handler(angle_info)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** print, format
- **Аргументы:**
  - `angle_info`: тип `не указан`; единицы `°`; допустимые значения `0..255`; параметр `angle_info`.
- **Пример:** `sub_data_handler(...)`


## Модуль `examples.04_camera.01_video_with_display` (`examples/04_camera/01_video_with_display.py`)


## Модуль `examples.04_camera.02_video_strategy` (`examples/04_camera/02_video_strategy.py`)


## Модуль `examples.04_camera.03_video_without_display` (`examples/04_camera/03_video_without_display.py`)


## Модуль `examples.04_camera.04_audio_without_playing` (`examples/04_camera/04_audio_without_playing.py`)

### Функции

#### `audio_playing_task`
- **Сигнатура:** `audio_playing_task(ep_robot)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** PyAudio, open, close, write, stop_stream, read_audio_frame
- **Аргументы:**
  - `ep_robot`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `ep_robot`.
- **Пример:** `audio_playing_task(...)`


## Модуль `examples.04_camera.05_record_audio` (`examples/04_camera/05_record_audio.py`)


## Модуль `examples.05_vision.01_marker` (`examples/05_vision/01_marker.py`)

### Функции

#### `on_detect_marker`
- **Сигнатура:** `on_detect_marker(marker_info)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** len, clear, range, append, print, MarkerInfo
- **Аргументы:**
  - `marker_info`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `marker_info`.
- **Пример:** `on_detect_marker(...)`

### Классы

### `MarkerInfo`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self, x, y, w, h, info)`
  - **Аргументы конструктора:**
    - `x`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; инициализационный параметр `x`.
    - `y`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; инициализационный параметр `y`.
    - `w`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; инициализационный параметр `w`.
    - `h`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; инициализационный параметр `h`.
    - `info`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; инициализационный параметр `info`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, x, y, w, h, info)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `x`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `x`.
      - `y`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `y`.
      - `w`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `w`.
      - `h`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `h`.
      - `info`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `info`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pt1`
    - Сигнатура: `pt1(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): int
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pt1()`
  - `pt2`
    - Сигнатура: `pt2(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): int
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pt2()`
  - `center`
    - Сигнатура: `center(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): int
    - Аргументы:
      - нет аргументов
    - Пример: `obj.center()`
  - `text`
    - Сигнатура: `text(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.text()`


## Модуль `examples.05_vision.02_line` (`examples/05_vision/02_line.py`)

### Функции

#### `on_detect_line`
- **Сигнатура:** `on_detect_line(line_info)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** len, clear, print, range, append, PointInfo
- **Аргументы:**
  - `line_info`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `line_info`.
- **Пример:** `on_detect_line(...)`

### Классы

### `PointInfo`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self, x, y, theta, c)`
  - **Аргументы конструктора:**
    - `x`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; инициализационный параметр `x`.
    - `y`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; инициализационный параметр `y`.
    - `theta`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; инициализационный параметр `theta`.
    - `c`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; инициализационный параметр `c`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, x, y, theta, c)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `x`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `x`.
      - `y`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `y`.
      - `theta`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `theta`.
      - `c`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `c`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pt`
    - Сигнатура: `pt(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): int
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pt()`
  - `color`
    - Сигнатура: `color(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.color()`


## Модуль `examples.05_vision.03_person` (`examples/05_vision/03_person.py`)

### Функции

#### `on_detect_person`
- **Сигнатура:** `on_detect_person(person_info)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** len, clear, range, append, print, PersonInfo
- **Аргументы:**
  - `person_info`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `person_info`.
- **Пример:** `on_detect_person(...)`

### Классы

### `PersonInfo`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self, x, y, w, h)`
  - **Аргументы конструктора:**
    - `x`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; инициализационный параметр `x`.
    - `y`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; инициализационный параметр `y`.
    - `w`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; инициализационный параметр `w`.
    - `h`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; инициализационный параметр `h`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, x, y, w, h)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `x`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `x`.
      - `y`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `y`.
      - `w`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `w`.
      - `h`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `h`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pt1`
    - Сигнатура: `pt1(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): int
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pt1()`
  - `pt2`
    - Сигнатура: `pt2(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): int
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pt2()`
  - `center`
    - Сигнатура: `center(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): int
    - Аргументы:
      - нет аргументов
    - Пример: `obj.center()`


## Модуль `examples.05_vision.04_robot` (`examples/05_vision/04_robot.py`)

### Функции

#### `on_detect_person`
- **Сигнатура:** `on_detect_person(person_info)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** len, clear, range, append, print, RobotInfo
- **Аргументы:**
  - `person_info`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `person_info`.
- **Пример:** `on_detect_person(...)`

### Классы

### `RobotInfo`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self, x, y, w, h)`
  - **Аргументы конструктора:**
    - `x`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; инициализационный параметр `x`.
    - `y`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; инициализационный параметр `y`.
    - `w`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; инициализационный параметр `w`.
    - `h`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; инициализационный параметр `h`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, x, y, w, h)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `x`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `x`.
      - `y`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `y`.
      - `w`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `w`.
      - `h`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `h`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pt1`
    - Сигнатура: `pt1(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): int
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pt1()`
  - `pt2`
    - Сигнатура: `pt2(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): int
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pt2()`
  - `center`
    - Сигнатура: `center(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): int
    - Аргументы:
      - нет аргументов
    - Пример: `obj.center()`


## Модуль `examples.05_vision.05_gesture` (`examples/05_vision/05_gesture.py`)

### Функции

#### `on_detect_person`
- **Сигнатура:** `on_detect_person(gesture_info)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** len, acquire, clear, range, release, append
- **Аргументы:**
  - `gesture_info`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `gesture_info`.
- **Пример:** `on_detect_person(...)`

### Классы

### `GestureInfo`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self, x, y, w, h, info)`
  - **Аргументы конструктора:**
    - `x`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; инициализационный параметр `x`.
    - `y`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; инициализационный параметр `y`.
    - `w`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; инициализационный параметр `w`.
    - `h`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; инициализационный параметр `h`.
    - `info`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; инициализационный параметр `info`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, x, y, w, h, info)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `x`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `x`.
      - `y`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `y`.
      - `w`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `w`.
      - `h`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `h`.
      - `info`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `info`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pt1`
    - Сигнатура: `pt1(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): int
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pt1()`
  - `pt2`
    - Сигнатура: `pt2(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): int
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pt2()`
  - `center`
    - Сигнатура: `center(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): int
    - Аргументы:
      - нет аргументов
    - Пример: `obj.center()`
  - `text`
    - Сигнатура: `text(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): str
    - Аргументы:
      - нет аргументов
    - Пример: `obj.text()`


## Модуль `examples.06_blaster.01_fire` (`examples/06_blaster/01_fire.py`)


## Модуль `examples.06_blaster.02_led` (`examples/06_blaster/02_led.py`)


## Модуль `examples.07_led.01_set_led` (`examples/07_led/01_set_led.py`)


## Модуль `examples.07_led.02_set_gimbal_led` (`examples/07_led/02_set_gimbal_led.py`)


## Модуль `examples.08_battery.01_sub_battery` (`examples/08_battery/01_sub_battery.py`)

### Функции

#### `sub_info_handler`
- **Сигнатура:** `sub_info_handler(batter_info, ep_robot)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** print, int, set_led, format
- **Аргументы:**
  - `batter_info`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `batter_info`.
  - `ep_robot`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `ep_robot`.
- **Пример:** `sub_info_handler(..., ...)`


## Модуль `examples.09_armor.01_hit_event` (`examples/09_armor/01_hit_event.py`)

### Функции

#### `hit_callback`
- **Сигнатура:** `hit_callback(sub_info, ep_robot)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** print, set_led, format, randint
- **Аргументы:**
  - `sub_info`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `sub_info`.
  - `ep_robot`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `ep_robot`.
- **Пример:** `hit_callback(..., ...)`


## Модуль `examples.09_armor.02_ir_event` (`examples/09_armor/02_ir_event.py`)

### Функции

#### `hit_callback`
- **Сигнатура:** `hit_callback(sub_info, ep_robot)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** print, set_led, format, randint
- **Аргументы:**
  - `sub_info`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `sub_info`.
  - `ep_robot`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `ep_robot`.
- **Пример:** `hit_callback(..., ...)`


## Модуль `examples.10_robotic_arm.01_move` (`examples/10_robotic_arm/01_move.py`)


## Модуль `examples.10_robotic_arm.02_sub_position` (`examples/10_robotic_arm/02_sub_position.py`)

### Функции

#### `sub_data_handler`
- **Сигнатура:** `sub_data_handler(sub_info)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** print, format
- **Аргументы:**
  - `sub_info`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `sub_info`.
- **Пример:** `sub_data_handler(...)`


## Модуль `examples.11_gripper.01_open_close` (`examples/11_gripper/01_open_close.py`)


## Модуль `examples.11_gripper.02_sub_status` (`examples/11_gripper/02_sub_status.py`)

### Функции

#### `sub_data_handler`
- **Сигнатура:** `sub_data_handler(sub_info)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** print, format
- **Аргументы:**
  - `sub_info`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `sub_info`.
- **Пример:** `sub_data_handler(...)`


## Модуль `examples.12_drone.00_logger` (`examples/12_drone/00_logger.py`)


## Модуль `examples.12_drone.01_ap_conn` (`examples/12_drone/01_ap_conn.py`)


## Модуль `examples.12_drone.02_get_version` (`examples/12_drone/02_get_version.py`)


## Модуль `examples.12_drone.03_get_sn` (`examples/12_drone/03_get_sn.py`)


## Модуль `examples.12_drone.04_get_battery` (`examples/12_drone/04_get_battery.py`)


## Модуль `examples.12_drone.05_takeoff_land` (`examples/12_drone/05_takeoff_land.py`)


## Модуль `examples.12_drone.06_rotate` (`examples/12_drone/06_rotate.py`)


## Модуль `examples.12_drone.07_forward_backward` (`examples/12_drone/07_forward_backward.py`)


## Модуль `examples.12_drone.08_up_down` (`examples/12_drone/08_up_down.py`)


## Модуль `examples.12_drone.09_left_right` (`examples/12_drone/09_left_right.py`)


## Модуль `examples.12_drone.10_go` (`examples/12_drone/10_go.py`)


## Модуль `examples.12_drone.11_curve` (`examples/12_drone/11_curve.py`)


## Модуль `examples.12_drone.12_flip` (`examples/12_drone/12_flip.py`)


## Модуль `examples.12_drone.13_rc` (`examples/12_drone/13_rc.py`)


## Модуль `examples.12_drone.14_mission_pad` (`examples/12_drone/14_mission_pad.py`)


## Модуль `examples.12_drone.15_jump` (`examples/12_drone/15_jump.py`)


## Модуль `examples.12_drone.16_video_stream` (`examples/12_drone/16_video_stream.py`)


## Модуль `examples.12_drone.17_sub_info` (`examples/12_drone/17_sub_info.py`)

### Функции

#### `sub_tof_info_handler`
- **Сигнатура:** `sub_tof_info_handler(tof_info)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** print, format
- **Аргументы:**
  - `tof_info`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `tof_info`.
- **Пример:** `sub_tof_info_handler(...)`

#### `sub_drone_info_handler`
- **Сигнатура:** `sub_drone_info_handler(drone_info)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** print, format
- **Аргументы:**
  - `drone_info`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `drone_info`.
- **Пример:** `sub_drone_info_handler(...)`


## Модуль `examples.12_drone.18_sub_battery` (`examples/12_drone/18_sub_battery.py`)

### Функции

#### `sub_battery_info_handler`
- **Сигнатура:** `sub_battery_info_handler(battery_info)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** print, format
- **Аргументы:**
  - `battery_info`: тип `не указан`; единицы `м`; допустимые значения `0..255`; параметр `battery_info`.
- **Пример:** `sub_battery_info_handler(...)`


## Модуль `examples.12_drone.19_sub_flight` (`examples/12_drone/19_sub_flight.py`)

### Функции

#### `sub_atti_info_handler`
- **Сигнатура:** `sub_atti_info_handler(attitute_info)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** print, format
- **Аргументы:**
  - `attitute_info`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `attitute_info`.
- **Пример:** `sub_atti_info_handler(...)`

#### `sub_imu_info_handler`
- **Сигнатура:** `sub_imu_info_handler(imu_info)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** print, format
- **Аргументы:**
  - `imu_info`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `imu_info`.
- **Пример:** `sub_imu_info_handler(...)`


## Модуль `examples.12_drone.20_led` (`examples/12_drone/20_led.py`)


## Модуль `examples.12_drone.21_mled` (`examples/12_drone/21_mled.py`)


## Модуль `examples.12_drone.22_tof` (`examples/12_drone/22_tof.py`)


## Модуль `examples.12_drone.23_set_sta` (`examples/12_drone/23_set_sta.py`)


## Модуль `examples.12_drone.24_get_ssid` (`examples/12_drone/24_get_ssid.py`)


## Модуль `examples.13_servo.01_set_angle` (`examples/13_servo/01_set_angle.py`)


## Модуль `examples.14_sensor.01_get_data` (`examples/14_sensor/01_get_data.py`)


## Модуль `examples.14_sensor.02_tof_data` (`examples/14_sensor/02_tof_data.py`)

### Функции

#### `sub_data_handler`
- **Сигнатура:** `sub_data_handler(sub_info)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** print, format
- **Аргументы:**
  - `sub_info`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `sub_info`.
- **Пример:** `sub_data_handler(...)`


## Модуль `examples.14_sensor.03_io_data` (`examples/14_sensor/03_io_data.py`)

### Функции

#### `sub_data_handler`
- **Сигнатура:** `sub_data_handler(sub_info)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** print, format
- **Аргументы:**
  - `sub_info`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `sub_info`.
- **Пример:** `sub_data_handler(...)`


## Модуль `examples.15_multi_robot.multi_drone.01_scan_ip` (`examples/15_multi_robot/multi_drone/01_scan_ip.py`)


## Модуль `examples.15_multi_robot.multi_drone.02_basic` (`examples/15_multi_robot/multi_drone/02_basic.py`)

### Функции

#### `basic_task`
- **Сигнатура:** `basic_task(robot_group)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** get_sn, get_battery
- **Аргументы:**
  - `robot_group`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot_group`.
- **Пример:** `basic_task(...)`


## Модуль `examples.15_multi_robot.multi_drone.03_takeoff_land` (`examples/15_multi_robot/multi_drone/03_takeoff_land.py`)

### Функции

#### `takeoff_land_task1`
- **Сигнатура:** `takeoff_land_task1(robot_group)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** wait_for_completed, takeoff, forward, land
- **Аргументы:**
  - `robot_group`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot_group`.
- **Пример:** `takeoff_land_task1(...)`

#### `takeoff_land_task2`
- **Сигнатура:** `takeoff_land_task2(robot_group)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** wait_for_completed, takeoff, backward, land
- **Аргументы:**
  - `robot_group`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot_group`.
- **Пример:** `takeoff_land_task2(...)`


## Модуль `examples.15_multi_robot.multi_drone.04_flight` (`examples/15_multi_robot/multi_drone/04_flight.py`)

### Функции

#### `base_action_1`
- **Сигнатура:** `base_action_1(robot_group)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** wait_for_completed, set_mled_char, set_led, takeoff, down, up
- **Аргументы:**
  - `robot_group`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot_group`.
- **Пример:** `base_action_1(...)`

#### `base_action_2`
- **Сигнатура:** `base_action_2(robot_group)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** wait_for_completed, set_mled_char, set_led, takeoff, up, down
- **Аргументы:**
  - `robot_group`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot_group`.
- **Пример:** `base_action_2(...)`


## Модуль `examples.15_multi_robot.multi_drone.05_go` (`examples/15_multi_robot/multi_drone/05_go.py`)

### Функции

#### `base_action_1`
- **Сигнатура:** `base_action_1(robot_group)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** mission_pad_on, wait_for_completed, set_mled_char, mission_pad_off, takeoff, go
- **Аргументы:**
  - `robot_group`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot_group`.
- **Пример:** `base_action_1(...)`


## Модуль `examples.15_multi_robot.multi_drone.06_led` (`examples/15_multi_robot/multi_drone/06_led.py`)

### Функции

#### `base_action_1`
- **Сигнатура:** `base_action_1(robot_group)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** set_led, sleep
- **Аргументы:**
  - `robot_group`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot_group`.
- **Пример:** `base_action_1(...)`


## Модуль `examples.15_multi_robot.multi_drone.07_takeoff_order` (`examples/15_multi_robot/multi_drone/07_takeoff_order.py`)

### Функции

#### `group_forward`
- **Сигнатура:** `group_forward(robot_group)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** wait_for_completed, forward
- **Аргументы:**
  - `robot_group`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot_group`.
- **Пример:** `group_forward(...)`

#### `group_land`
- **Сигнатура:** `group_land(robot_group)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** wait_for_completed, land
- **Аргументы:**
  - `robot_group`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot_group`.
- **Пример:** `group_land(...)`


## Модуль `examples.15_multi_robot.multi_ep.01_scan_robot_sn` (`examples/15_multi_robot/multi_ep/01_scan_robot_sn.py`)


## Модуль `examples.15_multi_robot.multi_ep.02_two_ep_demo` (`examples/15_multi_robot/multi_ep/02_two_ep_demo.py`)

### Функции

#### `group_task`
- **Сигнатура:** `group_task(robot_group)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** wait_for_completed, move
- **Аргументы:**
  - `robot_group`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot_group`.
- **Пример:** `group_task(...)`

#### `group_task1`
- **Сигнатура:** `group_task1(robot_group)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** wait_for_completed, move
- **Аргументы:**
  - `robot_group`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot_group`.
- **Пример:** `group_task1(...)`


## Модуль `examples.15_multi_robot.multi_ep.03_six_ep_demo` (`examples/15_multi_robot/multi_ep/03_six_ep_demo.py`)

### Функции

#### `reset_task`
- **Сигнатура:** `reset_task(robot_group)`
- **Приватная:** нет
- **Описание:** 初始自由模式 & 关掉所有灯效
- **Связи (вызовы):** set_led, set_group_robots_mode, wait_for_completed, moveto
- **Аргументы:**
  - `robot_group`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot_group`.
- **Пример:** `reset_task(...)`

#### `ep_arm_initial_pos`
- **Сигнатура:** `ep_arm_initial_pos(robot_group)`
- **Приватная:** нет
- **Описание:** ep_arm 初始云台位置
- **Связи (вызовы):** wait_for_completed, moveto
- **Аргументы:**
  - `robot_group`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot_group`.
- **Пример:** `ep_arm_initial_pos(...)`

#### `ep_gimbal_initial_pos`
- **Сигнатура:** `ep_gimbal_initial_pos(robot_group)`
- **Приватная:** нет
- **Описание:** ep_gimbal 初始云台位置
- **Связи (вызовы):** wait_for_completed, moveto
- **Аргументы:**
  - `robot_group`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot_group`.
- **Пример:** `ep_gimbal_initial_pos(...)`

#### `light_order`
- **Сигнатура:** `light_order(robot_group)`
- **Приватная:** нет
- **Описание:** 组内小车灯依次亮起,云台依次抬起
- **Связи (вызовы):** get_robot, fire, sleep, set_led, wait_for_completed, moveto
- **Аргументы:**
  - `robot_group`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot_group`.
- **Пример:** `light_order(...)`

#### `move_forward`
- **Сигнатура:** `move_forward(robot_group)`
- **Приватная:** нет
- **Описание:** 全体前进
- **Связи (вызовы):** wait_for_completed, move
- **Аргументы:**
  - `robot_group`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot_group`.
- **Пример:** `move_forward(...)`

#### `rotate_right`
- **Сигнатура:** `rotate_right(robot_group)`
- **Приватная:** нет
- **Описание:** 底盘右转
- **Связи (вызовы):** set_group_robots_mode, sleep, wait_for_completed, move
- **Аргументы:**
  - `robot_group`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot_group`.
- **Пример:** `rotate_right(...)`

#### `rotate_left`
- **Сигнатура:** `rotate_left(robot_group)`
- **Приватная:** нет
- **Описание:** 底盘左转
- **Связи (вызовы):** set_group_robots_mode, sleep, wait_for_completed, move
- **Аргументы:**
  - `robot_group`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot_group`.
- **Пример:** `rotate_left(...)`

#### `rotate_dance`
- **Сигнатура:** `rotate_dance(robot_group)`
- **Приватная:** нет
- **Описание:** 底盘solo舞蹈
- **Связи (вызовы):** set_group_robots_mode, wait_for_completed, move
- **Аргументы:**
  - `robot_group`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot_group`.
- **Пример:** `rotate_dance(...)`

#### `move_backward`
- **Сигнатура:** `move_backward(robot_group)`
- **Приватная:** нет
- **Описание:** 底盘后移
- **Связи (вызовы):** wait_for_completed, move
- **Аргументы:**
  - `robot_group`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot_group`.
- **Пример:** `move_backward(...)`

#### `led_red_blink`
- **Сигнатура:** `led_red_blink(robot_group)`
- **Приватная:** нет
- **Описание:** 红灯闪烁
- **Связи (вызовы):** set_led
- **Аргументы:**
  - `robot_group`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot_group`.
- **Пример:** `led_red_blink(...)`

#### `led_grey_blink`
- **Сигнатура:** `led_grey_blink(robot_group)`
- **Приватная:** нет
- **Описание:** grey闪烁
- **Связи (вызовы):** set_led
- **Аргументы:**
  - `robot_group`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot_group`.
- **Пример:** `led_grey_blink(...)`

#### `led_red_solid`
- **Сигнатура:** `led_red_solid(robot_group)`
- **Приватная:** нет
- **Описание:** 红灯常亮
- **Связи (вызовы):** set_led
- **Аргументы:**
  - `robot_group`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot_group`.
- **Пример:** `led_red_solid(...)`

#### `led_grey_solid`
- **Сигнатура:** `led_grey_solid(robot_group)`
- **Приватная:** нет
- **Описание:** grey常亮
- **Связи (вызовы):** set_led
- **Аргументы:**
  - `robot_group`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot_group`.
- **Пример:** `led_grey_solid(...)`

#### `move_left`
- **Сигнатура:** `move_left(robot_group)`
- **Приватная:** нет
- **Описание:** 底盘左移
- **Связи (вызовы):** wait_for_completed, move
- **Аргументы:**
  - `robot_group`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot_group`.
- **Пример:** `move_left(...)`

#### `move_right`
- **Сигнатура:** `move_right(robot_group)`
- **Приватная:** нет
- **Описание:** 底盘右移
- **Связи (вызовы):** wait_for_completed, move
- **Аргументы:**
  - `robot_group`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot_group`.
- **Пример:** `move_right(...)`

#### `gimbal_down`
- **Сигнатура:** `gimbal_down(robot_group)`
- **Приватная:** нет
- **Описание:** 云台下垂
- **Связи (вызовы):** wait_for_completed, moveto
- **Аргументы:**
  - `robot_group`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot_group`.
- **Пример:** `gimbal_down(...)`

#### `gimbal_recenter`
- **Сигнатура:** `gimbal_recenter(robot_group)`
- **Приватная:** нет
- **Описание:** 云台回中
- **Связи (вызовы):** wait_for_completed, moveto
- **Аргументы:**
  - `robot_group`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot_group`.
- **Пример:** `gimbal_recenter(...)`

#### `rotate_circle_right`
- **Сигнатура:** `rotate_circle_right(robot_group)`
- **Приватная:** нет
- **Описание:** 顺时针转圈
- **Связи (вызовы):** wait_for_completed, move
- **Аргументы:**
  - `robot_group`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot_group`.
- **Пример:** `rotate_circle_right(...)`

#### `rotate_circle_left`
- **Сигнатура:** `rotate_circle_left(robot_group)`
- **Приватная:** нет
- **Описание:** 逆时针转圈
- **Связи (вызовы):** wait_for_completed, move
- **Аргументы:**
  - `robot_group`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot_group`.
- **Пример:** `rotate_circle_left(...)`

#### `rotate_right_dance`
- **Сигнатура:** `rotate_right_dance(robot_group)`
- **Приватная:** нет
- **Описание:** 右转
- **Связи (вызовы):** set_group_robots_mode, wait_for_completed, move, moveto
- **Аргументы:**
  - `robot_group`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot_group`.
- **Пример:** `rotate_right_dance(...)`

#### `rotate_left_dance`
- **Сигнатура:** `rotate_left_dance(robot_group)`
- **Приватная:** нет
- **Описание:** 左转
- **Связи (вызовы):** set_group_robots_mode, wait_for_completed, move, moveto
- **Аргументы:**
  - `robot_group`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot_group`.
- **Пример:** `rotate_left_dance(...)`

#### `gimbal_left_up`
- **Сигнатура:** `gimbal_left_up(robot_group)`
- **Приватная:** нет
- **Описание:** 云台左转，并抬起
- **Связи (вызовы):** set_group_robots_mode, wait_for_completed, moveto
- **Аргументы:**
  - `robot_group`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot_group`.
- **Пример:** `gimbal_left_up(...)`

#### `gimbal_right_up`
- **Сигнатура:** `gimbal_right_up(robot_group)`
- **Приватная:** нет
- **Описание:** 云台右转,并抬起
- **Связи (вызовы):** set_group_robots_mode, wait_for_completed, moveto
- **Аргументы:**
  - `robot_group`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot_group`.
- **Пример:** `gimbal_right_up(...)`

#### `ending_formation`
- **Сигнатура:** `ending_formation(robot_group)`
- **Приватная:** нет
- **Описание:** 结束队形
- **Связи (вызовы):** fire, sleep, wait_for_completed, range, set_led, moveto
- **Аргументы:**
  - `robot_group`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot_group`.
- **Пример:** `ending_formation(...)`

#### `nod_action`
- **Сигнатура:** `nod_action(robot_group)`
- **Приватная:** нет
- **Описание:** 云台做点头动作
- **Связи (вызовы):** wait_for_completed, moveto
- **Аргументы:**
  - `robot_group`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot_group`.
- **Пример:** `nod_action(...)`


## Модуль `examples.16_gamesystem.00_gamesystem` (`examples/16_gamesystem/00_gamesystem.py`)

### Функции

#### `robot_control`
- **Сигнатура:** `robot_control(run)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** ord, print, drive_speed
- **Аргументы:**
  - `run`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `run`.
- **Пример:** `robot_control(...)`

#### `sub_data_handler`
- **Сигнатура:** `sub_data_handler(sub_info)`
- **Приватная:** нет
- **Описание:** 返回数据 (buf: 键鼠数据 [mouse_press, mouse_x, mouse_y, seq, key_num, key_1, key2, ….])
- **Связи (вызовы):** print, robot_control, format
- **Аргументы:**
  - `sub_info`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `sub_info`.
- **Пример:** `sub_data_handler(...)`


## Модуль `examples.17_ai_module.00_ai_module_ep` (`examples/17_ai_module/00_ai_module_ep.py`)

### Функции

#### `ai_callback`
- **Сигнатура:** `ai_callback(sub_info)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** print, range, format
- **Аргументы:**
  - `sub_info`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `sub_info`.
- **Пример:** `ai_callback(...)`


## Модуль `examples.17_ai_module.01_ai_module_tt` (`examples/17_ai_module/01_ai_module_tt.py`)

### Функции

#### `sub_ia_info_handler`
- **Сигнатура:** `sub_ia_info_handler(ai_info)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** print, format
- **Аргументы:**
  - `ai_info`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `ai_info`.
- **Пример:** `sub_ia_info_handler(...)`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.connection.network.direct_connection` (`examples/plaintext_sample_code/RoboMasterEP/connection/network/direct_connection.py`)


## Модуль `examples.plaintext_sample_code.RoboMasterEP.connection.network.networking_connection` (`examples/plaintext_sample_code/RoboMasterEP/connection/network/networking_connection.py`)


## Модуль `examples.plaintext_sample_code.RoboMasterEP.connection.network.robot_connection` (`examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py`)

### Функции

#### `test`
- **Сигнатура:** `test()`
- **Приватная:** нет
- **Описание:** Test funciton
- **Связи (вызовы):** RobotConnection, open, send_data, print, recv_ctrl_data, start_video_recv
- **Аргументы:**
  - нет аргументов
- **Пример:** `test()`

### Классы

### `RobotConnection`
- **Приватный класс:** нет
- **Описание:** Create a RobotConnection object with a given robot ip.
- **Конструктор:** `__init__(self, robot_ip='')`
  - **Аргументы конструктора:**
    - `robot_ip`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `robot_ip`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, robot_ip='')`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): socket, bind, Thread, Queue
    - Аргументы:
      - `robot_ip`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot_ip`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `update_robot_ip`
    - Сигнатура: `update_robot_ip(self, robot_ip)`
    - Приватный: нет
    - Описание: Update the robot ip
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `robot_ip`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot_ip`.
    - Пример(ы) из репозитория:
      - `robot.update_robot_ip(robot_ip)` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/networking_connection.py:11`)
      - `self.connection.update_robot_ip(RobotLiveview.WIFI_DIRECT_IP)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/python_stream_liveview/liveview.py:55`)
  - `get_robot_ip`
    - Сигнатура: `get_robot_ip(self, timeout=None)`
    - Приватный: нет
    - Описание: Get the robot ip from ip broadcat port
    - Связи (вызовы): settimeout, recvfrom, decode, print, find, len
    - Аргументы:
      - `timeout`: тип `не указан`; единицы `с`; допустимые значения `не указаны`; параметр `timeout`.
    - Пример(ы) из репозитория:
      - `robot_ip = robot.get_robot_ip(10)` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/networking_connection.py:7`)
      - `robot_ip = self.connection.get_robot_ip(timeout=10)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/python_stream_liveview/liveview.py:59`)
  - `open`
    - Сигнатура: `open(self)`
    - Приватный: нет
    - Описание: Open the connection
    - Связи (вызовы): settimeout, connect, start, print
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `img = Image.open(QRCODE_NAME)` (из `examples/01_robot/05_sta_conn_helper.py:32`)
      - `playing_stream = audio_player.open(format=pyaudio.paInt16,` (из `examples/04_camera/04_audio_without_playing.py:27`)
  - `close`
    - Сигнатура: `close(self)`
    - Приватный: нет
    - Описание: Close the connection
    - Связи (вызовы): join
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `ep_robot.close()` (из `examples/01_robot/00_logger.py:34`)
      - `ep_robot.close()` (из `examples/01_robot/01_get_version.py:27`)
  - `start_video_recv`
    - Сигнатура: `start_video_recv(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): settimeout, append, connect, print
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `result = robot.start_video_recv()` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:272`)
      - `self.connection.start_video_recv()` (из `examples/plaintext_sample_code/RoboMasterEP/stream/python_stream_liveview/liveview.py:113`)
  - `stop_video_recv`
    - Сигнатура: `stop_video_recv(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): remove
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `robot.stop_video_recv()` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:276`)
      - `self.connection.stop_video_recv()` (из `examples/plaintext_sample_code/RoboMasterEP/stream/python_stream_liveview/liveview.py:130`)
  - `start_audio_recv`
    - Сигнатура: `start_audio_recv(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): settimeout, append, connect, print
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `result = robot.start_audio_recv()` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:286`)
      - `self.connection.start_audio_recv()` (из `examples/plaintext_sample_code/RoboMasterEP/stream/python_stream_liveview/liveview.py:149`)
  - `stop_audio_recv`
    - Сигнатура: `stop_audio_recv(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): remove
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `robot.stop_audio_recv()` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:290`)
      - `self.connection.stop_audio_recv()` (из `examples/plaintext_sample_code/RoboMasterEP/stream/python_stream_liveview/liveview.py:167`)
  - `send_data`
    - Сигнатура: `send_data(self, msg)`
    - Приватный: нет
    - Описание: Send data to control port
    - Связи (вызовы): __send_data
    - Аргументы:
      - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
    - Пример(ы) из репозитория:
      - `robot.send_data('command')` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/direct_connection.py:13`)
      - `robot.send_data('version')` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/direct_connection.py:19`)
  - `recv_video_data`
    - Сигнатура: `recv_video_data(self, timeout=None, latest_data=False)`
    - Приватный: нет
    - Описание: Receive control data
    - Связи (вызовы): __recv_data
    - Аргументы:
      - `timeout`: тип `не указан`; единицы `с`; допустимые значения `не указаны`; параметр `timeout`.
      - `latest_data`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `latest_data`.
    - Пример(ы) из репозитория:
      - `stream_data = robot.recv_video_data(5)` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:274`)
      - `buff = self.connection.recv_video_data()` (из `examples/plaintext_sample_code/RoboMasterEP/stream/python_stream_liveview/liveview.py:116`)
  - `recv_audio_data`
    - Сигнатура: `recv_audio_data(self, timeout=None, latest_data=False)`
    - Приватный: нет
    - Описание: Receive control data
    - Связи (вызовы): __recv_data
    - Аргументы:
      - `timeout`: тип `не указан`; единицы `с`; допустимые значения `не указаны`; параметр `timeout`.
      - `latest_data`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `latest_data`.
    - Пример(ы) из репозитория:
      - `stream_data = robot.recv_audio_data(5)` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:288`)
      - `buff = self.connection.recv_audio_data()` (из `examples/plaintext_sample_code/RoboMasterEP/stream/python_stream_liveview/liveview.py:152`)
  - `recv_ctrl_data`
    - Сигнатура: `recv_ctrl_data(self, timeout=None, latest_data=False)`
    - Приватный: нет
    - Описание: Receive control data
    - Связи (вызовы): __recv_data
    - Аргументы:
      - `timeout`: тип `не указан`; единицы `с`; допустимые значения `не указаны`; параметр `timeout`.
      - `latest_data`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `latest_data`.
    - Пример(ы) из репозитория:
      - `recv = robot.recv_ctrl_data(5)` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/direct_connection.py:15`)
      - `recv = robot.recv_ctrl_data(5)` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/direct_connection.py:21`)
  - `recv_push_data`
    - Сигнатура: `recv_push_data(self, timeout=None, latest_data=False)`
    - Приватный: нет
    - Описание: Receive push data
    - Связи (вызовы): __recv_data
    - Аргументы:
      - `timeout`: тип `не указан`; единицы `с`; допустимые значения `не указаны`; параметр `timeout`.
      - `latest_data`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `latest_data`.
    - Пример: `obj.recv_push_data()`
  - `recv_event_data`
    - Сигнатура: `recv_event_data(self, timeout=None, latest_data=False)`
    - Приватный: нет
    - Описание: Receive event data
    - Связи (вызовы): __recv_data
    - Аргументы:
      - `timeout`: тип `не указан`; единицы `с`; допустимые значения `не указаны`; параметр `timeout`.
      - `latest_data`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `latest_data`.
    - Пример: `obj.recv_event_data()`
  - `__send_data` (приватный)
    - Сигнатура: `__send_data(self, socket_obj, data)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): send, encode
    - Аргументы:
      - `socket_obj`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `socket_obj`.
      - `data`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `data`.
    - Пример(ы) из репозитория:
      - `self.__send_data(self.ctrl_socket, msg)` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:140`)
  - `__recv_data` (приватный)
    - Сигнатура: `__recv_data(self, socket_obj, timeout, latest_data)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): get, qsize
    - Аргументы:
      - `socket_obj`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `socket_obj`.
      - `timeout`: тип `не указан`; единицы `с`; допустимые значения `не указаны`; параметр `timeout`.
      - `latest_data`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `latest_data`.
    - Пример(ы) из репозитория:
      - `return self.__recv_data(self.video_socket, timeout, latest_data)` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:155`)
      - `return self.__recv_data(self.audio_socket, timeout, latest_data)` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:170`)
  - `__socket_recv_task` (приватный)
    - Сигнатура: `__socket_recv_task(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): select, recvfrom, full, put, shutdown, get
    - Аргументы:
      - нет аргументов
    - Пример: `obj.__socket_recv_task()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.connection.network.usb_connection` (`examples/plaintext_sample_code/RoboMasterEP/connection/network/usb_connection.py`)


## Модуль `examples.plaintext_sample_code.RoboMasterEP.connection.uart.uart_connection` (`examples/plaintext_sample_code/RoboMasterEP/connection/uart/uart_connection.py`)


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.docs.benchmark` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/docs/benchmark.py`)

### Функции

#### `generate_dummy_code_pybind11`
- **Сигнатура:** `generate_dummy_code_pybind11(nclasses=10)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** range, randint, join
- **Аргументы:**
  - `nclasses`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `nclasses`.
- **Пример:** `generate_dummy_code_pybind11()`

#### `generate_dummy_code_boost`
- **Сигнатура:** `generate_dummy_code_boost(nclasses=10)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** range, randint, join
- **Аргументы:**
  - `nclasses`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `nclasses`.
- **Пример:** `generate_dummy_code_boost()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.docs.conf` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/docs/conf.py`)

### Функции

#### `generate_doxygen_xml`
- **Сигнатура:** `generate_doxygen_xml(app)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** join, exists, mkdir, call, write, format
- **Аргументы:**
  - `app`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `app`.
- **Пример:** `generate_doxygen_xml(...)`

#### `setup`
- **Сигнатура:** `setup(app)`
- **Приватная:** нет
- **Описание:** Add hook for building doxygen xml when needed
- **Связи (вызовы):** connect
- **Аргументы:**
  - `app`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `app`.
- **Пример:** `setup(...)`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.pybind11.__init__` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/pybind11/__init__.py`)

### Функции

#### `get_include`
- **Сигнатура:** `get_include(user=False)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** dirname, exists, join
- **Аргументы:**
  - `user`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `user`.
- **Пример:** `get_include()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.pybind11.__main__` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/pybind11/__main__.py`)

### Функции

#### `print_includes`
- **Сигнатура:** `print_includes()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** print, get_path, get_include, join, append
- **Аргументы:**
  - нет аргументов
- **Пример:** `print_includes()`

#### `main`
- **Сигнатура:** `main()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** ArgumentParser, add_argument, parse_args, print_help, print_includes
- **Аргументы:**
  - нет аргументов
- **Пример:** `main()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.pybind11._version` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/pybind11/_version.py`)


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.setup` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/setup.py`)

### Классы

### `InstallHeaders`
- **Приватный класс:** нет
- **Описание:** Use custom header installer because the default one flattens subdirectories
- **Конструктор:** явно не определён.
- **Методы:**
  - `run`
    - Сигнатура: `run(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): dirname, join, mkpath, copy_file, append, relpath
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `myqr.run(words=info)` (из `examples/01_robot/05_sta_conn_helper.py:30`)
      - `multi_drone.run([tello_group, basic_task])` (из `examples/15_multi_robot/multi_drone/02_basic.py:35`)

### `BuildPy`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** явно не определён.
- **Методы:**
  - `build_package_data`
    - Сигнатура: `build_package_data(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): build_package_data, join, mkpath, copy_file, dirname
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `build_py.build_package_data(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/setup.py:64`)
      - `build_py.build_package_data(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/setup.py:64`)


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.tests.conftest` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/conftest.py`)

### Функции

#### `_strip_and_dedent` (приватная)
- **Сигнатура:** `_strip_and_dedent(s)`
- **Приватная:** да
- **Описание:** For triple-quote strings
- **Связи (вызовы):** dedent, rstrip, lstrip
- **Аргументы:**
  - `s`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `s`.
- **Пример:** `_strip_and_dedent(...)`

#### `_split_and_sort` (приватная)
- **Сигнатура:** `_split_and_sort(s)`
- **Приватная:** да
- **Описание:** For output which does not require specific line order
- **Связи (вызовы):** sorted, splitlines, _strip_and_dedent
- **Аргументы:**
  - `s`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `s`.
- **Пример:** `_split_and_sort(...)`

#### `_make_explanation` (приватная)
- **Сигнатура:** `_make_explanation(a, b)`
- **Приватная:** да
- **Описание:** Explanation for a failed assert -- the a and b arguments are List[str]
- **Связи (вызовы):** strip, ndiff
- **Аргументы:**
  - `a`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `a`.
  - `b`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `b`.
- **Пример:** `_make_explanation(..., ...)`

#### `capture`
- **Сигнатура:** `capture(capsys)`
- **Приватная:** нет
- **Описание:** Extended `capsys` with context manager and custom equality operators
- **Связи (вызовы):** Capture
- **Аргументы:**
  - `capsys`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `capsys`.
- **Пример:** `capture(...)`

#### `_sanitize_general` (приватная)
- **Сигнатура:** `_sanitize_general(s)`
- **Приватная:** да
- **Описание:** описание отсутствует
- **Связи (вызовы):** strip, replace, sub
- **Аргументы:**
  - `s`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `s`.
- **Пример:** `_sanitize_general(...)`

#### `_sanitize_docstring` (приватная)
- **Сигнатура:** `_sanitize_docstring(thing)`
- **Приватная:** да
- **Описание:** описание отсутствует
- **Связи (вызовы):** _sanitize_general
- **Аргументы:**
  - `thing`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `thing`.
- **Пример:** `_sanitize_docstring(...)`

#### `doc`
- **Сигнатура:** `doc()`
- **Приватная:** нет
- **Описание:** Sanitize docstrings and add custom failure explanation
- **Связи (вызовы):** SanitizedString
- **Аргументы:**
  - нет аргументов
- **Пример:** `doc()`

#### `_sanitize_message` (приватная)
- **Сигнатура:** `_sanitize_message(thing)`
- **Приватная:** да
- **Описание:** описание отсутствует
- **Связи (вызовы):** str, _sanitize_general, sub
- **Аргументы:**
  - `thing`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `thing`.
- **Пример:** `_sanitize_message(...)`

#### `msg`
- **Сигнатура:** `msg()`
- **Приватная:** нет
- **Описание:** Sanitize messages and add custom failure explanation
- **Связи (вызовы):** SanitizedString
- **Аргументы:**
  - нет аргументов
- **Пример:** `msg()`

#### `pytest_assertrepr_compare`
- **Сигнатура:** `pytest_assertrepr_compare(op, left, right)`
- **Приватная:** нет
- **Описание:** Hook to insert custom failure explanation
- **Связи (вызовы):** hasattr
- **Аргументы:**
  - `op`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `op`.
  - `left`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `left`.
  - `right`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `right`.
- **Пример:** `pytest_assertrepr_compare(..., ..., ...)`

#### `suppress`
- **Сигнатура:** `suppress(exception)`
- **Приватная:** нет
- **Описание:** Suppress the desired exception
- **Связи (вызовы):** не выявлены
- **Аргументы:**
  - `exception`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `exception`.
- **Пример(ы) из репозитория:**
  - `with pytest.suppress(ImportError):` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_buffers.py:14`)
  - `with pytest.suppress(ImportError):` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_eigen.py:6`)

#### `gc_collect`
- **Сигнатура:** `gc_collect()`
- **Приватная:** нет
- **Описание:** Run the garbage collector twice (needed when running
- **Связи (вызовы):** collect
- **Аргументы:**
  - нет аргументов
- **Пример(ы) из репозитория:**
  - `pytest.gc_collect()` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_buffers.py:66`)
  - `pytest.gc_collect()` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_buffers.py:69`)

#### `pytest_configure`
- **Сигнатура:** `pytest_configure()`
- **Приватная:** нет
- **Описание:** Add import suppression and test requirements to `pytest` namespace
- **Связи (вызовы):** skipif, python_implementation
- **Аргументы:**
  - нет аргументов
- **Пример:** `pytest_configure()`

#### `_test_import_pybind11` (приватная)
- **Сигнатура:** `_test_import_pybind11()`
- **Приватная:** да
- **Описание:** Early diagnostic for test module initialization errors
- **Связи (вызовы):** print, exit, format, type
- **Аргументы:**
  - нет аргументов
- **Пример:** `_test_import_pybind11()`

### Классы

### `Output`
- **Приватный класс:** нет
- **Описание:** Basic output post-processing and comparison
- **Конструктор:** `__init__(self, string)`
  - **Аргументы конструктора:**
    - `string`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `string`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, string)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `string`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `string`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `__str__` (приватный)
    - Сигнатура: `__str__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.__str__()`
  - `__eq__` (приватный)
    - Сигнатура: `__eq__(self, other)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): splitlines, _make_explanation, _strip_and_dedent, startswith, strip
    - Аргументы:
      - `other`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `other`.
    - Пример: `obj.__eq__(...)`

### `Unordered`
- **Приватный класс:** нет
- **Описание:** Custom comparison for output without strict line ordering
- **Конструктор:** явно не определён.
- **Методы:**
  - `__eq__` (приватный)
    - Сигнатура: `__eq__(self, other)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): _split_and_sort, _make_explanation
    - Аргументы:
      - `other`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `other`.
    - Пример: `obj.__eq__(...)`

### `Capture`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self, capfd)`
  - **Аргументы конструктора:**
    - `capfd`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; инициализационный параметр `capfd`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, capfd)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `capfd`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `capfd`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `__enter__` (приватный)
    - Сигнатура: `__enter__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): readouterr
    - Аргументы:
      - нет аргументов
    - Пример: `obj.__enter__()`
  - `__exit__` (приватный)
    - Сигнатура: `__exit__(self, *args)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): readouterr
    - Аргументы:
      - `*args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `*args`.
    - Пример: `obj.__exit__()`
  - `__eq__` (приватный)
    - Сигнатура: `__eq__(self, other)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): Output
    - Аргументы:
      - `other`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `other`.
    - Пример: `obj.__eq__(...)`
  - `__str__` (приватный)
    - Сигнатура: `__str__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.__str__()`
  - `__contains__` (приватный)
    - Сигнатура: `__contains__(self, item)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `item`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `item`.
    - Пример: `obj.__contains__(...)`
  - `unordered`
    - Сигнатура: `unordered(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): Unordered
    - Аргументы:
      - нет аргументов
    - Пример: `obj.unordered()`
  - `stderr`
    - Сигнатура: `stderr(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): Output
    - Аргументы:
      - нет аргументов
    - Пример: `obj.stderr()`

### `SanitizedString`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self, sanitizer)`
  - **Аргументы конструктора:**
    - `sanitizer`: тип `не указан`; единицы `м`; допустимые значения `0..255`; инициализационный параметр `sanitizer`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, sanitizer)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `sanitizer`: тип `не указан`; единицы `м`; допустимые значения `0..255`; параметр `sanitizer`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `__call__` (приватный)
    - Сигнатура: `__call__(self, thing)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): sanitizer
    - Аргументы:
      - `thing`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `thing`.
    - Пример: `obj.__call__(...)`
  - `__eq__` (приватный)
    - Сигнатура: `__eq__(self, other)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): _strip_and_dedent, _make_explanation, splitlines
    - Аргументы:
      - `other`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `other`.
    - Пример: `obj.__eq__(...)`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.tests.test_async` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_async.py`)

### Функции

#### `event_loop`
- **Сигнатура:** `event_loop()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** new_event_loop, close
- **Аргументы:**
  - нет аргументов
- **Пример:** `event_loop()`

#### `get_await_result`
- **Сигнатура:** `get_await_result(x)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** не выявлены
- **Аргументы:**
  - `x`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `x`.
- **Пример:** `get_await_result(...)`

#### `test_await`
- **Сигнатура:** `test_await(event_loop)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** run_until_complete, get_await_result, SupportsAsync
- **Аргументы:**
  - `event_loop`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `event_loop`.
- **Пример:** `test_await(...)`

#### `test_await_missing`
- **Сигнатура:** `test_await_missing(event_loop)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** raises, run_until_complete, get_await_result, DoesNotSupportAsync
- **Аргументы:**
  - `event_loop`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `event_loop`.
- **Пример:** `test_await_missing(...)`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.tests.test_buffers` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_buffers.py`)

### Функции

#### `test_from_python`
- **Сигнатура:** `test_from_python()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** astype, Matrix, range, get, raises, str
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_from_python()`

#### `test_to_python`
- **Сигнатура:** `test_to_python()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** Matrix, array, get, gc_collect, unpack_from, sum
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_to_python()`

#### `test_inherited_protocol`
- **Сигнатура:** `test_inherited_protocol()`
- **Приватная:** нет
- **Описание:** SquareMatrix is derived from Matrix and inherits the buffer protocol
- **Связи (вызовы):** SquareMatrix, memoryview, asarray
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_inherited_protocol()`

#### `test_pointer_to_member_fn`
- **Сигнатура:** `test_pointer_to_member_fn()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** cls, unpack, bytearray
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_pointer_to_member_fn()`

#### `test_readonly_buffer`
- **Сигнатура:** `test_readonly_buffer()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** BufferReadOnly, memoryview
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_readonly_buffer()`

#### `test_selective_readonly_buffer`
- **Сигнатура:** `test_selective_readonly_buffer()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** BufferReadOnlySelect, readinto, memoryview, ord, raises, BytesIO
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_selective_readonly_buffer()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.tests.test_builtin_casters` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_builtin_casters.py`)

### Функции

#### `test_simple_string`
- **Сигнатура:** `test_simple_string()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** string_roundtrip
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_simple_string()`

#### `test_unicode_conversion`
- **Сигнатура:** `test_unicode_conversion()`
- **Приватная:** нет
- **Описание:** Tests unicode conversion and error reporting.
- **Связи (вызовы):** hasattr, good_utf8_string, good_utf16_string, good_utf32_string, good_wchar_string, raises
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_unicode_conversion()`

#### `test_single_char_arguments`
- **Сигнатура:** `test_single_char_arguments()`
- **Приватная:** нет
- **Описание:** Tests failures for passing invalid inputs to char-accepting functions
- **Связи (вызовы):** format, ord_char, ord_char_lv, raises, str, toobig_message
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_single_char_arguments()`

#### `test_bytes_to_string`
- **Сигнатура:** `test_bytes_to_string()`
- **Приватная:** нет
- **Описание:** Tests the ability to pass bytes to C++ string-accepting functions.  Note that this is
- **Связи (вызовы):** strlen, string_length, byte, encode
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_bytes_to_string()`

#### `test_string_view`
- **Сигнатура:** `test_string_view(capture)`
- **Приватная:** нет
- **Описание:** Tests support for C++17 string_view arguments and return values
- **Связи (вызовы):** skipif, string_view_chars, string_view16_chars, string_view32_chars, string_view_return, string_view16_return
- **Аргументы:**
  - `capture`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `capture`.
- **Пример:** `test_string_view(...)`

#### `test_integer_casting`
- **Сигнатура:** `test_integer_casting()`
- **Приватная:** нет
- **Описание:** Issue #929 - out-of-range integer values shouldn't be accepted
- **Связи (вызовы):** i32_str, i64_str, u32_str, raises, str, u64_str
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_integer_casting()`

#### `test_tuple`
- **Сигнатура:** `test_tuple(doc)`
- **Приватная:** нет
- **Описание:** std::pair <-> tuple & std::tuple <-> tuple
- **Связи (вызовы):** pair_passthrough, tuple_passthrough, empty_tuple, doc, rvalue_pair, lvalue_pair
- **Аргументы:**
  - `doc`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `doc`.
- **Пример:** `test_tuple(...)`

#### `test_builtins_cast_return_none`
- **Сигнатура:** `test_builtins_cast_return_none()`
- **Приватная:** нет
- **Описание:** Casters produced with PYBIND11_TYPE_CASTER() should convert nullptr to None
- **Связи (вызовы):** return_none_string, return_none_char, return_none_bool, return_none_int, return_none_float
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_builtins_cast_return_none()`

#### `test_none_deferred`
- **Сигнатура:** `test_none_deferred()`
- **Приватная:** нет
- **Описание:** None passed as various argument types should defer to other overloads
- **Связи (вызовы):** defer_none_cstring, defer_none_custom, nodefer_none_void, UserType
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_none_deferred()`

#### `test_void_caster`
- **Сигнатура:** `test_void_caster()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** load_nullptr_t, cast_nullptr_t
- **Аргументы:**
  - нет аргументов
- **Пример(ы) из репозитория:**
  - `assert m.test_void_caster()` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_builtin_casters.py:346`)
  - `assert m.test_void_caster()` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/tests/test_builtin_casters.py:346`)

#### `test_reference_wrapper`
- **Сигнатура:** `test_reference_wrapper()`
- **Приватная:** нет
- **Описание:** std::reference_wrapper for builtin and user types
- **Связи (вызовы):** refwrap_list, refwrap_builtin, refwrap_usertype, raises, str, refwrap_iiw
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_reference_wrapper()`

#### `test_complex_cast`
- **Сигнатура:** `test_complex_cast()`
- **Приватная:** нет
- **Описание:** std::complex casts
- **Связи (вызовы):** complex_cast
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_complex_cast()`

#### `test_bool_caster`
- **Сигнатура:** `test_bool_caster()`
- **Приватная:** нет
- **Описание:** Test bool caster implicit conversions.
- **Связи (вызовы):** require_implicit, cant_convert, raises, convert, noconvert, object
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_bool_caster()`

#### `test_numpy_bool`
- **Сигнатура:** `test_numpy_bool()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** cant_convert, raises, convert, noconvert, zeros, bool_
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_numpy_bool()`

#### `test_int_long`
- **Сигнатура:** `test_int_long()`
- **Приватная:** нет
- **Описание:** In Python 2, a C++ int should return a Python int rather than long
- **Связи (вызовы):** type, isinstance, int_cast, long_cast, longlong_cast, getattr
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_int_long()`

#### `test_void_caster_2`
- **Сигнатура:** `test_void_caster_2()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** test_void_caster
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_void_caster_2()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.tests.test_call_policies` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py`)

### Функции

#### `test_keep_alive_argument`
- **Сигнатура:** `test_keep_alive_argument(capture)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** detail_reg_inst, Parent, addChild, addChildKeepAlive, Child
- **Аргументы:**
  - `capture`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `capture`.
- **Пример:** `test_keep_alive_argument(...)`

#### `test_keep_alive_return_value`
- **Сигнатура:** `test_keep_alive_return_value(capture)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** detail_reg_inst, Parent, returnChild, returnChildKeepAlive
- **Аргументы:**
  - `capture`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `capture`.
- **Пример:** `test_keep_alive_return_value(...)`

#### `test_alive_gc`
- **Сигнатура:** `test_alive_gc(capture)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** detail_reg_inst, ParentGC, addChildKeepAlive, append, Child
- **Аргументы:**
  - `capture`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `capture`.
- **Пример:** `test_alive_gc(...)`

#### `test_alive_gc_derived`
- **Сигнатура:** `test_alive_gc_derived(capture)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** detail_reg_inst, Derived, addChildKeepAlive, append, Child
- **Аргументы:**
  - `capture`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `capture`.
- **Пример:** `test_alive_gc_derived(...)`

#### `test_alive_gc_multi_derived`
- **Сигнатура:** `test_alive_gc_multi_derived(capture)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** detail_reg_inst, Derived, addChildKeepAlive, append, Child, __init__
- **Аргументы:**
  - `capture`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `capture`.
- **Пример:** `test_alive_gc_multi_derived(...)`

#### `test_return_none`
- **Сигнатура:** `test_return_none(capture)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** detail_reg_inst, Parent, returnNullChildKeepAliveChild, returnNullChildKeepAliveParent
- **Аргументы:**
  - `capture`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `capture`.
- **Пример:** `test_return_none(...)`

#### `test_keep_alive_constructor`
- **Сигнатура:** `test_keep_alive_constructor(capture)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** detail_reg_inst, Parent, Child
- **Аргументы:**
  - `capture`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `capture`.
- **Пример:** `test_keep_alive_constructor(...)`

#### `test_call_guard`
- **Сигнатура:** `test_call_guard()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** hasattr, unguarded_call, guarded_call, multiple_guards_correct_order, multiple_guards_wrong_order, with_gil
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_call_guard()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.tests.test_callbacks` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_callbacks.py`)

### Функции

#### `test_callbacks`
- **Сигнатура:** `test_callbacks()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** test_callback4, test_callback5, format, test_callback1, test_callback2, test_callback3
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_callbacks()`

#### `test_bound_method_callback`
- **Сигнатура:** `test_bound_method_callback()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** MyClass, CppBoundMethodTest, test_callback3
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_bound_method_callback()`

#### `test_keyword_args_and_generalized_unpacking`
- **Сигнатура:** `test_keyword_args_and_generalized_unpacking()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** test_tuple_unpacking, test_dict_unpacking, test_keyword_args, test_unpacking_and_keywords1, test_unpacking_and_keywords2, raises
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_keyword_args_and_generalized_unpacking()`

#### `test_lambda_closure_cleanup`
- **Сигнатура:** `test_lambda_closure_cleanup()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** test_cleanup, payload_cstats, alive
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_lambda_closure_cleanup()`

#### `test_cpp_function_roundtrip`
- **Сигнатура:** `test_cpp_function_roundtrip()`
- **Приватная:** нет
- **Описание:** Test if passing a function pointer from C++ -> Python -> C++ yields the original pointer
- **Связи (вызовы):** any, test_dummy_function, roundtrip, raises, str
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_cpp_function_roundtrip()`

#### `test_function_signatures`
- **Сигнатура:** `test_function_signatures(doc)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** doc
- **Аргументы:**
  - `doc`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `doc`.
- **Пример:** `test_function_signatures(...)`

#### `test_movable_object`
- **Сигнатура:** `test_movable_object()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** callback_with_movable
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_movable_object()`

#### `test_async_callbacks`
- **Сигнатура:** `test_async_callbacks()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** test_async_callback, sleep, Item, gen_f, sum, append
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_async_callbacks()`

#### `test_async_async_callbacks`
- **Сигнатура:** `test_async_async_callbacks()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** Thread, start, join
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_async_async_callbacks()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.tests.test_chrono` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_chrono.py`)

### Функции

#### `test_chrono_system_clock`
- **Сигнатура:** `test_chrono_system_clock()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** test_chrono1, today, isinstance, abs
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_chrono_system_clock()`

#### `test_chrono_system_clock_roundtrip`
- **Сигнатура:** `test_chrono_system_clock_roundtrip()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** today, test_chrono2, isinstance, abs
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_chrono_system_clock_roundtrip()`

#### `test_chrono_system_clock_roundtrip_date`
- **Сигнатура:** `test_chrono_system_clock_roundtrip_date()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** today, test_chrono2, date, time, isinstance, abs
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_chrono_system_clock_roundtrip_date()`

#### `test_chrono_system_clock_roundtrip_time`
- **Сигнатура:** `test_chrono_system_clock_roundtrip_time()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** time, test_chrono2, date, isinstance, today
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_chrono_system_clock_roundtrip_time()`

#### `test_chrono_duration_roundtrip`
- **Сигнатура:** `test_chrono_duration_roundtrip()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** today, isinstance, test_chrono3
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_chrono_duration_roundtrip()`

#### `test_chrono_duration_subtraction_equivalence`
- **Сигнатура:** `test_chrono_duration_subtraction_equivalence()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** today, test_chrono4
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_chrono_duration_subtraction_equivalence()`

#### `test_chrono_duration_subtraction_equivalence_date`
- **Сигнатура:** `test_chrono_duration_subtraction_equivalence_date()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** today, test_chrono4
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_chrono_duration_subtraction_equivalence_date()`

#### `test_chrono_steady_clock`
- **Сигнатура:** `test_chrono_steady_clock()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** test_chrono5, isinstance
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_chrono_steady_clock()`

#### `test_chrono_steady_clock_roundtrip`
- **Сигнатура:** `test_chrono_steady_clock_roundtrip()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** timedelta, test_chrono6, isinstance
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_chrono_steady_clock_roundtrip()`

#### `test_floating_point_duration`
- **Сигнатура:** `test_floating_point_duration()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** test_chrono7, isinstance, test_chrono_float_diff
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_floating_point_duration()`

#### `test_nano_timepoint`
- **Сигнатура:** `test_nano_timepoint()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** now, test_nano_timepoint, timedelta
- **Аргументы:**
  - нет аргументов
- **Пример(ы) из репозитория:**
  - `time1 = m.test_nano_timepoint(time, datetime.timedelta(seconds=60))` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_chrono.py:175`)
  - `time1 = m.test_nano_timepoint(time, datetime.timedelta(seconds=60))` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/tests/test_chrono.py:175`)


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.tests.test_class` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_class.py`)

### Функции

#### `test_repr`
- **Сигнатура:** `test_repr()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** repr, type
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_repr()`

#### `test_instance`
- **Сигнатура:** `test_instance(msg)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** new_instance, get, raises, NoConstructor, msg, alive
- **Аргументы:**
  - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
- **Пример:** `test_instance(...)`

#### `test_docstrings`
- **Сигнатура:** `test_docstrings(doc)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** doc
- **Аргументы:**
  - `doc`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `doc`.
- **Пример:** `test_docstrings(...)`

#### `test_qualname`
- **Сигнатура:** `test_qualname(doc)`
- **Приватная:** нет
- **Описание:** Tests that a properly qualified name is set in __qualname__ (even in pre-3.3, where we
- **Связи (вызовы):** doc
- **Аргументы:**
  - `doc`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `doc`.
- **Пример:** `test_qualname(...)`

#### `test_inheritance`
- **Сигнатура:** `test_inheritance(msg)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** Rabbit, Pet, Dog, Hamster, pet_name_species, dog_bark
- **Аргументы:**
  - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
- **Пример:** `test_inheritance(...)`

#### `test_automatic_upcasting`
- **Сигнатура:** `test_automatic_upcasting()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** type, return_class_1, return_class_2, return_none, return_class_n
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_automatic_upcasting()`

#### `test_isinstance`
- **Сигнатура:** `test_isinstance()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** check_instances, tuple, dict, Pet, Dog
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_isinstance()`

#### `test_mismatched_holder`
- **Сигнатура:** `test_mismatched_holder()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** match, raises, mismatched_holder_1, str, mismatched_holder_2
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_mismatched_holder()`

#### `test_override_static`
- **Сигнатура:** `test_override_static()`
- **Приватная:** нет
- **Описание:** #511: problem with inheritance + overwritten def_static
- **Связи (вызовы):** make, make2, isinstance
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_override_static()`

#### `test_implicit_conversion_life_support`
- **Сигнатура:** `test_implicit_conversion_life_support()`
- **Приватная:** нет
- **Описание:** Ensure the lifetime of temporary objects created for implicit conversions
- **Связи (вызовы):** implicitly_convert_argument, implicitly_convert_variable, implicitly_convert_variable_fail, UserType
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_implicit_conversion_life_support()`

#### `test_operator_new_delete`
- **Сигнатура:** `test_operator_new_delete(capture)`
- **Приватная:** нет
- **Описание:** Tests that class-specific operator new/delete functions are invoked
- **Связи (вызовы):** str, HasOpNewDel, HasOpNewDelSize, HasOpNewDelBoth, AliasedHasOpNewDelSize, SubAliased
- **Аргументы:**
  - `capture`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `capture`.
- **Пример:** `test_operator_new_delete(...)`

#### `test_bind_protected_functions`
- **Сигнатура:** `test_bind_protected_functions()`
- **Приватная:** нет
- **Описание:** Expose protected member functions to Python using a helper class
- **Связи (вызовы):** ProtectedA, ProtectedB, C, foo, __init__
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_bind_protected_functions()`

#### `test_brace_initialization`
- **Сигнатура:** `test_brace_initialization()`
- **Приватная:** нет
- **Описание:** Tests that simple POD classes can be constructed using C++11 brace initialization
- **Связи (вызовы):** BraceInitialization, NoBraceInitialization
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_brace_initialization()`

#### `test_class_refcount`
- **Сигнатура:** `test_class_refcount()`
- **Приватная:** нет
- **Описание:** Instances must correctly increase/decrease the reference count of their types (#1029)
- **Связи (вызовы):** getrefcount, gc_collect, cls, range
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_class_refcount()`

#### `test_reentrant_implicit_conversion_failure`
- **Сигнатура:** `test_reentrant_implicit_conversion_failure(msg)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** raises, BogusImplicitConversion, msg
- **Аргументы:**
  - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
- **Пример:** `test_reentrant_implicit_conversion_failure(...)`

#### `test_error_after_conversions`
- **Сигнатура:** `test_error_after_conversions()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** startswith, raises, test_error_after_conversions, str
- **Аргументы:**
  - нет аргументов
- **Пример(ы) из репозитория:**
  - `m.test_error_after_conversions("hello")` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_class.py:273`)
  - `m.test_error_after_conversions("hello")` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/tests/test_class.py:273`)

#### `test_aligned`
- **Сигнатура:** `test_aligned()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** hasattr, ptr, Aligned
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_aligned()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.tests.test_cmake_build.test` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_cmake_build/test.py`)


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.tests.test_constants_and_functions` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_constants_and_functions.py`)

### Функции

#### `test_constants`
- **Сигнатура:** `test_constants()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** не выявлены
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_constants()`

#### `test_function_overloading`
- **Сигнатура:** `test_function_overloading()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** test_function
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_function_overloading()`

#### `test_bytes`
- **Сигнатура:** `test_bytes()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** print_bytes, return_bytes
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_bytes()`

#### `test_exception_specifiers`
- **Сигнатура:** `test_exception_specifiers()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** C, m1, m2, m3, m4, m5
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_exception_specifiers()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.tests.test_copy_move` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_copy_move.py`)

### Функции

#### `test_lacking_copy_ctor`
- **Сигнатура:** `test_lacking_copy_ctor()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** raises, get_one, str
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_lacking_copy_ctor()`

#### `test_lacking_move_ctor`
- **Сигнатура:** `test_lacking_move_ctor()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** raises, get_one, str
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_lacking_move_ctor()`

#### `test_move_and_copy_casts`
- **Сигнатура:** `test_move_and_copy_casts()`
- **Приватная:** нет
- **Описание:** Cast some values in C++ via custom type casters and count the number of moves/copies.
- **Связи (вызовы):** move_and_copy_cstats, move_and_copy_casts, alive
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_move_and_copy_casts()`

#### `test_move_and_copy_loads`
- **Сигнатура:** `test_move_and_copy_loads()`
- **Приватная:** нет
- **Описание:** Call some functions that load arguments via custom type casters and count the number of
- **Связи (вызовы):** move_and_copy_cstats, move_only, move_or_copy, copy_only, move_pair, move_tuple
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_move_and_copy_loads()`

#### `test_move_and_copy_load_optional`
- **Сигнатура:** `test_move_and_copy_load_optional()`
- **Приватная:** нет
- **Описание:** Tests move/copy loads of std::optional arguments
- **Связи (вызовы):** skipif, move_and_copy_cstats, move_optional, move_or_copy_optional, copy_optional, move_optional_tuple
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_move_and_copy_load_optional()`

#### `test_private_op_new`
- **Сигнатура:** `test_private_op_new()`
- **Приватная:** нет
- **Описание:** An object with a private `operator new` cannot be returned by value
- **Связи (вызовы):** raises, private_op_new_value, str, private_op_new_reference
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_private_op_new()`

#### `test_move_fallback`
- **Сигнатура:** `test_move_fallback()`
- **Приватная:** нет
- **Описание:** #389: rvp::move should fall-through to copy on non-movable objects
- **Связи (вызовы):** get_moveissue2, get_moveissue1
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_move_fallback()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.tests.test_docstring_options` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_docstring_options.py`)

### Функции

#### `test_docstring_options`
- **Сигнатура:** `test_docstring_options()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** startswith, endswith
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_docstring_options()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.tests.test_eigen` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_eigen.py`)

### Функции

#### `assert_equal_ref`
- **Сигнатура:** `assert_equal_ref(mat)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** assert_array_equal
- **Аргументы:**
  - `mat`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `mat`.
- **Пример:** `assert_equal_ref(...)`

#### `assert_sparse_equal_ref`
- **Сигнатура:** `assert_sparse_equal_ref(sparse_mat)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** assert_equal_ref, toarray
- **Аргументы:**
  - `sparse_mat`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `sparse_mat`.
- **Пример:** `assert_sparse_equal_ref(...)`

#### `test_fixed`
- **Сигнатура:** `test_fixed()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** assert_equal_ref, fixed_c, fixed_r, fixed_copy_r, fixed_copy_c
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_fixed()`

#### `test_dense`
- **Сигнатура:** `test_dense()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** assert_equal_ref, dense_r, dense_c, dense_copy_r, dense_copy_c
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_dense()`

#### `test_partially_fixed`
- **Сигнатура:** `test_partially_fixed()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** array, assert_array_equal, partial_copy_four_rm_r, partial_copy_four_rm_c, partial_copy_four_cm_r, partial_copy_four_cm_c
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_partially_fixed()`

#### `test_mutator_descriptors`
- **Сигнатура:** `test_mutator_descriptors()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** reshape, transpose, fixed_mutator_r, fixed_mutator_c, fixed_mutator_a, raises
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_mutator_descriptors()`

#### `test_cpp_casting`
- **Сигнатура:** `test_cpp_casting()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** array, cpp_copy, cpp_ref_c, cpp_ref_r, raises, cpp_ref_any
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_cpp_casting()`

#### `test_pass_readonly_array`
- **Сигнатура:** `test_pass_readonly_array()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** full, assert_array_equal, fixed_copy_r, fixed_r_const, fixed_r
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_pass_readonly_array()`

#### `test_nonunit_stride_from_python`
- **Сигнатура:** `test_nonunit_stride_from_python()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** reshape, assert_array_equal, enumerate, double_threer, double_threec, double_row
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_nonunit_stride_from_python()`

#### `test_negative_stride_from_python`
- **Сигнатура:** `test_negative_stride_from_python(msg)`
- **Приватная:** нет
- **Описание:** Eigen doesn't support (as of yet) negative strides. When a function takes an Eigen matrix by
- **Связи (вызовы):** reshape, assert_array_equal, enumerate, double_row, double_col, double_complex
- **Аргументы:**
  - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
- **Пример:** `test_negative_stride_from_python(...)`

#### `test_nonunit_stride_to_python`
- **Сигнатура:** `test_nonunit_stride_to_python()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** all, range, format, diagonal, diagonal_1, block
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_nonunit_stride_to_python()`

#### `test_eigen_ref_to_python`
- **Сигнатура:** `test_eigen_ref_to_python()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** enumerate, chol, all, format, array
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_eigen_ref_to_python()`

#### `assign_both`
- **Сигнатура:** `assign_both(a1, a2, r, c, v)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** не выявлены
- **Аргументы:**
  - `a1`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `a1`.
  - `a2`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `a2`.
  - `r`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `r`.
  - `c`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `c`.
  - `v`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `v`.
- **Пример:** `assign_both(..., ..., ..., ..., ...)`

#### `array_copy_but_one`
- **Сигнатура:** `array_copy_but_one(a, r, c, v)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** array
- **Аргументы:**
  - `a`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `a`.
  - `r`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `r`.
  - `c`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `c`.
  - `v`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `v`.
- **Пример:** `array_copy_but_one(..., ..., ..., ...)`

#### `test_eigen_return_references`
- **Сигнатура:** `test_eigen_return_references()`
- **Приватная:** нет
- **Описание:** Tests various ways of returning references and non-referencing copies
- **Связи (вызовы):** ones, ReturnTester, get, assign_both, get_ptr, view
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_eigen_return_references()`

#### `assert_keeps_alive`
- **Сигнатура:** `assert_keeps_alive(cl, method, *args)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** get, alive, cl, method
- **Аргументы:**
  - `cl`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `cl`.
  - `method`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `method`.
  - `*args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `*args`.
- **Пример:** `assert_keeps_alive(..., ...)`

#### `test_eigen_keepalive`
- **Сигнатура:** `test_eigen_keepalive()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** ReturnTester, get, alive, ref, ref_const, block
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_eigen_keepalive()`

#### `test_eigen_ref_mutators`
- **Сигнатура:** `test_eigen_ref_mutators()`
- **Приватная:** нет
- **Описание:** Tests Eigen's ability to mutate numpy values
- **Связи (вызовы):** array, add_rm, all, add_cm, add_any, add1
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_eigen_ref_mutators()`

#### `test_numpy_ref_mutators`
- **Сигнатура:** `test_numpy_ref_mutators()`
- **Приватная:** нет
- **Описание:** Tests numpy mutating Eigen matrices (for returned Eigen::Ref<...>s)
- **Связи (вызовы):** reset_refs, get_cm_ref, get_cm_const_ref, get_rm_ref, get_rm_const_ref, array
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_numpy_ref_mutators()`

#### `test_both_ref_mutators`
- **Сигнатура:** `test_both_ref_mutators()`
- **Приватная:** нет
- **Описание:** Tests a complex chain of nested eigen/numpy references
- **Связи (вызовы):** reset_refs, get_cm_ref, incr_matrix, all, array, reshape
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_both_ref_mutators()`

#### `test_nocopy_wrapper`
- **Сигнатура:** `test_nocopy_wrapper()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** array, get_elem, raises, get_elem_nocopy, get_elem_rm_nocopy, str
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_nocopy_wrapper()`

#### `test_eigen_ref_life_support`
- **Сигнатура:** `test_eigen_ref_life_support()`
- **Приватная:** нет
- **Описание:** Ensure the lifetime of temporary arrays created by the `Ref` caster
- **Связи (вызовы):** full, get_elem_direct, get_elem_indirect
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_eigen_ref_life_support()`

#### `test_special_matrix_objects`
- **Сигнатура:** `test_special_matrix_objects()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** all, array, range, incr_diag, diag, symmetric_lower
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_special_matrix_objects()`

#### `test_dense_signature`
- **Сигнатура:** `test_dense_signature(doc)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** doc
- **Аргументы:**
  - `doc`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `doc`.
- **Пример:** `test_dense_signature(...)`

#### `test_named_arguments`
- **Сигнатура:** `test_named_arguments()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** array, ones, all, raises, matrix_multiply, str
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_named_arguments()`

#### `test_sparse`
- **Сигнатура:** `test_sparse()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** assert_sparse_equal_ref, sparse_r, sparse_c, sparse_copy_r, sparse_copy_c
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_sparse()`

#### `test_sparse_signature`
- **Сигнатура:** `test_sparse_signature(doc)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** doc
- **Аргументы:**
  - `doc`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `doc`.
- **Пример:** `test_sparse_signature(...)`

#### `test_issue738`
- **Сигнатура:** `test_issue738()`
- **Приватная:** нет
- **Описание:** Ignore strides on a length-1 dimension (even if they would be incompatible length > 1)
- **Связи (вызовы):** all, iss738_f1, array, iss738_f2
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_issue738()`

#### `test_issue1105`
- **Сигнатура:** `test_issue1105()`
- **Приватная:** нет
- **Описание:** Issue 1105: 1xN or Nx1 input arrays weren't accepted for eigen
- **Связи (вызовы):** iss1105_row, iss1105_col, ones, raises, str
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_issue1105()`

#### `test_custom_operator_new`
- **Сигнатура:** `test_custom_operator_new()`
- **Приватная:** нет
- **Описание:** Using Eigen types as member variables requires a class-specific
- **Связи (вызовы):** CustomOperatorNew, assert_allclose, diagonal
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_custom_operator_new()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.tests.test_embed.test_interpreter` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_embed/test_interpreter.py`)

### Классы

### `DerivedWidget`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self, message)`
  - **Аргументы конструктора:**
    - `message`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `message`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, message)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): __init__, super
    - Аргументы:
      - `message`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `message`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `the_answer`
    - Сигнатура: `the_answer(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.the_answer()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.tests.test_enum` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_enum.py`)

### Функции

#### `test_unscoped_enum`
- **Сигнатура:** `test_unscoped_enum()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** split, str, raises, object, int, UnscopedEnum
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_unscoped_enum()`

#### `test_scoped_enum`
- **Сигнатура:** `test_scoped_enum()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** test_scoped_enum, object, raises
- **Аргументы:**
  - нет аргументов
- **Пример(ы) из репозитория:**
  - `assert m.test_scoped_enum(m.ScopedEnum.Three) == "ScopedEnum::Three"` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_enum.py:108`)
  - `assert m.test_scoped_enum(z) == "ScopedEnum::Two"` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_enum.py:110`)

#### `test_implicit_conversion`
- **Сигнатура:** `test_implicit_conversion()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** str, f, int
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_implicit_conversion()`

#### `test_binary_operators`
- **Сигнатура:** `test_binary_operators()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** int
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_binary_operators()`

#### `test_enum_to_int`
- **Сигнатура:** `test_enum_to_int()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** test_enum_to_int, test_enum_to_uint, test_enum_to_long_long
- **Аргументы:**
  - нет аргументов
- **Пример(ы) из репозитория:**
  - `m.test_enum_to_int(m.Flags.Read)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_enum.py:195`)
  - `m.test_enum_to_int(m.ClassWithUnscopedEnum.EMode.EFirstMode)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_enum.py:196`)

#### `test_duplicate_enum_name`
- **Сигнатура:** `test_duplicate_enum_name()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** raises, register_bad_enum, str
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_duplicate_enum_name()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.tests.test_eval` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_eval.py`)

### Функции

#### `test_evals`
- **Сигнатура:** `test_evals(capture)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** test_eval, test_eval_single_statement, join, test_eval_file, test_eval_failure, test_eval_file_failure
- **Аргументы:**
  - `capture`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `capture`.
- **Пример:** `test_evals(...)`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.tests.test_eval_call` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_eval_call.py`)


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.tests.test_exceptions` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_exceptions.py`)

### Функции

#### `test_std_exception`
- **Сигнатура:** `test_std_exception(msg)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** raises, throw_std_exception, msg
- **Аргументы:**
  - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
- **Пример:** `test_std_exception(...)`

#### `test_error_already_set`
- **Сигнатура:** `test_error_already_set(msg)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** raises, throw_already_set, msg
- **Аргументы:**
  - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
- **Пример:** `test_error_already_set(...)`

#### `test_cross_module_exceptions`
- **Сигнатура:** `test_cross_module_exceptions()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** raises, raise_runtime_error, str, raise_value_error, throw_pybind_value_error, throw_pybind_type_error
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_cross_module_exceptions()`

#### `test_python_call_in_catch`
- **Сигнатура:** `test_python_call_in_catch()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** python_call_in_destructor
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_python_call_in_catch()`

#### `test_exception_matches`
- **Сигнатура:** `test_exception_matches()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** exception_matches, exception_matches_base, modulenotfound_exception_matches_base
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_exception_matches()`

#### `test_custom`
- **Сигнатура:** `test_custom(msg)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** isinstance, raises, throws1, msg, throws2, throws3
- **Аргументы:**
  - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
- **Пример:** `test_custom(...)`

#### `test_nested_throws`
- **Сигнатура:** `test_nested_throws(capture)`
- **Приватная:** нет
- **Описание:** Tests nested (e.g. C++ -> Python -> C++) exception handling
- **Связи (вызовы):** startswith, MyException, MyException5, try_catch, raises, str
- **Аргументы:**
  - `capture`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `capture`.
- **Пример:** `test_nested_throws(...)`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.tests.test_factory_constructors` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_factory_constructors.py`)

### Функции

#### `test_init_factory_basic`
- **Сигнатура:** `test_init_factory_basic()`
- **Приватная:** нет
- **Описание:** Tests py::init_factory() wrapper around various ways of returning the object
- **Связи (вызовы):** alive, detail_reg_inst, TestFactory1, TestFactory2, TestFactory3, get
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_init_factory_basic()`

#### `test_init_factory_signature`
- **Сигнатура:** `test_init_factory_signature(msg)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** raises, TestFactory1, msg
- **Аргументы:**
  - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
- **Пример:** `test_init_factory_signature(...)`

#### `test_init_factory_casting`
- **Сигнатура:** `test_init_factory_casting()`
- **Приватная:** нет
- **Описание:** Tests py::init_factory() wrapper with various upcasting and downcasting returns
- **Связи (вызовы):** alive, detail_reg_inst, TestFactory3, TestFactory4, get, values
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_init_factory_casting()`

#### `test_init_factory_alias`
- **Сигнатура:** `test_init_factory_alias()`
- **Приватная:** нет
- **Описание:** Tests py::init_factory() wrapper with value conversions and alias types
- **Связи (вызовы):** alive, detail_reg_inst, TestFactory6, has_alias, MyTest, get_cstats
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_init_factory_alias()`

#### `test_init_factory_dual`
- **Сигнатура:** `test_init_factory_dual()`
- **Приватная:** нет
- **Описание:** Tests init factory functions with dual main/alias factory functions
- **Связи (вызовы):** alive, detail_reg_inst, TestFactory7, PythFactory7, has_alias, get_cstats
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_init_factory_dual()`

#### `test_no_placement_new`
- **Сигнатура:** `test_no_placement_new(capture)`
- **Приватная:** нет
- **Описание:** Prior to 2.2, `py::init<...>` relied on the type supporting placement
- **Связи (вызовы):** search, NoPlacementNew, str, gc_collect, group
- **Аргументы:**
  - `capture`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `capture`.
- **Пример:** `test_no_placement_new(...)`

#### `test_multiple_inheritance`
- **Сигнатура:** `test_multiple_inheritance()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** MITest, fget, __init__
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_multiple_inheritance()`

#### `create_and_destroy`
- **Сигнатура:** `create_and_destroy(*args)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** NoisyAlloc, print, gc_collect
- **Аргументы:**
  - `*args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `*args`.
- **Пример:** `create_and_destroy()`

#### `strip_comments`
- **Сигнатура:** `strip_comments(s)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** sub
- **Аргументы:**
  - `s`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `s`.
- **Пример:** `strip_comments(...)`

#### `test_reallocations`
- **Сигнатура:** `test_reallocations(capture, msg)`
- **Приватная:** нет
- **Описание:** When the constructor is overloaded, previous overloads can require a preallocated value.
- **Связи (вызовы):** gc_collect, create_and_destroy, msg, strip_comments
- **Аргументы:**
  - `capture`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `capture`.
  - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
- **Пример:** `test_reallocations(..., ...)`

#### `test_invalid_self`
- **Сигнатура:** `test_invalid_self()`
- **Приватная:** нет
- **Описание:** Tests invocation of the pybind-registered base class with an invalid `self` argument.  You
- **Связи (вызовы):** raises, BrokenTF1, str, BrokenTF6, TestFactory2, __init__
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_invalid_self()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.tests.test_gil_scoped` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_gil_scoped.py`)

### Функции

#### `_run_in_process` (приватная)
- **Сигнатура:** `_run_in_process(target, *args, **kwargs)`
- **Приватная:** да
- **Описание:** Runs target in process and returns its exitcode after 10s (None if still alive).
- **Связи (вызовы):** Process, start, join, is_alive, terminate
- **Аргументы:**
  - `target`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `target`.
  - `*args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `*args`.
  - `**kwargs`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `**kwargs`.
- **Пример:** `_run_in_process(...)`

#### `_python_to_cpp_to_python` (приватная)
- **Сигнатура:** `_python_to_cpp_to_python()`
- **Приватная:** да
- **Описание:** Calls different C++ functions that come back to Python.
- **Связи (вызовы):** ExtendedVirtClass, test_callback_py_obj, test_callback_std_func, test_callback_virtual_func, test_callback_pure_virtual_func
- **Аргументы:**
  - нет аргументов
- **Пример:** `_python_to_cpp_to_python()`

#### `_python_to_cpp_to_python_from_threads` (приватная)
- **Сигнатура:** `_python_to_cpp_to_python_from_threads(num_threads, parallel=False)`
- **Приватная:** да
- **Описание:** Calls different C++ functions that come back to Python, from Python threads.
- **Связи (вызовы):** range, Thread, start, join, append
- **Аргументы:**
  - `num_threads`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `num_threads`.
  - `parallel`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `parallel`.
- **Пример:** `_python_to_cpp_to_python_from_threads(...)`

#### `test_python_to_cpp_to_python_from_thread`
- **Сигнатура:** `test_python_to_cpp_to_python_from_thread()`
- **Приватная:** нет
- **Описание:** Makes sure there is no GIL deadlock when running in a thread.
- **Связи (вызовы):** _run_in_process
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_python_to_cpp_to_python_from_thread()`

#### `test_python_to_cpp_to_python_from_thread_multiple_parallel`
- **Сигнатура:** `test_python_to_cpp_to_python_from_thread_multiple_parallel()`
- **Приватная:** нет
- **Описание:** Makes sure there is no GIL deadlock when running in a thread multiple times in parallel.
- **Связи (вызовы):** _run_in_process
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_python_to_cpp_to_python_from_thread_multiple_parallel()`

#### `test_python_to_cpp_to_python_from_thread_multiple_sequential`
- **Сигнатура:** `test_python_to_cpp_to_python_from_thread_multiple_sequential()`
- **Приватная:** нет
- **Описание:** Makes sure there is no GIL deadlock when running in a thread multiple times sequentially.
- **Связи (вызовы):** _run_in_process
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_python_to_cpp_to_python_from_thread_multiple_sequential()`

#### `test_python_to_cpp_to_python_from_process`
- **Сигнатура:** `test_python_to_cpp_to_python_from_process()`
- **Приватная:** нет
- **Описание:** Makes sure there is no GIL deadlock when using processes.
- **Связи (вызовы):** _run_in_process
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_python_to_cpp_to_python_from_process()`

#### `test_cross_module_gil`
- **Сигнатура:** `test_cross_module_gil()`
- **Приватная:** нет
- **Описание:** Makes sure that the GIL can be acquired by another module from a GIL-released state.
- **Связи (вызовы):** test_cross_module_gil
- **Аргументы:**
  - нет аргументов
- **Пример(ы) из репозитория:**
  - `m.test_cross_module_gil()  # Should not raise a SIGSEGV` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_gil_scoped.py:85`)
  - `m.test_cross_module_gil()  # Should not raise a SIGSEGV` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/tests/test_gil_scoped.py:85`)


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.tests.test_iostream` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_iostream.py`)

### Функции

#### `test_captured`
- **Сигнатура:** `test_captured(capsys)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** captured_output, readouterr, captured_output_default, captured_err
- **Аргументы:**
  - `capsys`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `capsys`.
- **Пример:** `test_captured(...)`

#### `test_captured_large_string`
- **Сигнатура:** `test_captured_large_string(capsys)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** captured_output_default, readouterr, len
- **Аргументы:**
  - `capsys`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `capsys`.
- **Пример:** `test_captured_large_string(...)`

#### `test_guard_capture`
- **Сигнатура:** `test_guard_capture(capsys)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** guard_output, readouterr
- **Аргументы:**
  - `capsys`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `capsys`.
- **Пример:** `test_guard_capture(...)`

#### `test_series_captured`
- **Сигнатура:** `test_series_captured(capture)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** captured_output
- **Аргументы:**
  - `capture`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `capture`.
- **Пример:** `test_series_captured(...)`

#### `test_flush`
- **Сигнатура:** `test_flush(capfd)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** readouterr, ostream_redirect, noisy_function
- **Аргументы:**
  - `capfd`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `capfd`.
- **Пример:** `test_flush(...)`

#### `test_not_captured`
- **Сигнатура:** `test_not_captured(capfd)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** StringIO, readouterr, redirect_stdout, raw_output, getvalue, captured_output
- **Аргументы:**
  - `capfd`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `capfd`.
- **Пример:** `test_not_captured(...)`

#### `test_err`
- **Сигнатура:** `test_err(capfd)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** StringIO, readouterr, redirect_stderr, raw_err, getvalue, captured_err
- **Аргументы:**
  - `capfd`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `capfd`.
- **Пример:** `test_err(...)`

#### `test_multi_captured`
- **Сигнатура:** `test_multi_captured(capfd)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** StringIO, readouterr, redirect_stdout, captured_output, raw_output, getvalue
- **Аргументы:**
  - `capfd`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `capfd`.
- **Пример:** `test_multi_captured(...)`

#### `test_dual`
- **Сигнатура:** `test_dual(capsys)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** captured_dual, readouterr
- **Аргументы:**
  - `capsys`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `capsys`.
- **Пример:** `test_dual(...)`

#### `test_redirect`
- **Сигнатура:** `test_redirect(capfd)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** StringIO, readouterr, redirect_stdout, raw_output, getvalue, ostream_redirect
- **Аргументы:**
  - `capfd`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `capfd`.
- **Пример:** `test_redirect(...)`

#### `test_redirect_err`
- **Сигнатура:** `test_redirect_err(capfd)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** StringIO, readouterr, redirect_stderr, getvalue, ostream_redirect, raw_output
- **Аргументы:**
  - `capfd`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `capfd`.
- **Пример:** `test_redirect_err(...)`

#### `test_redirect_both`
- **Сигнатура:** `test_redirect_both(capfd)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** StringIO, readouterr, redirect_stdout, getvalue, redirect_stderr, ostream_redirect
- **Аргументы:**
  - `capfd`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `capfd`.
- **Пример:** `test_redirect_both(...)`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.tests.test_kwargs_and_defaults` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_kwargs_and_defaults.py`)

### Функции

#### `test_function_signatures`
- **Сигнатура:** `test_function_signatures(doc)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** doc
- **Аргументы:**
  - `doc`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `doc`.
- **Пример:** `test_function_signatures(...)`

#### `test_named_arguments`
- **Сигнатура:** `test_named_arguments(msg)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** match, kw_func0, kw_func1, kw_func2, raises, kw_func4
- **Аргументы:**
  - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
- **Пример:** `test_named_arguments(...)`

#### `test_arg_and_kwargs`
- **Сигнатура:** `test_arg_and_kwargs()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** dict, args_function, args_kwargs_function
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_arg_and_kwargs()`

#### `test_mixed_args_and_kwargs`
- **Сигнатура:** `test_mixed_args_and_kwargs(msg)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** mpa, raises, msg, mpk, mpak, mpakd
- **Аргументы:**
  - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
- **Пример:** `test_mixed_args_and_kwargs(...)`

#### `test_args_refcount`
- **Сигнатура:** `test_args_refcount()`
- **Приватная:** нет
- **Описание:** Issue/PR #1216 - py::args elements get double-inc_ref()ed when combined with regular
- **Связи (вызовы):** refcount, arg_refcount_h, arg_refcount_o, mixed_plus_args, mixed_plus_kwargs, args_function
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_args_refcount()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.tests.test_local_bindings` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_local_bindings.py`)

### Функции

#### `test_load_external`
- **Сигнатура:** `test_load_external()`
- **Приватная:** нет
- **Описание:** Load a `py::module_local` type that's only registered in an external module
- **Связи (вызовы):** load_external1, load_external2, raises, str, ExternalType1, ExternalType2
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_load_external()`

#### `test_local_bindings`
- **Сигнатура:** `test_local_bindings()`
- **Приватная:** нет
- **Описание:** Tests that duplicate `py::module_local` class bindings work across modules
- **Связи (вызовы):** LocalType, get, get3, get2, hasattr, local_value
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_local_bindings()`

#### `test_nonlocal_failure`
- **Сигнатура:** `test_nonlocal_failure()`
- **Приватная:** нет
- **Описание:** Tests that attempting to register a non-local type in multiple modules fails
- **Связи (вызовы):** raises, register_nonlocal, str
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_nonlocal_failure()`

#### `test_duplicate_local`
- **Сигнатура:** `test_duplicate_local()`
- **Приватная:** нет
- **Описание:** Tests expected failure when registering a class twice with py::local in the same module
- **Связи (вызовы):** raises, register_local_external, str, hasattr
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_duplicate_local()`

#### `test_stl_bind_local`
- **Сигнатура:** `test_stl_bind_local()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** append, LocalVec, LocalType, NonLocalVec, NonLocalVec2, NonLocalType
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_stl_bind_local()`

#### `test_stl_bind_global`
- **Сигнатура:** `test_stl_bind_global()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** raises, register_nonlocal_map, str, register_nonlocal_vec, register_nonlocal_map2
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_stl_bind_global()`

#### `test_mixed_local_global`
- **Сигнатура:** `test_mixed_local_global()`
- **Приватная:** нет
- **Описание:** Local types take precedence over globally registered types: a module with a `module_local`
- **Связи (вызовы):** register_mixed_global, register_mixed_local, append, register_mixed_global_local, register_mixed_local_global, MixedGlobalLocal
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_mixed_local_global()`

#### `test_internal_locals_differ`
- **Сигнатура:** `test_internal_locals_differ()`
- **Приватная:** нет
- **Описание:** Makes sure the internal local type map differs across the two modules
- **Связи (вызовы):** local_cpp_types_addr
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_internal_locals_differ()`

#### `test_stl_caster_vs_stl_bind`
- **Сигнатура:** `test_stl_caster_vs_stl_bind(msg)`
- **Приватная:** нет
- **Описание:** One module uses a generic vector caster from `<pybind11/stl.h>` while the other
- **Связи (вызовы):** VectorInt, load_vector_via_caster, load_vector_via_binding, raises, msg
- **Аргументы:**
  - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
- **Пример:** `test_stl_caster_vs_stl_bind(...)`

#### `test_cross_module_calls`
- **Сигнатура:** `test_cross_module_calls()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** LocalVec, append, Cat, Dog, MixGL, LocalType
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_cross_module_calls()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.tests.test_methods_and_attributes` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_methods_and_attributes.py`)

### Функции

#### `test_methods_and_attributes`
- **Сигнатура:** `test_methods_and_attributes()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** ExampleMandA, add1, add2, add3, add4, add5
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_methods_and_attributes()`

#### `test_copy_method`
- **Сигнатура:** `test_copy_method()`
- **Приватная:** нет
- **Описание:** Issue #443: calling copied methods fails in Python 3
- **Связи (вызовы):** ExampleMandA, add2, add2b, add2c, add2d
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_copy_method()`

#### `test_properties`
- **Сигнатура:** `test_properties()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** TestProperties, raises, str
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_properties()`

#### `test_static_properties`
- **Сигнатура:** `test_static_properties()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** TestProperties, raises, str, TestPropertiesOverride
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_static_properties()`

#### `test_static_cls`
- **Сигнатура:** `test_static_cls()`
- **Приватная:** нет
- **Описание:** Static property getter and setters expect the type object as the their only argument
- **Связи (вызовы):** TestProperties
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_static_cls()`

#### `test_metaclass_override`
- **Сигнатура:** `test_metaclass_override()`
- **Приватная:** нет
- **Описание:** Overriding pybind11's default metaclass changes the behavior of `static_property`
- **Связи (вызовы):** isinstance, type
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_metaclass_override()`

#### `test_no_mixed_overloads`
- **Сигнатура:** `test_no_mixed_overloads()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** raises, add_mixed_overloads1, str, add_mixed_overloads2
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_no_mixed_overloads()`

#### `test_property_return_value_policies`
- **Сигнатура:** `test_property_return_value_policies(access)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** parametrize, getattr, startswith, TestPropRVP
- **Аргументы:**
  - `access`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `access`.
- **Пример:** `test_property_return_value_policies(...)`

#### `test_property_rvalue_policy`
- **Сигнатура:** `test_property_rvalue_policy()`
- **Приватная:** нет
- **Описание:** When returning an rvalue, the return value policy is automatically changed from
- **Связи (вызовы):** TestPropRVP
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_property_rvalue_policy()`

#### `test_dynamic_attributes`
- **Сигнатура:** `test_dynamic_attributes()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** DynamicClass, hasattr, get, dir, raises, str
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_dynamic_attributes()`

#### `test_cyclic_gc`
- **Сигнатура:** `test_cyclic_gc()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** DynamicClass, get, alive
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_cyclic_gc()`

#### `test_noconvert_args`
- **Сигнатура:** `test_noconvert_args(msg)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** ArgInspector, msg, h, floats_preferred, floats_only, raises
- **Аргументы:**
  - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
- **Пример:** `test_noconvert_args(...)`

#### `test_bad_arg_default`
- **Сигнатура:** `test_bad_arg_default(msg)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** raises, bad_arg_def_named, msg, bad_arg_def_unnamed
- **Аргументы:**
  - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
- **Пример:** `test_bad_arg_default(...)`

#### `test_accepts_none`
- **Сигнатура:** `test_accepts_none(msg)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** NoneTester, no_none1, no_none2, no_none3, no_none4, no_none5
- **Аргументы:**
  - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
- **Пример:** `test_accepts_none(...)`

#### `test_str_issue`
- **Сигнатура:** `test_str_issue(msg)`
- **Приватная:** нет
- **Описание:** #283: __str__ called on uninitialized instance when constructor arguments invalid
- **Связи (вызовы):** str, raises, msg, StrIssue
- **Аргументы:**
  - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
- **Пример:** `test_str_issue(...)`

#### `test_unregistered_base_implementations`
- **Сигнатура:** `test_unregistered_base_implementations()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** RegisteredDerived, do_nothing, increase_value, sum
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_unregistered_base_implementations()`

#### `test_custom_caster_destruction`
- **Сигнатура:** `test_custom_caster_destruction()`
- **Приватная:** нет
- **Описание:** Tests that returning a pointer to a type that gets converted with a custom type caster gets
- **Связи (вызовы):** destruction_tester_cstats, custom_caster_no_destroy, custom_caster_destroy, custom_caster_destroy_const, alive
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_custom_caster_destruction()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.tests.test_modules` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_modules.py`)

### Функции

#### `test_nested_modules`
- **Сигнатура:** `test_nested_modules()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** submodule_func
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_nested_modules()`

#### `test_reference_internal`
- **Сигнатура:** `test_reference_internal()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** B, A, str, get, alive, values
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_reference_internal()`

#### `test_importing`
- **Сигнатура:** `test_importing()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** str, OD
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_importing()`

#### `test_pydoc`
- **Сигнатура:** `test_pydoc()`
- **Приватная:** нет
- **Описание:** Pydoc needs to be able to provide help() for everything inside a pybind11 module
- **Связи (вызовы):** docmodule
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_pydoc()`

#### `test_duplicate_registration`
- **Сигнатура:** `test_duplicate_registration()`
- **Приватная:** нет
- **Описание:** Registering two things with the same name
- **Связи (вызовы):** duplicate_registration
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_duplicate_registration()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.tests.test_multiple_inheritance` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_multiple_inheritance.py`)

### Функции

#### `test_multiple_inheritance_cpp`
- **Сигнатура:** `test_multiple_inheritance_cpp()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** MIType, foo, bar
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_multiple_inheritance_cpp()`

#### `test_multiple_inheritance_mix1`
- **Сигнатура:** `test_multiple_inheritance_mix1()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** MITypePy, foo, bar, __init__
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_multiple_inheritance_mix1()`

#### `test_multiple_inheritance_mix2`
- **Сигнатура:** `test_multiple_inheritance_mix2()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** MITypePy, foo, bar, __init__
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_multiple_inheritance_mix2()`

#### `test_multiple_inheritance_python`
- **Сигнатура:** `test_multiple_inheritance_python()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** MI1, MI2, MI3, MI4, MI5, MI6
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_multiple_inheritance_python()`

#### `test_multiple_inheritance_python_many_bases`
- **Сигнатура:** `test_multiple_inheritance_python_many_bases()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** MIMany14, range, MIMany916, MIMany19, MIMany117, __init__
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_multiple_inheritance_python_many_bases()`

#### `test_multiple_inheritance_virtbase`
- **Сигнатура:** `test_multiple_inheritance_virtbase()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** MITypePy, bar, bar_base2a, bar_base2a_sharedptr, __init__
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_multiple_inheritance_virtbase()`

#### `test_mi_static_properties`
- **Сигнатура:** `test_mi_static_properties()`
- **Приватная:** нет
- **Описание:** Mixing bases with and without static properties should be possible
- **Связи (вызовы):** VanillaStaticMix1, VanillaStaticMix2, vanilla, static_func1, static_func2, static_func
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_mi_static_properties()`

#### `test_mi_dynamic_attributes`
- **Сигнатура:** `test_mi_dynamic_attributes()`
- **Приватная:** нет
- **Описание:** Mixing bases with and without dynamic attribute support
- **Связи (вызовы):** VanillaDictMix1, VanillaDictMix2
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_mi_dynamic_attributes()`

#### `test_mi_unaligned_base`
- **Сигнатура:** `test_mi_unaligned_base()`
- **Приватная:** нет
- **Описание:** Returning an offset (non-first MI) base class pointer should recognize the instance
- **Связи (вызовы):** detail_reg_inst, I801C, I801D, i801b1_c, i801b2_c, i801b1_d
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_mi_unaligned_base()`

#### `test_mi_base_return`
- **Сигнатура:** `test_mi_base_return()`
- **Приватная:** нет
- **Описание:** Tests returning an offset (non-first MI) base class pointer to a derived instance
- **Связи (вызовы):** detail_reg_inst, i801c_b1, i801d_b1, i801c_b2, i801d_b2, i801e_c
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_mi_base_return()`

#### `test_diamond_inheritance`
- **Сигнатура:** `test_diamond_inheritance()`
- **Приватная:** нет
- **Описание:** Tests that diamond inheritance works as expected (issue #959)
- **Связи (вызовы):** D, c0, c1, b
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_diamond_inheritance()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.tests.test_numpy_array` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_numpy_array.py`)

### Функции

#### `test_dtypes`
- **Сигнатура:** `test_dtypes()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** get_platform_dtype_size_checks, get_concrete_dtype_checks, print, format
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_dtypes()`

#### `arr`
- **Сигнатура:** `arr()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** fixture, array
- **Аргументы:**
  - нет аргументов
- **Пример:** `arr()`

#### `test_array_attributes`
- **Сигнатура:** `test_array_attributes()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** array, all, writeable, owndata, view, ndim
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_array_attributes()`

#### `test_index_offset`
- **Сигнатура:** `test_index_offset(arr, args, ret)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** parametrize, index_at, index_at_t, offset_at, offset_at_t
- **Аргументы:**
  - `arr`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `arr`.
  - `args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `args`.
  - `ret`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `ret`.
- **Пример:** `test_index_offset(..., ..., ...)`

#### `test_dim_check_fail`
- **Сигнатура:** `test_dim_check_fail(arr)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** raises, func, str
- **Аргументы:**
  - `arr`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `arr`.
- **Пример:** `test_dim_check_fail(...)`

#### `test_data`
- **Сигнатура:** `test_data(arr, args, ret)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** parametrize, all, data_t, data
- **Аргументы:**
  - `arr`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `arr`.
  - `args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `args`.
  - `ret`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `ret`.
- **Пример:** `test_data(..., ..., ...)`

#### `test_at_fail`
- **Сигнатура:** `test_at_fail(arr, dim)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** parametrize, raises, func, str, format
- **Аргументы:**
  - `arr`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `arr`.
  - `dim`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `dim`.
- **Пример:** `test_at_fail(..., ...)`

#### `test_at`
- **Сигнатура:** `test_at(arr)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** all, at_t, ravel, mutate_at_t
- **Аргументы:**
  - `arr`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `arr`.
- **Пример:** `test_at(...)`

#### `test_mutate_readonly`
- **Сигнатура:** `test_mutate_readonly(arr)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** raises, func, str
- **Аргументы:**
  - `arr`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `arr`.
- **Пример:** `test_mutate_readonly(...)`

#### `test_mutate_data`
- **Сигнатура:** `test_mutate_data(arr)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** all, ravel, mutate_data, mutate_data_t
- **Аргументы:**
  - `arr`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `arr`.
- **Пример:** `test_mutate_data(...)`

#### `test_bounds_check`
- **Сигнатура:** `test_bounds_check(arr)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** raises, func, str
- **Аргументы:**
  - `arr`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `arr`.
- **Пример:** `test_bounds_check(...)`

#### `test_make_c_f_array`
- **Сигнатура:** `test_make_c_f_array()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** make_c_array, make_f_array
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_make_c_f_array()`

#### `test_make_empty_shaped_array`
- **Сигнатура:** `test_make_empty_shaped_array()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** make_empty_shaped_array, scalar_int
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_make_empty_shaped_array()`

#### `test_wrap`
- **Сигнатура:** `test_wrap()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** array, wrap, assert_references, random, transpose, diagonal
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_wrap()`

#### `test_numpy_view`
- **Сигнатура:** `test_numpy_view(capture)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** ArrayClass, numpy_view, all, gc_collect, array
- **Аргументы:**
  - `capture`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `capture`.
- **Пример:** `test_numpy_view(...)`

#### `test_cast_numpy_int64_to_uint64`
- **Сигнатура:** `test_cast_numpy_int64_to_uint64()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** function_taking_uint64, uint64
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_cast_numpy_int64_to_uint64()`

#### `test_isinstance`
- **Сигнатура:** `test_isinstance()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** isinstance_untyped, isinstance_typed, array
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_isinstance()`

#### `test_constructors`
- **Сигнатура:** `test_constructors()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** default_constructors, values, converting_constructors, assert_array_equal, array
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_constructors()`

#### `test_overload_resolution`
- **Сигнатура:** `test_overload_resolution(msg)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** overloaded, raises, msg, overloaded2, overloaded3, overloaded4
- **Аргументы:**
  - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
- **Пример:** `test_overload_resolution(...)`

#### `test_greedy_string_overload`
- **Сигнатура:** `test_greedy_string_overload()`
- **Приватная:** нет
- **Описание:** Tests fix for #685 - ndarray shouldn't go to std::string overload
- **Связи (вызовы):** issue685, array
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_greedy_string_overload()`

#### `test_array_unchecked_fixed_dims`
- **Сигнатура:** `test_array_unchecked_fixed_dims(msg)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** array, proxy_add2, all, ndarray, transpose, raises
- **Аргументы:**
  - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
- **Пример:** `test_array_unchecked_fixed_dims(...)`

#### `test_array_unchecked_dyn_dims`
- **Сигнатура:** `test_array_unchecked_dyn_dims(msg)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** array, proxy_add2_dyn, all, ndarray, proxy_auxiliaries2_dyn, array_auxiliaries2
- **Аргументы:**
  - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
- **Пример:** `test_array_unchecked_dyn_dims(...)`

#### `test_array_failure`
- **Сигнатура:** `test_array_failure()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** raises, array_fail_test, str, array_t_fail_test, array_fail_test_negative_size
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_array_failure()`

#### `test_initializer_list`
- **Сигнатура:** `test_initializer_list()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** array_initializer_list1, array_initializer_list2, array_initializer_list3, array_initializer_list4
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_initializer_list()`

#### `test_array_resize`
- **Сигнатура:** `test_array_resize(msg)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** array, array_reshape2, all, array_resize3, transpose, startswith
- **Аргументы:**
  - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
- **Пример:** `test_array_resize(...)`

#### `test_array_create_and_resize`
- **Сигнатура:** `test_array_create_and_resize(msg)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** create_and_resize, all
- **Аргументы:**
  - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
- **Пример:** `test_array_create_and_resize(...)`

#### `test_index_using_ellipsis`
- **Сигнатура:** `test_index_using_ellipsis()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** index_using_ellipsis, zeros
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_index_using_ellipsis()`

#### `test_dtype_refcount_leak`
- **Сигнатура:** `test_dtype_refcount_leak()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** dtype, array, getrefcount, ndim
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_dtype_refcount_leak()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.tests.test_numpy_dtypes` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_numpy_dtypes.py`)

### Функции

#### `simple_dtype`
- **Сигнатура:** `simple_dtype()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** fixture, dtype, format
- **Аргументы:**
  - нет аргументов
- **Пример:** `simple_dtype()`

#### `packed_dtype`
- **Сигнатура:** `packed_dtype()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** fixture, dtype
- **Аргументы:**
  - нет аргументов
- **Пример:** `packed_dtype()`

#### `dt_fmt`
- **Сигнатура:** `dt_fmt()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** не выявлены
- **Аргументы:**
  - нет аргументов
- **Пример:** `dt_fmt()`

#### `simple_dtype_fmt`
- **Сигнатура:** `simple_dtype_fmt()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** dtype, format, dt_fmt
- **Аргументы:**
  - нет аргументов
- **Пример:** `simple_dtype_fmt()`

#### `packed_dtype_fmt`
- **Сигнатура:** `packed_dtype_fmt()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** format, dtype
- **Аргументы:**
  - нет аргументов
- **Пример:** `packed_dtype_fmt()`

#### `partial_ld_offset`
- **Сигнатура:** `partial_ld_offset()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** dtype
- **Аргументы:**
  - нет аргументов
- **Пример:** `partial_ld_offset()`

#### `partial_dtype_fmt`
- **Сигнатура:** `partial_dtype_fmt()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** dtype, partial_ld_offset, format, dt_fmt
- **Аргументы:**
  - нет аргументов
- **Пример:** `partial_dtype_fmt()`

#### `partial_nested_fmt`
- **Сигнатура:** `partial_nested_fmt()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** dtype, partial_ld_offset, format, partial_dtype_fmt
- **Аргументы:**
  - нет аргументов
- **Пример:** `partial_nested_fmt()`

#### `assert_equal`
- **Сигнатура:** `assert_equal(actual, expected_data, expected_dtype)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** assert_equal, array
- **Аргументы:**
  - `actual`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `actual`.
  - `expected_data`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `expected_data`.
  - `expected_dtype`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `expected_dtype`.
- **Пример(ы) из репозитория:**
  - `np.testing.assert_equal(actual, np.array(expected_data, dtype=expected_dtype))` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_numpy_dtypes.py:65`)
  - `np.testing.assert_equal(arr['a'], m.create_rec_partial(3))` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_numpy_dtypes.py:182`)

#### `test_format_descriptors`
- **Сигнатура:** `test_format_descriptors()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** match, dtype, str, raises, get_format_unbound, max
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_format_descriptors()`

#### `test_dtype`
- **Сигнатура:** `test_dtype(simple_dtype)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** dtype, print_dtypes, test_dtype_ctors, test_dtype_methods, trailing_padding_dtype, buffer_to_dtype
- **Аргументы:**
  - `simple_dtype`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `simple_dtype`.
- **Пример:** `test_dtype(...)`

#### `test_recarray`
- **Сигнатура:** `test_recarray(simple_dtype, packed_dtype)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** dtype, create_rec_nested, assert_equal, create_rec_partial, create_rec_partial_nested, func
- **Аргументы:**
  - `simple_dtype`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `simple_dtype`.
  - `packed_dtype`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `packed_dtype`.
- **Пример:** `test_recarray(..., ...)`

#### `test_array_constructors`
- **Сигнатура:** `test_array_constructors()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** arange, range, assert_array_equal, test_array_ctors, reshape
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_array_constructors()`

#### `test_string_array`
- **Сигнатура:** `test_string_array()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** create_string_array, str, print_string_array, tolist
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_string_array()`

#### `test_array_array`
- **Сигнатура:** `test_array_array()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** create_array_array, str, format, print_array_array, tolist
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_array_array()`

#### `test_enum_array`
- **Сигнатура:** `test_enum_array()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** create_enum_array, dtype, print_enum_array, tolist
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_enum_array()`

#### `test_complex_array`
- **Сигнатура:** `test_complex_array()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** create_complex_array, dtype, print_complex_array, tolist
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_complex_array()`

#### `test_signature`
- **Сигнатура:** `test_signature(doc)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** doc
- **Аргументы:**
  - `doc`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `doc`.
- **Пример:** `test_signature(...)`

#### `test_scalar_conversion`
- **Сигнатура:** `test_scalar_conversion()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** enumerate, create_rec_simple, create_rec_packed, create_rec_nested, create_enum_array, raises
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_scalar_conversion()`

#### `test_register_dtype`
- **Сигнатура:** `test_register_dtype()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** raises, register_dtype, str
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_register_dtype()`

#### `test_str_leak`
- **Сигнатура:** `test_str_leak()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** gc_collect, getrefcount, dtype_wrapper, dtype
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_str_leak()`

#### `test_compare_buffer_info`
- **Сигнатура:** `test_compare_buffer_info()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** all, compare_buffer_info
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_compare_buffer_info()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.tests.test_numpy_vectorize` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_numpy_vectorize.py`)

### Функции

#### `test_vectorize`
- **Сигнатура:** `test_vectorize(capture)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** isclose, vectorized_func3, array, allclose, f
- **Аргументы:**
  - `capture`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `capture`.
- **Пример:** `test_vectorize(...)`

#### `test_type_selection`
- **Сигнатура:** `test_type_selection()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** selective_func, array
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_type_selection()`

#### `test_docs`
- **Сигнатура:** `test_docs(doc)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** doc
- **Аргументы:**
  - `doc`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `doc`.
- **Пример:** `test_docs(...)`

#### `test_trivial_broadcasting`
- **Сигнатура:** `test_trivial_broadcasting()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** array, vectorized_is_trivial, vectorized_func
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_trivial_broadcasting()`

#### `test_passthrough_arguments`
- **Сигнатура:** `test_passthrough_arguments(doc)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** array, all, doc, vec_passthrough, join, NonPODClass
- **Аргументы:**
  - `doc`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `doc`.
- **Пример:** `test_passthrough_arguments(...)`

#### `test_method_vectorization`
- **Сигнатура:** `test_method_vectorization()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** VectorizeTestClass, array, all, method
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_method_vectorization()`

#### `test_array_collapse`
- **Сигнатура:** `test_array_collapse()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** vectorized_func, isinstance, array
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_array_collapse()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.tests.test_opaque_types` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_opaque_types.py`)

### Функции

#### `test_string_list`
- **Сигнатура:** `test_string_list()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** StringList, push_back, enumerate, pop_back, ClassWithSTLVecProperty, print_opaque_list
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_string_list()`

#### `test_pointers`
- **Сигнатура:** `test_pointers(msg)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** alive, get_void_ptr_value, return_unique_ptr, UserType, raises, msg
- **Аргументы:**
  - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
- **Пример:** `test_pointers(...)`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.tests.test_operator_overloading` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_operator_overloading.py`)

### Функции

#### `test_operator_overloading`
- **Сигнатура:** `test_operator_overloading()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** Vector2, Vector, get, str, hash, alive
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_operator_overloading()`

#### `test_operators_notimplemented`
- **Сигнатура:** `test_operators_notimplemented()`
- **Приватная:** нет
- **Описание:** #393: need to return NotSupported to ensure correct arithmetic operator behavior
- **Связи (вызовы):** C1, C2
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_operators_notimplemented()`

#### `test_nested`
- **Сигнатура:** `test_nested()`
- **Приватная:** нет
- **Описание:** #328: first member in a class can't be used in operators
- **Связи (вызовы):** NestA, NestB, NestC, as_base, gc_collect, get_NestA
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_nested()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.tests.test_pickling` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_pickling.py`)

### Функции

#### `test_roundtrip`
- **Сигнатура:** `test_roundtrip(cls_name)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** parametrize, getattr, cls, setExtra1, setExtra2, dumps
- **Аргументы:**
  - `cls_name`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `cls_name`.
- **Пример:** `test_roundtrip(...)`

#### `test_roundtrip_with_dict`
- **Сигнатура:** `test_roundtrip_with_dict(cls_name)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** parametrize, getattr, cls, dumps, loads
- **Аргументы:**
  - `cls_name`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `cls_name`.
- **Пример:** `test_roundtrip_with_dict(...)`

#### `test_enum_pickle`
- **Сигнатура:** `test_enum_pickle()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** dumps, loads
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_enum_pickle()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.tests.test_pytypes` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_pytypes.py`)

### Функции

#### `test_list`
- **Сигнатура:** `test_list(capture, doc)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** get_list, append, print_list, doc
- **Аргументы:**
  - `capture`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `capture`.
  - `doc`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `doc`.
- **Пример:** `test_list(..., ...)`

#### `test_set`
- **Сигнатура:** `test_set(capture, doc)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** get_set, set_contains, add, print_set, doc, set
- **Аргументы:**
  - `capture`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `capture`.
  - `doc`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `doc`.
- **Пример:** `test_set(..., ...)`

#### `test_dict`
- **Сигнатура:** `test_dict(capture, doc)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** get_dict, dict_contains, print_dict, doc, dict_keyword_constructor
- **Аргументы:**
  - `capture`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `capture`.
  - `doc`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `doc`.
- **Пример:** `test_dict(..., ...)`

#### `test_str`
- **Сигнатура:** `test_str(doc)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** str_format, decode, doc, str_from_object, repr_from_object, A
- **Аргументы:**
  - `doc`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `doc`.
- **Пример:** `test_str(...)`

#### `test_bytes`
- **Сигнатура:** `test_bytes(doc)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** decode, doc, format, bytes_from_string, bytes_from_str
- **Аргументы:**
  - `doc`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `doc`.
- **Пример:** `test_bytes(...)`

#### `test_capsule`
- **Сигнатура:** `test_capsule(capture)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** gc_collect, return_capsule_with_destructor, return_capsule_with_destructor_2, return_capsule_with_name_and_destructor
- **Аргументы:**
  - `capture`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `capture`.
- **Пример:** `test_capsule(...)`

#### `test_accessors`
- **Сигнатура:** `test_accessors()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** accessor_api, all, accessor_assignment, SubTestObject, TestObject, tuple_accessor
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_accessors()`

#### `test_constructors`
- **Сигнатура:** `test_constructors()`
- **Приватная:** нет
- **Описание:** C++ default and converting constructors are equivalent to type calls in Python
- **Связи (вызовы):** converting_constructors, cast_functions, t, default_constructors, range, k
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_constructors()`

#### `test_implicit_casting`
- **Сигнатура:** `test_implicit_casting()`
- **Приватная:** нет
- **Описание:** Tests implicit casting when assigning or appending to dicts and lists.
- **Связи (вызовы):** get_implicit_casting
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_implicit_casting()`

#### `test_print`
- **Сигнатура:** `test_print(capture)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** print_function, raises, print_failure, str
- **Аргументы:**
  - `capture`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `capture`.
- **Пример:** `test_print(...)`

#### `test_hash`
- **Сигнатура:** `test_hash()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** hash_function, raises, Hashable, Unhashable
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_hash()`

#### `test_number_protocol`
- **Сигнатура:** `test_number_protocol()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** test_number_protocol
- **Аргументы:**
  - нет аргументов
- **Пример(ы) из репозитория:**
  - `assert m.test_number_protocol(a, b) == li` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_pytypes.py:258`)
  - `assert m.test_number_protocol(a, b) == li` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/tests/test_pytypes.py:258`)

#### `test_list_slicing`
- **Сигнатура:** `test_list_slicing()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** list, range, test_list_slicing
- **Аргументы:**
  - нет аргументов
- **Пример(ы) из репозитория:**
  - `assert li[::2] == m.test_list_slicing(li)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_pytypes.py:263`)
  - `assert li[::2] == m.test_list_slicing(li)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/tests/test_pytypes.py:263`)


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.tests.test_sequences_and_iterators` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_sequences_and_iterators.py`)

### Функции

#### `isclose`
- **Сигнатура:** `isclose(a, b, rel_tol=1e-05, abs_tol=0.0)`
- **Приватная:** нет
- **Описание:** Like math.isclose() from Python 3.5
- **Связи (вызовы):** abs, max
- **Аргументы:**
  - `a`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `a`.
  - `b`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `b`.
  - `rel_tol`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `rel_tol`.
  - `abs_tol`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `abs_tol`.
- **Пример(ы) из репозитория:**
  - `assert np.isclose(m.vectorized_func3(np.array(3 + 7j)), [6 + 14j])` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_numpy_vectorize.py:11`)
  - `assert np.isclose(f(1, 2, 3), 6)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_numpy_vectorize.py:15`)

#### `allclose`
- **Сигнатура:** `allclose(a_list, b_list, rel_tol=1e-05, abs_tol=0.0)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** all, isclose, zip
- **Аргументы:**
  - `a_list`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `a_list`.
  - `b_list`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `b_list`.
  - `rel_tol`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `rel_tol`.
  - `abs_tol`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `abs_tol`.
- **Пример(ы) из репозитория:**
  - `assert np.allclose(f(np.array([1, 3]), np.array([2, 4]), 3), [6, 36])` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_numpy_vectorize.py:21`)
  - `assert np.allclose(result, a * b * c)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_numpy_vectorize.py:31`)

#### `test_generalized_iterators`
- **Сигнатура:** `test_generalized_iterators()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** nonzero, range, nonzero_keys, list, IntPairs, raises
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_generalized_iterators()`

#### `test_sliceable`
- **Сигнатура:** `test_sliceable()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** Sliceable
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_sliceable()`

#### `test_sequence`
- **Сигнатура:** `test_sequence()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** get, Sequence, reversed, iter, range, allclose
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_sequence()`

#### `test_map_iterator`
- **Сигнатура:** `test_map_iterator()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** StringMap, items, iter, range, len, raises
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_map_iterator()`

#### `test_python_iterator_in_cpp`
- **Сигнатура:** `test_python_iterator_in_cpp()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** range, all, object_to_list, iterator_to_list, raises, str
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_python_iterator_in_cpp()`

#### `test_iterator_passthrough`
- **Сигнатура:** `test_iterator_passthrough()`
- **Приватная:** нет
- **Описание:** #181: iterator passthrough did not compile
- **Связи (вызовы):** list, iterator_passthrough, iter
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_iterator_passthrough()`

#### `test_iterator_rvp`
- **Сигнатура:** `test_iterator_rvp()`
- **Приватная:** нет
- **Описание:** #388: Can't make iterators via make_iterator() with different r/v policies
- **Связи (вызовы):** list, isinstance, make_iterator_1, make_iterator_2, type
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_iterator_rvp()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.tests.test_smart_ptr` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_smart_ptr.py`)

### Функции

#### `test_smart_ptr`
- **Сигнатура:** `test_smart_ptr(capture)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** enumerate, get, zip, cstats_ref, print, alive
- **Аргументы:**
  - `capture`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `capture`.
- **Пример:** `test_smart_ptr(...)`

#### `test_smart_ptr_refcounting`
- **Сигнатура:** `test_smart_ptr_refcounting()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** test_object1_refcounting
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_smart_ptr_refcounting()`

#### `test_unique_nodelete`
- **Сигнатура:** `test_unique_nodelete()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** MyObject4, get, alive
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_unique_nodelete()`

#### `test_unique_nodelete4a`
- **Сигнатура:** `test_unique_nodelete4a()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** MyObject4a, get, alive
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_unique_nodelete4a()`

#### `test_unique_deleter`
- **Сигнатура:** `test_unique_deleter()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** MyObject4b, get, alive
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_unique_deleter()`

#### `test_large_holder`
- **Сигнатура:** `test_large_holder()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** MyObject5, get, alive
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_large_holder()`

#### `test_shared_ptr_and_references`
- **Сигнатура:** `test_shared_ptr_and_references()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** SharedPtrRef, get, set_ref, set_holder, alive, raises
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_shared_ptr_and_references()`

#### `test_shared_ptr_from_this_and_references`
- **Сигнатура:** `test_shared_ptr_from_this_and_references()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** SharedFromThisRef, get, set_ref, set_holder, alive, raises
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_shared_ptr_from_this_and_references()`

#### `test_move_only_holder`
- **Сигнатура:** `test_move_only_holder()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** make, get, alive
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_move_only_holder()`

#### `test_holder_with_addressof_operator`
- **Сигнатура:** `test_holder_with_addressof_operator()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** make, print_object_1, print_object_2, print_object_3, print_object_4, get
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_holder_with_addressof_operator()`

#### `test_move_only_holder_with_addressof_operator`
- **Сигнатура:** `test_move_only_holder_with_addressof_operator()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** make, print_object, get, alive
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_move_only_holder_with_addressof_operator()`

#### `test_smart_ptr_from_default`
- **Сигнатура:** `test_smart_ptr_from_default()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** HeldByDefaultHolder, raises, load_shared_ptr, str
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_smart_ptr_from_default()`

#### `test_shared_ptr_gc`
- **Сигнатура:** `test_shared_ptr_gc()`
- **Приватная:** нет
- **Описание:** #187: issue involving std::shared_ptr<> return value policy & garbage collection
- **Связи (вызовы):** ElementList, range, gc_collect, enumerate, add, get
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_shared_ptr_gc()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.tests.test_stl` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_stl.py`)

### Функции

#### `test_vector`
- **Сигнатура:** `test_vector(doc)`
- **Приватная:** нет
- **Описание:** std::vector <-> list
- **Связи (вызовы):** cast_vector, append, load_vector, load_bool_vector, tuple, cast_bool_vector
- **Аргументы:**
  - `doc`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `doc`.
- **Пример:** `test_vector(...)`

#### `test_deque`
- **Сигнатура:** `test_deque(doc)`
- **Приватная:** нет
- **Описание:** std::deque <-> list
- **Связи (вызовы):** cast_deque, append, load_deque, tuple
- **Аргументы:**
  - `doc`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `doc`.
- **Пример:** `test_deque(...)`

#### `test_array`
- **Сигнатура:** `test_array(doc)`
- **Приватная:** нет
- **Описание:** std::array <-> list
- **Связи (вызовы):** cast_array, load_array, doc
- **Аргументы:**
  - `doc`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `doc`.
- **Пример:** `test_array(...)`

#### `test_valarray`
- **Сигнатура:** `test_valarray(doc)`
- **Приватная:** нет
- **Описание:** std::valarray <-> list
- **Связи (вызовы):** cast_valarray, load_valarray, doc
- **Аргументы:**
  - `doc`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `doc`.
- **Пример:** `test_valarray(...)`

#### `test_map`
- **Сигнатура:** `test_map(doc)`
- **Приватная:** нет
- **Описание:** std::map <-> dict
- **Связи (вызовы):** cast_map, load_map, doc
- **Аргументы:**
  - `doc`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `doc`.
- **Пример:** `test_map(...)`

#### `test_set`
- **Сигнатура:** `test_set(doc)`
- **Приватная:** нет
- **Описание:** std::set <-> set
- **Связи (вызовы):** cast_set, add, load_set, doc
- **Аргументы:**
  - `doc`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `doc`.
- **Пример:** `test_set(...)`

#### `test_recursive_casting`
- **Сигнатура:** `test_recursive_casting()`
- **Приватная:** нет
- **Описание:** Tests that stl casters preserve lvalue/rvalue context for container values
- **Связи (вызовы):** cast_unique_ptr_vector, cast_rv_vector, cast_lv_vector, cast_rv_array, cast_lv_array, cast_rv_map
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_recursive_casting()`

#### `test_move_out_container`
- **Сигнатура:** `test_move_out_container()`
- **Приватная:** нет
- **Описание:** Properties use the `reference_internal` policy by default. If the underlying function
- **Связи (вызовы):** MoveOutContainer
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_move_out_container()`

#### `test_optional`
- **Сигнатура:** `test_optional()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** skipif, raises, nodefer_none_optional, double_or_zero, half_or_none, test_nullopt
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_optional()`

#### `test_exp_optional`
- **Сигнатура:** `test_exp_optional()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** skipif, raises, double_or_zero_exp, half_or_none_exp, test_nullopt_exp, test_no_assign_exp
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_exp_optional()`

#### `test_variant`
- **Сигнатура:** `test_variant(doc)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** skipif, load_variant, load_variant_2pass, cast_variant, doc, hasattr
- **Аргументы:**
  - `doc`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `doc`.
- **Пример:** `test_variant(...)`

#### `test_vec_of_reference_wrapper`
- **Сигнатура:** `test_vec_of_reference_wrapper()`
- **Приватная:** нет
- **Описание:** #171: Can't return reference wrappers (or STL structures containing them)
- **Связи (вызовы):** str, return_vec_of_reference_wrapper, UserType
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_vec_of_reference_wrapper()`

#### `test_stl_pass_by_pointer`
- **Сигнатура:** `test_stl_pass_by_pointer(msg)`
- **Приватная:** нет
- **Описание:** Passing nullptr or None to an STL container pointer is not expected to work
- **Связи (вызовы):** raises, stl_pass_by_pointer, msg
- **Аргументы:**
  - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
- **Пример:** `test_stl_pass_by_pointer(...)`

#### `test_missing_header_message`
- **Сигнатура:** `test_missing_header_message()`
- **Приватная:** нет
- **Описание:** Trying convert `list` to a `std::vector`, or vice versa, without including
- **Связи (вызовы):** raises, missing_header_arg, str, missing_header_return
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_missing_header_message()`

#### `test_function_with_string_and_vector_string_arg`
- **Сигнатура:** `test_function_with_string_and_vector_string_arg()`
- **Приватная:** нет
- **Описание:** Check if a string is NOT implicitly converted to a list, which was the
- **Связи (вызовы):** func_with_string_or_vector_string_arg_overload
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_function_with_string_and_vector_string_arg()`

#### `test_stl_ownership`
- **Сигнатура:** `test_stl_ownership()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** get, test_stl_ownership, alive, len
- **Аргументы:**
  - нет аргументов
- **Пример(ы) из репозитория:**
  - `r = m.test_stl_ownership()` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_stl.py:226`)
  - `r = m.test_stl_ownership()` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/tests/test_stl.py:226`)

#### `test_array_cast_sequence`
- **Сигнатура:** `test_array_cast_sequence()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** array_cast_sequence
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_array_cast_sequence()`

#### `test_issue_1561`
- **Сигнатура:** `test_issue_1561()`
- **Приватная:** нет
- **Описание:** check fix for issue #1561
- **Связи (вызовы):** Issue1561Outer, Issue1561Inner
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_issue_1561()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.tests.test_stl_binders` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_stl_binders.py`)

### Функции

#### `test_vector_int`
- **Сигнатура:** `test_vector_int()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** VectorInt, append, insert, extend, len, bool
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_vector_int()`

#### `test_vector_buffer`
- **Сигнатура:** `test_vector_buffer()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** bytearray, VectorUChar, memoryview, raises, create_undeclstruct, str
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_vector_buffer()`

#### `test_vector_buffer_numpy`
- **Сигнатура:** `test_vector_buffer_numpy()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** array, VectorInt, asarray, get_vectorstruct, VectorStruct, raises
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_vector_buffer_numpy()`

#### `test_vector_bool`
- **Сигнатура:** `test_vector_bool()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** VectorBool, range, append, str
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_vector_bool()`

#### `test_vector_custom`
- **Сигнатура:** `test_vector_custom()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** VectorEl, append, VectorVectorEl, El, str
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_vector_custom()`

#### `test_map_string_double`
- **Сигнатура:** `test_map_string_double()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** MapStringDouble, UnorderedMapStringDouble, list, str, sorted, items
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_map_string_double()`

#### `test_map_string_double_const`
- **Сигнатура:** `test_map_string_double_const()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** MapStringDoubleConst, UnorderedMapStringDoubleConst, str
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_map_string_double_const()`

#### `test_noncopyable_containers`
- **Сигнатура:** `test_noncopyable_containers()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** get_vnc, range, enumerate, get_dnc, get_mnc, items
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_noncopyable_containers()`

#### `test_map_delitem`
- **Сигнатура:** `test_map_delitem()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** MapStringDouble, UnorderedMapStringDouble, list, sorted, items
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_map_delitem()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.tests.test_tagbased_polymorphic` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_tagbased_polymorphic.py`)

### Функции

#### `test_downcast`
- **Сигнатура:** `test_downcast()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** create_zoo, type, bark, purr
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_downcast()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.tests.test_union` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_union.py`)

### Функции

#### `test_union`
- **Сигнатура:** `test_union()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** TestUnion
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_union()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.tests.test_virtual_functions` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_virtual_functions.py`)

### Функции

#### `test_override`
- **Сигнатура:** `test_override(capture, msg)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** ExampleVirt, ExtendedExampleVirt, ExtendedExampleVirt2, get, raises, runExampleVirtVirtual
- **Аргументы:**
  - `capture`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `capture`.
  - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
- **Пример:** `test_override(..., ...)`

#### `test_alias_delay_initialization1`
- **Сигнатура:** `test_alias_delay_initialization1(capture)`
- **Приватная:** нет
- **Описание:** `A` only initializes its trampoline class when we inherit from it
- **Связи (вызовы):** A, call_f, gc_collect, B, __init__, print
- **Аргументы:**
  - `capture`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `capture`.
- **Пример:** `test_alias_delay_initialization1(...)`

#### `test_alias_delay_initialization2`
- **Сигнатура:** `test_alias_delay_initialization2(capture)`
- **Приватная:** нет
- **Описание:** `A2`, unlike the above, is configured to always initialize the alias
- **Связи (вызовы):** A2, call_f, gc_collect, B2, __init__, print
- **Аргументы:**
  - `capture`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `capture`.
- **Пример:** `test_alias_delay_initialization2(...)`

#### `test_move_support`
- **Сигнатура:** `test_move_support()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** skipif, NCVirtExt, NCVirtExt2, get, print_nc, print_movable
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_move_support()`

#### `test_dispatch_issue`
- **Сигнатура:** `test_dispatch_issue(msg)`
- **Приватная:** нет
- **Описание:** #159: virtual function dispatch has problems with similar-named functions
- **Связи (вызовы):** PyClass2, dispatch_issue_go, PyClass1, raises, dispatch, msg
- **Аргументы:**
  - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
- **Пример:** `test_dispatch_issue(...)`

#### `test_override_ref`
- **Сигнатура:** `test_override_ref()`
- **Приватная:** нет
- **Описание:** #392/397: overriding reference-returning functions
- **Связи (вызовы):** OverrideTest, A_ref, str_value, A_value
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_override_ref()`

#### `test_inherited_virtuals`
- **Сигнатура:** `test_inherited_virtuals()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** AR, AT, CR, CT, CCR, CCT
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_inherited_virtuals()`

#### `test_issue_1454`
- **Сигнатура:** `test_issue_1454()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** test_gil, test_gil_from_thread
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_issue_1454()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.tools.libsize` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tools/libsize.py`)


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.src.pybind11.tools.mkdoc` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tools/mkdoc.py`)

### Функции

#### `d`
- **Сигнатура:** `d(s)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** isinstance, decode
- **Аргументы:**
  - `s`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `s`.
- **Пример:** `d(...)`

#### `sanitize_name`
- **Сигнатура:** `sanitize_name(name)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** sub, items, join, replace, isalnum
- **Аргументы:**
  - `name`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `name`.
- **Пример:** `sanitize_name(...)`

#### `process_comment`
- **Сигнатура:** `process_comment(comment)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** float, splitlines, sub, items, replace, TextWrapper
- **Аргументы:**
  - `comment`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `comment`.
- **Пример:** `process_comment(...)`

#### `extract`
- **Сигнатура:** `extract(filename, node, prefix, output)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** get_children, process_comment, samefile, d, extract, len
- **Аргументы:**
  - `filename`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `filename`.
  - `node`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `node`.
  - `prefix`: тип `не указан`; единицы `м`; допустимые значения `0..255`; параметр `prefix`.
  - `output`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `output`.
- **Пример:** `extract(..., ..., ..., ...)`

#### `read_args`
- **Сигнатура:** `read_args(args)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** extend, any, append, system, exists, startswith
- **Аргументы:**
  - `args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `args`.
- **Пример:** `read_args(...)`

#### `extract_all`
- **Сигнатура:** `extract_all(args)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** read_args, print, range, ExtractionThread, start, acquire
- **Аргументы:**
  - `args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `args`.
- **Пример:** `extract_all(...)`

#### `write_header`
- **Сигнатура:** `write_header(comments, out_file=sys.stdout)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** print, list, sorted
- **Аргументы:**
  - `comments`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `comments`.
  - `out_file`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `out_file`.
- **Пример:** `write_header(...)`

#### `mkdoc`
- **Сигнатура:** `mkdoc(args)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** list, enumerate, extract_all, startswith, write_header, remove
- **Аргументы:**
  - `args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `args`.
- **Пример:** `mkdoc(...)`

### Классы

### `NoFilenamesError`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** явно не определён.
- **Методы:**
  - отсутствуют

### `ExtractionThread`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self, filename, parameters, output)`
  - **Аргументы конструктора:**
    - `filename`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; инициализационный параметр `filename`.
    - `parameters`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `parameters`.
    - `output`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; инициализационный параметр `output`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, filename, parameters, output)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): __init__, acquire
    - Аргументы:
      - `filename`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `filename`.
      - `parameters`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `parameters`.
      - `output`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `output`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `run`
    - Сигнатура: `run(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): print, Index, parse, extract, release, clang_createIndex
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `myqr.run(words=info)` (из `examples/01_robot/05_sta_conn_helper.py:30`)
      - `multi_drone.run([tello_group, basic_task])` (из `examples/15_multi_robot/multi_drone/02_basic.py:35`)


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.docs.benchmark` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/docs/benchmark.py`)

### Функции

#### `generate_dummy_code_pybind11`
- **Сигнатура:** `generate_dummy_code_pybind11(nclasses=10)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** range, randint, join
- **Аргументы:**
  - `nclasses`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `nclasses`.
- **Пример:** `generate_dummy_code_pybind11()`

#### `generate_dummy_code_boost`
- **Сигнатура:** `generate_dummy_code_boost(nclasses=10)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** range, randint, join
- **Аргументы:**
  - `nclasses`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `nclasses`.
- **Пример:** `generate_dummy_code_boost()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.docs.conf` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/docs/conf.py`)

### Функции

#### `generate_doxygen_xml`
- **Сигнатура:** `generate_doxygen_xml(app)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** join, exists, mkdir, call, write, format
- **Аргументы:**
  - `app`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `app`.
- **Пример:** `generate_doxygen_xml(...)`

#### `setup`
- **Сигнатура:** `setup(app)`
- **Приватная:** нет
- **Описание:** Add hook for building doxygen xml when needed
- **Связи (вызовы):** connect
- **Аргументы:**
  - `app`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `app`.
- **Пример:** `setup(...)`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.pybind11.__init__` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/pybind11/__init__.py`)

### Функции

#### `get_include`
- **Сигнатура:** `get_include(user=False)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** dirname, exists, join
- **Аргументы:**
  - `user`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `user`.
- **Пример:** `get_include()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.pybind11.__main__` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/pybind11/__main__.py`)

### Функции

#### `print_includes`
- **Сигнатура:** `print_includes()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** print, get_path, get_include, join, append
- **Аргументы:**
  - нет аргументов
- **Пример:** `print_includes()`

#### `main`
- **Сигнатура:** `main()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** ArgumentParser, add_argument, parse_args, print_help, print_includes
- **Аргументы:**
  - нет аргументов
- **Пример:** `main()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.pybind11._version` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/pybind11/_version.py`)


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.setup` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/setup.py`)

### Классы

### `InstallHeaders`
- **Приватный класс:** нет
- **Описание:** Use custom header installer because the default one flattens subdirectories
- **Конструктор:** явно не определён.
- **Методы:**
  - `run`
    - Сигнатура: `run(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): dirname, join, mkpath, copy_file, append, relpath
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `myqr.run(words=info)` (из `examples/01_robot/05_sta_conn_helper.py:30`)
      - `multi_drone.run([tello_group, basic_task])` (из `examples/15_multi_robot/multi_drone/02_basic.py:35`)

### `BuildPy`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** явно не определён.
- **Методы:**
  - `build_package_data`
    - Сигнатура: `build_package_data(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): build_package_data, join, mkpath, copy_file, dirname
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `build_py.build_package_data(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/setup.py:64`)
      - `build_py.build_package_data(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/setup.py:64`)


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.tests.conftest` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/tests/conftest.py`)

### Функции

#### `_strip_and_dedent` (приватная)
- **Сигнатура:** `_strip_and_dedent(s)`
- **Приватная:** да
- **Описание:** For triple-quote strings
- **Связи (вызовы):** dedent, rstrip, lstrip
- **Аргументы:**
  - `s`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `s`.
- **Пример:** `_strip_and_dedent(...)`

#### `_split_and_sort` (приватная)
- **Сигнатура:** `_split_and_sort(s)`
- **Приватная:** да
- **Описание:** For output which does not require specific line order
- **Связи (вызовы):** sorted, splitlines, _strip_and_dedent
- **Аргументы:**
  - `s`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `s`.
- **Пример:** `_split_and_sort(...)`

#### `_make_explanation` (приватная)
- **Сигнатура:** `_make_explanation(a, b)`
- **Приватная:** да
- **Описание:** Explanation for a failed assert -- the a and b arguments are List[str]
- **Связи (вызовы):** strip, ndiff
- **Аргументы:**
  - `a`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `a`.
  - `b`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `b`.
- **Пример:** `_make_explanation(..., ...)`

#### `capture`
- **Сигнатура:** `capture(capsys)`
- **Приватная:** нет
- **Описание:** Extended `capsys` with context manager and custom equality operators
- **Связи (вызовы):** Capture
- **Аргументы:**
  - `capsys`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `capsys`.
- **Пример:** `capture(...)`

#### `_sanitize_general` (приватная)
- **Сигнатура:** `_sanitize_general(s)`
- **Приватная:** да
- **Описание:** описание отсутствует
- **Связи (вызовы):** strip, replace, sub
- **Аргументы:**
  - `s`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `s`.
- **Пример:** `_sanitize_general(...)`

#### `_sanitize_docstring` (приватная)
- **Сигнатура:** `_sanitize_docstring(thing)`
- **Приватная:** да
- **Описание:** описание отсутствует
- **Связи (вызовы):** _sanitize_general
- **Аргументы:**
  - `thing`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `thing`.
- **Пример:** `_sanitize_docstring(...)`

#### `doc`
- **Сигнатура:** `doc()`
- **Приватная:** нет
- **Описание:** Sanitize docstrings and add custom failure explanation
- **Связи (вызовы):** SanitizedString
- **Аргументы:**
  - нет аргументов
- **Пример:** `doc()`

#### `_sanitize_message` (приватная)
- **Сигнатура:** `_sanitize_message(thing)`
- **Приватная:** да
- **Описание:** описание отсутствует
- **Связи (вызовы):** str, _sanitize_general, sub
- **Аргументы:**
  - `thing`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `thing`.
- **Пример:** `_sanitize_message(...)`

#### `msg`
- **Сигнатура:** `msg()`
- **Приватная:** нет
- **Описание:** Sanitize messages and add custom failure explanation
- **Связи (вызовы):** SanitizedString
- **Аргументы:**
  - нет аргументов
- **Пример:** `msg()`

#### `pytest_assertrepr_compare`
- **Сигнатура:** `pytest_assertrepr_compare(op, left, right)`
- **Приватная:** нет
- **Описание:** Hook to insert custom failure explanation
- **Связи (вызовы):** hasattr
- **Аргументы:**
  - `op`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `op`.
  - `left`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `left`.
  - `right`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `right`.
- **Пример:** `pytest_assertrepr_compare(..., ..., ...)`

#### `suppress`
- **Сигнатура:** `suppress(exception)`
- **Приватная:** нет
- **Описание:** Suppress the desired exception
- **Связи (вызовы):** не выявлены
- **Аргументы:**
  - `exception`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `exception`.
- **Пример(ы) из репозитория:**
  - `with pytest.suppress(ImportError):` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_buffers.py:14`)
  - `with pytest.suppress(ImportError):` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_eigen.py:6`)

#### `gc_collect`
- **Сигнатура:** `gc_collect()`
- **Приватная:** нет
- **Описание:** Run the garbage collector twice (needed when running
- **Связи (вызовы):** collect
- **Аргументы:**
  - нет аргументов
- **Пример(ы) из репозитория:**
  - `pytest.gc_collect()` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_buffers.py:66`)
  - `pytest.gc_collect()` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_buffers.py:69`)

#### `pytest_configure`
- **Сигнатура:** `pytest_configure()`
- **Приватная:** нет
- **Описание:** Add import suppression and test requirements to `pytest` namespace
- **Связи (вызовы):** skipif, python_implementation
- **Аргументы:**
  - нет аргументов
- **Пример:** `pytest_configure()`

#### `_test_import_pybind11` (приватная)
- **Сигнатура:** `_test_import_pybind11()`
- **Приватная:** да
- **Описание:** Early diagnostic for test module initialization errors
- **Связи (вызовы):** print, exit, format, type
- **Аргументы:**
  - нет аргументов
- **Пример:** `_test_import_pybind11()`

### Классы

### `Output`
- **Приватный класс:** нет
- **Описание:** Basic output post-processing and comparison
- **Конструктор:** `__init__(self, string)`
  - **Аргументы конструктора:**
    - `string`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `string`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, string)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `string`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `string`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `__str__` (приватный)
    - Сигнатура: `__str__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.__str__()`
  - `__eq__` (приватный)
    - Сигнатура: `__eq__(self, other)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): splitlines, _make_explanation, _strip_and_dedent, startswith, strip
    - Аргументы:
      - `other`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `other`.
    - Пример: `obj.__eq__(...)`

### `Unordered`
- **Приватный класс:** нет
- **Описание:** Custom comparison for output without strict line ordering
- **Конструктор:** явно не определён.
- **Методы:**
  - `__eq__` (приватный)
    - Сигнатура: `__eq__(self, other)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): _split_and_sort, _make_explanation
    - Аргументы:
      - `other`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `other`.
    - Пример: `obj.__eq__(...)`

### `Capture`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self, capfd)`
  - **Аргументы конструктора:**
    - `capfd`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; инициализационный параметр `capfd`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, capfd)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `capfd`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `capfd`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `__enter__` (приватный)
    - Сигнатура: `__enter__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): readouterr
    - Аргументы:
      - нет аргументов
    - Пример: `obj.__enter__()`
  - `__exit__` (приватный)
    - Сигнатура: `__exit__(self, *args)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): readouterr
    - Аргументы:
      - `*args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `*args`.
    - Пример: `obj.__exit__()`
  - `__eq__` (приватный)
    - Сигнатура: `__eq__(self, other)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): Output
    - Аргументы:
      - `other`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `other`.
    - Пример: `obj.__eq__(...)`
  - `__str__` (приватный)
    - Сигнатура: `__str__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.__str__()`
  - `__contains__` (приватный)
    - Сигнатура: `__contains__(self, item)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `item`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `item`.
    - Пример: `obj.__contains__(...)`
  - `unordered`
    - Сигнатура: `unordered(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): Unordered
    - Аргументы:
      - нет аргументов
    - Пример: `obj.unordered()`
  - `stderr`
    - Сигнатура: `stderr(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): Output
    - Аргументы:
      - нет аргументов
    - Пример: `obj.stderr()`

### `SanitizedString`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self, sanitizer)`
  - **Аргументы конструктора:**
    - `sanitizer`: тип `не указан`; единицы `м`; допустимые значения `0..255`; инициализационный параметр `sanitizer`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, sanitizer)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `sanitizer`: тип `не указан`; единицы `м`; допустимые значения `0..255`; параметр `sanitizer`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `__call__` (приватный)
    - Сигнатура: `__call__(self, thing)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): sanitizer
    - Аргументы:
      - `thing`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `thing`.
    - Пример: `obj.__call__(...)`
  - `__eq__` (приватный)
    - Сигнатура: `__eq__(self, other)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): _strip_and_dedent, _make_explanation, splitlines
    - Аргументы:
      - `other`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `other`.
    - Пример: `obj.__eq__(...)`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.tests.test_async` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/tests/test_async.py`)

### Функции

#### `event_loop`
- **Сигнатура:** `event_loop()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** new_event_loop, close
- **Аргументы:**
  - нет аргументов
- **Пример:** `event_loop()`

#### `get_await_result`
- **Сигнатура:** `get_await_result(x)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** не выявлены
- **Аргументы:**
  - `x`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `x`.
- **Пример:** `get_await_result(...)`

#### `test_await`
- **Сигнатура:** `test_await(event_loop)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** run_until_complete, get_await_result, SupportsAsync
- **Аргументы:**
  - `event_loop`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `event_loop`.
- **Пример:** `test_await(...)`

#### `test_await_missing`
- **Сигнатура:** `test_await_missing(event_loop)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** raises, run_until_complete, get_await_result, DoesNotSupportAsync
- **Аргументы:**
  - `event_loop`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `event_loop`.
- **Пример:** `test_await_missing(...)`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.tests.test_buffers` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/tests/test_buffers.py`)

### Функции

#### `test_from_python`
- **Сигнатура:** `test_from_python()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** astype, Matrix, range, get, raises, str
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_from_python()`

#### `test_to_python`
- **Сигнатура:** `test_to_python()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** Matrix, array, get, gc_collect, unpack_from, sum
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_to_python()`

#### `test_inherited_protocol`
- **Сигнатура:** `test_inherited_protocol()`
- **Приватная:** нет
- **Описание:** SquareMatrix is derived from Matrix and inherits the buffer protocol
- **Связи (вызовы):** SquareMatrix, memoryview, asarray
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_inherited_protocol()`

#### `test_pointer_to_member_fn`
- **Сигнатура:** `test_pointer_to_member_fn()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** cls, unpack, bytearray
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_pointer_to_member_fn()`

#### `test_readonly_buffer`
- **Сигнатура:** `test_readonly_buffer()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** BufferReadOnly, memoryview
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_readonly_buffer()`

#### `test_selective_readonly_buffer`
- **Сигнатура:** `test_selective_readonly_buffer()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** BufferReadOnlySelect, readinto, memoryview, ord, raises, BytesIO
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_selective_readonly_buffer()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.tests.test_builtin_casters` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/tests/test_builtin_casters.py`)

### Функции

#### `test_simple_string`
- **Сигнатура:** `test_simple_string()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** string_roundtrip
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_simple_string()`

#### `test_unicode_conversion`
- **Сигнатура:** `test_unicode_conversion()`
- **Приватная:** нет
- **Описание:** Tests unicode conversion and error reporting.
- **Связи (вызовы):** hasattr, good_utf8_string, good_utf16_string, good_utf32_string, good_wchar_string, raises
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_unicode_conversion()`

#### `test_single_char_arguments`
- **Сигнатура:** `test_single_char_arguments()`
- **Приватная:** нет
- **Описание:** Tests failures for passing invalid inputs to char-accepting functions
- **Связи (вызовы):** format, ord_char, ord_char_lv, raises, str, toobig_message
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_single_char_arguments()`

#### `test_bytes_to_string`
- **Сигнатура:** `test_bytes_to_string()`
- **Приватная:** нет
- **Описание:** Tests the ability to pass bytes to C++ string-accepting functions.  Note that this is
- **Связи (вызовы):** strlen, string_length, byte, encode
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_bytes_to_string()`

#### `test_string_view`
- **Сигнатура:** `test_string_view(capture)`
- **Приватная:** нет
- **Описание:** Tests support for C++17 string_view arguments and return values
- **Связи (вызовы):** skipif, string_view_chars, string_view16_chars, string_view32_chars, string_view_return, string_view16_return
- **Аргументы:**
  - `capture`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `capture`.
- **Пример:** `test_string_view(...)`

#### `test_integer_casting`
- **Сигнатура:** `test_integer_casting()`
- **Приватная:** нет
- **Описание:** Issue #929 - out-of-range integer values shouldn't be accepted
- **Связи (вызовы):** i32_str, i64_str, u32_str, raises, str, u64_str
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_integer_casting()`

#### `test_tuple`
- **Сигнатура:** `test_tuple(doc)`
- **Приватная:** нет
- **Описание:** std::pair <-> tuple & std::tuple <-> tuple
- **Связи (вызовы):** pair_passthrough, tuple_passthrough, empty_tuple, doc, rvalue_pair, lvalue_pair
- **Аргументы:**
  - `doc`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `doc`.
- **Пример:** `test_tuple(...)`

#### `test_builtins_cast_return_none`
- **Сигнатура:** `test_builtins_cast_return_none()`
- **Приватная:** нет
- **Описание:** Casters produced with PYBIND11_TYPE_CASTER() should convert nullptr to None
- **Связи (вызовы):** return_none_string, return_none_char, return_none_bool, return_none_int, return_none_float
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_builtins_cast_return_none()`

#### `test_none_deferred`
- **Сигнатура:** `test_none_deferred()`
- **Приватная:** нет
- **Описание:** None passed as various argument types should defer to other overloads
- **Связи (вызовы):** defer_none_cstring, defer_none_custom, nodefer_none_void, UserType
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_none_deferred()`

#### `test_void_caster`
- **Сигнатура:** `test_void_caster()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** load_nullptr_t, cast_nullptr_t
- **Аргументы:**
  - нет аргументов
- **Пример(ы) из репозитория:**
  - `assert m.test_void_caster()` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_builtin_casters.py:346`)
  - `assert m.test_void_caster()` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/tests/test_builtin_casters.py:346`)

#### `test_reference_wrapper`
- **Сигнатура:** `test_reference_wrapper()`
- **Приватная:** нет
- **Описание:** std::reference_wrapper for builtin and user types
- **Связи (вызовы):** refwrap_list, refwrap_builtin, refwrap_usertype, raises, str, refwrap_iiw
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_reference_wrapper()`

#### `test_complex_cast`
- **Сигнатура:** `test_complex_cast()`
- **Приватная:** нет
- **Описание:** std::complex casts
- **Связи (вызовы):** complex_cast
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_complex_cast()`

#### `test_bool_caster`
- **Сигнатура:** `test_bool_caster()`
- **Приватная:** нет
- **Описание:** Test bool caster implicit conversions.
- **Связи (вызовы):** require_implicit, cant_convert, raises, convert, noconvert, object
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_bool_caster()`

#### `test_numpy_bool`
- **Сигнатура:** `test_numpy_bool()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** cant_convert, raises, convert, noconvert, zeros, bool_
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_numpy_bool()`

#### `test_int_long`
- **Сигнатура:** `test_int_long()`
- **Приватная:** нет
- **Описание:** In Python 2, a C++ int should return a Python int rather than long
- **Связи (вызовы):** type, isinstance, int_cast, long_cast, longlong_cast, getattr
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_int_long()`

#### `test_void_caster_2`
- **Сигнатура:** `test_void_caster_2()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** test_void_caster
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_void_caster_2()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.tests.test_call_policies` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/tests/test_call_policies.py`)

### Функции

#### `test_keep_alive_argument`
- **Сигнатура:** `test_keep_alive_argument(capture)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** detail_reg_inst, Parent, addChild, addChildKeepAlive, Child
- **Аргументы:**
  - `capture`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `capture`.
- **Пример:** `test_keep_alive_argument(...)`

#### `test_keep_alive_return_value`
- **Сигнатура:** `test_keep_alive_return_value(capture)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** detail_reg_inst, Parent, returnChild, returnChildKeepAlive
- **Аргументы:**
  - `capture`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `capture`.
- **Пример:** `test_keep_alive_return_value(...)`

#### `test_alive_gc`
- **Сигнатура:** `test_alive_gc(capture)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** detail_reg_inst, ParentGC, addChildKeepAlive, append, Child
- **Аргументы:**
  - `capture`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `capture`.
- **Пример:** `test_alive_gc(...)`

#### `test_alive_gc_derived`
- **Сигнатура:** `test_alive_gc_derived(capture)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** detail_reg_inst, Derived, addChildKeepAlive, append, Child
- **Аргументы:**
  - `capture`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `capture`.
- **Пример:** `test_alive_gc_derived(...)`

#### `test_alive_gc_multi_derived`
- **Сигнатура:** `test_alive_gc_multi_derived(capture)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** detail_reg_inst, Derived, addChildKeepAlive, append, Child, __init__
- **Аргументы:**
  - `capture`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `capture`.
- **Пример:** `test_alive_gc_multi_derived(...)`

#### `test_return_none`
- **Сигнатура:** `test_return_none(capture)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** detail_reg_inst, Parent, returnNullChildKeepAliveChild, returnNullChildKeepAliveParent
- **Аргументы:**
  - `capture`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `capture`.
- **Пример:** `test_return_none(...)`

#### `test_keep_alive_constructor`
- **Сигнатура:** `test_keep_alive_constructor(capture)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** detail_reg_inst, Parent, Child
- **Аргументы:**
  - `capture`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `capture`.
- **Пример:** `test_keep_alive_constructor(...)`

#### `test_call_guard`
- **Сигнатура:** `test_call_guard()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** hasattr, unguarded_call, guarded_call, multiple_guards_correct_order, multiple_guards_wrong_order, with_gil
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_call_guard()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.tests.test_callbacks` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/tests/test_callbacks.py`)

### Функции

#### `test_callbacks`
- **Сигнатура:** `test_callbacks()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** test_callback4, test_callback5, format, test_callback1, test_callback2, test_callback3
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_callbacks()`

#### `test_bound_method_callback`
- **Сигнатура:** `test_bound_method_callback()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** MyClass, CppBoundMethodTest, test_callback3
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_bound_method_callback()`

#### `test_keyword_args_and_generalized_unpacking`
- **Сигнатура:** `test_keyword_args_and_generalized_unpacking()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** test_tuple_unpacking, test_dict_unpacking, test_keyword_args, test_unpacking_and_keywords1, test_unpacking_and_keywords2, raises
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_keyword_args_and_generalized_unpacking()`

#### `test_lambda_closure_cleanup`
- **Сигнатура:** `test_lambda_closure_cleanup()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** test_cleanup, payload_cstats, alive
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_lambda_closure_cleanup()`

#### `test_cpp_function_roundtrip`
- **Сигнатура:** `test_cpp_function_roundtrip()`
- **Приватная:** нет
- **Описание:** Test if passing a function pointer from C++ -> Python -> C++ yields the original pointer
- **Связи (вызовы):** any, test_dummy_function, roundtrip, raises, str
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_cpp_function_roundtrip()`

#### `test_function_signatures`
- **Сигнатура:** `test_function_signatures(doc)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** doc
- **Аргументы:**
  - `doc`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `doc`.
- **Пример:** `test_function_signatures(...)`

#### `test_movable_object`
- **Сигнатура:** `test_movable_object()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** callback_with_movable
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_movable_object()`

#### `test_async_callbacks`
- **Сигнатура:** `test_async_callbacks()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** test_async_callback, sleep, Item, gen_f, sum, append
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_async_callbacks()`

#### `test_async_async_callbacks`
- **Сигнатура:** `test_async_async_callbacks()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** Thread, start, join
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_async_async_callbacks()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.tests.test_chrono` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/tests/test_chrono.py`)

### Функции

#### `test_chrono_system_clock`
- **Сигнатура:** `test_chrono_system_clock()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** test_chrono1, today, isinstance, abs
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_chrono_system_clock()`

#### `test_chrono_system_clock_roundtrip`
- **Сигнатура:** `test_chrono_system_clock_roundtrip()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** today, test_chrono2, isinstance, abs
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_chrono_system_clock_roundtrip()`

#### `test_chrono_system_clock_roundtrip_date`
- **Сигнатура:** `test_chrono_system_clock_roundtrip_date()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** today, test_chrono2, date, time, isinstance, abs
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_chrono_system_clock_roundtrip_date()`

#### `test_chrono_system_clock_roundtrip_time`
- **Сигнатура:** `test_chrono_system_clock_roundtrip_time()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** time, test_chrono2, date, isinstance, today
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_chrono_system_clock_roundtrip_time()`

#### `test_chrono_duration_roundtrip`
- **Сигнатура:** `test_chrono_duration_roundtrip()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** today, isinstance, test_chrono3
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_chrono_duration_roundtrip()`

#### `test_chrono_duration_subtraction_equivalence`
- **Сигнатура:** `test_chrono_duration_subtraction_equivalence()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** today, test_chrono4
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_chrono_duration_subtraction_equivalence()`

#### `test_chrono_duration_subtraction_equivalence_date`
- **Сигнатура:** `test_chrono_duration_subtraction_equivalence_date()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** today, test_chrono4
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_chrono_duration_subtraction_equivalence_date()`

#### `test_chrono_steady_clock`
- **Сигнатура:** `test_chrono_steady_clock()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** test_chrono5, isinstance
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_chrono_steady_clock()`

#### `test_chrono_steady_clock_roundtrip`
- **Сигнатура:** `test_chrono_steady_clock_roundtrip()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** timedelta, test_chrono6, isinstance
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_chrono_steady_clock_roundtrip()`

#### `test_floating_point_duration`
- **Сигнатура:** `test_floating_point_duration()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** test_chrono7, isinstance, test_chrono_float_diff
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_floating_point_duration()`

#### `test_nano_timepoint`
- **Сигнатура:** `test_nano_timepoint()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** now, test_nano_timepoint, timedelta
- **Аргументы:**
  - нет аргументов
- **Пример(ы) из репозитория:**
  - `time1 = m.test_nano_timepoint(time, datetime.timedelta(seconds=60))` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_chrono.py:175`)
  - `time1 = m.test_nano_timepoint(time, datetime.timedelta(seconds=60))` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/tests/test_chrono.py:175`)


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.tests.test_class` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/tests/test_class.py`)

### Функции

#### `test_repr`
- **Сигнатура:** `test_repr()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** repr, type
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_repr()`

#### `test_instance`
- **Сигнатура:** `test_instance(msg)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** new_instance, get, raises, NoConstructor, msg, alive
- **Аргументы:**
  - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
- **Пример:** `test_instance(...)`

#### `test_docstrings`
- **Сигнатура:** `test_docstrings(doc)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** doc
- **Аргументы:**
  - `doc`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `doc`.
- **Пример:** `test_docstrings(...)`

#### `test_qualname`
- **Сигнатура:** `test_qualname(doc)`
- **Приватная:** нет
- **Описание:** Tests that a properly qualified name is set in __qualname__ (even in pre-3.3, where we
- **Связи (вызовы):** doc
- **Аргументы:**
  - `doc`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `doc`.
- **Пример:** `test_qualname(...)`

#### `test_inheritance`
- **Сигнатура:** `test_inheritance(msg)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** Rabbit, Pet, Dog, Hamster, pet_name_species, dog_bark
- **Аргументы:**
  - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
- **Пример:** `test_inheritance(...)`

#### `test_automatic_upcasting`
- **Сигнатура:** `test_automatic_upcasting()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** type, return_class_1, return_class_2, return_none, return_class_n
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_automatic_upcasting()`

#### `test_isinstance`
- **Сигнатура:** `test_isinstance()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** check_instances, tuple, dict, Pet, Dog
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_isinstance()`

#### `test_mismatched_holder`
- **Сигнатура:** `test_mismatched_holder()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** match, raises, mismatched_holder_1, str, mismatched_holder_2
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_mismatched_holder()`

#### `test_override_static`
- **Сигнатура:** `test_override_static()`
- **Приватная:** нет
- **Описание:** #511: problem with inheritance + overwritten def_static
- **Связи (вызовы):** make, make2, isinstance
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_override_static()`

#### `test_implicit_conversion_life_support`
- **Сигнатура:** `test_implicit_conversion_life_support()`
- **Приватная:** нет
- **Описание:** Ensure the lifetime of temporary objects created for implicit conversions
- **Связи (вызовы):** implicitly_convert_argument, implicitly_convert_variable, implicitly_convert_variable_fail, UserType
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_implicit_conversion_life_support()`

#### `test_operator_new_delete`
- **Сигнатура:** `test_operator_new_delete(capture)`
- **Приватная:** нет
- **Описание:** Tests that class-specific operator new/delete functions are invoked
- **Связи (вызовы):** str, HasOpNewDel, HasOpNewDelSize, HasOpNewDelBoth, AliasedHasOpNewDelSize, SubAliased
- **Аргументы:**
  - `capture`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `capture`.
- **Пример:** `test_operator_new_delete(...)`

#### `test_bind_protected_functions`
- **Сигнатура:** `test_bind_protected_functions()`
- **Приватная:** нет
- **Описание:** Expose protected member functions to Python using a helper class
- **Связи (вызовы):** ProtectedA, ProtectedB, C, foo, __init__
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_bind_protected_functions()`

#### `test_brace_initialization`
- **Сигнатура:** `test_brace_initialization()`
- **Приватная:** нет
- **Описание:** Tests that simple POD classes can be constructed using C++11 brace initialization
- **Связи (вызовы):** BraceInitialization, NoBraceInitialization
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_brace_initialization()`

#### `test_class_refcount`
- **Сигнатура:** `test_class_refcount()`
- **Приватная:** нет
- **Описание:** Instances must correctly increase/decrease the reference count of their types (#1029)
- **Связи (вызовы):** getrefcount, gc_collect, cls, range
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_class_refcount()`

#### `test_reentrant_implicit_conversion_failure`
- **Сигнатура:** `test_reentrant_implicit_conversion_failure(msg)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** raises, BogusImplicitConversion, msg
- **Аргументы:**
  - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
- **Пример:** `test_reentrant_implicit_conversion_failure(...)`

#### `test_error_after_conversions`
- **Сигнатура:** `test_error_after_conversions()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** startswith, raises, test_error_after_conversions, str
- **Аргументы:**
  - нет аргументов
- **Пример(ы) из репозитория:**
  - `m.test_error_after_conversions("hello")` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_class.py:273`)
  - `m.test_error_after_conversions("hello")` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/tests/test_class.py:273`)

#### `test_aligned`
- **Сигнатура:** `test_aligned()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** hasattr, ptr, Aligned
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_aligned()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.tests.test_cmake_build.test` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/tests/test_cmake_build/test.py`)


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.tests.test_constants_and_functions` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/tests/test_constants_and_functions.py`)

### Функции

#### `test_constants`
- **Сигнатура:** `test_constants()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** не выявлены
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_constants()`

#### `test_function_overloading`
- **Сигнатура:** `test_function_overloading()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** test_function
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_function_overloading()`

#### `test_bytes`
- **Сигнатура:** `test_bytes()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** print_bytes, return_bytes
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_bytes()`

#### `test_exception_specifiers`
- **Сигнатура:** `test_exception_specifiers()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** C, m1, m2, m3, m4, m5
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_exception_specifiers()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.tests.test_copy_move` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/tests/test_copy_move.py`)

### Функции

#### `test_lacking_copy_ctor`
- **Сигнатура:** `test_lacking_copy_ctor()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** raises, get_one, str
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_lacking_copy_ctor()`

#### `test_lacking_move_ctor`
- **Сигнатура:** `test_lacking_move_ctor()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** raises, get_one, str
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_lacking_move_ctor()`

#### `test_move_and_copy_casts`
- **Сигнатура:** `test_move_and_copy_casts()`
- **Приватная:** нет
- **Описание:** Cast some values in C++ via custom type casters and count the number of moves/copies.
- **Связи (вызовы):** move_and_copy_cstats, move_and_copy_casts, alive
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_move_and_copy_casts()`

#### `test_move_and_copy_loads`
- **Сигнатура:** `test_move_and_copy_loads()`
- **Приватная:** нет
- **Описание:** Call some functions that load arguments via custom type casters and count the number of
- **Связи (вызовы):** move_and_copy_cstats, move_only, move_or_copy, copy_only, move_pair, move_tuple
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_move_and_copy_loads()`

#### `test_move_and_copy_load_optional`
- **Сигнатура:** `test_move_and_copy_load_optional()`
- **Приватная:** нет
- **Описание:** Tests move/copy loads of std::optional arguments
- **Связи (вызовы):** skipif, move_and_copy_cstats, move_optional, move_or_copy_optional, copy_optional, move_optional_tuple
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_move_and_copy_load_optional()`

#### `test_private_op_new`
- **Сигнатура:** `test_private_op_new()`
- **Приватная:** нет
- **Описание:** An object with a private `operator new` cannot be returned by value
- **Связи (вызовы):** raises, private_op_new_value, str, private_op_new_reference
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_private_op_new()`

#### `test_move_fallback`
- **Сигнатура:** `test_move_fallback()`
- **Приватная:** нет
- **Описание:** #389: rvp::move should fall-through to copy on non-movable objects
- **Связи (вызовы):** get_moveissue2, get_moveissue1
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_move_fallback()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.tests.test_docstring_options` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/tests/test_docstring_options.py`)

### Функции

#### `test_docstring_options`
- **Сигнатура:** `test_docstring_options()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** startswith, endswith
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_docstring_options()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.tests.test_eigen` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/tests/test_eigen.py`)

### Функции

#### `assert_equal_ref`
- **Сигнатура:** `assert_equal_ref(mat)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** assert_array_equal
- **Аргументы:**
  - `mat`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `mat`.
- **Пример:** `assert_equal_ref(...)`

#### `assert_sparse_equal_ref`
- **Сигнатура:** `assert_sparse_equal_ref(sparse_mat)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** assert_equal_ref, toarray
- **Аргументы:**
  - `sparse_mat`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `sparse_mat`.
- **Пример:** `assert_sparse_equal_ref(...)`

#### `test_fixed`
- **Сигнатура:** `test_fixed()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** assert_equal_ref, fixed_c, fixed_r, fixed_copy_r, fixed_copy_c
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_fixed()`

#### `test_dense`
- **Сигнатура:** `test_dense()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** assert_equal_ref, dense_r, dense_c, dense_copy_r, dense_copy_c
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_dense()`

#### `test_partially_fixed`
- **Сигнатура:** `test_partially_fixed()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** array, assert_array_equal, partial_copy_four_rm_r, partial_copy_four_rm_c, partial_copy_four_cm_r, partial_copy_four_cm_c
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_partially_fixed()`

#### `test_mutator_descriptors`
- **Сигнатура:** `test_mutator_descriptors()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** reshape, transpose, fixed_mutator_r, fixed_mutator_c, fixed_mutator_a, raises
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_mutator_descriptors()`

#### `test_cpp_casting`
- **Сигнатура:** `test_cpp_casting()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** array, cpp_copy, cpp_ref_c, cpp_ref_r, raises, cpp_ref_any
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_cpp_casting()`

#### `test_pass_readonly_array`
- **Сигнатура:** `test_pass_readonly_array()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** full, assert_array_equal, fixed_copy_r, fixed_r_const, fixed_r
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_pass_readonly_array()`

#### `test_nonunit_stride_from_python`
- **Сигнатура:** `test_nonunit_stride_from_python()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** reshape, assert_array_equal, enumerate, double_threer, double_threec, double_row
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_nonunit_stride_from_python()`

#### `test_negative_stride_from_python`
- **Сигнатура:** `test_negative_stride_from_python(msg)`
- **Приватная:** нет
- **Описание:** Eigen doesn't support (as of yet) negative strides. When a function takes an Eigen matrix by
- **Связи (вызовы):** reshape, assert_array_equal, enumerate, double_row, double_col, double_complex
- **Аргументы:**
  - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
- **Пример:** `test_negative_stride_from_python(...)`

#### `test_nonunit_stride_to_python`
- **Сигнатура:** `test_nonunit_stride_to_python()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** all, range, format, diagonal, diagonal_1, block
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_nonunit_stride_to_python()`

#### `test_eigen_ref_to_python`
- **Сигнатура:** `test_eigen_ref_to_python()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** enumerate, chol, all, format, array
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_eigen_ref_to_python()`

#### `assign_both`
- **Сигнатура:** `assign_both(a1, a2, r, c, v)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** не выявлены
- **Аргументы:**
  - `a1`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `a1`.
  - `a2`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `a2`.
  - `r`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `r`.
  - `c`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `c`.
  - `v`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `v`.
- **Пример:** `assign_both(..., ..., ..., ..., ...)`

#### `array_copy_but_one`
- **Сигнатура:** `array_copy_but_one(a, r, c, v)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** array
- **Аргументы:**
  - `a`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `a`.
  - `r`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `r`.
  - `c`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `c`.
  - `v`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `v`.
- **Пример:** `array_copy_but_one(..., ..., ..., ...)`

#### `test_eigen_return_references`
- **Сигнатура:** `test_eigen_return_references()`
- **Приватная:** нет
- **Описание:** Tests various ways of returning references and non-referencing copies
- **Связи (вызовы):** ones, ReturnTester, get, assign_both, get_ptr, view
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_eigen_return_references()`

#### `assert_keeps_alive`
- **Сигнатура:** `assert_keeps_alive(cl, method, *args)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** get, alive, cl, method
- **Аргументы:**
  - `cl`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `cl`.
  - `method`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `method`.
  - `*args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `*args`.
- **Пример:** `assert_keeps_alive(..., ...)`

#### `test_eigen_keepalive`
- **Сигнатура:** `test_eigen_keepalive()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** ReturnTester, get, alive, ref, ref_const, block
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_eigen_keepalive()`

#### `test_eigen_ref_mutators`
- **Сигнатура:** `test_eigen_ref_mutators()`
- **Приватная:** нет
- **Описание:** Tests Eigen's ability to mutate numpy values
- **Связи (вызовы):** array, add_rm, all, add_cm, add_any, add1
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_eigen_ref_mutators()`

#### `test_numpy_ref_mutators`
- **Сигнатура:** `test_numpy_ref_mutators()`
- **Приватная:** нет
- **Описание:** Tests numpy mutating Eigen matrices (for returned Eigen::Ref<...>s)
- **Связи (вызовы):** reset_refs, get_cm_ref, get_cm_const_ref, get_rm_ref, get_rm_const_ref, array
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_numpy_ref_mutators()`

#### `test_both_ref_mutators`
- **Сигнатура:** `test_both_ref_mutators()`
- **Приватная:** нет
- **Описание:** Tests a complex chain of nested eigen/numpy references
- **Связи (вызовы):** reset_refs, get_cm_ref, incr_matrix, all, array, reshape
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_both_ref_mutators()`

#### `test_nocopy_wrapper`
- **Сигнатура:** `test_nocopy_wrapper()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** array, get_elem, raises, get_elem_nocopy, get_elem_rm_nocopy, str
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_nocopy_wrapper()`

#### `test_eigen_ref_life_support`
- **Сигнатура:** `test_eigen_ref_life_support()`
- **Приватная:** нет
- **Описание:** Ensure the lifetime of temporary arrays created by the `Ref` caster
- **Связи (вызовы):** full, get_elem_direct, get_elem_indirect
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_eigen_ref_life_support()`

#### `test_special_matrix_objects`
- **Сигнатура:** `test_special_matrix_objects()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** all, array, range, incr_diag, diag, symmetric_lower
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_special_matrix_objects()`

#### `test_dense_signature`
- **Сигнатура:** `test_dense_signature(doc)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** doc
- **Аргументы:**
  - `doc`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `doc`.
- **Пример:** `test_dense_signature(...)`

#### `test_named_arguments`
- **Сигнатура:** `test_named_arguments()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** array, ones, all, raises, matrix_multiply, str
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_named_arguments()`

#### `test_sparse`
- **Сигнатура:** `test_sparse()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** assert_sparse_equal_ref, sparse_r, sparse_c, sparse_copy_r, sparse_copy_c
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_sparse()`

#### `test_sparse_signature`
- **Сигнатура:** `test_sparse_signature(doc)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** doc
- **Аргументы:**
  - `doc`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `doc`.
- **Пример:** `test_sparse_signature(...)`

#### `test_issue738`
- **Сигнатура:** `test_issue738()`
- **Приватная:** нет
- **Описание:** Ignore strides on a length-1 dimension (even if they would be incompatible length > 1)
- **Связи (вызовы):** all, iss738_f1, array, iss738_f2
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_issue738()`

#### `test_issue1105`
- **Сигнатура:** `test_issue1105()`
- **Приватная:** нет
- **Описание:** Issue 1105: 1xN or Nx1 input arrays weren't accepted for eigen
- **Связи (вызовы):** iss1105_row, iss1105_col, ones, raises, str
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_issue1105()`

#### `test_custom_operator_new`
- **Сигнатура:** `test_custom_operator_new()`
- **Приватная:** нет
- **Описание:** Using Eigen types as member variables requires a class-specific
- **Связи (вызовы):** CustomOperatorNew, assert_allclose, diagonal
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_custom_operator_new()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.tests.test_embed.test_interpreter` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/tests/test_embed/test_interpreter.py`)

### Классы

### `DerivedWidget`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self, message)`
  - **Аргументы конструктора:**
    - `message`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `message`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, message)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): __init__, super
    - Аргументы:
      - `message`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `message`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `the_answer`
    - Сигнатура: `the_answer(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.the_answer()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.tests.test_enum` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/tests/test_enum.py`)

### Функции

#### `test_unscoped_enum`
- **Сигнатура:** `test_unscoped_enum()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** split, str, raises, object, int, UnscopedEnum
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_unscoped_enum()`

#### `test_scoped_enum`
- **Сигнатура:** `test_scoped_enum()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** test_scoped_enum, object, raises
- **Аргументы:**
  - нет аргументов
- **Пример(ы) из репозитория:**
  - `assert m.test_scoped_enum(m.ScopedEnum.Three) == "ScopedEnum::Three"` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_enum.py:108`)
  - `assert m.test_scoped_enum(z) == "ScopedEnum::Two"` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_enum.py:110`)

#### `test_implicit_conversion`
- **Сигнатура:** `test_implicit_conversion()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** str, f, int
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_implicit_conversion()`

#### `test_binary_operators`
- **Сигнатура:** `test_binary_operators()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** int
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_binary_operators()`

#### `test_enum_to_int`
- **Сигнатура:** `test_enum_to_int()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** test_enum_to_int, test_enum_to_uint, test_enum_to_long_long
- **Аргументы:**
  - нет аргументов
- **Пример(ы) из репозитория:**
  - `m.test_enum_to_int(m.Flags.Read)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_enum.py:195`)
  - `m.test_enum_to_int(m.ClassWithUnscopedEnum.EMode.EFirstMode)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_enum.py:196`)

#### `test_duplicate_enum_name`
- **Сигнатура:** `test_duplicate_enum_name()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** raises, register_bad_enum, str
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_duplicate_enum_name()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.tests.test_eval` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/tests/test_eval.py`)

### Функции

#### `test_evals`
- **Сигнатура:** `test_evals(capture)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** test_eval, test_eval_single_statement, join, test_eval_file, test_eval_failure, test_eval_file_failure
- **Аргументы:**
  - `capture`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `capture`.
- **Пример:** `test_evals(...)`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.tests.test_eval_call` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/tests/test_eval_call.py`)


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.tests.test_exceptions` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/tests/test_exceptions.py`)

### Функции

#### `test_std_exception`
- **Сигнатура:** `test_std_exception(msg)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** raises, throw_std_exception, msg
- **Аргументы:**
  - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
- **Пример:** `test_std_exception(...)`

#### `test_error_already_set`
- **Сигнатура:** `test_error_already_set(msg)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** raises, throw_already_set, msg
- **Аргументы:**
  - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
- **Пример:** `test_error_already_set(...)`

#### `test_cross_module_exceptions`
- **Сигнатура:** `test_cross_module_exceptions()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** raises, raise_runtime_error, str, raise_value_error, throw_pybind_value_error, throw_pybind_type_error
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_cross_module_exceptions()`

#### `test_python_call_in_catch`
- **Сигнатура:** `test_python_call_in_catch()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** python_call_in_destructor
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_python_call_in_catch()`

#### `test_exception_matches`
- **Сигнатура:** `test_exception_matches()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** exception_matches, exception_matches_base, modulenotfound_exception_matches_base
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_exception_matches()`

#### `test_custom`
- **Сигнатура:** `test_custom(msg)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** isinstance, raises, throws1, msg, throws2, throws3
- **Аргументы:**
  - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
- **Пример:** `test_custom(...)`

#### `test_nested_throws`
- **Сигнатура:** `test_nested_throws(capture)`
- **Приватная:** нет
- **Описание:** Tests nested (e.g. C++ -> Python -> C++) exception handling
- **Связи (вызовы):** startswith, MyException, MyException5, try_catch, raises, str
- **Аргументы:**
  - `capture`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `capture`.
- **Пример:** `test_nested_throws(...)`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.tests.test_factory_constructors` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/tests/test_factory_constructors.py`)

### Функции

#### `test_init_factory_basic`
- **Сигнатура:** `test_init_factory_basic()`
- **Приватная:** нет
- **Описание:** Tests py::init_factory() wrapper around various ways of returning the object
- **Связи (вызовы):** alive, detail_reg_inst, TestFactory1, TestFactory2, TestFactory3, get
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_init_factory_basic()`

#### `test_init_factory_signature`
- **Сигнатура:** `test_init_factory_signature(msg)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** raises, TestFactory1, msg
- **Аргументы:**
  - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
- **Пример:** `test_init_factory_signature(...)`

#### `test_init_factory_casting`
- **Сигнатура:** `test_init_factory_casting()`
- **Приватная:** нет
- **Описание:** Tests py::init_factory() wrapper with various upcasting and downcasting returns
- **Связи (вызовы):** alive, detail_reg_inst, TestFactory3, TestFactory4, get, values
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_init_factory_casting()`

#### `test_init_factory_alias`
- **Сигнатура:** `test_init_factory_alias()`
- **Приватная:** нет
- **Описание:** Tests py::init_factory() wrapper with value conversions and alias types
- **Связи (вызовы):** alive, detail_reg_inst, TestFactory6, has_alias, MyTest, get_cstats
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_init_factory_alias()`

#### `test_init_factory_dual`
- **Сигнатура:** `test_init_factory_dual()`
- **Приватная:** нет
- **Описание:** Tests init factory functions with dual main/alias factory functions
- **Связи (вызовы):** alive, detail_reg_inst, TestFactory7, PythFactory7, has_alias, get_cstats
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_init_factory_dual()`

#### `test_no_placement_new`
- **Сигнатура:** `test_no_placement_new(capture)`
- **Приватная:** нет
- **Описание:** Prior to 2.2, `py::init<...>` relied on the type supporting placement
- **Связи (вызовы):** search, NoPlacementNew, str, gc_collect, group
- **Аргументы:**
  - `capture`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `capture`.
- **Пример:** `test_no_placement_new(...)`

#### `test_multiple_inheritance`
- **Сигнатура:** `test_multiple_inheritance()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** MITest, fget, __init__
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_multiple_inheritance()`

#### `create_and_destroy`
- **Сигнатура:** `create_and_destroy(*args)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** NoisyAlloc, print, gc_collect
- **Аргументы:**
  - `*args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `*args`.
- **Пример:** `create_and_destroy()`

#### `strip_comments`
- **Сигнатура:** `strip_comments(s)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** sub
- **Аргументы:**
  - `s`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `s`.
- **Пример:** `strip_comments(...)`

#### `test_reallocations`
- **Сигнатура:** `test_reallocations(capture, msg)`
- **Приватная:** нет
- **Описание:** When the constructor is overloaded, previous overloads can require a preallocated value.
- **Связи (вызовы):** gc_collect, create_and_destroy, msg, strip_comments
- **Аргументы:**
  - `capture`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `capture`.
  - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
- **Пример:** `test_reallocations(..., ...)`

#### `test_invalid_self`
- **Сигнатура:** `test_invalid_self()`
- **Приватная:** нет
- **Описание:** Tests invocation of the pybind-registered base class with an invalid `self` argument.  You
- **Связи (вызовы):** raises, BrokenTF1, str, BrokenTF6, TestFactory2, __init__
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_invalid_self()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.tests.test_gil_scoped` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/tests/test_gil_scoped.py`)

### Функции

#### `_run_in_process` (приватная)
- **Сигнатура:** `_run_in_process(target, *args, **kwargs)`
- **Приватная:** да
- **Описание:** Runs target in process and returns its exitcode after 10s (None if still alive).
- **Связи (вызовы):** Process, start, join, is_alive, terminate
- **Аргументы:**
  - `target`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `target`.
  - `*args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `*args`.
  - `**kwargs`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `**kwargs`.
- **Пример:** `_run_in_process(...)`

#### `_python_to_cpp_to_python` (приватная)
- **Сигнатура:** `_python_to_cpp_to_python()`
- **Приватная:** да
- **Описание:** Calls different C++ functions that come back to Python.
- **Связи (вызовы):** ExtendedVirtClass, test_callback_py_obj, test_callback_std_func, test_callback_virtual_func, test_callback_pure_virtual_func
- **Аргументы:**
  - нет аргументов
- **Пример:** `_python_to_cpp_to_python()`

#### `_python_to_cpp_to_python_from_threads` (приватная)
- **Сигнатура:** `_python_to_cpp_to_python_from_threads(num_threads, parallel=False)`
- **Приватная:** да
- **Описание:** Calls different C++ functions that come back to Python, from Python threads.
- **Связи (вызовы):** range, Thread, start, join, append
- **Аргументы:**
  - `num_threads`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `num_threads`.
  - `parallel`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `parallel`.
- **Пример:** `_python_to_cpp_to_python_from_threads(...)`

#### `test_python_to_cpp_to_python_from_thread`
- **Сигнатура:** `test_python_to_cpp_to_python_from_thread()`
- **Приватная:** нет
- **Описание:** Makes sure there is no GIL deadlock when running in a thread.
- **Связи (вызовы):** _run_in_process
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_python_to_cpp_to_python_from_thread()`

#### `test_python_to_cpp_to_python_from_thread_multiple_parallel`
- **Сигнатура:** `test_python_to_cpp_to_python_from_thread_multiple_parallel()`
- **Приватная:** нет
- **Описание:** Makes sure there is no GIL deadlock when running in a thread multiple times in parallel.
- **Связи (вызовы):** _run_in_process
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_python_to_cpp_to_python_from_thread_multiple_parallel()`

#### `test_python_to_cpp_to_python_from_thread_multiple_sequential`
- **Сигнатура:** `test_python_to_cpp_to_python_from_thread_multiple_sequential()`
- **Приватная:** нет
- **Описание:** Makes sure there is no GIL deadlock when running in a thread multiple times sequentially.
- **Связи (вызовы):** _run_in_process
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_python_to_cpp_to_python_from_thread_multiple_sequential()`

#### `test_python_to_cpp_to_python_from_process`
- **Сигнатура:** `test_python_to_cpp_to_python_from_process()`
- **Приватная:** нет
- **Описание:** Makes sure there is no GIL deadlock when using processes.
- **Связи (вызовы):** _run_in_process
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_python_to_cpp_to_python_from_process()`

#### `test_cross_module_gil`
- **Сигнатура:** `test_cross_module_gil()`
- **Приватная:** нет
- **Описание:** Makes sure that the GIL can be acquired by another module from a GIL-released state.
- **Связи (вызовы):** test_cross_module_gil
- **Аргументы:**
  - нет аргументов
- **Пример(ы) из репозитория:**
  - `m.test_cross_module_gil()  # Should not raise a SIGSEGV` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_gil_scoped.py:85`)
  - `m.test_cross_module_gil()  # Should not raise a SIGSEGV` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/tests/test_gil_scoped.py:85`)


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.tests.test_iostream` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/tests/test_iostream.py`)

### Функции

#### `test_captured`
- **Сигнатура:** `test_captured(capsys)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** captured_output, readouterr, captured_output_default, captured_err
- **Аргументы:**
  - `capsys`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `capsys`.
- **Пример:** `test_captured(...)`

#### `test_captured_large_string`
- **Сигнатура:** `test_captured_large_string(capsys)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** captured_output_default, readouterr, len
- **Аргументы:**
  - `capsys`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `capsys`.
- **Пример:** `test_captured_large_string(...)`

#### `test_guard_capture`
- **Сигнатура:** `test_guard_capture(capsys)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** guard_output, readouterr
- **Аргументы:**
  - `capsys`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `capsys`.
- **Пример:** `test_guard_capture(...)`

#### `test_series_captured`
- **Сигнатура:** `test_series_captured(capture)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** captured_output
- **Аргументы:**
  - `capture`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `capture`.
- **Пример:** `test_series_captured(...)`

#### `test_flush`
- **Сигнатура:** `test_flush(capfd)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** readouterr, ostream_redirect, noisy_function
- **Аргументы:**
  - `capfd`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `capfd`.
- **Пример:** `test_flush(...)`

#### `test_not_captured`
- **Сигнатура:** `test_not_captured(capfd)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** StringIO, readouterr, redirect_stdout, raw_output, getvalue, captured_output
- **Аргументы:**
  - `capfd`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `capfd`.
- **Пример:** `test_not_captured(...)`

#### `test_err`
- **Сигнатура:** `test_err(capfd)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** StringIO, readouterr, redirect_stderr, raw_err, getvalue, captured_err
- **Аргументы:**
  - `capfd`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `capfd`.
- **Пример:** `test_err(...)`

#### `test_multi_captured`
- **Сигнатура:** `test_multi_captured(capfd)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** StringIO, readouterr, redirect_stdout, captured_output, raw_output, getvalue
- **Аргументы:**
  - `capfd`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `capfd`.
- **Пример:** `test_multi_captured(...)`

#### `test_dual`
- **Сигнатура:** `test_dual(capsys)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** captured_dual, readouterr
- **Аргументы:**
  - `capsys`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `capsys`.
- **Пример:** `test_dual(...)`

#### `test_redirect`
- **Сигнатура:** `test_redirect(capfd)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** StringIO, readouterr, redirect_stdout, raw_output, getvalue, ostream_redirect
- **Аргументы:**
  - `capfd`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `capfd`.
- **Пример:** `test_redirect(...)`

#### `test_redirect_err`
- **Сигнатура:** `test_redirect_err(capfd)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** StringIO, readouterr, redirect_stderr, getvalue, ostream_redirect, raw_output
- **Аргументы:**
  - `capfd`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `capfd`.
- **Пример:** `test_redirect_err(...)`

#### `test_redirect_both`
- **Сигнатура:** `test_redirect_both(capfd)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** StringIO, readouterr, redirect_stdout, getvalue, redirect_stderr, ostream_redirect
- **Аргументы:**
  - `capfd`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `capfd`.
- **Пример:** `test_redirect_both(...)`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.tests.test_kwargs_and_defaults` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/tests/test_kwargs_and_defaults.py`)

### Функции

#### `test_function_signatures`
- **Сигнатура:** `test_function_signatures(doc)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** doc
- **Аргументы:**
  - `doc`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `doc`.
- **Пример:** `test_function_signatures(...)`

#### `test_named_arguments`
- **Сигнатура:** `test_named_arguments(msg)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** match, kw_func0, kw_func1, kw_func2, raises, kw_func4
- **Аргументы:**
  - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
- **Пример:** `test_named_arguments(...)`

#### `test_arg_and_kwargs`
- **Сигнатура:** `test_arg_and_kwargs()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** dict, args_function, args_kwargs_function
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_arg_and_kwargs()`

#### `test_mixed_args_and_kwargs`
- **Сигнатура:** `test_mixed_args_and_kwargs(msg)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** mpa, raises, msg, mpk, mpak, mpakd
- **Аргументы:**
  - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
- **Пример:** `test_mixed_args_and_kwargs(...)`

#### `test_args_refcount`
- **Сигнатура:** `test_args_refcount()`
- **Приватная:** нет
- **Описание:** Issue/PR #1216 - py::args elements get double-inc_ref()ed when combined with regular
- **Связи (вызовы):** refcount, arg_refcount_h, arg_refcount_o, mixed_plus_args, mixed_plus_kwargs, args_function
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_args_refcount()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.tests.test_local_bindings` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/tests/test_local_bindings.py`)

### Функции

#### `test_load_external`
- **Сигнатура:** `test_load_external()`
- **Приватная:** нет
- **Описание:** Load a `py::module_local` type that's only registered in an external module
- **Связи (вызовы):** load_external1, load_external2, raises, str, ExternalType1, ExternalType2
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_load_external()`

#### `test_local_bindings`
- **Сигнатура:** `test_local_bindings()`
- **Приватная:** нет
- **Описание:** Tests that duplicate `py::module_local` class bindings work across modules
- **Связи (вызовы):** LocalType, get, get3, get2, hasattr, local_value
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_local_bindings()`

#### `test_nonlocal_failure`
- **Сигнатура:** `test_nonlocal_failure()`
- **Приватная:** нет
- **Описание:** Tests that attempting to register a non-local type in multiple modules fails
- **Связи (вызовы):** raises, register_nonlocal, str
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_nonlocal_failure()`

#### `test_duplicate_local`
- **Сигнатура:** `test_duplicate_local()`
- **Приватная:** нет
- **Описание:** Tests expected failure when registering a class twice with py::local in the same module
- **Связи (вызовы):** raises, register_local_external, str, hasattr
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_duplicate_local()`

#### `test_stl_bind_local`
- **Сигнатура:** `test_stl_bind_local()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** append, LocalVec, LocalType, NonLocalVec, NonLocalVec2, NonLocalType
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_stl_bind_local()`

#### `test_stl_bind_global`
- **Сигнатура:** `test_stl_bind_global()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** raises, register_nonlocal_map, str, register_nonlocal_vec, register_nonlocal_map2
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_stl_bind_global()`

#### `test_mixed_local_global`
- **Сигнатура:** `test_mixed_local_global()`
- **Приватная:** нет
- **Описание:** Local types take precedence over globally registered types: a module with a `module_local`
- **Связи (вызовы):** register_mixed_global, register_mixed_local, append, register_mixed_global_local, register_mixed_local_global, MixedGlobalLocal
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_mixed_local_global()`

#### `test_internal_locals_differ`
- **Сигнатура:** `test_internal_locals_differ()`
- **Приватная:** нет
- **Описание:** Makes sure the internal local type map differs across the two modules
- **Связи (вызовы):** local_cpp_types_addr
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_internal_locals_differ()`

#### `test_stl_caster_vs_stl_bind`
- **Сигнатура:** `test_stl_caster_vs_stl_bind(msg)`
- **Приватная:** нет
- **Описание:** One module uses a generic vector caster from `<pybind11/stl.h>` while the other
- **Связи (вызовы):** VectorInt, load_vector_via_caster, load_vector_via_binding, raises, msg
- **Аргументы:**
  - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
- **Пример:** `test_stl_caster_vs_stl_bind(...)`

#### `test_cross_module_calls`
- **Сигнатура:** `test_cross_module_calls()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** LocalVec, append, Cat, Dog, MixGL, LocalType
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_cross_module_calls()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.tests.test_methods_and_attributes` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/tests/test_methods_and_attributes.py`)

### Функции

#### `test_methods_and_attributes`
- **Сигнатура:** `test_methods_and_attributes()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** ExampleMandA, add1, add2, add3, add4, add5
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_methods_and_attributes()`

#### `test_copy_method`
- **Сигнатура:** `test_copy_method()`
- **Приватная:** нет
- **Описание:** Issue #443: calling copied methods fails in Python 3
- **Связи (вызовы):** ExampleMandA, add2, add2b, add2c, add2d
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_copy_method()`

#### `test_properties`
- **Сигнатура:** `test_properties()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** TestProperties, raises, str
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_properties()`

#### `test_static_properties`
- **Сигнатура:** `test_static_properties()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** TestProperties, raises, str, TestPropertiesOverride
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_static_properties()`

#### `test_static_cls`
- **Сигнатура:** `test_static_cls()`
- **Приватная:** нет
- **Описание:** Static property getter and setters expect the type object as the their only argument
- **Связи (вызовы):** TestProperties
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_static_cls()`

#### `test_metaclass_override`
- **Сигнатура:** `test_metaclass_override()`
- **Приватная:** нет
- **Описание:** Overriding pybind11's default metaclass changes the behavior of `static_property`
- **Связи (вызовы):** isinstance, type
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_metaclass_override()`

#### `test_no_mixed_overloads`
- **Сигнатура:** `test_no_mixed_overloads()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** raises, add_mixed_overloads1, str, add_mixed_overloads2
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_no_mixed_overloads()`

#### `test_property_return_value_policies`
- **Сигнатура:** `test_property_return_value_policies(access)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** parametrize, getattr, startswith, TestPropRVP
- **Аргументы:**
  - `access`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `access`.
- **Пример:** `test_property_return_value_policies(...)`

#### `test_property_rvalue_policy`
- **Сигнатура:** `test_property_rvalue_policy()`
- **Приватная:** нет
- **Описание:** When returning an rvalue, the return value policy is automatically changed from
- **Связи (вызовы):** TestPropRVP
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_property_rvalue_policy()`

#### `test_dynamic_attributes`
- **Сигнатура:** `test_dynamic_attributes()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** DynamicClass, hasattr, get, dir, raises, str
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_dynamic_attributes()`

#### `test_cyclic_gc`
- **Сигнатура:** `test_cyclic_gc()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** DynamicClass, get, alive
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_cyclic_gc()`

#### `test_noconvert_args`
- **Сигнатура:** `test_noconvert_args(msg)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** ArgInspector, msg, h, floats_preferred, floats_only, raises
- **Аргументы:**
  - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
- **Пример:** `test_noconvert_args(...)`

#### `test_bad_arg_default`
- **Сигнатура:** `test_bad_arg_default(msg)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** raises, bad_arg_def_named, msg, bad_arg_def_unnamed
- **Аргументы:**
  - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
- **Пример:** `test_bad_arg_default(...)`

#### `test_accepts_none`
- **Сигнатура:** `test_accepts_none(msg)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** NoneTester, no_none1, no_none2, no_none3, no_none4, no_none5
- **Аргументы:**
  - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
- **Пример:** `test_accepts_none(...)`

#### `test_str_issue`
- **Сигнатура:** `test_str_issue(msg)`
- **Приватная:** нет
- **Описание:** #283: __str__ called on uninitialized instance when constructor arguments invalid
- **Связи (вызовы):** str, raises, msg, StrIssue
- **Аргументы:**
  - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
- **Пример:** `test_str_issue(...)`

#### `test_unregistered_base_implementations`
- **Сигнатура:** `test_unregistered_base_implementations()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** RegisteredDerived, do_nothing, increase_value, sum
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_unregistered_base_implementations()`

#### `test_custom_caster_destruction`
- **Сигнатура:** `test_custom_caster_destruction()`
- **Приватная:** нет
- **Описание:** Tests that returning a pointer to a type that gets converted with a custom type caster gets
- **Связи (вызовы):** destruction_tester_cstats, custom_caster_no_destroy, custom_caster_destroy, custom_caster_destroy_const, alive
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_custom_caster_destruction()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.tests.test_modules` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/tests/test_modules.py`)

### Функции

#### `test_nested_modules`
- **Сигнатура:** `test_nested_modules()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** submodule_func
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_nested_modules()`

#### `test_reference_internal`
- **Сигнатура:** `test_reference_internal()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** B, A, str, get, alive, values
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_reference_internal()`

#### `test_importing`
- **Сигнатура:** `test_importing()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** str, OD
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_importing()`

#### `test_pydoc`
- **Сигнатура:** `test_pydoc()`
- **Приватная:** нет
- **Описание:** Pydoc needs to be able to provide help() for everything inside a pybind11 module
- **Связи (вызовы):** docmodule
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_pydoc()`

#### `test_duplicate_registration`
- **Сигнатура:** `test_duplicate_registration()`
- **Приватная:** нет
- **Описание:** Registering two things with the same name
- **Связи (вызовы):** duplicate_registration
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_duplicate_registration()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.tests.test_multiple_inheritance` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/tests/test_multiple_inheritance.py`)

### Функции

#### `test_multiple_inheritance_cpp`
- **Сигнатура:** `test_multiple_inheritance_cpp()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** MIType, foo, bar
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_multiple_inheritance_cpp()`

#### `test_multiple_inheritance_mix1`
- **Сигнатура:** `test_multiple_inheritance_mix1()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** MITypePy, foo, bar, __init__
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_multiple_inheritance_mix1()`

#### `test_multiple_inheritance_mix2`
- **Сигнатура:** `test_multiple_inheritance_mix2()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** MITypePy, foo, bar, __init__
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_multiple_inheritance_mix2()`

#### `test_multiple_inheritance_python`
- **Сигнатура:** `test_multiple_inheritance_python()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** MI1, MI2, MI3, MI4, MI5, MI6
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_multiple_inheritance_python()`

#### `test_multiple_inheritance_python_many_bases`
- **Сигнатура:** `test_multiple_inheritance_python_many_bases()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** MIMany14, range, MIMany916, MIMany19, MIMany117, __init__
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_multiple_inheritance_python_many_bases()`

#### `test_multiple_inheritance_virtbase`
- **Сигнатура:** `test_multiple_inheritance_virtbase()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** MITypePy, bar, bar_base2a, bar_base2a_sharedptr, __init__
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_multiple_inheritance_virtbase()`

#### `test_mi_static_properties`
- **Сигнатура:** `test_mi_static_properties()`
- **Приватная:** нет
- **Описание:** Mixing bases with and without static properties should be possible
- **Связи (вызовы):** VanillaStaticMix1, VanillaStaticMix2, vanilla, static_func1, static_func2, static_func
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_mi_static_properties()`

#### `test_mi_dynamic_attributes`
- **Сигнатура:** `test_mi_dynamic_attributes()`
- **Приватная:** нет
- **Описание:** Mixing bases with and without dynamic attribute support
- **Связи (вызовы):** VanillaDictMix1, VanillaDictMix2
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_mi_dynamic_attributes()`

#### `test_mi_unaligned_base`
- **Сигнатура:** `test_mi_unaligned_base()`
- **Приватная:** нет
- **Описание:** Returning an offset (non-first MI) base class pointer should recognize the instance
- **Связи (вызовы):** detail_reg_inst, I801C, I801D, i801b1_c, i801b2_c, i801b1_d
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_mi_unaligned_base()`

#### `test_mi_base_return`
- **Сигнатура:** `test_mi_base_return()`
- **Приватная:** нет
- **Описание:** Tests returning an offset (non-first MI) base class pointer to a derived instance
- **Связи (вызовы):** detail_reg_inst, i801c_b1, i801d_b1, i801c_b2, i801d_b2, i801e_c
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_mi_base_return()`

#### `test_diamond_inheritance`
- **Сигнатура:** `test_diamond_inheritance()`
- **Приватная:** нет
- **Описание:** Tests that diamond inheritance works as expected (issue #959)
- **Связи (вызовы):** D, c0, c1, b
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_diamond_inheritance()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.tests.test_numpy_array` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/tests/test_numpy_array.py`)

### Функции

#### `test_dtypes`
- **Сигнатура:** `test_dtypes()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** get_platform_dtype_size_checks, get_concrete_dtype_checks, print, format
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_dtypes()`

#### `arr`
- **Сигнатура:** `arr()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** fixture, array
- **Аргументы:**
  - нет аргументов
- **Пример:** `arr()`

#### `test_array_attributes`
- **Сигнатура:** `test_array_attributes()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** array, all, writeable, owndata, view, ndim
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_array_attributes()`

#### `test_index_offset`
- **Сигнатура:** `test_index_offset(arr, args, ret)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** parametrize, index_at, index_at_t, offset_at, offset_at_t
- **Аргументы:**
  - `arr`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `arr`.
  - `args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `args`.
  - `ret`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `ret`.
- **Пример:** `test_index_offset(..., ..., ...)`

#### `test_dim_check_fail`
- **Сигнатура:** `test_dim_check_fail(arr)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** raises, func, str
- **Аргументы:**
  - `arr`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `arr`.
- **Пример:** `test_dim_check_fail(...)`

#### `test_data`
- **Сигнатура:** `test_data(arr, args, ret)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** parametrize, all, data_t, data
- **Аргументы:**
  - `arr`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `arr`.
  - `args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `args`.
  - `ret`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `ret`.
- **Пример:** `test_data(..., ..., ...)`

#### `test_at_fail`
- **Сигнатура:** `test_at_fail(arr, dim)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** parametrize, raises, func, str, format
- **Аргументы:**
  - `arr`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `arr`.
  - `dim`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `dim`.
- **Пример:** `test_at_fail(..., ...)`

#### `test_at`
- **Сигнатура:** `test_at(arr)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** all, at_t, ravel, mutate_at_t
- **Аргументы:**
  - `arr`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `arr`.
- **Пример:** `test_at(...)`

#### `test_mutate_readonly`
- **Сигнатура:** `test_mutate_readonly(arr)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** raises, func, str
- **Аргументы:**
  - `arr`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `arr`.
- **Пример:** `test_mutate_readonly(...)`

#### `test_mutate_data`
- **Сигнатура:** `test_mutate_data(arr)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** all, ravel, mutate_data, mutate_data_t
- **Аргументы:**
  - `arr`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `arr`.
- **Пример:** `test_mutate_data(...)`

#### `test_bounds_check`
- **Сигнатура:** `test_bounds_check(arr)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** raises, func, str
- **Аргументы:**
  - `arr`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `arr`.
- **Пример:** `test_bounds_check(...)`

#### `test_make_c_f_array`
- **Сигнатура:** `test_make_c_f_array()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** make_c_array, make_f_array
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_make_c_f_array()`

#### `test_make_empty_shaped_array`
- **Сигнатура:** `test_make_empty_shaped_array()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** make_empty_shaped_array, scalar_int
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_make_empty_shaped_array()`

#### `test_wrap`
- **Сигнатура:** `test_wrap()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** array, wrap, assert_references, random, transpose, diagonal
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_wrap()`

#### `test_numpy_view`
- **Сигнатура:** `test_numpy_view(capture)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** ArrayClass, numpy_view, all, gc_collect, array
- **Аргументы:**
  - `capture`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `capture`.
- **Пример:** `test_numpy_view(...)`

#### `test_cast_numpy_int64_to_uint64`
- **Сигнатура:** `test_cast_numpy_int64_to_uint64()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** function_taking_uint64, uint64
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_cast_numpy_int64_to_uint64()`

#### `test_isinstance`
- **Сигнатура:** `test_isinstance()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** isinstance_untyped, isinstance_typed, array
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_isinstance()`

#### `test_constructors`
- **Сигнатура:** `test_constructors()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** default_constructors, values, converting_constructors, assert_array_equal, array
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_constructors()`

#### `test_overload_resolution`
- **Сигнатура:** `test_overload_resolution(msg)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** overloaded, raises, msg, overloaded2, overloaded3, overloaded4
- **Аргументы:**
  - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
- **Пример:** `test_overload_resolution(...)`

#### `test_greedy_string_overload`
- **Сигнатура:** `test_greedy_string_overload()`
- **Приватная:** нет
- **Описание:** Tests fix for #685 - ndarray shouldn't go to std::string overload
- **Связи (вызовы):** issue685, array
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_greedy_string_overload()`

#### `test_array_unchecked_fixed_dims`
- **Сигнатура:** `test_array_unchecked_fixed_dims(msg)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** array, proxy_add2, all, ndarray, transpose, raises
- **Аргументы:**
  - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
- **Пример:** `test_array_unchecked_fixed_dims(...)`

#### `test_array_unchecked_dyn_dims`
- **Сигнатура:** `test_array_unchecked_dyn_dims(msg)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** array, proxy_add2_dyn, all, ndarray, proxy_auxiliaries2_dyn, array_auxiliaries2
- **Аргументы:**
  - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
- **Пример:** `test_array_unchecked_dyn_dims(...)`

#### `test_array_failure`
- **Сигнатура:** `test_array_failure()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** raises, array_fail_test, str, array_t_fail_test, array_fail_test_negative_size
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_array_failure()`

#### `test_initializer_list`
- **Сигнатура:** `test_initializer_list()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** array_initializer_list1, array_initializer_list2, array_initializer_list3, array_initializer_list4
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_initializer_list()`

#### `test_array_resize`
- **Сигнатура:** `test_array_resize(msg)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** array, array_reshape2, all, array_resize3, transpose, startswith
- **Аргументы:**
  - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
- **Пример:** `test_array_resize(...)`

#### `test_array_create_and_resize`
- **Сигнатура:** `test_array_create_and_resize(msg)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** create_and_resize, all
- **Аргументы:**
  - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
- **Пример:** `test_array_create_and_resize(...)`

#### `test_index_using_ellipsis`
- **Сигнатура:** `test_index_using_ellipsis()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** index_using_ellipsis, zeros
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_index_using_ellipsis()`

#### `test_dtype_refcount_leak`
- **Сигнатура:** `test_dtype_refcount_leak()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** dtype, array, getrefcount, ndim
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_dtype_refcount_leak()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.tests.test_numpy_dtypes` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/tests/test_numpy_dtypes.py`)

### Функции

#### `simple_dtype`
- **Сигнатура:** `simple_dtype()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** fixture, dtype, format
- **Аргументы:**
  - нет аргументов
- **Пример:** `simple_dtype()`

#### `packed_dtype`
- **Сигнатура:** `packed_dtype()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** fixture, dtype
- **Аргументы:**
  - нет аргументов
- **Пример:** `packed_dtype()`

#### `dt_fmt`
- **Сигнатура:** `dt_fmt()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** не выявлены
- **Аргументы:**
  - нет аргументов
- **Пример:** `dt_fmt()`

#### `simple_dtype_fmt`
- **Сигнатура:** `simple_dtype_fmt()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** dtype, format, dt_fmt
- **Аргументы:**
  - нет аргументов
- **Пример:** `simple_dtype_fmt()`

#### `packed_dtype_fmt`
- **Сигнатура:** `packed_dtype_fmt()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** format, dtype
- **Аргументы:**
  - нет аргументов
- **Пример:** `packed_dtype_fmt()`

#### `partial_ld_offset`
- **Сигнатура:** `partial_ld_offset()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** dtype
- **Аргументы:**
  - нет аргументов
- **Пример:** `partial_ld_offset()`

#### `partial_dtype_fmt`
- **Сигнатура:** `partial_dtype_fmt()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** dtype, partial_ld_offset, format, dt_fmt
- **Аргументы:**
  - нет аргументов
- **Пример:** `partial_dtype_fmt()`

#### `partial_nested_fmt`
- **Сигнатура:** `partial_nested_fmt()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** dtype, partial_ld_offset, format, partial_dtype_fmt
- **Аргументы:**
  - нет аргументов
- **Пример:** `partial_nested_fmt()`

#### `assert_equal`
- **Сигнатура:** `assert_equal(actual, expected_data, expected_dtype)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** assert_equal, array
- **Аргументы:**
  - `actual`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `actual`.
  - `expected_data`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `expected_data`.
  - `expected_dtype`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `expected_dtype`.
- **Пример(ы) из репозитория:**
  - `np.testing.assert_equal(actual, np.array(expected_data, dtype=expected_dtype))` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_numpy_dtypes.py:65`)
  - `np.testing.assert_equal(arr['a'], m.create_rec_partial(3))` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_numpy_dtypes.py:182`)

#### `test_format_descriptors`
- **Сигнатура:** `test_format_descriptors()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** match, dtype, str, raises, get_format_unbound, max
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_format_descriptors()`

#### `test_dtype`
- **Сигнатура:** `test_dtype(simple_dtype)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** dtype, print_dtypes, test_dtype_ctors, test_dtype_methods, trailing_padding_dtype, buffer_to_dtype
- **Аргументы:**
  - `simple_dtype`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `simple_dtype`.
- **Пример:** `test_dtype(...)`

#### `test_recarray`
- **Сигнатура:** `test_recarray(simple_dtype, packed_dtype)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** dtype, create_rec_nested, assert_equal, create_rec_partial, create_rec_partial_nested, func
- **Аргументы:**
  - `simple_dtype`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `simple_dtype`.
  - `packed_dtype`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `packed_dtype`.
- **Пример:** `test_recarray(..., ...)`

#### `test_array_constructors`
- **Сигнатура:** `test_array_constructors()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** arange, range, assert_array_equal, test_array_ctors, reshape
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_array_constructors()`

#### `test_string_array`
- **Сигнатура:** `test_string_array()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** create_string_array, str, print_string_array, tolist
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_string_array()`

#### `test_array_array`
- **Сигнатура:** `test_array_array()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** create_array_array, str, format, print_array_array, tolist
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_array_array()`

#### `test_enum_array`
- **Сигнатура:** `test_enum_array()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** create_enum_array, dtype, print_enum_array, tolist
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_enum_array()`

#### `test_complex_array`
- **Сигнатура:** `test_complex_array()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** create_complex_array, dtype, print_complex_array, tolist
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_complex_array()`

#### `test_signature`
- **Сигнатура:** `test_signature(doc)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** doc
- **Аргументы:**
  - `doc`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `doc`.
- **Пример:** `test_signature(...)`

#### `test_scalar_conversion`
- **Сигнатура:** `test_scalar_conversion()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** enumerate, create_rec_simple, create_rec_packed, create_rec_nested, create_enum_array, raises
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_scalar_conversion()`

#### `test_register_dtype`
- **Сигнатура:** `test_register_dtype()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** raises, register_dtype, str
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_register_dtype()`

#### `test_str_leak`
- **Сигнатура:** `test_str_leak()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** gc_collect, getrefcount, dtype_wrapper, dtype
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_str_leak()`

#### `test_compare_buffer_info`
- **Сигнатура:** `test_compare_buffer_info()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** all, compare_buffer_info
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_compare_buffer_info()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.tests.test_numpy_vectorize` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/tests/test_numpy_vectorize.py`)

### Функции

#### `test_vectorize`
- **Сигнатура:** `test_vectorize(capture)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** isclose, vectorized_func3, array, allclose, f
- **Аргументы:**
  - `capture`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `capture`.
- **Пример:** `test_vectorize(...)`

#### `test_type_selection`
- **Сигнатура:** `test_type_selection()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** selective_func, array
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_type_selection()`

#### `test_docs`
- **Сигнатура:** `test_docs(doc)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** doc
- **Аргументы:**
  - `doc`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `doc`.
- **Пример:** `test_docs(...)`

#### `test_trivial_broadcasting`
- **Сигнатура:** `test_trivial_broadcasting()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** array, vectorized_is_trivial, vectorized_func
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_trivial_broadcasting()`

#### `test_passthrough_arguments`
- **Сигнатура:** `test_passthrough_arguments(doc)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** array, all, doc, vec_passthrough, join, NonPODClass
- **Аргументы:**
  - `doc`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `doc`.
- **Пример:** `test_passthrough_arguments(...)`

#### `test_method_vectorization`
- **Сигнатура:** `test_method_vectorization()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** VectorizeTestClass, array, all, method
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_method_vectorization()`

#### `test_array_collapse`
- **Сигнатура:** `test_array_collapse()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** vectorized_func, isinstance, array
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_array_collapse()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.tests.test_opaque_types` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/tests/test_opaque_types.py`)

### Функции

#### `test_string_list`
- **Сигнатура:** `test_string_list()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** StringList, push_back, enumerate, pop_back, ClassWithSTLVecProperty, print_opaque_list
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_string_list()`

#### `test_pointers`
- **Сигнатура:** `test_pointers(msg)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** alive, get_void_ptr_value, return_unique_ptr, UserType, raises, msg
- **Аргументы:**
  - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
- **Пример:** `test_pointers(...)`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.tests.test_operator_overloading` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/tests/test_operator_overloading.py`)

### Функции

#### `test_operator_overloading`
- **Сигнатура:** `test_operator_overloading()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** Vector2, Vector, get, str, hash, alive
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_operator_overloading()`

#### `test_operators_notimplemented`
- **Сигнатура:** `test_operators_notimplemented()`
- **Приватная:** нет
- **Описание:** #393: need to return NotSupported to ensure correct arithmetic operator behavior
- **Связи (вызовы):** C1, C2
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_operators_notimplemented()`

#### `test_nested`
- **Сигнатура:** `test_nested()`
- **Приватная:** нет
- **Описание:** #328: first member in a class can't be used in operators
- **Связи (вызовы):** NestA, NestB, NestC, as_base, gc_collect, get_NestA
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_nested()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.tests.test_pickling` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/tests/test_pickling.py`)

### Функции

#### `test_roundtrip`
- **Сигнатура:** `test_roundtrip(cls_name)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** parametrize, getattr, cls, setExtra1, setExtra2, dumps
- **Аргументы:**
  - `cls_name`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `cls_name`.
- **Пример:** `test_roundtrip(...)`

#### `test_roundtrip_with_dict`
- **Сигнатура:** `test_roundtrip_with_dict(cls_name)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** parametrize, getattr, cls, dumps, loads
- **Аргументы:**
  - `cls_name`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `cls_name`.
- **Пример:** `test_roundtrip_with_dict(...)`

#### `test_enum_pickle`
- **Сигнатура:** `test_enum_pickle()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** dumps, loads
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_enum_pickle()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.tests.test_pytypes` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/tests/test_pytypes.py`)

### Функции

#### `test_list`
- **Сигнатура:** `test_list(capture, doc)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** get_list, append, print_list, doc
- **Аргументы:**
  - `capture`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `capture`.
  - `doc`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `doc`.
- **Пример:** `test_list(..., ...)`

#### `test_set`
- **Сигнатура:** `test_set(capture, doc)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** get_set, set_contains, add, print_set, doc, set
- **Аргументы:**
  - `capture`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `capture`.
  - `doc`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `doc`.
- **Пример:** `test_set(..., ...)`

#### `test_dict`
- **Сигнатура:** `test_dict(capture, doc)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** get_dict, dict_contains, print_dict, doc, dict_keyword_constructor
- **Аргументы:**
  - `capture`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `capture`.
  - `doc`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `doc`.
- **Пример:** `test_dict(..., ...)`

#### `test_str`
- **Сигнатура:** `test_str(doc)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** str_format, decode, doc, str_from_object, repr_from_object, A
- **Аргументы:**
  - `doc`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `doc`.
- **Пример:** `test_str(...)`

#### `test_bytes`
- **Сигнатура:** `test_bytes(doc)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** decode, doc, format, bytes_from_string, bytes_from_str
- **Аргументы:**
  - `doc`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `doc`.
- **Пример:** `test_bytes(...)`

#### `test_capsule`
- **Сигнатура:** `test_capsule(capture)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** gc_collect, return_capsule_with_destructor, return_capsule_with_destructor_2, return_capsule_with_name_and_destructor
- **Аргументы:**
  - `capture`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `capture`.
- **Пример:** `test_capsule(...)`

#### `test_accessors`
- **Сигнатура:** `test_accessors()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** accessor_api, all, accessor_assignment, SubTestObject, TestObject, tuple_accessor
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_accessors()`

#### `test_constructors`
- **Сигнатура:** `test_constructors()`
- **Приватная:** нет
- **Описание:** C++ default and converting constructors are equivalent to type calls in Python
- **Связи (вызовы):** converting_constructors, cast_functions, t, default_constructors, range, k
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_constructors()`

#### `test_implicit_casting`
- **Сигнатура:** `test_implicit_casting()`
- **Приватная:** нет
- **Описание:** Tests implicit casting when assigning or appending to dicts and lists.
- **Связи (вызовы):** get_implicit_casting
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_implicit_casting()`

#### `test_print`
- **Сигнатура:** `test_print(capture)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** print_function, raises, print_failure, str
- **Аргументы:**
  - `capture`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `capture`.
- **Пример:** `test_print(...)`

#### `test_hash`
- **Сигнатура:** `test_hash()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** hash_function, raises, Hashable, Unhashable
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_hash()`

#### `test_number_protocol`
- **Сигнатура:** `test_number_protocol()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** test_number_protocol
- **Аргументы:**
  - нет аргументов
- **Пример(ы) из репозитория:**
  - `assert m.test_number_protocol(a, b) == li` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_pytypes.py:258`)
  - `assert m.test_number_protocol(a, b) == li` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/tests/test_pytypes.py:258`)

#### `test_list_slicing`
- **Сигнатура:** `test_list_slicing()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** list, range, test_list_slicing
- **Аргументы:**
  - нет аргументов
- **Пример(ы) из репозитория:**
  - `assert li[::2] == m.test_list_slicing(li)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_pytypes.py:263`)
  - `assert li[::2] == m.test_list_slicing(li)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/tests/test_pytypes.py:263`)


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.tests.test_sequences_and_iterators` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/tests/test_sequences_and_iterators.py`)

### Функции

#### `isclose`
- **Сигнатура:** `isclose(a, b, rel_tol=1e-05, abs_tol=0.0)`
- **Приватная:** нет
- **Описание:** Like math.isclose() from Python 3.5
- **Связи (вызовы):** abs, max
- **Аргументы:**
  - `a`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `a`.
  - `b`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `b`.
  - `rel_tol`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `rel_tol`.
  - `abs_tol`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `abs_tol`.
- **Пример(ы) из репозитория:**
  - `assert np.isclose(m.vectorized_func3(np.array(3 + 7j)), [6 + 14j])` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_numpy_vectorize.py:11`)
  - `assert np.isclose(f(1, 2, 3), 6)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_numpy_vectorize.py:15`)

#### `allclose`
- **Сигнатура:** `allclose(a_list, b_list, rel_tol=1e-05, abs_tol=0.0)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** all, isclose, zip
- **Аргументы:**
  - `a_list`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `a_list`.
  - `b_list`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `b_list`.
  - `rel_tol`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `rel_tol`.
  - `abs_tol`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `abs_tol`.
- **Пример(ы) из репозитория:**
  - `assert np.allclose(f(np.array([1, 3]), np.array([2, 4]), 3), [6, 36])` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_numpy_vectorize.py:21`)
  - `assert np.allclose(result, a * b * c)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_numpy_vectorize.py:31`)

#### `test_generalized_iterators`
- **Сигнатура:** `test_generalized_iterators()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** nonzero, range, nonzero_keys, list, IntPairs, raises
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_generalized_iterators()`

#### `test_sliceable`
- **Сигнатура:** `test_sliceable()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** Sliceable
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_sliceable()`

#### `test_sequence`
- **Сигнатура:** `test_sequence()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** get, Sequence, reversed, iter, range, allclose
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_sequence()`

#### `test_map_iterator`
- **Сигнатура:** `test_map_iterator()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** StringMap, items, iter, range, len, raises
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_map_iterator()`

#### `test_python_iterator_in_cpp`
- **Сигнатура:** `test_python_iterator_in_cpp()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** range, all, object_to_list, iterator_to_list, raises, str
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_python_iterator_in_cpp()`

#### `test_iterator_passthrough`
- **Сигнатура:** `test_iterator_passthrough()`
- **Приватная:** нет
- **Описание:** #181: iterator passthrough did not compile
- **Связи (вызовы):** list, iterator_passthrough, iter
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_iterator_passthrough()`

#### `test_iterator_rvp`
- **Сигнатура:** `test_iterator_rvp()`
- **Приватная:** нет
- **Описание:** #388: Can't make iterators via make_iterator() with different r/v policies
- **Связи (вызовы):** list, isinstance, make_iterator_1, make_iterator_2, type
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_iterator_rvp()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.tests.test_smart_ptr` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/tests/test_smart_ptr.py`)

### Функции

#### `test_smart_ptr`
- **Сигнатура:** `test_smart_ptr(capture)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** enumerate, get, zip, cstats_ref, print, alive
- **Аргументы:**
  - `capture`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `capture`.
- **Пример:** `test_smart_ptr(...)`

#### `test_smart_ptr_refcounting`
- **Сигнатура:** `test_smart_ptr_refcounting()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** test_object1_refcounting
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_smart_ptr_refcounting()`

#### `test_unique_nodelete`
- **Сигнатура:** `test_unique_nodelete()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** MyObject4, get, alive
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_unique_nodelete()`

#### `test_unique_nodelete4a`
- **Сигнатура:** `test_unique_nodelete4a()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** MyObject4a, get, alive
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_unique_nodelete4a()`

#### `test_unique_deleter`
- **Сигнатура:** `test_unique_deleter()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** MyObject4b, get, alive
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_unique_deleter()`

#### `test_large_holder`
- **Сигнатура:** `test_large_holder()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** MyObject5, get, alive
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_large_holder()`

#### `test_shared_ptr_and_references`
- **Сигнатура:** `test_shared_ptr_and_references()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** SharedPtrRef, get, set_ref, set_holder, alive, raises
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_shared_ptr_and_references()`

#### `test_shared_ptr_from_this_and_references`
- **Сигнатура:** `test_shared_ptr_from_this_and_references()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** SharedFromThisRef, get, set_ref, set_holder, alive, raises
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_shared_ptr_from_this_and_references()`

#### `test_move_only_holder`
- **Сигнатура:** `test_move_only_holder()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** make, get, alive
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_move_only_holder()`

#### `test_holder_with_addressof_operator`
- **Сигнатура:** `test_holder_with_addressof_operator()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** make, print_object_1, print_object_2, print_object_3, print_object_4, get
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_holder_with_addressof_operator()`

#### `test_move_only_holder_with_addressof_operator`
- **Сигнатура:** `test_move_only_holder_with_addressof_operator()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** make, print_object, get, alive
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_move_only_holder_with_addressof_operator()`

#### `test_smart_ptr_from_default`
- **Сигнатура:** `test_smart_ptr_from_default()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** HeldByDefaultHolder, raises, load_shared_ptr, str
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_smart_ptr_from_default()`

#### `test_shared_ptr_gc`
- **Сигнатура:** `test_shared_ptr_gc()`
- **Приватная:** нет
- **Описание:** #187: issue involving std::shared_ptr<> return value policy & garbage collection
- **Связи (вызовы):** ElementList, range, gc_collect, enumerate, add, get
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_shared_ptr_gc()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.tests.test_stl` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/tests/test_stl.py`)

### Функции

#### `test_vector`
- **Сигнатура:** `test_vector(doc)`
- **Приватная:** нет
- **Описание:** std::vector <-> list
- **Связи (вызовы):** cast_vector, append, load_vector, load_bool_vector, tuple, cast_bool_vector
- **Аргументы:**
  - `doc`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `doc`.
- **Пример:** `test_vector(...)`

#### `test_deque`
- **Сигнатура:** `test_deque(doc)`
- **Приватная:** нет
- **Описание:** std::deque <-> list
- **Связи (вызовы):** cast_deque, append, load_deque, tuple
- **Аргументы:**
  - `doc`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `doc`.
- **Пример:** `test_deque(...)`

#### `test_array`
- **Сигнатура:** `test_array(doc)`
- **Приватная:** нет
- **Описание:** std::array <-> list
- **Связи (вызовы):** cast_array, load_array, doc
- **Аргументы:**
  - `doc`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `doc`.
- **Пример:** `test_array(...)`

#### `test_valarray`
- **Сигнатура:** `test_valarray(doc)`
- **Приватная:** нет
- **Описание:** std::valarray <-> list
- **Связи (вызовы):** cast_valarray, load_valarray, doc
- **Аргументы:**
  - `doc`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `doc`.
- **Пример:** `test_valarray(...)`

#### `test_map`
- **Сигнатура:** `test_map(doc)`
- **Приватная:** нет
- **Описание:** std::map <-> dict
- **Связи (вызовы):** cast_map, load_map, doc
- **Аргументы:**
  - `doc`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `doc`.
- **Пример:** `test_map(...)`

#### `test_set`
- **Сигнатура:** `test_set(doc)`
- **Приватная:** нет
- **Описание:** std::set <-> set
- **Связи (вызовы):** cast_set, add, load_set, doc
- **Аргументы:**
  - `doc`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `doc`.
- **Пример:** `test_set(...)`

#### `test_recursive_casting`
- **Сигнатура:** `test_recursive_casting()`
- **Приватная:** нет
- **Описание:** Tests that stl casters preserve lvalue/rvalue context for container values
- **Связи (вызовы):** cast_unique_ptr_vector, cast_rv_vector, cast_lv_vector, cast_rv_array, cast_lv_array, cast_rv_map
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_recursive_casting()`

#### `test_move_out_container`
- **Сигнатура:** `test_move_out_container()`
- **Приватная:** нет
- **Описание:** Properties use the `reference_internal` policy by default. If the underlying function
- **Связи (вызовы):** MoveOutContainer
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_move_out_container()`

#### `test_optional`
- **Сигнатура:** `test_optional()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** skipif, raises, nodefer_none_optional, double_or_zero, half_or_none, test_nullopt
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_optional()`

#### `test_exp_optional`
- **Сигнатура:** `test_exp_optional()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** skipif, raises, double_or_zero_exp, half_or_none_exp, test_nullopt_exp, test_no_assign_exp
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_exp_optional()`

#### `test_variant`
- **Сигнатура:** `test_variant(doc)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** skipif, load_variant, load_variant_2pass, cast_variant, doc, hasattr
- **Аргументы:**
  - `doc`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `doc`.
- **Пример:** `test_variant(...)`

#### `test_vec_of_reference_wrapper`
- **Сигнатура:** `test_vec_of_reference_wrapper()`
- **Приватная:** нет
- **Описание:** #171: Can't return reference wrappers (or STL structures containing them)
- **Связи (вызовы):** str, return_vec_of_reference_wrapper, UserType
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_vec_of_reference_wrapper()`

#### `test_stl_pass_by_pointer`
- **Сигнатура:** `test_stl_pass_by_pointer(msg)`
- **Приватная:** нет
- **Описание:** Passing nullptr or None to an STL container pointer is not expected to work
- **Связи (вызовы):** raises, stl_pass_by_pointer, msg
- **Аргументы:**
  - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
- **Пример:** `test_stl_pass_by_pointer(...)`

#### `test_missing_header_message`
- **Сигнатура:** `test_missing_header_message()`
- **Приватная:** нет
- **Описание:** Trying convert `list` to a `std::vector`, or vice versa, without including
- **Связи (вызовы):** raises, missing_header_arg, str, missing_header_return
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_missing_header_message()`

#### `test_function_with_string_and_vector_string_arg`
- **Сигнатура:** `test_function_with_string_and_vector_string_arg()`
- **Приватная:** нет
- **Описание:** Check if a string is NOT implicitly converted to a list, which was the
- **Связи (вызовы):** func_with_string_or_vector_string_arg_overload
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_function_with_string_and_vector_string_arg()`

#### `test_stl_ownership`
- **Сигнатура:** `test_stl_ownership()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** get, test_stl_ownership, alive, len
- **Аргументы:**
  - нет аргументов
- **Пример(ы) из репозитория:**
  - `r = m.test_stl_ownership()` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_stl.py:226`)
  - `r = m.test_stl_ownership()` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/tests/test_stl.py:226`)

#### `test_array_cast_sequence`
- **Сигнатура:** `test_array_cast_sequence()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** array_cast_sequence
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_array_cast_sequence()`

#### `test_issue_1561`
- **Сигнатура:** `test_issue_1561()`
- **Приватная:** нет
- **Описание:** check fix for issue #1561
- **Связи (вызовы):** Issue1561Outer, Issue1561Inner
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_issue_1561()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.tests.test_stl_binders` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/tests/test_stl_binders.py`)

### Функции

#### `test_vector_int`
- **Сигнатура:** `test_vector_int()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** VectorInt, append, insert, extend, len, bool
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_vector_int()`

#### `test_vector_buffer`
- **Сигнатура:** `test_vector_buffer()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** bytearray, VectorUChar, memoryview, raises, create_undeclstruct, str
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_vector_buffer()`

#### `test_vector_buffer_numpy`
- **Сигнатура:** `test_vector_buffer_numpy()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** array, VectorInt, asarray, get_vectorstruct, VectorStruct, raises
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_vector_buffer_numpy()`

#### `test_vector_bool`
- **Сигнатура:** `test_vector_bool()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** VectorBool, range, append, str
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_vector_bool()`

#### `test_vector_custom`
- **Сигнатура:** `test_vector_custom()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** VectorEl, append, VectorVectorEl, El, str
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_vector_custom()`

#### `test_map_string_double`
- **Сигнатура:** `test_map_string_double()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** MapStringDouble, UnorderedMapStringDouble, list, str, sorted, items
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_map_string_double()`

#### `test_map_string_double_const`
- **Сигнатура:** `test_map_string_double_const()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** MapStringDoubleConst, UnorderedMapStringDoubleConst, str
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_map_string_double_const()`

#### `test_noncopyable_containers`
- **Сигнатура:** `test_noncopyable_containers()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** get_vnc, range, enumerate, get_dnc, get_mnc, items
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_noncopyable_containers()`

#### `test_map_delitem`
- **Сигнатура:** `test_map_delitem()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** MapStringDouble, UnorderedMapStringDouble, list, sorted, items
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_map_delitem()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.tests.test_tagbased_polymorphic` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/tests/test_tagbased_polymorphic.py`)

### Функции

#### `test_downcast`
- **Сигнатура:** `test_downcast()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** create_zoo, type, bark, purr
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_downcast()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.tests.test_union` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/tests/test_union.py`)

### Функции

#### `test_union`
- **Сигнатура:** `test_union()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** TestUnion
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_union()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.tests.test_virtual_functions` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/tests/test_virtual_functions.py`)

### Функции

#### `test_override`
- **Сигнатура:** `test_override(capture, msg)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** ExampleVirt, ExtendedExampleVirt, ExtendedExampleVirt2, get, raises, runExampleVirtVirtual
- **Аргументы:**
  - `capture`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `capture`.
  - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
- **Пример:** `test_override(..., ...)`

#### `test_alias_delay_initialization1`
- **Сигнатура:** `test_alias_delay_initialization1(capture)`
- **Приватная:** нет
- **Описание:** `A` only initializes its trampoline class when we inherit from it
- **Связи (вызовы):** A, call_f, gc_collect, B, __init__, print
- **Аргументы:**
  - `capture`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `capture`.
- **Пример:** `test_alias_delay_initialization1(...)`

#### `test_alias_delay_initialization2`
- **Сигнатура:** `test_alias_delay_initialization2(capture)`
- **Приватная:** нет
- **Описание:** `A2`, unlike the above, is configured to always initialize the alias
- **Связи (вызовы):** A2, call_f, gc_collect, B2, __init__, print
- **Аргументы:**
  - `capture`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `capture`.
- **Пример:** `test_alias_delay_initialization2(...)`

#### `test_move_support`
- **Сигнатура:** `test_move_support()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** skipif, NCVirtExt, NCVirtExt2, get, print_nc, print_movable
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_move_support()`

#### `test_dispatch_issue`
- **Сигнатура:** `test_dispatch_issue(msg)`
- **Приватная:** нет
- **Описание:** #159: virtual function dispatch has problems with similar-named functions
- **Связи (вызовы):** PyClass2, dispatch_issue_go, PyClass1, raises, dispatch, msg
- **Аргументы:**
  - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
- **Пример:** `test_dispatch_issue(...)`

#### `test_override_ref`
- **Сигнатура:** `test_override_ref()`
- **Приватная:** нет
- **Описание:** #392/397: overriding reference-returning functions
- **Связи (вызовы):** OverrideTest, A_ref, str_value, A_value
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_override_ref()`

#### `test_inherited_virtuals`
- **Сигнатура:** `test_inherited_virtuals()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** AR, AT, CR, CT, CCR, CCT
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_inherited_virtuals()`

#### `test_issue_1454`
- **Сигнатура:** `test_issue_1454()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** test_gil, test_gil_from_thread
- **Аргументы:**
  - нет аргументов
- **Пример:** `test_issue_1454()`


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.tools.libsize` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/tools/libsize.py`)


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.decoder.ubuntu.src.pybind11.tools.mkdoc` (`examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/tools/mkdoc.py`)

### Функции

#### `d`
- **Сигнатура:** `d(s)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** isinstance, decode
- **Аргументы:**
  - `s`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `s`.
- **Пример:** `d(...)`

#### `sanitize_name`
- **Сигнатура:** `sanitize_name(name)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** sub, items, join, replace, isalnum
- **Аргументы:**
  - `name`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `name`.
- **Пример:** `sanitize_name(...)`

#### `process_comment`
- **Сигнатура:** `process_comment(comment)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** float, splitlines, sub, items, replace, TextWrapper
- **Аргументы:**
  - `comment`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `comment`.
- **Пример:** `process_comment(...)`

#### `extract`
- **Сигнатура:** `extract(filename, node, prefix, output)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** get_children, process_comment, samefile, d, extract, len
- **Аргументы:**
  - `filename`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `filename`.
  - `node`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `node`.
  - `prefix`: тип `не указан`; единицы `м`; допустимые значения `0..255`; параметр `prefix`.
  - `output`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `output`.
- **Пример:** `extract(..., ..., ..., ...)`

#### `read_args`
- **Сигнатура:** `read_args(args)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** extend, any, append, system, exists, startswith
- **Аргументы:**
  - `args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `args`.
- **Пример:** `read_args(...)`

#### `extract_all`
- **Сигнатура:** `extract_all(args)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** read_args, print, range, ExtractionThread, start, acquire
- **Аргументы:**
  - `args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `args`.
- **Пример:** `extract_all(...)`

#### `write_header`
- **Сигнатура:** `write_header(comments, out_file=sys.stdout)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** print, list, sorted
- **Аргументы:**
  - `comments`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `comments`.
  - `out_file`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `out_file`.
- **Пример:** `write_header(...)`

#### `mkdoc`
- **Сигнатура:** `mkdoc(args)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** list, enumerate, extract_all, startswith, write_header, remove
- **Аргументы:**
  - `args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `args`.
- **Пример:** `mkdoc(...)`

### Классы

### `NoFilenamesError`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** явно не определён.
- **Методы:**
  - отсутствуют

### `ExtractionThread`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self, filename, parameters, output)`
  - **Аргументы конструктора:**
    - `filename`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; инициализационный параметр `filename`.
    - `parameters`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `parameters`.
    - `output`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; инициализационный параметр `output`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, filename, parameters, output)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): __init__, acquire
    - Аргументы:
      - `filename`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `filename`.
      - `parameters`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `parameters`.
      - `output`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `output`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `run`
    - Сигнатура: `run(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): print, Index, parse, extract, release, clang_createIndex
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `myqr.run(words=info)` (из `examples/01_robot/05_sta_conn_helper.py:30`)
      - `multi_drone.run([tello_group, basic_task])` (из `examples/15_multi_robot/multi_drone/02_basic.py:35`)


## Модуль `examples.plaintext_sample_code.RoboMasterEP.stream.python_stream_liveview.liveview` (`examples/plaintext_sample_code/RoboMasterEP/stream/python_stream_liveview/liveview.py`)

### Функции

#### `test`
- **Сигнатура:** `test()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** RobotLiveview, signal, open, display, close
- **Аргументы:**
  - нет аргументов
- **Пример:** `test()`

### Классы

### `ConnectionType`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** явно не определён.
- **Методы:**
  - отсутствуют

### `RobotLiveview`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self, connection_type)`
  - **Аргументы конструктора:**
    - `connection_type`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; инициализационный параметр `connection_type`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, connection_type)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): RobotConnection, H264Decoder, disable_logging, opus_decoder, Thread, Queue
    - Аргументы:
      - `connection_type`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `connection_type`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `open`
    - Сигнатура: `open(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): update_robot_ip, open, get_robot_ip, print
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `img = Image.open(QRCODE_NAME)` (из `examples/01_robot/05_sta_conn_helper.py:32`)
      - `playing_stream = audio_player.open(format=pyaudio.paInt16,` (из `examples/04_camera/04_audio_without_playing.py:27`)
  - `close`
    - Сигнатура: `close(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): join, close
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `ep_robot.close()` (из `examples/01_robot/00_logger.py:34`)
      - `ep_robot.close()` (из `examples/01_robot/01_get_version.py:27`)
  - `display`
    - Сигнатура: `display(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): command, sleep, start, print
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `robot.display()` (из `examples/plaintext_sample_code/RoboMasterEP/stream/python_stream_liveview/liveview.py:203`)
  - `command`
    - Сигнатура: `command(self, msg)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): send_data
    - Аргументы:
      - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
    - Пример(ы) из репозитория:
      - `self.command('command')` (из `examples/plaintext_sample_code/RoboMasterEP/stream/python_stream_liveview/liveview.py:76`)
      - `self.command('audio on')` (из `examples/plaintext_sample_code/RoboMasterEP/stream/python_stream_liveview/liveview.py:78`)
  - `_h264_decode` (приватный)
    - Сигнатура: `_h264_decode(self, packet_data)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): decode, fromstring, reshape, append, len, int
    - Аргументы:
      - `packet_data`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `packet_data`.
    - Пример(ы) из репозитория:
      - `for frame in self._h264_decode(package_data):` (из `examples/plaintext_sample_code/RoboMasterEP/stream/python_stream_liveview/liveview.py:120`)
  - `_video_decoder_task` (приватный)
    - Сигнатура: `_video_decoder_task(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): start_video_recv, stop_video_recv, recv_video_data, len, _h264_decode, put
    - Аргументы:
      - нет аргументов
    - Пример: `obj._video_decoder_task()`
  - `_video_display_task` (приватный)
    - Сигнатура: `_video_display_task(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): fromarray, cvtColor, imshow, waitKey, get, array
    - Аргументы:
      - нет аргументов
    - Пример: `obj._video_display_task()`
  - `_audio_decoder_task` (приватный)
    - Сигнатура: `_audio_decoder_task(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): start_audio_recv, stop_audio_recv, recv_audio_data, len, decode, put
    - Аргументы:
      - нет аргументов
    - Пример: `obj._audio_decoder_task()`
  - `_audio_display_task` (приватный)
    - Сигнатура: `_audio_display_task(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): PyAudio, open, stop_stream, close, write, get
    - Аргументы:
      - нет аргументов
    - Пример: `obj._audio_display_task()`


## Модуль `src.multi_robomaster.__init__` (`src/multi_robomaster/__init__.py`)

### Функции

#### `enable_logging_to_file`
- **Сигнатура:** `enable_logging_to_file()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** setLevel, format, FileHandler, setFormatter, addHandler, strftime
- **Аргументы:**
  - нет аргументов
- **Пример(ы) из репозитория:**
  - `robomaster.enable_logging_to_file()` (из `examples/01_robot/00_logger.py:22`)


## Модуль `src.multi_robomaster.multi_group` (`src/multi_robomaster/multi_group.py`)

### Классы

### `RobotGroupBase`
- **Приватный класс:** нет
- **Описание:** robot group object
- **Конструктор:** `__init__(self, robots_group_list, all_robots_dict)`
  - **Аргументы конструктора:**
    - `robots_group_list`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `robots_group_list`.
    - `all_robots_dict`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `all_robots_dict`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, robots_group_list, all_robots_dict)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `robots_group_list`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robots_group_list`.
      - `all_robots_dict`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `all_robots_dict`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `__del__` (приватный)
    - Сигнатура: `__del__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): items, info, format
    - Аргументы:
      - нет аргументов
    - Пример: `obj.__del__()`
  - `initialize`
    - Сигнатура: `initialize(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): _scan_group_module
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `ep_robot.initialize(conn_type='rndis')` (из `examples/01_robot/00_logger.py:30`)
      - `ep_robot.initialize(conn_type="ap")` (из `examples/01_robot/01_get_version.py:22`)
  - `get_robot`
    - Сигнатура: `get_robot(self, robot_id)`
    - Приватный: нет
    - Описание: Get robot by robot-id
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `robot_id`: тип `не указан`; единицы `0-255`; допустимые значения `ID/целое`; параметр `robot_id`.
    - Пример(ы) из репозитория:
      - `drone_obj = multi_drone_group1.get_robot(drone_id)` (из `examples/15_multi_robot/multi_drone/07_takeoff_order.py:38`)
      - `robot_obj = robot_group.get_robot(robot_id)` (из `examples/15_multi_robot/multi_ep/03_six_ep_demo.py:54`)
  - `robots_num`
    - Сигнатура: `robots_num(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): len
    - Аргументы:
      - нет аргументов
    - Пример: `obj.robots_num()`
  - `all_robots_dict`
    - Сигнатура: `all_robots_dict(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.all_robots_dict()`
  - `_scan_group_module` (приватный)
    - Сигнатура: `_scan_group_module(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj._scan_group_module()`
  - `get_group_module`
    - Сигнатура: `get_group_module(self, name)`
    - Приватный: нет
    - Описание: Get group module by name
    - Связи (вызовы): debug, get_module, error, format
    - Аргументы:
      - `name`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `name`.
    - Пример: `obj.get_group_module(...)`
  - `robots_id_list`
    - Сигнатура: `robots_id_list(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.robots_id_list()`
  - `append`
    - Сигнатура: `append(self, robots_id_list)`
    - Приватный: нет
    - Описание: Add robots to the group
    - Связи (вызовы): check_robots_id, Exception, warning, append, info, format
    - Аргументы:
      - `robots_id_list`: тип `не указан`; единицы `0-255`; допустимые значения `ID/целое`; параметр `robots_id_list`.
    - Пример(ы) из репозитория:
      - `markers.append(MarkerInfo(x, y, w, h, info))` (из `examples/05_vision/01_marker.py:57`)
      - `line.append(PointInfo(x, y, ceta, c))` (из `examples/05_vision/02_line.py:50`)
  - `remove`
    - Сигнатура: `remove(self, robots_id_list)`
    - Приватный: нет
    - Описание: remove the robots from robot group
    - Связи (вызовы): warning, remove, info, format
    - Аргументы:
      - `robots_id_list`: тип `не указан`; единицы `0-255`; допустимые значения `ID/целое`; параметр `robots_id_list`.
    - Пример(ы) из репозитория:
      - `self.cmd_socket_list.remove(self.video_socket)` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:115`)
      - `self.cmd_socket_list.remove(self.audio_socket)` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:132`)
  - `execute_action`
    - Сигнатура: `execute_action(self, action_name, *args, **kw)`
    - Приватный: нет
    - Описание: Executive function for non-instantaneous action
    - Связи (вызовы): MultiAction, info, getattr, format
    - Аргументы:
      - `action_name`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; which action need exec
      - `*args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; the action key params
      - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `**kw`.
    - Пример: `obj.execute_action(...)`
  - `execute_command`
    - Сигнатура: `execute_command(self, command_name, *input_args, **input_kw)`
    - Приватный: нет
    - Описание: Executive function for instantaneous action
    - Связи (вызовы): time, items, debug, TelloThread, start, format
    - Аргументы:
      - `command_name`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; which command need send
      - `*input_args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `*input_args`.
      - `**input_kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `**input_kw`.
    - Пример: `obj.execute_command(...)`
  - `get_sn`
    - Сигнатура: `get_sn(self)`
    - Приватный: нет
    - Описание: 获取组内机器的sn编号
    - Связи (вызовы): execute_command
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `SN = ep_robot.get_sn()` (из `examples/01_robot/02_get_sn.py:24`)
      - `SN = tl_drone.get_sn()` (из `examples/12_drone/03_get_sn.py:26`)

### `RMGroup`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self, robots_group_list, all_robots_dict)`
  - **Аргументы конструктора:**
    - `robots_group_list`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `robots_group_list`.
    - `all_robots_dict`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `all_robots_dict`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, robots_group_list, all_robots_dict)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): __init__, super
    - Аргументы:
      - `robots_group_list`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robots_group_list`.
      - `all_robots_dict`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `all_robots_dict`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `_scan_group_module` (приватный)
    - Сигнатура: `_scan_group_module(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): MultiRmModule
    - Аргументы:
      - нет аргументов
    - Пример: `obj._scan_group_module()`
  - `set_group_robots_mode`
    - Сигнатура: `set_group_robots_mode(self, mode='free')`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): set_robot_mode, info, error, format
    - Аргументы:
      - `mode`: тип `не указан`; единицы `не указаны`; допустимые значения `enum/строка`; параметр `mode`.
    - Пример(ы) из репозитория:
      - `robot_group.set_group_robots_mode(multi_robot.FREE_MODE)` (из `examples/15_multi_robot/multi_ep/03_six_ep_demo.py:28`)
      - `robot_group.set_group_robots_mode(multi_robot.CHASSIS_LEAD_MODE)` (из `examples/15_multi_robot/multi_ep/03_six_ep_demo.py:75`)
  - `play_sound`
    - Сигнатура: `play_sound(self, sound_id, times=1)`
    - Приватный: нет
    - Описание: robots in group play sound
    - Связи (вызовы): play_sound, warning, format
    - Аргументы:
      - `sound_id`: тип `не указан`; единицы `не указаны`; допустимые значения `ID/целое`; параметр `sound_id`.
      - `times`: тип `не указан`; единицы `с`; допустимые значения `не указаны`; параметр `times`.
    - Пример(ы) из репозитория:
      - `ep_robot.play_sound(robot.SOUND_ID_ATTACK).wait_for_completed()` (из `examples/01_robot/03_play_sound.py:26`)
      - `ep_robot.play_sound(robot.SOUND_ID_SHOOT).wait_for_completed()` (из `examples/01_robot/03_play_sound.py:27`)
  - `chassis`
    - Сигнатура: `chassis(self)`
    - Приватный: нет
    - Описание: Get chassis obj
    - Связи (вызовы): get_group_module
    - Аргументы:
      - нет аргументов
    - Пример: `obj.chassis()`
  - `gimbal`
    - Сигнатура: `gimbal(self)`
    - Приватный: нет
    - Описание: Get gimbal obj
    - Связи (вызовы): get_group_module
    - Аргументы:
      - нет аргументов
    - Пример: `obj.gimbal()`
  - `blaster`
    - Сигнатура: `blaster(self)`
    - Приватный: нет
    - Описание: Get blaster obj
    - Связи (вызовы): get_group_module
    - Аргументы:
      - нет аргументов
    - Пример: `obj.blaster()`
  - `led`
    - Сигнатура: `led(self)`
    - Приватный: нет
    - Описание: Get led obj
    - Связи (вызовы): get_group_module
    - Аргументы:
      - нет аргументов
    - Пример: `obj.led()`
  - `robotic_arm`
    - Сигнатура: `robotic_arm(self)`
    - Приватный: нет
    - Описание: Get arm obj
    - Связи (вызовы): get_group_module
    - Аргументы:
      - нет аргументов
    - Пример: `obj.robotic_arm()`
  - `sensor`
    - Сигнатура: `sensor(self)`
    - Приватный: нет
    - Описание: Get sensor obj
    - Связи (вызовы): get_group_module
    - Аргументы:
      - нет аргументов
    - Пример: `obj.sensor()`
  - `gripper`
    - Сигнатура: `gripper(self)`
    - Приватный: нет
    - Описание: Get gripper obj
    - Связи (вызовы): get_group_module
    - Аргументы:
      - нет аргументов
    - Пример: `obj.gripper()`

### `SingleDroneInGroup`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self, client, _robot_id, _robot_sn, _robot_host)`
  - **Аргументы конструктора:**
    - `client`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; инициализационный параметр `client`.
    - `_robot_id`: тип `не указан`; единицы `0-255`; допустимые значения `ID/целое`; инициализационный параметр `_robot_id`.
    - `_robot_sn`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `_robot_sn`.
    - `_robot_host`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `_robot_host`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, client, _robot_id, _robot_sn, _robot_host)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): Event, set, TelloDispatcher
    - Аргументы:
      - `client`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `client`.
      - `_robot_id`: тип `не указан`; единицы `0-255`; допустимые значения `ID/целое`; параметр `_robot_id`.
      - `_robot_sn`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `_robot_sn`.
      - `_robot_host`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `_robot_host`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `close`
    - Сигнатура: `close(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `ep_robot.close()` (из `examples/01_robot/00_logger.py:34`)
      - `ep_robot.close()` (из `examples/01_robot/01_get_version.py:27`)
  - `send_command`
    - Сигнатура: `send_command(self, command)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): wait, isSet, info, TelloProtocol, send, clear
    - Аргументы:
      - `command`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `command`.
    - Пример: `obj.send_command(...)`

### `TelloGroup`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self, client, robot_id_group_list, _robot_id_dict={}, _robot_host_dict={})`
  - **Аргументы конструктора:**
    - `client`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; инициализационный параметр `client`.
    - `robot_id_group_list`: тип `не указан`; единицы `0-255`; допустимые значения `ID/целое`; инициализационный параметр `robot_id_group_list`.
    - `_robot_id_dict`: тип `не указан`; единицы `0-255`; допустимые значения `ID/целое`; инициализационный параметр `_robot_id_dict`.
    - `_robot_host_dict`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `_robot_host_dict`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, client, robot_id_group_list, _robot_id_dict={}, _robot_host_dict={})`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): __init__, init, super
    - Аргументы:
      - `client`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `client`.
      - `robot_id_group_list`: тип `не указан`; единицы `0-255`; допустимые значения `ID/целое`; параметр `robot_id_group_list`.
      - `_robot_id_dict`: тип `не указан`; единицы `0-255`; допустимые значения `ID/целое`; параметр `_robot_id_dict`.
      - `_robot_host_dict`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `_robot_host_dict`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `init`
    - Сигнатура: `init(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): append
    - Аргументы:
      - нет аргументов
    - Пример: `obj.init()`
  - `get_sn`
    - Сигнатура: `get_sn(self)`
    - Приватный: нет
    - Описание: find sn in group
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `SN = ep_robot.get_sn()` (из `examples/01_robot/02_get_sn.py:24`)
      - `SN = tl_drone.get_sn()` (из `examples/12_drone/03_get_sn.py:26`)
  - `robot_group_host_list`
    - Сигнатура: `robot_group_host_list(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.robot_group_host_list()`
  - `get_robot`
    - Сигнатура: `get_robot(self, robot_id)`
    - Приватный: нет
    - Описание: get Drone obj
    - Связи (вызовы): info, SingleDroneInGroup, format
    - Аргументы:
      - `robot_id`: тип `не указан`; единицы `0-255`; допустимые значения `ID/целое`; параметр `robot_id`.
    - Пример(ы) из репозитория:
      - `drone_obj = multi_drone_group1.get_robot(drone_id)` (из `examples/15_multi_robot/multi_drone/07_takeoff_order.py:38`)
      - `robot_obj = robot_group.get_robot(robot_id)` (из `examples/15_multi_robot/multi_ep/03_six_ep_demo.py:54`)


## Модуль `src.multi_robomaster.multi_module` (`src/multi_robomaster/multi_module.py`)

### Классы

### `MultiAction`
- **Приватный класс:** нет
- **Описание:** Action manager for multi robots
- **Конструктор:** `__init__(self, robots_action_dict)`
  - **Аргументы конструктора:**
    - `robots_action_dict`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `robots_action_dict`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, robots_action_dict)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `robots_action_dict`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robots_action_dict`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `wait_for_completed`
    - Сигнатура: `wait_for_completed(self, timeout=8)`
    - Приватный: нет
    - Описание: Wait for all robots to complete their actions
    - Связи (вызовы): time, keys, info, error, append, format
    - Аргументы:
      - `timeout`: тип `не указан`; единицы `с`; допустимые значения `не указаны`; Add up the wait times for all the cars.
    - Пример(ы) из репозитория:
      - `ep_robot.play_audio(filename="demo1.wav").wait_for_completed()` (из `examples/01_robot/03_play_audio.py:27`)
      - `ep_robot.play_audio(filename="demo2.wav").wait_for_completed()` (из `examples/01_robot/03_play_audio.py:28`)

### `TelloDispatcher`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self, client, event, _robot_host_dict)`
  - **Аргументы конструктора:**
    - `client`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; инициализационный параметр `client`.
    - `event`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; инициализационный параметр `event`.
    - `_robot_host_dict`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `_robot_host_dict`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, client, event, _robot_host_dict)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `client`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `client`.
      - `event`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `event`.
      - `_robot_host_dict`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `_robot_host_dict`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `action_host_list`
    - Сигнатура: `action_host_list(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.action_host_list()`
  - `action_host_list`
    - Сигнатура: `action_host_list(self, value)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `value`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `value`.
    - Пример: `obj.action_host_list(...)`
  - `wait_for_completed`
    - Сигнатура: `wait_for_completed(self, timeout=10)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): copy, TelloStatus, time, info, set, len
    - Аргументы:
      - `timeout`: тип `не указан`; единицы `с`; допустимые значения `не указаны`; параметр `timeout`.
    - Пример(ы) из репозитория:
      - `ep_robot.play_audio(filename="demo1.wav").wait_for_completed()` (из `examples/01_robot/03_play_audio.py:27`)
      - `ep_robot.play_audio(filename="demo2.wav").wait_for_completed()` (из `examples/01_robot/03_play_audio.py:28`)

### `MultiModule`
- **Приватный класс:** нет
- **Описание:** multi-robot`s module object
- **Конструктор:** `__init__(self, robot_group, module_name)`
  - **Аргументы конструктора:**
    - `robot_group`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `robot_group`.
    - `module_name`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; инициализационный параметр `module_name`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, robot_group, module_name)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `robot_group`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot_group`.
      - `module_name`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `module_name`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `name`
    - Сигнатура: `name(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `assert roger.name() + " is a " + roger.species() == "Rabbit is a parrot"` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_class.py:74`)
      - `assert polly.name() + " is a " + polly.species() == "Polly is a parrot"` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_class.py:78`)
  - `execute_action`
    - Сигнатура: `execute_action(self, action_name, *args, **kw)`
    - Приватный: нет
    - Описание: Executive function for non-instantaneous action
    - Связи (вызовы): MultiAction, get_module, info, getattr, format
    - Аргументы:
      - `action_name`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; which action need exec
      - `*args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; the action key params
      - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `**kw`.
    - Пример: `obj.execute_action(...)`
  - `execute_command`
    - Сигнатура: `execute_command(self, command_name, *input_args, **input_kw)`
    - Приватный: нет
    - Описание: Executive function for instantaneous action
    - Связи (вызовы): time, items, debug, get_module, TelloThread, start
    - Аргументы:
      - `command_name`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; which command need send
      - `*input_args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `*input_args`.
      - `**input_kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `**input_kw`.
    - Пример: `obj.execute_command(...)`

### `MultiRmModule`
- **Приватный класс:** нет
- **Описание:** Robomaster module
- **Конструктор:** `__init__(self, robot_group, module_name)`
  - **Аргументы конструктора:**
    - `robot_group`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `robot_group`.
    - `module_name`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; инициализационный параметр `module_name`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, robot_group, module_name)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): __init__, super
    - Аргументы:
      - `robot_group`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot_group`.
      - `module_name`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `module_name`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `recenter`
    - Сигнатура: `recenter(self, *args, **kw)`
    - Приватный: нет
    - Описание: gimbal recenter
    - Связи (вызовы): execute_action
    - Аргументы:
      - `*args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `*args`.
      - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `**kw`.
    - Пример(ы) из репозитория:
      - `ep_gimbal.recenter().wait_for_completed()` (из `examples/03_gimbal/04_recenter.py:32`)
      - `ep_gimbal.recenter(pitch_speed=100, yaw_speed=100).wait_for_completed()` (из `examples/03_gimbal/04_recenter.py:38`)
  - `suspend`
    - Сигнатура: `suspend(self, *args, **kw)`
    - Приватный: нет
    - Описание: gimbal suspend
    - Связи (вызовы): execute_command
    - Аргументы:
      - `*args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `*args`.
      - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `**kw`.
    - Пример(ы) из репозитория:
      - `ep_gimbal.suspend()` (из `examples/03_gimbal/03_control.py:29`)
  - `resume`
    - Сигнатура: `resume(self, *args, **kw)`
    - Приватный: нет
    - Описание: gimbal resume
    - Связи (вызовы): execute_command
    - Аргументы:
      - `*args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `*args`.
      - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `**kw`.
    - Пример(ы) из репозитория:
      - `ep_gimbal.resume()` (из `examples/03_gimbal/03_control.py:33`)
  - `drive_wheels`
    - Сигнатура: `drive_wheels(self, *args, **kw)`
    - Приватный: нет
    - Описание: chassis drive wheels
    - Связи (вызовы): execute_action
    - Аргументы:
      - `*args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `*args`.
      - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `**kw`.
    - Пример(ы) из репозитория:
      - `ep_chassis.drive_wheels(w1=speed, w2=0, w3=0, w4=0)` (из `examples/02_chassis/02_wheel.py:33`)
      - `ep_chassis.drive_wheels(w1=0, w2=speed, w3=0, w4=0)` (из `examples/02_chassis/02_wheel.py:37`)
  - `drive_speed`
    - Сигнатура: `drive_speed(self, *args, **kw)`
    - Приватный: нет
    - Описание: chassis drive speed
    - Связи (вызовы): execute_action
    - Аргументы:
      - `*args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `*args`.
      - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `**kw`.
    - Пример(ы) из репозитория:
      - `ep_chassis.drive_speed(x=x_val, y=0, z=0, timeout=5)` (из `examples/02_chassis/03_speed.py:32`)
      - `ep_chassis.drive_speed(x=-x_val, y=0, z=0, timeout=5)` (из `examples/02_chassis/03_speed.py:36`)
  - `fire`
    - Сигнатура: `fire(self, *args, **kw)`
    - Приватный: нет
    - Описание: blaster fire
    - Связи (вызовы): execute_command
    - Аргументы:
      - `*args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `*args`.
      - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `**kw`.
    - Пример(ы) из репозитория:
      - `ep_blaster.fire(times=1)` (из `examples/06_blaster/01_fire.py:29`)
      - `ep_blaster.fire(fire_type=blaster.WATER_FIRE, times=3)` (из `examples/06_blaster/01_fire.py:33`)
  - `move`
    - Сигнатура: `move(self, *args, **kw)`
    - Приватный: нет
    - Описание: gimbal & chassis move
    - Связи (вызовы): execute_action
    - Аргументы:
      - `*args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `*args`.
      - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `**kw`.
    - Пример(ы) из репозитория:
      - `ep_chassis.move(x=x_val, y=0, z=0, xy_speed=0.7).wait_for_completed()` (из `examples/02_chassis/01_move.py:31`)
      - `ep_chassis.move(x=-x_val, y=0, z=0, xy_speed=0.7).wait_for_completed()` (из `examples/02_chassis/01_move.py:34`)
  - `moveto`
    - Сигнатура: `moveto(self, *args, **kw)`
    - Приватный: нет
    - Описание: gimbal & chassis moveto
    - Связи (вызовы): execute_action
    - Аргументы:
      - `*args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `*args`.
      - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `**kw`.
    - Пример(ы) из репозитория:
      - `ep_gimbal.moveto(pitch=0, yaw=0).wait_for_completed()` (из `examples/03_gimbal/01_move.py:32`)
      - `ep_gimbal.moveto(pitch=15, yaw=90, pitch_speed=50, yaw_speed=100).wait_for_completed()` (из `examples/03_gimbal/01_move.py:35`)
  - `set_led`
    - Сигнатура: `set_led(self, *args, **kw)`
    - Приватный: нет
    - Описание: blaster & armor led
    - Связи (вызовы): execute_command
    - Аргументы:
      - `*args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `*args`.
      - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `**kw`.
    - Пример(ы) из репозитория:
      - `ep_blaster.set_led(brightness=2, effect=blaster.LED_ON)` (из `examples/06_blaster/02_led.py:30`)
      - `ep_blaster.set_led(brightness=4, effect=blaster.LED_ON)` (из `examples/06_blaster/02_led.py:32`)
  - `close`
    - Сигнатура: `close(self, *args, **kw)`
    - Приватный: нет
    - Описание: gripper
    - Связи (вызовы): execute_command
    - Аргументы:
      - `*args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `*args`.
      - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `**kw`.
    - Пример(ы) из репозитория:
      - `ep_robot.close()` (из `examples/01_robot/00_logger.py:34`)
      - `ep_robot.close()` (из `examples/01_robot/01_get_version.py:27`)
  - `open`
    - Сигнатура: `open(self, *args, **kw)`
    - Приватный: нет
    - Описание: gripper
    - Связи (вызовы): execute_command
    - Аргументы:
      - `*args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `*args`.
      - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `**kw`.
    - Пример(ы) из репозитория:
      - `img = Image.open(QRCODE_NAME)` (из `examples/01_robot/05_sta_conn_helper.py:32`)
      - `playing_stream = audio_player.open(format=pyaudio.paInt16,` (из `examples/04_camera/04_audio_without_playing.py:27`)
  - `pause`
    - Сигнатура: `pause(self)`
    - Приватный: нет
    - Описание: gripper
    - Связи (вызовы): execute_command
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `ep_gripper.pause()` (из `examples/11_gripper/01_open_close.py:31`)
      - `ep_gripper.pause()` (из `examples/11_gripper/01_open_close.py:36`)

### `TelloAction`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self, client, _robot_id_dict, _robot_sn_dict, _robot_host_dict)`
  - **Аргументы конструктора:**
    - `client`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; инициализационный параметр `client`.
    - `_robot_id_dict`: тип `не указан`; единицы `0-255`; допустимые значения `ID/целое`; инициализационный параметр `_robot_id_dict`.
    - `_robot_sn_dict`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `_robot_sn_dict`.
    - `_robot_host_dict`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `_robot_host_dict`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, client, _robot_id_dict, _robot_sn_dict, _robot_host_dict)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): Event, set, TelloDispatcher
    - Аргументы:
      - `client`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `client`.
      - `_robot_id_dict`: тип `не указан`; единицы `0-255`; допустимые значения `ID/целое`; параметр `_robot_id_dict`.
      - `_robot_sn_dict`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `_robot_sn_dict`.
      - `_robot_host_dict`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `_robot_host_dict`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `action_group`
    - Сигнатура: `action_group(self, robot_group)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `robot_group`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot_group`.
    - Пример: `obj.action_group(...)`
  - `send_command`
    - Сигнатура: `send_command(self, command)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): wait, isSet, clear, set, warning, info
    - Аргументы:
      - `command`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `command`.
    - Пример: `obj.send_command(...)`
  - `send_custom_command`
    - Сигнатура: `send_custom_command(self, command_host_list, action='go')`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): wait, isSet, clear, set, warning, info
    - Аргументы:
      - `command_host_list`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `command_host_list`.
      - `action`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `action`.
    - Пример: `obj.send_custom_command(...)`
  - `get_sn`
    - Сигнатура: `get_sn(self)`
    - Приватный: нет
    - Описание: 获取sn
    - Связи (вызовы): send_command, wait_for_completed
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `SN = ep_robot.get_sn()` (из `examples/01_robot/02_get_sn.py:24`)
      - `SN = tl_drone.get_sn()` (из `examples/12_drone/03_get_sn.py:26`)
  - `get_battery`
    - Сигнатура: `get_battery(self)`
    - Приватный: нет
    - Описание: 获取电量
    - Связи (вызовы): send_command, wait_for_completed
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `battery_info = tl_battery.get_battery()` (из `examples/12_drone/04_get_battery.py:27`)
      - `robot_group.get_battery()` (из `examples/15_multi_robot/multi_drone/02_basic.py:21`)
  - `takeoff`
    - Сигнатура: `takeoff(self, retry=True)`
    - Приватный: нет
    - Описание: 自动起飞
    - Связи (вызовы): send_command
    - Аргументы:
      - `retry`: тип `не указан`; единицы `м`; допустимые значения `0..255`; параметр `retry`.
    - Пример(ы) из репозитория:
      - `tl_flight.takeoff().wait_for_completed()` (из `examples/12_drone/05_takeoff_land.py:28`)
      - `tl_flight.takeoff().wait_for_completed()` (из `examples/12_drone/06_rotate.py:28`)
  - `land`
    - Сигнатура: `land(self, retry=True)`
    - Приватный: нет
    - Описание: 自动降落
    - Связи (вызовы): send_command
    - Аргументы:
      - `retry`: тип `не указан`; единицы `м`; допустимые значения `0..255`; параметр `retry`.
    - Пример(ы) из репозитория:
      - `tl_flight.land().wait_for_completed()` (из `examples/12_drone/05_takeoff_land.py:29`)
      - `tl_flight.land().wait_for_completed()` (из `examples/12_drone/06_rotate.py:35`)
  - `up`
    - Сигнатура: `up(self, distance, retry=True)`
    - Приватный: нет
    - Описание: 向上飞distance厘米，指相对距离
    - Связи (вызовы): fly
    - Аргументы:
      - `distance`: тип `не указан`; единицы `см`; допустимые значения `не указаны`; параметр `distance`.
      - `retry`: тип `не указан`; единицы `м`; допустимые значения `0..255`; параметр `retry`.
    - Пример(ы) из репозитория:
      - `tl_flight.up(distance=20).wait_for_completed()` (из `examples/12_drone/08_up_down.py:31`)
      - `robot_group.up(50).wait_for_completed()` (из `examples/15_multi_robot/multi_drone/04_flight.py:23`)
  - `down`
    - Сигнатура: `down(self, distance, retry=True)`
    - Приватный: нет
    - Описание: 向下飞distance厘米，指相对距离
    - Связи (вызовы): fly
    - Аргументы:
      - `distance`: тип `не указан`; единицы `см`; допустимые значения `не указаны`; параметр `distance`.
      - `retry`: тип `не указан`; единицы `м`; допустимые значения `0..255`; параметр `retry`.
    - Пример(ы) из репозитория:
      - `tl_flight.down(distance=20).wait_for_completed()` (из `examples/12_drone/08_up_down.py:32`)
      - `robot_group.down(50).wait_for_completed()` (из `examples/15_multi_robot/multi_drone/04_flight.py:22`)
  - `forward`
    - Сигнатура: `forward(self, distance, retry=True)`
    - Приватный: нет
    - Описание: 向前飞distance厘米，指相对距离
    - Связи (вызовы): fly
    - Аргументы:
      - `distance`: тип `не указан`; единицы `см`; допустимые значения `не указаны`; параметр `distance`.
      - `retry`: тип `не указан`; единицы `м`; допустимые значения `0..255`; параметр `retry`.
    - Пример(ы) из репозитория:
      - `tl_flight.forward(distance=50).wait_for_completed()` (из `examples/12_drone/07_forward_backward.py:31`)
      - `robot_group.forward(100).wait_for_completed()` (из `examples/15_multi_robot/multi_drone/03_takeoff_land.py:22`)
  - `backward`
    - Сигнатура: `backward(self, distance, retry=True)`
    - Приватный: нет
    - Описание: 向后飞distance厘米，指相对距离
    - Связи (вызовы): fly
    - Аргументы:
      - `distance`: тип `не указан`; единицы `см`; допустимые значения `не указаны`; параметр `distance`.
      - `retry`: тип `не указан`; единицы `м`; допустимые значения `0..255`; параметр `retry`.
    - Пример(ы) из репозитория:
      - `tl_flight.backward(distance=50).wait_for_completed()` (из `examples/12_drone/07_forward_backward.py:32`)
      - `robot_group.backward(100).wait_for_completed()` (из `examples/15_multi_robot/multi_drone/03_takeoff_land.py:28`)
  - `left`
    - Сигнатура: `left(self, distance, retry=True)`
    - Приватный: нет
    - Описание: 向左飞distance厘米，指相对距离
    - Связи (вызовы): fly
    - Аргументы:
      - `distance`: тип `не указан`; единицы `см`; допустимые значения `не указаны`; параметр `distance`.
      - `retry`: тип `не указан`; единицы `м`; допустимые значения `0..255`; параметр `retry`.
    - Пример(ы) из репозитория:
      - `tl_flight.left(distance=50).wait_for_completed()` (из `examples/12_drone/09_left_right.py:31`)
      - `robot_group.left(50).wait_for_completed()` (из `examples/15_multi_robot/multi_drone/04_flight.py:28`)
  - `right`
    - Сигнатура: `right(self, distance, retry=True)`
    - Приватный: нет
    - Описание: 向右飞distance厘米，指相对距离
    - Связи (вызовы): fly
    - Аргументы:
      - `distance`: тип `не указан`; единицы `см`; допустимые значения `не указаны`; параметр `distance`.
      - `retry`: тип `не указан`; единицы `м`; допустимые значения `0..255`; параметр `retry`.
    - Пример(ы) из репозитория:
      - `tl_flight.right(distance=50).wait_for_completed()` (из `examples/12_drone/09_left_right.py:32`)
      - `robot_group.right(50).wait_for_completed()` (из `examples/15_multi_robot/multi_drone/04_flight.py:26`)
  - `fly`
    - Сигнатура: `fly(self, _action, distance, retry)`
    - Приватный: нет
    - Описание: 控制飞机向指定方向飞行指定距离。
    - Связи (вызовы): format, send_command
    - Аргументы:
      - `_action`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `_action`.
      - `distance`: тип `не указан`; единицы `см`; допустимые значения `не указаны`; параметр `distance`.
      - `retry`: тип `не указан`; единицы `м`; допустимые значения `0..255`; параметр `retry`.
    - Пример: `obj.fly(..., ..., ...)`
  - `rotate`
    - Сигнатура: `rotate(self, angle=0, retry=True)`
    - Приватный: нет
    - Описание: 控制飞机旋转指定角度
    - Связи (вызовы): format, send_command
    - Аргументы:
      - `angle`: тип `не указан`; единицы `°`; допустимые значения `0..255`; параметр `angle`.
      - `retry`: тип `не указан`; единицы `м`; допустимые значения `0..255`; параметр `retry`.
    - Пример(ы) из репозитория:
      - `tl_flight.rotate(angle=180).wait_for_completed()` (из `examples/12_drone/06_rotate.py:31`)
      - `tl_flight.rotate(angle=-180).wait_for_completed()` (из `examples/12_drone/06_rotate.py:32`)
  - `flip_forward`
    - Сигнатура: `flip_forward(self, retry=True)`
    - Приватный: нет
    - Описание: 控制飞机向前翻滚
    - Связи (вызовы): flip
    - Аргументы:
      - `retry`: тип `не указан`; единицы `м`; допустимые значения `0..255`; параметр `retry`.
    - Пример(ы) из репозитория:
      - `tl_flight.flip_forward().wait_for_completed()` (из `examples/12_drone/12_flip.py:31`)
  - `flip_backward`
    - Сигнатура: `flip_backward(self, retry=True)`
    - Приватный: нет
    - Описание: 控制飞机向后翻滚
    - Связи (вызовы): flip
    - Аргументы:
      - `retry`: тип `не указан`; единицы `м`; допустимые значения `0..255`; параметр `retry`.
    - Пример(ы) из репозитория:
      - `tl_flight.flip_backward().wait_for_completed()` (из `examples/12_drone/12_flip.py:32`)
  - `flip_left`
    - Сигнатура: `flip_left(self, retry=True)`
    - Приватный: нет
    - Описание: 控制飞机向左翻滚
    - Связи (вызовы): flip
    - Аргументы:
      - `retry`: тип `не указан`; единицы `м`; допустимые значения `0..255`; параметр `retry`.
    - Пример(ы) из репозитория:
      - `tl_flight.flip_left().wait_for_completed()` (из `examples/12_drone/12_flip.py:33`)
  - `flip_right`
    - Сигнатура: `flip_right(self, retry=True)`
    - Приватный: нет
    - Описание: 控制飞机向右翻滚
    - Связи (вызовы): flip
    - Аргументы:
      - `retry`: тип `не указан`; единицы `м`; допустимые значения `0..255`; параметр `retry`.
    - Пример(ы) из репозитория:
      - `tl_flight.flip_right().wait_for_completed()` (из `examples/12_drone/12_flip.py:34`)
  - `flip`
    - Сигнатура: `flip(self, direction='f', retry=True)`
    - Приватный: нет
    - Описание: 控制飞机向指定方向翻滚
    - Связи (вызовы): format, send_command
    - Аргументы:
      - `direction`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; string: 飞机翻转的方向， ’l‘ 向左翻滚，’r‘ 向右翻滚，’f‘ 向前翻滚， ’b‘ 向后翻滚
      - `retry`: тип `не указан`; единицы `м`; допустимые значения `0..255`; параметр `retry`.
    - Пример: `obj.flip()`
  - `go`
    - Сигнатура: `go(self, go_dict)`
    - Приватный: нет
    - Описание: 控制飞机以设置速度飞向指定坐标位置
    - Связи (вызовы): isinstance, _custom_drone_command, Exception
    - Аргументы:
      - `go_dict`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `go_dict`.
    - Пример(ы) из репозитория:
      - `tl_flight.go(x=100, y=100, z=30, speed=30).wait_for_completed()` (из `examples/12_drone/10_go.py:31`)
      - `tl_flight.go(x=-100, y=-100, z=-30, speed=30).wait_for_completed()` (из `examples/12_drone/10_go.py:32`)
  - `mission_pad_on`
    - Сигнатура: `mission_pad_on(self)`
    - Приватный: нет
    - Описание: 开启视觉识别
    - Связи (вызовы): send_command, wait_for_completed
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `tl_flight.mission_pad_on()` (из `examples/12_drone/14_mission_pad.py:30`)
      - `tl_flight.mission_pad_on()` (из `examples/12_drone/15_jump.py:28`)
  - `mission_pad_off`
    - Сигнатура: `mission_pad_off(self)`
    - Приватный: нет
    - Описание: 关闭视觉识别
    - Связи (вызовы): send_command, wait_for_completed
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `tl_flight.mission_pad_off()` (из `examples/12_drone/14_mission_pad.py:45`)
      - `tl_flight.mission_pad_off()` (из `examples/12_drone/15_jump.py:37`)
  - `motor_on`
    - Сигнатура: `motor_on(self)`
    - Приватный: нет
    - Описание: 开启静置转桨
    - Связи (вызовы): send_command, wait_for_completed
    - Аргументы:
      - нет аргументов
    - Пример: `obj.motor_on()`
  - `motor_off`
    - Сигнатура: `motor_off(self)`
    - Приватный: нет
    - Описание: 开启静置转桨
    - Связи (вызовы): send_command, wait_for_completed
    - Аргументы:
      - нет аргументов
    - Пример: `obj.motor_off()`
  - `set_led`
    - Сигнатура: `set_led(self, r=0, g=255, b=0, command_dict=None)`
    - Приватный: нет
    - Описание: 设置扩展模块led颜色
    - Связи (вызовы): isinstance, wait_for_completed, _custom_drone_command, format, send_command
    - Аргументы:
      - `r`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; int:[0, 255], 扩展led红色通道的强度
      - `g`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; int:[0, 255], 扩展led绿色通道的强度
      - `b`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; int:[0, 255], 扩展led蓝色通道的强度
      - `command_dict`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; dict, 多飞机的自定义显示
    - Пример(ы) из репозитория:
      - `ep_blaster.set_led(brightness=2, effect=blaster.LED_ON)` (из `examples/06_blaster/02_led.py:30`)
      - `ep_blaster.set_led(brightness=4, effect=blaster.LED_ON)` (из `examples/06_blaster/02_led.py:32`)
  - `set_led_breath`
    - Сигнатура: `set_led_breath(self, freq=1, r=0, g=255, b=0, command_dict=None)`
    - Приватный: нет
    - Описание: 设置扩展模块led以指定的颜色与频率实现呼吸效果
    - Связи (вызовы): isinstance, wait_for_completed, _custom_drone_command, format, send_command
    - Аргументы:
      - `freq`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; int:[0.1, 2.5], 扩展led呼吸模式下的频率，共十档，随着数字增大速度变快
      - `r`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; int:[0, 255], 扩展led红色通道的强度
      - `g`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; int:[0, 255], 扩展led绿色通道的强度
      - `b`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; int:[0, 255], 扩展led蓝色通道的强度
      - `command_dict`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; dict, 多飞机的自定义显示
    - Пример: `obj.set_led_breath()`
  - `set_led_blink`
    - Сигнатура: `set_led_blink(self, freq=5, r1=0, g1=255, b1=0, r2=0, g2=255, b2=255, command_dict=None)`
    - Приватный: нет
    - Описание: 设置扩展模块led以制定的两种颜色与频率实现闪烁效果
    - Связи (вызовы): isinstance, wait_for_completed, _custom_drone_command, format, send_command
    - Аргументы:
      - `freq`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; int:[0.1, 10], 扩展ked闪烁模式下的频率， 共十档，随着数字增大速度变快
      - `r1`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; int:[0, 255], 第一种颜色的红色通道的强度
      - `g1`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; int:[0, 255], 第一种颜色的绿色通道的强度
      - `b1`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; int:[0, 255], 第一种颜色的蓝色通道的强度
      - `r2`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; int:[0, 255], 第二种颜色的红色通道的强度
      - `g2`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; int:[0, 255], 第二种颜色的绿色通道的强度
      - `b2`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; int:[0, 255], 第二种颜色的蓝色通道的强度
      - `command_dict`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; dict, 多飞机的自定义显示
    - Пример: `obj.set_led_blink()`
  - `set_mled_bright`
    - Сигнатура: `set_mled_bright(self, bright=255)`
    - Приватный: нет
    - Описание: 设置点阵屏的亮度
    - Связи (вызовы): format, send_command, wait_for_completed
    - Аргументы:
      - `bright`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; int:[0, 255] 点阵屏的亮度
    - Пример: `obj.set_mled_bright()`
  - `set_mled_boot`
    - Сигнатура: `set_mled_boot(self, display_graph)`
    - Приватный: нет
    - Описание: 设置点阵屏的开机画面
    - Связи (вызовы): format, send_command, wait_for_completed
    - Аргументы:
      - `display_graph`: тип `не указан`; единицы `м`; допустимые значения `0..255`; string: 长度最大为64，点阵屏显示图案的编码字符串，每个字符解读为二进制后对应位置的led点的状态，
    - Пример: `obj.set_mled_boot(...)`
  - `set_mled_sc`
    - Сигнатура: `set_mled_sc(self)`
    - Приватный: нет
    - Описание: 清除点阵屏开机显示画面
    - Связи (вызовы): send_command, wait_for_completed
    - Аргументы:
      - нет аргументов
    - Пример: `obj.set_mled_sc()`
  - `set_mled_char`
    - Сигнатура: `set_mled_char(self, color='r', display_char='0', command_dict=None)`
    - Приватный: нет
    - Описание: 控制扩展点阵屏模块，显示输入的字符
    - Связи (вызовы): isinstance, wait_for_completed, _custom_drone_command, format, send_command
    - Аргументы:
      - `color`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `color`.
      - `display_char`: тип `не указан`; единицы `м`; допустимые значения `0..255`; параметр `display_char`.
      - `command_dict`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; dict, 多飞机的自定义显示
    - Пример(ы) из репозитория:
      - `tl_drone.led.set_mled_char('r', num)` (из `examples/12_drone/21_mled.py:37`)
      - `tl_drone.led.set_mled_char(color='b', display_char='A')` (из `examples/12_drone/21_mled.py:41`)
  - `set_mled_graph`
    - Сигнатура: `set_mled_graph(self, display_graph, command_dict=None)`
    - Приватный: нет
    - Описание: 用户自定义扩展点阵屏显示图案
    - Связи (вызовы): isinstance, wait_for_completed, _custom_drone_command, format, send_command
    - Аргументы:
      - `display_graph`: тип `не указан`; единицы `м`; допустимые значения `0..255`; string: 长度最大为64，点阵屏显示图案的编码字符串，每个字符解读为二进制后对应位置的led点的状态，
      - `command_dict`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; dict, 多飞机的自定义显示
    - Пример(ы) из репозитория:
      - `tl_drone.led.set_mled_graph(mled_smile1)` (из `examples/12_drone/21_mled.py:30`)
      - `tl_drone.led.set_mled_graph(mled_smile2)` (из `examples/12_drone/21_mled.py:32`)
  - `set_mled_char_scroll`
    - Сигнатура: `set_mled_char_scroll(self, direction='l', color='r', freq=1.5, display_str='DJI')`
    - Приватный: нет
    - Описание: 控制扩展点阵屏滚动显示字符串
    - Связи (вызовы): format, _set_mled_scroll
    - Аргументы:
      - `direction`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `direction`.
      - `color`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `color`.
      - `freq`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `freq`.
      - `display_str`: тип `не указан`; единицы `м`; допустимые значения `0..255`; параметр `display_str`.
    - Пример: `obj.set_mled_char_scroll()`
  - `set_mled_graph_scroll`
    - Сигнатура: `set_mled_graph_scroll(self, direction='l', freq=1.5, display_graph=led.TELLO_DISPLAY_GRAPH)`
    - Приватный: нет
    - Описание: 控制扩展点阵屏滚动显示图像
    - Связи (вызовы): format, _set_mled_scroll
    - Аргументы:
      - `direction`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `direction`.
      - `freq`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `freq`.
      - `display_graph`: тип `не указан`; единицы `м`; допустимые значения `0..255`; параметр `display_graph`.
    - Пример: `obj.set_mled_graph_scroll()`
  - `_set_mled_scroll` (приватный)
    - Сигнатура: `_set_mled_scroll(self, cmd)`
    - Приватный: да
    - Описание: 控制扩展点阵屏滚动显示
    - Связи (вызовы): send_command, wait_for_completed
    - Аргументы:
      - `cmd`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `cmd`.
    - Пример: `obj._set_mled_scroll(...)`
  - `set_custom_text`
    - Сигнатура: `set_custom_text(self, text='', command_dict=None)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): set, isinstance, _custom_drone_command, format, send_command
    - Аргументы:
      - `text`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `text`.
      - `command_dict`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `command_dict`.
    - Пример: `obj.set_custom_text()`
  - `_custom_drone_command` (приватный)
    - Сигнатура: `_custom_drone_command(self, command_dict, cmd_formatter)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): items, send_custom_command, len, error, Exception, format
    - Аргументы:
      - `command_dict`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `command_dict`.
      - `cmd_formatter`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `cmd_formatter`.
    - Пример: `obj._custom_drone_command(..., ...)`


## Модуль `src.multi_robomaster.multi_robot` (`src/multi_robomaster/multi_robot.py`)

### Классы

### `MultiRobotBase`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `__del__` (приватный)
    - Сигнатура: `__del__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.__del__()`
  - `initialize`
    - Сигнатура: `initialize(self, robot_num)`
    - Приватный: нет
    - Описание: scan all robots and init its
    - Связи (вызовы): _scan_multi_robot, len, error, Exception, initialize
    - Аргументы:
      - `robot_num`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot_num`.
    - Пример(ы) из репозитория:
      - `ep_robot.initialize(conn_type='rndis')` (из `examples/01_robot/00_logger.py:30`)
      - `ep_robot.initialize(conn_type="ap")` (из `examples/01_robot/01_get_version.py:22`)
  - `close`
    - Сигнатура: `close(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): close
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `ep_robot.close()` (из `examples/01_robot/00_logger.py:34`)
      - `ep_robot.close()` (из `examples/01_robot/01_get_version.py:27`)
  - `all_robots`
    - Сигнатура: `all_robots(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.all_robots()`
  - `robots_num`
    - Сигнатура: `robots_num(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): len
    - Аргументы:
      - нет аргументов
    - Пример: `obj.robots_num()`
  - `groups_num`
    - Сигнатура: `groups_num(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): len
    - Аргументы:
      - нет аргументов
    - Пример: `obj.groups_num()`
  - `_scan_multi_robot` (приватный)
    - Сигнатура: `_scan_multi_robot(self, num=0)`
    - Приватный: да
    - Описание: Automatic scanning of robots in the network
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `num`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `num`.
    - Пример: `obj._scan_multi_robot()`
  - `reset_all_robot`
    - Сигнатура: `reset_all_robot(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): reset
    - Аргументы:
      - нет аргументов
    - Пример: `obj.reset_all_robot()`
  - `number_id_by_sn`
    - Сигнатура: `number_id_by_sn(self, *args)`
    - Приватный: нет
    - Описание: number id by SN
    - Связи (вызовы): get_robots_sn, info, len, keys, Exception, format
    - Аргументы:
      - `*args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; [id, SN] id int, SN str
    - Пример(ы) из репозитория:
      - `multi_drone.number_id_by_sn([0, robot_sn_list[0]], [1, robot_sn_list[1]])` (из `examples/15_multi_robot/multi_drone/02_basic.py:33`)
      - `multi_drone.number_id_by_sn([0, robot_sn_list[0]], [1, robot_sn_list[1]])` (из `examples/15_multi_robot/multi_drone/03_takeoff_land.py:38`)
  - `build_group`
    - Сигнатура: `build_group(self, robot_id_list)`
    - Приватный: нет
    - Описание: build a group that contains input robots
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `robot_id_list`: тип `не указан`; единицы `0-255`; допустимые значения `ID/целое`; параметр `robot_id_list`.
    - Пример(ы) из репозитория:
      - `tello_group = multi_drone.build_group([0, 1])` (из `examples/15_multi_robot/multi_drone/02_basic.py:34`)
      - `multi_drone_group1 = multi_drone.build_group([0])` (из `examples/15_multi_robot/multi_drone/03_takeoff_land.py:39`)
  - `remove_group`
    - Сигнатура: `remove_group(self, group_list)`
    - Приватный: нет
    - Описание: remove group from MultiRobot obj
    - Связи (вызовы): warning, remove, info, format
    - Аргументы:
      - `group_list`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `group_list`.
    - Пример: `obj.remove_group(...)`
  - `run`
    - Сигнатура: `run(self, *exec_list)`
    - Приватный: нет
    - Описание: Execute the action from the input list
    - Связи (вызовы): info, items, format, tuple, Thread, start
    - Аргументы:
      - `*exec_list`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; [robot_group, action_task]...
    - Пример(ы) из репозитория:
      - `myqr.run(words=info)` (из `examples/01_robot/05_sta_conn_helper.py:30`)
      - `multi_drone.run([tello_group, basic_task])` (из `examples/15_multi_robot/multi_drone/02_basic.py:35`)

### `MultiEP`
- **Приватный класс:** нет
- **Описание:** S1_EP
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): __init__, super
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `initialize`
    - Сигнатура: `initialize(self, proto_type=config.DEFAULT_PROTO_TYPE)`
    - Приватный: нет
    - Описание: scan all robots and init its
    - Связи (вызовы): _scan_multi_robot, len, error, Exception, initialize
    - Аргументы:
      - `proto_type`: тип `не указан`; единицы `м`; допустимые значения `0..255`; параметр `proto_type`.
    - Пример(ы) из репозитория:
      - `ep_robot.initialize(conn_type='rndis')` (из `examples/01_robot/00_logger.py:30`)
      - `ep_robot.initialize(conn_type="ap")` (из `examples/01_robot/01_get_version.py:22`)
  - `_scan_multi_robot` (приватный)
    - Сигнатура: `_scan_multi_robot(self, proto_type=config.DEFAULT_PROTO_TYPE)`
    - Приватный: да
    - Описание: Automatic scanning of robots in the network
    - Связи (вызовы): scan_robot_ip_list, enumerate, SdkConnection, ProtoSetSdkConnection, host2byte, randint
    - Аргументы:
      - `proto_type`: тип `не указан`; единицы `м`; допустимые значения `0..255`; параметр `proto_type`.
    - Пример: `obj._scan_multi_robot()`
  - `build_group`
    - Сигнатура: `build_group(self, robot_id_list)`
    - Приватный: нет
    - Описание: build a group that contains input robots
    - Связи (вызовы): check_robots_id, RMGroup, initialize, append, info, Exception
    - Аргументы:
      - `robot_id_list`: тип `не указан`; единицы `0-255`; допустимые значения `ID/целое`; параметр `robot_id_list`.
    - Пример(ы) из репозитория:
      - `tello_group = multi_drone.build_group([0, 1])` (из `examples/15_multi_robot/multi_drone/02_basic.py:34`)
      - `multi_drone_group1 = multi_drone.build_group([0])` (из `examples/15_multi_robot/multi_drone/03_takeoff_land.py:39`)
  - `set_all_robots_mode`
    - Сигнатура: `set_all_robots_mode(self, mode='gimbal_lead')`
    - Приватный: нет
    - Описание: :param mode: free, gimbal_lead, chassis_lead
    - Связи (вызовы): items, set_robot_mode, print
    - Аргументы:
      - `mode`: тип `не указан`; единицы `не указаны`; допустимые значения `enum/строка`; free, gimbal_lead, chassis_lead
    - Пример: `obj.set_all_robots_mode()`
  - `number_id`
    - Сигнатура: `number_id(self)`
    - Приватный: нет
    - Описание: Manually number of all the robots entered at initialization.
    - Связи (вызовы): _number_prompt
    - Аргументы:
      - нет аргументов
    - Пример: `obj.number_id()`

### `MultiDrone`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): TelloClient
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `initialize`
    - Сигнатура: `initialize(self, robot_num=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): start, scan_multi_robot
    - Аргументы:
      - `robot_num`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot_num`.
    - Пример(ы) из репозитория:
      - `ep_robot.initialize(conn_type='rndis')` (из `examples/01_robot/00_logger.py:30`)
      - `ep_robot.initialize(conn_type="ap")` (из `examples/01_robot/01_get_version.py:22`)
  - `close`
    - Сигнатура: `close(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): close
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `ep_robot.close()` (из `examples/01_robot/00_logger.py:34`)
      - `ep_robot.close()` (из `examples/01_robot/01_get_version.py:27`)
  - `_scan_multi_robot` (приватный)
    - Сигнатура: `_scan_multi_robot(self, num=0)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): initialize
    - Аргументы:
      - `num`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `num`.
    - Пример: `obj._scan_multi_robot()`
  - `reset_all_robot`
    - Сигнатура: `reset_all_robot()`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): warning, format, _getframe
    - Аргументы:
      - нет аргументов
    - Пример: `obj.reset_all_robot()`
  - `all_robots`
    - Сигнатура: `all_robots()`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): warning, format, _getframe
    - Аргументы:
      - нет аргументов
    - Пример: `obj.all_robots()`
  - `robots_num`
    - Сигнатура: `robots_num(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): len
    - Аргументы:
      - нет аргументов
    - Пример: `obj.robots_num()`
  - `run`
    - Сигнатура: `run(self, *exec_list)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): check_group_host, items, info, TelloAction, Thread, append
    - Аргументы:
      - `*exec_list`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `*exec_list`.
    - Пример(ы) из репозитория:
      - `myqr.run(words=info)` (из `examples/01_robot/05_sta_conn_helper.py:30`)
      - `multi_drone.run([tello_group, basic_task])` (из `examples/15_multi_robot/multi_drone/02_basic.py:35`)
  - `build_group`
    - Сигнатура: `build_group(self, robot_id_group_list)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): check_robots_id, TelloGroup, append, Exception
    - Аргументы:
      - `robot_id_group_list`: тип `не указан`; единицы `0-255`; допустимые значения `ID/целое`; параметр `robot_id_group_list`.
    - Пример(ы) из репозитория:
      - `tello_group = multi_drone.build_group([0, 1])` (из `examples/15_multi_robot/multi_drone/02_basic.py:34`)
      - `multi_drone_group1 = multi_drone.build_group([0])` (из `examples/15_multi_robot/multi_drone/03_takeoff_land.py:39`)
  - `send_command`
    - Сигнатура: `send_command(self, text, host_list=None)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): TelloProtocol, send
    - Аргументы:
      - `text`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `text`.
      - `host_list`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `host_list`.
    - Пример: `obj.send_command(...)`
  - `_get_sn` (приватный)
    - Сигнатура: `_get_sn(self, timeout=0)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): send_command, time, qsize, empty, get, sleep
    - Аргументы:
      - `timeout`: тип `не указан`; единицы `с`; допустимые значения `не указаны`; параметр `timeout`.
    - Пример(ы) из репозитория:
      - `drone_ip_list = multi_drone._get_sn(timeout=10)` (из `examples/15_multi_robot/multi_drone/01_scan_ip.py:24`)
  - `number_id_by_sn`
    - Сигнатура: `number_id_by_sn(self, *id_sn, timeout=3)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): _get_sn, Exception, get, isinstance, format
    - Аргументы:
      - `*id_sn`: тип `не указан`; единицы `не указаны`; допустимые значения `ID/целое`; параметр `*id_sn`.
      - `timeout`: тип `не указан`; единицы `с`; допустимые значения `не указаны`; параметр `timeout`.
    - Пример(ы) из репозитория:
      - `multi_drone.number_id_by_sn([0, robot_sn_list[0]], [1, robot_sn_list[1]])` (из `examples/15_multi_robot/multi_drone/02_basic.py:33`)
      - `multi_drone.number_id_by_sn([0, robot_sn_list[0]], [1, robot_sn_list[1]])` (из `examples/15_multi_robot/multi_drone/03_takeoff_land.py:38`)
  - `number_id_to_all_drone`
    - Сигнатура: `number_id_to_all_drone(self, timeout=10)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): _get_sn, enumerate, items
    - Аргументы:
      - `timeout`: тип `не указан`; единицы `с`; допустимые значения `не указаны`; параметр `timeout`.
    - Пример: `obj.number_id_to_all_drone()`


## Модуль `src.multi_robomaster.tool` (`src/multi_robomaster/tool.py`)

### Функции

#### `get_func_name`
- **Сигнатура:** `get_func_name()`
- **Приватная:** нет
- **Описание:** Get the name of the calling function
- **Связи (вызовы):** extract_stack
- **Аргументы:**
  - нет аргументов
- **Пример:** `get_func_name()`

#### `get_robots_sn`
- **Сигнатура:** `get_robots_sn(robots_list)`
- **Приватная:** нет
- **Описание:** Get the sn for the robots_list,
- **Связи (вызовы):** get_sn
- **Аргументы:**
  - `robots_list`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; which robots need to get sn
- **Пример:** `get_robots_sn(...)`

#### `check_robot_id`
- **Сигнатура:** `check_robot_id(robot_id, robots_dict)`
- **Приватная:** нет
- **Описание:** check to see if the robot id exists
- **Связи (вызовы):** list, keys
- **Аргументы:**
  - `robot_id`: тип `не указан`; единицы `0-255`; допустимые значения `ID/целое`; параметр `robot_id`.
  - `robots_dict`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; the dict to search
- **Пример:** `check_robot_id(..., ...)`

#### `check_robots_id`
- **Сигнатура:** `check_robots_id(robots_id_list, robots_dict)`
- **Приватная:** нет
- **Описание:** check to see if the robots id in input list exist
- **Связи (вызовы):** check_robot_id
- **Аргументы:**
  - `robots_id_list`: тип `не указан`; единицы `0-255`; допустимые значения `ID/целое`; параметр `robots_id_list`.
  - `robots_dict`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; the dict to search
- **Пример:** `check_robots_id(..., ...)`

#### `check_group_host`
- **Сигнатура:** `check_group_host(robot_group_host_list)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** set, len, warning, union
- **Аргументы:**
  - `robot_group_host_list`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot_group_host_list`.
- **Пример:** `check_group_host(...)`

#### `get_subnets`
- **Сигнатура:** `get_subnets()`
- **Приватная:** нет
- **Описание:** Look through the machine's internet connection and
- **Связи (вызовы):** interfaces, ifaddresses, IPNetwork, append, rsplit
- **Аргументы:**
  - нет аргументов
- **Пример:** `get_subnets()`

### Классы

### `TelloProtocol`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self, text=None, host=None, encoding='utf-8')`
  - **Аргументы конструктора:**
    - `text`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; инициализационный параметр `text`.
    - `host`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; инициализационный параметр `host`.
    - `encoding`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `encoding`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, text=None, host=None, encoding='utf-8')`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): init
    - Аргументы:
      - `text`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `text`.
      - `host`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `host`.
      - `encoding`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `encoding`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `init`
    - Сигнатура: `init(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): isinstance, warning, _decode, _encode, format
    - Аргументы:
      - нет аргументов
    - Пример: `obj.init()`
  - `text`
    - Сигнатура: `text(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.text()`
  - `host`
    - Сигнатура: `host(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.host()`
  - `host`
    - Сигнатура: `host(self, value)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `value`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `value`.
    - Пример: `obj.host(...)`
  - `text`
    - Сигнатура: `text(self, value)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `value`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `value`.
    - Пример: `obj.text(...)`
  - `_encode` (приватный)
    - Сигнатура: `_encode(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): encode
    - Аргументы:
      - нет аргументов
    - Пример: `obj._encode()`
  - `_decode` (приватный)
    - Сигнатура: `_decode(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): decode
    - Аргументы:
      - нет аргументов
    - Пример: `obj._decode()`

### `TelloConnection`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self, local_ip=conn.get_local_ip(), local_port=8889)`
  - **Аргументы конструктора:**
    - `local_ip`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; инициализационный параметр `local_ip`.
    - `local_port`: тип `не указан`; единицы `0-255`; допустимые значения `1..65535`; инициализационный параметр `local_port`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, local_ip=conn.get_local_ip(), local_port=8889)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): get_local_ip
    - Аргументы:
      - `local_ip`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `local_ip`.
      - `local_port`: тип `не указан`; единицы `0-255`; допустимые значения `1..65535`; параметр `local_port`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `start`
    - Сигнатура: `start(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): socket, bind, warning, format
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `self.cmd_socket_recv_thread.start()` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:90`)
      - `t.start()` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_callbacks.py:135`)
  - `pre_close`
    - Сигнатура: `pre_close(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): len, warning, send, TelloProtocol
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pre_close()`
  - `close`
    - Сигнатура: `close(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): pre_close, sleep, close
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `ep_robot.close()` (из `examples/01_robot/00_logger.py:34`)
      - `ep_robot.close()` (из `examples/01_robot/01_get_version.py:27`)
  - `recv`
    - Сигнатура: `recv(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): TelloProtocol, recvfrom, Exception, warning, format
    - Аргументы:
      - нет аргументов
    - Пример: `obj.recv()`
  - `send`
    - Сигнатура: `send(self, proto)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): sendto, warning, format
    - Аргументы:
      - `proto`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `proto`.
    - Пример(ы) из репозитория:
      - `return socket_obj.send(data.encode('utf-8'))` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:217`)
  - `_scan_host` (приватный)
    - Сигнатура: `_scan_host(self, num)`
    - Приватный: да
    - Описание: Find avaliable ip list in server's subnets
    - Связи (вызовы): info, get_subnets, IPNetwork, len, append, sendto
    - Аргументы:
      - `num`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; Number of Tello this method is expected to find
    - Пример: `obj._scan_host(...)`
  - `scan_multi_robot`
    - Сигнатура: `scan_multi_robot(self, num=0)`
    - Приватный: нет
    - Описание: Automatic scanning of robots in the network
    - Связи (вызовы): Thread, start, _scan_host, join
    - Аргументы:
      - `num`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `num`.
    - Пример: `obj.scan_multi_robot()`
  - `_scan_receive_task` (приватный)
    - Сигнатура: `_scan_receive_task(self, num)`
    - Приватный: да
    - Описание: Listen to responses from the Tello when scan the devices.
    - Связи (вызовы): info, len, recvfrom, join, format, str
    - Аргументы:
      - `num`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `num`.
    - Пример: `obj._scan_receive_task(...)`

### `TelloClient`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): TelloConnection, Queue, Thread
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `start`
    - Сигнатура: `start(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): start
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `self.cmd_socket_recv_thread.start()` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:90`)
      - `t.start()` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_callbacks.py:135`)
  - `close`
    - Сигнатура: `close(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): join, close
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `ep_robot.close()` (из `examples/01_robot/00_logger.py:34`)
      - `ep_robot.close()` (из `examples/01_robot/01_get_version.py:27`)
  - `recv`
    - Сигнатура: `recv(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): info, recv, put
    - Аргументы:
      - нет аргументов
    - Пример: `obj.recv()`
  - `send`
    - Сигнатура: `send(self, proto)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): send
    - Аргументы:
      - `proto`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `proto`.
    - Пример(ы) из репозитория:
      - `return socket_obj.send(data.encode('utf-8'))` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:217`)
  - `scan_multi_robot`
    - Сигнатура: `scan_multi_robot(self, num)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): scan_multi_robot
    - Аргументы:
      - `num`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `num`.
    - Пример: `obj.scan_multi_robot(...)`

### `TelloStatus`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self, cur_action)`
  - **Аргументы конструктора:**
    - `cur_action`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `cur_action`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, cur_action)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `cur_action`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `cur_action`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `judge`
    - Сигнатура: `judge(proto)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): waring, strip, debug, float, format, warning
    - Аргументы:
      - `proto`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `proto`.
    - Пример: `obj.judge(...)`

### `TelloThread`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self, target, *args, **kwargs)`
  - **Аргументы конструктора:**
    - `target`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `target`.
    - `*args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `*args`.
    - `**kwargs`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `**kwargs`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, target, *args, **kwargs)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): __init__
    - Аргументы:
      - `target`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `target`.
      - `*args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `*args`.
      - `**kwargs`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `**kwargs`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `run`
    - Сигнатура: `run(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): target
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `myqr.run(words=info)` (из `examples/01_robot/05_sta_conn_helper.py:30`)
      - `multi_drone.run([tello_group, basic_task])` (из `examples/15_multi_robot/multi_drone/02_basic.py:35`)
  - `get_result`
    - Сигнатура: `get_result(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.get_result()`


## Модуль `src.robomaster.__init__` (`src/robomaster/__init__.py`)

### Функции

#### `enable_logging_to_file`
- **Сигнатура:** `enable_logging_to_file()`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** setLevel, format, FileHandler, setFormatter, addHandler, strftime
- **Аргументы:**
  - нет аргументов
- **Пример(ы) из репозитория:**
  - `robomaster.enable_logging_to_file()` (из `examples/01_robot/00_logger.py:22`)


## Модуль `src.robomaster.action` (`src/robomaster/action.py`)

### Функции

#### `_make_action_key` (приватная)
- **Сигнатура:** `_make_action_key(cmdid, action_id)`
- **Приватная:** да
- **Описание:** описание отсутствует
- **Связи (вызовы):** не выявлены
- **Аргументы:**
  - `cmdid`: тип `не указан`; единицы `не указаны`; допустимые значения `ID/целое`; параметр `cmdid`.
  - `action_id`: тип `не указан`; единицы `не указаны`; допустимые значения `ID/целое`; параметр `action_id`.
- **Пример:** `_make_action_key(..., ...)`

### Классы

### `_AutoRegisterAction` (приватный класс)
- **Приватный класс:** да
- **Описание:** hepler to automatically register Proto Class whereever they're defined
- **Конструктор:** `__init__(cls, name, bases, attrs, **kw)`
  - **Аргументы конструктора:**
    - `name`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; инициализационный параметр `name`.
    - `bases`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `bases`.
    - `attrs`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `attrs`.
    - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; инициализационный параметр `**kw`.
- **Методы:**
  - `__new__` (приватный)
    - Сигнатура: `__new__(mcs, name, bases, attrs, **kw)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): __new__, super
    - Аргументы:
      - `mcs`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `mcs`.
      - `name`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `name`.
      - `bases`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `bases`.
      - `attrs`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `attrs`.
      - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `**kw`.
    - Пример(ы) из репозитория:
      - `m.TestFactory6.__init__(NotPybindDerived.__new__(NotPybindDerived), tag.base, 1)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_factory_constructors.py:447`)
      - `m.TestFactory6.__init__(NotPybindDerived.__new__(NotPybindDerived), tag.alias, 1)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_factory_constructors.py:449`)
  - `__init__` (приватный)
    - Сигнатура: `__init__(cls, name, bases, attrs, **kw)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): __init__, keys, ValueError, super, format
    - Аргументы:
      - `name`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `name`.
      - `bases`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `bases`.
      - `attrs`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `attrs`.
      - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `**kw`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)

### `Action`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self, **kw)`
  - **Аргументы конструктора:**
    - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; инициализационный параметр `**kw`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, **kw)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): __init__, Event, super
    - Аргументы:
      - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `**kw`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `_get_next_action_id` (приватный)
    - Сигнатура: `_get_next_action_id(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): acquire, release
    - Аргументы:
      - нет аргументов
    - Пример: `obj._get_next_action_id()`
  - `__repr__` (приватный)
    - Сигнатура: `__repr__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): format
    - Аргументы:
      - нет аргументов
    - Пример: `obj.__repr__()`
  - `target`
    - Сигнатура: `target(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.target()`
  - `is_running`
    - Сигнатура: `is_running(self)`
    - Приватный: нет
    - Описание: 是否正在运行中。
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.is_running()`
  - `is_completed`
    - Сигнатура: `is_completed(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.is_completed()`
  - `_is_aborting` (приватный)
    - Сигнатура: `_is_aborting(self)`
    - Приватный: да
    - Описание: 是否在取消任务状态中
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj._is_aborting()`
  - `has_succeeded`
    - Сигнатура: `has_succeeded(self)`
    - Приватный: нет
    - Описание: 是否已经成功完成
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.has_succeeded()`
  - `has_failed`
    - Сигнатура: `has_failed(self)`
    - Приватный: нет
    - Описание: 是否已经执行失败
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.has_failed()`
  - `failure_reason`
    - Сигнатура: `failure_reason(self)`
    - Приватный: нет
    - Описание: 获取执行失败原因
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.failure_reason()`
  - `state`
    - Сигнатура: `state(self)`
    - Приватный: нет
    - Описание: 返回当前任务动作状态。
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.state()`
  - `encode`
    - Сигнатура: `encode(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): NotImplementedError
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `return socket_obj.send(data.encode('utf-8'))` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:217`)
      - `ser.write('command'.encode('utf-8'))` (из `examples/plaintext_sample_code/RoboMasterEP/connection/uart/uart_connection.py:16`)
  - `make_action_key`
    - Сигнатура: `make_action_key(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.make_action_key()`
  - `_update_action_state` (приватный)
    - Сигнатура: `_update_action_state(self, proto_state)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): _changeto_state
    - Аргументы:
      - `proto_state`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `proto_state`.
    - Пример: `obj._update_action_state(...)`
  - `_changeto_state` (приватный)
    - Сигнатура: `_changeto_state(self, state)`
    - Приватный: да
    - Описание: 修改action状态
    - Связи (вызовы): info, format, _on_state_changed, set
    - Аргументы:
      - `state`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `state`.
    - Пример: `obj._changeto_state(...)`
  - `wait_for_completed`
    - Сигнатура: `wait_for_completed(self, timeout=None)`
    - Приватный: нет
    - Описание: 等待任务动作直到完成
    - Связи (вызовы): isSet, wait, warning, _changeto_state
    - Аргументы:
      - `timeout`: тип `не указан`; единицы `с`; допустимые значения `не указаны`; 超时，在timeout前未完成任务动作，直接返回
    - Пример(ы) из репозитория:
      - `ep_robot.play_audio(filename="demo1.wav").wait_for_completed()` (из `examples/01_robot/03_play_audio.py:27`)
      - `ep_robot.play_audio(filename="demo2.wav").wait_for_completed()` (из `examples/01_robot/03_play_audio.py:28`)
  - `_abort` (приватный)
    - Сигнатура: `_abort(self)`
    - Приватный: да
    - Описание: 取消任务动作
    - Связи (вызовы): _changeto_state, set
    - Аргументы:
      - нет аргументов
    - Пример: `obj._abort()`
  - `found_proto`
    - Сигнатура: `found_proto(self, proto)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `proto`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `proto`.
    - Пример: `obj.found_proto(...)`
  - `found_action`
    - Сигнатура: `found_action(self, proto)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `proto`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `proto`.
    - Пример: `obj.found_action(...)`

### `TextAction`
- **Приватный класс:** нет
- **Описание:** Blocking action in plaintext protocol
- **Конструктор:** `__init__(self, **kw)`
  - **Аргументы конструктора:**
    - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; инициализационный параметр `**kw`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, **kw)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): __init__, super
    - Аргументы:
      - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `**kw`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `__repr__` (приватный)
    - Сигнатура: `__repr__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): format
    - Аргументы:
      - нет аргументов
    - Пример: `obj.__repr__()`
  - `_update_action_state` (приватный)
    - Сигнатура: `_update_action_state(self, proto_state)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): debug, format, _changeto_state, match, error
    - Аргументы:
      - `proto_state`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `proto_state`.
    - Пример: `obj._update_action_state(...)`
  - `make_action_key`
    - Сигнатура: `make_action_key(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.make_action_key()`
  - `text_proto`
    - Сигнатура: `text_proto(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.text_proto()`
  - `text_proto`
    - Сигнатура: `text_proto(self, text_cmd)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): error
    - Аргументы:
      - `text_cmd`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `text_cmd`.
    - Пример: `obj.text_proto(...)`
  - `found_proto`
    - Сигнатура: `found_proto(self, proto)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `proto`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `proto`.
    - Пример: `obj.found_proto(...)`
  - `found_action`
    - Сигнатура: `found_action(self, proto)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): match
    - Аргументы:
      - `proto`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `proto`.
    - Пример: `obj.found_action(...)`

### `ActionDispatcher`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self, client=None)`
  - **Аргументы конструктора:**
    - `client`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; инициализационный параметр `client`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, client=None)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): Lock
    - Аргументы:
      - `client`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `client`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `initialize`
    - Сигнатура: `initialize(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): add_handler
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `ep_robot.initialize(conn_type='rndis')` (из `examples/01_robot/00_logger.py:30`)
      - `ep_robot.initialize(conn_type="ap")` (из `examples/01_robot/01_get_version.py:22`)
  - `has_in_progress_actions`
    - Сигнатура: `has_in_progress_actions(self)`
    - Приватный: нет
    - Описание: 是否有正在执行的任务
    - Связи (вызовы): len
    - Аргументы:
      - нет аргументов
    - Пример: `obj.has_in_progress_actions()`
  - `_on_recv` (приватный)
    - Сигнатура: `_on_recv(cls, self, msg)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): debug, get_proto, acquire, keys, release, format
    - Аргументы:
      - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
    - Пример: `obj._on_recv(...)`
  - `get_msg_by_action`
    - Сигнатура: `get_msg_by_action(self, action)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): encode, isinstance, TextMsg, Msg
    - Аргументы:
      - `action`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `action`.
    - Пример: `obj.get_msg_by_action(...)`
  - `send_action`
    - Сигнатура: `send_action(self, action, action_type=ACTION_NOW)`
    - Приватный: нет
    - Описание: 发送任务动作命令
    - Связи (вызовы): _get_next_action_id, get_msg_by_action, make_action_key, add_handler, send_msg, isinstance
    - Аргументы:
      - `action`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `action`.
      - `action_type`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `action_type`.
    - Пример: `obj.send_action(...)`
  - `_on_action_state_changed` (приватный)
    - Сигнатура: `_on_action_state_changed(cls, self, action, orgin, target)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): make_action_key, debug, acquire, release, format, keys
    - Аргументы:
      - `action`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `action`.
      - `orgin`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `orgin`.
      - `target`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `target`.
    - Пример: `obj._on_action_state_changed(..., ..., ...)`


## Модуль `src.robomaster.ai_module` (`src/robomaster/ai_module.py`)

### Классы

### `AiModuleEvent`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `data_info`
    - Сигнатура: `data_info(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.data_info()`
  - `decode`
    - Сигнатура: `decode(self, buf)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
    - Пример(ы) из репозитория:
      - `msg = msg.decode('utf-8')` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:68`)
      - `assert m.str_from_string().encode().decode() == "baz"` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_pytypes.py:73`)

### `AiModule`
- **Приватный класс:** нет
- **Описание:** EP AI模块
- **Конструктор:** `__init__(self, robot)`
  - **Аргументы конструктора:**
    - `robot`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `robot`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, robot)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): __init__, super
    - Аргументы:
      - `robot`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `init_ai_module`
    - Сигнатура: `init_ai_module(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): ProtoRoboticAiInit, _send_async_proto, host2byte
    - Аргументы:
      - нет аргументов
    - Пример: `obj.init_ai_module()`
  - `sub_ai_event`
    - Сигнатура: `sub_ai_event(self, callback=None, *args, **kw)`
    - Приватный: нет
    - Описание: 订阅AI信息
    - Связи (вызовы): init_ai_module, AiModuleEvent, ProtoAiModuleEvent, add_subject_event_info
    - Аргументы:
      - `callback`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 回调函数，返回数据 明文字符串:
      - `*args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 可变参数
      - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; 关键字参数
    - Пример(ы) из репозитория:
      - `ep_ai_module.sub_ai_event(callback=ai_callback)` (из `examples/17_ai_module/00_ai_module_ep.py:36`)
  - `unsub_ai_event`
    - Сигнатура: `unsub_ai_event(self)`
    - Приватный: нет
    - Описание: 取消AI数据订阅
    - Связи (вызовы): AiModuleEvent, del_subject_event_info
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `ep_ai_module.unsub_ai_event()` (из `examples/17_ai_module/00_ai_module_ep.py:38`)

### `TelloAIInfoSubject`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): __init__, super
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `percent`
    - Сигнатура: `percent(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.percent()`
  - `data_info`
    - Сигнатура: `data_info(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.data_info()`
  - `decode`
    - Сигнатура: `decode(self, buf)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): split, len, debug, append, int
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
    - Пример(ы) из репозитория:
      - `msg = msg.decode('utf-8')` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:68`)
      - `assert m.str_from_string().encode().decode() == "baz"` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_pytypes.py:73`)

### `TelloAI`
- **Приватный класс:** нет
- **Описание:** 教育无人机 AI模块
- **Конструктор:** `__init__(self, robot)`
  - **Аргументы конструктора:**
    - `robot`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `robot`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, robot)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `robot`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `get_ai`
    - Сигнатура: `get_ai(self)`
    - Приватный: нет
    - Описание: 获取AI模块信息
    - Связи (вызовы): TextProtoDrone, TextMsg, send_sync_msg, get_proto, warning, int
    - Аргументы:
      - нет аргументов
    - Пример: `obj.get_ai()`
  - `sub_ai_info`
    - Сигнатура: `sub_ai_info(self, freq=5, callback=None, *args, **kw)`
    - Приватный: нет
    - Описание: 订阅AI信息
    - Связи (вызовы): TelloAIInfoSubject, add_subject_info
    - Аргументы:
      - `freq`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; enum:(1,5,10) 设置数据订阅数据的推送频率，单位 Hz
      - `callback`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 回调函数，返回数据 明文字符串:
      - `*args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 可变参数
      - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; 关键字参数
    - Пример(ы) из репозитория:
      - `tl_drone.ai_module.sub_ai_info(freq=5, callback=sub_ia_info_handler)` (из `examples/17_ai_module/01_ai_module_tt.py:31`)
  - `unsub_ai_info`
    - Сигнатура: `unsub_ai_info(self)`
    - Приватный: нет
    - Описание: 取消订阅AI模块信息
    - Связи (вызовы): del_subject_info
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `tl_drone.ai_module.unsub_ai_info()` (из `examples/17_ai_module/01_ai_module_tt.py:35`)


## Модуль `src.robomaster.algo` (`src/robomaster/algo.py`)

### Функции

#### `crc8_calc`
- **Сигнатура:** `crc8_calc(data, crc=119)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** range, len
- **Аргументы:**
  - `data`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `data`.
  - `crc`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `crc`.
- **Пример:** `crc8_calc(...)`

#### `crc16_calc`
- **Сигнатура:** `crc16_calc(data, crc=13970)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** range, len
- **Аргументы:**
  - `data`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `data`.
  - `crc`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `crc`.
- **Пример:** `crc16_calc(...)`

#### `simple_encrypt`
- **Сигнатура:** `simple_encrypt(data)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** bytearray, range, len
- **Аргументы:**
  - `data`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `data`.
- **Пример:** `simple_encrypt(...)`


## Модуль `src.robomaster.armor` (`src/robomaster/armor.py`)

### Классы

### `ArmorHitEvent`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `armor_id`
    - Сигнатура: `armor_id(self)`
    - Приватный: нет
    - Описание: 上一次被击打的装甲板ID
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.armor_id()`
  - `armor_comp`
    - Сигнатура: `armor_comp(self)`
    - Приватный: нет
    - Описание: 上一次被击打的装甲板部位
    - Связи (вызовы): id2comp
    - Аргументы:
      - нет аргументов
    - Пример: `obj.armor_comp()`
  - `hit_type`
    - Сигнатура: `hit_type(self)`
    - Приватный: нет
    - Описание: 被击打类型
    - Связи (вызовы): warning, format
    - Аргументы:
      - нет аргументов
    - Пример: `obj.hit_type()`
  - `strength`
    - Сигнатура: `strength(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.strength()`
  - `data_info`
    - Сигнатура: `data_info(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.data_info()`
  - `decode`
    - Сигнатура: `decode(self, buf)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
    - Пример(ы) из репозитория:
      - `msg = msg.decode('utf-8')` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:68`)
      - `assert m.str_from_string().encode().decode() == "baz"` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_pytypes.py:73`)

### `IrHitEvent`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `hit_times`
    - Сигнатура: `hit_times(self)`
    - Приватный: нет
    - Описание: 受到红外打击的次数
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.hit_times()`
  - `data_info`
    - Сигнатура: `data_info(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.data_info()`
  - `decode`
    - Сигнатура: `decode(self, buf)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
    - Пример(ы) из репозитория:
      - `msg = msg.decode('utf-8')` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:68`)
      - `assert m.str_from_string().encode().decode() == "baz"` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_pytypes.py:73`)

### `Armor`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self, robot)`
  - **Аргументы конструктора:**
    - `robot`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `robot`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, robot)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): __init__, super
    - Аргументы:
      - `robot`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `sub_hit_event`
    - Сигнатура: `sub_hit_event(self, callback=None, *args, **kw)`
    - Приватный: нет
    - Описание: 打击事件订阅
    - Связи (вызовы): ArmorHitEvent, ProtoArmorHitEvent, add_subject_event_info
    - Аргументы:
      - `callback`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 回调函数, 返回数据 (armor_id, hit_type)：
      - `*args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 可变参数
      - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; 关键字参数
    - Пример(ы) из репозитория:
      - `ep_armor.sub_hit_event(hit_callback, ep_robot)` (из `examples/09_armor/01_hit_event.py:43`)
  - `sub_ir_event`
    - Сигнатура: `sub_ir_event(self, callback=None, *args, **kw)`
    - Приватный: нет
    - Описание: 红外打击事件订阅
    - Связи (вызовы): IrHitEvent, ProtoIrHitEvent, add_subject_event_info
    - Аргументы:
      - `callback`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 回调函数, 返回数据 (hit_cnt)
      - `*args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 可变参数
      - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; 关键字参数
    - Пример(ы) из репозитория:
      - `ep_armor.sub_ir_event(hit_callback, ep_robot)` (из `examples/09_armor/02_ir_event.py:40`)
  - `unsub_hit_event`
    - Сигнатура: `unsub_hit_event(self)`
    - Приватный: нет
    - Описание: 取消打击事件订阅
    - Связи (вызовы): ArmorHitEvent, del_subject_event_info
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `ep_armor.unsub_hit_event()` (из `examples/09_armor/01_hit_event.py:45`)
  - `unsub_ir_event`
    - Сигнатура: `unsub_ir_event(self)`
    - Приватный: нет
    - Описание: 取消红外打击事件订阅
    - Связи (вызовы): IrHitEvent, del_subject_event_info
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `ep_armor.unsub_ir_event()` (из `examples/09_armor/02_ir_event.py:42`)
  - `set_hit_sensitivity`
    - Сигнатура: `set_hit_sensitivity(self, comp=COMP_ALL, sensitivity=5)`
    - Приватный: нет
    - Описание: 设置装甲灵敏度
    - Связи (вызовы): ProtoSetArmorParam, int, info, _send_sync_proto, _comp2mask, format
    - Аргументы:
      - `comp`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; enum:("all", "top_all", "bottom_all", "top_left", "top_right", "bottom_left",         "bottom_right", "bottom_front", "bottom_back")：要设置的装甲部位
      - `sensitivity`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; int:[0, 10] 灵敏度系数，系数越大灵敏度越低
    - Пример(ы) из репозитория:
      - `ep_armor.set_hit_sensitivity(comp="all", sensitivity=5)` (из `examples/09_armor/01_hit_event.py:40`)
  - `comp2id`
    - Сигнатура: `comp2id(comp)`
    - Приватный: нет
    - Описание: 装甲部位转换为装甲ID
    - Связи (вызовы): warning, format
    - Аргументы:
      - `comp`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; enum ("bottom_back", "bottom_front", "bottom_left", "bottom_right", "top_left", "top_right") 装甲部位
    - Пример: `obj.comp2id(...)`
  - `id2comp`
    - Сигнатура: `id2comp(armor_id)`
    - Приватный: нет
    - Описание: 装甲ID转换为装甲部位
    - Связи (вызовы): warning, format
    - Аргументы:
      - `armor_id`: тип `не указан`; единицы `0-255`; допустимые значения `ID/целое`; int [1, 6]，装甲ID
    - Пример: `obj.id2comp(...)`
  - `_mask2comp` (приватный)
    - Сигнатура: `_mask2comp(comp_mask)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): warning, format
    - Аргументы:
      - `comp_mask`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `comp_mask`.
    - Пример: `obj._mask2comp(...)`
  - `_comp2mask` (приватный)
    - Сигнатура: `_comp2mask(comp)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): warning, format
    - Аргументы:
      - `comp`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `comp`.
    - Пример: `obj._comp2mask(...)`


## Модуль `src.robomaster.battery` (`src/robomaster/battery.py`)

### Классы

### `TelloBatInfoSubject`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): __init__, super
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `percent`
    - Сигнатура: `percent(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.percent()`
  - `data_info`
    - Сигнатура: `data_info(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.data_info()`
  - `decode`
    - Сигнатура: `decode(self, buf)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): split, debug, int, format
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
    - Пример(ы) из репозитория:
      - `msg = msg.decode('utf-8')` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:68`)
      - `assert m.str_from_string().encode().decode() == "baz"` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_pytypes.py:73`)
  - `freq`
    - Сигнатура: `freq(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.freq()`
  - `freq`
    - Сигнатура: `freq(self, in_freq)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `in_freq`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `in_freq`.
    - Пример: `obj.freq(...)`

### `BatterySubject`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `percent`
    - Сигнатура: `percent(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.percent()`
  - `data_info`
    - Сигнатура: `data_info(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.data_info()`
  - `decode`
    - Сигнатура: `decode(self, buf)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): unpack
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
    - Пример(ы) из репозитория:
      - `msg = msg.decode('utf-8')` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:68`)
      - `assert m.str_from_string().encode().decode() == "baz"` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_pytypes.py:73`)

### `TelloBattery`
- **Приватный класс:** нет
- **Описание:** 教育无人机 电池模块
- **Конструктор:** `__init__(self, robot)`
  - **Аргументы конструктора:**
    - `robot`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `robot`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, robot)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `robot`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `get_battery`
    - Сигнатура: `get_battery(self)`
    - Приватный: нет
    - Описание: 获取电池电量信息
    - Связи (вызовы): TextProtoDrone, TextMsg, send_sync_msg, get_proto, warning, int
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `battery_info = tl_battery.get_battery()` (из `examples/12_drone/04_get_battery.py:27`)
      - `robot_group.get_battery()` (из `examples/15_multi_robot/multi_drone/02_basic.py:21`)
  - `sub_battery_info`
    - Сигнатура: `sub_battery_info(self, freq=5, callback=None, *args, **kw)`
    - Приватный: нет
    - Описание: 订阅电池信息
    - Связи (вызовы): TelloBatInfoSubject, add_subject_info
    - Аргументы:
      - `freq`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; enum:(1,5,10) 设置数据订阅数据的推送频率，单位 Hz
      - `callback`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 回调函数，返回数据 percent:
      - `*args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 可变参数
      - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; 关键字参数
    - Пример(ы) из репозитория:
      - `ep_battery.sub_battery_info(5, sub_info_handler, ep_robot)` (из `examples/08_battery/01_sub_battery.py:36`)
      - `tl_drone.battery.sub_battery_info(freq=1, callback=sub_battery_info_handler)` (из `examples/12_drone/18_sub_battery.py:32`)
  - `unsub_battery_info`
    - Сигнатура: `unsub_battery_info(self)`
    - Приватный: нет
    - Описание: 取消订阅飞机电池信息
    - Связи (вызовы): del_subject_info
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `ep_battery.unsub_battery_info()` (из `examples/08_battery/01_sub_battery.py:38`)
      - `tl_drone.battery.unsub_battery_info()` (из `examples/12_drone/18_sub_battery.py:36`)

### `Battery`
- **Приватный класс:** нет
- **Описание:** EP 电池模块
- **Конструктор:** `__init__(self, robot)`
  - **Аргументы конструктора:**
    - `robot`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `robot`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, robot)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): __init__, super
    - Аргументы:
      - `robot`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `sub_battery_info`
    - Сигнатура: `sub_battery_info(self, freq=5, callback=None, *args, **kw)`
    - Приватный: нет
    - Описание: 订阅电池信息
    - Связи (вызовы): BatterySubject, add_subject_info
    - Аргументы:
      - `freq`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; enum:(1,5,10,20,50) 设置数据订阅数据的推送频率，单位 Hz
      - `callback`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 回调函数，返回数据 percent:
      - `*args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 可变参数
      - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; 关键字参数
    - Пример(ы) из репозитория:
      - `ep_battery.sub_battery_info(5, sub_info_handler, ep_robot)` (из `examples/08_battery/01_sub_battery.py:36`)
      - `tl_drone.battery.sub_battery_info(freq=1, callback=sub_battery_info_handler)` (из `examples/12_drone/18_sub_battery.py:32`)
  - `unsub_battery_info`
    - Сигнатура: `unsub_battery_info(self)`
    - Приватный: нет
    - Описание: 取消电池订阅
    - Связи (вызовы): del_subject_info
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `ep_battery.unsub_battery_info()` (из `examples/08_battery/01_sub_battery.py:38`)
      - `tl_drone.battery.unsub_battery_info()` (из `examples/12_drone/18_sub_battery.py:36`)


## Модуль `src.robomaster.blaster` (`src/robomaster/blaster.py`)

### Классы

### `Blaster`
- **Приватный класс:** нет
- **Описание:** EP 发射器模块
- **Конструктор:** `__init__(self, robot)`
  - **Аргументы конструктора:**
    - `robot`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `robot`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, robot)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): __init__, super
    - Аргументы:
      - `robot`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `fire`
    - Сигнатура: `fire(self, fire_type=WATER_FIRE, times=1)`
    - Приватный: нет
    - Описание: 发射器发射
    - Связи (вызовы): ProtoBlasterFire, val2proto, _send_sync_proto, warning, format
    - Аргументы:
      - `fire_type`: тип `не указан`; единицы `м`; допустимые значения `0..255`; enum: ("water", "ir")， 发射器发射类型，水弹、红外弹
      - `times`: тип `не указан`; единицы `с`; допустимые значения `не указаны`; 发射次数
    - Пример(ы) из репозитория:
      - `ep_blaster.fire(times=1)` (из `examples/06_blaster/01_fire.py:29`)
      - `ep_blaster.fire(fire_type=blaster.WATER_FIRE, times=3)` (из `examples/06_blaster/01_fire.py:33`)
  - `set_led`
    - Сигнатура: `set_led(self, brightness=255, effect=LED_ON)`
    - Приватный: нет
    - Описание: 设置发射器灯效
    - Связи (вызовы): ProtoBlasterSetLed, check, _send_sync_proto, warning, format
    - Аргументы:
      - `brightness`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; int:[0,255]，亮度
      - `effect`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; enum:("on", "off")，on 表示常亮，off 表示常灭
    - Пример(ы) из репозитория:
      - `ep_blaster.set_led(brightness=2, effect=blaster.LED_ON)` (из `examples/06_blaster/02_led.py:30`)
      - `ep_blaster.set_led(brightness=4, effect=blaster.LED_ON)` (из `examples/06_blaster/02_led.py:32`)


## Модуль `src.robomaster.camera` (`src/robomaster/camera.py`)

### Классы

### `Camera`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self, robot)`
  - **Аргументы конструктора:**
    - `robot`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `robot`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, robot)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): LiveView
    - Аргументы:
      - `robot`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `start_video_stream`
    - Сигнатура: `start_video_stream(self, display=True)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `display`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `display`.
    - Пример(ы) из репозитория:
      - `ep_camera.start_video_stream(display=True, resolution=camera.STREAM_360P)` (из `examples/04_camera/01_video_with_display.py:29`)
      - `ep_camera.start_video_stream(display=False)` (из `examples/04_camera/02_video_strategy.py:30`)
  - `stop_video_stream`
    - Сигнатура: `stop_video_stream(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `ep_camera.stop_video_stream()` (из `examples/04_camera/01_video_with_display.py:31`)
      - `ep_camera.stop_video_stream()` (из `examples/04_camera/02_video_strategy.py:37`)
  - `read_video_frame`
    - Сигнатура: `read_video_frame(self, timeout=3, strategy='pipeline')`
    - Приватный: нет
    - Описание: 读取一帧视频流帧
    - Связи (вызовы): read_video_frame
    - Аргументы:
      - `timeout`: тип `не указан`; единицы `с`; допустимые значения `не указаны`; float: (0, inf)，超时时间，超过指定timeout时间后函数返回
      - `strategy`: тип `не указан`; единицы `м`; допустимые значения `0..255`; enum: ("pipeline", "newest") 读取帧策略：pipeline 流水线依次读取，newest 获取最新的一帧数据，        注意会清空老的数据帧队列
    - Пример: `obj.read_video_frame()`
  - `read_cv2_image`
    - Сигнатура: `read_cv2_image(self, timeout=3, strategy='pipeline')`
    - Приватный: нет
    - Описание: 读取一帧视频流帧
    - Связи (вызовы): read_video_frame, array
    - Аргументы:
      - `timeout`: тип `не указан`; единицы `с`; допустимые значения `не указаны`; float: (0, inf)，超时参数，在timeout时间内未获取到视频流帧，函数返回
      - `strategy`: тип `не указан`; единицы `м`; допустимые значения `0..255`; enum: ("pipeline", "newest")，读取帧策略：pipeline 依次读取缓存的帧信息，newest 获取最新的一帧        数据，会清空旧的数据帧
    - Пример(ы) из репозитория:
      - `img = ep_camera.read_cv2_image(strategy="newest")` (из `examples/04_camera/02_video_strategy.py:32`)
      - `img = ep_camera.read_cv2_image()` (из `examples/04_camera/03_video_without_display.py:30`)

### `TelloCamera`
- **Приватный класс:** нет
- **Описание:** 教育无人机 摄像机模块
- **Конструктор:** `__init__(self, robot)`
  - **Аргументы конструктора:**
    - `robot`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `robot`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, robot)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): __init__, super
    - Аргументы:
      - `robot`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `__del__` (приватный)
    - Сигнатура: `__del__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): stop
    - Аргументы:
      - нет аргументов
    - Пример: `obj.__del__()`
  - `conf`
    - Сигнатура: `conf(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.conf()`
  - `start_video_stream`
    - Сигнатура: `start_video_stream(self, display=True)`
    - Приватный: нет
    - Описание: 开启视频流
    - Связи (вызовы): _video_stream, start_video_stream
    - Аргументы:
      - `display`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; bool, 是否显示视频流
    - Пример(ы) из репозитория:
      - `ep_camera.start_video_stream(display=True, resolution=camera.STREAM_360P)` (из `examples/04_camera/01_video_with_display.py:29`)
      - `ep_camera.start_video_stream(display=False)` (из `examples/04_camera/02_video_strategy.py:30`)
  - `stop_video_stream`
    - Сигнатура: `stop_video_stream(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): stop_video_stream, _video_stream
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `ep_camera.stop_video_stream()` (из `examples/04_camera/01_video_with_display.py:31`)
      - `ep_camera.stop_video_stream()` (из `examples/04_camera/02_video_strategy.py:37`)
  - `_video_stream` (приватный)
    - Сигнатура: `_video_stream(self, on_off=1)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): TextProtoDrone, TextMsg, send_sync_msg, warning, get_proto, format
    - Аргументы:
      - `on_off`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `on_off`.
    - Пример: `obj._video_stream()`
  - `stop`
    - Сигнатура: `stop(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): _stop_video_stream, stop
    - Аргументы:
      - нет аргументов
    - Пример: `obj.stop()`
  - `set_fps`
    - Сигнатура: `set_fps(self, fps)`
    - Приватный: нет
    - Описание: 设置飞机视频帧率
    - Связи (вызовы): format, TextProtoDrone, TextMsg, send_sync_msg, get_proto, warning
    - Аргументы:
      - `fps`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; 需要设置的帧率，[high, middle, low]
    - Пример(ы) из репозитория:
      - `tl_camera.set_fps("high")` (из `examples/12_drone/16_video_stream.py:27`)
  - `set_bitrate`
    - Сигнатура: `set_bitrate(self, bitrate)`
    - Приватный: нет
    - Описание: 设置飞机传输码率
    - Связи (вызовы): format, TextProtoDrone, TextMsg, send_sync_msg, get_proto, warning
    - Аргументы:
      - `bitrate`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 需要设置的传输码率，[0, 6]
    - Пример(ы) из репозитория:
      - `tl_camera.set_bitrate(6)` (из `examples/12_drone/16_video_stream.py:29`)
  - `set_resolution`
    - Сигнатура: `set_resolution(self, resolution)`
    - Приватный: нет
    - Описание: 设置飞机视频分辨率
    - Связи (вызовы): format, TextProtoDrone, TextMsg, send_sync_msg, get_proto, warning
    - Аргументы:
      - `resolution`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 需要设置的视频分辨率，[high, low]
    - Пример(ы) из репозитория:
      - `tl_camera.set_resolution("high")` (из `examples/12_drone/16_video_stream.py:28`)
  - `set_down_vision`
    - Сигнатура: `set_down_vision(self, setting)`
    - Приватный: нет
    - Описание: 设置飞机图像源
    - Связи (вызовы): format, print, TextProtoDrone, TextMsg, send_sync_msg, get_proto
    - Аргументы:
      - `setting`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `setting`.
    - Пример: `obj.set_down_vision(...)`

### `EPCamera`
- **Приватный класс:** нет
- **Описание:** EP 摄像机模块
- **Конструктор:** `__init__(self, robot)`
  - **Аргументы конструктора:**
    - `robot`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `robot`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, robot)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): __init__
    - Аргументы:
      - `robot`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `__del__` (приватный)
    - Сигнатура: `__del__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): stop
    - Аргументы:
      - нет аргументов
    - Пример: `obj.__del__()`
  - `conf`
    - Сигнатура: `conf(self)`
    - Приватный: нет
    - Описание: 相机参数配置
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.conf()`
  - `audio_stream_addr`
    - Сигнатура: `audio_stream_addr(self)`
    - Приватный: нет
    - Описание: 机器人音频流地址
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.audio_stream_addr()`
  - `video_stream_addr`
    - Сигнатура: `video_stream_addr(self)`
    - Приватный: нет
    - Описание: 机器人视频流地址
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.video_stream_addr()`
  - `start_video_stream`
    - Сигнатура: `start_video_stream(self, display=True, resolution='720p')`
    - Приватный: нет
    - Описание: 开启视频流
    - Связи (вызовы): _stream_sdk, _video_stream, start_video_stream, error
    - Аргументы:
      - `display`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; bool，是否显示视频流
      - `resolution`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; enum: ("360p", "540p", "720p")，设置图传分辨率尺寸
    - Пример(ы) из репозитория:
      - `ep_camera.start_video_stream(display=True, resolution=camera.STREAM_360P)` (из `examples/04_camera/01_video_with_display.py:29`)
      - `ep_camera.start_video_stream(display=False)` (из `examples/04_camera/02_video_strategy.py:30`)
  - `stop_video_stream`
    - Сигнатура: `stop_video_stream(self)`
    - Приватный: нет
    - Описание: 停止视频流
    - Связи (вызовы): _video_stream, stop_video_stream, warning, _stream_sdk
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `ep_camera.stop_video_stream()` (из `examples/04_camera/01_video_with_display.py:31`)
      - `ep_camera.stop_video_stream()` (из `examples/04_camera/02_video_strategy.py:37`)
  - `start_audio_stream`
    - Сигнатура: `start_audio_stream(self)`
    - Приватный: нет
    - Описание: 开启音频流
    - Связи (вызовы): _stream_sdk, _audio_stream, start_audio_stream, error
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `ep_camera.start_audio_stream()` (из `examples/04_camera/04_audio_without_playing.py:54`)
  - `stop_audio_stream`
    - Сигнатура: `stop_audio_stream(self)`
    - Приватный: нет
    - Описание: 停止音频流
    - Связи (вызовы): _audio_stream, stop_audio_stream, warning, _stream_sdk
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `ep_camera.stop_audio_stream()` (из `examples/04_camera/04_audio_without_playing.py:57`)
  - `read_audio_frame`
    - Сигнатура: `read_audio_frame(self, timeout=1)`
    - Приватный: нет
    - Описание: 读取一段音频流信息
    - Связи (вызовы): read_audio_frame
    - Аргументы:
      - `timeout`: тип `не указан`; единицы `с`; допустимые значения `не указаны`; float: (0, inf)，超时时间，超过指定timeout时间后函数返回
    - Пример(ы) из репозитория:
      - `frame = ep_camera.read_audio_frame()` (из `examples/04_camera/04_audio_without_playing.py:33`)
  - `record_audio`
    - Сигнатура: `record_audio(self, save_file='output.wav', seconds=5, sample_rate=48000)`
    - Приватный: нет
    - Описание: 录制音频，保存到本地，支持wav格式，单通道
    - Связи (вызовы): start_audio_stream, time, open, setparams, close, stop_audio_stream
    - Аргументы:
      - `save_file`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; 本地文件路径，目前仅支持wav格式
      - `seconds`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; 录制时间
      - `sample_rate`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 采样率
    - Пример(ы) из репозитория:
      - `ep_camera.record_audio(save_file="output.wav", seconds=5, sample_rate=16000)` (из `examples/04_camera/05_record_audio.py:26`)
  - `_stream_sdk` (приватный)
    - Сигнатура: `_stream_sdk(self, on_off=1, resolution='720p')`
    - Приватный: да
    - Описание: 控制媒体流sdk模式
    - Связи (вызовы): ProtoStreamCtrl, _send_sync_proto, error, format, warning
    - Аргументы:
      - `on_off`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; 1 表示进入SDK模式，0 表示退出SDK模式
      - `resolution`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `resolution`.
    - Пример: `obj._stream_sdk()`
  - `_video_stream` (приватный)
    - Сигнатура: `_video_stream(self, on_off=1, resolution='720p')`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): ProtoStreamCtrl, _send_sync_proto, error, warning, format
    - Аргументы:
      - `on_off`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `on_off`.
      - `resolution`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `resolution`.
    - Пример: `obj._video_stream()`
  - `_audio_stream` (приватный)
    - Сигнатура: `_audio_stream(self, on_off=1)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): ProtoStreamCtrl, _send_sync_proto, error, format
    - Аргументы:
      - `on_off`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `on_off`.
    - Пример: `obj._audio_stream()`
  - `stop`
    - Сигнатура: `stop(self)`
    - Приватный: нет
    - Описание: 停止
    - Связи (вызовы): stop_video_stream, stop_audio_stream, stop
    - Аргументы:
      - нет аргументов
    - Пример: `obj.stop()`
  - `take_photo`
    - Сигнатура: `take_photo(self)`
    - Приватный: нет
    - Описание: 拍照
    - Связи (вызовы): ProtoTakePhoto, _send_sync_proto
    - Аргументы:
      - нет аргументов
    - Пример: `obj.take_photo()`
  - `_set_zoom` (приватный)
    - Сигнатура: `_set_zoom(self, zoom=1.0)`
    - Приватный: да
    - Описание: 设置变焦参数
    - Связи (вызовы): ProtoSetZoom, _send_sync_proto
    - Аргументы:
      - `zoom`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; 变焦值
    - Пример: `obj._set_zoom()`


## Модуль `src.robomaster.chassis` (`src/robomaster/chassis.py`)

### Классы

### `ChassisMoveAction`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self, x=0, y=0, z=0, spd_xy=0, spd_z=0, **kw)`
  - **Аргументы конструктора:**
    - `x`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; инициализационный параметр `x`.
    - `y`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; инициализационный параметр `y`.
    - `z`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; инициализационный параметр `z`.
    - `spd_xy`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; инициализационный параметр `spd_xy`.
    - `spd_z`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; инициализационный параметр `spd_z`.
    - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; инициализационный параметр `**kw`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, x=0, y=0, z=0, spd_xy=0, spd_z=0, **kw)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): __init__, super
    - Аргументы:
      - `x`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `x`.
      - `y`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `y`.
      - `z`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `z`.
      - `spd_xy`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `spd_xy`.
      - `spd_z`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `spd_z`.
      - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `**kw`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `__repr__` (приватный)
    - Сигнатура: `__repr__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): format
    - Аргументы:
      - нет аргументов
    - Пример: `obj.__repr__()`
  - `encode`
    - Сигнатура: `encode(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): ProtoPositionMove, val2proto, int, warning
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `return socket_obj.send(data.encode('utf-8'))` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:217`)
      - `ser.write('command'.encode('utf-8'))` (из `examples/plaintext_sample_code/RoboMasterEP/connection/uart/uart_connection.py:16`)
  - `update_from_push`
    - Сигнатура: `update_from_push(self, proto)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): _update_action_state, proto2val, info, format
    - Аргументы:
      - `proto`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `proto`.
    - Пример: `obj.update_from_push(...)`

### `PositionSubject`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self, cs)`
  - **Аргументы конструктора:**
    - `cs`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; инициализационный параметр `cs`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, cs)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `cs`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `cs`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `position`
    - Сигнатура: `position(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.position()`
  - `data_info`
    - Сигнатура: `data_info(self)`
    - Приватный: нет
    - Описание: cs=0选用当前位置作为坐标原点，否则选用机器人上电时刻位置作为坐标原点
    - Связи (вызовы): proto2val
    - Аргументы:
      - нет аргументов
    - Пример: `obj.data_info()`
  - `decode`
    - Сигнатура: `decode(self, buf)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): unpack
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
    - Пример(ы) из репозитория:
      - `msg = msg.decode('utf-8')` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:68`)
      - `assert m.str_from_string().encode().decode() == "baz"` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_pytypes.py:73`)

### `AttiInfoSubject`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `atti_info`
    - Сигнатура: `atti_info(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.atti_info()`
  - `data_info`
    - Сигнатура: `data_info(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.data_info()`
  - `decode`
    - Сигнатура: `decode(self, buf)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): unpack, proto2val
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
    - Пример(ы) из репозитория:
      - `msg = msg.decode('utf-8')` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:68`)
      - `assert m.str_from_string().encode().decode() == "baz"` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_pytypes.py:73`)

### `ChassisModeSubject`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `chassis_mode`
    - Сигнатура: `chassis_mode(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.chassis_mode()`
  - `data_info`
    - Сигнатура: `data_info(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.data_info()`
  - `decode`
    - Сигнатура: `decode(self, buf)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): unpack
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
    - Пример(ы) из репозитория:
      - `msg = msg.decode('utf-8')` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:68`)
      - `assert m.str_from_string().encode().decode() == "baz"` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_pytypes.py:73`)

### `SbusSubject`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `subs_data`
    - Сигнатура: `subs_data(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.subs_data()`
  - `data_info`
    - Сигнатура: `data_info(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.data_info()`
  - `decode`
    - Сигнатура: `decode(self, buf)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): unpack
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
    - Пример(ы) из репозитория:
      - `msg = msg.decode('utf-8')` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:68`)
      - `assert m.str_from_string().encode().decode() == "baz"` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_pytypes.py:73`)

### `VelocitySubject`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `vel_data`
    - Сигнатура: `vel_data(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.vel_data()`
  - `data_info`
    - Сигнатура: `data_info(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.data_info()`
  - `decode`
    - Сигнатура: `decode(self, buf)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): unpack, proto2val
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
    - Пример(ы) из репозитория:
      - `msg = msg.decode('utf-8')` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:68`)
      - `assert m.str_from_string().encode().decode() == "baz"` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_pytypes.py:73`)

### `EscSubject`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `esc_info`
    - Сигнатура: `esc_info(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.esc_info()`
  - `data_info`
    - Сигнатура: `data_info(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.data_info()`
  - `decode`
    - Сигнатура: `decode(self, buf)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): unpack
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
    - Пример(ы) из репозитория:
      - `msg = msg.decode('utf-8')` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:68`)
      - `assert m.str_from_string().encode().decode() == "baz"` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_pytypes.py:73`)

### `ImuSubject`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `imu_info`
    - Сигнатура: `imu_info(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.imu_info()`
  - `data_info`
    - Сигнатура: `data_info(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.data_info()`
  - `decode`
    - Сигнатура: `decode(self, buf)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): unpack, proto2val
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
    - Пример(ы) из репозитория:
      - `msg = msg.decode('utf-8')` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:68`)
      - `assert m.str_from_string().encode().decode() == "baz"` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_pytypes.py:73`)

### `SaStatusSubject`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `sa_status`
    - Сигнатура: `sa_status(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.sa_status()`
  - `data_info`
    - Сигнатура: `data_info(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.data_info()`
  - `decode`
    - Сигнатура: `decode(self, buf)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
    - Пример(ы) из репозитория:
      - `msg = msg.decode('utf-8')` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:68`)
      - `assert m.str_from_string().encode().decode() == "baz"` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_pytypes.py:73`)

### `Chassis`
- **Приватный класс:** нет
- **Описание:** EP 底盘模块，可以控制底盘的速度、位置、订阅底盘的数据，控制麦克纳姆轮等操作
- **Конструктор:** `__init__(self, robot)`
  - **Аргументы конструктора:**
    - `robot`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `robot`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, robot)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): __init__, super
    - Аргументы:
      - `robot`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `stop`
    - Сигнатура: `stop(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): stop, is_alive, cancel, super
    - Аргументы:
      - нет аргументов
    - Пример: `obj.stop()`
  - `_set_mode` (приватный)
    - Сигнатура: `_set_mode(self, mode)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): ProtoChassisSetWorkMode, _send_sync_proto
    - Аргументы:
      - `mode`: тип `не указан`; единицы `не указаны`; допустимые значения `enum/строка`; параметр `mode`.
    - Пример: `obj._set_mode(...)`
  - `_get_mode` (приватный)
    - Сигнатура: `_get_mode(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): ProtoChassisGetWorkMode, _send_sync_proto
    - Аргументы:
      - нет аргументов
    - Пример: `obj._get_mode()`
  - `stick_overlay`
    - Сигнатура: `stick_overlay(self, fusion_mode=0)`
    - Приватный: нет
    - Описание: 设置底盘的杆量叠加模式
    - Связи (вызовы): ProtoChassisStickOverlay, _send_sync_proto
    - Аргументы:
      - `fusion_mode`: тип `не указан`; единицы `не указаны`; допустимые значения `enum/строка`; int:[0,1,2]  0 = 关闭SDK的杆量叠加, 1 = 使能杆量叠加,速度正方向为车身坐标系, 2 = 使能SDK模式,速度正方向为云台朝向
    - Пример(ы) из репозитория:
      - `ep.chassis.stick_overlay(1)` (из `examples/16_gamesystem/00_gamesystem.py:55`)
  - `drive_wheels`
    - Сигнатура: `drive_wheels(self, w1=0, w2=0, w3=0, w4=0, timeout=None)`
    - Приватный: нет
    - Описание: 设置麦轮转速
    - Связи (вызовы): ProtoSetWheelSpeed, val2proto, _send_sync_proto, Timer, start, is_alive
    - Аргументы:
      - `w1`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; int:[-1000,1000]，右前麦轮速度，以车头方向前进旋转为正方向，单位 rpm
      - `w2`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; int:[-1000,1000]，左前麦轮速度，以车头方向前进旋转为正方向，单位 rpm
      - `w3`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; int:[-1000,1000]，左后麦轮速度，以车头方向前进旋转为正方向，单位 rpm
      - `w4`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; int:[-1000,1000]，右后麦轮速度，以车头方向前进旋转为正方向，单位 rpm
      - `timeout`: тип `не указан`; единицы `с`; допустимые значения `не указаны`; float:(0,inf)，超过指定时间内未收到麦轮转速指令，主动控制机器人停止，单位 s
    - Пример(ы) из репозитория:
      - `ep_chassis.drive_wheels(w1=speed, w2=0, w3=0, w4=0)` (из `examples/02_chassis/02_wheel.py:33`)
      - `ep_chassis.drive_wheels(w1=0, w2=speed, w3=0, w4=0)` (из `examples/02_chassis/02_wheel.py:37`)
  - `_auto_stop_timer` (приватный)
    - Сигнатура: `_auto_stop_timer(self, api='drive_speed')`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): info, drive_speed, drive_wheels, warning, format
    - Аргументы:
      - `api`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `api`.
    - Пример: `obj._auto_stop_timer()`
  - `drive_speed`
    - Сигнатура: `drive_speed(self, x=0.0, y=0.0, z=0.0, timeout=None)`
    - Приватный: нет
    - Описание: 设置底盘速度，立即生效
    - Связи (вызовы): ProtoChassisSpeedMode, val2proto, info, _send_sync_proto, format, Timer
    - Аргументы:
      - `x`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; float:[-3.5,3.5]，x 轴向运动速度即前进速度，单位 m/s
      - `y`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; float:[-3.5,3.5]，y 轴向运动速度即横移速度，单位 m/s
      - `z`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; float:[-600,600]，z 轴向运动速度即旋转速度，单位 °/s
      - `timeout`: тип `не указан`; единицы `с`; допустимые значения `не указаны`; float:(0,inf)，超过指定时间内未收到麦轮转速指令，主动控制机器人停止，单位 s
    - Пример(ы) из репозитория:
      - `ep_chassis.drive_speed(x=x_val, y=0, z=0, timeout=5)` (из `examples/02_chassis/03_speed.py:32`)
      - `ep_chassis.drive_speed(x=-x_val, y=0, z=0, timeout=5)` (из `examples/02_chassis/03_speed.py:36`)
  - `set_pwm_value`
    - Сигнатура: `set_pwm_value(self, pwm1=None, pwm2=None, pwm3=None, pwm4=None, pwm5=None, pwm6=None)`
    - Приватный: нет
    - Описание: 设置PWM输出占空比
    - Связи (вызовы): ProtoChassisPwmPercent, _send_sync_proto, val2proto
    - Аргументы:
      - `pwm1`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; int:[0,100]，pwm输出占空比，单位%
      - `pwm2`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; int:[0,100]，pwm输出占空比，单位%
      - `pwm3`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; int:[0,100]，pwm输出占空比，单位%
      - `pwm4`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; int:[0,100]，pwm输出占空比，单位%
      - `pwm5`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; int:[0,100]，pwm输出占空比，单位%
      - `pwm6`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; int:[0,100]，pwm输出占空比，单位%
    - Пример(ы) из репозитория:
      - `ep_chassis.set_pwm_value(pwm1=20,pwm2=20,pwm3=20,pwm4=20,pwm5=20,pwm6=20)` (из `examples/02_chassis/11_pwm.py:29`)
  - `set_pwm_freq`
    - Сигнатура: `set_pwm_freq(self, pwm1=None, pwm2=None, pwm3=None, pwm4=None, pwm5=None, pwm6=None)`
    - Приватный: нет
    - Описание: 设置PWM输出频率
    - Связи (вызовы): ProtoChassisPwmFreq, _send_sync_proto, val2proto
    - Аргументы:
      - `pwm1`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `pwm1`.
      - `pwm2`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `pwm2`.
      - `pwm3`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `pwm3`.
      - `pwm4`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `pwm4`.
      - `pwm5`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `pwm5`.
      - `pwm6`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `pwm6`.
    - Пример(ы) из репозитория:
      - `ep_chassis.set_pwm_freq(pwm1=50,pwm2=50,pwm3=50,pwm4=50,pwm5=50,pwm6=50)` (из `examples/02_chassis/11_pwm.py:27`)
  - `move`
    - Сигнатура: `move(self, x=0, y=0, z=0, xy_speed=0.5, z_speed=30)`
    - Приватный: нет
    - Описание: 控制底盘运动当指定位置，坐标轴原点为当前位置
    - Связи (вызовы): ChassisMoveAction, send_action
    - Аргументы:
      - `x`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; float: [-5,5]，x轴向运动距离，单位 m
      - `y`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; float: [-5,5]，y轴向运动距离，单位 m
      - `z`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; float: [-1800,1800]，z轴向旋转角度，单位 °
      - `xy_speed`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; float: [0.5,2]，xy轴向运动速度，单位 m/s
      - `z_speed`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; float: [10,540]，z轴向旋转速度，单位 °/s
    - Пример(ы) из репозитория:
      - `ep_chassis.move(x=x_val, y=0, z=0, xy_speed=0.7).wait_for_completed()` (из `examples/02_chassis/01_move.py:31`)
      - `ep_chassis.move(x=-x_val, y=0, z=0, xy_speed=0.7).wait_for_completed()` (из `examples/02_chassis/01_move.py:34`)
  - `sub_position`
    - Сигнатура: `sub_position(self, cs=0, freq=5, callback=None, *args, **kw)`
    - Приватный: нет
    - Описание: 订阅底盘位置信息
    - Связи (вызовы): PositionSubject, add_subject_info
    - Аргументы:
      - `cs`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; int: [0,1] 设置底盘位置的坐标系，0 机器人当前位置，1 机器人上电位置
      - `freq`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; enum: (1, 5, 10, 20, 50) 设置数据订阅数据的推送频率，单位 Hz
      - `callback`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 回调函数，返回数据 (x, y, z):
      - `*args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 可变参数
      - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; 关键字参数
    - Пример(ы) из репозитория:
      - `ep_chassis.sub_position(freq=10, callback=sub_position_handler)` (из `examples/02_chassis/05_sub_position.py:33`)
      - `ep_chassis.sub_position(freq=1, callback=sub_info_handler)` (из `examples/02_chassis/09_sub_all.py:33`)
  - `unsub_position`
    - Сигнатура: `unsub_position(self)`
    - Приватный: нет
    - Описание: 取消订阅底盘位置信息
    - Связи (вызовы): del_subject_info
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `ep_chassis.unsub_position()` (из `examples/02_chassis/05_sub_position.py:35`)
      - `ep_chassis.unsub_position()` (из `examples/02_chassis/09_sub_all.py:53`)
  - `sub_attitude`
    - Сигнатура: `sub_attitude(self, freq=5, callback=None, *args, **kw)`
    - Приватный: нет
    - Описание: 订阅底盘姿态信息
    - Связи (вызовы): AttiInfoSubject, add_subject_info
    - Аргументы:
      - `freq`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; enum: (1, 5, 10, 20, 50) 设置数据订阅数据的推送频率，单位 Hz
      - `callback`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 回调函数，返回数据 (yaw, pitch, roll)：
      - `*args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 可变参数
      - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; 关键字参数
    - Пример(ы) из репозитория:
      - `ep_chassis.sub_attitude(freq=10, callback=sub_attitude_info_handler)` (из `examples/02_chassis/04_sub_attitude.py:33`)
      - `ep_chassis.sub_attitude(freq=5, callback=sub_info_handler)` (из `examples/02_chassis/09_sub_all.py:36`)
  - `unsub_attitude`
    - Сигнатура: `unsub_attitude(self)`
    - Приватный: нет
    - Описание: 取消订阅底盘姿态信息
    - Связи (вызовы): del_subject_info
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `ep_chassis.unsub_attitude()` (из `examples/02_chassis/04_sub_attitude.py:36`)
      - `ep_chassis.unsub_attitude()` (из `examples/02_chassis/09_sub_all.py:52`)
  - `sub_status`
    - Сигнатура: `sub_status(self, freq=5, callback=None, *args, **kw)`
    - Приватный: нет
    - Описание: 订阅底盘状态信息
    - Связи (вызовы): SaStatusSubject, add_subject_info
    - Аргументы:
      - `freq`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; enum: (1, 5, 10, 20, 50)，设置数据订阅数据的推送频率，单位 Hz
      - `callback`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 回调函数，返回数据 (static_flag, up_hill, down_hill, on_slope, is_pickup, slip_flag,         impact_x, impact_y, impact_z, roll_over, hill_static):
      - `*args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 可变参数
      - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; 关键字参数
    - Пример(ы) из репозитория:
      - `ep_chassis.sub_status(freq=5, callback=sub_status_info_handler)` (из `examples/02_chassis/07_sub_status.py:38`)
      - `ep_chassis.sub_status(freq=50, callback=sub_info_handler)` (из `examples/02_chassis/09_sub_all.py:45`)
  - `unsub_status`
    - Сигнатура: `unsub_status(self)`
    - Приватный: нет
    - Описание: 取消订阅底盘状态信息
    - Связи (вызовы): del_subject_info
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `ep_chassis.unsub_status()` (из `examples/02_chassis/07_sub_status.py:40`)
      - `ep_chassis.unsub_status()` (из `examples/02_chassis/09_sub_all.py:49`)
  - `sub_imu`
    - Сигнатура: `sub_imu(self, freq=5, callback=None, *args, **kw)`
    - Приватный: нет
    - Описание: 订阅底盘IMU陀螺仪信息
    - Связи (вызовы): ImuSubject, add_subject_info
    - Аргументы:
      - `freq`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; enum: (1, 5, 10, 20, 50)，设置数据订阅数据的推送频率，单位 Hz
      - `callback`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 回调函数，返回数据 (acc_x, acc_y, acc_z, gyro_x, gyro_y, gyro_z):
      - `*args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 可变参数
      - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; 关键字参数
    - Пример(ы) из репозитория:
      - `ep_chassis.sub_imu(freq=5, callback=sub_imu_info_handler)` (из `examples/02_chassis/06_sub_imu.py:35`)
      - `ep_chassis.sub_imu(freq=10, callback=sub_info_handler)` (из `examples/02_chassis/09_sub_all.py:39`)
  - `unsub_imu`
    - Сигнатура: `unsub_imu(self)`
    - Приватный: нет
    - Описание: 取消订阅底盘IMU陀螺仪信息
    - Связи (вызовы): del_subject_info
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `ep_chassis.unsub_imu()` (из `examples/02_chassis/06_sub_imu.py:37`)
      - `ep_chassis.unsub_imu()` (из `examples/02_chassis/09_sub_all.py:51`)
  - `sub_mode`
    - Сигнатура: `sub_mode(self, freq=5, callback=None, *args, **kw)`
    - Приватный: нет
    - Описание: 订阅底盘模式信息
    - Связи (вызовы): ChassisModeSubject, add_subject_info
    - Аргументы:
      - `freq`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; enum: (1, 5, 10, 20, 50)，设置数据订阅数据的推送频率，单位 Hz
      - `callback`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 回调函数，返回数据 mode:
      - `*args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 可变参数
      - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; 关键字参数
    - Пример: `obj.sub_mode()`
  - `unsub_mode`
    - Сигнатура: `unsub_mode(self)`
    - Приватный: нет
    - Описание: 取消订阅底盘模式信息
    - Связи (вызовы): del_subject_info
    - Аргументы:
      - нет аргументов
    - Пример: `obj.unsub_mode()`
  - `sub_esc`
    - Сигнатура: `sub_esc(self, freq=5, callback=None, *args, **kw)`
    - Приватный: нет
    - Описание: 订阅底盘电调信息
    - Связи (вызовы): EscSubject, add_subject_info
    - Аргументы:
      - `freq`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; enum: (1, 5, 10, 20, 50)，设置数据订阅数据的推送频率，单位 Hz
      - `callback`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 回调函数，返回数据 (speed[4], angle[4], timestamp, state):
      - `*args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 可变参数
      - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; 关键字参数
    - Пример(ы) из репозитория:
      - `ep_chassis.sub_esc(freq=5, callback=sub_esc_info_handler)` (из `examples/02_chassis/08_sub_esc.py:34`)
      - `ep_chassis.sub_esc(freq=20, callback=sub_info_handler)` (из `examples/02_chassis/09_sub_all.py:42`)
  - `unsub_esc`
    - Сигнатура: `unsub_esc(self)`
    - Приватный: нет
    - Описание: 取消订阅电调信息
    - Связи (вызовы): del_subject_info
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `ep_chassis.unsub_esc()` (из `examples/02_chassis/08_sub_esc.py:37`)
      - `ep_chassis.unsub_esc()` (из `examples/02_chassis/09_sub_all.py:50`)
  - `sub_velocity`
    - Сигнатура: `sub_velocity(self, freq=5, callback=None, *args, **kw)`
    - Приватный: нет
    - Описание: 订阅底盘加速度信息
    - Связи (вызовы): VelocitySubject, add_subject_info
    - Аргументы:
      - `freq`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; enum:(1, 5, 10, 20, 50) 设置数据订阅数据的推送频率，单位 Hz
      - `callback`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 回调函数，返回数据（vgx, vgy, vgz, vbx, vby, vbz)：
      - `*args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 可变参数
      - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; 关键字参数
    - Пример: `obj.sub_velocity()`
  - `unsub_velocity`
    - Сигнатура: `unsub_velocity(self)`
    - Приватный: нет
    - Описание: 取消订阅底盘加速度信息
    - Связи (вызовы): del_subject_info
    - Аргументы:
      - нет аргументов
    - Пример: `obj.unsub_velocity()`
  - `_sub_sbus` (приватный)
    - Сигнатура: `_sub_sbus(self, freq=5, callback=None, *args, **kw)`
    - Приватный: да
    - Описание: 订阅底盘SBUS信息
    - Связи (вызовы): SbusSubject, add_subject_info
    - Аргументы:
      - `freq`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; enum: (1, 5, 10, 20, 50)，设置数据订阅数据的推送频率，单位 Hz
      - `callback`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 回调函数，返回数据 (connect_status, sbus_channel[16]):
      - `*args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 可变参数
      - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; 关键字参数
    - Пример: `obj._sub_sbus()`
  - `_unsub_sbus` (приватный)
    - Сигнатура: `_unsub_sbus(self)`
    - Приватный: да
    - Описание: 取消订阅SBUS信息
    - Связи (вызовы): del_subject_info
    - Аргументы:
      - нет аргументов
    - Пример: `obj._unsub_sbus()`


## Модуль `src.robomaster.client` (`src/robomaster/client.py`)

### Классы

### `EventIdentify`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): Event
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)

### `MsgHandler`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self, proto_data=None, req_cb=None, ack_cb=None)`
  - **Аргументы конструктора:**
    - `proto_data`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `proto_data`.
    - `req_cb`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `req_cb`.
    - `ack_cb`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `ack_cb`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, proto_data=None, req_cb=None, ack_cb=None)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `proto_data`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `proto_data`.
      - `req_cb`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `req_cb`.
      - `ack_cb`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `ack_cb`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `proto_data`
    - Сигнатура: `proto_data(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.proto_data()`
  - `make_dict_key`
    - Сигнатура: `make_dict_key(cmd_set, cmd_id)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `cmd_set`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `cmd_set`.
      - `cmd_id`: тип `не указан`; единицы `не указаны`; допустимые значения `ID/целое`; параметр `cmd_id`.
    - Пример: `obj.make_dict_key(..., ...)`
  - `dict_key`
    - Сигнатура: `dict_key(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): debug, isinstance, make_dict_key
    - Аргументы:
      - нет аргументов
    - Пример: `obj.dict_key()`

### `Client`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self, host=0, index=0, connect=None)`
  - **Аргументы конструктора:**
    - `host`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; инициализационный параметр `host`.
    - `index`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; инициализационный параметр `index`.
    - `connect`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; инициализационный параметр `connect`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, host=0, index=0, connect=None)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): Dispatcher, Lock, Connection, error, format
    - Аргументы:
      - `host`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `host`.
      - `index`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `index`.
      - `connect`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `connect`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `__del__` (приватный)
    - Сигнатура: `__del__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): stop
    - Аргументы:
      - нет аргументов
    - Пример: `obj.__del__()`
  - `remote_addr`
    - Сигнатура: `remote_addr(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): print
    - Аргументы:
      - нет аргументов
    - Пример: `obj.remote_addr()`
  - `add_handler`
    - Сигнатура: `add_handler(self, obj, name, f)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): add_handler
    - Аргументы:
      - `obj`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `obj`.
      - `name`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `name`.
      - `f`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `f`.
    - Пример: `obj.add_handler(..., ..., ...)`
  - `remove_handler`
    - Сигнатура: `remove_handler(self, name)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): remove_handler
    - Аргументы:
      - `name`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `name`.
    - Пример: `obj.remove_handler(...)`
  - `initialize`
    - Сигнатура: `initialize(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): range, warning, EventIdentify, append, create
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `ep_robot.initialize(conn_type='rndis')` (из `examples/01_robot/00_logger.py:30`)
      - `ep_robot.initialize(conn_type="ap")` (из `examples/01_robot/01_get_version.py:22`)
  - `hostbyte`
    - Сигнатура: `hostbyte(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): host2byte
    - Аргументы:
      - нет аргументов
    - Пример: `obj.hostbyte()`
  - `start`
    - Сигнатура: `start(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): initialize, Thread, start
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `self.cmd_socket_recv_thread.start()` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:90`)
      - `t.start()` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_callbacks.py:135`)
  - `stop`
    - Сигнатура: `stop(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): is_alive, ProtoGetVersion, Msg, send_self, join, close
    - Аргументы:
      - нет аргументов
    - Пример: `obj.stop()`
  - `send_msg`
    - Сигнатура: `send_msg(self, msg)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): pack, debug, send, format, hexlify
    - Аргументы:
      - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
    - Пример: `obj.send_msg(...)`
  - `send_sync_msg`
    - Сигнатура: `send_sync_msg(self, msg, callback=None, timeout=3.0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): error, _ack_register_identify, send_msg, wait, _ack_unregister_identify, isSet
    - Аргументы:
      - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
      - `callback`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `callback`.
      - `timeout`: тип `не указан`; единицы `с`; допустимые значения `не указаны`; параметр `timeout`.
    - Пример: `obj.send_sync_msg(...)`
  - `resp_msg`
    - Сигнатура: `resp_msg(self, msg)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): pack, send
    - Аргументы:
      - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
    - Пример: `obj.resp_msg(...)`
  - `send`
    - Сигнатура: `send(self, data)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): send, warning, format, str
    - Аргументы:
      - `data`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `data`.
    - Пример(ы) из репозитория:
      - `return socket_obj.send(data.encode('utf-8'))` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:217`)
  - `send_async_msg`
    - Сигнатура: `send_async_msg(self, msg)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): send_msg, error
    - Аргументы:
      - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
    - Пример: `obj.send_async_msg(...)`
  - `is_ready`
    - Сигнатура: `is_ready(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.is_ready()`
  - `_recv_task` (приватный)
    - Сигнатура: `_recv_task(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): info, recv, _dispatch_to_send_sync, _dispatch_to_callback, warning, format
    - Аргументы:
      - нет аргументов
    - Пример: `obj._recv_task()`
  - `_dispatch_to_send_sync` (приватный)
    - Сигнатура: `_dispatch_to_send_sync(self, msg)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): debug, _make_ack_identify, acquire, release, format, keys
    - Аргументы:
      - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
    - Пример: `obj._dispatch_to_send_sync(...)`
  - `_dispatch_to_callback` (приватный)
    - Сигнатура: `_dispatch_to_callback(self, msg)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): make_dict_key, keys, _ack_cb, debug, _req_cb, format
    - Аргументы:
      - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
    - Пример: `obj._dispatch_to_callback(...)`
  - `_make_ack_identify` (приватный)
    - Сигнатура: `_make_ack_identify(msg)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): str, hex
    - Аргументы:
      - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
    - Пример: `obj._make_ack_identify(...)`
  - `_ack_register_identify` (приватный)
    - Сигнатура: `_ack_register_identify(self, msg)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): acquire, _make_ack_identify, release, enumerate, clear, error
    - Аргументы:
      - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
    - Пример: `obj._ack_register_identify(...)`
  - `_ack_unregister_identify` (приватный)
    - Сигнатура: `_ack_unregister_identify(self, identify)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): acquire, release, keys, pop, warning, format
    - Аргументы:
      - `identify`: тип `не указан`; единицы `м`; допустимые значения `ID/целое`; параметр `identify`.
    - Пример: `obj._ack_unregister_identify(...)`
  - `add_msg_handler`
    - Сигнатура: `add_msg_handler(self, handler)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): dict_key
    - Аргументы:
      - `handler`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `handler`.
    - Пример: `obj.add_msg_handler(...)`

### `TextClient`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self, conf)`
  - **Аргументы конструктора:**
    - `conf`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; инициализационный параметр `conf`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, conf)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): Connection, Thread, Event, Dispatcher, Lock
    - Аргументы:
      - `conf`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `conf`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `initialize`
    - Сигнатура: `initialize(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): create
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `ep_robot.initialize(conn_type='rndis')` (из `examples/01_robot/00_logger.py:30`)
      - `ep_robot.initialize(conn_type="ap")` (из `examples/01_robot/01_get_version.py:22`)
  - `start`
    - Сигнатура: `start(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): initialize, start
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `self.cmd_socket_recv_thread.start()` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:90`)
      - `t.start()` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_callbacks.py:135`)
  - `stop`
    - Сигнатура: `stop(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): join, close
    - Аргументы:
      - нет аргументов
    - Пример: `obj.stop()`
  - `check_is_dds_msg`
    - Сигнатура: `check_is_dds_msg(self, msg)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): get_buf
    - Аргументы:
      - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
    - Пример: `obj.check_is_dds_msg(...)`
  - `_recv_task` (приватный)
    - Сигнатура: `_recv_task(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): info, recv, acquire, release, warning, check_is_dds_msg
    - Аргументы:
      - нет аргументов
    - Пример: `obj._recv_task()`
  - `send`
    - Сигнатура: `send(self, text)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): debug, info, format, send, encode, warning
    - Аргументы:
      - `text`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `text`.
    - Пример(ы) из репозитория:
      - `return socket_obj.send(data.encode('utf-8'))` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:217`)
  - `send_sync_msg`
    - Сигнатура: `send_sync_msg(self, msg, callback=None, timeout=10)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): acquire, send_msg, release, wait, isSet, error
    - Аргументы:
      - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
      - `callback`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `callback`.
      - `timeout`: тип `не указан`; единицы `с`; допустимые значения `не указаны`; параметр `timeout`.
    - Пример: `obj.send_sync_msg(...)`
  - `send_async_msg`
    - Сигнатура: `send_async_msg(self, msg)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): send_msg, error
    - Аргументы:
      - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
    - Пример: `obj.send_async_msg(...)`
  - `send_msg`
    - Сигнатура: `send_msg(self, msg)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): pack, send
    - Аргументы:
      - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
    - Пример: `obj.send_msg(...)`
  - `add_handler`
    - Сигнатура: `add_handler(self, obj, name, f)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): add_handler
    - Аргументы:
      - `obj`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `obj`.
      - `name`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `name`.
      - `f`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `f`.
    - Пример: `obj.add_handler(..., ..., ...)`
  - `remove_handler`
    - Сигнатура: `remove_handler(self, name)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): remove_handler
    - Аргументы:
      - `name`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `name`.
    - Пример: `obj.remove_handler(...)`
  - `_dispatch_to_send_sync` (приватный)
    - Сигнатура: `_dispatch_to_send_sync(self, msg)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): debug, set, format
    - Аргументы:
      - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
    - Пример: `obj._dispatch_to_send_sync(...)`
  - `_make_ack_identify` (приватный)
    - Сигнатура: `_make_ack_identify(self, msg)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
    - Пример: `obj._make_ack_identify(...)`


## Модуль `src.robomaster.config` (`src/robomaster/config.py`)

### Классы

### `Config`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self, name)`
  - **Аргументы конструктора:**
    - `name`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; инициализационный параметр `name`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, name)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `name`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `name`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `default_cmd_addr_port`
    - Сигнатура: `default_cmd_addr_port(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.default_cmd_addr_port()`
  - `product`
    - Сигнатура: `product(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.product()`
  - `product`
    - Сигнатура: `product(self, val)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `val`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `val`.
    - Пример: `obj.product(...)`
  - `default_robot_addr`
    - Сигнатура: `default_robot_addr(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.default_robot_addr()`
  - `default_robot_addr`
    - Сигнатура: `default_robot_addr(self, val)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `val`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `val`.
    - Пример: `obj.default_robot_addr(...)`
  - `cmd_proto`
    - Сигнатура: `cmd_proto(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.cmd_proto()`
  - `cmd_proto`
    - Сигнатура: `cmd_proto(self, val)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `val`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `val`.
    - Пример: `obj.cmd_proto(...)`
  - `default_cmd_addr`
    - Сигнатура: `default_cmd_addr(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.default_cmd_addr()`
  - `default_cmd_addr`
    - Сигнатура: `default_cmd_addr(self, val)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `val`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `val`.
    - Пример: `obj.default_cmd_addr(...)`
  - `default_sdk_addr`
    - Сигнатура: `default_sdk_addr(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.default_sdk_addr()`
  - `default_sdk_addr`
    - Сигнатура: `default_sdk_addr(self, val)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `val`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `val`.
    - Пример: `obj.default_sdk_addr(...)`
  - `video_stream_addr`
    - Сигнатура: `video_stream_addr(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.video_stream_addr()`
  - `video_stream_addr`
    - Сигнатура: `video_stream_addr(self, val)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `val`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `val`.
    - Пример: `obj.video_stream_addr(...)`
  - `video_stream_port`
    - Сигнатура: `video_stream_port(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.video_stream_port()`
  - `video_stream_port`
    - Сигнатура: `video_stream_port(self, val)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `val`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `val`.
    - Пример: `obj.video_stream_port(...)`
  - `video_stream_proto`
    - Сигнатура: `video_stream_proto(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.video_stream_proto()`
  - `video_stream_proto`
    - Сигнатура: `video_stream_proto(self, val)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `val`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `val`.
    - Пример: `obj.video_stream_proto(...)`
  - `audio_stream_addr`
    - Сигнатура: `audio_stream_addr(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.audio_stream_addr()`
  - `audio_stream_addr`
    - Сигнатура: `audio_stream_addr(self, val)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `val`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `val`.
    - Пример: `obj.audio_stream_addr(...)`
  - `audio_stream_port`
    - Сигнатура: `audio_stream_port(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.audio_stream_port()`
  - `audio_stream_port`
    - Сигнатура: `audio_stream_port(self, val)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `val`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `val`.
    - Пример: `obj.audio_stream_port(...)`


## Модуль `src.robomaster.conn` (`src/robomaster/conn.py`)

### Функции

#### `get_local_ip`
- **Сигнатура:** `get_local_ip()`
- **Приватная:** нет
- **Описание:** 获取本地ip地址
- **Связи (вызовы):** gethostbyname, gethostname
- **Аргументы:**
  - нет аргументов
- **Пример:** `get_local_ip()`

#### `get_sn_form_data`
- **Сигнатура:** `get_sn_form_data(data)`
- **Приватная:** нет
- **Описание:** 从 data 中获取 sn 字段
- **Связи (вызовы):** split, decode
- **Аргументы:**
  - `data`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `data`.
- **Пример:** `get_sn_form_data(...)`

#### `scan_robot_ip`
- **Сигнатура:** `scan_robot_ip(user_sn=None, timeout=3.0)`
- **Приватная:** нет
- **Описание:** 扫描机器人的IP地址
- **Связи (вызовы):** time, socket, bind, settimeout, recvfrom, info
- **Аргументы:**
  - `user_sn`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `user_sn`.
  - `timeout`: тип `не указан`; единицы `с`; допустимые значения `не указаны`; параметр `timeout`.
- **Пример:** `scan_robot_ip()`

#### `scan_robot_ip_list`
- **Сигнатура:** `scan_robot_ip_list(timeout=3.0)`
- **Приватная:** нет
- **Описание:** 扫描局域网内的机器人IP地址
- **Связи (вызовы):** time, socket, bind, settimeout, info, warning
- **Аргументы:**
  - `timeout`: тип `не указан`; единицы `с`; допустимые значения `не указаны`; 超时时间
- **Пример(ы) из репозитория:**
  - `conn.scan_robot_ip_list(timeout=10)` (из `examples/15_multi_robot/multi_ep/01_scan_robot_sn.py:21`)

### Классы

### `BaseConnection`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): bytearray
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `create`
    - Сигнатура: `create(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): socket, bind, connect, info, warning, format
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `assert m.cpp_ref_any(m.ReturnTester.create()) == 1.` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_eigen.py:116`)
      - `assert m.cpp_ref_any(m.ReturnTester.create()) == 1.` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/tests/test_eigen.py:116`)
  - `close`
    - Сигнатура: `close(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): close
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `ep_robot.close()` (из `examples/01_robot/00_logger.py:34`)
      - `ep_robot.close()` (из `examples/01_robot/01_get_version.py:27`)
  - `recv`
    - Сигнатура: `recv(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): extend, decode_msg, warning, len, isinstance, recvfrom
    - Аргументы:
      - нет аргументов
    - Пример: `obj.recv()`
  - `send`
    - Сигнатура: `send(self, buf)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): sendto, warning, format
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
    - Пример(ы) из репозитория:
      - `return socket_obj.send(data.encode('utf-8'))` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:217`)
  - `send_self`
    - Сигнатура: `send_self(self, buf)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): sendto, warning, format
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
    - Пример: `obj.send_self(...)`

### `Connection`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self, host_addr, target_addr, proto='v1', protocol=CONNECTION_PROTO_UDP)`
  - **Аргументы конструктора:**
    - `host_addr`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `host_addr`.
    - `target_addr`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `target_addr`.
    - `proto`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `proto`.
    - `protocol`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `protocol`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, host_addr, target_addr, proto='v1', protocol=CONNECTION_PROTO_UDP)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): bytearray
    - Аргументы:
      - `host_addr`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `host_addr`.
      - `target_addr`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `target_addr`.
      - `proto`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `proto`.
      - `protocol`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `protocol`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `__repr__` (приватный)
    - Сигнатура: `__repr__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): format
    - Аргументы:
      - нет аргументов
    - Пример: `obj.__repr__()`
  - `target_addr`
    - Сигнатура: `target_addr(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.target_addr()`
  - `protocol`
    - Сигнатура: `protocol(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.protocol()`

### `SdkConnection`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): socket, setsockopt
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `__del__` (приватный)
    - Сигнатура: `__del__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): close
    - Аргументы:
      - нет аргументов
    - Пример: `obj.__del__()`
  - `switch_remote_route`
    - Сигнатура: `switch_remote_route(self, msg, remote_addr, timeout=5)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): pack, settimeout, sendto, recvfrom, debug, decode_msg
    - Аргументы:
      - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
      - `remote_addr`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `remote_addr`.
      - `timeout`: тип `не указан`; единицы `с`; допустимые значения `не указаны`; параметр `timeout`.
    - Пример: `obj.switch_remote_route(..., ...)`
  - `request_connection`
    - Сигнатура: `request_connection(self, sdk_host, conn_type=None, proto_type=None, sn=None)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): info, ProtoSetSdkConnection, Msg, error, format, randint
    - Аргументы:
      - `sdk_host`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `sdk_host`.
      - `conn_type`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `conn_type`.
      - `proto_type`: тип `не указан`; единицы `м`; допустимые значения `0..255`; параметр `proto_type`.
      - `sn`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `sn`.
    - Пример: `obj.request_connection(...)`

### `StreamConnection`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): Queue
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `__del__` (приватный)
    - Сигнатура: `__del__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): close
    - Аргументы:
      - нет аргументов
    - Пример: `obj.__del__()`
  - `connect`
    - Сигнатура: `connect(self, addr, ip_proto='tcp')`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): Thread, start, info, format, socket, settimeout
    - Аргументы:
      - `addr`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `addr`.
      - `ip_proto`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `ip_proto`.
    - Пример(ы) из репозитория:
      - `self.ctrl_socket.connect((self.robot_ip, RobotConnection.CTRL_PORT))` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:83`)
      - `self.event_socket.connect((self.robot_ip, RobotConnection.EVENT_PORT))` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:84`)
  - `disconnect`
    - Сигнатура: `disconnect(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): put, close, clear, info, join
    - Аргументы:
      - нет аргументов
    - Пример: `obj.disconnect()`
  - `_recv_task` (приватный)
    - Сигнатура: `_recv_task(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): info, recvfrom, full, warning, get, debug
    - Аргументы:
      - нет аргументов
    - Пример: `obj._recv_task()`
  - `read_buf`
    - Сигнатура: `read_buf(self, timeout=2)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): get, warning, format
    - Аргументы:
      - `timeout`: тип `не указан`; единицы `с`; допустимые значения `не указаны`; параметр `timeout`.
    - Пример: `obj.read_buf()`

### `ConnectionHelper`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): str, STAConnInfo, randint
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `build_qrcode_string`
    - Сигнатура: `build_qrcode_string(self, ssid='', password='')`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): set_info, pack, simple_encrypt, decode, b64encode
    - Аргументы:
      - `ssid`: тип `не указан`; единицы `не указаны`; допустимые значения `ID/целое`; параметр `ssid`.
      - `password`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `password`.
    - Пример(ы) из репозитория:
      - `info = helper.build_qrcode_string(ssid="RoboMaster_SDK_WIFI", password="12341234")` (из `examples/01_robot/05_sta_conn_helper.py:29`)
  - `get_qrcode_string`
    - Сигнатура: `get_qrcode_string(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): pack, simple_encrypt, decode, b64encode
    - Аргументы:
      - нет аргументов
    - Пример: `obj.get_qrcode_string()`
  - `wait_for_connection`
    - Сигнатура: `wait_for_connection(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): socket, bind, settimeout, info, recvfrom, warning
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `if helper.wait_for_connection():` (из `examples/01_robot/05_sta_conn_helper.py:34`)

### `FtpConnection`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): FTP, set_debuglevel
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `connect`
    - Сигнатура: `connect(self, ip)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): info, connect, format
    - Аргументы:
      - `ip`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `ip`.
    - Пример(ы) из репозитория:
      - `self.ctrl_socket.connect((self.robot_ip, RobotConnection.CTRL_PORT))` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:83`)
      - `self.event_socket.connect((self.robot_ip, RobotConnection.EVENT_PORT))` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:84`)
  - `upload`
    - Сигнатура: `upload(self, src_file, target_file)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): open, storbinary, close, warning, format
    - Аргументы:
      - `src_file`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `src_file`.
      - `target_file`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `target_file`.
    - Пример: `obj.upload(..., ...)`
  - `stop`
    - Сигнатура: `stop(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): close
    - Аргументы:
      - нет аргументов
    - Пример: `obj.stop()`


## Модуль `src.robomaster.dds` (`src/robomaster/dds.py`)

### Классы

### `_AutoRegisterSubject` (приватный класс)
- **Приватный класс:** да
- **Описание:** hepler to automatically register Proto Class whereever they're defined
- **Конструктор:** `__init__(cls, name, bases, attrs, **kw)`
  - **Аргументы конструктора:**
    - `name`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; инициализационный параметр `name`.
    - `bases`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `bases`.
    - `attrs`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `attrs`.
    - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; инициализационный параметр `**kw`.
- **Методы:**
  - `__new__` (приватный)
    - Сигнатура: `__new__(mcs, name, bases, attrs, **kw)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): __new__, super
    - Аргументы:
      - `mcs`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `mcs`.
      - `name`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `name`.
      - `bases`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `bases`.
      - `attrs`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `attrs`.
      - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `**kw`.
    - Пример(ы) из репозитория:
      - `m.TestFactory6.__init__(NotPybindDerived.__new__(NotPybindDerived), tag.base, 1)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_factory_constructors.py:447`)
      - `m.TestFactory6.__init__(NotPybindDerived.__new__(NotPybindDerived), tag.alias, 1)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_factory_constructors.py:449`)
  - `__init__` (приватный)
    - Сигнатура: `__init__(cls, name, bases, attrs, **kw)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): __init__, keys, ValueError, super, format
    - Аргументы:
      - `name`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `name`.
      - `bases`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `bases`.
      - `attrs`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `attrs`.
      - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `**kw`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)

### `Subject`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `__repr__` (приватный)
    - Сигнатура: `__repr__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): format
    - Аргументы:
      - нет аргументов
    - Пример: `obj.__repr__()`
  - `set_callback`
    - Сигнатура: `set_callback(self, callback, args, kw)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `callback`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `callback`.
      - `args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `args`.
      - `kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `kw`.
    - Пример: `obj.set_callback(..., ..., ...)`
  - `data_info`
    - Сигнатура: `data_info(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.data_info()`
  - `exec`
    - Сигнатура: `exec(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): _callback, data_info
    - Аргументы:
      - нет аргументов
    - Пример: `obj.exec()`

### `SubHandler`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** явно не определён.
- **Методы:**
  - отсутствуют

### `Subscriber`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self, robot)`
  - **Аргументы конструктора:**
    - `robot`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `robot`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, robot)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): __init__, defaultdict, Queue, ThreadPoolExecutor, super
    - Аргументы:
      - `robot`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `__del__` (приватный)
    - Сигнатура: `__del__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): stop
    - Аргументы:
      - нет аргументов
    - Пример: `obj.__del__()`
  - `get_next_subject_id`
    - Сигнатура: `get_next_subject_id(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.get_next_subject_id()`
  - `start`
    - Сигнатура: `start(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): Lock, add_handler, Thread, start
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `self.cmd_socket_recv_thread.start()` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:90`)
      - `t.start()` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_callbacks.py:135`)
  - `stop`
    - Сигнатура: `stop(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): shutdown, put, join
    - Аргументы:
      - нет аргументов
    - Пример: `obj.stop()`
  - `_msg_recv` (приватный)
    - Сигнатура: `_msg_recv(cls, self, msg)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): list, put
    - Аргументы:
      - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
    - Пример: `obj._msg_recv(...)`
  - `_dispatch_task` (приватный)
    - Сигнатура: `_dispatch_task(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): info, get, acquire, release, debug, get_proto
    - Аргументы:
      - нет аргументов
    - Пример: `obj._dispatch_task()`
  - `add_cmd_filter`
    - Сигнатура: `add_cmd_filter(self, cmd_set, cmd_id)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): add
    - Аргументы:
      - `cmd_set`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `cmd_set`.
      - `cmd_id`: тип `не указан`; единицы `не указаны`; допустимые значения `ID/целое`; параметр `cmd_id`.
    - Пример: `obj.add_cmd_filter(..., ...)`
  - `del_cmd_filter`
    - Сигнатура: `del_cmd_filter(self, cmd_set, cmd_id)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): remove
    - Аргументы:
      - `cmd_set`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `cmd_set`.
      - `cmd_id`: тип `не указан`; единицы `не указаны`; допустимые значения `ID/целое`; параметр `cmd_id`.
    - Пример: `obj.del_cmd_filter(..., ...)`
  - `add_subject_event_info`
    - Сигнатура: `add_subject_event_info(self, subject, callback=None, *args)`
    - Приватный: нет
    - Описание: 添加事件订阅
    - Связи (вызовы): set_callback, SubHandler, acquire, release, add_cmd_filter
    - Аргументы:
      - `subject`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 事件订阅对应的subject
      - `callback`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 事件订阅对应的解析函数
      - `*args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `*args`.
    - Пример: `obj.add_subject_event_info(...)`
  - `del_subject_event_info`
    - Сигнатура: `del_subject_event_info(self, subject)`
    - Приватный: нет
    - Описание: 删除事件订阅
    - Связи (вызовы): del_cmd_filter, done, cancel
    - Аргументы:
      - `subject`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 事件订阅对应的subject
    - Пример: `obj.del_subject_event_info(...)`
  - `add_subject_info`
    - Сигнатура: `add_subject_info(self, subject, callback=None, *args)`
    - Приватный: нет
    - Описание: 请求数据订阅底层接口
    - Связи (вызовы): set_callback, SubHandler, acquire, release, ProtoAddSubMsg, get_next_subject_id
    - Аргументы:
      - `subject`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 数据订阅对应subject
      - `callback`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 订阅数据对应的解析函数
      - `*args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `*args`.
    - Пример: `obj.add_subject_info(...)`
  - `del_subject_info`
    - Сигнатура: `del_subject_info(self, subject_name)`
    - Приватный: нет
    - Описание: 删除数据订阅消息
    - Связи (вызовы): debug, format, acquire, release, ProtoDelMsg, _send_sync_proto
    - Аргументы:
      - `subject_name`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 要删除的订阅subject
    - Пример: `obj.del_subject_info(...)`

### `TelloSubscriber`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self, robot)`
  - **Аргументы конструктора:**
    - `robot`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `robot`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, robot)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): defaultdict
    - Аргументы:
      - `robot`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `__del__` (приватный)
    - Сигнатура: `__del__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): stop
    - Аргументы:
      - нет аргументов
    - Пример: `obj.__del__()`
  - `start`
    - Сигнатура: `start(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): add_handler, Thread, start
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `self.cmd_socket_recv_thread.start()` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:90`)
      - `t.start()` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_callbacks.py:135`)
  - `stop`
    - Сигнатура: `stop(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): join
    - Аргументы:
      - нет аргументов
    - Пример: `obj.stop()`
  - `_msg_recv` (приватный)
    - Сигнатура: `_msg_recv(cls, self, msg)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): get_proto
    - Аргументы:
      - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
    - Пример: `obj._msg_recv(...)`
  - `_dispatch_task` (приватный)
    - Сигнатура: `_dispatch_task(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): info, get_proto, sleep, warning, format, decode
    - Аргументы:
      - нет аргументов
    - Пример: `obj._dispatch_task()`
  - `add_subject_info`
    - Сигнатура: `add_subject_info(self, subject, callback=None, *args)`
    - Приватный: нет
    - Описание: 请求数据订阅底层接口
    - Связи (вызовы): set_callback, SubHandler, debug
    - Аргументы:
      - `subject`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 数据订阅对应subject
      - `callback`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 订阅数据对应的解析函数
      - `*args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `*args`.
    - Пример: `obj.add_subject_info(...)`
  - `del_subject_info`
    - Сигнатура: `del_subject_info(self, subject_name)`
    - Приватный: нет
    - Описание: 删除数据订阅消息
    - Связи (вызовы): debug, format, warning
    - Аргументы:
      - `subject_name`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 要删除的订阅subject
    - Пример: `obj.del_subject_info(...)`
  - `freq`
    - Сигнатура: `freq(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.freq()`
  - `freq`
    - Сигнатура: `freq(self, in_freq)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `in_freq`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `in_freq`.
    - Пример: `obj.freq(...)`


## Модуль `src.robomaster.event` (`src/robomaster/event.py`)

### Классы

### `Handler`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** явно не определён.
- **Методы:**
  - отсутствуют

### `Dispatcher`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): defaultdict
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `add_handler`
    - Сигнатура: `add_handler(self, obj, name, f)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): Handler, debug, format
    - Аргументы:
      - `obj`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `obj`.
      - `name`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `name`.
      - `f`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `f`.
    - Пример: `obj.add_handler(..., ..., ...)`
  - `remove_handler`
    - Сигнатура: `remove_handler(self, name)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `name`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `name`.
    - Пример: `obj.remove_handler(...)`
  - `dispatch`
    - Сигнатура: `dispatch(self, msg, **kw)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): f
    - Аргументы:
      - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
      - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `**kw`.
    - Пример(ы) из репозитория:
      - `super(PyClass2, self).dispatch()` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_virtual_functions.py:219`)
      - `super(PyClass2, self).dispatch()` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/tests/test_virtual_functions.py:219`)


## Модуль `src.robomaster.exceptions` (`src/robomaster/exceptions.py`)

### Классы

### `SDKException`
- **Приватный класс:** нет
- **Описание:** Base class of all SDK exceptions.
- **Конструктор:** явно не определён.
- **Методы:**
  - отсутствуют

### `TimeOutError`
- **Приватный класс:** нет
- **Описание:** Remote Call Timeout.
- **Конструктор:** явно не определён.
- **Методы:**
  - отсутствуют

### `OutOfRangeError`
- **Приватный класс:** нет
- **Описание:** Params Values OutOfRange.
- **Конструктор:** явно не определён.
- **Методы:**
  - отсутствуют

### `ConnectionError`
- **Приватный класс:** нет
- **Описание:** Connection TimeOut.
- **Конструктор:** явно не определён.
- **Методы:**
  - отсутствуют


## Модуль `src.robomaster.flight` (`src/robomaster/flight.py`)

### Классы

### `FlightAction`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self, text_cmd, **kw)`
  - **Аргументы конструктора:**
    - `text_cmd`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; инициализационный параметр `text_cmd`.
    - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; инициализационный параметр `**kw`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, text_cmd, **kw)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): __init__, print, format, super
    - Аргументы:
      - `text_cmd`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `text_cmd`.
      - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `**kw`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `encode`
    - Сигнатура: `encode(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): _action_proto_cls
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `return socket_obj.send(data.encode('utf-8'))` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:217`)
      - `ser.write('command'.encode('utf-8'))` (из `examples/plaintext_sample_code/RoboMasterEP/connection/uart/uart_connection.py:16`)
  - `update_from_push`
    - Сигнатура: `update_from_push(self, proto)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): _update_action_state, info, warning, format, vars
    - Аргументы:
      - `proto`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `proto`.
    - Пример: `obj.update_from_push(...)`

### `TelloAttiInfoSubject`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `atti_info`
    - Сигнатура: `atti_info(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.atti_info()`
  - `data_info`
    - Сигнатура: `data_info(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.data_info()`
  - `decode`
    - Сигнатура: `decode(self, buf)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): split, warning, int, format
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
    - Пример(ы) из репозитория:
      - `msg = msg.decode('utf-8')` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:68`)
      - `assert m.str_from_string().encode().decode() == "baz"` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_pytypes.py:73`)
  - `freq`
    - Сигнатура: `freq(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.freq()`
  - `freq`
    - Сигнатура: `freq(self, in_freq)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `in_freq`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `in_freq`.
    - Пример: `obj.freq(...)`

### `TelloImuInfoSubject`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `Imu_info`
    - Сигнатура: `Imu_info(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.Imu_info()`
  - `data_info`
    - Сигнатура: `data_info(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.data_info()`
  - `decode`
    - Сигнатура: `decode(self, buf)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): split, debug, float, format
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
    - Пример(ы) из репозитория:
      - `msg = msg.decode('utf-8')` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:68`)
      - `assert m.str_from_string().encode().decode() == "baz"` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_pytypes.py:73`)
  - `freq`
    - Сигнатура: `freq(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.freq()`
  - `freq`
    - Сигнатура: `freq(self, in_freq)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `in_freq`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `in_freq`.
    - Пример: `obj.freq(...)`

### `Flight`
- **Приватный класс:** нет
- **Описание:** 教育无人机 飞行器模块
- **Конструктор:** `__init__(self, robot)`
  - **Аргументы конструктора:**
    - `robot`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `robot`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, robot)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `robot`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `takeoff`
    - Сигнатура: `takeoff(self, retry=True)`
    - Приватный: нет
    - Описание: 自动起飞
    - Связи (вызовы): FlightAction, send_action, range, format
    - Аргументы:
      - `retry`: тип `не указан`; единицы `м`; допустимые значения `0..255`; параметр `retry`.
    - Пример(ы) из репозитория:
      - `tl_flight.takeoff().wait_for_completed()` (из `examples/12_drone/05_takeoff_land.py:28`)
      - `tl_flight.takeoff().wait_for_completed()` (из `examples/12_drone/06_rotate.py:28`)
  - `land`
    - Сигнатура: `land(self, retry=True)`
    - Приватный: нет
    - Описание: 自动降落
    - Связи (вызовы): FlightAction, send_action, range, format
    - Аргументы:
      - `retry`: тип `не указан`; единицы `м`; допустимые значения `0..255`; параметр `retry`.
    - Пример(ы) из репозитория:
      - `tl_flight.land().wait_for_completed()` (из `examples/12_drone/05_takeoff_land.py:29`)
      - `tl_flight.land().wait_for_completed()` (из `examples/12_drone/06_rotate.py:35`)
  - `up`
    - Сигнатура: `up(self, distance=0, retry=True)`
    - Приватный: нет
    - Описание: 向上飞distance厘米，指相对距离
    - Связи (вызовы): fly
    - Аргументы:
      - `distance`: тип `не указан`; единицы `см`; допустимые значения `не указаны`; параметр `distance`.
      - `retry`: тип `не указан`; единицы `м`; допустимые значения `0..255`; параметр `retry`.
    - Пример(ы) из репозитория:
      - `tl_flight.up(distance=20).wait_for_completed()` (из `examples/12_drone/08_up_down.py:31`)
      - `robot_group.up(50).wait_for_completed()` (из `examples/15_multi_robot/multi_drone/04_flight.py:23`)
  - `down`
    - Сигнатура: `down(self, distance=0, retry=True)`
    - Приватный: нет
    - Описание: 向下飞distance厘米，指相对距离
    - Связи (вызовы): fly
    - Аргументы:
      - `distance`: тип `не указан`; единицы `см`; допустимые значения `не указаны`; параметр `distance`.
      - `retry`: тип `не указан`; единицы `м`; допустимые значения `0..255`; параметр `retry`.
    - Пример(ы) из репозитория:
      - `tl_flight.down(distance=20).wait_for_completed()` (из `examples/12_drone/08_up_down.py:32`)
      - `robot_group.down(50).wait_for_completed()` (из `examples/15_multi_robot/multi_drone/04_flight.py:22`)
  - `forward`
    - Сигнатура: `forward(self, distance=0, retry=True)`
    - Приватный: нет
    - Описание: 向前飞行distance厘米，指相对距离
    - Связи (вызовы): fly
    - Аргументы:
      - `distance`: тип `не указан`; единицы `см`; допустимые значения `не указаны`; параметр `distance`.
      - `retry`: тип `не указан`; единицы `м`; допустимые значения `0..255`; параметр `retry`.
    - Пример(ы) из репозитория:
      - `tl_flight.forward(distance=50).wait_for_completed()` (из `examples/12_drone/07_forward_backward.py:31`)
      - `robot_group.forward(100).wait_for_completed()` (из `examples/15_multi_robot/multi_drone/03_takeoff_land.py:22`)
  - `backward`
    - Сигнатура: `backward(self, distance=0, retry=True)`
    - Приватный: нет
    - Описание: 向后飞行distance厘米， 指相对距离
    - Связи (вызовы): fly
    - Аргументы:
      - `distance`: тип `не указан`; единицы `см`; допустимые значения `не указаны`; параметр `distance`.
      - `retry`: тип `не указан`; единицы `м`; допустимые значения `0..255`; параметр `retry`.
    - Пример(ы) из репозитория:
      - `tl_flight.backward(distance=50).wait_for_completed()` (из `examples/12_drone/07_forward_backward.py:32`)
      - `robot_group.backward(100).wait_for_completed()` (из `examples/15_multi_robot/multi_drone/03_takeoff_land.py:28`)
  - `left`
    - Сигнатура: `left(self, distance=0, retry=True)`
    - Приватный: нет
    - Описание: 向左飞行distance厘米， 指相对距离
    - Связи (вызовы): fly
    - Аргументы:
      - `distance`: тип `не указан`; единицы `см`; допустимые значения `не указаны`; параметр `distance`.
      - `retry`: тип `не указан`; единицы `м`; допустимые значения `0..255`; параметр `retry`.
    - Пример(ы) из репозитория:
      - `tl_flight.left(distance=50).wait_for_completed()` (из `examples/12_drone/09_left_right.py:31`)
      - `robot_group.left(50).wait_for_completed()` (из `examples/15_multi_robot/multi_drone/04_flight.py:28`)
  - `right`
    - Сигнатура: `right(self, distance=0, retry=True)`
    - Приватный: нет
    - Описание: 向右飞行distance厘米， 指相对距离
    - Связи (вызовы): fly
    - Аргументы:
      - `distance`: тип `не указан`; единицы `см`; допустимые значения `не указаны`; параметр `distance`.
      - `retry`: тип `не указан`; единицы `м`; допустимые значения `0..255`; параметр `retry`.
    - Пример(ы) из репозитория:
      - `tl_flight.right(distance=50).wait_for_completed()` (из `examples/12_drone/09_left_right.py:32`)
      - `robot_group.right(50).wait_for_completed()` (из `examples/15_multi_robot/multi_drone/04_flight.py:26`)
  - `fly`
    - Сигнатура: `fly(self, direction=FORWARD, distance=0, retry=True)`
    - Приватный: нет
    - Описание: 控制飞机向指定方向飞行指定距离。
    - Связи (вызовы): format, FlightAction, send_action, range
    - Аргументы:
      - `direction`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `direction`.
      - `distance`: тип `не указан`; единицы `см`; допустимые значения `не указаны`; параметр `distance`.
      - `retry`: тип `не указан`; единицы `м`; допустимые значения `0..255`; параметр `retry`.
    - Пример: `obj.fly()`
  - `rotate`
    - Сигнатура: `rotate(self, angle=0, retry=True)`
    - Приватный: нет
    - Описание: 控制飞机旋转指定角度
    - Связи (вызовы): format, FlightAction, send_action, range
    - Аргументы:
      - `angle`: тип `не указан`; единицы `°`; допустимые значения `0..255`; параметр `angle`.
      - `retry`: тип `не указан`; единицы `м`; допустимые значения `0..255`; параметр `retry`.
    - Пример(ы) из репозитория:
      - `tl_flight.rotate(angle=180).wait_for_completed()` (из `examples/12_drone/06_rotate.py:31`)
      - `tl_flight.rotate(angle=-180).wait_for_completed()` (из `examples/12_drone/06_rotate.py:32`)
  - `flip_forward`
    - Сигнатура: `flip_forward(self, retry=True)`
    - Приватный: нет
    - Описание: 控制飞机向前翻滚
    - Связи (вызовы): flip
    - Аргументы:
      - `retry`: тип `не указан`; единицы `м`; допустимые значения `0..255`; параметр `retry`.
    - Пример(ы) из репозитория:
      - `tl_flight.flip_forward().wait_for_completed()` (из `examples/12_drone/12_flip.py:31`)
  - `flip_backward`
    - Сигнатура: `flip_backward(self, retry=True)`
    - Приватный: нет
    - Описание: 控制飞机向后翻滚
    - Связи (вызовы): flip
    - Аргументы:
      - `retry`: тип `не указан`; единицы `м`; допустимые значения `0..255`; параметр `retry`.
    - Пример(ы) из репозитория:
      - `tl_flight.flip_backward().wait_for_completed()` (из `examples/12_drone/12_flip.py:32`)
  - `flip_left`
    - Сигнатура: `flip_left(self, retry=True)`
    - Приватный: нет
    - Описание: 控制飞机向左翻滚
    - Связи (вызовы): flip
    - Аргументы:
      - `retry`: тип `не указан`; единицы `м`; допустимые значения `0..255`; параметр `retry`.
    - Пример(ы) из репозитория:
      - `tl_flight.flip_left().wait_for_completed()` (из `examples/12_drone/12_flip.py:33`)
  - `flip_right`
    - Сигнатура: `flip_right(self, retry=True)`
    - Приватный: нет
    - Описание: 控制飞机向右翻滚
    - Связи (вызовы): flip
    - Аргументы:
      - `retry`: тип `не указан`; единицы `м`; допустимые значения `0..255`; параметр `retry`.
    - Пример(ы) из репозитория:
      - `tl_flight.flip_right().wait_for_completed()` (из `examples/12_drone/12_flip.py:34`)
  - `flip`
    - Сигнатура: `flip(self, direction='f', retry=True)`
    - Приватный: нет
    - Описание: 控制飞机向指定方向翻滚
    - Связи (вызовы): format, FlightAction, send_action, range
    - Аргументы:
      - `direction`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; string: 飞机翻转的方向， ’l‘ 向左翻滚，’r‘ 向右翻滚，’f‘ 向前翻滚， ’b‘ 向后翻滚
      - `retry`: тип `не указан`; единицы `м`; допустимые значения `0..255`; параметр `retry`.
    - Пример: `obj.flip()`
  - `throw_fly`
    - Сигнатура: `throw_fly(self)`
    - Приватный: нет
    - Описание: 控制飞机抛飞
    - Связи (вызовы): FlightAction, send_action
    - Аргументы:
      - нет аргументов
    - Пример: `obj.throw_fly()`
  - `go`
    - Сигнатура: `go(self, x, y, z, speed=10, mid=None, retry=True)`
    - Приватный: нет
    - Описание: 控制飞机以设置速度飞向指定坐标位置
    - Связи (вызовы): format, FlightAction, send_action, range
    - Аргументы:
      - `x`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `x`.
      - `y`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `y`.
      - `z`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `z`.
      - `speed`: тип `не указан`; единицы `м/с`; допустимые значения `не указаны`; параметр `speed`.
      - `mid`: тип `не указан`; единицы `не указаны`; допустимые значения `ID/целое`; параметр `mid`.
      - `retry`: тип `не указан`; единицы `м`; допустимые значения `0..255`; параметр `retry`.
    - Пример(ы) из репозитория:
      - `tl_flight.go(x=100, y=100, z=30, speed=30).wait_for_completed()` (из `examples/12_drone/10_go.py:31`)
      - `tl_flight.go(x=-100, y=-100, z=-30, speed=30).wait_for_completed()` (из `examples/12_drone/10_go.py:32`)
  - `move`
    - Сигнатура: `move(self, x=0, y=0, z=0, speed=10, mid=None, retry=True)`
    - Приватный: нет
    - Описание: 飞机相对位置的控制
    - Связи (вызовы): get_status, info, go, error, format
    - Аргументы:
      - `x`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `x`.
      - `y`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `y`.
      - `z`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `z`.
      - `speed`: тип `не указан`; единицы `м/с`; допустимые значения `не указаны`; параметр `speed`.
      - `mid`: тип `не указан`; единицы `не указаны`; допустимые значения `ID/целое`; параметр `mid`.
      - `retry`: тип `не указан`; единицы `м`; допустимые значения `0..255`; параметр `retry`.
    - Пример(ы) из репозитория:
      - `ep_chassis.move(x=x_val, y=0, z=0, xy_speed=0.7).wait_for_completed()` (из `examples/02_chassis/01_move.py:31`)
      - `ep_chassis.move(x=-x_val, y=0, z=0, xy_speed=0.7).wait_for_completed()` (из `examples/02_chassis/01_move.py:34`)
  - `moveto`
    - Сигнатура: `moveto(self, yaw=0, retry=True)`
    - Приватный: нет
    - Описание: 控制飞机旋转到挑战卡坐标系中指定的绝对角度
    - Связи (вызовы): get_status, debug, info, rotate, format
    - Аргументы:
      - `yaw`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `yaw`.
      - `retry`: тип `не указан`; единицы `м`; допустимые значения `0..255`; параметр `retry`.
    - Пример(ы) из репозитория:
      - `ep_gimbal.moveto(pitch=0, yaw=0).wait_for_completed()` (из `examples/03_gimbal/01_move.py:32`)
      - `ep_gimbal.moveto(pitch=15, yaw=90, pitch_speed=50, yaw_speed=100).wait_for_completed()` (из `examples/03_gimbal/01_move.py:35`)
  - `rc`
    - Сигнатура: `rc(self, a=0, b=0, c=0, d=0)`
    - Приватный: нет
    - Описание: 控制飞机遥控器的四个杆量
    - Связи (вызовы): format, TextProtoDrone, TextMsg, send_async_msg, warning, str
    - Аргументы:
      - `a`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; float:[-100, 100] 横滚
      - `b`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; float:[-100, 100] 俯仰
      - `c`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; float:[-100, 100] 油门
      - `d`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; float:[-100, 100] 偏航
    - Пример(ы) из репозитория:
      - `tl_flight.rc(a=20, b=0, c=0, d=0)` (из `examples/12_drone/13_rc.py:31`)
      - `tl_flight.rc(a=-20, b=0, c=0, d=0)` (из `examples/12_drone/13_rc.py:35`)
  - `curve`
    - Сигнатура: `curve(self, x1=0, y1=0, z1=0, x2=0, y2=0, z2=0, speed=20, mid=None, retry=True)`
    - Приватный: нет
    - Описание: 以设置速度飞弧线，经过对应坐标系中的(x1, y1, z1)点到（x2, y2, z2）点
    - Связи (вызовы): format, FlightAction, send_action, range
    - Аргументы:
      - `x1`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `x1`.
      - `y1`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `y1`.
      - `z1`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `z1`.
      - `x2`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `x2`.
      - `y2`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `y2`.
      - `z2`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `z2`.
      - `speed`: тип `не указан`; единицы `м/с`; допустимые значения `не указаны`; параметр `speed`.
      - `mid`: тип `не указан`; единицы `не указаны`; допустимые значения `ID/целое`; параметр `mid`.
      - `retry`: тип `не указан`; единицы `м`; допустимые значения `0..255`; параметр `retry`.
    - Пример(ы) из репозитория:
      - `tl_flight.curve(x1=60, y1=60, z1=0, x2=120, y2=0, z2=30, speed=30).wait_for_completed()` (из `examples/12_drone/11_curve.py:32`)
      - `tl_flight.curve(x1=-60, y1=60, z1=0, x2=-120, y2=0, z2=-30, speed=30).wait_for_completed()` (из `examples/12_drone/11_curve.py:33`)
  - `stop`
    - Сигнатура: `stop(self, retry=True)`
    - Приватный: нет
    - Описание: 停止rc运动并悬停，任何时候都可以
    - Связи (вызовы): FlightAction, send_action, range, format
    - Аргументы:
      - `retry`: тип `не указан`; единицы `м`; допустимые значения `0..255`; параметр `retry`.
    - Пример: `obj.stop()`
  - `jump`
    - Сигнатура: `jump(self, x=0, y=0, z=0, speed=20, yaw=0, mid1='m-1', mid2='m-1', retry=True)`
    - Приватный: нет
    - Описание: 飞行器飞往mid1坐标系的(x, y, z)点后悬停，识别mid2的挑战卡，飞到mid2坐标系下(0, 0, z)的位置并且旋转到设定的yaw值
    - Связи (вызовы): format, FlightAction, send_action, range
    - Аргументы:
      - `x`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `x`.
      - `y`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `y`.
      - `z`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `z`.
      - `speed`: тип `не указан`; единицы `м/с`; допустимые значения `не указаны`; параметр `speed`.
      - `yaw`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `yaw`.
      - `mid1`: тип `не указан`; единицы `не указаны`; допустимые значения `ID/целое`; параметр `mid1`.
      - `mid2`: тип `не указан`; единицы `не указаны`; допустимые значения `ID/целое`; параметр `mid2`.
      - `retry`: тип `не указан`; единицы `м`; допустимые значения `0..255`; параметр `retry`.
    - Пример(ы) из репозитория:
      - `tl_flight.jump(x=0, y=0, z=100, speed=20, yaw=90, mid1="m1", mid2="m2").wait_for_completed()` (из `examples/12_drone/15_jump.py:33`)
      - `tl_flight.jump(x=0, y=0, z=100, speed=20, yaw=-90, mid1="m1", mid2="m2").wait_for_completed()` (из `examples/12_drone/15_jump.py:34`)
  - `set_speed`
    - Сигнатура: `set_speed(self, speed=0)`
    - Приватный: нет
    - Описание: 设置当前飞行速度
    - Связи (вызовы): format, TextProtoDrone, TextMsg, send_sync_msg, get_proto, warning
    - Аргументы:
      - `speed`: тип `не указан`; единицы `м/с`; допустимые значения `не указаны`; float:[10, 100]，飞行速度，单位 cm/s
    - Пример: `obj.set_speed()`
  - `mission_pad_on`
    - Сигнатура: `mission_pad_on(self)`
    - Приватный: нет
    - Описание: 打开挑战卡探测
    - Связи (вызовы): _pad_detection
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `tl_flight.mission_pad_on()` (из `examples/12_drone/14_mission_pad.py:30`)
      - `tl_flight.mission_pad_on()` (из `examples/12_drone/15_jump.py:28`)
  - `mission_pad_off`
    - Сигнатура: `mission_pad_off(self)`
    - Приватный: нет
    - Описание: 关闭挑战卡探测
    - Связи (вызовы): _pad_detection
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `tl_flight.mission_pad_off()` (из `examples/12_drone/14_mission_pad.py:45`)
      - `tl_flight.mission_pad_off()` (из `examples/12_drone/15_jump.py:37`)
  - `_pad_detection` (приватный)
    - Сигнатура: `_pad_detection(self, on_off=1)`
    - Приватный: да
    - Описание: 挑战卡检测功能开启/关闭的底层控制接口
    - Связи (вызовы): TextProtoDrone, TextMsg, send_sync_msg, get_proto, warning, format
    - Аргументы:
      - `on_off`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; int:[0, 1], 0 关闭挑战卡检测功能，1 打开挑战卡检测功能
    - Пример: `obj._pad_detection()`
  - `motor_on`
    - Сигнатура: `motor_on(self)`
    - Приватный: нет
    - Описание: 控制飞机转桨
    - Связи (вызовы): FlightAction, send_action
    - Аргументы:
      - нет аргументов
    - Пример: `obj.motor_on()`
  - `motor_off`
    - Сигнатура: `motor_off(self)`
    - Приватный: нет
    - Описание: 控制飞机停桨
    - Связи (вызовы): FlightAction, send_action
    - Аргументы:
      - нет аргументов
    - Пример: `obj.motor_off()`
  - `get_speed`
    - Сигнатура: `get_speed(self)`
    - Приватный: нет
    - Описание: 获取当前设置速度
    - Связи (вызовы): TextProtoDrone, TextMsg, send_sync_msg, get_proto, warning, float
    - Аргументы:
      - нет аргументов
    - Пример: `obj.get_speed()`
  - `sub_attitude`
    - Сигнатура: `sub_attitude(self, freq=5, callback=None, *args, **kw)`
    - Приватный: нет
    - Описание: 订阅飞机姿态信息
    - Связи (вызовы): TelloAttiInfoSubject, add_subject_info
    - Аргументы:
      - `freq`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; enum:(1, 5, 10)，订阅数据的频率
      - `callback`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 传入数据处理的回掉函数
      - `*args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 回调函数参数
      - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; 回调函数参数
    - Пример(ы) из репозитория:
      - `ep_chassis.sub_attitude(freq=10, callback=sub_attitude_info_handler)` (из `examples/02_chassis/04_sub_attitude.py:33`)
      - `ep_chassis.sub_attitude(freq=5, callback=sub_info_handler)` (из `examples/02_chassis/09_sub_all.py:36`)
  - `unsub_attitude`
    - Сигнатура: `unsub_attitude(self)`
    - Приватный: нет
    - Описание: 取消订阅飞机姿态信息
    - Связи (вызовы): del_subject_info
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `ep_chassis.unsub_attitude()` (из `examples/02_chassis/04_sub_attitude.py:36`)
      - `ep_chassis.unsub_attitude()` (из `examples/02_chassis/09_sub_all.py:52`)
  - `sub_imu`
    - Сигнатура: `sub_imu(self, freq=5, callback=None, *args, **kw)`
    - Приватный: нет
    - Описание: 订阅飞机陀螺仪信息
    - Связи (вызовы): TelloImuInfoSubject, add_subject_info
    - Аргументы:
      - `freq`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; enum:(1, 5, 10)，订阅数据的频率
      - `callback`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 传入数据处理的回掉函数
      - `*args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 回调函数参数
      - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; 回调函数参数
    - Пример(ы) из репозитория:
      - `ep_chassis.sub_imu(freq=5, callback=sub_imu_info_handler)` (из `examples/02_chassis/06_sub_imu.py:35`)
      - `ep_chassis.sub_imu(freq=10, callback=sub_info_handler)` (из `examples/02_chassis/09_sub_all.py:39`)
  - `unsub_imu`
    - Сигнатура: `unsub_imu(self)`
    - Приватный: нет
    - Описание: 取消订阅飞机陀螺仪信息
    - Связи (вызовы): del_subject_info
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `ep_chassis.unsub_imu()` (из `examples/02_chassis/06_sub_imu.py:37`)
      - `ep_chassis.unsub_imu()` (из `examples/02_chassis/09_sub_all.py:51`)


## Модуль `src.robomaster.gimbal` (`src/robomaster/gimbal.py`)

### Классы

### `GimbalMoveAction`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self, pitch=0, yaw=0, pitch_speed=30, yaw_speed=30, coord=COORDINATE_YCPN, **kw)`
  - **Аргументы конструктора:**
    - `pitch`: тип `не указан`; единицы `°`; допустимые значения `не указаны`; инициализационный параметр `pitch`.
    - `yaw`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; инициализационный параметр `yaw`.
    - `pitch_speed`: тип `не указан`; единицы `м/с`; допустимые значения `не указаны`; инициализационный параметр `pitch_speed`.
    - `yaw_speed`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; инициализационный параметр `yaw_speed`.
    - `coord`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `coord`.
    - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; инициализационный параметр `**kw`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, pitch=0, yaw=0, pitch_speed=30, yaw_speed=30, coord=COORDINATE_YCPN, **kw)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): __init__, super
    - Аргументы:
      - `pitch`: тип `не указан`; единицы `°`; допустимые значения `не указаны`; параметр `pitch`.
      - `yaw`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `yaw`.
      - `pitch_speed`: тип `не указан`; единицы `м/с`; допустимые значения `не указаны`; параметр `pitch_speed`.
      - `yaw_speed`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `yaw_speed`.
      - `coord`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `coord`.
      - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `**kw`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `__repr__` (приватный)
    - Сигнатура: `__repr__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): format
    - Аргументы:
      - нет аргументов
    - Пример: `obj.__repr__()`
  - `encode`
    - Сигнатура: `encode(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): ProtoGimbalRotate, val2proto
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `return socket_obj.send(data.encode('utf-8'))` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:217`)
      - `ser.write('command'.encode('utf-8'))` (из `examples/plaintext_sample_code/RoboMasterEP/connection/uart/uart_connection.py:16`)
  - `update_from_push`
    - Сигнатура: `update_from_push(self, proto)`
    - Приватный: нет
    - Описание: 推送消息更新Action状态
    - Связи (вызовы): info, _changeto_state, float, format, warning
    - Аргументы:
      - `proto`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `proto`.
    - Пример: `obj.update_from_push(...)`

### `GimbalRecenterAction`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self, pitch_speed=100, yaw_speed=100, **kw)`
  - **Аргументы конструктора:**
    - `pitch_speed`: тип `не указан`; единицы `м/с`; допустимые значения `не указаны`; инициализационный параметр `pitch_speed`.
    - `yaw_speed`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; инициализационный параметр `yaw_speed`.
    - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; инициализационный параметр `**kw`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, pitch_speed=100, yaw_speed=100, **kw)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): __init__, super
    - Аргументы:
      - `pitch_speed`: тип `не указан`; единицы `м/с`; допустимые значения `не указаны`; параметр `pitch_speed`.
      - `yaw_speed`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `yaw_speed`.
      - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `**kw`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `__repr__` (приватный)
    - Сигнатура: `__repr__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): format
    - Аргументы:
      - нет аргументов
    - Пример: `obj.__repr__()`
  - `encode`
    - Сигнатура: `encode(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): ProtoGimbalRecenter
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `return socket_obj.send(data.encode('utf-8'))` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:217`)
      - `ser.write('command'.encode('utf-8'))` (из `examples/plaintext_sample_code/RoboMasterEP/connection/uart/uart_connection.py:16`)
  - `update_from_push`
    - Сигнатура: `update_from_push(self, proto)`
    - Приватный: нет
    - Описание: 推送消息更新Action状态
    - Связи (вызовы): _update_action_state, info, float, format
    - Аргументы:
      - `proto`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `proto`.
    - Пример: `obj.update_from_push(...)`

### `GimbalPosSubject`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `angle`
    - Сигнатура: `angle(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.angle()`
  - `data_info`
    - Сигнатура: `data_info(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.data_info()`
  - `decode`
    - Сигнатура: `decode(self, buf)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): unpack, proto2val
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
    - Пример(ы) из репозитория:
      - `msg = msg.decode('utf-8')` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:68`)
      - `assert m.str_from_string().encode().decode() == "baz"` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_pytypes.py:73`)

### `Gimbal`
- **Приватный класс:** нет
- **Описание:** EP 云台模块
- **Конструктор:** `__init__(self, robot)`
  - **Аргументы конструктора:**
    - `robot`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `robot`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, robot)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): __init__, super
    - Аргументы:
      - `robot`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `suspend`
    - Сигнатура: `suspend(self)`
    - Приватный: нет
    - Описание: 控制云台进入休眠状态
    - Связи (вызовы): ProtoGimbalCtrl, Msg, send_async_msg, warning, format, str
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `ep_gimbal.suspend()` (из `examples/03_gimbal/03_control.py:29`)
  - `resume`
    - Сигнатура: `resume(self)`
    - Приватный: нет
    - Описание: 控制云台从休眠状态中恢复
    - Связи (вызовы): ProtoGimbalCtrl, Msg, send_async_msg, warning, format, str
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `ep_gimbal.resume()` (из `examples/03_gimbal/03_control.py:33`)
  - `drive_speed`
    - Сигнатура: `drive_speed(self, pitch_speed=30.0, yaw_speed=30.0)`
    - Приватный: нет
    - Описание: 控制以一定速度转动
    - Связи (вызовы): ProtoGimbalCtrlSpeed, val2proto, _send_async_proto
    - Аргументы:
      - `pitch_speed`: тип `не указан`; единицы `м/с`; допустимые значения `не указаны`; float: [-360, 360]，pitch轴速度，单位 °/s
      - `yaw_speed`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; float: [-360, 360]，yaw 轴速度，单位 °/s
    - Пример(ы) из репозитория:
      - `ep_chassis.drive_speed(x=x_val, y=0, z=0, timeout=5)` (из `examples/02_chassis/03_speed.py:32`)
      - `ep_chassis.drive_speed(x=-x_val, y=0, z=0, timeout=5)` (из `examples/02_chassis/03_speed.py:36`)
  - `recenter`
    - Сигнатура: `recenter(self, pitch_speed=60, yaw_speed=60)`
    - Приватный: нет
    - Описание: 控制云台回中
    - Связи (вызовы): GimbalRecenterAction, send_action
    - Аргументы:
      - `pitch_speed`: тип `не указан`; единицы `м/с`; допустимые значения `не указаны`; float: [-360, 360]，pitch轴速度，单位 °/s
      - `yaw_speed`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; float: [-360, 360]，yaw 轴速度，单位 °/s
    - Пример(ы) из репозитория:
      - `ep_gimbal.recenter().wait_for_completed()` (из `examples/03_gimbal/04_recenter.py:32`)
      - `ep_gimbal.recenter(pitch_speed=100, yaw_speed=100).wait_for_completed()` (из `examples/03_gimbal/04_recenter.py:38`)
  - `_set_work_mode` (приватный)
    - Сигнатура: `_set_work_mode(self, mode)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): ProtoGimbalSetWorkMode, _send_sync_proto
    - Аргументы:
      - `mode`: тип `не указан`; единицы `не указаны`; допустимые значения `enum/строка`; параметр `mode`.
    - Пример: `obj._set_work_mode(...)`
  - `move`
    - Сигнатура: `move(self, pitch=0, yaw=0, pitch_speed=30, yaw_speed=30)`
    - Приватный: нет
    - Описание: 控制云台运动到指定位置，坐标轴原点为当前位置
    - Связи (вызовы): val2proto, GimbalMoveAction, send_action
    - Аргументы:
      - `pitch`: тип `не указан`; единицы `°`; допустимые значения `не указаны`; float: [-55, 55]，pitch 轴角度，单位 °
      - `yaw`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; float: [-55, 55]，yaw 轴角度，单位 °
      - `pitch_speed`: тип `не указан`; единицы `м/с`; допустимые значения `не указаны`; float: [0, 540]，pitch 轴运动速速，单位 °/s
      - `yaw_speed`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; float: [0, 540]，yaw 轴运动速度，单位 °/s
    - Пример(ы) из репозитория:
      - `ep_chassis.move(x=x_val, y=0, z=0, xy_speed=0.7).wait_for_completed()` (из `examples/02_chassis/01_move.py:31`)
      - `ep_chassis.move(x=-x_val, y=0, z=0, xy_speed=0.7).wait_for_completed()` (из `examples/02_chassis/01_move.py:34`)
  - `moveto`
    - Сигнатура: `moveto(self, pitch=0, yaw=0, pitch_speed=30, yaw_speed=30)`
    - Приватный: нет
    - Описание: 控制云台运动到指定位置，坐标轴原点为上电位置
    - Связи (вызовы): val2proto, GimbalMoveAction, send_action
    - Аргументы:
      - `pitch`: тип `не указан`; единицы `°`; допустимые значения `не указаны`; int: [-25, 30]，pitch 轴角度，单位 °
      - `yaw`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; int: [-250, 250]，yaw 轴角度，单位 °
      - `pitch_speed`: тип `не указан`; единицы `м/с`; допустимые значения `не указаны`; int: [0, 540]，pitch 轴运动速度，单位 °
      - `yaw_speed`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; int: [0, 540]，yaw 轴运动速度，单位 °
    - Пример(ы) из репозитория:
      - `ep_gimbal.moveto(pitch=0, yaw=0).wait_for_completed()` (из `examples/03_gimbal/01_move.py:32`)
      - `ep_gimbal.moveto(pitch=15, yaw=90, pitch_speed=50, yaw_speed=100).wait_for_completed()` (из `examples/03_gimbal/01_move.py:35`)
  - `sub_angle`
    - Сигнатура: `sub_angle(self, freq=5, callback=None, *args, **kw)`
    - Приватный: нет
    - Описание: 订阅云台姿态角信息
    - Связи (вызовы): GimbalPosSubject, add_subject_info
    - Аргументы:
      - `freq`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; enum: (1, 5, 10, 20, 50) 设置数据订阅数据的推送频率，单位 Hz
      - `callback`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 回调函数，返回数据 (pitch_angle, yaw_angle, pitch_ground_angle, yaw_ground_angle):
      - `*args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 可变参数
      - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; 关键字参数
    - Пример(ы) из репозитория:
      - `ep_gimbal.sub_angle(freq=5, callback=sub_data_handler)` (из `examples/03_gimbal/05_sub_angle.py:34`)
  - `unsub_angle`
    - Сигнатура: `unsub_angle(self)`
    - Приватный: нет
    - Описание: 取消云台姿态角订阅
    - Связи (вызовы): del_subject_info
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `ep_gimbal.unsub_angle()` (из `examples/03_gimbal/05_sub_angle.py:38`)


## Модуль `src.robomaster.gripper` (`src/robomaster/gripper.py`)

### Классы

### `GripperSubject`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `status`
    - Сигнатура: `status(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): warning, format
    - Аргументы:
      - нет аргументов
    - Пример: `obj.status()`
  - `data_info`
    - Сигнатура: `data_info(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.data_info()`
  - `decode`
    - Сигнатура: `decode(self, buf)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
    - Пример(ы) из репозитория:
      - `msg = msg.decode('utf-8')` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:68`)
      - `assert m.str_from_string().encode().decode() == "baz"` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_pytypes.py:73`)

### `Gripper`
- **Приватный класс:** нет
- **Описание:** EP 机械爪模块
- **Конструктор:** `__init__(self, robot)`
  - **Аргументы конструктора:**
    - `robot`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `robot`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, robot)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): __init__, super
    - Аргументы:
      - `robot`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `reset`
    - Сигнатура: `reset(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.reset()`
  - `open`
    - Сигнатура: `open(self, power=50)`
    - Приватный: нет
    - Описание: 控制机械爪张开
    - Связи (вызовы): ProtoGripperCtrl, val2proto, _send_sync_proto, host2byte
    - Аргументы:
      - `power`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; int: [1, 100]，控制出力
    - Пример(ы) из репозитория:
      - `img = Image.open(QRCODE_NAME)` (из `examples/01_robot/05_sta_conn_helper.py:32`)
      - `playing_stream = audio_player.open(format=pyaudio.paInt16,` (из `examples/04_camera/04_audio_without_playing.py:27`)
  - `close`
    - Сигнатура: `close(self, power=50)`
    - Приватный: нет
    - Описание: 控制机械爪关闭
    - Связи (вызовы): ProtoGripperCtrl, val2proto, _send_sync_proto, host2byte
    - Аргументы:
      - `power`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; int: [1, 100]，控制出力
    - Пример(ы) из репозитория:
      - `ep_robot.close()` (из `examples/01_robot/00_logger.py:34`)
      - `ep_robot.close()` (из `examples/01_robot/01_get_version.py:27`)
  - `pause`
    - Сигнатура: `pause(self)`
    - Приватный: нет
    - Описание: 控制机械爪停止
    - Связи (вызовы): ProtoGripperCtrl, _send_sync_proto, host2byte
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `ep_gripper.pause()` (из `examples/11_gripper/01_open_close.py:31`)
      - `ep_gripper.pause()` (из `examples/11_gripper/01_open_close.py:36`)
  - `sub_status`
    - Сигнатура: `sub_status(self, freq=5, callback=None, *args, **kw)`
    - Приватный: нет
    - Описание: 订阅夹爪的状态信息
    - Связи (вызовы): GripperSubject, add_subject_info
    - Аргументы:
      - `freq`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; enum: (1, 5, 10, 20, 50)，设置数据订阅数据的推送频率，单位 Hz
      - `callback`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 回调函数，返回数据 (status):
      - `*args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 可变参数
      - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; 关键字参数
    - Пример(ы) из репозитория:
      - `ep_chassis.sub_status(freq=5, callback=sub_status_info_handler)` (из `examples/02_chassis/07_sub_status.py:38`)
      - `ep_chassis.sub_status(freq=50, callback=sub_info_handler)` (из `examples/02_chassis/09_sub_all.py:45`)
  - `unsub_status`
    - Сигнатура: `unsub_status(self)`
    - Приватный: нет
    - Описание: 取消夹爪状态信息订阅
    - Связи (вызовы): del_subject_info
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `ep_chassis.unsub_status()` (из `examples/02_chassis/07_sub_status.py:40`)
      - `ep_chassis.unsub_status()` (из `examples/02_chassis/09_sub_all.py:49`)


## Модуль `src.robomaster.led` (`src/robomaster/led.py`)

### Классы

### `Led`
- **Приватный класс:** нет
- **Описание:** EP 装甲灯模块
- **Конструктор:** `__init__(self, robot)`
  - **Аргументы конструктора:**
    - `robot`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `robot`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, robot)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): __init__, super
    - Аргументы:
      - `robot`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `set_led`
    - Сигнатура: `set_led(self, comp=COMP_ALL, r=0, g=0, b=0, effect=EFFECT_ON, freq=1)`
    - Приватный: нет
    - Описание: 设置整机装甲灯效
    - Связи (вызовы): ProtoSetSystemLed, val2proto, _send_sync_proto, host2byte, int, warning
    - Аргументы:
      - `comp`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; enum: ("all", "top_all", "top_right", "top_left", "bottom_all", "bottom_front",         "bottom_back", "bottom_left", "bottom_right") 灯效部位，all: 所有装甲灯；top_all:云台所有装甲灯；        top_right: 云台右侧装甲灯；top_left: 云台左侧装甲灯; bottom_all: 底盘所有装甲灯；bottom_front: 前装甲灯；        bottom_back: 后装甲灯；bottom_left: 左装甲灯；bottom_right: 右装甲灯
      - `r`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; int: [0~255]，RGB红色分量值
      - `g`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; int: [0~255]，RGB绿色分量值
      - `b`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; int: [0~255]，RGB蓝色分量值
      - `effect`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; enum: ("on", "off", "flash", "breath", "scrolling") 灯效类型，on:常亮；off:常灭；flash:闪烁；        breath:呼吸；scrolling:跑马灯（仅对云台灯有效）
      - `freq`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; int: [1, 10]，闪烁频率，仅对闪烁灯效有效
    - Пример(ы) из репозитория:
      - `ep_blaster.set_led(brightness=2, effect=blaster.LED_ON)` (из `examples/06_blaster/02_led.py:30`)
      - `ep_blaster.set_led(brightness=4, effect=blaster.LED_ON)` (из `examples/06_blaster/02_led.py:32`)
  - `set_gimbal_led`
    - Сигнатура: `set_gimbal_led(self, comp=COMP_TOP_ALL, r=255, g=255, b=255, led_list=[0, 1, 2, 3], effect=EFFECT_ON)`
    - Приватный: нет
    - Описание: 设置云台灯效
    - Связи (вызовы): ProtoSetSystemLed, range, val2proto, _send_sync_proto, len, host2byte
    - Аргументы:
      - `comp`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; enum: ("top_all", "top_left", "top_right")，云台部位
      - `r`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; int: [0, 255]，RGB红色分量值
      - `g`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; int: [0, 255]，RGB绿色分量值
      - `b`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; int: [0, 255]，RGB蓝色分量值
      - `led_list`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; list [idx0, idx1, ...]，idx：int[0,7] 云台灯序号列表.
      - `effect`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; enum: ("on", "off")，灯效类型
    - Пример(ы) из репозитория:
      - `ep_led.set_gimbal_led(comp=led.COMP_TOP_ALL, r=255, g=25, b=25,` (из `examples/07_led/02_set_gimbal_led.py:36`)

### `TelloLed`
- **Приватный класс:** нет
- **Описание:** 教育无人机 扩展LED模块
- **Конструктор:** `__init__(self, robot)`
  - **Аргументы конструктора:**
    - `robot`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `robot`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, robot)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `robot`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `set_led`
    - Сигнатура: `set_led(self, r=0, g=255, b=0)`
    - Приватный: нет
    - Описание: 设置扩展模块led颜色
    - Связи (вызовы): format, TextProtoDrone, TextMsg, send_sync_msg, error, get_proto
    - Аргументы:
      - `r`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; int:[0, 255], 扩展led红色通道的强度
      - `g`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; int:[0, 255], 扩展led绿色通道的强度
      - `b`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; int:[0, 255], 扩展led蓝色通道的强度
    - Пример(ы) из репозитория:
      - `ep_blaster.set_led(brightness=2, effect=blaster.LED_ON)` (из `examples/06_blaster/02_led.py:30`)
      - `ep_blaster.set_led(brightness=4, effect=blaster.LED_ON)` (из `examples/06_blaster/02_led.py:32`)
  - `set_led_breath`
    - Сигнатура: `set_led_breath(self, freq=1, r=0, g=255, b=0)`
    - Приватный: нет
    - Описание: 设置扩展模块led以指定的颜色与频率实现呼吸效果
    - Связи (вызовы): format, TextProtoDrone, TextMsg, send_sync_msg, error, get_proto
    - Аргументы:
      - `freq`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; int:[0.1, 2.5], 扩展led呼吸模式下的频率，共十档，随着数字增大速度变快
      - `r`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; int:[0, 255], 扩展led红色通道的强度
      - `g`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; int:[0, 255], 扩展led绿色通道的强度
      - `b`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; int:[0, 255], 扩展led蓝色通道的强度
    - Пример: `obj.set_led_breath()`
  - `set_led_blink`
    - Сигнатура: `set_led_blink(self, freq=5, r1=0, g1=255, b1=0, r2=0, g2=255, b2=255)`
    - Приватный: нет
    - Описание: 设置扩展模块led以制定的两种颜色与频率实现闪烁效果
    - Связи (вызовы): format, TextProtoDrone, TextMsg, send_sync_msg, error, get_proto
    - Аргументы:
      - `freq`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; int:[0.1, 10], 扩展ked闪烁模式下的频率， 共十档，随着数字增大速度变快
      - `r1`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; int:[0, 255], 第一种颜色的红色通道的强度
      - `g1`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; int:[0, 255], 第一种颜色的绿色通道的强度
      - `b1`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; int:[0, 255], 第一种颜色的蓝色通道的强度
      - `r2`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; int:[0, 255], 第二种颜色的红色通道的强度
      - `g2`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; int:[0, 255], 第二种颜色的绿色通道的强度
      - `b2`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; int:[0, 255], 第二种颜色的蓝色通道的强度
    - Пример: `obj.set_led_blink()`
  - `set_mled_bright`
    - Сигнатура: `set_mled_bright(self, bright=255)`
    - Приватный: нет
    - Описание: 设置点阵屏的亮度
    - Связи (вызовы): format, TextProtoDrone, TextMsg, send_sync_msg, error, get_proto
    - Аргументы:
      - `bright`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; int:[0, 255] 点阵屏的亮度
    - Пример: `obj.set_mled_bright()`
  - `set_mled_boot`
    - Сигнатура: `set_mled_boot(self, display_graph)`
    - Приватный: нет
    - Описание: 设置点阵屏的开机画面
    - Связи (вызовы): format, TextProtoDrone, TextMsg, send_sync_msg, error, get_proto
    - Аргументы:
      - `display_graph`: тип `не указан`; единицы `м`; допустимые значения `0..255`; string: 长度最大为64，点阵屏显示图案的编码字符串，每个字符解读为二进制后对应位置的led点的状态，
    - Пример: `obj.set_mled_boot(...)`
  - `set_mled_sc`
    - Сигнатура: `set_mled_sc(self)`
    - Приватный: нет
    - Описание: 清除点阵屏开机显示画面
    - Связи (вызовы): TextProtoDrone, TextMsg, send_sync_msg, error, get_proto, format
    - Аргументы:
      - нет аргументов
    - Пример: `obj.set_mled_sc()`
  - `set_mled_char`
    - Сигнатура: `set_mled_char(self, color='r', display_char='0')`
    - Приватный: нет
    - Описание: 控制扩展点阵屏模块，显示输入的字符
    - Связи (вызовы): format, TextProtoDrone, TextMsg, send_sync_msg, error, get_proto
    - Аргументы:
      - `color`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `color`.
      - `display_char`: тип `не указан`; единицы `м`; допустимые значения `0..255`; параметр `display_char`.
    - Пример(ы) из репозитория:
      - `tl_drone.led.set_mled_char('r', num)` (из `examples/12_drone/21_mled.py:37`)
      - `tl_drone.led.set_mled_char(color='b', display_char='A')` (из `examples/12_drone/21_mled.py:41`)
  - `set_mled_graph`
    - Сигнатура: `set_mled_graph(self, display_graph)`
    - Приватный: нет
    - Описание: 用户自定义扩展点阵屏显示图案
    - Связи (вызовы): format, TextProtoDrone, TextMsg, send_sync_msg, warning, get_proto
    - Аргументы:
      - `display_graph`: тип `не указан`; единицы `м`; допустимые значения `0..255`; string: 长度最大为64，点阵屏显示图案的编码字符串，每个字符解读为二进制后对应位置的led点的状态，
    - Пример(ы) из репозитория:
      - `tl_drone.led.set_mled_graph(mled_smile1)` (из `examples/12_drone/21_mled.py:30`)
      - `tl_drone.led.set_mled_graph(mled_smile2)` (из `examples/12_drone/21_mled.py:32`)
  - `set_mled_char_scroll`
    - Сигнатура: `set_mled_char_scroll(self, direction='l', color='r', freq=1.5, display_str='DJI')`
    - Приватный: нет
    - Описание: 控制扩展点阵屏滚动显示字符串
    - Связи (вызовы): format, _set_mled_scroll
    - Аргументы:
      - `direction`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `direction`.
      - `color`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `color`.
      - `freq`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `freq`.
      - `display_str`: тип `не указан`; единицы `м`; допустимые значения `0..255`; параметр `display_str`.
    - Пример: `obj.set_mled_char_scroll()`
  - `set_mled_graph_scroll`
    - Сигнатура: `set_mled_graph_scroll(self, direction='l', freq=1.5, display_graph=TELLO_DISPLAY_GRAPH)`
    - Приватный: нет
    - Описание: 控制扩展点阵屏滚动显示图像
    - Связи (вызовы): format, _set_mled_scroll
    - Аргументы:
      - `direction`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `direction`.
      - `freq`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `freq`.
      - `display_graph`: тип `не указан`; единицы `м`; допустимые значения `0..255`; параметр `display_graph`.
    - Пример: `obj.set_mled_graph_scroll()`
  - `_set_mled_scroll` (приватный)
    - Сигнатура: `_set_mled_scroll(self, cmd)`
    - Приватный: да
    - Описание: 控制扩展点阵屏滚动显示
    - Связи (вызовы): TextProtoDrone, TextMsg, send_sync_msg, error, get_proto, warning
    - Аргументы:
      - `cmd`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `cmd`.
    - Пример: `obj._set_mled_scroll(...)`


## Модуль `src.robomaster.media` (`src/robomaster/media.py`)

### Классы

### `LiveView`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self, robot)`
  - **Аргументы конструктора:**
    - `robot`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `robot`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, robot)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): StreamConnection, H264Decoder, Queue, OpusDecoder
    - Аргументы:
      - `robot`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `__del__` (приватный)
    - Сигнатура: `__del__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): stop
    - Аргументы:
      - нет аргументов
    - Пример: `obj.__del__()`
  - `stop`
    - Сигнатура: `stop(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): stop_video_stream, stop_audio_stream
    - Аргументы:
      - нет аргументов
    - Пример: `obj.stop()`
  - `start_video_stream`
    - Сигнатура: `start_video_stream(self, display=True, addr=None, ip_proto='tcp')`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): info, connect, Thread, start, format, error
    - Аргументы:
      - `display`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `display`.
      - `addr`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `addr`.
      - `ip_proto`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `ip_proto`.
    - Пример(ы) из репозитория:
      - `ep_camera.start_video_stream(display=True, resolution=camera.STREAM_360P)` (из `examples/04_camera/01_video_with_display.py:29`)
      - `ep_camera.start_video_stream(display=False)` (из `examples/04_camera/02_video_strategy.py:30`)
  - `stop_video_stream`
    - Сигнатура: `stop_video_stream(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): info, clear, disconnect, join, error, put
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `ep_camera.stop_video_stream()` (из `examples/04_camera/01_video_with_display.py:31`)
      - `ep_camera.stop_video_stream()` (из `examples/04_camera/02_video_strategy.py:37`)
  - `read_video_frame`
    - Сигнатура: `read_video_frame(self, timeout=3, strategy='pipeline')`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): get, warning, qsize, format
    - Аргументы:
      - `timeout`: тип `не указан`; единицы `с`; допустимые значения `не указаны`; параметр `timeout`.
      - `strategy`: тип `не указан`; единицы `м`; допустимые значения `0..255`; параметр `strategy`.
    - Пример: `obj.read_video_frame()`
  - `_h264_decode` (приватный)
    - Сигнатура: `_h264_decode(self, data)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): decode, fromstring, reshape, append, len
    - Аргументы:
      - `data`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `data`.
    - Пример(ы) из репозитория:
      - `for frame in self._h264_decode(package_data):` (из `examples/plaintext_sample_code/RoboMasterEP/stream/python_stream_liveview/liveview.py:120`)
  - `_video_decoder_task` (приватный)
    - Сигнатура: `_video_decoder_task(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): info, read_buf, _h264_decode, put, warning, format
    - Аргументы:
      - нет аргументов
    - Пример: `obj._video_decoder_task()`
  - `_video_display_task` (приватный)
    - Сигнатура: `_video_display_task(self, name='RoboMaster LiveView')`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): info, array, imshow, waitKey, get, warning
    - Аргументы:
      - `name`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `name`.
    - Пример: `obj._video_display_task()`
  - `read_audio_frame`
    - Сигнатура: `read_audio_frame(self, timeout=1)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): get
    - Аргументы:
      - `timeout`: тип `не указан`; единицы `с`; допустимые значения `не указаны`; параметр `timeout`.
    - Пример(ы) из репозитория:
      - `frame = ep_camera.read_audio_frame()` (из `examples/04_camera/04_audio_without_playing.py:33`)
  - `start_audio_stream`
    - Сигнатура: `start_audio_stream(self, addr=None, ip_proto='tcp')`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): info, connect, Thread, start, format, error
    - Аргументы:
      - `addr`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `addr`.
      - `ip_proto`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `ip_proto`.
    - Пример(ы) из репозитория:
      - `ep_camera.start_audio_stream()` (из `examples/04_camera/04_audio_without_playing.py:54`)
  - `stop_audio_stream`
    - Сигнатура: `stop_audio_stream(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): info, disconnect, clear, sleep, join, error
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `ep_camera.stop_audio_stream()` (из `examples/04_camera/04_audio_without_playing.py:57`)
  - `_audio_decoder_task` (приватный)
    - Сигнатура: `_audio_decoder_task(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): info, read_buf, len, decode, put, format
    - Аргументы:
      - нет аргументов
    - Пример: `obj._audio_decoder_task()`


## Модуль `src.robomaster.module` (`src/robomaster/module.py`)

### Классы

### `_AutoRegisterModule` (приватный класс)
- **Приватный класс:** да
- **Описание:** help to automatically register Proto Class where ever they're defined
- **Конструктор:** `__init__(cls, name, bases, attrs, **kw)`
  - **Аргументы конструктора:**
    - `name`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; инициализационный параметр `name`.
    - `bases`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `bases`.
    - `attrs`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `attrs`.
    - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; инициализационный параметр `**kw`.
- **Методы:**
  - `__new__` (приватный)
    - Сигнатура: `__new__(mcs, name, bases, attrs, **kw)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): __new__, super
    - Аргументы:
      - `mcs`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `mcs`.
      - `name`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `name`.
      - `bases`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `bases`.
      - `attrs`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `attrs`.
      - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `**kw`.
    - Пример(ы) из репозитория:
      - `m.TestFactory6.__init__(NotPybindDerived.__new__(NotPybindDerived), tag.base, 1)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_factory_constructors.py:447`)
      - `m.TestFactory6.__init__(NotPybindDerived.__new__(NotPybindDerived), tag.alias, 1)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_factory_constructors.py:449`)
  - `__init__` (приватный)
    - Сигнатура: `__init__(cls, name, bases, attrs, **kw)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): __init__, keys, ValueError, super, format
    - Аргументы:
      - `name`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `name`.
      - `bases`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `bases`.
      - `attrs`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `attrs`.
      - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `**kw`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)

### `Module`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self, robot)`
  - **Аргументы конструктора:**
    - `robot`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `robot`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, robot)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `robot`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `client`
    - Сигнатура: `client(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.client()`
  - `reset`
    - Сигнатура: `reset(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): Exception
    - Аргументы:
      - нет аргументов
    - Пример: `obj.reset()`
  - `start`
    - Сигнатура: `start(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `self.cmd_socket_recv_thread.start()` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:90`)
      - `t.start()` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_callbacks.py:135`)
  - `stop`
    - Сигнатура: `stop(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.stop()`
  - `get_version`
    - Сигнатура: `get_version(self)`
    - Приватный: нет
    - Описание: 获取模块版本号
    - Связи (вызовы): ProtoGetVersion, Msg, send_sync_msg, get_proto, format, warning
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `version = ep_robot.get_version()` (из `examples/01_robot/00_logger.py:32`)
      - `ep_version = ep_robot.get_version()` (из `examples/01_robot/01_get_version.py:24`)
  - `_send_sync_proto` (приватный)
    - Сигнатура: `_send_sync_proto(self, proto, target=None)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): Msg, send_sync_msg, get_proto, warning, format
    - Аргументы:
      - `proto`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `proto`.
      - `target`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `target`.
    - Пример: `obj._send_sync_proto(...)`
  - `_send_async_proto` (приватный)
    - Сигнатура: `_send_async_proto(self, proto, target=None)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): Msg, send_async_msg, error, format
    - Аргументы:
      - `proto`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `proto`.
      - `target`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `target`.
    - Пример: `obj._send_async_proto(...)`


## Модуль `src.robomaster.protocol` (`src/robomaster/protocol.py`)

### Функции

#### `host2byte`
- **Сигнатура:** `host2byte(host, index)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** не выявлены
- **Аргументы:**
  - `host`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `host`.
  - `index`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `index`.
- **Пример:** `host2byte(..., ...)`

#### `byte2host`
- **Сигнатура:** `byte2host(b)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** не выявлены
- **Аргументы:**
  - `b`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `b`.
- **Пример:** `byte2host(...)`

#### `make_proto_cls_key`
- **Сигнатура:** `make_proto_cls_key(cmdset, cmdid)`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** не выявлены
- **Аргументы:**
  - `cmdset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `cmdset`.
  - `cmdid`: тип `не указан`; единицы `не указаны`; допустимые значения `ID/целое`; параметр `cmdid`.
- **Пример:** `make_proto_cls_key(..., ...)`

#### `decode_msg`
- **Сигнатура:** `decode_msg(buff, protocol='v1')`
- **Приватная:** нет
- **Описание:** описание отсутствует
- **Связи (вызовы):** Msg, int, len, info, warning, crc8_calc
- **Аргументы:**
  - `buff`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buff`.
  - `protocol`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `protocol`.
- **Пример:** `decode_msg(...)`

### Классы

### `_AutoRegisterProto` (приватный класс)
- **Приватный класс:** да
- **Описание:** help to automatically register Proto Class where ever they're defined
- **Конструктор:** `__init__(cls, name, bases, attrs, **kw)`
  - **Аргументы конструктора:**
    - `name`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; инициализационный параметр `name`.
    - `bases`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `bases`.
    - `attrs`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `attrs`.
    - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; инициализационный параметр `**kw`.
- **Методы:**
  - `__new__` (приватный)
    - Сигнатура: `__new__(mcs, name, bases, attrs, **kw)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): __new__, super
    - Аргументы:
      - `mcs`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `mcs`.
      - `name`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `name`.
      - `bases`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `bases`.
      - `attrs`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `attrs`.
      - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `**kw`.
    - Пример(ы) из репозитория:
      - `m.TestFactory6.__init__(NotPybindDerived.__new__(NotPybindDerived), tag.base, 1)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_factory_constructors.py:447`)
      - `m.TestFactory6.__init__(NotPybindDerived.__new__(NotPybindDerived), tag.alias, 1)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_factory_constructors.py:449`)
  - `__init__` (приватный)
    - Сигнатура: `__init__(cls, name, bases, attrs, **kw)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): __init__, make_proto_cls_key, keys, ValueError, super
    - Аргументы:
      - `name`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `name`.
      - `bases`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `bases`.
      - `attrs`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `attrs`.
      - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `**kw`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)

### `ProtoData`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self, **kwargs)`
  - **Аргументы конструктора:**
    - `**kwargs`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `**kwargs`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, **kwargs)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `**kwargs`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `**kwargs`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `__repr__` (приватный)
    - Сигнатура: `__repr__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): format
    - Аргументы:
      - нет аргументов
    - Пример: `obj.__repr__()`
  - `cmdset`
    - Сигнатура: `cmdset(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.cmdset()`
  - `cmset`
    - Сигнатура: `cmset(self, value)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `value`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `value`.
    - Пример: `obj.cmset(...)`
  - `cmdid`
    - Сигнатура: `cmdid(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.cmdid()`
  - `cmdid`
    - Сигнатура: `cmdid(self, value)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `value`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `value`.
    - Пример: `obj.cmdid(...)`
  - `cmdkey`
    - Сигнатура: `cmdkey(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.cmdkey()`
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: 协议对象打包发送数据为字节流
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`
  - `unpack_req`
    - Сигнатура: `unpack_req(self, buf, offset=0)`
    - Приватный: нет
    - Описание: 从字节流解包
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_req(...)`
  - `pack_resp`
    - Сигнатура: `pack_resp(self)`
    - Приватный: нет
    - Описание: 协议对象打包
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_resp()`
  - `unpack_resp`
    - Сигнатура: `unpack_resp(self, buf, offset=0)`
    - Приватный: нет
    - Описание: 从字节流解包为返回值和相关属性
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_resp(...)`

### `MsgBase`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)

### `Msg`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self, sender=0, receiver=0, proto=None)`
  - **Аргументы конструктора:**
    - `sender`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `sender`.
    - `receiver`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `receiver`.
    - `proto`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `proto`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, sender=0, receiver=0, proto=None)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `sender`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `sender`.
      - `receiver`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `receiver`.
      - `proto`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `proto`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `__repr__` (приватный)
    - Сигнатура: `__repr__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): format
    - Аргументы:
      - нет аргументов
    - Пример: `obj.__repr__()`
  - `cmdset`
    - Сигнатура: `cmdset(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.cmdset()`
  - `cmdid`
    - Сигнатура: `cmdid(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.cmdid()`
  - `is_ack`
    - Сигнатура: `is_ack(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.is_ack()`
  - `receiver`
    - Сигнатура: `receiver(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): byte2host, format
    - Аргументы:
      - нет аргументов
    - Пример: `obj.receiver()`
  - `sender`
    - Сигнатура: `sender(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): byte2host, format
    - Аргументы:
      - нет аргументов
    - Пример: `obj.sender()`
  - `pack`
    - Сигнатура: `pack(self, is_ack=False)`
    - Приватный: нет
    - Описание: Msg 消息打包
    - Связи (вызовы): bytearray, crc8_calc, crc16_calc, pack_into, debug, Exception
    - Аргументы:
      - `is_ack`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; bool: 是否是ack消息
    - Пример: `obj.pack()`
  - `unpack_protocol`
    - Сигнатура: `unpack_protocol(self)`
    - Приватный: нет
    - Описание: 从自身的buf数据解码协议及协议内容。
    - Связи (вызовы): make_proto_cls_key, warning, keys, info, format, unpack_resp
    - Аргументы:
      - нет аргументов
    - Пример: `obj.unpack_protocol()`
  - `get_proto`
    - Сигнатура: `get_proto(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.get_proto()`

### `TextMsg`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self, proto=None)`
  - **Аргументы конструктора:**
    - `proto`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `proto`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, proto=None)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `proto`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `proto`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `__repr__` (приватный)
    - Сигнатура: `__repr__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): format
    - Аргументы:
      - нет аргументов
    - Пример: `obj.__repr__()`
  - `pack`
    - Сигнатура: `pack(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): pack_req
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack()`
  - `unpack_protocol`
    - Сигнатура: `unpack_protocol(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): TextProtoDrone, unpack_resp, warining, format
    - Аргументы:
      - нет аргументов
    - Пример: `obj.unpack_protocol()`
  - `get_proto`
    - Сигнатура: `get_proto(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.get_proto()`
  - `get_buf`
    - Сигнатура: `get_buf(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.get_buf()`

### `ProtoGetVersion`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`
  - `unpack_resp`
    - Сигнатура: `unpack_resp(self, buf, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): len, Exception
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_resp(...)`

### `ProtoGetProductVersion`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): bytearray
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`
  - `unpack_resp`
    - Сигнатура: `unpack_resp(self, buf, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): unpack_from, format, warning
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_resp(...)`

### `ProtoGetSn`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): bytearray
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`
  - `unpack_resp`
    - Сигнатура: `unpack_resp(self, buf, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): decode
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_resp(...)`

### `ProtoTakePhoto`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): bytearray
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`
  - `unpack_resp`
    - Сигнатура: `unpack_resp(self, buf, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_resp(...)`

### `ProtoSetZoom`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): bytearray, pack_into
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`
  - `unpack_resp`
    - Сигнатура: `unpack_resp(self, buf, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_resp(...)`

### `ProtoGetZoom`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`
  - `unpack_resp`
    - Сигнатура: `unpack_resp(self, buf, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_resp(...)`

### `ProtoSetWhiteBalance`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): bytearray, pack_into
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`
  - `unpack_resp`
    - Сигнатура: `unpack_resp(self, buf, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_resp(...)`

### `ProtoFcSubInfoReq`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): bytearray, pack_into, enumerate, debug, format, len
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`
  - `unpack_resp`
    - Сигнатура: `unpack_resp(self, buf, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): warning, format
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_resp(...)`

### `ProtoChassisStickOverlay`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): bytearray
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`
  - `unpack_resp`
    - Сигнатура: `unpack_resp(self, buf, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): warning, format
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_resp(...)`

### `ProtoGimbalCtrlSpeed`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): bytearray, pack_into
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`
  - `unpack_resp`
    - Сигнатура: `unpack_resp(self, buf, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): warning, format
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_resp(...)`

### `ProtoArmorHitEvent`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`
  - `unpack_req`
    - Сигнатура: `unpack_req(self, buf, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): unpack
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_req(...)`

### `ProtoIrHitEvent`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`
  - `unpack_req`
    - Сигнатура: `unpack_req(self, buf, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): unpack
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_req(...)`

### `ProtoGameMsgEvent`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`
  - `unpack_req`
    - Сигнатура: `unpack_req(self, buf, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_req(...)`

### `ProtoSetArmorParam`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): bytearray, pack_into
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`
  - `unpack_resp`
    - Сигнатура: `unpack_resp(self, buf, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_resp(...)`

### `ProtoChassisWheelSpeed`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): bytearray
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`
  - `unpack_resp`
    - Сигнатура: `unpack_resp(self, buf, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_resp(...)`

### `ProtoSetSystemLed`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): bytearray, pack_into
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`
  - `unpack_resp`
    - Сигнатура: `unpack_resp(self, buf, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_resp(...)`

### `ProtoSetRobotMode`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): bytearray
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`
  - `unpack_resp`
    - Сигнатура: `unpack_resp(self, buff, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `buff`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buff`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_resp(...)`

### `ProtoGetRobotMode`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`
  - `unpack_resp`
    - Сигнатура: `unpack_resp(self, buf, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_resp(...)`

### `ProtoBlasterFire`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): bytearray
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`
  - `unpack_resp`
    - Сигнатура: `unpack_resp(self, buf, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_resp(...)`

### `ProtoBlasterSetLed`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): bytearray, pack_into
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`
  - `unpack_resp`
    - Сигнатура: `unpack_resp(self, buf, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_resp(...)`

### `ProtoSetSdkMode`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): bytearray
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`
  - `unpack_resp`
    - Сигнатура: `unpack_resp(self, buf, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_resp(...)`

### `ProtoStreamCtrl`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): bytearray
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`
  - `unpack_resp`
    - Сигнатура: `unpack_resp(self, buf, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_resp(...)`

### `ProtoSetSdkConnection`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): bytearray, bytes, pack_into, map, split
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`
  - `unpack_resp`
    - Сигнатура: `unpack_resp(self, buf, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): format
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_resp(...)`

### `ProtoSdkHeartBeat`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`
  - `unpack_resp`
    - Сигнатура: `unpack_resp(self, buf, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_resp(...)`

### `ProtoAiModuleEvent`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`
  - `unpack_req`
    - Сигнатура: `unpack_req(self, buf, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): round, range, len, unpack, append
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_req(...)`

### `ProtoUwbModuleEvent`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`
  - `unpack_req`
    - Сигнатура: `unpack_req(self, buf, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): unpack
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_req(...)`

### `ProtoGimbalSetWorkMode`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): bytearray
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`
  - `unpack_resp`
    - Сигнатура: `unpack_resp(self, buf, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_resp(...)`

### `ProtoGimbalCtrl`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): bytearray, pack_into
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`
  - `unpack_resp`
    - Сигнатура: `unpack_resp(self, buf, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_resp(...)`

### `ProtoPlaySound`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): bytearray, pack_into, debug, format, hexlify
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`
  - `unpack_resp`
    - Сигнатура: `unpack_resp(self, buf, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): debug, format, hexlify
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_resp(...)`
  - `sound_id`
    - Сигнатура: `sound_id(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.sound_id()`
  - `sound_id`
    - Сигнатура: `sound_id(self, value)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `value`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `value`.
    - Пример: `obj.sound_id(...)`
  - `play_times`
    - Сигнатура: `play_times(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.play_times()`
  - `play_times`
    - Сигнатура: `play_times(self, value)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `value`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `value`.
    - Пример: `obj.play_times(...)`

### `ProtoSoundPush`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`
  - `unpack_req`
    - Сигнатура: `unpack_req(self, buf, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): unpack_from, debug, format, hexlify
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_req(...)`
  - `unpack_resp`
    - Сигнатура: `unpack_resp(self, buf, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): unpack_from, debug, format, hexlify
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_resp(...)`
  - `percent`
    - Сигнатура: `percent(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.percent()`
  - `percent`
    - Сигнатура: `percent(self, value)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `value`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `value`.
    - Пример: `obj.percent(...)`
  - `sound_id`
    - Сигнатура: `sound_id(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.sound_id()`
  - `sound_id`
    - Сигнатура: `sound_id(self, value)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `value`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `value`.
    - Пример: `obj.sound_id(...)`

### `ProtoGimbalRotate`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): bytearray, pack_into
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`
  - `unpack_resp`
    - Сигнатура: `unpack_resp(self, buf, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_resp(...)`

### `ProtoGimbalActionPush`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`
  - `unpack_req`
    - Сигнатура: `unpack_req(self, buf, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): unpack_from
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_req(...)`
  - `unpack_resp`
    - Сигнатура: `unpack_resp(self, buf, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): unpack_from
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_resp(...)`

### `ProtoGimbalRecenter`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): bytearray, pack_into
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`
  - `unpack_resp`
    - Сигнатура: `unpack_resp(self, buf, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_resp(...)`

### `ProtoVisionDetectStatus`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`
  - `unpack_resp`
    - Сигнатура: `unpack_resp(self, buf, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): warning
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_resp(...)`

### `ProtoVisionSetColor`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): bytearray
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`
  - `unpack_resp`
    - Сигнатура: `unpack_resp(self, buf, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): warning, format
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_resp(...)`

### `ProtoPositionMove`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): bytearray, pack_into
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`
  - `unpack_resp`
    - Сигнатура: `unpack_resp(self, buf, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): warning, format
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_resp(...)`

### `ProtoPositionPush`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`
  - `unpack_req`
    - Сигнатура: `unpack_req(self, buf, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): unpack_from
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_req(...)`
  - `unpack_resp`
    - Сигнатура: `unpack_resp(self, buf, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): unpack_from
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_resp(...)`

### `ProtoSetWheelSpeed`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): bytearray, pack_into
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`
  - `unpack_resp`
    - Сигнатура: `unpack_resp(self, buf, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): warning, format
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_resp(...)`

### `ProtoChassisSetWorkMode`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): bytearray
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`
  - `unpack_resp`
    - Сигнатура: `unpack_resp(self, buf, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_resp(...)`

### `ProtoChassisSpeedMode`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): float
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): bytearray, pack_into
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`
  - `unpack_resp`
    - Сигнатура: `unpack_resp(self, buf, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_resp(...)`

### `ProtoChassisPwmPercent`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): bytearray, pack_into
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`
  - `unpack_resp`
    - Сигнатура: `unpack_resp(self, buf, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_resp(...)`

### `ProtoChassisPwmFreq`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): bytearray, pack_into
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`
  - `unpack_resp`
    - Сигнатура: `unpack_resp(self, buf, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_resp(...)`

### `ProtoChassisSerialSet`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): bytearray, pack_into
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`
  - `unpack_resp`
    - Сигнатура: `unpack_resp(self, buf, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_resp(...)`

### `ProtoChassisSerialMsgSend`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): bytearray, pack_into, len
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`
  - `unpack_resp`
    - Сигнатура: `unpack_resp(self, buf, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_resp(...)`

### `ProtoVisionDetectEnable`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): bytearray, pack_into
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`
  - `unpack_resp`
    - Сигнатура: `unpack_resp(self, buf, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): unpack_from, warning, format
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_resp(...)`

### `ProtoVisionDetectInfo`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`
  - `unpack_req`
    - Сигнатура: `unpack_req(self, buf, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): range, unpack_from, append, round, warning, format
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_req(...)`

### `ProtoSubscribeAddNode`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): bytearray, pack_into
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`
  - `unpack_resp`
    - Сигнатура: `unpack_resp(self, buf, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): warning, format
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_resp(...)`

### `ProtoSubNodeReset`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): bytearray
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`
  - `unpack_resp`
    - Сигнатура: `unpack_resp(self, buf, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_resp(...)`

### `ProtoDelMsg`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): bytearray
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`
  - `unpack_resp`
    - Сигнатура: `unpack_resp(self, buf, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_resp(...)`

### `ProtoAddSubMsg`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): bytearray, range, pack_into, info, format, hexlify
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`
  - `unpack_resp`
    - Сигнатура: `unpack_resp(self, buf, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_resp(...)`

### `ProtoPushPeriodMsg`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`
  - `unpack_req`
    - Сигнатура: `unpack_req(self, buf, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_req(...)`

### `ProtoGripperCtrl`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): host2byte
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): bytearray, pack_into, debug, format, hexlify
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`
  - `unpack_resp`
    - Сигнатура: `unpack_resp(self, buf, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_resp(...)`

### `ProtoRoboticArmMove`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): host2byte
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): bytearray, pack_into
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`
  - `unpack_resp`
    - Сигнатура: `unpack_resp(self, buf, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_resp(...)`

### `ProtoRoboticArmGetPostion`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): bytearray
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`
  - `unpack_resp`
    - Сигнатура: `unpack_resp(self, buf, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): unpack_from
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_resp(...)`

### `ProtoSensorGetData`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): bytearray
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`
  - `unpack_resp`
    - Сигнатура: `unpack_resp(self, buf, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): unpack_from
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_resp(...)`

### `ProtoServoModeSet`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): bytearray
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`

### `ProtoServoControl`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): bytearray, pack_into
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`

### `ProtoServoGetAngle`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): bytearray
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`
  - `unpack_resp`
    - Сигнатура: `unpack_resp(self, buf, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_resp(...)`

### `ProtoServoCtrlSet`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): bytearray, host2byte, pack_into
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`
  - `unpack_resp`
    - Сигнатура: `unpack_resp(self, buf, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): warning, format
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_resp(...)`

### `ProtoServoCtrlPush`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`
  - `unpack_req`
    - Сигнатура: `unpack_req(self, buf, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): unpack_from
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_req(...)`

### `ProtoRoboticArmMoveCtrl`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): host2byte
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): bytearray, pack_into
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`
  - `unpack_resp`
    - Сигнатура: `unpack_resp(self, buf, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): warning, format
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_resp(...)`

### `ProtoRoboticArmMovePush`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`
  - `unpack_req`
    - Сигнатура: `unpack_req(self, buf, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): unpack_from
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_req(...)`

### `ProtoRoboticAiInit`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): randint
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): bytearray, crc8_calc, crc16_calc
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`
  - `unpack_req`
    - Сигнатура: `unpack_req(self, buf, offset=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_req(...)`

### `TextProtoData`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `__repr__` (приватный)
    - Сигнатура: `__repr__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): format
    - Аргументы:
      - нет аргументов
    - Пример: `obj.__repr__()`
  - `text_cmd`
    - Сигнатура: `text_cmd(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.text_cmd()`
  - `text_cmd`
    - Сигнатура: `text_cmd(self, cmd)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `cmd`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `cmd`.
    - Пример: `obj.text_cmd(...)`
  - `pack_req`
    - Сигнатура: `pack_req(self)`
    - Приватный: нет
    - Описание: 协议对象打包发送数据为字节流。
    - Связи (вызовы): debug, format, type
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_req()`
  - `unpack_req`
    - Сигнатура: `unpack_req(self, buf, offset=0)`
    - Приватный: нет
    - Описание: 从字节流解包。
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_req(...)`
  - `pack_resp`
    - Сигнатура: `pack_resp(self)`
    - Приватный: нет
    - Описание: 协议对象打包。
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack_resp()`
  - `unpack_resp`
    - Сигнатура: `unpack_resp(self, buf, offset=0)`
    - Приватный: нет
    - Описание: 从字节流解包为返回值和相关属性。
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
      - `offset`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `offset`.
    - Пример: `obj.unpack_resp(...)`
  - `get_status`
    - Сигнатура: `get_status(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.get_status()`
  - `resp`
    - Сигнатура: `resp(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): strip
    - Аргументы:
      - нет аргументов
    - Пример: `obj.resp()`
  - `proresp`
    - Сигнатура: `proresp(self)`
    - Приватный: нет
    - Описание: 针对acceleration?、attitude?、temp?命令的回复进行预处理。
    - Связи (вызовы): dict, len, int, split, warning, float
    - Аргументы:
      - нет аргументов
    - Пример: `obj.proresp()`

### `TextProtoDrone`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): __init__, super
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)

### `TextProtoDronePush`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): __init__, super
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)

### `TelloDdsProto`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)

### `STAConnInfo`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `set_info`
    - Сигнатура: `set_info(self, ssid='', password='', id='', cc='CN')`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `ssid`: тип `не указан`; единицы `не указаны`; допустимые значения `ID/целое`; параметр `ssid`.
      - `password`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `password`.
      - `id`: тип `не указан`; единицы `не указаны`; допустимые значения `ID/целое`; параметр `id`.
      - `cc`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `cc`.
    - Пример: `obj.set_info()`
  - `pack`
    - Сигнатура: `pack(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): len, encode, bytearray
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pack()`
  - `unpack`
    - Сигнатура: `unpack(self, buf)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): bytearray, unpack_from, format, replace, int, str
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
    - Пример(ы) из репозитория:
      - `value = struct.unpack('i', bytearray(buf))[0]` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_buffers.py:92`)
      - `value = struct.unpack('i', bytearray(buf))[0]` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/ubuntu/src/pybind11/tests/test_buffers.py:92`)


## Модуль `src.robomaster.robot` (`src/robomaster/robot.py`)

### Классы

### `RobotPlaySoundAction`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self, sound_id, times, **kw)`
  - **Аргументы конструктора:**
    - `sound_id`: тип `не указан`; единицы `не указаны`; допустимые значения `ID/целое`; инициализационный параметр `sound_id`.
    - `times`: тип `не указан`; единицы `с`; допустимые значения `не указаны`; инициализационный параметр `times`.
    - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; инициализационный параметр `**kw`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, sound_id, times, **kw)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): __init__, super
    - Аргументы:
      - `sound_id`: тип `не указан`; единицы `не указаны`; допустимые значения `ID/целое`; параметр `sound_id`.
      - `times`: тип `не указан`; единицы `с`; допустимые значения `не указаны`; параметр `times`.
      - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `**kw`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `__repr__` (приватный)
    - Сигнатура: `__repr__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): format
    - Аргументы:
      - нет аргументов
    - Пример: `obj.__repr__()`
  - `encode`
    - Сигнатура: `encode(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): _action_proto_cls
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `return socket_obj.send(data.encode('utf-8'))` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:217`)
      - `ser.write('command'.encode('utf-8'))` (из `examples/plaintext_sample_code/RoboMasterEP/connection/uart/uart_connection.py:16`)
  - `update_from_push`
    - Сигнатура: `update_from_push(self, proto)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): _update_action_state, info, format
    - Аргументы:
      - `proto`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `proto`.
    - Пример: `obj.update_from_push(...)`

### `TelloTempInfoSubject`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `temp_info`
    - Сигнатура: `temp_info(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.temp_info()`
  - `data_info`
    - Сигнатура: `data_info(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.data_info()`
  - `decode`
    - Сигнатура: `decode(self, buf)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): split, debug, int, format
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
    - Пример(ы) из репозитория:
      - `msg = msg.decode('utf-8')` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:68`)
      - `assert m.str_from_string().encode().decode() == "baz"` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_pytypes.py:73`)

### `TelloTofInfoSubject`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `tof_info`
    - Сигнатура: `tof_info(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.tof_info()`
  - `data_info`
    - Сигнатура: `data_info(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.data_info()`
  - `decode`
    - Сигнатура: `decode(self, buf)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): split, debug, int, format
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
    - Пример(ы) из репозитория:
      - `msg = msg.decode('utf-8')` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:68`)
      - `assert m.str_from_string().encode().decode() == "baz"` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_pytypes.py:73`)

### `TelloDroneInfoSubject`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `drone_info`
    - Сигнатура: `drone_info(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.drone_info()`
  - `data_info`
    - Сигнатура: `data_info(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.data_info()`
  - `decode`
    - Сигнатура: `decode(self, buf)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): split, startswith, warning, int, format, float
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
    - Пример(ы) из репозитория:
      - `msg = msg.decode('utf-8')` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:68`)
      - `assert m.str_from_string().encode().decode() == "baz"` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_pytypes.py:73`)

### `TelloStatusSubject`
- **Приватный класс:** нет
- **Описание:** Tello 飞机的所有状态数据
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `decode`
    - Сигнатура: `decode(self, buf)`
    - Приватный: нет
    - Описание: 根据数据推送更新 drone 的状态数据
    - Связи (вызовы): split, clear, range, float, append
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
    - Пример(ы) из репозитория:
      - `msg = msg.decode('utf-8')` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:68`)
      - `assert m.str_from_string().encode().decode() == "baz"` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_pytypes.py:73`)
  - `freq`
    - Сигнатура: `freq(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.freq()`
  - `freq`
    - Сигнатура: `freq(self, in_freq)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `in_freq`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `in_freq`.
    - Пример: `obj.freq(...)`
  - `pad_position`
    - Сигнатура: `pad_position(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.pad_position()`
  - `get_status`
    - Сигнатура: `get_status(self, name)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `name`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `name`.
    - Пример: `obj.get_status(...)`

### `RobotBase`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self, cli=None, conf=config.ep_conf)`
  - **Аргументы конструктора:**
    - `cli`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; инициализационный параметр `cli`.
    - `conf`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; инициализационный параметр `conf`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, cli=None, conf=config.ep_conf)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `cli`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `cli`.
      - `conf`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `conf`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `client`
    - Сигнатура: `client(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.client()`
  - `product`
    - Сигнатура: `product(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.product()`

### `Drone`
- **Приватный класс:** нет
- **Описание:** 教育系列无人机
- **Конструктор:** `__init__(self, cli=None)`
  - **Аргументы конструктора:**
    - `cli`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; инициализационный параметр `cli`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, cli=None)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): __init__, super
    - Аргументы:
      - `cli`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `cli`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `conf`
    - Сигнатура: `conf(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.conf()`
  - `flight`
    - Сигнатура: `flight(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): get_module
    - Аргументы:
      - нет аргументов
    - Пример: `obj.flight()`
  - `action_dispatcher`
    - Сигнатура: `action_dispatcher(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.action_dispatcher()`
  - `battery`
    - Сигнатура: `battery(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): get_module
    - Аргументы:
      - нет аргументов
    - Пример: `obj.battery()`
  - `camera`
    - Сигнатура: `camera(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): get_module
    - Аргументы:
      - нет аргументов
    - Пример: `obj.camera()`
  - `dds`
    - Сигнатура: `dds(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): get_module
    - Аргументы:
      - нет аргументов
    - Пример: `obj.dds()`
  - `sensor`
    - Сигнатура: `sensor(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): get_module
    - Аргументы:
      - нет аргументов
    - Пример: `obj.sensor()`
  - `led`
    - Сигнатура: `led(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): get_module
    - Аргументы:
      - нет аргументов
    - Пример: `obj.led()`
  - `ai_module`
    - Сигнатура: `ai_module(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): get_module
    - Аргументы:
      - нет аргументов
    - Пример: `obj.ai_module()`
  - `get_module`
    - Сигнатура: `get_module(self, name)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `name`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `name`.
    - Пример: `obj.get_module(...)`
  - `_scan_modules` (приватный)
    - Сигнатура: `_scan_modules(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): Flight, TelloCamera, TelloBattery, TelloAI, TelloSubscriber, start
    - Аргументы:
      - нет аргументов
    - Пример: `obj._scan_modules()`
  - `get_subnets`
    - Сигнатура: `get_subnets(self)`
    - Приватный: нет
    - Описание: Look through the machine's internet connection and
    - Связи (вызовы): interfaces, ifaddresses, IPNetwork, append
    - Аргументы:
      - нет аргументов
    - Пример: `obj.get_subnets()`
  - `_scan_host` (приватный)
    - Сигнатура: `_scan_host(self, timeout=10)`
    - Приватный: да
    - Описание: Find avaliable ip list in server's subnets
    - Связи (вызовы): info, get_subnets, time, IPNetwork, len, append
    - Аргументы:
      - `timeout`: тип `не указан`; единицы `с`; допустимые значения `не указаны`; параметр `timeout`.
    - Пример: `obj._scan_host()`
  - `scan_drone_robot`
    - Сигнатура: `scan_drone_robot(self)`
    - Приватный: нет
    - Описание: Automatic scanning of robots in the network
    - Связи (вызовы): Thread, start, _scan_host, join
    - Аргументы:
      - нет аргументов
    - Пример: `obj.scan_drone_robot()`
  - `_scan_receive_task` (приватный)
    - Сигнатура: `_scan_receive_task(self)`
    - Приватный: да
    - Описание: Listen to responses from the Tello when scan the devices.
    - Связи (вызовы): info, len, recvfrom, join, format, str
    - Аргументы:
      - нет аргументов
    - Пример: `obj._scan_receive_task()`
  - `start`
    - Сигнатура: `start(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): socket, bind, get_local_ip, warning, format
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `self.cmd_socket_recv_thread.start()` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:90`)
      - `t.start()` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_callbacks.py:135`)
  - `search_stop`
    - Сигнатура: `search_stop(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): close
    - Аргументы:
      - нет аргументов
    - Пример: `obj.search_stop()`
  - `initialize`
    - Сигнатура: `initialize(self, conn_type=config.DEFAULT_CONN_TYPE)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): ActionDispatcher, initialize, _scan_modules, _enable_sdk, start, info
    - Аргументы:
      - `conn_type`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `conn_type`.
    - Пример(ы) из репозитория:
      - `ep_robot.initialize(conn_type='rndis')` (из `examples/01_robot/00_logger.py:30`)
      - `ep_robot.initialize(conn_type="ap")` (из `examples/01_robot/01_get_version.py:22`)
  - `_enable_sdk` (приватный)
    - Сигнатура: `_enable_sdk(self, on_off=1)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): TextProtoDrone, TextMsg, get_status, send_sync_msg, get_proto, info
    - Аргументы:
      - `on_off`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `on_off`.
    - Пример: `obj._enable_sdk()`
  - `close`
    - Сигнатура: `close(self)`
    - Приватный: нет
    - Описание: 停止drone对象
    - Связи (вызовы): _enable_sdk, stop, info
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `ep_robot.close()` (из `examples/01_robot/00_logger.py:34`)
      - `ep_robot.close()` (из `examples/01_robot/01_get_version.py:27`)
  - `send_command`
    - Сигнатура: `send_command(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): _enable_sdk
    - Аргументы:
      - нет аргументов
    - Пример: `obj.send_command()`
  - `get_sdk_version`
    - Сигнатура: `get_sdk_version(self)`
    - Приватный: нет
    - Описание: 获取SDK版本号
    - Связи (вызовы): TextProtoDrone, TextMsg, send_sync_msg, get_proto, warning, format
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `version = tl_drone.get_sdk_version()` (из `examples/12_drone/00_logger.py:28`)
      - `version = tl_drone.get_sdk_version()` (из `examples/12_drone/01_ap_conn.py:28`)
  - `get_wifi_version`
    - Сигнатура: `get_wifi_version(self)`
    - Приватный: нет
    - Описание: 获取WIFI版本号
    - Связи (вызовы): TextProtoDrone, TextMsg, send_sync_msg, get_proto, warning, format
    - Аргументы:
      - нет аргументов
    - Пример: `obj.get_wifi_version()`
  - `get_ssid`
    - Сигнатура: `get_ssid(self)`
    - Приватный: нет
    - Описание: 获取SSID名称
    - Связи (вызовы): TextProtoDrone, TextMsg, send_sync_msg, get_proto, warning, format
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `ssid = tl_drone.get_ssid()` (из `examples/12_drone/24_get_ssid.py:26`)
  - `get_drone_version`
    - Сигнатура: `get_drone_version(self)`
    - Приватный: нет
    - Описание: 获取飞机固件版本号
    - Связи (вызовы): TextProtoDrone, TextMsg, send_sync_msg, get_proto, warning, format
    - Аргументы:
      - нет аргументов
    - Пример: `obj.get_drone_version()`
  - `get_esp32_version`
    - Сигнатура: `get_esp32_version(self)`
    - Приватный: нет
    - Описание: 获取esp32版本号
    - Связи (вызовы): TextProtoDrone, TextMsg, send_sync_msg, get_proto, warning, format
    - Аргументы:
      - нет аргументов
    - Пример: `obj.get_esp32_version()`
  - `get_hardware`
    - Сигнатура: `get_hardware(self)`
    - Приватный: нет
    - Описание: 获取飞机硬件信息
    - Связи (вызовы): TextProtoDrone, TextMsg, send_sync_msg, get_proto, warning, format
    - Аргументы:
      - нет аргументов
    - Пример: `obj.get_hardware()`
  - `get_sn`
    - Сигнатура: `get_sn(self)`
    - Приватный: нет
    - Описание: 获取飞机sn号
    - Связи (вызовы): TextProtoDrone, TextMsg, send_sync_msg, get_proto, warning, format
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `SN = ep_robot.get_sn()` (из `examples/01_robot/02_get_sn.py:24`)
      - `SN = tl_drone.get_sn()` (из `examples/12_drone/03_get_sn.py:26`)
  - `get_wifi`
    - Сигнатура: `get_wifi(self)`
    - Приватный: нет
    - Описание: 获取wifi信噪比
    - Связи (вызовы): TextProtoDrone, TextMsg, send_sync_msg, get_proto, warning, float
    - Аргументы:
      - нет аргументов
    - Пример: `obj.get_wifi()`
  - `get_motor_time`
    - Сигнатура: `get_motor_time(self)`
    - Приватный: нет
    - Описание: 获取电机运行时间
    - Связи (вызовы): TextProtoDrone, TextMsg, send_sync_msg, get_proto, warning, format
    - Аргументы:
      - нет аргументов
    - Пример: `obj.get_motor_time()`
  - `get_height`
    - Сигнатура: `get_height(self)`
    - Приватный: нет
    - Описание: 获取飞机相对高度
    - Связи (вызовы): TextProtoDrone, TextMsg, send_sync_msg, get_proto, warning, format
    - Аргументы:
      - нет аргументов
    - Пример: `obj.get_height()`
  - `get_temp`
    - Сигнатура: `get_temp(self)`
    - Приватный: нет
    - Описание: 获取飞机机身温度
    - Связи (вызовы): TextProtoDrone, TextMsg, send_sync_msg, get_proto, warning, format
    - Аргументы:
      - нет аргументов
    - Пример: `obj.get_temp()`
  - `get_attitude`
    - Сигнатура: `get_attitude(self)`
    - Приватный: нет
    - Описание: 获取飞机三轴姿态信息
    - Связи (вызовы): TextProtoDrone, TextMsg, send_sync_msg, get_proto, warning, format
    - Аргументы:
      - нет аргументов
    - Пример: `obj.get_attitude()`
  - `get_baro`
    - Сигнатура: `get_baro(self)`
    - Приватный: нет
    - Описание: 获取电机气压计高度
    - Связи (вызовы): TextProtoDrone, TextMsg, send_sync_msg, get_proto, warning, float
    - Аргументы:
      - нет аргументов
    - Пример: `obj.get_baro()`
  - `get_acceleration`
    - Сигнатура: `get_acceleration(self)`
    - Приватный: нет
    - Описание: 获取飞机三轴加速度值
    - Связи (вызовы): TextProtoDrone, TextMsg, send_sync_msg, get_proto, warning, format
    - Аргументы:
      - нет аргументов
    - Пример: `obj.get_acceleration()`
  - `set_wifichannel`
    - Сигнатура: `set_wifichannel(self, channel)`
    - Приватный: нет
    - Описание: 设置飞机WIFI信道
    - Связи (вызовы): format, TextProtoDrone, TextMsg, send_sync_msg, get_proto, warning
    - Аргументы:
      - `channel`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; 需要设置的信道
    - Пример: `obj.set_wifichannel(...)`
  - `config_sta`
    - Сигнатура: `config_sta(self, ssid, password)`
    - Приватный: нет
    - Описание: 设置飞机的连接模式为组网模式
    - Связи (вызовы): format, TextProtoDrone, TextMsg, send_sync_msg, warning, get_proto
    - Аргументы:
      - `ssid`: тип `не указан`; единицы `не указаны`; допустимые значения `ID/целое`; 路由器的账号
      - `password`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 路由器的密码
    - Пример(ы) из репозитория:
      - `tl_drone.config_sta(ssid="RoboMaster_SDK_WiFi", password="12341234")` (из `examples/12_drone/23_set_sta.py:26`)
  - `sub_temp`
    - Сигнатура: `sub_temp(self, freq=5, callback=None, *args, **kw)`
    - Приватный: нет
    - Описание: 订阅飞机温度信息
    - Связи (вызовы): TelloTempInfoSubject, add_subject_info
    - Аргументы:
      - `freq`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 订阅数据的频率, 1HZ, 5HZ, 10HZ
      - `callback`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 传入数据处理的回掉函数
      - `*args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 回调函数参数
      - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; 回调函数参数
    - Пример: `obj.sub_temp()`
  - `unsub_temp`
    - Сигнатура: `unsub_temp(self)`
    - Приватный: нет
    - Описание: 取消订阅温度信息。
    - Связи (вызовы): del_subject_info
    - Аргументы:
      - нет аргументов
    - Пример: `obj.unsub_temp()`
  - `sub_tof`
    - Сигнатура: `sub_tof(self, freq=5, callback=None, *args, **kw)`
    - Приватный: нет
    - Описание: 订阅飞机tof信息
    - Связи (вызовы): TelloTofInfoSubject, add_subject_info
    - Аргументы:
      - `freq`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 订阅数据的频率, 1HZ, 5HZ, 10HZ
      - `callback`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 传入数据处理的回掉函数
      - `*args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 回调函数参数
      - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; 回调函数参数
    - Пример(ы) из репозитория:
      - `tl_drone.sub_tof(freq=10, callback=sub_tof_info_handler)` (из `examples/12_drone/17_sub_info.py:36`)
  - `unsub_tof`
    - Сигнатура: `unsub_tof(self)`
    - Приватный: нет
    - Описание: 取消订阅tof信息
    - Связи (вызовы): del_subject_info
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `tl_drone.unsub_tof()` (из `examples/12_drone/17_sub_info.py:44`)
  - `sub_drone_info`
    - Сигнатура: `sub_drone_info(self, freq=5, callback=None, *args, **kw)`
    - Приватный: нет
    - Описание: 订阅飞机高度、气压计、电机运行时间信息
    - Связи (вызовы): TelloDroneInfoSubject, add_subject_info
    - Аргументы:
      - `freq`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 订阅数据的频率, 1HZ, 5HZ, 10HZ
      - `callback`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 传入数据处理的回掉函数
      - `*args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 回调函数参数
      - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; 回调函数参数
    - Пример(ы) из репозитория:
      - `tl_drone.sub_drone_info(freq=1, callback=sub_drone_info_handler)` (из `examples/12_drone/17_sub_info.py:37`)
  - `unsub_drone_info`
    - Сигнатура: `unsub_drone_info(self)`
    - Приватный: нет
    - Описание: 取消订阅飞机高度、气压计、电机运行时间信息
    - Связи (вызовы): del_subject_info
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `tl_drone.unsub_drone_info()` (из `examples/12_drone/17_sub_info.py:45`)
  - `_sub_drone_all_status` (приватный)
    - Сигнатура: `_sub_drone_all_status(self, freq=10, callback=None, *args, **kw)`
    - Приватный: да
    - Описание: 订阅飞机所有状态数据
    - Связи (вызовы): TelloStatusSubject, add_subject_info
    - Аргументы:
      - `freq`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 订阅数据的频率, 1HZ, 5HZ, 10HZ
      - `callback`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; function:传入数据处理的回掉函数
      - `*args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 回调函数参数
      - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; 回调函数参数
    - Пример: `obj._sub_drone_all_status()`
  - `_unsub_drone_all_status` (приватный)
    - Сигнатура: `_unsub_drone_all_status(self)`
    - Приватный: да
    - Описание: 取消订阅飞机所有状态
    - Связи (вызовы): del_subject_info
    - Аргументы:
      - нет аргументов
    - Пример: `obj._unsub_drone_all_status()`
  - `get_status`
    - Сигнатура: `get_status(self, name)`
    - Приватный: нет
    - Описание: 获取飞机指定的状态
    - Связи (вызовы): get_status
    - Аргументы:
      - `name`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; string:需要获取的状态名，可列表["MID", "x", "y", "z", "mpry", "pitch", "roll", "yaw", "vgx", "vgy",
    - Пример: `obj.get_status(...)`

### `Robot`
- **Приватный класс:** нет
- **Описание:** RoboMaster EP 机甲大师 机器人
- **Конструктор:** `__init__(self, cli=None)`
  - **Аргументы конструктора:**
    - `cli`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; инициализационный параметр `cli`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, cli=None)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): __init__, SdkConnection, FtpConnection, super
    - Аргументы:
      - `cli`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `cli`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `__del__` (приватный)
    - Сигнатура: `__del__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): close, list, keys
    - Аргументы:
      - нет аргументов
    - Пример: `obj.__del__()`
  - `_start_heart_beat_timer` (приватный)
    - Сигнатура: `_start_heart_beat_timer(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): _send_heart_beat_msg
    - Аргументы:
      - нет аргументов
    - Пример: `obj._start_heart_beat_timer()`
  - `_stop_heart_beat_timer` (приватный)
    - Сигнатура: `_stop_heart_beat_timer(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): cancel
    - Аргументы:
      - нет аргументов
    - Пример: `obj._stop_heart_beat_timer()`
  - `_send_heart_beat_msg` (приватный)
    - Сигнатура: `_send_heart_beat_msg(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): ProtoSdkHeartBeat, Msg, host2byte, send_msg, Timer, start
    - Аргументы:
      - нет аргументов
    - Пример: `obj._send_heart_beat_msg()`
  - `conf`
    - Сигнатура: `conf(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.conf()`
  - `action_dispatcher`
    - Сигнатура: `action_dispatcher(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.action_dispatcher()`
  - `ip`
    - Сигнатура: `ip(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.ip()`
  - `conn_type`
    - Сигнатура: `conn_type(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.conn_type()`
  - `proto_type`
    - Сигнатура: `proto_type(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.proto_type()`
  - `chassis`
    - Сигнатура: `chassis(self)`
    - Приватный: нет
    - Описание: 获取底盘模块对象
    - Связи (вызовы): get_module
    - Аргументы:
      - нет аргументов
    - Пример: `obj.chassis()`
  - `gimbal`
    - Сигнатура: `gimbal(self)`
    - Приватный: нет
    - Описание: 获取云台模块对象
    - Связи (вызовы): get_module
    - Аргументы:
      - нет аргументов
    - Пример: `obj.gimbal()`
  - `blaster`
    - Сигнатура: `blaster(self)`
    - Приватный: нет
    - Описание: 获取水弹枪模块对象
    - Связи (вызовы): get_module
    - Аргументы:
      - нет аргументов
    - Пример: `obj.blaster()`
  - `led`
    - Сигнатура: `led(self)`
    - Приватный: нет
    - Описание: 获取灯效控制模块对象
    - Связи (вызовы): get_module
    - Аргументы:
      - нет аргументов
    - Пример: `obj.led()`
  - `vision`
    - Сигнатура: `vision(self)`
    - Приватный: нет
    - Описание: 获取智能识别模块对象
    - Связи (вызовы): get_module
    - Аргументы:
      - нет аргументов
    - Пример: `obj.vision()`
  - `battery`
    - Сигнатура: `battery(self)`
    - Приватный: нет
    - Описание: 获取电池模块对象
    - Связи (вызовы): get_module
    - Аргументы:
      - нет аргументов
    - Пример: `obj.battery()`
  - `camera`
    - Сигнатура: `camera(self)`
    - Приватный: нет
    - Описание: 获取相机模块对象
    - Связи (вызовы): get_module
    - Аргументы:
      - нет аргументов
    - Пример: `obj.camera()`
  - `robotic_arm`
    - Сигнатура: `robotic_arm(self)`
    - Приватный: нет
    - Описание: 获取机械臂模块对象
    - Связи (вызовы): get_module
    - Аргументы:
      - нет аргументов
    - Пример: `obj.robotic_arm()`
  - `dds`
    - Сигнатура: `dds(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): get_module
    - Аргументы:
      - нет аргументов
    - Пример: `obj.dds()`
  - `servo`
    - Сигнатура: `servo(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): get_module
    - Аргументы:
      - нет аргументов
    - Пример: `obj.servo()`
  - `sensor`
    - Сигнатура: `sensor(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): get_module
    - Аргументы:
      - нет аргументов
    - Пример: `obj.sensor()`
  - `sensor_adaptor`
    - Сигнатура: `sensor_adaptor(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): get_module
    - Аргументы:
      - нет аргументов
    - Пример: `obj.sensor_adaptor()`
  - `gripper`
    - Сигнатура: `gripper(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): get_module
    - Аргументы:
      - нет аргументов
    - Пример: `obj.gripper()`
  - `armor`
    - Сигнатура: `armor(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): get_module
    - Аргументы:
      - нет аргументов
    - Пример: `obj.armor()`
  - `uart`
    - Сигнатура: `uart(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): get_module
    - Аргументы:
      - нет аргументов
    - Пример: `obj.uart()`
  - `ai_module`
    - Сигнатура: `ai_module(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): get_module
    - Аргументы:
      - нет аргументов
    - Пример: `obj.ai_module()`
  - `is_initialized`
    - Сигнатура: `is_initialized(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.is_initialized()`
  - `_scan_modules` (приватный)
    - Сигнатура: `_scan_modules(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): Gimbal, Chassis, EPCamera, Blaster, Vision, Subscriber
    - Аргументы:
      - нет аргументов
    - Пример: `obj._scan_modules()`
  - `get_module`
    - Сигнатура: `get_module(self, name)`
    - Приватный: нет
    - Описание: 获取模块对象
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `name`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; 模块名称，字符串，如：chassis, gimbal, led, blaster, camera, battery, vision, etc.
    - Пример: `obj.get_module(...)`
  - `initialize`
    - Сигнатура: `initialize(self, conn_type=config.DEFAULT_CONN_TYPE, proto_type=config.DEFAULT_PROTO_TYPE, sn=None)`
    - Приватный: нет
    - Описание: 初始化机器人
    - Связи (вызовы): ActionDispatcher, initialize, _scan_modules, _enable_sdk, reset, connect
    - Аргументы:
      - `conn_type`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; 连接建立类型: ap表示使用热点直连；sta表示使用组网连接，rndis表示使用USB连接
      - `proto_type`: тип `не указан`; единицы `м`; допустимые значения `0..255`; 通讯方式: tcp, udp
      - `sn`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `sn`.
    - Пример(ы) из репозитория:
      - `ep_robot.initialize(conn_type='rndis')` (из `examples/01_robot/00_logger.py:30`)
      - `ep_robot.initialize(conn_type="ap")` (из `examples/01_robot/01_get_version.py:22`)
  - `close`
    - Сигнатура: `close(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): stop, list, info, _enable_sdk, _stop_heart_beat_timer, keys
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `ep_robot.close()` (из `examples/01_robot/00_logger.py:34`)
      - `ep_robot.close()` (из `examples/01_robot/01_get_version.py:27`)
  - `_wait_for_connection` (приватный)
    - Сигнатура: `_wait_for_connection(self, conn_type, proto_type, sn=None)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): request_connection, Connection, error, format
    - Аргументы:
      - `conn_type`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `conn_type`.
      - `proto_type`: тип `не указан`; единицы `м`; допустимые значения `0..255`; параметр `proto_type`.
      - `sn`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `sn`.
    - Пример: `obj._wait_for_connection(..., ...)`
  - `reset`
    - Сигнатура: `reset(self)`
    - Приватный: нет
    - Описание: 重置机器人到初始默认状态
    - Связи (вызовы): _sub_node_reset, _sub_add_node, set_robot_mode, reset
    - Аргументы:
      - нет аргументов
    - Пример: `obj.reset()`
  - `reset_robot_mode`
    - Сигнатура: `reset_robot_mode(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): ProtoSetRobotMode, Msg, host2byte, send_sync_msg, warning, format
    - Аргументы:
      - нет аргументов
    - Пример: `obj.reset_robot_mode()`
  - `set_robot_mode`
    - Сигнатура: `set_robot_mode(self, mode=GIMBAL_LEAD)`
    - Приватный: нет
    - Описание: 设置机器人工作模式
    - Связи (вызовы): ProtoSetRobotMode, Msg, host2byte, send_sync_msg, reset_robot_mode, warning
    - Аргументы:
      - `mode`: тип `не указан`; единицы `не указаны`; допустимые значения `enum/строка`; 机器人工作模式: free表示自由模式；chassis_lead表示云台跟随底盘模式；gimbal_lead表示底盘跟随云台模式
    - Пример(ы) из репозитория:
      - `ep_robot.set_robot_mode(mode=robot.GIMBAL_LEAD)` (из `examples/01_robot/09_set_mode.py:24`)
      - `ep.set_robot_mode(mode=robot.GIMBAL_LEAD)` (из `examples/16_gamesystem/00_gamesystem.py:56`)
  - `get_robot_mode`
    - Сигнатура: `get_robot_mode(self)`
    - Приватный: нет
    - Описание: 获取机器人工作模式
    - Связи (вызовы): Msg, host2byte, ProtoGetRobotMode, send_sync_msg, get_proto, Exception
    - Аргументы:
      - нет аргументов
    - Пример: `obj.get_robot_mode()`
  - `_enable_sdk` (приватный)
    - Сигнатура: `_enable_sdk(self, enable=1)`
    - Приватный: да
    - Описание: 进入和退出SDK模式
    - Связи (вызовы): ProtoSetSdkMode, Msg, host2byte, send_sync_msg, warning, format
    - Аргументы:
      - `enable`: тип `не указан`; единицы `0-255`; допустимые значения `True/False`; 进入或退出SDK模式，1 为进入SDK模式，0 为退出SDK模式
    - Пример: `obj._enable_sdk()`
  - `get_version`
    - Сигнатура: `get_version(self)`
    - Приватный: нет
    - Описание: 获取机器人固件版本号信息
    - Связи (вызовы): ProtoGetProductVersion, Msg, host2byte, send_sync_msg, get_proto, warning
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `version = ep_robot.get_version()` (из `examples/01_robot/00_logger.py:32`)
      - `ep_version = ep_robot.get_version()` (из `examples/01_robot/01_get_version.py:24`)
  - `get_sn`
    - Сигнатура: `get_sn(self)`
    - Приватный: нет
    - Описание: 获取机器人硬件SN信息
    - Связи (вызовы): ProtoGetSn, Msg, host2byte, send_sync_msg, get_proto, warning
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `SN = ep_robot.get_sn()` (из `examples/01_robot/02_get_sn.py:24`)
      - `SN = tl_drone.get_sn()` (из `examples/12_drone/03_get_sn.py:26`)
  - `_sub_add_node` (приватный)
    - Сигнатура: `_sub_add_node(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): ProtoSubscribeAddNode, Msg, host2byte, send_sync_msg, warning, format
    - Аргументы:
      - нет аргументов
    - Пример: `obj._sub_add_node()`
  - `_sub_node_reset` (приватный)
    - Сигнатура: `_sub_node_reset(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): ProtoSubNodeReset, Msg, host2byte, send_sync_msg, warning, format
    - Аргументы:
      - нет аргументов
    - Пример: `obj._sub_node_reset()`
  - `play_audio`
    - Сигнатура: `play_audio(self, filename)`
    - Приватный: нет
    - Описание: 播放本地音频文件
    - Связи (вызовы): format, upload, info, play_sound, exists, error
    - Аргументы:
      - `filename`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; 播放音效的文件名，目前仅支持单通道，48KHz采样的wav格式文件
    - Пример(ы) из репозитория:
      - `ep_robot.play_audio(filename="demo1.wav").wait_for_completed()` (из `examples/01_robot/03_play_audio.py:27`)
      - `ep_robot.play_audio(filename="demo2.wav").wait_for_completed()` (из `examples/01_robot/03_play_audio.py:28`)
  - `play_sound`
    - Сигнатура: `play_sound(self, sound_id, times=1)`
    - Приватный: нет
    - Описание: 播放系统音效
    - Связи (вызовы): RobotPlaySoundAction, send_action
    - Аргументы:
      - `sound_id`: тип `не указан`; единицы `не указаны`; допустимые значения `ID/целое`; 系统音效ID值
      - `times`: тип `не указан`; единицы `с`; допустимые значения `не указаны`; 播放次数
    - Пример(ы) из репозитория:
      - `ep_robot.play_sound(robot.SOUND_ID_ATTACK).wait_for_completed()` (из `examples/01_robot/03_play_sound.py:26`)
      - `ep_robot.play_sound(robot.SOUND_ID_SHOOT).wait_for_completed()` (из `examples/01_robot/03_play_sound.py:27`)


## Модуль `src.robomaster.robotic_arm` (`src/robomaster/robotic_arm.py`)

### Классы

### `ArmSubject`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `arm_data`
    - Сигнатура: `arm_data(self)`
    - Приватный: нет
    - Описание: 获取机械臂信息
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.arm_data()`
  - `data_info`
    - Сигнатура: `data_info(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.data_info()`
  - `decode`
    - Сигнатура: `decode(self, buf)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): unpack
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
    - Пример(ы) из репозитория:
      - `msg = msg.decode('utf-8')` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:68`)
      - `assert m.str_from_string().encode().decode() == "baz"` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_pytypes.py:73`)

### `RoboticArmMoveAction`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self, x=0, y=0, z=0, mode=0, **kw)`
  - **Аргументы конструктора:**
    - `x`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; инициализационный параметр `x`.
    - `y`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; инициализационный параметр `y`.
    - `z`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; инициализационный параметр `z`.
    - `mode`: тип `не указан`; единицы `не указаны`; допустимые значения `enum/строка`; инициализационный параметр `mode`.
    - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; инициализационный параметр `**kw`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, x=0, y=0, z=0, mode=0, **kw)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): __init__, super
    - Аргументы:
      - `x`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `x`.
      - `y`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `y`.
      - `z`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `z`.
      - `mode`: тип `не указан`; единицы `не указаны`; допустимые значения `enum/строка`; параметр `mode`.
      - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `**kw`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `__repr__` (приватный)
    - Сигнатура: `__repr__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): format
    - Аргументы:
      - нет аргументов
    - Пример: `obj.__repr__()`
  - `encode`
    - Сигнатура: `encode(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): ProtoRoboticArmMoveCtrl, val2proto
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `return socket_obj.send(data.encode('utf-8'))` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:217`)
      - `ser.write('command'.encode('utf-8'))` (из `examples/plaintext_sample_code/RoboMasterEP/connection/uart/uart_connection.py:16`)
  - `update_from_push`
    - Сигнатура: `update_from_push(self, proto)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): _update_action_state, info, format
    - Аргументы:
      - `proto`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `proto`.
    - Пример: `obj.update_from_push(...)`

### `RoboticArm`
- **Приватный класс:** нет
- **Описание:** EP 机械臂 模块
- **Конструктор:** `__init__(self, robot)`
  - **Аргументы конструктора:**
    - `robot`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `robot`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, robot)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): __init__, super
    - Аргументы:
      - `robot`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `reset`
    - Сигнатура: `reset(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.reset()`
  - `recenter`
    - Сигнатура: `recenter(self)`
    - Приватный: нет
    - Описание: 控制机械臂回中
    - Связи (вызовы): moveto
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `ep_gimbal.recenter().wait_for_completed()` (из `examples/03_gimbal/04_recenter.py:32`)
      - `ep_gimbal.recenter(pitch_speed=100, yaw_speed=100).wait_for_completed()` (из `examples/03_gimbal/04_recenter.py:38`)
  - `move`
    - Сигнатура: `move(self, x=0, y=0)`
    - Приватный: нет
    - Описание: 机械臂相对位置移动
    - Связи (вызовы): RoboticArmMoveAction, send_action
    - Аргументы:
      - `x`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; float, x轴运动距离，向前移动为正方向，单位 mm
      - `y`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; float, y轴运动距离，向上移动为正方向，单位 mm
    - Пример(ы) из репозитория:
      - `ep_chassis.move(x=x_val, y=0, z=0, xy_speed=0.7).wait_for_completed()` (из `examples/02_chassis/01_move.py:31`)
      - `ep_chassis.move(x=-x_val, y=0, z=0, xy_speed=0.7).wait_for_completed()` (из `examples/02_chassis/01_move.py:34`)
  - `moveto`
    - Сигнатура: `moveto(self, x=0, y=0)`
    - Приватный: нет
    - Описание: 机械臂绝对位置移动
    - Связи (вызовы): RoboticArmMoveAction, send_action
    - Аргументы:
      - `x`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; float, x轴运动距离，向前移动为正方向，单位 mm
      - `y`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; float, y轴运动距离，向上移动为正方向，单位 mm
    - Пример(ы) из репозитория:
      - `ep_gimbal.moveto(pitch=0, yaw=0).wait_for_completed()` (из `examples/03_gimbal/01_move.py:32`)
      - `ep_gimbal.moveto(pitch=15, yaw=90, pitch_speed=50, yaw_speed=100).wait_for_completed()` (из `examples/03_gimbal/01_move.py:35`)
  - `sub_position`
    - Сигнатура: `sub_position(self, freq=5, callback=None, *args, **kw)`
    - Приватный: нет
    - Описание: 订阅机械臂的位置信息
    - Связи (вызовы): ArmSubject, add_subject_info
    - Аргументы:
      - `freq`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; enum:(1,5,10,20,50) 设置数据订阅数据的推送频率，单位 Hz
      - `callback`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 回调函数，返回数据 (pos_x, pos_y)：
      - `*args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 可变参数
      - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; 关键字参数
    - Пример(ы) из репозитория:
      - `ep_chassis.sub_position(freq=10, callback=sub_position_handler)` (из `examples/02_chassis/05_sub_position.py:33`)
      - `ep_chassis.sub_position(freq=1, callback=sub_info_handler)` (из `examples/02_chassis/09_sub_all.py:33`)
  - `unsub_position`
    - Сигнатура: `unsub_position(self)`
    - Приватный: нет
    - Описание: 取消机械臂位置信息订阅
    - Связи (вызовы): del_subject_info
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `ep_chassis.unsub_position()` (из `examples/02_chassis/05_sub_position.py:35`)
      - `ep_chassis.unsub_position()` (из `examples/02_chassis/09_sub_all.py:53`)


## Модуль `src.robomaster.sensor` (`src/robomaster/sensor.py`)

### Классы

### `TofSubject`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `tof`
    - Сигнатура: `tof(self)`
    - Приватный: нет
    - Описание: 距离传感器数据获取
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.tof()`
  - `data_info`
    - Сигнатура: `data_info(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.data_info()`
  - `decode`
    - Сигнатура: `decode(self, buf)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): range
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
    - Пример(ы) из репозитория:
      - `msg = msg.decode('utf-8')` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:68`)
      - `assert m.str_from_string().encode().decode() == "baz"` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_pytypes.py:73`)

### `AdapterSubject`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `adapter`
    - Сигнатура: `adapter(self)`
    - Приватный: нет
    - Описание: 距离传感器转接板数据获取
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.adapter()`
  - `data_info`
    - Сигнатура: `data_info(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.data_info()`
  - `decode`
    - Сигнатура: `decode(self, buf)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): range
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
    - Пример(ы) из репозитория:
      - `msg = msg.decode('utf-8')` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:68`)
      - `assert m.str_from_string().encode().decode() == "baz"` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_pytypes.py:73`)

### `DistanceSensor`
- **Приватный класс:** нет
- **Описание:** EP 距离传感器模块
- **Конструктор:** `__init__(self, robot)`
  - **Аргументы конструктора:**
    - `robot`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `robot`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, robot)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): __init__, super
    - Аргументы:
      - `robot`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `sub_distance`
    - Сигнатура: `sub_distance(self, freq=5, callback=None, *args, **kw)`
    - Приватный: нет
    - Описание: 订阅距离传感器测量的距离信息
    - Связи (вызовы): TofSubject, add_subject_info
    - Аргументы:
      - `freq`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 订阅数据的频率，支持的订阅频率为1、5、10、20、50hz
      - `callback`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 传入数据处理的回调函数，回调函数的参数为：
      - `*args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 传入参数。
      - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `**kw`.
    - Пример(ы) из репозитория:
      - `ep_sensor.sub_distance(freq=5, callback=sub_data_handler)` (из `examples/14_sensor/02_tof_data.py:32`)
  - `unsub_distance`
    - Сигнатура: `unsub_distance(self)`
    - Приватный: нет
    - Описание: 取消距离传感器的信息订阅。
    - Связи (вызовы): del_subject_info
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `ep_sensor.unsub_distance()` (из `examples/14_sensor/02_tof_data.py:34`)

### `SensorAdaptor`
- **Приватный класс:** нет
- **Описание:** EP 传感器板模块
- **Конструктор:** `__init__(self, robot)`
  - **Аргументы конструктора:**
    - `robot`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `robot`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, robot)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): __init__, super
    - Аргументы:
      - `robot`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `get_adc`
    - Сигнатура: `get_adc(self, id=1, port=1)`
    - Приватный: нет
    - Описание: 传感器板adc值获取
    - Связи (вызовы): ProtoSensorGetData, Msg, host2byte, send_sync_msg, get_proto, warning
    - Аргументы:
      - `id`: тип `не указан`; единицы `не указаны`; допустимые значения `ID/целое`; int[1,8]，传感器板编号
      - `port`: тип `не указан`; единицы `0-255`; допустимые значения `1..65535`; int:[1,2]，传感器板端口号
    - Пример(ы) из репозитория:
      - `adc = ep_sensor_adaptor.get_adc(id=1, port=1)` (из `examples/14_sensor/01_get_data.py:27`)
  - `get_io`
    - Сигнатура: `get_io(self, id=1, port=1)`
    - Приватный: нет
    - Описание: 传感器板io电平值获取
    - Связи (вызовы): ProtoSensorGetData, Msg, host2byte, send_sync_msg, get_proto, warning
    - Аргументы:
      - `id`: тип `не указан`; единицы `не указаны`; допустимые значения `ID/целое`; int[1,8], 传感器板编号
      - `port`: тип `не указан`; единицы `0-255`; допустимые значения `1..65535`; int:[1,2], 传感器板端口号
    - Пример(ы) из репозитория:
      - `io = ep_sensor_adaptor.get_io(id=1, port=1)` (из `examples/14_sensor/01_get_data.py:31`)
  - `get_pulse_period`
    - Сигнатура: `get_pulse_period(self, id=1, port=1)`
    - Приватный: нет
    - Описание: 传感器板电平持续时间获取
    - Связи (вызовы): ProtoSensorGetData, Msg, host2byte, send_sync_msg, get_proto, warning
    - Аргументы:
      - `id`: тип `не указан`; единицы `не указаны`; допустимые значения `ID/целое`; int[1,8], 传感器板编号
      - `port`: тип `не указан`; единицы `0-255`; допустимые значения `1..65535`; int:[1,2], 传感器板端口号
    - Пример(ы) из репозитория:
      - `duration = ep_sensor_adaptor.get_pulse_period(id=1, port=1)` (из `examples/14_sensor/01_get_data.py:35`)
  - `sub_adapter`
    - Сигнатура: `sub_adapter(self, freq=5, callback=None, *args, **kw)`
    - Приватный: нет
    - Описание: 订阅传感器转接板信息
    - Связи (вызовы): AdapterSubject, add_subject_info
    - Аргументы:
      - `freq`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 订阅数据的频率，支持的订阅频率为1、5、10、20、50hz
      - `callback`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 传入数据处理的回调函数，回调函数的参数为：
      - `*args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 传入参数。
      - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `**kw`.
    - Пример(ы) из репозитория:
      - `ep_sensor.sub_adapter(freq=5, callback=sub_data_handler)` (из `examples/14_sensor/03_io_data.py:32`)
  - `unsub_adapter`
    - Сигнатура: `unsub_adapter(self)`
    - Приватный: нет
    - Описание: 取消传感器转接板的信息订阅。
    - Связи (вызовы): del_subject_info
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `ep_sensor.unsub_adapter()` (из `examples/14_sensor/03_io_data.py:34`)

### `TelloDistanceSensor`
- **Приватный класс:** нет
- **Описание:** 教育无人机 距离传感器模块
- **Конструктор:** `__init__(self, robot)`
  - **Аргументы конструктора:**
    - `robot`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `robot`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, robot)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `robot`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `get_ext_tof`
    - Сигнатура: `get_ext_tof(self)`
    - Приватный: нет
    - Описание: 获取扩展模块tof传感器的数值
    - Связи (вызовы): format, TextProtoDrone, TextMsg, send_sync_msg, warning, get_proto
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `tof_info = tl_drone.sensor.get_ext_tof()` (из `examples/12_drone/22_tof.py:27`)


## Модуль `src.robomaster.servo` (`src/robomaster/servo.py`)

### Классы

### `ServoSubject`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `servo_data`
    - Сигнатура: `servo_data(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.servo_data()`
  - `data_info`
    - Сигнатура: `data_info(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.data_info()`
  - `decode`
    - Сигнатура: `decode(self, buf)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): unpack
    - Аргументы:
      - `buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `buf`.
    - Пример(ы) из репозитория:
      - `msg = msg.decode('utf-8')` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:68`)
      - `assert m.str_from_string().encode().decode() == "baz"` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_pytypes.py:73`)

### `ServoSetAngleAction`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self, index=0, angle=0, **kw)`
  - **Аргументы конструктора:**
    - `index`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; инициализационный параметр `index`.
    - `angle`: тип `не указан`; единицы `°`; допустимые значения `0..255`; инициализационный параметр `angle`.
    - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; инициализационный параметр `**kw`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, index=0, angle=0, **kw)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): __init__, super
    - Аргументы:
      - `index`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `index`.
      - `angle`: тип `не указан`; единицы `°`; допустимые значения `0..255`; параметр `angle`.
      - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `**kw`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `__repr__` (приватный)
    - Сигнатура: `__repr__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): format
    - Аргументы:
      - нет аргументов
    - Пример: `obj.__repr__()`
  - `encode`
    - Сигнатура: `encode(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): ProtoServoCtrlSet
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `return socket_obj.send(data.encode('utf-8'))` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:217`)
      - `ser.write('command'.encode('utf-8'))` (из `examples/plaintext_sample_code/RoboMasterEP/connection/uart/uart_connection.py:16`)
  - `update_from_push`
    - Сигнатура: `update_from_push(self, proto)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): _update_action_state, info, format
    - Аргументы:
      - `proto`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `proto`.
    - Пример: `obj.update_from_push(...)`

### `Servo`
- **Приватный класс:** нет
- **Описание:** EP 舵机模块
- **Конструктор:** `__init__(self, robot)`
  - **Аргументы конструктора:**
    - `robot`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `robot`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, robot)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): __init__, super
    - Аргументы:
      - `robot`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `moveto`
    - Сигнатура: `moveto(self, index=0, angle=0)`
    - Приватный: нет
    - Описание: 舵机绝对位置移动
    - Связи (вызовы): ServoSetAngleAction, send_action
    - Аргументы:
      - `index`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; int [1, 3]，舵机编号
      - `angle`: тип `не указан`; единицы `°`; допустимые значения `0..255`; int: [-180, 180]，舵机旋转角度，单位（°）
    - Пример(ы) из репозитория:
      - `ep_gimbal.moveto(pitch=0, yaw=0).wait_for_completed()` (из `examples/03_gimbal/01_move.py:32`)
      - `ep_gimbal.moveto(pitch=15, yaw=90, pitch_speed=50, yaw_speed=100).wait_for_completed()` (из `examples/03_gimbal/01_move.py:35`)
  - `drive_speed`
    - Сигнатура: `drive_speed(self, index=0, speed=0)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): ProtoServoModeSet, Msg, send_sync_msg, get_proto, warning, ProtoServoControl
    - Аргументы:
      - `index`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `index`.
      - `speed`: тип `не указан`; единицы `м/с`; допустимые значения `не указаны`; параметр `speed`.
    - Пример(ы) из репозитория:
      - `ep_chassis.drive_speed(x=x_val, y=0, z=0, timeout=5)` (из `examples/02_chassis/03_speed.py:32`)
      - `ep_chassis.drive_speed(x=-x_val, y=0, z=0, timeout=5)` (из `examples/02_chassis/03_speed.py:36`)
  - `pause`
    - Сигнатура: `pause(self, index=0)`
    - Приватный: нет
    - Описание: 停止
    - Связи (вызовы): ProtoServoControl, Msg, send_sync_msg, get_proto, warning, format
    - Аргументы:
      - `index`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; int: [1, 3]，舵机编号
    - Пример(ы) из репозитория:
      - `ep_gripper.pause()` (из `examples/11_gripper/01_open_close.py:31`)
      - `ep_gripper.pause()` (из `examples/11_gripper/01_open_close.py:36`)
  - `get_angle`
    - Сигнатура: `get_angle(self, index=1)`
    - Приватный: нет
    - Описание: 获取舵机角度值
    - Связи (вызовы): ProtoServoGetAngle, Msg, print, send_sync_msg, get_proto, warning
    - Аргументы:
      - `index`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; int: [1，3]，舵机编号
    - Пример: `obj.get_angle()`
  - `sub_servo_info`
    - Сигнатура: `sub_servo_info(self, freq=5, callback=None, *args, **kw)`
    - Приватный: нет
    - Описание: 订阅舵机角度信息
    - Связи (вызовы): ServoSubject, add_subject_info
    - Аргументы:
      - `freq`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; enum: (1, 5, 10, 20, 50) 设置数据订阅数据的推送频率，单位 Hz
      - `callback`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 回调函数，返回数据 (valid[4], speed[4], angle[4]):
      - `*args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 可变参数
      - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; 关键字参数
    - Пример: `obj.sub_servo_info()`
  - `unsub_servo_info`
    - Сигнатура: `unsub_servo_info(self)`
    - Приватный: нет
    - Описание: 取消订阅舵机的角度信息
    - Связи (вызовы): del_subject_info
    - Аргументы:
      - нет аргументов
    - Пример: `obj.unsub_servo_info()`


## Модуль `src.robomaster.uart` (`src/robomaster/uart.py`)

### Классы

### `Uart`
- **Приватный класс:** нет
- **Описание:** EP 串口模块
- **Конструктор:** `__init__(self, robot)`
  - **Аргументы конструктора:**
    - `robot`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `robot`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, robot)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): __init__, defaultdict, Queue, super
    - Аргументы:
      - `robot`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `__del__` (приватный)
    - Сигнатура: `__del__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): stop
    - Аргументы:
      - нет аргументов
    - Пример: `obj.__del__()`
  - `start`
    - Сигнатура: `start(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): add_handler, Thread, start
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `self.cmd_socket_recv_thread.start()` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:90`)
      - `t.start()` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_callbacks.py:135`)
  - `stop`
    - Сигнатура: `stop(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): put, join
    - Аргументы:
      - нет аргументов
    - Пример: `obj.stop()`
  - `_msg_recv` (приватный)
    - Сигнатура: `_msg_recv(cls, self, msg)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): put
    - Аргументы:
      - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
    - Пример: `obj._msg_recv(...)`
  - `_dispatch_task` (приватный)
    - Сигнатура: `_dispatch_task(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): info, get, get_proto, warning, format, serial_process_decode
    - Аргументы:
      - нет аргументов
    - Пример: `obj._dispatch_task()`
  - `serial_process_decode`
    - Сигнатура: `serial_process_decode(self, msg)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `msg`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg`.
    - Пример: `obj.serial_process_decode(...)`
  - `sub_serial_msg`
    - Сигнатура: `sub_serial_msg(self, callback=None, *args)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `callback`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `callback`.
      - `*args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `*args`.
    - Пример: `obj.sub_serial_msg()`
  - `unsub_serial_msg`
    - Сигнатура: `unsub_serial_msg(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.unsub_serial_msg()`
  - `serial_process_exec`
    - Сигнатура: `serial_process_exec(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): _callback
    - Аргументы:
      - нет аргументов
    - Пример: `obj.serial_process_exec()`
  - `serial_read_data`
    - Сигнатура: `serial_read_data(self, msg_len)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `msg_len`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `msg_len`.
    - Пример: `obj.serial_read_data(...)`
  - `serial_param_set`
    - Сигнатура: `serial_param_set(self, baud_rate=0, data_bit=1, odd_even=0, stop_bit=0, rx_en=1, tx_en=1, rx_size=50, tx_size=50)`
    - Приватный: нет
    - Описание: 底盘串口参数设置
    - Связи (вызовы): ProtoChassisSerialSet, _send_sync_proto, host2byte
    - Аргументы:
      - `baud_rate`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 串口波特率，设置范围：0~4映射‘9600’，‘19200’，‘38400’，‘57600’，‘115200’
      - `data_bit`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 数据位设置，设置范围：0~3映射‘bit7’, 'bit8', 'bit9', 'bit10'
      - `odd_even`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; 数据校验位，设置范围：0~3映射‘none’, 'odd', 'even'
      - `stop_bit`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 停止位，设置范围：1~2
      - `rx_en`: тип `не указан`; единицы `м`; допустимые значения `0..255`; 接收使能
      - `tx_en`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; 发送使能
      - `rx_size`: тип `не указан`; единицы `м`; допустимые значения `0..255`; 接收buff大小
      - `tx_size`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; 发送buff大小
    - Пример(ы) из репозитория:
      - `uart.serial_param_set(baud_rate=0, data_bit=1, odd_even=0, \` (из `examples/02_chassis/10_serial.py:29`)
  - `serial_send_msg`
    - Сигнатура: `serial_send_msg(self, msg_buf)`
    - Приватный: нет
    - Описание: 底盘串口数据数据发送
    - Связи (вызовы): ProtoChassisSerialMsgSend, len, _send_sync_proto, type, encode, host2byte
    - Аргументы:
      - `msg_buf`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 发送的数据
    - Пример(ы) из репозитория:
      - `uart.serial_send_msg(send_dict)` (из `examples/02_chassis/10_serial.py:35`)
      - `uart.serial_send_msg(send_tuple)` (из `examples/02_chassis/10_serial.py:40`)


## Модуль `src.robomaster.util` (`src/robomaster/util.py`)

### Классы

### `UnitChecker`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self, name, default=0, start=0, end=0, step=1, decimal=2, scale=1, unit=UNIT_METRIC)`
  - **Аргументы конструктора:**
    - `name`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; инициализационный параметр `name`.
    - `default`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; инициализационный параметр `default`.
    - `start`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `start`.
    - `end`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; инициализационный параметр `end`.
    - `step`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; инициализационный параметр `step`.
    - `decimal`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; инициализационный параметр `decimal`.
    - `scale`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; инициализационный параметр `scale`.
    - `unit`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; инициализационный параметр `unit`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, name, default=0, start=0, end=0, step=1, decimal=2, scale=1, unit=UNIT_METRIC)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - `name`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `name`.
      - `default`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `default`.
      - `start`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `start`.
      - `end`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `end`.
      - `step`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `step`.
      - `decimal`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `decimal`.
      - `scale`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `scale`.
      - `unit`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `unit`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `name`
    - Сигнатура: `name(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `assert roger.name() + " is a " + roger.species() == "Rabbit is a parrot"` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_class.py:74`)
      - `assert polly.name() + " is a " + polly.species() == "Polly is a parrot"` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_class.py:78`)
  - `default`
    - Сигнатура: `default(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.default()`
  - `scale`
    - Сигнатура: `scale(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.scale()`
  - `step`
    - Сигнатура: `step(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.step()`
  - `decimal`
    - Сигнатура: `decimal(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.decimal()`
  - `start`
    - Сигнатура: `start(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `self.cmd_socket_recv_thread.start()` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:90`)
      - `t.start()` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_callbacks.py:135`)
  - `end`
    - Сигнатура: `end(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.end()`
  - `unit`
    - Сигнатура: `unit(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.unit()`
  - `check`
    - Сигнатура: `check(self, value)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): warning, format
    - Аргументы:
      - `value`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `value`.
    - Пример: `obj.check(...)`
  - `proto2val`
    - Сигнатура: `proto2val(self, val)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): round, check
    - Аргументы:
      - `val`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `val`.
    - Пример: `obj.proto2val(...)`
  - `val2proto`
    - Сигнатура: `val2proto(self, val)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): check, round
    - Аргументы:
      - `val`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `val`.
    - Пример: `obj.val2proto(...)`


## Модуль `src.robomaster.version` (`src/robomaster/version.py`)


## Модуль `src.robomaster.vision` (`src/robomaster/vision.py`)

### Классы

### `VisionPushEvent`
- **Приватный класс:** нет
- **Описание:** описание отсутствует
- **Конструктор:** `__init__(self)`
  - **Аргументы конструктора:**
    - нет аргументов
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `data_info`
    - Сигнатура: `data_info(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): не выявлены
    - Аргументы:
      - нет аргументов
    - Пример: `obj.data_info()`
  - `decode`
    - Сигнатура: `decode(self, data)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): info, len, format, range, _type2info, _id2gesture
    - Аргументы:
      - `data`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `data`.
    - Пример(ы) из репозитория:
      - `msg = msg.decode('utf-8')` (из `examples/plaintext_sample_code/RoboMasterEP/connection/network/robot_connection.py:68`)
      - `assert m.str_from_string().encode().decode() == "baz"` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_pytypes.py:73`)

### `Vision`
- **Приватный класс:** нет
- **Описание:** EP 视觉识别模块
- **Конструктор:** `__init__(self, robot)`
  - **Аргументы конструктора:**
    - `robot`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; инициализационный параметр `robot`.
- **Методы:**
  - `__init__` (приватный)
    - Сигнатура: `__init__(self, robot)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): __init__, super
    - Аргументы:
      - `robot`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `robot`.
    - Пример(ы) из репозитория:
      - `m.Parent.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:112`)
      - `m.Child.__init__(self)` (из `examples/plaintext_sample_code/RoboMasterEP/stream/decoder/src/pybind11/tests/test_call_policies.py:113`)
  - `reset`
    - Сигнатура: `reset(self)`
    - Приватный: нет
    - Описание: описание отсутствует
    - Связи (вызовы): _disable_detection
    - Аргументы:
      - нет аргументов
    - Пример: `obj.reset()`
  - `_id2marker` (приватный)
    - Сигнатура: `_id2marker(marker_id)`
    - Приватный: да
    - Описание: ID转换为Marker字符
    - Связи (вызовы): str, chr, warning, format
    - Аргументы:
      - `marker_id`: тип `не указан`; единицы `0-255`; допустимые значения `ID/целое`; параметр `marker_id`.
    - Пример: `obj._id2marker(...)`
  - `_type2info` (приватный)
    - Сигнатура: `_type2info(det_type)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): warning, format
    - Аргументы:
      - `det_type`: тип `не указан`; единицы `м`; допустимые значения `не указаны`; параметр `det_type`.
    - Пример: `obj._type2info(...)`
  - `_id2gesture` (приватный)
    - Сигнатура: `_id2gesture(gus_id)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): warning, format
    - Аргументы:
      - `gus_id`: тип `не указан`; единицы `0-255`; допустимые значения `ID/целое`; параметр `gus_id`.
    - Пример: `obj._id2gesture(...)`
  - `sub_detect_info`
    - Сигнатура: `sub_detect_info(self, name, color=None, callback=None, *args, **kw)`
    - Приватный: нет
    - Описание: 订阅智能识别消息
    - Связи (вызовы): _get_sdk_function, _enable_detection, error, VisionPushEvent, ProtoVisionDetectInfo, add_subject_event_info
    - Аргументы:
      - `name`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; enum: ("person", "gesture", "line", "marker", "robot")，person 行人，gesture 手势，line 线识别，        marker 标签识别，robot 机器人识别
      - `color`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; enum:("red", "green", "blue"): 指定识别颜色，仅线识别和标签识别时生效
      - `callback`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; 回调函数，返回数据 (list(rect_info)):
      - `*args`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `*args`.
      - `**kw`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `**kw`.
    - Пример(ы) из репозитория:
      - `result = ep_vision.sub_detect_info(name="marker", callback=on_detect_marker)` (из `examples/05_vision/01_marker.py:69`)
      - `result = ep_vision.sub_detect_info(name="line", color="blue", callback=on_detect_line)` (из `examples/05_vision/02_line.py:61`)
  - `unsub_detect_info`
    - Сигнатура: `unsub_detect_info(self, name)`
    - Приватный: нет
    - Описание: 取消智能订阅消息
    - Связи (вызовы): _get_sdk_function, _disable_detection, warning, format
    - Аргументы:
      - `name`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; enum: ("person", "gesture", "line", "marker", "robot")，取消的智能识别功能
    - Пример(ы) из репозитория:
      - `result = ep_vision.unsub_detect_info(name="marker")` (из `examples/05_vision/01_marker.py:80`)
      - `result = ep_vision.unsub_detect_info(name="line")` (из `examples/05_vision/02_line.py:70`)
  - `_enable_detection` (приватный)
    - Сигнатура: `_enable_detection(self, name)`
    - Приватный: да
    - Описание: 开启视觉检测功能
    - Связи (вызовы): ProtoVisionDetectEnable, Msg, send_sync_msg, warning, format
    - Аргументы:
      - `name`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; 检测功能的类型
    - Пример: `obj._enable_detection(...)`
  - `_disable_detection` (приватный)
    - Сигнатура: `_disable_detection(self, func_mask)`
    - Приватный: да
    - Описание: 关闭视觉对应类型的检测功能
    - Связи (вызовы): ProtoVisionDetectEnable, Msg, send_sync_msg, warning, format, str
    - Аргументы:
      - `func_mask`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; 视觉检测功能类型
    - Пример: `obj._disable_detection(...)`
  - `_get_sdk_function` (приватный)
    - Сигнатура: `_get_sdk_function(self)`
    - Приватный: да
    - Описание: 获取视觉检测的功能类型
    - Связи (вызовы): ProtoVisionDetectStatus, Msg, send_sync_msg, get_proto, warning, format
    - Аргументы:
      - нет аргументов
    - Пример: `obj._get_sdk_function()`
  - `_set_color` (приватный)
    - Сигнатура: `_set_color(self, name, color)`
    - Приватный: да
    - Описание: описание отсутствует
    - Связи (вызовы): ProtoVisionSetColor, _send_sync_proto, warning, format
    - Аргументы:
      - `name`: тип `не указан`; единицы `не указаны`; допустимые значения `не указаны`; параметр `name`.
      - `color`: тип `не указан`; единицы `0-255`; допустимые значения `0..255`; параметр `color`.
    - Пример: `obj._set_color(..., ...)`
