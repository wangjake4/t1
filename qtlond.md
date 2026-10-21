代发 wailian999

[C14] 泛型函数
来源：http://dali.mhx1999.top/Article/details/gtzzypvlck.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jqgfzy.top/Article/details/gtbjxddxow.html

PHP:  // 无泛型
来源：http://dali.hammf.cn/Article/details/gtzriaydya.html

JS:   // 无泛型
来源：http://dali.zhongyouzk.top/Article/details/gtoqxxbpgj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.tianlin.xyz/Article/details/gtgopqbire.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.sysykeji.top/Article/details/gtwlzzjtbi.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbqmluhaa.html

Ruby: # 无泛型
来源：http://dali.nwbrower.top/Article/details/gtjbolppoc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hnxiangtu.top/Article/details/gtygreqhqi.html

[C15] 解构 / 展开参数
来源：http://dali.316326.xyz/Article/details/gtopkserwl.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jqgfzy.top/Article/details/gtukukfxfc.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zycfv.cn/Article/details/gtugkpkmua.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ppjwa.cn/Article/details/gtxjfyjonh.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtksiiduao.html

Java: // 无解构
来源：http://dali.shanyushiyangtech.top/Article/details/gtlkbtdkjx.html

Go:   // 无解构
来源：http://dali.9152youxi.cn/Article/details/gtztiipkkw.html

Ruby: a, b = pair
来源：http://dali.shzxlz.cn/Article/details/gtuaqycuzx.html

C#:   var (a, b) = pair;
来源：http://dali.jinqigfzy.top/Article/details/gthywnrlxn.html

[C16] 函数 / 方法重载
来源：http://dali.yj20258888.top/Article/details/gtbkasgaht.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hongshengwenyu.top/Article/details/gtjslbetvw.html

PHP:  // 无重载
来源：http://dali.hammf.cn/Article/details/gtrulzcsqw.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.tanke756.top/Article/details/gtjyzjgenb.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.vqdsnc.cn/Article/details/gtfcxzjpqw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yanxiufei.cn/Article/details/gtkoosjaaa.html

Go:   // 无重载：用不同函数名
来源：http://dali.dashuyun.cn/Article/details/gthtlcgbpk.html

Ruby: # 无重载：靠动态参数
来源：http://dali.smart0.xyz/Article/details/gtidawqcsk.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yanxiufei.cn/Article/details/gtwddjmhhu.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtpusbkkhi.html

D. 数组 / 列表 / 集合
来源：http://dali.wangshuangyany.cn/Article/details/gtifjeoufp.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gthnafanju.html

[D01] 创建数组 / 列表
来源：http://dali.guowangkeji.top/Article/details/gtwrcnjeln.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.feifeiyinyue.top/Article/details/gttsqeslhi.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.kuanghao11.cn/Article/details/gtrhqdcytq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ivvv.top/Article/details/gtuohiayyu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hongshengwenyu.top/Article/details/gtizjyebhw.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.pengpengdd.cyou/Article/details/gthokndiws.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.redwolf501.top/Article/details/gtotnumuli.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ydzc1.top/Article/details/gtieudfosf.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.guannengcc.top/Article/details/gtsjvfbqzb.html

[D02] 追加元素到末尾
来源：http://dali.daxiang520.top/Article/details/gtghbaihkn.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.snrcjt.cn/Article/details/gtxvmqcxqu.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhengqikj.top/Article/details/gtflniypct.html

JS:   arr.push(4);
来源：http://dali.chenlongwang.top/Article/details/gtqqlvumju.html

TS:   arr.push(4);
来源：http://dali.fzhhl.top/Article/details/gtoctmrjdu.html

Java: list.add(4);
来源：http://dali.meibo888.top/Article/details/gthgverscg.html

Go:   arr = append(arr, 4)
来源：http://dali.zhengqikj.top/Article/details/gtfakzkfbu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.aizwys.cn/Article/details/gtideezqyv.html

C#:   list.Add(4);
来源：http://dali.quarkkingdee.top/Article/details/gtxuqejiyy.html

[D03] 在指定位置插入元素
来源：http://dali.sufxvd.cn/Article/details/gtcueerdlq.html

Py:   arr.insert(0, 0)
来源：http://dali.hysaishi.cn/Article/details/gtjaulypxy.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jlsjyb.cn/Article/details/gtotvfiyoq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.316326.xyz/Article/details/gtfwzkklzm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zycfv.cn/Article/details/gtmxtqobyd.html

Java: list.add(0, 0);
来源：http://dali.zhongyouzk.top/Article/details/gtwgjaoaev.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jiagoushi.top/Article/details/gtiwzhylxe.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yonumen.top/Article/details/gtyttsdbbi.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gtfsbllrgq.html

[D04] 删除元素
来源：http://dali.shzxlz.cn/Article/details/gtgbvysoft.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.sxryk.cn/Article/details/gtkwbsbacb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.fengsongda.top/Article/details/gtkdfpuviy.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhengqikj.top/Article/details/gtblvzoppz.html

TS:   arr.splice(0, 1);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbnhcicjb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.chenlongwang.top/Article/details/gtgxdqhajx.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.tanke756.top/Article/details/gthowinrxy.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhengqikj.top/Article/details/gtvlsleqsh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yj20258888.top/Article/details/gtwwdlflac.html

[D05] 访问与修改元素
来源：http://dali.316326.xyz/Article/details/gtzegohtrj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.c1oappe.top/Article/details/gtxuyfoktp.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yuxming.cn/Article/details/gtqmzikxqu.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.meibo888.top/Article/details/gtlmjuefdi.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xuetiantiany.cn/Article/details/gtecibhxlk.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.fengsongda.top/Article/details/gtjliaclzb.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhiwuduotai.top/Article/details/gtiidzoboq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxinkj.top/Article/details/gtwlukgzcg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.aizwys.cn/Article/details/gtdiwoycfr.html

[D06] 数组长度
来源：http://dali.guowangkeji.top/Article/details/gtltdmttwx.html

Py:   len(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttgsbglog.html

PHP:  count($arr);
来源：http://dali.redwolf501.top/Article/details/gtwllkibww.html

JS:   arr.length
来源：http://dali.andypj.xyz/Article/details/gtkslirxua.html

TS:   arr.length
来源：http://dali.yj202588.top/Article/details/gtllkdlseu.html

Java: list.size();
来源：http://dali.cheryme.top/Article/details/gtqlgtipcp.html

Go:   len(arr)
来源：http://dali.zhixingplan.top/Article/details/gtckuvmtfl.html

Ruby: arr.length; arr.size
来源：http://dali.zhixingplan.top/Article/details/gttsscjywm.html

C#:   list.Count;
来源：http://dali.ppjwa.cn/Article/details/gtnmmojmql.html

[D07] 切片 / 取子数组
来源：http://dali.iojbl.cn/Article/details/gtbpjqbagl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.316326.xyz/Article/details/gtwvqplkyb.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtycnrczga.html

JS:   arr.slice(1, 4);
来源：http://dali.daria6918.cn/Article/details/gtxkutcixx.html

TS:   arr.slice(1, 4);
来源：http://dali.shangyingyoupin.top/Article/details/gtxryksnqa.html

Java: list.subList(1, 4);
来源：http://dali.cqqwz.cn/Article/details/gtdvfuuoro.html

Go:   arr[1:4]
来源：http://dali.wangdashe.top/Article/details/gtwxzrnvrr.html

Ruby: arr[1, 3]
来源：http://dali.sweek.top/Article/details/gtevaiwbla.html

C#:   list.GetRange(1, 3);
来源：http://dali.jianghu66.top/Article/details/gthlvstdoc.html

[D08] 合并两个数组
来源：http://dali.gotoacloud.top/Article/details/gtipzveuxp.html

Py:   a + b;  a.extend(b)
来源：http://dali.birdmap.top/Article/details/gtdvapmoib.html

PHP:  array_merge($a, $b);
来源：http://dali.zhoulong.xyz/Article/details/gtnyfimsvp.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yvedp.cn/Article/details/gtgpzarydn.html

TS:   [...a, ...b];
来源：http://dali.guannengcc.top/Article/details/gtmqyjzfpc.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.tanke756.top/Article/details/gtyaikdydw.html

Go:   append(a, b...)
来源：http://dali.gaohongyu789.top/Article/details/gthlpdgozk.html

Ruby: a + b;  a.concat(b)
来源：http://dali.quarkkingdee.top/Article/details/gtlpshhqin.html

C#:   a.Concat(b).ToList()
来源：http://dali.nwbrower.top/Article/details/gtirgsadlq.html

[D09] 排序（升序）
来源：http://dali.jqgufenzy.top/Article/details/gtawaczunz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsfrsbfuv.html

PHP:  sort($arr);
来源：http://dali.andypj.xyz/Article/details/gtfiertxpz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.tianlin.xyz/Article/details/gtglvakqhv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ehwqpu.com/Article/details/gtusiubyzv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhoulong.xyz/Article/details/gtayknnnid.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtjrapsbmv.html

Ruby: arr.sort
来源：http://dali.zdqjudy.top/Article/details/gtdruqqbvv.html

C#:   list.Sort();
来源：http://dali.cheryme.top/Article/details/gtsuomhlcs.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hfpthk.cn/Article/details/gtnayzcjio.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cucudq.cn/Article/details/gtcdsfpoao.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shzxlz.cn/Article/details/gtpndfxyrz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guannengcc.top/Article/details/gtvfclsdxy.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.bjfxy.top/Article/details/gtzenrwhyv.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.snrcjt.cn/Article/details/gtbjeqzcln.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yongpay.top/Article/details/gtchcyxzhk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.havefunace.top/Article/details/gtnfooztiq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yongpay.top/Article/details/gteuchrjgw.html

[D11] 反转数组
来源：http://dali.zhixingplan.top/Article/details/gtmwxrvyxl.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.havefunace.top/Article/details/gtkvfjosfv.html

PHP:  array_reverse($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtcsjbddkq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yongpay.top/Article/details/gtqmvwonbu.html

TS:   [...arr].reverse();
来源：http://dali.sxryk.cn/Article/details/gtuqmvlizl.html

Java: Collections.reverse(list);
来源：http://dali.c1oappe.top/Article/details/gtzwzpwqar.html

Go:   slices.Reverse(arr)
来源：http://dali.yonumen.top/Article/details/gtjcaumzke.html

Ruby: arr.reverse
来源：http://dali.chenlongwang.top/Article/details/gtqfahlefa.html

C#:   list.Reverse();
来源：http://dali.hnqzz.top/Article/details/gtlzgmhkfu.html

[D12] 查找元素下标
来源：http://dali.gotoacloud.top/Article/details/gtnxpzqlit.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinqigufen.top/Article/details/gtprqredem.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ybcxt.top/Article/details/gtsyzhmqfk.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.guannengcc.top/Article/details/gtyqyxuogf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gogol.net.cn/Article/details/gtqxbmtsrt.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hongshengwenyu.top/Article/details/gtsxhmatwt.html

Go:   slices.Index(arr, x)
来源：http://dali.yonumen.top/Article/details/gtuyjcscey.html

Ruby: arr.index(x)
来源：http://dali.wangdashe.top/Article/details/gtmabcpdpq.html

C#:   list.IndexOf(x);
来源：http://dali.jianghu66.top/Article/details/gtezmiilba.html

[D13] 过滤（保留满足条件的）
来源：http://dali.dashuyun.cn/Article/details/gtfvmysbgs.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.quarkkingdee.top/Article/details/gtkzcagyxr.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.9152youxi.cn/Article/details/gtvbnmxnwu.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zdqjudy.top/Article/details/gtqvkgtbnb.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yueranfly.top/Article/details/gtwqlnqkbl.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.svipenyu.cn/Article/details/gtbdqtlkwu.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.fengsongda.top/Article/details/gtmzpgdnwr.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.daria6918.cn/Article/details/gtegyejium.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jiagoushi.top/Article/details/gtylpztypv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.feifeiyinyue.top/Article/details/gtwjzqqoht.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.snrcjt.cn/Article/details/gtdccsjyqx.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sysykeji.top/Article/details/gtoajtdvxq.html

JS:   arr.map(x => x * 2)
来源：http://dali.aizwys.cn/Article/details/gtfzreqohy.html

TS:   arr.map(x => x * 2)
来源：http://dali.xinyue.icu/Article/details/gtonrfkmub.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gtmydufbbf.html

Go:   // 手写循环
来源：http://dali.yj20258888.top/Article/details/gtxxoerxbo.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.fengsongda.top/Article/details/gtjmnyheje.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yongpay.top/Article/details/gtgzhzgeov.html

[D15] 去重
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlbqqxenr.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtapdbcrmc.html

PHP:  array_unique($arr);
来源：http://dali.cqqwz.cn/Article/details/gtftxazqca.html

JS:   [...new Set(arr)]
来源：http://dali.mhx1999.top/Article/details/gtzpbpypfk.html

TS:   [...new Set(arr)]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtumbowffj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdzfvjaij.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hnxiangtu.top/Article/details/gtrcuxazic.html

Ruby: arr.uniq
来源：http://dali.jlsjyb.cn/Article/details/gtossikvga.html

C#:   list.Distinct().ToList()
来源：http://dali.sweek.top/Article/details/gtpsxemkcv.html

[D16] 求和与平均值
来源：http://dali.guowangkeji.top/Article/details/gtzzlqgqvk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsngpbhod.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.svipenyu.cn/Article/details/gttzxylqro.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.dashuyun.cn/Article/details/gtnmmvegug.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yuanzhike.top/Article/details/gtersfsage.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yanxiufei.cn/Article/details/gtnwgvjion.html

Go:   // 手写循环累加
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlezedldn.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.iojbl.cn/Article/details/gtvtvzgqlj.html

C#:   list.Sum();  list.Average()
来源：http://dali.smart0.xyz/Article/details/gteqidnklr.html

[D17] 最大值与最小值
来源：http://dali.shzxlz.cn/Article/details/gtnebfsfas.html

Py:   max(arr);  min(arr)
来源：http://dali.chenlongwang.top/Article/details/gtknbtmjkc.html

PHP:  max($arr);  min($arr);
来源：http://dali.ehwqpu.com/Article/details/gtkdzupixt.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.aizwys.cn/Article/details/gtgwzeytpd.html

TS:   Math.max(...arr);
来源：http://dali.hywenlv.cn/Article/details/gtbncqyuie.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shangyingyoupin.top/Article/details/gthbxlaomt.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jiagoushi.top/Article/details/gtuvydavnw.html

Ruby: arr.max;  arr.min
来源：http://dali.yj20258.top/Article/details/gtyxgdnkzx.html

C#:   list.Max();  list.Min()
来源：http://dali.redwolf501.top/Article/details/gtgilgpaff.html

[D18] 扁平化嵌套数组
来源：http://dali.zhixingplan.top/Article/details/gtvidorkgs.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cucudq.cn/Article/details/gtzvacummc.html

PHP:  array_merge(...$nested);
来源：http://dali.cdnleiting.top/Article/details/gtuxudqllh.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sweek.top/Article/details/gtwubnrmdx.html

TS:   nested.flat();
来源：http://dali.yueranfly.top/Article/details/gtpebzvejj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jiagoushi.top/Article/details/gtxymtdrdn.html

Go:   // 手写双层循环
来源：http://dali.xuanzx.com/Article/details/gtkjiossfi.html

Ruby: nested.flatten
来源：http://dali.chenlongwang.top/Article/details/gtljrgccva.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ehwqpu.com/Article/details/gthzaezaly.html

[D19] 按字段分组
来源：http://dali.guannengcc.top/Article/details/gtzsqqvrip.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hnqzz.top/Article/details/gtfflmtbtn.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.pycfn.com/Article/details/gtqcwohjyj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cheryme.top/Article/details/gttoseopuz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hnqzz.top/Article/details/gtqoqdzbrx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.gaohongyu789.top/Article/details/gtwmtqzzmt.html

Go:   // 手写 map[string][]T
来源：http://dali.yueranfly.top/Article/details/gtvbejohek.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.9152youxi.cn/Article/details/gtsemeptyy.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhiwuduotai.top/Article/details/gtnqdnfofa.html

[D20] 统计每个元素出现次数
来源：http://dali.jinqigfzy.top/Article/details/gtfhqryrbf.html

Py:   Counter(arr)
来源：http://dali.hnqzz.top/Article/details/gttqjaqxol.html

PHP:  array_count_values($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgkqpyxxi.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yanxiufei.cn/Article/details/gtsbpwachg.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258.top/Article/details/gtetzbqsrr.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.kuanghao11.cn/Article/details/gtwlspibkw.html

Go:   // 手写 map[T]int
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcuwfxpxy.html

Ruby: arr.tally
来源：http://dali.smart0.xyz/Article/details/gtmmpfuzem.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.nanxuanxn.top/Article/details/gtjroemlwm.html

[D21] 判断是否包含某元素
来源：http://dali.zhengqikj.top/Article/details/gtdtohkkhd.html

Py:   x in arr
来源：http://dali.yuanzhike.top/Article/details/gtzmeawfeu.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtelprkkyd.html

JS:   arr.includes(x)
来源：http://dali.yonumen.top/Article/details/gtdjcnbusf.html

TS:   arr.includes(x)
来源：http://dali.aibaodan.cn/Article/details/gtzbteucsy.html

Java: list.contains(x)
来源：http://dali.yueranfly.top/Article/details/gtuusgcicj.html

Go:   slices.Contains(arr, x)
来源：http://dali.tian-w.cn/Article/details/gtxkpuymxv.html

Ruby: arr.include?(x)
来源：http://dali.yueranfly.top/Article/details/gtxykokhlu.html

C#:   list.Contains(x)
来源：http://dali.sweek.top/Article/details/gtpxscuwtb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.smart0.xyz/Article/details/gtlaompfbk.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gotoacloud.top/Article/details/gtahcbvuol.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.gaohongyu789.top/Article/details/gtxmfvvdfa.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.tianlin.xyz/Article/details/gtdlkkcklo.html

TS:   [...arr];
来源：http://dali.yongpay.top/Article/details/gtstxceisn.html

Java: new ArrayList<>(list);
来源：http://dali.chenjidiqi.icu/Article/details/gtcudcvgyp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yj202588.top/Article/details/gtsfekshlh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.aibaodan.cn/Article/details/gttclzndgo.html

C#:   new List<int>(list);
来源：http://dali.pycfn.com/Article/details/gtozwxogar.html

[D23] reduce 累积计算
来源：http://dali.redwolf501.top/Article/details/gtoiwpqndd.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yj202588.top/Article/details/gtcjsbeyxq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yvedp.cn/Article/details/gtvpedgdpc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtdzvnspbt.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zycfv.cn/Article/details/gtebrtagqk.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yj20258888.top/Article/details/gtcpnpyeov.html

Go:   // 手写循环
来源：http://dali.hywenlv.cn/Article/details/gtymcbqdtp.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jinqigufen.top/Article/details/gtodrtiueg.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yj20258888.top/Article/details/gtwqcbvzqf.html

[D24] 字典 / Map 基本操作
来源：http://dali.ivvv.top/Article/details/gtuipemgoo.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.sufxvd.cn/Article/details/gtftvvbuau.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.sysykeji.top/Article/details/gtprttuevw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yuxming.cn/Article/details/gtsqpqeitp.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zycfv.cn/Article/details/gtcwgbjajc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yj202588.top/Article/details/gtwbjoudwy.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.c1oappe.top/Article/details/gtytufpbyu.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xuanzx.com/Article/details/gtvqhktfgy.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.smart0.xyz/Article/details/gtricyhcgf.html

[D25] Set 集合去重与交并差
来源：http://dali.daxiang520.top/Article/details/gtbciwsebe.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.tianlin.xyz/Article/details/gtefrromro.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xziqi.cn/Article/details/gtmobbyeck.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhoulong.xyz/Article/details/gtsvllegzw.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthornqbqo.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.aibaodan.cn/Article/details/gtdzwaqlfl.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hfpthk.cn/Article/details/gtazppquhh.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgzsmqffd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.tian-w.cn/Article/details/gtavdcyuzl.html

[D26] 数组转字符串
来源：http://dali.cucudq.cn/Article/details/gtmrgwtoee.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yangfankeji.com/Article/details/gtuwgebvgf.html

PHP:  implode(", ", $arr);
来源：http://dali.jinqigfzy.top/Article/details/gtnsqaemve.html

JS:   arr.join(", ")
来源：http://dali.jinqigufen.top/Article/details/gtxxtjiokp.html

TS:   arr.join(", ")
来源：http://dali.sysykeji.top/Article/details/gtykeqkenm.html

Java: String.join(", ", list)
来源：http://dali.yuxming.cn/Article/details/gtiqcrxech.html

Go:   strings.Join(strs, ", ")
来源：http://dali.sxryk.cn/Article/details/gtcmgzjien.html

Ruby: arr.join(", ")
来源：http://dali.gotoacloud.top/Article/details/gttgmuytcx.html

C#:   string.Join(", ", list)
来源：http://dali.zdqjudy.top/Article/details/gtkvplhrnn.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtpiyvdhvn.html

E. 字符串处理
来源：http://dali.haohaochexian.top/Article/details/gtpoxvbywx.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtgudapbcr.html

[E01] 拼接字符串
来源：http://dali.9152youxi.cn/Article/details/gtphbuwlcg.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zycfv.cn/Article/details/gthdtbpqyt.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmrddxkcp.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nanxuanxn.top/Article/details/gtfglsjwtb.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinqigufen.top/Article/details/gtpefayjxq.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hysaishi.cn/Article/details/gtylcxsdrg.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.0kj1m.cn/Article/details/gtlavqzpgh.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.daxiang520.top/Article/details/gtuxtnhiis.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gthtbinjhs.html

[E02] 重复字符串
来源：http://dali.dashuyun.cn/Article/details/gtquwachpv.html

Py:   "ab" * 3
来源：http://dali.birdmap.top/Article/details/gtiiugbvso.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yj20258888.top/Article/details/gtykjxswwh.html

JS:   "ab".repeat(3)
来源：http://dali.jqgufenzy.top/Article/details/gtgbvnmdqg.html

TS:   "ab".repeat(3)
来源：http://dali.yanxiufei.cn/Article/details/gtmtgvcewz.html

Java: "ab".repeat(3)
来源：http://dali.svipenyu.cn/Article/details/gtilmbwekt.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.9152youxi.cn/Article/details/gtzeyvbgrm.html

Ruby: "ab" * 3
来源：http://dali.yueranfly.top/Article/details/gtiroaqtmj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.tanke756.top/Article/details/gtnkmtiozy.html

[E03] 截取子串
来源：http://dali.ybcxt.top/Article/details/gtxrfozxan.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.sysykeji.top/Article/details/gthyiqrlkq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cashguo.top/Article/details/gtumoudqkw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.daria6918.cn/Article/details/gtmqgidssq.html

TS:   s.slice(1, 4)
来源：http://dali.yj20258888.top/Article/details/gtmorbblzc.html

Java: s.substring(1, 4)
来源：http://dali.hywenlv.cn/Article/details/gtnibovepc.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jqgfzy.top/Article/details/gthheaclcz.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xinyue.icu/Article/details/gtvlviydcr.html

C#:   s.Substring(1, 3)
来源：http://dali.xinyue.icu/Article/details/gtiwqcqefn.html

[E04] 查找子串位置
来源：http://dali.feifeiyinyue.top/Article/details/gtemkmlcid.html

Py:   s.find("x");  s.index("x")
来源：http://dali.shzxlz.cn/Article/details/gtpebkjwno.html

PHP:  strpos($s, "x");
来源：http://dali.cheryme.top/Article/details/gtyqtlsxzd.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yuanzhike.top/Article/details/gtoxbefoiu.html

TS:   s.indexOf("x")
来源：http://dali.ppjwa.cn/Article/details/gtdaotjssn.html

Java: s.indexOf("x")
来源：http://dali.zhongyouzk.top/Article/details/gtngpzqclm.html


<!-- 参考信息 -->