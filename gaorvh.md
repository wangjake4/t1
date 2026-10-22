代发 wailian999

PHP:  (function () { echo "run"; })();
来源：http://dali.sweek.top/Article/details/gtitcigttt.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnswgkzgy.html

TS:   (() => { console.log("run"); })();
来源：http://dali.gaohongyu789.top/Article/details/gtgnnnoboz.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yanxiufei.cn/Article/details/gtoygcndau.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.sweek.top/Article/details/gtoczddsdw.html

Ruby: -> { puts "run" }.call
来源：http://dali.fengsongda.top/Article/details/gtyoszpokc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.wangdashe.top/Article/details/gtkcexmklq.html

[C13] 类型声明 / 类型注解
来源：http://dali.svipenyu.cn/Article/details/gtyucxvuha.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hysaishi.cn/Article/details/gtstrrekgs.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hywenlv.cn/Article/details/gtvhmupsco.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xziqi.cn/Article/details/gtatmocldy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtxvynqimh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gteumyqmws.html

Go:   func add(a, b int) int
来源：http://dali.ehwqpu.com/Article/details/gtycukgthg.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hywenlv.cn/Article/details/gtpycaotne.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.shzxlz.cn/Article/details/gtsuzunjse.html

[C14] 泛型函数
来源：http://dali.yanxiufei.cn/Article/details/gtgbsmbtqm.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.sufxvd.cn/Article/details/gtjvcgfrpb.html

PHP:  // 无泛型
来源：http://dali.aizwys.cn/Article/details/gtpdicftnt.html

JS:   // 无泛型
来源：http://dali.hywenlv.cn/Article/details/gtgrdthdxb.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.cdnleiting.top/Article/details/gtizxinggp.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.kuanghao11.cn/Article/details/gtcbkddxee.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.gaohongyu789.top/Article/details/gtrcapkjnv.html

Ruby: # 无泛型
来源：http://dali.jinqigfzy.top/Article/details/gtiuyrgtyk.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtprkxxows.html

[C15] 解构 / 展开参数
来源：http://dali.yonumen.top/Article/details/gtdciajsho.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.kuanghao11.cn/Article/details/gtnodrughs.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yj202588.top/Article/details/gtsmonfdmi.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.meibo888.top/Article/details/gtdpstmdsf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.meibo888.top/Article/details/gttgnmkztw.html

Java: // 无解构
来源：http://dali.hnqzz.top/Article/details/gtmkqrklir.html

Go:   // 无解构
来源：http://dali.jlsjyb.cn/Article/details/gttmywrdqa.html

Ruby: a, b = pair
来源：http://dali.meibo888.top/Article/details/gtirnmlied.html

C#:   var (a, b) = pair;
来源：http://dali.chenzaomai.com/Article/details/gtvkkaqkde.html

[C16] 函数 / 方法重载
来源：http://dali.shuidangran.top/Article/details/gtxdplfagk.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yanxiufei.cn/Article/details/gtfolxrwin.html

PHP:  // 无重载
来源：http://dali.nanxinkj.top/Article/details/gtxsjdcvut.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.wangdashe.top/Article/details/gtyhiwiaud.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jlsjyb.cn/Article/details/gtrlnzjrba.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.guowangkeji.top/Article/details/gtsonkaskv.html

Go:   // 无重载：用不同函数名
来源：http://dali.yj20258.top/Article/details/gtftnwoydr.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jlsjyb.cn/Article/details/gtkowzdbam.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yj20258888.top/Article/details/gtdfftynxd.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzcjxnesi.html

D. 数组 / 列表 / 集合
来源：http://dali.jlsjyb.cn/Article/details/gthkqsgxxz.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtlivthjoo.html

[D01] 创建数组 / 列表
来源：http://dali.guannengcc.top/Article/details/gtezkttwjw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.birdmap.top/Article/details/gtktcloamj.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.tianlin.xyz/Article/details/gtlsedijoa.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yj20258.top/Article/details/gtyuewdjdv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ivvv.top/Article/details/gthozhvzat.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.havefunace.top/Article/details/gtmphwpuim.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jqgufenzy.top/Article/details/gtratlxqet.html

Ruby: arr = [1, 2, 3]
来源：http://dali.chenlongwang.top/Article/details/gtnmqyjcyh.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xylfe.cn/Article/details/gtutyxwagi.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gtnmwurpun.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhengqikj.top/Article/details/gtsveezmay.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jqgufenzy.top/Article/details/gtuxbbaspy.html

JS:   arr.push(4);
来源：http://dali.zdqjudy.top/Article/details/gtkabzcohm.html

TS:   arr.push(4);
来源：http://dali.xuanzx.com/Article/details/gtyhbnsycb.html

Java: list.add(4);
来源：http://dali.yj20258888.top/Article/details/gtephdpxqo.html

Go:   arr = append(arr, 4)
来源：http://dali.nanxuanxn.top/Article/details/gtzqwhlknr.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shuidangran.top/Article/details/gtoiyxotbc.html

C#:   list.Add(4);
来源：http://dali.xziqi.cn/Article/details/gtchwgybzh.html

[D03] 在指定位置插入元素
来源：http://dali.jqgufenzy.top/Article/details/gtuexipiia.html

Py:   arr.insert(0, 0)
来源：http://dali.cheryme.top/Article/details/gtymtkitpr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hammf.cn/Article/details/gttfuetmer.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.wangdashe.top/Article/details/gtopjfvqjp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yuanzhike.top/Article/details/gteqytxgrd.html

Java: list.add(0, 0);
来源：http://dali.hammf.cn/Article/details/gtzufqpmut.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yj20258888.top/Article/details/gtclaadarc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.tian-w.cn/Article/details/gthhbnlsxv.html

C#:   list.Insert(0, 0);
来源：http://dali.gogol.net.cn/Article/details/gtfbxdksor.html

[D04] 删除元素
来源：http://dali.zhongyouzk.top/Article/details/gtbxzfpjcq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.chenjidiqi.icu/Article/details/gtgsgofhbk.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yuxming.cn/Article/details/gtcugebugo.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.wangshuangyany.cn/Article/details/gtpcwtuqiy.html

TS:   arr.splice(0, 1);
来源：http://dali.hfpthk.cn/Article/details/gtvqpttjln.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gthcuiaxlz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.c1oappe.top/Article/details/gtbdmctozs.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtpwhxxtte.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sxryk.cn/Article/details/gtqeigymff.html

[D05] 访问与修改元素
来源：http://dali.ydzc1.top/Article/details/gtznkgondk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnqzz.top/Article/details/gtierueups.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtezbfqhye.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jinqigufen.top/Article/details/gtelwnfkvs.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.bjfxy.top/Article/details/gtmbtalmbz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yj202588.top/Article/details/gttlnwdgoe.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.mhx1999.top/Article/details/gtovezklez.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tianlin.xyz/Article/details/gturiidgls.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.aizwys.cn/Article/details/gttjuaqejq.html

[D06] 数组长度
来源：http://dali.havefunace.top/Article/details/gtoxjyspts.html

Py:   len(arr)
来源：http://dali.fzhhl.top/Article/details/gtualqcvrq.html

PHP:  count($arr);
来源：http://dali.hammf.cn/Article/details/gthgruhabq.html

JS:   arr.length
来源：http://dali.jqgfzy.top/Article/details/gtymidnkwl.html

TS:   arr.length
来源：http://dali.xziqi.cn/Article/details/gtyftpcxpi.html

Java: list.size();
来源：http://dali.xziqi.cn/Article/details/gtzooursrh.html

Go:   len(arr)
来源：http://dali.snrcjt.cn/Article/details/gtwmbvpuyz.html

Ruby: arr.length; arr.size
来源：http://dali.yj20258.top/Article/details/gtufslwsev.html

C#:   list.Count;
来源：http://dali.wangshuangyany.cn/Article/details/gtufoluqsu.html

[D07] 切片 / 取子数组
来源：http://dali.yonumen.top/Article/details/gthyahcwpp.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ydzc1.top/Article/details/gtbyqesrgw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.dianchejie.cn/Article/details/gtnldivvcb.html

JS:   arr.slice(1, 4);
来源：http://dali.hfpthk.cn/Article/details/gtbkgcwkfu.html

TS:   arr.slice(1, 4);
来源：http://dali.bjfxy.top/Article/details/gtadkwhzqm.html

Java: list.subList(1, 4);
来源：http://dali.zdqjudy.top/Article/details/gtimjwxbsx.html

Go:   arr[1:4]
来源：http://dali.shanyushiyangtech.top/Article/details/gtbtvuyvdx.html

Ruby: arr[1, 3]
来源：http://dali.yvedp.cn/Article/details/gtfbxpamlm.html

C#:   list.GetRange(1, 3);
来源：http://dali.yj202588.top/Article/details/gtkyradmqp.html

[D08] 合并两个数组
来源：http://dali.ydzc1.top/Article/details/gtcdnwycjp.html

Py:   a + b;  a.extend(b)
来源：http://dali.xuanzx.com/Article/details/gtmgfgyesp.html

PHP:  array_merge($a, $b);
来源：http://dali.redwolf501.top/Article/details/gtwagulhir.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cdnleiting.top/Article/details/gtegibvnht.html

TS:   [...a, ...b];
来源：http://dali.daria6918.cn/Article/details/gtubzmkrws.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.wangdashe.top/Article/details/gtvgmlymak.html

Go:   append(a, b...)
来源：http://dali.quarkkingdee.top/Article/details/gtmxigcxiu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.smart0.xyz/Article/details/gtensqppuh.html

C#:   a.Concat(b).ToList()
来源：http://dali.zdqjudy.top/Article/details/gteljznihs.html

[D09] 排序（升序）
来源：http://dali.guowangkeji.top/Article/details/gtqsspqrld.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.snrcjt.cn/Article/details/gtpdrygnmh.html

PHP:  sort($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtybqbkpiq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmvxhsslw.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hysaishi.cn/Article/details/gthepzlggb.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gaohongyu789.top/Article/details/gtyorhavxq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhixingplan.top/Article/details/gtfgybvafk.html

Ruby: arr.sort
来源：http://dali.aibaodan.cn/Article/details/gtftqltbtg.html

C#:   list.Sort();
来源：http://dali.chenlongwang.top/Article/details/gtoefvbqut.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.nanxinkj.top/Article/details/gtzncvqlhu.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.tian-w.cn/Article/details/gtmwtdsgqu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cucudq.cn/Article/details/gtndzbjruz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tianlin.xyz/Article/details/gtuhmreheh.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jyoumei.cn/Article/details/gtwzehedgk.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.andypj.xyz/Article/details/gtxwmrlsuy.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.pycfn.com/Article/details/gtjkefmwtu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.tianlin.xyz/Article/details/gtgdaqaxky.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shangyingyoupin.top/Article/details/gtiaugetlo.html

[D11] 反转数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdyhdrywt.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.fzhhl.top/Article/details/gtxwwxiclu.html

PHP:  array_reverse($arr);
来源：http://dali.cashguo.top/Article/details/gtjsmjjlpi.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hfpthk.cn/Article/details/gtvcosfanf.html

TS:   [...arr].reverse();
来源：http://dali.zhiwuduotai.top/Article/details/gtmhccozng.html

Java: Collections.reverse(list);
来源：http://dali.zhiwuduotai.top/Article/details/gtwogyojli.html

Go:   slices.Reverse(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtqapswprw.html

Ruby: arr.reverse
来源：http://dali.chenjidiqi.icu/Article/details/gtafqhirxa.html

C#:   list.Reverse();
来源：http://dali.chenzaomai.com/Article/details/gtteoajwuy.html

[D12] 查找元素下标
来源：http://dali.tian-w.cn/Article/details/gtoykvvoip.html

Py:   arr.index(x);  x in arr
来源：http://dali.yanxiufei.cn/Article/details/gtxbouhufq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.nanxinkj.top/Article/details/gtwgglprbw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gtsnzwxcll.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aibaodan.cn/Article/details/gtrurtcmyr.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.mhx1999.top/Article/details/gtnnpzglzb.html

Go:   slices.Index(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gthmqhflvy.html

Ruby: arr.index(x)
来源：http://dali.shzxlz.cn/Article/details/gtuvxvnuex.html

C#:   list.IndexOf(x);
来源：http://dali.yangfankeji.com/Article/details/gtcyzngldn.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hammf.cn/Article/details/gthnjekzwg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.fengsongda.top/Article/details/gtdvqpfvof.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtqoamzqpx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jianghu66.top/Article/details/gtoqknotdu.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jinqigfzy.top/Article/details/gtmebzwipa.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gthqmbwnse.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shangyingyoupin.top/Article/details/gtchwjrgxm.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ybcxt.top/Article/details/gtzjzzgsru.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shuidangran.top/Article/details/gtbajocwhu.html

[D14] 映射转换（每个元素变形）
来源：http://dali.sufxvd.cn/Article/details/gtbzmeslca.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.aizwys.cn/Article/details/gtbzmkesua.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhixingplan.top/Article/details/gtomdqssyp.html

JS:   arr.map(x => x * 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtkeqvizzq.html

TS:   arr.map(x => x * 2)
来源：http://dali.vqdsnc.cn/Article/details/gtwjgrfgoc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtlyfiupso.html

Go:   // 手写循环
来源：http://dali.316326.xyz/Article/details/gtzdvfioei.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yvedp.cn/Article/details/gtlwffzmaj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xuanzx.com/Article/details/gtfoxangau.html

[D15] 去重
来源：http://dali.nwbrower.top/Article/details/gtfspofozb.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xylfe.cn/Article/details/gttoehfekz.html

PHP:  array_unique($arr);
来源：http://dali.pycfn.com/Article/details/gtgjdzdpwg.html

JS:   [...new Set(arr)]
来源：http://dali.jinghuilouyu.cn/Article/details/gtkoshuydp.html

TS:   [...new Set(arr)]
来源：http://dali.havefunace.top/Article/details/gtpjgshzwr.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.havefunace.top/Article/details/gtnqobffti.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.meibo888.top/Article/details/gthggyczgr.html

Ruby: arr.uniq
来源：http://dali.cheryme.top/Article/details/gtffenkggz.html

C#:   list.Distinct().ToList()
来源：http://dali.shzxlz.cn/Article/details/gtrhkvcasd.html

[D16] 求和与平均值
来源：http://dali.yj202588.top/Article/details/gtrbbfhvwa.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.wangdashe.top/Article/details/gteskempmd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.pycfn.com/Article/details/gtlsuvniyt.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xziqi.cn/Article/details/gtlztdeyoe.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.smart0.xyz/Article/details/gtbfernbxr.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.chenlongwang.top/Article/details/gtjozgoqcx.html

Go:   // 手写循环累加
来源：http://dali.bjfxy.top/Article/details/gtugwefrgv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ywan-chungtsiang.top/Article/details/gtklunmtcm.html

C#:   list.Sum();  list.Average()
来源：http://dali.wangdashe.top/Article/details/gtditlkwqc.html

[D17] 最大值与最小值
来源：http://dali.yuanzhike.top/Article/details/gtdlirqyib.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtknwjbpoq.html

PHP:  max($arr);  min($arr);
来源：http://dali.yongpay.top/Article/details/gtevwfvtos.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xuetiantiany.cn/Article/details/gthotioify.html

TS:   Math.max(...arr);
来源：http://dali.tanke756.top/Article/details/gtkbwnvrml.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.aibaodan.cn/Article/details/gtptwvscqt.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yueranfly.top/Article/details/gtcdtbwsxh.html

Ruby: arr.max;  arr.min
来源：http://dali.yueranfly.top/Article/details/gtnixedadl.html

C#:   list.Max();  list.Min()
来源：http://dali.hongshengwenyu.top/Article/details/gtsoioctcq.html

[D18] 扁平化嵌套数组
来源：http://dali.xinyue.icu/Article/details/gtzkuzfqyk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yonumen.top/Article/details/gtfbburfjy.html

PHP:  array_merge(...$nested);
来源：http://dali.hysaishi.cn/Article/details/gtiodrrrwi.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.iojbl.cn/Article/details/gtwqstrloh.html

TS:   nested.flat();
来源：http://dali.yj202588.top/Article/details/gthbjkaqxw.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.fengsongda.top/Article/details/gtcbqcogsu.html

Go:   // 手写双层循环
来源：http://dali.jinqigfzy.top/Article/details/gtpnxijgcz.html

Ruby: nested.flatten
来源：http://dali.jlsjyb.cn/Article/details/gtpfksuswv.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ydzc1.top/Article/details/gtypmnvwem.html

[D19] 按字段分组
来源：http://dali.316326.xyz/Article/details/gtrhdqhelv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.tanke756.top/Article/details/gtgbumnhbf.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yvedp.cn/Article/details/gtiaydtbfo.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yvedp.cn/Article/details/gtdxydtknw.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sxryk.cn/Article/details/gtvsyxfdrk.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jyoumei.cn/Article/details/gtoxqmkbol.html

Go:   // 手写 map[string][]T
来源：http://dali.ydzc1.top/Article/details/gtjqxvysqu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yuxming.cn/Article/details/gtqhatvvml.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hywenlv.cn/Article/details/gtqxjqjpbk.html

[D20] 统计每个元素出现次数
来源：http://dali.0kj1m.cn/Article/details/gtwjfpdejh.html

Py:   Counter(arr)
来源：http://dali.xuanzx.com/Article/details/gtqjkisxel.html

PHP:  array_count_values($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsoeaanip.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tian-w.cn/Article/details/gtxwnqgguy.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.vqdsnc.cn/Article/details/gtqdqnkhtb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhongyouzk.top/Article/details/gtaiguhdvz.html

Go:   // 手写 map[T]int
来源：http://dali.daxiang520.top/Article/details/gtueuyjtkg.html

Ruby: arr.tally
来源：http://dali.yueranfly.top/Article/details/gtejgmpvag.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.vqdsnc.cn/Article/details/gthogdsmyl.html

[D21] 判断是否包含某元素
来源：http://dali.hywenlv.cn/Article/details/gtcncypfyh.html

Py:   x in arr
来源：http://dali.hammf.cn/Article/details/gtuhgpfipv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhongyouzk.top/Article/details/gtetzghehl.html

JS:   arr.includes(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtsmvxmdsx.html

TS:   arr.includes(x)
来源：http://dali.sxryk.cn/Article/details/gthncgjjpp.html

Java: list.contains(x)
来源：http://dali.jlsjyb.cn/Article/details/gtkfxbitne.html

Go:   slices.Contains(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxnfhtrem.html

Ruby: arr.include?(x)
来源：http://dali.yanxiufei.cn/Article/details/gtsfqxssdk.html

C#:   list.Contains(x)
来源：http://dali.mhx1999.top/Article/details/gtnbroxqgu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.dianchejie.cn/Article/details/gtngpdyudd.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtjumboynk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sufxvd.cn/Article/details/gtjaawblpm.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shzxlz.cn/Article/details/gthztkhdsv.html

TS:   [...arr];
来源：http://dali.316326.xyz/Article/details/gtlgashzbw.html

Java: new ArrayList<>(list);
来源：http://dali.ydzc1.top/Article/details/gtvwzqsrcj.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cashguo.top/Article/details/gtkkszehxw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yangfankeji.com/Article/details/gtvoxcnvjr.html

C#:   new List<int>(list);
来源：http://dali.0kj1m.cn/Article/details/gtyookdimu.html

[D23] reduce 累积计算
来源：http://dali.sysykeji.top/Article/details/gtnclqdlck.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtoinrzjor.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhongyouzk.top/Article/details/gtwqjxzqit.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtogleejis.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gotoacloud.top/Article/details/gtxznfryaf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jlsjyb.cn/Article/details/gtsbuqqwjr.html

Go:   // 手写循环
来源：http://dali.svipenyu.cn/Article/details/gtlsapatnj.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.dashuyun.cn/Article/details/gtvcgezlsa.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhiwuduotai.top/Article/details/gtzryxwnql.html

[D24] 字典 / Map 基本操作
来源：http://dali.jinghuilouyu.cn/Article/details/gtteynhdyt.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.kuanghao11.cn/Article/details/gtgggrflcu.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hysaishi.cn/Article/details/gtwpyightz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtrqtxcgfl.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtzbfalten.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cucudq.cn/Article/details/gtqyltibdx.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ehwqpu.com/Article/details/gtectaphzo.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.c1oappe.top/Article/details/gtnwysjimv.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gotoacloud.top/Article/details/gtbhtyjeat.html

[D25] Set 集合去重与交并差
来源：http://dali.chenlongwang.top/Article/details/gtavxkatqx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shuidangran.top/Article/details/gtltlfpoon.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhaomingkeji.xyz/Article/details/gtytwyyncx.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.guowangkeji.top/Article/details/gtrinslgjy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yueranfly.top/Article/details/gtgoaxakju.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.svipenyu.cn/Article/details/gtonayjjoh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zycfv.cn/Article/details/gtequyaznj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gotoacloud.top/Article/details/gtvesczdtc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ehwqpu.com/Article/details/gtehvlexyu.html

[D26] 数组转字符串
来源：http://dali.yvedp.cn/Article/details/gtwamlvucd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ehwqpu.com/Article/details/gtwbzbqhby.html

PHP:  implode(", ", $arr);
来源：http://dali.mhx1999.top/Article/details/gtaycvlmfs.html

JS:   arr.join(", ")
来源：http://dali.yanxiufei.cn/Article/details/gtdwuccnii.html

TS:   arr.join(", ")
来源：http://dali.jqgufenzy.top/Article/details/gtmmsyuwpp.html

Java: String.join(", ", list)
来源：http://dali.yangfankeji.com/Article/details/gtnjebdsfr.html

Go:   strings.Join(strs, ", ")
来源：http://dali.nwbrower.top/Article/details/gtaizmbpgp.html

Ruby: arr.join(", ")
来源：http://dali.xuetiantiany.cn/Article/details/gtvheyawzy.html

C#:   string.Join(", ", list)
来源：http://dali.gzhubu.top/Article/details/gtznkvsekt.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtfnbvgfld.html

E. 字符串处理
来源：http://dali.svipenyu.cn/Article/details/gtguahmtyw.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtdlckbhhj.html

[E01] 拼接字符串
来源：http://dali.cheryme.top/Article/details/gtdwwrgtto.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhengqikj.top/Article/details/gtfrsakfta.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zycfv.cn/Article/details/gthdrnxqqc.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnxiangtu.top/Article/details/gtejvthnlj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xuetiantiany.cn/Article/details/gtraqqjjzj.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.nanxuanxn.top/Article/details/gtlbyprmhk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ppjwa.cn/Article/details/gtflrrruyq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hnqzz.top/Article/details/gtqwpexnsz.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtwomeibqd.html

[E02] 重复字符串
来源：http://dali.shzxlz.cn/Article/details/gtcnftqirt.html

Py:   "ab" * 3
来源：http://dali.yuanzhike.top/Article/details/gtawbsdttt.html

PHP:  str_repeat("ab", 3);
来源：http://dali.tianlin.xyz/Article/details/gtpvohwvpc.html

JS:   "ab".repeat(3)
来源：http://dali.hywenlv.cn/Article/details/gtulfowzir.html

TS:   "ab".repeat(3)
来源：http://dali.fzhhl.top/Article/details/gtewqzzmsd.html

Java: "ab".repeat(3)
来源：http://dali.cashguo.top/Article/details/gtqnrxhfqo.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.tianlin.xyz/Article/details/gtofckpdoe.html

Ruby: "ab" * 3
来源：http://dali.jyoumei.cn/Article/details/gtatvwstzv.html


<!-- 参考信息 -->