代发 wailian999

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.316326.xyz/Article/details/gtfrmfeuhb.html

JS:   `Hello, ${name}!`
来源：http://dali.ydzc1.top/Article/details/gtpouvlagl.html

TS:   `Hello, ${name}!`
来源：http://dali.zhengqikj.top/Article/details/gtnbgkzwhp.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.snrcjt.cn/Article/details/gtlniymmhm.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.fengsongda.top/Article/details/gtygclfijs.html

Ruby: "Hello, #{name}!"
来源：http://dali.ivvv.top/Article/details/gtpigefpuj.html

C#:   $"Hello, {name}!"
来源：http://dali.xylfe.cn/Article/details/gtnyizdyna.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.guowangkeji.top/Article/details/gtbntkrsav.html

Py:   "第一行\n第二行"
来源：http://dali.yonumen.top/Article/details/gtwhfvaqqt.html

PHP:  "第一行\n第二行"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjtnoczmh.html

JS:   "第一行\n第二行"
来源：http://dali.svipenyu.cn/Article/details/gtzzzmzfnx.html

TS:   "第一行\n第二行"
来源：http://dali.9152youxi.cn/Article/details/gtnjmerpbc.html

Java: "第一行\n第二行"
来源：http://dali.pycfn.com/Article/details/gtacobpsxc.html

Go:   "第一行\n第二行"
来源：http://dali.xylfe.cn/Article/details/gtkozgdbbg.html

Ruby: "第一行\n第二行"
来源：http://dali.yuanzhike.top/Article/details/gtvoyalpdj.html

C#:   "第一行\n第二行"
来源：http://dali.yueranfly.top/Article/details/gtfsbztbuj.html

[A14] 注释写法
来源：http://dali.jinghuilouyu.cn/Article/details/gtomezhvfy.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.pengpengdd.cyou/Article/details/gtrucbeknu.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.c1oappe.top/Article/details/gtjypicjcg.html

JS:   // 单行；/* 多行 */
来源：http://dali.sufxvd.cn/Article/details/gtatdnvwpn.html

TS:   // 单行；/* 多行 */
来源：http://dali.yangfankeji.com/Article/details/gtrkrcijxc.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.guowangkeji.top/Article/details/gteselvdmp.html

Go:   // 单行；/* 多行 */
来源：http://dali.zdqjudy.top/Article/details/gtuxigakjs.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.feifeiyinyue.top/Article/details/gtdgjduhos.html

C#:   // 单行；/* 多行 */
来源：http://dali.ybcxt.top/Article/details/gtkpkufzew.html

[A15] 空值判断与默认值
来源：http://dali.yuanzhike.top/Article/details/gtnyluosek.html

Py:   value = data or "默认值"
来源：http://dali.yanxiufei.cn/Article/details/gtyjnayvsf.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.sysykeji.top/Article/details/gtbtgaaxmh.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhongyouzk.top/Article/details/gtvbndzkcq.html

TS:   const value = data ?? "默认值";
来源：http://dali.cdnleiting.top/Article/details/gtqoiddgsh.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.andypj.xyz/Article/details/gtpffpyyoo.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.daria6918.cn/Article/details/gtxcyayhqn.html

Ruby: value = data || "默认值"
来源：http://dali.sweek.top/Article/details/gtztuiiouw.html

C#:   var value = data ?? "默认值";
来源：http://dali.jqgfzy.top/Article/details/gtihnmgxvg.html

[A16] 真假值判断规则
来源：http://dali.chenlongwang.top/Article/details/gtezkbnksu.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.havefunace.top/Article/details/gtarfzphsv.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.hywenlv.cn/Article/details/gtemejtezl.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.sxryk.cn/Article/details/gtvtamkxxn.html

TS:   if (!x) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsftaiuzn.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.shuidangran.top/Article/details/gtbnyrmjhm.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.ydzc1.top/Article/details/gtltwrafvu.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.jqgfzy.top/Article/details/gtcjgxwgkg.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.nanxinkj.top/Article/details/gtnjangygf.html

[A17] 位运算
来源：http://dali.9152youxi.cn/Article/details/gtdwtdscnw.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.snrcjt.cn/Article/details/gtgjtllabd.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.quarkkingdee.top/Article/details/gtbgijobxt.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhengqikj.top/Article/details/gtexliophj.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.cashguo.top/Article/details/gtlysmegpp.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tanke756.top/Article/details/gtteyvgyjb.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.shangyingyoupin.top/Article/details/gtbeanavqn.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sxryk.cn/Article/details/gtpcennrlt.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.smart0.xyz/Article/details/gtvjztzzuo.html

[A18] 字符与 ASCII 码互转
来源：http://dali.shuidangran.top/Article/details/gtbkqkqyoy.html

Py:   ord("A"); chr(65)
来源：http://dali.wangdashe.top/Article/details/gttgpohjpl.html

PHP:  ord("A"); chr(65)
来源：http://dali.guowangkeji.top/Article/details/gtksrrswow.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtecwopoic.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.c1oappe.top/Article/details/gtddnsfbkl.html

Java: (int) 'A'; (char) 65
来源：http://dali.pengpengdd.cyou/Article/details/gtjiuxposu.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.gaohongyu789.top/Article/details/gthfhfkqst.html

Ruby: "A".ord; 65.chr
来源：http://dali.gaohongyu789.top/Article/details/gtqiyvkpzd.html

C#:   (int)'A'; (char)65
来源：http://dali.mhx1999.top/Article/details/gtxmffuror.html

[A19] 交换两个变量
来源：http://dali.zdqjudy.top/Article/details/gttlinvtrf.html

Py:   a, b = b, a
来源：http://dali.gzhubu.top/Article/details/gtffkknrvx.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.nanxuanxn.top/Article/details/gtqkldwwnv.html

JS:   [a, b] = [b, a];
来源：http://dali.snrcjt.cn/Article/details/gtlhqbaxog.html

TS:   [a, b] = [b, a];
来源：http://dali.guowangkeji.top/Article/details/gtskvhehxt.html

Java: int t = a; a = b; b = t;
来源：http://dali.yongpay.top/Article/details/gtvmlbmxno.html

Go:   a, b = b, a
来源：http://dali.aibaodan.cn/Article/details/gtcwpbgebb.html

Ruby: a, b = b, a
来源：http://dali.hnqzz.top/Article/details/gtccijmdfl.html

C#:   (a, b) = (b, a);
来源：http://dali.chenjidiqi.icu/Article/details/gtnthtkjuz.html

[A20] 读取标准输入
来源：http://dali.yuxming.cn/Article/details/gtgkzbbyyg.html

Py:   name = input("请输入：")
来源：http://dali.hnqzz.top/Article/details/gtmokgrvgn.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.andypj.xyz/Article/details/gtfoetxtph.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.hnqzz.top/Article/details/gtgqfikxgp.html

TS:   // Node.js：readline 模块
来源：http://dali.fzhhl.top/Article/details/gtkngghgcm.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.dashuyun.cn/Article/details/gtxixtsmfd.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.gotoacloud.top/Article/details/gtavoqxqqe.html

Ruby: gets.chomp
来源：http://dali.hnxiangtu.top/Article/details/gtnmbupwsk.html

C#:   Console.ReadLine();
来源：http://dali.nwbrower.top/Article/details/gtkrwzeijs.html

[A21] 保留指定小数位输出
来源：http://dali.jinghuilouyu.cn/Article/details/gtnoyygsfb.html

Py:   f"{3.14159:.2f}"
来源：http://dali.shangyingyoupin.top/Article/details/gtpxbitgwc.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.zdqjudy.top/Article/details/gtkajjazzo.html

JS:   (3.14159).toFixed(2)
来源：http://dali.hnxiangtu.top/Article/details/gttbdwmphl.html

TS:   (3.14159).toFixed(2)
来源：http://dali.daria6918.cn/Article/details/gtbcqzihlz.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmkufnqhg.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.tianlin.xyz/Article/details/gtelembfpt.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.jyoumei.cn/Article/details/gtxsrmiqzx.html

C#:   3.14159.ToString("F2")
来源：http://dali.tianlin.xyz/Article/details/gtwegoqcue.html

[A22] 获取字符串长度
来源：http://dali.shuidangran.top/Article/details/gtxehrzdda.html

Py:   len(s)
来源：http://dali.yuxming.cn/Article/details/gtoqkkvxvy.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.zycfv.cn/Article/details/gtoludgrep.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.chenzaomai.com/Article/details/gtrkqqumss.html

TS:   s.length
来源：http://dali.zdqjudy.top/Article/details/gtrfkkagkh.html

Java: s.length()
来源：http://dali.iojbl.cn/Article/details/gtzlnjzkjp.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.ydzc1.top/Article/details/gtnaupzhzb.html

Ruby: s.length
来源：http://dali.jlsjyb.cn/Article/details/gtfurseadx.html

C#:   s.Length
来源：http://dali.yangfankeji.com/Article/details/gtoiwkorxt.html

[A23] 大小写转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtwkocfylz.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.yonumen.top/Article/details/gtphkbouqe.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.sxryk.cn/Article/details/gtpebgdcqp.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.chenlongwang.top/Article/details/gtmfkxnxrr.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.feifeiyinyue.top/Article/details/gtrykyatgz.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.zdqjudy.top/Article/details/gtgiersmxi.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.hywenlv.cn/Article/details/gtgfyxrlrx.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.yj20258888.top/Article/details/gtghklcyht.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.sxryk.cn/Article/details/gtumtqdnvj.html

[A24] 去除首尾空白
来源：http://dali.jqgfzy.top/Article/details/gtfsytcqfg.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.snrcjt.cn/Article/details/gtrqqortum.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.cheryme.top/Article/details/gtornlzyxi.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.cqqwz.cn/Article/details/gtrkinhmbq.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.gotoacloud.top/Article/details/gtkbbeggce.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.guowangkeji.top/Article/details/gtghrzwlgx.html

Go:   strings.TrimSpace(s)
来源：http://dali.yj20258.top/Article/details/gtgdryocfd.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.ybcxt.top/Article/details/gtghjbvfee.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.aizwys.cn/Article/details/gtynnimhya.html

[A25] 字符串比较
来源：http://dali.ivvv.top/Article/details/gtietuobvx.html

Py:   s1 == s2; s1 != s2
来源：http://dali.ppjwa.cn/Article/details/gtndopbeov.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yj202588.top/Article/details/gtewtkotgv.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jqgufenzy.top/Article/details/gtedwwjads.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jinqigufen.top/Article/details/gtinvdjbvo.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.jinqigfzy.top/Article/details/gtpgdygugl.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.shzxlz.cn/Article/details/gtgidilpjv.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.feifeiyinyue.top/Article/details/gttiueiquq.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.sweek.top/Article/details/gtcsbtyynv.html

[A26] 类型转换总览
来源：http://dali.yuanzhike.top/Article/details/gtvrkwxfws.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.c1oappe.top/Article/details/gthdlhuhvj.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.sufxvd.cn/Article/details/gtmfgmcocf.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.ppjwa.cn/Article/details/gtsvdkvycf.html

TS:   Number() String() Boolean() x as number
来源：http://dali.shuidangran.top/Article/details/gtthveelgs.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.hammf.cn/Article/details/gtckwswepp.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.hongshengwenyu.top/Article/details/gtueuipsho.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.hnxiangtu.top/Article/details/gtxonouqmf.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zhijiandao.cn/Article/details/gtcqjhozos.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gticpsuiol.html

B. 流程控制
来源：http://dali.zhijiandao.cn/Article/details/gtqzbqxwqt.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtbhrdsrta.html

[B01] 条件判断 if / else
来源：http://dali.andypj.xyz/Article/details/gtjnzqbbmg.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.jqgufenzy.top/Article/details/gtdrkhxsoj.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.andypj.xyz/Article/details/gtotpnnmon.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.smart0.xyz/Article/details/gtzxdkxgqy.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xylfe.cn/Article/details/gtcpwpwfyb.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.ydzc1.top/Article/details/gtebukfjew.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.nanxinkj.top/Article/details/gtcvpwqylt.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.gotoacloud.top/Article/details/gtuppzykwl.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.yj20258.top/Article/details/gtaiitiqqc.html

[B02] 多分支 else if / elif
来源：http://dali.chenjidiqi.icu/Article/details/gtzmdqfuvr.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.wangdashe.top/Article/details/gtfwhyirmx.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.jiagoushi.top/Article/details/gttosekizj.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xziqi.cn/Article/details/gtmdtaddei.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tian-w.cn/Article/details/gtygarnqwd.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yonumen.top/Article/details/gtzdpxsuws.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.meibo888.top/Article/details/gtlvxqchmv.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.cashguo.top/Article/details/gtequmhqmz.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sweek.top/Article/details/gtfyegrocx.html

[B03] switch / match / case
来源：http://dali.chenlongwang.top/Article/details/gtsofnpiyz.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.9152youxi.cn/Article/details/gtywftovtt.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.cqqwz.cn/Article/details/gtmovmpwim.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yj20258888.top/Article/details/gtirqkzegh.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtpbmlayzu.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.ydzc1.top/Article/details/gtfsyqipqz.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.zdqjudy.top/Article/details/gtrgsbobam.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.yj202588.top/Article/details/gtookfrjgy.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.ehwqpu.com/Article/details/gtubjcgere.html

[B04] for 计数循环
来源：http://dali.fengsongda.top/Article/details/gtrpiswqyd.html

Py:   for i in range(10): print(i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyxyhlvwb.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.sysykeji.top/Article/details/gterlgebjt.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hnxiangtu.top/Article/details/gtltxtewvt.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.svipenyu.cn/Article/details/gtkhsnwzvn.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.cucudq.cn/Article/details/gtpfaylmdf.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.gogol.net.cn/Article/details/gtajcoguzd.html

Ruby: 10.times { |i| puts i }
来源：http://dali.shangyingyoupin.top/Article/details/gtmyseabrs.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yj20258888.top/Article/details/gtryhphefi.html

[B05] 遍历数组 / 列表
来源：http://dali.yueranfly.top/Article/details/gtliftqtcb.html

Py:   for item in arr: print(item)
来源：http://dali.xinyue.icu/Article/details/gtswalqunn.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.nwbrower.top/Article/details/gtwikppmhx.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.bjfxy.top/Article/details/gtxqawwjun.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yvedp.cn/Article/details/gtzzgkthuu.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hongshengwenyu.top/Article/details/gthnqsgwfw.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jqgufenzy.top/Article/details/gtcehdoinx.html

Ruby: arr.each { |item| puts item }
来源：http://dali.jqgufenzy.top/Article/details/gtxjrdsoug.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.ehwqpu.com/Article/details/gtjnhxwqtu.html

[B06] 遍历字典 / 对象
来源：http://dali.jinghuilouyu.cn/Article/details/gtwtkcezun.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.cqqwz.cn/Article/details/gtvbvgkeig.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.redwolf501.top/Article/details/gtaltipusl.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.feifeiyinyue.top/Article/details/gtqkxbfcxm.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxvemkmjt.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jianghu66.top/Article/details/gtinzlpcxw.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yj202588.top/Article/details/gtjjnfhjzd.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.kuanghao11.cn/Article/details/gtjdhijavu.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.tanke756.top/Article/details/gtqzikenah.html

[B07] while 循环
来源：http://dali.daxiang520.top/Article/details/gttuqfjxry.html

Py:   while i < 10: i += 1
来源：http://dali.yueranfly.top/Article/details/gtyqxnozmg.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jianghu66.top/Article/details/gtcgwxuicu.html

JS:   while (i < 10) { i++; }
来源：http://dali.yuxming.cn/Article/details/gtixtsuoqr.html

TS:   while (i < 10) { i++; }
来源：http://dali.gzhubu.top/Article/details/gtwldbirhi.html

Java: while (i < 10) { i++; }
来源：http://dali.zhiwuduotai.top/Article/details/gtcfqsnmch.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.guowangkeji.top/Article/details/gtgrympdrl.html

Ruby: while i < 10; i += 1; end
来源：http://dali.9152youxi.cn/Article/details/gtunjrvzuo.html

C#:   while (i < 10) { i++; }
来源：http://dali.haohaochexian.top/Article/details/gtvlzaxqfi.html

[B08] do-while（至少执行一次）
来源：http://dali.vqdsnc.cn/Article/details/gtwntohmnw.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jinyuanbaomall.cn/Article/details/gtukxrgvpp.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yvedp.cn/Article/details/gtegcmeiwk.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jiagoushi.top/Article/details/gtecdrpbqn.html

TS:   do { i++; } while (i < 10);
来源：http://dali.ydzc1.top/Article/details/gtjsoyippv.html

Java: do { i++; } while (i < 10);
来源：http://dali.nanxuanxn.top/Article/details/gtizpziwfx.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhixingplan.top/Article/details/gtsegxbgri.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.quarkkingdee.top/Article/details/gtioshgsfs.html

C#:   do { i++; } while (i < 10);
来源：http://dali.vqdsnc.cn/Article/details/gtmwlolljl.html

[B09] break 与 continue
来源：http://dali.yuxming.cn/Article/details/gtviczdpkf.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.cheryme.top/Article/details/gttvycsnpg.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.ehwqpu.com/Article/details/gtuhnlcjpm.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.bjfxy.top/Article/details/gtmxudvqwr.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhoulong.xyz/Article/details/gtbddebslv.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zdqjudy.top/Article/details/gtdjwuszbe.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.pycfn.com/Article/details/gtjqwxywvq.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.sweek.top/Article/details/gttwnnvnqu.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cheryme.top/Article/details/gtbjznrzyi.html

[B10] 遍历同时拿索引
来源：http://dali.zhiwuduotai.top/Article/details/gtcwdtlvtb.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yueranfly.top/Article/details/gtjffsruxe.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.hysaishi.cn/Article/details/gtzbbgsmfx.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.nwbrower.top/Article/details/gtiskyzrms.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.ivvv.top/Article/details/gtrcrghojd.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.sweek.top/Article/details/gtdmcfxpyn.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.aibaodan.cn/Article/details/gthsknsrly.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.dianchejie.cn/Article/details/gtbdtoruzp.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.haohaochexian.top/Article/details/gtpthgretl.html

[B11] 生成数字序列 / 区间
来源：http://dali.nanxinkj.top/Article/details/gtrjezivfj.html

Py:   list(range(0, 10, 2))
来源：http://dali.jyoumei.cn/Article/details/gtvhpzldnz.html

PHP:  range(0, 10, 2);
来源：http://dali.hnqzz.top/Article/details/gtaekuelzj.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cdnleiting.top/Article/details/gtrterftzj.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.birdmap.top/Article/details/gteytunski.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtetzldouq.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.gotoacloud.top/Article/details/gtxhnnuxga.html

Ruby: (0...10).step(2).to_a
来源：http://dali.aibaodan.cn/Article/details/gtekdfahoa.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.chenzaomai.com/Article/details/gtnxijkuzp.html

[B12] 跳出多层循环
来源：http://dali.hnxiangtu.top/Article/details/gtbptkqaeq.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.guannengcc.top/Article/details/gtwdufaner.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.shzxlz.cn/Article/details/gtcptqrfll.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yueranfly.top/Article/details/gtpkdrwxqs.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gtvzrndhpq.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.nwbrower.top/Article/details/gtadcnwafz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jinqigfzy.top/Article/details/gtpnbhkhra.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yanxiufei.cn/Article/details/gtvwiavyus.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yonumen.top/Article/details/gtwesrwojw.html

[B13] 判断是否为数字
来源：http://dali.cashguo.top/Article/details/gtxwqbqbip.html

Py:   isinstance(x, (int, float))
来源：http://dali.gotoacloud.top/Article/details/gtwmxbgieb.html

PHP:  is_numeric($x)
来源：http://dali.yanxiufei.cn/Article/details/gtupathiqf.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ehwqpu.com/Article/details/gtmoezifmo.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj20258.top/Article/details/gtysnuudgv.html

Java: x instanceof Number
来源：http://dali.yonumen.top/Article/details/gtgsrlktmu.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yanxiufei.cn/Article/details/gthwbwbfzi.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yangfankeji.com/Article/details/gthefbidlh.html

C#:   x is int or double or decimal
来源：http://dali.ehwqpu.com/Article/details/gttlbxcvdl.html

[B14] 判断值是否在集合内
来源：http://dali.jianghu66.top/Article/details/gtgxwjmjof.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yanxiufei.cn/Article/details/gtowyytkir.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.andypj.xyz/Article/details/gtcwvkorji.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.ppjwa.cn/Article/details/gtmtbaqnqh.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.nanxuanxn.top/Article/details/gtmakpyytp.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.xuanzx.com/Article/details/gtcogpyqkq.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hammf.cn/Article/details/gtkizmkber.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.dianchejie.cn/Article/details/gtflktohbn.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gtvsesttzm.html

[B15] 布尔运算与取反
来源：http://dali.chenlongwang.top/Article/details/gtgsmtwbdm.html

Py:   a and b or not c
来源：http://dali.dashuyun.cn/Article/details/gtzjnzesdu.html

PHP:  $a && $b || !$c
来源：http://dali.gaohongyu789.top/Article/details/gtmufbopnx.html

JS:   a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gtkkfntuyu.html

TS:   a && b || !c
来源：http://dali.birdmap.top/Article/details/gtgkyqmxpb.html

Java: a && b || !c
来源：http://dali.andypj.xyz/Article/details/gtjztjroip.html

Go:   a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gtwblphnyr.html

Ruby: a && b || !c
来源：http://dali.snrcjt.cn/Article/details/gtzorbqppl.html

C#:   a && b || !c
来源：http://dali.yongpay.top/Article/details/gtfqrjqkeo.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jiagoushi.top/Article/details/gtulxlpewi.html

Py:   if not data: return
来源：http://dali.jiagoushi.top/Article/details/gtphrtrxxz.html

PHP:  if (!$data) { return; }
来源：http://dali.xuetiantiany.cn/Article/details/gtuypcsslr.html

JS:   if (!data) return;
来源：http://dali.kuanghao11.cn/Article/details/gtfoantauv.html

TS:   if (!data) return;
来源：http://dali.zdqjudy.top/Article/details/gtfslpppbi.html

Java: if (data == null) return;
来源：http://dali.yuxming.cn/Article/details/gtobyznbfs.html

Go:   if data == nil { return }
来源：http://dali.svipenyu.cn/Article/details/gtrwofocoy.html

Ruby: return if data.nil?
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfunlfurb.html

C#:   if (data == null) return;
来源：http://dali.316326.xyz/Article/details/gtvblfcdze.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtcqkecsdq.html

C. 函数与作用域
来源：http://dali.yongpay.top/Article/details/gtkfpwfehi.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtokrxbfzj.html

[C01] 定义函数
来源：http://dali.pengpengdd.cyou/Article/details/gtkfhkgbvh.html

Py:   def add(a, b): return a + b
来源：http://dali.tanke756.top/Article/details/gtcmqptpek.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sweek.top/Article/details/gtvqrtkiou.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gtowgfcxhi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfqwejpaw.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gtgtujzzsd.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnwiuocej.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yj20258888.top/Article/details/gtjefpoxzi.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gtjmplpckq.html

[C02] 默认参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlpdhztxo.html

Py:   def greet(name="World"): return name
来源：http://dali.yuxming.cn/Article/details/gtgxqmehdu.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.aizwys.cn/Article/details/gtofckrcjn.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.tanke756.top/Article/details/gtttitbvjf.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.chenzaomai.com/Article/details/gtbjxjkewd.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xuetiantiany.cn/Article/details/gtvpwaxowz.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.pengpengdd.cyou/Article/details/gtywvzwnqc.html

Ruby: def greet(name = "World") = name
来源：http://dali.jianghu66.top/Article/details/gtbwrfxsjt.html


<!-- 参考信息 -->