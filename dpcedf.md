代发 wailian999

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gtnkqchweb.html

Go:   func add(a, b int) int
来源：http://dali.yongpay.top/Article/details/gtpjrmunsp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.kuanghao11.cn/Article/details/gthfndiudp.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.tian-w.cn/Article/details/gtbftzghrz.html

[C14] 泛型函数
来源：http://dali.redwolf501.top/Article/details/gtfdeqqbbe.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.havefunace.top/Article/details/gtqmbjyrlq.html

PHP:  // 无泛型
来源：http://dali.fengsongda.top/Article/details/gtejgxaqgh.html

JS:   // 无泛型
来源：http://dali.dashuyun.cn/Article/details/gtobnnljms.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhengqikj.top/Article/details/gtrozwvamu.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ybcxt.top/Article/details/gtwrpajlix.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.chenlongwang.top/Article/details/gtjytculgf.html

Ruby: # 无泛型
来源：http://dali.yuxming.cn/Article/details/gtcbfapkxx.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqonrgycu.html

[C15] 解构 / 展开参数
来源：http://dali.9152youxi.cn/Article/details/gtbahdrgob.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.cdnleiting.top/Article/details/gtgyzpkajh.html

PHP:  [$a, $b] = $pair;
来源：http://dali.smart0.xyz/Article/details/gtzhpatdzk.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.meibo888.top/Article/details/gtnftsgiuz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.gotoacloud.top/Article/details/gttlwscwqn.html

Java: // 无解构
来源：http://dali.cdnleiting.top/Article/details/gtbzujsnfe.html

Go:   // 无解构
来源：http://dali.tianlin.xyz/Article/details/gtgxnxebpq.html

Ruby: a, b = pair
来源：http://dali.nanxinkj.top/Article/details/gtobxmprbt.html

C#:   var (a, b) = pair;
来源：http://dali.bjfxy.top/Article/details/gtaehzfmla.html

[C16] 函数 / 方法重载
来源：http://dali.snrcjt.cn/Article/details/gtpbmgpcca.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.wangshuangyany.cn/Article/details/gtvmrmqvau.html

PHP:  // 无重载
来源：http://dali.xylfe.cn/Article/details/gtrrtrtguu.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuxksjnhj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.haohaochexian.top/Article/details/gtuhwvbwsj.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gtthuvqycq.html

Go:   // 无重载：用不同函数名
来源：http://dali.xinyue.icu/Article/details/gtdvnnhqiu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gotoacloud.top/Article/details/gtgdmovucy.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yvedp.cn/Article/details/gtxpleisus.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtedbkznyd.html

D. 数组 / 列表 / 集合
来源：http://dali.chenjidiqi.icu/Article/details/gtkobjitha.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtjrhtoxsj.html

[D01] 创建数组 / 列表
来源：http://dali.zdqjudy.top/Article/details/gtjxeyxmdq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.andypj.xyz/Article/details/gtdtvrnzlz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yuanzhike.top/Article/details/gtppbrarzm.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yongpay.top/Article/details/gtzkutoryj.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jiagoushi.top/Article/details/gtxhygrsiw.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yj202588.top/Article/details/gttrgvyvjd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.sufxvd.cn/Article/details/gtqazzwztm.html

Ruby: arr = [1, 2, 3]
来源：http://dali.dashuyun.cn/Article/details/gtlsnfqqya.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.haohaochexian.top/Article/details/gtgjfuptnf.html

[D02] 追加元素到末尾
来源：http://dali.yueranfly.top/Article/details/gtsyeyjukq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhiwuduotai.top/Article/details/gtkxizekzw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.iojbl.cn/Article/details/gtezuowgbb.html

JS:   arr.push(4);
来源：http://dali.fengsongda.top/Article/details/gtyrlrinjx.html

TS:   arr.push(4);
来源：http://dali.jqgufenzy.top/Article/details/gtnejbuueg.html

Java: list.add(4);
来源：http://dali.svipenyu.cn/Article/details/gtzbhcjcwn.html

Go:   arr = append(arr, 4)
来源：http://dali.chenzaomai.com/Article/details/gtsthllnqg.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.havefunace.top/Article/details/gtdaehnirm.html

C#:   list.Add(4);
来源：http://dali.tianlin.xyz/Article/details/gtxmcjuhhj.html

[D03] 在指定位置插入元素
来源：http://dali.jyoumei.cn/Article/details/gtnohczkdb.html

Py:   arr.insert(0, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnjjmlcqd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtinwsyvcs.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhiwuduotai.top/Article/details/gtzkgvbkiq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtwmasmuar.html

Java: list.add(0, 0);
来源：http://dali.vqdsnc.cn/Article/details/gtkomikpxw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.chenjidiqi.icu/Article/details/gtwlxenjvp.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.tian-w.cn/Article/details/gtgaxsgome.html

C#:   list.Insert(0, 0);
来源：http://dali.ivvv.top/Article/details/gtxnfmzkbx.html

[D04] 删除元素
来源：http://dali.yangfankeji.com/Article/details/gtiqjwhkol.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.wangdashe.top/Article/details/gtchwsofsa.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.fengsongda.top/Article/details/gtidbobeke.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.chenzaomai.com/Article/details/gtgsxzkoin.html

TS:   arr.splice(0, 1);
来源：http://dali.ivvv.top/Article/details/gtgmxajpcb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gtoiylbbpx.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhongyouzk.top/Article/details/gtrrxtkaut.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhongyouzk.top/Article/details/gtkqmumjdj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ppjwa.cn/Article/details/gthzjqboda.html

[D05] 访问与修改元素
来源：http://dali.shzxlz.cn/Article/details/gtxnvtghez.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.kuanghao11.cn/Article/details/gtffhfmomx.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.svipenyu.cn/Article/details/gtincluiuv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jqgufenzy.top/Article/details/gtjdnwhxdn.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zycfv.cn/Article/details/gtvtbznlgy.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhiwuduotai.top/Article/details/gtcbsardjc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hnqzz.top/Article/details/gtpiusdfrl.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenjidiqi.icu/Article/details/gtgmbpvfbe.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtccgmrfdq.html

[D06] 数组长度
来源：http://dali.mhx1999.top/Article/details/gtbdksylec.html

Py:   len(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtjdewxvqb.html

PHP:  count($arr);
来源：http://dali.0kj1m.cn/Article/details/gtsvxnkgzb.html

JS:   arr.length
来源：http://dali.tianlin.xyz/Article/details/gtbdsaevck.html

TS:   arr.length
来源：http://dali.jqgfzy.top/Article/details/gtrppyymiu.html

Java: list.size();
来源：http://dali.0kj1m.cn/Article/details/gtwhajsjyq.html

Go:   len(arr)
来源：http://dali.ybcxt.top/Article/details/gtnjgntwne.html

Ruby: arr.length; arr.size
来源：http://dali.jqgfzy.top/Article/details/gtjktzatlj.html

C#:   list.Count;
来源：http://dali.shanyushiyangtech.top/Article/details/gtfljmhxew.html

[D07] 切片 / 取子数组
来源：http://dali.smart0.xyz/Article/details/gtmrndwlgo.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.nanxuanxn.top/Article/details/gthqgdirnv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.fzhhl.top/Article/details/gtjftpmehy.html

JS:   arr.slice(1, 4);
来源：http://dali.hongshengwenyu.top/Article/details/gtdymhzfvl.html

TS:   arr.slice(1, 4);
来源：http://dali.chenlongwang.top/Article/details/gtlwbkxixw.html

Java: list.subList(1, 4);
来源：http://dali.fengsongda.top/Article/details/gtyasxrseo.html

Go:   arr[1:4]
来源：http://dali.xylfe.cn/Article/details/gtqnfccnak.html

Ruby: arr[1, 3]
来源：http://dali.zhiwuduotai.top/Article/details/gtlwhnvsrc.html

C#:   list.GetRange(1, 3);
来源：http://dali.quarkkingdee.top/Article/details/gtzczsdnkj.html

[D08] 合并两个数组
来源：http://dali.andypj.xyz/Article/details/gtlrbqxkmw.html

Py:   a + b;  a.extend(b)
来源：http://dali.svipenyu.cn/Article/details/gtblfbuplh.html

PHP:  array_merge($a, $b);
来源：http://dali.jinqigfzy.top/Article/details/gtosduxaue.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jianghu66.top/Article/details/gtnizayvda.html

TS:   [...a, ...b];
来源：http://dali.hysaishi.cn/Article/details/gtddsmyidb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ivvv.top/Article/details/gtspmrgvqn.html

Go:   append(a, b...)
来源：http://dali.iojbl.cn/Article/details/gtquybwrhp.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cheryme.top/Article/details/gtekpfnfff.html

C#:   a.Concat(b).ToList()
来源：http://dali.sysykeji.top/Article/details/gtvputolyo.html

[D09] 排序（升序）
来源：http://dali.xinyue.icu/Article/details/gtxytfeamg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.havefunace.top/Article/details/gtvchqnuzu.html

PHP:  sort($arr);
来源：http://dali.ybcxt.top/Article/details/gtnqffwwde.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.mhx1999.top/Article/details/gtfmumdqvh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jinqigfzy.top/Article/details/gtdupeenex.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xuanzx.com/Article/details/gtgmtaprqd.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.meibo888.top/Article/details/gtzwbokrxd.html

Ruby: arr.sort
来源：http://dali.yj20258.top/Article/details/gtbmorypip.html

C#:   list.Sort();
来源：http://dali.shanyushiyangtech.top/Article/details/gtdsjgjjwl.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.haohaochexian.top/Article/details/gtguulvcox.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.sxryk.cn/Article/details/gtggjuhohp.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zdqjudy.top/Article/details/gtdosqcwia.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ppjwa.cn/Article/details/gtbmcoznvv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.316326.xyz/Article/details/gtixacojsa.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zycfv.cn/Article/details/gtutvogjsb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yanxiufei.cn/Article/details/gtpijowsvn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.redwolf501.top/Article/details/gttajccphq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhengqikj.top/Article/details/gtwyzgnfmh.html

[D11] 反转数组
来源：http://dali.dianchejie.cn/Article/details/gtfszfrqux.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jinghuilouyu.cn/Article/details/gtrtpegxrn.html

PHP:  array_reverse($arr);
来源：http://dali.c1oappe.top/Article/details/gtezecxfci.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.tanke756.top/Article/details/gtpjoganom.html

TS:   [...arr].reverse();
来源：http://dali.andypj.xyz/Article/details/gtsgrxtpfl.html

Java: Collections.reverse(list);
来源：http://dali.jinqigfzy.top/Article/details/gtndknpttp.html

Go:   slices.Reverse(arr)
来源：http://dali.daxiang520.top/Article/details/gtovcmwgie.html

Ruby: arr.reverse
来源：http://dali.yongpay.top/Article/details/gtxeeqqasd.html

C#:   list.Reverse();
来源：http://dali.zycfv.cn/Article/details/gtgdqqpiet.html

[D12] 查找元素下标
来源：http://dali.yangfankeji.com/Article/details/gtusazmwec.html

Py:   arr.index(x);  x in arr
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbmqrmerj.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yuxming.cn/Article/details/gtngihxmgf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ppjwa.cn/Article/details/gtybzllvsc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj20258888.top/Article/details/gtmslzjaqm.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.haohaochexian.top/Article/details/gtsjjrdhyr.html

Go:   slices.Index(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gtxkptzwdf.html

Ruby: arr.index(x)
来源：http://dali.xuanzx.com/Article/details/gtakrsxbzs.html

C#:   list.IndexOf(x);
来源：http://dali.ehwqpu.com/Article/details/gtckxzxlqx.html

[D13] 过滤（保留满足条件的）
来源：http://dali.wangshuangyany.cn/Article/details/gtodzyavhr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.dianchejie.cn/Article/details/gtvloksovu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.0kj1m.cn/Article/details/gtlduxqazg.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hfpthk.cn/Article/details/gtculkyczc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.pycfn.com/Article/details/gthcaimamt.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.gotoacloud.top/Article/details/gtayoeagdm.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ppjwa.cn/Article/details/gtcrpvqian.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.tianlin.xyz/Article/details/gtqxmqkaez.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yuxming.cn/Article/details/gtqksrwvpw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.wangshuangyany.cn/Article/details/gtimjemeya.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jqgfzy.top/Article/details/gtcezqztxa.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hfpthk.cn/Article/details/gtzxkkywqc.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtuhvkekbu.html

TS:   arr.map(x => x * 2)
来源：http://dali.xinyue.icu/Article/details/gtrjqfvjes.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ydzc1.top/Article/details/gtzaqjcudt.html

Go:   // 手写循环
来源：http://dali.gzhubu.top/Article/details/gthercnpic.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jlsjyb.cn/Article/details/gtpyeqfqxi.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.guannengcc.top/Article/details/gtrctelbmz.html

[D15] 去重
来源：http://dali.chenlongwang.top/Article/details/gttwszcoxc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hysaishi.cn/Article/details/gtejbxkfhc.html

PHP:  array_unique($arr);
来源：http://dali.hnqzz.top/Article/details/gtdoufbfjs.html

JS:   [...new Set(arr)]
来源：http://dali.yvedp.cn/Article/details/gtrzddvvia.html

TS:   [...new Set(arr)]
来源：http://dali.jinyuanbaomall.cn/Article/details/gticeeblwy.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtydbcjbls.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinqigfzy.top/Article/details/gtramcopfw.html

Ruby: arr.uniq
来源：http://dali.daria6918.cn/Article/details/gtauadcxzp.html

C#:   list.Distinct().ToList()
来源：http://dali.birdmap.top/Article/details/gtnlwhdzxx.html

[D16] 求和与平均值
来源：http://dali.dashuyun.cn/Article/details/gtettrtyxc.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hfpthk.cn/Article/details/gtujzkbjcb.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.tanke756.top/Article/details/gtjmmerlrt.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jiagoushi.top/Article/details/gtxusvwbqs.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cqqwz.cn/Article/details/gtsqqhcuuq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xuetiantiany.cn/Article/details/gtdhahenej.html

Go:   // 手写循环累加
来源：http://dali.dianchejie.cn/Article/details/gttxtzeeee.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrqmdzumi.html

C#:   list.Sum();  list.Average()
来源：http://dali.cdnleiting.top/Article/details/gtnnpudgry.html

[D17] 最大值与最小值
来源：http://dali.zhixingplan.top/Article/details/gtmatyyqrd.html

Py:   max(arr);  min(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtlzsfqafv.html

PHP:  max($arr);  min($arr);
来源：http://dali.ppjwa.cn/Article/details/gtcgxajfjz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhongyouzk.top/Article/details/gtcstufgoy.html

TS:   Math.max(...arr);
来源：http://dali.sweek.top/Article/details/gtqbfxjtfa.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jqgufenzy.top/Article/details/gtweiywnpy.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtipgckfqf.html

Ruby: arr.max;  arr.min
来源：http://dali.ydzc1.top/Article/details/gtvaypfuen.html

C#:   list.Max();  list.Min()
来源：http://dali.pycfn.com/Article/details/gthpvtinjj.html

[D18] 扁平化嵌套数组
来源：http://dali.chenlongwang.top/Article/details/gtommhvpnv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.c1oappe.top/Article/details/gthedaetbc.html

PHP:  array_merge(...$nested);
来源：http://dali.svipenyu.cn/Article/details/gtjjbwbizj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xuetiantiany.cn/Article/details/gtzawryksr.html

TS:   nested.flat();
来源：http://dali.birdmap.top/Article/details/gtrqngtbkd.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gthkboxsnx.html

Go:   // 手写双层循环
来源：http://dali.zhengqikj.top/Article/details/gtqhkgcvkr.html

Ruby: nested.flatten
来源：http://dali.cucudq.cn/Article/details/gtpvjqkllb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yj20258.top/Article/details/gtjmgeobww.html

[D19] 按字段分组
来源：http://dali.chenjidiqi.icu/Article/details/gtehjebllv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xinyue.icu/Article/details/gtntfcmvcs.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhixingplan.top/Article/details/gtpqbttvew.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zycfv.cn/Article/details/gtsopoghax.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.nanxinkj.top/Article/details/gtlhkoccph.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hywenlv.cn/Article/details/gtgsfkwbnn.html

Go:   // 手写 map[string][]T
来源：http://dali.yj20258888.top/Article/details/gtkzlzqrti.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hammf.cn/Article/details/gtdctrbhgt.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sxryk.cn/Article/details/gtbsbqglet.html

[D20] 统计每个元素出现次数
来源：http://dali.dianchejie.cn/Article/details/gtzvqhgjhf.html

Py:   Counter(arr)
来源：http://dali.jyoumei.cn/Article/details/gtcpfrefkq.html

PHP:  array_count_values($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlfmvezmz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fengsongda.top/Article/details/gtencksdmp.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yueranfly.top/Article/details/gtgcpintre.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.mhx1999.top/Article/details/gtlglqyzvn.html

Go:   // 手写 map[T]int
来源：http://dali.dashuyun.cn/Article/details/gtrdqfvkli.html

Ruby: arr.tally
来源：http://dali.feifeiyinyue.top/Article/details/gtohllctek.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.pycfn.com/Article/details/gtisuyiajr.html

[D21] 判断是否包含某元素
来源：http://dali.gotoacloud.top/Article/details/gtfkrqaaep.html

Py:   x in arr
来源：http://dali.yj20258888.top/Article/details/gtzfjfpfzb.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jyoumei.cn/Article/details/gtywkpcaru.html

JS:   arr.includes(x)
来源：http://dali.yangfankeji.com/Article/details/gtrdpfxiwm.html

TS:   arr.includes(x)
来源：http://dali.svipenyu.cn/Article/details/gtzrhtmqpa.html

Java: list.contains(x)
来源：http://dali.shzxlz.cn/Article/details/gtkchgpjis.html

Go:   slices.Contains(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtngimgpbp.html

Ruby: arr.include?(x)
来源：http://dali.quarkkingdee.top/Article/details/gtlnhsngnz.html

C#:   list.Contains(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoqwndnob.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yueranfly.top/Article/details/gtbpaznxmh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.iojbl.cn/Article/details/gthfuqcsmj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yueranfly.top/Article/details/gtpdmqguji.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yonumen.top/Article/details/gtgbgesyju.html

TS:   [...arr];
来源：http://dali.mhx1999.top/Article/details/gtyyfxgspu.html

Java: new ArrayList<>(list);
来源：http://dali.mhx1999.top/Article/details/gtkudqktzg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jlsjyb.cn/Article/details/gtqsfyirfl.html

Ruby: arr.dup;  arr.clone
来源：http://dali.svipenyu.cn/Article/details/gtqybpnano.html

C#:   new List<int>(list);
来源：http://dali.shzxlz.cn/Article/details/gtdvtpgzsg.html

[D23] reduce 累积计算
来源：http://dali.gogol.net.cn/Article/details/gttmnczhqv.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtmaydgkdn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.vqdsnc.cn/Article/details/gtnpqegjzs.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtbeoofvnx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtqlcailbz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.havefunace.top/Article/details/gtjhxlssib.html

Go:   // 手写循环
来源：http://dali.zhoulong.xyz/Article/details/gtcuiqnydh.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jinqigufen.top/Article/details/gtyxdqorwt.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.snrcjt.cn/Article/details/gtmadvwnjh.html

[D24] 字典 / Map 基本操作
来源：http://dali.yj202588.top/Article/details/gtrnwnnivd.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.nwbrower.top/Article/details/gtxjjxomjz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.chenlongwang.top/Article/details/gtmnxnujap.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yonumen.top/Article/details/gtquaygccg.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.guowangkeji.top/Article/details/gtknmwdisi.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yonumen.top/Article/details/gtjmdbxqzy.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yvedp.cn/Article/details/gtqhsgujub.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.c1oappe.top/Article/details/gtubfhjbrp.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.smart0.xyz/Article/details/gtvuwpcanv.html

[D25] Set 集合去重与交并差
来源：http://dali.jianghu66.top/Article/details/gtosnhicpp.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hammf.cn/Article/details/gtxxgqrvwq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinqigfzy.top/Article/details/gtxvdqebmn.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cdnleiting.top/Article/details/gtiakfkusq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jqgfzy.top/Article/details/gtrabrtzco.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jyoumei.cn/Article/details/gtjhodrxkt.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.sxryk.cn/Article/details/gtbvdssbrb.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpkqsbgla.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.dianchejie.cn/Article/details/gtsmvbeepb.html

[D26] 数组转字符串
来源：http://dali.cqqwz.cn/Article/details/gtbrupsauz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.chenlongwang.top/Article/details/gtdkvndsnf.html

PHP:  implode(", ", $arr);
来源：http://dali.gogol.net.cn/Article/details/gtwungqjpx.html

JS:   arr.join(", ")
来源：http://dali.hywenlv.cn/Article/details/gtpekwtdbd.html

TS:   arr.join(", ")
来源：http://dali.nanxinkj.top/Article/details/gtqiqdjayk.html

Java: String.join(", ", list)
来源：http://dali.cashguo.top/Article/details/gtzzukvkyi.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yuanzhike.top/Article/details/gtfenahdgh.html

Ruby: arr.join(", ")
来源：http://dali.cheryme.top/Article/details/gtpkmeotjk.html

C#:   string.Join(", ", list)
来源：http://dali.sysykeji.top/Article/details/gtovamzfcy.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtvnzfydek.html

E. 字符串处理
来源：http://dali.chenjidiqi.icu/Article/details/gtxujkvqiq.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtqepqtaox.html

[E01] 拼接字符串
来源：http://dali.xinyue.icu/Article/details/gtitljxsnu.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.birdmap.top/Article/details/gtrblekikk.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhengqikj.top/Article/details/gtpqkoiqbx.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenzaomai.com/Article/details/gtsghvuuwh.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nanxinkj.top/Article/details/gtapnoaroq.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xziqi.cn/Article/details/gtmlnkzpst.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhiwuduotai.top/Article/details/gtyphwydjs.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.tianlin.xyz/Article/details/gttrhwaapj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtpztiyedp.html

[E02] 重复字符串
来源：http://dali.guowangkeji.top/Article/details/gtksxjvslo.html

Py:   "ab" * 3
来源：http://dali.yangfankeji.com/Article/details/gttkkiyhnh.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jiagoushi.top/Article/details/gtlpuxtqob.html

JS:   "ab".repeat(3)
来源：http://dali.cheryme.top/Article/details/gtecyqbndj.html

TS:   "ab".repeat(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzeemvyao.html

Java: "ab".repeat(3)
来源：http://dali.dianchejie.cn/Article/details/gttvrettha.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.mhx1999.top/Article/details/gtmbbmzjla.html

Ruby: "ab" * 3
来源：http://dali.feifeiyinyue.top/Article/details/gtcnvrrulf.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yongpay.top/Article/details/gtuwjlpgnf.html

[E03] 截取子串
来源：http://dali.hysaishi.cn/Article/details/gtvlsuamwx.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhixingplan.top/Article/details/gtjyngpbfk.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yanxiufei.cn/Article/details/gtxvbubkaw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yj202588.top/Article/details/gtgokasory.html

TS:   s.slice(1, 4)
来源：http://dali.fengsongda.top/Article/details/gtciqdklkv.html

Java: s.substring(1, 4)
来源：http://dali.cqqwz.cn/Article/details/gtbkavtzvw.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gtlherrbex.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.chenzaomai.com/Article/details/gtnsfgazch.html

C#:   s.Substring(1, 3)
来源：http://dali.iojbl.cn/Article/details/gtyqxupzjs.html

[E04] 查找子串位置
来源：http://dali.zhengqikj.top/Article/details/gtrubzjrhj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sxryk.cn/Article/details/gtikepkmcd.html


<!-- 参考信息 -->