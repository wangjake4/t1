代发 wailian999

Java: int add(int a, int b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gtepjeqsfj.html

Go:   func add(a, b int) int
来源：http://dali.jyoumei.cn/Article/details/gtrzaijmfj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yongpay.top/Article/details/gtmfxwxpbt.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hfpthk.cn/Article/details/gtirurygxw.html

[C14] 泛型函数
来源：http://dali.ppjwa.cn/Article/details/gtupwrqwwa.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.c1oappe.top/Article/details/gtdeqgnodb.html

PHP:  // 无泛型
来源：http://dali.sysykeji.top/Article/details/gtgubnghtm.html

JS:   // 无泛型
来源：http://dali.xuetiantiany.cn/Article/details/gtmjcklhjp.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.kuanghao11.cn/Article/details/gthejbcwox.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.tanke756.top/Article/details/gtfhxoqshy.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.wangdashe.top/Article/details/gtvzwmlvgc.html

Ruby: # 无泛型
来源：http://dali.yuxming.cn/Article/details/gtmqwlqlyg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.haohaochexian.top/Article/details/gtozubboru.html

[C15] 解构 / 展开参数
来源：http://dali.tanke756.top/Article/details/gtexwwlrdp.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hfpthk.cn/Article/details/gtxsyeibkr.html

PHP:  [$a, $b] = $pair;
来源：http://dali.pengpengdd.cyou/Article/details/gtzyztxais.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcbgfecim.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ppjwa.cn/Article/details/gtlzrsmoaz.html

Java: // 无解构
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjupfzion.html

Go:   // 无解构
来源：http://dali.tanke756.top/Article/details/gtvbkmgvwj.html

Ruby: a, b = pair
来源：http://dali.sxryk.cn/Article/details/gtehdldprb.html

C#:   var (a, b) = pair;
来源：http://dali.fengsongda.top/Article/details/gtkeoipbya.html

[C16] 函数 / 方法重载
来源：http://dali.jqgufenzy.top/Article/details/gtzfwhlism.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yj20258.top/Article/details/gtyybwdslp.html

PHP:  // 无重载
来源：http://dali.chenjidiqi.icu/Article/details/gtnqtrrfdw.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zycfv.cn/Article/details/gtovseknbc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.snrcjt.cn/Article/details/gtqhfkvzmq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.havefunace.top/Article/details/gtlkhzcmhm.html

Go:   // 无重载：用不同函数名
来源：http://dali.jqgufenzy.top/Article/details/gtarazgxox.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jyoumei.cn/Article/details/gtwlsskwtv.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gtmpghjtey.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtrucxynhr.html

D. 数组 / 列表 / 集合
来源：http://dali.hnqzz.top/Article/details/gtzodmkycf.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtlgevyqiy.html

[D01] 创建数组 / 列表
来源：http://dali.zhixingplan.top/Article/details/gtvowlgnub.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yuxming.cn/Article/details/gtlddukmxd.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.bjfxy.top/Article/details/gtoohynhvo.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.havefunace.top/Article/details/gtbvhikrsr.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shzxlz.cn/Article/details/gtbcgauvxn.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.snrcjt.cn/Article/details/gtcawhxqoo.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xinyue.icu/Article/details/gteizpgsqs.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jinqigufen.top/Article/details/gtnpxocead.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhixingplan.top/Article/details/gtyypouxlk.html

[D02] 追加元素到末尾
来源：http://dali.jyoumei.cn/Article/details/gtjhynriol.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hfpthk.cn/Article/details/gtiipholrq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gzhubu.top/Article/details/gtqaarllnj.html

JS:   arr.push(4);
来源：http://dali.tianlin.xyz/Article/details/gtuiwjwtln.html

TS:   arr.push(4);
来源：http://dali.meibo888.top/Article/details/gtbrvxhqvt.html

Java: list.add(4);
来源：http://dali.yj20258888.top/Article/details/gtinxkxbnz.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gtswhtysvy.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxtdaibau.html

C#:   list.Add(4);
来源：http://dali.havefunace.top/Article/details/gthjuzlewh.html

[D03] 在指定位置插入元素
来源：http://dali.xuanzx.com/Article/details/gtbshliike.html

Py:   arr.insert(0, 0)
来源：http://dali.iojbl.cn/Article/details/gtvhmbolhh.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yueranfly.top/Article/details/gtjtmvdufu.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.wangdashe.top/Article/details/gtjuxcgmjj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cdnleiting.top/Article/details/gtqnyjfybg.html

Java: list.add(0, 0);
来源：http://dali.yj20258.top/Article/details/gthdeaywoh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.nanxuanxn.top/Article/details/gtsuawmhww.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.iojbl.cn/Article/details/gtxguvuovb.html

C#:   list.Insert(0, 0);
来源：http://dali.yuxming.cn/Article/details/gthllymprd.html

[D04] 删除元素
来源：http://dali.yvedp.cn/Article/details/gtcbubccay.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.haohaochexian.top/Article/details/gtsmokymkb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.redwolf501.top/Article/details/gtbqyrxptk.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.haohaochexian.top/Article/details/gtigzyxhnu.html

TS:   arr.splice(0, 1);
来源：http://dali.bjfxy.top/Article/details/gtnyjhviby.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ehwqpu.com/Article/details/gtowmrrfqq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xylfe.cn/Article/details/gtgschrzdh.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gttlwslniq.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hfpthk.cn/Article/details/gtoufvedlv.html

[D05] 访问与修改元素
来源：http://dali.hnqzz.top/Article/details/gtnzijdgcy.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shzxlz.cn/Article/details/gtlcfjvnam.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmmhuhexf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shanyushiyangtech.top/Article/details/gtfvtcjwch.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.havefunace.top/Article/details/gtotnccxaa.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.nwbrower.top/Article/details/gthvusrnnk.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hysaishi.cn/Article/details/gtzdqnmsol.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.mhx1999.top/Article/details/gtomsrhsip.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xuetiantiany.cn/Article/details/gtpmrdhhvz.html

[D06] 数组长度
来源：http://dali.sysykeji.top/Article/details/gtuhgvvkse.html

Py:   len(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnneihbkn.html

PHP:  count($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtdsaclyov.html

JS:   arr.length
来源：http://dali.iojbl.cn/Article/details/gtvenwuwhd.html

TS:   arr.length
来源：http://dali.jlsjyb.cn/Article/details/gtqimuwrdw.html

Java: list.size();
来源：http://dali.zhiwuduotai.top/Article/details/gtiduyimee.html

Go:   len(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtayihviag.html

Ruby: arr.length; arr.size
来源：http://dali.mhx1999.top/Article/details/gtgglsisna.html

C#:   list.Count;
来源：http://dali.quarkkingdee.top/Article/details/gtmtcibmtk.html

[D07] 切片 / 取子数组
来源：http://dali.yj20258.top/Article/details/gtjkogxquy.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jiagoushi.top/Article/details/gtzbnfyqfc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ydzc1.top/Article/details/gtjxhqanav.html

JS:   arr.slice(1, 4);
来源：http://dali.nanxuanxn.top/Article/details/gtndymhckq.html

TS:   arr.slice(1, 4);
来源：http://dali.jiagoushi.top/Article/details/gtnoyxysip.html

Java: list.subList(1, 4);
来源：http://dali.cashguo.top/Article/details/gthwmadqhh.html

Go:   arr[1:4]
来源：http://dali.hnxiangtu.top/Article/details/gtszgccajw.html

Ruby: arr[1, 3]
来源：http://dali.cheryme.top/Article/details/gticjvpkim.html

C#:   list.GetRange(1, 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtkzbcqcez.html

[D08] 合并两个数组
来源：http://dali.shangyingyoupin.top/Article/details/gtwhfshfmh.html

Py:   a + b;  a.extend(b)
来源：http://dali.yj202588.top/Article/details/gtahcnhzwa.html

PHP:  array_merge($a, $b);
来源：http://dali.gogol.net.cn/Article/details/gtwueemhtn.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.birdmap.top/Article/details/gtcgjmzmpp.html

TS:   [...a, ...b];
来源：http://dali.kuanghao11.cn/Article/details/gtfdoghlnf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xinyue.icu/Article/details/gtemcpibck.html

Go:   append(a, b...)
来源：http://dali.ppjwa.cn/Article/details/gtoiitcjkl.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cucudq.cn/Article/details/gthlmrguue.html

C#:   a.Concat(b).ToList()
来源：http://dali.cqqwz.cn/Article/details/gtzlzyzlti.html

[D09] 排序（升序）
来源：http://dali.cashguo.top/Article/details/gtkzufpjgp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hfpthk.cn/Article/details/gttulclzgt.html

PHP:  sort($arr);
来源：http://dali.smart0.xyz/Article/details/gtxpobzrfz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.gaohongyu789.top/Article/details/gtzryusrma.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.sufxvd.cn/Article/details/gtohyvznhn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gaohongyu789.top/Article/details/gtemzvpcys.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zdqjudy.top/Article/details/gthhuzsbuq.html

Ruby: arr.sort
来源：http://dali.gzhubu.top/Article/details/gtgyfqimjt.html

C#:   list.Sort();
来源：http://dali.birdmap.top/Article/details/gtwadoespb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hammf.cn/Article/details/gttejgmlbw.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.wangshuangyany.cn/Article/details/gtbmqnlnfy.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.316326.xyz/Article/details/gthjppffpu.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xuetiantiany.cn/Article/details/gtanrcotah.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.redwolf501.top/Article/details/gtorfqxjgb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jinqigufen.top/Article/details/gtxbabtcxb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yuxming.cn/Article/details/gtgpmcbuyj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.vqdsnc.cn/Article/details/gtyxrarcka.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.gotoacloud.top/Article/details/gtlajdnwiq.html

[D11] 反转数组
来源：http://dali.hfpthk.cn/Article/details/gtwaintbyf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yvedp.cn/Article/details/gtmhgqaauc.html

PHP:  array_reverse($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpzerbrtu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.daxiang520.top/Article/details/gtizrffmxv.html

TS:   [...arr].reverse();
来源：http://dali.shzxlz.cn/Article/details/gtqdympouy.html

Java: Collections.reverse(list);
来源：http://dali.xuanzx.com/Article/details/gtpfrpmioj.html

Go:   slices.Reverse(arr)
来源：http://dali.meibo888.top/Article/details/gtwaegphkw.html

Ruby: arr.reverse
来源：http://dali.yongpay.top/Article/details/gtkmmokuku.html

C#:   list.Reverse();
来源：http://dali.hfpthk.cn/Article/details/gtyhihuyuy.html

[D12] 查找元素下标
来源：http://dali.wangdashe.top/Article/details/gtfqzufgxe.html

Py:   arr.index(x);  x in arr
来源：http://dali.316326.xyz/Article/details/gtpvjsbwpz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.snrcjt.cn/Article/details/gtqpcxuhcm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cashguo.top/Article/details/gtzynejnou.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pycfn.com/Article/details/gtdqgvnkee.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtphhjychr.html

Go:   slices.Index(arr, x)
来源：http://dali.xziqi.cn/Article/details/gtkidiksza.html

Ruby: arr.index(x)
来源：http://dali.ybcxt.top/Article/details/gtulczojlc.html

C#:   list.IndexOf(x);
来源：http://dali.yuxming.cn/Article/details/gtazcbshja.html

[D13] 过滤（保留满足条件的）
来源：http://dali.vqdsnc.cn/Article/details/gtupzxnrgr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.snrcjt.cn/Article/details/gtsxglktzq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.dianchejie.cn/Article/details/gtibotadcx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.meibo888.top/Article/details/gtnuwpifwd.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxvtdmhyr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ydzc1.top/Article/details/gtfpxtgjtw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xinyue.icu/Article/details/gtyynvkfac.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jiagoushi.top/Article/details/gtqqaxdzml.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zycfv.cn/Article/details/gtoumtwpoq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.0kj1m.cn/Article/details/gtkaboaroz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shzxlz.cn/Article/details/gteeoijzjn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsfllboqy.html

JS:   arr.map(x => x * 2)
来源：http://dali.yuxming.cn/Article/details/gtxmijzdvt.html

TS:   arr.map(x => x * 2)
来源：http://dali.shzxlz.cn/Article/details/gtazdsmukm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtkwwotpsz.html

Go:   // 手写循环
来源：http://dali.mhx1999.top/Article/details/gtprubqrlc.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ydzc1.top/Article/details/gtbrubtxyv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtuenojzud.html

[D15] 去重
来源：http://dali.cashguo.top/Article/details/gtmxqehiee.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmxwdxbab.html

PHP:  array_unique($arr);
来源：http://dali.shuidangran.top/Article/details/gtjfmasokh.html

JS:   [...new Set(arr)]
来源：http://dali.hfpthk.cn/Article/details/gtwksgajgr.html

TS:   [...new Set(arr)]
来源：http://dali.redwolf501.top/Article/details/gtrcazurtr.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.quarkkingdee.top/Article/details/gtltyelmrg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.nwbrower.top/Article/details/gtoacpozgd.html

Ruby: arr.uniq
来源：http://dali.smart0.xyz/Article/details/gtwghltzic.html

C#:   list.Distinct().ToList()
来源：http://dali.yuxming.cn/Article/details/gtgssmrxon.html

[D16] 求和与平均值
来源：http://dali.bjfxy.top/Article/details/gtghemtbmj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jqgfzy.top/Article/details/gtevkaagee.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.chenlongwang.top/Article/details/gthfwfiooi.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sxryk.cn/Article/details/gtrxlnstko.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigufen.top/Article/details/gtprkwcmvi.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cheryme.top/Article/details/gtqqqqrdnc.html

Go:   // 手写循环累加
来源：http://dali.smart0.xyz/Article/details/gtpbokdvgl.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hfpthk.cn/Article/details/gtpumyizfy.html

C#:   list.Sum();  list.Average()
来源：http://dali.jinqigufen.top/Article/details/gtqgpykwvw.html

[D17] 最大值与最小值
来源：http://dali.nwbrower.top/Article/details/gtpuxlmedd.html

Py:   max(arr);  min(arr)
来源：http://dali.svipenyu.cn/Article/details/gtwyqimaeg.html

PHP:  max($arr);  min($arr);
来源：http://dali.aizwys.cn/Article/details/gtcpkadniq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shzxlz.cn/Article/details/gttjdncqjx.html

TS:   Math.max(...arr);
来源：http://dali.iojbl.cn/Article/details/gtwjfopygw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yvedp.cn/Article/details/gtuloepwdn.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtcdginppa.html

Ruby: arr.max;  arr.min
来源：http://dali.yvedp.cn/Article/details/gtmgvahcxr.html

C#:   list.Max();  list.Min()
来源：http://dali.xuetiantiany.cn/Article/details/gttvuwnvck.html

[D18] 扁平化嵌套数组
来源：http://dali.jqgufenzy.top/Article/details/gtgscwqplq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.c1oappe.top/Article/details/gtzakxkrqw.html

PHP:  array_merge(...$nested);
来源：http://dali.sufxvd.cn/Article/details/gtocyhhjlh.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yj20258888.top/Article/details/gtnhyxrafc.html

TS:   nested.flat();
来源：http://dali.xinyue.icu/Article/details/gtursltsub.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtirrtcwaj.html

Go:   // 手写双层循环
来源：http://dali.wangdashe.top/Article/details/gtmgcnjnys.html

Ruby: nested.flatten
来源：http://dali.jyoumei.cn/Article/details/gtskeundun.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gtflwnnlxh.html

[D19] 按字段分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtisrhyndh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.daria6918.cn/Article/details/gterymvxzf.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxqmygqmc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.nanxinkj.top/Article/details/gtrpzbqiih.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zdqjudy.top/Article/details/gtknwrgofp.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ppjwa.cn/Article/details/gtedmbqpnc.html

Go:   // 手写 map[string][]T
来源：http://dali.gogol.net.cn/Article/details/gtmomuwdoj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hammf.cn/Article/details/gtcammxydq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hfpthk.cn/Article/details/gtcggviluu.html

[D20] 统计每个元素出现次数
来源：http://dali.fengsongda.top/Article/details/gtlxgqhyhb.html

Py:   Counter(arr)
来源：http://dali.mhx1999.top/Article/details/gttixqrmug.html

PHP:  array_count_values($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtqtnojmvs.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtypfhsgjn.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenjidiqi.icu/Article/details/gtcqznwgql.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.kuanghao11.cn/Article/details/gtkafkjjqh.html

Go:   // 手写 map[T]int
来源：http://dali.c1oappe.top/Article/details/gtrzdnaxdq.html

Ruby: arr.tally
来源：http://dali.yj20258888.top/Article/details/gtjtdozkcd.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ehwqpu.com/Article/details/gthgnvtiry.html

[D21] 判断是否包含某元素
来源：http://dali.shuidangran.top/Article/details/gtmqdjcsox.html

Py:   x in arr
来源：http://dali.mhx1999.top/Article/details/gtvzhkpvjp.html

PHP:  in_array($x, $arr, true);
来源：http://dali.9152youxi.cn/Article/details/gtbltygpcv.html

JS:   arr.includes(x)
来源：http://dali.yangfankeji.com/Article/details/gtcttbjggv.html

TS:   arr.includes(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtadkussuu.html

Java: list.contains(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfurzgqxv.html

Go:   slices.Contains(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gtdxljvrmo.html

Ruby: arr.include?(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtjqivhmel.html

C#:   list.Contains(x)
来源：http://dali.hnqzz.top/Article/details/gtvckomveh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.guowangkeji.top/Article/details/gtlrzggmym.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.guowangkeji.top/Article/details/gtzhcaursl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xinyue.icu/Article/details/gtcoakkazb.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.snrcjt.cn/Article/details/gteetvrdzu.html

TS:   [...arr];
来源：http://dali.yuxming.cn/Article/details/gtpqpvdvfl.html

Java: new ArrayList<>(list);
来源：http://dali.yanxiufei.cn/Article/details/gtjlfvphzu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxpmiewib.html

Ruby: arr.dup;  arr.clone
来源：http://dali.nanxinkj.top/Article/details/gtqsuxjyyo.html

C#:   new List<int>(list);
来源：http://dali.jqgufenzy.top/Article/details/gtdackapqb.html

[D23] reduce 累积计算
来源：http://dali.jqgfzy.top/Article/details/gtvsxhrvkn.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yonumen.top/Article/details/gtaokeveoy.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xziqi.cn/Article/details/gtgaetnjck.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtkbhtaqkl.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tian-w.cn/Article/details/gtjgqlfhzt.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ivvv.top/Article/details/gtvnatcuqq.html

Go:   // 手写循环
来源：http://dali.sweek.top/Article/details/gtmqnlwksr.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gotoacloud.top/Article/details/gttedloiwk.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhengqikj.top/Article/details/gthanfnjkt.html

[D24] 字典 / Map 基本操作
来源：http://dali.haohaochexian.top/Article/details/gtwajcvsao.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yongpay.top/Article/details/gteetsyeiz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.sufxvd.cn/Article/details/gtuscgnacd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.svipenyu.cn/Article/details/gtqenngcfv.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.guowangkeji.top/Article/details/gtkkfwivyx.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ydzc1.top/Article/details/gtttssyvok.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.pycfn.com/Article/details/gtmgoolyog.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.chenjidiqi.icu/Article/details/gtidnhqdkx.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinyuanbaomall.cn/Article/details/gthfmangjf.html

[D25] Set 集合去重与交并差
来源：http://dali.jinghuilouyu.cn/Article/details/gtoxtpgkyc.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jyoumei.cn/Article/details/gtspjwbcig.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hammf.cn/Article/details/gtcxhylhkw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ehwqpu.com/Article/details/gtifhngpqv.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtufabtexg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jqgfzy.top/Article/details/gtqsguntlo.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.guowangkeji.top/Article/details/gtlppipclp.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoaqdunxa.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cucudq.cn/Article/details/gtzrcatjme.html

[D26] 数组转字符串
来源：http://dali.wangdashe.top/Article/details/gtdeemdxcr.html

Py:   ", ".join(map(str, arr))
来源：http://dali.aibaodan.cn/Article/details/gtwtffabsk.html

PHP:  implode(", ", $arr);
来源：http://dali.jianghu66.top/Article/details/gtrhnxgzro.html

JS:   arr.join(", ")
来源：http://dali.sweek.top/Article/details/gthvtrmmhg.html

TS:   arr.join(", ")
来源：http://dali.yongpay.top/Article/details/gtrwkmqtoq.html

Java: String.join(", ", list)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkkowcgmm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.aizwys.cn/Article/details/gtcvfmpgsv.html

Ruby: arr.join(", ")
来源：http://dali.cashguo.top/Article/details/gtgdtrsxyf.html

C#:   string.Join(", ", list)
来源：http://dali.wangshuangyany.cn/Article/details/gtlxnqswxr.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtahytzyxe.html

E. 字符串处理
来源：http://dali.pengpengdd.cyou/Article/details/gtyufxegzd.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtrchenujw.html

[E01] 拼接字符串
来源：http://dali.svipenyu.cn/Article/details/gttvrobieq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.andypj.xyz/Article/details/gtjadfjpca.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.fengsongda.top/Article/details/gtfdcabtkq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gtpuvemoix.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.316326.xyz/Article/details/gtfwzmwpqx.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.redwolf501.top/Article/details/gthdachjax.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.kuanghao11.cn/Article/details/gtgfacdbbe.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.vqdsnc.cn/Article/details/gtmxnutsmk.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yongpay.top/Article/details/gtlynimdbn.html

[E02] 重复字符串
来源：http://dali.chenzaomai.com/Article/details/gtkuuenqlq.html

Py:   "ab" * 3
来源：http://dali.haohaochexian.top/Article/details/gtrigcwlsm.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gthuadtsom.html

JS:   "ab".repeat(3)
来源：http://dali.feifeiyinyue.top/Article/details/gtqbvixshj.html

TS:   "ab".repeat(3)
来源：http://dali.hfpthk.cn/Article/details/gtayzhvcno.html

Java: "ab".repeat(3)
来源：http://dali.yvedp.cn/Article/details/gteqkmtnfn.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.daxiang520.top/Article/details/gtpnegbyjo.html

Ruby: "ab" * 3
来源：http://dali.nanxuanxn.top/Article/details/gtdpwpbvfx.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.quarkkingdee.top/Article/details/gtphdtpqxr.html

[E03] 截取子串
来源：http://dali.vqdsnc.cn/Article/details/gtisbmnlsg.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.guowangkeji.top/Article/details/gttspgvdcv.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyydhoodi.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.guowangkeji.top/Article/details/gtnhevrdzf.html

TS:   s.slice(1, 4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqezzwdwf.html

Java: s.substring(1, 4)
来源：http://dali.ehwqpu.com/Article/details/gtridezvge.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gaohongyu789.top/Article/details/gtjblbzjrd.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hfpthk.cn/Article/details/gtcdlubsde.html

C#:   s.Substring(1, 3)
来源：http://dali.daxiang520.top/Article/details/gtdxtecrvb.html

[E04] 查找子串位置
来源：http://dali.daxiang520.top/Article/details/gtodlwpsnz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.daria6918.cn/Article/details/gthncqfhgv.html


<!-- 参考信息 -->