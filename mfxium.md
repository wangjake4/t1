代发 wailian999

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zycfv.cn/Article/details/gtwfskbfis.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnqzz.top/Article/details/gtctmsjcls.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jinqigfzy.top/Article/details/gtcgtvtrxf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gtwnghpyvy.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gtqgfvjzsf.html

Go:   func add(a, b int) int
来源：http://dali.jyoumei.cn/Article/details/gtwzmzqpfj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yuxming.cn/Article/details/gtteujvvpi.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yvedp.cn/Article/details/gtvzxhlmnc.html

[C14] 泛型函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtoyilpfgp.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.guannengcc.top/Article/details/gtsrwixraw.html

PHP:  // 无泛型
来源：http://dali.zhongyouzk.top/Article/details/gtygvmuihx.html

JS:   // 无泛型
来源：http://dali.hysaishi.cn/Article/details/gtveciotqz.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.chenzaomai.com/Article/details/gtqvkoogkw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jqgufenzy.top/Article/details/gtjdozfnil.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yj20258.top/Article/details/gthfkyfyur.html

Ruby: # 无泛型
来源：http://dali.aibaodan.cn/Article/details/gtlvlypibm.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yuanzhike.top/Article/details/gtzdifwcqz.html

[C15] 解构 / 展开参数
来源：http://dali.hnqzz.top/Article/details/gtkuujscmk.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jianghu66.top/Article/details/gtlxhzoctw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.tianlin.xyz/Article/details/gtofvibntx.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.haohaochexian.top/Article/details/gtoiljbxpe.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cdnleiting.top/Article/details/gtabahoqnr.html

Java: // 无解构
来源：http://dali.jinghuilouyu.cn/Article/details/gtrtrwhfom.html

Go:   // 无解构
来源：http://dali.hongshengwenyu.top/Article/details/gtaxgcsqnd.html

Ruby: a, b = pair
来源：http://dali.xziqi.cn/Article/details/gtsbvkeumx.html

C#:   var (a, b) = pair;
来源：http://dali.tian-w.cn/Article/details/gtdlssozlc.html

[C16] 函数 / 方法重载
来源：http://dali.svipenyu.cn/Article/details/gtdmbpfwbq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.tian-w.cn/Article/details/gtjqufviuf.html

PHP:  // 无重载
来源：http://dali.316326.xyz/Article/details/gtmvckhecm.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.tian-w.cn/Article/details/gtoawslfeu.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jqgufenzy.top/Article/details/gtghhhbtse.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtasfuashn.html

Go:   // 无重载：用不同函数名
来源：http://dali.yanxiufei.cn/Article/details/gtaibrekjr.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gaohongyu789.top/Article/details/gtwdzskgzd.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gterlpnrfb.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtfxoszwjc.html

D. 数组 / 列表 / 集合
来源：http://dali.zhiwuduotai.top/Article/details/gtknobniud.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtztzzdoiw.html

[D01] 创建数组 / 列表
来源：http://dali.xylfe.cn/Article/details/gtadsqwlzi.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.c1oappe.top/Article/details/gtpcfvsbpe.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.pycfn.com/Article/details/gtwcvowocq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.feifeiyinyue.top/Article/details/gtvbxpevrc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.birdmap.top/Article/details/gtbnbvprhz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.sysykeji.top/Article/details/gtpqnrjmqu.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xinyue.icu/Article/details/gtufrgxrub.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jqgufenzy.top/Article/details/gtydxddvnq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jyoumei.cn/Article/details/gtmftxqfjm.html

[D02] 追加元素到末尾
来源：http://dali.ivvv.top/Article/details/gtgcmxqagj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xylfe.cn/Article/details/gtqdqgksej.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.9152youxi.cn/Article/details/gtjjsbmbtt.html

JS:   arr.push(4);
来源：http://dali.xuetiantiany.cn/Article/details/gtpggxgtox.html

TS:   arr.push(4);
来源：http://dali.svipenyu.cn/Article/details/gtrgykbcpn.html

Java: list.add(4);
来源：http://dali.meibo888.top/Article/details/gtbkutquns.html

Go:   arr = append(arr, 4)
来源：http://dali.gzhubu.top/Article/details/gtbkttnouo.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmxsmfixl.html

C#:   list.Add(4);
来源：http://dali.chenlongwang.top/Article/details/gtreazvgnd.html

[D03] 在指定位置插入元素
来源：http://dali.hnqzz.top/Article/details/gtyxzjccuw.html

Py:   arr.insert(0, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtruqxytrw.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrrrpnyes.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jinqigfzy.top/Article/details/gtayovlajd.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.guannengcc.top/Article/details/gtwfbbphjd.html

Java: list.add(0, 0);
来源：http://dali.shuidangran.top/Article/details/gtrcgipvyb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sweek.top/Article/details/gtwuziwipq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cucudq.cn/Article/details/gtnjiafnlh.html

C#:   list.Insert(0, 0);
来源：http://dali.xuanzx.com/Article/details/gtyjsbalwe.html

[D04] 删除元素
来源：http://dali.dianchejie.cn/Article/details/gtrnxotevh.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yj202588.top/Article/details/gtsmowrttu.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jiagoushi.top/Article/details/gtygigfgvc.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.chenjidiqi.icu/Article/details/gtvagkalzg.html

TS:   arr.splice(0, 1);
来源：http://dali.daxiang520.top/Article/details/gtrtgrwuom.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ybcxt.top/Article/details/gtljwehplp.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.tianlin.xyz/Article/details/gtigwypdxm.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xuanzx.com/Article/details/gtzqowtxkj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hongshengwenyu.top/Article/details/gtwodikpuh.html

[D05] 访问与修改元素
来源：http://dali.sweek.top/Article/details/gtrtcdvavr.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hysaishi.cn/Article/details/gtwzafgvkb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yangfankeji.com/Article/details/gtdqnlvdep.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.tianlin.xyz/Article/details/gtmpkbxebz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cdnleiting.top/Article/details/gtsdoqdjtc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shanyushiyangtech.top/Article/details/gtdadpgcas.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.nanxinkj.top/Article/details/gtosbwszkb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnfygcfid.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.tianlin.xyz/Article/details/gtipfqpdwd.html

[D06] 数组长度
来源：http://dali.zhengqikj.top/Article/details/gtfuopeuuc.html

Py:   len(arr)
来源：http://dali.cashguo.top/Article/details/gttscrqmls.html

PHP:  count($arr);
来源：http://dali.yj20258888.top/Article/details/gtftbpvdbw.html

JS:   arr.length
来源：http://dali.0kj1m.cn/Article/details/gtpkgdqbod.html

TS:   arr.length
来源：http://dali.c1oappe.top/Article/details/gtclprhkfh.html

Java: list.size();
来源：http://dali.yonumen.top/Article/details/gtqjwocdvu.html

Go:   len(arr)
来源：http://dali.yj20258888.top/Article/details/gtoxusndbi.html

Ruby: arr.length; arr.size
来源：http://dali.gzhubu.top/Article/details/gttzzudrml.html

C#:   list.Count;
来源：http://dali.pycfn.com/Article/details/gtljgkulwr.html

[D07] 切片 / 取子数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtohwcozrn.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.316326.xyz/Article/details/gtlkjfkwrr.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhoulong.xyz/Article/details/gtkturamkb.html

JS:   arr.slice(1, 4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwdzrthzq.html

TS:   arr.slice(1, 4);
来源：http://dali.xziqi.cn/Article/details/gtequxulwd.html

Java: list.subList(1, 4);
来源：http://dali.jinqigufen.top/Article/details/gtcotsokgd.html

Go:   arr[1:4]
来源：http://dali.tian-w.cn/Article/details/gtrihlvngf.html

Ruby: arr[1, 3]
来源：http://dali.jqgfzy.top/Article/details/gtesydttcs.html

C#:   list.GetRange(1, 3);
来源：http://dali.c1oappe.top/Article/details/gttkhoztdn.html

[D08] 合并两个数组
来源：http://dali.316326.xyz/Article/details/gtdnqrqkap.html

Py:   a + b;  a.extend(b)
来源：http://dali.yuanzhike.top/Article/details/gtxppotdnj.html

PHP:  array_merge($a, $b);
来源：http://dali.snrcjt.cn/Article/details/gtqdwszwvh.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.gotoacloud.top/Article/details/gtgovdcokn.html

TS:   [...a, ...b];
来源：http://dali.yuxming.cn/Article/details/gtbuhygmnw.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.cashguo.top/Article/details/gtmjtrcdbq.html

Go:   append(a, b...)
来源：http://dali.iojbl.cn/Article/details/gthismwxod.html

Ruby: a + b;  a.concat(b)
来源：http://dali.svipenyu.cn/Article/details/gtetpzxrct.html

C#:   a.Concat(b).ToList()
来源：http://dali.andypj.xyz/Article/details/gtmzrikhgl.html

[D09] 排序（升序）
来源：http://dali.hysaishi.cn/Article/details/gtmewbfnfe.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gaohongyu789.top/Article/details/gtpftgdflt.html

PHP:  sort($arr);
来源：http://dali.yvedp.cn/Article/details/gtxgskakmj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yuanzhike.top/Article/details/gtkycuwxto.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.sysykeji.top/Article/details/gtgbvqbgxm.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvxzcjxvn.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ybcxt.top/Article/details/gtxzsibwcb.html

Ruby: arr.sort
来源：http://dali.smart0.xyz/Article/details/gtpsqhnwic.html

C#:   list.Sort();
来源：http://dali.sufxvd.cn/Article/details/gtxuzepyrj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.wangdashe.top/Article/details/gtxxdpotis.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.dianchejie.cn/Article/details/gtkxtrbizi.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cqqwz.cn/Article/details/gtvsyztovn.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.mhx1999.top/Article/details/gtkhznvdlt.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenlongwang.top/Article/details/gtkgukpiao.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cucudq.cn/Article/details/gtubolphhm.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.snrcjt.cn/Article/details/gtcxzuoeey.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.daxiang520.top/Article/details/gtjwxoamqc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.sweek.top/Article/details/gtuxaefkqf.html

[D11] 反转数组
来源：http://dali.bjfxy.top/Article/details/gthvyezdjr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ybcxt.top/Article/details/gtdniqckzr.html

PHP:  array_reverse($arr);
来源：http://dali.nanxinkj.top/Article/details/gtiwxwsvmk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cashguo.top/Article/details/gtqcwhpafe.html

TS:   [...arr].reverse();
来源：http://dali.svipenyu.cn/Article/details/gtwrgyjmvx.html

Java: Collections.reverse(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gtrwjyirzm.html

Go:   slices.Reverse(arr)
来源：http://dali.hnqzz.top/Article/details/gtfpdftrus.html

Ruby: arr.reverse
来源：http://dali.ybcxt.top/Article/details/gthtrvarsh.html

C#:   list.Reverse();
来源：http://dali.wangshuangyany.cn/Article/details/gtnniwogqu.html

[D12] 查找元素下标
来源：http://dali.yuanzhike.top/Article/details/gtjnsfiscc.html

Py:   arr.index(x);  x in arr
来源：http://dali.xylfe.cn/Article/details/gteacgxeqs.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.redwolf501.top/Article/details/gtqefbqexk.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yonumen.top/Article/details/gtgthjkwjn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj20258.top/Article/details/gtommrrxvd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.fzhhl.top/Article/details/gthqjcnyyi.html

Go:   slices.Index(arr, x)
来源：http://dali.fzhhl.top/Article/details/gtfglwfggq.html

Ruby: arr.index(x)
来源：http://dali.chenzaomai.com/Article/details/gtkoskdncl.html

C#:   list.IndexOf(x);
来源：http://dali.aibaodan.cn/Article/details/gtlwacqfyw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.nanxinkj.top/Article/details/gtyzzphlws.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.smart0.xyz/Article/details/gtsdumtbqw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhongyouzk.top/Article/details/gtrglswxdg.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xinyue.icu/Article/details/gtiemvqqra.html

TS:   arr.filter(x => x > 3)
来源：http://dali.nwbrower.top/Article/details/gtptthggsb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.sysykeji.top/Article/details/gtqjnafmhn.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ybcxt.top/Article/details/gttacpyxof.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtytscejjx.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.mhx1999.top/Article/details/gtkcpbkhmb.html

[D14] 映射转换（每个元素变形）
来源：http://dali.kuanghao11.cn/Article/details/gtylmajopj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yonumen.top/Article/details/gtdmszqvbx.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtcksndvgv.html

JS:   arr.map(x => x * 2)
来源：http://dali.shuidangran.top/Article/details/gtcbqczfnv.html

TS:   arr.map(x => x * 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbupclauv.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yueranfly.top/Article/details/gtecwwxzkw.html

Go:   // 手写循环
来源：http://dali.gogol.net.cn/Article/details/gtxgowiztc.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.fengsongda.top/Article/details/gtxizvswda.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.daxiang520.top/Article/details/gtkaenrnfz.html

[D15] 去重
来源：http://dali.daxiang520.top/Article/details/gthkvwtrcs.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xinyue.icu/Article/details/gtmbskouih.html

PHP:  array_unique($arr);
来源：http://dali.gogol.net.cn/Article/details/gtzqdmvcin.html

JS:   [...new Set(arr)]
来源：http://dali.jlsjyb.cn/Article/details/gtnmkgtjll.html

TS:   [...new Set(arr)]
来源：http://dali.hnxiangtu.top/Article/details/gtkyefuhoq.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.aizwys.cn/Article/details/gtgvqbmfta.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.sweek.top/Article/details/gttwhkwxwh.html

Ruby: arr.uniq
来源：http://dali.yuanzhike.top/Article/details/gtvkdetrsu.html

C#:   list.Distinct().ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtegbrsmyr.html

[D16] 求和与平均值
来源：http://dali.hongshengwenyu.top/Article/details/gtfgoeydwh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.haohaochexian.top/Article/details/gtapzlwzjk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.316326.xyz/Article/details/gtowjlbeqm.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ehwqpu.com/Article/details/gtiqimjcef.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj20258888.top/Article/details/gtwwukcrbg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zdqjudy.top/Article/details/gtdzseukiw.html

Go:   // 手写循环累加
来源：http://dali.aibaodan.cn/Article/details/gtnnjrkckj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sysykeji.top/Article/details/gtkzvsacev.html

C#:   list.Sum();  list.Average()
来源：http://dali.quarkkingdee.top/Article/details/gtrnpcdsac.html

[D17] 最大值与最小值
来源：http://dali.xylfe.cn/Article/details/gtngqpsmwf.html

Py:   max(arr);  min(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtekpudxxs.html

PHP:  max($arr);  min($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gttkwojjmx.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yanxiufei.cn/Article/details/gtfyjcypbq.html

TS:   Math.max(...arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtdzdqsxpx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.sweek.top/Article/details/gtlzkdmlty.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sweek.top/Article/details/gthuuvrxsx.html

Ruby: arr.max;  arr.min
来源：http://dali.hongshengwenyu.top/Article/details/gtxjqxczaa.html

C#:   list.Max();  list.Min()
来源：http://dali.yuxming.cn/Article/details/gtpufpfdbh.html

[D18] 扁平化嵌套数组
来源：http://dali.jinqigfzy.top/Article/details/gtahqrvmps.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zdqjudy.top/Article/details/gtndxevgtl.html

PHP:  array_merge(...$nested);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtolhytmsi.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jinqigufen.top/Article/details/gtvzfwcaue.html

TS:   nested.flat();
来源：http://dali.zycfv.cn/Article/details/gthagykzbe.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ybcxt.top/Article/details/gtkedrvmwz.html

Go:   // 手写双层循环
来源：http://dali.wangshuangyany.cn/Article/details/gttgpiueng.html

Ruby: nested.flatten
来源：http://dali.gzhubu.top/Article/details/gtqdocbkfq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.316326.xyz/Article/details/gtfspogdhd.html

[D19] 按字段分组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmdcvqsnp.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.316326.xyz/Article/details/gtpxtpxrir.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jqgfzy.top/Article/details/gtvslcsxei.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.wangdashe.top/Article/details/gtndkgkfpx.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.wangshuangyany.cn/Article/details/gtwnyhcwqx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.daria6918.cn/Article/details/gtvfmfmlxv.html

Go:   // 手写 map[string][]T
来源：http://dali.nwbrower.top/Article/details/gtexxdagke.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.sufxvd.cn/Article/details/gtmvpxmpwk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hywenlv.cn/Article/details/gtrrdlyesk.html

[D20] 统计每个元素出现次数
来源：http://dali.ivvv.top/Article/details/gtqnhnodiq.html

Py:   Counter(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtvihcxcer.html

PHP:  array_count_values($arr);
来源：http://dali.yj20258888.top/Article/details/gtgavgjavi.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxxyrfmxh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.havefunace.top/Article/details/gtbupmbrch.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.tianlin.xyz/Article/details/gtoxjkrimt.html

Go:   // 手写 map[T]int
来源：http://dali.nanxinkj.top/Article/details/gtcxjszpyh.html

Ruby: arr.tally
来源：http://dali.pycfn.com/Article/details/gtyaymkttz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yongpay.top/Article/details/gtzpydfumo.html

[D21] 判断是否包含某元素
来源：http://dali.ivvv.top/Article/details/gtlmqjpxds.html

Py:   x in arr
来源：http://dali.redwolf501.top/Article/details/gtfjhwallq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cdnleiting.top/Article/details/gtbcrxipgf.html

JS:   arr.includes(x)
来源：http://dali.gogol.net.cn/Article/details/gtcbwufmrt.html

TS:   arr.includes(x)
来源：http://dali.smart0.xyz/Article/details/gttpolykoi.html

Java: list.contains(x)
来源：http://dali.aibaodan.cn/Article/details/gtohemotcl.html

Go:   slices.Contains(arr, x)
来源：http://dali.xziqi.cn/Article/details/gtfswejpyi.html

Ruby: arr.include?(x)
来源：http://dali.fzhhl.top/Article/details/gtntgwhyll.html

C#:   list.Contains(x)
来源：http://dali.316326.xyz/Article/details/gtagyhkzos.html

[D22] 复制数组（避免共享引用）
来源：http://dali.havefunace.top/Article/details/gtolwbiwoz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shzxlz.cn/Article/details/gtqivgyggp.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.smart0.xyz/Article/details/gtbwmrbtrv.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cqqwz.cn/Article/details/gteopmgehq.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gtxnjezyix.html

Java: new ArrayList<>(list);
来源：http://dali.wangshuangyany.cn/Article/details/gtmfbmzzfb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yueranfly.top/Article/details/gtiwqbylcg.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jqgufenzy.top/Article/details/gtexoyzdti.html

C#:   new List<int>(list);
来源：http://dali.gotoacloud.top/Article/details/gttactcome.html

[D23] reduce 累积计算
来源：http://dali.daria6918.cn/Article/details/gtwbfonoez.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yonumen.top/Article/details/gtstxeqcfw.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gttcpicxiw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.fzhhl.top/Article/details/gtcrozlztu.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hfpthk.cn/Article/details/gtwjbeeoej.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.guowangkeji.top/Article/details/gtijuhkhez.html

Go:   // 手写循环
来源：http://dali.cqqwz.cn/Article/details/gtobpmjuaf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jlsjyb.cn/Article/details/gtfysobwqd.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ivvv.top/Article/details/gtrlyydygr.html

[D24] 字典 / Map 基本操作
来源：http://dali.jinghuilouyu.cn/Article/details/gtxngmdspj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shanyushiyangtech.top/Article/details/gthgjirnzz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.svipenyu.cn/Article/details/gtpcdjklhc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yongpay.top/Article/details/gtbvlrbiiv.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.andypj.xyz/Article/details/gtmfgizhvu.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hnxiangtu.top/Article/details/gtkyujyujd.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinqigufen.top/Article/details/gtzpbcudig.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.fengsongda.top/Article/details/gtjyiyqztr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yuanzhike.top/Article/details/gtdnddewlc.html

[D25] Set 集合去重与交并差
来源：http://dali.jqgufenzy.top/Article/details/gtpbzjyfku.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.sxryk.cn/Article/details/gtezrpyhsz.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jyoumei.cn/Article/details/gtayrhqxbs.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlehqcarp.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.quarkkingdee.top/Article/details/gtcbxdkfma.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sxryk.cn/Article/details/gtbrszgczy.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.fengsongda.top/Article/details/gtrjzzrhig.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hywenlv.cn/Article/details/gtbhlbfgjp.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.daxiang520.top/Article/details/gtmkkkwhft.html

[D26] 数组转字符串
来源：http://dali.c1oappe.top/Article/details/gtaglojrhv.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yueranfly.top/Article/details/gtlxbaahiz.html

PHP:  implode(", ", $arr);
来源：http://dali.tianlin.xyz/Article/details/gtmawcefbl.html

JS:   arr.join(", ")
来源：http://dali.havefunace.top/Article/details/gtqdpachwf.html

TS:   arr.join(", ")
来源：http://dali.pycfn.com/Article/details/gtznycrvql.html

Java: String.join(", ", list)
来源：http://dali.nanxinkj.top/Article/details/gthweuefzz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xziqi.cn/Article/details/gtmjyiumzr.html

Ruby: arr.join(", ")
来源：http://dali.ydzc1.top/Article/details/gtjgkyylqe.html

C#:   string.Join(", ", list)
来源：http://dali.hnxiangtu.top/Article/details/gtyanzwjkp.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gthqsguyzg.html

E. 字符串处理
来源：http://dali.0kj1m.cn/Article/details/gtjvhairat.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtzcsgvskx.html

[E01] 拼接字符串
来源：http://dali.zycfv.cn/Article/details/gttgzzwxmj.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.guowangkeji.top/Article/details/gtfjmraycq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ppjwa.cn/Article/details/gtyzdfsciq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.feifeiyinyue.top/Article/details/gtbekkysnr.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xylfe.cn/Article/details/gtxtzjsqht.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhiwuduotai.top/Article/details/gtndhsglhn.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sufxvd.cn/Article/details/gtrchwsxls.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yuxming.cn/Article/details/gtdajizdmb.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgowuutne.html

[E02] 重复字符串
来源：http://dali.xziqi.cn/Article/details/gtrxoefjxa.html

Py:   "ab" * 3
来源：http://dali.aibaodan.cn/Article/details/gtihnlemnc.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlcxqzumc.html

JS:   "ab".repeat(3)
来源：http://dali.ppjwa.cn/Article/details/gtwfbbmkiz.html

TS:   "ab".repeat(3)
来源：http://dali.havefunace.top/Article/details/gtnjuxawvf.html

Java: "ab".repeat(3)
来源：http://dali.zycfv.cn/Article/details/gtddyqdjyb.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.aizwys.cn/Article/details/gtlvesqnzm.html

Ruby: "ab" * 3
来源：http://dali.cashguo.top/Article/details/gtiucosowe.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ppjwa.cn/Article/details/gtvxqhkkar.html

[E03] 截取子串
来源：http://dali.yongpay.top/Article/details/gtkjgglhxq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxzuooxsz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hfpthk.cn/Article/details/gtlvbtapci.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.meibo888.top/Article/details/gtozciqpvu.html

TS:   s.slice(1, 4)
来源：http://dali.jqgfzy.top/Article/details/gtxgqkplpw.html

Java: s.substring(1, 4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttrcfmggh.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xziqi.cn/Article/details/gtsplmfocx.html


<!-- 参考信息 -->