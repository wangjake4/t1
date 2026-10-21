代发 wailian999

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gtppagfggs.html

Go:   func add(a, b int) int
来源：http://dali.jqgfzy.top/Article/details/gtmyrggrbo.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.chenzaomai.com/Article/details/gttxympqvt.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.sysykeji.top/Article/details/gtdsyveemr.html

[C14] 泛型函数
来源：http://dali.zhixingplan.top/Article/details/gtapgiiogr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ywan-chungtsiang.top/Article/details/gtipcccvnp.html

PHP:  // 无泛型
来源：http://dali.shangyingyoupin.top/Article/details/gtzymazmeh.html

JS:   // 无泛型
来源：http://dali.shanyushiyangtech.top/Article/details/gtzfkwptko.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xinyue.icu/Article/details/gtzewwwvcx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.nwbrower.top/Article/details/gtkcsvzhqt.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtedsegewb.html

Ruby: # 无泛型
来源：http://dali.zhaomingkeji.xyz/Article/details/gttfdcwlll.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.smart0.xyz/Article/details/gtdvyrpekq.html

[C15] 解构 / 展开参数
来源：http://dali.zhengqikj.top/Article/details/gtqaanepvs.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hysaishi.cn/Article/details/gtmbymchee.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ppjwa.cn/Article/details/gtdnfaumva.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yueranfly.top/Article/details/gttopqmtpk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.sufxvd.cn/Article/details/gticgymtyc.html

Java: // 无解构
来源：http://dali.hfpthk.cn/Article/details/gtuorjzydk.html

Go:   // 无解构
来源：http://dali.iojbl.cn/Article/details/gtofxapdib.html

Ruby: a, b = pair
来源：http://dali.chenzaomai.com/Article/details/gttjruhxhp.html

C#:   var (a, b) = pair;
来源：http://dali.nanxinkj.top/Article/details/gtokquidai.html

[C16] 函数 / 方法重载
来源：http://dali.yuxming.cn/Article/details/gtoautamrx.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yangfankeji.com/Article/details/gtmacwhfsu.html

PHP:  // 无重载
来源：http://dali.daxiang520.top/Article/details/gtbetkhxlp.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhoulong.xyz/Article/details/gtnzbxsneg.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ivvv.top/Article/details/gtokzgolhb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zdqjudy.top/Article/details/gtmnesijqx.html

Go:   // 无重载：用不同函数名
来源：http://dali.hnqzz.top/Article/details/gtlkrfdylp.html

Ruby: # 无重载：靠动态参数
来源：http://dali.smart0.xyz/Article/details/gtppajbvvi.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jinqigfzy.top/Article/details/gtwfebcmlz.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtmrkrfgoy.html

D. 数组 / 列表 / 集合
来源：http://dali.zhoulong.xyz/Article/details/gtlrmdheft.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtopkngczi.html

[D01] 创建数组 / 列表
来源：http://dali.shzxlz.cn/Article/details/gtwhowwznv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhoulong.xyz/Article/details/gtagzeuawr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsedfrtzt.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.wangshuangyany.cn/Article/details/gtllkqylzw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hnqzz.top/Article/details/gtzvtiodqo.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yj20258888.top/Article/details/gtxzqzdsoa.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yonumen.top/Article/details/gtcimmpjjd.html

Ruby: arr = [1, 2, 3]
来源：http://dali.wangshuangyany.cn/Article/details/gtleedxnbc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfzxeeosk.html

[D02] 追加元素到末尾
来源：http://dali.wangshuangyany.cn/Article/details/gtavwvenuj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yonumen.top/Article/details/gtjdttmcun.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hongshengwenyu.top/Article/details/gtrwunasjs.html

JS:   arr.push(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzgwbakts.html

TS:   arr.push(4);
来源：http://dali.ydzc1.top/Article/details/gtrkfqsaiv.html

Java: list.add(4);
来源：http://dali.chenzaomai.com/Article/details/gtjdmsvwvb.html

Go:   arr = append(arr, 4)
来源：http://dali.daxiang520.top/Article/details/gtxwhqgcui.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.316326.xyz/Article/details/gtlmxcbetu.html

C#:   list.Add(4);
来源：http://dali.yuanzhike.top/Article/details/gtlsjskvin.html

[D03] 在指定位置插入元素
来源：http://dali.hammf.cn/Article/details/gtghnbjmhp.html

Py:   arr.insert(0, 0)
来源：http://dali.redwolf501.top/Article/details/gtrcsrynnx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.bjfxy.top/Article/details/gtnughkpae.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.tanke756.top/Article/details/gtbdyjildz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.daxiang520.top/Article/details/gtdrqgemtw.html

Java: list.add(0, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwmgbaxqy.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.guannengcc.top/Article/details/gtegqufakt.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shangyingyoupin.top/Article/details/gtlwqpwbmh.html

C#:   list.Insert(0, 0);
来源：http://dali.zdqjudy.top/Article/details/gtfestctji.html

[D04] 删除元素
来源：http://dali.hywenlv.cn/Article/details/gtlnjkoziz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shangyingyoupin.top/Article/details/gtqfeasrpx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zycfv.cn/Article/details/gtznlmoxko.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.aizwys.cn/Article/details/gtmbcisrby.html

TS:   arr.splice(0, 1);
来源：http://dali.redwolf501.top/Article/details/gtzrjbfhjx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtejmztroa.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gotoacloud.top/Article/details/gtnbqgqjil.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcwtqcdcy.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hfpthk.cn/Article/details/gtznenaslu.html

[D05] 访问与修改元素
来源：http://dali.zhongyouzk.top/Article/details/gtmtpxczcn.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pycfn.com/Article/details/gtxdyuegoi.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jinghuilouyu.cn/Article/details/gtkrntvrie.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hammf.cn/Article/details/gtvdhlepwp.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.redwolf501.top/Article/details/gtagjwekga.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hywenlv.cn/Article/details/gtwaaujoxo.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.smart0.xyz/Article/details/gtzxsciiwe.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.fengsongda.top/Article/details/gttrtiypqt.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jqgfzy.top/Article/details/gtziritvbx.html

[D06] 数组长度
来源：http://dali.yanxiufei.cn/Article/details/gtqrwebsbt.html

Py:   len(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtgxgfxmjz.html

PHP:  count($arr);
来源：http://dali.sxryk.cn/Article/details/gtpvnovkcm.html

JS:   arr.length
来源：http://dali.jianghu66.top/Article/details/gtxvmgvjyg.html

TS:   arr.length
来源：http://dali.chenlongwang.top/Article/details/gtjsydigav.html

Java: list.size();
来源：http://dali.shanyushiyangkeji.top/Article/details/gthiksohxa.html

Go:   len(arr)
来源：http://dali.birdmap.top/Article/details/gttkebqmbf.html

Ruby: arr.length; arr.size
来源：http://dali.tian-w.cn/Article/details/gtchnsizlk.html

C#:   list.Count;
来源：http://dali.dashuyun.cn/Article/details/gtsgccunos.html

[D07] 切片 / 取子数组
来源：http://dali.svipenyu.cn/Article/details/gtysipjvpg.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.sysykeji.top/Article/details/gtizrfrwzd.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.snrcjt.cn/Article/details/gtycqbbrat.html

JS:   arr.slice(1, 4);
来源：http://dali.gotoacloud.top/Article/details/gtstrnwivu.html

TS:   arr.slice(1, 4);
来源：http://dali.shangyingyoupin.top/Article/details/gtqxjdhsvj.html

Java: list.subList(1, 4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtcavmgdnk.html

Go:   arr[1:4]
来源：http://dali.tian-w.cn/Article/details/gtcndjqfvk.html

Ruby: arr[1, 3]
来源：http://dali.yangfankeji.com/Article/details/gtyfxbcepg.html

C#:   list.GetRange(1, 3);
来源：http://dali.hongshengwenyu.top/Article/details/gthbnpxpph.html

[D08] 合并两个数组
来源：http://dali.sweek.top/Article/details/gtpllriphe.html

Py:   a + b;  a.extend(b)
来源：http://dali.c1oappe.top/Article/details/gtbpdgqkne.html

PHP:  array_merge($a, $b);
来源：http://dali.gaohongyu789.top/Article/details/gtjpheoktm.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.chenjidiqi.icu/Article/details/gtiqcegwsi.html

TS:   [...a, ...b];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyuzodvfk.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hfpthk.cn/Article/details/gtirieaevs.html

Go:   append(a, b...)
来源：http://dali.yj202588.top/Article/details/gttznysynm.html

Ruby: a + b;  a.concat(b)
来源：http://dali.chenzaomai.com/Article/details/gtkkrvcpte.html

C#:   a.Concat(b).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gtbwbhqskm.html

[D09] 排序（升序）
来源：http://dali.cashguo.top/Article/details/gtvtbcdmuj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fengsongda.top/Article/details/gtqwoisgmc.html

PHP:  sort($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtamnsezpm.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yj202588.top/Article/details/gtpcqgrsqy.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.tianlin.xyz/Article/details/gtsctyssff.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yuxming.cn/Article/details/gtoiutpmsm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shzxlz.cn/Article/details/gtrerrnqjv.html

Ruby: arr.sort
来源：http://dali.jqgufenzy.top/Article/details/gtrjdtshjt.html

C#:   list.Sort();
来源：http://dali.jianghu66.top/Article/details/gtulsobxyo.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yongpay.top/Article/details/gthkkvtwws.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yueranfly.top/Article/details/gtwoimwyyj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gaohongyu789.top/Article/details/gtyrjjntds.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.quarkkingdee.top/Article/details/gthzacmvya.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.aibaodan.cn/Article/details/gtixcnkuvq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.mhx1999.top/Article/details/gthdeqogma.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinqigufen.top/Article/details/gtvbvrvdeh.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xylfe.cn/Article/details/gtzajmywpe.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.aizwys.cn/Article/details/gtwiyvuire.html

[D11] 反转数组
来源：http://dali.xinyue.icu/Article/details/gtogxuouai.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.chenjidiqi.icu/Article/details/gtyspglgyw.html

PHP:  array_reverse($arr);
来源：http://dali.xziqi.cn/Article/details/gtcdycnwkv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.chenzaomai.com/Article/details/gtbmkrnycx.html

TS:   [...arr].reverse();
来源：http://dali.tian-w.cn/Article/details/gttubeqozp.html

Java: Collections.reverse(list);
来源：http://dali.aibaodan.cn/Article/details/gtmtalvewr.html

Go:   slices.Reverse(arr)
来源：http://dali.xinyue.icu/Article/details/gtnagiewvc.html

Ruby: arr.reverse
来源：http://dali.jyoumei.cn/Article/details/gtdqharspp.html

C#:   list.Reverse();
来源：http://dali.kuanghao11.cn/Article/details/gtwilridkz.html

[D12] 查找元素下标
来源：http://dali.yj20258.top/Article/details/gtacttdpxa.html

Py:   arr.index(x);  x in arr
来源：http://dali.jlsjyb.cn/Article/details/gtdfwfjloi.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.sweek.top/Article/details/gtwngptrjd.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hongshengwenyu.top/Article/details/gtogxszyep.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jqgufenzy.top/Article/details/gtzlcqsjmp.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jiagoushi.top/Article/details/gtdztrluwe.html

Go:   slices.Index(arr, x)
来源：http://dali.xinyue.icu/Article/details/gtefuzjkjg.html

Ruby: arr.index(x)
来源：http://dali.yanxiufei.cn/Article/details/gtodxgxwir.html

C#:   list.IndexOf(x);
来源：http://dali.svipenyu.cn/Article/details/gtnyzdzxol.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhoulong.xyz/Article/details/gtzkzcodyp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.tianlin.xyz/Article/details/gtaxbbqpfs.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yj20258888.top/Article/details/gtkgsalhuh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sysykeji.top/Article/details/gtfbxucmof.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ivvv.top/Article/details/gttpoicwne.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.meibo888.top/Article/details/gttrziooul.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jiagoushi.top/Article/details/gtevmgwbhm.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xylfe.cn/Article/details/gtnccfopwd.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gtxwqpunhy.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hammf.cn/Article/details/gtxfgjrgsm.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jiagoushi.top/Article/details/gtaytmedpx.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sufxvd.cn/Article/details/gtgpiperki.html

JS:   arr.map(x => x * 2)
来源：http://dali.ydzc1.top/Article/details/gtlvpxtlol.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gtbaoxyrgo.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwhbuzzyv.html

Go:   // 手写循环
来源：http://dali.daxiang520.top/Article/details/gtpfnjxagi.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jqgufenzy.top/Article/details/gthivtjhsv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.wangdashe.top/Article/details/gthubouaie.html

[D15] 去重
来源：http://dali.aizwys.cn/Article/details/gtxsgyvtyb.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gaohongyu789.top/Article/details/gtkgvsqqka.html

PHP:  array_unique($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfyufyhix.html

JS:   [...new Set(arr)]
来源：http://dali.smart0.xyz/Article/details/gtoksvnyeq.html

TS:   [...new Set(arr)]
来源：http://dali.vqdsnc.cn/Article/details/gtwspuxuok.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cashguo.top/Article/details/gtzblmghqp.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.cqqwz.cn/Article/details/gtdkqsgtzs.html

Ruby: arr.uniq
来源：http://dali.yongpay.top/Article/details/gtfhrdsbmf.html

C#:   list.Distinct().ToList()
来源：http://dali.aizwys.cn/Article/details/gtiuougdkm.html

[D16] 求和与平均值
来源：http://dali.jianghu66.top/Article/details/gtdnjlkqls.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sxryk.cn/Article/details/gtevhazzxs.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.guannengcc.top/Article/details/gttqqgoqbh.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.316326.xyz/Article/details/gtkgqqbnvl.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtvuoriiob.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhiwuduotai.top/Article/details/gthmwkihvx.html

Go:   // 手写循环累加
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmhziaswb.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sweek.top/Article/details/gtkqfmzbxh.html

C#:   list.Sum();  list.Average()
来源：http://dali.smart0.xyz/Article/details/gtuoylauwe.html

[D17] 最大值与最小值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqyfuuzbf.html

Py:   max(arr);  min(arr)
来源：http://dali.tanke756.top/Article/details/gtaevlaahx.html

PHP:  max($arr);  min($arr);
来源：http://dali.tanke756.top/Article/details/gtygqcemiz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.sysykeji.top/Article/details/gtzlzlnohx.html

TS:   Math.max(...arr);
来源：http://dali.sweek.top/Article/details/gtdhornkym.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gtebzivjhl.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shzxlz.cn/Article/details/gtnubtvxhm.html

Ruby: arr.max;  arr.min
来源：http://dali.jinqigfzy.top/Article/details/gtfsjwahid.html

C#:   list.Max();  list.Min()
来源：http://dali.hnxiangtu.top/Article/details/gtlmancnit.html

[D18] 扁平化嵌套数组
来源：http://dali.hysaishi.cn/Article/details/gthrseqiyt.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.haohaochexian.top/Article/details/gtdgfbiwcv.html

PHP:  array_merge(...$nested);
来源：http://dali.redwolf501.top/Article/details/gtbvnfltdx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.0kj1m.cn/Article/details/gtggenjmts.html

TS:   nested.flat();
来源：http://dali.gogol.net.cn/Article/details/gthiekrtla.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shangyingyoupin.top/Article/details/gtwzmwefhq.html

Go:   // 手写双层循环
来源：http://dali.tianlin.xyz/Article/details/gtrbzfpvfu.html

Ruby: nested.flatten
来源：http://dali.shanyushiyangtech.top/Article/details/gttzwbgisf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ydzc1.top/Article/details/gtdwmurgor.html

[D19] 按字段分组
来源：http://dali.zhixingplan.top/Article/details/gtrpjwjjwg.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hywenlv.cn/Article/details/gtpufwqvbf.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.kuanghao11.cn/Article/details/gtyaadqrac.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hfpthk.cn/Article/details/gtxfsfoift.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzqzgoipv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yvedp.cn/Article/details/gtxblpcbix.html

Go:   // 手写 map[string][]T
来源：http://dali.0kj1m.cn/Article/details/gtkzmbfppl.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.sysykeji.top/Article/details/gtimcpghns.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.nanxuanxn.top/Article/details/gtgsohpdsw.html

[D20] 统计每个元素出现次数
来源：http://dali.jinghuilouyu.cn/Article/details/gtfboeoeck.html

Py:   Counter(arr)
来源：http://dali.yj20258888.top/Article/details/gthlfdhvyq.html

PHP:  array_count_values($arr);
来源：http://dali.tianlin.xyz/Article/details/gtijfupapq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sxryk.cn/Article/details/gthxumgbzx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgufenzy.top/Article/details/gtdwfqwlui.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhoulong.xyz/Article/details/gtobewjpgn.html

Go:   // 手写 map[T]int
来源：http://dali.nanxinkj.top/Article/details/gtosvpmebk.html

Ruby: arr.tally
来源：http://dali.daria6918.cn/Article/details/gtqcsvtfss.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xinyue.icu/Article/details/gtxqyygogx.html

[D21] 判断是否包含某元素
来源：http://dali.chenlongwang.top/Article/details/gtacbjbuxz.html

Py:   x in arr
来源：http://dali.jiagoushi.top/Article/details/gtlljscqbs.html

PHP:  in_array($x, $arr, true);
来源：http://dali.fengsongda.top/Article/details/gtzcpvlkhe.html

JS:   arr.includes(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtkjjkcfox.html

TS:   arr.includes(x)
来源：http://dali.fzhhl.top/Article/details/gtnlvcjxgc.html

Java: list.contains(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtqdcvhlcj.html

Go:   slices.Contains(arr, x)
来源：http://dali.tanke756.top/Article/details/gtlsfxwejx.html

Ruby: arr.include?(x)
来源：http://dali.tanke756.top/Article/details/gtlxdpxdgk.html

C#:   list.Contains(x)
来源：http://dali.ybcxt.top/Article/details/gtnmceiecf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.vqdsnc.cn/Article/details/gtdguffuyk.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hammf.cn/Article/details/gtdsrhtjev.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.cheryme.top/Article/details/gtomhytuks.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sweek.top/Article/details/gtzmenirze.html

TS:   [...arr];
来源：http://dali.shangyingyoupin.top/Article/details/gtycslcvew.html

Java: new ArrayList<>(list);
来源：http://dali.hammf.cn/Article/details/gttdmtdihc.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.tanke756.top/Article/details/gtcfldtoyn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cashguo.top/Article/details/gtbhvkpotb.html

C#:   new List<int>(list);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiepaujpb.html

[D23] reduce 累积计算
来源：http://dali.zhengqikj.top/Article/details/gtakptyxpp.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ydzc1.top/Article/details/gtauohcqar.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.gaohongyu789.top/Article/details/gttbckopvp.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdcmkjbcd.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigfzy.top/Article/details/gticwkdgdj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.havefunace.top/Article/details/gtntzrmgmn.html

Go:   // 手写循环
来源：http://dali.zhiwuduotai.top/Article/details/gtotsnreaf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.tian-w.cn/Article/details/gtzautujis.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shangyingyoupin.top/Article/details/gtwhjxovil.html

[D24] 字典 / Map 基本操作
来源：http://dali.hongshengwenyu.top/Article/details/gtjampisdj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xylfe.cn/Article/details/gtsmvriltg.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jinqigufen.top/Article/details/gtiulkibnd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yuxming.cn/Article/details/gtievhecao.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hnxiangtu.top/Article/details/gtycyadoug.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jiagoushi.top/Article/details/gtcfzrqjjm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jqgfzy.top/Article/details/gtsbjeomtr.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.snrcjt.cn/Article/details/gtbphmhsbx.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.tian-w.cn/Article/details/gtpqchufoi.html

[D25] Set 集合去重与交并差
来源：http://dali.jinqigufen.top/Article/details/gtopginlxz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhiwuduotai.top/Article/details/gtizlmoebr.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.c1oappe.top/Article/details/gtdvhgjsem.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.guowangkeji.top/Article/details/gtjglykhzy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.bjfxy.top/Article/details/gtkavlgfio.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhengqikj.top/Article/details/gtxiopmrml.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yuanzhike.top/Article/details/gtjyklhnvx.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ybcxt.top/Article/details/gtmherezvn.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zycfv.cn/Article/details/gtxawabzov.html

[D26] 数组转字符串
来源：http://dali.316326.xyz/Article/details/gtebfqokbv.html

Py:   ", ".join(map(str, arr))
来源：http://dali.chenzaomai.com/Article/details/gtutjfbxny.html

PHP:  implode(", ", $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gthpngnoyd.html

JS:   arr.join(", ")
来源：http://dali.sweek.top/Article/details/gtbgziyhmy.html

TS:   arr.join(", ")
来源：http://dali.chenlongwang.top/Article/details/gtcjlcotcl.html

Java: String.join(", ", list)
来源：http://dali.ydzc1.top/Article/details/gtgfqyfigj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hfpthk.cn/Article/details/gtnosjrnfo.html

Ruby: arr.join(", ")
来源：http://dali.shanyushiyangtech.top/Article/details/gtobsdthps.html

C#:   string.Join(", ", list)
来源：http://dali.fengsongda.top/Article/details/gtdvufqzbb.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxqtuiimu.html

E. 字符串处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzvsaiweo.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtfsjvjufk.html

[E01] 拼接字符串
来源：http://dali.xziqi.cn/Article/details/gtiramerhn.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jinghuilouyu.cn/Article/details/gtglcgrusj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hnqzz.top/Article/details/gtiizcwwts.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinqigufen.top/Article/details/gtnhjqpiyy.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yongpay.top/Article/details/gtuuzxmhpx.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.fengsongda.top/Article/details/gtujhzppmx.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yuanzhike.top/Article/details/gtbxyriqkt.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.tanke756.top/Article/details/gtwujivjzd.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.iojbl.cn/Article/details/gtgqrnbzbl.html

[E02] 重复字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbcfthxql.html

Py:   "ab" * 3
来源：http://dali.jinqigfzy.top/Article/details/gtbvhkgysr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cqqwz.cn/Article/details/gtgutsigwe.html

JS:   "ab".repeat(3)
来源：http://dali.zdqjudy.top/Article/details/gtkqgghwxd.html

TS:   "ab".repeat(3)
来源：http://dali.9152youxi.cn/Article/details/gtjxzsfgdf.html

Java: "ab".repeat(3)
来源：http://dali.ydzc1.top/Article/details/gtjlupsqbt.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cdnleiting.top/Article/details/gtprjpadll.html

Ruby: "ab" * 3
来源：http://dali.fengsongda.top/Article/details/gtvtmdpjbo.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.316326.xyz/Article/details/gtuypmxfvw.html

[E03] 截取子串
来源：http://dali.quarkkingdee.top/Article/details/gtqzcvjnhk.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.quarkkingdee.top/Article/details/gtiprmiwaq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yonumen.top/Article/details/gtwqgcpeem.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yonumen.top/Article/details/gtsqnkeign.html

TS:   s.slice(1, 4)
来源：http://dali.yonumen.top/Article/details/gttbtkdhja.html

Java: s.substring(1, 4)
来源：http://dali.jinqigfzy.top/Article/details/gttrducorc.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xylfe.cn/Article/details/gtskzmrkce.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.bjfxy.top/Article/details/gtcksnscrz.html

C#:   s.Substring(1, 3)
来源：http://dali.yuxming.cn/Article/details/gtxnepdmfj.html

[E04] 查找子串位置
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvhgwikoz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xziqi.cn/Article/details/gtbigjizvh.html


<!-- 参考信息 -->