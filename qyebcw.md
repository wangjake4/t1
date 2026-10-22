代发 wailian999

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gtgqsuzmpo.html

Go:   func add(a, b int) int
来源：http://dali.yvedp.cn/Article/details/gtolskqosr.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shuidangran.top/Article/details/gtekeibtge.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.feifeiyinyue.top/Article/details/gtycehaqer.html

[C14] 泛型函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtolmverlc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.guowangkeji.top/Article/details/gtczbarpjx.html

PHP:  // 无泛型
来源：http://dali.yangfankeji.com/Article/details/gtrgxcuztb.html

JS:   // 无泛型
来源：http://dali.sxryk.cn/Article/details/gtqekuzapy.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gteuamubso.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jinqigufen.top/Article/details/gttzzinupu.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.wangshuangyany.cn/Article/details/gtuaeugyzw.html

Ruby: # 无泛型
来源：http://dali.jinqigufen.top/Article/details/gtasybphjc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.c1oappe.top/Article/details/gtphfkdvbv.html

[C15] 解构 / 展开参数
来源：http://dali.ehwqpu.com/Article/details/gtixwotoql.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.daria6918.cn/Article/details/gtjuapkrpu.html

PHP:  [$a, $b] = $pair;
来源：http://dali.316326.xyz/Article/details/gtxtewzwgx.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yanxiufei.cn/Article/details/gtfjprntam.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhengqikj.top/Article/details/gtremocinr.html

Java: // 无解构
来源：http://dali.cqqwz.cn/Article/details/gtwxlvoruo.html

Go:   // 无解构
来源：http://dali.shuidangran.top/Article/details/gtksoagmld.html

Ruby: a, b = pair
来源：http://dali.xinyue.icu/Article/details/gtjpggdvny.html

C#:   var (a, b) = pair;
来源：http://dali.zhiwuduotai.top/Article/details/gtvncxqxbu.html

[C16] 函数 / 方法重载
来源：http://dali.shanyushiyangtech.top/Article/details/gtsigzjcjq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cheryme.top/Article/details/gtwgwhcvvk.html

PHP:  // 无重载
来源：http://dali.pycfn.com/Article/details/gtffiwwvdg.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yj202588.top/Article/details/gtphstsqwv.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ivvv.top/Article/details/gtqhinockn.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.c1oappe.top/Article/details/gtpifylztx.html

Go:   // 无重载：用不同函数名
来源：http://dali.nanxuanxn.top/Article/details/gtcegdhrtk.html

Ruby: # 无重载：靠动态参数
来源：http://dali.smart0.xyz/Article/details/gttdkztcut.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtcxllvvce.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtaygihcvp.html

D. 数组 / 列表 / 集合
来源：http://dali.jinghuilouyu.cn/Article/details/gtywkxxtnq.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtmpufumjj.html

[D01] 创建数组 / 列表
来源：http://dali.jqgfzy.top/Article/details/gtziqmykgp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmdsnthmj.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.nanxuanxn.top/Article/details/gtapoitmtl.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zdqjudy.top/Article/details/gtvqrmgcaf.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gtbijxbyje.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.nanxinkj.top/Article/details/gtwejnvmzm.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.gaohongyu789.top/Article/details/gtqlkftkvl.html

Ruby: arr = [1, 2, 3]
来源：http://dali.bjfxy.top/Article/details/gtqnizakbv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sysykeji.top/Article/details/gtdqnabtby.html

[D02] 追加元素到末尾
来源：http://dali.wangshuangyany.cn/Article/details/gtkibyfaza.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.aibaodan.cn/Article/details/gtvioanieb.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ydzc1.top/Article/details/gtdzdfbppt.html

JS:   arr.push(4);
来源：http://dali.feifeiyinyue.top/Article/details/gtgnlnalvn.html

TS:   arr.push(4);
来源：http://dali.bjfxy.top/Article/details/gtopykqhuv.html

Java: list.add(4);
来源：http://dali.feifeiyinyue.top/Article/details/gtlbijliay.html

Go:   arr = append(arr, 4)
来源：http://dali.haohaochexian.top/Article/details/gtjbclxyhh.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shzxlz.cn/Article/details/gtsbdmscpa.html

C#:   list.Add(4);
来源：http://dali.hnqzz.top/Article/details/gtnxhahsrm.html

[D03] 在指定位置插入元素
来源：http://dali.jinqigufen.top/Article/details/gtzfwsqugm.html

Py:   arr.insert(0, 0)
来源：http://dali.daxiang520.top/Article/details/gtmefqzxnr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.guannengcc.top/Article/details/gtiwkwlbim.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yuanzhike.top/Article/details/gtzrcriwas.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hammf.cn/Article/details/gtnlwgwqwp.html

Java: list.add(0, 0);
来源：http://dali.tian-w.cn/Article/details/gtduwgeras.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.316326.xyz/Article/details/gtmbkwngve.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jianghu66.top/Article/details/gtpdklzlyz.html

C#:   list.Insert(0, 0);
来源：http://dali.fengsongda.top/Article/details/gtrypcqian.html

[D04] 删除元素
来源：http://dali.haohaochexian.top/Article/details/gtusdkklxp.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ybcxt.top/Article/details/gtubelinyn.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ydzc1.top/Article/details/gtduvtlmek.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hnxiangtu.top/Article/details/gtocbaadrh.html

TS:   arr.splice(0, 1);
来源：http://dali.fzhhl.top/Article/details/gtnrfhyfmr.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.guannengcc.top/Article/details/gtkgaikiva.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.tanke756.top/Article/details/gtvugjroon.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.aibaodan.cn/Article/details/gtmneledue.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hysaishi.cn/Article/details/gtsanfkegl.html

[D05] 访问与修改元素
来源：http://dali.316326.xyz/Article/details/gtufueipud.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.c1oappe.top/Article/details/gtphcjinng.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hnxiangtu.top/Article/details/gtabafqnis.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.vqdsnc.cn/Article/details/gtpjekchch.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.nwbrower.top/Article/details/gtrtupursy.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jlsjyb.cn/Article/details/gtznduwwuo.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.havefunace.top/Article/details/gtckkqneua.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ehwqpu.com/Article/details/gthgzcvkfb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zdqjudy.top/Article/details/gtxihjnyhi.html

[D06] 数组长度
来源：http://dali.cdnleiting.top/Article/details/gtfpvwwbdl.html

Py:   len(arr)
来源：http://dali.gogol.net.cn/Article/details/gtlrdnqpbh.html

PHP:  count($arr);
来源：http://dali.yvedp.cn/Article/details/gtzhiixvjq.html

JS:   arr.length
来源：http://dali.haohaochexian.top/Article/details/gtwbqvfrdf.html

TS:   arr.length
来源：http://dali.fzhhl.top/Article/details/gtqqycqdaf.html

Java: list.size();
来源：http://dali.jiagoushi.top/Article/details/gtzndtoxdh.html

Go:   len(arr)
来源：http://dali.cdnleiting.top/Article/details/gtsibdybtp.html

Ruby: arr.length; arr.size
来源：http://dali.ydzc1.top/Article/details/gtedpapmpf.html

C#:   list.Count;
来源：http://dali.andypj.xyz/Article/details/gtfeptmsvp.html

[D07] 切片 / 取子数组
来源：http://dali.316326.xyz/Article/details/gtydfophbi.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.daria6918.cn/Article/details/gtdtppgiuc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jinqigufen.top/Article/details/gtggmybnep.html

JS:   arr.slice(1, 4);
来源：http://dali.sweek.top/Article/details/gtzotirqyr.html

TS:   arr.slice(1, 4);
来源：http://dali.xinyue.icu/Article/details/gtjzdoymjn.html

Java: list.subList(1, 4);
来源：http://dali.cashguo.top/Article/details/gthbigiark.html

Go:   arr[1:4]
来源：http://dali.shanyushiyangtech.top/Article/details/gtvobpxfde.html

Ruby: arr[1, 3]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqpqrzzvw.html

C#:   list.GetRange(1, 3);
来源：http://dali.yvedp.cn/Article/details/gtcpzczgen.html

[D08] 合并两个数组
来源：http://dali.tian-w.cn/Article/details/gtmirrqvvx.html

Py:   a + b;  a.extend(b)
来源：http://dali.yuxming.cn/Article/details/gtbxhkaydf.html

PHP:  array_merge($a, $b);
来源：http://dali.chenjidiqi.icu/Article/details/gthlgiidhx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cashguo.top/Article/details/gtmmehslkq.html

TS:   [...a, ...b];
来源：http://dali.chenjidiqi.icu/Article/details/gtfdmpotpu.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtryvrzaaf.html

Go:   append(a, b...)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtulukybee.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cashguo.top/Article/details/gtficuqrxq.html

C#:   a.Concat(b).ToList()
来源：http://dali.nanxinkj.top/Article/details/gtoebuneef.html

[D09] 排序（升序）
来源：http://dali.smart0.xyz/Article/details/gtpjosjzhn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzvwanjsp.html

PHP:  sort($arr);
来源：http://dali.jinqigufen.top/Article/details/gtiwqacnqs.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.svipenyu.cn/Article/details/gtquytexsk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.aibaodan.cn/Article/details/gtjlxraqkd.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hnqzz.top/Article/details/gtubqmqrgv.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jinqigufen.top/Article/details/gthkuezzjx.html

Ruby: arr.sort
来源：http://dali.yongpay.top/Article/details/gttmnjrago.html

C#:   list.Sort();
来源：http://dali.zhoulong.xyz/Article/details/gtvjyeorsi.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.aibaodan.cn/Article/details/gtfmvceolf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ybcxt.top/Article/details/gtpqyluvrg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yueranfly.top/Article/details/gtoqvejapy.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cucudq.cn/Article/details/gtopengczx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhiwuduotai.top/Article/details/gtycqzwnpt.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cheryme.top/Article/details/gtdetqipdf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhixingplan.top/Article/details/gtgivimazt.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shzxlz.cn/Article/details/gtvzfgrden.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ehwqpu.com/Article/details/gtrpawfneu.html

[D11] 反转数组
来源：http://dali.nwbrower.top/Article/details/gtncahniar.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.chenjidiqi.icu/Article/details/gtquygwgji.html

PHP:  array_reverse($arr);
来源：http://dali.guannengcc.top/Article/details/gtzbxgnviz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.bjfxy.top/Article/details/gteokmalih.html

TS:   [...arr].reverse();
来源：http://dali.hammf.cn/Article/details/gtlzecveew.html

Java: Collections.reverse(list);
来源：http://dali.yanxiufei.cn/Article/details/gtugzitlie.html

Go:   slices.Reverse(arr)
来源：http://dali.ybcxt.top/Article/details/gtimeckasd.html

Ruby: arr.reverse
来源：http://dali.yanxiufei.cn/Article/details/gtaiqbkdag.html

C#:   list.Reverse();
来源：http://dali.sxryk.cn/Article/details/gtrhcwrlgk.html

[D12] 查找元素下标
来源：http://dali.yj20258888.top/Article/details/gtmxmrbpqp.html

Py:   arr.index(x);  x in arr
来源：http://dali.haohaochexian.top/Article/details/gttmfesmnt.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.316326.xyz/Article/details/gtfmdmhtfh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj20258.top/Article/details/gtgjsteell.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoqskajxm.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yuanzhike.top/Article/details/gtqaakrgcv.html

Go:   slices.Index(arr, x)
来源：http://dali.fengsongda.top/Article/details/gtwsscnwes.html

Ruby: arr.index(x)
来源：http://dali.jqgufenzy.top/Article/details/gthtwtghty.html

C#:   list.IndexOf(x);
来源：http://dali.zycfv.cn/Article/details/gtjkvawsue.html

[D13] 过滤（保留满足条件的）
来源：http://dali.chenzaomai.com/Article/details/gtvfxhmvdo.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.nanxinkj.top/Article/details/gtdpdajyas.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.vqdsnc.cn/Article/details/gtvtnozntv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.vqdsnc.cn/Article/details/gtsksclcmf.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ivvv.top/Article/details/gtobvtfglf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.kuanghao11.cn/Article/details/gtyszkptej.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hfpthk.cn/Article/details/gtuvrfvetd.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.wangdashe.top/Article/details/gtstmiytnm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zycfv.cn/Article/details/gtlsguommf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.guowangkeji.top/Article/details/gttkpfxrhq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.daxiang520.top/Article/details/gtdumzqrvn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sxryk.cn/Article/details/gtsqzrtyyt.html

JS:   arr.map(x => x * 2)
来源：http://dali.wangdashe.top/Article/details/gtldmumzjg.html

TS:   arr.map(x => x * 2)
来源：http://dali.gaohongyu789.top/Article/details/gtacrdtuic.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.pycfn.com/Article/details/gtugcgvynb.html

Go:   // 手写循环
来源：http://dali.hfpthk.cn/Article/details/gtqfrqcltm.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.316326.xyz/Article/details/gtsrlacsav.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cashguo.top/Article/details/gtieedekea.html

[D15] 去重
来源：http://dali.chenjidiqi.icu/Article/details/gtqediyxcx.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.sweek.top/Article/details/gtomjilxtw.html

PHP:  array_unique($arr);
来源：http://dali.hammf.cn/Article/details/gtorkfaxcs.html

JS:   [...new Set(arr)]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgtunwdkm.html

TS:   [...new Set(arr)]
来源：http://dali.xziqi.cn/Article/details/gtgixvbekw.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yvedp.cn/Article/details/gtqlzgfhfw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.nwbrower.top/Article/details/gtufmjskad.html

Ruby: arr.uniq
来源：http://dali.tianlin.xyz/Article/details/gtonkgvibd.html

C#:   list.Distinct().ToList()
来源：http://dali.yuanzhike.top/Article/details/gtibyrtexz.html

[D16] 求和与平均值
来源：http://dali.guannengcc.top/Article/details/gtnxjpgmfl.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtrvzzsodn.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.meibo888.top/Article/details/gtztlntafo.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jianghu66.top/Article/details/gtpezhbowp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigufen.top/Article/details/gtdvcruswl.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yangfankeji.com/Article/details/gtiyjfmern.html

Go:   // 手写循环累加
来源：http://dali.guannengcc.top/Article/details/gtzvlfayvq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hfpthk.cn/Article/details/gtwqxwutyu.html

C#:   list.Sum();  list.Average()
来源：http://dali.tianlin.xyz/Article/details/gtvclphraj.html

[D17] 最大值与最小值
来源：http://dali.jlsjyb.cn/Article/details/gtlgqtuize.html

Py:   max(arr);  min(arr)
来源：http://dali.aizwys.cn/Article/details/gtxldxvrii.html

PHP:  max($arr);  min($arr);
来源：http://dali.9152youxi.cn/Article/details/gtcvhvlrli.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jinqigfzy.top/Article/details/gtgqzqmahu.html

TS:   Math.max(...arr);
来源：http://dali.zhongyouzk.top/Article/details/gtddegjwkw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xziqi.cn/Article/details/gtlxnxrfho.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cashguo.top/Article/details/gthoygpgbb.html

Ruby: arr.max;  arr.min
来源：http://dali.dashuyun.cn/Article/details/gtyeytisct.html

C#:   list.Max();  list.Min()
来源：http://dali.xziqi.cn/Article/details/gtgqrntbbu.html

[D18] 扁平化嵌套数组
来源：http://dali.hysaishi.cn/Article/details/gtldlmveou.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.aizwys.cn/Article/details/gtsughqvpi.html

PHP:  array_merge(...$nested);
来源：http://dali.wangshuangyany.cn/Article/details/gtuptleils.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.gogol.net.cn/Article/details/gtwbjinzbz.html

TS:   nested.flat();
来源：http://dali.bjfxy.top/Article/details/gtgnqjdwlu.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtdauhjquk.html

Go:   // 手写双层循环
来源：http://dali.dianchejie.cn/Article/details/gtsbwfeodq.html

Ruby: nested.flatten
来源：http://dali.daria6918.cn/Article/details/gtdwanouod.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yuanzhike.top/Article/details/gtboupnueo.html

[D19] 按字段分组
来源：http://dali.nwbrower.top/Article/details/gtqsznmbju.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yongpay.top/Article/details/gtqwnatkry.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shuidangran.top/Article/details/gtwyjouijk.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xziqi.cn/Article/details/gthryurijl.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jlsjyb.cn/Article/details/gtcrcctpgh.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hnqzz.top/Article/details/gtuxscwefz.html

Go:   // 手写 map[string][]T
来源：http://dali.sysykeji.top/Article/details/gtgwxlwudw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.smart0.xyz/Article/details/gtbzscxcmr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jqgfzy.top/Article/details/gtxwbplvcq.html

[D20] 统计每个元素出现次数
来源：http://dali.jyoumei.cn/Article/details/gtxhtqliex.html

Py:   Counter(arr)
来源：http://dali.yj202588.top/Article/details/gtxtopmqfr.html

PHP:  array_count_values($arr);
来源：http://dali.zdqjudy.top/Article/details/gtmkfvxqcg.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hongshengwenyu.top/Article/details/gtfqrgkvfu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.9152youxi.cn/Article/details/gtlxtmauha.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gzhubu.top/Article/details/gthlwswuqx.html

Go:   // 手写 map[T]int
来源：http://dali.ydzc1.top/Article/details/gtfgelaukq.html

Ruby: arr.tally
来源：http://dali.zhixingplan.top/Article/details/gtjtinnarm.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.0kj1m.cn/Article/details/gtykveizbv.html

[D21] 判断是否包含某元素
来源：http://dali.xylfe.cn/Article/details/gtljfzujxx.html

Py:   x in arr
来源：http://dali.jyoumei.cn/Article/details/gtdsguuilh.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hongshengwenyu.top/Article/details/gtpbwgjgqq.html

JS:   arr.includes(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnbkyuaox.html

TS:   arr.includes(x)
来源：http://dali.chenlongwang.top/Article/details/gtivkhaxgn.html

Java: list.contains(x)
来源：http://dali.shuidangran.top/Article/details/gtntqbwkpn.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkabehkbd.html

Ruby: arr.include?(x)
来源：http://dali.jianghu66.top/Article/details/gthyokalys.html

C#:   list.Contains(x)
来源：http://dali.yuxming.cn/Article/details/gtbbjxiesd.html

[D22] 复制数组（避免共享引用）
来源：http://dali.kuanghao11.cn/Article/details/gtxnysppjz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtbquxbxvx.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sxryk.cn/Article/details/gtdytjrzxu.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yangfankeji.com/Article/details/gtincuxgaf.html

TS:   [...arr];
来源：http://dali.yj202588.top/Article/details/gtricfcdxh.html

Java: new ArrayList<>(list);
来源：http://dali.zhongyouzk.top/Article/details/gtblhvdtyg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jyoumei.cn/Article/details/gttdmyacli.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yuxming.cn/Article/details/gtbhgjqqbb.html

C#:   new List<int>(list);
来源：http://dali.c1oappe.top/Article/details/gtnjqdibyy.html

[D23] reduce 累积计算
来源：http://dali.jqgfzy.top/Article/details/gtyjmtbmtr.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.c1oappe.top/Article/details/gtoufwbgqk.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jyoumei.cn/Article/details/gtrhrqeduw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj202588.top/Article/details/gttxpbzwpd.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenzaomai.com/Article/details/gthsmgddcm.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.iojbl.cn/Article/details/gtkdggttjs.html

Go:   // 手写循环
来源：http://dali.jiagoushi.top/Article/details/gtlfzohbgx.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlurirjau.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xuanzx.com/Article/details/gtzucxebyx.html

[D24] 字典 / Map 基本操作
来源：http://dali.jinqigfzy.top/Article/details/gtoinifwva.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ybcxt.top/Article/details/gtskpfggph.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.smart0.xyz/Article/details/gtiwvuoeyl.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shzxlz.cn/Article/details/gtsbfjzapi.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jinqigufen.top/Article/details/gtfonbxazd.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.gzhubu.top/Article/details/gttpsngfpg.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.nanxuanxn.top/Article/details/gtigquxviq.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.tianlin.xyz/Article/details/gtoswqqjtz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjocxqztw.html

[D25] Set 集合去重与交并差
来源：http://dali.zhixingplan.top/Article/details/gtobozmrei.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cucudq.cn/Article/details/gthrxtcvfo.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xziqi.cn/Article/details/gtmpnxdeiz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.chenjidiqi.icu/Article/details/gteradfdeu.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yuxming.cn/Article/details/gtuqfeozjb.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.iojbl.cn/Article/details/gtjxpxcxgb.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinqigufen.top/Article/details/gtufxluafr.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.guowangkeji.top/Article/details/gthaljnrpv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.nwbrower.top/Article/details/gtmukiflum.html

[D26] 数组转字符串
来源：http://dali.sufxvd.cn/Article/details/gtmaezgraw.html

Py:   ", ".join(map(str, arr))
来源：http://dali.pycfn.com/Article/details/gtzgxcoasa.html

PHP:  implode(", ", $arr);
来源：http://dali.yj20258888.top/Article/details/gtsytiqdhi.html

JS:   arr.join(", ")
来源：http://dali.hnxiangtu.top/Article/details/gtrvggerat.html

TS:   arr.join(", ")
来源：http://dali.ivvv.top/Article/details/gtdouenasy.html

Java: String.join(", ", list)
来源：http://dali.cucudq.cn/Article/details/gthlrjahjh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.redwolf501.top/Article/details/gtxlzguhyl.html

Ruby: arr.join(", ")
来源：http://dali.zhiwuduotai.top/Article/details/gtryezmpnf.html

C#:   string.Join(", ", list)
来源：http://dali.nwbrower.top/Article/details/gtvyqwmjzk.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtkvkyvvsn.html

E. 字符串处理
来源：http://dali.daxiang520.top/Article/details/gthkbihinc.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtaomaahjm.html

[E01] 拼接字符串
来源：http://dali.xylfe.cn/Article/details/gtknxzxtug.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yanxiufei.cn/Article/details/gtdfjiahym.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.sweek.top/Article/details/gtvseizfcy.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtsvgnaflr.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jqgfzy.top/Article/details/gtcphbnqic.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.kuanghao11.cn/Article/details/gtidtuvspv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.daxiang520.top/Article/details/gthcncglei.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.dianchejie.cn/Article/details/gtkgpcylvp.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvopfpcmw.html

[E02] 重复字符串
来源：http://dali.yj20258.top/Article/details/gtfriqfewt.html

Py:   "ab" * 3
来源：http://dali.jinqigufen.top/Article/details/gtlsmltikh.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yongpay.top/Article/details/gtpdktkdbj.html

JS:   "ab".repeat(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqvpazqfb.html

TS:   "ab".repeat(3)
来源：http://dali.daxiang520.top/Article/details/gtelbnarew.html

Java: "ab".repeat(3)
来源：http://dali.jianghu66.top/Article/details/gtfjftnpmx.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yonumen.top/Article/details/gtamytazxa.html

Ruby: "ab" * 3
来源：http://dali.shuidangran.top/Article/details/gtucstcjjg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.pengpengdd.cyou/Article/details/gtrhkgprif.html

[E03] 截取子串
来源：http://dali.hnqzz.top/Article/details/gtoxuevnlx.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ybcxt.top/Article/details/gtisgwflxs.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gtoknrpscw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.wangshuangyany.cn/Article/details/gttugdzukj.html

TS:   s.slice(1, 4)
来源：http://dali.daxiang520.top/Article/details/gtisigxlhs.html

Java: s.substring(1, 4)
来源：http://dali.c1oappe.top/Article/details/gtnpoddtrd.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.tianlin.xyz/Article/details/gtjklsgnrv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.chenjidiqi.icu/Article/details/gtatdejkfs.html

C#:   s.Substring(1, 3)
来源：http://dali.dianchejie.cn/Article/details/gtqunwzvww.html

[E04] 查找子串位置
来源：http://dali.guannengcc.top/Article/details/gtpqnzdgnm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.pycfn.com/Article/details/gtuseujuhb.html


<!-- 参考信息 -->