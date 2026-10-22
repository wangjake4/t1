代发 wailian999

[A02] 变量声明与赋值
来源：http://dali.yj20258.top/Article/details/gt2ddjdvaac.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yvedp.cn/Article/details/gt2dmvidrsr.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.sxryk.cn/Article/details/gt2drnxahtv.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ssrgxjtz.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.pengpengdd.cyou/Article/details/gt2xewfiedr.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yj20258.top/Article/details/gt2pfkfbkye.html

Go:   name := "Alex"; age := 20
来源：http://dali.birdmap.top/Article/details/gt2lqixqpka.html

Ruby: name = "Alex"; age = 20
来源：http://dali.c1oappe.top/Article/details/gt2pgzyouon.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.andypj.xyz/Article/details/gt2evipfgui.html

[A03] 常量定义
来源：http://dali.9152youxi.cn/Article/details/gt2ksxpqypl.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.shuidangran.top/Article/details/gt2xdopmhia.html

PHP:  const PI = 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2szwrfhfx.html

JS:   const PI = 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gt2krfokzna.html

TS:   const PI: number = 3.14159;
来源：http://dali.zdqjudy.top/Article/details/gt2falmpnsg.html

Java: static final double PI = 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gt2qcwvbvcd.html

Go:   const PI = 3.14159
来源：http://dali.yangfankeji.com/Article/details/gt2wtpejugp.html

Ruby: PI = 3.14159
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wvvnrwly.html

C#:   const double PI = 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gt2fqbjanrr.html

[A04] 判断变量类型
来源：http://dali.ybcxt.top/Article/details/gt2oyislmnf.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.ppjwa.cn/Article/details/gt2eqmkxhoe.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.aibaodan.cn/Article/details/gt2mxqzynqx.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.sufxvd.cn/Article/details/gt2dzxynwxd.html

TS:   typeof x; x instanceof Date
来源：http://dali.cheryme.top/Article/details/gt2bbqfxcgk.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhengqikj.top/Article/details/gt2pjufincr.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tlzpqyet.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.0kj1m.cn/Article/details/gt2rmbwqqry.html

C#:   x.GetType().Name; x is int
来源：http://dali.sxryk.cn/Article/details/gt2egpiyycs.html

[A05] 整数除法与取模
来源：http://dali.gogol.net.cn/Article/details/gt2emveedef.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.gogol.net.cn/Article/details/gt2tsnjbymb.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.dianchejie.cn/Article/details/gt2aaukmbbu.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.gaohongyu789.top/Article/details/gt2sewxxlbk.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.bjfxy.top/Article/details/gt2hdnbnvdi.html

Java: 7 / 2; 7 % 2
来源：http://dali.jianghu66.top/Article/details/gt2araaqmye.html

Go:   7 / 2; 7 % 2
来源：http://dali.jlsjyb.cn/Article/details/gt2efbcawiw.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.chenlongwang.top/Article/details/gt2fhycaxxq.html

C#:   7 / 2; 7 % 2
来源：http://dali.gotoacloud.top/Article/details/gt2xlhwuvyj.html

[A06] 字符串转数字
来源：http://dali.birdmap.top/Article/details/gt2qzztdacp.html

Py:   int("42"); float("3.14")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ppfuhmef.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.bjfxy.top/Article/details/gt2lovdbmww.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.daria6918.cn/Article/details/gt2nmnonvkh.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.hysaishi.cn/Article/details/gt2ihtcdrmy.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.hnxiangtu.top/Article/details/gt2rohrbgig.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yj202588.top/Article/details/gt2zlioxcdq.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.jianghu66.top/Article/details/gt2shsaemsa.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.ivvv.top/Article/details/gt2ksvusasz.html

[A07] 数字转字符串
来源：http://dali.yangfankeji.com/Article/details/gt2qeprkahk.html

Py:   str(42)
来源：http://dali.wangdashe.top/Article/details/gt2spmsvqxv.html

PHP:  (string) 42; strval(42)
来源：http://dali.snrcjt.cn/Article/details/gt2gykryuqg.html

JS:   String(42); (42).toString()
来源：http://dali.zhengqikj.top/Article/details/gt2rmwbjzfv.html

TS:   String(42)
来源：http://dali.zhiwuduotai.top/Article/details/gt2rerkisnx.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.cqqwz.cn/Article/details/gt2sbajdrky.html

Go:   strconv.Itoa(42)
来源：http://dali.jiagoushi.top/Article/details/gt2xyjfdgyk.html

Ruby: 42.to_s
来源：http://dali.zhongyouzk.top/Article/details/gt2qpzzujmp.html

C#:   42.ToString()
来源：http://dali.jlsjyb.cn/Article/details/gt2ngjfvdju.html

[A08] 取整与四舍五入
来源：http://dali.yueranfly.top/Article/details/gt2jaxdqhqi.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.daria6918.cn/Article/details/gt2xxweywew.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhixingplan.top/Article/details/gt2ehlsydvy.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.hnxiangtu.top/Article/details/gt2qspajbwq.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.xinyue.icu/Article/details/gt2irpzoedj.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.havefunace.top/Article/details/gt2urdkcucl.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.yuxming.cn/Article/details/gt2widvaecr.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.jianghu66.top/Article/details/gt2hlhfwjxe.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.0kj1m.cn/Article/details/gt2cuplyblv.html

[A09] 绝对值与最大最小值
来源：http://dali.9152youxi.cn/Article/details/gt2ijyrttax.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.gaohongyu789.top/Article/details/gt2aljnecfx.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bavubjjz.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.kuanghao11.cn/Article/details/gt2hwlbzfbh.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.yuxming.cn/Article/details/gt2npeigqnr.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pjgiwygu.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhengqikj.top/Article/details/gt2nbujtzmw.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.ehwqpu.com/Article/details/gt2zndomfte.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.hywenlv.cn/Article/details/gt2areszbtj.html

[A10] 生成随机数
来源：http://dali.ppjwa.cn/Article/details/gt2yjvhlkdt.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhoulong.xyz/Article/details/gt2mlupidmy.html

PHP:  random_int(1, 100);
来源：http://dali.fzhhl.top/Article/details/gt2gucyrwmp.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jqgufenzy.top/Article/details/gt2vfaimwke.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhixingplan.top/Article/details/gt2pjzuhjvg.html

Java: new Random().nextInt(100) + 1
来源：http://dali.iojbl.cn/Article/details/gt2lkyabyzr.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.nwbrower.top/Article/details/gt2tffnssju.html

Ruby: rand(1..100)
来源：http://dali.ybcxt.top/Article/details/gt2kcxbywnu.html

C#:   new Random().Next(1, 101)
来源：http://dali.cucudq.cn/Article/details/gt2uccjgrhn.html

[A11] 条件表达式（三元）
来源：http://dali.sufxvd.cn/Article/details/gt2oyznhvxq.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2orqjkxrh.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.jinqigfzy.top/Article/details/gt2jgjwqabb.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.nanxinkj.top/Article/details/gt2wkmevmgf.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.hnxiangtu.top/Article/details/gt2fbxscdus.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.hfpthk.cn/Article/details/gt2mowplriz.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.havefunace.top/Article/details/gt2boymvtif.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.jinqigufen.top/Article/details/gt2nztzafze.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.xylfe.cn/Article/details/gt2mtmmaukw.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhiwuduotai.top/Article/details/gt2ygvjjohq.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.yuxming.cn/Article/details/gt2ognjaxjo.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.gotoacloud.top/Article/details/gt2ywdfnuwn.html

JS:   `Hello, ${name}!`
来源：http://dali.yj20258888.top/Article/details/gt2apryojhc.html

TS:   `Hello, ${name}!`
来源：http://dali.sufxvd.cn/Article/details/gt2jpdosuce.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.yueranfly.top/Article/details/gt2iglxlywt.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.yj20258888.top/Article/details/gt2agayvshn.html

Ruby: "Hello, #{name}!"
来源：http://dali.nwbrower.top/Article/details/gt2qbyljgka.html

C#:   $"Hello, {name}!"
来源：http://dali.pycfn.com/Article/details/gt2jugxpoxk.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.wangdashe.top/Article/details/gt2tqxigoab.html

Py:   "第一行\n第二行"
来源：http://dali.yangfankeji.com/Article/details/gt2yqfbjmzz.html

PHP:  "第一行\n第二行"
来源：http://dali.smart0.xyz/Article/details/gt2cxemphrm.html

JS:   "第一行\n第二行"
来源：http://dali.mhx1999.top/Article/details/gt2czgakbab.html

TS:   "第一行\n第二行"
来源：http://dali.gzhubu.top/Article/details/gt2ctopleue.html

Java: "第一行\n第二行"
来源：http://dali.bjfxy.top/Article/details/gt2zmkoxwjs.html

Go:   "第一行\n第二行"
来源：http://dali.shuidangran.top/Article/details/gt2bqpphxdi.html

Ruby: "第一行\n第二行"
来源：http://dali.ppjwa.cn/Article/details/gt2jevodhpn.html

C#:   "第一行\n第二行"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pnirpwjy.html

[A14] 注释写法
来源：http://dali.chenlongwang.top/Article/details/gt2okjlwvjx.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.xylfe.cn/Article/details/gt2lfnbfasp.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zycfv.cn/Article/details/gt2nufojjyw.html

JS:   // 单行；/* 多行 */
来源：http://dali.birdmap.top/Article/details/gt2ykgskxok.html

TS:   // 单行；/* 多行 */
来源：http://dali.9152youxi.cn/Article/details/gt2pdsalieh.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.jlsjyb.cn/Article/details/gt2renznrmd.html

Go:   // 单行；/* 多行 */
来源：http://dali.sweek.top/Article/details/gt2cmlquzor.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.yonumen.top/Article/details/gt2bnxnqtdy.html

C#:   // 单行；/* 多行 */
来源：http://dali.dianchejie.cn/Article/details/gt2yujpkqvu.html

[A15] 空值判断与默认值
来源：http://dali.bjfxy.top/Article/details/gt2hjvwaxjg.html

Py:   value = data or "默认值"
来源：http://dali.pengpengdd.cyou/Article/details/gt2efzcgigi.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.smart0.xyz/Article/details/gt2vvkxnlke.html

JS:   const value = data ?? "默认值";
来源：http://dali.cheryme.top/Article/details/gt2hsitvssa.html

TS:   const value = data ?? "默认值";
来源：http://dali.hnxiangtu.top/Article/details/gt2yikfkqpp.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cmmacica.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.shuidangran.top/Article/details/gt2fydefnox.html

Ruby: value = data || "默认值"
来源：http://dali.guannengcc.top/Article/details/gt2bfozrkub.html

C#:   var value = data ?? "默认值";
来源：http://dali.shzxlz.cn/Article/details/gt2zzbarvky.html

[A16] 真假值判断规则
来源：http://dali.c1oappe.top/Article/details/gt2qzmthcfm.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.iojbl.cn/Article/details/gt2frahlzgd.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.shzxlz.cn/Article/details/gt2xoxteqrp.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.jqgfzy.top/Article/details/gt2mnxsxrds.html

TS:   if (!x) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2avusqiwz.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.nwbrower.top/Article/details/gt2kyxpgorl.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.xuetiantiany.cn/Article/details/gt2zznhrbpj.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.xuetiantiany.cn/Article/details/gt2kdyivoey.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.ivvv.top/Article/details/gt2glvjulpo.html

[A17] 位运算
来源：http://dali.haohaochexian.top/Article/details/gt2yxlogqur.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ybcxt.top/Article/details/gt2cussadxj.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.meibo888.top/Article/details/gt2xdibuuaf.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.smart0.xyz/Article/details/gt2shnulodz.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.yuanzhike.top/Article/details/gt2cwgcjtdk.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zdqjudy.top/Article/details/gt2qpvnbhkf.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.ybcxt.top/Article/details/gt2qmqqajnd.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hongshengwenyu.top/Article/details/gt2klktyktc.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.meibo888.top/Article/details/gt2xmnaddcj.html

[A18] 字符与 ASCII 码互转
来源：http://dali.zhengqikj.top/Article/details/gt2tsmbbijs.html

Py:   ord("A"); chr(65)
来源：http://dali.xinyue.icu/Article/details/gt2emfolsfn.html

PHP:  ord("A"); chr(65)
来源：http://dali.aibaodan.cn/Article/details/gt2urnotdsy.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.sufxvd.cn/Article/details/gt2aqzgjbzi.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xxfxvmdj.html

Java: (int) 'A'; (char) 65
来源：http://dali.feifeiyinyue.top/Article/details/gt2cflqoiso.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.shzxlz.cn/Article/details/gt2wqevyivw.html

Ruby: "A".ord; 65.chr
来源：http://dali.zycfv.cn/Article/details/gt2zijpsrii.html

C#:   (int)'A'; (char)65
来源：http://dali.shuidangran.top/Article/details/gt2vkzntaui.html

[A19] 交换两个变量
来源：http://dali.jianghu66.top/Article/details/gt2idaffkhf.html

Py:   a, b = b, a
来源：http://dali.wangshuangyany.cn/Article/details/gt2zzesitjg.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.tanke756.top/Article/details/gt2lnkhlggd.html

JS:   [a, b] = [b, a];
来源：http://dali.fzhhl.top/Article/details/gt2wymkubvt.html

TS:   [a, b] = [b, a];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kuzbhakv.html

Java: int t = a; a = b; b = t;
来源：http://dali.yj202588.top/Article/details/gt2mamidehd.html

Go:   a, b = b, a
来源：http://dali.dashuyun.cn/Article/details/gt2yrczjeqo.html

Ruby: a, b = b, a
来源：http://dali.hysaishi.cn/Article/details/gt2mtbzrxqx.html

C#:   (a, b) = (b, a);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xjgzvlcw.html

[A20] 读取标准输入
来源：http://dali.nanxinkj.top/Article/details/gt2aborialh.html

Py:   name = input("请输入：")
来源：http://dali.zdqjudy.top/Article/details/gt2qkysyitw.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.hywenlv.cn/Article/details/gt2xkmbkdrc.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.nanxuanxn.top/Article/details/gt2xmkxpaeg.html

TS:   // Node.js：readline 模块
来源：http://dali.svipenyu.cn/Article/details/gt2rkdvxqsw.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.wangdashe.top/Article/details/gt2ppjmiuyy.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.gzhubu.top/Article/details/gt2mdybmzzq.html

Ruby: gets.chomp
来源：http://dali.yangfankeji.com/Article/details/gt2blssxfep.html

C#:   Console.ReadLine();
来源：http://dali.c1oappe.top/Article/details/gt2ooiklufl.html

[A21] 保留指定小数位输出
来源：http://dali.gzhubu.top/Article/details/gt2ynckdbye.html

Py:   f"{3.14159:.2f}"
来源：http://dali.dianchejie.cn/Article/details/gt2vwijnafj.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.havefunace.top/Article/details/gt2xvqpcvwf.html

JS:   (3.14159).toFixed(2)
来源：http://dali.daxiang520.top/Article/details/gt2orocagug.html

TS:   (3.14159).toFixed(2)
来源：http://dali.aizwys.cn/Article/details/gt2rzfaedon.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.dianchejie.cn/Article/details/gt2twxkynjg.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.fengsongda.top/Article/details/gt2lwmvwpcl.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.zdqjudy.top/Article/details/gt2kmzpvksm.html

C#:   3.14159.ToString("F2")
来源：http://dali.c1oappe.top/Article/details/gt2uvjfzqsd.html

[A22] 获取字符串长度
来源：http://dali.yj202588.top/Article/details/gt2ovtfqzaq.html

Py:   len(s)
来源：http://dali.tanke756.top/Article/details/gt2ukvhzgbs.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.yangfankeji.com/Article/details/gt2hzoaomnl.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.hywenlv.cn/Article/details/gt2esoxufct.html

TS:   s.length
来源：http://dali.svipenyu.cn/Article/details/gt2enwasifk.html

Java: s.length()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ycgvjece.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.yj20258.top/Article/details/gt2bhojbjwk.html

Ruby: s.length
来源：http://dali.jinqigufen.top/Article/details/gt2fjptxzgj.html

C#:   s.Length
来源：http://dali.yj20258888.top/Article/details/gt2muulhqqm.html

[A23] 大小写转换
来源：http://dali.yongpay.top/Article/details/gt2zpoygqjn.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.wangshuangyany.cn/Article/details/gt2rkmjnuwi.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.jlsjyb.cn/Article/details/gt2xuetpvtc.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.vqdsnc.cn/Article/details/gt2aeknqepl.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.smart0.xyz/Article/details/gt2selggdyh.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.hammf.cn/Article/details/gt2qfgruclt.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.yongpay.top/Article/details/gt2jiwhtezu.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.hysaishi.cn/Article/details/gt2nnwhfcwr.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.gotoacloud.top/Article/details/gt2mxurkqxl.html

[A24] 去除首尾空白
来源：http://dali.xziqi.cn/Article/details/gt2ywwbcjsc.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.9152youxi.cn/Article/details/gt2jnqhswri.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.yj202588.top/Article/details/gt2lkgcwsaz.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.tianlin.xyz/Article/details/gt2lpveysmy.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jqgufenzy.top/Article/details/gt2mixsjkzd.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.pycfn.com/Article/details/gt2wfoeryfs.html

Go:   strings.TrimSpace(s)
来源：http://dali.meibo888.top/Article/details/gt2dyifvjju.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.dianchejie.cn/Article/details/gt2msnutexk.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.ybcxt.top/Article/details/gt2cmkuqjry.html

[A25] 字符串比较
来源：http://dali.fzhhl.top/Article/details/gt2ucdeljgi.html

Py:   s1 == s2; s1 != s2
来源：http://dali.tianlin.xyz/Article/details/gt2fsknuuqe.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.zdqjudy.top/Article/details/gt2vdbwlihs.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gzwnkrra.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yueranfly.top/Article/details/gt2tytokxlu.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.zhengqikj.top/Article/details/gt2ifmufkxc.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yongpay.top/Article/details/gt2rpflpklm.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.svipenyu.cn/Article/details/gt2sylocaka.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2bbtcppcf.html

[A26] 类型转换总览
来源：http://dali.hongshengwenyu.top/Article/details/gt2djfrgbvn.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yuanzhike.top/Article/details/gt2qdowontr.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.daria6918.cn/Article/details/gt2mhnveqqm.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.cdnleiting.top/Article/details/gt2bffyfywk.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zhiwuduotai.top/Article/details/gt2micxlggp.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.xziqi.cn/Article/details/gt2qxsskwwh.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zycfv.cn/Article/details/gt2wvyneuoq.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.wangdashe.top/Article/details/gt2taezvpzz.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yongpay.top/Article/details/gt2wltyxsjb.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2gvjmxnhg.html

B. 流程控制
来源：http://dali.zhongyouzk.top/Article/details/gt2aweamjnn.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2nerilkqr.html

[B01] 条件判断 if / else
来源：http://dali.jqgfzy.top/Article/details/gt2kynpqruz.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dhwrasdv.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yueranfly.top/Article/details/gt2oltgrfic.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jqgufenzy.top/Article/details/gt2rkvpkcth.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xuanzx.com/Article/details/gt2dvqcoomh.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.quarkkingdee.top/Article/details/gt2tfrribwq.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.jiagoushi.top/Article/details/gt2cpbxmjwh.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2alwzjndg.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sytwfcks.html

[B02] 多分支 else if / elif
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zakzpaya.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.zhiwuduotai.top/Article/details/gt2fytdtvbe.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.aibaodan.cn/Article/details/gt2nzzplndg.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.guowangkeji.top/Article/details/gt2eridkods.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gzhubu.top/Article/details/gt2fhkzzrfx.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenlongwang.top/Article/details/gt2ynckjizl.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yuxming.cn/Article/details/gt2xcacugsj.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.ydzc1.top/Article/details/gt2iohpdlvz.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2liaplyjt.html

[B03] switch / match / case
来源：http://dali.guowangkeji.top/Article/details/gt2rvmlgigb.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jiagoushi.top/Article/details/gt2vddkvrgb.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.hnqzz.top/Article/details/gt2tgalszwa.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yonumen.top/Article/details/gt2gauewqfc.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ehwqpu.com/Article/details/gt2vempdrrg.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2efkgrgaz.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yonumen.top/Article/details/gt2lotrqgfm.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.yanxiufei.cn/Article/details/gt2arbzyusv.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.aizwys.cn/Article/details/gt2lxdanvye.html

[B04] for 计数循环
来源：http://dali.wangshuangyany.cn/Article/details/gt2jzwciokg.html

Py:   for i in range(10): print(i)
来源：http://dali.yongpay.top/Article/details/gt2qnfgtshe.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.zycfv.cn/Article/details/gt2vanozlmr.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wexfnbzs.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.aizwys.cn/Article/details/gt2dpozlurm.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.xuanzx.com/Article/details/gt2yiwteltl.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.jyoumei.cn/Article/details/gt2dchwuljs.html

Ruby: 10.times { |i| puts i }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wgkziend.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.wangdashe.top/Article/details/gt2hskwlzjk.html

[B05] 遍历数组 / 列表
来源：http://dali.dianchejie.cn/Article/details/gt2zizvliso.html

Py:   for item in arr: print(item)
来源：http://dali.wangdashe.top/Article/details/gt2jlmgcjfd.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.smart0.xyz/Article/details/gt2coqglqdf.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.mhx1999.top/Article/details/gt2gbvonfxl.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.nanxinkj.top/Article/details/gt2teyytbgw.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jqgufenzy.top/Article/details/gt2jsvzbyzc.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bxtofjoc.html

Ruby: arr.each { |item| puts item }
来源：http://dali.chenjidiqi.icu/Article/details/gt2vyriyjro.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.tanke756.top/Article/details/gt2rkhjozit.html

[B06] 遍历字典 / 对象
来源：http://dali.shuidangran.top/Article/details/gt2fckxoopn.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.wangdashe.top/Article/details/gt2trhpyilo.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.aibaodan.cn/Article/details/gt2payjiruq.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xuanzx.com/Article/details/gt2colvpila.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhoulong.xyz/Article/details/gt2xstyntlr.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.vqdsnc.cn/Article/details/gt2csrrsppq.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.guannengcc.top/Article/details/gt2ixgmfamb.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jinqigufen.top/Article/details/gt2phkqxvlp.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.xylfe.cn/Article/details/gt2dayfwnoy.html

[B07] while 循环
来源：http://dali.yuxming.cn/Article/details/gt2isjshsjp.html

Py:   while i < 10: i += 1
来源：http://dali.316326.xyz/Article/details/gt2synopvdh.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.hfpthk.cn/Article/details/gt2jgeuybma.html

JS:   while (i < 10) { i++; }
来源：http://dali.hysaishi.cn/Article/details/gt2kjkigomy.html

TS:   while (i < 10) { i++; }
来源：http://dali.ppjwa.cn/Article/details/gt2sfqogmvp.html

Java: while (i < 10) { i++; }
来源：http://dali.jqgufenzy.top/Article/details/gt2ruouarsb.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.gotoacloud.top/Article/details/gt2qijrfhhc.html

Ruby: while i < 10; i += 1; end
来源：http://dali.guannengcc.top/Article/details/gt2mcbtwxet.html

C#:   while (i < 10) { i++; }
来源：http://dali.xuanzx.com/Article/details/gt2xsqjauax.html

[B08] do-while（至少执行一次）
来源：http://dali.ppjwa.cn/Article/details/gt2jvajdlcu.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jyoumei.cn/Article/details/gt2owgmbfch.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhoulong.xyz/Article/details/gt2oievqilv.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hongshengwenyu.top/Article/details/gt2bufirsoo.html

TS:   do { i++; } while (i < 10);
来源：http://dali.cashguo.top/Article/details/gt2dhpjsohs.html

Java: do { i++; } while (i < 10);
来源：http://dali.yongpay.top/Article/details/gt2ndkqjlsx.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.sweek.top/Article/details/gt2jcimueig.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.cdnleiting.top/Article/details/gt2twyiwidx.html

C#:   do { i++; } while (i < 10);
来源：http://dali.bjfxy.top/Article/details/gt2sdsuboxs.html


<!-- 参考信息 -->