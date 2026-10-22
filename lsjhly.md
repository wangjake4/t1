代发 wailian999

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.wangshuangyany.cn/Article/details/gt2kvtyxlvf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.316326.xyz/Article/details/gt2jxnwxovy.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cdnleiting.top/Article/details/gt2vvctgkxc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gt2oasgtchw.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gt2phtorjxy.html

Go:   func add(a, b int) int
来源：http://dali.aibaodan.cn/Article/details/gt2vkhocqfr.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.wangshuangyany.cn/Article/details/gt2attogiae.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.chenjidiqi.icu/Article/details/gt2qiqwmgwq.html

[C14] 泛型函数
来源：http://dali.yongpay.top/Article/details/gt2ehjzndzl.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hammf.cn/Article/details/gt2ucfeidal.html

PHP:  // 无泛型
来源：http://dali.havefunace.top/Article/details/gt2civjiipt.html

JS:   // 无泛型
来源：http://dali.tian-w.cn/Article/details/gt2lxvhnpyf.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zycfv.cn/Article/details/gt2zaxbseuf.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.gotoacloud.top/Article/details/gt2wlksszhf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ybcxt.top/Article/details/gt2ibsusatm.html

Ruby: # 无泛型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2coikcvtb.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jinqigufen.top/Article/details/gt2foxlruql.html

[C15] 解构 / 展开参数
来源：http://dali.kuanghao11.cn/Article/details/gt2ntlpxozh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bpcuegag.html

PHP:  [$a, $b] = $pair;
来源：http://dali.tian-w.cn/Article/details/gt2ctdsykgz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.wangdashe.top/Article/details/gt2rnphbsqe.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zdqjudy.top/Article/details/gt2cddunesx.html

Java: // 无解构
来源：http://dali.xuanzx.com/Article/details/gt2ehqmxzsi.html

Go:   // 无解构
来源：http://dali.zycfv.cn/Article/details/gt2coafyfxa.html

Ruby: a, b = pair
来源：http://dali.sxryk.cn/Article/details/gt2fymxbsuy.html

C#:   var (a, b) = pair;
来源：http://dali.tanke756.top/Article/details/gt2ulztchqs.html

[C16] 函数 / 方法重载
来源：http://dali.wangshuangyany.cn/Article/details/gt2opjmhmrs.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.mhx1999.top/Article/details/gt2mxaoxnny.html

PHP:  // 无重载
来源：http://dali.cucudq.cn/Article/details/gt2oubswpzm.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.0kj1m.cn/Article/details/gt2lmnfpwjr.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yj20258.top/Article/details/gt2zpukwskq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.c1oappe.top/Article/details/gt2gjyapiot.html

Go:   // 无重载：用不同函数名
来源：http://dali.gzhubu.top/Article/details/gt2fndaynvo.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2piljrdaw.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2ascybftw.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2qphvjufi.html

D. 数组 / 列表 / 集合
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yymyegxm.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xijvtqfx.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wnsvzgax.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hysaishi.cn/Article/details/gt2nbgkaswm.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jinqigufen.top/Article/details/gt2iddvpdvu.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yongpay.top/Article/details/gt2jbxftkhc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.sufxvd.cn/Article/details/gt2tpbqemsa.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.guannengcc.top/Article/details/gt2kczmjnfo.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jyoumei.cn/Article/details/gt2whmeroeu.html

Ruby: arr = [1, 2, 3]
来源：http://dali.kuanghao11.cn/Article/details/gt2wytefret.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2oieprpes.html

[D02] 追加元素到末尾
来源：http://dali.snrcjt.cn/Article/details/gt2ghujnakj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hammf.cn/Article/details/gt2sakaxcar.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.vqdsnc.cn/Article/details/gt2enascciy.html

JS:   arr.push(4);
来源：http://dali.hammf.cn/Article/details/gt2hckszrdj.html

TS:   arr.push(4);
来源：http://dali.zdqjudy.top/Article/details/gt2hlnvdpdt.html

Java: list.add(4);
来源：http://dali.gotoacloud.top/Article/details/gt2rehfwafu.html

Go:   arr = append(arr, 4)
来源：http://dali.kuanghao11.cn/Article/details/gt2kbnlsdbp.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.kuanghao11.cn/Article/details/gt2hkonzlod.html

C#:   list.Add(4);
来源：http://dali.kuanghao11.cn/Article/details/gt2bfiocexk.html

[D03] 在指定位置插入元素
来源：http://dali.zhongyouzk.top/Article/details/gt2cpwqqlzr.html

Py:   arr.insert(0, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gt2tlffjlgb.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cdnleiting.top/Article/details/gt2naxfqwkp.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.tanke756.top/Article/details/gt2jaawsnko.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gt2mspphdbp.html

Java: list.add(0, 0);
来源：http://dali.316326.xyz/Article/details/gt2gcouzvws.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.guannengcc.top/Article/details/gt2dtlhawrg.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ejfmpjac.html

C#:   list.Insert(0, 0);
来源：http://dali.hammf.cn/Article/details/gt2lcbxahqt.html

[D04] 删除元素
来源：http://dali.cucudq.cn/Article/details/gt2amdfbebk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fknmswqs.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.cdnleiting.top/Article/details/gt2yhjmhjyl.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.haohaochexian.top/Article/details/gt2todxvnmx.html

TS:   arr.splice(0, 1);
来源：http://dali.9152youxi.cn/Article/details/gt2kxxorkxv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.nwbrower.top/Article/details/gt2ihlydhxv.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jianghu66.top/Article/details/gt2bjirqivp.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shangyingyoupin.top/Article/details/gt2yyhhjpjn.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.wangshuangyany.cn/Article/details/gt2rmrkqrxw.html

[D05] 访问与修改元素
来源：http://dali.yuxming.cn/Article/details/gt2mkjxwree.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258888.top/Article/details/gt2etbtzluu.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.birdmap.top/Article/details/gt2udyqzsmr.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.vqdsnc.cn/Article/details/gt2ypigtypd.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.gogol.net.cn/Article/details/gt2eurixwfr.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hfpthk.cn/Article/details/gt2mjthwxjh.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vlvspqkx.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hongshengwenyu.top/Article/details/gt2tciyhpia.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.sysykeji.top/Article/details/gt2ifumrxus.html

[D06] 数组长度
来源：http://dali.gaohongyu789.top/Article/details/gt2mhjgjoep.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcrjlknv.html

PHP:  count($arr);
来源：http://dali.ivvv.top/Article/details/gt2nmqgdmty.html

JS:   arr.length
来源：http://dali.meibo888.top/Article/details/gt2uxzrihco.html

TS:   arr.length
来源：http://dali.meibo888.top/Article/details/gt2gtktnsxk.html

Java: list.size();
来源：http://dali.gogol.net.cn/Article/details/gt2yeulfahy.html

Go:   len(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2hrghxujn.html

Ruby: arr.length; arr.size
来源：http://dali.zdqjudy.top/Article/details/gt2unceqqmo.html

C#:   list.Count;
来源：http://dali.zycfv.cn/Article/details/gt2ycvnzgld.html

[D07] 切片 / 取子数组
来源：http://dali.jiagoushi.top/Article/details/gt2aywrqycl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hezyjedy.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zarwzaog.html

JS:   arr.slice(1, 4);
来源：http://dali.hongshengwenyu.top/Article/details/gt2vmvtjyry.html

TS:   arr.slice(1, 4);
来源：http://dali.nanxinkj.top/Article/details/gt2jqypanpa.html

Java: list.subList(1, 4);
来源：http://dali.wangshuangyany.cn/Article/details/gt2qxgfoiyx.html

Go:   arr[1:4]
来源：http://dali.vqdsnc.cn/Article/details/gt2iaghmuwz.html

Ruby: arr[1, 3]
来源：http://dali.sxryk.cn/Article/details/gt2xgzpjsrb.html

C#:   list.GetRange(1, 3);
来源：http://dali.cashguo.top/Article/details/gt2irgqozro.html

[D08] 合并两个数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2idstmvib.html

Py:   a + b;  a.extend(b)
来源：http://dali.xinyue.icu/Article/details/gt2nrbubpjr.html

PHP:  array_merge($a, $b);
来源：http://dali.316326.xyz/Article/details/gt2jbvjrsru.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xylfe.cn/Article/details/gt2vktavfcj.html

TS:   [...a, ...b];
来源：http://dali.sufxvd.cn/Article/details/gt2ionafdot.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2qzqhskwd.html

Go:   append(a, b...)
来源：http://dali.zhongyouzk.top/Article/details/gt2odprkkyg.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hammf.cn/Article/details/gt2brgfizio.html

C#:   a.Concat(b).ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2vcehzmrw.html

[D09] 排序（升序）
来源：http://dali.jlsjyb.cn/Article/details/gt2eionzhxa.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhoulong.xyz/Article/details/gt2vxdfpegx.html

PHP:  sort($arr);
来源：http://dali.sysykeji.top/Article/details/gt2rvwtoquv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.birdmap.top/Article/details/gt2fdewrjhf.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.feifeiyinyue.top/Article/details/gt2sqhaghft.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hysaishi.cn/Article/details/gt2foctvyam.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2vgzlvmhf.html

Ruby: arr.sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kfcrlenx.html

C#:   list.Sort();
来源：http://dali.yj20258.top/Article/details/gt2pjxppslh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.gaohongyu789.top/Article/details/gt2fmsajhsk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.pycfn.com/Article/details/gt2ybyartik.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nwbrower.top/Article/details/gt2pumtmici.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jqgufenzy.top/Article/details/gt2qqguixpx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jqgufenzy.top/Article/details/gt2utnypten.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.daria6918.cn/Article/details/gt2esgkwnjm.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yj20258.top/Article/details/gt2uxamqwjk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.316326.xyz/Article/details/gt2gyzfvjos.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jinqigufen.top/Article/details/gt2ucmgmfjh.html

[D11] 反转数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2odfmeptz.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2voffdptp.html

PHP:  array_reverse($arr);
来源：http://dali.chenzaomai.com/Article/details/gt2xbbzhvrq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shzxlz.cn/Article/details/gt2tsederww.html

TS:   [...arr].reverse();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vzgqxgct.html

Java: Collections.reverse(list);
来源：http://dali.gogol.net.cn/Article/details/gt2lqzjrifg.html

Go:   slices.Reverse(arr)
来源：http://dali.jiagoushi.top/Article/details/gt2jayhzavf.html

Ruby: arr.reverse
来源：http://dali.vqdsnc.cn/Article/details/gt2txsfpcam.html

C#:   list.Reverse();
来源：http://dali.hongshengwenyu.top/Article/details/gt2tqxhneoo.html

[D12] 查找元素下标
来源：http://dali.hnxiangtu.top/Article/details/gt2tqrcqmjb.html

Py:   arr.index(x);  x in arr
来源：http://dali.chenjidiqi.icu/Article/details/gt2xtglyytx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yongpay.top/Article/details/gt2eganhycd.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.snrcjt.cn/Article/details/gt2vezzdaua.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hnqzz.top/Article/details/gt2osbjukof.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shzxlz.cn/Article/details/gt2pdxhspbh.html

Go:   slices.Index(arr, x)
来源：http://dali.fengsongda.top/Article/details/gt2whlmxmqh.html

Ruby: arr.index(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2mlsxcxrd.html

C#:   list.IndexOf(x);
来源：http://dali.chenlongwang.top/Article/details/gt2ggvwhwik.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shuidangran.top/Article/details/gt2psabqyvq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.wangshuangyany.cn/Article/details/gt2hyvvundr.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hysaishi.cn/Article/details/gt2nnlqcnum.html

JS:   arr.filter(x => x > 3)
来源：http://dali.kuanghao11.cn/Article/details/gt2ybbbayor.html

TS:   arr.filter(x => x > 3)
来源：http://dali.sweek.top/Article/details/gt2pbwrkvwj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.bjfxy.top/Article/details/gt2mgqswbgw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.wangshuangyany.cn/Article/details/gt2fklcdtvb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kyxdnlzb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2rcpuemgc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yhdtolvw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2pdepcbua.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jinqigufen.top/Article/details/gt2ihbigtoo.html

JS:   arr.map(x => x * 2)
来源：http://dali.yj20258.top/Article/details/gt2wynhutud.html

TS:   arr.map(x => x * 2)
来源：http://dali.daria6918.cn/Article/details/gt2sqlmokvw.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sweek.top/Article/details/gt2kcvqbfqv.html

Go:   // 手写循环
来源：http://dali.c1oappe.top/Article/details/gt2naetilzx.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.sweek.top/Article/details/gt2gojkmgsm.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gt2iuacnnjp.html

[D15] 去重
来源：http://dali.cqqwz.cn/Article/details/gt2jxngradx.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.quarkkingdee.top/Article/details/gt2qxyeytsp.html

PHP:  array_unique($arr);
来源：http://dali.c1oappe.top/Article/details/gt2zwricqxb.html

JS:   [...new Set(arr)]
来源：http://dali.nanxinkj.top/Article/details/gt2dovsgvef.html

TS:   [...new Set(arr)]
来源：http://dali.zhixingplan.top/Article/details/gt2kkcvknsk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jiagoushi.top/Article/details/gt2hcwqiyms.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.daxiang520.top/Article/details/gt2ogqijazr.html

Ruby: arr.uniq
来源：http://dali.guowangkeji.top/Article/details/gt2nnauezsj.html

C#:   list.Distinct().ToList()
来源：http://dali.jianghu66.top/Article/details/gt2wtsqhpkz.html

[D16] 求和与平均值
来源：http://dali.ydzc1.top/Article/details/gt2cgyhhxdp.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.bjfxy.top/Article/details/gt2rupxqtkl.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gxwprzgp.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2chbevgbg.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gotoacloud.top/Article/details/gt2xsvemkvg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.vqdsnc.cn/Article/details/gt2henmikae.html

Go:   // 手写循环累加
来源：http://dali.shangyingyoupin.top/Article/details/gt2pespveqv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.guannengcc.top/Article/details/gt2ehunfsnn.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhiwuduotai.top/Article/details/gt2xnnxebly.html

[D17] 最大值与最小值
来源：http://dali.sweek.top/Article/details/gt2piqevuwn.html

Py:   max(arr);  min(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2naowgyge.html

PHP:  max($arr);  min($arr);
来源：http://dali.daria6918.cn/Article/details/gt2jyvbbfxm.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2dagiczry.html

TS:   Math.max(...arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2ncbdnrer.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xziqi.cn/Article/details/gt2uiptakup.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.meibo888.top/Article/details/gt2pnmdqnqv.html

Ruby: arr.max;  arr.min
来源：http://dali.wangshuangyany.cn/Article/details/gt2tteczyif.html

C#:   list.Max();  list.Min()
来源：http://dali.sysykeji.top/Article/details/gt2ksownjhc.html

[D18] 扁平化嵌套数组
来源：http://dali.andypj.xyz/Article/details/gt2rxrcgkcg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.kuanghao11.cn/Article/details/gt2kgqwxdzy.html

PHP:  array_merge(...$nested);
来源：http://dali.hfpthk.cn/Article/details/gt2uqrmikbe.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zycfv.cn/Article/details/gt2goosmfme.html

TS:   nested.flat();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2indprkoa.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.iojbl.cn/Article/details/gt2ckuvokgh.html

Go:   // 手写双层循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lfgzbvkz.html

Ruby: nested.flatten
来源：http://dali.jianghu66.top/Article/details/gt2aiwqhjgd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zdqjudy.top/Article/details/gt2wjvgszps.html

[D19] 按字段分组
来源：http://dali.gogol.net.cn/Article/details/gt2bpyluiha.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2aigcztke.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jyoumei.cn/Article/details/gt2fdwbdubf.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shzxlz.cn/Article/details/gt2qgukpyae.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ljqdzaos.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.aibaodan.cn/Article/details/gt2bupdgfxe.html

Go:   // 手写 map[string][]T
来源：http://dali.haohaochexian.top/Article/details/gt2hfwltmso.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yj202588.top/Article/details/gt2kfghbsso.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iekgznjr.html

[D20] 统计每个元素出现次数
来源：http://dali.zhiwuduotai.top/Article/details/gt2vjuahuke.html

Py:   Counter(arr)
来源：http://dali.yonumen.top/Article/details/gt2nrhmayur.html

PHP:  array_count_values($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2tyusqiyh.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenlongwang.top/Article/details/gt2jaqyyyqw.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shuidangran.top/Article/details/gt2vnnsgvke.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.pycfn.com/Article/details/gt2apmujvyw.html

Go:   // 手写 map[T]int
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bqgnxuob.html

Ruby: arr.tally
来源：http://dali.guannengcc.top/Article/details/gt2zkliequq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.pycfn.com/Article/details/gt2zmxqeknz.html

[D21] 判断是否包含某元素
来源：http://dali.fengsongda.top/Article/details/gt2kdzxmoww.html

Py:   x in arr
来源：http://dali.aibaodan.cn/Article/details/gt2kmektzbu.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xylfe.cn/Article/details/gt2xsglocwr.html

JS:   arr.includes(x)
来源：http://dali.smart0.xyz/Article/details/gt2slwvapkp.html

TS:   arr.includes(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2tjxuhmoj.html

Java: list.contains(x)
来源：http://dali.svipenyu.cn/Article/details/gt2plxuwxgj.html

Go:   slices.Contains(arr, x)
来源：http://dali.ydzc1.top/Article/details/gt2exwccenm.html

Ruby: arr.include?(x)
来源：http://dali.aizwys.cn/Article/details/gt2juwnhddq.html

C#:   list.Contains(x)
来源：http://dali.fzhhl.top/Article/details/gt2ygjlslde.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yongpay.top/Article/details/gt2qqcdczdc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2njdxkmbd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ppjwa.cn/Article/details/gt2rbtmasxj.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.tian-w.cn/Article/details/gt2tysmraom.html

TS:   [...arr];
来源：http://dali.chenlongwang.top/Article/details/gt2qpkdwjuh.html

Java: new ArrayList<>(list);
来源：http://dali.havefunace.top/Article/details/gt2wxggqhge.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cucudq.cn/Article/details/gt2oyuelubo.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gzhubu.top/Article/details/gt2ttnkbafu.html

C#:   new List<int>(list);
来源：http://dali.sysykeji.top/Article/details/gt2akoekjyx.html

[D23] reduce 累积计算
来源：http://dali.cheryme.top/Article/details/gt2uvpjbndj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhixingplan.top/Article/details/gt2haesornm.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yueranfly.top/Article/details/gt2xteezzas.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jianghu66.top/Article/details/gt2bsjnrqwq.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sufxvd.cn/Article/details/gt2szpvcmus.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.fengsongda.top/Article/details/gt2nlwamddi.html

Go:   // 手写循环
来源：http://dali.yvedp.cn/Article/details/gt2oznwzcvv.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.cdnleiting.top/Article/details/gt2luufqqdl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sysykeji.top/Article/details/gt2aujmsvcl.html

[D24] 字典 / Map 基本操作
来源：http://dali.pengpengdd.cyou/Article/details/gt2ybaazdqv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2houumaqx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.0kj1m.cn/Article/details/gt2dtxeqefr.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.birdmap.top/Article/details/gt2vfnpifwh.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shzxlz.cn/Article/details/gt2bzabkiaj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.aizwys.cn/Article/details/gt2yovzfxjs.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.chenzaomai.com/Article/details/gt2tafxhptu.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.cucudq.cn/Article/details/gt2iphdhdbk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.tian-w.cn/Article/details/gt2kozemhxz.html

[D25] Set 集合去重与交并差
来源：http://dali.kuanghao11.cn/Article/details/gt2splhlmiw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hfpthk.cn/Article/details/gt2twirglfl.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhongyouzk.top/Article/details/gt2obyyaylt.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gliifgyj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jinqigufen.top/Article/details/gt2hoemrztb.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yonumen.top/Article/details/gt2drfptenh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhoulong.xyz/Article/details/gt2yurkncfv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jqgfzy.top/Article/details/gt2prrsevsi.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.mhx1999.top/Article/details/gt2zwsuygzt.html

[D26] 数组转字符串
来源：http://dali.jianghu66.top/Article/details/gt2qfqsalat.html

Py:   ", ".join(map(str, arr))
来源：http://dali.kuanghao11.cn/Article/details/gt2bybtsvpb.html

PHP:  implode(", ", $arr);
来源：http://dali.andypj.xyz/Article/details/gt2exkfooma.html

JS:   arr.join(", ")
来源：http://dali.gzhubu.top/Article/details/gt2frgaygmf.html

TS:   arr.join(", ")
来源：http://dali.jiagoushi.top/Article/details/gt2qxoqjvyf.html

Java: String.join(", ", list)
来源：http://dali.redwolf501.top/Article/details/gt2qbhlquxq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.chenlongwang.top/Article/details/gt2obnfznqe.html

Ruby: arr.join(", ")
来源：http://dali.jyoumei.cn/Article/details/gt2cfpzqvki.html

C#:   string.Join(", ", list)
来源：http://dali.dianchejie.cn/Article/details/gt2titnegqt.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2rjmxnfse.html

E. 字符串处理
来源：http://dali.zhoulong.xyz/Article/details/gt2xqwlooqu.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2fypexbhz.html

[E01] 拼接字符串
来源：http://dali.jinqigufen.top/Article/details/gt2pwgahzaw.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yangfankeji.com/Article/details/gt2wafmpjgj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.meibo888.top/Article/details/gt2pxqjmoif.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yvedp.cn/Article/details/gt2tlcxaxdm.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhixingplan.top/Article/details/gt2cammfdvq.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yuxming.cn/Article/details/gt2vueztgvu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wtrhtgps.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.tian-w.cn/Article/details/gt2gtfmqfeu.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gt2ouoexypt.html

[E02] 重复字符串
来源：http://dali.xinyue.icu/Article/details/gt2whiiecwz.html

Py:   "ab" * 3
来源：http://dali.chenzaomai.com/Article/details/gt2ehqxnknl.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ehwqpu.com/Article/details/gt2dpitrwwa.html

JS:   "ab".repeat(3)
来源：http://dali.xylfe.cn/Article/details/gt2wmqqrdec.html

TS:   "ab".repeat(3)
来源：http://dali.yj20258.top/Article/details/gt2vhxwcahx.html

Java: "ab".repeat(3)
来源：http://dali.meibo888.top/Article/details/gt2uelnaltk.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ehwqpu.com/Article/details/gt2vhgqqevg.html

Ruby: "ab" * 3
来源：http://dali.fzhhl.top/Article/details/gt2svccoycz.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhiwuduotai.top/Article/details/gt2vkjgrskw.html

[E03] 截取子串
来源：http://dali.fzhhl.top/Article/details/gt2xazlkicx.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.birdmap.top/Article/details/gt2riybzxji.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gt2uozpkted.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yj20258888.top/Article/details/gt2wobpofdm.html

TS:   s.slice(1, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gt2etnbfznm.html

Java: s.substring(1, 4)
来源：http://dali.dianchejie.cn/Article/details/gt2ioihwqcu.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xuetiantiany.cn/Article/details/gt2nzhbkkub.html


<!-- 参考信息 -->