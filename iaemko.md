代发 wailian999

[A02] 变量声明与赋值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zlqpbtro.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.feifeiyinyue.top/Article/details/gt2jbsjlwri.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.hysaishi.cn/Article/details/gt2gmhbacxe.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.cdnleiting.top/Article/details/gt2hltfpzdz.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.quarkkingdee.top/Article/details/gt2vxsytidi.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.dashuyun.cn/Article/details/gt2qhczvlrm.html

Go:   name := "Alex"; age := 20
来源：http://dali.redwolf501.top/Article/details/gt2eeksogjy.html

Ruby: name = "Alex"; age = 20
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2miapydum.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yj20258.top/Article/details/gt2tnonqwor.html

[A03] 常量定义
来源：http://dali.shangyingyoupin.top/Article/details/gt2evltnwuo.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.snrcjt.cn/Article/details/gt2nrpmcvhh.html

PHP:  const PI = 3.14159;
来源：http://dali.cqqwz.cn/Article/details/gt2rruvzqim.html

JS:   const PI = 3.14159;
来源：http://dali.tanke756.top/Article/details/gt2ymmfjwjf.html

TS:   const PI: number = 3.14159;
来源：http://dali.yanxiufei.cn/Article/details/gt2ytqoucbe.html

Java: static final double PI = 3.14159;
来源：http://dali.yj20258.top/Article/details/gt2gpztieku.html

Go:   const PI = 3.14159
来源：http://dali.iojbl.cn/Article/details/gt2zwnfzskd.html

Ruby: PI = 3.14159
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ubznxdih.html

C#:   const double PI = 3.14159;
来源：http://dali.vqdsnc.cn/Article/details/gt2pottzcwh.html

[A04] 判断变量类型
来源：http://dali.pengpengdd.cyou/Article/details/gt2gjvaevfw.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.nanxinkj.top/Article/details/gt2acfqguib.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.dashuyun.cn/Article/details/gt2kstczhim.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.tianlin.xyz/Article/details/gt2phbovmqs.html

TS:   typeof x; x instanceof Date
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ikojgnfn.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.meibo888.top/Article/details/gt2eehnflio.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.hfpthk.cn/Article/details/gt2whcojasw.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.meibo888.top/Article/details/gt2srlpwsky.html

C#:   x.GetType().Name; x is int
来源：http://dali.hammf.cn/Article/details/gt2khfskhuj.html

[A05] 整数除法与取模
来源：http://dali.pycfn.com/Article/details/gt2jcxmdrtr.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.gogol.net.cn/Article/details/gt2ylafxrcc.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yongpay.top/Article/details/gt2jyqhnggb.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.sufxvd.cn/Article/details/gt2phtqfapy.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xylfe.cn/Article/details/gt2xhvpshcg.html

Java: 7 / 2; 7 % 2
来源：http://dali.hnxiangtu.top/Article/details/gt2aykjnbqa.html

Go:   7 / 2; 7 % 2
来源：http://dali.hnqzz.top/Article/details/gt2rmstogcg.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.jqgufenzy.top/Article/details/gt2apiskkwl.html

C#:   7 / 2; 7 % 2
来源：http://dali.gaohongyu789.top/Article/details/gt2tlafliml.html

[A06] 字符串转数字
来源：http://dali.jianghu66.top/Article/details/gt2pucvcyaa.html

Py:   int("42"); float("3.14")
来源：http://dali.yanxiufei.cn/Article/details/gt2klrcrhva.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.9152youxi.cn/Article/details/gt2miqkovbz.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.gogol.net.cn/Article/details/gt2dqmwxswr.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.tianlin.xyz/Article/details/gt2fiegdyrm.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.nanxuanxn.top/Article/details/gt2qpajshzg.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.hysaishi.cn/Article/details/gt2fbtbqzgy.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yanxiufei.cn/Article/details/gt2gzkthedd.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.meibo888.top/Article/details/gt2zoaupeqs.html

[A07] 数字转字符串
来源：http://dali.snrcjt.cn/Article/details/gt2uvhukdas.html

Py:   str(42)
来源：http://dali.jiagoushi.top/Article/details/gt2srxdkxgs.html

PHP:  (string) 42; strval(42)
来源：http://dali.kuanghao11.cn/Article/details/gt2pehzgckt.html

JS:   String(42); (42).toString()
来源：http://dali.sysykeji.top/Article/details/gt2twezzklm.html

TS:   String(42)
来源：http://dali.bjfxy.top/Article/details/gt2rfpcrdiz.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.yj20258.top/Article/details/gt2rvokwumr.html

Go:   strconv.Itoa(42)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vlhwzzmz.html

Ruby: 42.to_s
来源：http://dali.ybcxt.top/Article/details/gt2fdbijzmn.html

C#:   42.ToString()
来源：http://dali.andypj.xyz/Article/details/gt2apozsqis.html

[A08] 取整与四舍五入
来源：http://dali.hnqzz.top/Article/details/gt2pbpkaekq.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.jiagoushi.top/Article/details/gt2jywxtskk.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.daria6918.cn/Article/details/gt2dgvlxhpx.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.xinyue.icu/Article/details/gt2gqgbtmcb.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.jlsjyb.cn/Article/details/gt2dxinvzub.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.gotoacloud.top/Article/details/gt2hylqvsbc.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.yangfankeji.com/Article/details/gt2vqycoylu.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.xinyue.icu/Article/details/gt2thyknsfc.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.aibaodan.cn/Article/details/gt2mzsiehai.html

[A09] 绝对值与最大最小值
来源：http://dali.aibaodan.cn/Article/details/gt2duxoojks.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.iojbl.cn/Article/details/gt2gforrthf.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mrncsqzl.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.tanke756.top/Article/details/gt2vkoupddg.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.jyoumei.cn/Article/details/gt2uodacrtc.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.yvedp.cn/Article/details/gt2vbbxirfq.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.jqgfzy.top/Article/details/gt2ziyrukou.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.gaohongyu789.top/Article/details/gt2drwezgco.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.svipenyu.cn/Article/details/gt2ehllqgdr.html

[A10] 生成随机数
来源：http://dali.zhoulong.xyz/Article/details/gt2hxepgtnq.html

Py:   import random; random.randint(1, 100)
来源：http://dali.daxiang520.top/Article/details/gt2xitclhcg.html

PHP:  random_int(1, 100);
来源：http://dali.xinyue.icu/Article/details/gt2apylmqqb.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.mhx1999.top/Article/details/gt2djwvqyvg.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.tanke756.top/Article/details/gt2ztbhiakb.html

Java: new Random().nextInt(100) + 1
来源：http://dali.vqdsnc.cn/Article/details/gt2xodvtzhv.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.fzhhl.top/Article/details/gt2sbvdsdnp.html

Ruby: rand(1..100)
来源：http://dali.c1oappe.top/Article/details/gt2sjnmbpdt.html

C#:   new Random().Next(1, 101)
来源：http://dali.hammf.cn/Article/details/gt2rayjpkqa.html

[A11] 条件表达式（三元）
来源：http://dali.c1oappe.top/Article/details/gt2ajeguyca.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.jiagoushi.top/Article/details/gt2tjyurkut.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.hysaishi.cn/Article/details/gt2oxufvfjd.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.cqqwz.cn/Article/details/gt2kkvsmzya.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.hongshengwenyu.top/Article/details/gt2fytpaoew.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.haohaochexian.top/Article/details/gt2pnjksxjr.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zycfv.cn/Article/details/gt2acucdycn.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.shzxlz.cn/Article/details/gt2duavztya.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.nanxuanxn.top/Article/details/gt2flmqkfia.html

[A12] 字符串插值 / 格式化
来源：http://dali.smart0.xyz/Article/details/gt2hlqmknhw.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.nanxuanxn.top/Article/details/gt2osbfhheu.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.yj202588.top/Article/details/gt2ofknjfao.html

JS:   `Hello, ${name}!`
来源：http://dali.andypj.xyz/Article/details/gt2asbzcroc.html

TS:   `Hello, ${name}!`
来源：http://dali.yvedp.cn/Article/details/gt2hnrtheml.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.meibo888.top/Article/details/gt2fdkpauuk.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pmvnjzgm.html

Ruby: "Hello, #{name}!"
来源：http://dali.cucudq.cn/Article/details/gt2esfsrwal.html

C#:   $"Hello, {name}!"
来源：http://dali.birdmap.top/Article/details/gt2uklmakvv.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.316326.xyz/Article/details/gt2omhwwkau.html

Py:   "第一行\n第二行"
来源：http://dali.jinqigufen.top/Article/details/gt2ytktlqax.html

PHP:  "第一行\n第二行"
来源：http://dali.kuanghao11.cn/Article/details/gt2yxahwzon.html

JS:   "第一行\n第二行"
来源：http://dali.snrcjt.cn/Article/details/gt2cwvzyyyw.html

TS:   "第一行\n第二行"
来源：http://dali.smart0.xyz/Article/details/gt2uxozlelp.html

Java: "第一行\n第二行"
来源：http://dali.daria6918.cn/Article/details/gt2wtrsvqti.html

Go:   "第一行\n第二行"
来源：http://dali.yonumen.top/Article/details/gt2povbnfrb.html

Ruby: "第一行\n第二行"
来源：http://dali.shangyingyoupin.top/Article/details/gt2zcyruxio.html

C#:   "第一行\n第二行"
来源：http://dali.yanxiufei.cn/Article/details/gt2cgkjldrl.html

[A14] 注释写法
来源：http://dali.yvedp.cn/Article/details/gt2wogngxon.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.pengpengdd.cyou/Article/details/gt2yhpolmfi.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.yanxiufei.cn/Article/details/gt2cbetdvtq.html

JS:   // 单行；/* 多行 */
来源：http://dali.xuetiantiany.cn/Article/details/gt2cyhguylw.html

TS:   // 单行；/* 多行 */
来源：http://dali.hnxiangtu.top/Article/details/gt2kdhwsvhe.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.andypj.xyz/Article/details/gt2cvlpoimr.html

Go:   // 单行；/* 多行 */
来源：http://dali.haohaochexian.top/Article/details/gt2pwuyuzwv.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.iojbl.cn/Article/details/gt2ggmjonou.html

C#:   // 单行；/* 多行 */
来源：http://dali.jinqigfzy.top/Article/details/gt2kmwwyldv.html

[A15] 空值判断与默认值
来源：http://dali.jiagoushi.top/Article/details/gt2zfwebxse.html

Py:   value = data or "默认值"
来源：http://dali.hywenlv.cn/Article/details/gt2eixhbirr.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhiwuduotai.top/Article/details/gt2hoffitch.html

JS:   const value = data ?? "默认值";
来源：http://dali.cqqwz.cn/Article/details/gt2gmrqktrb.html

TS:   const value = data ?? "默认值";
来源：http://dali.gaohongyu789.top/Article/details/gt2afsgymfy.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.svipenyu.cn/Article/details/gt2qzlconyx.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.mhx1999.top/Article/details/gt2cpfxlwyq.html

Ruby: value = data || "默认值"
来源：http://dali.redwolf501.top/Article/details/gt2ghgcltev.html

C#:   var value = data ?? "默认值";
来源：http://dali.aibaodan.cn/Article/details/gt2trdattcq.html

[A16] 真假值判断规则
来源：http://dali.meibo888.top/Article/details/gt2gkansjoq.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.sufxvd.cn/Article/details/gt2lxpnkrdq.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.xuanzx.com/Article/details/gt2qswpclcq.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.hongshengwenyu.top/Article/details/gt2xnhpvjvn.html

TS:   if (!x) {}
来源：http://dali.xuanzx.com/Article/details/gt2okggmgvb.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hmwcnwtm.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.cheryme.top/Article/details/gt2aynqrhul.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhiwuduotai.top/Article/details/gt2dwcxiwzj.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.ybcxt.top/Article/details/gt2mwempnmg.html

[A17] 位运算
来源：http://dali.yvedp.cn/Article/details/gt2gavfsqmk.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.svipenyu.cn/Article/details/gt2ydhfefoj.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.quarkkingdee.top/Article/details/gt2eoamyuyr.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.dashuyun.cn/Article/details/gt2nyoszubq.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.gaohongyu789.top/Article/details/gt2gujenmds.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tanke756.top/Article/details/gt2cgqyvfgn.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.nanxinkj.top/Article/details/gt2pqltwnbb.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hywenlv.cn/Article/details/gt2akteehji.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shzxlz.cn/Article/details/gt2dxffusse.html

[A18] 字符与 ASCII 码互转
来源：http://dali.guannengcc.top/Article/details/gt2bhkxfmma.html

Py:   ord("A"); chr(65)
来源：http://dali.gzhubu.top/Article/details/gt2jotdmxrv.html

PHP:  ord("A"); chr(65)
来源：http://dali.chenzaomai.com/Article/details/gt2qmujveia.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.9152youxi.cn/Article/details/gt2faftbnka.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jiagoushi.top/Article/details/gt2btawtgdl.html

Java: (int) 'A'; (char) 65
来源：http://dali.jqgfzy.top/Article/details/gt2ebxnhjto.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.yvedp.cn/Article/details/gt2ggpacwwp.html

Ruby: "A".ord; 65.chr
来源：http://dali.zhiwuduotai.top/Article/details/gt2kzzypboj.html

C#:   (int)'A'; (char)65
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rsubdeky.html

[A19] 交换两个变量
来源：http://dali.cdnleiting.top/Article/details/gt2infcyfqh.html

Py:   a, b = b, a
来源：http://dali.vqdsnc.cn/Article/details/gt2jtedkhqx.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ufififob.html

JS:   [a, b] = [b, a];
来源：http://dali.sufxvd.cn/Article/details/gt2mcfcntyv.html

TS:   [a, b] = [b, a];
来源：http://dali.yuxming.cn/Article/details/gt2gnvusyrr.html

Java: int t = a; a = b; b = t;
来源：http://dali.yvedp.cn/Article/details/gt2dxgajslb.html

Go:   a, b = b, a
来源：http://dali.snrcjt.cn/Article/details/gt2yzyygmnl.html

Ruby: a, b = b, a
来源：http://dali.dashuyun.cn/Article/details/gt2dngyfpbs.html

C#:   (a, b) = (b, a);
来源：http://dali.nwbrower.top/Article/details/gt2bgytrrso.html

[A20] 读取标准输入
来源：http://dali.cucudq.cn/Article/details/gt2orjpvvyz.html

Py:   name = input("请输入：")
来源：http://dali.tanke756.top/Article/details/gt2bwjrsyee.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pklzruez.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.meibo888.top/Article/details/gt2jtcrsphj.html

TS:   // Node.js：readline 模块
来源：http://dali.sysykeji.top/Article/details/gt2jgwltmix.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.feifeiyinyue.top/Article/details/gt2csxyfice.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.chenlongwang.top/Article/details/gt2jhgtdfdl.html

Ruby: gets.chomp
来源：http://dali.sxryk.cn/Article/details/gt2afyerouz.html

C#:   Console.ReadLine();
来源：http://dali.yuanzhike.top/Article/details/gt2nqdhppyb.html

[A21] 保留指定小数位输出
来源：http://dali.jiagoushi.top/Article/details/gt2rogeqbsi.html

Py:   f"{3.14159:.2f}"
来源：http://dali.gaohongyu789.top/Article/details/gt2rnpmxrzo.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.dianchejie.cn/Article/details/gt2ejcbddne.html

JS:   (3.14159).toFixed(2)
来源：http://dali.iojbl.cn/Article/details/gt2tgnggqha.html

TS:   (3.14159).toFixed(2)
来源：http://dali.yanxiufei.cn/Article/details/gt2zxnonnhk.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.yonumen.top/Article/details/gt2tzlqbcnn.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.aizwys.cn/Article/details/gt2ayoebicw.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.yonumen.top/Article/details/gt2karvlxqp.html

C#:   3.14159.ToString("F2")
来源：http://dali.jyoumei.cn/Article/details/gt2agouewbl.html

[A22] 获取字符串长度
来源：http://dali.birdmap.top/Article/details/gt2lvvxsqon.html

Py:   len(s)
来源：http://dali.bjfxy.top/Article/details/gt2xjpgqgqc.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.zhixingplan.top/Article/details/gt2shhcuvvv.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.haohaochexian.top/Article/details/gt2symigxls.html

TS:   s.length
来源：http://dali.chenlongwang.top/Article/details/gt2bhnrdsmk.html

Java: s.length()
来源：http://dali.cashguo.top/Article/details/gt2hdsitppl.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.yvedp.cn/Article/details/gt2kmqxvkbh.html

Ruby: s.length
来源：http://dali.jianghu66.top/Article/details/gt2rzzzvsaq.html

C#:   s.Length
来源：http://dali.yj20258.top/Article/details/gt2xrtzfgkt.html

[A23] 大小写转换
来源：http://dali.redwolf501.top/Article/details/gt2kstgskgj.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.cucudq.cn/Article/details/gt2gvtztnah.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.jqgufenzy.top/Article/details/gt2yspboxbd.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.andypj.xyz/Article/details/gt2nuckcnkh.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.andypj.xyz/Article/details/gt2jubfvfks.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.fengsongda.top/Article/details/gt2tmnetgzj.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.pycfn.com/Article/details/gt2stopmujl.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.ppjwa.cn/Article/details/gt2cvlkbalv.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.birdmap.top/Article/details/gt2peapewvl.html

[A24] 去除首尾空白
来源：http://dali.chenzaomai.com/Article/details/gt2tdpkashj.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.jyoumei.cn/Article/details/gt2lhphfxje.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.cucudq.cn/Article/details/gt2lajljskt.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hfpthk.cn/Article/details/gt2dvqcmiic.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.daxiang520.top/Article/details/gt2enepddnt.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.daria6918.cn/Article/details/gt2fmrnprgv.html

Go:   strings.TrimSpace(s)
来源：http://dali.gzhubu.top/Article/details/gt2uhzdfcoi.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hirmdzcp.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.dianchejie.cn/Article/details/gt2okosavtt.html

[A25] 字符串比较
来源：http://dali.zhixingplan.top/Article/details/gt2bcphccmk.html

Py:   s1 == s2; s1 != s2
来源：http://dali.xuetiantiany.cn/Article/details/gt2vcgelmbj.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vnqophpe.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.tanke756.top/Article/details/gt2nhfziirt.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jinqigufen.top/Article/details/gt2esfoqxph.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.ppjwa.cn/Article/details/gt2rxdgfjmn.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.sxryk.cn/Article/details/gt2ywyhoake.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.dianchejie.cn/Article/details/gt2tillcwkl.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.ydzc1.top/Article/details/gt2uinlkoaj.html

[A26] 类型转换总览
来源：http://dali.cdnleiting.top/Article/details/gt2lnrdcnrm.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.gotoacloud.top/Article/details/gt2emtacdjj.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.nanxuanxn.top/Article/details/gt2qjdxnghv.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.aizwys.cn/Article/details/gt2mdysvnks.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zhengqikj.top/Article/details/gt2srcpbkzu.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.dashuyun.cn/Article/details/gt2zajkanqi.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.tian-w.cn/Article/details/gt2scsdcdtr.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.cqqwz.cn/Article/details/gt2tzzkfjha.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.shangyingyoupin.top/Article/details/gt2utloyefy.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2wnuomhyk.html

B. 流程控制
来源：http://dali.xuetiantiany.cn/Article/details/gt2fwhqgzka.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2frccemmg.html

[B01] 条件判断 if / else
来源：http://dali.snrcjt.cn/Article/details/gt2hagvtbso.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.hywenlv.cn/Article/details/gt2ogyminod.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.dianchejie.cn/Article/details/gt2uqhrrbcf.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yj202588.top/Article/details/gt2owjecptu.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.aibaodan.cn/Article/details/gt2qappwkln.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.hfpthk.cn/Article/details/gt2kyqbaszo.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.quarkkingdee.top/Article/details/gt2zdwyrbyl.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.ivvv.top/Article/details/gt2mizafwah.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.xuetiantiany.cn/Article/details/gt2kwfwvtdy.html

[B02] 多分支 else if / elif
来源：http://dali.ybcxt.top/Article/details/gt2qkycaizc.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.xinyue.icu/Article/details/gt2vttlgdsu.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.xziqi.cn/Article/details/gt2qwajplcz.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jqgfzy.top/Article/details/gt2zzondqre.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zdqjudy.top/Article/details/gt2dgzgqgfy.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xziqi.cn/Article/details/gt2qguovmcw.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.xylfe.cn/Article/details/gt2dqtztkfg.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.shangyingyoupin.top/Article/details/gt2zmdebjwd.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.aizwys.cn/Article/details/gt2mrnrfizf.html

[B03] switch / match / case
来源：http://dali.redwolf501.top/Article/details/gt2qobtwucz.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yvedp.cn/Article/details/gt2wgwtehct.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2upgnurdt.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hammf.cn/Article/details/gt2jglgoijj.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.c1oappe.top/Article/details/gt2tkiynlxv.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.yj202588.top/Article/details/gt2dmkdnxjc.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yj202588.top/Article/details/gt2fxiolpyn.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.redwolf501.top/Article/details/gt2hbpgmnsu.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ckdrnajy.html

[B04] for 计数循环
来源：http://dali.daria6918.cn/Article/details/gt2tvctzxtp.html

Py:   for i in range(10): print(i)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rsrdkbhp.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2atekasoc.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.fzhhl.top/Article/details/gt2televskb.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2uhyywkgl.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.gzhubu.top/Article/details/gt2mqmhjvig.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yuxming.cn/Article/details/gt2tfwumfqe.html

Ruby: 10.times { |i| puts i }
来源：http://dali.guannengcc.top/Article/details/gt2cstwatiz.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.fzhhl.top/Article/details/gt2ksnuwiwv.html

[B05] 遍历数组 / 列表
来源：http://dali.jqgfzy.top/Article/details/gt2pbjkxpdi.html

Py:   for item in arr: print(item)
来源：http://dali.zhoulong.xyz/Article/details/gt2witnwesb.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zhixingplan.top/Article/details/gt2dljzrzwt.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.dianchejie.cn/Article/details/gt2qdvfujiz.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.kuanghao11.cn/Article/details/gt2kloyegny.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.guowangkeji.top/Article/details/gt2xiuhwixo.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.xziqi.cn/Article/details/gt2krexxuim.html

Ruby: arr.each { |item| puts item }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nisxfogu.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jlsjyb.cn/Article/details/gt2jhxxsper.html

[B06] 遍历字典 / 对象
来源：http://dali.aibaodan.cn/Article/details/gt2jxgblmof.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.gotoacloud.top/Article/details/gt2tqlskrlr.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.aizwys.cn/Article/details/gt2jwdivblu.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jianghu66.top/Article/details/gt2vklrvjgm.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nuwmessk.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kvnacpgu.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.chenzaomai.com/Article/details/gt2udqcqqwr.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.ehwqpu.com/Article/details/gt2zkybjnxc.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.hammf.cn/Article/details/gt2wtlfqatf.html

[B07] while 循环
来源：http://dali.quarkkingdee.top/Article/details/gt2rssuwrqw.html

Py:   while i < 10: i += 1
来源：http://dali.yueranfly.top/Article/details/gt2ogtjqaam.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ougpbisq.html

JS:   while (i < 10) { i++; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2wizbsjnz.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvfppkte.html

Java: while (i < 10) { i++; }
来源：http://dali.andypj.xyz/Article/details/gt2xbyuhxab.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.xuetiantiany.cn/Article/details/gt2ppisffza.html

Ruby: while i < 10; i += 1; end
来源：http://dali.haohaochexian.top/Article/details/gt2zfjbpwxh.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhongyouzk.top/Article/details/gt2gyyfxhug.html

[B08] do-while（至少执行一次）
来源：http://dali.xuetiantiany.cn/Article/details/gt2jfuyydnu.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.xuanzx.com/Article/details/gt2baatcrro.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.hfpthk.cn/Article/details/gt2ntefzybg.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yj20258888.top/Article/details/gt2dqrjjwgw.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zycfv.cn/Article/details/gt2awhjrnnw.html

Java: do { i++; } while (i < 10);
来源：http://dali.hfpthk.cn/Article/details/gt2zksonwbz.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.gogol.net.cn/Article/details/gt2kxbwkcic.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.0kj1m.cn/Article/details/gt2tvpgcoct.html

C#:   do { i++; } while (i < 10);
来源：http://dali.hywenlv.cn/Article/details/gt2yiposmdz.html


<!-- 参考信息 -->