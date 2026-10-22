代发 wailian999

[A02] 变量声明与赋值
来源：http://dali.jyoumei.cn/Article/details/gt2etfjnuzz.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yueranfly.top/Article/details/gt2tgsnlaro.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.smart0.xyz/Article/details/gt2plmlwzgp.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.jinqigfzy.top/Article/details/gt2gfgyuroj.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.daria6918.cn/Article/details/gt2ctlpidlo.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.sweek.top/Article/details/gt2jerbyyno.html

Go:   name := "Alex"; age := 20
来源：http://dali.pengpengdd.cyou/Article/details/gt2uzqmjdbd.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yanxiufei.cn/Article/details/gt2nabivbwr.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.xinyue.icu/Article/details/gt2stsukklh.html

[A03] 常量定义
来源：http://dali.sxryk.cn/Article/details/gt2aujbkocp.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yddvzftd.html

PHP:  const PI = 3.14159;
来源：http://dali.sysykeji.top/Article/details/gt2uskryakd.html

JS:   const PI = 3.14159;
来源：http://dali.yj20258888.top/Article/details/gt2gkpiesgj.html

TS:   const PI: number = 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gt2adjxuoyy.html

Java: static final double PI = 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2daszilsu.html

Go:   const PI = 3.14159
来源：http://dali.yj20258888.top/Article/details/gt2tozfjopo.html

Ruby: PI = 3.14159
来源：http://dali.ppjwa.cn/Article/details/gt2pkleaigv.html

C#:   const double PI = 3.14159;
来源：http://dali.tanke756.top/Article/details/gt2avksizzx.html

[A04] 判断变量类型
来源：http://dali.sysykeji.top/Article/details/gt2jzlfevsf.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.fengsongda.top/Article/details/gt2qrrgdogg.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.sufxvd.cn/Article/details/gt2lqliaqhy.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.shzxlz.cn/Article/details/gt2ebhntiww.html

TS:   typeof x; x instanceof Date
来源：http://dali.pengpengdd.cyou/Article/details/gt2eishpzdk.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.hnxiangtu.top/Article/details/gt2enairlbw.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.chenjidiqi.icu/Article/details/gt2fsvhjqbq.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.fzhhl.top/Article/details/gt2jwbdqifa.html

C#:   x.GetType().Name; x is int
来源：http://dali.sxryk.cn/Article/details/gt2nxsvewsv.html

[A05] 整数除法与取模
来源：http://dali.gotoacloud.top/Article/details/gt2qjzwxvxm.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.hongshengwenyu.top/Article/details/gt2qimlugxl.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.pycfn.com/Article/details/gt2potrnhrp.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vtgvlacb.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.iojbl.cn/Article/details/gt2jnodhhju.html

Java: 7 / 2; 7 % 2
来源：http://dali.yonumen.top/Article/details/gt2gixsbbgx.html

Go:   7 / 2; 7 % 2
来源：http://dali.jinqigufen.top/Article/details/gt2egtgyeyj.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.0kj1m.cn/Article/details/gt2yqswvlop.html

C#:   7 / 2; 7 % 2
来源：http://dali.ppjwa.cn/Article/details/gt2jiqkhzgf.html

[A06] 字符串转数字
来源：http://dali.nwbrower.top/Article/details/gt2qjgemggy.html

Py:   int("42"); float("3.14")
来源：http://dali.nanxuanxn.top/Article/details/gt2cutdyntw.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.cashguo.top/Article/details/gt2qrpsmxhm.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.jqgfzy.top/Article/details/gt2qnalfjeg.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.hfpthk.cn/Article/details/gt2xubuatvp.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhongyouzk.top/Article/details/gt2lekjquyk.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.havefunace.top/Article/details/gt2cpjmwpux.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yangfankeji.com/Article/details/gt2ilgctdqn.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.hongshengwenyu.top/Article/details/gt2aqawgqto.html

[A07] 数字转字符串
来源：http://dali.iojbl.cn/Article/details/gt2cbwtzgxy.html

Py:   str(42)
来源：http://dali.fengsongda.top/Article/details/gt2lbviclzw.html

PHP:  (string) 42; strval(42)
来源：http://dali.wangdashe.top/Article/details/gt2jbgrhlwq.html

JS:   String(42); (42).toString()
来源：http://dali.xuanzx.com/Article/details/gt2lfypaudv.html

TS:   String(42)
来源：http://dali.chenlongwang.top/Article/details/gt2rlzwwxtn.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.dianchejie.cn/Article/details/gt2xkphoxli.html

Go:   strconv.Itoa(42)
来源：http://dali.shzxlz.cn/Article/details/gt2zvllibwq.html

Ruby: 42.to_s
来源：http://dali.jiagoushi.top/Article/details/gt2mwwibqsm.html

C#:   42.ToString()
来源：http://dali.jqgfzy.top/Article/details/gt2zisyejay.html

[A08] 取整与四舍五入
来源：http://dali.ppjwa.cn/Article/details/gt2gvqfgczy.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhiwuduotai.top/Article/details/gt2nslrtajr.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.tian-w.cn/Article/details/gt2agrjbtor.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.dianchejie.cn/Article/details/gt2wauedctt.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.sysykeji.top/Article/details/gt2owvasnqh.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.chenlongwang.top/Article/details/gt2eyywlnik.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.hnqzz.top/Article/details/gt2hougwtoi.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.ppjwa.cn/Article/details/gt2sjdlyxmd.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.svipenyu.cn/Article/details/gt2kcbwixme.html

[A09] 绝对值与最大最小值
来源：http://dali.meibo888.top/Article/details/gt2epnvwwnp.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.vqdsnc.cn/Article/details/gt2jdibcxtp.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.sysykeji.top/Article/details/gt2pwvpfnfb.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.daria6918.cn/Article/details/gt2ufmrkyfe.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.yvedp.cn/Article/details/gt2xnogzuws.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rlyacfft.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.c1oappe.top/Article/details/gt2edbqfdxj.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.hnxiangtu.top/Article/details/gt2rsicypcb.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.c1oappe.top/Article/details/gt2vaktafhn.html

[A10] 生成随机数
来源：http://dali.guannengcc.top/Article/details/gt2fzibuggb.html

Py:   import random; random.randint(1, 100)
来源：http://dali.xuanzx.com/Article/details/gt2supnqqxp.html

PHP:  random_int(1, 100);
来源：http://dali.fzhhl.top/Article/details/gt2typhjybb.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.mhx1999.top/Article/details/gt2tqwdfprh.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.xylfe.cn/Article/details/gt2zpqxiyys.html

Java: new Random().nextInt(100) + 1
来源：http://dali.sysykeji.top/Article/details/gt2haaqzfeu.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.shangyingyoupin.top/Article/details/gt2ufqtpamc.html

Ruby: rand(1..100)
来源：http://dali.xinyue.icu/Article/details/gt2nblblvkm.html

C#:   new Random().Next(1, 101)
来源：http://dali.dianchejie.cn/Article/details/gt2irqgqqkr.html

[A11] 条件表达式（三元）
来源：http://dali.xziqi.cn/Article/details/gt2wbnvyiaa.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.birdmap.top/Article/details/gt2kipzjlcb.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zdqjudy.top/Article/details/gt2bavixgrh.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zdqjudy.top/Article/details/gt2ortlitju.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.nwbrower.top/Article/details/gt2foqmgnov.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.xuanzx.com/Article/details/gt2krxlxywv.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.jlsjyb.cn/Article/details/gt2xhowwzmk.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.sysykeji.top/Article/details/gt2ekglygvl.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ouwbssqi.html

[A12] 字符串插值 / 格式化
来源：http://dali.ivvv.top/Article/details/gt2jegigazv.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.birdmap.top/Article/details/gt2ltxgixij.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.shangyingyoupin.top/Article/details/gt2pjqcbxit.html

JS:   `Hello, ${name}!`
来源：http://dali.fzhhl.top/Article/details/gt2tyjoovla.html

TS:   `Hello, ${name}!`
来源：http://dali.cqqwz.cn/Article/details/gt2czulemvo.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.wangshuangyany.cn/Article/details/gt2porkrhpn.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.c1oappe.top/Article/details/gt2yseoclck.html

Ruby: "Hello, #{name}!"
来源：http://dali.9152youxi.cn/Article/details/gt2qbkqdtzr.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvsctvv.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2hffotdgq.html

Py:   "第一行\n第二行"
来源：http://dali.zhixingplan.top/Article/details/gt2opaebmxu.html

PHP:  "第一行\n第二行"
来源：http://dali.chenzaomai.com/Article/details/gt2trcucnwe.html

JS:   "第一行\n第二行"
来源：http://dali.havefunace.top/Article/details/gt2hdlshsmy.html

TS:   "第一行\n第二行"
来源：http://dali.chenzaomai.com/Article/details/gt2ngxdvzka.html

Java: "第一行\n第二行"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jcdppumr.html

Go:   "第一行\n第二行"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2reuvcmfr.html

Ruby: "第一行\n第二行"
来源：http://dali.yongpay.top/Article/details/gt2ylmntqsg.html

C#:   "第一行\n第二行"
来源：http://dali.fzhhl.top/Article/details/gt2tcauiuwj.html

[A14] 注释写法
来源：http://dali.xuanzx.com/Article/details/gt2qkhihlck.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.ehwqpu.com/Article/details/gt2gawomxbe.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.tianlin.xyz/Article/details/gt2zyuomrep.html

JS:   // 单行；/* 多行 */
来源：http://dali.c1oappe.top/Article/details/gt2hskdrjfn.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhongyouzk.top/Article/details/gt2buywtufv.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.dashuyun.cn/Article/details/gt2kqtytoqs.html

Go:   // 单行；/* 多行 */
来源：http://dali.yanxiufei.cn/Article/details/gt2apelvcgv.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.xziqi.cn/Article/details/gt2bjtrfbat.html

C#:   // 单行；/* 多行 */
来源：http://dali.chenlongwang.top/Article/details/gt2ibhjsrlh.html

[A15] 空值判断与默认值
来源：http://dali.pycfn.com/Article/details/gt2dqybmxgc.html

Py:   value = data or "默认值"
来源：http://dali.redwolf501.top/Article/details/gt2qystigla.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.hnxiangtu.top/Article/details/gt2tbvltavw.html

JS:   const value = data ?? "默认值";
来源：http://dali.sufxvd.cn/Article/details/gt2gxyqsfkg.html

TS:   const value = data ?? "默认值";
来源：http://dali.gogol.net.cn/Article/details/gt2wgwlqgkq.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.cdnleiting.top/Article/details/gt2pczgrhes.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.feifeiyinyue.top/Article/details/gt2dcmicphe.html

Ruby: value = data || "默认值"
来源：http://dali.fengsongda.top/Article/details/gt2iygrglfx.html

C#:   var value = data ?? "默认值";
来源：http://dali.vqdsnc.cn/Article/details/gt2rmuoikqw.html

[A16] 真假值判断规则
来源：http://dali.cashguo.top/Article/details/gt2rqbebatf.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.pycfn.com/Article/details/gt2xrhyhqeh.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.cdnleiting.top/Article/details/gt2zmdoyicw.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.yueranfly.top/Article/details/gt2otcgnprk.html

TS:   if (!x) {}
来源：http://dali.ybcxt.top/Article/details/gt2eccqzzwq.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2avecyrxx.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.meibo888.top/Article/details/gt2klnhoxiu.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.smart0.xyz/Article/details/gt2novuuvxg.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2rkapiggz.html

[A17] 位运算
来源：http://dali.daxiang520.top/Article/details/gt2yafivfmv.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shzxlz.cn/Article/details/gt2vfcmdvss.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.yanxiufei.cn/Article/details/gt2lwrnhjoh.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jyoumei.cn/Article/details/gt2yfdbvufw.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.yanxiufei.cn/Article/details/gt2mbwjwpjp.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.guowangkeji.top/Article/details/gt2ambhsbgi.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.jinqigfzy.top/Article/details/gt2qvtemxip.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tian-w.cn/Article/details/gt2ugpsqccl.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yuxming.cn/Article/details/gt2loajpqpp.html

[A18] 字符与 ASCII 码互转
来源：http://dali.dianchejie.cn/Article/details/gt2ccuzwfvy.html

Py:   ord("A"); chr(65)
来源：http://dali.nanxuanxn.top/Article/details/gt2ciezkcku.html

PHP:  ord("A"); chr(65)
来源：http://dali.yongpay.top/Article/details/gt2mxjxxzqa.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.wangdashe.top/Article/details/gt2ugftnqjf.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.cheryme.top/Article/details/gt2nupskcxw.html

Java: (int) 'A'; (char) 65
来源：http://dali.hfpthk.cn/Article/details/gt2zlmgsojj.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.0kj1m.cn/Article/details/gt2lwbewhce.html

Ruby: "A".ord; 65.chr
来源：http://dali.yanxiufei.cn/Article/details/gt2lnxxtyyo.html

C#:   (int)'A'; (char)65
来源：http://dali.fengsongda.top/Article/details/gt2vnzkavsq.html

[A19] 交换两个变量
来源：http://dali.zhiwuduotai.top/Article/details/gt2vjvtmgzk.html

Py:   a, b = b, a
来源：http://dali.jyoumei.cn/Article/details/gt2lrgpduuc.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.quarkkingdee.top/Article/details/gt2ewulnwkh.html

JS:   [a, b] = [b, a];
来源：http://dali.zhixingplan.top/Article/details/gt2guzzdmxh.html

TS:   [a, b] = [b, a];
来源：http://dali.hnxiangtu.top/Article/details/gt2mwoskzom.html

Java: int t = a; a = b; b = t;
来源：http://dali.shuidangran.top/Article/details/gt2tovzkbjy.html

Go:   a, b = b, a
来源：http://dali.dashuyun.cn/Article/details/gt2dpeavhag.html

Ruby: a, b = b, a
来源：http://dali.zdqjudy.top/Article/details/gt2zhptspaa.html

C#:   (a, b) = (b, a);
来源：http://dali.gzhubu.top/Article/details/gt2odnmslcg.html

[A20] 读取标准输入
来源：http://dali.sufxvd.cn/Article/details/gt2xlufqjka.html

Py:   name = input("请输入：")
来源：http://dali.birdmap.top/Article/details/gt2brtvayjr.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.sufxvd.cn/Article/details/gt2kvbqxvob.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.cucudq.cn/Article/details/gt2yhjkbarv.html

TS:   // Node.js：readline 模块
来源：http://dali.hywenlv.cn/Article/details/gt2qooetvgw.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.andypj.xyz/Article/details/gt2rimdnahr.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.havefunace.top/Article/details/gt2kkxjktxd.html

Ruby: gets.chomp
来源：http://dali.hfpthk.cn/Article/details/gt2fhxhlbyi.html

C#:   Console.ReadLine();
来源：http://dali.fengsongda.top/Article/details/gt2gdmqiwbf.html

[A21] 保留指定小数位输出
来源：http://dali.zhoulong.xyz/Article/details/gt2jsrlcocq.html

Py:   f"{3.14159:.2f}"
来源：http://dali.dashuyun.cn/Article/details/gt2ipbseoux.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.chenjidiqi.icu/Article/details/gt2stenbbag.html

JS:   (3.14159).toFixed(2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2apwkyfag.html

TS:   (3.14159).toFixed(2)
来源：http://dali.0kj1m.cn/Article/details/gt2evyicgnv.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.yuxming.cn/Article/details/gt2urmpozja.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.hysaishi.cn/Article/details/gt2hyifeibz.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qrlbppgm.html

C#:   3.14159.ToString("F2")
来源：http://dali.redwolf501.top/Article/details/gt2focfjezp.html

[A22] 获取字符串长度
来源：http://dali.pengpengdd.cyou/Article/details/gt2xefoires.html

Py:   len(s)
来源：http://dali.ydzc1.top/Article/details/gt2emqmtczg.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.0kj1m.cn/Article/details/gt2jmwbqcke.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.fzhhl.top/Article/details/gt2wkqpwzpi.html

TS:   s.length
来源：http://dali.dashuyun.cn/Article/details/gt2fgqjzekl.html

Java: s.length()
来源：http://dali.jinqigfzy.top/Article/details/gt2hstubcnr.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.tanke756.top/Article/details/gt2mdbvgbmv.html

Ruby: s.length
来源：http://dali.jinqigfzy.top/Article/details/gt2sjsgtzqg.html

C#:   s.Length
来源：http://dali.snrcjt.cn/Article/details/gt2amwhooaf.html

[A23] 大小写转换
来源：http://dali.zhongyouzk.top/Article/details/gt2gxcuidgs.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.jianghu66.top/Article/details/gt2qxxqaysb.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.ivvv.top/Article/details/gt2svpalfxz.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.feifeiyinyue.top/Article/details/gt2elieedye.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.hysaishi.cn/Article/details/gt2hhkpoved.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.jlsjyb.cn/Article/details/gt2xhlvbrgn.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.sxryk.cn/Article/details/gt2jipbhgfk.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.shangyingyoupin.top/Article/details/gt2lhqdzhky.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.xuanzx.com/Article/details/gt2utyjptcg.html

[A24] 去除首尾空白
来源：http://dali.dashuyun.cn/Article/details/gt2owqcqfom.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.feifeiyinyue.top/Article/details/gt2zvxhisrv.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.iojbl.cn/Article/details/gt2crhvacan.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.nwbrower.top/Article/details/gt2scfnxdae.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hnxiangtu.top/Article/details/gt2ctwdhjwt.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.yuanzhike.top/Article/details/gt2djaugkmi.html

Go:   strings.TrimSpace(s)
来源：http://dali.mhx1999.top/Article/details/gt2bqgwjadc.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yonumen.top/Article/details/gt2hduqvlcv.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.zhoulong.xyz/Article/details/gt2edasligh.html

[A25] 字符串比较
来源：http://dali.hongshengwenyu.top/Article/details/gt2qujmiwqq.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yongpay.top/Article/details/gt2ioyfjnqa.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.cqqwz.cn/Article/details/gt2ktcbmjgq.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.cheryme.top/Article/details/gt2jipdvkdv.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jiagoushi.top/Article/details/gt2jztoooxo.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.zhoulong.xyz/Article/details/gt2sksyoyyz.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lduldcoo.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.yj202588.top/Article/details/gt2wkpyvjvq.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.kuanghao11.cn/Article/details/gt2ktbmeuuw.html

[A26] 类型转换总览
来源：http://dali.ehwqpu.com/Article/details/gt2llcxnhps.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.chenjidiqi.icu/Article/details/gt2pacahwxf.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bqdkslxn.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.andypj.xyz/Article/details/gt2cezwljpv.html

TS:   Number() String() Boolean() x as number
来源：http://dali.gogol.net.cn/Article/details/gt2ljtewxqi.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.xuetiantiany.cn/Article/details/gt2afafckyr.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.aizwys.cn/Article/details/gt2nnjkoqek.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.fengsongda.top/Article/details/gt2vwmzfbez.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.haohaochexian.top/Article/details/gt2ylcxqmtj.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2bynigvlq.html

B. 流程控制
来源：http://dali.pycfn.com/Article/details/gt2kwqrpaxx.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2auxscovm.html

[B01] 条件判断 if / else
来源：http://dali.chenlongwang.top/Article/details/gt2qrwxqpsk.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.tian-w.cn/Article/details/gt2autwpska.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.shuidangran.top/Article/details/gt2rlzhdeao.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ehwqpu.com/Article/details/gt2eplsosuj.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.bjfxy.top/Article/details/gt2emgfcxhb.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.cqqwz.cn/Article/details/gt2cqqnahzz.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.zdqjudy.top/Article/details/gt2snvptkiv.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.sweek.top/Article/details/gt2cgddxznt.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.guowangkeji.top/Article/details/gt2fhexxyuk.html

[B02] 多分支 else if / elif
来源：http://dali.bjfxy.top/Article/details/gt2locyognm.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.shzxlz.cn/Article/details/gt2wfxzlrwk.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.birdmap.top/Article/details/gt2fcqmjlzc.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.redwolf501.top/Article/details/gt2mmlmafht.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shangyingyoupin.top/Article/details/gt2fvsstovt.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ydzc1.top/Article/details/gt2nrxdtdhz.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.sweek.top/Article/details/gt2iclrazhd.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.hfpthk.cn/Article/details/gt2xvbpcxro.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yonumen.top/Article/details/gt2ozejlyzp.html

[B03] switch / match / case
来源：http://dali.0kj1m.cn/Article/details/gt2hjdtktrr.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.smart0.xyz/Article/details/gt2qxppgeex.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.xinyue.icu/Article/details/gt2rcfxrpou.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.chenzaomai.com/Article/details/gt2jsbbnipu.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yvedp.cn/Article/details/gt2sagojdwk.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2adjxpexd.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.shzxlz.cn/Article/details/gt2gwncnsan.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.zhengqikj.top/Article/details/gt2qumhmtvd.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ogiylzer.html

[B04] for 计数循环
来源：http://dali.xuetiantiany.cn/Article/details/gt2vwyjklcw.html

Py:   for i in range(10): print(i)
来源：http://dali.quarkkingdee.top/Article/details/gt2llaquifh.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.316326.xyz/Article/details/gt2rvekjcho.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xinyue.icu/Article/details/gt2ixmgghdf.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.smart0.xyz/Article/details/gt2hozfpgli.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yueranfly.top/Article/details/gt2bcwdeisg.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.andypj.xyz/Article/details/gt2jttdlcei.html

Ruby: 10.times { |i| puts i }
来源：http://dali.jyoumei.cn/Article/details/gt2uscbfksz.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2dlxcvios.html

[B05] 遍历数组 / 列表
来源：http://dali.jqgufenzy.top/Article/details/gt2kdtvkuli.html

Py:   for item in arr: print(item)
来源：http://dali.xziqi.cn/Article/details/gt2dlhcvmsd.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ygvgpzap.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2oaolqizz.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.ivvv.top/Article/details/gt2ulvxwrua.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hysaishi.cn/Article/details/gt2wpdbeuot.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.smart0.xyz/Article/details/gt2tauilvcb.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yj202588.top/Article/details/gt2lvlfukzo.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jyoumei.cn/Article/details/gt2qfofebjy.html

[B06] 遍历字典 / 对象
来源：http://dali.jqgufenzy.top/Article/details/gt2qfvxbdob.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.shangyingyoupin.top/Article/details/gt2lkrdcvhc.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.svipenyu.cn/Article/details/gt2qfonzweo.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yj20258888.top/Article/details/gt2dboaoppt.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gotoacloud.top/Article/details/gt2hxsytjbe.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2znfyrlmd.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.ivvv.top/Article/details/gt2eefielbq.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.kuanghao11.cn/Article/details/gt2mcybbsks.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.sufxvd.cn/Article/details/gt2jpyzucoi.html

[B07] while 循环
来源：http://dali.zhengqikj.top/Article/details/gt2pveciveo.html

Py:   while i < 10: i += 1
来源：http://dali.9152youxi.cn/Article/details/gt2qmrralbh.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.ybcxt.top/Article/details/gt2fyypyoex.html

JS:   while (i < 10) { i++; }
来源：http://dali.snrcjt.cn/Article/details/gt2ofvaexrx.html

TS:   while (i < 10) { i++; }
来源：http://dali.pycfn.com/Article/details/gt2wskhuewz.html

Java: while (i < 10) { i++; }
来源：http://dali.shuidangran.top/Article/details/gt2ornczeaf.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.kuanghao11.cn/Article/details/gt2zcmxbtxm.html

Ruby: while i < 10; i += 1; end
来源：http://dali.ppjwa.cn/Article/details/gt2igesbfpc.html

C#:   while (i < 10) { i++; }
来源：http://dali.fengsongda.top/Article/details/gt2fwcqtnmj.html

[B08] do-while（至少执行一次）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fmnvzjrr.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.xziqi.cn/Article/details/gt2adorhvqp.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.hnqzz.top/Article/details/gt2qrexnmkh.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yanxiufei.cn/Article/details/gt2wybjjevf.html

TS:   do { i++; } while (i < 10);
来源：http://dali.tian-w.cn/Article/details/gt2piwvngzc.html

Java: do { i++; } while (i < 10);
来源：http://dali.guannengcc.top/Article/details/gt2hbwvdnuq.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.meibo888.top/Article/details/gt2covdgpbt.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.shangyingyoupin.top/Article/details/gt2iorfujaz.html

C#:   do { i++; } while (i < 10);
来源：http://dali.daria6918.cn/Article/details/gt2vvwuqyrr.html


<!-- 参考信息 -->