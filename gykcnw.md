代发 wailian999

[A02] 变量声明与赋值
来源：http://dali.hfpthk.cn/Article/details/gt2vxprstbp.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.hammf.cn/Article/details/gt2qzlsspix.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.gzhubu.top/Article/details/gt2jobfyzwg.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.gzhubu.top/Article/details/gt2otuwazej.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.dashuyun.cn/Article/details/gt2arfqottk.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.dashuyun.cn/Article/details/gt2ohvaneme.html

Go:   name := "Alex"; age := 20
来源：http://dali.yuanzhike.top/Article/details/gt2hntyshcv.html

Ruby: name = "Alex"; age = 20
来源：http://dali.redwolf501.top/Article/details/gt2rfieoyrb.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.nanxinkj.top/Article/details/gt2dggdimtg.html

[A03] 常量定义
来源：http://dali.hnqzz.top/Article/details/gt2pvyqwljg.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhongyouzk.top/Article/details/gt2hrmwgjmu.html

PHP:  const PI = 3.14159;
来源：http://dali.guowangkeji.top/Article/details/gt2dyzsjdqi.html

JS:   const PI = 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gt2amjpdbrk.html

TS:   const PI: number = 3.14159;
来源：http://dali.hfpthk.cn/Article/details/gt2ikjkbnpg.html

Java: static final double PI = 3.14159;
来源：http://dali.hnqzz.top/Article/details/gt2pxifltyk.html

Go:   const PI = 3.14159
来源：http://dali.nwbrower.top/Article/details/gt2csetpmti.html

Ruby: PI = 3.14159
来源：http://dali.mhx1999.top/Article/details/gt2ombzphzk.html

C#:   const double PI = 3.14159;
来源：http://dali.daxiang520.top/Article/details/gt2uujhochp.html

[A04] 判断变量类型
来源：http://dali.snrcjt.cn/Article/details/gt2jjqdcyzx.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.aizwys.cn/Article/details/gt2cwghulqk.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jqgfzy.top/Article/details/gt2bwkkalfi.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.tianlin.xyz/Article/details/gt2cibofuoz.html

TS:   typeof x; x instanceof Date
来源：http://dali.cashguo.top/Article/details/gt2fxhifafo.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.cqqwz.cn/Article/details/gt2ibbiqjvo.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.xziqi.cn/Article/details/gt2osizoopt.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.xziqi.cn/Article/details/gt2sqdckwum.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhoulong.xyz/Article/details/gt2agkznkip.html

[A05] 整数除法与取模
来源：http://dali.0kj1m.cn/Article/details/gt2pajbyrvd.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.svipenyu.cn/Article/details/gt2tuhlgkza.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yj202588.top/Article/details/gt2lmbekucb.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.gzhubu.top/Article/details/gt2eufjiowl.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yuanzhike.top/Article/details/gt2ncawphjh.html

Java: 7 / 2; 7 % 2
来源：http://dali.xylfe.cn/Article/details/gt2kbqqrvsk.html

Go:   7 / 2; 7 % 2
来源：http://dali.daria6918.cn/Article/details/gt2kmoyilgk.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.snrcjt.cn/Article/details/gt2piygdabv.html

C#:   7 / 2; 7 % 2
来源：http://dali.nwbrower.top/Article/details/gt2bskcnbyf.html

[A06] 字符串转数字
来源：http://dali.redwolf501.top/Article/details/gt2uwdfdxwn.html

Py:   int("42"); float("3.14")
来源：http://dali.sysykeji.top/Article/details/gt2sqzwrfpc.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.xziqi.cn/Article/details/gt2yxhztelc.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.svipenyu.cn/Article/details/gt2jlxqzwxe.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.yanxiufei.cn/Article/details/gt2gtfoglwg.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.andypj.xyz/Article/details/gt2nbcdcxyh.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.sxryk.cn/Article/details/gt2nldredft.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.daxiang520.top/Article/details/gt2bdnmffel.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.cheryme.top/Article/details/gt2ylldimlx.html

[A07] 数字转字符串
来源：http://dali.yvedp.cn/Article/details/gt2prskkcng.html

Py:   str(42)
来源：http://dali.zhixingplan.top/Article/details/gt2dapfnhdx.html

PHP:  (string) 42; strval(42)
来源：http://dali.kuanghao11.cn/Article/details/gt2vodbmigs.html

JS:   String(42); (42).toString()
来源：http://dali.sysykeji.top/Article/details/gt2cxrvizbe.html

TS:   String(42)
来源：http://dali.dashuyun.cn/Article/details/gt2yyxnxczv.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ytkvjivm.html

Go:   strconv.Itoa(42)
来源：http://dali.chenzaomai.com/Article/details/gt2jkzfnvlg.html

Ruby: 42.to_s
来源：http://dali.hfpthk.cn/Article/details/gt2thbpiaug.html

C#:   42.ToString()
来源：http://dali.redwolf501.top/Article/details/gt2lpaesshe.html

[A08] 取整与四舍五入
来源：http://dali.chenjidiqi.icu/Article/details/gt2yijytfjy.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.meibo888.top/Article/details/gt2sityyqbn.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.nanxinkj.top/Article/details/gt2nzljhihh.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2gftukdgf.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.shuidangran.top/Article/details/gt2huxitsqv.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.316326.xyz/Article/details/gt2iygthhxp.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.pycfn.com/Article/details/gt2lzvqgrvq.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.shangyingyoupin.top/Article/details/gt2quyfedyc.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.ppjwa.cn/Article/details/gt2pwnteyri.html

[A09] 绝对值与最大最小值
来源：http://dali.shzxlz.cn/Article/details/gt2vyzzcyrs.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.sweek.top/Article/details/gt2msrgmgol.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yangfankeji.com/Article/details/gt2ftfpwzci.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.andypj.xyz/Article/details/gt2ghcfbwvc.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.birdmap.top/Article/details/gt2gkjmocea.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zycfv.cn/Article/details/gt2twazefyk.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zycfv.cn/Article/details/gt2demanxtu.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.jqgufenzy.top/Article/details/gt2yignuolk.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.yuxming.cn/Article/details/gt2qmqwhhed.html

[A10] 生成随机数
来源：http://dali.zhixingplan.top/Article/details/gt2xyolyuqx.html

Py:   import random; random.randint(1, 100)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jgrkuvyh.html

PHP:  random_int(1, 100);
来源：http://dali.yangfankeji.com/Article/details/gt2htoswsli.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.snrcjt.cn/Article/details/gt2esvtatdn.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.feifeiyinyue.top/Article/details/gt2ewnavarq.html

Java: new Random().nextInt(100) + 1
来源：http://dali.cdnleiting.top/Article/details/gt2hfmmvkrp.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.jqgufenzy.top/Article/details/gt2pvsztlkg.html

Ruby: rand(1..100)
来源：http://dali.jianghu66.top/Article/details/gt2pkckpgtq.html

C#:   new Random().Next(1, 101)
来源：http://dali.ydzc1.top/Article/details/gt2xwruqypx.html

[A11] 条件表达式（三元）
来源：http://dali.zhengqikj.top/Article/details/gt2hyfllzbc.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.snrcjt.cn/Article/details/gt2ofqgvhuq.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.jyoumei.cn/Article/details/gt2pimvqtld.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rskmxrvd.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.gogol.net.cn/Article/details/gt2oeoacxig.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.0kj1m.cn/Article/details/gt2oeicqhji.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhongyouzk.top/Article/details/gt2vpywpbtr.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.guowangkeji.top/Article/details/gt2egwwlftd.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fmlulgss.html

[A12] 字符串插值 / 格式化
来源：http://dali.tanke756.top/Article/details/gt2ipspdwmi.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.hongshengwenyu.top/Article/details/gt2pkplllnv.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.cucudq.cn/Article/details/gt2crwxupin.html

JS:   `Hello, ${name}!`
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mzxlofio.html

TS:   `Hello, ${name}!`
来源：http://dali.yj202588.top/Article/details/gt2scpxtxko.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.yonumen.top/Article/details/gt2gkxtsqlw.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.jqgfzy.top/Article/details/gt2zhshdzhv.html

Ruby: "Hello, #{name}!"
来源：http://dali.bjfxy.top/Article/details/gt2xlqtcgon.html

C#:   $"Hello, {name}!"
来源：http://dali.yvedp.cn/Article/details/gt2asjjtwbt.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.xuetiantiany.cn/Article/details/gt2lnjtdhao.html

Py:   "第一行\n第二行"
来源：http://dali.chenzaomai.com/Article/details/gt2qjrmvaxh.html

PHP:  "第一行\n第二行"
来源：http://dali.wangshuangyany.cn/Article/details/gt2oqilzmxp.html

JS:   "第一行\n第二行"
来源：http://dali.cheryme.top/Article/details/gt2xwsvlmre.html

TS:   "第一行\n第二行"
来源：http://dali.nwbrower.top/Article/details/gt2rgfnemvd.html

Java: "第一行\n第二行"
来源：http://dali.hnxiangtu.top/Article/details/gt2omwejbma.html

Go:   "第一行\n第二行"
来源：http://dali.yuxming.cn/Article/details/gt2gwhocwyk.html

Ruby: "第一行\n第二行"
来源：http://dali.ehwqpu.com/Article/details/gt2zfhblnkd.html

C#:   "第一行\n第二行"
来源：http://dali.quarkkingdee.top/Article/details/gt2xztychbl.html

[A14] 注释写法
来源：http://dali.nanxuanxn.top/Article/details/gt2ngrjyyql.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.aibaodan.cn/Article/details/gt2enuooxfi.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.nanxinkj.top/Article/details/gt2trryavcf.html

JS:   // 单行；/* 多行 */
来源：http://dali.ppjwa.cn/Article/details/gt2xlgrwndy.html

TS:   // 单行；/* 多行 */
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gwnisitj.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.wangdashe.top/Article/details/gt2eakgmgmt.html

Go:   // 单行；/* 多行 */
来源：http://dali.chenzaomai.com/Article/details/gt2gjsdhicd.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.xuetiantiany.cn/Article/details/gt2jqqkvybi.html

C#:   // 单行；/* 多行 */
来源：http://dali.yuanzhike.top/Article/details/gt2ewhdixhc.html

[A15] 空值判断与默认值
来源：http://dali.sweek.top/Article/details/gt2jbmkdozt.html

Py:   value = data or "默认值"
来源：http://dali.ydzc1.top/Article/details/gt2yxvzhbcf.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.iojbl.cn/Article/details/gt2qkkejwza.html

JS:   const value = data ?? "默认值";
来源：http://dali.dianchejie.cn/Article/details/gt2tkkgaxar.html

TS:   const value = data ?? "默认值";
来源：http://dali.yvedp.cn/Article/details/gt2fxwqbljj.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.ydzc1.top/Article/details/gt2uruhhtnm.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.sysykeji.top/Article/details/gt2hijegnss.html

Ruby: value = data || "默认值"
来源：http://dali.yongpay.top/Article/details/gt2iwqugnbc.html

C#:   var value = data ?? "默认值";
来源：http://dali.svipenyu.cn/Article/details/gt2egsuovfd.html

[A16] 真假值判断规则
来源：http://dali.guannengcc.top/Article/details/gt2hkitkraj.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.aizwys.cn/Article/details/gt2lyfirjnn.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.yonumen.top/Article/details/gt2wtuamgmg.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.daria6918.cn/Article/details/gt2rluhbtky.html

TS:   if (!x) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2ydvqpmza.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2bvrwqqxh.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.yangfankeji.com/Article/details/gt2wwnugjib.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.pycfn.com/Article/details/gt2zpcfgdot.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.xziqi.cn/Article/details/gt2ubzsarxn.html

[A17] 位运算
来源：http://dali.yuxming.cn/Article/details/gt2cggokiig.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cucudq.cn/Article/details/gt2hltnucol.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.nwbrower.top/Article/details/gt2lcchqanf.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jlsjyb.cn/Article/details/gt2dubrmqfg.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.haohaochexian.top/Article/details/gt2afcitsay.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sufxvd.cn/Article/details/gt2qgmsmjic.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.yj20258.top/Article/details/gt2zdihvvcf.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zycfv.cn/Article/details/gt2cixrvrdt.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gaohongyu789.top/Article/details/gt2ytocngor.html

[A18] 字符与 ASCII 码互转
来源：http://dali.yuanzhike.top/Article/details/gt2nagkyzqf.html

Py:   ord("A"); chr(65)
来源：http://dali.cheryme.top/Article/details/gt2otivxvnv.html

PHP:  ord("A"); chr(65)
来源：http://dali.jinqigfzy.top/Article/details/gt2rrgmtqmz.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.sweek.top/Article/details/gt2grkdjyuv.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.pengpengdd.cyou/Article/details/gt2cuinwqvw.html

Java: (int) 'A'; (char) 65
来源：http://dali.chenjidiqi.icu/Article/details/gt2rwmelosa.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.hfpthk.cn/Article/details/gt2iygybnxd.html

Ruby: "A".ord; 65.chr
来源：http://dali.xziqi.cn/Article/details/gt2pxijxvlm.html

C#:   (int)'A'; (char)65
来源：http://dali.tian-w.cn/Article/details/gt2ifwpxwuh.html

[A19] 交换两个变量
来源：http://dali.snrcjt.cn/Article/details/gt2yzuufhks.html

Py:   a, b = b, a
来源：http://dali.xylfe.cn/Article/details/gt2eqihheyj.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.zdqjudy.top/Article/details/gt2pbvnuarw.html

JS:   [a, b] = [b, a];
来源：http://dali.sysykeji.top/Article/details/gt2hshydhzw.html

TS:   [a, b] = [b, a];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dbhpngey.html

Java: int t = a; a = b; b = t;
来源：http://dali.ybcxt.top/Article/details/gt2ykwlfvgn.html

Go:   a, b = b, a
来源：http://dali.hongshengwenyu.top/Article/details/gt2gkcghdgi.html

Ruby: a, b = b, a
来源：http://dali.bjfxy.top/Article/details/gt2gdabrwsw.html

C#:   (a, b) = (b, a);
来源：http://dali.sxryk.cn/Article/details/gt2iobpusjx.html

[A20] 读取标准输入
来源：http://dali.jinqigfzy.top/Article/details/gt2kqlqqkou.html

Py:   name = input("请输入：")
来源：http://dali.ivvv.top/Article/details/gt2oziccjbg.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.birdmap.top/Article/details/gt2ijuhlpeh.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.xziqi.cn/Article/details/gt2psiqczda.html

TS:   // Node.js：readline 模块
来源：http://dali.ehwqpu.com/Article/details/gt2xqiifgok.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.meibo888.top/Article/details/gt2zvjgchsw.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.yongpay.top/Article/details/gt2nbdopiyy.html

Ruby: gets.chomp
来源：http://dali.xuetiantiany.cn/Article/details/gt2lzdtipsp.html

C#:   Console.ReadLine();
来源：http://dali.yj20258888.top/Article/details/gt2rkdbcvph.html

[A21] 保留指定小数位输出
来源：http://dali.havefunace.top/Article/details/gt2ihoiebdk.html

Py:   f"{3.14159:.2f}"
来源：http://dali.ppjwa.cn/Article/details/gt2dgbhcwkm.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.aibaodan.cn/Article/details/gt2fikvylzi.html

JS:   (3.14159).toFixed(2)
来源：http://dali.yongpay.top/Article/details/gt2tedlnewa.html

TS:   (3.14159).toFixed(2)
来源：http://dali.zhoulong.xyz/Article/details/gt2dboflhhh.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.ehwqpu.com/Article/details/gt2gdatjmqz.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.cqqwz.cn/Article/details/gt2jewlmips.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.jlsjyb.cn/Article/details/gt2cxdszckc.html

C#:   3.14159.ToString("F2")
来源：http://dali.jianghu66.top/Article/details/gt2hiyhixld.html

[A22] 获取字符串长度
来源：http://dali.kuanghao11.cn/Article/details/gt2yikoliuo.html

Py:   len(s)
来源：http://dali.yongpay.top/Article/details/gt2byqunstw.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.xylfe.cn/Article/details/gt2zynhubmw.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.dashuyun.cn/Article/details/gt2eptujpkb.html

TS:   s.length
来源：http://dali.tanke756.top/Article/details/gt2axpplrmo.html

Java: s.length()
来源：http://dali.cdnleiting.top/Article/details/gt2kunmqpyb.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2vdlhnvez.html

Ruby: s.length
来源：http://dali.mhx1999.top/Article/details/gt2tiduxcld.html

C#:   s.Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2axfisrdi.html

[A23] 大小写转换
来源：http://dali.jqgfzy.top/Article/details/gt2eepsvssw.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.tianlin.xyz/Article/details/gt2tfhjlfac.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.zhijiandao.cn/Article/details/gt2onwnjqjr.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhixingplan.top/Article/details/gt2bckstapg.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.meibo888.top/Article/details/gt2dsrpmobn.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.gzhubu.top/Article/details/gt2wpejchfl.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.hfpthk.cn/Article/details/gt2okqvlhui.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.hammf.cn/Article/details/gt2vellyxpd.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.ydzc1.top/Article/details/gt2huqmdunt.html

[A24] 去除首尾空白
来源：http://dali.zhongyouzk.top/Article/details/gt2qrtmprnn.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.chenjidiqi.icu/Article/details/gt2ocwutmsr.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.kuanghao11.cn/Article/details/gt2rlddzqaz.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.birdmap.top/Article/details/gt2bvtnlopi.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vmdkrykc.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.sysykeji.top/Article/details/gt2eetjxsul.html

Go:   strings.TrimSpace(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2bqreksvu.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.daxiang520.top/Article/details/gt2ipxpuiyo.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jyoumei.cn/Article/details/gt2vvnpkzig.html

[A25] 字符串比较
来源：http://dali.zhengqikj.top/Article/details/gt2ekhkkmex.html

Py:   s1 == s2; s1 != s2
来源：http://dali.haohaochexian.top/Article/details/gt2iopyqlto.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.zhixingplan.top/Article/details/gt2xneblzru.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.0kj1m.cn/Article/details/gt2pekgtrrm.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.cqqwz.cn/Article/details/gt2nryzhhkj.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.shzxlz.cn/Article/details/gt2ucvhofvu.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.gzhubu.top/Article/details/gt2rhmeexvu.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.zhiwuduotai.top/Article/details/gt2pkqrwpyz.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.sxryk.cn/Article/details/gt2vthcapvg.html

[A26] 类型转换总览
来源：http://dali.dashuyun.cn/Article/details/gt2dqrbzsoq.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.svipenyu.cn/Article/details/gt2hnuracdg.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.ivvv.top/Article/details/gt2qlphdvuf.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jqgfzy.top/Article/details/gt2zrykxnpq.html

TS:   Number() String() Boolean() x as number
来源：http://dali.feifeiyinyue.top/Article/details/gt2kxzbmlop.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.kuanghao11.cn/Article/details/gt2wwomytua.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.daxiang520.top/Article/details/gt2igjxrwhi.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yonumen.top/Article/details/gt2zqfdwcxg.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.ppjwa.cn/Article/details/gt2gekqnfte.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2ywlghrii.html

B. 流程控制
来源：http://dali.zdqjudy.top/Article/details/gt2taceprjt.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2oynzkvgu.html

[B01] 条件判断 if / else
来源：http://dali.guowangkeji.top/Article/details/gt2mczncmgj.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.gaohongyu789.top/Article/details/gt2suoywpiz.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.meibo888.top/Article/details/gt2webkiqpf.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yuanzhike.top/Article/details/gt2sivwkjas.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dhtaerrq.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.iojbl.cn/Article/details/gt2sfxgrmgo.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.ydzc1.top/Article/details/gt2nnpwzysq.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.daria6918.cn/Article/details/gt2wdcolhpz.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.cashguo.top/Article/details/gt2oxtydzuc.html

[B02] 多分支 else if / elif
来源：http://dali.sxryk.cn/Article/details/gt2aywmtcwv.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.xuetiantiany.cn/Article/details/gt2iybxwulx.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2awxmyjlv.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yongpay.top/Article/details/gt2qlmhqpep.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ppjwa.cn/Article/details/gt2uszgjbge.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.316326.xyz/Article/details/gt2vvojuxtf.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.zycfv.cn/Article/details/gt2lpytdoug.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.birdmap.top/Article/details/gt2rgcghmjn.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.dashuyun.cn/Article/details/gt2tvprlpkp.html

[B03] switch / match / case
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kyvavzeu.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.c1oappe.top/Article/details/gt2ljruvram.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.jyoumei.cn/Article/details/gt2zzvwlckc.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2pqenikpg.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zycfv.cn/Article/details/gt2mftldbkl.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.haohaochexian.top/Article/details/gt2jlgkbwot.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.zhoulong.xyz/Article/details/gt2ktstyadf.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.shuidangran.top/Article/details/gt2gosdfxiy.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jqgufenzy.top/Article/details/gt2vcfustiz.html

[B04] for 计数循环
来源：http://dali.yuxming.cn/Article/details/gt2qidddabf.html

Py:   for i in range(10): print(i)
来源：http://dali.yangfankeji.com/Article/details/gt2haauyywm.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.9152youxi.cn/Article/details/gt2owsbqdiu.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.sweek.top/Article/details/gt2vsvkpefe.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jlsjyb.cn/Article/details/gt2lfcchxek.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.xziqi.cn/Article/details/gt2dwgquqii.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.hfpthk.cn/Article/details/gt2sldzbvuw.html

Ruby: 10.times { |i| puts i }
来源：http://dali.cashguo.top/Article/details/gt2zezpvzwz.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.havefunace.top/Article/details/gt2ojernxll.html

[B05] 遍历数组 / 列表
来源：http://dali.hammf.cn/Article/details/gt2nnsazixw.html

Py:   for item in arr: print(item)
来源：http://dali.shuidangran.top/Article/details/gt2uwmvjvfv.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yangfankeji.com/Article/details/gt2sxugwkts.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qrnlqlsy.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2cusjgawq.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jqgufenzy.top/Article/details/gt2omtvabwj.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.wangdashe.top/Article/details/gt2dwwiavkl.html

Ruby: arr.each { |item| puts item }
来源：http://dali.gzhubu.top/Article/details/gt2wiiidkpw.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zdqjudy.top/Article/details/gt2clsnscmi.html

[B06] 遍历字典 / 对象
来源：http://dali.ppjwa.cn/Article/details/gt2hggwboxh.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yj20258.top/Article/details/gt2jyxxzfrf.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.ppjwa.cn/Article/details/gt2uumjnzcp.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jianghu66.top/Article/details/gt2trvsuawl.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.sweek.top/Article/details/gt2pxaidmpr.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.hnxiangtu.top/Article/details/gt2xjpuzcok.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zdqjudy.top/Article/details/gt2vbcznllk.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.hnxiangtu.top/Article/details/gt2bvumbskw.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ulzylvte.html

[B07] while 循环
来源：http://dali.birdmap.top/Article/details/gt2pucnoobe.html

Py:   while i < 10: i += 1
来源：http://dali.xziqi.cn/Article/details/gt2xihmdllo.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.ppjwa.cn/Article/details/gt2egtayhjt.html

JS:   while (i < 10) { i++; }
来源：http://dali.jinqigufen.top/Article/details/gt2qlrjiljg.html

TS:   while (i < 10) { i++; }
来源：http://dali.haohaochexian.top/Article/details/gt2gccqdjcm.html

Java: while (i < 10) { i++; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2yvmfikza.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.chenzaomai.com/Article/details/gt2kjhvrumg.html

Ruby: while i < 10; i += 1; end
来源：http://dali.316326.xyz/Article/details/gt2khfjozcq.html

C#:   while (i < 10) { i++; }
来源：http://dali.gogol.net.cn/Article/details/gt2svikjpvv.html

[B08] do-while（至少执行一次）
来源：http://dali.hnxiangtu.top/Article/details/gt2uplergwt.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jianghu66.top/Article/details/gt2xxyqalvw.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.cqqwz.cn/Article/details/gt2zruuwnjz.html

JS:   do { i++; } while (i < 10);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qsfovonr.html

TS:   do { i++; } while (i < 10);
来源：http://dali.kuanghao11.cn/Article/details/gt2oipqczyj.html

Java: do { i++; } while (i < 10);
来源：http://dali.hnqzz.top/Article/details/gt2lyorxchv.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.haohaochexian.top/Article/details/gt2gqdyxxdo.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.xinyue.icu/Article/details/gt2xavnglbl.html

C#:   do { i++; } while (i < 10);
来源：http://dali.haohaochexian.top/Article/details/gt2hqlzspef.html


<!-- 参考信息 -->