代发 wailian999

Go:   func() { fmt.Println("run") }()
来源：http://dali.cqqwz.cn/Article/details/gtbbntztqf.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhoulong.xyz/Article/details/gtudmxefis.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.sufxvd.cn/Article/details/gtncmjmtyi.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrtsvicyr.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cashguo.top/Article/details/gtyyuedoeh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nwbrower.top/Article/details/gtpomnuyqd.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yueranfly.top/Article/details/gtjcmqvjhf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtcmahuops.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gtammctgez.html

Go:   func add(a, b int) int
来源：http://dali.pycfn.com/Article/details/gtycrgbzfx.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hammf.cn/Article/details/gtzlwunrnl.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yuanzhike.top/Article/details/gtrtdbduby.html

[C14] 泛型函数
来源：http://dali.xuetiantiany.cn/Article/details/gtaliqnvid.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yuanzhike.top/Article/details/gtltlckqqz.html

PHP:  // 无泛型
来源：http://dali.aibaodan.cn/Article/details/gtytunrmeo.html

JS:   // 无泛型
来源：http://dali.sufxvd.cn/Article/details/gtmxtvghzl.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhixingplan.top/Article/details/gtzqsygles.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxnemehez.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cheryme.top/Article/details/gtftrqmjki.html

Ruby: # 无泛型
来源：http://dali.yj20258888.top/Article/details/gtnqgxhukd.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.gzhubu.top/Article/details/gtgzatkrsr.html

[C15] 解构 / 展开参数
来源：http://dali.bjfxy.top/Article/details/gtubigwhch.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.tianlin.xyz/Article/details/gttqjpxgiz.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhoulong.xyz/Article/details/gtaxvpbyvq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ybcxt.top/Article/details/gtfuabaipk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ehwqpu.com/Article/details/gtnuksyfql.html

Java: // 无解构
来源：http://dali.zhiwuduotai.top/Article/details/gtylicsuvr.html

Go:   // 无解构
来源：http://dali.yanxiufei.cn/Article/details/gtrjfxthxj.html

Ruby: a, b = pair
来源：http://dali.yvedp.cn/Article/details/gtektfhtqi.html

C#:   var (a, b) = pair;
来源：http://dali.daria6918.cn/Article/details/gtswgymlkx.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gttjxcgtbk.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ywan-chungtsiang.top/Article/details/gtymkxfvon.html

PHP:  // 无重载
来源：http://dali.cqqwz.cn/Article/details/gtjfchmpsq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.shangyingyoupin.top/Article/details/gthkbbbpdq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ivvv.top/Article/details/gtkktsmdhk.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.gogol.net.cn/Article/details/gtpdoxpmsc.html

Go:   // 无重载：用不同函数名
来源：http://dali.yuanzhike.top/Article/details/gtgcdermhr.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hnqzz.top/Article/details/gthyqylymw.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jqgufenzy.top/Article/details/gtgdxdptre.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtejpqwuid.html

D. 数组 / 列表 / 集合
来源：http://dali.zhoulong.xyz/Article/details/gtlmjolpsl.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtzmeqvlfw.html

[D01] 创建数组 / 列表
来源：http://dali.shanyushiyangtech.top/Article/details/gtznvjoask.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.iojbl.cn/Article/details/gthsuuqqbo.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.shuidangran.top/Article/details/gteklsxvzk.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cdnleiting.top/Article/details/gtlkylbldv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.gotoacloud.top/Article/details/gtlrwvwyfm.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yj20258888.top/Article/details/gtsuxtzewa.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.fengsongda.top/Article/details/gtndrnvapz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sufxvd.cn/Article/details/gtvqcwtsav.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ybcxt.top/Article/details/gttilvlgnw.html

[D02] 追加元素到末尾
来源：http://dali.hysaishi.cn/Article/details/gtuxcvtfre.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.c1oappe.top/Article/details/gtnnhpnkab.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gzhubu.top/Article/details/gtphgxhxsj.html

JS:   arr.push(4);
来源：http://dali.yj20258.top/Article/details/gtuhnekggk.html

TS:   arr.push(4);
来源：http://dali.yj202588.top/Article/details/gtyqqjtjby.html

Java: list.add(4);
来源：http://dali.yongpay.top/Article/details/gtdqumiico.html

Go:   arr = append(arr, 4)
来源：http://dali.daria6918.cn/Article/details/gtcdpnztol.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yanxiufei.cn/Article/details/gtzjjruffp.html

C#:   list.Add(4);
来源：http://dali.hnqzz.top/Article/details/gtjezrpcoj.html

[D03] 在指定位置插入元素
来源：http://dali.jqgfzy.top/Article/details/gtzacgkwem.html

Py:   arr.insert(0, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtgdrwjsic.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jinqigufen.top/Article/details/gtzufwjfls.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hnqzz.top/Article/details/gtlpbexcai.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cashguo.top/Article/details/gtmrcizegb.html

Java: list.add(0, 0);
来源：http://dali.meibo888.top/Article/details/gtqfyzayvc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jiagoushi.top/Article/details/gttahgntea.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwjpfwzzx.html

C#:   list.Insert(0, 0);
来源：http://dali.havefunace.top/Article/details/gtctglpmgh.html

[D04] 删除元素
来源：http://dali.havefunace.top/Article/details/gtaqgjuyef.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.aizwys.cn/Article/details/gtskizhuww.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jqgfzy.top/Article/details/gtzrixhrat.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yueranfly.top/Article/details/gtrdstcjha.html

TS:   arr.splice(0, 1);
来源：http://dali.svipenyu.cn/Article/details/gtxukisfpe.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yuanzhike.top/Article/details/gttwmvlzko.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.guannengcc.top/Article/details/gtihcpupuq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.pycfn.com/Article/details/gtenkgsvrg.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.guowangkeji.top/Article/details/gteygdhuei.html

[D05] 访问与修改元素
来源：http://dali.hnxiangtu.top/Article/details/gtvkcpmaje.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.daxiang520.top/Article/details/gtmveixqqv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yongpay.top/Article/details/gtrpdkmjlb.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xinyue.icu/Article/details/gtqdbjxybb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.gaohongyu789.top/Article/details/gtopovrfkt.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.sxryk.cn/Article/details/gtihbhttfm.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zycfv.cn/Article/details/gtrwwdxqzz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.dashuyun.cn/Article/details/gtrljjhbtr.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.daria6918.cn/Article/details/gtoeyraqld.html

[D06] 数组长度
来源：http://dali.yj20258.top/Article/details/gtgmhqezbu.html

Py:   len(arr)
来源：http://dali.redwolf501.top/Article/details/gtxzrzusti.html

PHP:  count($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtxexyktfi.html

JS:   arr.length
来源：http://dali.cqqwz.cn/Article/details/gtdxbwhflc.html

TS:   arr.length
来源：http://dali.cucudq.cn/Article/details/gtzadexotc.html

Java: list.size();
来源：http://dali.chenlongwang.top/Article/details/gtiswvfljk.html

Go:   len(arr)
来源：http://dali.yvedp.cn/Article/details/gtfeoawqhn.html

Ruby: arr.length; arr.size
来源：http://dali.cheryme.top/Article/details/gtexsmvhfj.html

C#:   list.Count;
来源：http://dali.dianchejie.cn/Article/details/gtcjnvwlht.html

[D07] 切片 / 取子数组
来源：http://dali.jinqigufen.top/Article/details/gtwxzabpbn.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ppjwa.cn/Article/details/gtiugdhoam.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.chenlongwang.top/Article/details/gthmjxeynx.html

JS:   arr.slice(1, 4);
来源：http://dali.ivvv.top/Article/details/gtnmvfwteu.html

TS:   arr.slice(1, 4);
来源：http://dali.guowangkeji.top/Article/details/gtnfvxmdes.html

Java: list.subList(1, 4);
来源：http://dali.dianchejie.cn/Article/details/gtbswarurt.html

Go:   arr[1:4]
来源：http://dali.shzxlz.cn/Article/details/gtyqwnmrvs.html

Ruby: arr[1, 3]
来源：http://dali.hnqzz.top/Article/details/gtdciiogme.html

C#:   list.GetRange(1, 3);
来源：http://dali.svipenyu.cn/Article/details/gtfbazulra.html

[D08] 合并两个数组
来源：http://dali.jianghu66.top/Article/details/gthldcvmow.html

Py:   a + b;  a.extend(b)
来源：http://dali.sufxvd.cn/Article/details/gtoylfyodi.html

PHP:  array_merge($a, $b);
来源：http://dali.jinghuilouyu.cn/Article/details/gtsinnmqtx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.snrcjt.cn/Article/details/gtldofcjgh.html

TS:   [...a, ...b];
来源：http://dali.fzhhl.top/Article/details/gtcvyauidz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xuanzx.com/Article/details/gtoclsxknu.html

Go:   append(a, b...)
来源：http://dali.wangshuangyany.cn/Article/details/gtzymbmwaj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hnqzz.top/Article/details/gtotakctcw.html

C#:   a.Concat(b).ToList()
来源：http://dali.guowangkeji.top/Article/details/gtsnynmbga.html

[D09] 排序（升序）
来源：http://dali.fzhhl.top/Article/details/gtecocyceh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.iojbl.cn/Article/details/gtaleaqihu.html

PHP:  sort($arr);
来源：http://dali.guannengcc.top/Article/details/gtkpudxucl.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.9152youxi.cn/Article/details/gtbvtofnxx.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.smart0.xyz/Article/details/gtqxzqevjw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.316326.xyz/Article/details/gtshscyclu.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xuanzx.com/Article/details/gtyevxcjsf.html

Ruby: arr.sort
来源：http://dali.sxryk.cn/Article/details/gtxqgviiqq.html

C#:   list.Sort();
来源：http://dali.hongshengwenyu.top/Article/details/gtdmrctznd.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.chenjidiqi.icu/Article/details/gtthqddgcr.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.svipenyu.cn/Article/details/gtuzfyuosl.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.iojbl.cn/Article/details/gtpaninqov.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tianlin.xyz/Article/details/gtwonrrzyy.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yueranfly.top/Article/details/gttetbahqy.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shangyingyoupin.top/Article/details/gtcdbruemx.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ppjwa.cn/Article/details/gttpfduqtz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhiwuduotai.top/Article/details/gtrhevbbjb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xuetiantiany.cn/Article/details/gtccgqtmyu.html

[D11] 反转数组
来源：http://dali.vqdsnc.cn/Article/details/gtmekeifdz.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.gotoacloud.top/Article/details/gtohfbthjv.html

PHP:  array_reverse($arr);
来源：http://dali.yj20258.top/Article/details/gtjpjncsoz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.aizwys.cn/Article/details/gtkthtqeyr.html

TS:   [...arr].reverse();
来源：http://dali.nanxuanxn.top/Article/details/gtyzedubbr.html

Java: Collections.reverse(list);
来源：http://dali.yuxming.cn/Article/details/gtyiitlpak.html

Go:   slices.Reverse(arr)
来源：http://dali.xinyue.icu/Article/details/gtfsplnjak.html

Ruby: arr.reverse
来源：http://dali.mhx1999.top/Article/details/gtdmjrofuw.html

C#:   list.Reverse();
来源：http://dali.jqgufenzy.top/Article/details/gtknskduoa.html

[D12] 查找元素下标
来源：http://dali.ybcxt.top/Article/details/gtvpiofnpx.html

Py:   arr.index(x);  x in arr
来源：http://dali.hammf.cn/Article/details/gtkupdiyux.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtggfksmtc.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hysaishi.cn/Article/details/gtytvndwvn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jyoumei.cn/Article/details/gtrlkwfzcq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.tianlin.xyz/Article/details/gtdlfzfbig.html

Go:   slices.Index(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gtfgbbadzc.html

Ruby: arr.index(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcvixjbqb.html

C#:   list.IndexOf(x);
来源：http://dali.shanyushiyangkeji.top/Article/details/gthfhedrft.html

[D13] 过滤（保留满足条件的）
来源：http://dali.tian-w.cn/Article/details/gtritsgtow.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.wangshuangyany.cn/Article/details/gthvdwordt.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtkfcjwymo.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtldznntcu.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jqgfzy.top/Article/details/gtjxhyvmzt.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.sufxvd.cn/Article/details/gtgcmomqtk.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.gotoacloud.top/Article/details/gtsstekzdf.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.chenzaomai.com/Article/details/gtqfezfeih.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtnzosvwkh.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jinqigfzy.top/Article/details/gtnlijpaaz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.meibo888.top/Article/details/gteojsqpjh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shuidangran.top/Article/details/gtwprycxaf.html

JS:   arr.map(x => x * 2)
来源：http://dali.sxryk.cn/Article/details/gtpkzepvtw.html

TS:   arr.map(x => x * 2)
来源：http://dali.hnxiangtu.top/Article/details/gtlkvdqwen.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.fzhhl.top/Article/details/gtmkerldhi.html

Go:   // 手写循环
来源：http://dali.hongshengwenyu.top/Article/details/gtzpqappoj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hammf.cn/Article/details/gtptvasgvq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.nwbrower.top/Article/details/gtwpyawcsw.html

[D15] 去重
来源：http://dali.guannengcc.top/Article/details/gtatlhikqm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.chenlongwang.top/Article/details/gteycihwsc.html

PHP:  array_unique($arr);
来源：http://dali.smart0.xyz/Article/details/gtntjjdfht.html

JS:   [...new Set(arr)]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjrzpeijc.html

TS:   [...new Set(arr)]
来源：http://dali.jqgufenzy.top/Article/details/gtnfqeucqh.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cucudq.cn/Article/details/gtmrwumhps.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yj202588.top/Article/details/gtyksbhwhg.html

Ruby: arr.uniq
来源：http://dali.hywenlv.cn/Article/details/gthzkpvbrl.html

C#:   list.Distinct().ToList()
来源：http://dali.316326.xyz/Article/details/gtkxuteaxh.html

[D16] 求和与平均值
来源：http://dali.jinqigfzy.top/Article/details/gtvmslwazu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtjslzgpza.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.redwolf501.top/Article/details/gtdffwfode.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtmiptxqbl.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gthdgjxqhb.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.sweek.top/Article/details/gtfiexoicp.html

Go:   // 手写循环累加
来源：http://dali.birdmap.top/Article/details/gtbvsjscei.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yanxiufei.cn/Article/details/gtpgtifnzd.html

C#:   list.Sum();  list.Average()
来源：http://dali.jiagoushi.top/Article/details/gtgqiilfnv.html

[D17] 最大值与最小值
来源：http://dali.xuanzx.com/Article/details/gtcvoiujow.html

Py:   max(arr);  min(arr)
来源：http://dali.jinqigufen.top/Article/details/gtydkvdxqd.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtbyuvzwaa.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.sysykeji.top/Article/details/gtqlwpmxsl.html

TS:   Math.max(...arr);
来源：http://dali.yj202588.top/Article/details/gthnlmwoyp.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hnqzz.top/Article/details/gtlwxdsevs.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hywenlv.cn/Article/details/gtqcglhgyv.html

Ruby: arr.max;  arr.min
来源：http://dali.zhiwuduotai.top/Article/details/gtcuztfjmz.html

C#:   list.Max();  list.Min()
来源：http://dali.andypj.xyz/Article/details/gtcwcxsnkt.html

[D18] 扁平化嵌套数组
来源：http://dali.nanxuanxn.top/Article/details/gtyavodpzs.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.vqdsnc.cn/Article/details/gtpcjnhrci.html

PHP:  array_merge(...$nested);
来源：http://dali.daxiang520.top/Article/details/gtkltiauem.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.havefunace.top/Article/details/gtxybciwwu.html

TS:   nested.flat();
来源：http://dali.hysaishi.cn/Article/details/gtcysbsivj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jqgfzy.top/Article/details/gtjgcuvqtq.html

Go:   // 手写双层循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsbcbexxi.html

Ruby: nested.flatten
来源：http://dali.xziqi.cn/Article/details/gthmynrnmb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yueranfly.top/Article/details/gtsjzupobr.html

[D19] 按字段分组
来源：http://dali.chenzaomai.com/Article/details/gtjwrwuvfr.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.birdmap.top/Article/details/gtxopcdfep.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.tian-w.cn/Article/details/gtomxwcqth.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hnxiangtu.top/Article/details/gtqbstajae.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinqigufen.top/Article/details/gtvjkosqik.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.gzhubu.top/Article/details/gtuotwflse.html

Go:   // 手写 map[string][]T
来源：http://dali.hysaishi.cn/Article/details/gticnepwfb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jyoumei.cn/Article/details/gtjtefzagy.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhixingplan.top/Article/details/gtwtzvnuad.html

[D20] 统计每个元素出现次数
来源：http://dali.wangdashe.top/Article/details/gtiemskjdc.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtmhmqhxqt.html

PHP:  array_count_values($arr);
来源：http://dali.mhx1999.top/Article/details/gtewqwmwwy.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.vqdsnc.cn/Article/details/gtsisicgme.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ydzc1.top/Article/details/gtqdcirxjq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.quarkkingdee.top/Article/details/gtbteqhuyd.html

Go:   // 手写 map[T]int
来源：http://dali.mhx1999.top/Article/details/gtjrzcotrl.html

Ruby: arr.tally
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrbfkiqda.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sysykeji.top/Article/details/gtclrmkwax.html

[D21] 判断是否包含某元素
来源：http://dali.havefunace.top/Article/details/gtdyejwmki.html

Py:   x in arr
来源：http://dali.daxiang520.top/Article/details/gtbpnvxoxt.html

PHP:  in_array($x, $arr, true);
来源：http://dali.guowangkeji.top/Article/details/gtbtbvhgee.html

JS:   arr.includes(x)
来源：http://dali.hnxiangtu.top/Article/details/gtjzyrkijy.html

TS:   arr.includes(x)
来源：http://dali.jinqigufen.top/Article/details/gtklcnthju.html

Java: list.contains(x)
来源：http://dali.yanxiufei.cn/Article/details/gtgihoijet.html

Go:   slices.Contains(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcmfgfmmu.html

Ruby: arr.include?(x)
来源：http://dali.jyoumei.cn/Article/details/gtsfsecxzo.html

C#:   list.Contains(x)
来源：http://dali.cheryme.top/Article/details/gtwdaejzvz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yj20258.top/Article/details/gtftyqgzek.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xziqi.cn/Article/details/gtnpjtfxdq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ivvv.top/Article/details/gtjqxfcifc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ybcxt.top/Article/details/gtdjqugwki.html

TS:   [...arr];
来源：http://dali.shzxlz.cn/Article/details/gthbaptxnv.html

Java: new ArrayList<>(list);
来源：http://dali.nanxinkj.top/Article/details/gtabpmaync.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ppjwa.cn/Article/details/gtrvszrvjh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hysaishi.cn/Article/details/gtctsuqsmr.html

C#:   new List<int>(list);
来源：http://dali.yj20258888.top/Article/details/gttcrwhoaf.html

[D23] reduce 累积计算
来源：http://dali.jinqigfzy.top/Article/details/gtzcscvfqb.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtbkootwqc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yj20258888.top/Article/details/gtfgugbtlp.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.mhx1999.top/Article/details/gtuuqrkful.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigufen.top/Article/details/gtahirhpkj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hfpthk.cn/Article/details/gtdsvyrxck.html

Go:   // 手写循环
来源：http://dali.shuidangran.top/Article/details/gtkaamgltn.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yueranfly.top/Article/details/gtrpyvmhdu.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhongyouzk.top/Article/details/gtglnbkmfc.html

[D24] 字典 / Map 基本操作
来源：http://dali.tianlin.xyz/Article/details/gtazdfaeih.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ehwqpu.com/Article/details/gtrampafqc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yonumen.top/Article/details/gtjgkfcvxk.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthjttmrby.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zycfv.cn/Article/details/gteepqhtkd.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.nanxinkj.top/Article/details/gtpocyvcre.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.nanxinkj.top/Article/details/gtzrtodwbj.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gogol.net.cn/Article/details/gtwgdnswep.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.haohaochexian.top/Article/details/gtnlhlspqn.html

[D25] Set 集合去重与交并差
来源：http://dali.zhiwuduotai.top/Article/details/gtrvefrvcl.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.mhx1999.top/Article/details/gtreqtjgvj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.chenzaomai.com/Article/details/gtzqpgxmvm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.gaohongyu789.top/Article/details/gtphsfyqym.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shuidangran.top/Article/details/gtfnblivwm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yuxming.cn/Article/details/gtoylwmrhp.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.guowangkeji.top/Article/details/gtngdqagbr.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zdqjudy.top/Article/details/gtqmrkofnl.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.snrcjt.cn/Article/details/gtluxeezus.html

[D26] 数组转字符串
来源：http://dali.tianlin.xyz/Article/details/gtluststgc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrljkasyl.html

PHP:  implode(", ", $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxdesaxha.html

JS:   arr.join(", ")
来源：http://dali.jlsjyb.cn/Article/details/gtwhyggqvf.html

TS:   arr.join(", ")
来源：http://dali.9152youxi.cn/Article/details/gtrnehtxdt.html

Java: String.join(", ", list)
来源：http://dali.jqgfzy.top/Article/details/gtpirjusoa.html

Go:   strings.Join(strs, ", ")
来源：http://dali.gaohongyu789.top/Article/details/gtxnjnriua.html

Ruby: arr.join(", ")
来源：http://dali.sufxvd.cn/Article/details/gthhekvwuy.html

C#:   string.Join(", ", list)
来源：http://dali.hnxiangtu.top/Article/details/gtnvdptvxm.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gttoploeok.html

E. 字符串处理
来源：http://dali.havefunace.top/Article/details/gthkpvdlxs.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtikomhkji.html

[E01] 拼接字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtipektzez.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.wangshuangyany.cn/Article/details/gtxxdaveyw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtksujqgqv.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yanxiufei.cn/Article/details/gttsnpmuxe.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yanxiufei.cn/Article/details/gtaevgvjrv.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yonumen.top/Article/details/gtgjjxqvtp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.andypj.xyz/Article/details/gteleqprrq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xuetiantiany.cn/Article/details/gtzpxhxbgk.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sweek.top/Article/details/gtmbgputtp.html

[E02] 重复字符串
来源：http://dali.sweek.top/Article/details/gthyjglffk.html

Py:   "ab" * 3
来源：http://dali.tanke756.top/Article/details/gtizcfvcct.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gzhubu.top/Article/details/gtshumaryb.html

JS:   "ab".repeat(3)
来源：http://dali.guowangkeji.top/Article/details/gtoudsnqer.html

TS:   "ab".repeat(3)
来源：http://dali.zhixingplan.top/Article/details/gtunmriouc.html

Java: "ab".repeat(3)
来源：http://dali.quarkkingdee.top/Article/details/gtqttxywxd.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ehwqpu.com/Article/details/gtfvfmwqej.html

Ruby: "ab" * 3
来源：http://dali.pycfn.com/Article/details/gtekvnntxg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yuanzhike.top/Article/details/gtzllonytb.html

[E03] 截取子串
来源：http://dali.jqgfzy.top/Article/details/gtihgtzzxo.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jyoumei.cn/Article/details/gtbqbevnrl.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.nanxinkj.top/Article/details/gtidghldmo.html


<!-- 参考信息 -->