代发 wailian999

Py:   # 无 do-while：用 while True + break
来源：http://dali.ehwqpu.com/Article/details/gtldjwkszx.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.xinyue.icu/Article/details/gtagezupnh.html

JS:   do { i++; } while (i < 10);
来源：http://dali.aibaodan.cn/Article/details/gtfiknqykn.html

TS:   do { i++; } while (i < 10);
来源：http://dali.nanxinkj.top/Article/details/gtecicdzzg.html

Java: do { i++; } while (i < 10);
来源：http://dali.wangshuangyany.cn/Article/details/gttpydrmkw.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.9152youxi.cn/Article/details/gtbcpnzrki.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.quarkkingdee.top/Article/details/gtysukcksm.html

C#:   do { i++; } while (i < 10);
来源：http://dali.xuetiantiany.cn/Article/details/gtwhahaakg.html

[B09] break 与 continue
来源：http://dali.hysaishi.cn/Article/details/gtmejdtuou.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.cqqwz.cn/Article/details/gtktjmfmzm.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.tianlin.xyz/Article/details/gtohnijqud.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnxiangtu.top/Article/details/gtqcdpdxqt.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hongshengwenyu.top/Article/details/gtfcguchqz.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hammf.cn/Article/details/gtbradadxt.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yueranfly.top/Article/details/gtcgxmzrra.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.redwolf501.top/Article/details/gttmoaanww.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgufenzy.top/Article/details/gtumqwftbm.html

[B10] 遍历同时拿索引
来源：http://dali.yueranfly.top/Article/details/gtircjtqas.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.svipenyu.cn/Article/details/gtftefwygx.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.hysaishi.cn/Article/details/gtvnvsutdk.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.shzxlz.cn/Article/details/gtsnahqqos.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhengqikj.top/Article/details/gtjxqiwzzg.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hfpthk.cn/Article/details/gtovuhivue.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.quarkkingdee.top/Article/details/gtplgnvisd.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jiagoushi.top/Article/details/gtzwldptfv.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.0kj1m.cn/Article/details/gtagdestsl.html

[B11] 生成数字序列 / 区间
来源：http://dali.9152youxi.cn/Article/details/gtbqfvyxcz.html

Py:   list(range(0, 10, 2))
来源：http://dali.bjfxy.top/Article/details/gtakrsmegj.html

PHP:  range(0, 10, 2);
来源：http://dali.shangyingyoupin.top/Article/details/gtxgozkjne.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.havefunace.top/Article/details/gtsrizbrrr.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hywenlv.cn/Article/details/gtgxiqwtzh.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.ydzc1.top/Article/details/gtqmyxkuok.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhengqikj.top/Article/details/gtmxefpzrq.html

Ruby: (0...10).step(2).to_a
来源：http://dali.c1oappe.top/Article/details/gtnyoqeiks.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.xinyue.icu/Article/details/gtwaanstvb.html

[B12] 跳出多层循环
来源：http://dali.jianghu66.top/Article/details/gtaqdvlstu.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.haohaochexian.top/Article/details/gtomsnkrqo.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.redwolf501.top/Article/details/gtltalnvna.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gthbhoylgl.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.quarkkingdee.top/Article/details/gtmwjorxgc.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.gotoacloud.top/Article/details/gtewgsklmz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.cqqwz.cn/Article/details/gtkcovblfs.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.bjfxy.top/Article/details/gtfhgcbolf.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxrnwbizj.html

[B13] 判断是否为数字
来源：http://dali.hysaishi.cn/Article/details/gtevbtvvfb.html

Py:   isinstance(x, (int, float))
来源：http://dali.iojbl.cn/Article/details/gteyeonvha.html

PHP:  is_numeric($x)
来源：http://dali.cheryme.top/Article/details/gtkfrmvsbe.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj20258.top/Article/details/gtssqnofnp.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.fengsongda.top/Article/details/gtauwqkkub.html

Java: x instanceof Number
来源：http://dali.ywan-chungtsiang.top/Article/details/gtesgqamnk.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hnxiangtu.top/Article/details/gtmtdhoolv.html

Ruby: x.is_a?(Numeric)
来源：http://dali.wangshuangyany.cn/Article/details/gtorlwemak.html

C#:   x is int or double or decimal
来源：http://dali.gzhubu.top/Article/details/gtphvdvvqt.html

[B14] 判断值是否在集合内
来源：http://dali.kuanghao11.cn/Article/details/gtnwvmfujg.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.chenzaomai.com/Article/details/gtxlstwedp.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.xuetiantiany.cn/Article/details/gtcittwbea.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yonumen.top/Article/details/gtiypapcpj.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrgdggbnd.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.shuidangran.top/Article/details/gtlnrdtikq.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.guannengcc.top/Article/details/gtbyaomcam.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.svipenyu.cn/Article/details/gtmkicxick.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ppjwa.cn/Article/details/gtxwsrakck.html

[B15] 布尔运算与取反
来源：http://dali.tanke756.top/Article/details/gttctxetxp.html

Py:   a and b or not c
来源：http://dali.nwbrower.top/Article/details/gtdlabnpud.html

PHP:  $a && $b || !$c
来源：http://dali.haohaochexian.top/Article/details/gtmywlxyqq.html

JS:   a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gtpfpxweyr.html

TS:   a && b || !c
来源：http://dali.yj20258888.top/Article/details/gtcxkrcziw.html

Java: a && b || !c
来源：http://dali.zycfv.cn/Article/details/gtgrixfrzd.html

Go:   a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gtdbzyrbpf.html

Ruby: a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gtfzudyyby.html

C#:   a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gtfvbsjast.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ybcxt.top/Article/details/gtycmtwhvs.html

Py:   if not data: return
来源：http://dali.ydzc1.top/Article/details/gtfmxedcwe.html

PHP:  if (!$data) { return; }
来源：http://dali.hnqzz.top/Article/details/gtkwnmpqxr.html

JS:   if (!data) return;
来源：http://dali.shangyingyoupin.top/Article/details/gtbickviiq.html

TS:   if (!data) return;
来源：http://dali.yongpay.top/Article/details/gtgqlpivpb.html

Java: if (data == null) return;
来源：http://dali.chenjidiqi.icu/Article/details/gtfopnwsls.html

Go:   if data == nil { return }
来源：http://dali.c1oappe.top/Article/details/gthljbeuam.html

Ruby: return if data.nil?
来源：http://dali.zhixingplan.top/Article/details/gthyflknus.html

C#:   if (data == null) return;
来源：http://dali.jianghu66.top/Article/details/gtvjiiwelr.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtjaireode.html

C. 函数与作用域
来源：http://dali.xylfe.cn/Article/details/gtlortsdpf.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtteqtdrwv.html

[C01] 定义函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqitmacju.html

Py:   def add(a, b): return a + b
来源：http://dali.0kj1m.cn/Article/details/gtfuduqfjj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkwyesgwo.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gttxfxeyor.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gtcwopgnvf.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.pycfn.com/Article/details/gtkhnmvkmh.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.wangshuangyany.cn/Article/details/gtenaawupv.html

Ruby: def add(a, b); a + b; end
来源：http://dali.tanke756.top/Article/details/gtdmpxywsp.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gtqhylsskd.html

[C02] 默认参数
来源：http://dali.meibo888.top/Article/details/gtagumqmpq.html

Py:   def greet(name="World"): return name
来源：http://dali.cheryme.top/Article/details/gtstihwfdp.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwzkdupxs.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gtsgqgehrj.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yvedp.cn/Article/details/gtpnwxcpde.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.fengsongda.top/Article/details/gtttcghadp.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.sxryk.cn/Article/details/gtnzvriuen.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhiwuduotai.top/Article/details/gttqsmlanc.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jiagoushi.top/Article/details/gtshnjpeep.html

[C03] 可变参数
来源：http://dali.pengpengdd.cyou/Article/details/gtebdgypuo.html

Py:   def total(*args): return sum(args)
来源：http://dali.tianlin.xyz/Article/details/gthswkoniz.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.snrcjt.cn/Article/details/gtmlybfkxd.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yangfankeji.com/Article/details/gtxrigrdti.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yvedp.cn/Article/details/gtifbgpgvj.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.daria6918.cn/Article/details/gthuykhlfc.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.wangdashe.top/Article/details/gtgbmncyrs.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.tian-w.cn/Article/details/gttqnjncch.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cucudq.cn/Article/details/gtthoycddl.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zdqjudy.top/Article/details/gtdflvxnge.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ivvv.top/Article/details/gtlujhfjkn.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hnqzz.top/Article/details/gtafupsdwc.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtfcehnoob.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.sxryk.cn/Article/details/gtfxziqsft.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zdqjudy.top/Article/details/gtykwfymtj.html

Go:   // 无：用配置结构体参数
来源：http://dali.andypj.xyz/Article/details/gtittfhlwv.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiutlaghy.html

C#:   f(a: 1, b: 2)
来源：http://dali.svipenyu.cn/Article/details/gtxgtfzviz.html

[C05] 返回多个值
来源：http://dali.jqgufenzy.top/Article/details/gtaybgxxdy.html

Py:   return a, b
来源：http://dali.yj20258.top/Article/details/gtqybtnxzz.html

PHP:  return [$a, $b];
来源：http://dali.chenlongwang.top/Article/details/gthtrqxmlb.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.sxryk.cn/Article/details/gtadukawhc.html

TS:   return { a, b };
来源：http://dali.feifeiyinyue.top/Article/details/gtwraegqdx.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yj20258888.top/Article/details/gtydnjhghe.html

Go:   return a, b
来源：http://dali.zdqjudy.top/Article/details/gtutijlbed.html

Ruby: return a, b
来源：http://dali.yueranfly.top/Article/details/gtnrjvnxtj.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ydzc1.top/Article/details/gtlqsidzqg.html

[C06] 匿名函数 / lambda
来源：http://dali.yj20258.top/Article/details/gtkdxvlirk.html

Py:   square = lambda x: x * x
来源：http://dali.chenjidiqi.icu/Article/details/gtksllrwhl.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.sweek.top/Article/details/gtnrqfutvy.html

JS:   const square = x => x * x;
来源：http://dali.aizwys.cn/Article/details/gtxbrhxcuu.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.meibo888.top/Article/details/gtprjptvrx.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.tianlin.xyz/Article/details/gtsgmiuoke.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.fengsongda.top/Article/details/gtrdihaeqj.html

Ruby: square = ->(x) { x * x }
来源：http://dali.9152youxi.cn/Article/details/gtgmwbzwmc.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhiwuduotai.top/Article/details/gtfsxdrcbc.html

[C07] 把函数作为参数传入
来源：http://dali.zhixingplan.top/Article/details/gtzllvhcff.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.guannengcc.top/Article/details/gtfbsagrkd.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.0kj1m.cn/Article/details/gtxkqkigec.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hywenlv.cn/Article/details/gtmyqyirrs.html

TS:   arr.map(String)
来源：http://dali.chenzaomai.com/Article/details/gteecixftl.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yuanzhike.top/Article/details/gtvtijwnrw.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jinghuilouyu.cn/Article/details/gtyjhavmdc.html

Ruby: arr.map(&:upcase)
来源：http://dali.shzxlz.cn/Article/details/gttqbfczlp.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.sweek.top/Article/details/gtxttnwofu.html

[C08] 闭包
来源：http://dali.dianchejie.cn/Article/details/gtbpeyetot.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xinyue.icu/Article/details/gtwgmpxppd.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.birdmap.top/Article/details/gthouskkxo.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hongshengwenyu.top/Article/details/gtujfntavt.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ehwqpu.com/Article/details/gtgmxpffqr.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.fzhhl.top/Article/details/gtylpuskcd.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yj20258.top/Article/details/gtkjltgeyc.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hnqzz.top/Article/details/gthwglvuvf.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhengqikj.top/Article/details/gtnzhgcfng.html

[C09] 递归
来源：http://dali.gogol.net.cn/Article/details/gtdljpdnea.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.sufxvd.cn/Article/details/gtyrveutrk.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhixingplan.top/Article/details/gtfrvoyxqw.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yuxming.cn/Article/details/gtmnnyilat.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tianlin.xyz/Article/details/gtaybtcznu.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcductril.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yuanzhike.top/Article/details/gtzftupijo.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.havefunace.top/Article/details/gtoqsycqry.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.svipenyu.cn/Article/details/gtlmivvoyn.html

[C10] 变量作用域
来源：http://dali.hnqzz.top/Article/details/gtrrlxvtgz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.sweek.top/Article/details/gtegmmcdqg.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cashguo.top/Article/details/gtonodehei.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.shuidangran.top/Article/details/gtpfpyuqef.html

TS:   同 JS
来源：http://dali.iojbl.cn/Article/details/gtlwncfbjm.html

Java: 方法内为块级作用域
来源：http://dali.chenlongwang.top/Article/details/gtmkrbtwns.html

Go:   花括号块级作用域
来源：http://dali.haohaochexian.top/Article/details/gtwvkmgobd.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.nwbrower.top/Article/details/gtnnikobkj.html

C#:   块级作用域
来源：http://dali.tanke756.top/Article/details/gtvetkkzae.html

[C11] 模块导入与导出
来源：http://dali.fzhhl.top/Article/details/gtxkixkfvi.html

Py:   from module import func
来源：http://dali.yuxming.cn/Article/details/gtjcqoosfk.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.0kj1m.cn/Article/details/gtsykqfpmp.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.sxryk.cn/Article/details/gtjnvpimmh.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hongshengwenyu.top/Article/details/gtppuniauw.html

Java: import java.util.List;
来源：http://dali.zdqjudy.top/Article/details/gtgznsdtle.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cucudq.cn/Article/details/gtniahxocl.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yangfankeji.com/Article/details/gtvkmtyewj.html

C#:   using System.Text;
来源：http://dali.zhongyouzk.top/Article/details/gttgodrljv.html

[C12] 立即执行函数 IIFE
来源：http://dali.pycfn.com/Article/details/gtnrlsexnp.html

Py:   (lambda: print("run"))()
来源：http://dali.ybcxt.top/Article/details/gtfxemwxuy.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhaomingkeji.xyz/Article/details/gttpzquujf.html

JS:   (() => { console.log("run"); })();
来源：http://dali.dianchejie.cn/Article/details/gtpdstrihq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jinqigufen.top/Article/details/gtphcfulla.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.fzhhl.top/Article/details/gtveyzgcuq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hongshengwenyu.top/Article/details/gtdtlbvzqh.html

Ruby: -> { puts "run" }.call
来源：http://dali.hnqzz.top/Article/details/gtjezupowm.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yj202588.top/Article/details/gtimxoyrof.html

[C13] 类型声明 / 类型注解
来源：http://dali.sweek.top/Article/details/gtubklanlq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jqgfzy.top/Article/details/gtgioiuhbp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hfpthk.cn/Article/details/gtidthggde.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ybcxt.top/Article/details/gtvstrlnfe.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gttaqulgpq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gtktymeeom.html

Go:   func add(a, b int) int
来源：http://dali.birdmap.top/Article/details/gthznwctjs.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hongshengwenyu.top/Article/details/gtauvjvdhg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.tanke756.top/Article/details/gtynupnrbc.html

[C14] 泛型函数
来源：http://dali.zhongyouzk.top/Article/details/gtigozrexp.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.tanke756.top/Article/details/gtqufvonex.html

PHP:  // 无泛型
来源：http://dali.yonumen.top/Article/details/gtuskqyftr.html

JS:   // 无泛型
来源：http://dali.ehwqpu.com/Article/details/gtvghhrujd.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ehwqpu.com/Article/details/gtlrvhtftf.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xylfe.cn/Article/details/gtgpvazasf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hammf.cn/Article/details/gtcepbxcil.html

Ruby: # 无泛型
来源：http://dali.haohaochexian.top/Article/details/gtffwzcthh.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.redwolf501.top/Article/details/gtpdsotjaz.html

[C15] 解构 / 展开参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtrqnoaxli.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.sysykeji.top/Article/details/gtbodxakcw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yj202588.top/Article/details/gtvlgfoojk.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpwglnstn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.wangdashe.top/Article/details/gtjqfwqxtq.html

Java: // 无解构
来源：http://dali.jinghuilouyu.cn/Article/details/gtcixvfdeh.html

Go:   // 无解构
来源：http://dali.zycfv.cn/Article/details/gtgsmrttqi.html

Ruby: a, b = pair
来源：http://dali.zhoulong.xyz/Article/details/gtkpyejaqv.html

C#:   var (a, b) = pair;
来源：http://dali.yonumen.top/Article/details/gtfhdpykwq.html

[C16] 函数 / 方法重载
来源：http://dali.hfpthk.cn/Article/details/gtbnupxmhn.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.feifeiyinyue.top/Article/details/gttxuoiqbk.html

PHP:  // 无重载
来源：http://dali.hfpthk.cn/Article/details/gtndfjfesn.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhiwuduotai.top/Article/details/gtovpyoshr.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shuidangran.top/Article/details/gtfnkidjqv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.tianlin.xyz/Article/details/gtyortramj.html

Go:   // 无重载：用不同函数名
来源：http://dali.c1oappe.top/Article/details/gtqrmxzmel.html

Ruby: # 无重载：靠动态参数
来源：http://dali.nanxuanxn.top/Article/details/gtevvawaic.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.9152youxi.cn/Article/details/gtnxknsldv.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtwairgbjm.html

D. 数组 / 列表 / 集合
来源：http://dali.mhx1999.top/Article/details/gtyhzgxbpn.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtvvbpsxlk.html

[D01] 创建数组 / 列表
来源：http://dali.dianchejie.cn/Article/details/gtnauzttyi.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.haohaochexian.top/Article/details/gtdimtbgtm.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cdnleiting.top/Article/details/gtyctlsbch.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cashguo.top/Article/details/gtdvvhuxmi.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yonumen.top/Article/details/gtzhivreuq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yuxming.cn/Article/details/gtihdtdrnd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.quarkkingdee.top/Article/details/gtsulgvhrp.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cqqwz.cn/Article/details/gtxpjnwdxo.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.c1oappe.top/Article/details/gtekyqxdfg.html

[D02] 追加元素到末尾
来源：http://dali.yuxming.cn/Article/details/gtrgpthduo.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.aibaodan.cn/Article/details/gtnfmhqasr.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ybcxt.top/Article/details/gtqnzemwuc.html

JS:   arr.push(4);
来源：http://dali.tianlin.xyz/Article/details/gtliwhprdr.html

TS:   arr.push(4);
来源：http://dali.hnqzz.top/Article/details/gtovaaimwt.html

Java: list.add(4);
来源：http://dali.nanxuanxn.top/Article/details/gtfvizurvm.html

Go:   arr = append(arr, 4)
来源：http://dali.gaohongyu789.top/Article/details/gtfndayyhs.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yanxiufei.cn/Article/details/gtcpoymcpl.html

C#:   list.Add(4);
来源：http://dali.smart0.xyz/Article/details/gtdjnnsajx.html

[D03] 在指定位置插入元素
来源：http://dali.zhixingplan.top/Article/details/gtxwibmemq.html

Py:   arr.insert(0, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtweirmxbx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhengqikj.top/Article/details/gtjgycilhf.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ydzc1.top/Article/details/gtmngufubw.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.guowangkeji.top/Article/details/gtwvsdvrln.html

Java: list.add(0, 0);
来源：http://dali.yj20258.top/Article/details/gtqojnzncl.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gtalgrubmm.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhixingplan.top/Article/details/gtgawqegaj.html

C#:   list.Insert(0, 0);
来源：http://dali.jianghu66.top/Article/details/gtaoxfumil.html

[D04] 删除元素
来源：http://dali.ybcxt.top/Article/details/gtossnnqbp.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hfpthk.cn/Article/details/gtfhtcytpw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yueranfly.top/Article/details/gteptzmkmu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.svipenyu.cn/Article/details/gtyzikkbtd.html

TS:   arr.splice(0, 1);
来源：http://dali.meibo888.top/Article/details/gtnrqejhjp.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yj20258888.top/Article/details/gtlnghablo.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yuanzhike.top/Article/details/gtgfclsuch.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jqgfzy.top/Article/details/gtacbxzaay.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.andypj.xyz/Article/details/gtsdlpgwkv.html

[D05] 访问与修改元素
来源：http://dali.316326.xyz/Article/details/gtcoyaoigw.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.bjfxy.top/Article/details/gtftjvkqnt.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhongyouzk.top/Article/details/gtbgnddvux.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.svipenyu.cn/Article/details/gtpmgegdhf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.dashuyun.cn/Article/details/gtpboepiip.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.svipenyu.cn/Article/details/gtmirijctw.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.redwolf501.top/Article/details/gtjrelxgga.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yueranfly.top/Article/details/gtvawbyqos.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinqigfzy.top/Article/details/gtwiznlwwy.html

[D06] 数组长度
来源：http://dali.zhongyouzk.top/Article/details/gtqeelzsyb.html

Py:   len(arr)
来源：http://dali.sysykeji.top/Article/details/gtelopgeqh.html

PHP:  count($arr);
来源：http://dali.ehwqpu.com/Article/details/gtullifjvn.html

JS:   arr.length
来源：http://dali.yongpay.top/Article/details/gthlxtpzwn.html

TS:   arr.length
来源：http://dali.sxryk.cn/Article/details/gtlmwxafur.html

Java: list.size();
来源：http://dali.xziqi.cn/Article/details/gtvuhcrdgc.html

Go:   len(arr)
来源：http://dali.yvedp.cn/Article/details/gtwwwewxui.html

Ruby: arr.length; arr.size
来源：http://dali.c1oappe.top/Article/details/gtgxwleucl.html

C#:   list.Count;
来源：http://dali.gzhubu.top/Article/details/gtkrnnqyir.html

[D07] 切片 / 取子数组
来源：http://dali.gzhubu.top/Article/details/gtlaoqtadg.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.birdmap.top/Article/details/gtzoqzexov.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cashguo.top/Article/details/gtupijzwqu.html

JS:   arr.slice(1, 4);
来源：http://dali.iojbl.cn/Article/details/gtyvpsvkgt.html

TS:   arr.slice(1, 4);
来源：http://dali.zhiwuduotai.top/Article/details/gtwrrahgry.html

Java: list.subList(1, 4);
来源：http://dali.jinqigfzy.top/Article/details/gtbgkwyufo.html

Go:   arr[1:4]
来源：http://dali.daxiang520.top/Article/details/gtkianvobh.html

Ruby: arr[1, 3]
来源：http://dali.cqqwz.cn/Article/details/gtlzavxkcg.html

C#:   list.GetRange(1, 3);
来源：http://dali.xinyue.icu/Article/details/gtesedjekr.html

[D08] 合并两个数组
来源：http://dali.cashguo.top/Article/details/gtnkqynjaa.html

Py:   a + b;  a.extend(b)
来源：http://dali.c1oappe.top/Article/details/gtqotumaki.html

PHP:  array_merge($a, $b);
来源：http://dali.ybcxt.top/Article/details/gtflhbufkd.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.dashuyun.cn/Article/details/gtmjpqekcw.html

TS:   [...a, ...b];
来源：http://dali.meibo888.top/Article/details/gtnpnqipdo.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.0kj1m.cn/Article/details/gtgudiidhs.html

Go:   append(a, b...)
来源：http://dali.yvedp.cn/Article/details/gtdageaddu.html


<!-- 参考信息 -->