代发 wailian999

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.pycfn.com/Article/details/gtvdkukybn.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.0kj1m.cn/Article/details/gtgyxioatd.html

[A12] 字符串插值 / 格式化
来源：http://dali.svipenyu.cn/Article/details/gtuurbveha.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.aizwys.cn/Article/details/gtqabvowck.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.cqqwz.cn/Article/details/gtsfizpfvp.html

JS:   `Hello, ${name}!`
来源：http://dali.hywenlv.cn/Article/details/gtdotvjyze.html

TS:   `Hello, ${name}!`
来源：http://dali.haohaochexian.top/Article/details/gtpbodyzgk.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.aibaodan.cn/Article/details/gtppilzjlf.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.wangdashe.top/Article/details/gtfkxjujbu.html

Ruby: "Hello, #{name}!"
来源：http://dali.yanxiufei.cn/Article/details/gttyvuvihr.html

C#:   $"Hello, {name}!"
来源：http://dali.shuidangran.top/Article/details/gtjthedfai.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.ybcxt.top/Article/details/gtpfjsohfn.html

Py:   "第一行\n第二行"
来源：http://dali.ybcxt.top/Article/details/gtcbwiasfr.html

PHP:  "第一行\n第二行"
来源：http://dali.jinghuilouyu.cn/Article/details/gtbqayoymg.html

JS:   "第一行\n第二行"
来源：http://dali.fzhhl.top/Article/details/gtkiqrhlie.html

TS:   "第一行\n第二行"
来源：http://dali.cqqwz.cn/Article/details/gttjlbjueq.html

Java: "第一行\n第二行"
来源：http://dali.yonumen.top/Article/details/gtklhxvtnf.html

Go:   "第一行\n第二行"
来源：http://dali.feifeiyinyue.top/Article/details/gtktmycgat.html

Ruby: "第一行\n第二行"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuiujwbtz.html

C#:   "第一行\n第二行"
来源：http://dali.jiagoushi.top/Article/details/gtjzafsnty.html

[A14] 注释写法
来源：http://dali.shanyushiyangtech.top/Article/details/gtudvyjvkq.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.gzhubu.top/Article/details/gtiykwwdte.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.smart0.xyz/Article/details/gtnnxegzvi.html

JS:   // 单行；/* 多行 */
来源：http://dali.cucudq.cn/Article/details/gtbienzgdc.html

TS:   // 单行；/* 多行 */
来源：http://dali.pengpengdd.cyou/Article/details/gtyiyvlcmd.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.cucudq.cn/Article/details/gtkavhxsua.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhiwuduotai.top/Article/details/gtrngeuqga.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.tanke756.top/Article/details/gtdrqvusuc.html

C#:   // 单行；/* 多行 */
来源：http://dali.feifeiyinyue.top/Article/details/gtsrtemnhq.html

[A15] 空值判断与默认值
来源：http://dali.guowangkeji.top/Article/details/gtzmysvrsy.html

Py:   value = data or "默认值"
来源：http://dali.sweek.top/Article/details/gturhittlm.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.jinqigfzy.top/Article/details/gtismqqxfj.html

JS:   const value = data ?? "默认值";
来源：http://dali.chenzaomai.com/Article/details/gtgewobeln.html

TS:   const value = data ?? "默认值";
来源：http://dali.haohaochexian.top/Article/details/gtqfmznlma.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.bjfxy.top/Article/details/gtqjjjpjmo.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.shzxlz.cn/Article/details/gtkageaigq.html

Ruby: value = data || "默认值"
来源：http://dali.mhx1999.top/Article/details/gtjfparjes.html

C#:   var value = data ?? "默认值";
来源：http://dali.jiagoushi.top/Article/details/gtrcatbhnl.html

[A16] 真假值判断规则
来源：http://dali.tanke756.top/Article/details/gtlligwnba.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.ivvv.top/Article/details/gtbflongry.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.gogol.net.cn/Article/details/gtzlqqmsfs.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.yanxiufei.cn/Article/details/gtjrwgunuh.html

TS:   if (!x) {}
来源：http://dali.wangshuangyany.cn/Article/details/gteivhjjmr.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.smart0.xyz/Article/details/gticyiyooa.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.gaohongyu789.top/Article/details/gtaylxivtv.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.jqgfzy.top/Article/details/gtymdcxycu.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.andypj.xyz/Article/details/gtstatgeod.html

[A17] 位运算
来源：http://dali.shanyushiyangtech.top/Article/details/gtxqodkyym.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cdnleiting.top/Article/details/gtflugvdvh.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.iojbl.cn/Article/details/gtuvefigho.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ivvv.top/Article/details/gtnuehhboc.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.0kj1m.cn/Article/details/gtvsnxaehc.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ydzc1.top/Article/details/gtgbajbkca.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.chenzaomai.com/Article/details/gtfucjawyt.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gzhubu.top/Article/details/gtzrmjnscq.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.0kj1m.cn/Article/details/gteyhgawfn.html

[A18] 字符与 ASCII 码互转
来源：http://dali.yuxming.cn/Article/details/gtdcjhnbfr.html

Py:   ord("A"); chr(65)
来源：http://dali.tian-w.cn/Article/details/gtgzdjmdft.html

PHP:  ord("A"); chr(65)
来源：http://dali.cheryme.top/Article/details/gtltyvolxx.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtndpehuvc.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.pengpengdd.cyou/Article/details/gtoitbntzz.html

Java: (int) 'A'; (char) 65
来源：http://dali.snrcjt.cn/Article/details/gttjodkzei.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.ywan-chungtsiang.top/Article/details/gtklwmlmek.html

Ruby: "A".ord; 65.chr
来源：http://dali.cqqwz.cn/Article/details/gtnjofgoqr.html

C#:   (int)'A'; (char)65
来源：http://dali.shzxlz.cn/Article/details/gtozngrisy.html

[A19] 交换两个变量
来源：http://dali.quarkkingdee.top/Article/details/gtqvrfwxpu.html

Py:   a, b = b, a
来源：http://dali.daria6918.cn/Article/details/gtmqotmyrr.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.aizwys.cn/Article/details/gtkohrczhs.html

JS:   [a, b] = [b, a];
来源：http://dali.gotoacloud.top/Article/details/gtnahetdon.html

TS:   [a, b] = [b, a];
来源：http://dali.mhx1999.top/Article/details/gtaxczlgpj.html

Java: int t = a; a = b; b = t;
来源：http://dali.zdqjudy.top/Article/details/gtcepcwhkw.html

Go:   a, b = b, a
来源：http://dali.zhoulong.xyz/Article/details/gtgogmlmbe.html

Ruby: a, b = b, a
来源：http://dali.nwbrower.top/Article/details/gtcqeybhjd.html

C#:   (a, b) = (b, a);
来源：http://dali.sysykeji.top/Article/details/gtpfeiwekn.html

[A20] 读取标准输入
来源：http://dali.cucudq.cn/Article/details/gtizanovix.html

Py:   name = input("请输入：")
来源：http://dali.ybcxt.top/Article/details/gtzhmhyecp.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.dianchejie.cn/Article/details/gtpbvwhdga.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.tian-w.cn/Article/details/gtzngjtlzc.html

TS:   // Node.js：readline 模块
来源：http://dali.jiagoushi.top/Article/details/gtslljskwc.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.jianghu66.top/Article/details/gtfltoqfwi.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.mhx1999.top/Article/details/gtzgwfxcyq.html

Ruby: gets.chomp
来源：http://dali.shuidangran.top/Article/details/gtsgpfnzgq.html

C#:   Console.ReadLine();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvmaosfvq.html

[A21] 保留指定小数位输出
来源：http://dali.birdmap.top/Article/details/gtztmsgnxa.html

Py:   f"{3.14159:.2f}"
来源：http://dali.tian-w.cn/Article/details/gtdrfrwdsi.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.nanxinkj.top/Article/details/gtmgaraquq.html

JS:   (3.14159).toFixed(2)
来源：http://dali.xinyue.icu/Article/details/gtrhpjpkdb.html

TS:   (3.14159).toFixed(2)
来源：http://dali.sufxvd.cn/Article/details/gtahfdvcmt.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.mhx1999.top/Article/details/gtndfzqsrn.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.bjfxy.top/Article/details/gttdbxkdpk.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.hysaishi.cn/Article/details/gtyibrcesv.html

C#:   3.14159.ToString("F2")
来源：http://dali.hongshengwenyu.top/Article/details/gtldunalfk.html

[A22] 获取字符串长度
来源：http://dali.yueranfly.top/Article/details/gtnofzvfmu.html

Py:   len(s)
来源：http://dali.hnqzz.top/Article/details/gtxpvzlsfb.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.yueranfly.top/Article/details/gttbjqtett.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.0kj1m.cn/Article/details/gtsyxelqud.html

TS:   s.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjeydntop.html

Java: s.length()
来源：http://dali.guannengcc.top/Article/details/gtpvdpeyey.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.yangfankeji.com/Article/details/gtkkoerbry.html

Ruby: s.length
来源：http://dali.316326.xyz/Article/details/gttedfiimn.html

C#:   s.Length
来源：http://dali.zhengqikj.top/Article/details/gtztwwkchl.html

[A23] 大小写转换
来源：http://dali.jianghu66.top/Article/details/gtqcqthzyo.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.sysykeji.top/Article/details/gtkhiaktgc.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.hysaishi.cn/Article/details/gtbvjuxlze.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.9152youxi.cn/Article/details/gtgxmxqgxu.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.c1oappe.top/Article/details/gtlnofylvz.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhiwuduotai.top/Article/details/gtuijnbfgz.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.jianghu66.top/Article/details/gtlpkncmdd.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.gzhubu.top/Article/details/gtlpdzrijr.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.jinqigufen.top/Article/details/gtfubvxywc.html

[A24] 去除首尾空白
来源：http://dali.bjfxy.top/Article/details/gtshdsoand.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.pycfn.com/Article/details/gtzrxkrysm.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.gogol.net.cn/Article/details/gtghgtocex.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcklcvsxm.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.mhx1999.top/Article/details/gtufmkrasv.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.hywenlv.cn/Article/details/gtiswrjwkm.html

Go:   strings.TrimSpace(s)
来源：http://dali.havefunace.top/Article/details/gtgglsptks.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.hongshengwenyu.top/Article/details/gtgwmzwpsq.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.svipenyu.cn/Article/details/gtexqzekem.html

[A25] 字符串比较
来源：http://dali.pengpengdd.cyou/Article/details/gtsakpoolr.html

Py:   s1 == s2; s1 != s2
来源：http://dali.chenlongwang.top/Article/details/gtfsiwszbd.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.tian-w.cn/Article/details/gtqtbnhiti.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yangfankeji.com/Article/details/gtwjguwper.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.316326.xyz/Article/details/gtzpunemxg.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.zhixingplan.top/Article/details/gtyymkogsi.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.zdqjudy.top/Article/details/gtgtgrmsrh.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.kuanghao11.cn/Article/details/gtebmkoqdy.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yuanzhike.top/Article/details/gtiyywlnoz.html

[A26] 类型转换总览
来源：http://dali.quarkkingdee.top/Article/details/gtukquskme.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.hywenlv.cn/Article/details/gtsffgtdor.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.tanke756.top/Article/details/gtidkgmzzr.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.9152youxi.cn/Article/details/gtyucrxpoo.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zhixingplan.top/Article/details/gtmcvaxnoz.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zhongyouzk.top/Article/details/gtqtwpzpao.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.wangdashe.top/Article/details/gtijlplxwy.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.jiagoushi.top/Article/details/gtmqlrsroo.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.svipenyu.cn/Article/details/gtvnimivtu.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzdsxmopq.html

B. 流程控制
来源：http://dali.birdmap.top/Article/details/gtlvleszdb.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtzshlohke.html

[B01] 条件判断 if / else
来源：http://dali.cucudq.cn/Article/details/gtmmfpqtdf.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqhatorlj.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jianghu66.top/Article/details/gthtemgirr.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.sysykeji.top/Article/details/gtqzabzagj.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zdqjudy.top/Article/details/gtxzerlvpf.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.dashuyun.cn/Article/details/gtzpxweufs.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.guowangkeji.top/Article/details/gtsyajmyxg.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.yanxiufei.cn/Article/details/gtyiwxmlii.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jqgfzy.top/Article/details/gtdmpzzyml.html

[B02] 多分支 else if / elif
来源：http://dali.nanxinkj.top/Article/details/gtihozqnfk.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.ydzc1.top/Article/details/gtympvhtnm.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.fengsongda.top/Article/details/gtubxvmagi.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xuetiantiany.cn/Article/details/gtaweptgqc.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gaohongyu789.top/Article/details/gtsculivlv.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tianlin.xyz/Article/details/gtxinemmnj.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.zycfv.cn/Article/details/gtfilavkeb.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.haohaochexian.top/Article/details/gthmrgkpsp.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.316326.xyz/Article/details/gtpdhrealj.html

[B03] switch / match / case
来源：http://dali.yangfankeji.com/Article/details/gtvczqrjqe.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdtlihsxd.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.daxiang520.top/Article/details/gtseulyzkn.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfkvaaedh.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.svipenyu.cn/Article/details/gtnrlohuic.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtidkpfgbw.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.aibaodan.cn/Article/details/gtkkdbnbyq.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.xuanzx.com/Article/details/gtnqamcdcj.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.fengsongda.top/Article/details/gtiknysozo.html

[B04] for 计数循环
来源：http://dali.yanxiufei.cn/Article/details/gtzulsgpls.html

Py:   for i in range(10): print(i)
来源：http://dali.nanxuanxn.top/Article/details/gtlzroynmw.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.zhiwuduotai.top/Article/details/gtcwofcurl.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.0kj1m.cn/Article/details/gtpwmfzhro.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.tianlin.xyz/Article/details/gtcxwvzafv.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.chenlongwang.top/Article/details/gtluavbfjq.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.hysaishi.cn/Article/details/gtsohmfxne.html

Ruby: 10.times { |i| puts i }
来源：http://dali.9152youxi.cn/Article/details/gtmobbgzbz.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zhiwuduotai.top/Article/details/gtbdksfzaj.html

[B05] 遍历数组 / 列表
来源：http://dali.daria6918.cn/Article/details/gtbtaexemw.html

Py:   for item in arr: print(item)
来源：http://dali.snrcjt.cn/Article/details/gttdwmhweq.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.meibo888.top/Article/details/gtvmutnbho.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlypxfntq.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.jianghu66.top/Article/details/gtnzmrvsvr.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zhiwuduotai.top/Article/details/gtuznqlkkq.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.hnqzz.top/Article/details/gtirqougyf.html

Ruby: arr.each { |item| puts item }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmzgaybza.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.pycfn.com/Article/details/gtevrwyxuq.html

[B06] 遍历字典 / 对象
来源：http://dali.jianghu66.top/Article/details/gtrjelkaal.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.fzhhl.top/Article/details/gttmyozett.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtfmjaamgn.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpwpjrilo.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yongpay.top/Article/details/gtsguwzztz.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.wangshuangyany.cn/Article/details/gtdvrfugcc.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jinqigfzy.top/Article/details/gtpzfwphix.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yanxiufei.cn/Article/details/gtpvfxiwud.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.fzhhl.top/Article/details/gtsfhgeoxi.html

[B07] while 循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtybnbjtlz.html

Py:   while i < 10: i += 1
来源：http://dali.cucudq.cn/Article/details/gtoubseavb.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpnhinojt.html

JS:   while (i < 10) { i++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpcpaimwh.html

TS:   while (i < 10) { i++; }
来源：http://dali.jqgufenzy.top/Article/details/gteeayqyyj.html

Java: while (i < 10) { i++; }
来源：http://dali.redwolf501.top/Article/details/gtbatlhlpe.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.feifeiyinyue.top/Article/details/gthsojeenm.html

Ruby: while i < 10; i += 1; end
来源：http://dali.chenzaomai.com/Article/details/gttkzwashy.html

C#:   while (i < 10) { i++; }
来源：http://dali.birdmap.top/Article/details/gtqicffvxy.html

[B08] do-while（至少执行一次）
来源：http://dali.jiagoushi.top/Article/details/gtkztincln.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.cdnleiting.top/Article/details/gtlhekitme.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.xylfe.cn/Article/details/gtufaqbomo.html

JS:   do { i++; } while (i < 10);
来源：http://dali.tian-w.cn/Article/details/gtnqxhwjhs.html

TS:   do { i++; } while (i < 10);
来源：http://dali.ppjwa.cn/Article/details/gtqzkcnblc.html

Java: do { i++; } while (i < 10);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtehvbwamx.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.wangdashe.top/Article/details/gtkqurcsdj.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.fzhhl.top/Article/details/gtfowdfrzq.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yanxiufei.cn/Article/details/gtijuwfvms.html

[B09] break 与 continue
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzlztniuv.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.meibo888.top/Article/details/gtilhrrxsm.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.ppjwa.cn/Article/details/gtsukfdrob.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yonumen.top/Article/details/gtzueilype.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtojnoaude.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jyoumei.cn/Article/details/gtzckmopsy.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.hammf.cn/Article/details/gtcscuxvcd.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.shuidangran.top/Article/details/gtsotuiqwe.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.c1oappe.top/Article/details/gthesfihxd.html

[B10] 遍历同时拿索引
来源：http://dali.zdqjudy.top/Article/details/gtdaqxjpfi.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.316326.xyz/Article/details/gtqnpvxjnc.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.cqqwz.cn/Article/details/gtocpoiela.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.aibaodan.cn/Article/details/gtrptwqqtx.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.redwolf501.top/Article/details/gtjvusjqcu.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yangfankeji.com/Article/details/gtlndibxrj.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttilrysth.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.chenzaomai.com/Article/details/gtorrtqjlj.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.aizwys.cn/Article/details/gtuaaxymtp.html

[B11] 生成数字序列 / 区间
来源：http://dali.redwolf501.top/Article/details/gtpunnuraf.html

Py:   list(range(0, 10, 2))
来源：http://dali.xuanzx.com/Article/details/gtubtgtoft.html

PHP:  range(0, 10, 2);
来源：http://dali.nwbrower.top/Article/details/gtogbwwzbm.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gttvvwkkvo.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhoulong.xyz/Article/details/gtxfbhgsew.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.gogol.net.cn/Article/details/gtdkidubpi.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.nanxuanxn.top/Article/details/gtlqkbebri.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yongpay.top/Article/details/gtrzptigmg.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yvedp.cn/Article/details/gtvlyjwzng.html

[B12] 跳出多层循环
来源：http://dali.hnqzz.top/Article/details/gthwnelvlv.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhengqikj.top/Article/details/gtkbcjmpfn.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hywenlv.cn/Article/details/gtuorhcujb.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.pycfn.com/Article/details/gtxokdtyei.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cdnleiting.top/Article/details/gtmmjxquyu.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gtmmtygsvk.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yj20258888.top/Article/details/gtjhyuhebd.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yongpay.top/Article/details/gthgjacrhj.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hongshengwenyu.top/Article/details/gtayjlnstc.html

[B13] 判断是否为数字
来源：http://dali.jqgfzy.top/Article/details/gtsfqmrgak.html

Py:   isinstance(x, (int, float))
来源：http://dali.guannengcc.top/Article/details/gtzoxeifrn.html

PHP:  is_numeric($x)
来源：http://dali.hysaishi.cn/Article/details/gtymkckshp.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.guowangkeji.top/Article/details/gtddswgmmw.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtcfwcxngc.html

Java: x instanceof Number
来源：http://dali.nwbrower.top/Article/details/gtvudtvyok.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.gzhubu.top/Article/details/gtiuilyfet.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yj20258.top/Article/details/gtwfjecxjd.html

C#:   x is int or double or decimal
来源：http://dali.gogol.net.cn/Article/details/gtzohrhbfe.html

[B14] 判断值是否在集合内
来源：http://dali.jinqigfzy.top/Article/details/gtynxibamu.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.wangshuangyany.cn/Article/details/gtuufpvqij.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.vqdsnc.cn/Article/details/gtdklcewll.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.dashuyun.cn/Article/details/gtybodfvfi.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jyoumei.cn/Article/details/gteltiwxsm.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdclyxblx.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yongpay.top/Article/details/gtchwpliza.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtujhtoerv.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.aizwys.cn/Article/details/gtxbdacpan.html

[B15] 布尔运算与取反
来源：http://dali.yj20258888.top/Article/details/gtmtoqnnwv.html

Py:   a and b or not c
来源：http://dali.yuxming.cn/Article/details/gtwwttdial.html

PHP:  $a && $b || !$c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtalnsvqnf.html

JS:   a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gtnzsutmjs.html

TS:   a && b || !c
来源：http://dali.tian-w.cn/Article/details/gtqxygsfpz.html

Java: a && b || !c
来源：http://dali.fengsongda.top/Article/details/gtlzexwicv.html

Go:   a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gtquwfrvxu.html

Ruby: a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gtjtfuvrsd.html

C#:   a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gtgkvensrg.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.pengpengdd.cyou/Article/details/gtlxaasjcz.html

Py:   if not data: return
来源：http://dali.hfpthk.cn/Article/details/gtofsxrjwy.html

PHP:  if (!$data) { return; }
来源：http://dali.hfpthk.cn/Article/details/gtfnhkplag.html

JS:   if (!data) return;
来源：http://dali.hnxiangtu.top/Article/details/gtnqtnuqve.html

TS:   if (!data) return;
来源：http://dali.wangshuangyany.cn/Article/details/gtmwgfmvqt.html

Java: if (data == null) return;
来源：http://dali.aibaodan.cn/Article/details/gtvuzgtasf.html

Go:   if data == nil { return }
来源：http://dali.jianghu66.top/Article/details/gtfvrxjqjy.html

Ruby: return if data.nil?
来源：http://dali.zhoulong.xyz/Article/details/gtjzjlzjlt.html

C#:   if (data == null) return;
来源：http://dali.jinqigfzy.top/Article/details/gtcdvhszfz.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtgqhguekx.html

C. 函数与作用域
来源：http://dali.tianlin.xyz/Article/details/gtgrctoksx.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtjemipgvo.html

[C01] 定义函数
来源：http://dali.cdnleiting.top/Article/details/gtspoupvgl.html

Py:   def add(a, b): return a + b
来源：http://dali.gogol.net.cn/Article/details/gtoxvhqmur.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yonumen.top/Article/details/gthwqwpccc.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtphcidvhx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gtdtaxxzfv.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttmcpjcdk.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.smart0.xyz/Article/details/gtbtcvcaxh.html

Ruby: def add(a, b); a + b; end
来源：http://dali.pengpengdd.cyou/Article/details/gtmvxjajza.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gtwctuvvgs.html

[C02] 默认参数
来源：http://dali.cqqwz.cn/Article/details/gtyhjqwfvh.html

Py:   def greet(name="World"): return name
来源：http://dali.daria6918.cn/Article/details/gtzapnnvrj.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ydzc1.top/Article/details/gtpyggtuow.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtfzsjwhww.html


<!-- 参考信息 -->