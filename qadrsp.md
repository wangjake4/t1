代发 wailian999

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.sysykeji.top/Article/details/gt2szmtawdw.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yanxiufei.cn/Article/details/gt2edqokndm.html

C#:   while (i < 10) { i++; }
来源：http://dali.redwolf501.top/Article/details/gt2ottqqnux.html

[B08] do-while（至少执行一次）
来源：http://dali.nanxinkj.top/Article/details/gt2vzrcqquu.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.hammf.cn/Article/details/gt2amomjnlm.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.shangyingyoupin.top/Article/details/gt2gbtumrhx.html

JS:   do { i++; } while (i < 10);
来源：http://dali.tianlin.xyz/Article/details/gt2ftvvfqto.html

TS:   do { i++; } while (i < 10);
来源：http://dali.cdnleiting.top/Article/details/gt2aaqvjpca.html

Java: do { i++; } while (i < 10);
来源：http://dali.daria6918.cn/Article/details/gt2otrofpty.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.pycfn.com/Article/details/gt2bmiabarh.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhongyouzk.top/Article/details/gt2hmreknvk.html

C#:   do { i++; } while (i < 10);
来源：http://dali.sweek.top/Article/details/gt2jpdyrcpb.html

[B09] break 与 continue
来源：http://dali.yongpay.top/Article/details/gt2jwhpqgur.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.xuetiantiany.cn/Article/details/gt2yhrvbohk.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.mhx1999.top/Article/details/gt2tpdaqtcd.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.0kj1m.cn/Article/details/gt2urtgjppz.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj202588.top/Article/details/gt2itlsvajk.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.vqdsnc.cn/Article/details/gt2phkqnlyz.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2txnhwvry.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ivvv.top/Article/details/gt2zhjfwlsh.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nwbrower.top/Article/details/gt2fjsgfpak.html

[B10] 遍历同时拿索引
来源：http://dali.yongpay.top/Article/details/gt2shhukuhm.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xhapxakx.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.hfpthk.cn/Article/details/gt2zdlulqhs.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jqgfzy.top/Article/details/gt2chgehgpn.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jlsjyb.cn/Article/details/gt2kpyeewmo.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.gotoacloud.top/Article/details/gt2omamewwq.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.sweek.top/Article/details/gt2yvbtspkt.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.aibaodan.cn/Article/details/gt2qrgojzrd.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.dianchejie.cn/Article/details/gt2rvsfzewu.html

[B11] 生成数字序列 / 区间
来源：http://dali.yj20258.top/Article/details/gt2odrpbngr.html

Py:   list(range(0, 10, 2))
来源：http://dali.cqqwz.cn/Article/details/gt2dlbconcs.html

PHP:  range(0, 10, 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lmeinckb.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.havefunace.top/Article/details/gt2bkvmwtkf.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jqgufenzy.top/Article/details/gt2cxqymlgm.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2aqgfqidm.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.ybcxt.top/Article/details/gt2kezomylm.html

Ruby: (0...10).step(2).to_a
来源：http://dali.bjfxy.top/Article/details/gt2ffahable.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jianghu66.top/Article/details/gt2scjgibyh.html

[B12] 跳出多层循环
来源：http://dali.sxryk.cn/Article/details/gt2lwzdohlk.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yj20258888.top/Article/details/gt2katqktjd.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xziqi.cn/Article/details/gt2oihmwebi.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxinkj.top/Article/details/gt2kilywhpa.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.tian-w.cn/Article/details/gt2ytorjxso.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ydzc1.top/Article/details/gt2qpwlfstd.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.sysykeji.top/Article/details/gt2obcxqjbf.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hysaishi.cn/Article/details/gt2jkxdqfij.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.svipenyu.cn/Article/details/gt2thjidifh.html

[B13] 判断是否为数字
来源：http://dali.zhixingplan.top/Article/details/gt2nscispnd.html

Py:   isinstance(x, (int, float))
来源：http://dali.shuidangran.top/Article/details/gt2wobdahyv.html

PHP:  is_numeric($x)
来源：http://dali.quarkkingdee.top/Article/details/gt2kliyhnpp.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2minidcwq.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nanxinkj.top/Article/details/gt2lipnckiw.html

Java: x instanceof Number
来源：http://dali.c1oappe.top/Article/details/gt2axzfwsoa.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jlkvyoie.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hywenlv.cn/Article/details/gt2njvaowtw.html

C#:   x is int or double or decimal
来源：http://dali.havefunace.top/Article/details/gt2gcyuiplo.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfvtijb.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.mhx1999.top/Article/details/gt2qaknclna.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.vqdsnc.cn/Article/details/gt2obynprsj.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mbocvnmq.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.gaohongyu789.top/Article/details/gt2cruhiuce.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.cheryme.top/Article/details/gt2teowceau.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jianghu66.top/Article/details/gt2vknlireh.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.dashuyun.cn/Article/details/gt2gwgzxcws.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xylfe.cn/Article/details/gt2biymmldb.html

[B15] 布尔运算与取反
来源：http://dali.mhx1999.top/Article/details/gt2lfnbljfc.html

Py:   a and b or not c
来源：http://dali.shuidangran.top/Article/details/gt2uskdlcfd.html

PHP:  $a && $b || !$c
来源：http://dali.guannengcc.top/Article/details/gt2zzrsuzpw.html

JS:   a && b || !c
来源：http://dali.fengsongda.top/Article/details/gt2tbezptea.html

TS:   a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gt2qkcupdxp.html

Java: a && b || !c
来源：http://dali.bjfxy.top/Article/details/gt2pdkxoxfh.html

Go:   a && b || !c
来源：http://dali.yj20258.top/Article/details/gt2vdllnoed.html

Ruby: a && b || !c
来源：http://dali.xylfe.cn/Article/details/gt2dntclgbb.html

C#:   a && b || !c
来源：http://dali.9152youxi.cn/Article/details/gt2psjdxncv.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.sweek.top/Article/details/gt2uyxqchnj.html

Py:   if not data: return
来源：http://dali.ppjwa.cn/Article/details/gt2wwyqoesy.html

PHP:  if (!$data) { return; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2rksjbjik.html

JS:   if (!data) return;
来源：http://dali.xylfe.cn/Article/details/gt2cokmvwyw.html

TS:   if (!data) return;
来源：http://dali.dianchejie.cn/Article/details/gt2azxpgrxc.html

Java: if (data == null) return;
来源：http://dali.zhengqikj.top/Article/details/gt2hqwuiquq.html

Go:   if data == nil { return }
来源：http://dali.gogol.net.cn/Article/details/gt2ydhniild.html

Ruby: return if data.nil?
来源：http://dali.snrcjt.cn/Article/details/gt2rvogazpj.html

C#:   if (data == null) return;
来源：http://dali.andypj.xyz/Article/details/gt2lqvwgpdt.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2pmekdsfv.html

C. 函数与作用域
来源：http://dali.chenzaomai.com/Article/details/gt2lsrixzfv.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2olgqlfsy.html

[C01] 定义函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iebppbvq.html

Py:   def add(a, b): return a + b
来源：http://dali.pycfn.com/Article/details/gt2wqkyrptq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangdashe.top/Article/details/gt2atrvtaul.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gt2phyzpvgu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gt2hcciemtp.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gt2ounfsjsl.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jianghu66.top/Article/details/gt2qkjkcplm.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zdqjudy.top/Article/details/gt2esbifext.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2bzlautec.html

[C02] 默认参数
来源：http://dali.yongpay.top/Article/details/gt2rmzwxwkg.html

Py:   def greet(name="World"): return name
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nchzwrji.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2xmzqwkhp.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2qbixhvkg.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.sweek.top/Article/details/gt2xgulbdkj.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.sysykeji.top/Article/details/gt2djuggmkf.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.fengsongda.top/Article/details/gt2axudxatl.html

Ruby: def greet(name = "World") = name
来源：http://dali.sufxvd.cn/Article/details/gt2wprebsxz.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yonumen.top/Article/details/gt2lqkmhlag.html

[C03] 可变参数
来源：http://dali.sweek.top/Article/details/gt2wneadunl.html

Py:   def total(*args): return sum(args)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vouiijfg.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.316326.xyz/Article/details/gt2mnmlwfnq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.snrcjt.cn/Article/details/gt2qsslrfbs.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yangfankeji.com/Article/details/gt2pdpecmhr.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.tianlin.xyz/Article/details/gt2htfgxwmi.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.haohaochexian.top/Article/details/gt2ynwbvnis.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ppjwa.cn/Article/details/gt2ktssvela.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.wangdashe.top/Article/details/gt2nknoklmv.html

[C04] 命名参数 / 关键字参数
来源：http://dali.guowangkeji.top/Article/details/gt2jpuizfsg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zycfv.cn/Article/details/gt2udoljbnq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.vqdsnc.cn/Article/details/gt2kkycmryu.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.meibo888.top/Article/details/gt2vbgzyett.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yueranfly.top/Article/details/gt2pjwiavja.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shzxlz.cn/Article/details/gt2jypduuwy.html

Go:   // 无：用配置结构体参数
来源：http://dali.shzxlz.cn/Article/details/gt2xkwpdgcv.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhixingplan.top/Article/details/gt2quufykuo.html

C#:   f(a: 1, b: 2)
来源：http://dali.jiagoushi.top/Article/details/gt2fcoqrmdl.html

[C05] 返回多个值
来源：http://dali.yuanzhike.top/Article/details/gt2svxwtkdv.html

Py:   return a, b
来源：http://dali.tanke756.top/Article/details/gt2rvuedzdg.html

PHP:  return [$a, $b];
来源：http://dali.sysykeji.top/Article/details/gt2ckidweao.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.sysykeji.top/Article/details/gt2ofunsgbb.html

TS:   return { a, b };
来源：http://dali.yangfankeji.com/Article/details/gt2tlrbklvc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jqgfzy.top/Article/details/gt2ocqpxdzg.html

Go:   return a, b
来源：http://dali.fzhhl.top/Article/details/gt2pdureghi.html

Ruby: return a, b
来源：http://dali.zhiwuduotai.top/Article/details/gt2ooczhzee.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hywenlv.cn/Article/details/gt2vytxpddl.html

[C06] 匿名函数 / lambda
来源：http://dali.jinqigufen.top/Article/details/gt2qlocbfih.html

Py:   square = lambda x: x * x
来源：http://dali.316326.xyz/Article/details/gt2kwpaedty.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ybcxt.top/Article/details/gt2xbrxmlqo.html

JS:   const square = x => x * x;
来源：http://dali.c1oappe.top/Article/details/gt2yuxwvenv.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.pengpengdd.cyou/Article/details/gt2cvtbpcpt.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jinqigufen.top/Article/details/gt2ktwsjvrb.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yj20258888.top/Article/details/gt2huvibahb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.vqdsnc.cn/Article/details/gt2rinyoqeq.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shuidangran.top/Article/details/gt2fgifpgse.html

[C07] 把函数作为参数传入
来源：http://dali.xuanzx.com/Article/details/gt2zgxhwerj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.quarkkingdee.top/Article/details/gt2lpwlbphc.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.meibo888.top/Article/details/gt2oywhkqpv.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jinqigfzy.top/Article/details/gt2knvoieas.html

TS:   arr.map(String)
来源：http://dali.nanxinkj.top/Article/details/gt2gtsbrefe.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhongyouzk.top/Article/details/gt2kmjxkdjc.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.wangdashe.top/Article/details/gt2dkgdnozn.html

Ruby: arr.map(&:upcase)
来源：http://dali.shangyingyoupin.top/Article/details/gt2eioenkdx.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aeiixvov.html

[C08] 闭包
来源：http://dali.chenjidiqi.icu/Article/details/gt2rleofzyy.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.dianchejie.cn/Article/details/gt2uovmhngw.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2tlszxzig.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.nanxinkj.top/Article/details/gt2wqwdtnqm.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jiagoushi.top/Article/details/gt2owcocdbg.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hfpthk.cn/Article/details/gt2qvuowenk.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yj202588.top/Article/details/gt2caprnldz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jqgufenzy.top/Article/details/gt2ytibknzf.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.dianchejie.cn/Article/details/gt2krvkmdww.html

[C09] 递归
来源：http://dali.jyoumei.cn/Article/details/gt2ikchlddt.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.vqdsnc.cn/Article/details/gt2ljsayitm.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.316326.xyz/Article/details/gt2zleeevle.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.redwolf501.top/Article/details/gt2qkaiwkqg.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2zimjptbc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.guannengcc.top/Article/details/gt2lgirydra.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.chenzaomai.com/Article/details/gt2tduawqdy.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.dianchejie.cn/Article/details/gt2samjxwbc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yj20258888.top/Article/details/gt2gmdjsjsd.html

[C10] 变量作用域
来源：http://dali.zhongyouzk.top/Article/details/gt2uzqxzaus.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.aibaodan.cn/Article/details/gt2sdtdeoyx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhixingplan.top/Article/details/gt2vyjoszbo.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jinqigfzy.top/Article/details/gt2wckpsslx.html

TS:   同 JS
来源：http://dali.yonumen.top/Article/details/gt2ezcbwteb.html

Java: 方法内为块级作用域
来源：http://dali.mhx1999.top/Article/details/gt2qetanryz.html

Go:   花括号块级作用域
来源：http://dali.haohaochexian.top/Article/details/gt2whsauvzl.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.vqdsnc.cn/Article/details/gt2sxxsifcd.html

C#:   块级作用域
来源：http://dali.snrcjt.cn/Article/details/gt2mvrfdaio.html

[C11] 模块导入与导出
来源：http://dali.jinqigufen.top/Article/details/gt2tojujxkj.html

Py:   from module import func
来源：http://dali.nanxinkj.top/Article/details/gt2gzeiwypw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.snrcjt.cn/Article/details/gt2fpjlpcad.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.havefunace.top/Article/details/gt2ulvjabxi.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rfohqldz.html

Java: import java.util.List;
来源：http://dali.quarkkingdee.top/Article/details/gt2iafurzec.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhoulong.xyz/Article/details/gt2tfpehxwb.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.feifeiyinyue.top/Article/details/gt2whdmxboi.html

C#:   using System.Text;
来源：http://dali.nwbrower.top/Article/details/gt2tlkdrjxt.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhongyouzk.top/Article/details/gt2fnjykkah.html

Py:   (lambda: print("run"))()
来源：http://dali.gaohongyu789.top/Article/details/gt2oaccvzjk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hywenlv.cn/Article/details/gt2objbekro.html

JS:   (() => { console.log("run"); })();
来源：http://dali.redwolf501.top/Article/details/gt2kwuwrvnz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.iojbl.cn/Article/details/gt2kzcyvlow.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.sysykeji.top/Article/details/gt2bvevfgcj.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yanxiufei.cn/Article/details/gt2xpybsfru.html

Ruby: -> { puts "run" }.call
来源：http://dali.cheryme.top/Article/details/gt2oyihnuks.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.snrcjt.cn/Article/details/gt2slngtovw.html

[C13] 类型声明 / 类型注解
来源：http://dali.tian-w.cn/Article/details/gt2aemslypq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hmziqihb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhixingplan.top/Article/details/gt2fxhyispn.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.gzhubu.top/Article/details/gt2qvfcyjco.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gt2qavugitn.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gt2pqcevmxh.html

Go:   func add(a, b int) int
来源：http://dali.tianlin.xyz/Article/details/gt2qkyvnztt.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.redwolf501.top/Article/details/gt2bnjmmjoh.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.aibaodan.cn/Article/details/gt2sdaoygoc.html

[C14] 泛型函数
来源：http://dali.ydzc1.top/Article/details/gt2buirqykn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yvedp.cn/Article/details/gt2soyvyyfd.html

PHP:  // 无泛型
来源：http://dali.daria6918.cn/Article/details/gt2weeuiajs.html

JS:   // 无泛型
来源：http://dali.sxryk.cn/Article/details/gt2nvgsttrs.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yuksovhh.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2kvwxmpgk.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.tianlin.xyz/Article/details/gt2zbdzalwx.html

Ruby: # 无泛型
来源：http://dali.chenlongwang.top/Article/details/gt2cnhjbvyh.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.chenjidiqi.icu/Article/details/gt2gcgrkppb.html

[C15] 解构 / 展开参数
来源：http://dali.tian-w.cn/Article/details/gt2pqekamoe.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2htegroey.html

PHP:  [$a, $b] = $pair;
来源：http://dali.guannengcc.top/Article/details/gt2cntiasng.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.redwolf501.top/Article/details/gt2qwvautug.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.haohaochexian.top/Article/details/gt2rntzawjd.html

Java: // 无解构
来源：http://dali.bjfxy.top/Article/details/gt2nhydsvvj.html

Go:   // 无解构
来源：http://dali.zycfv.cn/Article/details/gt2lygkttnv.html

Ruby: a, b = pair
来源：http://dali.0kj1m.cn/Article/details/gt2edztixko.html

C#:   var (a, b) = pair;
来源：http://dali.guowangkeji.top/Article/details/gt2lflxuxuw.html

[C16] 函数 / 方法重载
来源：http://dali.jiagoushi.top/Article/details/gt2unshdkem.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.kuanghao11.cn/Article/details/gt2kpkklbzm.html

PHP:  // 无重载
来源：http://dali.yvedp.cn/Article/details/gt2lypnfbhs.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.shangyingyoupin.top/Article/details/gt2vqwuaayb.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xziqi.cn/Article/details/gt2tbkqatao.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zdqjudy.top/Article/details/gt2ymnbbfag.html

Go:   // 无重载：用不同函数名
来源：http://dali.ehwqpu.com/Article/details/gt2kianucjx.html

Ruby: # 无重载：靠动态参数
来源：http://dali.smart0.xyz/Article/details/gt2bglwvsye.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.mhx1999.top/Article/details/gt2qdxgclzd.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2barnbmar.html

D. 数组 / 列表 / 集合
来源：http://dali.yvedp.cn/Article/details/gt2quljtyad.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2jbzbozyb.html

[D01] 创建数组 / 列表
来源：http://dali.zycfv.cn/Article/details/gt2hipcyxfj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.vqdsnc.cn/Article/details/gt2ilpqlrbg.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.sxryk.cn/Article/details/gt2tuhifruj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.vqdsnc.cn/Article/details/gt2bjqdgwrv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.iojbl.cn/Article/details/gt2jhtqpbne.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.c1oappe.top/Article/details/gt2ooeitmwl.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhoulong.xyz/Article/details/gt2nsmgkqpx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.tanke756.top/Article/details/gt2qhfomrug.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jiagoushi.top/Article/details/gt2lxathxcz.html

[D02] 追加元素到末尾
来源：http://dali.xziqi.cn/Article/details/gt2uyfrzrir.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aeetsawx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.wangdashe.top/Article/details/gt2imocgwky.html

JS:   arr.push(4);
来源：http://dali.hnxiangtu.top/Article/details/gt2mrfrfotu.html

TS:   arr.push(4);
来源：http://dali.jianghu66.top/Article/details/gt2xniqulpd.html

Java: list.add(4);
来源：http://dali.gotoacloud.top/Article/details/gt2ptsbjhkj.html

Go:   arr = append(arr, 4)
来源：http://dali.jinqigufen.top/Article/details/gt2wwglrcap.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jlsjyb.cn/Article/details/gt2egejgwjq.html

C#:   list.Add(4);
来源：http://dali.feifeiyinyue.top/Article/details/gt2qjxtkqgx.html

[D03] 在指定位置插入元素
来源：http://dali.xuetiantiany.cn/Article/details/gt2hvefaugg.html

Py:   arr.insert(0, 0)
来源：http://dali.cashguo.top/Article/details/gt2jyuxwanv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xgibccld.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.feifeiyinyue.top/Article/details/gt2suorwgim.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.smart0.xyz/Article/details/gt2dqvmojdj.html

Java: list.add(0, 0);
来源：http://dali.0kj1m.cn/Article/details/gt2mopapqij.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yangfankeji.com/Article/details/gt2ejfkodqa.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jqgufenzy.top/Article/details/gt2nwelzgkp.html

C#:   list.Insert(0, 0);
来源：http://dali.jqgufenzy.top/Article/details/gt2lolihfia.html

[D04] 删除元素
来源：http://dali.zdqjudy.top/Article/details/gt2junvzszp.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.kuanghao11.cn/Article/details/gt2mpqmqtkh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2urrbkakf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cdnleiting.top/Article/details/gt2poyrygan.html

TS:   arr.splice(0, 1);
来源：http://dali.hywenlv.cn/Article/details/gt2hcjmhldj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jinqigfzy.top/Article/details/gt2xqeibgev.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yuanzhike.top/Article/details/gt2xileppop.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jinqigufen.top/Article/details/gt2xsnyxjgl.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.mhx1999.top/Article/details/gt2prslczkg.html

[D05] 访问与修改元素
来源：http://dali.svipenyu.cn/Article/details/gt2schcbcbe.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258888.top/Article/details/gt2jlwiczry.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenlongwang.top/Article/details/gt2xbmapagp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yangfankeji.com/Article/details/gt2vpmxvugq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.haohaochexian.top/Article/details/gt2ydrqflpg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.sweek.top/Article/details/gt2zpqcjjhz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2tjzypyru.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jianghu66.top/Article/details/gt2jlqfzyov.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.redwolf501.top/Article/details/gt2iawredit.html

[D06] 数组长度
来源：http://dali.jlsjyb.cn/Article/details/gt2hxazkljr.html

Py:   len(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2srusxftf.html

PHP:  count($arr);
来源：http://dali.zdqjudy.top/Article/details/gt2lbnfmckp.html

JS:   arr.length
来源：http://dali.yanxiufei.cn/Article/details/gt2wxfdlsrh.html

TS:   arr.length
来源：http://dali.0kj1m.cn/Article/details/gt2fdwkpdwy.html

Java: list.size();
来源：http://dali.yj202588.top/Article/details/gt2tjcjvhno.html

Go:   len(arr)
来源：http://dali.shuidangran.top/Article/details/gt2buflorvf.html

Ruby: arr.length; arr.size
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2usbjldnc.html

C#:   list.Count;
来源：http://dali.hywenlv.cn/Article/details/gt2zayfccmk.html

[D07] 切片 / 取子数组
来源：http://dali.ybcxt.top/Article/details/gt2ikgorgqv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.havefunace.top/Article/details/gt2ttkeahgf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hnqzz.top/Article/details/gt2cbvykocy.html

JS:   arr.slice(1, 4);
来源：http://dali.jyoumei.cn/Article/details/gt2anmxlwpw.html

TS:   arr.slice(1, 4);
来源：http://dali.jiagoushi.top/Article/details/gt2nmlnuaej.html

Java: list.subList(1, 4);
来源：http://dali.xziqi.cn/Article/details/gt2bdupcgmq.html

Go:   arr[1:4]
来源：http://dali.meibo888.top/Article/details/gt2esdlfgya.html

Ruby: arr[1, 3]
来源：http://dali.jianghu66.top/Article/details/gt2xrznxlna.html

C#:   list.GetRange(1, 3);
来源：http://dali.pycfn.com/Article/details/gt2xitawucg.html

[D08] 合并两个数组
来源：http://dali.haohaochexian.top/Article/details/gt2htafokvc.html

Py:   a + b;  a.extend(b)
来源：http://dali.jiagoushi.top/Article/details/gt2ftuirbme.html

PHP:  array_merge($a, $b);
来源：http://dali.zycfv.cn/Article/details/gt2rrjhgppc.html


<!-- 参考信息 -->