代发 wailian999

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhengqikj.top/Article/details/gttdlgvnza.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ppjwa.cn/Article/details/gtxkwyxexd.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhiwuduotai.top/Article/details/gtemiyjiac.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtbvovuyfv.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yonumen.top/Article/details/gtqqtxerow.html

Go:   func add(a, b int) int
来源：http://dali.mhx1999.top/Article/details/gtpamnecho.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.bjfxy.top/Article/details/gtirqvkzer.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.guowangkeji.top/Article/details/gtkszwuyif.html

[C14] 泛型函数
来源：http://dali.xuanzx.com/Article/details/gtzlyohkkw.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ydzc1.top/Article/details/gtcqlgjbdu.html

PHP:  // 无泛型
来源：http://dali.wangshuangyany.cn/Article/details/gtwrytgcbz.html

JS:   // 无泛型
来源：http://dali.kuanghao11.cn/Article/details/gtrkrvodgp.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.svipenyu.cn/Article/details/gtfchcvjwi.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.sweek.top/Article/details/gtdnjmznjf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.snrcjt.cn/Article/details/gteonjbylu.html

Ruby: # 无泛型
来源：http://dali.fzhhl.top/Article/details/gthkzlzgav.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xylfe.cn/Article/details/gtewgrtmee.html

[C15] 解构 / 展开参数
来源：http://dali.jiagoushi.top/Article/details/gthvmbllpk.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xziqi.cn/Article/details/gtqihwjvqp.html

PHP:  [$a, $b] = $pair;
来源：http://dali.gotoacloud.top/Article/details/gtzvoztdze.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hnqzz.top/Article/details/gtdmmirhct.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yueranfly.top/Article/details/gtwdtqobhv.html

Java: // 无解构
来源：http://dali.smart0.xyz/Article/details/gtqrymebxq.html

Go:   // 无解构
来源：http://dali.jinqigufen.top/Article/details/gtintgazbm.html

Ruby: a, b = pair
来源：http://dali.shzxlz.cn/Article/details/gtlaemryez.html

C#:   var (a, b) = pair;
来源：http://dali.cdnleiting.top/Article/details/gtvpedilht.html

[C16] 函数 / 方法重载
来源：http://dali.jyoumei.cn/Article/details/gtlkwrxioq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.sweek.top/Article/details/gtpuodeuvk.html

PHP:  // 无重载
来源：http://dali.0kj1m.cn/Article/details/gtjzirfyyz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cqqwz.cn/Article/details/gteajgttkc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.havefunace.top/Article/details/gtznyhaaaz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.mhx1999.top/Article/details/gtndvxoqsu.html

Go:   // 无重载：用不同函数名
来源：http://dali.yvedp.cn/Article/details/gtucgxiwgh.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hongshengwenyu.top/Article/details/gtjbtqcpft.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtinjtlsyd.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtwmjkjayu.html

D. 数组 / 列表 / 集合
来源：http://dali.birdmap.top/Article/details/gtxrwzhvbs.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtfhtaeuhn.html

[D01] 创建数组 / 列表
来源：http://dali.cdnleiting.top/Article/details/gtvinaosxo.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hnqzz.top/Article/details/gtmavzezdg.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.aizwys.cn/Article/details/gtosasfadf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.fzhhl.top/Article/details/gtgwkbibcg.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jinghuilouyu.cn/Article/details/gtgazfwhfz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhengqikj.top/Article/details/gthzohdpit.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yuxming.cn/Article/details/gthpjngcjj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhoulong.xyz/Article/details/gtcursdjvt.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcambndrk.html

[D02] 追加元素到末尾
来源：http://dali.xziqi.cn/Article/details/gtiguyruje.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.nwbrower.top/Article/details/gtcoikujzv.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xuetiantiany.cn/Article/details/gtlekxnjnj.html

JS:   arr.push(4);
来源：http://dali.jqgfzy.top/Article/details/gtwumxemfo.html

TS:   arr.push(4);
来源：http://dali.chenzaomai.com/Article/details/gtieyvuquz.html

Java: list.add(4);
来源：http://dali.chenlongwang.top/Article/details/gtsfliwovs.html

Go:   arr = append(arr, 4)
来源：http://dali.cashguo.top/Article/details/gtmzlpnmah.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqfraymwe.html

C#:   list.Add(4);
来源：http://dali.havefunace.top/Article/details/gtjiwmzrxz.html

[D03] 在指定位置插入元素
来源：http://dali.fzhhl.top/Article/details/gtcofsrhca.html

Py:   arr.insert(0, 0)
来源：http://dali.andypj.xyz/Article/details/gtncgqsbws.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jinqigufen.top/Article/details/gttvjdielq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.pengpengdd.cyou/Article/details/gtmvljhwio.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.0kj1m.cn/Article/details/gthwbdmtog.html

Java: list.add(0, 0);
来源：http://dali.nanxuanxn.top/Article/details/gtvwuhwaih.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shangyingyoupin.top/Article/details/gtawmuvyag.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gtxskylygi.html

C#:   list.Insert(0, 0);
来源：http://dali.jianghu66.top/Article/details/gtesjdtrec.html

[D04] 删除元素
来源：http://dali.smart0.xyz/Article/details/gtstjtbqfm.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.aibaodan.cn/Article/details/gtlcznibuo.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.dashuyun.cn/Article/details/gtvbgtjbuz.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.nwbrower.top/Article/details/gtxakhqqpw.html

TS:   arr.splice(0, 1);
来源：http://dali.nwbrower.top/Article/details/gtwtvivtqg.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.bjfxy.top/Article/details/gtyshjjftq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.cashguo.top/Article/details/gteeymtssb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xuanzx.com/Article/details/gtpmhxvgcs.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cucudq.cn/Article/details/gtubskcybx.html

[D05] 访问与修改元素
来源：http://dali.hongshengwenyu.top/Article/details/gtksfbzrtq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ydzc1.top/Article/details/gtorafjkcl.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ydzc1.top/Article/details/gthuevvkou.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cqqwz.cn/Article/details/gtjngrcvnq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhengqikj.top/Article/details/gtgmngznye.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.0kj1m.cn/Article/details/gtrorgvrgr.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.dashuyun.cn/Article/details/gtqovhvois.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhixingplan.top/Article/details/gtkotvgzfo.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yj20258.top/Article/details/gtglrmqtvw.html

[D06] 数组长度
来源：http://dali.daxiang520.top/Article/details/gtfcaiiwpz.html

Py:   len(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtffggnjjo.html

PHP:  count($arr);
来源：http://dali.svipenyu.cn/Article/details/gtrzmrnthx.html

JS:   arr.length
来源：http://dali.hammf.cn/Article/details/gtnqosrkxm.html

TS:   arr.length
来源：http://dali.jqgfzy.top/Article/details/gtalnrssjc.html

Java: list.size();
来源：http://dali.sweek.top/Article/details/gtzekvxljk.html

Go:   len(arr)
来源：http://dali.hammf.cn/Article/details/gtmchzhqkq.html

Ruby: arr.length; arr.size
来源：http://dali.tian-w.cn/Article/details/gtyijacmxy.html

C#:   list.Count;
来源：http://dali.316326.xyz/Article/details/gttpnurxbt.html

[D07] 切片 / 取子数组
来源：http://dali.xylfe.cn/Article/details/gtkfddkjoo.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtetfeqmrn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jqgufenzy.top/Article/details/gtchacqzwp.html

JS:   arr.slice(1, 4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxfrykamm.html

TS:   arr.slice(1, 4);
来源：http://dali.redwolf501.top/Article/details/gtxrftguiy.html

Java: list.subList(1, 4);
来源：http://dali.yj202588.top/Article/details/gtuvjagfof.html

Go:   arr[1:4]
来源：http://dali.shanyushiyangtech.top/Article/details/gtwnatzcqe.html

Ruby: arr[1, 3]
来源：http://dali.chenjidiqi.icu/Article/details/gtqdcpnrzc.html

C#:   list.GetRange(1, 3);
来源：http://dali.shuidangran.top/Article/details/gtqatxmogm.html

[D08] 合并两个数组
来源：http://dali.zhixingplan.top/Article/details/gtzpjlthec.html

Py:   a + b;  a.extend(b)
来源：http://dali.yuanzhike.top/Article/details/gtbccxetnw.html

PHP:  array_merge($a, $b);
来源：http://dali.nwbrower.top/Article/details/gtdrhjtitm.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sweek.top/Article/details/gtbqpnskwm.html

TS:   [...a, ...b];
来源：http://dali.jqgfzy.top/Article/details/gtsrsvgioj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sweek.top/Article/details/gtjmniktwr.html

Go:   append(a, b...)
来源：http://dali.hongshengwenyu.top/Article/details/gtprgeyobv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xziqi.cn/Article/details/gtmnltjyot.html

C#:   a.Concat(b).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gtxarmsxbh.html

[D09] 排序（升序）
来源：http://dali.jqgfzy.top/Article/details/gtjvsoxqbc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zdqjudy.top/Article/details/gtthnivfap.html

PHP:  sort($arr);
来源：http://dali.meibo888.top/Article/details/gtgascbqdu.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.fengsongda.top/Article/details/gtgaadnwkm.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.aibaodan.cn/Article/details/gtekdrhsuy.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.vqdsnc.cn/Article/details/gtervysenc.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtoidteunb.html

Ruby: arr.sort
来源：http://dali.meibo888.top/Article/details/gtozdqmpvj.html

C#:   list.Sort();
来源：http://dali.quarkkingdee.top/Article/details/gtnczfkfgz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.gogol.net.cn/Article/details/gtekjbqjpv.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cqqwz.cn/Article/details/gtqkriobft.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.iojbl.cn/Article/details/gtcaaldxpm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhengqikj.top/Article/details/gtxakgfwlb.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yanxiufei.cn/Article/details/gtxngqoboy.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.smart0.xyz/Article/details/gtddjhzkpv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.aibaodan.cn/Article/details/gtgfftryko.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yj20258888.top/Article/details/gtfypziuov.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.kuanghao11.cn/Article/details/gtvyqfskdp.html

[D11] 反转数组
来源：http://dali.cqqwz.cn/Article/details/gtrjuwjgzu.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zdqjudy.top/Article/details/gtvyuvdjrd.html

PHP:  array_reverse($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtfkiubwsp.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.chenjidiqi.icu/Article/details/gtxpkksxbk.html

TS:   [...arr].reverse();
来源：http://dali.yongpay.top/Article/details/gtjbtzcblo.html

Java: Collections.reverse(list);
来源：http://dali.gaohongyu789.top/Article/details/gtmyxrnbxu.html

Go:   slices.Reverse(arr)
来源：http://dali.zhengqikj.top/Article/details/gtbsutullp.html

Ruby: arr.reverse
来源：http://dali.fzhhl.top/Article/details/gtesqkjxyr.html

C#:   list.Reverse();
来源：http://dali.sufxvd.cn/Article/details/gtrmvqpfnu.html

[D12] 查找元素下标
来源：http://dali.zycfv.cn/Article/details/gtqsjonudh.html

Py:   arr.index(x);  x in arr
来源：http://dali.ehwqpu.com/Article/details/gtoyhspgnw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.c1oappe.top/Article/details/gteaunhywd.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jiagoushi.top/Article/details/gtlpbkgwyi.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sufxvd.cn/Article/details/gtvzchjuum.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.guowangkeji.top/Article/details/gtdwzwwrll.html

Go:   slices.Index(arr, x)
来源：http://dali.yvedp.cn/Article/details/gthvmvfrkj.html

Ruby: arr.index(x)
来源：http://dali.tian-w.cn/Article/details/gtorvrumxj.html

C#:   list.IndexOf(x);
来源：http://dali.pycfn.com/Article/details/gtapyeiinp.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yonumen.top/Article/details/gtdbkewtvd.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.chenzaomai.com/Article/details/gtrdadhsom.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.sxryk.cn/Article/details/gtpvhttanm.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sweek.top/Article/details/gtltclnduw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hysaishi.cn/Article/details/gtfrlergld.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.tanke756.top/Article/details/gtnlhhdkor.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yongpay.top/Article/details/gtanyjcxhz.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cucudq.cn/Article/details/gtxxvhllha.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtgisijfav.html

[D14] 映射转换（每个元素变形）
来源：http://dali.vqdsnc.cn/Article/details/gtznojremh.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.fzhhl.top/Article/details/gtficaoptq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtdlawcvry.html

JS:   arr.map(x => x * 2)
来源：http://dali.yanxiufei.cn/Article/details/gtfmxelbuf.html

TS:   arr.map(x => x * 2)
来源：http://dali.yanxiufei.cn/Article/details/gtniergmzw.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jqgfzy.top/Article/details/gtyoxrlbsk.html

Go:   // 手写循环
来源：http://dali.ivvv.top/Article/details/gtixzknolw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.fzhhl.top/Article/details/gtvscydmnj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.pycfn.com/Article/details/gtsibobwko.html

[D15] 去重
来源：http://dali.yonumen.top/Article/details/gttswsjcxv.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.dianchejie.cn/Article/details/gthcsrwrtg.html

PHP:  array_unique($arr);
来源：http://dali.yvedp.cn/Article/details/gtydncbijw.html

JS:   [...new Set(arr)]
来源：http://dali.hnqzz.top/Article/details/gtycoldegt.html

TS:   [...new Set(arr)]
来源：http://dali.yangfankeji.com/Article/details/gtmthssiyj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.fzhhl.top/Article/details/gtcgxilmdu.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.birdmap.top/Article/details/gtglkxxcaa.html

Ruby: arr.uniq
来源：http://dali.yuanzhike.top/Article/details/gtcutoccrm.html

C#:   list.Distinct().ToList()
来源：http://dali.sufxvd.cn/Article/details/gtsbrymkuj.html

[D16] 求和与平均值
来源：http://dali.xinyue.icu/Article/details/gtkpvetype.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.chenlongwang.top/Article/details/gtjsjlnglu.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtzykygenq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sysykeji.top/Article/details/gtavkunblh.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtkgcrujre.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ivvv.top/Article/details/gtvxrpwgqx.html

Go:   // 手写循环累加
来源：http://dali.meibo888.top/Article/details/gteovriauj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yvedp.cn/Article/details/gthoionkjs.html

C#:   list.Sum();  list.Average()
来源：http://dali.jqgufenzy.top/Article/details/gtixtltdul.html

[D17] 最大值与最小值
来源：http://dali.xziqi.cn/Article/details/gtdatdhqql.html

Py:   max(arr);  min(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtuepqklwf.html

PHP:  max($arr);  min($arr);
来源：http://dali.svipenyu.cn/Article/details/gtwqkjucxt.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.sufxvd.cn/Article/details/gtlajgfdoe.html

TS:   Math.max(...arr);
来源：http://dali.nanxuanxn.top/Article/details/gtmbzgrydu.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cucudq.cn/Article/details/gtbrzejoth.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.aizwys.cn/Article/details/gtpxozshgo.html

Ruby: arr.max;  arr.min
来源：http://dali.cheryme.top/Article/details/gtfixezdjw.html

C#:   list.Max();  list.Min()
来源：http://dali.yongpay.top/Article/details/gtvydpyrjj.html

[D18] 扁平化嵌套数组
来源：http://dali.cdnleiting.top/Article/details/gtoydgjafz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shuidangran.top/Article/details/gtmjzeopqb.html

PHP:  array_merge(...$nested);
来源：http://dali.ivvv.top/Article/details/gtmxqnacnc.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.haohaochexian.top/Article/details/gtzmygiklc.html

TS:   nested.flat();
来源：http://dali.chenlongwang.top/Article/details/gtpkljaaqe.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jyoumei.cn/Article/details/gtrgpacpdj.html

Go:   // 手写双层循环
来源：http://dali.yongpay.top/Article/details/gtibwnxjwd.html

Ruby: nested.flatten
来源：http://dali.chenlongwang.top/Article/details/gthrigztod.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.0kj1m.cn/Article/details/gtrtieaccs.html

[D19] 按字段分组
来源：http://dali.kuanghao11.cn/Article/details/gthutwihkq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjsysoesu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cucudq.cn/Article/details/gtvrjtpwrn.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hammf.cn/Article/details/gttslisira.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hysaishi.cn/Article/details/gtowcsdpfc.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.0kj1m.cn/Article/details/gtybciqnek.html

Go:   // 手写 map[string][]T
来源：http://dali.zhaomingkeji.xyz/Article/details/gttoutslbf.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hfpthk.cn/Article/details/gtgrkpedcn.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.wangdashe.top/Article/details/gtssyxepix.html

[D20] 统计每个元素出现次数
来源：http://dali.316326.xyz/Article/details/gtdfrwzzba.html

Py:   Counter(arr)
来源：http://dali.cheryme.top/Article/details/gtgmgayrmk.html

PHP:  array_count_values($arr);
来源：http://dali.gotoacloud.top/Article/details/gtivnkexrh.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnxiangtu.top/Article/details/gthqknbcjw.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pengpengdd.cyou/Article/details/gtqdsqeaue.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hammf.cn/Article/details/gthlbegzen.html

Go:   // 手写 map[T]int
来源：http://dali.mhx1999.top/Article/details/gtbcphgccb.html

Ruby: arr.tally
来源：http://dali.bjfxy.top/Article/details/gtlhedlcqk.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ivvv.top/Article/details/gtfflqfgjb.html

[D21] 判断是否包含某元素
来源：http://dali.jinqigufen.top/Article/details/gtehihdgrg.html

Py:   x in arr
来源：http://dali.nanxuanxn.top/Article/details/gtxhhkqahx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.9152youxi.cn/Article/details/gtxisnufnz.html

JS:   arr.includes(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthuqfgwow.html

TS:   arr.includes(x)
来源：http://dali.cashguo.top/Article/details/gthtwdfnxq.html

Java: list.contains(x)
来源：http://dali.cqqwz.cn/Article/details/gtrwlvwhpt.html

Go:   slices.Contains(arr, x)
来源：http://dali.fzhhl.top/Article/details/gtwerjkjsn.html

Ruby: arr.include?(x)
来源：http://dali.yonumen.top/Article/details/gtzbimoitc.html

C#:   list.Contains(x)
来源：http://dali.cdnleiting.top/Article/details/gttekqgucf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hnxiangtu.top/Article/details/gtcnlvexup.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhengqikj.top/Article/details/gtmdnycmry.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ywan-chungtsiang.top/Article/details/gtktngcera.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.wangdashe.top/Article/details/gtxziovhri.html

TS:   [...arr];
来源：http://dali.xylfe.cn/Article/details/gtzkidemfs.html

Java: new ArrayList<>(list);
来源：http://dali.gaohongyu789.top/Article/details/gtgwqdxcfw.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnlbiiusd.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yangfankeji.com/Article/details/gthkeonswn.html

C#:   new List<int>(list);
来源：http://dali.pycfn.com/Article/details/gtbnnvgopu.html

[D23] reduce 累积计算
来源：http://dali.cqqwz.cn/Article/details/gtfanpdxvy.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.chenzaomai.com/Article/details/gtbpcczkoz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.sufxvd.cn/Article/details/gtwwuxnqsv.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.wangdashe.top/Article/details/gtbqzuwoyc.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hnqzz.top/Article/details/gtqngotgwx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ivvv.top/Article/details/gtebjmnsaw.html

Go:   // 手写循环
来源：http://dali.iojbl.cn/Article/details/gtencxuxvg.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ybcxt.top/Article/details/gtkodqrjyt.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.fengsongda.top/Article/details/gtaqqixpfm.html

[D24] 字典 / Map 基本操作
来源：http://dali.gogol.net.cn/Article/details/gtmtjjheee.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.daria6918.cn/Article/details/gtqqurlwwu.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jianghu66.top/Article/details/gtmfxwgcoi.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgaildkfy.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cqqwz.cn/Article/details/gtajarzmwa.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtavjerwil.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.aibaodan.cn/Article/details/gtncpwvmgh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ivvv.top/Article/details/gtxvsjzfdq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yanxiufei.cn/Article/details/gtmsgpxodm.html

[D25] Set 集合去重与交并差
来源：http://dali.hywenlv.cn/Article/details/gtdvknzjlg.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.tianlin.xyz/Article/details/gtqkqdkqod.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hnqzz.top/Article/details/gtjatytfik.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhoulong.xyz/Article/details/gtbvgwhmle.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zycfv.cn/Article/details/gtmvsvpbeq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gotoacloud.top/Article/details/gtrmnmgzsb.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhoulong.xyz/Article/details/gtbkntlcoq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cdnleiting.top/Article/details/gtzmgtbtzn.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.iojbl.cn/Article/details/gtwyueqfho.html

[D26] 数组转字符串
来源：http://dali.wangdashe.top/Article/details/gtgjploalp.html

Py:   ", ".join(map(str, arr))
来源：http://dali.andypj.xyz/Article/details/gtksviojdw.html

PHP:  implode(", ", $arr);
来源：http://dali.yuxming.cn/Article/details/gtutbmnufk.html

JS:   arr.join(", ")
来源：http://dali.9152youxi.cn/Article/details/gtmpfnolik.html

TS:   arr.join(", ")
来源：http://dali.0kj1m.cn/Article/details/gtajkzrrvy.html

Java: String.join(", ", list)
来源：http://dali.pycfn.com/Article/details/gtihjalste.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yangfankeji.com/Article/details/gtwmxtpsfh.html

Ruby: arr.join(", ")
来源：http://dali.hywenlv.cn/Article/details/gtftrzsiqv.html

C#:   string.Join(", ", list)
来源：http://dali.iojbl.cn/Article/details/gtysospgfy.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtkvkhvuqq.html

E. 字符串处理
来源：http://dali.ppjwa.cn/Article/details/gtbropaevs.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtudciscmh.html

[E01] 拼接字符串
来源：http://dali.yanxiufei.cn/Article/details/gtjbtzfdkr.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yj202588.top/Article/details/gtelhxzmah.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.cashguo.top/Article/details/gtfdrkbfft.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daxiang520.top/Article/details/gtzgmgflvc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnxiangtu.top/Article/details/gtewdrxrwd.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhengqikj.top/Article/details/gtwckxibzy.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.tian-w.cn/Article/details/gtptycbcwg.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jinqigufen.top/Article/details/gtvygdbsbk.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtjvedffkm.html

[E02] 重复字符串
来源：http://dali.nwbrower.top/Article/details/gtitvzipwp.html

Py:   "ab" * 3
来源：http://dali.daria6918.cn/Article/details/gtbnyuqjph.html

PHP:  str_repeat("ab", 3);
来源：http://dali.smart0.xyz/Article/details/gtspjosqyh.html

JS:   "ab".repeat(3)
来源：http://dali.cheryme.top/Article/details/gtysudsvji.html

TS:   "ab".repeat(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtulzyferq.html

Java: "ab".repeat(3)
来源：http://dali.bjfxy.top/Article/details/gtjvvckeal.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.tian-w.cn/Article/details/gtydebiwkr.html

Ruby: "ab" * 3
来源：http://dali.guannengcc.top/Article/details/gtncevfsbv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yongpay.top/Article/details/gtrpqmmdvx.html

[E03] 截取子串
来源：http://dali.jinghuilouyu.cn/Article/details/gttmetyfwv.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.meibo888.top/Article/details/gttdmbliii.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gtlgxqthfy.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jqgufenzy.top/Article/details/gtjvyqxnej.html

TS:   s.slice(1, 4)
来源：http://dali.nanxinkj.top/Article/details/gtrztvfisn.html

Java: s.substring(1, 4)
来源：http://dali.jqgufenzy.top/Article/details/gtgxremsdc.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jqgfzy.top/Article/details/gtocrbkkoj.html


<!-- 参考信息 -->