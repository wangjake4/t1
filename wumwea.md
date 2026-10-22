代发 wailian999

[A22] 获取字符串长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lkcjfxyp.html

Py:   len(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2hteuxhcf.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.sufxvd.cn/Article/details/gt2jjcczqqd.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.vqdsnc.cn/Article/details/gt2mhiyhsvh.html

TS:   s.length
来源：http://dali.wangshuangyany.cn/Article/details/gt2juzhsixt.html

Java: s.length()
来源：http://dali.cucudq.cn/Article/details/gt2lupuffio.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2dfxllxfm.html

Ruby: s.length
来源：http://dali.chenlongwang.top/Article/details/gt2tdandfuk.html

C#:   s.Length
来源：http://dali.jinqigufen.top/Article/details/gt2hdqlwvfw.html

[A23] 大小写转换
来源：http://dali.daxiang520.top/Article/details/gt2zvbkbgcj.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.jlsjyb.cn/Article/details/gt2jrfgxkhx.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uwgsesrs.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.daxiang520.top/Article/details/gt2nspbsosk.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yueranfly.top/Article/details/gt2exscahbf.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tmbcalfh.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.iojbl.cn/Article/details/gt2iiiysxux.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.chenjidiqi.icu/Article/details/gt2nippuniz.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.pycfn.com/Article/details/gt2gsdncvvq.html

[A24] 去除首尾空白
来源：http://dali.hnqzz.top/Article/details/gt2urxzjmhb.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.gogol.net.cn/Article/details/gt2zvtcdwqu.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.jqgfzy.top/Article/details/gt2dmkspqzk.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jqgufenzy.top/Article/details/gt2ukeaqofu.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhoulong.xyz/Article/details/gt2ehnkewhm.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.yongpay.top/Article/details/gt2vlqojmge.html

Go:   strings.TrimSpace(s)
来源：http://dali.gogol.net.cn/Article/details/gt2bdovayrb.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yuanzhike.top/Article/details/gt2qcmsudxv.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.zhiwuduotai.top/Article/details/gt2srmmryse.html

[A25] 字符串比较
来源：http://dali.dianchejie.cn/Article/details/gt2hbvbgolx.html

Py:   s1 == s2; s1 != s2
来源：http://dali.9152youxi.cn/Article/details/gt2rsjpylvo.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.sysykeji.top/Article/details/gt2beceymxs.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yuanzhike.top/Article/details/gt2yypqsnpb.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ozlyzctt.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wbqjykiu.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mftpztif.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.sxryk.cn/Article/details/gt2pucutfos.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.tianlin.xyz/Article/details/gt2ykghgzpu.html

[A26] 类型转换总览
来源：http://dali.zhijiandao.cn/Article/details/gt2fchwzhuc.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jqgfzy.top/Article/details/gt2ddmegmev.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ciqeihdo.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.sxryk.cn/Article/details/gt2tdrqvjrm.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zhongyouzk.top/Article/details/gt2zrykrbab.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2joewjdaj.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.nanxuanxn.top/Article/details/gt2itvnjjfs.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.ydzc1.top/Article/details/gt2gvyjgdvg.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eaulvcbb.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2krcqhccf.html

B. 流程控制
来源：http://dali.gogol.net.cn/Article/details/gt2vrijhswt.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2vlmrebgu.html

[B01] 条件判断 if / else
来源：http://dali.jqgfzy.top/Article/details/gt2rajrnbgp.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.havefunace.top/Article/details/gt2fntlywgn.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2ujofucht.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.tanke756.top/Article/details/gt2cclnwyqg.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.daxiang520.top/Article/details/gt2judiomja.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.sysykeji.top/Article/details/gt2ljlqqmny.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.pycfn.com/Article/details/gt2grswtaou.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.smart0.xyz/Article/details/gt2ozauygxe.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.zycfv.cn/Article/details/gt2hmppkiio.html

[B02] 多分支 else if / elif
来源：http://dali.aibaodan.cn/Article/details/gt2dnlqoeby.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.zhiwuduotai.top/Article/details/gt2rukzpkyu.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.hammf.cn/Article/details/gt2dpznagxj.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhengqikj.top/Article/details/gt2izwxytci.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigfzy.top/Article/details/gt2uevhxhmr.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.vqdsnc.cn/Article/details/gt2fnxmbezv.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jxburstf.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.c1oappe.top/Article/details/gt2ztraryct.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tian-w.cn/Article/details/gt2vwgsusuf.html

[B03] switch / match / case
来源：http://dali.zhijiandao.cn/Article/details/gt2jkgcxgfw.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jlsjyb.cn/Article/details/gt2cxiysrmj.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2xenyvgdr.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yj20258.top/Article/details/gt2dgvafrtb.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xuanzx.com/Article/details/gt2czcocbof.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.pycfn.com/Article/details/gt2znvvteja.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.havefunace.top/Article/details/gt2stktbgip.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.cashguo.top/Article/details/gt2zkbsubnc.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.ybcxt.top/Article/details/gt2cikpsyrc.html

[B04] for 计数循环
来源：http://dali.zycfv.cn/Article/details/gt2czqymuwd.html

Py:   for i in range(10): print(i)
来源：http://dali.c1oappe.top/Article/details/gt2vwptcgyx.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.kuanghao11.cn/Article/details/gt2kzlevzbw.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jqgfzy.top/Article/details/gt2qgdbucov.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.havefunace.top/Article/details/gt2wrhxrzwv.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.svipenyu.cn/Article/details/gt2yhzqhxwd.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.jlsjyb.cn/Article/details/gt2miinjxlh.html

Ruby: 10.times { |i| puts i }
来源：http://dali.fzhhl.top/Article/details/gt2ymtdmzff.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.xinyue.icu/Article/details/gt2fenwoxsk.html

[B05] 遍历数组 / 列表
来源：http://dali.xuanzx.com/Article/details/gt2hnpldqtz.html

Py:   for item in arr: print(item)
来源：http://dali.hysaishi.cn/Article/details/gt2aogcsxgo.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.jlsjyb.cn/Article/details/gt2ttrqsoau.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.hywenlv.cn/Article/details/gt2kohogfal.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.shuidangran.top/Article/details/gt2yqyjdgob.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2craxlsvu.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.mhx1999.top/Article/details/gt2vqbdgikt.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yj20258.top/Article/details/gt2jouxnnwy.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.haohaochexian.top/Article/details/gt2ucucshex.html

[B06] 遍历字典 / 对象
来源：http://dali.shzxlz.cn/Article/details/gt2gepqggxk.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.dianchejie.cn/Article/details/gt2uuhuhosr.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2trehqdqe.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xuanzx.com/Article/details/gt2tyqwrrnz.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ydzc1.top/Article/details/gt2ggrftxxn.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.birdmap.top/Article/details/gt2ybhqhadv.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.9152youxi.cn/Article/details/gt2ilibiiow.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.chenzaomai.com/Article/details/gt2uftetlzs.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yangfankeji.com/Article/details/gt2vbealwbi.html

[B07] while 循环
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lkieqowi.html

Py:   while i < 10: i += 1
来源：http://dali.nanxinkj.top/Article/details/gt2rmqncoqb.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yanxiufei.cn/Article/details/gt2yafszann.html

JS:   while (i < 10) { i++; }
来源：http://dali.sxryk.cn/Article/details/gt2tbhbxxlw.html

TS:   while (i < 10) { i++; }
来源：http://dali.kuanghao11.cn/Article/details/gt2wfgcwztu.html

Java: while (i < 10) { i++; }
来源：http://dali.dashuyun.cn/Article/details/gt2ruotdfbb.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yvedp.cn/Article/details/gt2xelngpus.html

Ruby: while i < 10; i += 1; end
来源：http://dali.bjfxy.top/Article/details/gt2eeczxsvu.html

C#:   while (i < 10) { i++; }
来源：http://dali.haohaochexian.top/Article/details/gt2qnswnhmx.html

[B08] do-while（至少执行一次）
来源：http://dali.yvedp.cn/Article/details/gt2rshegfra.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhiwuduotai.top/Article/details/gt2kxqkwmoo.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yueranfly.top/Article/details/gt2hfbyufym.html

JS:   do { i++; } while (i < 10);
来源：http://dali.nanxuanxn.top/Article/details/gt2zfwoodtc.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jinqigufen.top/Article/details/gt2bbselmbc.html

Java: do { i++; } while (i < 10);
来源：http://dali.chenzaomai.com/Article/details/gt2jnagzelr.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.tanke756.top/Article/details/gt2lqktxgit.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.dashuyun.cn/Article/details/gt2zrfdgrnc.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yonumen.top/Article/details/gt2ruyvhndt.html

[B09] break 与 continue
来源：http://dali.zhoulong.xyz/Article/details/gt2xkgoafai.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.haohaochexian.top/Article/details/gt2mnfpcbwk.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.dianchejie.cn/Article/details/gt2lscowpob.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shuidangran.top/Article/details/gt2jdsmvlxk.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nanxuanxn.top/Article/details/gt2pqfhwwdp.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cheryme.top/Article/details/gt2eorzwzxg.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ehwqpu.com/Article/details/gt2hpappryp.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhoulong.xyz/Article/details/gt2pgbacrlr.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wquypbjm.html

[B10] 遍历同时拿索引
来源：http://dali.xziqi.cn/Article/details/gt2kuileyzs.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.shuidangran.top/Article/details/gt2voopwixf.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.ybcxt.top/Article/details/gt2qeqrnvbh.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hnqzz.top/Article/details/gt2wifxyzmn.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.chenjidiqi.icu/Article/details/gt2gcqkwudm.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.shuidangran.top/Article/details/gt2hvgmzpjl.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.shangyingyoupin.top/Article/details/gt2gqteqssr.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zdqjudy.top/Article/details/gt2xjthnumz.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.snrcjt.cn/Article/details/gt2pcrmfyou.html

[B11] 生成数字序列 / 区间
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oyewuaii.html

Py:   list(range(0, 10, 2))
来源：http://dali.xuanzx.com/Article/details/gt2zofgdeff.html

PHP:  range(0, 10, 2);
来源：http://dali.jianghu66.top/Article/details/gt2oekboklg.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ivvv.top/Article/details/gt2xecoaxxt.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yongpay.top/Article/details/gt2ihimpmjl.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.wangdashe.top/Article/details/gt2dpdayhhl.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.guowangkeji.top/Article/details/gt2pcvkcrqx.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yonumen.top/Article/details/gt2yndescsx.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yuanzhike.top/Article/details/gt2lnzrvalk.html

[B12] 跳出多层循环
来源：http://dali.hammf.cn/Article/details/gt2omjzinil.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yuanzhike.top/Article/details/gt2brpecbom.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jyoumei.cn/Article/details/gt2ynzmwpsd.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nwbrower.top/Article/details/gt2qfogcwfr.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj20258.top/Article/details/gt2vyzdwqep.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fhuumhdc.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.mhx1999.top/Article/details/gt2wfhmkymw.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hongshengwenyu.top/Article/details/gt2pmhtfkti.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yanxiufei.cn/Article/details/gt2ejyfuyqt.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2udrtnxif.html

Py:   isinstance(x, (int, float))
来源：http://dali.hysaishi.cn/Article/details/gt2nvcnykbu.html

PHP:  is_numeric($x)
来源：http://dali.dianchejie.cn/Article/details/gt2yigvdxkp.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.fzhhl.top/Article/details/gt2csyxhyau.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhixingplan.top/Article/details/gt2vcihfwcq.html

Java: x instanceof Number
来源：http://dali.hongshengwenyu.top/Article/details/gt2kkzxeexs.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rtrymyix.html

Ruby: x.is_a?(Numeric)
来源：http://dali.pengpengdd.cyou/Article/details/gt2oibclejv.html

C#:   x is int or double or decimal
来源：http://dali.hnqzz.top/Article/details/gt2stpmoqvx.html

[B14] 判断值是否在集合内
来源：http://dali.daria6918.cn/Article/details/gt2ikizbour.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.tian-w.cn/Article/details/gt2gvxzgjnu.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhiwuduotai.top/Article/details/gt2apdzdiab.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hnnyyaam.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yuxming.cn/Article/details/gt2qlumkrit.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.tanke756.top/Article/details/gt2ixqrceyu.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.quarkkingdee.top/Article/details/gt2erdikhti.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2qmkuwmjc.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hammf.cn/Article/details/gt2ludavnrx.html

[B15] 布尔运算与取反
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fuozqsbi.html

Py:   a and b or not c
来源：http://dali.andypj.xyz/Article/details/gt2xlpgeehb.html

PHP:  $a && $b || !$c
来源：http://dali.yuxming.cn/Article/details/gt2kqsjrkms.html

JS:   a && b || !c
来源：http://dali.ydzc1.top/Article/details/gt2wvvcxhag.html

TS:   a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gt2tsfwxupm.html

Java: a && b || !c
来源：http://dali.xuanzx.com/Article/details/gt2svpoawit.html

Go:   a && b || !c
来源：http://dali.fzhhl.top/Article/details/gt2wfphcsrg.html

Ruby: a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gt2chdwldvf.html

C#:   a && b || !c
来源：http://dali.xylfe.cn/Article/details/gt2ajovcvqf.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.redwolf501.top/Article/details/gt2ooffhlkh.html

Py:   if not data: return
来源：http://dali.pycfn.com/Article/details/gt2tgiykozi.html

PHP:  if (!$data) { return; }
来源：http://dali.hnqzz.top/Article/details/gt2tjihqgav.html

JS:   if (!data) return;
来源：http://dali.yj202588.top/Article/details/gt2futqsyhv.html

TS:   if (!data) return;
来源：http://dali.gogol.net.cn/Article/details/gt2tbscqlqi.html

Java: if (data == null) return;
来源：http://dali.kuanghao11.cn/Article/details/gt2hdaqpdbc.html

Go:   if data == nil { return }
来源：http://dali.nanxuanxn.top/Article/details/gt2kfknlzct.html

Ruby: return if data.nil?
来源：http://dali.guannengcc.top/Article/details/gt2pygkeigl.html

C#:   if (data == null) return;
来源：http://dali.jyoumei.cn/Article/details/gt2zohyifpi.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2dsngvtde.html

C. 函数与作用域
来源：http://dali.guowangkeji.top/Article/details/gt2isfrngtk.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2qijrweey.html

[C01] 定义函数
来源：http://dali.ydzc1.top/Article/details/gt2kcstxkfe.html

Py:   def add(a, b): return a + b
来源：http://dali.hnqzz.top/Article/details/gt2uidlvivp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gt2lqjnjwcz.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gt2wgkeakdg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gt2tktkiyyx.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gt2xqzcoiyu.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zycfv.cn/Article/details/gt2stoiivpn.html

Ruby: def add(a, b); a + b; end
来源：http://dali.dianchejie.cn/Article/details/gt2szzpcloe.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hammf.cn/Article/details/gt2inotzseg.html

[C02] 默认参数
来源：http://dali.yonumen.top/Article/details/gt2mekgkmwz.html

Py:   def greet(name="World"): return name
来源：http://dali.yuanzhike.top/Article/details/gt2jvbtujte.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qifheyps.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhengqikj.top/Article/details/gt2flpckrrz.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rahnymod.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cqqwz.cn/Article/details/gt2qjytwwuk.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.aibaodan.cn/Article/details/gt2jcxgkqnd.html

Ruby: def greet(name = "World") = name
来源：http://dali.sufxvd.cn/Article/details/gt2tmpktghb.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yonumen.top/Article/details/gt2iwraggdf.html

[C03] 可变参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hzsmsaqv.html

Py:   def total(*args): return sum(args)
来源：http://dali.gotoacloud.top/Article/details/gt2zfzvzjdd.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.daria6918.cn/Article/details/gt2osibahuv.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gotoacloud.top/Article/details/gt2ceesegrn.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.mhx1999.top/Article/details/gt2dletmjtl.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jiagoushi.top/Article/details/gt2kmfomldl.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.fzhhl.top/Article/details/gt2wvkgcxlr.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sxryk.cn/Article/details/gt2pjhimbbw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oicdosog.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hnxiangtu.top/Article/details/gt2ecwkhkds.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.birdmap.top/Article/details/gt2zhyvhdfd.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yongpay.top/Article/details/gt2bcyaubnj.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2chzowddi.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hnxiangtu.top/Article/details/gt2aiiapmip.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.fengsongda.top/Article/details/gt2yhsbgpcu.html

Go:   // 无：用配置结构体参数
来源：http://dali.wangshuangyany.cn/Article/details/gt2leotzccj.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2gslxcwpb.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fxeptrzq.html

[C05] 返回多个值
来源：http://dali.xinyue.icu/Article/details/gt2dazeorxh.html

Py:   return a, b
来源：http://dali.hammf.cn/Article/details/gt2kmrmdbuo.html

PHP:  return [$a, $b];
来源：http://dali.nwbrower.top/Article/details/gt2ctibggtr.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.wangshuangyany.cn/Article/details/gt2vxfslddh.html

TS:   return { a, b };
来源：http://dali.9152youxi.cn/Article/details/gt2dgjzvlej.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jqgufenzy.top/Article/details/gt2piudveya.html

Go:   return a, b
来源：http://dali.yonumen.top/Article/details/gt2fntyqcwa.html

Ruby: return a, b
来源：http://dali.ivvv.top/Article/details/gt2ucanzqbc.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.xylfe.cn/Article/details/gt2dwzzbvex.html

[C06] 匿名函数 / lambda
来源：http://dali.hfpthk.cn/Article/details/gt2frzoutae.html

Py:   square = lambda x: x * x
来源：http://dali.nanxinkj.top/Article/details/gt2odidyncg.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.andypj.xyz/Article/details/gt2aroppqei.html

JS:   const square = x => x * x;
来源：http://dali.sufxvd.cn/Article/details/gt2yeptbluy.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yvedp.cn/Article/details/gt2sonzhksz.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.fzhhl.top/Article/details/gt2yxdoxxsm.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhengqikj.top/Article/details/gt2mlxgbbvx.html

Ruby: square = ->(x) { x * x }
来源：http://dali.sweek.top/Article/details/gt2hophdkmf.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.fzhhl.top/Article/details/gt2xvpmcyrw.html

[C07] 把函数作为参数传入
来源：http://dali.xuanzx.com/Article/details/gt2fxqvsuen.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.cheryme.top/Article/details/gt2rdseecfz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hfpthk.cn/Article/details/gt2dkvfqxsl.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hammf.cn/Article/details/gt2tpaqvvgd.html

TS:   arr.map(String)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xaipqauq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lhtzdnmd.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.gaohongyu789.top/Article/details/gt2xrpxkniw.html

Ruby: arr.map(&:upcase)
来源：http://dali.smart0.xyz/Article/details/gt2xfjaxqxp.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ydzc1.top/Article/details/gt2vcfxyehm.html

[C08] 闭包
来源：http://dali.pycfn.com/Article/details/gt2kprrjgit.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cqqwz.cn/Article/details/gt2mrvffnum.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.snrcjt.cn/Article/details/gt2fvwhowih.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.sufxvd.cn/Article/details/gt2afimtdaz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ppjwa.cn/Article/details/gt2juhapman.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.sxryk.cn/Article/details/gt2bppatbld.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ccwrsbex.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.gaohongyu789.top/Article/details/gt2lnzcmhyg.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hnqzz.top/Article/details/gt2zkmcyezt.html

[C09] 递归
来源：http://dali.jqgufenzy.top/Article/details/gt2noscsuss.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.guowangkeji.top/Article/details/gt2bdwlcnir.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.dianchejie.cn/Article/details/gt2vtdifcyc.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.svipenyu.cn/Article/details/gt2thcrlmtp.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hywenlv.cn/Article/details/gt2juhgsdku.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jqgufenzy.top/Article/details/gt2htjhemxy.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.iojbl.cn/Article/details/gt2ugxucktb.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.kuanghao11.cn/Article/details/gt2qdqegdew.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.gaohongyu789.top/Article/details/gt2kiinxtkh.html

[C10] 变量作用域
来源：http://dali.yongpay.top/Article/details/gt2iccpympv.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.pengpengdd.cyou/Article/details/gt2fioynonx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.wangdashe.top/Article/details/gt2apqcmamr.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ehwqpu.com/Article/details/gt2jnzynnns.html

TS:   同 JS
来源：http://dali.yj20258.top/Article/details/gt2mjfjrpqx.html

Java: 方法内为块级作用域
来源：http://dali.yuxming.cn/Article/details/gt2dvczfvmc.html

Go:   花括号块级作用域
来源：http://dali.tianlin.xyz/Article/details/gt2lhebnmds.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yanxiufei.cn/Article/details/gt2ndvqzjms.html

C#:   块级作用域
来源：http://dali.cashguo.top/Article/details/gt2sqakprkc.html

[C11] 模块导入与导出
来源：http://dali.snrcjt.cn/Article/details/gt2glvfauzm.html

Py:   from module import func
来源：http://dali.yongpay.top/Article/details/gt2delawuvb.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.dianchejie.cn/Article/details/gt2cwglkqsj.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bifgiqjv.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.andypj.xyz/Article/details/gt2kevtoriv.html

Java: import java.util.List;
来源：http://dali.andypj.xyz/Article/details/gt2lcablkyd.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shangyingyoupin.top/Article/details/gt2jsdjhvyz.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shangyingyoupin.top/Article/details/gt2aatwaazf.html

C#:   using System.Text;
来源：http://dali.zhoulong.xyz/Article/details/gt2gtmnbunw.html

[C12] 立即执行函数 IIFE
来源：http://dali.guannengcc.top/Article/details/gt2ebjrdeem.html

Py:   (lambda: print("run"))()
来源：http://dali.aibaodan.cn/Article/details/gt2doxwdbhe.html

PHP:  (function () { echo "run"; })();
来源：http://dali.316326.xyz/Article/details/gt2kvhvynqb.html

JS:   (() => { console.log("run"); })();
来源：http://dali.sufxvd.cn/Article/details/gt2cbmrobga.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jqgufenzy.top/Article/details/gt2uvpdseyc.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.iojbl.cn/Article/details/gt2lqltbrgj.html


<!-- 参考信息 -->