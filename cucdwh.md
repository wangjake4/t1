代发 wailian999

Go:   func() { fmt.Println("run") }()
来源：http://dali.iojbl.cn/Article/details/gtxfxgjzbm.html

Ruby: -> { puts "run" }.call
来源：http://dali.feifeiyinyue.top/Article/details/gthlvfkbiw.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhoulong.xyz/Article/details/gtnsirejzf.html

[C13] 类型声明 / 类型注解
来源：http://dali.zdqjudy.top/Article/details/gtgatlexfc.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jlsjyb.cn/Article/details/gtylpllete.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shzxlz.cn/Article/details/gthnxyktfx.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.chenlongwang.top/Article/details/gtsmvkyitp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gtjipnbnsa.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gtqzbtgnln.html

Go:   func add(a, b int) int
来源：http://dali.gaohongyu789.top/Article/details/gtymfocmsv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shanyushiyangtech.top/Article/details/gtqnotbmop.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.kuanghao11.cn/Article/details/gtghclkvjr.html

[C14] 泛型函数
来源：http://dali.sysykeji.top/Article/details/gtsbszpahp.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.dianchejie.cn/Article/details/gtvavsmxgx.html

PHP:  // 无泛型
来源：http://dali.shangyingyoupin.top/Article/details/gtcrkshjys.html

JS:   // 无泛型
来源：http://dali.vqdsnc.cn/Article/details/gtcijgjkog.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.fzhhl.top/Article/details/gtqvliviux.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.sweek.top/Article/details/gtrfijptxo.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hywenlv.cn/Article/details/gttqynmaqg.html

Ruby: # 无泛型
来源：http://dali.hnqzz.top/Article/details/gtnjrhxtkf.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.haohaochexian.top/Article/details/gtuzqxpwmr.html

[C15] 解构 / 展开参数
来源：http://dali.hnxiangtu.top/Article/details/gtbumsutop.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jinqigfzy.top/Article/details/gtfygyxupn.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shanyushiyangtech.top/Article/details/gtsemyodon.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zdqjudy.top/Article/details/gtslipqebw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hnxiangtu.top/Article/details/gtzetnjjgg.html

Java: // 无解构
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxjiehsde.html

Go:   // 无解构
来源：http://dali.ppjwa.cn/Article/details/gtcplvggbr.html

Ruby: a, b = pair
来源：http://dali.redwolf501.top/Article/details/gtcltyrkhf.html

C#:   var (a, b) = pair;
来源：http://dali.kuanghao11.cn/Article/details/gtldrchqsu.html

[C16] 函数 / 方法重载
来源：http://dali.ppjwa.cn/Article/details/gtdyyfflgp.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.fzhhl.top/Article/details/gtidcsivps.html

PHP:  // 无重载
来源：http://dali.hammf.cn/Article/details/gtpjdwezcw.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.c1oappe.top/Article/details/gtvusmpsul.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jqgfzy.top/Article/details/gthdlqbojm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtwldsyejk.html

Go:   // 无重载：用不同函数名
来源：http://dali.yongpay.top/Article/details/gtzbzsonwy.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yanxiufei.cn/Article/details/gtltqryard.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zdqjudy.top/Article/details/gtiorvmztr.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtutncloat.html

D. 数组 / 列表 / 集合
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnemkyzmc.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtdctkxtef.html

[D01] 创建数组 / 列表
来源：http://dali.c1oappe.top/Article/details/gtchblrsmt.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwjkrkbsa.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.snrcjt.cn/Article/details/gtuakrfghe.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.pengpengdd.cyou/Article/details/gtetzekcpl.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.andypj.xyz/Article/details/gtohdwwvus.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hywenlv.cn/Article/details/gtqyfazibx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shzxlz.cn/Article/details/gtqjsvvtal.html

Ruby: arr = [1, 2, 3]
来源：http://dali.guannengcc.top/Article/details/gtulpwtyvq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhengqikj.top/Article/details/gtmsllpzrb.html

[D02] 追加元素到末尾
来源：http://dali.yangfankeji.com/Article/details/gtdismrehq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jinqigufen.top/Article/details/gtktyxluvh.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yangfankeji.com/Article/details/gtnwuptxzb.html

JS:   arr.push(4);
来源：http://dali.shuidangran.top/Article/details/gtkaprrovr.html

TS:   arr.push(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtahjiwpei.html

Java: list.add(4);
来源：http://dali.feifeiyinyue.top/Article/details/gtwqubkuur.html

Go:   arr = append(arr, 4)
来源：http://dali.daxiang520.top/Article/details/gtjwxarqgz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.chenlongwang.top/Article/details/gtktvwnqpi.html

C#:   list.Add(4);
来源：http://dali.cucudq.cn/Article/details/gtarbesxce.html

[D03] 在指定位置插入元素
来源：http://dali.yangfankeji.com/Article/details/gtwffrcyhs.html

Py:   arr.insert(0, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvlucpfkh.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jlsjyb.cn/Article/details/gtlavjlruw.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.dianchejie.cn/Article/details/gtlnyatluc.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.sxryk.cn/Article/details/gtygrjtzkm.html

Java: list.add(0, 0);
来源：http://dali.jinqigufen.top/Article/details/gtjnnrevya.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.redwolf501.top/Article/details/gtfdbqfelx.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hnqzz.top/Article/details/gtaprjnqsx.html

C#:   list.Insert(0, 0);
来源：http://dali.yongpay.top/Article/details/gtjwnesozi.html

[D04] 删除元素
来源：http://dali.hywenlv.cn/Article/details/gtqyuiprjs.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cucudq.cn/Article/details/gtwisjvyfx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.gotoacloud.top/Article/details/gteaoswhkv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shzxlz.cn/Article/details/gtihaeelmj.html

TS:   arr.splice(0, 1);
来源：http://dali.hammf.cn/Article/details/gtzythscbd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.dianchejie.cn/Article/details/gtjrikyvbt.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.guowangkeji.top/Article/details/gtczozqtbw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.sweek.top/Article/details/gtobfhpnpy.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yuxming.cn/Article/details/gtwisinqvo.html

[D05] 访问与修改元素
来源：http://dali.jinqigfzy.top/Article/details/gtcbznrrbk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ehwqpu.com/Article/details/gtiygdujgw.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hnxiangtu.top/Article/details/gtglxfusks.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xuanzx.com/Article/details/gtdyiqvisw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jqgfzy.top/Article/details/gteiuopnph.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.mhx1999.top/Article/details/gtyqcstyrx.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yonumen.top/Article/details/gtvlssdlyu.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ppjwa.cn/Article/details/gtlnmgvcma.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yueranfly.top/Article/details/gtllhnwolc.html

[D06] 数组长度
来源：http://dali.feifeiyinyue.top/Article/details/gthkrlqnyf.html

Py:   len(arr)
来源：http://dali.ehwqpu.com/Article/details/gtlhwopmoo.html

PHP:  count($arr);
来源：http://dali.c1oappe.top/Article/details/gtakzdnycs.html

JS:   arr.length
来源：http://dali.jiagoushi.top/Article/details/gtvilyfhur.html

TS:   arr.length
来源：http://dali.dashuyun.cn/Article/details/gttvqrgocp.html

Java: list.size();
来源：http://dali.jiagoushi.top/Article/details/gtlhtcungb.html

Go:   len(arr)
来源：http://dali.xuanzx.com/Article/details/gtxyihzbad.html

Ruby: arr.length; arr.size
来源：http://dali.cucudq.cn/Article/details/gtbmxbxgcr.html

C#:   list.Count;
来源：http://dali.jlsjyb.cn/Article/details/gtrgjulrph.html

[D07] 切片 / 取子数组
来源：http://dali.svipenyu.cn/Article/details/gtvtdxsbvt.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yvedp.cn/Article/details/gtiuzzrdbe.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.9152youxi.cn/Article/details/gtvfjplksp.html

JS:   arr.slice(1, 4);
来源：http://dali.hfpthk.cn/Article/details/gtdxgicvzm.html

TS:   arr.slice(1, 4);
来源：http://dali.daria6918.cn/Article/details/gtqbumerym.html

Java: list.subList(1, 4);
来源：http://dali.yj20258.top/Article/details/gtcabbgcdi.html

Go:   arr[1:4]
来源：http://dali.wangdashe.top/Article/details/gttdilcrza.html

Ruby: arr[1, 3]
来源：http://dali.yuxming.cn/Article/details/gtcjwzsfkb.html

C#:   list.GetRange(1, 3);
来源：http://dali.chenlongwang.top/Article/details/gtbcaynncs.html

[D08] 合并两个数组
来源：http://dali.havefunace.top/Article/details/gtykmjmfqz.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhengqikj.top/Article/details/gtsfuvduvo.html

PHP:  array_merge($a, $b);
来源：http://dali.yueranfly.top/Article/details/gtcbtwrkww.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.tanke756.top/Article/details/gtlhdirotx.html

TS:   [...a, ...b];
来源：http://dali.snrcjt.cn/Article/details/gtoxzeuhks.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtisyxognk.html

Go:   append(a, b...)
来源：http://dali.cashguo.top/Article/details/gtwmeucqns.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zycfv.cn/Article/details/gtxicboadq.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtbusirobg.html

[D09] 排序（升序）
来源：http://dali.svipenyu.cn/Article/details/gtlevqinbt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aizwys.cn/Article/details/gtkaylmwtc.html

PHP:  sort($arr);
来源：http://dali.bjfxy.top/Article/details/gtvcrcedby.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdahyhizp.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.aizwys.cn/Article/details/gtraiirciv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xziqi.cn/Article/details/gtrzghaymx.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtedvgmxha.html

Ruby: arr.sort
来源：http://dali.meibo888.top/Article/details/gtuyuyssqv.html

C#:   list.Sort();
来源：http://dali.hysaishi.cn/Article/details/gtlnsgvlnp.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xinyue.icu/Article/details/gtdpbzovzp.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.snrcjt.cn/Article/details/gtnzrlhjsq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.9152youxi.cn/Article/details/gtapfyhebb.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.redwolf501.top/Article/details/gtktnzexjk.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ehwqpu.com/Article/details/gtvumbjtxf.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hnxiangtu.top/Article/details/gtugytjdjw.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yj202588.top/Article/details/gtxygyvulc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.tanke756.top/Article/details/gtodnsuvfq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.guowangkeji.top/Article/details/gtuixeyeaf.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gtgqftwxch.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.sufxvd.cn/Article/details/gtiltprqgt.html

PHP:  array_reverse($arr);
来源：http://dali.dashuyun.cn/Article/details/gtqeafkinr.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.wangdashe.top/Article/details/gtzhbbpxts.html

TS:   [...arr].reverse();
来源：http://dali.yangfankeji.com/Article/details/gtfurlvdcn.html

Java: Collections.reverse(list);
来源：http://dali.jyoumei.cn/Article/details/gtqlwmxdsy.html

Go:   slices.Reverse(arr)
来源：http://dali.xinyue.icu/Article/details/gteaxihvwk.html

Ruby: arr.reverse
来源：http://dali.cheryme.top/Article/details/gtnzvinlel.html

C#:   list.Reverse();
来源：http://dali.jqgfzy.top/Article/details/gtvxrxamuh.html

[D12] 查找元素下标
来源：http://dali.yuanzhike.top/Article/details/gtzprzlwch.html

Py:   arr.index(x);  x in arr
来源：http://dali.mhx1999.top/Article/details/gtffahcewq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.iojbl.cn/Article/details/gtktsgchzk.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hongshengwenyu.top/Article/details/gttpuerwcw.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gogol.net.cn/Article/details/gtppandrwz.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.svipenyu.cn/Article/details/gthjcgmilk.html

Go:   slices.Index(arr, x)
来源：http://dali.daria6918.cn/Article/details/gtqejpaqcf.html

Ruby: arr.index(x)
来源：http://dali.yongpay.top/Article/details/gtnxagdjjs.html

C#:   list.IndexOf(x);
来源：http://dali.c1oappe.top/Article/details/gtbijnyfwe.html

[D13] 过滤（保留满足条件的）
来源：http://dali.wangshuangyany.cn/Article/details/gtmdbwsqfs.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yueranfly.top/Article/details/gtkfhwnxck.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jiagoushi.top/Article/details/gtzpzqzupc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gtwhkhbakx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jqgufenzy.top/Article/details/gtqsujbmky.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcojyhizf.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yj202588.top/Article/details/gtafwngwgn.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.dianchejie.cn/Article/details/gtrvalclrz.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.guannengcc.top/Article/details/gtbqwbpntv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.daxiang520.top/Article/details/gtpfoozpam.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpuluzngi.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.kuanghao11.cn/Article/details/gtjhwjeaba.html

JS:   arr.map(x => x * 2)
来源：http://dali.yj20258888.top/Article/details/gtrokwmqso.html

TS:   arr.map(x => x * 2)
来源：http://dali.yonumen.top/Article/details/gtqygufwwq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yj20258.top/Article/details/gtkhcwtbgp.html

Go:   // 手写循环
来源：http://dali.sweek.top/Article/details/gtprtfgpae.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jqgufenzy.top/Article/details/gtykmnawqp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sweek.top/Article/details/gtveyroyvl.html

[D15] 去重
来源：http://dali.cqqwz.cn/Article/details/gtezhcfyqp.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yongpay.top/Article/details/gtslghztfc.html

PHP:  array_unique($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtffyxrzwt.html

JS:   [...new Set(arr)]
来源：http://dali.yongpay.top/Article/details/gtdugljlbc.html

TS:   [...new Set(arr)]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwsiiyekh.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jqgufenzy.top/Article/details/gtkxtnuovd.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shangyingyoupin.top/Article/details/gtdskevbtl.html

Ruby: arr.uniq
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtapuvqucs.html

C#:   list.Distinct().ToList()
来源：http://dali.vqdsnc.cn/Article/details/gtdvxymfht.html

[D16] 求和与平均值
来源：http://dali.snrcjt.cn/Article/details/gtgpnaulco.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gogol.net.cn/Article/details/gtyfkaelyn.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtpfdczovd.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtadknppws.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.bjfxy.top/Article/details/gtwumwtsyw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.bjfxy.top/Article/details/gtxakfivdq.html

Go:   // 手写循环累加
来源：http://dali.iojbl.cn/Article/details/gtqjjybqme.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hnxiangtu.top/Article/details/gtffxkiojn.html

C#:   list.Sum();  list.Average()
来源：http://dali.mhx1999.top/Article/details/gtmuuchyhv.html

[D17] 最大值与最小值
来源：http://dali.cashguo.top/Article/details/gtesmtwjce.html

Py:   max(arr);  min(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtbiqhqquq.html

PHP:  max($arr);  min($arr);
来源：http://dali.jqgfzy.top/Article/details/gtzyymemza.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yj20258.top/Article/details/gtexhsqmvl.html

TS:   Math.max(...arr);
来源：http://dali.jqgfzy.top/Article/details/gtdvqpltxb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.daria6918.cn/Article/details/gtviimfrom.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtzcqaleit.html

Ruby: arr.max;  arr.min
来源：http://dali.cdnleiting.top/Article/details/gtvpkuklad.html

C#:   list.Max();  list.Min()
来源：http://dali.andypj.xyz/Article/details/gtlubqczrr.html

[D18] 扁平化嵌套数组
来源：http://dali.aibaodan.cn/Article/details/gtiryxpoez.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.bjfxy.top/Article/details/gtiranqkcb.html

PHP:  array_merge(...$nested);
来源：http://dali.meibo888.top/Article/details/gtjztwoims.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hammf.cn/Article/details/gtymdevqho.html

TS:   nested.flat();
来源：http://dali.wangdashe.top/Article/details/gtxvsyxqbg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.fengsongda.top/Article/details/gtljxypkdy.html

Go:   // 手写双层循环
来源：http://dali.9152youxi.cn/Article/details/gtmahaqpqj.html

Ruby: nested.flatten
来源：http://dali.gzhubu.top/Article/details/gtkszxnjxp.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gtggsuehnp.html

[D19] 按字段分组
来源：http://dali.daxiang520.top/Article/details/gtfoiptcur.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.andypj.xyz/Article/details/gtefwaopkg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.fengsongda.top/Article/details/gtjfgjknih.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jianghu66.top/Article/details/gtwgvtysre.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.nanxinkj.top/Article/details/gtufhivygv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.c1oappe.top/Article/details/gtdmlcpyrg.html

Go:   // 手写 map[string][]T
来源：http://dali.mhx1999.top/Article/details/gtgftspbdp.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthgkkxmfr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zycfv.cn/Article/details/gthssxfwyv.html

[D20] 统计每个元素出现次数
来源：http://dali.jinghuilouyu.cn/Article/details/gtubsqdugl.html

Py:   Counter(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gthfcvotxw.html

PHP:  array_count_values($arr);
来源：http://dali.yueranfly.top/Article/details/gtcnzntzpy.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sxryk.cn/Article/details/gtsfmxldpj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.kuanghao11.cn/Article/details/gtplysqcmv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ybcxt.top/Article/details/gtfufkjepl.html

Go:   // 手写 map[T]int
来源：http://dali.wangshuangyany.cn/Article/details/gtfkfvlffz.html

Ruby: arr.tally
来源：http://dali.snrcjt.cn/Article/details/gtowpjsden.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zycfv.cn/Article/details/gtatmfutdp.html

[D21] 判断是否包含某元素
来源：http://dali.jqgfzy.top/Article/details/gtkyycpnfn.html

Py:   x in arr
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnwxmrprz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.tanke756.top/Article/details/gtnbcsngwn.html

JS:   arr.includes(x)
来源：http://dali.jinqigufen.top/Article/details/gtslhstnpq.html

TS:   arr.includes(x)
来源：http://dali.aizwys.cn/Article/details/gtvuyyolli.html

Java: list.contains(x)
来源：http://dali.fengsongda.top/Article/details/gtiqkpsslb.html

Go:   slices.Contains(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gtfvxoczlj.html

Ruby: arr.include?(x)
来源：http://dali.zhengqikj.top/Article/details/gtkcfieisq.html

C#:   list.Contains(x)
来源：http://dali.tianlin.xyz/Article/details/gtczmjlyec.html

[D22] 复制数组（避免共享引用）
来源：http://dali.chenlongwang.top/Article/details/gtldjnjdmm.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shuidangran.top/Article/details/gtacydzjjd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.nwbrower.top/Article/details/gtfgxsimkh.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.daxiang520.top/Article/details/gtzfbltwyz.html

TS:   [...arr];
来源：http://dali.zdqjudy.top/Article/details/gtgddsvxmu.html

Java: new ArrayList<>(list);
来源：http://dali.vqdsnc.cn/Article/details/gthllcpokx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.pycfn.com/Article/details/gtiuptklqu.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yanxiufei.cn/Article/details/gtnwdmdhks.html

C#:   new List<int>(list);
来源：http://dali.wangshuangyany.cn/Article/details/gttlzsvmrc.html

[D23] reduce 累积计算
来源：http://dali.yonumen.top/Article/details/gtvyneomax.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.chenzaomai.com/Article/details/gtnzztslhp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.316326.xyz/Article/details/gtmfhizcjt.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtasbepmwi.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhoulong.xyz/Article/details/gttkkyxopo.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hnxiangtu.top/Article/details/gtjgcrflnk.html

Go:   // 手写循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxcufnnoh.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.tanke756.top/Article/details/gtkgqkvuov.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnkdcpfgq.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhoulong.xyz/Article/details/gtvablefws.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.sufxvd.cn/Article/details/gtbujmyyvv.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.tanke756.top/Article/details/gtzpjycifj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hywenlv.cn/Article/details/gtvnqriqkp.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.nanxuanxn.top/Article/details/gtlznxnsjz.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinqigfzy.top/Article/details/gtymblgsxa.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.havefunace.top/Article/details/gtpxkqiujm.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shzxlz.cn/Article/details/gtgleulcoo.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hfpthk.cn/Article/details/gttzbkfmzw.html

[D25] Set 集合去重与交并差
来源：http://dali.pengpengdd.cyou/Article/details/gtcfbcieqs.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnugvkmud.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ybcxt.top/Article/details/gtpcqusvqp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jqgufenzy.top/Article/details/gtbftmqrme.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.sxryk.cn/Article/details/gtcrrdwcsm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.meibo888.top/Article/details/gtzvgfnrwt.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.sufxvd.cn/Article/details/gtozqexzzq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sysykeji.top/Article/details/gttptrambf.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shuidangran.top/Article/details/gttlkgbhfl.html

[D26] 数组转字符串
来源：http://dali.c1oappe.top/Article/details/gtvhnfirgy.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hnxiangtu.top/Article/details/gtehqloubg.html

PHP:  implode(", ", $arr);
来源：http://dali.svipenyu.cn/Article/details/gtdorpooqp.html

JS:   arr.join(", ")
来源：http://dali.jianghu66.top/Article/details/gtqlgczxoa.html

TS:   arr.join(", ")
来源：http://dali.jyoumei.cn/Article/details/gtonhnwbae.html

Java: String.join(", ", list)
来源：http://dali.daxiang520.top/Article/details/gtzkpwfptf.html

Go:   strings.Join(strs, ", ")
来源：http://dali.feifeiyinyue.top/Article/details/gtpatprmym.html

Ruby: arr.join(", ")
来源：http://dali.yj20258.top/Article/details/gtfylamywr.html

C#:   string.Join(", ", list)
来源：http://dali.ybcxt.top/Article/details/gttqwszoas.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtspeoagif.html

E. 字符串处理
来源：http://dali.cheryme.top/Article/details/gtmipwejsg.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtqszwaegp.html

[E01] 拼接字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtcksveief.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cheryme.top/Article/details/gthnpragxd.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.birdmap.top/Article/details/gttskbecjs.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gtexueyiln.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zdqjudy.top/Article/details/gtmuovmjmc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hongshengwenyu.top/Article/details/gteehemqqm.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.chenjidiqi.icu/Article/details/gtkvkymfns.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ydzc1.top/Article/details/gtbqwocwsu.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.nwbrower.top/Article/details/gtrithgroa.html

[E02] 重复字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqajnhowz.html

Py:   "ab" * 3
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuaxbkerv.html

PHP:  str_repeat("ab", 3);
来源：http://dali.sxryk.cn/Article/details/gtzzhckvwq.html

JS:   "ab".repeat(3)
来源：http://dali.jqgufenzy.top/Article/details/gtudlavleg.html

TS:   "ab".repeat(3)
来源：http://dali.9152youxi.cn/Article/details/gtoxeyjtkn.html

Java: "ab".repeat(3)
来源：http://dali.feifeiyinyue.top/Article/details/gtesgynxtk.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yangfankeji.com/Article/details/gttlpqkerq.html

Ruby: "ab" * 3
来源：http://dali.xziqi.cn/Article/details/gtcxlgjbkj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzrxecryu.html

[E03] 截取子串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjtkluwlr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yanxiufei.cn/Article/details/gtmbdokgqm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gtxciaefhj.html


<!-- 参考信息 -->