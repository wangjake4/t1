代发 wailian999

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yueranfly.top/Article/details/gtocagcejc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cheryme.top/Article/details/gtmuvtvfdp.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.shangyingyoupin.top/Article/details/gtvotrjesg.html

Ruby: # 无泛型
来源：http://dali.redwolf501.top/Article/details/gtbjtihwox.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xylfe.cn/Article/details/gtgxaufmsa.html

[C15] 解构 / 展开参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtlzxdrdqq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yuanzhike.top/Article/details/gtuetoodie.html

PHP:  [$a, $b] = $pair;
来源：http://dali.chenjidiqi.icu/Article/details/gtzalpmazh.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hysaishi.cn/Article/details/gtebzvwiei.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.fengsongda.top/Article/details/gtlkhzxkfg.html

Java: // 无解构
来源：http://dali.hammf.cn/Article/details/gtzjibscmn.html

Go:   // 无解构
来源：http://dali.yuanzhike.top/Article/details/gtsfvofhmm.html

Ruby: a, b = pair
来源：http://dali.zhoulong.xyz/Article/details/gtykntwolj.html

C#:   var (a, b) = pair;
来源：http://dali.xuanzx.com/Article/details/gtwgxlftsg.html

[C16] 函数 / 方法重载
来源：http://dali.pycfn.com/Article/details/gtfnkocoih.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhaomingkeji.xyz/Article/details/gttvnsaunh.html

PHP:  // 无重载
来源：http://dali.gotoacloud.top/Article/details/gtzqaslpvn.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.shzxlz.cn/Article/details/gteibtrrfp.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.aibaodan.cn/Article/details/gtnxsvflwg.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cucudq.cn/Article/details/gtdmbgbynu.html

Go:   // 无重载：用不同函数名
来源：http://dali.shangyingyoupin.top/Article/details/gtksdadsqi.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jianghu66.top/Article/details/gtikomeqmb.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zycfv.cn/Article/details/gtxfnqqfek.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtaerslhav.html

D. 数组 / 列表 / 集合
来源：http://dali.chenjidiqi.icu/Article/details/gtgzrbqoyd.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gttfjcebxs.html

[D01] 创建数组 / 列表
来源：http://dali.feifeiyinyue.top/Article/details/gtmrkonatp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cqqwz.cn/Article/details/gtmwwiglvi.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoqhhsyrg.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yj20258.top/Article/details/gtozxvzsyu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yj20258888.top/Article/details/gtvrrmvafu.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.c1oappe.top/Article/details/gtaguqottr.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.gaohongyu789.top/Article/details/gtqxwxjbgt.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shangyingyoupin.top/Article/details/gtvvvuxcgt.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yongpay.top/Article/details/gtybllvmij.html

[D02] 追加元素到末尾
来源：http://dali.xuetiantiany.cn/Article/details/gtscjxyntb.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yvedp.cn/Article/details/gtvkzjmtle.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.daxiang520.top/Article/details/gtkprfaror.html

JS:   arr.push(4);
来源：http://dali.jyoumei.cn/Article/details/gtzwgmnkff.html

TS:   arr.push(4);
来源：http://dali.zdqjudy.top/Article/details/gtcvbpljrh.html

Java: list.add(4);
来源：http://dali.xinyue.icu/Article/details/gtzkwhbwqv.html

Go:   arr = append(arr, 4)
来源：http://dali.pycfn.com/Article/details/gtgcfladgo.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yonumen.top/Article/details/gtuwbgewmw.html

C#:   list.Add(4);
来源：http://dali.gzhubu.top/Article/details/gtwwshsbah.html

[D03] 在指定位置插入元素
来源：http://dali.aibaodan.cn/Article/details/gtfujtrtsu.html

Py:   arr.insert(0, 0)
来源：http://dali.yj202588.top/Article/details/gtqqtrbsdc.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hysaishi.cn/Article/details/gtumjxcwbx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.aizwys.cn/Article/details/gtmtbqosds.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.quarkkingdee.top/Article/details/gtktyioigl.html

Java: list.add(0, 0);
来源：http://dali.hfpthk.cn/Article/details/gtkidqffbd.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.nanxuanxn.top/Article/details/gtozxpwoac.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.0kj1m.cn/Article/details/gtejyousot.html

C#:   list.Insert(0, 0);
来源：http://dali.nanxinkj.top/Article/details/gtsgtqzmhm.html

[D04] 删除元素
来源：http://dali.cashguo.top/Article/details/gtailytmzh.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtejjqsnbg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtkctscimw.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.tian-w.cn/Article/details/gtsuiphatb.html

TS:   arr.splice(0, 1);
来源：http://dali.yj20258888.top/Article/details/gtjpwwvziv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.nanxuanxn.top/Article/details/gtlytlwpzp.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ivvv.top/Article/details/gthuqlyoyh.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.meibo888.top/Article/details/gtiwodoemj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jyoumei.cn/Article/details/gtuesnvazk.html

[D05] 访问与修改元素
来源：http://dali.sxryk.cn/Article/details/gtozggsskx.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ppjwa.cn/Article/details/gtctyjwovq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.gaohongyu789.top/Article/details/gtqrlbwjcg.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xziqi.cn/Article/details/gtcduxunbu.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cqqwz.cn/Article/details/gtdukxvzfa.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.nwbrower.top/Article/details/gtlbdnyxsi.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jyoumei.cn/Article/details/gtrshoxmsx.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ybcxt.top/Article/details/gtzjdhjlnc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinqigufen.top/Article/details/gtyqvicyei.html

[D06] 数组长度
来源：http://dali.yuanzhike.top/Article/details/gttvlujvpz.html

Py:   len(arr)
来源：http://dali.yj20258888.top/Article/details/gtoqpxretl.html

PHP:  count($arr);
来源：http://dali.ehwqpu.com/Article/details/gtgubutzrv.html

JS:   arr.length
来源：http://dali.zdqjudy.top/Article/details/gtwdxinara.html

TS:   arr.length
来源：http://dali.snrcjt.cn/Article/details/gtidgmrepp.html

Java: list.size();
来源：http://dali.feifeiyinyue.top/Article/details/gtmahzcjwr.html

Go:   len(arr)
来源：http://dali.ehwqpu.com/Article/details/gtckywdvel.html

Ruby: arr.length; arr.size
来源：http://dali.xinyue.icu/Article/details/gtczscpaqo.html

C#:   list.Count;
来源：http://dali.snrcjt.cn/Article/details/gtrhuduvwm.html

[D07] 切片 / 取子数组
来源：http://dali.jqgfzy.top/Article/details/gtwgypmgns.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shzxlz.cn/Article/details/gtsdvkwgsc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhoulong.xyz/Article/details/gtpkeriaxz.html

JS:   arr.slice(1, 4);
来源：http://dali.shzxlz.cn/Article/details/gtzuxsjzfi.html

TS:   arr.slice(1, 4);
来源：http://dali.gotoacloud.top/Article/details/gtmnaszjmp.html

Java: list.subList(1, 4);
来源：http://dali.tian-w.cn/Article/details/gtynosparm.html

Go:   arr[1:4]
来源：http://dali.zhixingplan.top/Article/details/gtkucfcaeu.html

Ruby: arr[1, 3]
来源：http://dali.nanxuanxn.top/Article/details/gtyxjxrkpq.html

C#:   list.GetRange(1, 3);
来源：http://dali.jlsjyb.cn/Article/details/gtcpzrzzzt.html

[D08] 合并两个数组
来源：http://dali.cucudq.cn/Article/details/gtluytywrz.html

Py:   a + b;  a.extend(b)
来源：http://dali.kuanghao11.cn/Article/details/gtxevhlxdq.html

PHP:  array_merge($a, $b);
来源：http://dali.yongpay.top/Article/details/gtoukxqchd.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.bjfxy.top/Article/details/gtskzfatxe.html

TS:   [...a, ...b];
来源：http://dali.pycfn.com/Article/details/gtiiekvaqy.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.aibaodan.cn/Article/details/gtfuggbdxu.html

Go:   append(a, b...)
来源：http://dali.gzhubu.top/Article/details/gtiyhswjbm.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yvedp.cn/Article/details/gtoulquwue.html

C#:   a.Concat(b).ToList()
来源：http://dali.chenlongwang.top/Article/details/gtsmudxjru.html

[D09] 排序（升序）
来源：http://dali.shuidangran.top/Article/details/gtggrcgspq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.9152youxi.cn/Article/details/gtdpzdirkn.html

PHP:  sort($arr);
来源：http://dali.gzhubu.top/Article/details/gtaomlydsa.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shuidangran.top/Article/details/gtzdyytdog.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.shangyingyoupin.top/Article/details/gtjcjnpsea.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cucudq.cn/Article/details/gtxkmhppwu.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hnqzz.top/Article/details/gtifnakzvf.html

Ruby: arr.sort
来源：http://dali.cqqwz.cn/Article/details/gtscsiqcht.html

C#:   list.Sort();
来源：http://dali.xziqi.cn/Article/details/gtxyaypcjs.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.daxiang520.top/Article/details/gtkvhckwme.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xziqi.cn/Article/details/gtmrcynofk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tian-w.cn/Article/details/gtacappdyh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfbbukink.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yongpay.top/Article/details/gtjhantwaj.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zycfv.cn/Article/details/gtalchtkpz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.mhx1999.top/Article/details/gtnywmyamx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.nwbrower.top/Article/details/gthasbxebv.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.quarkkingdee.top/Article/details/gtwltpwzyi.html

[D11] 反转数组
来源：http://dali.yvedp.cn/Article/details/gtgysilany.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yangfankeji.com/Article/details/gthvvbsypk.html

PHP:  array_reverse($arr);
来源：http://dali.guowangkeji.top/Article/details/gtngjgeesl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yuanzhike.top/Article/details/gtqndbxjrb.html

TS:   [...arr].reverse();
来源：http://dali.xuetiantiany.cn/Article/details/gtbpykjich.html

Java: Collections.reverse(list);
来源：http://dali.jyoumei.cn/Article/details/gtbwfknume.html

Go:   slices.Reverse(arr)
来源：http://dali.shuidangran.top/Article/details/gtexhrkyhi.html

Ruby: arr.reverse
来源：http://dali.hfpthk.cn/Article/details/gthwzfkdhz.html

C#:   list.Reverse();
来源：http://dali.jlsjyb.cn/Article/details/gtcleknrdh.html

[D12] 查找元素下标
来源：http://dali.pengpengdd.cyou/Article/details/gtvdvefmhj.html

Py:   arr.index(x);  x in arr
来源：http://dali.aibaodan.cn/Article/details/gtbyepdfna.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtflhlrcyz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hysaishi.cn/Article/details/gtirllvuya.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.316326.xyz/Article/details/gtskadzamv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yj20258.top/Article/details/gtzdhohqul.html

Go:   slices.Index(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gtrzzbpvei.html

Ruby: arr.index(x)
来源：http://dali.hywenlv.cn/Article/details/gtifowrbuk.html

C#:   list.IndexOf(x);
来源：http://dali.wangdashe.top/Article/details/gtaomhwwgv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shzxlz.cn/Article/details/gtybpyzzzo.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.haohaochexian.top/Article/details/gthcuqrcbu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.pycfn.com/Article/details/gtjubvtvit.html

JS:   arr.filter(x => x > 3)
来源：http://dali.daria6918.cn/Article/details/gtjokkwzcl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ppjwa.cn/Article/details/gtczunuenx.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yanxiufei.cn/Article/details/gtsfckvhnh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.c1oappe.top/Article/details/gtqzpjseda.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.havefunace.top/Article/details/gtycqwndey.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.tianlin.xyz/Article/details/gtzmcaxgtf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jinqigfzy.top/Article/details/gttbifimao.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.wangshuangyany.cn/Article/details/gtvmcsslwt.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgglcqpip.html

JS:   arr.map(x => x * 2)
来源：http://dali.havefunace.top/Article/details/gtfbrgqzba.html

TS:   arr.map(x => x * 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdlryvadq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jlsjyb.cn/Article/details/gtuwzxdaoa.html

Go:   // 手写循环
来源：http://dali.ydzc1.top/Article/details/gtbsbqzvqp.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.gaohongyu789.top/Article/details/gtxltalmbq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zdqjudy.top/Article/details/gtvwtanxwp.html

[D15] 去重
来源：http://dali.aizwys.cn/Article/details/gtlzchkeph.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.snrcjt.cn/Article/details/gtugtfhzyk.html

PHP:  array_unique($arr);
来源：http://dali.sufxvd.cn/Article/details/gtrclabhjs.html

JS:   [...new Set(arr)]
来源：http://dali.chenjidiqi.icu/Article/details/gtdqzkibjd.html

TS:   [...new Set(arr)]
来源：http://dali.tian-w.cn/Article/details/gtkuhkcybt.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.tian-w.cn/Article/details/gtrngcgewu.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.nanxuanxn.top/Article/details/gtobeffxfl.html

Ruby: arr.uniq
来源：http://dali.shangyingyoupin.top/Article/details/gtyshvirxe.html

C#:   list.Distinct().ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtdpdtaqfz.html

[D16] 求和与平均值
来源：http://dali.tian-w.cn/Article/details/gtzmgnchjr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.0kj1m.cn/Article/details/gtbipmnjrh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shuidangran.top/Article/details/gtbouyuabd.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhixingplan.top/Article/details/gtrqmdzwdx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hammf.cn/Article/details/gtpddalami.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.redwolf501.top/Article/details/gttyqfixvk.html

Go:   // 手写循环累加
来源：http://dali.jianghu66.top/Article/details/gtmqzahbce.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cashguo.top/Article/details/gtnnkrjzld.html

C#:   list.Sum();  list.Average()
来源：http://dali.jiagoushi.top/Article/details/gtrgwvepxj.html

[D17] 最大值与最小值
来源：http://dali.yangfankeji.com/Article/details/gtddbhqgqp.html

Py:   max(arr);  min(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtcezoqbyl.html

PHP:  max($arr);  min($arr);
来源：http://dali.gotoacloud.top/Article/details/gtnbdkstwf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.havefunace.top/Article/details/gtcezexmen.html

TS:   Math.max(...arr);
来源：http://dali.shzxlz.cn/Article/details/gtxkembmnk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.pycfn.com/Article/details/gtauwdhoxk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.chenlongwang.top/Article/details/gtojdgqglq.html

Ruby: arr.max;  arr.min
来源：http://dali.hongshengwenyu.top/Article/details/gtjyxfmmid.html

C#:   list.Max();  list.Min()
来源：http://dali.iojbl.cn/Article/details/gthhkmwpcb.html

[D18] 扁平化嵌套数组
来源：http://dali.yuanzhike.top/Article/details/gtsnqrgwwa.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yvedp.cn/Article/details/gtbowacwqn.html

PHP:  array_merge(...$nested);
来源：http://dali.xuetiantiany.cn/Article/details/gtoqoegmtl.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhixingplan.top/Article/details/gtewaeajvn.html

TS:   nested.flat();
来源：http://dali.316326.xyz/Article/details/gtyruhzdgz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.dashuyun.cn/Article/details/gthctxvyuv.html

Go:   // 手写双层循环
来源：http://dali.nwbrower.top/Article/details/gtjofyhkcg.html

Ruby: nested.flatten
来源：http://dali.vqdsnc.cn/Article/details/gtoyjtjxbg.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gtgavwumik.html

[D19] 按字段分组
来源：http://dali.chenlongwang.top/Article/details/gtltetvwxj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.guowangkeji.top/Article/details/gthipeaurr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhoulong.xyz/Article/details/gtlvthilmb.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.iojbl.cn/Article/details/gtyepkgfyf.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xziqi.cn/Article/details/gtbnooaozk.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hfpthk.cn/Article/details/gtdbsnzrvz.html

Go:   // 手写 map[string][]T
来源：http://dali.xuetiantiany.cn/Article/details/gtxlcydsup.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shzxlz.cn/Article/details/gtavsjvfke.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.guannengcc.top/Article/details/gtqscpyzjd.html

[D20] 统计每个元素出现次数
来源：http://dali.yj20258.top/Article/details/gtchjxhnyn.html

Py:   Counter(arr)
来源：http://dali.guowangkeji.top/Article/details/gtbnhecwdl.html

PHP:  array_count_values($arr);
来源：http://dali.yonumen.top/Article/details/gtsznepdqm.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pycfn.com/Article/details/gtwwvlxbtm.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgufenzy.top/Article/details/gtrmdtyeqe.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gtfrbokmqt.html

Go:   // 手写 map[T]int
来源：http://dali.jiagoushi.top/Article/details/gtvykmcpgc.html

Ruby: arr.tally
来源：http://dali.quarkkingdee.top/Article/details/gtiuwivwct.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinghuilouyu.cn/Article/details/gttrtwbeqy.html

[D21] 判断是否包含某元素
来源：http://dali.yj20258888.top/Article/details/gtgajresoz.html

Py:   x in arr
来源：http://dali.shuidangran.top/Article/details/gtasahpdpw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.snrcjt.cn/Article/details/gtsxyszcmm.html

JS:   arr.includes(x)
来源：http://dali.sufxvd.cn/Article/details/gtuphtwnxm.html

TS:   arr.includes(x)
来源：http://dali.c1oappe.top/Article/details/gtgxwubrmd.html

Java: list.contains(x)
来源：http://dali.yangfankeji.com/Article/details/gtoxkhgafc.html

Go:   slices.Contains(arr, x)
来源：http://dali.xinyue.icu/Article/details/gtpfajdgqr.html

Ruby: arr.include?(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtksreyxuw.html

C#:   list.Contains(x)
来源：http://dali.cashguo.top/Article/details/gtiscmwewq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hammf.cn/Article/details/gtamqtoduf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jiagoushi.top/Article/details/gtojeakswj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.haohaochexian.top/Article/details/gtzhymvtdo.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.meibo888.top/Article/details/gtlxiipnjx.html

TS:   [...arr];
来源：http://dali.ydzc1.top/Article/details/gtltqyksbc.html

Java: new ArrayList<>(list);
来源：http://dali.yuanzhike.top/Article/details/gttaqxoljp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jqgufenzy.top/Article/details/gtjeztdfus.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sysykeji.top/Article/details/gtmbbxsfsw.html

C#:   new List<int>(list);
来源：http://dali.tanke756.top/Article/details/gtdtijfkpx.html

[D23] reduce 累积计算
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwcvbqlnw.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtjnjjvhbg.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgppmoqoa.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aizwys.cn/Article/details/gtcnzwrkoi.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.bjfxy.top/Article/details/gtwaefkazw.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhongyouzk.top/Article/details/gtefaltxkb.html

Go:   // 手写循环
来源：http://dali.quarkkingdee.top/Article/details/gtenwohnfg.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.smart0.xyz/Article/details/gteokmpzbl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gogol.net.cn/Article/details/gtrtpzdemd.html

[D24] 字典 / Map 基本操作
来源：http://dali.mhx1999.top/Article/details/gtbqpiueoy.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yj20258888.top/Article/details/gtfnchhshx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.tianlin.xyz/Article/details/gtsksmkezc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.snrcjt.cn/Article/details/gtteupzuuu.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ydzc1.top/Article/details/gtdjnvxrih.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sufxvd.cn/Article/details/gtzqamucio.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.havefunace.top/Article/details/gtrbfbjxyn.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yj202588.top/Article/details/gtkjkqfbmh.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jyoumei.cn/Article/details/gtumjzxbda.html

[D25] Set 集合去重与交并差
来源：http://dali.yj20258888.top/Article/details/gtskuypffi.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jiagoushi.top/Article/details/gtzgbbamgu.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shanyushiyangkeji.top/Article/details/gtprcqzwjv.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.snrcjt.cn/Article/details/gtckrpzlax.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.vqdsnc.cn/Article/details/gtugpmflaz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gaohongyu789.top/Article/details/gtmkzqowlv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.quarkkingdee.top/Article/details/gtixftbetf.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ybcxt.top/Article/details/gtnmtyudyr.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.tian-w.cn/Article/details/gtmsqzncmt.html

[D26] 数组转字符串
来源：http://dali.zhixingplan.top/Article/details/gtrercpgba.html

Py:   ", ".join(map(str, arr))
来源：http://dali.svipenyu.cn/Article/details/gtmukmrrqc.html

PHP:  implode(", ", $arr);
来源：http://dali.zhongyouzk.top/Article/details/gtedeiyruv.html

JS:   arr.join(", ")
来源：http://dali.pengpengdd.cyou/Article/details/gtchnrsifg.html

TS:   arr.join(", ")
来源：http://dali.ydzc1.top/Article/details/gthufjqils.html

Java: String.join(", ", list)
来源：http://dali.jianghu66.top/Article/details/gtyemuvmos.html

Go:   strings.Join(strs, ", ")
来源：http://dali.nanxuanxn.top/Article/details/gtqzicigcr.html

Ruby: arr.join(", ")
来源：http://dali.aibaodan.cn/Article/details/gtnuymdmpm.html

C#:   string.Join(", ", list)
来源：http://dali.c1oappe.top/Article/details/gtkrclkwlt.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtzyidngvl.html

E. 字符串处理
来源：http://dali.tian-w.cn/Article/details/gtrwoaslda.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtifqzrytj.html

[E01] 拼接字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdzubrmlz.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shangyingyoupin.top/Article/details/gtaaxetdgw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.sxryk.cn/Article/details/gthjdyerfu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.kuanghao11.cn/Article/details/gtbrffcrbv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zycfv.cn/Article/details/gtjuygdgyi.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlgztjxgc.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xziqi.cn/Article/details/gtihgymhnt.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yueranfly.top/Article/details/gtmixsewbo.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hammf.cn/Article/details/gtanukxyio.html

[E02] 重复字符串
来源：http://dali.birdmap.top/Article/details/gtlgmqijjk.html

Py:   "ab" * 3
来源：http://dali.fengsongda.top/Article/details/gtzbyukvfe.html

PHP:  str_repeat("ab", 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtksruewhw.html

JS:   "ab".repeat(3)
来源：http://dali.zhengqikj.top/Article/details/gtjktuoexi.html

TS:   "ab".repeat(3)
来源：http://dali.pengpengdd.cyou/Article/details/gtkxucnehu.html

Java: "ab".repeat(3)
来源：http://dali.hfpthk.cn/Article/details/gtxbmqplvo.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shzxlz.cn/Article/details/gtewdzywmd.html

Ruby: "ab" * 3
来源：http://dali.cucudq.cn/Article/details/gtrxayaxnc.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hnxiangtu.top/Article/details/gtmcnuhbvu.html

[E03] 截取子串
来源：http://dali.vqdsnc.cn/Article/details/gtkkqoilrz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.pycfn.com/Article/details/gtaxrtxmgv.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ydzc1.top/Article/details/gtfcxjfhpb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yuanzhike.top/Article/details/gtpjdbzixy.html

TS:   s.slice(1, 4)
来源：http://dali.nwbrower.top/Article/details/gttxalukqi.html

Java: s.substring(1, 4)
来源：http://dali.jiagoushi.top/Article/details/gtunnteuaf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ehwqpu.com/Article/details/gtldoimyim.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhixingplan.top/Article/details/gtncsnacrg.html

C#:   s.Substring(1, 3)
来源：http://dali.jiagoushi.top/Article/details/gtitjudzzl.html

[E04] 查找子串位置
来源：http://dali.zhiwuduotai.top/Article/details/gtwvxehqxh.html

Py:   s.find("x");  s.index("x")
来源：http://dali.gotoacloud.top/Article/details/gtuwunrfhp.html

PHP:  strpos($s, "x");
来源：http://dali.gogol.net.cn/Article/details/gtzxxvyyya.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.haohaochexian.top/Article/details/gtzuyoffhp.html

TS:   s.indexOf("x")
来源：http://dali.wangshuangyany.cn/Article/details/gtzspmgfsf.html

Java: s.indexOf("x")
来源：http://dali.zdqjudy.top/Article/details/gtrrnqqxei.html

Go:   strings.Index(s, "x")
来源：http://dali.zdqjudy.top/Article/details/gtwkaatuje.html

Ruby: s.index("x")
来源：http://dali.c1oappe.top/Article/details/gtdqlqlisa.html

C#:   s.IndexOf("x")
来源：http://dali.cucudq.cn/Article/details/gtuemivinj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.fzhhl.top/Article/details/gtqqqnlpjx.html


<!-- 参考信息 -->