代发 wailian999

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.shzxlz.cn/Article/details/gtkfcvurdt.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.tian-w.cn/Article/details/gtnezogvxw.html

TS:   // Node.js：readline 模块
来源：http://dali.9152youxi.cn/Article/details/gtbmdvsesr.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.hywenlv.cn/Article/details/gtrdcbakef.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.316326.xyz/Article/details/gtrhmgotyt.html

Ruby: gets.chomp
来源：http://dali.dianchejie.cn/Article/details/gtkanfcsdy.html

C#:   Console.ReadLine();
来源：http://dali.havefunace.top/Article/details/gtdvfmxach.html

[A21] 保留指定小数位输出
来源：http://dali.ivvv.top/Article/details/gtprptkmtd.html

Py:   f"{3.14159:.2f}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtvwyadepc.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.xziqi.cn/Article/details/gtsdpplnbq.html

JS:   (3.14159).toFixed(2)
来源：http://dali.mhx1999.top/Article/details/gtmawjzftp.html

TS:   (3.14159).toFixed(2)
来源：http://dali.quarkkingdee.top/Article/details/gthgbmrdje.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.9152youxi.cn/Article/details/gtqckfmafr.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.zhijiandao.cn/Article/details/gtsmklvamk.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.snrcjt.cn/Article/details/gtqjipebfb.html

C#:   3.14159.ToString("F2")
来源：http://dali.pengpengdd.cyou/Article/details/gtckqelfsc.html

[A22] 获取字符串长度
来源：http://dali.kuanghao11.cn/Article/details/gtnmesbvvb.html

Py:   len(s)
来源：http://dali.yuxming.cn/Article/details/gtppxalwlu.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.yonumen.top/Article/details/gtrrzalcol.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.yj20258.top/Article/details/gtjpiqznjf.html

TS:   s.length
来源：http://dali.haohaochexian.top/Article/details/gtdlrlsihv.html

Java: s.length()
来源：http://dali.fengsongda.top/Article/details/gtsdvokrpn.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.bjfxy.top/Article/details/gtkkyfmdir.html

Ruby: s.length
来源：http://dali.guowangkeji.top/Article/details/gtfjxefpdm.html

C#:   s.Length
来源：http://dali.nwbrower.top/Article/details/gtaiuitjnq.html

[A23] 大小写转换
来源：http://dali.jyoumei.cn/Article/details/gtefqbngen.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.hnqzz.top/Article/details/gtokjkunas.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.guannengcc.top/Article/details/gtmposimoh.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yvedp.cn/Article/details/gtvskajvmx.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhengqikj.top/Article/details/gtdudpijre.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.sweek.top/Article/details/gtdkvmnaik.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.yuxming.cn/Article/details/gtaspeidtg.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.jinqigufen.top/Article/details/gtifxmlkta.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.wangshuangyany.cn/Article/details/gtvwdtsuwa.html

[A24] 去除首尾空白
来源：http://dali.vqdsnc.cn/Article/details/gtnciulaar.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.gzhubu.top/Article/details/gthaahznts.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.vqdsnc.cn/Article/details/gtozqnrclx.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.svipenyu.cn/Article/details/gtoydkdscm.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.daxiang520.top/Article/details/gtjaezrgev.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.hnxiangtu.top/Article/details/gttdwtpjwb.html

Go:   strings.TrimSpace(s)
来源：http://dali.dashuyun.cn/Article/details/gtmwozmxtx.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.tanke756.top/Article/details/gtsvehgakf.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.andypj.xyz/Article/details/gtegpdymxk.html

[A25] 字符串比较
来源：http://dali.yvedp.cn/Article/details/gtedoluckl.html

Py:   s1 == s2; s1 != s2
来源：http://dali.0kj1m.cn/Article/details/gthhsnafhi.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yanxiufei.cn/Article/details/gtupdxgmiq.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jqgufenzy.top/Article/details/gteefcpkwq.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ppjwa.cn/Article/details/gtwnpaburw.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.nwbrower.top/Article/details/gtzeestjhb.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.fengsongda.top/Article/details/gtfkdbznqq.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.chenjidiqi.icu/Article/details/gtthlblgkg.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.sysykeji.top/Article/details/gtqkaphnpy.html

[A26] 类型转换总览
来源：http://dali.ydzc1.top/Article/details/gttqrtxjnl.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.havefunace.top/Article/details/gtlxzxopye.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.nanxuanxn.top/Article/details/gtsuqwsryz.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.pycfn.com/Article/details/gtkgsurfrp.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yj20258888.top/Article/details/gtonzkmijb.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.kuanghao11.cn/Article/details/gtzgxzjlux.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.9152youxi.cn/Article/details/gttbnyjzkc.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.ppjwa.cn/Article/details/gtdraaejxo.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.jyoumei.cn/Article/details/gtkyohsgzp.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtgyzniwgx.html

B. 流程控制
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyinlrsrc.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtyrdfimjy.html

[B01] 条件判断 if / else
来源：http://dali.shzxlz.cn/Article/details/gtubqeoqqe.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zhongyouzk.top/Article/details/gtfmjzdkep.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.andypj.xyz/Article/details/gtvcrobwra.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtytjpdgco.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.kuanghao11.cn/Article/details/gtidmzudfx.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.yvedp.cn/Article/details/gtnqcnxmzl.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yj20258888.top/Article/details/gtjmllguys.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.shanyushiyangtech.top/Article/details/gtpcohevkq.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.ybcxt.top/Article/details/gtyowsgxwc.html

[B02] 多分支 else if / elif
来源：http://dali.yuanzhike.top/Article/details/gtovvzcvmx.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.iojbl.cn/Article/details/gtekdtcnyy.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yangfankeji.com/Article/details/gtvwcptfui.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shanyushiyangtech.top/Article/details/gtuvhgirjb.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhongyouzk.top/Article/details/gtadznlwym.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ybcxt.top/Article/details/gtpmbajpmn.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yonumen.top/Article/details/gttfcfzfql.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtccjblcts.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwoxqrdat.html

[B03] switch / match / case
来源：http://dali.jqgufenzy.top/Article/details/gtmcbcyfqe.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.fzhhl.top/Article/details/gtdciswaxm.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.hywenlv.cn/Article/details/gtlwpcznhp.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jlsjyb.cn/Article/details/gtlbtgdlvx.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhoulong.xyz/Article/details/gtddonhetr.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.gogol.net.cn/Article/details/gtfqunzskf.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.cdnleiting.top/Article/details/gtxpkuwteg.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.zhengqikj.top/Article/details/gttikridjh.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.havefunace.top/Article/details/gtoqckzevy.html

[B04] for 计数循环
来源：http://dali.jiagoushi.top/Article/details/gtnsqtvhni.html

Py:   for i in range(10): print(i)
来源：http://dali.feifeiyinyue.top/Article/details/gtywcetpgx.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.wangdashe.top/Article/details/gtyetxjsjt.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.vqdsnc.cn/Article/details/gtkxducmlr.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ppjwa.cn/Article/details/gtlzxmizpw.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yj20258888.top/Article/details/gtzsxxuvxv.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.bjfxy.top/Article/details/gtgzjgmkzb.html

Ruby: 10.times { |i| puts i }
来源：http://dali.guannengcc.top/Article/details/gtwislxvff.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.mhx1999.top/Article/details/gtsuetbzwv.html

[B05] 遍历数组 / 列表
来源：http://dali.sufxvd.cn/Article/details/gtyiiwaqge.html

Py:   for item in arr: print(item)
来源：http://dali.yj20258.top/Article/details/gtjbihkdkr.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zhijiandao.cn/Article/details/gtmyhinfbr.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yj20258.top/Article/details/gtbzavlegb.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.nanxinkj.top/Article/details/gtaskwcrvy.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthulfioct.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtligohpfa.html

Ruby: arr.each { |item| puts item }
来源：http://dali.andypj.xyz/Article/details/gtwynwjwyt.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.shzxlz.cn/Article/details/gtqiyrvvys.html

[B06] 遍历字典 / 对象
来源：http://dali.mhx1999.top/Article/details/gtjemnegfr.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.andypj.xyz/Article/details/gtcbubbjtm.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hfpthk.cn/Article/details/gtgqexygza.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.pengpengdd.cyou/Article/details/gtjbkjsrff.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.havefunace.top/Article/details/gtiugiehfy.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzyhdvypk.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.gotoacloud.top/Article/details/gtowqqopge.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.ivvv.top/Article/details/gtsvztywah.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jianghu66.top/Article/details/gtwtsznaxd.html

[B07] while 循环
来源：http://dali.havefunace.top/Article/details/gtsaoaegyh.html

Py:   while i < 10: i += 1
来源：http://dali.xuanzx.com/Article/details/gtvvdepmww.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.hysaishi.cn/Article/details/gtdjpyimrv.html

JS:   while (i < 10) { i++; }
来源：http://dali.0kj1m.cn/Article/details/gtpcryfwtb.html

TS:   while (i < 10) { i++; }
来源：http://dali.jiagoushi.top/Article/details/gtowzpvoea.html

Java: while (i < 10) { i++; }
来源：http://dali.jinqigfzy.top/Article/details/gtnyjwcvev.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhengqikj.top/Article/details/gtubaqqial.html

Ruby: while i < 10; i += 1; end
来源：http://dali.sweek.top/Article/details/gtysuloxjn.html

C#:   while (i < 10) { i++; }
来源：http://dali.yvedp.cn/Article/details/gtnobgflwj.html

[B08] do-while（至少执行一次）
来源：http://dali.9152youxi.cn/Article/details/gtuncvjzcr.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.0kj1m.cn/Article/details/gtiamrkdub.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yanxiufei.cn/Article/details/gtihihvvbg.html

JS:   do { i++; } while (i < 10);
来源：http://dali.gzhubu.top/Article/details/gtqielonju.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhengqikj.top/Article/details/gtgipqhhkj.html

Java: do { i++; } while (i < 10);
来源：http://dali.jqgufenzy.top/Article/details/gtvaukieqv.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.daxiang520.top/Article/details/gtpwhtquwa.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.tanke756.top/Article/details/gtycqffted.html

C#:   do { i++; } while (i < 10);
来源：http://dali.shzxlz.cn/Article/details/gtlpegwakh.html

[B09] break 与 continue
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpiwylicq.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.hfpthk.cn/Article/details/gtyhgustsv.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.hywenlv.cn/Article/details/gtbcwccauw.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tian-w.cn/Article/details/gtistakuby.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pycfn.com/Article/details/gtkdkwsgyc.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tian-w.cn/Article/details/gtzfervzmp.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.fengsongda.top/Article/details/gtejdqjmgz.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.hnqzz.top/Article/details/gtneyoiatj.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daxiang520.top/Article/details/gtnrwvnocw.html

[B10] 遍历同时拿索引
来源：http://dali.c1oappe.top/Article/details/gtmudpmbem.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.hammf.cn/Article/details/gtjrymqxrj.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.svipenyu.cn/Article/details/gtqqrwbzxn.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.chenlongwang.top/Article/details/gtrhbuwupb.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.hywenlv.cn/Article/details/gtrocggwua.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yuanzhike.top/Article/details/gthtcydgtm.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.gogol.net.cn/Article/details/gtxhgowcjj.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.xinyue.icu/Article/details/gtxbycjqtk.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.ppjwa.cn/Article/details/gtqdbtuhmb.html

[B11] 生成数字序列 / 区间
来源：http://dali.shzxlz.cn/Article/details/gtewxysaaf.html

Py:   list(range(0, 10, 2))
来源：http://dali.gogol.net.cn/Article/details/gtokrajujx.html

PHP:  range(0, 10, 2);
来源：http://dali.shzxlz.cn/Article/details/gtmwrwgnas.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.fengsongda.top/Article/details/gtgtakbiyu.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.nanxuanxn.top/Article/details/gtllxdtoin.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.dashuyun.cn/Article/details/gtnxcuysam.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.shzxlz.cn/Article/details/gttmibtggr.html

Ruby: (0...10).step(2).to_a
来源：http://dali.aibaodan.cn/Article/details/gtvrnqonoc.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gtzfiywrow.html

[B12] 跳出多层循环
来源：http://dali.smart0.xyz/Article/details/gtfkpylxwk.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.sufxvd.cn/Article/details/gtqyllgovt.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.aizwys.cn/Article/details/gtmdfdtzal.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.svipenyu.cn/Article/details/gtnsghyzgk.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.kuanghao11.cn/Article/details/gtyjpvrtwx.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.redwolf501.top/Article/details/gtubijkiew.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.gotoacloud.top/Article/details/gtouxmgkve.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.fengsongda.top/Article/details/gtlsmuomxw.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jyoumei.cn/Article/details/gtmahxhgtq.html

[B13] 判断是否为数字
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzxfjawdo.html

Py:   isinstance(x, (int, float))
来源：http://dali.ehwqpu.com/Article/details/gtpqnzlvki.html

PHP:  is_numeric($x)
来源：http://dali.shuidangran.top/Article/details/gtojfgxfdn.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tian-w.cn/Article/details/gtiinzexqr.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenzaomai.com/Article/details/gthxuyraju.html

Java: x instanceof Number
来源：http://dali.hysaishi.cn/Article/details/gtjnyfatza.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jinqigufen.top/Article/details/gtgkwmuawa.html

Ruby: x.is_a?(Numeric)
来源：http://dali.chenzaomai.com/Article/details/gtlrmitgix.html

C#:   x is int or double or decimal
来源：http://dali.cashguo.top/Article/details/gtiheytjid.html

[B14] 判断值是否在集合内
来源：http://dali.birdmap.top/Article/details/gtwaostdmp.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.sysykeji.top/Article/details/gtxumsqcdn.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnlfatvhk.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.nanxinkj.top/Article/details/gtdmsrdrau.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yanxiufei.cn/Article/details/gtjpwerqek.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.xinyue.icu/Article/details/gtsnrxevzh.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.shuidangran.top/Article/details/gtifqmqiwt.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yongpay.top/Article/details/gtwuolnkcq.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtthcqhrpj.html

[B15] 布尔运算与取反
来源：http://dali.cashguo.top/Article/details/gtdlghxxfl.html

Py:   a and b or not c
来源：http://dali.hammf.cn/Article/details/gtegwdccxf.html

PHP:  $a && $b || !$c
来源：http://dali.yuxming.cn/Article/details/gtewfesvuc.html

JS:   a && b || !c
来源：http://dali.yj202588.top/Article/details/gtvqzmkieh.html

TS:   a && b || !c
来源：http://dali.aizwys.cn/Article/details/gtwhgnodar.html

Java: a && b || !c
来源：http://dali.zhiwuduotai.top/Article/details/gtgbzhfeli.html

Go:   a && b || !c
来源：http://dali.wangdashe.top/Article/details/gtxxddhrtu.html

Ruby: a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gtaqgbtoqt.html

C#:   a && b || !c
来源：http://dali.andypj.xyz/Article/details/gttxiunbns.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.kuanghao11.cn/Article/details/gtdwuhnaqd.html

Py:   if not data: return
来源：http://dali.xuanzx.com/Article/details/gtanbofcpy.html

PHP:  if (!$data) { return; }
来源：http://dali.316326.xyz/Article/details/gtuwdmobzg.html

JS:   if (!data) return;
来源：http://dali.yuxming.cn/Article/details/gtfthxbmje.html

TS:   if (!data) return;
来源：http://dali.pengpengdd.cyou/Article/details/gtyfmtnsvf.html

Java: if (data == null) return;
来源：http://dali.gaohongyu789.top/Article/details/gtiejbnsnm.html

Go:   if data == nil { return }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthjnzqsrl.html

Ruby: return if data.nil?
来源：http://dali.zdqjudy.top/Article/details/gttsiwifyw.html

C#:   if (data == null) return;
来源：http://dali.jqgufenzy.top/Article/details/gthfbyvqrf.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtvqtnvayk.html

C. 函数与作用域
来源：http://dali.pycfn.com/Article/details/gtpqbdrxbg.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtzpeqzmxq.html

[C01] 定义函数
来源：http://dali.cqqwz.cn/Article/details/gtfytgzxgc.html

Py:   def add(a, b): return a + b
来源：http://dali.havefunace.top/Article/details/gtxnjvlgjl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.snrcjt.cn/Article/details/gtqmnbhqyr.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gtmptswtrm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hywenlv.cn/Article/details/gtmmadaahh.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.birdmap.top/Article/details/gtvgnaujnm.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhengqikj.top/Article/details/gthtfwfipo.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ivvv.top/Article/details/gtdajcigqn.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gtzdhwvtja.html

[C02] 默认参数
来源：http://dali.jiagoushi.top/Article/details/gtvsvnzzqe.html

Py:   def greet(name="World"): return name
来源：http://dali.hongshengwenyu.top/Article/details/gtdazgyttn.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.dashuyun.cn/Article/details/gtqkexhxus.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.snrcjt.cn/Article/details/gtdsevprwy.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yj20258888.top/Article/details/gtvkyidklj.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfoxzoevn.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hammf.cn/Article/details/gtpsmdipsn.html

Ruby: def greet(name = "World") = name
来源：http://dali.haohaochexian.top/Article/details/gtrogxgpoe.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hywenlv.cn/Article/details/gtrqrctgnp.html

[C03] 可变参数
来源：http://dali.svipenyu.cn/Article/details/gtewstmjmo.html

Py:   def total(*args): return sum(args)
来源：http://dali.redwolf501.top/Article/details/gtqzftyhvw.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yj20258.top/Article/details/gtalawnczn.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yuanzhike.top/Article/details/gttlnotdln.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.snrcjt.cn/Article/details/gtounzqgsx.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiuzzjgpp.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.fzhhl.top/Article/details/gtbapdjykq.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.chenzaomai.com/Article/details/gtdkkigltn.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.fengsongda.top/Article/details/gtwaghsbob.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yonumen.top/Article/details/gtbzhnribu.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.gogol.net.cn/Article/details/gtcmnuxjyn.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yj202588.top/Article/details/gtjbvlroml.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbpjskzgi.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.wangdashe.top/Article/details/gtgomerutp.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.gzhubu.top/Article/details/gtlypenazw.html

Go:   // 无：用配置结构体参数
来源：http://dali.yangfankeji.com/Article/details/gtxzjvtamv.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hnqzz.top/Article/details/gtltuowhsj.html

C#:   f(a: 1, b: 2)
来源：http://dali.jqgufenzy.top/Article/details/gteyaieonp.html

[C05] 返回多个值
来源：http://dali.sweek.top/Article/details/gtocnewfdw.html

Py:   return a, b
来源：http://dali.tanke756.top/Article/details/gtrteysdoo.html

PHP:  return [$a, $b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpyxypzlb.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.gaohongyu789.top/Article/details/gtrirmdola.html

TS:   return { a, b };
来源：http://dali.aibaodan.cn/Article/details/gtgrrugyju.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jianghu66.top/Article/details/gtgiazdjfz.html

Go:   return a, b
来源：http://dali.cucudq.cn/Article/details/gthxzrtvfz.html

Ruby: return a, b
来源：http://dali.mhx1999.top/Article/details/gttrgmdveg.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hysaishi.cn/Article/details/gtimsogvha.html

[C06] 匿名函数 / lambda
来源：http://dali.meibo888.top/Article/details/gtlkncjsio.html

Py:   square = lambda x: x * x
来源：http://dali.0kj1m.cn/Article/details/gtktyjtfqj.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.fzhhl.top/Article/details/gtlmlxammd.html

JS:   const square = x => x * x;
来源：http://dali.jianghu66.top/Article/details/gtmvcykscm.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.guannengcc.top/Article/details/gtdlkfhbsc.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yuxming.cn/Article/details/gtkxhnjgnh.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.feifeiyinyue.top/Article/details/gtuopnvxfb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.svipenyu.cn/Article/details/gtqyciawcd.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hongshengwenyu.top/Article/details/gtuvrbmiux.html

[C07] 把函数作为参数传入
来源：http://dali.aizwys.cn/Article/details/gtpiypiase.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.guowangkeji.top/Article/details/gtxxbbcfha.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.316326.xyz/Article/details/gtkvojbdrw.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hnxiangtu.top/Article/details/gtuochknjt.html

TS:   arr.map(String)
来源：http://dali.tanke756.top/Article/details/gtivhkpcxi.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yangfankeji.com/Article/details/gtuvhcjoib.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.guowangkeji.top/Article/details/gtoclqlbqr.html

Ruby: arr.map(&:upcase)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvedsclbx.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.c1oappe.top/Article/details/gtcrwntymd.html

[C08] 闭包
来源：http://dali.jinqigfzy.top/Article/details/gtiudiuzct.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cqqwz.cn/Article/details/gtyjdcaulf.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jqgfzy.top/Article/details/gtymtdfrfs.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hysaishi.cn/Article/details/gtpxwlrpdw.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.vqdsnc.cn/Article/details/gtnzwwoorb.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ybcxt.top/Article/details/gthwkavkpb.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.gogol.net.cn/Article/details/gthvtgplva.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhoulong.xyz/Article/details/gtmwsvvedh.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfabckraa.html

[C09] 递归
来源：http://dali.shuidangran.top/Article/details/gtkkxtjzbt.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ybcxt.top/Article/details/gtwmsintsi.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.iojbl.cn/Article/details/gtanwsgmug.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hywenlv.cn/Article/details/gtwtnywswx.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cheryme.top/Article/details/gttezrxfir.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shangyingyoupin.top/Article/details/gtdsokkqct.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.wangdashe.top/Article/details/gtvwfeuzdi.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jianghu66.top/Article/details/gtqpzslpne.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.sufxvd.cn/Article/details/gtzvkvdyhz.html

[C10] 变量作用域
来源：http://dali.0kj1m.cn/Article/details/gtjhymcihr.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gtftacudyr.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jianghu66.top/Article/details/gtlmvfmwbt.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yj20258888.top/Article/details/gtlpfqexiz.html

TS:   同 JS
来源：http://dali.gzhubu.top/Article/details/gteipkxpwa.html

Java: 方法内为块级作用域
来源：http://dali.gogol.net.cn/Article/details/gtzbsxnsyg.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gtsiwoohif.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cashguo.top/Article/details/gtcikgvpzs.html


<!-- 参考信息 -->