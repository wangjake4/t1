代发 wailian999

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.wangshuangyany.cn/Article/details/gt2esvtpysd.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.yuxming.cn/Article/details/gt2vtafftsd.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.quarkkingdee.top/Article/details/gt2igeqkzif.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cashguo.top/Article/details/gt2bckfsavg.html

[A18] 字符与 ASCII 码互转
来源：http://dali.redwolf501.top/Article/details/gt2ykiaevbg.html

Py:   ord("A"); chr(65)
来源：http://dali.mhx1999.top/Article/details/gt2qqtomolw.html

PHP:  ord("A"); chr(65)
来源：http://dali.ehwqpu.com/Article/details/gt2gjzpzthy.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.nanxinkj.top/Article/details/gt2hepshfed.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.dashuyun.cn/Article/details/gt2ruemnkfo.html

Java: (int) 'A'; (char) 65
来源：http://dali.guannengcc.top/Article/details/gt2zunjuuus.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.nanxuanxn.top/Article/details/gt2baavfcid.html

Ruby: "A".ord; 65.chr
来源：http://dali.tianlin.xyz/Article/details/gt2vjhvjuku.html

C#:   (int)'A'; (char)65
来源：http://dali.iojbl.cn/Article/details/gt2omklgmvx.html

[A19] 交换两个变量
来源：http://dali.nanxinkj.top/Article/details/gt2rcboqhde.html

Py:   a, b = b, a
来源：http://dali.cdnleiting.top/Article/details/gt2fvzoybfs.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.shzxlz.cn/Article/details/gt2oapwmuhx.html

JS:   [a, b] = [b, a];
来源：http://dali.yanxiufei.cn/Article/details/gt2jhppofoy.html

TS:   [a, b] = [b, a];
来源：http://dali.zhengqikj.top/Article/details/gt2zbnndwxf.html

Java: int t = a; a = b; b = t;
来源：http://dali.hongshengwenyu.top/Article/details/gt2jbmqffme.html

Go:   a, b = b, a
来源：http://dali.gaohongyu789.top/Article/details/gt2krlponjc.html

Ruby: a, b = b, a
来源：http://dali.meibo888.top/Article/details/gt2pyzvksny.html

C#:   (a, b) = (b, a);
来源：http://dali.aibaodan.cn/Article/details/gt2goybqbpk.html

[A20] 读取标准输入
来源：http://dali.kuanghao11.cn/Article/details/gt2cnkyifvh.html

Py:   name = input("请输入：")
来源：http://dali.aibaodan.cn/Article/details/gt2enjirueg.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tcnyshfi.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.fzhhl.top/Article/details/gt2oldxkmyt.html

TS:   // Node.js：readline 模块
来源：http://dali.xuanzx.com/Article/details/gt2nbrltrpu.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.meibo888.top/Article/details/gt2bhvuvrno.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.tianlin.xyz/Article/details/gt2pduqdgsk.html

Ruby: gets.chomp
来源：http://dali.sufxvd.cn/Article/details/gt2nklbycgx.html

C#:   Console.ReadLine();
来源：http://dali.ppjwa.cn/Article/details/gt2nhejrvvx.html

[A21] 保留指定小数位输出
来源：http://dali.cqqwz.cn/Article/details/gt2anvdoavm.html

Py:   f"{3.14159:.2f}"
来源：http://dali.nanxinkj.top/Article/details/gt2fmefadnw.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.cheryme.top/Article/details/gt2luubyxne.html

JS:   (3.14159).toFixed(2)
来源：http://dali.dianchejie.cn/Article/details/gt2siejqkyy.html

TS:   (3.14159).toFixed(2)
来源：http://dali.guowangkeji.top/Article/details/gt2nqjkzoyy.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.sufxvd.cn/Article/details/gt2xfoboary.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.jianghu66.top/Article/details/gt2cdnwatsi.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.haohaochexian.top/Article/details/gt2hgtsfvks.html

C#:   3.14159.ToString("F2")
来源：http://dali.cucudq.cn/Article/details/gt2sxbbfdtj.html

[A22] 获取字符串长度
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gljwegux.html

Py:   len(s)
来源：http://dali.tanke756.top/Article/details/gt2mvjkeqkj.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.shangyingyoupin.top/Article/details/gt2ysqqhtzf.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uytavpby.html

TS:   s.length
来源：http://dali.fzhhl.top/Article/details/gt2rpbgston.html

Java: s.length()
来源：http://dali.cqqwz.cn/Article/details/gt2sxobnynh.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kmkvsrnf.html

Ruby: s.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rcjdiisa.html

C#:   s.Length
来源：http://dali.iojbl.cn/Article/details/gt2npopoizx.html

[A23] 大小写转换
来源：http://dali.xylfe.cn/Article/details/gt2tswixczp.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.ehwqpu.com/Article/details/gt2twmblxya.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.yuxming.cn/Article/details/gt2euplmbdy.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yonumen.top/Article/details/gt2cryplepc.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.xylfe.cn/Article/details/gt2bdylqzdd.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.dianchejie.cn/Article/details/gt2paapqfeu.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.sysykeji.top/Article/details/gt2ojawtkmm.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.jqgfzy.top/Article/details/gt2jkblyncw.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.zhixingplan.top/Article/details/gt2wlryjdvn.html

[A24] 去除首尾空白
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tacnxjeb.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.cucudq.cn/Article/details/gt2jbeucwts.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.smart0.xyz/Article/details/gt2eqgrntqf.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.havefunace.top/Article/details/gt2yphfrtyg.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ibawqyum.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.9152youxi.cn/Article/details/gt2hlzzjvrr.html

Go:   strings.TrimSpace(s)
来源：http://dali.zycfv.cn/Article/details/gt2evurgplj.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.hongshengwenyu.top/Article/details/gt2ttetsxzu.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.zhiwuduotai.top/Article/details/gt2kviclghv.html

[A25] 字符串比较
来源：http://dali.pycfn.com/Article/details/gt2slwfcgex.html

Py:   s1 == s2; s1 != s2
来源：http://dali.guowangkeji.top/Article/details/gt2pbtpbmrn.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.ydzc1.top/Article/details/gt2osaxdzpo.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.dashuyun.cn/Article/details/gt2fqemcckt.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yongpay.top/Article/details/gt2oggmvyka.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.ybcxt.top/Article/details/gt2bzkakqbu.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yueranfly.top/Article/details/gt2udanzdfi.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.tian-w.cn/Article/details/gt2reuomuan.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.cdnleiting.top/Article/details/gt2dzhxgkrq.html

[A26] 类型转换总览
来源：http://dali.jiagoushi.top/Article/details/gt2wifhmqgb.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.smart0.xyz/Article/details/gt2eqptrljp.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.yj20258888.top/Article/details/gt2ccktxpfj.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.svipenyu.cn/Article/details/gt2fhiyqvih.html

TS:   Number() String() Boolean() x as number
来源：http://dali.gaohongyu789.top/Article/details/gt2zumfsame.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.pengpengdd.cyou/Article/details/gt2zzwyiwye.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.jqgufenzy.top/Article/details/gt2pbazjkxz.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.ppjwa.cn/Article/details/gt2rbqgfshc.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.hywenlv.cn/Article/details/gt2hgghpgot.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2zuxnxhsw.html

B. 流程控制
来源：http://dali.dashuyun.cn/Article/details/gt2xdlwxbof.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2wqomzszh.html

[B01] 条件判断 if / else
来源：http://dali.wangshuangyany.cn/Article/details/gt2hdtohfli.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.wangdashe.top/Article/details/gt2xsgjyqam.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.guowangkeji.top/Article/details/gt2naylowwr.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xylfe.cn/Article/details/gt2kpkrqcof.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.meibo888.top/Article/details/gt2frlhxnug.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.dianchejie.cn/Article/details/gt2ipbxddzf.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.jinqigufen.top/Article/details/gt2gigruhaf.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.xuanzx.com/Article/details/gt2qopbjhwi.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.guowangkeji.top/Article/details/gt2eqmouxbt.html

[B02] 多分支 else if / elif
来源：http://dali.quarkkingdee.top/Article/details/gt2ivurcgxs.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yvedp.cn/Article/details/gt2kppypytc.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.hammf.cn/Article/details/gt2cqoawdey.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.aizwys.cn/Article/details/gt2scknlqsx.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenlongwang.top/Article/details/gt2ksetmmuz.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fzhhl.top/Article/details/gt2khfjyeri.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.hammf.cn/Article/details/gt2uarbxess.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.xinyue.icu/Article/details/gt2wklyuaeo.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gzhubu.top/Article/details/gt2usekvzfw.html

[B03] switch / match / case
来源：http://dali.yueranfly.top/Article/details/gt2hncmkgez.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.hysaishi.cn/Article/details/gt2dgjnxcgx.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zdqjudy.top/Article/details/gt2bloctrev.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.fengsongda.top/Article/details/gt2vuqighhv.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2whazmkzu.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.tian-w.cn/Article/details/gt2glznkttd.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.daria6918.cn/Article/details/gt2mwjgjjhm.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.andypj.xyz/Article/details/gt2dhwjfxfy.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.haohaochexian.top/Article/details/gt2jatttccl.html

[B04] for 计数循环
来源：http://dali.zdqjudy.top/Article/details/gt2hydkyrhf.html

Py:   for i in range(10): print(i)
来源：http://dali.gaohongyu789.top/Article/details/gt2ayhscwmj.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.gzhubu.top/Article/details/gt2iilhhmsb.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zdqjudy.top/Article/details/gt2hwqznqbb.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.sufxvd.cn/Article/details/gt2dulzsyuu.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ekgwgnfr.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.guannengcc.top/Article/details/gt2yafsovgy.html

Ruby: 10.times { |i| puts i }
来源：http://dali.tanke756.top/Article/details/gt2hiefmdgd.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.xinyue.icu/Article/details/gt2tawbczst.html

[B05] 遍历数组 / 列表
来源：http://dali.jyoumei.cn/Article/details/gt2giccdcub.html

Py:   for item in arr: print(item)
来源：http://dali.jinqigufen.top/Article/details/gt2vyqdqwgx.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.andypj.xyz/Article/details/gt2oubngzzk.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.havefunace.top/Article/details/gt2jmvaucwi.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.9152youxi.cn/Article/details/gt2stibcmvj.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.daria6918.cn/Article/details/gt2jkgrlvcv.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.vqdsnc.cn/Article/details/gt2gdhfudjv.html

Ruby: arr.each { |item| puts item }
来源：http://dali.xziqi.cn/Article/details/gt2zwdudqxh.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.hywenlv.cn/Article/details/gt2rgzfcnwr.html

[B06] 遍历字典 / 对象
来源：http://dali.cashguo.top/Article/details/gt2xnzxovea.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jiagoushi.top/Article/details/gt2kpmlaqdj.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2qixgsecj.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.mhx1999.top/Article/details/gt2pmmpyzsu.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yuanzhike.top/Article/details/gt2lbtfkurm.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.daxiang520.top/Article/details/gt2gucrczmq.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.andypj.xyz/Article/details/gt2fynkbxvf.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.guowangkeji.top/Article/details/gt2grgjdgix.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yj20258.top/Article/details/gt2aihwclvf.html

[B07] while 循环
来源：http://dali.hongshengwenyu.top/Article/details/gt2bdetedok.html

Py:   while i < 10: i += 1
来源：http://dali.nwbrower.top/Article/details/gt2ihmomlub.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.tanke756.top/Article/details/gt2slrxhrfz.html

JS:   while (i < 10) { i++; }
来源：http://dali.tanke756.top/Article/details/gt2fuuoczei.html

TS:   while (i < 10) { i++; }
来源：http://dali.xinyue.icu/Article/details/gt2ombflswu.html

Java: while (i < 10) { i++; }
来源：http://dali.svipenyu.cn/Article/details/gt2qytfnise.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.cheryme.top/Article/details/gt2gognteoi.html

Ruby: while i < 10; i += 1; end
来源：http://dali.hfpthk.cn/Article/details/gt2thavikiv.html

C#:   while (i < 10) { i++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sdrxxczt.html

[B08] do-while（至少执行一次）
来源：http://dali.sweek.top/Article/details/gt2wtvdpjvt.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.nanxuanxn.top/Article/details/gt2wicsakhe.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yuxming.cn/Article/details/gt2plhgurzp.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sljigbou.html

TS:   do { i++; } while (i < 10);
来源：http://dali.shangyingyoupin.top/Article/details/gt2gyrosmjk.html

Java: do { i++; } while (i < 10);
来源：http://dali.feifeiyinyue.top/Article/details/gt2upmuzizx.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yonumen.top/Article/details/gt2hiadtgpu.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yuanzhike.top/Article/details/gt2oufazrva.html

C#:   do { i++; } while (i < 10);
来源：http://dali.guowangkeji.top/Article/details/gt2sgxqbgpe.html

[B09] break 与 continue
来源：http://dali.zdqjudy.top/Article/details/gt2nuczofvp.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nqpchxso.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jinqigfzy.top/Article/details/gt2luhzarsi.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yonumen.top/Article/details/gt2ercekgap.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cucudq.cn/Article/details/gt2oxvdrmym.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xkosrdoo.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ehwqpu.com/Article/details/gt2rvxpdcag.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.bjfxy.top/Article/details/gt2vffklvtf.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2yobcfhyh.html

[B10] 遍历同时拿索引
来源：http://dali.yongpay.top/Article/details/gt2kcqwqakp.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.guannengcc.top/Article/details/gt2exslhszq.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.gzhubu.top/Article/details/gt2wtbusnhf.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.wangdashe.top/Article/details/gt2pkqylwds.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.sxryk.cn/Article/details/gt2gbazhhjl.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.0kj1m.cn/Article/details/gt2pgedmohy.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.fzhhl.top/Article/details/gt2lxniersk.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yuxming.cn/Article/details/gt2yghquwjs.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2txsdfeqg.html

[B11] 生成数字序列 / 区间
来源：http://dali.jinqigufen.top/Article/details/gt2hiqgaxir.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhijiandao.cn/Article/details/gt2taouxtua.html

PHP:  range(0, 10, 2);
来源：http://dali.andypj.xyz/Article/details/gt2boeqpmst.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.mhx1999.top/Article/details/gt2pvgapryf.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gotoacloud.top/Article/details/gt2fdkexasx.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.mhx1999.top/Article/details/gt2qhwzgtpm.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.daxiang520.top/Article/details/gt2gegpbnmz.html

Ruby: (0...10).step(2).to_a
来源：http://dali.sufxvd.cn/Article/details/gt2vuhymqka.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.chenlongwang.top/Article/details/gt2iclvjrmp.html

[B12] 跳出多层循环
来源：http://dali.xziqi.cn/Article/details/gt2sqjvdagb.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.fengsongda.top/Article/details/gt2ehitxhsi.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.9152youxi.cn/Article/details/gt2hqgnutpx.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.snrcjt.cn/Article/details/gt2xtozliqt.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.tanke756.top/Article/details/gt2qlzfxcxn.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhixingplan.top/Article/details/gt2myfalmsm.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qjbnihpn.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.ybcxt.top/Article/details/gt2nglufbui.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.pengpengdd.cyou/Article/details/gt2zgljlvle.html

[B13] 判断是否为数字
来源：http://dali.yj20258888.top/Article/details/gt2dwuyeevn.html

Py:   isinstance(x, (int, float))
来源：http://dali.jinqigfzy.top/Article/details/gt2toyoqvgl.html

PHP:  is_numeric($x)
来源：http://dali.jyoumei.cn/Article/details/gt2gpqfrmrv.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cheryme.top/Article/details/gt2ugykrhdt.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.fzhhl.top/Article/details/gt2ablnvldj.html

Java: x instanceof Number
来源：http://dali.tian-w.cn/Article/details/gt2zszmiunb.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.havefunace.top/Article/details/gt2zvagotkp.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yanxiufei.cn/Article/details/gt2omxtowxa.html

C#:   x is int or double or decimal
来源：http://dali.jyoumei.cn/Article/details/gt2gnxfyvjb.html

[B14] 判断值是否在集合内
来源：http://dali.jlsjyb.cn/Article/details/gt2qpbeeijs.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hywenlv.cn/Article/details/gt2tpkvyarz.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jdtwagjr.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.havefunace.top/Article/details/gt2xzohiwnu.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hfpthk.cn/Article/details/gt2uhonukin.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yangfankeji.com/Article/details/gt2lkznejuv.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.dianchejie.cn/Article/details/gt2nillqgva.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yueranfly.top/Article/details/gt2bhskqxhs.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2jdattwah.html

[B15] 布尔运算与取反
来源：http://dali.ppjwa.cn/Article/details/gt2urukwrhy.html

Py:   a and b or not c
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bnocljtg.html

PHP:  $a && $b || !$c
来源：http://dali.sweek.top/Article/details/gt2idrqwtoj.html

JS:   a && b || !c
来源：http://dali.zdqjudy.top/Article/details/gt2twgzwqzl.html

TS:   a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gt2bvpmegrx.html

Java: a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2glglqtyz.html

Go:   a && b || !c
来源：http://dali.jianghu66.top/Article/details/gt2rupmmoko.html

Ruby: a && b || !c
来源：http://dali.pycfn.com/Article/details/gt2fyivjxma.html

C#:   a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jmbnhpcj.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.chenjidiqi.icu/Article/details/gt2mpxamgzl.html

Py:   if not data: return
来源：http://dali.vqdsnc.cn/Article/details/gt2amfbrzzn.html

PHP:  if (!$data) { return; }
来源：http://dali.ydzc1.top/Article/details/gt2pgsalmde.html

JS:   if (!data) return;
来源：http://dali.gaohongyu789.top/Article/details/gt2lrhqmdby.html

TS:   if (!data) return;
来源：http://dali.redwolf501.top/Article/details/gt2nlbfcrke.html

Java: if (data == null) return;
来源：http://dali.yongpay.top/Article/details/gt2zisesbgv.html

Go:   if data == nil { return }
来源：http://dali.cucudq.cn/Article/details/gt2whrqvkqs.html

Ruby: return if data.nil?
来源：http://dali.snrcjt.cn/Article/details/gt2ovjbotmq.html

C#:   if (data == null) return;
来源：http://dali.vqdsnc.cn/Article/details/gt2odcdmowh.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2ddvtvjpo.html

C. 函数与作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ktwwipaw.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2otqcpmeo.html

[C01] 定义函数
来源：http://dali.yuanzhike.top/Article/details/gt2xqrvwaxn.html

Py:   def add(a, b): return a + b
来源：http://dali.pycfn.com/Article/details/gt2pfeagfkj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gaohongyu789.top/Article/details/gt2eqeefwmv.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gt2rkeniuff.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gt2hxebqrtg.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gt2kygjrguh.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhiwuduotai.top/Article/details/gt2qbrzjntq.html

Ruby: def add(a, b); a + b; end
来源：http://dali.aizwys.cn/Article/details/gt2nkrlctsd.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wnfuyvnl.html

[C02] 默认参数
来源：http://dali.sysykeji.top/Article/details/gt2pnrgrwvl.html

Py:   def greet(name="World"): return name
来源：http://dali.hywenlv.cn/Article/details/gt2snwwggoq.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2gnsfeynv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cashguo.top/Article/details/gt2nxzrtwfn.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.smart0.xyz/Article/details/gt2lsajapib.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yongpay.top/Article/details/gt2jijwrews.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.chenlongwang.top/Article/details/gt2vpansydo.html

Ruby: def greet(name = "World") = name
来源：http://dali.chenlongwang.top/Article/details/gt2wcjupvgt.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.shuidangran.top/Article/details/gt2fnrqabpi.html

[C03] 可变参数
来源：http://dali.fzhhl.top/Article/details/gt2ginsubxl.html

Py:   def total(*args): return sum(args)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jycftcil.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yj202588.top/Article/details/gt2hswdpjeq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj20258888.top/Article/details/gt2bicvkhkb.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.wangdashe.top/Article/details/gt2vavcgvql.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jlsjyb.cn/Article/details/gt2lsarmlih.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yj202588.top/Article/details/gt2qswmuqsc.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yonumen.top/Article/details/gt2csnowhqw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.wangshuangyany.cn/Article/details/gt2oyhilfvc.html

[C04] 命名参数 / 关键字参数
来源：http://dali.gogol.net.cn/Article/details/gt2elffjfaq.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ewuygduk.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yuanzhike.top/Article/details/gt2updqanbd.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hammf.cn/Article/details/gt2szrovzcb.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.birdmap.top/Article/details/gt2xmppnxqv.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xziqi.cn/Article/details/gt2dgixdzih.html

Go:   // 无：用配置结构体参数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2glggfpzo.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yueranfly.top/Article/details/gt2jstjptdj.html

C#:   f(a: 1, b: 2)
来源：http://dali.hysaishi.cn/Article/details/gt2slvqvbgx.html

[C05] 返回多个值
来源：http://dali.zhoulong.xyz/Article/details/gt2ynfpyefy.html

Py:   return a, b
来源：http://dali.zhoulong.xyz/Article/details/gt2fxyqudap.html

PHP:  return [$a, $b];
来源：http://dali.quarkkingdee.top/Article/details/gt2rebndbil.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.guowangkeji.top/Article/details/gt2yxqcqklr.html

TS:   return { a, b };
来源：http://dali.feifeiyinyue.top/Article/details/gt2gqxynwul.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shuidangran.top/Article/details/gt2ckpdefwz.html

Go:   return a, b
来源：http://dali.smart0.xyz/Article/details/gt2vrgbckcv.html

Ruby: return a, b
来源：http://dali.yuxming.cn/Article/details/gt2fkcvxpyk.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.sweek.top/Article/details/gt2copcglgq.html

[C06] 匿名函数 / lambda
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qwameahj.html

Py:   square = lambda x: x * x
来源：http://dali.haohaochexian.top/Article/details/gt2yhgzmqxz.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yongpay.top/Article/details/gt2oguxtlyy.html

JS:   const square = x => x * x;
来源：http://dali.shangyingyoupin.top/Article/details/gt2khxtmziw.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpblmifi.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.nanxuanxn.top/Article/details/gt2slqfabrb.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uxxrmeyi.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jyoumei.cn/Article/details/gt2dekusgbr.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.gotoacloud.top/Article/details/gt2pvpsrthy.html

[C07] 把函数作为参数传入
来源：http://dali.tianlin.xyz/Article/details/gt2mkaluqgi.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2umyiglkm.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2tsihmyqz.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.wangdashe.top/Article/details/gt2opgagrge.html

TS:   arr.map(String)
来源：http://dali.meibo888.top/Article/details/gt2ucyvadot.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2xrixemeq.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.bjfxy.top/Article/details/gt2bbpvqiag.html

Ruby: arr.map(&:upcase)
来源：http://dali.daxiang520.top/Article/details/gt2pzqdeprb.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.fzhhl.top/Article/details/gt2ozgxpoku.html

[C08] 闭包
来源：http://dali.redwolf501.top/Article/details/gt2pguukkih.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.smart0.xyz/Article/details/gt2ukmeupdo.html


<!-- 参考信息 -->