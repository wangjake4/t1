代发 wailian999

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.jyoumei.cn/Article/details/gtlwlgbsyo.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.svipenyu.cn/Article/details/gtevqukgvq.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.bjfxy.top/Article/details/gtmgfekwce.html

[A17] 位运算
来源：http://dali.shzxlz.cn/Article/details/gtvqtbinul.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gogol.net.cn/Article/details/gtbtegapvf.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.yangfankeji.com/Article/details/gtdvwrknri.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yvedp.cn/Article/details/gtjxalqgum.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtsjnzvcce.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinqigfzy.top/Article/details/gtwrbjjbwh.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.tianlin.xyz/Article/details/gtoinwezwo.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gaohongyu789.top/Article/details/gtewbcoqgg.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.andypj.xyz/Article/details/gtzuclzqsu.html

[A18] 字符与 ASCII 码互转
来源：http://dali.hywenlv.cn/Article/details/gtxsjlyacc.html

Py:   ord("A"); chr(65)
来源：http://dali.ehwqpu.com/Article/details/gtmcgcjgwi.html

PHP:  ord("A"); chr(65)
来源：http://dali.ppjwa.cn/Article/details/gtpuvobfpj.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.cqqwz.cn/Article/details/gtmfximqpv.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.cdnleiting.top/Article/details/gtkgrmfdhw.html

Java: (int) 'A'; (char) 65
来源：http://dali.andypj.xyz/Article/details/gtnqxaagsx.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.yvedp.cn/Article/details/gtqlhgdlac.html

Ruby: "A".ord; 65.chr
来源：http://dali.wangdashe.top/Article/details/gtksbrtexc.html

C#:   (int)'A'; (char)65
来源：http://dali.kuanghao11.cn/Article/details/gtzcluocym.html

[A19] 交换两个变量
来源：http://dali.sufxvd.cn/Article/details/gtlubyrgds.html

Py:   a, b = b, a
来源：http://dali.pycfn.com/Article/details/gtvykugusp.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.meibo888.top/Article/details/gtoucypqcs.html

JS:   [a, b] = [b, a];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnfnvxkpm.html

TS:   [a, b] = [b, a];
来源：http://dali.0kj1m.cn/Article/details/gtcciqksfv.html

Java: int t = a; a = b; b = t;
来源：http://dali.havefunace.top/Article/details/gtiblnwytx.html

Go:   a, b = b, a
来源：http://dali.dashuyun.cn/Article/details/gtsjgdfpdr.html

Ruby: a, b = b, a
来源：http://dali.yangfankeji.com/Article/details/gtexhxrsmi.html

C#:   (a, b) = (b, a);
来源：http://dali.yangfankeji.com/Article/details/gtnetvknuz.html

[A20] 读取标准输入
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyxcwalcn.html

Py:   name = input("请输入：")
来源：http://dali.guannengcc.top/Article/details/gthghdpset.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.ivvv.top/Article/details/gtlodkejhw.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.ppjwa.cn/Article/details/gtwfamjnbo.html

TS:   // Node.js：readline 模块
来源：http://dali.jiagoushi.top/Article/details/gthfonfmzc.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxzpzimga.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.yonumen.top/Article/details/gtyvvxiynf.html

Ruby: gets.chomp
来源：http://dali.jqgfzy.top/Article/details/gtnbwjqyla.html

C#:   Console.ReadLine();
来源：http://dali.vqdsnc.cn/Article/details/gtkurqanlw.html

[A21] 保留指定小数位输出
来源：http://dali.hysaishi.cn/Article/details/gtxahtzwjr.html

Py:   f"{3.14159:.2f}"
来源：http://dali.havefunace.top/Article/details/gtybyjymna.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.gotoacloud.top/Article/details/gtaclutytd.html

JS:   (3.14159).toFixed(2)
来源：http://dali.zdqjudy.top/Article/details/gtjgpcunoo.html

TS:   (3.14159).toFixed(2)
来源：http://dali.yonumen.top/Article/details/gttjnknbfi.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.mhx1999.top/Article/details/gtyttdnrks.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.hfpthk.cn/Article/details/gttksjecef.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.zhongyouzk.top/Article/details/gthshkndop.html

C#:   3.14159.ToString("F2")
来源：http://dali.iojbl.cn/Article/details/gtsrbwigwj.html

[A22] 获取字符串长度
来源：http://dali.nanxinkj.top/Article/details/gtikzdtfkj.html

Py:   len(s)
来源：http://dali.guowangkeji.top/Article/details/gtkikjpqqg.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.9152youxi.cn/Article/details/gtlwbzsqbn.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.zhixingplan.top/Article/details/gtmcghvmuw.html

TS:   s.length
来源：http://dali.shzxlz.cn/Article/details/gtoaazpirp.html

Java: s.length()
来源：http://dali.quarkkingdee.top/Article/details/gtleztdlmd.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.9152youxi.cn/Article/details/gtwftudmos.html

Ruby: s.length
来源：http://dali.fengsongda.top/Article/details/gteaxxyvth.html

C#:   s.Length
来源：http://dali.cashguo.top/Article/details/gtnkkxsgck.html

[A23] 大小写转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbjmdqqxj.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.dianchejie.cn/Article/details/gtucbgzlig.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.fzhhl.top/Article/details/gtbyeebieu.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.chenlongwang.top/Article/details/gtzefxaqyg.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.meibo888.top/Article/details/gtbniwwilb.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.hnxiangtu.top/Article/details/gtuddkqlff.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtmrawpffi.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.yongpay.top/Article/details/gtixgqpfqy.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.0kj1m.cn/Article/details/gteyihytev.html

[A24] 去除首尾空白
来源：http://dali.jqgufenzy.top/Article/details/gtqimvhrdv.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.jiagoushi.top/Article/details/gtliturjnl.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.yongpay.top/Article/details/gtwqrihemb.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.gzhubu.top/Article/details/gtuanqbnse.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.sysykeji.top/Article/details/gtwevjmrji.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.yj202588.top/Article/details/gtubmpgpkc.html

Go:   strings.TrimSpace(s)
来源：http://dali.0kj1m.cn/Article/details/gtxvckaiqq.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.guannengcc.top/Article/details/gtxfemhqxw.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.mhx1999.top/Article/details/gtclcpweyf.html

[A25] 字符串比较
来源：http://dali.smart0.xyz/Article/details/gthlzaljoh.html

Py:   s1 == s2; s1 != s2
来源：http://dali.smart0.xyz/Article/details/gtdvffsppj.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtecnbmthy.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhengqikj.top/Article/details/gtcvtjqmtr.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthzotyjef.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.xylfe.cn/Article/details/gtxmrevrfu.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.daxiang520.top/Article/details/gtfawcwbjw.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.yj20258888.top/Article/details/gtpcweuvfs.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.jinqigufen.top/Article/details/gtieejydcd.html

[A26] 类型转换总览
来源：http://dali.shuidangran.top/Article/details/gthofkyskq.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.ivvv.top/Article/details/gtxmoycoai.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmhqldctu.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.ywan-chungtsiang.top/Article/details/gthugqkivg.html

TS:   Number() String() Boolean() x as number
来源：http://dali.316326.xyz/Article/details/gtlghsurpo.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.hywenlv.cn/Article/details/gtddvmzjkg.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zhiwuduotai.top/Article/details/gtxonnqazh.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.meibo888.top/Article/details/gtkgcjejxr.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.ybcxt.top/Article/details/gtpzbyiukb.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtnmqzryhb.html

B. 流程控制
来源：http://dali.jiagoushi.top/Article/details/gtqebnxtlm.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtccwsusqm.html

[B01] 条件判断 if / else
来源：http://dali.quarkkingdee.top/Article/details/gtpeqowezb.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.ivvv.top/Article/details/gtnbghwtzl.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.hywenlv.cn/Article/details/gtdcaosysv.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.daxiang520.top/Article/details/gtiadafnfy.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xuetiantiany.cn/Article/details/gtuowhcvjp.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.wangshuangyany.cn/Article/details/gtdzrprwcf.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.cheryme.top/Article/details/gtpnsvwqta.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.redwolf501.top/Article/details/gtasmipuhg.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.feifeiyinyue.top/Article/details/gtdmhiakyu.html

[B02] 多分支 else if / elif
来源：http://dali.fzhhl.top/Article/details/gtdglopyew.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.0kj1m.cn/Article/details/gthsdwmmhw.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.chenzaomai.com/Article/details/gtmuinegzx.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nanxinkj.top/Article/details/gtjmlywvot.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tanke756.top/Article/details/gtatrbntxo.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.svipenyu.cn/Article/details/gtxljnrrdb.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.aibaodan.cn/Article/details/gtlhrcetge.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.gotoacloud.top/Article/details/gtoyqjshti.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xuanzx.com/Article/details/gtifnrftyg.html

[B03] switch / match / case
来源：http://dali.tianlin.xyz/Article/details/gtkbboobjs.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.feifeiyinyue.top/Article/details/gtniuviuzk.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.jlsjyb.cn/Article/details/gtjgibeckh.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shzxlz.cn/Article/details/gtvkflknvw.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhixingplan.top/Article/details/gthlwegmsr.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtpjqzzinw.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.fzhhl.top/Article/details/gthjgatvpi.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.hnqzz.top/Article/details/gtcbgutyux.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jinghuilouyu.cn/Article/details/gtmgfxfjhm.html

[B04] for 计数循环
来源：http://dali.yongpay.top/Article/details/gtajcreckn.html

Py:   for i in range(10): print(i)
来源：http://dali.sxryk.cn/Article/details/gtgplfqkmp.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jqgfzy.top/Article/details/gtmtnqqdns.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtklnsmcxv.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.shuidangran.top/Article/details/gtfrzhnora.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.andypj.xyz/Article/details/gtbimrnmbl.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.jyoumei.cn/Article/details/gtbranvyvl.html

Ruby: 10.times { |i| puts i }
来源：http://dali.smart0.xyz/Article/details/gtlepypddr.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.cheryme.top/Article/details/gtonilbdzu.html

[B05] 遍历数组 / 列表
来源：http://dali.chenjidiqi.icu/Article/details/gttzcfbeck.html

Py:   for item in arr: print(item)
来源：http://dali.yj20258.top/Article/details/gtmdkclvff.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.xziqi.cn/Article/details/gtfifhrrlv.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtggrddpuy.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhixingplan.top/Article/details/gtlqxwcohn.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.mhx1999.top/Article/details/gtdxwupxlr.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zdqjudy.top/Article/details/gtmxhpsvch.html

Ruby: arr.each { |item| puts item }
来源：http://dali.svipenyu.cn/Article/details/gttmzagxxh.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.kuanghao11.cn/Article/details/gtonmavifx.html

[B06] 遍历字典 / 对象
来源：http://dali.smart0.xyz/Article/details/gtiialcdcd.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.hongshengwenyu.top/Article/details/gtyrnvdslk.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.dianchejie.cn/Article/details/gtvapaggku.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.daria6918.cn/Article/details/gtfspkkyde.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.aibaodan.cn/Article/details/gtiltxltko.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtupqotrqr.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yuanzhike.top/Article/details/gtizfxyzkx.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.wangshuangyany.cn/Article/details/gtdqttngzr.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.tanke756.top/Article/details/gtxudhdsvy.html

[B07] while 循环
来源：http://dali.gotoacloud.top/Article/details/gtvkjdqbxp.html

Py:   while i < 10: i += 1
来源：http://dali.quarkkingdee.top/Article/details/gtmffnbcjs.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.nanxinkj.top/Article/details/gtofxlvpcs.html

JS:   while (i < 10) { i++; }
来源：http://dali.chenzaomai.com/Article/details/gtcmovpjox.html

TS:   while (i < 10) { i++; }
来源：http://dali.hongshengwenyu.top/Article/details/gtkppbcanh.html

Java: while (i < 10) { i++; }
来源：http://dali.cashguo.top/Article/details/gtwmztejka.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.haohaochexian.top/Article/details/gtxluxmfjn.html

Ruby: while i < 10; i += 1; end
来源：http://dali.shzxlz.cn/Article/details/gtqptyprtr.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhixingplan.top/Article/details/gtseusehty.html

[B08] do-while（至少执行一次）
来源：http://dali.dashuyun.cn/Article/details/gtzyocopkp.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.cashguo.top/Article/details/gtrsdkuuzn.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtobzjcvfo.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hnxiangtu.top/Article/details/gtwalxdlnu.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yuanzhike.top/Article/details/gtkgkpbvjs.html

Java: do { i++; } while (i < 10);
来源：http://dali.sweek.top/Article/details/gtuxdiuoaf.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.cucudq.cn/Article/details/gtxdspdfrl.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.ppjwa.cn/Article/details/gtnjzsydap.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhoulong.xyz/Article/details/gtjuhmndfa.html

[B09] break 与 continue
来源：http://dali.hnxiangtu.top/Article/details/gtvvfbpkcr.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yuxming.cn/Article/details/gtegjiuoxu.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.vqdsnc.cn/Article/details/gtuqjnckvc.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yanxiufei.cn/Article/details/gtaiymxwop.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shuidangran.top/Article/details/gtflwswkph.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aibaodan.cn/Article/details/gtqhmypbbt.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.hywenlv.cn/Article/details/gtdqueptnd.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhixingplan.top/Article/details/gtjcgnvcdm.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cashguo.top/Article/details/gtvdluzamf.html

[B10] 遍历同时拿索引
来源：http://dali.ybcxt.top/Article/details/gttnwhbetd.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.guannengcc.top/Article/details/gtdgwdouyz.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.tian-w.cn/Article/details/gtavjmeryz.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.sxryk.cn/Article/details/gtvswrctzi.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.hongshengwenyu.top/Article/details/gththzveue.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhixingplan.top/Article/details/gtreeftura.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.sxryk.cn/Article/details/gtwxvzujjl.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.sxryk.cn/Article/details/gtemacvbqb.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.shzxlz.cn/Article/details/gttkjmxveh.html

[B11] 生成数字序列 / 区间
来源：http://dali.316326.xyz/Article/details/gtxwemrbun.html

Py:   list(range(0, 10, 2))
来源：http://dali.tianlin.xyz/Article/details/gtjtkokexn.html

PHP:  range(0, 10, 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtaqqeeplv.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.vqdsnc.cn/Article/details/gtaluzhwxn.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hnxiangtu.top/Article/details/gtezaiboqj.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.gotoacloud.top/Article/details/gtqevbinjh.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.nanxuanxn.top/Article/details/gtyrnyxzrq.html

Ruby: (0...10).step(2).to_a
来源：http://dali.sxryk.cn/Article/details/gtpzjzbynx.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yuxming.cn/Article/details/gtqewqhsts.html

[B12] 跳出多层循环
来源：http://dali.jiagoushi.top/Article/details/gtwbbofgmo.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.sysykeji.top/Article/details/gtuuanmndy.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.mhx1999.top/Article/details/gtylayjxkt.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.mhx1999.top/Article/details/gtzgzdfjvt.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpthlsdrp.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cucudq.cn/Article/details/gtrksicxve.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.ppjwa.cn/Article/details/gtkankufqi.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.birdmap.top/Article/details/gtqswjozda.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.snrcjt.cn/Article/details/gtavzruiex.html

[B13] 判断是否为数字
来源：http://dali.zhongyouzk.top/Article/details/gtjmrzyece.html

Py:   isinstance(x, (int, float))
来源：http://dali.daxiang520.top/Article/details/gtvntlriuf.html

PHP:  is_numeric($x)
来源：http://dali.zhoulong.xyz/Article/details/gtymaqvgyn.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj20258888.top/Article/details/gtxdhrpcpr.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj20258.top/Article/details/gtgydkfoaq.html

Java: x instanceof Number
来源：http://dali.hysaishi.cn/Article/details/gtnpqvgkkk.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zycfv.cn/Article/details/gtdzwvbtju.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jinqigufen.top/Article/details/gttzxrlama.html

C#:   x is int or double or decimal
来源：http://dali.fzhhl.top/Article/details/gtlbmoispw.html

[B14] 判断值是否在集合内
来源：http://dali.chenlongwang.top/Article/details/gtkmurhwae.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.kuanghao11.cn/Article/details/gtfftmzfwm.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.shuidangran.top/Article/details/gtnhtvwgrm.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yj202588.top/Article/details/gtrmhiawft.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hammf.cn/Article/details/gtdwuwjuks.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jinqigfzy.top/Article/details/gtzxfcehod.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gtjkmuerlr.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yangfankeji.com/Article/details/gtvkjotqts.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hammf.cn/Article/details/gtxxogworv.html

[B15] 布尔运算与取反
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbfpgiuff.html

Py:   a and b or not c
来源：http://dali.xuetiantiany.cn/Article/details/gtbowkucnw.html

PHP:  $a && $b || !$c
来源：http://dali.xziqi.cn/Article/details/gtknpzucnr.html

JS:   a && b || !c
来源：http://dali.vqdsnc.cn/Article/details/gtkmnkjaxs.html

TS:   a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gtcdqcacsn.html

Java: a && b || !c
来源：http://dali.mhx1999.top/Article/details/gtekcbapyj.html

Go:   a && b || !c
来源：http://dali.cashguo.top/Article/details/gtwrtvzgqo.html

Ruby: a && b || !c
来源：http://dali.xylfe.cn/Article/details/gtclkxlhed.html

C#:   a && b || !c
来源：http://dali.316326.xyz/Article/details/gttscnobsw.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.meibo888.top/Article/details/gtiirwsnxr.html

Py:   if not data: return
来源：http://dali.xinyue.icu/Article/details/gtlyhjwkae.html

PHP:  if (!$data) { return; }
来源：http://dali.zycfv.cn/Article/details/gtastuvfut.html

JS:   if (!data) return;
来源：http://dali.zhengqikj.top/Article/details/gtzfzuollt.html

TS:   if (!data) return;
来源：http://dali.zhiwuduotai.top/Article/details/gtsnvtsvqw.html

Java: if (data == null) return;
来源：http://dali.svipenyu.cn/Article/details/gtnvftvwyr.html

Go:   if data == nil { return }
来源：http://dali.tanke756.top/Article/details/gtawkootde.html

Ruby: return if data.nil?
来源：http://dali.xinyue.icu/Article/details/gtyyngxodx.html

C#:   if (data == null) return;
来源：http://dali.tanke756.top/Article/details/gtkpqjpzkd.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtsinnyftc.html

C. 函数与作用域
来源：http://dali.chenzaomai.com/Article/details/gtidlbatpj.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtdovpjhkv.html

[C01] 定义函数
来源：http://dali.xuetiantiany.cn/Article/details/gtxstbfwes.html

Py:   def add(a, b): return a + b
来源：http://dali.cucudq.cn/Article/details/gtdujkfotu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cucudq.cn/Article/details/gtketyxtjv.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gtnlqqbwvv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gtjqpzffrb.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmnqxmloy.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.c1oappe.top/Article/details/gtvloumztq.html

Ruby: def add(a, b); a + b; end
来源：http://dali.c1oappe.top/Article/details/gtxovjrrds.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hammf.cn/Article/details/gtpllqbleo.html

[C02] 默认参数
来源：http://dali.sweek.top/Article/details/gtsopowyxu.html

Py:   def greet(name="World"): return name
来源：http://dali.aizwys.cn/Article/details/gtxjejjtyv.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yvedp.cn/Article/details/gtzddzmriw.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtompujdka.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtndkdzijo.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hnqzz.top/Article/details/gtorigwmsb.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yj20258.top/Article/details/gticgfyjnv.html

Ruby: def greet(name = "World") = name
来源：http://dali.hnqzz.top/Article/details/gtdmalzipb.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.tian-w.cn/Article/details/gtcjdswtde.html

[C03] 可变参数
来源：http://dali.yangfankeji.com/Article/details/gtzkacgrfu.html

Py:   def total(*args): return sum(args)
来源：http://dali.hnqzz.top/Article/details/gtcigijokh.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.nwbrower.top/Article/details/gtxjxmyjoo.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.0kj1m.cn/Article/details/gtuntpvzng.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tanke756.top/Article/details/gtgkizjjkc.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.aibaodan.cn/Article/details/gtbmzyybco.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.pengpengdd.cyou/Article/details/gtodxnqegp.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hysaishi.cn/Article/details/gtgeyuidnm.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.fzhhl.top/Article/details/gtuwnclpcl.html

[C04] 命名参数 / 关键字参数
来源：http://dali.meibo888.top/Article/details/gtesihvhmt.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.vqdsnc.cn/Article/details/gtiastnlza.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jqgfzy.top/Article/details/gteanymgsn.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jqgfzy.top/Article/details/gtfmwbdltj.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.sysykeji.top/Article/details/gtotttpujc.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ivvv.top/Article/details/gtwlglfvie.html

Go:   // 无：用配置结构体参数
来源：http://dali.pycfn.com/Article/details/gtytbbjbhw.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ydzc1.top/Article/details/gtfhrjddbj.html

C#:   f(a: 1, b: 2)
来源：http://dali.sysykeji.top/Article/details/gtabiiampe.html

[C05] 返回多个值
来源：http://dali.xziqi.cn/Article/details/gtvvqxkekx.html

Py:   return a, b
来源：http://dali.yj20258888.top/Article/details/gtzkxkpiyd.html

PHP:  return [$a, $b];
来源：http://dali.chenlongwang.top/Article/details/gtswnuxuxp.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hfpthk.cn/Article/details/gtawbedamv.html

TS:   return { a, b };
来源：http://dali.daria6918.cn/Article/details/gtrqfmulan.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.haohaochexian.top/Article/details/gtjnxcfdmg.html

Go:   return a, b
来源：http://dali.ehwqpu.com/Article/details/gtqryzasqu.html

Ruby: return a, b
来源：http://dali.svipenyu.cn/Article/details/gtcmbdnvyg.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.svipenyu.cn/Article/details/gtotezeupg.html

[C06] 匿名函数 / lambda
来源：http://dali.hysaishi.cn/Article/details/gthifuhrlo.html

Py:   square = lambda x: x * x
来源：http://dali.wangshuangyany.cn/Article/details/gtshxkzzxe.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.feifeiyinyue.top/Article/details/gtcafjdsmx.html

JS:   const square = x => x * x;
来源：http://dali.cashguo.top/Article/details/gtpqfxeghw.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.daxiang520.top/Article/details/gtroelcere.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.sxryk.cn/Article/details/gttkgrtvmz.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xuetiantiany.cn/Article/details/gtqodjiycq.html

Ruby: square = ->(x) { x * x }
来源：http://dali.haohaochexian.top/Article/details/gtyuygegkz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.feifeiyinyue.top/Article/details/gtzyftoahx.html

[C07] 把函数作为参数传入
来源：http://dali.cucudq.cn/Article/details/gtvioxprqw.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ydzc1.top/Article/details/gtoqrlyjnk.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtjkokafss.html


<!-- 参考信息 -->