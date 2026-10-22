代发 wailian999

Ruby: a, b = b, a
来源：http://dali.tianlin.xyz/Article/details/gt2ttwynqgk.html

C#:   (a, b) = (b, a);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2idvsermo.html

[A20] 读取标准输入
来源：http://dali.sweek.top/Article/details/gt2nnibmnrs.html

Py:   name = input("请输入：")
来源：http://dali.xuetiantiany.cn/Article/details/gt2vdlnbpfi.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.pengpengdd.cyou/Article/details/gt2elizcmng.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2utvyzjcg.html

TS:   // Node.js：readline 模块
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2basewcyt.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.fengsongda.top/Article/details/gt2nkmwsjnd.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.jiagoushi.top/Article/details/gt2zetzzwix.html

Ruby: gets.chomp
来源：http://dali.tanke756.top/Article/details/gt2zeqeupzs.html

C#:   Console.ReadLine();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ntfdhywj.html

[A21] 保留指定小数位输出
来源：http://dali.hongshengwenyu.top/Article/details/gt2ivkpuisb.html

Py:   f"{3.14159:.2f}"
来源：http://dali.cqqwz.cn/Article/details/gt2vardhyqh.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.havefunace.top/Article/details/gt2dirydpus.html

JS:   (3.14159).toFixed(2)
来源：http://dali.gaohongyu789.top/Article/details/gt2jeyxeamu.html

TS:   (3.14159).toFixed(2)
来源：http://dali.jianghu66.top/Article/details/gt2mqyzpqnb.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ufgejbmp.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.hnqzz.top/Article/details/gt2uxgqiors.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.ehwqpu.com/Article/details/gt2pyqcckoq.html

C#:   3.14159.ToString("F2")
来源：http://dali.xuanzx.com/Article/details/gt2cayyodms.html

[A22] 获取字符串长度
来源：http://dali.vqdsnc.cn/Article/details/gt2yellzese.html

Py:   len(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2bjboupbt.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.pengpengdd.cyou/Article/details/gt2nkrkkvcn.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.yongpay.top/Article/details/gt2otusdxmu.html

TS:   s.length
来源：http://dali.9152youxi.cn/Article/details/gt2jjzltjlm.html

Java: s.length()
来源：http://dali.hongshengwenyu.top/Article/details/gt2wbikaylf.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.gzhubu.top/Article/details/gt2hgjrhiet.html

Ruby: s.length
来源：http://dali.aizwys.cn/Article/details/gt2xnbkgutm.html

C#:   s.Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gyecpunx.html

[A23] 大小写转换
来源：http://dali.nwbrower.top/Article/details/gt2apkuvabj.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.zdqjudy.top/Article/details/gt2kionxmxe.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.yuanzhike.top/Article/details/gt2ljwysozn.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nykjdlfs.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.havefunace.top/Article/details/gt2unniigjz.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.gaohongyu789.top/Article/details/gt2rbvtcclo.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.aibaodan.cn/Article/details/gt2fumixedw.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.zhongyouzk.top/Article/details/gt2gphmunzz.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.bjfxy.top/Article/details/gt2yigrnqxm.html

[A24] 去除首尾空白
来源：http://dali.yueranfly.top/Article/details/gt2fbkvndte.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.kuanghao11.cn/Article/details/gt2jkjeqrgs.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.dianchejie.cn/Article/details/gt2bkjwtudb.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.pycfn.com/Article/details/gt2qlmtnzxx.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.0kj1m.cn/Article/details/gt2uvwbszpo.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.xuetiantiany.cn/Article/details/gt2yoxlqajt.html

Go:   strings.TrimSpace(s)
来源：http://dali.hammf.cn/Article/details/gt2umtvmqhf.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.hnxiangtu.top/Article/details/gt2rnvogmpo.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.dashuyun.cn/Article/details/gt2urhmtttg.html

[A25] 字符串比较
来源：http://dali.ivvv.top/Article/details/gt2ouxnvvte.html

Py:   s1 == s2; s1 != s2
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qcdclzpv.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.gogol.net.cn/Article/details/gt2kliyilml.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.sxryk.cn/Article/details/gt2xsayjovl.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.meibo888.top/Article/details/gt2igumwcua.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.hammf.cn/Article/details/gt2anaowxdj.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.shuidangran.top/Article/details/gt2rotbqbpo.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.yuanzhike.top/Article/details/gt2pptcphwy.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.quarkkingdee.top/Article/details/gt2ekyipsiu.html

[A26] 类型转换总览
来源：http://dali.jiagoushi.top/Article/details/gt2cidpfoyt.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.xylfe.cn/Article/details/gt2feoyszyb.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.ivvv.top/Article/details/gt2uqclfqib.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gpgdzsvo.html

TS:   Number() String() Boolean() x as number
来源：http://dali.cqqwz.cn/Article/details/gt2zpatsjsu.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zdqjudy.top/Article/details/gt2snlvvgzz.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yj20258.top/Article/details/gt2cqaachfe.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.9152youxi.cn/Article/details/gt2ksevlfle.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xdqsvjgj.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2optdfshn.html

B. 流程控制
来源：http://dali.iojbl.cn/Article/details/gt2cfbcsdqo.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2jxdriakk.html

[B01] 条件判断 if / else
来源：http://dali.bjfxy.top/Article/details/gt2gjxtzahd.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.nanxuanxn.top/Article/details/gt2grythiip.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yj20258888.top/Article/details/gt2hzxphhjg.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yuanzhike.top/Article/details/gt2mmctqcmt.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.gzhubu.top/Article/details/gt2jfvxmoky.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.hammf.cn/Article/details/gt2rilhztts.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.xinyue.icu/Article/details/gt2vntanrwc.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.xziqi.cn/Article/details/gt2qmxibrpy.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vczsfere.html

[B02] 多分支 else if / elif
来源：http://dali.gotoacloud.top/Article/details/gt2gmbpstyr.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.dashuyun.cn/Article/details/gt2rbeacmmq.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eavibwdv.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jqgufenzy.top/Article/details/gt2qbmydwno.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.feifeiyinyue.top/Article/details/gt2uwnbgyih.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shzxlz.cn/Article/details/gt2qnjledcw.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yanxiufei.cn/Article/details/gt2ymyjjtlj.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.zhijiandao.cn/Article/details/gt2nsthxplx.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.316326.xyz/Article/details/gt2zknwiegw.html

[B03] switch / match / case
来源：http://dali.shzxlz.cn/Article/details/gt2niqvdiyy.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.havefunace.top/Article/details/gt2uzmrmzrm.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2hitkxbbn.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yuxming.cn/Article/details/gt2butfxzll.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.daxiang520.top/Article/details/gt2iclgdrtd.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2izpfifyq.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.mhx1999.top/Article/details/gt2shcrnmeu.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.pycfn.com/Article/details/gt2unabxubo.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.vqdsnc.cn/Article/details/gt2opulvlbw.html

[B04] for 计数循环
来源：http://dali.andypj.xyz/Article/details/gt2ibntzgmj.html

Py:   for i in range(10): print(i)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xjiiwvgl.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.chenzaomai.com/Article/details/gt2nnetzzer.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hnxiangtu.top/Article/details/gt2kzsxgbnw.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xinyue.icu/Article/details/gt2zssjdtnl.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.xuanzx.com/Article/details/gt2fxrhbkmi.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.nanxinkj.top/Article/details/gt2yvmrviun.html

Ruby: 10.times { |i| puts i }
来源：http://dali.jqgufenzy.top/Article/details/gt2vnwvxekl.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.haohaochexian.top/Article/details/gt2ixwelybg.html

[B05] 遍历数组 / 列表
来源：http://dali.xinyue.icu/Article/details/gt2xisfegjp.html

Py:   for item in arr: print(item)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgfzklim.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.daria6918.cn/Article/details/gt2xfobkbgx.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yanxiufei.cn/Article/details/gt2wmfqycbu.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yvedp.cn/Article/details/gt2meoncfua.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hnqzz.top/Article/details/gt2epckfssn.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.gaohongyu789.top/Article/details/gt2tyagljbs.html

Ruby: arr.each { |item| puts item }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zrazsitb.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.cdnleiting.top/Article/details/gt2nxagkrvr.html

[B06] 遍历字典 / 对象
来源：http://dali.sweek.top/Article/details/gt2rktnknfh.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.hnxiangtu.top/Article/details/gt2jieroppn.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.aizwys.cn/Article/details/gt2hnamjkly.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yvedp.cn/Article/details/gt2wwrewdvg.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2qngzcwwm.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2opvlpkbt.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.ppjwa.cn/Article/details/gt2yfxpkgcf.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.xuanzx.com/Article/details/gt2ajbqmrll.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.sufxvd.cn/Article/details/gt2rofbqiez.html

[B07] while 循环
来源：http://dali.xylfe.cn/Article/details/gt2veicpbvx.html

Py:   while i < 10: i += 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oqujawcf.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.gotoacloud.top/Article/details/gt2muzfnhvj.html

JS:   while (i < 10) { i++; }
来源：http://dali.316326.xyz/Article/details/gt2zzuctwac.html

TS:   while (i < 10) { i++; }
来源：http://dali.cheryme.top/Article/details/gt2mhuadvec.html

Java: while (i < 10) { i++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2melrxuqw.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.vqdsnc.cn/Article/details/gt2mpigyiwo.html

Ruby: while i < 10; i += 1; end
来源：http://dali.fengsongda.top/Article/details/gt2qkpxbaiv.html

C#:   while (i < 10) { i++; }
来源：http://dali.hywenlv.cn/Article/details/gt2lhkcixao.html

[B08] do-while（至少执行一次）
来源：http://dali.yongpay.top/Article/details/gt2gsljnqgq.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.daria6918.cn/Article/details/gt2wozvzwim.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jianghu66.top/Article/details/gt2akcnxwgi.html

JS:   do { i++; } while (i < 10);
来源：http://dali.fengsongda.top/Article/details/gt2pashiyvg.html

TS:   do { i++; } while (i < 10);
来源：http://dali.dashuyun.cn/Article/details/gt2qwhxoqzm.html

Java: do { i++; } while (i < 10);
来源：http://dali.c1oappe.top/Article/details/gt2lbthufzx.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.chenjidiqi.icu/Article/details/gt2tuuckerj.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jqgufenzy.top/Article/details/gt2piuoyulz.html

C#:   do { i++; } while (i < 10);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ciadhjtl.html

[B09] break 与 continue
来源：http://dali.chenzaomai.com/Article/details/gt2mpsdgbyl.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.pycfn.com/Article/details/gt2uzcfncpo.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.nanxinkj.top/Article/details/gt2zfawqmpf.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2bkakvcym.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hysaishi.cn/Article/details/gt2nhbaubmw.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.bjfxy.top/Article/details/gt2vsqmjrid.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.svipenyu.cn/Article/details/gt2uaitnuvh.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.xuanzx.com/Article/details/gt2xsoykaqq.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jiagoushi.top/Article/details/gt2tuuutqvs.html

[B10] 遍历同时拿索引
来源：http://dali.xziqi.cn/Article/details/gt2asqwoebj.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.tian-w.cn/Article/details/gt2ogzmvzea.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2zbpvapet.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.0kj1m.cn/Article/details/gt2ofshcspn.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.chenzaomai.com/Article/details/gt2yjkmmfoc.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.birdmap.top/Article/details/gt2qudibtgo.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hywenlv.cn/Article/details/gt2aepjgazd.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.dianchejie.cn/Article/details/gt2iblddqkq.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.snrcjt.cn/Article/details/gt2xhatepvk.html

[B11] 生成数字序列 / 区间
来源：http://dali.sweek.top/Article/details/gt2npcgekys.html

Py:   list(range(0, 10, 2))
来源：http://dali.ehwqpu.com/Article/details/gt2dxokwlkd.html

PHP:  range(0, 10, 2);
来源：http://dali.hysaishi.cn/Article/details/gt2uxlehzvx.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gogol.net.cn/Article/details/gt2xskqyfsl.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.aibaodan.cn/Article/details/gt2qqedrkxt.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.iojbl.cn/Article/details/gt2gfudmsiv.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.sweek.top/Article/details/gt2lzolybyr.html

Ruby: (0...10).step(2).to_a
来源：http://dali.guannengcc.top/Article/details/gt2ielhtdrg.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yj202588.top/Article/details/gt2huncmuzz.html

[B12] 跳出多层循环
来源：http://dali.fengsongda.top/Article/details/gt2aqavaxfv.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.ppjwa.cn/Article/details/gt2rcoegwvb.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.havefunace.top/Article/details/gt2kjgvxhjn.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangshuangyany.cn/Article/details/gt2bncebmiv.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxinkj.top/Article/details/gt2unpgjrvf.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.gotoacloud.top/Article/details/gt2jhmelene.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xylfe.cn/Article/details/gt2jphfwclj.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.aizwys.cn/Article/details/gt2qtdzaaxq.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.feifeiyinyue.top/Article/details/gt2tuxyvzoa.html

[B13] 判断是否为数字
来源：http://dali.sweek.top/Article/details/gt2xnfaqdll.html

Py:   isinstance(x, (int, float))
来源：http://dali.jqgufenzy.top/Article/details/gt2miwcfgau.html

PHP:  is_numeric($x)
来源：http://dali.jinqigufen.top/Article/details/gt2gaoyvmul.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.fzhhl.top/Article/details/gt2roacyxtk.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2fjnwocap.html

Java: x instanceof Number
来源：http://dali.yuanzhike.top/Article/details/gt2jfwakfxx.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ybcxt.top/Article/details/gt2qlttpxhz.html

Ruby: x.is_a?(Numeric)
来源：http://dali.316326.xyz/Article/details/gt2elhraxwx.html

C#:   x is int or double or decimal
来源：http://dali.dashuyun.cn/Article/details/gt2wdgvmrtb.html

[B14] 判断值是否在集合内
来源：http://dali.nanxinkj.top/Article/details/gt2fztmoqcn.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.haohaochexian.top/Article/details/gt2aiylaulv.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhoulong.xyz/Article/details/gt2sjezlbnh.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.pycfn.com/Article/details/gt2tzmnwpmu.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jinqigufen.top/Article/details/gt2uqzglaof.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.gotoacloud.top/Article/details/gt2lgjiyvbk.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jyoumei.cn/Article/details/gt2uxbjxnyk.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2wrhyovyb.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2thhfugel.html

[B15] 布尔运算与取反
来源：http://dali.jinqigufen.top/Article/details/gt2fluhvyjh.html

Py:   a and b or not c
来源：http://dali.pycfn.com/Article/details/gt2bdwdwotr.html

PHP:  $a && $b || !$c
来源：http://dali.jianghu66.top/Article/details/gt2oxcgtxvh.html

JS:   a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gt2geijwvsl.html

TS:   a && b || !c
来源：http://dali.aizwys.cn/Article/details/gt2zypwgkvw.html

Java: a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gt2aodffsxq.html

Go:   a && b || !c
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tdistbvu.html

Ruby: a && b || !c
来源：http://dali.aizwys.cn/Article/details/gt2oehskflv.html

C#:   a && b || !c
来源：http://dali.andypj.xyz/Article/details/gt2enwlzidc.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yvedp.cn/Article/details/gt2pjrpqaap.html

Py:   if not data: return
来源：http://dali.shzxlz.cn/Article/details/gt2aopbiarv.html

PHP:  if (!$data) { return; }
来源：http://dali.pycfn.com/Article/details/gt2imiihhwd.html

JS:   if (!data) return;
来源：http://dali.zhoulong.xyz/Article/details/gt2mciwpmcz.html

TS:   if (!data) return;
来源：http://dali.hywenlv.cn/Article/details/gt2pwlurdll.html

Java: if (data == null) return;
来源：http://dali.wangdashe.top/Article/details/gt2nvlyufwj.html

Go:   if data == nil { return }
来源：http://dali.nwbrower.top/Article/details/gt2iwmwnzrq.html

Ruby: return if data.nil?
来源：http://dali.shangyingyoupin.top/Article/details/gt2vdozbptu.html

C#:   if (data == null) return;
来源：http://dali.xuanzx.com/Article/details/gt2vsqgkegv.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2stpnnchx.html

C. 函数与作用域
来源：http://dali.xuanzx.com/Article/details/gt2kicfzyzq.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2lhicswlp.html

[C01] 定义函数
来源：http://dali.jlsjyb.cn/Article/details/gt2gcdoomml.html

Py:   def add(a, b): return a + b
来源：http://dali.zdqjudy.top/Article/details/gt2sddwfrwx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aibaodan.cn/Article/details/gt2lxqvzwwg.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2slfhwkpq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gt2brxlrcyr.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gt2zofonixr.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yj20258.top/Article/details/gt2xiwwqotk.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yangfankeji.com/Article/details/gt2dwkivlsc.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gt2jfkhcbuv.html

[C02] 默认参数
来源：http://dali.wangdashe.top/Article/details/gt2rmhkeiwl.html

Py:   def greet(name="World"): return name
来源：http://dali.0kj1m.cn/Article/details/gt2kkwmaypz.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.chenlongwang.top/Article/details/gt2jeikhvha.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.dashuyun.cn/Article/details/gt2elrkgkcf.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ehwqpu.com/Article/details/gt2llotvcsn.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.c1oappe.top/Article/details/gt2dliuugpd.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.c1oappe.top/Article/details/gt2tfnnqbiz.html

Ruby: def greet(name = "World") = name
来源：http://dali.cheryme.top/Article/details/gt2ikgdhgzh.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.guowangkeji.top/Article/details/gt2rkmpprlr.html

[C03] 可变参数
来源：http://dali.nanxinkj.top/Article/details/gt2fhmocsmq.html

Py:   def total(*args): return sum(args)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ustswllz.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hywenlv.cn/Article/details/gt2vkxwbqtr.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gaohongyu789.top/Article/details/gt2ofrfvwdm.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hywenlv.cn/Article/details/gt2rkiinbji.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sgpwfeqn.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kbnfiefd.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.chenlongwang.top/Article/details/gt2ydqcbekn.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kcyqsvol.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhengqikj.top/Article/details/gt2fnvgurgr.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yuxming.cn/Article/details/gt2ifnhpsnw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.sysykeji.top/Article/details/gt2hnqrmfat.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sakilcoi.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cdnleiting.top/Article/details/gt2kxqijurk.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yj202588.top/Article/details/gt2bibarvrd.html

Go:   // 无：用配置结构体参数
来源：http://dali.cheryme.top/Article/details/gt2poaprknr.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhengqikj.top/Article/details/gt2mewwipfc.html

C#:   f(a: 1, b: 2)
来源：http://dali.cqqwz.cn/Article/details/gt2vkjqclgf.html

[C05] 返回多个值
来源：http://dali.zhengqikj.top/Article/details/gt2udakxrsp.html

Py:   return a, b
来源：http://dali.sweek.top/Article/details/gt2npjtquuo.html

PHP:  return [$a, $b];
来源：http://dali.9152youxi.cn/Article/details/gt2gsgmrpls.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2glzvvooq.html

TS:   return { a, b };
来源：http://dali.gotoacloud.top/Article/details/gt2mbeezhij.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jinqigfzy.top/Article/details/gt2woxugzgw.html

Go:   return a, b
来源：http://dali.zhongyouzk.top/Article/details/gt2gfhquycd.html

Ruby: return a, b
来源：http://dali.zhixingplan.top/Article/details/gt2rfeoyrqw.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.c1oappe.top/Article/details/gt2headyxpy.html

[C06] 匿名函数 / lambda
来源：http://dali.tian-w.cn/Article/details/gt2vxuubmfc.html

Py:   square = lambda x: x * x
来源：http://dali.yanxiufei.cn/Article/details/gt2kvdpbizt.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xziqi.cn/Article/details/gt2jihsqgwg.html

JS:   const square = x => x * x;
来源：http://dali.quarkkingdee.top/Article/details/gt2doqooyzf.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.0kj1m.cn/Article/details/gt2eufyekjg.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.chenzaomai.com/Article/details/gt2ugfbtcmh.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.vqdsnc.cn/Article/details/gt2fvouwcmw.html

Ruby: square = ->(x) { x * x }
来源：http://dali.chenlongwang.top/Article/details/gt2ltgtsbtv.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2czwvgqbe.html

[C07] 把函数作为参数传入
来源：http://dali.xuanzx.com/Article/details/gt2toqawpht.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.svipenyu.cn/Article/details/gt2wykuorkk.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jiagoushi.top/Article/details/gt2njwaithf.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhengqikj.top/Article/details/gt2gamcotrl.html

TS:   arr.map(String)
来源：http://dali.jiagoushi.top/Article/details/gt2bntotszp.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yongpay.top/Article/details/gt2drqtntks.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hywenlv.cn/Article/details/gt2kpscapmm.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhiwuduotai.top/Article/details/gt2uaogbmtb.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jiagoushi.top/Article/details/gt2bhgejbgn.html

[C08] 闭包
来源：http://dali.xylfe.cn/Article/details/gt2fcnksxtd.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.vqdsnc.cn/Article/details/gt2ibblizso.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jianghu66.top/Article/details/gt2apwiejjo.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hnqzz.top/Article/details/gt2lzvwxvzr.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.gzhubu.top/Article/details/gt2qswjvhjf.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jyoumei.cn/Article/details/gt2wudecibf.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.ehwqpu.com/Article/details/gt2orauagss.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2esjcpbfu.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.9152youxi.cn/Article/details/gt2etvqopvt.html

[C09] 递归
来源：http://dali.jianghu66.top/Article/details/gt2rljhezqy.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.gaohongyu789.top/Article/details/gt2zxrjvkfz.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.havefunace.top/Article/details/gt2jgjfegkz.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zdqjudy.top/Article/details/gt2zazprybz.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ehwqpu.com/Article/details/gt2jymsjlvc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jqgufenzy.top/Article/details/gt2rtgnuoia.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sxryk.cn/Article/details/gt2nssbgamd.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cheryme.top/Article/details/gt2mtcrhlrd.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.aibaodan.cn/Article/details/gt2zmhvwrbx.html

[C10] 变量作用域
来源：http://dali.shzxlz.cn/Article/details/gt2bmhxjrmw.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ivvv.top/Article/details/gt2gplbkruj.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhongyouzk.top/Article/details/gt2btyzpnfq.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.pycfn.com/Article/details/gt2yzwrmgss.html


<!-- 参考信息 -->