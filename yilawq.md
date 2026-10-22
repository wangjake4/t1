代发 wailian999

TS:   // 单行；/* 多行 */
来源：http://dali.iojbl.cn/Article/details/gtukfqkpxn.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.aizwys.cn/Article/details/gtzboiiada.html

Go:   // 单行；/* 多行 */
来源：http://dali.jinqigfzy.top/Article/details/gtkljpbqun.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhongyouzk.top/Article/details/gtdcyafzpq.html

C#:   // 单行；/* 多行 */
来源：http://dali.aibaodan.cn/Article/details/gtwzvmziup.html

[A15] 空值判断与默认值
来源：http://dali.zhengqikj.top/Article/details/gtcfensieg.html

Py:   value = data or "默认值"
来源：http://dali.aibaodan.cn/Article/details/gtfrbnhlwa.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.jianghu66.top/Article/details/gtysplrmfm.html

JS:   const value = data ?? "默认值";
来源：http://dali.wangdashe.top/Article/details/gtxjedgszc.html

TS:   const value = data ?? "默认值";
来源：http://dali.andypj.xyz/Article/details/gtjsumrfvf.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.gogol.net.cn/Article/details/gtodqtfbjx.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgpybhsik.html

Ruby: value = data || "默认值"
来源：http://dali.ydzc1.top/Article/details/gtmdnrgbzj.html

C#:   var value = data ?? "默认值";
来源：http://dali.shanyushiyangtech.top/Article/details/gtzltbzzby.html

[A16] 真假值判断规则
来源：http://dali.jqgufenzy.top/Article/details/gtwxvneemz.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.jinyuanbaomall.cn/Article/details/gthedtwflh.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.ehwqpu.com/Article/details/gtmqhhvcwm.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.gaohongyu789.top/Article/details/gtjihqnfgb.html

TS:   if (!x) {}
来源：http://dali.fengsongda.top/Article/details/gtulokhlfa.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhongyouzk.top/Article/details/gtbfqnineb.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.yuxming.cn/Article/details/gtgpjyrnmj.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.haohaochexian.top/Article/details/gtyddtkbxv.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.xziqi.cn/Article/details/gtltonbija.html

[A17] 位运算
来源：http://dali.guannengcc.top/Article/details/gtnvvlgnqy.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinqigfzy.top/Article/details/gtudcvunlo.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.yonumen.top/Article/details/gtcfmvauii.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.wangshuangyany.cn/Article/details/gtwnvtluol.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.sufxvd.cn/Article/details/gtrtxswyqy.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcqaiyncu.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.jyoumei.cn/Article/details/gtpmqagvmt.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cdnleiting.top/Article/details/gtujmxgjle.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.svipenyu.cn/Article/details/gtybpyycww.html

[A18] 字符与 ASCII 码互转
来源：http://dali.aibaodan.cn/Article/details/gtdmgjzxve.html

Py:   ord("A"); chr(65)
来源：http://dali.sufxvd.cn/Article/details/gtgqfhjift.html

PHP:  ord("A"); chr(65)
来源：http://dali.redwolf501.top/Article/details/gtexoccrbe.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yuxming.cn/Article/details/gtiysmnfge.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.feifeiyinyue.top/Article/details/gtyokkcohe.html

Java: (int) 'A'; (char) 65
来源：http://dali.chenzaomai.com/Article/details/gtsmhxfqyc.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.zhoulong.xyz/Article/details/gtrxdzpdwa.html

Ruby: "A".ord; 65.chr
来源：http://dali.zycfv.cn/Article/details/gttqfsvdfr.html

C#:   (int)'A'; (char)65
来源：http://dali.cucudq.cn/Article/details/gtfwhuzfjp.html

[A19] 交换两个变量
来源：http://dali.xinyue.icu/Article/details/gtcjyrgumu.html

Py:   a, b = b, a
来源：http://dali.xinyue.icu/Article/details/gtguwvwssw.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.cheryme.top/Article/details/gtlvnfocbd.html

JS:   [a, b] = [b, a];
来源：http://dali.yonumen.top/Article/details/gtdcryndin.html

TS:   [a, b] = [b, a];
来源：http://dali.wangdashe.top/Article/details/gtvjkpwgkg.html

Java: int t = a; a = b; b = t;
来源：http://dali.tanke756.top/Article/details/gtfnwrcems.html

Go:   a, b = b, a
来源：http://dali.jyoumei.cn/Article/details/gtfsumxbqk.html

Ruby: a, b = b, a
来源：http://dali.xziqi.cn/Article/details/gtkdfrgtwy.html

C#:   (a, b) = (b, a);
来源：http://dali.yanxiufei.cn/Article/details/gtbtsohwbj.html

[A20] 读取标准输入
来源：http://dali.havefunace.top/Article/details/gtvpsuyemu.html

Py:   name = input("请输入：")
来源：http://dali.chenjidiqi.icu/Article/details/gtvvtksqec.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.sweek.top/Article/details/gtqneiaxev.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqhpogfwo.html

TS:   // Node.js：readline 模块
来源：http://dali.chenlongwang.top/Article/details/gtksdfqchr.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.havefunace.top/Article/details/gtrdscnatc.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.shzxlz.cn/Article/details/gtxfeqkmwg.html

Ruby: gets.chomp
来源：http://dali.xziqi.cn/Article/details/gtofazaicu.html

C#:   Console.ReadLine();
来源：http://dali.wangshuangyany.cn/Article/details/gtbzbhlnyy.html

[A21] 保留指定小数位输出
来源：http://dali.birdmap.top/Article/details/gtbygoprwo.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jiagoushi.top/Article/details/gtonnozilm.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.zycfv.cn/Article/details/gtvnjtwamg.html

JS:   (3.14159).toFixed(2)
来源：http://dali.jiagoushi.top/Article/details/gtuorfcqyk.html

TS:   (3.14159).toFixed(2)
来源：http://dali.daria6918.cn/Article/details/gtvkvpxjim.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.daria6918.cn/Article/details/gtngyohqrv.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.xinyue.icu/Article/details/gthxvrnlsx.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.hammf.cn/Article/details/gtkwedacim.html

C#:   3.14159.ToString("F2")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqaqvvsxn.html

[A22] 获取字符串长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdgeigdjs.html

Py:   len(s)
来源：http://dali.aizwys.cn/Article/details/gtlygcllqv.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.pycfn.com/Article/details/gtdexzhvvx.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.ybcxt.top/Article/details/gtirexqvlg.html

TS:   s.length
来源：http://dali.xylfe.cn/Article/details/gteepowotd.html

Java: s.length()
来源：http://dali.andypj.xyz/Article/details/gturcduftz.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.fzhhl.top/Article/details/gtspnunvwx.html

Ruby: s.length
来源：http://dali.nanxinkj.top/Article/details/gtvwywjwuu.html

C#:   s.Length
来源：http://dali.quarkkingdee.top/Article/details/gthaszvghs.html

[A23] 大小写转换
来源：http://dali.hnxiangtu.top/Article/details/gtrfhsflac.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.yueranfly.top/Article/details/gtkhxdsstr.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.c1oappe.top/Article/details/gtrbfxhssp.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ehwqpu.com/Article/details/gtjcqqszne.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yuanzhike.top/Article/details/gtlgoawfmc.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.jinqigfzy.top/Article/details/gtmitlobng.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.andypj.xyz/Article/details/gtuqedziwk.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.ivvv.top/Article/details/gttqafuplb.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.xinyue.icu/Article/details/gthfcyfyfv.html

[A24] 去除首尾空白
来源：http://dali.xuetiantiany.cn/Article/details/gtwtfjjlso.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.hysaishi.cn/Article/details/gtwxnccfqw.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.andypj.xyz/Article/details/gtzfavwiuk.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.nanxinkj.top/Article/details/gtywqyvhrz.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yanxiufei.cn/Article/details/gtngazhjlm.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.c1oappe.top/Article/details/gtksdnuwvb.html

Go:   strings.TrimSpace(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgcwiaumx.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.mhx1999.top/Article/details/gtnmydaxug.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.smart0.xyz/Article/details/gtkuxhogto.html

[A25] 字符串比较
来源：http://dali.hammf.cn/Article/details/gtfefexwrq.html

Py:   s1 == s2; s1 != s2
来源：http://dali.shangyingyoupin.top/Article/details/gtbcajbsrb.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.hammf.cn/Article/details/gtjpncsdts.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.chenzaomai.com/Article/details/gttqimjdib.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.vqdsnc.cn/Article/details/gtkybdjfvj.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.andypj.xyz/Article/details/gtkdgpcxot.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.vqdsnc.cn/Article/details/gtzgcnefvq.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jyoumei.cn/Article/details/gtnwxvlmiv.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.hywenlv.cn/Article/details/gtjyidimak.html

[A26] 类型转换总览
来源：http://dali.yj20258888.top/Article/details/gtgxycsemz.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.wangdashe.top/Article/details/gthxnijijf.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.yvedp.cn/Article/details/gtiwkdkpmf.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.quarkkingdee.top/Article/details/gtmzmayjuf.html

TS:   Number() String() Boolean() x as number
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpvuhykop.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.feifeiyinyue.top/Article/details/gtzptutjla.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.chenjidiqi.icu/Article/details/gteacmiddv.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.hywenlv.cn/Article/details/gtspzouneq.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.gaohongyu789.top/Article/details/gtwafydlkl.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gteflpoxji.html

B. 流程控制
来源：http://dali.feifeiyinyue.top/Article/details/gtdygoumwn.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpynpfvtv.html

[B01] 条件判断 if / else
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbihqsbfy.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.jyoumei.cn/Article/details/gttbkjlkay.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.ehwqpu.com/Article/details/gtgygfuiki.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.sxryk.cn/Article/details/gtkbuudtoc.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.sxryk.cn/Article/details/gtpemshnqb.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.yanxiufei.cn/Article/details/gtrbsznxyw.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.jqgfzy.top/Article/details/gtstimfbna.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.dianchejie.cn/Article/details/gthbsjjdvc.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.andypj.xyz/Article/details/gtbiysdiut.html

[B02] 多分支 else if / elif
来源：http://dali.sxryk.cn/Article/details/gtuicbgvwb.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.ivvv.top/Article/details/gtmrbxnwfk.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.hywenlv.cn/Article/details/gtrllssvtv.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cucudq.cn/Article/details/gtqitglitq.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gotoacloud.top/Article/details/gtqecderdx.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.andypj.xyz/Article/details/gtbivbxuwh.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.feifeiyinyue.top/Article/details/gtfaesobsc.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.fengsongda.top/Article/details/gtgghznazx.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sxryk.cn/Article/details/gtgsgqodgs.html

[B03] switch / match / case
来源：http://dali.ywan-chungtsiang.top/Article/details/gtftnxduew.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.cheryme.top/Article/details/gtfasbvbxr.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zhengqikj.top/Article/details/gtirjdeusi.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yangfankeji.com/Article/details/gtbczyqwci.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.andypj.xyz/Article/details/gtbnkxqmma.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.cucudq.cn/Article/details/gtzqyztzyf.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.bjfxy.top/Article/details/gtryctrhlz.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.zhoulong.xyz/Article/details/gtkexrputx.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.haohaochexian.top/Article/details/gtndzlcvzk.html

[B04] for 计数循环
来源：http://dali.yj20258888.top/Article/details/gtdskhtopy.html

Py:   for i in range(10): print(i)
来源：http://dali.cqqwz.cn/Article/details/gttllopjrf.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.birdmap.top/Article/details/gthvqzfrfi.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhongyouzk.top/Article/details/gtebwvlznx.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hfpthk.cn/Article/details/gtjbagxusk.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yuanzhike.top/Article/details/gtoymcmcdl.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.jiagoushi.top/Article/details/gtvawfquik.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zhengqikj.top/Article/details/gtrfrtmpuz.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.havefunace.top/Article/details/gtzrgvfxon.html

[B05] 遍历数组 / 列表
来源：http://dali.vqdsnc.cn/Article/details/gtrupqbzok.html

Py:   for item in arr: print(item)
来源：http://dali.aizwys.cn/Article/details/gtinfsncyt.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.tanke756.top/Article/details/gtulpxkylm.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpdwhegqp.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtimnjxtsn.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.chenjidiqi.icu/Article/details/gtgrltajha.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.ybcxt.top/Article/details/gtvvmxpmcl.html

Ruby: arr.each { |item| puts item }
来源：http://dali.ydzc1.top/Article/details/gtjhppnhyl.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yanxiufei.cn/Article/details/gtenkorzzj.html

[B06] 遍历字典 / 对象
来源：http://dali.xylfe.cn/Article/details/gtbbwwduxe.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.shuidangran.top/Article/details/gtqkblemuv.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.ivvv.top/Article/details/gtknnegqus.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.smart0.xyz/Article/details/gteqiwevle.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.nanxinkj.top/Article/details/gtfgrfxebk.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.guannengcc.top/Article/details/gtetiefhwg.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.ybcxt.top/Article/details/gtijhinqmm.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.pengpengdd.cyou/Article/details/gtzusneovj.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.tian-w.cn/Article/details/gtasqkobfv.html

[B07] while 循环
来源：http://dali.gogol.net.cn/Article/details/gtjkxypcpi.html

Py:   while i < 10: i += 1
来源：http://dali.ybcxt.top/Article/details/gtlfknmwct.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.xuetiantiany.cn/Article/details/gthsittscv.html

JS:   while (i < 10) { i++; }
来源：http://dali.ppjwa.cn/Article/details/gtzogqqnpl.html

TS:   while (i < 10) { i++; }
来源：http://dali.ppjwa.cn/Article/details/gtuerlvnuy.html

Java: while (i < 10) { i++; }
来源：http://dali.smart0.xyz/Article/details/gtioujjxbx.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.9152youxi.cn/Article/details/gtpxxtxgfx.html

Ruby: while i < 10; i += 1; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gttyzlchcc.html

C#:   while (i < 10) { i++; }
来源：http://dali.yj20258888.top/Article/details/gtzpggzxmj.html

[B08] do-while（至少执行一次）
来源：http://dali.aibaodan.cn/Article/details/gtrpancgqb.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.shangyingyoupin.top/Article/details/gtnnnnysob.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yuxming.cn/Article/details/gtcltaohgw.html

JS:   do { i++; } while (i < 10);
来源：http://dali.guowangkeji.top/Article/details/gtjfgerbdy.html

TS:   do { i++; } while (i < 10);
来源：http://dali.guowangkeji.top/Article/details/gtcoctiwwc.html

Java: do { i++; } while (i < 10);
来源：http://dali.ivvv.top/Article/details/gtyzfrbjbo.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.9152youxi.cn/Article/details/gtrfyqrcjr.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.fzhhl.top/Article/details/gtjlstkfrg.html

C#:   do { i++; } while (i < 10);
来源：http://dali.hnxiangtu.top/Article/details/gtddntbrkw.html

[B09] break 与 continue
来源：http://dali.shuidangran.top/Article/details/gttdnlhbwi.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.bjfxy.top/Article/details/gtzlxymtqu.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.shangyingyoupin.top/Article/details/gtjqsejouv.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zycfv.cn/Article/details/gtcrwnnlwm.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daria6918.cn/Article/details/gtnrvcsdyp.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cashguo.top/Article/details/gtltguxsnj.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.chenjidiqi.icu/Article/details/gteixxbbat.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.kuanghao11.cn/Article/details/gtwvhhhxkl.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dashuyun.cn/Article/details/gtlzfqsuik.html

[B10] 遍历同时拿索引
来源：http://dali.meibo888.top/Article/details/gthmqayfdh.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.mhx1999.top/Article/details/gtbdsoteze.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yanxiufei.cn/Article/details/gtusigxfuy.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.iojbl.cn/Article/details/gtcxabvhva.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.cucudq.cn/Article/details/gtqbqwmuou.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.tian-w.cn/Article/details/gtjhhnoehq.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hywenlv.cn/Article/details/gtgmittvuh.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.316326.xyz/Article/details/gtorfkdlpy.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.tanke756.top/Article/details/gtsjopstry.html

[B11] 生成数字序列 / 区间
来源：http://dali.nanxinkj.top/Article/details/gtzuctjgwm.html

Py:   list(range(0, 10, 2))
来源：http://dali.andypj.xyz/Article/details/gteosflqmh.html

PHP:  range(0, 10, 2);
来源：http://dali.havefunace.top/Article/details/gtdqiivfsa.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.kuanghao11.cn/Article/details/gtgnbhepln.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cucudq.cn/Article/details/gthpmalhug.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.xinyue.icu/Article/details/gtsdgzxwif.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.dashuyun.cn/Article/details/gtlhceqelu.html

Ruby: (0...10).step(2).to_a
来源：http://dali.vqdsnc.cn/Article/details/gtwymnvvfz.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.sxryk.cn/Article/details/gtymcoofej.html

[B12] 跳出多层循环
来源：http://dali.jqgufenzy.top/Article/details/gtctpjrrnk.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.shanyushiyangtech.top/Article/details/gtydykukkc.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.tianlin.xyz/Article/details/gtkbkkhpnq.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ydzc1.top/Article/details/gtmdefpimu.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj20258.top/Article/details/gtemueyqbj.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.redwolf501.top/Article/details/gtqxitomef.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.redwolf501.top/Article/details/gtebtnzdmo.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jinqigfzy.top/Article/details/gtceqfuhph.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.iojbl.cn/Article/details/gtwqkkfmyg.html

[B13] 判断是否为数字
来源：http://dali.yuanzhike.top/Article/details/gteyswewst.html

Py:   isinstance(x, (int, float))
来源：http://dali.wangdashe.top/Article/details/gtccodixsh.html

PHP:  is_numeric($x)
来源：http://dali.haohaochexian.top/Article/details/gtvvuledxo.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gaohongyu789.top/Article/details/gthkhevnjm.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhixingplan.top/Article/details/gtygkesbza.html

Java: x instanceof Number
来源：http://dali.gzhubu.top/Article/details/gtleumytge.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.svipenyu.cn/Article/details/gtlrxbrmox.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xinyue.icu/Article/details/gtaofbktiu.html

C#:   x is int or double or decimal
来源：http://dali.ybcxt.top/Article/details/gtkijloyec.html

[B14] 判断值是否在集合内
来源：http://dali.quarkkingdee.top/Article/details/gtferbxgni.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.gotoacloud.top/Article/details/gtbtogpfsz.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hongshengwenyu.top/Article/details/gtxlransal.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yj20258.top/Article/details/gtizoftyvx.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.svipenyu.cn/Article/details/gtkwvymmkk.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.bjfxy.top/Article/details/gtbovgcazf.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jqgufenzy.top/Article/details/gtilnhgocf.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yuanzhike.top/Article/details/gtzxvapjhq.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.pycfn.com/Article/details/gtnbrgykny.html

[B15] 布尔运算与取反
来源：http://dali.pycfn.com/Article/details/gtzypsemjw.html

Py:   a and b or not c
来源：http://dali.mhx1999.top/Article/details/gtsbivyfbg.html

PHP:  $a && $b || !$c
来源：http://dali.xuetiantiany.cn/Article/details/gtrobseadu.html

JS:   a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gtkupwiplh.html

TS:   a && b || !c
来源：http://dali.jqgufenzy.top/Article/details/gtbwzrvhsp.html

Java: a && b || !c
来源：http://dali.tian-w.cn/Article/details/gtdmzulvyv.html

Go:   a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gtnmivtjiv.html

Ruby: a && b || !c
来源：http://dali.guowangkeji.top/Article/details/gttsjlyniv.html

C#:   a && b || !c
来源：http://dali.zycfv.cn/Article/details/gtuivkmvqr.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.xuetiantiany.cn/Article/details/gtreggajki.html

Py:   if not data: return
来源：http://dali.redwolf501.top/Article/details/gtrhmqzjfm.html

PHP:  if (!$data) { return; }
来源：http://dali.ydzc1.top/Article/details/gtgqrlvxct.html

JS:   if (!data) return;
来源：http://dali.aibaodan.cn/Article/details/gtioqimukf.html

TS:   if (!data) return;
来源：http://dali.bjfxy.top/Article/details/gtedfqibxp.html

Java: if (data == null) return;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqhdfphea.html

Go:   if data == nil { return }
来源：http://dali.daxiang520.top/Article/details/gteocvfipa.html

Ruby: return if data.nil?
来源：http://dali.nwbrower.top/Article/details/gthjlwdqyd.html

C#:   if (data == null) return;
来源：http://dali.jianghu66.top/Article/details/gtrfzdvwop.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtuxhealrf.html

C. 函数与作用域
来源：http://dali.yj20258.top/Article/details/gtaddjjihy.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtqlxvkfao.html

[C01] 定义函数
来源：http://dali.gzhubu.top/Article/details/gttcbwcoas.html

Py:   def add(a, b): return a + b
来源：http://dali.nanxinkj.top/Article/details/gtznlkaizt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.c1oappe.top/Article/details/gtazwhdelq.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gtlxzhpqgq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.birdmap.top/Article/details/gtwbydbbua.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gtcubmdbug.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.316326.xyz/Article/details/gttpjclpls.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yj20258.top/Article/details/gtpvcmoryk.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gteysmzgls.html

[C02] 默认参数
来源：http://dali.jiagoushi.top/Article/details/gtkzllcaly.html

Py:   def greet(name="World"): return name
来源：http://dali.c1oappe.top/Article/details/gtjgexakqz.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zdqjudy.top/Article/details/gtjbfhypvy.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shuidangran.top/Article/details/gtgtbuddsj.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gtsnjjonfr.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.daxiang520.top/Article/details/gtvhhjsglo.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yj20258.top/Article/details/gtmrknwjno.html

Ruby: def greet(name = "World") = name
来源：http://dali.smart0.xyz/Article/details/gtbvhtisqd.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.kuanghao11.cn/Article/details/gtovdsbgyf.html

[C03] 可变参数
来源：http://dali.vqdsnc.cn/Article/details/gtrmhohuzr.html

Py:   def total(*args): return sum(args)
来源：http://dali.chenjidiqi.icu/Article/details/gtqdowamdq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yonumen.top/Article/details/gtbqnaxkgt.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sweek.top/Article/details/gtbnniuzsy.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xuanzx.com/Article/details/gtoxivrivu.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jiagoushi.top/Article/details/gtspgkgjrj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yvedp.cn/Article/details/gtwgdxiedo.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.quarkkingdee.top/Article/details/gtcswgdmig.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cucudq.cn/Article/details/gtcfedmzue.html

[C04] 命名参数 / 关键字参数
来源：http://dali.sysykeji.top/Article/details/gtvvxfmqps.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jqgufenzy.top/Article/details/gtpwghunmr.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.smart0.xyz/Article/details/gtitiwdqnk.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hywenlv.cn/Article/details/gtsisywikb.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.fzhhl.top/Article/details/gtlvoseflf.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.aizwys.cn/Article/details/gtjkxtstap.html

Go:   // 无：用配置结构体参数
来源：http://dali.chenlongwang.top/Article/details/gtlxivdhuz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.iojbl.cn/Article/details/gtgouwpyzp.html

C#:   f(a: 1, b: 2)
来源：http://dali.guowangkeji.top/Article/details/gtktwnwtjk.html

[C05] 返回多个值
来源：http://dali.jqgufenzy.top/Article/details/gtqibxrwqj.html


<!-- 参考信息 -->