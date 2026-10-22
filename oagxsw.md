代发 wailian999

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.redwolf501.top/Article/details/gt2zyzdvkcd.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.gaohongyu789.top/Article/details/gt2brfcmgnl.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jyoumei.cn/Article/details/gt2yfpnjomz.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.hnxiangtu.top/Article/details/gt2gcegbufg.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2puoqlmxq.html

A. 基础语法与类型
来源：http://dali.zhoulong.xyz/Article/details/gt2pkccqvlv.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2zovmhuxm.html

[A01] Hello World
来源：http://dali.hnxiangtu.top/Article/details/gt2ecgdisfb.html

Py:   print("Hello, World!")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ugvgwrhs.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2zexrmjeb.html

JS:   console.log("Hello, World!");
来源：http://dali.svipenyu.cn/Article/details/gt2lokqoous.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.nanxinkj.top/Article/details/gt2vtclueja.html

Java: System.out.println("Hello, World!");
来源：http://dali.svipenyu.cn/Article/details/gt2xhrqacrt.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.gzhubu.top/Article/details/gt2jyxblywj.html

Ruby: puts "Hello, World!"
来源：http://dali.jinqigfzy.top/Article/details/gt2ksokfpzo.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.xinyue.icu/Article/details/gt2lwgpxccm.html

[A02] 变量声明与赋值
来源：http://dali.jinqigufen.top/Article/details/gt2jzspkvzt.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.quarkkingdee.top/Article/details/gt2rkzjzgob.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhongyouzk.top/Article/details/gt2uwooqqlu.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.smart0.xyz/Article/details/gt2mcajgjvg.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.ehwqpu.com/Article/details/gt2tcbjcpkx.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.jyoumei.cn/Article/details/gt2npjhlwmn.html

Go:   name := "Alex"; age := 20
来源：http://dali.aizwys.cn/Article/details/gt2hlsnsigt.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yuxming.cn/Article/details/gt2uwlhkvse.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.wangshuangyany.cn/Article/details/gt2chwoatju.html

[A03] 常量定义
来源：http://dali.xuanzx.com/Article/details/gt2nowqcqld.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.sufxvd.cn/Article/details/gt2jjkiokkb.html

PHP:  const PI = 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gt2zkacancg.html

JS:   const PI = 3.14159;
来源：http://dali.tian-w.cn/Article/details/gt2zvwoytah.html

TS:   const PI: number = 3.14159;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lqkqavmw.html

Java: static final double PI = 3.14159;
来源：http://dali.zhongyouzk.top/Article/details/gt2qhvvhfha.html

Go:   const PI = 3.14159
来源：http://dali.gogol.net.cn/Article/details/gt2vqpytele.html

Ruby: PI = 3.14159
来源：http://dali.cucudq.cn/Article/details/gt2gpscbpbc.html

C#:   const double PI = 3.14159;
来源：http://dali.cashguo.top/Article/details/gt2zannbyhb.html

[A04] 判断变量类型
来源：http://dali.guowangkeji.top/Article/details/gt2thbxrsxr.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.andypj.xyz/Article/details/gt2lzmyhoya.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.dashuyun.cn/Article/details/gt2eohjitmi.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.gogol.net.cn/Article/details/gt2mpwpbulb.html

TS:   typeof x; x instanceof Date
来源：http://dali.cheryme.top/Article/details/gt2eqhytynz.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.daria6918.cn/Article/details/gt2txxyrotr.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.yj20258.top/Article/details/gt2cbmoorts.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jinqigfzy.top/Article/details/gt2yjhgztld.html

C#:   x.GetType().Name; x is int
来源：http://dali.shangyingyoupin.top/Article/details/gt2elsifgbm.html

[A05] 整数除法与取模
来源：http://dali.zdqjudy.top/Article/details/gt2crpbpzlu.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.cucudq.cn/Article/details/gt2hooswnzx.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.chenlongwang.top/Article/details/gt2htmlhuiy.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jqgufenzy.top/Article/details/gt2wqvkztpt.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.sysykeji.top/Article/details/gt2vpgcngnl.html

Java: 7 / 2; 7 % 2
来源：http://dali.andypj.xyz/Article/details/gt2mojwpnes.html

Go:   7 / 2; 7 % 2
来源：http://dali.yongpay.top/Article/details/gt2ncwbhxbf.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tcbteurb.html

C#:   7 / 2; 7 % 2
来源：http://dali.pycfn.com/Article/details/gt2ldexvnjm.html

[A06] 字符串转数字
来源：http://dali.chenzaomai.com/Article/details/gt2sviwyomz.html

Py:   int("42"); float("3.14")
来源：http://dali.nanxinkj.top/Article/details/gt2ahpxyhrs.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2imwtjnsc.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.xuanzx.com/Article/details/gt2dxtxohma.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.gzhubu.top/Article/details/gt2jedjcuib.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rzqfuoet.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.wangshuangyany.cn/Article/details/gt2pudhlfxo.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.ydzc1.top/Article/details/gt2vtewsogj.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.smart0.xyz/Article/details/gt2tjtndunx.html

[A07] 数字转字符串
来源：http://dali.zhoulong.xyz/Article/details/gt2rijonovv.html

Py:   str(42)
来源：http://dali.iojbl.cn/Article/details/gt2xqljohzz.html

PHP:  (string) 42; strval(42)
来源：http://dali.aibaodan.cn/Article/details/gt2pbrfvubp.html

JS:   String(42); (42).toString()
来源：http://dali.sysykeji.top/Article/details/gt2yrmyxkwl.html

TS:   String(42)
来源：http://dali.zycfv.cn/Article/details/gt2hlodvwef.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.bjfxy.top/Article/details/gt2igvjcrwy.html

Go:   strconv.Itoa(42)
来源：http://dali.cashguo.top/Article/details/gt2evycwrao.html

Ruby: 42.to_s
来源：http://dali.aizwys.cn/Article/details/gt2gishhens.html

C#:   42.ToString()
来源：http://dali.cdnleiting.top/Article/details/gt2lkmxhuan.html

[A08] 取整与四舍五入
来源：http://dali.haohaochexian.top/Article/details/gt2czoevabf.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.ppjwa.cn/Article/details/gt2xobrfrmo.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.ppjwa.cn/Article/details/gt2atdxlwmu.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.aibaodan.cn/Article/details/gt2ssdjstjl.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yozcjwpi.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.hongshengwenyu.top/Article/details/gt2wirznrpc.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.jiagoushi.top/Article/details/gt2xhutabep.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.kuanghao11.cn/Article/details/gt2ujgjturt.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.yj202588.top/Article/details/gt2mojanvmv.html

[A09] 绝对值与最大最小值
来源：http://dali.dianchejie.cn/Article/details/gt2lfqutorw.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.fzhhl.top/Article/details/gt2pmhfbwai.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2vsjecwqt.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kitmwqug.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.shuidangran.top/Article/details/gt2zgfnsdts.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.yj20258888.top/Article/details/gt2airaossw.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.gzhubu.top/Article/details/gt2ccdrswgz.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.hywenlv.cn/Article/details/gt2ssobetpg.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.xylfe.cn/Article/details/gt2estdaecq.html

[A10] 生成随机数
来源：http://dali.jinqigfzy.top/Article/details/gt2prghwesa.html

Py:   import random; random.randint(1, 100)
来源：http://dali.iojbl.cn/Article/details/gt2layprvnm.html

PHP:  random_int(1, 100);
来源：http://dali.gzhubu.top/Article/details/gt2gsfdfmri.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.chenjidiqi.icu/Article/details/gt2irtldpsz.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yongpay.top/Article/details/gt2sdpyyhtf.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhiwuduotai.top/Article/details/gt2djznydaf.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.xinyue.icu/Article/details/gt2eggrloro.html

Ruby: rand(1..100)
来源：http://dali.fzhhl.top/Article/details/gt2bjchnitk.html

C#:   new Random().Next(1, 101)
来源：http://dali.sufxvd.cn/Article/details/gt2yibwpqhp.html

[A11] 条件表达式（三元）
来源：http://dali.kuanghao11.cn/Article/details/gt2pftsjjep.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.tanke756.top/Article/details/gt2qvbxamtk.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.redwolf501.top/Article/details/gt2uouhobfe.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.chenzaomai.com/Article/details/gt2wmlomoca.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.guowangkeji.top/Article/details/gt2aujffkxb.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.xylfe.cn/Article/details/gt2fsguwjfa.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.jinqigufen.top/Article/details/gt2omneagev.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.cdnleiting.top/Article/details/gt2gkheekkp.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.nanxuanxn.top/Article/details/gt2mwdkydai.html

[A12] 字符串插值 / 格式化
来源：http://dali.quarkkingdee.top/Article/details/gt2dmmmwsjo.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.yueranfly.top/Article/details/gt2ypuaayou.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.316326.xyz/Article/details/gt2fctrdvwu.html

JS:   `Hello, ${name}!`
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wmbchtcb.html

TS:   `Hello, ${name}!`
来源：http://dali.mhx1999.top/Article/details/gt2vajklrvb.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.jianghu66.top/Article/details/gt2xadlhzzq.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.sufxvd.cn/Article/details/gt2jfjycutk.html

Ruby: "Hello, #{name}!"
来源：http://dali.fengsongda.top/Article/details/gt2dgmtpfee.html

C#:   $"Hello, {name}!"
来源：http://dali.chenzaomai.com/Article/details/gt2ndapgzts.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.smart0.xyz/Article/details/gt2fytomvxz.html

Py:   "第一行\n第二行"
来源：http://dali.daxiang520.top/Article/details/gt2kqnsovkg.html

PHP:  "第一行\n第二行"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mmrpolkp.html

JS:   "第一行\n第二行"
来源：http://dali.zhiwuduotai.top/Article/details/gt2hicgowjq.html

TS:   "第一行\n第二行"
来源：http://dali.hysaishi.cn/Article/details/gt2iiduvlvb.html

Java: "第一行\n第二行"
来源：http://dali.aizwys.cn/Article/details/gt2qhsxgeim.html

Go:   "第一行\n第二行"
来源：http://dali.xuanzx.com/Article/details/gt2hltzdwsf.html

Ruby: "第一行\n第二行"
来源：http://dali.sweek.top/Article/details/gt2daviwxyu.html

C#:   "第一行\n第二行"
来源：http://dali.ybcxt.top/Article/details/gt2wcssqmgc.html

[A14] 注释写法
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eqwkfznf.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.guannengcc.top/Article/details/gt2pyiktxha.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.jqgfzy.top/Article/details/gt2fyhwfbxp.html

JS:   // 单行；/* 多行 */
来源：http://dali.yuxming.cn/Article/details/gt2lsuttovx.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhongyouzk.top/Article/details/gt2enlhgkjp.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.yuxming.cn/Article/details/gt2hqhrnsgq.html

Go:   // 单行；/* 多行 */
来源：http://dali.bjfxy.top/Article/details/gt2lwptvspx.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.jqgufenzy.top/Article/details/gt2xibfhhfp.html

C#:   // 单行；/* 多行 */
来源：http://dali.hnxiangtu.top/Article/details/gt2dkrzyfok.html

[A15] 空值判断与默认值
来源：http://dali.cucudq.cn/Article/details/gt2niedqbdo.html

Py:   value = data or "默认值"
来源：http://dali.sweek.top/Article/details/gt2amuaguru.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.nwbrower.top/Article/details/gt2vqleoksq.html

JS:   const value = data ?? "默认值";
来源：http://dali.jyoumei.cn/Article/details/gt2cqklpgvv.html

TS:   const value = data ?? "默认值";
来源：http://dali.pengpengdd.cyou/Article/details/gt2adxgkshn.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.pengpengdd.cyou/Article/details/gt2fzbcansx.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.cheryme.top/Article/details/gt2lonzhcqh.html

Ruby: value = data || "默认值"
来源：http://dali.yuanzhike.top/Article/details/gt2zyndhrje.html

C#:   var value = data ?? "默认值";
来源：http://dali.gotoacloud.top/Article/details/gt2olaunvcf.html

[A16] 真假值判断规则
来源：http://dali.jinqigufen.top/Article/details/gt2qvblltpu.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.nwbrower.top/Article/details/gt2rqaebnfh.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.vqdsnc.cn/Article/details/gt2lstrmiei.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.gotoacloud.top/Article/details/gt2aglgihef.html

TS:   if (!x) {}
来源：http://dali.ivvv.top/Article/details/gt2aqxwlsqc.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.sufxvd.cn/Article/details/gt2ngfzegjj.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.jiagoushi.top/Article/details/gt2ypigfmrj.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.birdmap.top/Article/details/gt2wucbbaga.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.andypj.xyz/Article/details/gt2qxfhpbuh.html

[A17] 位运算
来源：http://dali.zdqjudy.top/Article/details/gt2mcccizwm.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.iojbl.cn/Article/details/gt2hjlinjnq.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rxdzfirr.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.iojbl.cn/Article/details/gt2cubkbbov.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.svipenyu.cn/Article/details/gt2otthvhrd.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.birdmap.top/Article/details/gt2hluwklka.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.tian-w.cn/Article/details/gt2arlcnoak.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hongshengwenyu.top/Article/details/gt2uephqlwp.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.nwbrower.top/Article/details/gt2xozhowfm.html

[A18] 字符与 ASCII 码互转
来源：http://dali.jqgufenzy.top/Article/details/gt2yhlfslid.html

Py:   ord("A"); chr(65)
来源：http://dali.zycfv.cn/Article/details/gt2tmwjbkox.html

PHP:  ord("A"); chr(65)
来源：http://dali.hongshengwenyu.top/Article/details/gt2xdbdmjnl.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.hongshengwenyu.top/Article/details/gt2tveudzcb.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.bjfxy.top/Article/details/gt2loqqlhlr.html

Java: (int) 'A'; (char) 65
来源：http://dali.cqqwz.cn/Article/details/gt2njppepja.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.shanyushiyangtech.top/Article/details/gt2miopljvs.html

Ruby: "A".ord; 65.chr
来源：http://dali.pengpengdd.cyou/Article/details/gt2edgzrekg.html

C#:   (int)'A'; (char)65
来源：http://dali.havefunace.top/Article/details/gt2ijdyncgq.html

[A19] 交换两个变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xsqkpisk.html

Py:   a, b = b, a
来源：http://dali.chenzaomai.com/Article/details/gt2tviimpej.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.chenlongwang.top/Article/details/gt2fuzgfdup.html

JS:   [a, b] = [b, a];
来源：http://dali.kuanghao11.cn/Article/details/gt2fgkkjikk.html

TS:   [a, b] = [b, a];
来源：http://dali.ybcxt.top/Article/details/gt2xqomvnbf.html

Java: int t = a; a = b; b = t;
来源：http://dali.hfpthk.cn/Article/details/gt2tevvijzk.html

Go:   a, b = b, a
来源：http://dali.ppjwa.cn/Article/details/gt2fnjqjwtu.html

Ruby: a, b = b, a
来源：http://dali.hammf.cn/Article/details/gt2tcboemwr.html

C#:   (a, b) = (b, a);
来源：http://dali.chenjidiqi.icu/Article/details/gt2kbzujwco.html

[A20] 读取标准输入
来源：http://dali.hfpthk.cn/Article/details/gt2wkgsxwpw.html

Py:   name = input("请输入：")
来源：http://dali.iojbl.cn/Article/details/gt2fqzzjcvn.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.zhongyouzk.top/Article/details/gt2mkqirvas.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.yonumen.top/Article/details/gt2owbdiiya.html

TS:   // Node.js：readline 模块
来源：http://dali.mhx1999.top/Article/details/gt2siwptxwa.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.gzhubu.top/Article/details/gt2gbqdykec.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.iojbl.cn/Article/details/gt2hgjsnexf.html

Ruby: gets.chomp
来源：http://dali.sufxvd.cn/Article/details/gt2zagrzipg.html

C#:   Console.ReadLine();
来源：http://dali.guowangkeji.top/Article/details/gt2sbrhhvxp.html

[A21] 保留指定小数位输出
来源：http://dali.ehwqpu.com/Article/details/gt2gzcssitn.html

Py:   f"{3.14159:.2f}"
来源：http://dali.fzhhl.top/Article/details/gt2oeqcgmio.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.snrcjt.cn/Article/details/gt2pzrccrbi.html

JS:   (3.14159).toFixed(2)
来源：http://dali.xziqi.cn/Article/details/gt2bgddbboq.html

TS:   (3.14159).toFixed(2)
来源：http://dali.ybcxt.top/Article/details/gt2mveswhhx.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.sweek.top/Article/details/gt2apezgves.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.xziqi.cn/Article/details/gt2zdpgglnr.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.ivvv.top/Article/details/gt2mrcqtpuz.html

C#:   3.14159.ToString("F2")
来源：http://dali.yongpay.top/Article/details/gt2wpabycho.html

[A22] 获取字符串长度
来源：http://dali.jinghuilouyu.cn/Article/details/gt2disggvqw.html

Py:   len(s)
来源：http://dali.cashguo.top/Article/details/gt2mhdsdxou.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.316326.xyz/Article/details/gt2zgxfsctk.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.yvedp.cn/Article/details/gt2schdyumd.html

TS:   s.length
来源：http://dali.yuxming.cn/Article/details/gt2aohofbeu.html

Java: s.length()
来源：http://dali.fengsongda.top/Article/details/gt2zmppokdj.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.yongpay.top/Article/details/gt2xmoffoxz.html

Ruby: s.length
来源：http://dali.vqdsnc.cn/Article/details/gt2krgypeos.html

C#:   s.Length
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wcononmh.html

[A23] 大小写转换
来源：http://dali.gotoacloud.top/Article/details/gt2nglahghy.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.andypj.xyz/Article/details/gt2gghiiynb.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.pycfn.com/Article/details/gt2gtjjigxb.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.9152youxi.cn/Article/details/gt2ewqnxwil.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.pycfn.com/Article/details/gt2hmlhdctf.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.haohaochexian.top/Article/details/gt2rlsqfmln.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.nanxinkj.top/Article/details/gt2kjaluqpf.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.jqgufenzy.top/Article/details/gt2efzttylx.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.andypj.xyz/Article/details/gt2dsesvtky.html

[A24] 去除首尾空白
来源：http://dali.mhx1999.top/Article/details/gt2drugrpgj.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.iojbl.cn/Article/details/gt2ysvgjuwy.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.cdnleiting.top/Article/details/gt2jzuwiwtc.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.kuanghao11.cn/Article/details/gt2jcfkefys.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.vqdsnc.cn/Article/details/gt2tctugjtt.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.wangdashe.top/Article/details/gt2ogieujrx.html

Go:   strings.TrimSpace(s)
来源：http://dali.yonumen.top/Article/details/gt2dcuvsgzo.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yvedp.cn/Article/details/gt2epxmrfba.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.chenjidiqi.icu/Article/details/gt2tmjipztw.html

[A25] 字符串比较
来源：http://dali.hammf.cn/Article/details/gt2npcmcprl.html

Py:   s1 == s2; s1 != s2
来源：http://dali.0kj1m.cn/Article/details/gt2umacopqz.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yanxiufei.cn/Article/details/gt2baxgaozn.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.andypj.xyz/Article/details/gt2ftvnzhhc.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.haohaochexian.top/Article/details/gt2faewttmz.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.mhx1999.top/Article/details/gt2dpugckip.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.gzhubu.top/Article/details/gt2bfognkyk.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.dianchejie.cn/Article/details/gt2kndrztgq.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.tanke756.top/Article/details/gt2nijmupiy.html

[A26] 类型转换总览
来源：http://dali.shuidangran.top/Article/details/gt2fcudwcdt.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yongpay.top/Article/details/gt2mhjvcjof.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.chenjidiqi.icu/Article/details/gt2wkxfuvjf.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jqgufenzy.top/Article/details/gt2xhbqxsfb.html

TS:   Number() String() Boolean() x as number
来源：http://dali.snrcjt.cn/Article/details/gt2rrjxdfoq.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zycfv.cn/Article/details/gt2tstcopbi.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zdqjudy.top/Article/details/gt2mgjqwahl.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.kuanghao11.cn/Article/details/gt2ulcjrxef.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.ybcxt.top/Article/details/gt2karfnims.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2obvmbrpo.html

B. 流程控制
来源：http://dali.bjfxy.top/Article/details/gt2xrdmbqhd.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2bfquuvfq.html

[B01] 条件判断 if / else
来源：http://dali.ivvv.top/Article/details/gt2hqlsyrdm.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.gotoacloud.top/Article/details/gt2mqpmjksn.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.zdqjudy.top/Article/details/gt2ocrmajfd.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jlsjyb.cn/Article/details/gt2lkficskx.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.kuanghao11.cn/Article/details/gt2khpdkbjd.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.nanxuanxn.top/Article/details/gt2rasaqtup.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghhftgvc.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.gogol.net.cn/Article/details/gt2uawajxfc.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2athwwhet.html

[B02] 多分支 else if / elif
来源：http://dali.ivvv.top/Article/details/gt2eowmevdb.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.hysaishi.cn/Article/details/gt2lqirloma.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zdqjudy.top/Article/details/gt2nnrwdciy.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xziqi.cn/Article/details/gt2xcznyvem.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.snrcjt.cn/Article/details/gt2zbrnzvxx.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xinyue.icu/Article/details/gt2cobtjvqk.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jzuewbtl.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.ybcxt.top/Article/details/gt2oifzymdf.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.daxiang520.top/Article/details/gt2rxoanixj.html

[B03] switch / match / case
来源：http://dali.meibo888.top/Article/details/gt2uymgveya.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yuanzhike.top/Article/details/gt2mhpyoeeb.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yuanzhike.top/Article/details/gt2zkjeojnh.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ijkuqgij.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.nanxuanxn.top/Article/details/gt2aurwfuoi.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2mhsqbglo.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.cucudq.cn/Article/details/gt2bqavibcs.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.svipenyu.cn/Article/details/gt2zxiyfqpw.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yvedp.cn/Article/details/gt2mudirrym.html

[B04] for 计数循环
来源：http://dali.jlsjyb.cn/Article/details/gt2zjvhoyow.html

Py:   for i in range(10): print(i)
来源：http://dali.fzhhl.top/Article/details/gt2hztndowz.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lofyaklm.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yj20258.top/Article/details/gt2jhgomyrq.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.sysykeji.top/Article/details/gt2qllubmfg.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yanxiufei.cn/Article/details/gt2flubtheo.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.cashguo.top/Article/details/gt2xaadhbdq.html

Ruby: 10.times { |i| puts i }
来源：http://dali.svipenyu.cn/Article/details/gt2kibxlgsr.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.havefunace.top/Article/details/gt2vamqtseo.html

[B05] 遍历数组 / 列表
来源：http://dali.jyoumei.cn/Article/details/gt2dpgtaawm.html

Py:   for item in arr: print(item)
来源：http://dali.shzxlz.cn/Article/details/gt2lswlzupb.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zhengqikj.top/Article/details/gt2jqvujnbv.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xveiznqd.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.kuanghao11.cn/Article/details/gt2flnbsrjl.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hysaishi.cn/Article/details/gt2hidaqfqf.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jiagoushi.top/Article/details/gt2hmyleinj.html

Ruby: arr.each { |item| puts item }
来源：http://dali.quarkkingdee.top/Article/details/gt2nmcjmjjx.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.tianlin.xyz/Article/details/gt2gvjkhvpk.html

[B06] 遍历字典 / 对象
来源：http://dali.jqgufenzy.top/Article/details/gt2kynnikft.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.hfpthk.cn/Article/details/gt2onttybys.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jteowzxq.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.aizwys.cn/Article/details/gt2ptatqiok.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.snrcjt.cn/Article/details/gt2frtllxzh.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.guannengcc.top/Article/details/gt2xkwchrps.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.nwbrower.top/Article/details/gt2zldvxvnw.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.svipenyu.cn/Article/details/gt2tczgzynp.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2chgawppq.html

[B07] while 循环
来源：http://dali.haohaochexian.top/Article/details/gt2lmdnyone.html

Py:   while i < 10: i += 1
来源：http://dali.feifeiyinyue.top/Article/details/gt2aohulxdy.html


<!-- 参考信息 -->