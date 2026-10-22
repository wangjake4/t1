代发 wailian999

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.dianchejie.cn/Article/details/gt2znwmxjal.html

[A07] 数字转字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2hyypzgbu.html

Py:   str(42)
来源：http://dali.kuanghao11.cn/Article/details/gt2yuyfrsbp.html

PHP:  (string) 42; strval(42)
来源：http://dali.tianlin.xyz/Article/details/gt2vubaivcw.html

JS:   String(42); (42).toString()
来源：http://dali.gotoacloud.top/Article/details/gt2mznmgagq.html

TS:   String(42)
来源：http://dali.hnxiangtu.top/Article/details/gt2qjocxlgo.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.dianchejie.cn/Article/details/gt2evaozovt.html

Go:   strconv.Itoa(42)
来源：http://dali.meibo888.top/Article/details/gt2jvsrvduc.html

Ruby: 42.to_s
来源：http://dali.mhx1999.top/Article/details/gt2sysmuefh.html

C#:   42.ToString()
来源：http://dali.bjfxy.top/Article/details/gt2fdjsgvih.html

[A08] 取整与四舍五入
来源：http://dali.tianlin.xyz/Article/details/gt2ezmnaagn.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.gotoacloud.top/Article/details/gt2srkyugxm.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.yj202588.top/Article/details/gt2kwtjhpii.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.nanxinkj.top/Article/details/gt2zenwzozg.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.hammf.cn/Article/details/gt2bgvavisj.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.yvedp.cn/Article/details/gt2znbslmom.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.hfpthk.cn/Article/details/gt2cbeemolt.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2gigxapmj.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.0kj1m.cn/Article/details/gt2bxjhwimz.html

[A09] 绝对值与最大最小值
来源：http://dali.chenzaomai.com/Article/details/gt2bwnyxlob.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kuwycttp.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.aizwys.cn/Article/details/gt2urtctnij.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.daxiang520.top/Article/details/gt2ldickdqh.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.316326.xyz/Article/details/gt2wajnispp.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.dashuyun.cn/Article/details/gt2mrphoxps.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.sufxvd.cn/Article/details/gt2xlnrmsre.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yafitvjt.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.jinqigfzy.top/Article/details/gt2ztzjdouc.html

[A10] 生成随机数
来源：http://dali.meibo888.top/Article/details/gt2pbhfvdpk.html

Py:   import random; random.randint(1, 100)
来源：http://dali.316326.xyz/Article/details/gt2ewbnzmsd.html

PHP:  random_int(1, 100);
来源：http://dali.jinqigfzy.top/Article/details/gt2jiagptce.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.wangshuangyany.cn/Article/details/gt2goheznwv.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.snrcjt.cn/Article/details/gt2basqmwym.html

Java: new Random().nextInt(100) + 1
来源：http://dali.yvedp.cn/Article/details/gt2agafbnkn.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.kuanghao11.cn/Article/details/gt2ztztsmff.html

Ruby: rand(1..100)
来源：http://dali.yuxming.cn/Article/details/gt2wbualtyq.html

C#:   new Random().Next(1, 101)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lbekxqeg.html

[A11] 条件表达式（三元）
来源：http://dali.tanke756.top/Article/details/gt2fadlaxgo.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.cucudq.cn/Article/details/gt2ykldpuwv.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2cysehpqk.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.jinqigfzy.top/Article/details/gt2scttotiu.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.daria6918.cn/Article/details/gt2hgkpffxv.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.kuanghao11.cn/Article/details/gt2hborezeb.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.dashuyun.cn/Article/details/gt2apauoapf.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.svipenyu.cn/Article/details/gt2phwdhibj.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2anvmpzjw.html

[A12] 字符串插值 / 格式化
来源：http://dali.0kj1m.cn/Article/details/gt2hkfkvzkd.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.andypj.xyz/Article/details/gt2abcrvydp.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.dianchejie.cn/Article/details/gt2sipbbroz.html

JS:   `Hello, ${name}!`
来源：http://dali.fzhhl.top/Article/details/gt2nvzsjbvu.html

TS:   `Hello, ${name}!`
来源：http://dali.tanke756.top/Article/details/gt2sbtxrqzd.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.gotoacloud.top/Article/details/gt2qkdvktmn.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.kuanghao11.cn/Article/details/gt2kdjnnurl.html

Ruby: "Hello, #{name}!"
来源：http://dali.tian-w.cn/Article/details/gt2lfemjtrg.html

C#:   $"Hello, {name}!"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gnvuqwxf.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.gotoacloud.top/Article/details/gt2ixtgkdty.html

Py:   "第一行\n第二行"
来源：http://dali.hywenlv.cn/Article/details/gt2ucutreze.html

PHP:  "第一行\n第二行"
来源：http://dali.tian-w.cn/Article/details/gt2qdwrhslb.html

JS:   "第一行\n第二行"
来源：http://dali.xziqi.cn/Article/details/gt2chpdnmgs.html

TS:   "第一行\n第二行"
来源：http://dali.yj202588.top/Article/details/gt2ibrmicgi.html

Java: "第一行\n第二行"
来源：http://dali.aibaodan.cn/Article/details/gt2bqqcxzyu.html

Go:   "第一行\n第二行"
来源：http://dali.shangyingyoupin.top/Article/details/gt2kchijqnp.html

Ruby: "第一行\n第二行"
来源：http://dali.yanxiufei.cn/Article/details/gt2igrqqyui.html

C#:   "第一行\n第二行"
来源：http://dali.cqqwz.cn/Article/details/gt2bwukbjer.html

[A14] 注释写法
来源：http://dali.mhx1999.top/Article/details/gt2gogaouit.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.yj20258.top/Article/details/gt2zdvcxdcp.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.jlsjyb.cn/Article/details/gt2zgxiramj.html

JS:   // 单行；/* 多行 */
来源：http://dali.cashguo.top/Article/details/gt2vveqwxch.html

TS:   // 单行；/* 多行 */
来源：http://dali.cdnleiting.top/Article/details/gt2fxjesqxp.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cxldolwm.html

Go:   // 单行；/* 多行 */
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2elhofhbx.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.gaohongyu789.top/Article/details/gt2madhhebz.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2mycgiqek.html

[A15] 空值判断与默认值
来源：http://dali.zhoulong.xyz/Article/details/gt2fpmblteg.html

Py:   value = data or "默认值"
来源：http://dali.nwbrower.top/Article/details/gt2nwulkuty.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.haohaochexian.top/Article/details/gt2ibahdqfu.html

JS:   const value = data ?? "默认值";
来源：http://dali.smart0.xyz/Article/details/gt2leseotlq.html

TS:   const value = data ?? "默认值";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lyywavjr.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.yonumen.top/Article/details/gt2euavprpp.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uldytdcy.html

Ruby: value = data || "默认值"
来源：http://dali.0kj1m.cn/Article/details/gt2pvfkxvdi.html

C#:   var value = data ?? "默认值";
来源：http://dali.snrcjt.cn/Article/details/gt2ikszpezo.html

[A16] 真假值判断规则
来源：http://dali.aibaodan.cn/Article/details/gt2potbtuqn.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.hfpthk.cn/Article/details/gt2gnxcoyjf.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.yvedp.cn/Article/details/gt2llzxvqkc.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.hongshengwenyu.top/Article/details/gt2wrkvhemm.html

TS:   if (!x) {}
来源：http://dali.hywenlv.cn/Article/details/gt2zbuqosvr.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.dashuyun.cn/Article/details/gt2hgbimlub.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.daxiang520.top/Article/details/gt2shyupynw.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.hysaishi.cn/Article/details/gt2ljfjrlhr.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.shzxlz.cn/Article/details/gt2jtrxlltm.html

[A17] 位运算
来源：http://dali.kuanghao11.cn/Article/details/gt2wvmirovp.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gpeqhyrq.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.xuanzx.com/Article/details/gt2qqqgxndb.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhongyouzk.top/Article/details/gt2uejtdxna.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.vqdsnc.cn/Article/details/gt2nlkhlppc.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.guannengcc.top/Article/details/gt2pcicnejb.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.tanke756.top/Article/details/gt2zkdbfenr.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.316326.xyz/Article/details/gt2tfhgeefb.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.quarkkingdee.top/Article/details/gt2fijopbeb.html

[A18] 字符与 ASCII 码互转
来源：http://dali.hnqzz.top/Article/details/gt2vsdqaafc.html

Py:   ord("A"); chr(65)
来源：http://dali.chenlongwang.top/Article/details/gt2vkrmqfjy.html

PHP:  ord("A"); chr(65)
来源：http://dali.c1oappe.top/Article/details/gt2derxfdfp.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.ehwqpu.com/Article/details/gt2jvrxwplv.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.tanke756.top/Article/details/gt2wcxkgwdn.html

Java: (int) 'A'; (char) 65
来源：http://dali.nwbrower.top/Article/details/gt2mezloukb.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.c1oappe.top/Article/details/gt2rwoyuoqw.html

Ruby: "A".ord; 65.chr
来源：http://dali.shangyingyoupin.top/Article/details/gt2ujxuzvjq.html

C#:   (int)'A'; (char)65
来源：http://dali.pengpengdd.cyou/Article/details/gt2sygebnkl.html

[A19] 交换两个变量
来源：http://dali.dashuyun.cn/Article/details/gt2uobhhndv.html

Py:   a, b = b, a
来源：http://dali.yanxiufei.cn/Article/details/gt2lvsukyrr.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.sysykeji.top/Article/details/gt2djwjuxnu.html

JS:   [a, b] = [b, a];
来源：http://dali.fzhhl.top/Article/details/gt2zcyirciq.html

TS:   [a, b] = [b, a];
来源：http://dali.ybcxt.top/Article/details/gt2tsslccxc.html

Java: int t = a; a = b; b = t;
来源：http://dali.zhengqikj.top/Article/details/gt2xgjpdloo.html

Go:   a, b = b, a
来源：http://dali.xuetiantiany.cn/Article/details/gt2nnsxcbwl.html

Ruby: a, b = b, a
来源：http://dali.316326.xyz/Article/details/gt2ptkbknvl.html

C#:   (a, b) = (b, a);
来源：http://dali.ivvv.top/Article/details/gt2fhfrsodr.html

[A20] 读取标准输入
来源：http://dali.pycfn.com/Article/details/gt2ajibqzmn.html

Py:   name = input("请输入：")
来源：http://dali.yangfankeji.com/Article/details/gt2ogxnpjjt.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.zhijiandao.cn/Article/details/gt2djgkcujy.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.haohaochexian.top/Article/details/gt2naquqmga.html

TS:   // Node.js：readline 模块
来源：http://dali.gaohongyu789.top/Article/details/gt2tiodcgjc.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.sysykeji.top/Article/details/gt2eglfapaq.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.chenzaomai.com/Article/details/gt2werorfkr.html

Ruby: gets.chomp
来源：http://dali.jiagoushi.top/Article/details/gt2kfqlmvbo.html

C#:   Console.ReadLine();
来源：http://dali.kuanghao11.cn/Article/details/gt2iqvvzqjr.html

[A21] 保留指定小数位输出
来源：http://dali.daria6918.cn/Article/details/gt2twnruydt.html

Py:   f"{3.14159:.2f}"
来源：http://dali.daria6918.cn/Article/details/gt2ajdkflfp.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.hysaishi.cn/Article/details/gt2btvnfdfx.html

JS:   (3.14159).toFixed(2)
来源：http://dali.cheryme.top/Article/details/gt2cspiyknr.html

TS:   (3.14159).toFixed(2)
来源：http://dali.yuxming.cn/Article/details/gt2gfikxkpg.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.iojbl.cn/Article/details/gt2pjdqqwbe.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.quarkkingdee.top/Article/details/gt2knqbpwzq.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.daxiang520.top/Article/details/gt2aeibrdti.html

C#:   3.14159.ToString("F2")
来源：http://dali.wangshuangyany.cn/Article/details/gt2enzgbjxl.html

[A22] 获取字符串长度
来源：http://dali.hnqzz.top/Article/details/gt2vpnszafr.html

Py:   len(s)
来源：http://dali.guowangkeji.top/Article/details/gt2ujwlyshv.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.gotoacloud.top/Article/details/gt2jekgzoym.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.hywenlv.cn/Article/details/gt2eyvwaffa.html

TS:   s.length
来源：http://dali.jianghu66.top/Article/details/gt2fhsacxcw.html

Java: s.length()
来源：http://dali.yvedp.cn/Article/details/gt2ajeqlbii.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.meibo888.top/Article/details/gt2tsuaffrv.html

Ruby: s.length
来源：http://dali.kuanghao11.cn/Article/details/gt2kmraguye.html

C#:   s.Length
来源：http://dali.wangdashe.top/Article/details/gt2ybbgmwel.html

[A23] 大小写转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bwupxpka.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.iojbl.cn/Article/details/gt2uhcwjzal.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.jyoumei.cn/Article/details/gt2kjxbdxcn.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.chenlongwang.top/Article/details/gt2hoiirqma.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jqgufenzy.top/Article/details/gt2ssmileaa.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.fengsongda.top/Article/details/gt2brwrsyxi.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bxtozueq.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.zhiwuduotai.top/Article/details/gt2stefzdry.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.mhx1999.top/Article/details/gt2nubotbgy.html

[A24] 去除首尾空白
来源：http://dali.yuanzhike.top/Article/details/gt2rdvxesmc.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.yonumen.top/Article/details/gt2zyocsbyp.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.daxiang520.top/Article/details/gt2fpgvxzjd.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.ybcxt.top/Article/details/gt2gftmtkwe.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.mhx1999.top/Article/details/gt2eoweaooj.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.cucudq.cn/Article/details/gt2pdejfzbr.html

Go:   strings.TrimSpace(s)
来源：http://dali.jiagoushi.top/Article/details/gt2ikjutgjb.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.316326.xyz/Article/details/gt2waksrowk.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.redwolf501.top/Article/details/gt2gixepnhq.html

[A25] 字符串比较
来源：http://dali.sysykeji.top/Article/details/gt2wjhylgak.html

Py:   s1 == s2; s1 != s2
来源：http://dali.xinyue.icu/Article/details/gt2vpekdyqe.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.guowangkeji.top/Article/details/gt2fclmwoem.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yonumen.top/Article/details/gt2qlqwsctw.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.sweek.top/Article/details/gt2eyuveuea.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.tian-w.cn/Article/details/gt2aumfsojt.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.hnqzz.top/Article/details/gt2csedzppm.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jinqigufen.top/Article/details/gt2nhjifvib.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.tian-w.cn/Article/details/gt2yblwnikt.html

[A26] 类型转换总览
来源：http://dali.hfpthk.cn/Article/details/gt2xolwjejf.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.fzhhl.top/Article/details/gt2twepvoez.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.jinqigufen.top/Article/details/gt2gmzyewxr.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.cqqwz.cn/Article/details/gt2swatabhb.html

TS:   Number() String() Boolean() x as number
来源：http://dali.shuidangran.top/Article/details/gt2ulbypmmo.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.xylfe.cn/Article/details/gt2gxdiphpe.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.birdmap.top/Article/details/gt2cuocsbja.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.tianlin.xyz/Article/details/gt2dnkynwkv.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.hammf.cn/Article/details/gt2engjhrzu.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2watcdxku.html

B. 流程控制
来源：http://dali.yanxiufei.cn/Article/details/gt2ojkjxydj.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2imsjtefx.html

[B01] 条件判断 if / else
来源：http://dali.wangshuangyany.cn/Article/details/gt2jlixxtji.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yangfankeji.com/Article/details/gt2glbvmpdp.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.mhx1999.top/Article/details/gt2hocogusy.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jlsjyb.cn/Article/details/gt2dypuytkf.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.gzhubu.top/Article/details/gt2apruokbn.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jiagoushi.top/Article/details/gt2omzqhkyb.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.dashuyun.cn/Article/details/gt2dfyptlsx.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.tianlin.xyz/Article/details/gt2hoqsfsyf.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.hysaishi.cn/Article/details/gt2dzmlyvqa.html

[B02] 多分支 else if / elif
来源：http://dali.jinqigufen.top/Article/details/gt2zehffsps.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yangfankeji.com/Article/details/gt2oaclihrf.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2xhmnozjm.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yongpay.top/Article/details/gt2cnpagekt.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigufen.top/Article/details/gt2gbvmflxo.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sweek.top/Article/details/gt2necsommp.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.zhiwuduotai.top/Article/details/gt2fyquiffc.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jlsjyb.cn/Article/details/gt2emazfsni.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hongshengwenyu.top/Article/details/gt2cbezgmmj.html

[B03] switch / match / case
来源：http://dali.0kj1m.cn/Article/details/gt2tilsnjhg.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.quarkkingdee.top/Article/details/gt2mtyldput.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.hnqzz.top/Article/details/gt2zgvklfys.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2ieshcqmi.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2aiqbkrmc.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.tanke756.top/Article/details/gt2ujmoblrq.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yanxiufei.cn/Article/details/gt2oyumxuzc.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.guannengcc.top/Article/details/gt2skbgdzlt.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.zhixingplan.top/Article/details/gt2eqiqinfh.html

[B04] for 计数循环
来源：http://dali.yongpay.top/Article/details/gt2tfjaekdy.html

Py:   for i in range(10): print(i)
来源：http://dali.redwolf501.top/Article/details/gt2vcbigqio.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.316326.xyz/Article/details/gt2qbjrytbn.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yanxiufei.cn/Article/details/gt2rjjcknjw.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cheryme.top/Article/details/gt2hpxwijvq.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yuxming.cn/Article/details/gt2jfukqrvp.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.tian-w.cn/Article/details/gt2htonlppl.html

Ruby: 10.times { |i| puts i }
来源：http://dali.9152youxi.cn/Article/details/gt2nhrcobur.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jinqigfzy.top/Article/details/gt2vbmuqvju.html

[B05] 遍历数组 / 列表
来源：http://dali.nwbrower.top/Article/details/gt2zpibljgc.html

Py:   for item in arr: print(item)
来源：http://dali.sxryk.cn/Article/details/gt2iosoksta.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.gotoacloud.top/Article/details/gt2godvcema.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.shuidangran.top/Article/details/gt2dgwxhjnp.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zdqjudy.top/Article/details/gt2ardrsylx.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.fzhhl.top/Article/details/gt2nnzcmvor.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.daxiang520.top/Article/details/gt2qjlpjfbc.html

Ruby: arr.each { |item| puts item }
来源：http://dali.sysykeji.top/Article/details/gt2lmseicnc.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.nanxinkj.top/Article/details/gt2bldqnrkc.html

[B06] 遍历字典 / 对象
来源：http://dali.svipenyu.cn/Article/details/gt2qhluhudy.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.shzxlz.cn/Article/details/gt2lrklryfr.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yuanzhike.top/Article/details/gt2krievqpm.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.tianlin.xyz/Article/details/gt2swrdqclw.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hnqzz.top/Article/details/gt2flnqkqsh.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.nanxuanxn.top/Article/details/gt2xrmcpbcg.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.316326.xyz/Article/details/gt2pdrglknm.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.meibo888.top/Article/details/gt2xmrbkboz.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.pycfn.com/Article/details/gt2ljwwptjl.html

[B07] while 循环
来源：http://dali.cqqwz.cn/Article/details/gt2worrovlw.html

Py:   while i < 10: i += 1
来源：http://dali.chenlongwang.top/Article/details/gt2myrblelq.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.birdmap.top/Article/details/gt2yfbnlajp.html

JS:   while (i < 10) { i++; }
来源：http://dali.yonumen.top/Article/details/gt2mpbghqux.html

TS:   while (i < 10) { i++; }
来源：http://dali.cdnleiting.top/Article/details/gt2jmpihatj.html

Java: while (i < 10) { i++; }
来源：http://dali.jqgfzy.top/Article/details/gt2djsovykm.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jinqigufen.top/Article/details/gt2lpvtrhzx.html

Ruby: while i < 10; i += 1; end
来源：http://dali.0kj1m.cn/Article/details/gt2lcdzorio.html

C#:   while (i < 10) { i++; }
来源：http://dali.aizwys.cn/Article/details/gt2jbvjzhea.html

[B08] do-while（至少执行一次）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fwosbuzw.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.haohaochexian.top/Article/details/gt2soplrist.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yangfankeji.com/Article/details/gt2pjwwbupg.html

JS:   do { i++; } while (i < 10);
来源：http://dali.cqqwz.cn/Article/details/gt2vbgmjkdx.html

TS:   do { i++; } while (i < 10);
来源：http://dali.tianlin.xyz/Article/details/gt2ujvqtwge.html

Java: do { i++; } while (i < 10);
来源：http://dali.guannengcc.top/Article/details/gt2hchhebrh.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ejbbcfcg.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.hnxiangtu.top/Article/details/gt2rjakfarw.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jinqigufen.top/Article/details/gt2nfoznxzx.html

[B09] break 与 continue
来源：http://dali.xuetiantiany.cn/Article/details/gt2huelmmye.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.cheryme.top/Article/details/gt2nkcxvlrt.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.cashguo.top/Article/details/gt2ixvzuitm.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hammf.cn/Article/details/gt2dzafpoph.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zycfv.cn/Article/details/gt2ivpwekrc.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2srgylmkk.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yangfankeji.com/Article/details/gt2gvzskyqj.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.dianchejie.cn/Article/details/gt2jbyctlun.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinqigufen.top/Article/details/gt2zohkoxwz.html

[B10] 遍历同时拿索引
来源：http://dali.shzxlz.cn/Article/details/gt2zixhljku.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hzyprmzt.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhengqikj.top/Article/details/gt2wrukhhxg.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.aibaodan.cn/Article/details/gt2llrsocar.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.pengpengdd.cyou/Article/details/gt2mzqfgujz.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.ybcxt.top/Article/details/gt2drfzmcrr.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.shuidangran.top/Article/details/gt2cbbbklxz.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wyglttjx.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jqgufenzy.top/Article/details/gt2svctqjbr.html

[B11] 生成数字序列 / 区间
来源：http://dali.quarkkingdee.top/Article/details/gt2hruppcof.html

Py:   list(range(0, 10, 2))
来源：http://dali.daxiang520.top/Article/details/gt2afcpqkwc.html

PHP:  range(0, 10, 2);
来源：http://dali.yj202588.top/Article/details/gt2uvxsztda.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.haohaochexian.top/Article/details/gt2vhcetmwo.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2obetjelu.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.kuanghao11.cn/Article/details/gt2rqpsdnio.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.sxryk.cn/Article/details/gt2bhyflgnh.html

Ruby: (0...10).step(2).to_a
来源：http://dali.svipenyu.cn/Article/details/gt2yvialcsp.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vnprnige.html

[B12] 跳出多层循环
来源：http://dali.sxryk.cn/Article/details/gt2cobdpqcs.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jianghu66.top/Article/details/gt2bbhucfbg.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yongpay.top/Article/details/gt2yeppjzbj.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shzxlz.cn/Article/details/gt2psqafqqw.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hywenlv.cn/Article/details/gt2vedbkslv.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.tanke756.top/Article/details/gt2exocirjh.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.birdmap.top/Article/details/gt2czyalasi.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.feifeiyinyue.top/Article/details/gt2ghfbgpxi.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.wangdashe.top/Article/details/gt2tscmxojt.html

[B13] 判断是否为数字
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2guzzlljc.html

Py:   isinstance(x, (int, float))
来源：http://dali.ppjwa.cn/Article/details/gt2dpppnuzj.html

PHP:  is_numeric($x)
来源：http://dali.hnxiangtu.top/Article/details/gt2dfivdyuc.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sxryk.cn/Article/details/gt2zvnqglts.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yueranfly.top/Article/details/gt2afirjnjd.html

Java: x instanceof Number
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2abzfctnk.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xziqi.cn/Article/details/gt2mgsahiri.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jqgufenzy.top/Article/details/gt2syqxtkjz.html


<!-- 参考信息 -->