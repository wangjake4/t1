代发 wailian999

Go:   func() { fmt.Println("run") }()
来源：http://dali.wangshuangyany.cn/Article/details/gtwkvrhuok.html

Ruby: -> { puts "run" }.call
来源：http://dali.yonumen.top/Article/details/gtflpjsabm.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.sweek.top/Article/details/gtavwabfbn.html

[C13] 类型声明 / 类型注解
来源：http://dali.hnqzz.top/Article/details/gtjwuxobto.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jinghuilouyu.cn/Article/details/gtxywuyqce.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnqfyjirr.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.guowangkeji.top/Article/details/gtozdbmhvg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gtwpludeak.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yanxiufei.cn/Article/details/gtbmolkpzh.html

Go:   func add(a, b int) int
来源：http://dali.zhixingplan.top/Article/details/gtzovnaehv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.snrcjt.cn/Article/details/gtlscamnyv.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.chenzaomai.com/Article/details/gtltlgujom.html

[C14] 泛型函数
来源：http://dali.iojbl.cn/Article/details/gtynuqciec.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.tanke756.top/Article/details/gtirvyzdnf.html

PHP:  // 无泛型
来源：http://dali.cucudq.cn/Article/details/gtgztfmndu.html

JS:   // 无泛型
来源：http://dali.chenzaomai.com/Article/details/gtgttnkrmf.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.smart0.xyz/Article/details/gtjwhcpmzv.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.chenzaomai.com/Article/details/gttysgsbex.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.sufxvd.cn/Article/details/gtplvvtwia.html

Ruby: # 无泛型
来源：http://dali.zhixingplan.top/Article/details/gthqevcrgh.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zycfv.cn/Article/details/gtuywqbfen.html

[C15] 解构 / 展开参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsgydyvxo.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.aizwys.cn/Article/details/gtfwjzhhjk.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cashguo.top/Article/details/gtbfuarous.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yj20258.top/Article/details/gtybexphbx.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ybcxt.top/Article/details/gtxiljaqug.html

Java: // 无解构
来源：http://dali.yangfankeji.com/Article/details/gtzonvggqk.html

Go:   // 无解构
来源：http://dali.jinqigfzy.top/Article/details/gtvvibipvs.html

Ruby: a, b = pair
来源：http://dali.jyoumei.cn/Article/details/gtjzgawkti.html

C#:   var (a, b) = pair;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtggcdpjjy.html

[C16] 函数 / 方法重载
来源：http://dali.cashguo.top/Article/details/gtkpofxpkq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yj20258888.top/Article/details/gtjljurftp.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gtmzwarxru.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.birdmap.top/Article/details/gtkypgpphd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yangfankeji.com/Article/details/gtdoyqfcvd.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.chenlongwang.top/Article/details/gtouadcqnp.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfqgotdtb.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jyoumei.cn/Article/details/gtcjlptnsq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.fzhhl.top/Article/details/gtpdgtqpes.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gttyoawqli.html

D. 数组 / 列表 / 集合
来源：http://dali.haohaochexian.top/Article/details/gtlsuxvtag.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyvwxllea.html

[D01] 创建数组 / 列表
来源：http://dali.nanxinkj.top/Article/details/gttriaazwe.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.9152youxi.cn/Article/details/gtxamgwdyq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hfpthk.cn/Article/details/gtnqajbzwy.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaysegawu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.andypj.xyz/Article/details/gtelujdboj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.316326.xyz/Article/details/gtdgmnkbqt.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.mhx1999.top/Article/details/gttlbkhfhk.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jqgufenzy.top/Article/details/gtglktslvz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xuetiantiany.cn/Article/details/gtqyterehi.html

[D02] 追加元素到末尾
来源：http://dali.zhongyouzk.top/Article/details/gttnzewzgg.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.andypj.xyz/Article/details/gtsxlwcpvu.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.bjfxy.top/Article/details/gtrdeizltl.html

JS:   arr.push(4);
来源：http://dali.fengsongda.top/Article/details/gtxislrnfx.html

TS:   arr.push(4);
来源：http://dali.0kj1m.cn/Article/details/gtsbonzpvo.html

Java: list.add(4);
来源：http://dali.nanxuanxn.top/Article/details/gtcpfcrvfs.html

Go:   arr = append(arr, 4)
来源：http://dali.jlsjyb.cn/Article/details/gtehgyjvni.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ydzc1.top/Article/details/gtcwltowvq.html

C#:   list.Add(4);
来源：http://dali.haohaochexian.top/Article/details/gtuqjgvstg.html

[D03] 在指定位置插入元素
来源：http://dali.cashguo.top/Article/details/gtqfvxgnrv.html

Py:   arr.insert(0, 0)
来源：http://dali.sxryk.cn/Article/details/gtwbtyhuto.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.sufxvd.cn/Article/details/gtuvrlnmnk.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jlsjyb.cn/Article/details/gtrknnbokw.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtntvraleg.html

Java: list.add(0, 0);
来源：http://dali.meibo888.top/Article/details/gtzqcrrrsg.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.gotoacloud.top/Article/details/gtktpwlagu.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hammf.cn/Article/details/gtnpmdpcsb.html

C#:   list.Insert(0, 0);
来源：http://dali.yuanzhike.top/Article/details/gtyuovtvjj.html

[D04] 删除元素
来源：http://dali.ehwqpu.com/Article/details/gtxbrzmbny.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xinyue.icu/Article/details/gttzqsqevi.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hysaishi.cn/Article/details/gtspjrqzmy.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.tanke756.top/Article/details/gtkuryzazx.html

TS:   arr.splice(0, 1);
来源：http://dali.zhixingplan.top/Article/details/gtlougydgm.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.wangdashe.top/Article/details/gtrjvkiilw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jqgufenzy.top/Article/details/gtjbkofwcs.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ppjwa.cn/Article/details/gtyjbbwdea.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuzohkrqy.html

[D05] 访问与修改元素
来源：http://dali.yanxiufei.cn/Article/details/gtbwooupcd.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yvedp.cn/Article/details/gtpmaizkam.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yvedp.cn/Article/details/gtfnrafuqq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.fengsongda.top/Article/details/gthkptjmxn.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhoulong.xyz/Article/details/gtnmhvkhkr.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ivvv.top/Article/details/gtfyggrlko.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yueranfly.top/Article/details/gttyvpbatl.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hysaishi.cn/Article/details/gtztsrijve.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.havefunace.top/Article/details/gtaodxklde.html

[D06] 数组长度
来源：http://dali.sweek.top/Article/details/gtobxaxtry.html

Py:   len(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtywbwsdta.html

PHP:  count($arr);
来源：http://dali.fengsongda.top/Article/details/gtftjcpfgs.html

JS:   arr.length
来源：http://dali.yvedp.cn/Article/details/gtcavapxga.html

TS:   arr.length
来源：http://dali.daxiang520.top/Article/details/gtaynmgqgx.html

Java: list.size();
来源：http://dali.yongpay.top/Article/details/gtaafyhlic.html

Go:   len(arr)
来源：http://dali.ybcxt.top/Article/details/gtjairgxyy.html

Ruby: arr.length; arr.size
来源：http://dali.haohaochexian.top/Article/details/gtqqjmpkzz.html

C#:   list.Count;
来源：http://dali.iojbl.cn/Article/details/gtowejueqd.html

[D07] 切片 / 取子数组
来源：http://dali.cqqwz.cn/Article/details/gtiacpsolv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ivvv.top/Article/details/gtynvlcovh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shuidangran.top/Article/details/gthsgibkiw.html

JS:   arr.slice(1, 4);
来源：http://dali.aizwys.cn/Article/details/gtrvobhxub.html

TS:   arr.slice(1, 4);
来源：http://dali.feifeiyinyue.top/Article/details/gtwoqgjwbs.html

Java: list.subList(1, 4);
来源：http://dali.tian-w.cn/Article/details/gtllsmhqsx.html

Go:   arr[1:4]
来源：http://dali.shzxlz.cn/Article/details/gtnpeufprq.html

Ruby: arr[1, 3]
来源：http://dali.fengsongda.top/Article/details/gtfccwzphp.html

C#:   list.GetRange(1, 3);
来源：http://dali.yongpay.top/Article/details/gtpvlgvcgw.html

[D08] 合并两个数组
来源：http://dali.jiagoushi.top/Article/details/gtuoapqcum.html

Py:   a + b;  a.extend(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzzqdpwed.html

PHP:  array_merge($a, $b);
来源：http://dali.gogol.net.cn/Article/details/gtbgdlivpw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.chenlongwang.top/Article/details/gtaufmkvrp.html

TS:   [...a, ...b];
来源：http://dali.nwbrower.top/Article/details/gtmflflgok.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.andypj.xyz/Article/details/gtjreesfny.html

Go:   append(a, b...)
来源：http://dali.snrcjt.cn/Article/details/gtwqjutudc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.0kj1m.cn/Article/details/gtuydhlwbr.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gttwwbmcqc.html

[D09] 排序（升序）
来源：http://dali.zhiwuduotai.top/Article/details/gtveelagai.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hongshengwenyu.top/Article/details/gtjjlbcezz.html

PHP:  sort($arr);
来源：http://dali.havefunace.top/Article/details/gthetlfvcl.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xuanzx.com/Article/details/gtccrgvvjl.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhengqikj.top/Article/details/gtbngqifzk.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sysykeji.top/Article/details/gtnqjunhsu.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hywenlv.cn/Article/details/gtyrchofnv.html

Ruby: arr.sort
来源：http://dali.gogol.net.cn/Article/details/gtxeagiowa.html

C#:   list.Sort();
来源：http://dali.yj20258888.top/Article/details/gtvjrmybzb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.havefunace.top/Article/details/gtkgbfeqbm.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ybcxt.top/Article/details/gtwutyatlm.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.wangdashe.top/Article/details/gtrbdnwxya.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.svipenyu.cn/Article/details/gtdqalujtq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yuxming.cn/Article/details/gtfytunbtt.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shanyushiyangtech.top/Article/details/gtbsbdqkjv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yuanzhike.top/Article/details/gtyiphejao.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yj20258888.top/Article/details/gtjmvibkir.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xziqi.cn/Article/details/gtyrzyvqek.html

[D11] 反转数组
来源：http://dali.ydzc1.top/Article/details/gtyouvodbx.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ydzc1.top/Article/details/gtuypmboop.html

PHP:  array_reverse($arr);
来源：http://dali.yangfankeji.com/Article/details/gtohxulubx.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.redwolf501.top/Article/details/gtgljqrqtp.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gtdmzdrzep.html

Java: Collections.reverse(list);
来源：http://dali.zhongyouzk.top/Article/details/gtbxypjhms.html

Go:   slices.Reverse(arr)
来源：http://dali.zhengqikj.top/Article/details/gtawaijagy.html

Ruby: arr.reverse
来源：http://dali.quarkkingdee.top/Article/details/gtrarrghwp.html

C#:   list.Reverse();
来源：http://dali.zhengqikj.top/Article/details/gtcudzgihq.html

[D12] 查找元素下标
来源：http://dali.cqqwz.cn/Article/details/gtmqdvqpgv.html

Py:   arr.index(x);  x in arr
来源：http://dali.nanxuanxn.top/Article/details/gtmbmsvhuv.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.bjfxy.top/Article/details/gtezkwcvbx.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.wangshuangyany.cn/Article/details/gtfjvjxglu.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xylfe.cn/Article/details/gtoixskspi.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shangyingyoupin.top/Article/details/gttsvmzidn.html

Go:   slices.Index(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtdcjihkcz.html

Ruby: arr.index(x)
来源：http://dali.quarkkingdee.top/Article/details/gttewvdafj.html

C#:   list.IndexOf(x);
来源：http://dali.xziqi.cn/Article/details/gteurvstqa.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jiagoushi.top/Article/details/gtzowbpkzs.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sweek.top/Article/details/gtxidzbktk.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.316326.xyz/Article/details/gtbfoduuuc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhixingplan.top/Article/details/gtwcllpnzy.html

TS:   arr.filter(x => x > 3)
来源：http://dali.fengsongda.top/Article/details/gtfrkrpsed.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.redwolf501.top/Article/details/gtrgyqijij.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.aizwys.cn/Article/details/gtqxxqscdi.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.smart0.xyz/Article/details/gtzhwsnoyb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gtzmhxdbbn.html

[D14] 映射转换（每个元素变形）
来源：http://dali.redwolf501.top/Article/details/gtbmfzeczu.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gttdsibjdt.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.daria6918.cn/Article/details/gtnkoxudem.html

JS:   arr.map(x => x * 2)
来源：http://dali.gogol.net.cn/Article/details/gttzpxjmjq.html

TS:   arr.map(x => x * 2)
来源：http://dali.bjfxy.top/Article/details/gtkqpxdrbz.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jianghu66.top/Article/details/gtmdhtardh.html

Go:   // 手写循环
来源：http://dali.guowangkeji.top/Article/details/gtrklvsgdt.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gtyuaieuro.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ybcxt.top/Article/details/gtljloxfys.html

[D15] 去重
来源：http://dali.zhiwuduotai.top/Article/details/gtdpvhpvni.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.aibaodan.cn/Article/details/gtpcxatqut.html

PHP:  array_unique($arr);
来源：http://dali.hnqzz.top/Article/details/gtfipwkudn.html

JS:   [...new Set(arr)]
来源：http://dali.zdqjudy.top/Article/details/gtthgynakf.html

TS:   [...new Set(arr)]
来源：http://dali.jlsjyb.cn/Article/details/gtafxatqdv.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.bjfxy.top/Article/details/gtfmcjkziv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xziqi.cn/Article/details/gtzjepdbos.html

Ruby: arr.uniq
来源：http://dali.shanyushiyangtech.top/Article/details/gtetmzeumd.html

C#:   list.Distinct().ToList()
来源：http://dali.xinyue.icu/Article/details/gtzrsefhbz.html

[D16] 求和与平均值
来源：http://dali.yj202588.top/Article/details/gtfqxqhfgx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.daxiang520.top/Article/details/gtecujzprr.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.c1oappe.top/Article/details/gtmawuanlx.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenzaomai.com/Article/details/gtnuhefwpw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.316326.xyz/Article/details/gtjnaogtvp.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cashguo.top/Article/details/gtxwgvbtzr.html

Go:   // 手写循环累加
来源：http://dali.jinqigfzy.top/Article/details/gthfsjoqot.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xuanzx.com/Article/details/gtwgcotswy.html

C#:   list.Sum();  list.Average()
来源：http://dali.kuanghao11.cn/Article/details/gtodlgvonj.html

[D17] 最大值与最小值
来源：http://dali.smart0.xyz/Article/details/gtcbeeshht.html

Py:   max(arr);  min(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtqgpfsigm.html

PHP:  max($arr);  min($arr);
来源：http://dali.hywenlv.cn/Article/details/gtqknzncep.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhengqikj.top/Article/details/gtmeaigncm.html

TS:   Math.max(...arr);
来源：http://dali.cqqwz.cn/Article/details/gthkwdxszp.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.snrcjt.cn/Article/details/gtchhfryyp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yongpay.top/Article/details/gtlaevtpfl.html

Ruby: arr.max;  arr.min
来源：http://dali.xylfe.cn/Article/details/gtltjzcret.html

C#:   list.Max();  list.Min()
来源：http://dali.zhengqikj.top/Article/details/gtuihovgwg.html

[D18] 扁平化嵌套数组
来源：http://dali.c1oappe.top/Article/details/gtmyzppfiz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhiwuduotai.top/Article/details/gtjjqzurdh.html

PHP:  array_merge(...$nested);
来源：http://dali.jinqigufen.top/Article/details/gttvxidxjw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jianghu66.top/Article/details/gtzsebggsu.html

TS:   nested.flat();
来源：http://dali.smart0.xyz/Article/details/gtvsxeqzxa.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.wangdashe.top/Article/details/gtlvrcxuil.html

Go:   // 手写双层循环
来源：http://dali.shuidangran.top/Article/details/gthzcmgbwm.html

Ruby: nested.flatten
来源：http://dali.shuidangran.top/Article/details/gthcmodfjy.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtjptyjnxp.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gtjakrbhvy.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gotoacloud.top/Article/details/gtqsbmxlwx.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.316326.xyz/Article/details/gtunoacgtj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.haohaochexian.top/Article/details/gtmwoatgsx.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jqgufenzy.top/Article/details/gtbphxlfdf.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.gogol.net.cn/Article/details/gtkhbabrmv.html

Go:   // 手写 map[string][]T
来源：http://dali.chenlongwang.top/Article/details/gtqcrsruqr.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhongyouzk.top/Article/details/gtrzldntmx.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.haohaochexian.top/Article/details/gtesoopccx.html

[D20] 统计每个元素出现次数
来源：http://dali.svipenyu.cn/Article/details/gtduamhpzi.html

Py:   Counter(arr)
来源：http://dali.chenzaomai.com/Article/details/gtlqpkxhvs.html

PHP:  array_count_values($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtupydzjiu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.316326.xyz/Article/details/gtscmncyih.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jianghu66.top/Article/details/gtqvbortpn.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yueranfly.top/Article/details/gtrkqhtcya.html

Go:   // 手写 map[T]int
来源：http://dali.jqgufenzy.top/Article/details/gtusnnhepd.html

Ruby: arr.tally
来源：http://dali.iojbl.cn/Article/details/gtzradvkpz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.dianchejie.cn/Article/details/gtborlhprg.html

[D21] 判断是否包含某元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbykxiprk.html

Py:   x in arr
来源：http://dali.jqgufenzy.top/Article/details/gtalrtfcci.html

PHP:  in_array($x, $arr, true);
来源：http://dali.havefunace.top/Article/details/gtbpazzdbf.html

JS:   arr.includes(x)
来源：http://dali.fengsongda.top/Article/details/gtvrlafyda.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gtfimporgp.html

Java: list.contains(x)
来源：http://dali.iojbl.cn/Article/details/gtpgiiivbb.html

Go:   slices.Contains(arr, x)
来源：http://dali.iojbl.cn/Article/details/gtaczrktgd.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gtlohfqere.html

C#:   list.Contains(x)
来源：http://dali.cheryme.top/Article/details/gtkwhrjtty.html

[D22] 复制数组（避免共享引用）
来源：http://dali.0kj1m.cn/Article/details/gtixralbns.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xinyue.icu/Article/details/gtusbicmmo.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yanxiufei.cn/Article/details/gtjzvksxoy.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zycfv.cn/Article/details/gtjeoqlsvy.html

TS:   [...arr];
来源：http://dali.smart0.xyz/Article/details/gtbtwtjoku.html

Java: new ArrayList<>(list);
来源：http://dali.zhongyouzk.top/Article/details/gtyaqtnisw.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.tanke756.top/Article/details/gtihileiai.html

Ruby: arr.dup;  arr.clone
来源：http://dali.fengsongda.top/Article/details/gtjvmsncya.html

C#:   new List<int>(list);
来源：http://dali.pycfn.com/Article/details/gtxxolaibq.html

[D23] reduce 累积计算
来源：http://dali.havefunace.top/Article/details/gtytbgwyhg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.nwbrower.top/Article/details/gtetddlkdo.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.sxryk.cn/Article/details/gtzqtykwyo.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.fengsongda.top/Article/details/gtomccaiqm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtanujkjas.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hammf.cn/Article/details/gtdvdpplfi.html

Go:   // 手写循环
来源：http://dali.shuidangran.top/Article/details/gtlnpyvkup.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.guowangkeji.top/Article/details/gtnvfudlwy.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cucudq.cn/Article/details/gtbsqpjyjg.html

[D24] 字典 / Map 基本操作
来源：http://dali.smart0.xyz/Article/details/gtjxwxjwyi.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmgsaqsix.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.nanxuanxn.top/Article/details/gtfopezknd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.tanke756.top/Article/details/gtbfnnobbm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sweek.top/Article/details/gtqmmbigmh.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.meibo888.top/Article/details/gtesoeywsm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xziqi.cn/Article/details/gtllwjmkiy.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yj20258.top/Article/details/gtilsbfwcp.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjdocesop.html

[D25] Set 集合去重与交并差
来源：http://dali.jinqigufen.top/Article/details/gtyrwihgdq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.guannengcc.top/Article/details/gtdgrqjlvq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.gaohongyu789.top/Article/details/gtmmfkkvie.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cdnleiting.top/Article/details/gtpvnzgigu.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cheryme.top/Article/details/gtfemjvdqu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gzhubu.top/Article/details/gtprazscur.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.c1oappe.top/Article/details/gtqjclhlci.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.316326.xyz/Article/details/gtwterbrjr.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yonumen.top/Article/details/gtugkmaefp.html

[D26] 数组转字符串
来源：http://dali.zhengqikj.top/Article/details/gtndtqubap.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yongpay.top/Article/details/gtlibbrefy.html

PHP:  implode(", ", $arr);
来源：http://dali.zhongyouzk.top/Article/details/gtlwzaxxsl.html

JS:   arr.join(", ")
来源：http://dali.chenlongwang.top/Article/details/gtuwnydevq.html

TS:   arr.join(", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvacmbrla.html

Java: String.join(", ", list)
来源：http://dali.kuanghao11.cn/Article/details/gtwppsxpge.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gttiihptgd.html

Ruby: arr.join(", ")
来源：http://dali.sxryk.cn/Article/details/gtbefsnrzg.html

C#:   string.Join(", ", list)
来源：http://dali.havefunace.top/Article/details/gtuerffyqe.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtpivaoave.html

E. 字符串处理
来源：http://dali.yj202588.top/Article/details/gtaugbmuqe.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtjmhchjiq.html

[E01] 拼接字符串
来源：http://dali.tianlin.xyz/Article/details/gtqfepjhtj.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cheryme.top/Article/details/gtjyvjtpvu.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yonumen.top/Article/details/gtqdqhuczk.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhixingplan.top/Article/details/gthcufzyda.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.feifeiyinyue.top/Article/details/gtaysxkupk.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhoulong.xyz/Article/details/gttkfaumfd.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtcmrzsgbr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzulpkmvi.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gtfaekacnp.html

[E02] 重复字符串
来源：http://dali.yj202588.top/Article/details/gtosdhgznj.html

Py:   "ab" * 3
来源：http://dali.9152youxi.cn/Article/details/gtltjrrgbg.html

PHP:  str_repeat("ab", 3);
来源：http://dali.316326.xyz/Article/details/gtrzweuxee.html

JS:   "ab".repeat(3)
来源：http://dali.aibaodan.cn/Article/details/gtfpztictc.html

TS:   "ab".repeat(3)
来源：http://dali.haohaochexian.top/Article/details/gttewzfcoa.html

Java: "ab".repeat(3)
来源：http://dali.chenlongwang.top/Article/details/gthfuysutb.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.dashuyun.cn/Article/details/gtakowqpsn.html

Ruby: "ab" * 3
来源：http://dali.nwbrower.top/Article/details/gtgtlepbym.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhixingplan.top/Article/details/gtcziivunk.html

[E03] 截取子串
来源：http://dali.zhixingplan.top/Article/details/gtbfcrpwgt.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuphayxwi.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gtavxsucjw.html


<!-- 参考信息 -->