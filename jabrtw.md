代发 wailian999

[C14] 泛型函数
来源：http://dali.jqgufenzy.top/Article/details/gt2ypmfgnzy.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.sufxvd.cn/Article/details/gt2upweepmw.html

PHP:  // 无泛型
来源：http://dali.chenjidiqi.icu/Article/details/gt2dddeklfd.html

JS:   // 无泛型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dlpcerff.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.vqdsnc.cn/Article/details/gt2nnryaouu.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.vqdsnc.cn/Article/details/gt2tceqfmek.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.sufxvd.cn/Article/details/gt2bdpzeome.html

Ruby: # 无泛型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xpbkdtve.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jqgfzy.top/Article/details/gt2alfpfnyb.html

[C15] 解构 / 展开参数
来源：http://dali.fzhhl.top/Article/details/gt2swwtkidt.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hysaishi.cn/Article/details/gt2zkeqqbdd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.sysykeji.top/Article/details/gt2mueksfrm.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2ruxfgroh.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.chenlongwang.top/Article/details/gt2qhqyxzvf.html

Java: // 无解构
来源：http://dali.iojbl.cn/Article/details/gt2shuhpmaa.html

Go:   // 无解构
来源：http://dali.hammf.cn/Article/details/gt2heglzlhx.html

Ruby: a, b = pair
来源：http://dali.sufxvd.cn/Article/details/gt2sgxynowm.html

C#:   var (a, b) = pair;
来源：http://dali.xuanzx.com/Article/details/gt2cklszrbg.html

[C16] 函数 / 方法重载
来源：http://dali.hysaishi.cn/Article/details/gt2qucrkxwg.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xziqi.cn/Article/details/gt2ouhkjpyd.html

PHP:  // 无重载
来源：http://dali.yuanzhike.top/Article/details/gt2osogkqob.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.havefunace.top/Article/details/gt2qebfgpai.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.gaohongyu789.top/Article/details/gt2ocgjsgjt.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jqgfzy.top/Article/details/gt2ignindji.html

Go:   // 无重载：用不同函数名
来源：http://dali.xinyue.icu/Article/details/gt2olflinhk.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zdqjudy.top/Article/details/gt2lxbretpm.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yuanzhike.top/Article/details/gt2auynmrdx.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2nhrpoznu.html

D. 数组 / 列表 / 集合
来源：http://dali.xuanzx.com/Article/details/gt2ynvehhue.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2ebbfgzuy.html

[D01] 创建数组 / 列表
来源：http://dali.wangshuangyany.cn/Article/details/gt2dzhiytqk.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.chenlongwang.top/Article/details/gt2hpvdqrqc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hysaishi.cn/Article/details/gt2zdgixijk.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.tanke756.top/Article/details/gt2dmthsgmd.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.daria6918.cn/Article/details/gt2uifnlekc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.gotoacloud.top/Article/details/gt2trkifrfl.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.wangshuangyany.cn/Article/details/gt2tdhjcswm.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hnxiangtu.top/Article/details/gt2ehfbvuvi.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hfpthk.cn/Article/details/gt2nimggetg.html

[D02] 追加元素到末尾
来源：http://dali.kuanghao11.cn/Article/details/gt2mojwyqdq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhixingplan.top/Article/details/gt2vpehqrfo.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.redwolf501.top/Article/details/gt2honuxbji.html

JS:   arr.push(4);
来源：http://dali.jinqigufen.top/Article/details/gt2tarnzxxy.html

TS:   arr.push(4);
来源：http://dali.ivvv.top/Article/details/gt2qcugdrpy.html

Java: list.add(4);
来源：http://dali.aizwys.cn/Article/details/gt2tiqjmowi.html

Go:   arr = append(arr, 4)
来源：http://dali.nanxinkj.top/Article/details/gt2fdoambay.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.c1oappe.top/Article/details/gt2nihyzkym.html

C#:   list.Add(4);
来源：http://dali.sweek.top/Article/details/gt2kxrburwe.html

[D03] 在指定位置插入元素
来源：http://dali.chenlongwang.top/Article/details/gt2dgrbvdxx.html

Py:   arr.insert(0, 0)
来源：http://dali.cucudq.cn/Article/details/gt2bhwqrrli.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jyoumei.cn/Article/details/gt2ebyyyntf.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yueranfly.top/Article/details/gt2lkxodghr.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qyhcbhcl.html

Java: list.add(0, 0);
来源：http://dali.hfpthk.cn/Article/details/gt2hksxkrql.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jinqigfzy.top/Article/details/gt2nmkicihg.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yj20258.top/Article/details/gt2eecsphyd.html

C#:   list.Insert(0, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gt2snwnlehi.html

[D04] 删除元素
来源：http://dali.shzxlz.cn/Article/details/gt2iruwrffi.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhengqikj.top/Article/details/gt2ksksfxtg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yueranfly.top/Article/details/gt2siqkfecq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.haohaochexian.top/Article/details/gt2emwxtzuk.html

TS:   arr.splice(0, 1);
来源：http://dali.xziqi.cn/Article/details/gt2sjxeyzvi.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yj202588.top/Article/details/gt2eddtoppm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shzxlz.cn/Article/details/gt2psbqtpjg.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ctxzohkr.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yanxiufei.cn/Article/details/gt2mutgxcnq.html

[D05] 访问与修改元素
来源：http://dali.yuxming.cn/Article/details/gt2jclcpcdf.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.snrcjt.cn/Article/details/gt2gfpqszqn.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.snrcjt.cn/Article/details/gt2gyvkyuwx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shzxlz.cn/Article/details/gt2rosptmll.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.fzhhl.top/Article/details/gt2stuzzfsx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ivvv.top/Article/details/gt2xoemgznm.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.wangshuangyany.cn/Article/details/gt2hjbuvzse.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.meibo888.top/Article/details/gt2tpzsiimk.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xylfe.cn/Article/details/gt2dulqvpbq.html

[D06] 数组长度
来源：http://dali.hammf.cn/Article/details/gt2moyfctnq.html

Py:   len(arr)
来源：http://dali.c1oappe.top/Article/details/gt2kpreylgm.html

PHP:  count($arr);
来源：http://dali.mhx1999.top/Article/details/gt2jxwulxca.html

JS:   arr.length
来源：http://dali.guowangkeji.top/Article/details/gt2yiqyedro.html

TS:   arr.length
来源：http://dali.wangdashe.top/Article/details/gt2vfjofoqj.html

Java: list.size();
来源：http://dali.jqgufenzy.top/Article/details/gt2jhkecvnv.html

Go:   len(arr)
来源：http://dali.mhx1999.top/Article/details/gt2mvfgplvq.html

Ruby: arr.length; arr.size
来源：http://dali.pycfn.com/Article/details/gt2butdknmc.html

C#:   list.Count;
来源：http://dali.jiagoushi.top/Article/details/gt2pfjusrkm.html

[D07] 切片 / 取子数组
来源：http://dali.mhx1999.top/Article/details/gt2yhtsfkma.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.aizwys.cn/Article/details/gt2gnuisezm.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ppjwa.cn/Article/details/gt2vgjqxyaq.html

JS:   arr.slice(1, 4);
来源：http://dali.redwolf501.top/Article/details/gt2brylishk.html

TS:   arr.slice(1, 4);
来源：http://dali.xziqi.cn/Article/details/gt2skjsaycw.html

Java: list.subList(1, 4);
来源：http://dali.xylfe.cn/Article/details/gt2hqsmgfwb.html

Go:   arr[1:4]
来源：http://dali.sweek.top/Article/details/gt2hubxbjmi.html

Ruby: arr[1, 3]
来源：http://dali.316326.xyz/Article/details/gt2ghdweotv.html

C#:   list.GetRange(1, 3);
来源：http://dali.tianlin.xyz/Article/details/gt2sttnunwf.html

[D08] 合并两个数组
来源：http://dali.hammf.cn/Article/details/gt2fzwwstyk.html

Py:   a + b;  a.extend(b)
来源：http://dali.yj202588.top/Article/details/gt2xaoqbewx.html

PHP:  array_merge($a, $b);
来源：http://dali.gogol.net.cn/Article/details/gt2zuizjenl.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jqgufenzy.top/Article/details/gt2cjivxrhg.html

TS:   [...a, ...b];
来源：http://dali.jinqigufen.top/Article/details/gt2wxczmvkl.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.0kj1m.cn/Article/details/gt2ofjcvxhz.html

Go:   append(a, b...)
来源：http://dali.yueranfly.top/Article/details/gt2qylheqav.html

Ruby: a + b;  a.concat(b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jwbztggr.html

C#:   a.Concat(b).ToList()
来源：http://dali.andypj.xyz/Article/details/gt2cmqvssee.html

[D09] 排序（升序）
来源：http://dali.hfpthk.cn/Article/details/gt2qejxbyyr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zycfv.cn/Article/details/gt2vhjzcvut.html

PHP:  sort($arr);
来源：http://dali.nanxinkj.top/Article/details/gt2emakzmxi.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yanxiufei.cn/Article/details/gt2ckfqqrsr.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jianghu66.top/Article/details/gt2yupbetet.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zycfv.cn/Article/details/gt2jpolpnet.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zpvqlqvo.html

Ruby: arr.sort
来源：http://dali.yj20258.top/Article/details/gt2twizcroc.html

C#:   list.Sort();
来源：http://dali.316326.xyz/Article/details/gt2cybthmwa.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yangfankeji.com/Article/details/gt2fqwkkwbx.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.nanxinkj.top/Article/details/gt2ortgvegl.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hongshengwenyu.top/Article/details/gt2odmlojbg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.mhx1999.top/Article/details/gt2lcbswufe.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2whnfrryr.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.smart0.xyz/Article/details/gt2lexkwzru.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hywenlv.cn/Article/details/gt2bgravzvj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.bjfxy.top/Article/details/gt2rwmiwddx.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fvodcaxz.html

[D11] 反转数组
来源：http://dali.yangfankeji.com/Article/details/gt2xistcsos.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.snrcjt.cn/Article/details/gt2zhsyzgvg.html

PHP:  array_reverse($arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2ruvwcxxq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.kuanghao11.cn/Article/details/gt2wkdhjpmq.html

TS:   [...arr].reverse();
来源：http://dali.yj202588.top/Article/details/gt2ufhvcpbe.html

Java: Collections.reverse(list);
来源：http://dali.316326.xyz/Article/details/gt2gszzwwrw.html

Go:   slices.Reverse(arr)
来源：http://dali.xylfe.cn/Article/details/gt2rknufhsj.html

Ruby: arr.reverse
来源：http://dali.mhx1999.top/Article/details/gt2ynispqsj.html

C#:   list.Reverse();
来源：http://dali.xziqi.cn/Article/details/gt2llyrspmh.html

[D12] 查找元素下标
来源：http://dali.aizwys.cn/Article/details/gt2uekdciam.html

Py:   arr.index(x);  x in arr
来源：http://dali.0kj1m.cn/Article/details/gt2qaoqjvzq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.fzhhl.top/Article/details/gt2xaipeosa.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jianghu66.top/Article/details/gt2ckbtjaml.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.birdmap.top/Article/details/gt2ignprkjm.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ibongarm.html

Go:   slices.Index(arr, x)
来源：http://dali.cashguo.top/Article/details/gt2brimcgeh.html

Ruby: arr.index(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ofuoorxv.html

C#:   list.IndexOf(x);
来源：http://dali.gaohongyu789.top/Article/details/gt2vdtyeewt.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sngnjuoa.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yj202588.top/Article/details/gt2sjtdxuoe.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.sxryk.cn/Article/details/gt2apmufgex.html

JS:   arr.filter(x => x > 3)
来源：http://dali.redwolf501.top/Article/details/gt2pqspknjf.html

TS:   arr.filter(x => x > 3)
来源：http://dali.aibaodan.cn/Article/details/gt2qomummwt.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yangfankeji.com/Article/details/gt2ujtjwpvj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.0kj1m.cn/Article/details/gt2obolodci.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.sxryk.cn/Article/details/gt2mrucdxiw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zdqjudy.top/Article/details/gt2gjehbhiv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cqqwz.cn/Article/details/gt2mycuchpz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cucudq.cn/Article/details/gt2ksmqujov.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2snwnruwr.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lhgmgulc.html

TS:   arr.map(x => x * 2)
来源：http://dali.yueranfly.top/Article/details/gt2pnvonyei.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xziqi.cn/Article/details/gt2kuquxfff.html

Go:   // 手写循环
来源：http://dali.nwbrower.top/Article/details/gt2mulbjprx.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.cheryme.top/Article/details/gt2nufssuoz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.svipenyu.cn/Article/details/gt2lcwbcqad.html

[D15] 去重
来源：http://dali.jinqigufen.top/Article/details/gt2acjeerly.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.0kj1m.cn/Article/details/gt2cwhxwzzo.html

PHP:  array_unique($arr);
来源：http://dali.dashuyun.cn/Article/details/gt2qiqtdxbv.html

JS:   [...new Set(arr)]
来源：http://dali.ppjwa.cn/Article/details/gt2caxovfjd.html

TS:   [...new Set(arr)]
来源：http://dali.zhongyouzk.top/Article/details/gt2yqnyndix.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.havefunace.top/Article/details/gt2lgpetsar.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhongyouzk.top/Article/details/gt2upfiblya.html

Ruby: arr.uniq
来源：http://dali.0kj1m.cn/Article/details/gt2oyqbqfym.html

C#:   list.Distinct().ToList()
来源：http://dali.yangfankeji.com/Article/details/gt2mcokrobq.html

[D16] 求和与平均值
来源：http://dali.dianchejie.cn/Article/details/gt2wejufxwv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zhxlbudv.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hysaishi.cn/Article/details/gt2jhxwxzgu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yanxiufei.cn/Article/details/gt2ukpbffnh.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgufenzy.top/Article/details/gt2ckeryugb.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.svipenyu.cn/Article/details/gt2fiibzfyp.html

Go:   // 手写循环累加
来源：http://dali.nanxinkj.top/Article/details/gt2snayvgpe.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.vqdsnc.cn/Article/details/gt2ydivngbk.html

C#:   list.Sum();  list.Average()
来源：http://dali.xziqi.cn/Article/details/gt2nfqxhycw.html

[D17] 最大值与最小值
来源：http://dali.snrcjt.cn/Article/details/gt2coucssum.html

Py:   max(arr);  min(arr)
来源：http://dali.fzhhl.top/Article/details/gt2cmqslihy.html

PHP:  max($arr);  min($arr);
来源：http://dali.ppjwa.cn/Article/details/gt2qidibhsd.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.chenzaomai.com/Article/details/gt2qtlzrgih.html

TS:   Math.max(...arr);
来源：http://dali.redwolf501.top/Article/details/gt2zydgrlyx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.chenlongwang.top/Article/details/gt2wgpisgmp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.guowangkeji.top/Article/details/gt2bvkyysjw.html

Ruby: arr.max;  arr.min
来源：http://dali.ppjwa.cn/Article/details/gt2vofcofwj.html

C#:   list.Max();  list.Min()
来源：http://dali.xuetiantiany.cn/Article/details/gt2dewxuncj.html

[D18] 扁平化嵌套数组
来源：http://dali.gogol.net.cn/Article/details/gt2jwsvujoo.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.quarkkingdee.top/Article/details/gt2dnnrdtyu.html

PHP:  array_merge(...$nested);
来源：http://dali.9152youxi.cn/Article/details/gt2phuarkbd.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.mhx1999.top/Article/details/gt2fxavryfr.html

TS:   nested.flat();
来源：http://dali.jinqigufen.top/Article/details/gt2wnietput.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.dashuyun.cn/Article/details/gt2vagyoyhv.html

Go:   // 手写双层循环
来源：http://dali.xinyue.icu/Article/details/gt2zotuqhav.html

Ruby: nested.flatten
来源：http://dali.dianchejie.cn/Article/details/gt2vslkqcza.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jyoumei.cn/Article/details/gt2lvhmaiuw.html

[D19] 按字段分组
来源：http://dali.mhx1999.top/Article/details/gt2gznhvbwr.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.guowangkeji.top/Article/details/gt2zuwhhrcd.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jinqigfzy.top/Article/details/gt2liwdobrx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ybcxt.top/Article/details/gt2jwpvbawb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yj20258888.top/Article/details/gt2cvgabcye.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sufxvd.cn/Article/details/gt2kkwrdaoy.html

Go:   // 手写 map[string][]T
来源：http://dali.yueranfly.top/Article/details/gt2wopfeboc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.mhx1999.top/Article/details/gt2yasrmxyk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ppjwa.cn/Article/details/gt2qakxngxt.html

[D20] 统计每个元素出现次数
来源：http://dali.fengsongda.top/Article/details/gt2cxcaiumb.html

Py:   Counter(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2tyyneylr.html

PHP:  array_count_values($arr);
来源：http://dali.yuanzhike.top/Article/details/gt2upgtodpa.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.wangdashe.top/Article/details/gt2vzbgetol.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hywenlv.cn/Article/details/gt2aivvfzxr.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pksksyjj.html

Go:   // 手写 map[T]int
来源：http://dali.daria6918.cn/Article/details/gt2nrurbrlj.html

Ruby: arr.tally
来源：http://dali.dashuyun.cn/Article/details/gt2ieqbbnir.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.birdmap.top/Article/details/gt2oapcimij.html

[D21] 判断是否包含某元素
来源：http://dali.zhengqikj.top/Article/details/gt2kfdrxhha.html

Py:   x in arr
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ouvobquf.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ieqftqsq.html

JS:   arr.includes(x)
来源：http://dali.cucudq.cn/Article/details/gt2misarycc.html

TS:   arr.includes(x)
来源：http://dali.jyoumei.cn/Article/details/gt2umqpmyhr.html

Java: list.contains(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2pdphzvei.html

Go:   slices.Contains(arr, x)
来源：http://dali.ydzc1.top/Article/details/gt2gosnxidz.html

Ruby: arr.include?(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ponkuxeg.html

C#:   list.Contains(x)
来源：http://dali.hysaishi.cn/Article/details/gt2vzkdzobs.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cucudq.cn/Article/details/gt2bwnyalsl.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.guowangkeji.top/Article/details/gt2xrwhyuar.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.smart0.xyz/Article/details/gt2nwixmokc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ivvv.top/Article/details/gt2yutbojfo.html

TS:   [...arr];
来源：http://dali.ivvv.top/Article/details/gt2sgoazbxg.html

Java: new ArrayList<>(list);
来源：http://dali.cqqwz.cn/Article/details/gt2xdaaywvl.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hammf.cn/Article/details/gt2hahzwcat.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xuanzx.com/Article/details/gt2xgxpcqey.html

C#:   new List<int>(list);
来源：http://dali.yuanzhike.top/Article/details/gt2hzqznfqn.html

[D23] reduce 累积计算
来源：http://dali.guowangkeji.top/Article/details/gt2hgkzckcf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.9152youxi.cn/Article/details/gt2bvmeyzpv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vbpspvcl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhixingplan.top/Article/details/gt2wvzkkhwg.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nedcecml.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jqgufenzy.top/Article/details/gt2bfbvtgcc.html

Go:   // 手写循环
来源：http://dali.zhongyouzk.top/Article/details/gt2gfwvpcec.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.nanxuanxn.top/Article/details/gt2bxrciigm.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2sezruchd.html

[D24] 字典 / Map 基本操作
来源：http://dali.wangdashe.top/Article/details/gt2pmgyimcu.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jianghu66.top/Article/details/gt2mpmgqjan.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jinqigfzy.top/Article/details/gt2gskkkyit.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.0kj1m.cn/Article/details/gt2jcgbfzux.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jqgufenzy.top/Article/details/gt2rhhwoxym.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yvedp.cn/Article/details/gt2mbzhhxdw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhengqikj.top/Article/details/gt2punmzfav.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yueranfly.top/Article/details/gt2ujilerbl.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zycfv.cn/Article/details/gt2jrzfpnhw.html

[D25] Set 集合去重与交并差
来源：http://dali.hfpthk.cn/Article/details/gt2xlyfnzti.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.aizwys.cn/Article/details/gt2qjbvhyzb.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xylfe.cn/Article/details/gt2svfsgxyu.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.daxiang520.top/Article/details/gt2ernvoyge.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.chenjidiqi.icu/Article/details/gt2buysachf.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.aibaodan.cn/Article/details/gt2wclowmwj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xkwqhgxy.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.svipenyu.cn/Article/details/gt2shlbfzah.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.9152youxi.cn/Article/details/gt2zkidzewi.html

[D26] 数组转字符串
来源：http://dali.xziqi.cn/Article/details/gt2vldlswfq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hammf.cn/Article/details/gt2jhieaigy.html

PHP:  implode(", ", $arr);
来源：http://dali.jianghu66.top/Article/details/gt2itjnjkhv.html

JS:   arr.join(", ")
来源：http://dali.yuxming.cn/Article/details/gt2aglkazcq.html

TS:   arr.join(", ")
来源：http://dali.gogol.net.cn/Article/details/gt2rbwqdizg.html

Java: String.join(", ", list)
来源：http://dali.kuanghao11.cn/Article/details/gt2lkzylklv.html

Go:   strings.Join(strs, ", ")
来源：http://dali.gzhubu.top/Article/details/gt2akwdwgoo.html

Ruby: arr.join(", ")
来源：http://dali.nanxinkj.top/Article/details/gt2awfnzgfr.html

C#:   string.Join(", ", list)
来源：http://dali.vqdsnc.cn/Article/details/gt2oxrkjenw.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2fkyvqvzd.html

E. 字符串处理
来源：http://dali.chenlongwang.top/Article/details/gt2biuzthyp.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2qtsqsqui.html

[E01] 拼接字符串
来源：http://dali.cdnleiting.top/Article/details/gt2wqtxobxs.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhongyouzk.top/Article/details/gt2rdvrzcwi.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.daxiang520.top/Article/details/gt2wjxcmtih.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.guannengcc.top/Article/details/gt2tgikmerq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gotoacloud.top/Article/details/gt2nfynpkir.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.birdmap.top/Article/details/gt2ljqoihsp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cashguo.top/Article/details/gt2xnfyqftt.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.wangdashe.top/Article/details/gt2afpnxckc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gt2zsfkchwl.html

[E02] 重复字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2ubjtlnbo.html

Py:   "ab" * 3
来源：http://dali.snrcjt.cn/Article/details/gt2eythyusl.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cqqwz.cn/Article/details/gt2gmphmiys.html

JS:   "ab".repeat(3)
来源：http://dali.yj202588.top/Article/details/gt2srzowdzm.html

TS:   "ab".repeat(3)
来源：http://dali.zhoulong.xyz/Article/details/gt2lgjamrao.html

Java: "ab".repeat(3)
来源：http://dali.tian-w.cn/Article/details/gt2kmkukpay.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhengqikj.top/Article/details/gt2phfgyhkl.html

Ruby: "ab" * 3
来源：http://dali.jyoumei.cn/Article/details/gt2kztayuby.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dqkosxun.html

[E03] 截取子串
来源：http://dali.jiagoushi.top/Article/details/gt2lytstkjf.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.aizwys.cn/Article/details/gt2aiderwex.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gt2tweizslu.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ehwqpu.com/Article/details/gt2ndmeqaic.html

TS:   s.slice(1, 4)
来源：http://dali.zycfv.cn/Article/details/gt2xezopmzh.html

Java: s.substring(1, 4)
来源：http://dali.cqqwz.cn/Article/details/gt2oosqxzyu.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhengqikj.top/Article/details/gt2skgkufes.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.gzhubu.top/Article/details/gt2dstjiatj.html

C#:   s.Substring(1, 3)
来源：http://dali.jqgfzy.top/Article/details/gt2tabuwjjh.html

[E04] 查找子串位置
来源：http://dali.zhongyouzk.top/Article/details/gt2fusdgumn.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yj20258.top/Article/details/gt2svkxzgnr.html

PHP:  strpos($s, "x");
来源：http://dali.cdnleiting.top/Article/details/gt2unxvtxih.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhoulong.xyz/Article/details/gt2bwtrtjox.html

TS:   s.indexOf("x")
来源：http://dali.aibaodan.cn/Article/details/gt2lunhhxaw.html

Java: s.indexOf("x")
来源：http://dali.wangshuangyany.cn/Article/details/gt2zquraszl.html


<!-- 参考信息 -->