代发 wailian999

[A22] 获取字符串长度
来源：http://dali.yonumen.top/Article/details/gt2xwbsmutl.html

Py:   len(s)
来源：http://dali.aibaodan.cn/Article/details/gt2njozzvma.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.feifeiyinyue.top/Article/details/gt2plxfumoj.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.shuidangran.top/Article/details/gt2yvhyzffw.html

TS:   s.length
来源：http://dali.snrcjt.cn/Article/details/gt2vedmxyek.html

Java: s.length()
来源：http://dali.jinqigufen.top/Article/details/gt2zqkvpsjd.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2gtsgahbx.html

Ruby: s.length
来源：http://dali.gzhubu.top/Article/details/gt2exlxxoyc.html

C#:   s.Length
来源：http://dali.dianchejie.cn/Article/details/gt2ovirjkoy.html

[A23] 大小写转换
来源：http://dali.cdnleiting.top/Article/details/gt2vboatsoa.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.cucudq.cn/Article/details/gt2apfmgeph.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.nanxuanxn.top/Article/details/gt2fpaejubb.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yj20258.top/Article/details/gt2odsxeuim.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.dashuyun.cn/Article/details/gt2hxjnjjwo.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xrziotky.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.cashguo.top/Article/details/gt2ymomffog.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.ppjwa.cn/Article/details/gt2ysayacjf.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.zhoulong.xyz/Article/details/gt2hfsavmot.html

[A24] 去除首尾空白
来源：http://dali.meibo888.top/Article/details/gt2lajmxacy.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.316326.xyz/Article/details/gt2wihvhugz.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.aizwys.cn/Article/details/gt2hsvigson.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.sxryk.cn/Article/details/gt2hdrpbhks.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.nanxuanxn.top/Article/details/gt2dsssepmm.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.wangshuangyany.cn/Article/details/gt2mhmcjmpu.html

Go:   strings.TrimSpace(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jrysofvp.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yanxiufei.cn/Article/details/gt2wcoprpyc.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jqgfzy.top/Article/details/gt2jkwfcitc.html

[A25] 字符串比较
来源：http://dali.nwbrower.top/Article/details/gt2fatyrbtr.html

Py:   s1 == s2; s1 != s2
来源：http://dali.vqdsnc.cn/Article/details/gt2pnnrgunx.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ubvtkaas.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhijiandao.cn/Article/details/gt2panpnwwq.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2nnkxdjpr.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.sxryk.cn/Article/details/gt2kuqvzlym.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.hnxiangtu.top/Article/details/gt2btlxvatc.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.hnxiangtu.top/Article/details/gt2ntxjtqwq.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.tanke756.top/Article/details/gt2ogeffqgj.html

[A26] 类型转换总览
来源：http://dali.zycfv.cn/Article/details/gt2tedyqdwh.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jksfyywu.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.svipenyu.cn/Article/details/gt2xezrqnfu.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.aibaodan.cn/Article/details/gt2ezxsmtvt.html

TS:   Number() String() Boolean() x as number
来源：http://dali.sweek.top/Article/details/gt2balorzfd.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2drvjynqw.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.fengsongda.top/Article/details/gt2wnwepojs.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.shuidangran.top/Article/details/gt2ixuuiynb.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.xuanzx.com/Article/details/gt2llnaylej.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2fpblaizm.html

B. 流程控制
来源：http://dali.tanke756.top/Article/details/gt2jafperlc.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2guyhecpf.html

[B01] 条件判断 if / else
来源：http://dali.gotoacloud.top/Article/details/gt2vgizaisb.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.guowangkeji.top/Article/details/gt2ldifgcpp.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yj20258888.top/Article/details/gt2mizhieab.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hnxiangtu.top/Article/details/gt2ckmpcmct.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xylfe.cn/Article/details/gt2lggjfcpf.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.zhengqikj.top/Article/details/gt2vmddpylk.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.dashuyun.cn/Article/details/gt2bholioco.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.pycfn.com/Article/details/gt2otwquyvo.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.snrcjt.cn/Article/details/gt2cmccptdt.html

[B02] 多分支 else if / elif
来源：http://dali.c1oappe.top/Article/details/gt2btnqeyrm.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.pycfn.com/Article/details/gt2kenevtgl.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zhengqikj.top/Article/details/gt2drsmwtcb.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.meibo888.top/Article/details/gt2dyoxyzhn.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigfzy.top/Article/details/gt2kklihgfj.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.havefunace.top/Article/details/gt2nfjcmsrx.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.shzxlz.cn/Article/details/gt2zpksjlmk.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.ppjwa.cn/Article/details/gt2sdqrpmro.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pivhchwz.html

[B03] switch / match / case
来源：http://dali.fzhhl.top/Article/details/gt2yzgucong.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.gzhubu.top/Article/details/gt2aponcsbd.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.hammf.cn/Article/details/gt2tijzywpz.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yuanzhike.top/Article/details/gt2lkcrpsyf.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ydzc1.top/Article/details/gt2iondgypw.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.nanxuanxn.top/Article/details/gt2gzfwvwfo.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yvedp.cn/Article/details/gt2ieppbmxw.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.haohaochexian.top/Article/details/gt2nxmelxyz.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.wangdashe.top/Article/details/gt2qhcygtzh.html

[B04] for 计数循环
来源：http://dali.dashuyun.cn/Article/details/gt2xxmowjuw.html

Py:   for i in range(10): print(i)
来源：http://dali.sweek.top/Article/details/gt2ijxgtixy.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.hfpthk.cn/Article/details/gt2hcpifqhk.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ivvv.top/Article/details/gt2keqflvam.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhengqikj.top/Article/details/gt2rylxqsdd.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yonumen.top/Article/details/gt2gccrdeqk.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.dianchejie.cn/Article/details/gt2lnaconut.html

Ruby: 10.times { |i| puts i }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pftgxdom.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.nanxinkj.top/Article/details/gt2vcnmlcxl.html

[B05] 遍历数组 / 列表
来源：http://dali.cqqwz.cn/Article/details/gt2dlwxmkpq.html

Py:   for item in arr: print(item)
来源：http://dali.xylfe.cn/Article/details/gt2bbeslqui.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hjdvipir.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.0kj1m.cn/Article/details/gt2gqjglfmp.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yongpay.top/Article/details/gt2errpezcc.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.quarkkingdee.top/Article/details/gt2gnyfwzfc.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yuxming.cn/Article/details/gt2ijhdrmoc.html

Ruby: arr.each { |item| puts item }
来源：http://dali.aibaodan.cn/Article/details/gt2uijqbihg.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.ydzc1.top/Article/details/gt2huaeniqz.html

[B06] 遍历字典 / 对象
来源：http://dali.pycfn.com/Article/details/gt2djcequxa.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2znkvpmjp.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.c1oappe.top/Article/details/gt2nuvvzfnf.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hnxiangtu.top/Article/details/gt2kicxkors.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xinyue.icu/Article/details/gt2yosciods.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.hywenlv.cn/Article/details/gt2yulxuwrx.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.ybcxt.top/Article/details/gt2ejsewfan.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.meibo888.top/Article/details/gt2dtzlamnt.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.mhx1999.top/Article/details/gt2mnysmtkw.html

[B07] while 循环
来源：http://dali.guowangkeji.top/Article/details/gt2ziuwzoxh.html

Py:   while i < 10: i += 1
来源：http://dali.gzhubu.top/Article/details/gt2urgzfqft.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.iojbl.cn/Article/details/gt2ftyslyvc.html

JS:   while (i < 10) { i++; }
来源：http://dali.nanxuanxn.top/Article/details/gt2ksryaqem.html

TS:   while (i < 10) { i++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uaekkbom.html

Java: while (i < 10) { i++; }
来源：http://dali.yueranfly.top/Article/details/gt2takzzoxn.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jianghu66.top/Article/details/gt2sjqhdcxu.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yangfankeji.com/Article/details/gt2lsskczkz.html

C#:   while (i < 10) { i++; }
来源：http://dali.hysaishi.cn/Article/details/gt2lvuibgff.html

[B08] do-while（至少执行一次）
来源：http://dali.gotoacloud.top/Article/details/gt2fuyucepc.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.xuanzx.com/Article/details/gt2lxgbzqvl.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.cashguo.top/Article/details/gt2gyvtxpgn.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yj202588.top/Article/details/gt2liiyvejm.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ysxwimbn.html

Java: do { i++; } while (i < 10);
来源：http://dali.wangshuangyany.cn/Article/details/gt2pidgouwc.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.ybcxt.top/Article/details/gt2lvgqcojp.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uqdgunid.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhiwuduotai.top/Article/details/gt2oylasvlz.html

[B09] break 与 continue
来源：http://dali.hnqzz.top/Article/details/gt2wfhcnyeq.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yueranfly.top/Article/details/gt2hdvbeidx.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.mhx1999.top/Article/details/gt2txdkoxop.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.kuanghao11.cn/Article/details/gt2ybpvipzm.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhengqikj.top/Article/details/gt2dixdinel.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hdwvifjw.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.xuanzx.com/Article/details/gt2tynrpklu.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jiagoushi.top/Article/details/gt2xruivzwl.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aizwys.cn/Article/details/gt2vbmuxozd.html

[B10] 遍历同时拿索引
来源：http://dali.xinyue.icu/Article/details/gt2vkexgqom.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.meibo888.top/Article/details/gt2quuikqav.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.tianlin.xyz/Article/details/gt2waothqxs.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.gogol.net.cn/Article/details/gt2hajnmvck.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2mgstiyiw.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.meibo888.top/Article/details/gt2fmzzjxrc.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.chenjidiqi.icu/Article/details/gt2yyejwurs.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.andypj.xyz/Article/details/gt2nkzkdbbc.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hammf.cn/Article/details/gt2edfjjdhp.html

[B11] 生成数字序列 / 区间
来源：http://dali.tianlin.xyz/Article/details/gt2fwlmjdey.html

Py:   list(range(0, 10, 2))
来源：http://dali.haohaochexian.top/Article/details/gt2aobrlhrp.html

PHP:  range(0, 10, 2);
来源：http://dali.hammf.cn/Article/details/gt2reznfsyf.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yuanzhike.top/Article/details/gt2jzxsntsm.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sweek.top/Article/details/gt2nyyxguwo.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.shuidangran.top/Article/details/gt2ncurwlrk.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.tian-w.cn/Article/details/gt2ropicqtt.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2srzhycdh.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zycfv.cn/Article/details/gt2yvobgbhr.html

[B12] 跳出多层循环
来源：http://dali.xuanzx.com/Article/details/gt2reslvdfb.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.pycfn.com/Article/details/gt2ytzmkypy.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.smart0.xyz/Article/details/gt2jihfmxnh.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnxiangtu.top/Article/details/gt2ciodxoko.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xuanzx.com/Article/details/gt2tyapqnym.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj20258888.top/Article/details/gt2tuezlhaz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.guowangkeji.top/Article/details/gt2cqvpkftx.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.ivvv.top/Article/details/gt2kbfjarbn.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jiagoushi.top/Article/details/gt2byvxdyge.html

[B13] 判断是否为数字
来源：http://dali.hfpthk.cn/Article/details/gt2gbnwmrby.html

Py:   isinstance(x, (int, float))
来源：http://dali.sysykeji.top/Article/details/gt2ufwwkjic.html

PHP:  is_numeric($x)
来源：http://dali.dashuyun.cn/Article/details/gt2wrddvwbb.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.snrcjt.cn/Article/details/gt2johrzxny.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zdqjudy.top/Article/details/gt2ymacpwus.html

Java: x instanceof Number
来源：http://dali.hnxiangtu.top/Article/details/gt2ygqjnwvr.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.daxiang520.top/Article/details/gt2dnismluf.html

Ruby: x.is_a?(Numeric)
来源：http://dali.shuidangran.top/Article/details/gt2rvhofrrw.html

C#:   x is int or double or decimal
来源：http://dali.jinqigfzy.top/Article/details/gt2tordeabb.html

[B14] 判断值是否在集合内
来源：http://dali.yuxming.cn/Article/details/gt2nkeaxiwd.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.vqdsnc.cn/Article/details/gt2suwawsif.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.wangdashe.top/Article/details/gt2ghzlalqh.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.gogol.net.cn/Article/details/gt2cgdgdddr.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2zwzaknfd.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2gisgqdls.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.cheryme.top/Article/details/gt2vprsiswr.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hfpthk.cn/Article/details/gt2ithlekgz.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xziqi.cn/Article/details/gt2bboucumr.html

[B15] 布尔运算与取反
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ivaerrmv.html

Py:   a and b or not c
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2voqvxnew.html

PHP:  $a && $b || !$c
来源：http://dali.yonumen.top/Article/details/gt2djygnznq.html

JS:   a && b || !c
来源：http://dali.aizwys.cn/Article/details/gt2whwxerek.html

TS:   a && b || !c
来源：http://dali.tian-w.cn/Article/details/gt2zyajouft.html

Java: a && b || !c
来源：http://dali.c1oappe.top/Article/details/gt2bfuzwfua.html

Go:   a && b || !c
来源：http://dali.zdqjudy.top/Article/details/gt2iprgqfjd.html

Ruby: a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xxqfpybl.html

C#:   a && b || !c
来源：http://dali.aizwys.cn/Article/details/gt2aashvtvz.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ydzc1.top/Article/details/gt2ujsxbmkp.html

Py:   if not data: return
来源：http://dali.kuanghao11.cn/Article/details/gt2ixaewkzr.html

PHP:  if (!$data) { return; }
来源：http://dali.jiagoushi.top/Article/details/gt2bkvwxdvs.html

JS:   if (!data) return;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cdexncte.html

TS:   if (!data) return;
来源：http://dali.yj20258.top/Article/details/gt2temjxhhu.html

Java: if (data == null) return;
来源：http://dali.cashguo.top/Article/details/gt2xhvbbeqe.html

Go:   if data == nil { return }
来源：http://dali.zdqjudy.top/Article/details/gt2kcydpzsn.html

Ruby: return if data.nil?
来源：http://dali.nanxuanxn.top/Article/details/gt2gdtdwqby.html

C#:   if (data == null) return;
来源：http://dali.hfpthk.cn/Article/details/gt2fhharimk.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2eswyrsni.html

C. 函数与作用域
来源：http://dali.yonumen.top/Article/details/gt2zvvaupzo.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2gavnltgo.html

[C01] 定义函数
来源：http://dali.tianlin.xyz/Article/details/gt2plxsrslw.html

Py:   def add(a, b): return a + b
来源：http://dali.yangfankeji.com/Article/details/gt2lqiijgso.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yongpay.top/Article/details/gt2ylmxvdiw.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2xtjnzvgq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gt2eohuupix.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gt2sijzkzmp.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.andypj.xyz/Article/details/gt2rvsdubbe.html

Ruby: def add(a, b); a + b; end
来源：http://dali.iojbl.cn/Article/details/gt2wafddrfv.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2lpftuiom.html

[C02] 默认参数
来源：http://dali.svipenyu.cn/Article/details/gt2tolcbvto.html

Py:   def greet(name="World"): return name
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ykypenug.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.c1oappe.top/Article/details/gt2tgqtlztw.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yueranfly.top/Article/details/gt2opoufdqd.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.shzxlz.cn/Article/details/gt2ettkfpwu.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.sufxvd.cn/Article/details/gt2jrnglfap.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zycfv.cn/Article/details/gt2ypagtyal.html

Ruby: def greet(name = "World") = name
来源：http://dali.sufxvd.cn/Article/details/gt2jemxuarg.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.dianchejie.cn/Article/details/gt2wppbsazx.html

[C03] 可变参数
来源：http://dali.zhoulong.xyz/Article/details/gt2arbagmuq.html

Py:   def total(*args): return sum(args)
来源：http://dali.jiagoushi.top/Article/details/gt2mwreivia.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.daria6918.cn/Article/details/gt2exoddpyh.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hywenlv.cn/Article/details/gt2getrtpge.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zdqjudy.top/Article/details/gt2irqzshah.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.sweek.top/Article/details/gt2kllyvppq.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jinqigfzy.top/Article/details/gt2birpqbsp.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jianghu66.top/Article/details/gt2ffvvhsgk.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jqgufenzy.top/Article/details/gt2fdutiulk.html

[C04] 命名参数 / 关键字参数
来源：http://dali.birdmap.top/Article/details/gt2iqwhxemp.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hysaishi.cn/Article/details/gt2qagbezrs.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yuxming.cn/Article/details/gt2qsmvgcgs.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ybcxt.top/Article/details/gt2esatgfjs.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ppjwa.cn/Article/details/gt2gdyvaexd.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.dianchejie.cn/Article/details/gt2lphhsvcg.html

Go:   // 无：用配置结构体参数
来源：http://dali.nanxuanxn.top/Article/details/gt2buenutxk.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xinyue.icu/Article/details/gt2hsubakam.html

C#:   f(a: 1, b: 2)
来源：http://dali.ppjwa.cn/Article/details/gt2subdtzgt.html

[C05] 返回多个值
来源：http://dali.cheryme.top/Article/details/gt2yqtjbkhd.html

Py:   return a, b
来源：http://dali.shuidangran.top/Article/details/gt2waiqxijw.html

PHP:  return [$a, $b];
来源：http://dali.iojbl.cn/Article/details/gt2ohixnnwl.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ehwqpu.com/Article/details/gt2vcnjfssc.html

TS:   return { a, b };
来源：http://dali.xuetiantiany.cn/Article/details/gt2qzmgeshr.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yangfankeji.com/Article/details/gt2dljrrfdh.html

Go:   return a, b
来源：http://dali.ppjwa.cn/Article/details/gt2eplnvidr.html

Ruby: return a, b
来源：http://dali.haohaochexian.top/Article/details/gt2lrxtbplb.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinqigufen.top/Article/details/gt2nuyfpbfq.html

[C06] 匿名函数 / lambda
来源：http://dali.316326.xyz/Article/details/gt2mvrutdqv.html

Py:   square = lambda x: x * x
来源：http://dali.shuidangran.top/Article/details/gt2uuemkdwh.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.tianlin.xyz/Article/details/gt2iftoppco.html

JS:   const square = x => x * x;
来源：http://dali.shuidangran.top/Article/details/gt2symfpzhb.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhiwuduotai.top/Article/details/gt2etrhqrzv.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yuxming.cn/Article/details/gt2lzolmrua.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhengqikj.top/Article/details/gt2huvfkcox.html

Ruby: square = ->(x) { x * x }
来源：http://dali.guannengcc.top/Article/details/gt2vbzzcmds.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.vqdsnc.cn/Article/details/gt2fqylbguf.html

[C07] 把函数作为参数传入
来源：http://dali.chenzaomai.com/Article/details/gt2uieqjhwu.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.quarkkingdee.top/Article/details/gt2nqrqkvxm.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cucudq.cn/Article/details/gt2uozrjokz.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cezavjwr.html

TS:   arr.map(String)
来源：http://dali.jinqigfzy.top/Article/details/gt2azonenuq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hnqzz.top/Article/details/gt2ldkxhghs.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yj20258888.top/Article/details/gt2lijgexyz.html

Ruby: arr.map(&:upcase)
来源：http://dali.meibo888.top/Article/details/gt2usxczotq.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.daria6918.cn/Article/details/gt2nffkfdfn.html

[C08] 闭包
来源：http://dali.zhixingplan.top/Article/details/gt2rdguphim.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.0kj1m.cn/Article/details/gt2poztvsgn.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.kuanghao11.cn/Article/details/gt2anjoooix.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.0kj1m.cn/Article/details/gt2oqzpcblm.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.snrcjt.cn/Article/details/gt2edlofwfd.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.haohaochexian.top/Article/details/gt2myjxgccs.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.316326.xyz/Article/details/gt2uaunjngf.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.bjfxy.top/Article/details/gt2pokyorsp.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.gogol.net.cn/Article/details/gt2uipakymj.html

[C09] 递归
来源：http://dali.yuanzhike.top/Article/details/gt2ktkiznkp.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.cqqwz.cn/Article/details/gt2dpbkztjc.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.nanxinkj.top/Article/details/gt2borixjqa.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hfpthk.cn/Article/details/gt2oufgzodz.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yjtiqnbd.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ybcxt.top/Article/details/gt2rugzfmrc.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hskuehai.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.nanxuanxn.top/Article/details/gt2lbrsxwcr.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhoulong.xyz/Article/details/gt2rbrhcbob.html

[C10] 变量作用域
来源：http://dali.hnqzz.top/Article/details/gt2tlhvlxpw.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.shuidangran.top/Article/details/gt2uqgeware.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.fengsongda.top/Article/details/gt2tefvdvjg.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yj20258.top/Article/details/gt2wfctoipu.html

TS:   同 JS
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hmiwoudf.html

Java: 方法内为块级作用域
来源：http://dali.hammf.cn/Article/details/gt2azqdgvio.html

Go:   花括号块级作用域
来源：http://dali.redwolf501.top/Article/details/gt2pozoyzot.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hfpthk.cn/Article/details/gt2vdotdqtm.html

C#:   块级作用域
来源：http://dali.gotoacloud.top/Article/details/gt2tzqaplrt.html

[C11] 模块导入与导出
来源：http://dali.tanke756.top/Article/details/gt2cqbreuyr.html

Py:   from module import func
来源：http://dali.snrcjt.cn/Article/details/gt2thaqqlgu.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yj202588.top/Article/details/gt2xaqguqmm.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cdnleiting.top/Article/details/gt2thtytdku.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.0kj1m.cn/Article/details/gt2mnkkknvv.html

Java: import java.util.List;
来源：http://dali.bjfxy.top/Article/details/gt2qqmgigpg.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zycfv.cn/Article/details/gt2zxfqhpdi.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shuidangran.top/Article/details/gt2ivsxnjyd.html

C#:   using System.Text;
来源：http://dali.guowangkeji.top/Article/details/gt2sxxckbad.html

[C12] 立即执行函数 IIFE
来源：http://dali.sysykeji.top/Article/details/gt2dgfbzyxx.html

Py:   (lambda: print("run"))()
来源：http://dali.hfpthk.cn/Article/details/gt2xrkbmeyd.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zycfv.cn/Article/details/gt2fxqveuyw.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shzxlz.cn/Article/details/gt2tuxnyblc.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kxowqfmk.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yonumen.top/Article/details/gt2hasamkjz.html


<!-- 参考信息 -->