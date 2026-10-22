代发 wailian999

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkbsbklvy.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.yvedp.cn/Article/details/gtdpobyivu.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.nanxuanxn.top/Article/details/gtdrwulukx.html

[A17] 位运算
来源：http://dali.sweek.top/Article/details/gtthnkjmeu.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ppjwa.cn/Article/details/gtxoqwchby.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.nanxinkj.top/Article/details/gtnjzvuimf.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.nanxinkj.top/Article/details/gtqrprwjjk.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtjrrqkbjn.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yanxiufei.cn/Article/details/gthvuwcofd.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.nanxuanxn.top/Article/details/gtuxmexcfp.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hywenlv.cn/Article/details/gtrxovllrb.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jqgfzy.top/Article/details/gtolmuuupo.html

[A18] 字符与 ASCII 码互转
来源：http://dali.cheryme.top/Article/details/gtvvjbsaqq.html

Py:   ord("A"); chr(65)
来源：http://dali.jyoumei.cn/Article/details/gtswtszavc.html

PHP:  ord("A"); chr(65)
来源：http://dali.shanyushiyangtech.top/Article/details/gtngflqivp.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.guannengcc.top/Article/details/gtrrfllqyv.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.chenzaomai.com/Article/details/gtuiorhkmx.html

Java: (int) 'A'; (char) 65
来源：http://dali.xuetiantiany.cn/Article/details/gtwbehwgat.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.nanxinkj.top/Article/details/gtrkeaqwjf.html

Ruby: "A".ord; 65.chr
来源：http://dali.zhongyouzk.top/Article/details/gtueytwdoh.html

C#:   (int)'A'; (char)65
来源：http://dali.iojbl.cn/Article/details/gtzkvbbjob.html

[A19] 交换两个变量
来源：http://dali.xinyue.icu/Article/details/gtfqlbrvwe.html

Py:   a, b = b, a
来源：http://dali.snrcjt.cn/Article/details/gthkwdelwc.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.guowangkeji.top/Article/details/gtukqzydgu.html

JS:   [a, b] = [b, a];
来源：http://dali.yonumen.top/Article/details/gtktpkxkud.html

TS:   [a, b] = [b, a];
来源：http://dali.zhengqikj.top/Article/details/gtcxxveqch.html

Java: int t = a; a = b; b = t;
来源：http://dali.hnxiangtu.top/Article/details/gtgafzlrnh.html

Go:   a, b = b, a
来源：http://dali.nanxinkj.top/Article/details/gtkamsvfmf.html

Ruby: a, b = b, a
来源：http://dali.xylfe.cn/Article/details/gtxlzpxogp.html

C#:   (a, b) = (b, a);
来源：http://dali.chenlongwang.top/Article/details/gtovdvkafd.html

[A20] 读取标准输入
来源：http://dali.hammf.cn/Article/details/gthkvmdnho.html

Py:   name = input("请输入：")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtroprkbiz.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.zhiwuduotai.top/Article/details/gtckxpityj.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.yanxiufei.cn/Article/details/gtgtlxyaso.html

TS:   // Node.js：readline 模块
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpyulgufy.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.hnqzz.top/Article/details/gtmwiewkgn.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.sufxvd.cn/Article/details/gttcrudchj.html

Ruby: gets.chomp
来源：http://dali.yvedp.cn/Article/details/gtuoekvzzr.html

C#:   Console.ReadLine();
来源：http://dali.redwolf501.top/Article/details/gtbzhhgrwe.html

[A21] 保留指定小数位输出
来源：http://dali.jyoumei.cn/Article/details/gtjyvmazym.html

Py:   f"{3.14159:.2f}"
来源：http://dali.hfpthk.cn/Article/details/gtxuzmfkin.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.zycfv.cn/Article/details/gtxryfbvqe.html

JS:   (3.14159).toFixed(2)
来源：http://dali.birdmap.top/Article/details/gthuywpadj.html

TS:   (3.14159).toFixed(2)
来源：http://dali.hnxiangtu.top/Article/details/gtrwhthcje.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.316326.xyz/Article/details/gtsdwyovde.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.ivvv.top/Article/details/gtpyqqibge.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.shzxlz.cn/Article/details/gtqnqhzacz.html

C#:   3.14159.ToString("F2")
来源：http://dali.guannengcc.top/Article/details/gtaqeahsxy.html

[A22] 获取字符串长度
来源：http://dali.xuetiantiany.cn/Article/details/gtvuyagvox.html

Py:   len(s)
来源：http://dali.quarkkingdee.top/Article/details/gtxlfpooog.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.zhengqikj.top/Article/details/gtjgajealt.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.daria6918.cn/Article/details/gtiexnvkzf.html

TS:   s.length
来源：http://dali.jinghuilouyu.cn/Article/details/gtusjrjosx.html

Java: s.length()
来源：http://dali.nwbrower.top/Article/details/gtrjrxsolb.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.redwolf501.top/Article/details/gtzkcfnawj.html

Ruby: s.length
来源：http://dali.smart0.xyz/Article/details/gtiolyyxwr.html

C#:   s.Length
来源：http://dali.yueranfly.top/Article/details/gtvpmgqmby.html

[A23] 大小写转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkdanetep.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.vqdsnc.cn/Article/details/gtsdqduoyb.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.yuxming.cn/Article/details/gtyobzpnqc.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yongpay.top/Article/details/gtnuputsiz.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.pengpengdd.cyou/Article/details/gtuhydogtg.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.guowangkeji.top/Article/details/gtiuqlzdfp.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.shzxlz.cn/Article/details/gtsgsvercz.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.haohaochexian.top/Article/details/gtizgjpttp.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.pengpengdd.cyou/Article/details/gttgrslcyg.html

[A24] 去除首尾空白
来源：http://dali.ehwqpu.com/Article/details/gtyicpvvek.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.chenlongwang.top/Article/details/gtyehylatx.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.jinqigfzy.top/Article/details/gtrabhusre.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.shanyushiyangtech.top/Article/details/gtaohwafcd.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcxwzmjln.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zhiwuduotai.top/Article/details/gtjvlcizxq.html

Go:   strings.TrimSpace(s)
来源：http://dali.yj202588.top/Article/details/gttllmzimz.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.zycfv.cn/Article/details/gtsmfmvgai.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.fzhhl.top/Article/details/gtzaifmuja.html

[A25] 字符串比较
来源：http://dali.chenjidiqi.icu/Article/details/gtpqthvdbj.html

Py:   s1 == s2; s1 != s2
来源：http://dali.aizwys.cn/Article/details/gtapzqfrsf.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.haohaochexian.top/Article/details/gtvbswtdoj.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.dashuyun.cn/Article/details/gtyhyuexbt.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.gotoacloud.top/Article/details/gtkknbqqze.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.tianlin.xyz/Article/details/gtanirgjuy.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.hysaishi.cn/Article/details/gtjmzgzbqg.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.gzhubu.top/Article/details/gtxhadocsk.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.shuidangran.top/Article/details/gtzhxnowuf.html

[A26] 类型转换总览
来源：http://dali.jqgfzy.top/Article/details/gtgoyeqzki.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.tianlin.xyz/Article/details/gtenewnpaj.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.tanke756.top/Article/details/gtpnvetyzj.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.pycfn.com/Article/details/gtcbfftaty.html

TS:   Number() String() Boolean() x as number
来源：http://dali.svipenyu.cn/Article/details/gtkbpmfgtm.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.chenzaomai.com/Article/details/gtvzalxdqw.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.gaohongyu789.top/Article/details/gtzjpwcfdc.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwyyhakml.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yanxiufei.cn/Article/details/gtysubwcjo.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gttezzowed.html

B. 流程控制
来源：http://dali.fzhhl.top/Article/details/gtobyfzuww.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtyjwupbkw.html

[B01] 条件判断 if / else
来源：http://dali.daxiang520.top/Article/details/gtfxhlnkwa.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.shzxlz.cn/Article/details/gtbtwohmfb.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.haohaochexian.top/Article/details/gtprzhwzcq.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.fengsongda.top/Article/details/gtxahfzbdi.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.birdmap.top/Article/details/gtoaxjefpp.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jiagoushi.top/Article/details/gtydzfrscs.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.nanxinkj.top/Article/details/gtgluvyvqx.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtckvjtjjt.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jlsjyb.cn/Article/details/gtulbpmqly.html

[B02] 多分支 else if / elif
来源：http://dali.iojbl.cn/Article/details/gtspkluprm.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.hnqzz.top/Article/details/gtymbkdzmb.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yangfankeji.com/Article/details/gtdpfdrtki.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhixingplan.top/Article/details/gtvmnjrfly.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttdotpfqd.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtblaqvhuq.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.xinyue.icu/Article/details/gtmxvmpoxa.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.9152youxi.cn/Article/details/gttfackarf.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nanxuanxn.top/Article/details/gthqzicoku.html

[B03] switch / match / case
来源：http://dali.yvedp.cn/Article/details/gtandjqjfe.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.ydzc1.top/Article/details/gtadtmcrdy.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.dashuyun.cn/Article/details/gtjgnheqzf.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hysaishi.cn/Article/details/gtlmrdqsnd.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhongyouzk.top/Article/details/gtwqrzsxyq.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.mhx1999.top/Article/details/gtozshunjh.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.xinyue.icu/Article/details/gtnhobpchr.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.nanxuanxn.top/Article/details/gteikroaeo.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.cashguo.top/Article/details/gthxueihcw.html

[B04] for 计数循环
来源：http://dali.hysaishi.cn/Article/details/gttlbsvuqc.html

Py:   for i in range(10): print(i)
来源：http://dali.jqgufenzy.top/Article/details/gtiyyzmqkm.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jyoumei.cn/Article/details/gtymctxemx.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.tanke756.top/Article/details/gtcwbsxtpb.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsowxvchw.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.bjfxy.top/Article/details/gtfhnlrlut.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.jlsjyb.cn/Article/details/gtdgoymbhh.html

Ruby: 10.times { |i| puts i }
来源：http://dali.cheryme.top/Article/details/gtsglevlxd.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.ehwqpu.com/Article/details/gtckwkzjxk.html

[B05] 遍历数组 / 列表
来源：http://dali.xuanzx.com/Article/details/gtgmfkcgwn.html

Py:   for item in arr: print(item)
来源：http://dali.zhijiandao.cn/Article/details/gtspbbdvcr.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.daxiang520.top/Article/details/gtvsymbzjr.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jqgfzy.top/Article/details/gtkdiclimf.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.iojbl.cn/Article/details/gtcqxuptqg.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.wangshuangyany.cn/Article/details/gtcikwxrjr.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.9152youxi.cn/Article/details/gttkokjqmb.html

Ruby: arr.each { |item| puts item }
来源：http://dali.meibo888.top/Article/details/gtgyerqqnb.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.shzxlz.cn/Article/details/gtualwqkzg.html

[B06] 遍历字典 / 对象
来源：http://dali.shzxlz.cn/Article/details/gtrfgqytkd.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.hnqzz.top/Article/details/gtlynqawst.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hysaishi.cn/Article/details/gtombppbwi.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zdqjudy.top/Article/details/gteigrhumd.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.svipenyu.cn/Article/details/gtyfcbkuki.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.nanxuanxn.top/Article/details/gtlcuybucw.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yongpay.top/Article/details/gtlpjletkf.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.chenzaomai.com/Article/details/gtfzmfhver.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.9152youxi.cn/Article/details/gtdqjzpnuv.html

[B07] while 循环
来源：http://dali.hywenlv.cn/Article/details/gtvjkzgcox.html

Py:   while i < 10: i += 1
来源：http://dali.ivvv.top/Article/details/gttoglhail.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jinqigfzy.top/Article/details/gtuexaqkhx.html

JS:   while (i < 10) { i++; }
来源：http://dali.snrcjt.cn/Article/details/gtfglqhgun.html

TS:   while (i < 10) { i++; }
来源：http://dali.jianghu66.top/Article/details/gtuleergdu.html

Java: while (i < 10) { i++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtksypqnju.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.iojbl.cn/Article/details/gtyncrmfnw.html

Ruby: while i < 10; i += 1; end
来源：http://dali.hongshengwenyu.top/Article/details/gtbaorwrco.html

C#:   while (i < 10) { i++; }
来源：http://dali.xziqi.cn/Article/details/gtckgdvknz.html

[B08] do-while（至少执行一次）
来源：http://dali.tian-w.cn/Article/details/gthntbeeil.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.feifeiyinyue.top/Article/details/gtharilnww.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jqgfzy.top/Article/details/gtncctleml.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yj20258.top/Article/details/gtpjoimewq.html

TS:   do { i++; } while (i < 10);
来源：http://dali.xuanzx.com/Article/details/gtwknqhqqr.html

Java: do { i++; } while (i < 10);
来源：http://dali.mhx1999.top/Article/details/gtlgyoxoiv.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jlsjyb.cn/Article/details/gtxppalqal.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.pengpengdd.cyou/Article/details/gtwemfyxwl.html

C#:   do { i++; } while (i < 10);
来源：http://dali.quarkkingdee.top/Article/details/gtuxisdfhp.html

[B09] break 与 continue
来源：http://dali.aizwys.cn/Article/details/gtpdhpfbrx.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jinqigfzy.top/Article/details/gtlbxaegzp.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.sysykeji.top/Article/details/gtpgybzhvz.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcqfiangh.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xziqi.cn/Article/details/gtgywidgvw.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hysaishi.cn/Article/details/gtixyposfp.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ydzc1.top/Article/details/gteuygxukv.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.xuetiantiany.cn/Article/details/gtbhmrsdty.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aibaodan.cn/Article/details/gtrhagurcz.html

[B10] 遍历同时拿索引
来源：http://dali.vqdsnc.cn/Article/details/gtzteebbrv.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yongpay.top/Article/details/gtlnvjioih.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.ybcxt.top/Article/details/gtjpffbuxr.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jinqigufen.top/Article/details/gtxblxbyta.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jqgufenzy.top/Article/details/gteuqrqymq.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.gotoacloud.top/Article/details/gtaksxgjkm.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtesnxurje.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.gzhubu.top/Article/details/gtxbepgdsa.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.cqqwz.cn/Article/details/gtrrpsjlbg.html

[B11] 生成数字序列 / 区间
来源：http://dali.aizwys.cn/Article/details/gtucqrtaoq.html

Py:   list(range(0, 10, 2))
来源：http://dali.jqgufenzy.top/Article/details/gtxljqcyzv.html

PHP:  range(0, 10, 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwcjdigdm.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jyoumei.cn/Article/details/gtdcsrpdjm.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.quarkkingdee.top/Article/details/gtzckngqgp.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yj20258.top/Article/details/gtrrjanrtw.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.wangdashe.top/Article/details/gtegligsyx.html

Ruby: (0...10).step(2).to_a
来源：http://dali.feifeiyinyue.top/Article/details/gtlfvqorsl.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.ppjwa.cn/Article/details/gtjswwviir.html

[B12] 跳出多层循环
来源：http://dali.ivvv.top/Article/details/gtfhhlknkw.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.birdmap.top/Article/details/gtlkeapmed.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.gotoacloud.top/Article/details/gthqbbkiog.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.svipenyu.cn/Article/details/gtvabrxqok.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ppjwa.cn/Article/details/gtmnaezxya.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzvzwtcky.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.316326.xyz/Article/details/gthkqihusz.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.shangyingyoupin.top/Article/details/gtkydwtqoe.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhiwuduotai.top/Article/details/gtrxkrjskt.html

[B13] 判断是否为数字
来源：http://dali.chenlongwang.top/Article/details/gtzaqttphs.html

Py:   isinstance(x, (int, float))
来源：http://dali.yj20258.top/Article/details/gtandalapz.html

PHP:  is_numeric($x)
来源：http://dali.haohaochexian.top/Article/details/gtauptmqdd.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jqgufenzy.top/Article/details/gtolwpnyil.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtefawqxwr.html

Java: x instanceof Number
来源：http://dali.ybcxt.top/Article/details/gtmsttosnd.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhengqikj.top/Article/details/gtlkufphcj.html

Ruby: x.is_a?(Numeric)
来源：http://dali.shangyingyoupin.top/Article/details/gtveluneqe.html

C#:   x is int or double or decimal
来源：http://dali.fengsongda.top/Article/details/gtymgfnwgh.html

[B14] 判断值是否在集合内
来源：http://dali.zhiwuduotai.top/Article/details/gtnirkokaq.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yongpay.top/Article/details/gtmhazmgnl.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.xziqi.cn/Article/details/gtwgqdextx.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.316326.xyz/Article/details/gtqebwaczk.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtchofstzw.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ivvv.top/Article/details/gtysmzyxod.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.sufxvd.cn/Article/details/gtxyuvoaez.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jyoumei.cn/Article/details/gtfkeqelfi.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jinqigufen.top/Article/details/gtcpmsilyp.html

[B15] 布尔运算与取反
来源：http://dali.guowangkeji.top/Article/details/gthmibqtvi.html

Py:   a and b or not c
来源：http://dali.hysaishi.cn/Article/details/gtbhjbtqyg.html

PHP:  $a && $b || !$c
来源：http://dali.nwbrower.top/Article/details/gtizwvxomf.html

JS:   a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gtnvgmyxjz.html

TS:   a && b || !c
来源：http://dali.guowangkeji.top/Article/details/gtrsqxcaxq.html

Java: a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gtmmdaygky.html

Go:   a && b || !c
来源：http://dali.aizwys.cn/Article/details/gtizweptzx.html

Ruby: a && b || !c
来源：http://dali.zycfv.cn/Article/details/gtkbzyhnli.html

C#:   a && b || !c
来源：http://dali.tianlin.xyz/Article/details/gtdmwrbkii.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.0kj1m.cn/Article/details/gtegrzaria.html

Py:   if not data: return
来源：http://dali.gotoacloud.top/Article/details/gtouzcizdb.html

PHP:  if (!$data) { return; }
来源：http://dali.chenzaomai.com/Article/details/gtbpivbbwb.html

JS:   if (!data) return;
来源：http://dali.zhoulong.xyz/Article/details/gtwezwygvp.html

TS:   if (!data) return;
来源：http://dali.kuanghao11.cn/Article/details/gttqcwkomu.html

Java: if (data == null) return;
来源：http://dali.daxiang520.top/Article/details/gtpjxddtuk.html

Go:   if data == nil { return }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrulbukcp.html

Ruby: return if data.nil?
来源：http://dali.redwolf501.top/Article/details/gthakpuxnf.html

C#:   if (data == null) return;
来源：http://dali.shanyushiyangtech.top/Article/details/gtdtieusxm.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtumgmsibp.html

C. 函数与作用域
来源：http://dali.zhoulong.xyz/Article/details/gtytzluzbr.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gttoddwxza.html

[C01] 定义函数
来源：http://dali.xziqi.cn/Article/details/gtfglbfebm.html

Py:   def add(a, b): return a + b
来源：http://dali.hnqzz.top/Article/details/gtzhdmjjry.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shuidangran.top/Article/details/gtasjiclnj.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gtkgslgkab.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gtapfywrvy.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yonumen.top/Article/details/gtihfdpdvl.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.cdnleiting.top/Article/details/gtlvkbhxbh.html

Ruby: def add(a, b); a + b; end
来源：http://dali.tianlin.xyz/Article/details/gtiyfdrlft.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yanxiufei.cn/Article/details/gtrbukukby.html

[C02] 默认参数
来源：http://dali.chenlongwang.top/Article/details/gtglmltact.html

Py:   def greet(name="World"): return name
来源：http://dali.316326.xyz/Article/details/gtsyxqsiji.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yj20258.top/Article/details/gtyeobybit.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.tanke756.top/Article/details/gtjyfoakea.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhengqikj.top/Article/details/gtssmzzrjv.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yanxiufei.cn/Article/details/gtoargovhd.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jiagoushi.top/Article/details/gtqjvsfhbz.html

Ruby: def greet(name = "World") = name
来源：http://dali.bjfxy.top/Article/details/gtjsmsijeu.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.wangdashe.top/Article/details/gtrkdlosib.html

[C03] 可变参数
来源：http://dali.snrcjt.cn/Article/details/gthdmjzdpp.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhoulong.xyz/Article/details/gtwkauzehz.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtflslgaik.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhixingplan.top/Article/details/gtumhgpnrx.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.daria6918.cn/Article/details/gtybhkqiaa.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.vqdsnc.cn/Article/details/gtyhdchtbk.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.iojbl.cn/Article/details/gtitjoismd.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhoulong.xyz/Article/details/gtfikfnvxp.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.sweek.top/Article/details/gtyeocziil.html

[C04] 命名参数 / 关键字参数
来源：http://dali.xziqi.cn/Article/details/gtcikdugfr.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.cheryme.top/Article/details/gtegosmtnn.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.tanke756.top/Article/details/gtononhxil.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.tian-w.cn/Article/details/gthafyhtch.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cashguo.top/Article/details/gtxthemotb.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.guowangkeji.top/Article/details/gtylvqopam.html

Go:   // 无：用配置结构体参数
来源：http://dali.jyoumei.cn/Article/details/gtluyeqgdl.html

Ruby: f(a: 1, b: 2)
来源：http://dali.sufxvd.cn/Article/details/gtifkivppf.html

C#:   f(a: 1, b: 2)
来源：http://dali.yonumen.top/Article/details/gtwneluunx.html

[C05] 返回多个值
来源：http://dali.havefunace.top/Article/details/gtmrveqgow.html

Py:   return a, b
来源：http://dali.guannengcc.top/Article/details/gtzprjtxtz.html

PHP:  return [$a, $b];
来源：http://dali.chenzaomai.com/Article/details/gthartylle.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.sysykeji.top/Article/details/gtxqavhsom.html

TS:   return { a, b };
来源：http://dali.yongpay.top/Article/details/gtvsaivbpe.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ivvv.top/Article/details/gtvapijxrp.html

Go:   return a, b
来源：http://dali.quarkkingdee.top/Article/details/gttmjtwwyy.html

Ruby: return a, b
来源：http://dali.aibaodan.cn/Article/details/gtyodstgdk.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hnqzz.top/Article/details/gtjonxcikv.html

[C06] 匿名函数 / lambda
来源：http://dali.birdmap.top/Article/details/gtpvubakfs.html

Py:   square = lambda x: x * x
来源：http://dali.jinqigufen.top/Article/details/gtvjiyfzyy.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.guannengcc.top/Article/details/gtoeyxhqce.html

JS:   const square = x => x * x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrsadlzpk.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jianghu66.top/Article/details/gteikjxcol.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yanxiufei.cn/Article/details/gtszysrugs.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.nanxinkj.top/Article/details/gtrfkeuwnw.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzoolcsgt.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.mhx1999.top/Article/details/gtanoagmsg.html

[C07] 把函数作为参数传入
来源：http://dali.cqqwz.cn/Article/details/gtnkfiecvz.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhongyouzk.top/Article/details/gthtuddwvx.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.bjfxy.top/Article/details/gtsxaazajb.html


<!-- 参考信息 -->