代发 wailian999

[C14] 泛型函数
来源：http://dali.xinyue.icu/Article/details/gtwhwopubf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.vqdsnc.cn/Article/details/gtuibsvifj.html

PHP:  // 无泛型
来源：http://dali.vqdsnc.cn/Article/details/gtkjqqfbvv.html

JS:   // 无泛型
来源：http://dali.yangfankeji.com/Article/details/gtyaauupic.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ydzc1.top/Article/details/gtrsuxacgk.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmvltddcf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.meibo888.top/Article/details/gtacspipks.html

Ruby: # 无泛型
来源：http://dali.dianchejie.cn/Article/details/gtgahjznjn.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cucudq.cn/Article/details/gtcgkdypxh.html

[C15] 解构 / 展开参数
来源：http://dali.hysaishi.cn/Article/details/gtnexyobbz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.gaohongyu789.top/Article/details/gtslpfdqpl.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cucudq.cn/Article/details/gthacgiemf.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shzxlz.cn/Article/details/gtmttdmlgt.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cqqwz.cn/Article/details/gthcbsjquh.html

Java: // 无解构
来源：http://dali.cashguo.top/Article/details/gtvrzorwef.html

Go:   // 无解构
来源：http://dali.ybcxt.top/Article/details/gtlubhdmyl.html

Ruby: a, b = pair
来源：http://dali.zhoulong.xyz/Article/details/gtruexwcnh.html

C#:   var (a, b) = pair;
来源：http://dali.daria6918.cn/Article/details/gtfwwrltsv.html

[C16] 函数 / 方法重载
来源：http://dali.hywenlv.cn/Article/details/gtcuuavcow.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.tian-w.cn/Article/details/gtxhufdoep.html

PHP:  // 无重载
来源：http://dali.yuanzhike.top/Article/details/gtyrjgafxr.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yuanzhike.top/Article/details/gtqsddznbg.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yj202588.top/Article/details/gtaegntevp.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yuanzhike.top/Article/details/gtplyicfce.html

Go:   // 无重载：用不同函数名
来源：http://dali.meibo888.top/Article/details/gttyhfgbpl.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtagcbeuov.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hysaishi.cn/Article/details/gtcfvethei.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtuspfuuen.html

D. 数组 / 列表 / 集合
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwcrbeqyw.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtafhswswx.html

[D01] 创建数组 / 列表
来源：http://dali.ppjwa.cn/Article/details/gtdsqmyyzk.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cheryme.top/Article/details/gttebbyntx.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zycfv.cn/Article/details/gtnnkmfpyu.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkwarufbg.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.mhx1999.top/Article/details/gtwmyhxmln.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jianghu66.top/Article/details/gttbeaskkt.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yanxiufei.cn/Article/details/gtcvldzvwo.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xinyue.icu/Article/details/gtwfyyyiog.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.birdmap.top/Article/details/gtqeacabgo.html

[D02] 追加元素到末尾
来源：http://dali.gotoacloud.top/Article/details/gtbziyfsmp.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cucudq.cn/Article/details/gtcbsoluth.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.316326.xyz/Article/details/gtkzxmanfh.html

JS:   arr.push(4);
来源：http://dali.svipenyu.cn/Article/details/gtnewmnzvd.html

TS:   arr.push(4);
来源：http://dali.birdmap.top/Article/details/gtlrohmiop.html

Java: list.add(4);
来源：http://dali.jqgfzy.top/Article/details/gtnbdoaqay.html

Go:   arr = append(arr, 4)
来源：http://dali.zhixingplan.top/Article/details/gtsmuzgutv.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cdnleiting.top/Article/details/gttzbnpcgc.html

C#:   list.Add(4);
来源：http://dali.hnxiangtu.top/Article/details/gtpvaiipbw.html

[D03] 在指定位置插入元素
来源：http://dali.hnxiangtu.top/Article/details/gtgxtbgfmb.html

Py:   arr.insert(0, 0)
来源：http://dali.ppjwa.cn/Article/details/gtrwmkidzx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hammf.cn/Article/details/gtzlhllnuk.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jlsjyb.cn/Article/details/gtzcdegwmd.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.c1oappe.top/Article/details/gtygxconer.html

Java: list.add(0, 0);
来源：http://dali.ppjwa.cn/Article/details/gtqbpjcyqf.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.guannengcc.top/Article/details/gtuzsmtell.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cqqwz.cn/Article/details/gtzyzqlqpn.html

C#:   list.Insert(0, 0);
来源：http://dali.gotoacloud.top/Article/details/gttebuwlml.html

[D04] 删除元素
来源：http://dali.yangfankeji.com/Article/details/gtqjjasfrf.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hfpthk.cn/Article/details/gtjjmnmfqi.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtcujuhhww.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.9152youxi.cn/Article/details/gtgnsrkyby.html

TS:   arr.splice(0, 1);
来源：http://dali.smart0.xyz/Article/details/gtgqirlxxc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.pengpengdd.cyou/Article/details/gtegqbtvfe.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.quarkkingdee.top/Article/details/gtfkotckvl.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzwdrtnga.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.vqdsnc.cn/Article/details/gtlqivnhxw.html

[D05] 访问与修改元素
来源：http://dali.jyoumei.cn/Article/details/gtddhmzeci.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yanxiufei.cn/Article/details/gtugxeuvnj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jqgufenzy.top/Article/details/gtfngxxmog.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.sweek.top/Article/details/gthfbmwceq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yj20258.top/Article/details/gtdyahykqt.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hammf.cn/Article/details/gtkrekxqyg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sufxvd.cn/Article/details/gtrsmecpjj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.dashuyun.cn/Article/details/gtdnfiutzq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xuetiantiany.cn/Article/details/gtadphbjef.html

[D06] 数组长度
来源：http://dali.jinqigfzy.top/Article/details/gtoexgfjif.html

Py:   len(arr)
来源：http://dali.chenlongwang.top/Article/details/gtrcuiastw.html

PHP:  count($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtzbunrqzg.html

JS:   arr.length
来源：http://dali.cucudq.cn/Article/details/gtjnoollom.html

TS:   arr.length
来源：http://dali.c1oappe.top/Article/details/gtxvyposje.html

Java: list.size();
来源：http://dali.bjfxy.top/Article/details/gtmnytilzv.html

Go:   len(arr)
来源：http://dali.hysaishi.cn/Article/details/gtxxtgwjmu.html

Ruby: arr.length; arr.size
来源：http://dali.ppjwa.cn/Article/details/gtfqlowzbf.html

C#:   list.Count;
来源：http://dali.redwolf501.top/Article/details/gtmnsnqhwz.html

[D07] 切片 / 取子数组
来源：http://dali.yvedp.cn/Article/details/gtgsotmxqq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jinghuilouyu.cn/Article/details/gtayplpdgp.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cdnleiting.top/Article/details/gtxznbqztf.html

JS:   arr.slice(1, 4);
来源：http://dali.yj202588.top/Article/details/gthjqeofzq.html

TS:   arr.slice(1, 4);
来源：http://dali.xziqi.cn/Article/details/gthdheuppm.html

Java: list.subList(1, 4);
来源：http://dali.sxryk.cn/Article/details/gtaptgcxep.html

Go:   arr[1:4]
来源：http://dali.hywenlv.cn/Article/details/gtrtjhutmt.html

Ruby: arr[1, 3]
来源：http://dali.9152youxi.cn/Article/details/gtxtdyecwi.html

C#:   list.GetRange(1, 3);
来源：http://dali.cqqwz.cn/Article/details/gtenigyozq.html

[D08] 合并两个数组
来源：http://dali.yonumen.top/Article/details/gtbamevktz.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhoulong.xyz/Article/details/gtwgfwpfae.html

PHP:  array_merge($a, $b);
来源：http://dali.gzhubu.top/Article/details/gtiiecvgxg.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.wangdashe.top/Article/details/gtarleyrks.html

TS:   [...a, ...b];
来源：http://dali.birdmap.top/Article/details/gtxoajjoqu.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ydzc1.top/Article/details/gtsycxnghx.html

Go:   append(a, b...)
来源：http://dali.ehwqpu.com/Article/details/gthvqyzify.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yj202588.top/Article/details/gtqyawvstw.html

C#:   a.Concat(b).ToList()
来源：http://dali.shzxlz.cn/Article/details/gtcpgqkfmq.html

[D09] 排序（升序）
来源：http://dali.yuanzhike.top/Article/details/gttbmyojpx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhongyouzk.top/Article/details/gthjzyyaco.html

PHP:  sort($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtexozzlbl.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.tian-w.cn/Article/details/gtrywckljn.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.sufxvd.cn/Article/details/gtjeaznadz.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xylfe.cn/Article/details/gtqwgboqml.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.tanke756.top/Article/details/gturqkyeli.html

Ruby: arr.sort
来源：http://dali.pycfn.com/Article/details/gtridwilju.html

C#:   list.Sort();
来源：http://dali.nanxinkj.top/Article/details/gtxelwdnfw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.nanxinkj.top/Article/details/gtlamakoeq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yonumen.top/Article/details/gtafkmvala.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhongyouzk.top/Article/details/gterebapfy.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cheryme.top/Article/details/gtqhlmxcoo.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.vqdsnc.cn/Article/details/gtoglmhuyo.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.gogol.net.cn/Article/details/gtipiklyoz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.sxryk.cn/Article/details/gtoraztdnp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.nanxuanxn.top/Article/details/gtjqmyocpt.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shanyushiyangtech.top/Article/details/gtnzhqshgf.html

[D11] 反转数组
来源：http://dali.hysaishi.cn/Article/details/gtsyefwwqi.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.pycfn.com/Article/details/gtbyrsckyt.html

PHP:  array_reverse($arr);
来源：http://dali.iojbl.cn/Article/details/gtmzprddqm.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.gaohongyu789.top/Article/details/gtdqjxjffh.html

TS:   [...arr].reverse();
来源：http://dali.shanyushiyangtech.top/Article/details/gtrlqkebum.html

Java: Collections.reverse(list);
来源：http://dali.nanxuanxn.top/Article/details/gtbufyzcuj.html

Go:   slices.Reverse(arr)
来源：http://dali.yj20258888.top/Article/details/gthhqoaimc.html

Ruby: arr.reverse
来源：http://dali.sweek.top/Article/details/gtxldpxncj.html

C#:   list.Reverse();
来源：http://dali.cheryme.top/Article/details/gttneuxnfg.html

[D12] 查找元素下标
来源：http://dali.cucudq.cn/Article/details/gtbjzyprhs.html

Py:   arr.index(x);  x in arr
来源：http://dali.yuxming.cn/Article/details/gtyljuucvx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jinqigfzy.top/Article/details/gtineuhagq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.redwolf501.top/Article/details/gtnuhxxabz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.vqdsnc.cn/Article/details/gtvgegfrbg.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.chenzaomai.com/Article/details/gtlmruumwk.html

Go:   slices.Index(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtuodewels.html

Ruby: arr.index(x)
来源：http://dali.jinqigfzy.top/Article/details/gtqzrgnbim.html

C#:   list.IndexOf(x);
来源：http://dali.svipenyu.cn/Article/details/gtnvbdtfup.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cashguo.top/Article/details/gtlqmgoowc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xziqi.cn/Article/details/gtpruftqef.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.pengpengdd.cyou/Article/details/gtxedopggx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtekcfdqgd.html

TS:   arr.filter(x => x > 3)
来源：http://dali.birdmap.top/Article/details/gtifwnzeya.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hnqzz.top/Article/details/gtlxylpdqc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.meibo888.top/Article/details/gtbrrbcaqt.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.quarkkingdee.top/Article/details/gtwtrhcwcp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtwnqcvtpb.html

[D14] 映射转换（每个元素变形）
来源：http://dali.sxryk.cn/Article/details/gtedpkgknz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yvedp.cn/Article/details/gtggmdtliy.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.daria6918.cn/Article/details/gtsmwcbioo.html

JS:   arr.map(x => x * 2)
来源：http://dali.yongpay.top/Article/details/gtotiumthb.html

TS:   arr.map(x => x * 2)
来源：http://dali.316326.xyz/Article/details/gtqnbnkysw.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hammf.cn/Article/details/gtxhagknad.html

Go:   // 手写循环
来源：http://dali.andypj.xyz/Article/details/gtfdrgauxw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.gogol.net.cn/Article/details/gtraixyhbn.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sxryk.cn/Article/details/gtpjlxoonf.html

[D15] 去重
来源：http://dali.iojbl.cn/Article/details/gtpeawgtka.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shuidangran.top/Article/details/gtxurgzyef.html

PHP:  array_unique($arr);
来源：http://dali.yueranfly.top/Article/details/gtsnamyvhv.html

JS:   [...new Set(arr)]
来源：http://dali.fzhhl.top/Article/details/gtkftmncxw.html

TS:   [...new Set(arr)]
来源：http://dali.ehwqpu.com/Article/details/gtvahvlzsz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yvedp.cn/Article/details/gtuvjizpvq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hfpthk.cn/Article/details/gtzjtiqmhh.html

Ruby: arr.uniq
来源：http://dali.cucudq.cn/Article/details/gtjwsgdlsk.html

C#:   list.Distinct().ToList()
来源：http://dali.xuanzx.com/Article/details/gtkayigyoj.html

[D16] 求和与平均值
来源：http://dali.vqdsnc.cn/Article/details/gtagnwyqau.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ppjwa.cn/Article/details/gtefywqvws.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jqgufenzy.top/Article/details/gthbmbwjpr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gotoacloud.top/Article/details/gtetlxhwgo.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkrnrsbye.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.c1oappe.top/Article/details/gthggkbngi.html

Go:   // 手写循环累加
来源：http://dali.fzhhl.top/Article/details/gtomimyoag.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.smart0.xyz/Article/details/gtecydhmij.html

C#:   list.Sum();  list.Average()
来源：http://dali.smart0.xyz/Article/details/gtrdmrlcwn.html

[D17] 最大值与最小值
来源：http://dali.gogol.net.cn/Article/details/gtfmdsjzcv.html

Py:   max(arr);  min(arr)
来源：http://dali.yangfankeji.com/Article/details/gthwbhulyu.html

PHP:  max($arr);  min($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtaanehnkz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtbnkrjvyh.html

TS:   Math.max(...arr);
来源：http://dali.yueranfly.top/Article/details/gtlsrsbvno.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.havefunace.top/Article/details/gtgadcllbw.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xuanzx.com/Article/details/gtrlgvyxol.html

Ruby: arr.max;  arr.min
来源：http://dali.dashuyun.cn/Article/details/gtsqlyfupd.html

C#:   list.Max();  list.Min()
来源：http://dali.mhx1999.top/Article/details/gtcltxxgow.html

[D18] 扁平化嵌套数组
来源：http://dali.jiagoushi.top/Article/details/gtfjkcwumo.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xziqi.cn/Article/details/gtsfusefkf.html

PHP:  array_merge(...$nested);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqmgsdjec.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xziqi.cn/Article/details/gtlnisizak.html

TS:   nested.flat();
来源：http://dali.vqdsnc.cn/Article/details/gtcmcupmqs.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtkpcebnmw.html

Go:   // 手写双层循环
来源：http://dali.cashguo.top/Article/details/gtdujpjxgr.html

Ruby: nested.flatten
来源：http://dali.cdnleiting.top/Article/details/gtpibmnysm.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xylfe.cn/Article/details/gtkzhzaevt.html

[D19] 按字段分组
来源：http://dali.0kj1m.cn/Article/details/gtocwbqlfj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhixingplan.top/Article/details/gtdtkgpjju.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnfpvhuim.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xziqi.cn/Article/details/gtbaknzcrv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xylfe.cn/Article/details/gtkmvflpnj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.guowangkeji.top/Article/details/gtkgiqdsfg.html

Go:   // 手写 map[string][]T
来源：http://dali.cqqwz.cn/Article/details/gtjmyzysew.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.chenjidiqi.icu/Article/details/gtyilrkvpq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jianghu66.top/Article/details/gtexrtfugq.html

[D20] 统计每个元素出现次数
来源：http://dali.bjfxy.top/Article/details/gtprorynvj.html

Py:   Counter(arr)
来源：http://dali.mhx1999.top/Article/details/gteblcxloc.html

PHP:  array_count_values($arr);
来源：http://dali.zhixingplan.top/Article/details/gtoengrjox.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shangyingyoupin.top/Article/details/gtkhgjsnyc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hysaishi.cn/Article/details/gtszrzopce.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yj20258888.top/Article/details/gthsqprlcr.html

Go:   // 手写 map[T]int
来源：http://dali.snrcjt.cn/Article/details/gtfekboysa.html

Ruby: arr.tally
来源：http://dali.daria6918.cn/Article/details/gtvqagpgat.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.daxiang520.top/Article/details/gtaxnssnne.html

[D21] 判断是否包含某元素
来源：http://dali.hnxiangtu.top/Article/details/gtosufejfr.html

Py:   x in arr
来源：http://dali.sweek.top/Article/details/gtdudbisge.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jyoumei.cn/Article/details/gtolqqohni.html

JS:   arr.includes(x)
来源：http://dali.xuanzx.com/Article/details/gtiwfxjfdw.html

TS:   arr.includes(x)
来源：http://dali.yueranfly.top/Article/details/gtsqxpgxye.html

Java: list.contains(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzdachzlr.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtteqdwzql.html

Ruby: arr.include?(x)
来源：http://dali.bjfxy.top/Article/details/gttwqcpoub.html

C#:   list.Contains(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtiqqxvxdz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yuanzhike.top/Article/details/gteuhkkyzd.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.smart0.xyz/Article/details/gtnetmtnsp.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.nwbrower.top/Article/details/gtiqizoeau.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.fzhhl.top/Article/details/gthsreupmh.html

TS:   [...arr];
来源：http://dali.tian-w.cn/Article/details/gtpbyrcsii.html

Java: new ArrayList<>(list);
来源：http://dali.guannengcc.top/Article/details/gtotlinhtq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.iojbl.cn/Article/details/gtzqcoqsmz.html

Ruby: arr.dup;  arr.clone
来源：http://dali.shangyingyoupin.top/Article/details/gtsirazgsu.html

C#:   new List<int>(list);
来源：http://dali.cashguo.top/Article/details/gtnvearrxl.html

[D23] reduce 累积计算
来源：http://dali.ivvv.top/Article/details/gtuiwdvomf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jqgfzy.top/Article/details/gtjxuaedmz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.0kj1m.cn/Article/details/gtslmzqesw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jiagoushi.top/Article/details/gtubidtbdw.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.birdmap.top/Article/details/gtxkjvrbbi.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhongyouzk.top/Article/details/gtnucgcwyo.html

Go:   // 手写循环
来源：http://dali.jinqigufen.top/Article/details/gtsuvcbsmw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.chenjidiqi.icu/Article/details/gtjftjdisi.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhixingplan.top/Article/details/gtjomnohgx.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhongyouzk.top/Article/details/gtkncxfiyh.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.gotoacloud.top/Article/details/gtjkitkgyu.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.0kj1m.cn/Article/details/gtwxnirtls.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.havefunace.top/Article/details/gtlnfskwym.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yuanzhike.top/Article/details/gtfcpfjkfe.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.tianlin.xyz/Article/details/gthpyrejvx.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.feifeiyinyue.top/Article/details/gttnsptjae.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.cucudq.cn/Article/details/gtevjphajq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yanxiufei.cn/Article/details/gtjgionrge.html

[D25] Set 集合去重与交并差
来源：http://dali.daxiang520.top/Article/details/gtonmxpuvk.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.316326.xyz/Article/details/gtzknhdwrw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jyoumei.cn/Article/details/gtvdhreatn.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtosfjyobe.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.tanke756.top/Article/details/gthxzwxryg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.haohaochexian.top/Article/details/gtzfzhmrlq.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jianghu66.top/Article/details/gtodeoebwa.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shzxlz.cn/Article/details/gtvdoxaudj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cqqwz.cn/Article/details/gtcxxwhqlm.html

[D26] 数组转字符串
来源：http://dali.hongshengwenyu.top/Article/details/gthdnyhzrr.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zdqjudy.top/Article/details/gtbzmuppmg.html

PHP:  implode(", ", $arr);
来源：http://dali.gzhubu.top/Article/details/gtpwbtigtu.html

JS:   arr.join(", ")
来源：http://dali.jyoumei.cn/Article/details/gtjbbuyzay.html

TS:   arr.join(", ")
来源：http://dali.yuxming.cn/Article/details/gtkjjprezz.html

Java: String.join(", ", list)
来源：http://dali.gotoacloud.top/Article/details/gtephovoyi.html

Go:   strings.Join(strs, ", ")
来源：http://dali.nanxinkj.top/Article/details/gtaflbuwvq.html

Ruby: arr.join(", ")
来源：http://dali.quarkkingdee.top/Article/details/gteufogbvv.html

C#:   string.Join(", ", list)
来源：http://dali.dashuyun.cn/Article/details/gtmurwnkqc.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtlfcvgptp.html

E. 字符串处理
来源：http://dali.dashuyun.cn/Article/details/gtkrwazrtu.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtanelhspp.html

[E01] 拼接字符串
来源：http://dali.jyoumei.cn/Article/details/gttjuidjti.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcfxrwcet.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yuxming.cn/Article/details/gtcxpfxxwl.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.c1oappe.top/Article/details/gtmtmzqkxg.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.havefunace.top/Article/details/gtqasqnaei.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.smart0.xyz/Article/details/gtqyllqzxk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shangyingyoupin.top/Article/details/gtuizguosx.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.vqdsnc.cn/Article/details/gtzdcepibu.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.birdmap.top/Article/details/gtkaicfhol.html

[E02] 重复字符串
来源：http://dali.ehwqpu.com/Article/details/gtfjqaxmbo.html

Py:   "ab" * 3
来源：http://dali.chenlongwang.top/Article/details/gtrhowmcpa.html

PHP:  str_repeat("ab", 3);
来源：http://dali.kuanghao11.cn/Article/details/gtdjwrkgjd.html

JS:   "ab".repeat(3)
来源：http://dali.316326.xyz/Article/details/gtrlxkroac.html

TS:   "ab".repeat(3)
来源：http://dali.yonumen.top/Article/details/gtfkmzjquw.html

Java: "ab".repeat(3)
来源：http://dali.vqdsnc.cn/Article/details/gtaikblaph.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cashguo.top/Article/details/gtmfahzwgx.html

Ruby: "ab" * 3
来源：http://dali.jiagoushi.top/Article/details/gtjqhsmdnm.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yj20258888.top/Article/details/gtmdvceevg.html

[E03] 截取子串
来源：http://dali.haohaochexian.top/Article/details/gtrvdgetmx.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xuanzx.com/Article/details/gtxfsbvyez.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yvedp.cn/Article/details/gtoeacvful.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shzxlz.cn/Article/details/gtnvulxhds.html

TS:   s.slice(1, 4)
来源：http://dali.fengsongda.top/Article/details/gtfdllvzzy.html

Java: s.substring(1, 4)
来源：http://dali.cheryme.top/Article/details/gtdcmnvwmp.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhaomingkeji.xyz/Article/details/gtifmofubq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzdzcuydd.html

C#:   s.Substring(1, 3)
来源：http://dali.yj202588.top/Article/details/gtvanunops.html

[E04] 查找子串位置
来源：http://dali.mhx1999.top/Article/details/gtffxpcnke.html

Py:   s.find("x");  s.index("x")
来源：http://dali.quarkkingdee.top/Article/details/gtlutwsemd.html

PHP:  strpos($s, "x");
来源：http://dali.wangshuangyany.cn/Article/details/gthsykcnzw.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhiwuduotai.top/Article/details/gtvewwsywe.html

TS:   s.indexOf("x")
来源：http://dali.ybcxt.top/Article/details/gtymugecxq.html

Java: s.indexOf("x")
来源：http://dali.cucudq.cn/Article/details/gtzcoilfxa.html


<!-- 参考信息 -->