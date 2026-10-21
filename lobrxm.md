代发 wailian999

Go:   strings.TrimSpace(s)
来源：http://dali.yanxiufei.cn/Article/details/gtvthzqgyx.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.zdqjudy.top/Article/details/gtipufsyoz.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.havefunace.top/Article/details/gtvkoixvvs.html

[A25] 字符串比较
来源：http://dali.snrcjt.cn/Article/details/gtzkotejfg.html

Py:   s1 == s2; s1 != s2
来源：http://dali.hnqzz.top/Article/details/gtqfmkxwzd.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.xylfe.cn/Article/details/gtfyscpmlp.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.havefunace.top/Article/details/gtgiwrkiho.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yuxming.cn/Article/details/gtmveqvkkh.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqnwslika.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.c1oappe.top/Article/details/gtmbubxgdq.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.mhx1999.top/Article/details/gtxyopttpy.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.ehwqpu.com/Article/details/gtlnljixtn.html

[A26] 类型转换总览
来源：http://dali.hnqzz.top/Article/details/gtrezbypyp.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.tianlin.xyz/Article/details/gtcvozguuf.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.chenjidiqi.icu/Article/details/gteixbrcnr.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.hongshengwenyu.top/Article/details/gtewtovonc.html

TS:   Number() String() Boolean() x as number
来源：http://dali.hnxiangtu.top/Article/details/gtqzoxpsyd.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.xinyue.icu/Article/details/gtjkjxrhkw.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.nanxinkj.top/Article/details/gturxqimbt.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.pengpengdd.cyou/Article/details/gtvzqylvhg.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.pengpengdd.cyou/Article/details/gtafhrpinv.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtzfjhfxxn.html

B. 流程控制
来源：http://dali.aibaodan.cn/Article/details/gtvzintwgr.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtmdshqwev.html

[B01] 条件判断 if / else
来源：http://dali.wangdashe.top/Article/details/gtlvrsueey.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.feifeiyinyue.top/Article/details/gtitlnnbfv.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yuanzhike.top/Article/details/gtjvrktvst.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jqgufenzy.top/Article/details/gtdpeemuvj.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhiwuduotai.top/Article/details/gtlshiykjt.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.sweek.top/Article/details/gtkbhijgnt.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.cucudq.cn/Article/details/gtnggdisug.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.yueranfly.top/Article/details/gtosnedyiv.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.gogol.net.cn/Article/details/gtbuybifjv.html

[B02] 多分支 else if / elif
来源：http://dali.yanxiufei.cn/Article/details/gtbmhlrwki.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yonumen.top/Article/details/gtryysqiuq.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.ybcxt.top/Article/details/gtcpgojxdz.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zdqjudy.top/Article/details/gtwevjgrqc.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.feifeiyinyue.top/Article/details/gtaxwdlfpb.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.redwolf501.top/Article/details/gtbxkihwll.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.zhongyouzk.top/Article/details/gtpuqbnijo.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.316326.xyz/Article/details/gtxoqynoit.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenzaomai.com/Article/details/gtsyeeojgt.html

[B03] switch / match / case
来源：http://dali.yj20258888.top/Article/details/gtaherxzmv.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.feifeiyinyue.top/Article/details/gtzyxgihel.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.sufxvd.cn/Article/details/gtfqhhpkob.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.fzhhl.top/Article/details/gtvcdfnqwu.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.daxiang520.top/Article/details/gtbuzirkhb.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.dashuyun.cn/Article/details/gtefcizmlk.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.nwbrower.top/Article/details/gtbvgelfzc.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.ehwqpu.com/Article/details/gtwntzhnjk.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.bjfxy.top/Article/details/gttemtrucj.html

[B04] for 计数循环
来源：http://dali.ydzc1.top/Article/details/gtvhgxuisb.html

Py:   for i in range(10): print(i)
来源：http://dali.jlsjyb.cn/Article/details/gtihuyalxg.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yanxiufei.cn/Article/details/gteuehpacl.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yj20258888.top/Article/details/gtzbjhwhwd.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.sxryk.cn/Article/details/gtkfqshgvs.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yuanzhike.top/Article/details/gtdmezkrlx.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.zycfv.cn/Article/details/gtdpvibjem.html

Ruby: 10.times { |i| puts i }
来源：http://dali.cheryme.top/Article/details/gtnaakxnif.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.mhx1999.top/Article/details/gtyviytwhp.html

[B05] 遍历数组 / 列表
来源：http://dali.ivvv.top/Article/details/gtjvmypssa.html

Py:   for item in arr: print(item)
来源：http://dali.dianchejie.cn/Article/details/gtimpbrrbk.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.gaohongyu789.top/Article/details/gtqtkonxlx.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.gotoacloud.top/Article/details/gtbwrdwcxf.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.nanxinkj.top/Article/details/gtdiijcsmk.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.haohaochexian.top/Article/details/gttytaamtu.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yueranfly.top/Article/details/gtznlkruqb.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yonumen.top/Article/details/gtphnuolgz.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.cucudq.cn/Article/details/gtrvajeqjz.html

[B06] 遍历字典 / 对象
来源：http://dali.sweek.top/Article/details/gtwlashtay.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.chenlongwang.top/Article/details/gteachnijn.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gticdkmzab.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.wangdashe.top/Article/details/gttufpqqvg.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shuidangran.top/Article/details/gtkqreddyr.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.svipenyu.cn/Article/details/gtxgdlpbvs.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jqgufenzy.top/Article/details/gtpwbudlna.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jyoumei.cn/Article/details/gtevluuivf.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yonumen.top/Article/details/gtpeykkrjn.html

[B07] while 循环
来源：http://dali.birdmap.top/Article/details/gtpcnogppt.html

Py:   while i < 10: i += 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtvntszbnc.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttudbviju.html

JS:   while (i < 10) { i++; }
来源：http://dali.jinqigufen.top/Article/details/gtknxscyun.html

TS:   while (i < 10) { i++; }
来源：http://dali.yj20258.top/Article/details/gtbrmvoobx.html

Java: while (i < 10) { i++; }
来源：http://dali.gogol.net.cn/Article/details/gtgoqdxuzz.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdbwomnsd.html

Ruby: while i < 10; i += 1; end
来源：http://dali.andypj.xyz/Article/details/gtnfcuhbrh.html

C#:   while (i < 10) { i++; }
来源：http://dali.yanxiufei.cn/Article/details/gtjngywwiq.html

[B08] do-while（至少执行一次）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtphwxoghw.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.cucudq.cn/Article/details/gtsselucdc.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.ydzc1.top/Article/details/gtgpyisqrh.html

JS:   do { i++; } while (i < 10);
来源：http://dali.shangyingyoupin.top/Article/details/gtzxzbnfed.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yueranfly.top/Article/details/gtzcnbmygm.html

Java: do { i++; } while (i < 10);
来源：http://dali.jinghuilouyu.cn/Article/details/gtbhjuemhx.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jianghu66.top/Article/details/gtesawxvky.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.gotoacloud.top/Article/details/gtsqupvqkm.html

C#:   do { i++; } while (i < 10);
来源：http://dali.xylfe.cn/Article/details/gtigobyela.html

[B09] break 与 continue
来源：http://dali.cucudq.cn/Article/details/gtnajkottw.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtubpkmfas.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.cqqwz.cn/Article/details/gtykhcjxii.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnqzz.top/Article/details/gtgnwfuuzy.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fengsongda.top/Article/details/gtukntjzmc.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.9152youxi.cn/Article/details/gtnmyxoedg.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.chenzaomai.com/Article/details/gtsgofplma.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.shuidangran.top/Article/details/gtmjuyrejz.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuxming.cn/Article/details/gtkivvvlkp.html

[B10] 遍历同时拿索引
来源：http://dali.sysykeji.top/Article/details/gtvxktphpl.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yueranfly.top/Article/details/gtvjredeke.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.tianlin.xyz/Article/details/gtilourgqb.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhongyouzk.top/Article/details/gtzuclbqxw.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.daxiang520.top/Article/details/gtsyqsects.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.ybcxt.top/Article/details/gtbxptjuxc.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.redwolf501.top/Article/details/gtqxktkacj.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhoulong.xyz/Article/details/gtscrjqbyq.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.wangdashe.top/Article/details/gtioohkpzs.html

[B11] 生成数字序列 / 区间
来源：http://dali.hnxiangtu.top/Article/details/gtuiachdsg.html

Py:   list(range(0, 10, 2))
来源：http://dali.dashuyun.cn/Article/details/gttzvyscvi.html

PHP:  range(0, 10, 2);
来源：http://dali.chenjidiqi.icu/Article/details/gtzaazcchh.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhixingplan.top/Article/details/gtxciqhort.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.andypj.xyz/Article/details/gtjgdnnoae.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zycfv.cn/Article/details/gtoxgjdfnh.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.shzxlz.cn/Article/details/gtigytrmbu.html

Ruby: (0...10).step(2).to_a
来源：http://dali.ivvv.top/Article/details/gtfmlcqjos.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jiagoushi.top/Article/details/gtplxtldjb.html

[B12] 跳出多层循环
来源：http://dali.ppjwa.cn/Article/details/gtahhyvmaj.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.birdmap.top/Article/details/gtxuyvujgx.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zycfv.cn/Article/details/gtiwfiuzoj.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sufxvd.cn/Article/details/gtyegqaqkg.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gzhubu.top/Article/details/gtmmxyzgqw.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.sweek.top/Article/details/gteygoghue.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hnqzz.top/Article/details/gtcqzrgouh.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.sweek.top/Article/details/gtlpyqjwfy.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.svipenyu.cn/Article/details/gtyhynpugl.html

[B13] 判断是否为数字
来源：http://dali.chenzaomai.com/Article/details/gthiqdwxzr.html

Py:   isinstance(x, (int, float))
来源：http://dali.nwbrower.top/Article/details/gtneisbrkp.html

PHP:  is_numeric($x)
来源：http://dali.pycfn.com/Article/details/gttijdsisj.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj202588.top/Article/details/gtmtylpuse.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shuidangran.top/Article/details/gtxmojtkzh.html

Java: x instanceof Number
来源：http://dali.jinqigufen.top/Article/details/gtjjbaamov.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.daxiang520.top/Article/details/gtljnmfssj.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrbxalxpk.html

C#:   x is int or double or decimal
来源：http://dali.cashguo.top/Article/details/gtsrxundgt.html

[B14] 判断值是否在集合内
来源：http://dali.jlsjyb.cn/Article/details/gtfntwthxf.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttyhhzhgr.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hongshengwenyu.top/Article/details/gtpcmteoyg.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtatpiofkh.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.guannengcc.top/Article/details/gtttdwzyqx.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.guannengcc.top/Article/details/gtmqaskfno.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hywenlv.cn/Article/details/gtmdxmaeos.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.gzhubu.top/Article/details/gtwmtmyevz.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuliocpjj.html

[B15] 布尔运算与取反
来源：http://dali.jqgufenzy.top/Article/details/gtimoxzxjq.html

Py:   a and b or not c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdhvaeirm.html

PHP:  $a && $b || !$c
来源：http://dali.nwbrower.top/Article/details/gtkcrmvvhx.html

JS:   a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gtoewylgxq.html

TS:   a && b || !c
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzczyfohg.html

Java: a && b || !c
来源：http://dali.zhiwuduotai.top/Article/details/gtvkwbddlz.html

Go:   a && b || !c
来源：http://dali.birdmap.top/Article/details/gtckbfbnfu.html

Ruby: a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gtvetxtmtz.html

C#:   a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gtnpxjargd.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.gaohongyu789.top/Article/details/gtepjahvcd.html

Py:   if not data: return
来源：http://dali.quarkkingdee.top/Article/details/gtdtbvvqky.html

PHP:  if (!$data) { return; }
来源：http://dali.zhixingplan.top/Article/details/gtlaqbmlek.html

JS:   if (!data) return;
来源：http://dali.jlsjyb.cn/Article/details/gtzslwtosp.html

TS:   if (!data) return;
来源：http://dali.gogol.net.cn/Article/details/gtsqooezae.html

Java: if (data == null) return;
来源：http://dali.wangdashe.top/Article/details/gthuepmjuv.html

Go:   if data == nil { return }
来源：http://dali.daria6918.cn/Article/details/gtoabveomn.html

Ruby: return if data.nil?
来源：http://dali.nwbrower.top/Article/details/gtvknokerw.html

C#:   if (data == null) return;
来源：http://dali.cheryme.top/Article/details/gtapxqlevj.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtvhmpdwxl.html

C. 函数与作用域
来源：http://dali.haohaochexian.top/Article/details/gtliwwhuon.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gttyfmrfxa.html

[C01] 定义函数
来源：http://dali.jqgufenzy.top/Article/details/gtarkfimhb.html

Py:   def add(a, b): return a + b
来源：http://dali.haohaochexian.top/Article/details/gtapquikqe.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cucudq.cn/Article/details/gtmplunynb.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gtnkagooqm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gtujxlcryo.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gtmrkokmmg.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.fzhhl.top/Article/details/gtgvtstlhq.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jyoumei.cn/Article/details/gtvhdghdfd.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gtjwlsxxqn.html

[C02] 默认参数
来源：http://dali.hysaishi.cn/Article/details/gthivoynkt.html

Py:   def greet(name="World"): return name
来源：http://dali.yongpay.top/Article/details/gtfsgynqul.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xziqi.cn/Article/details/gttwbepziv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtivdndmas.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.dianchejie.cn/Article/details/gtlbojihgb.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cdnleiting.top/Article/details/gtvarozmga.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.daxiang520.top/Article/details/gthnmaldpc.html

Ruby: def greet(name = "World") = name
来源：http://dali.gzhubu.top/Article/details/gtomuhthkg.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.smart0.xyz/Article/details/gttiawtxnd.html

[C03] 可变参数
来源：http://dali.yanxiufei.cn/Article/details/gtoqqjhqyl.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhixingplan.top/Article/details/gtzmhygpag.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.wangshuangyany.cn/Article/details/gtvceljiwe.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.daxiang520.top/Article/details/gtcgmiclfz.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.pengpengdd.cyou/Article/details/gthifyjfrd.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtppqugegm.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhiwuduotai.top/Article/details/gtrxbsdlmf.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jiagoushi.top/Article/details/gtqiiaxzif.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.meibo888.top/Article/details/gtfizmhtvs.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jinghuilouyu.cn/Article/details/gttexgfgvb.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gthndrppeh.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.wangdashe.top/Article/details/gtjkokarwm.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cashguo.top/Article/details/gttflwtfeg.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jqgufenzy.top/Article/details/gtordmzpco.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.svipenyu.cn/Article/details/gtvobexxal.html

Go:   // 无：用配置结构体参数
来源：http://dali.sweek.top/Article/details/gtnygwbicy.html

Ruby: f(a: 1, b: 2)
来源：http://dali.cheryme.top/Article/details/gtarykipzk.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gtmgskeytx.html

[C05] 返回多个值
来源：http://dali.bjfxy.top/Article/details/gthusxnnxa.html

Py:   return a, b
来源：http://dali.aibaodan.cn/Article/details/gtjyqnwrhl.html

PHP:  return [$a, $b];
来源：http://dali.jqgufenzy.top/Article/details/gtzwbdplpw.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ybcxt.top/Article/details/gtsoestazt.html

TS:   return { a, b };
来源：http://dali.wangshuangyany.cn/Article/details/gtikpefszb.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.pycfn.com/Article/details/gtqgjyhtxl.html

Go:   return a, b
来源：http://dali.jinqigufen.top/Article/details/gtutvghjxv.html

Ruby: return a, b
来源：http://dali.hammf.cn/Article/details/gtrheodupm.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shuidangran.top/Article/details/gtxfzkcfnl.html

[C06] 匿名函数 / lambda
来源：http://dali.aizwys.cn/Article/details/gtmqljgtji.html

Py:   square = lambda x: x * x
来源：http://dali.guowangkeji.top/Article/details/gtlvyhckfe.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.redwolf501.top/Article/details/gtlcivykdl.html

JS:   const square = x => x * x;
来源：http://dali.c1oappe.top/Article/details/gtocaiescw.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.snrcjt.cn/Article/details/gtcvblbdoe.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jinqigufen.top/Article/details/gtfiyjrczi.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.sxryk.cn/Article/details/gtdjdratqg.html

Ruby: square = ->(x) { x * x }
来源：http://dali.cheryme.top/Article/details/gtldodhgvo.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.guannengcc.top/Article/details/gtdrcvsqdi.html

[C07] 把函数作为参数传入
来源：http://dali.dianchejie.cn/Article/details/gtitfdrfua.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.feifeiyinyue.top/Article/details/gtswnyvukd.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtypwzbyfw.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cucudq.cn/Article/details/gtzhhgtblo.html

TS:   arr.map(String)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsbckekjt.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yongpay.top/Article/details/gtobbuflrr.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.havefunace.top/Article/details/gtbvltprfi.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhoulong.xyz/Article/details/gthvgirwuj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yj20258888.top/Article/details/gtbxqwmkti.html

[C08] 闭包
来源：http://dali.wangdashe.top/Article/details/gttceceudq.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhongyouzk.top/Article/details/gtytymakpb.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.andypj.xyz/Article/details/gtvfupfdwt.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cheryme.top/Article/details/gtullamdzq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.pengpengdd.cyou/Article/details/gteiwhpjbg.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.chenzaomai.com/Article/details/gtzccfxfmj.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.ivvv.top/Article/details/gtiwfcselr.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.sysykeji.top/Article/details/gtrqbtlqpd.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hfpthk.cn/Article/details/gtuthuplty.html

[C09] 递归
来源：http://dali.jyoumei.cn/Article/details/gtwazqamsd.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.svipenyu.cn/Article/details/gtapxouokm.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.aibaodan.cn/Article/details/gtmlbmdhmr.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtswunbqkc.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ydzc1.top/Article/details/gtnvpfqqna.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.gotoacloud.top/Article/details/gtfnyimucw.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zycfv.cn/Article/details/gtcdktblvn.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xziqi.cn/Article/details/gtlrnurhxf.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yuanzhike.top/Article/details/gtohpcscer.html

[C10] 变量作用域
来源：http://dali.guowangkeji.top/Article/details/gtgutdpdmy.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.sweek.top/Article/details/gtxqvmiztd.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinqigufen.top/Article/details/gthwowhdkw.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hywenlv.cn/Article/details/gtnaehigjb.html

TS:   同 JS
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtovatnydk.html

Java: 方法内为块级作用域
来源：http://dali.ybcxt.top/Article/details/gtwjtvznyf.html

Go:   花括号块级作用域
来源：http://dali.smart0.xyz/Article/details/gtrkdnnisv.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yvedp.cn/Article/details/gtgvghcgkw.html

C#:   块级作用域
来源：http://dali.sxryk.cn/Article/details/gtfepyfawq.html

[C11] 模块导入与导出
来源：http://dali.zhengqikj.top/Article/details/gtrzwgiojy.html

Py:   from module import func
来源：http://dali.gaohongyu789.top/Article/details/gtrzilrnxo.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jqgfzy.top/Article/details/gtukhvutpn.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthfseulfn.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.shanyushiyangtech.top/Article/details/gtpwmrostu.html

Java: import java.util.List;
来源：http://dali.kuanghao11.cn/Article/details/gtdsidkvzc.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.gaohongyu789.top/Article/details/gtosnmiikq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gtehhitboy.html

C#:   using System.Text;
来源：http://dali.cheryme.top/Article/details/gtleuhpjya.html

[C12] 立即执行函数 IIFE
来源：http://dali.nanxinkj.top/Article/details/gtlumjjfxq.html

Py:   (lambda: print("run"))()
来源：http://dali.cdnleiting.top/Article/details/gtjiuwgnwo.html

PHP:  (function () { echo "run"; })();
来源：http://dali.chenlongwang.top/Article/details/gtushwseme.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yvedp.cn/Article/details/gtlkaeepwt.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cqqwz.cn/Article/details/gtvcwufomf.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yongpay.top/Article/details/gtbrbulvqm.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yj20258888.top/Article/details/gtpzqvxgbs.html

Ruby: -> { puts "run" }.call
来源：http://dali.xinyue.icu/Article/details/gteeqjuuwx.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zycfv.cn/Article/details/gtcvukqzho.html

[C13] 类型声明 / 类型注解
来源：http://dali.ybcxt.top/Article/details/gtazzsuwtx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.wangshuangyany.cn/Article/details/gtgldgfjnz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.316326.xyz/Article/details/gtoxkiukcv.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.dashuyun.cn/Article/details/gtwbzrdgog.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gtnxxrmrlv.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gtochsgjjf.html

Go:   func add(a, b int) int
来源：http://dali.ybcxt.top/Article/details/gtpdnluyqm.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkxrblnlx.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xylfe.cn/Article/details/gtvtuuexnf.html

[C14] 泛型函数
来源：http://dali.smart0.xyz/Article/details/gtpdeowpwi.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.aizwys.cn/Article/details/gtepdyapvm.html

PHP:  // 无泛型
来源：http://dali.havefunace.top/Article/details/gtgngtruqy.html

JS:   // 无泛型
来源：http://dali.shuidangran.top/Article/details/gtaayyohlr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xinyue.icu/Article/details/gtlyqoexij.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xinyue.icu/Article/details/gtvbfowxmj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yvedp.cn/Article/details/gthgdvmfvy.html

Ruby: # 无泛型
来源：http://dali.ivvv.top/Article/details/gtgdxvrffr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhongyouzk.top/Article/details/gtrrldlnzc.html

[C15] 解构 / 展开参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsffwfmxk.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.iojbl.cn/Article/details/gtxppiripq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.smart0.xyz/Article/details/gtdfrowior.html


<!-- 参考信息 -->