代发 wailian999

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.aibaodan.cn/Article/details/gtqxfiehko.html

JS:   `Hello, ${name}!`
来源：http://dali.guannengcc.top/Article/details/gtiwdglatm.html

TS:   `Hello, ${name}!`
来源：http://dali.wangdashe.top/Article/details/gtojabbeiv.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.fengsongda.top/Article/details/gtpqginjsc.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.iojbl.cn/Article/details/gtyohylbwz.html

Ruby: "Hello, #{name}!"
来源：http://dali.fengsongda.top/Article/details/gttezwuwns.html

C#:   $"Hello, {name}!"
来源：http://dali.yj202588.top/Article/details/gtlwzryywp.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.cashguo.top/Article/details/gtnkcpnujh.html

Py:   "第一行\n第二行"
来源：http://dali.kuanghao11.cn/Article/details/gtjwionksd.html

PHP:  "第一行\n第二行"
来源：http://dali.hnxiangtu.top/Article/details/gtgucwauqn.html

JS:   "第一行\n第二行"
来源：http://dali.hysaishi.cn/Article/details/gtlabbrmqx.html

TS:   "第一行\n第二行"
来源：http://dali.zhiwuduotai.top/Article/details/gtbzofjaul.html

Java: "第一行\n第二行"
来源：http://dali.nanxuanxn.top/Article/details/gtepwgiijo.html

Go:   "第一行\n第二行"
来源：http://dali.meibo888.top/Article/details/gtrreevtkk.html

Ruby: "第一行\n第二行"
来源：http://dali.ydzc1.top/Article/details/gtsiutfyxl.html

C#:   "第一行\n第二行"
来源：http://dali.chenlongwang.top/Article/details/gttagativn.html

[A14] 注释写法
来源：http://dali.wangdashe.top/Article/details/gtvazmzmxw.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.nanxinkj.top/Article/details/gtwhhvtrwa.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.gogol.net.cn/Article/details/gtrkxxwlui.html

JS:   // 单行；/* 多行 */
来源：http://dali.mhx1999.top/Article/details/gttybnksqw.html

TS:   // 单行；/* 多行 */
来源：http://dali.daxiang520.top/Article/details/gtrkpmtwwl.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.yueranfly.top/Article/details/gttqtgfytt.html

Go:   // 单行；/* 多行 */
来源：http://dali.tianlin.xyz/Article/details/gtdlgebivq.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.hnqzz.top/Article/details/gtgfuqoinz.html

C#:   // 单行；/* 多行 */
来源：http://dali.shuidangran.top/Article/details/gtrflumpio.html

[A15] 空值判断与默认值
来源：http://dali.aibaodan.cn/Article/details/gtcceaddzn.html

Py:   value = data or "默认值"
来源：http://dali.meibo888.top/Article/details/gtluagfwcg.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuqfoctjn.html

JS:   const value = data ?? "默认值";
来源：http://dali.shanyushiyangkeji.top/Article/details/gttbfftezc.html

TS:   const value = data ?? "默认值";
来源：http://dali.zycfv.cn/Article/details/gtlacxeyaz.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.guowangkeji.top/Article/details/gtbsbgvupp.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.mhx1999.top/Article/details/gtdbabhzfq.html

Ruby: value = data || "默认值"
来源：http://dali.ivvv.top/Article/details/gtiikzvncl.html

C#:   var value = data ?? "默认值";
来源：http://dali.quarkkingdee.top/Article/details/gtjsckneis.html

[A16] 真假值判断规则
来源：http://dali.dianchejie.cn/Article/details/gtghiwyivp.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.hywenlv.cn/Article/details/gtznqwtdjd.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.jyoumei.cn/Article/details/gtttupkhom.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.svipenyu.cn/Article/details/gtgnhhzdwr.html

TS:   if (!x) {}
来源：http://dali.jiagoushi.top/Article/details/gtqotpmdfn.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.yanxiufei.cn/Article/details/gtgimlwbxo.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.xuetiantiany.cn/Article/details/gtrofxlujh.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.jiagoushi.top/Article/details/gtsvanjiyj.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.fzhhl.top/Article/details/gttcwobcdl.html

[A17] 位运算
来源：http://dali.jinqigufen.top/Article/details/gtvgrhtxuv.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yangfankeji.com/Article/details/gtwrctkzah.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.cashguo.top/Article/details/gtebvgppce.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zycfv.cn/Article/details/gtvybkirpa.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.aizwys.cn/Article/details/gtvudaqxvt.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.pycfn.com/Article/details/gtgamnsnbp.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.smart0.xyz/Article/details/gtpfzbbliu.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.pengpengdd.cyou/Article/details/gtvpyejfhh.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gzhubu.top/Article/details/gtoywajuwc.html

[A18] 字符与 ASCII 码互转
来源：http://dali.zhiwuduotai.top/Article/details/gtuftnvzwb.html

Py:   ord("A"); chr(65)
来源：http://dali.cdnleiting.top/Article/details/gtqttplqqi.html

PHP:  ord("A"); chr(65)
来源：http://dali.nanxuanxn.top/Article/details/gtibxhvxap.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.wangshuangyany.cn/Article/details/gthuhzgjev.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.havefunace.top/Article/details/gticfgzyqb.html

Java: (int) 'A'; (char) 65
来源：http://dali.xuanzx.com/Article/details/gtoiptbvsa.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.jqgufenzy.top/Article/details/gtmvijuczu.html

Ruby: "A".ord; 65.chr
来源：http://dali.jinqigufen.top/Article/details/gtliosubgg.html

C#:   (int)'A'; (char)65
来源：http://dali.jianghu66.top/Article/details/gtmirginyq.html

[A19] 交换两个变量
来源：http://dali.gotoacloud.top/Article/details/gtwbcqqmts.html

Py:   a, b = b, a
来源：http://dali.gogol.net.cn/Article/details/gtxsfvbhka.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.jinqigufen.top/Article/details/gtobjcgirg.html

JS:   [a, b] = [b, a];
来源：http://dali.mhx1999.top/Article/details/gteednvare.html

TS:   [a, b] = [b, a];
来源：http://dali.zdqjudy.top/Article/details/gtovtwiyse.html

Java: int t = a; a = b; b = t;
来源：http://dali.yvedp.cn/Article/details/gtbroqbrwn.html

Go:   a, b = b, a
来源：http://dali.cucudq.cn/Article/details/gtblpixlww.html

Ruby: a, b = b, a
来源：http://dali.daxiang520.top/Article/details/gtaczzrpzo.html

C#:   (a, b) = (b, a);
来源：http://dali.chenzaomai.com/Article/details/gtvuaxmfny.html

[A20] 读取标准输入
来源：http://dali.shuidangran.top/Article/details/gtxwxtekxg.html

Py:   name = input("请输入：")
来源：http://dali.hnxiangtu.top/Article/details/gtnpkeakov.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.jlsjyb.cn/Article/details/gtllocmrqi.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.cdnleiting.top/Article/details/gtodpflhqo.html

TS:   // Node.js：readline 模块
来源：http://dali.ehwqpu.com/Article/details/gtzebjcqzq.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.tanke756.top/Article/details/gtdrpjhepq.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.gogol.net.cn/Article/details/gtykhexybx.html

Ruby: gets.chomp
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtifdkaysv.html

C#:   Console.ReadLine();
来源：http://dali.tianlin.xyz/Article/details/gtofwttvjw.html

[A21] 保留指定小数位输出
来源：http://dali.hnqzz.top/Article/details/gtvgmnsyee.html

Py:   f"{3.14159:.2f}"
来源：http://dali.fzhhl.top/Article/details/gtecukrklc.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.zhongyouzk.top/Article/details/gtjmrhmrtx.html

JS:   (3.14159).toFixed(2)
来源：http://dali.yj20258888.top/Article/details/gtbhbxeigq.html

TS:   (3.14159).toFixed(2)
来源：http://dali.hnqzz.top/Article/details/gtubsncpxr.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.sufxvd.cn/Article/details/gtcdpydjcp.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.316326.xyz/Article/details/gtchrbzhyt.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.tanke756.top/Article/details/gtiutirsap.html

C#:   3.14159.ToString("F2")
来源：http://dali.birdmap.top/Article/details/gtnctxitur.html

[A22] 获取字符串长度
来源：http://dali.hnxiangtu.top/Article/details/gtnzwvbcgl.html

Py:   len(s)
来源：http://dali.fengsongda.top/Article/details/gtkugnsgfu.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.cdnleiting.top/Article/details/gtydklegba.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgvstduum.html

TS:   s.length
来源：http://dali.yangfankeji.com/Article/details/gtkgzsuhky.html

Java: s.length()
来源：http://dali.yonumen.top/Article/details/gtnrjuuxea.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.sweek.top/Article/details/gtyxddkilk.html

Ruby: s.length
来源：http://dali.nanxinkj.top/Article/details/gtcrxsxiue.html

C#:   s.Length
来源：http://dali.yangfankeji.com/Article/details/gtqskvqfap.html

[A23] 大小写转换
来源：http://dali.cqqwz.cn/Article/details/gtmumndlaq.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.shzxlz.cn/Article/details/gtyyzpusly.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.xinyue.icu/Article/details/gtrdwzbcaq.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jinghuilouyu.cn/Article/details/gtbawwihkc.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.hfpthk.cn/Article/details/gtseafntvx.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.jianghu66.top/Article/details/gtpntdnbux.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.yuanzhike.top/Article/details/gtrhptjnjb.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.tianlin.xyz/Article/details/gtrdqsvmpr.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.pycfn.com/Article/details/gtpdtscujm.html

[A24] 去除首尾空白
来源：http://dali.shzxlz.cn/Article/details/gtwxyascdv.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.jqgfzy.top/Article/details/gtoiydhhmi.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.aizwys.cn/Article/details/gtexxeeckp.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.chenzaomai.com/Article/details/gtdwcklezn.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.nanxuanxn.top/Article/details/gtatvpkmfu.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.havefunace.top/Article/details/gtgrpffrfg.html

Go:   strings.TrimSpace(s)
来源：http://dali.mhx1999.top/Article/details/gtcfdeexza.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yongpay.top/Article/details/gtumgqvhsw.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jinqigfzy.top/Article/details/gtmbjhselw.html

[A25] 字符串比较
来源：http://dali.fzhhl.top/Article/details/gtuiwwffyr.html

Py:   s1 == s2; s1 != s2
来源：http://dali.c1oappe.top/Article/details/gtcbqjskog.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.cashguo.top/Article/details/gthwajkfih.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.daria6918.cn/Article/details/gtgirpnvjf.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yvedp.cn/Article/details/gtepnbchui.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yj20258.top/Article/details/gtplrjgajp.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.chenlongwang.top/Article/details/gtgxurtwfu.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.xuanzx.com/Article/details/gtisszyjtw.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yuanzhike.top/Article/details/gtirasdine.html

[A26] 类型转换总览
来源：http://dali.guannengcc.top/Article/details/gtayvvfqvn.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.chenjidiqi.icu/Article/details/gteleskfky.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.sweek.top/Article/details/gtqpzltrij.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yanxiufei.cn/Article/details/gttegtjtsd.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zhijiandao.cn/Article/details/gttppgnkoq.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.gaohongyu789.top/Article/details/gtfrzbqopb.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.cucudq.cn/Article/details/gtnppnorlc.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.cdnleiting.top/Article/details/gtnytvwqza.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.guannengcc.top/Article/details/gtjdowupvr.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtxxyqtdxx.html

B. 流程控制
来源：http://dali.sysykeji.top/Article/details/gtexmopodn.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtgkhlsoor.html

[B01] 条件判断 if / else
来源：http://dali.jqgfzy.top/Article/details/gtldypldlc.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.fengsongda.top/Article/details/gtcpuiqglj.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.tianlin.xyz/Article/details/gtdxnfzttz.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.chenlongwang.top/Article/details/gtouaulxcr.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jlsjyb.cn/Article/details/gtutbzdujt.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.sxryk.cn/Article/details/gtrylucmxb.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.smart0.xyz/Article/details/gtffpwxspq.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.cqqwz.cn/Article/details/gtukjwaolk.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.yuanzhike.top/Article/details/gtyegzwtvl.html

[B02] 多分支 else if / elif
来源：http://dali.zhongyouzk.top/Article/details/gtiylhdyzu.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.smart0.xyz/Article/details/gtmbsdnvnz.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.shzxlz.cn/Article/details/gtsqqwgqud.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.dashuyun.cn/Article/details/gtbtxydant.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fengsongda.top/Article/details/gtwhkxprfe.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj202588.top/Article/details/gtjsdjdinu.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.zhiwuduotai.top/Article/details/gtjunbqogk.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.birdmap.top/Article/details/gtwclfbkuk.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gzhubu.top/Article/details/gtvteputiy.html

[B03] switch / match / case
来源：http://dali.quarkkingdee.top/Article/details/gtlprugtin.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zhiwuduotai.top/Article/details/gtnbgnyruu.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.redwolf501.top/Article/details/gtskirmtwq.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.iojbl.cn/Article/details/gtkypkonbv.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jqgfzy.top/Article/details/gttmlkjwjk.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtintayhmo.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.ehwqpu.com/Article/details/gtagjbxswn.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.jianghu66.top/Article/details/gtzldvjhyg.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.hammf.cn/Article/details/gthrwgwsvj.html

[B04] for 计数循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtmuzgapkk.html

Py:   for i in range(10): print(i)
来源：http://dali.jinqigfzy.top/Article/details/gtsnfjvuui.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jyoumei.cn/Article/details/gtazygrxvx.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.nwbrower.top/Article/details/gtfgipymro.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yj202588.top/Article/details/gtawlrmdor.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yueranfly.top/Article/details/gtdxnitlcs.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.zhijiandao.cn/Article/details/gtvsczymah.html

Ruby: 10.times { |i| puts i }
来源：http://dali.0kj1m.cn/Article/details/gtbpihwuln.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.daria6918.cn/Article/details/gtqgsmlthd.html

[B05] 遍历数组 / 列表
来源：http://dali.jlsjyb.cn/Article/details/gtmhwajmge.html

Py:   for item in arr: print(item)
来源：http://dali.ydzc1.top/Article/details/gtdjrnaafa.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.iojbl.cn/Article/details/gttfxmrkfz.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.hammf.cn/Article/details/gtdhnmtqej.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhongyouzk.top/Article/details/gtcuifmcua.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgnvidfbe.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.chenlongwang.top/Article/details/gtygjykxcn.html

Ruby: arr.each { |item| puts item }
来源：http://dali.tanke756.top/Article/details/gtivqasgpe.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.birdmap.top/Article/details/gtdsyvmona.html

[B06] 遍历字典 / 对象
来源：http://dali.iojbl.cn/Article/details/gtocaahcpa.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yongpay.top/Article/details/gtnyvvaoib.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zhijiandao.cn/Article/details/gtucgkjyqg.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.meibo888.top/Article/details/gtljporznx.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cashguo.top/Article/details/gtkrpagdvj.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhongyouzk.top/Article/details/gttiywpdky.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.guannengcc.top/Article/details/gtrejslbvq.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.fengsongda.top/Article/details/gtgscfalvt.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jqgfzy.top/Article/details/gtqzivapcr.html

[B07] while 循环
来源：http://dali.bjfxy.top/Article/details/gtmmoohrrr.html

Py:   while i < 10: i += 1
来源：http://dali.xziqi.cn/Article/details/gtaberlwjz.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.tianlin.xyz/Article/details/gtoaxgjnpd.html

JS:   while (i < 10) { i++; }
来源：http://dali.cashguo.top/Article/details/gtqonabucv.html

TS:   while (i < 10) { i++; }
来源：http://dali.hfpthk.cn/Article/details/gtvvhrqwky.html

Java: while (i < 10) { i++; }
来源：http://dali.jinqigufen.top/Article/details/gttscscfkj.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.aizwys.cn/Article/details/gtjrevwbwl.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jinqigufen.top/Article/details/gtlezordwl.html

C#:   while (i < 10) { i++; }
来源：http://dali.hammf.cn/Article/details/gtxqmezqht.html

[B08] do-while（至少执行一次）
来源：http://dali.xylfe.cn/Article/details/gtsclvoxyg.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.xuanzx.com/Article/details/gtnshqjpmz.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.sufxvd.cn/Article/details/gtbpblxpyr.html

JS:   do { i++; } while (i < 10);
来源：http://dali.0kj1m.cn/Article/details/gtdcoftnno.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jianghu66.top/Article/details/gtqnnihuzf.html

Java: do { i++; } while (i < 10);
来源：http://dali.jqgufenzy.top/Article/details/gtknavvbiv.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhixingplan.top/Article/details/gtusgmzpkg.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.pycfn.com/Article/details/gtapbziclm.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zycfv.cn/Article/details/gtqqktdgpu.html

[B09] break 与 continue
来源：http://dali.smart0.xyz/Article/details/gtysbynaft.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yonumen.top/Article/details/gtwggaydrg.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.pengpengdd.cyou/Article/details/gtvwbozwys.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xinyue.icu/Article/details/gtkxxibbvz.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gogol.net.cn/Article/details/gtzttbgxnj.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yangfankeji.com/Article/details/gtufsxtmli.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.gotoacloud.top/Article/details/gtldxnwyqu.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.tianlin.xyz/Article/details/gtxsizlcyd.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.smart0.xyz/Article/details/gtqnuemmpl.html

[B10] 遍历同时拿索引
来源：http://dali.mhx1999.top/Article/details/gtrivokqcj.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.hfpthk.cn/Article/details/gtlszisvsl.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yuanzhike.top/Article/details/gtjklbrpgn.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.guannengcc.top/Article/details/gtxknopurz.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jinghuilouyu.cn/Article/details/gtwaplnkhb.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yanxiufei.cn/Article/details/gtijxbdaal.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.redwolf501.top/Article/details/gtcgbxyqai.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzaixtksh.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhongyouzk.top/Article/details/gthhltjkmz.html

[B11] 生成数字序列 / 区间
来源：http://dali.guannengcc.top/Article/details/gtouvenqqq.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhiwuduotai.top/Article/details/gtczqpxjbd.html

PHP:  range(0, 10, 2);
来源：http://dali.zhixingplan.top/Article/details/gthrjxbkee.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.tian-w.cn/Article/details/gtlnyhjwon.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.nwbrower.top/Article/details/gtuxnivqfx.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.xylfe.cn/Article/details/gtqncbethd.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnzgnrvcl.html

Ruby: (0...10).step(2).to_a
来源：http://dali.feifeiyinyue.top/Article/details/gttegpbchp.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.guannengcc.top/Article/details/gtybwuxccv.html

[B12] 跳出多层循环
来源：http://dali.0kj1m.cn/Article/details/gtobimarfe.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.hongshengwenyu.top/Article/details/gtfhpyohvz.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcazqrael.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigfzy.top/Article/details/gttiptepde.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yuxming.cn/Article/details/gttsvbidwz.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gtmcxmtmpr.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.dashuyun.cn/Article/details/gtjxpnsniu.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.sweek.top/Article/details/gtwyvmwvjv.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.sxryk.cn/Article/details/gtwgegndzk.html

[B13] 判断是否为数字
来源：http://dali.chenjidiqi.icu/Article/details/gtiulmzuhb.html

Py:   isinstance(x, (int, float))
来源：http://dali.nanxinkj.top/Article/details/gtjlwlxnrk.html

PHP:  is_numeric($x)
来源：http://dali.yvedp.cn/Article/details/gtuxmqbezg.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.snrcjt.cn/Article/details/gtbzjhyikp.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.c1oappe.top/Article/details/gtslpsneav.html

Java: x instanceof Number
来源：http://dali.jiagoushi.top/Article/details/gtqhlqdmuy.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cqqwz.cn/Article/details/gtjlfmxneq.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xuetiantiany.cn/Article/details/gtwmflxqau.html

C#:   x is int or double or decimal
来源：http://dali.nanxinkj.top/Article/details/gtlswqrycx.html

[B14] 判断值是否在集合内
来源：http://dali.bjfxy.top/Article/details/gtksavrkco.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.bjfxy.top/Article/details/gtuiuvawql.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.sweek.top/Article/details/gtvrbaxxba.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.wangdashe.top/Article/details/gtryvbstrh.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.tianlin.xyz/Article/details/gtrutwbyyj.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.0kj1m.cn/Article/details/gtrxrnrgel.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hywenlv.cn/Article/details/gtimcusgtp.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.dashuyun.cn/Article/details/gtvprslnsz.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.daria6918.cn/Article/details/gtnepvhhge.html

[B15] 布尔运算与取反
来源：http://dali.yueranfly.top/Article/details/gtgzuosvbc.html

Py:   a and b or not c
来源：http://dali.xuetiantiany.cn/Article/details/gtiwqbfrhk.html

PHP:  $a && $b || !$c
来源：http://dali.nanxuanxn.top/Article/details/gtrsseehuv.html

JS:   a && b || !c
来源：http://dali.sweek.top/Article/details/gtrorffxbt.html

TS:   a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gtsjfpamdj.html

Java: a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gtbhrhwdoz.html

Go:   a && b || !c
来源：http://dali.cucudq.cn/Article/details/gtmvpnlagi.html

Ruby: a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gteyotxfcw.html

C#:   a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gtzdgbshpd.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.guannengcc.top/Article/details/gtmucyhrwm.html

Py:   if not data: return
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpximmuyu.html

PHP:  if (!$data) { return; }
来源：http://dali.cucudq.cn/Article/details/gtbdvvwdgi.html

JS:   if (!data) return;
来源：http://dali.yj20258888.top/Article/details/gtjcbagvmh.html

TS:   if (!data) return;
来源：http://dali.nwbrower.top/Article/details/gtkhbqfnng.html

Java: if (data == null) return;
来源：http://dali.quarkkingdee.top/Article/details/gtognibmvx.html

Go:   if data == nil { return }
来源：http://dali.hywenlv.cn/Article/details/gtesljhpvc.html

Ruby: return if data.nil?
来源：http://dali.jinqigfzy.top/Article/details/gttfkjrwkn.html

C#:   if (data == null) return;
来源：http://dali.zdqjudy.top/Article/details/gtfmxhzjyf.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtkccfmhha.html

C. 函数与作用域
来源：http://dali.zhoulong.xyz/Article/details/gtcprxjsdb.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtjrbfybgy.html

[C01] 定义函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwngebrfm.html

Py:   def add(a, b): return a + b
来源：http://dali.shzxlz.cn/Article/details/gtcxrletvr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.0kj1m.cn/Article/details/gtiyqzboat.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gttmrrtddf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gttjjttdia.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gtlvtygkvy.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.havefunace.top/Article/details/gtlhlslsan.html

Ruby: def add(a, b); a + b; end
来源：http://dali.aibaodan.cn/Article/details/gtbajfnopx.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gtschnrcgx.html

[C02] 默认参数
来源：http://dali.zhoulong.xyz/Article/details/gtcyghnpap.html

Py:   def greet(name="World"): return name
来源：http://dali.haohaochexian.top/Article/details/gtdxlqdpqa.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.cdnleiting.top/Article/details/gtplrufurb.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.c1oappe.top/Article/details/gtsiksvhbh.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.wangdashe.top/Article/details/gtpddjeawm.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.shuidangran.top/Article/details/gtgvipfrod.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hfpthk.cn/Article/details/gtudibewxj.html

Ruby: def greet(name = "World") = name
来源：http://dali.meibo888.top/Article/details/gtpagiftgr.html


<!-- 参考信息 -->