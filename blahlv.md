代发 wailian999

C#:   // 单行；/* 多行 */
来源：http://dali.sysykeji.top/Article/details/gtgloccovs.html

[A15] 空值判断与默认值
来源：http://dali.zhixingplan.top/Article/details/gtgczoncxg.html

Py:   value = data or "默认值"
来源：http://dali.yongpay.top/Article/details/gtrsmycyon.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.tian-w.cn/Article/details/gtppwpqnxq.html

JS:   const value = data ?? "默认值";
来源：http://dali.hongshengwenyu.top/Article/details/gtohiqxpge.html

TS:   const value = data ?? "默认值";
来源：http://dali.xylfe.cn/Article/details/gthexqziev.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.meibo888.top/Article/details/gtsbegwpyq.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhixingplan.top/Article/details/gtfqbfwjzp.html

Ruby: value = data || "默认值"
来源：http://dali.tianlin.xyz/Article/details/gtmssqfjbq.html

C#:   var value = data ?? "默认值";
来源：http://dali.yuxming.cn/Article/details/gtuhiyadkq.html

[A16] 真假值判断规则
来源：http://dali.0kj1m.cn/Article/details/gtyqhxucgh.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhoulong.xyz/Article/details/gtgqlqstpu.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.pengpengdd.cyou/Article/details/gtwfijixly.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.redwolf501.top/Article/details/gtckccoraz.html

TS:   if (!x) {}
来源：http://dali.ehwqpu.com/Article/details/gtawvnjftm.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.pycfn.com/Article/details/gtvxbytemi.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.shangyingyoupin.top/Article/details/gtkezwfmsv.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.bjfxy.top/Article/details/gtunhjapkp.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.gotoacloud.top/Article/details/gtslcpwrhp.html

[A17] 位运算
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcyvqaigh.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinqigfzy.top/Article/details/gtkjmdwpaz.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.jyoumei.cn/Article/details/gtpqtlptrb.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.kuanghao11.cn/Article/details/gtwpxkhnul.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.jqgfzy.top/Article/details/gtdubchsij.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yj202588.top/Article/details/gtimecbces.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zhiwuduotai.top/Article/details/gtdedqxqev.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yuxming.cn/Article/details/gthttzlbpz.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tanke756.top/Article/details/gtqrtvrhow.html

[A18] 字符与 ASCII 码互转
来源：http://dali.zdqjudy.top/Article/details/gtikqhsfic.html

Py:   ord("A"); chr(65)
来源：http://dali.yanxiufei.cn/Article/details/gtmpdqgrrl.html

PHP:  ord("A"); chr(65)
来源：http://dali.yj20258.top/Article/details/gtqqgyykmp.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.tian-w.cn/Article/details/gtytesldkv.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhiwuduotai.top/Article/details/gtldgcknvz.html

Java: (int) 'A'; (char) 65
来源：http://dali.yj20258.top/Article/details/gtsxcvdplv.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.daria6918.cn/Article/details/gtwzylykud.html

Ruby: "A".ord; 65.chr
来源：http://dali.fengsongda.top/Article/details/gtcfldxxop.html

C#:   (int)'A'; (char)65
来源：http://dali.gogol.net.cn/Article/details/gtkerxyhxk.html

[A19] 交换两个变量
来源：http://dali.hongshengwenyu.top/Article/details/gtpzrfbbyi.html

Py:   a, b = b, a
来源：http://dali.meibo888.top/Article/details/gtrtcwhefz.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.ppjwa.cn/Article/details/gtcdujvlit.html

JS:   [a, b] = [b, a];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqcuxvcri.html

TS:   [a, b] = [b, a];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtytdqjczq.html

Java: int t = a; a = b; b = t;
来源：http://dali.birdmap.top/Article/details/gtpvzpcuqq.html

Go:   a, b = b, a
来源：http://dali.chenjidiqi.icu/Article/details/gtorxmrrsz.html

Ruby: a, b = b, a
来源：http://dali.gzhubu.top/Article/details/gtnendejca.html

C#:   (a, b) = (b, a);
来源：http://dali.yuxming.cn/Article/details/gtlawlvocj.html

[A20] 读取标准输入
来源：http://dali.cheryme.top/Article/details/gtzedaqeqf.html

Py:   name = input("请输入：")
来源：http://dali.quarkkingdee.top/Article/details/gtaebnkdbn.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.xuanzx.com/Article/details/gtgxueoudt.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.tanke756.top/Article/details/gtjmkoorok.html

TS:   // Node.js：readline 模块
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfahjfyol.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.guannengcc.top/Article/details/gtgphplqpq.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.vqdsnc.cn/Article/details/gtebtpiqsi.html

Ruby: gets.chomp
来源：http://dali.hywenlv.cn/Article/details/gtfsjugcfh.html

C#:   Console.ReadLine();
来源：http://dali.ybcxt.top/Article/details/gtdfsbrgft.html

[A21] 保留指定小数位输出
来源：http://dali.birdmap.top/Article/details/gtnbfwvzgz.html

Py:   f"{3.14159:.2f}"
来源：http://dali.cucudq.cn/Article/details/gtwewlmdrw.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcjpiyptj.html

JS:   (3.14159).toFixed(2)
来源：http://dali.redwolf501.top/Article/details/gtgrwfymxy.html

TS:   (3.14159).toFixed(2)
来源：http://dali.zhoulong.xyz/Article/details/gthrponhoy.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgpsvudjw.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.jqgfzy.top/Article/details/gtsgrxzedx.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.gzhubu.top/Article/details/gtktahnslm.html

C#:   3.14159.ToString("F2")
来源：http://dali.iojbl.cn/Article/details/gtrnsislmr.html

[A22] 获取字符串长度
来源：http://dali.zhoulong.xyz/Article/details/gtcywxpphd.html

Py:   len(s)
来源：http://dali.9152youxi.cn/Article/details/gtdbqcwokm.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.chenzaomai.com/Article/details/gtrqfjmdad.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdeicinbv.html

TS:   s.length
来源：http://dali.hywenlv.cn/Article/details/gtvlwjbsce.html

Java: s.length()
来源：http://dali.wangdashe.top/Article/details/gtfljgnvdn.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.yongpay.top/Article/details/gtxrkfvpyq.html

Ruby: s.length
来源：http://dali.tanke756.top/Article/details/gtjnogxcvj.html

C#:   s.Length
来源：http://dali.sysykeji.top/Article/details/gtpscdvmti.html

[A23] 大小写转换
来源：http://dali.xuetiantiany.cn/Article/details/gtrflujcdt.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.jianghu66.top/Article/details/gtcjboxmrt.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.xinyue.icu/Article/details/gtftejljet.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.kuanghao11.cn/Article/details/gtbtuzimqf.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.chenjidiqi.icu/Article/details/gtsywbxzvo.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.fengsongda.top/Article/details/gtiuztludf.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttflwpvso.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.sxryk.cn/Article/details/gthvsfxbnk.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdouzodkt.html

[A24] 去除首尾空白
来源：http://dali.cashguo.top/Article/details/gtcjghupef.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.cucudq.cn/Article/details/gtrwywgwgh.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.hywenlv.cn/Article/details/gttmolmfen.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jyoumei.cn/Article/details/gtvefanebz.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.quarkkingdee.top/Article/details/gtswcdgzpb.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.ydzc1.top/Article/details/gtjusuiqwj.html

Go:   strings.TrimSpace(s)
来源：http://dali.jianghu66.top/Article/details/gtamquczmu.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.zycfv.cn/Article/details/gtbqocyrvq.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpbttaoue.html

[A25] 字符串比较
来源：http://dali.yuxming.cn/Article/details/gtclpqfsks.html

Py:   s1 == s2; s1 != s2
来源：http://dali.ehwqpu.com/Article/details/gtkuceuxwu.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.tian-w.cn/Article/details/gtlasiievi.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhixingplan.top/Article/details/gtsmwvwpmf.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ivvv.top/Article/details/gthszkwlru.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.guannengcc.top/Article/details/gtwmbeashk.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.sysykeji.top/Article/details/gtjssqziqb.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.zhengqikj.top/Article/details/gtupwxtbvu.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.sufxvd.cn/Article/details/gtpndeubfi.html

[A26] 类型转换总览
来源：http://dali.aizwys.cn/Article/details/gtxnbksolu.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.zhengqikj.top/Article/details/gtikakwqgq.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.chenlongwang.top/Article/details/gtchpmllyu.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.ydzc1.top/Article/details/gtggpzxiss.html

TS:   Number() String() Boolean() x as number
来源：http://dali.316326.xyz/Article/details/gtmxulsblh.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.nanxuanxn.top/Article/details/gtgnasrijm.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.smart0.xyz/Article/details/gtanitqgdf.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.ydzc1.top/Article/details/gtdwivmmvn.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.andypj.xyz/Article/details/gtbrvfunpq.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gthktdbijk.html

B. 流程控制
来源：http://dali.xuanzx.com/Article/details/gtytficgju.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtlangorrd.html

[B01] 条件判断 if / else
来源：http://dali.daria6918.cn/Article/details/gtiquoxxue.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.jiagoushi.top/Article/details/gtrnhsiwuo.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.nanxuanxn.top/Article/details/gthbfgjwgs.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hysaishi.cn/Article/details/gtlkeecccp.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.aibaodan.cn/Article/details/gtugoqtgpd.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.dashuyun.cn/Article/details/gtjilkhncm.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.ivvv.top/Article/details/gthantzswh.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.xuanzx.com/Article/details/gtdodopqul.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.hfpthk.cn/Article/details/gtrpxelbjx.html

[B02] 多分支 else if / elif
来源：http://dali.hammf.cn/Article/details/gtzeuazlzt.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.vqdsnc.cn/Article/details/gtefqkvopr.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtqkbjmoiu.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shuidangran.top/Article/details/gtfccrzltz.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yuxming.cn/Article/details/gthjcxjrru.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzxmaftbv.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.tianlin.xyz/Article/details/gtykhjzdvo.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.cdnleiting.top/Article/details/gtjjqlbfhy.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cheryme.top/Article/details/gtcjbnlcky.html

[B03] switch / match / case
来源：http://dali.jinqigfzy.top/Article/details/gtanzlgqbv.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.xylfe.cn/Article/details/gtwroiaqmv.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.wangdashe.top/Article/details/gtieurgfuk.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ivvv.top/Article/details/gterddcjzn.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yj202588.top/Article/details/gtulcfamac.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.yanxiufei.cn/Article/details/gtpltblqoy.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.feifeiyinyue.top/Article/details/gtctcvqltn.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.jqgufenzy.top/Article/details/gtbccowedg.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yanxiufei.cn/Article/details/gtvkzoxnjr.html

[B04] for 计数循环
来源：http://dali.kuanghao11.cn/Article/details/gtsteyeauo.html

Py:   for i in range(10): print(i)
来源：http://dali.daxiang520.top/Article/details/gtjzjrthfz.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.xylfe.cn/Article/details/gtknysusvs.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.sxryk.cn/Article/details/gterfoszkr.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.kuanghao11.cn/Article/details/gtytzofbpt.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zhijiandao.cn/Article/details/gtegdeubkx.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.shuidangran.top/Article/details/gtiwlwtyfw.html

Ruby: 10.times { |i| puts i }
来源：http://dali.hammf.cn/Article/details/gtdmbskylk.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.daria6918.cn/Article/details/gtusvtskks.html

[B05] 遍历数组 / 列表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqcbrfepg.html

Py:   for item in arr: print(item)
来源：http://dali.zhongyouzk.top/Article/details/gtkmwpohru.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.ybcxt.top/Article/details/gttyzbaxlf.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.aibaodan.cn/Article/details/gtbloemesm.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.gzhubu.top/Article/details/gttuntvtru.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yanxiufei.cn/Article/details/gtlqctsfak.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.iojbl.cn/Article/details/gtykrlmpus.html

Ruby: arr.each { |item| puts item }
来源：http://dali.kuanghao11.cn/Article/details/gtcvisqejc.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.ydzc1.top/Article/details/gtzgtcrask.html

[B06] 遍历字典 / 对象
来源：http://dali.gogol.net.cn/Article/details/gthksurggl.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.hywenlv.cn/Article/details/gtxybaawlf.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zhengqikj.top/Article/details/gtihbocjjc.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yj202588.top/Article/details/gtgnoamptv.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hnqzz.top/Article/details/gtdmghetia.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhengqikj.top/Article/details/gtdinkikqr.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jinqigufen.top/Article/details/gthdqpdbhj.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yj20258888.top/Article/details/gtbuozobdj.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yvedp.cn/Article/details/gtrotzfngp.html

[B07] while 循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gthdftusff.html

Py:   while i < 10: i += 1
来源：http://dali.gzhubu.top/Article/details/gtyheszeye.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.9152youxi.cn/Article/details/gtempwgiiw.html

JS:   while (i < 10) { i++; }
来源：http://dali.sweek.top/Article/details/gtpoqdezkw.html

TS:   while (i < 10) { i++; }
来源：http://dali.shuidangran.top/Article/details/gtllopfzhs.html

Java: while (i < 10) { i++; }
来源：http://dali.chenzaomai.com/Article/details/gthditqlcg.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.hammf.cn/Article/details/gtbpplthgy.html

Ruby: while i < 10; i += 1; end
来源：http://dali.birdmap.top/Article/details/gtkijgqnnj.html

C#:   while (i < 10) { i++; }
来源：http://dali.yongpay.top/Article/details/gtepyriguk.html

[B08] do-while（至少执行一次）
来源：http://dali.hywenlv.cn/Article/details/gtgakjntid.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.aizwys.cn/Article/details/gtjquagazw.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.wangshuangyany.cn/Article/details/gtcdljqtyk.html

JS:   do { i++; } while (i < 10);
来源：http://dali.tanke756.top/Article/details/gtrgqlgobc.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jianghu66.top/Article/details/gtajdssnbl.html

Java: do { i++; } while (i < 10);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmijszmfy.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.nwbrower.top/Article/details/gtqhpadbww.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhongyouzk.top/Article/details/gtwcuisybg.html

C#:   do { i++; } while (i < 10);
来源：http://dali.cashguo.top/Article/details/gteywpvqbu.html

[B09] break 与 continue
来源：http://dali.hywenlv.cn/Article/details/gtodxijngg.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.nanxuanxn.top/Article/details/gtohpahefh.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yanxiufei.cn/Article/details/gttflhcioi.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ehwqpu.com/Article/details/gtyrctlyng.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guowangkeji.top/Article/details/gtnjghpavh.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgfzy.top/Article/details/gtlvetobhs.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.shangyingyoupin.top/Article/details/gtwnzgnlqk.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yonumen.top/Article/details/gtgrpgkybl.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj202588.top/Article/details/gtmycpqusq.html

[B10] 遍历同时拿索引
来源：http://dali.hysaishi.cn/Article/details/gtrzrwlhtw.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.pycfn.com/Article/details/gtzbmjctbz.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhongyouzk.top/Article/details/gtltmopjqu.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jinghuilouyu.cn/Article/details/gttynbgagx.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yueranfly.top/Article/details/gtjkvcvssz.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yj202588.top/Article/details/gtjjuualab.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.havefunace.top/Article/details/gtjhsuysji.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhoulong.xyz/Article/details/gtvewfrdac.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.guannengcc.top/Article/details/gtieqafdmk.html

[B11] 生成数字序列 / 区间
来源：http://dali.svipenyu.cn/Article/details/gtjjdwywux.html

Py:   list(range(0, 10, 2))
来源：http://dali.cqqwz.cn/Article/details/gtuewwvyga.html

PHP:  range(0, 10, 2);
来源：http://dali.zhengqikj.top/Article/details/gtyivkeiue.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yueranfly.top/Article/details/gtfzhktpct.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yvedp.cn/Article/details/gthlsokgur.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.xylfe.cn/Article/details/gtwizyjieg.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.chenlongwang.top/Article/details/gtwcbgkqjf.html

Ruby: (0...10).step(2).to_a
来源：http://dali.chenzaomai.com/Article/details/gtinixcjha.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.haohaochexian.top/Article/details/gtevfcaubc.html

[B12] 跳出多层循环
来源：http://dali.ppjwa.cn/Article/details/gtnszvytjj.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xuanzx.com/Article/details/gtqecvqboo.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yangfankeji.com/Article/details/gtlgrdfrdt.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.smart0.xyz/Article/details/gtjcufwqee.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangdashe.top/Article/details/gthspnxzdp.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.tianlin.xyz/Article/details/gtofyzakic.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.fengsongda.top/Article/details/gtqzhmusai.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.pengpengdd.cyou/Article/details/gtudbtyfxc.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.316326.xyz/Article/details/gtdvufjhpm.html

[B13] 判断是否为数字
来源：http://dali.daria6918.cn/Article/details/gtpzdsavwr.html

Py:   isinstance(x, (int, float))
来源：http://dali.jianghu66.top/Article/details/gtfgwepccy.html

PHP:  is_numeric($x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtymxzqkvn.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhongyouzk.top/Article/details/gtqaqktmwp.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenlongwang.top/Article/details/gtsknaosqn.html

Java: x instanceof Number
来源：http://dali.bjfxy.top/Article/details/gtpdokphyi.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.aibaodan.cn/Article/details/gtmxsymlbx.html

Ruby: x.is_a?(Numeric)
来源：http://dali.cucudq.cn/Article/details/gtslaetphp.html

C#:   x is int or double or decimal
来源：http://dali.sysykeji.top/Article/details/gtdjctyodo.html

[B14] 判断值是否在集合内
来源：http://dali.chenjidiqi.icu/Article/details/gtmbemzlht.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.wangdashe.top/Article/details/gtmxdqgxsy.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.ppjwa.cn/Article/details/gthlhwqfpx.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jinqigfzy.top/Article/details/gtdltamedz.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yuanzhike.top/Article/details/gtaemusyvq.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yj20258888.top/Article/details/gtwxivemqn.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ppjwa.cn/Article/details/gtuorctnrk.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hammf.cn/Article/details/gtzejobhny.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xinyue.icu/Article/details/gtxuadsojv.html

[B15] 布尔运算与取反
来源：http://dali.tianlin.xyz/Article/details/gtbksmhfvv.html

Py:   a and b or not c
来源：http://dali.hfpthk.cn/Article/details/gtjaylqcpn.html

PHP:  $a && $b || !$c
来源：http://dali.yonumen.top/Article/details/gtgjkytzhw.html

JS:   a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gtswtefqhd.html

TS:   a && b || !c
来源：http://dali.xinyue.icu/Article/details/gthmvhyxag.html

Java: a && b || !c
来源：http://dali.jinqigfzy.top/Article/details/gtjdfteoii.html

Go:   a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvdjjnwxp.html

Ruby: a && b || !c
来源：http://dali.ivvv.top/Article/details/gtmaddmjot.html

C#:   a && b || !c
来源：http://dali.hysaishi.cn/Article/details/gtkbrffouc.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jinghuilouyu.cn/Article/details/gtbartbfyz.html

Py:   if not data: return
来源：http://dali.shuidangran.top/Article/details/gtujrbmwpz.html

PHP:  if (!$data) { return; }
来源：http://dali.chenzaomai.com/Article/details/gtmorczdik.html

JS:   if (!data) return;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxubnqdkk.html

TS:   if (!data) return;
来源：http://dali.jlsjyb.cn/Article/details/gtfftxbmdq.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gtmgplrlck.html

Go:   if data == nil { return }
来源：http://dali.kuanghao11.cn/Article/details/gtcvoavemi.html

Ruby: return if data.nil?
来源：http://dali.c1oappe.top/Article/details/gtxprreqgf.html

C#:   if (data == null) return;
来源：http://dali.jinqigfzy.top/Article/details/gtmmrsdrxm.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtwfpyogzo.html

C. 函数与作用域
来源：http://dali.quarkkingdee.top/Article/details/gthkotjzba.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtakbyimbp.html

[C01] 定义函数
来源：http://dali.xuetiantiany.cn/Article/details/gtwakmcezf.html

Py:   def add(a, b): return a + b
来源：http://dali.sweek.top/Article/details/gtpodpgclh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sysykeji.top/Article/details/gtevfwxunl.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtlzrdgzme.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gtgwnlgzqg.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtcodvzxmo.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jlsjyb.cn/Article/details/gtoijfzame.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ehwqpu.com/Article/details/gtkdeeeqsz.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gtkqfflbfx.html

[C02] 默认参数
来源：http://dali.xuetiantiany.cn/Article/details/gtecyldfui.html

Py:   def greet(name="World"): return name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmhoajorv.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhoulong.xyz/Article/details/gtulzzuucd.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwxzdpmkz.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtaujsgwlu.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yongpay.top/Article/details/gtidkyhobb.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.chenlongwang.top/Article/details/gtfpeehywy.html

Ruby: def greet(name = "World") = name
来源：http://dali.hongshengwenyu.top/Article/details/gtrxkobhol.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.nanxuanxn.top/Article/details/gtycovytog.html

[C03] 可变参数
来源：http://dali.xinyue.icu/Article/details/gtyblksbxx.html

Py:   def total(*args): return sum(args)
来源：http://dali.cashguo.top/Article/details/gtbkfornam.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hnqzz.top/Article/details/gtzgveiiby.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jqgufenzy.top/Article/details/gttncqxmwa.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.0kj1m.cn/Article/details/gtqlqwowei.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhengqikj.top/Article/details/gtpolxyzzr.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.feifeiyinyue.top/Article/details/gtyjcidxal.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.aizwys.cn/Article/details/gtjkeczktu.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yuxming.cn/Article/details/gtbkipofjf.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yj20258888.top/Article/details/gtxkkonkoc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.sxryk.cn/Article/details/gterbzqooo.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.guowangkeji.top/Article/details/gtfguchizo.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cqqwz.cn/Article/details/gtdbdelcbr.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hnqzz.top/Article/details/gtigcdyczt.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhongyouzk.top/Article/details/gtgbjyuajz.html

Go:   // 无：用配置结构体参数
来源：http://dali.yj20258.top/Article/details/gtpoqojvjd.html

Ruby: f(a: 1, b: 2)
来源：http://dali.316326.xyz/Article/details/gtyaszohmf.html

C#:   f(a: 1, b: 2)
来源：http://dali.feifeiyinyue.top/Article/details/gttgpzyztu.html

[C05] 返回多个值
来源：http://dali.cdnleiting.top/Article/details/gtaskafqqq.html

Py:   return a, b
来源：http://dali.smart0.xyz/Article/details/gtihgymzqt.html

PHP:  return [$a, $b];
来源：http://dali.wangshuangyany.cn/Article/details/gtoxglsgfs.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.feifeiyinyue.top/Article/details/gtdmcewbjz.html

TS:   return { a, b };
来源：http://dali.316326.xyz/Article/details/gthtxzrykr.html


<!-- 参考信息 -->