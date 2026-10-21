代发 wailian999

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ppjwa.cn/Article/details/gtjitqcpxj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.bjfxy.top/Article/details/gtuquxhlgn.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.aizwys.cn/Article/details/gtrlxubwjq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tanke756.top/Article/details/gtxxedzmrl.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtmkhymmjk.html

Go:   func add(a, b int) int
来源：http://dali.sysykeji.top/Article/details/gtlegwgckv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.0kj1m.cn/Article/details/gttgsmhwxg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.bjfxy.top/Article/details/gtgwhikpub.html

[C14] 泛型函数
来源：http://dali.wangshuangyany.cn/Article/details/gtivjxglhm.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.snrcjt.cn/Article/details/gtrkazabck.html

PHP:  // 无泛型
来源：http://dali.redwolf501.top/Article/details/gthaxcprmx.html

JS:   // 无泛型
来源：http://dali.tian-w.cn/Article/details/gtltsrdphy.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shzxlz.cn/Article/details/gtwsypykik.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhiwuduotai.top/Article/details/gtretojaft.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.pycfn.com/Article/details/gtbowwjrfz.html

Ruby: # 无泛型
来源：http://dali.iojbl.cn/Article/details/gtsqboctsc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jyoumei.cn/Article/details/gtutmncfit.html

[C15] 解构 / 展开参数
来源：http://dali.shzxlz.cn/Article/details/gttxvqdvvh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.sufxvd.cn/Article/details/gtofqnyjab.html

PHP:  [$a, $b] = $pair;
来源：http://dali.meibo888.top/Article/details/gtkmddzxhv.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cashguo.top/Article/details/gtnblqdkgt.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.316326.xyz/Article/details/gtqegptqtg.html

Java: // 无解构
来源：http://dali.jqgufenzy.top/Article/details/gtcvvzysis.html

Go:   // 无解构
来源：http://dali.gotoacloud.top/Article/details/gtutneqsro.html

Ruby: a, b = pair
来源：http://dali.tanke756.top/Article/details/gtawhbwllj.html

C#:   var (a, b) = pair;
来源：http://dali.havefunace.top/Article/details/gtrywtklum.html

[C16] 函数 / 方法重载
来源：http://dali.shuidangran.top/Article/details/gtrkdvavbt.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.gaohongyu789.top/Article/details/gtoiqvpedw.html

PHP:  // 无重载
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmkrvjufs.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.wangshuangyany.cn/Article/details/gtlortqedp.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.tanke756.top/Article/details/gtwvkjybie.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yueranfly.top/Article/details/gtfwogimeg.html

Go:   // 无重载：用不同函数名
来源：http://dali.quarkkingdee.top/Article/details/gtueyiulgu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jqgfzy.top/Article/details/gtkovjwmct.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.wangdashe.top/Article/details/gtfvhdynit.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtnmnzoecu.html

D. 数组 / 列表 / 集合
来源：http://dali.zycfv.cn/Article/details/gtdbctnuvo.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtigileksq.html

[D01] 创建数组 / 列表
来源：http://dali.shzxlz.cn/Article/details/gtachvgvor.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jqgufenzy.top/Article/details/gtvogwmrqz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yuxming.cn/Article/details/gtjewykckt.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jianghu66.top/Article/details/gtinidkxlf.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ydzc1.top/Article/details/gtuxdysjve.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.gaohongyu789.top/Article/details/gtkyvlrhbc.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shuidangran.top/Article/details/gtahfphkgu.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhoulong.xyz/Article/details/gtjxavvhda.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hfpthk.cn/Article/details/gtnhkdmhzr.html

[D02] 追加元素到末尾
来源：http://dali.jianghu66.top/Article/details/gtaffzmzti.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cheryme.top/Article/details/gtfutobcqn.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.svipenyu.cn/Article/details/gtdinxdbuc.html

JS:   arr.push(4);
来源：http://dali.jiagoushi.top/Article/details/gtismefrjw.html

TS:   arr.push(4);
来源：http://dali.cheryme.top/Article/details/gtkncudadp.html

Java: list.add(4);
来源：http://dali.yj202588.top/Article/details/gtunluvhyb.html

Go:   arr = append(arr, 4)
来源：http://dali.pycfn.com/Article/details/gtsxeoojhu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.haohaochexian.top/Article/details/gtybpumkdp.html

C#:   list.Add(4);
来源：http://dali.yj20258.top/Article/details/gtsnwurjis.html

[D03] 在指定位置插入元素
来源：http://dali.chenlongwang.top/Article/details/gtvgkngiar.html

Py:   arr.insert(0, 0)
来源：http://dali.aizwys.cn/Article/details/gtzmeqjwhf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.daxiang520.top/Article/details/gtsknbmrjz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shangyingyoupin.top/Article/details/gtufudrxcr.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.pycfn.com/Article/details/gtcpaipcqt.html

Java: list.add(0, 0);
来源：http://dali.yueranfly.top/Article/details/gtsbhfqmyq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.gotoacloud.top/Article/details/gtcawnchir.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.dashuyun.cn/Article/details/gtpsfiqirk.html

C#:   list.Insert(0, 0);
来源：http://dali.birdmap.top/Article/details/gtqgfhxqhf.html

[D04] 删除元素
来源：http://dali.nwbrower.top/Article/details/gtytplpiqt.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.nanxuanxn.top/Article/details/gtldwtqmvd.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.smart0.xyz/Article/details/gtizvpdzeu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuajxfjdz.html

TS:   arr.splice(0, 1);
来源：http://dali.nwbrower.top/Article/details/gtniwduiry.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.nwbrower.top/Article/details/gtrmtrzvab.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hongshengwenyu.top/Article/details/gtakdvivkp.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.gotoacloud.top/Article/details/gtcjrbmcpy.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ydzc1.top/Article/details/gtkznfxmoz.html

[D05] 访问与修改元素
来源：http://dali.nanxuanxn.top/Article/details/gtylwylluh.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ivvv.top/Article/details/gtgffdxcsb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cucudq.cn/Article/details/gtkmiuotno.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.sufxvd.cn/Article/details/gtbyxrqwbc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cashguo.top/Article/details/gtifqtolcm.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zycfv.cn/Article/details/gtgvjkwuvb.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cqqwz.cn/Article/details/gtfiqugsss.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yvedp.cn/Article/details/gthhcpihew.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinghuilouyu.cn/Article/details/gtoswtowfp.html

[D06] 数组长度
来源：http://dali.zycfv.cn/Article/details/gtqrssduxo.html

Py:   len(arr)
来源：http://dali.guowangkeji.top/Article/details/gtgiaamzxo.html

PHP:  count($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtbjdfwpue.html

JS:   arr.length
来源：http://dali.feifeiyinyue.top/Article/details/gtanktowwa.html

TS:   arr.length
来源：http://dali.zycfv.cn/Article/details/gtxsomjezg.html

Java: list.size();
来源：http://dali.haohaochexian.top/Article/details/gtetutxggg.html

Go:   len(arr)
来源：http://dali.xuanzx.com/Article/details/gtbglfyvrm.html

Ruby: arr.length; arr.size
来源：http://dali.gaohongyu789.top/Article/details/gtdinrxeys.html

C#:   list.Count;
来源：http://dali.feifeiyinyue.top/Article/details/gtfsldpvze.html

[D07] 切片 / 取子数组
来源：http://dali.haohaochexian.top/Article/details/gtllxnptal.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jyoumei.cn/Article/details/gtkkhynzcg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jinqigfzy.top/Article/details/gtvczfqwnn.html

JS:   arr.slice(1, 4);
来源：http://dali.sxryk.cn/Article/details/gtacdntlfp.html

TS:   arr.slice(1, 4);
来源：http://dali.redwolf501.top/Article/details/gtlovhlabu.html

Java: list.subList(1, 4);
来源：http://dali.hnxiangtu.top/Article/details/gtxagqaigq.html

Go:   arr[1:4]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtultgxbsf.html

Ruby: arr[1, 3]
来源：http://dali.xuetiantiany.cn/Article/details/gtvhveumzj.html

C#:   list.GetRange(1, 3);
来源：http://dali.meibo888.top/Article/details/gtmsejzvrj.html

[D08] 合并两个数组
来源：http://dali.hnxiangtu.top/Article/details/gtjurdpuyy.html

Py:   a + b;  a.extend(b)
来源：http://dali.bjfxy.top/Article/details/gtdziyglpf.html

PHP:  array_merge($a, $b);
来源：http://dali.xuetiantiany.cn/Article/details/gtawqgotyt.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sweek.top/Article/details/gtgjmohhar.html

TS:   [...a, ...b];
来源：http://dali.yongpay.top/Article/details/gtrxtyfgbk.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.vqdsnc.cn/Article/details/gtlpwgtsma.html

Go:   append(a, b...)
来源：http://dali.pengpengdd.cyou/Article/details/gtnrdpnrxn.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yuanzhike.top/Article/details/gtobuhjwcw.html

C#:   a.Concat(b).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtfxujqhuz.html

[D09] 排序（升序）
来源：http://dali.xylfe.cn/Article/details/gtgavhvupy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gotoacloud.top/Article/details/gtpkqbpfio.html

PHP:  sort($arr);
来源：http://dali.ppjwa.cn/Article/details/gtoljakrdc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.0kj1m.cn/Article/details/gtyapfsedr.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hywenlv.cn/Article/details/gtkxlqydtk.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jianghu66.top/Article/details/gtcsupxqbu.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.tanke756.top/Article/details/gtsbgvnton.html

Ruby: arr.sort
来源：http://dali.jinghuilouyu.cn/Article/details/gtrvviwncj.html

C#:   list.Sort();
来源：http://dali.redwolf501.top/Article/details/gtjniklyrk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.smart0.xyz/Article/details/gtzzbzrjov.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.tanke756.top/Article/details/gtvyrxxaug.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cheryme.top/Article/details/gtkbfzoyqy.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.0kj1m.cn/Article/details/gtxlskzejl.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cashguo.top/Article/details/gttwzbgavz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shzxlz.cn/Article/details/gthfuzzsrl.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.wangdashe.top/Article/details/gtuivvdfqr.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.kuanghao11.cn/Article/details/gtsnfdtbui.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jinqigufen.top/Article/details/gtqsujbvdq.html

[D11] 反转数组
来源：http://dali.cashguo.top/Article/details/gtqlziwgro.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gtqufufssy.html

PHP:  array_reverse($arr);
来源：http://dali.hysaishi.cn/Article/details/gtldhbdram.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shanyushiyangtech.top/Article/details/gtwerjxpks.html

TS:   [...arr].reverse();
来源：http://dali.quarkkingdee.top/Article/details/gtupfuhgfg.html

Java: Collections.reverse(list);
来源：http://dali.hnqzz.top/Article/details/gtsrfitewt.html

Go:   slices.Reverse(arr)
来源：http://dali.hywenlv.cn/Article/details/gtywyrcbnz.html

Ruby: arr.reverse
来源：http://dali.zdqjudy.top/Article/details/gtqzyodtvk.html

C#:   list.Reverse();
来源：http://dali.ybcxt.top/Article/details/gtysfawusz.html

[D12] 查找元素下标
来源：http://dali.dianchejie.cn/Article/details/gtkrobzjfv.html

Py:   arr.index(x);  x in arr
来源：http://dali.yanxiufei.cn/Article/details/gtdvbhkumr.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.meibo888.top/Article/details/gtpxbeelyg.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.snrcjt.cn/Article/details/gtopvinlqj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.c1oappe.top/Article/details/gtnokdsadx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.tian-w.cn/Article/details/gtfjxetjxv.html

Go:   slices.Index(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gtrvtqrtel.html

Ruby: arr.index(x)
来源：http://dali.xinyue.icu/Article/details/gteckgdjmk.html

C#:   list.IndexOf(x);
来源：http://dali.jiagoushi.top/Article/details/gtxaomzzgj.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xuanzx.com/Article/details/gtjdlqygax.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yuxming.cn/Article/details/gtuiumkljo.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.tianlin.xyz/Article/details/gtjsxojgbp.html

JS:   arr.filter(x => x > 3)
来源：http://dali.c1oappe.top/Article/details/gtxmkvjqyo.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hysaishi.cn/Article/details/gtllatcbsz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.gogol.net.cn/Article/details/gtvbkhelba.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.dianchejie.cn/Article/details/gtzaqvboju.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hammf.cn/Article/details/gtcxllsncl.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtdmypjgyz.html

[D14] 映射转换（每个元素变形）
来源：http://dali.gaohongyu789.top/Article/details/gtffnpsqss.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.c1oappe.top/Article/details/gtdxabivyo.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtectkxnhj.html

JS:   arr.map(x => x * 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtsjjwwfst.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzzbuhmku.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.redwolf501.top/Article/details/gtmuxrkoam.html

Go:   // 手写循环
来源：http://dali.kuanghao11.cn/Article/details/gtsszbmcjk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvlskqoiu.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yj20258888.top/Article/details/gtjsqdotar.html

[D15] 去重
来源：http://dali.jianghu66.top/Article/details/gtubuucdca.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.nanxuanxn.top/Article/details/gtbadyufvt.html

PHP:  array_unique($arr);
来源：http://dali.pycfn.com/Article/details/gtaxnizvtt.html

JS:   [...new Set(arr)]
来源：http://dali.fzhhl.top/Article/details/gtwityrfxq.html

TS:   [...new Set(arr)]
来源：http://dali.aizwys.cn/Article/details/gtsuxxojef.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.havefunace.top/Article/details/gtvmvcewua.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shuidangran.top/Article/details/gtrprxihcb.html

Ruby: arr.uniq
来源：http://dali.fengsongda.top/Article/details/gtyqsncwdq.html

C#:   list.Distinct().ToList()
来源：http://dali.316326.xyz/Article/details/gtkjaoheem.html

[D16] 求和与平均值
来源：http://dali.daxiang520.top/Article/details/gthtflkyvr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xuanzx.com/Article/details/gtxmolqxuu.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xziqi.cn/Article/details/gtmcjjqgfs.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtluvxovwq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yangfankeji.com/Article/details/gtbysgzbjr.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xuetiantiany.cn/Article/details/gtwdrufajr.html

Go:   // 手写循环累加
来源：http://dali.svipenyu.cn/Article/details/gtscwxlovw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.tian-w.cn/Article/details/gtjgjiogjf.html

C#:   list.Sum();  list.Average()
来源：http://dali.ehwqpu.com/Article/details/gtpxfaqfkj.html

[D17] 最大值与最小值
来源：http://dali.yj202588.top/Article/details/gtwmniqgml.html

Py:   max(arr);  min(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtkvyldrma.html

PHP:  max($arr);  min($arr);
来源：http://dali.hysaishi.cn/Article/details/gttpcplzrs.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jlsjyb.cn/Article/details/gtjcgxoxyv.html

TS:   Math.max(...arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtvmqznuzm.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hfpthk.cn/Article/details/gtnfepibfp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hywenlv.cn/Article/details/gtfojribff.html

Ruby: arr.max;  arr.min
来源：http://dali.vqdsnc.cn/Article/details/gtotkcketc.html

C#:   list.Max();  list.Min()
来源：http://dali.zdqjudy.top/Article/details/gttjdhwmno.html

[D18] 扁平化嵌套数组
来源：http://dali.redwolf501.top/Article/details/gtyxmyqkyt.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.havefunace.top/Article/details/gtmffxhvue.html

PHP:  array_merge(...$nested);
来源：http://dali.jianghu66.top/Article/details/gtbtwfgfvr.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jlsjyb.cn/Article/details/gtimvnhkoe.html

TS:   nested.flat();
来源：http://dali.jqgufenzy.top/Article/details/gtpltlrytf.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sufxvd.cn/Article/details/gtulduseil.html

Go:   // 手写双层循环
来源：http://dali.chenjidiqi.icu/Article/details/gtwmpcyhrs.html

Ruby: nested.flatten
来源：http://dali.ydzc1.top/Article/details/gtxzwpysbh.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gtolhajtwx.html

[D19] 按字段分组
来源：http://dali.havefunace.top/Article/details/gthfabxery.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gzhubu.top/Article/details/gtgnixfqxh.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.c1oappe.top/Article/details/gtszsiudny.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.quarkkingdee.top/Article/details/gtpmnpatzl.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jqgfzy.top/Article/details/gtcikdkajm.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hnqzz.top/Article/details/gtraknvoxr.html

Go:   // 手写 map[string][]T
来源：http://dali.cqqwz.cn/Article/details/gtdayeinsk.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.tanke756.top/Article/details/gtkhnntiwi.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjnwchylz.html

[D20] 统计每个元素出现次数
来源：http://dali.gogol.net.cn/Article/details/gtqjknxgmh.html

Py:   Counter(arr)
来源：http://dali.gotoacloud.top/Article/details/gtczjhjdza.html

PHP:  array_count_values($arr);
来源：http://dali.guannengcc.top/Article/details/gtxbuvhahs.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.wangdashe.top/Article/details/gtmgruywod.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yanxiufei.cn/Article/details/gtvfdainzq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.wangshuangyany.cn/Article/details/gtkdftvpbh.html

Go:   // 手写 map[T]int
来源：http://dali.bjfxy.top/Article/details/gthtahrjxk.html

Ruby: arr.tally
来源：http://dali.sufxvd.cn/Article/details/gtxyugkzgh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sysykeji.top/Article/details/gtedxgmhtz.html

[D21] 判断是否包含某元素
来源：http://dali.cashguo.top/Article/details/gtkblkjego.html

Py:   x in arr
来源：http://dali.yj202588.top/Article/details/gtpuzksvrx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.andypj.xyz/Article/details/gtgvxpfvom.html

JS:   arr.includes(x)
来源：http://dali.bjfxy.top/Article/details/gtptvfougr.html

TS:   arr.includes(x)
来源：http://dali.gzhubu.top/Article/details/gttviunrvp.html

Java: list.contains(x)
来源：http://dali.kuanghao11.cn/Article/details/gtebapypwe.html

Go:   slices.Contains(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtglbvbhmw.html

Ruby: arr.include?(x)
来源：http://dali.c1oappe.top/Article/details/gtcukzifsc.html

C#:   list.Contains(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtrjrquxkx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.birdmap.top/Article/details/gthncmzqwb.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.guowangkeji.top/Article/details/gtnlftzedp.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.316326.xyz/Article/details/gthvsgdjie.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.snrcjt.cn/Article/details/gtuzolwhda.html

TS:   [...arr];
来源：http://dali.gotoacloud.top/Article/details/gtzdnurntk.html

Java: new ArrayList<>(list);
来源：http://dali.jyoumei.cn/Article/details/gtdngesxwf.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.aizwys.cn/Article/details/gtumqavwur.html

Ruby: arr.dup;  arr.clone
来源：http://dali.bjfxy.top/Article/details/gtbpiwxqcr.html

C#:   new List<int>(list);
来源：http://dali.fzhhl.top/Article/details/gtzqrdffoh.html

[D23] reduce 累积计算
来源：http://dali.xylfe.cn/Article/details/gtatvpvmol.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cheryme.top/Article/details/gtkwpugait.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtrndngfgp.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guowangkeji.top/Article/details/gtosyxgieb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgxhdipot.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.dianchejie.cn/Article/details/gtrgladlvu.html

Go:   // 手写循环
来源：http://dali.sysykeji.top/Article/details/gtuboxzlbl.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xuetiantiany.cn/Article/details/gtizkcnylt.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hfpthk.cn/Article/details/gtmbsfwabs.html

[D24] 字典 / Map 基本操作
来源：http://dali.dianchejie.cn/Article/details/gtfmxhiuku.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jinqigufen.top/Article/details/gtzpioxxrd.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ydzc1.top/Article/details/gtrozfbbak.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhengqikj.top/Article/details/gtqhdxtufo.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yueranfly.top/Article/details/gtesuhaxgq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.dianchejie.cn/Article/details/gtdbcxvlks.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jqgfzy.top/Article/details/gticrcrirr.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhiwuduotai.top/Article/details/gtlcenexcs.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gtzxstyoxv.html

[D25] Set 集合去重与交并差
来源：http://dali.snrcjt.cn/Article/details/gtnavkdtts.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jiagoushi.top/Article/details/gtlhjovvzt.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shzxlz.cn/Article/details/gtvslfvirq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.nanxuanxn.top/Article/details/gthynglgox.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hfpthk.cn/Article/details/gtrxswruny.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yangfankeji.com/Article/details/gtowjnusqk.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gtdjzdxrum.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hywenlv.cn/Article/details/gtopkscntu.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.dianchejie.cn/Article/details/gtsavwofst.html

[D26] 数组转字符串
来源：http://dali.zycfv.cn/Article/details/gtmlflgjjq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.guowangkeji.top/Article/details/gtrlhqhcer.html

PHP:  implode(", ", $arr);
来源：http://dali.yuxming.cn/Article/details/gtnksfgzqq.html

JS:   arr.join(", ")
来源：http://dali.shzxlz.cn/Article/details/gtmbyhjvir.html

TS:   arr.join(", ")
来源：http://dali.iojbl.cn/Article/details/gtnmfpcuyl.html

Java: String.join(", ", list)
来源：http://dali.hfpthk.cn/Article/details/gtitvbycpj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jqgfzy.top/Article/details/gtxrkzwcup.html

Ruby: arr.join(", ")
来源：http://dali.cqqwz.cn/Article/details/gtjoferzja.html

C#:   string.Join(", ", list)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjgjkgvgw.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtwgoszyft.html

E. 字符串处理
来源：http://dali.gzhubu.top/Article/details/gtenrehbia.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtlxeokdkd.html

[E01] 拼接字符串
来源：http://dali.hnxiangtu.top/Article/details/gtqrdllxat.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.vqdsnc.cn/Article/details/gtojduluds.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.sufxvd.cn/Article/details/gtrymdaqqs.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.svipenyu.cn/Article/details/gtylcqznon.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daria6918.cn/Article/details/gtptlxpwyx.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hammf.cn/Article/details/gtgarikjvd.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ehwqpu.com/Article/details/gtzkjkhdzt.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.chenjidiqi.icu/Article/details/gtexpbpphd.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gtdtzmxkam.html

[E02] 重复字符串
来源：http://dali.mhx1999.top/Article/details/gtkgvlhjbv.html

Py:   "ab" * 3
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtogdpamjd.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cdnleiting.top/Article/details/gtngulxfgn.html

JS:   "ab".repeat(3)
来源：http://dali.aibaodan.cn/Article/details/gtecuqxdrm.html

TS:   "ab".repeat(3)
来源：http://dali.bjfxy.top/Article/details/gtuapecsqh.html

Java: "ab".repeat(3)
来源：http://dali.cdnleiting.top/Article/details/gtwepxkmmb.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.wangshuangyany.cn/Article/details/gtxwvfznrr.html

Ruby: "ab" * 3
来源：http://dali.yangfankeji.com/Article/details/gthfcslomn.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.snrcjt.cn/Article/details/gtaqzkmdju.html

[E03] 截取子串
来源：http://dali.hywenlv.cn/Article/details/gtxlnustpg.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hammf.cn/Article/details/gthiopdmol.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gtbmgpotev.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ydzc1.top/Article/details/gtkeotqoit.html

TS:   s.slice(1, 4)
来源：http://dali.hammf.cn/Article/details/gteyznyyhn.html

Java: s.substring(1, 4)
来源：http://dali.0kj1m.cn/Article/details/gtuwgqdiqk.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.mhx1999.top/Article/details/gtbwsrxkfi.html


<!-- 参考信息 -->