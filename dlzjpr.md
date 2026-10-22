代发 wailian999

Go:   func() { fmt.Println("run") }()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ubnoxhzh.html

Ruby: -> { puts "run" }.call
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2urucqnue.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.tianlin.xyz/Article/details/gt2ycdhfdfz.html

[C13] 类型声明 / 类型注解
来源：http://dali.redwolf501.top/Article/details/gt2geqedplf.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cheryme.top/Article/details/gt2toprqwto.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj202588.top/Article/details/gt2fdpenhoq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.tianlin.xyz/Article/details/gt2vylbkyht.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gt2aosyixsh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eovrbeth.html

Go:   func add(a, b int) int
来源：http://dali.mhx1999.top/Article/details/gt2ndmsuste.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hnxiangtu.top/Article/details/gt2ajxbetss.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.sysykeji.top/Article/details/gt2dddtrsqx.html

[C14] 泛型函数
来源：http://dali.jqgufenzy.top/Article/details/gt2ckmlztms.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.guowangkeji.top/Article/details/gt2wqyodugm.html

PHP:  // 无泛型
来源：http://dali.daxiang520.top/Article/details/gt2gnqursle.html

JS:   // 无泛型
来源：http://dali.dashuyun.cn/Article/details/gt2eyxarqbh.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jyoumei.cn/Article/details/gt2iwmxvjwo.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jlsjyb.cn/Article/details/gt2ifvjuhys.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hammf.cn/Article/details/gt2qnmyiora.html

Ruby: # 无泛型
来源：http://dali.zhongyouzk.top/Article/details/gt2ncfvmylb.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hywenlv.cn/Article/details/gt2hznamqsw.html

[C15] 解构 / 展开参数
来源：http://dali.guowangkeji.top/Article/details/gt2udjecemu.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.c1oappe.top/Article/details/gt2xftdqaqw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.chenlongwang.top/Article/details/gt2plbmezoa.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.smart0.xyz/Article/details/gt2qdskvjqh.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.chenzaomai.com/Article/details/gt2cfvgwgrg.html

Java: // 无解构
来源：http://dali.yangfankeji.com/Article/details/gt2vlxevvfj.html

Go:   // 无解构
来源：http://dali.pengpengdd.cyou/Article/details/gt2takkkqak.html

Ruby: a, b = pair
来源：http://dali.svipenyu.cn/Article/details/gt2rmnvnipy.html

C#:   var (a, b) = pair;
来源：http://dali.xinyue.icu/Article/details/gt2nsooghov.html

[C16] 函数 / 方法重载
来源：http://dali.zhiwuduotai.top/Article/details/gt2dadtunxy.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ehwqpu.com/Article/details/gt2cjajqzpm.html

PHP:  // 无重载
来源：http://dali.chenjidiqi.icu/Article/details/gt2yvyobxnw.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ppjwa.cn/Article/details/gt2olvvbfyw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.feifeiyinyue.top/Article/details/gt2msvcimuc.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yvedp.cn/Article/details/gt2bbcdzdsq.html

Go:   // 无重载：用不同函数名
来源：http://dali.smart0.xyz/Article/details/gt2zzhbtpwk.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shuidangran.top/Article/details/gt2fwpxgiyj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jyvqfvip.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2flcehjls.html

D. 数组 / 列表 / 集合
来源：http://dali.yonumen.top/Article/details/gt2xqscwayz.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2qjxzaejs.html

[D01] 创建数组 / 列表
来源：http://dali.yongpay.top/Article/details/gt2yqllcdso.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xylfe.cn/Article/details/gt2cpupexrj.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.chenlongwang.top/Article/details/gt2cdgjtonf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhiwuduotai.top/Article/details/gt2jvbzmpqu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.vqdsnc.cn/Article/details/gt2zjieiaoq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jqgufenzy.top/Article/details/gt2mwefbinr.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.c1oappe.top/Article/details/gt2aqqkmtgq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ppjwa.cn/Article/details/gt2nskqbagw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.birdmap.top/Article/details/gt2lgrhzuql.html

[D02] 追加元素到末尾
来源：http://dali.zhoulong.xyz/Article/details/gt2ufakkwve.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhiwuduotai.top/Article/details/gt2oxkegasj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shuidangran.top/Article/details/gt2iakzrsha.html

JS:   arr.push(4);
来源：http://dali.iojbl.cn/Article/details/gt2cknadeqc.html

TS:   arr.push(4);
来源：http://dali.guowangkeji.top/Article/details/gt2yedqbruw.html

Java: list.add(4);
来源：http://dali.nanxuanxn.top/Article/details/gt2zdqcgypx.html

Go:   arr = append(arr, 4)
来源：http://dali.zhixingplan.top/Article/details/gt2tpxzbdct.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ivvv.top/Article/details/gt2rrnwnszr.html

C#:   list.Add(4);
来源：http://dali.jqgufenzy.top/Article/details/gt2pjgmpdbg.html

[D03] 在指定位置插入元素
来源：http://dali.yonumen.top/Article/details/gt2vxugvjpj.html

Py:   arr.insert(0, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gt2juouslim.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shangyingyoupin.top/Article/details/gt2kcnwnelq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cashguo.top/Article/details/gt2rfndtqns.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.sweek.top/Article/details/gt2epuiqhlp.html

Java: list.add(0, 0);
来源：http://dali.snrcjt.cn/Article/details/gt2ivkkkikb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yangfankeji.com/Article/details/gt2rekfurqs.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.aizwys.cn/Article/details/gt2vhvcpbit.html

C#:   list.Insert(0, 0);
来源：http://dali.havefunace.top/Article/details/gt2glaqzogd.html

[D04] 删除元素
来源：http://dali.jyoumei.cn/Article/details/gt2jlycmwje.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.smart0.xyz/Article/details/gt2tyanloew.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.birdmap.top/Article/details/gt2bbdymhif.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.pycfn.com/Article/details/gt2dnfxelyc.html

TS:   arr.splice(0, 1);
来源：http://dali.pycfn.com/Article/details/gt2odeyurzy.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yj202588.top/Article/details/gt2gzcjgjnr.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqvrnse.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.andypj.xyz/Article/details/gt2dycqwdws.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yvwtvhtx.html

[D05] 访问与修改元素
来源：http://dali.316326.xyz/Article/details/gt2sdqzhthf.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258.top/Article/details/gt2kzcvtitc.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenzaomai.com/Article/details/gt2rdytsqyz.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhengqikj.top/Article/details/gt2bqdsqaxo.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xuetiantiany.cn/Article/details/gt2dqptatew.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cheryme.top/Article/details/gt2apdgcwpd.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yj202588.top/Article/details/gt2eoqrkbti.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yanxiufei.cn/Article/details/gt2uekhsfdc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zkrqckko.html

[D06] 数组长度
来源：http://dali.zhengqikj.top/Article/details/gt2zdenbilo.html

Py:   len(arr)
来源：http://dali.wangdashe.top/Article/details/gt2jratigmu.html

PHP:  count($arr);
来源：http://dali.hfpthk.cn/Article/details/gt2tywxehne.html

JS:   arr.length
来源：http://dali.zhengqikj.top/Article/details/gt2jenviyto.html

TS:   arr.length
来源：http://dali.feifeiyinyue.top/Article/details/gt2nqwmevoa.html

Java: list.size();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pbkbfelx.html

Go:   len(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2zncihqhw.html

Ruby: arr.length; arr.size
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yjdvnrgj.html

C#:   list.Count;
来源：http://dali.tanke756.top/Article/details/gt2kohsorrk.html

[D07] 切片 / 取子数组
来源：http://dali.zhongyouzk.top/Article/details/gt2ijsagpxq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jinqigufen.top/Article/details/gt2ngqrbupq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cqqwz.cn/Article/details/gt2sdtzyejf.html

JS:   arr.slice(1, 4);
来源：http://dali.nanxuanxn.top/Article/details/gt2bfutdidp.html

TS:   arr.slice(1, 4);
来源：http://dali.jinqigufen.top/Article/details/gt2ywpmkycw.html

Java: list.subList(1, 4);
来源：http://dali.zhiwuduotai.top/Article/details/gt2jdcykzwl.html

Go:   arr[1:4]
来源：http://dali.sxryk.cn/Article/details/gt2elujybhx.html

Ruby: arr[1, 3]
来源：http://dali.fzhhl.top/Article/details/gt2bcngdilg.html

C#:   list.GetRange(1, 3);
来源：http://dali.jinqigfzy.top/Article/details/gt2oxbicdis.html

[D08] 合并两个数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zevvrsgv.html

Py:   a + b;  a.extend(b)
来源：http://dali.sweek.top/Article/details/gt2eaapwkbv.html

PHP:  array_merge($a, $b);
来源：http://dali.shzxlz.cn/Article/details/gt2lgsdshim.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yueranfly.top/Article/details/gt2xmgmgrpq.html

TS:   [...a, ...b];
来源：http://dali.shuidangran.top/Article/details/gt2utajkoxt.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sysykeji.top/Article/details/gt2mgdofupr.html

Go:   append(a, b...)
来源：http://dali.jiagoushi.top/Article/details/gt2ydbtkycq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yuanzhike.top/Article/details/gt2mwjeafwi.html

C#:   a.Concat(b).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gt2pycznpns.html

[D09] 排序（升序）
来源：http://dali.aibaodan.cn/Article/details/gt2jcbawmzo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xnmpxptb.html

PHP:  sort($arr);
来源：http://dali.tanke756.top/Article/details/gt2ncfvnato.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.daria6918.cn/Article/details/gt2aawwaxfc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yj20258.top/Article/details/gt2misyefxu.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhengqikj.top/Article/details/gt2pyedzlgc.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2hvvbgwfu.html

Ruby: arr.sort
来源：http://dali.zdqjudy.top/Article/details/gt2gwetvfvh.html

C#:   list.Sort();
来源：http://dali.hammf.cn/Article/details/gt2ddkqrqey.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.chenlongwang.top/Article/details/gt2jsvexclg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dwbtyley.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj202588.top/Article/details/gt2jftgrwsr.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gotoacloud.top/Article/details/gt2aiajmnyg.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.iojbl.cn/Article/details/gt2hrqfskme.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.gogol.net.cn/Article/details/gt2qdsvmwdd.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jianghu66.top/Article/details/gt2psejgfaj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.mhx1999.top/Article/details/gt2acggdawg.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.316326.xyz/Article/details/gt2zxemgoye.html

[D11] 反转数组
来源：http://dali.hfpthk.cn/Article/details/gt2cmgyaijb.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ayzkoftn.html

PHP:  array_reverse($arr);
来源：http://dali.guowangkeji.top/Article/details/gt2nhljabfa.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cashguo.top/Article/details/gt2pvsmvmki.html

TS:   [...arr].reverse();
来源：http://dali.hnxiangtu.top/Article/details/gt2jarimuuk.html

Java: Collections.reverse(list);
来源：http://dali.ivvv.top/Article/details/gt2jctqtsfx.html

Go:   slices.Reverse(arr)
来源：http://dali.gotoacloud.top/Article/details/gt2qhtbgkjd.html

Ruby: arr.reverse
来源：http://dali.quarkkingdee.top/Article/details/gt2gwmrorrr.html

C#:   list.Reverse();
来源：http://dali.jqgufenzy.top/Article/details/gt2btjcakym.html

[D12] 查找元素下标
来源：http://dali.yuanzhike.top/Article/details/gt2jnljyqbd.html

Py:   arr.index(x);  x in arr
来源：http://dali.sxryk.cn/Article/details/gt2zryaijkc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zycfv.cn/Article/details/gt2ncirfrjj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.snrcjt.cn/Article/details/gt2ssigwdgz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dianchejie.cn/Article/details/gt2euyplvyp.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.pycfn.com/Article/details/gt2olveiqbd.html

Go:   slices.Index(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gt2glqugwxl.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eeflglcu.html

C#:   list.IndexOf(x);
来源：http://dali.sxryk.cn/Article/details/gt2fpdloeqi.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hammf.cn/Article/details/gt2tlgilscd.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ybcxt.top/Article/details/gt2hewfoypw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xziqi.cn/Article/details/gt2finejyqu.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hysaishi.cn/Article/details/gt2uruvywel.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hfpthk.cn/Article/details/gt2koppzvvt.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jqgfzy.top/Article/details/gt2bxpdrbhv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zdqjudy.top/Article/details/gt2xkclwird.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.pycfn.com/Article/details/gt2bcuzvhmh.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.guowangkeji.top/Article/details/gt2pofmgcar.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ydzc1.top/Article/details/gt2wkvehkka.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.chenjidiqi.icu/Article/details/gt2boprbmgs.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.mhx1999.top/Article/details/gt2htkrkmop.html

JS:   arr.map(x => x * 2)
来源：http://dali.chenzaomai.com/Article/details/gt2eiidzfjn.html

TS:   arr.map(x => x * 2)
来源：http://dali.xinyue.icu/Article/details/gt2kqvvsgec.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jlsjyb.cn/Article/details/gt2kjxkokpe.html

Go:   // 手写循环
来源：http://dali.hywenlv.cn/Article/details/gt2tssepsml.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zdqjudy.top/Article/details/gt2jqysntkc.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gt2wwhffezr.html

[D15] 去重
来源：http://dali.gaohongyu789.top/Article/details/gt2qaqraynf.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.9152youxi.cn/Article/details/gt2tzvxcgyd.html

PHP:  array_unique($arr);
来源：http://dali.xinyue.icu/Article/details/gt2xtutlydl.html

JS:   [...new Set(arr)]
来源：http://dali.xuanzx.com/Article/details/gt2kazmkjlv.html

TS:   [...new Set(arr)]
来源：http://dali.fzhhl.top/Article/details/gt2xegmqklo.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jianghu66.top/Article/details/gt2fvrgelxa.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.cucudq.cn/Article/details/gt2mmtlqamk.html

Ruby: arr.uniq
来源：http://dali.dianchejie.cn/Article/details/gt2froltvyi.html

C#:   list.Distinct().ToList()
来源：http://dali.snrcjt.cn/Article/details/gt2nbphpmwb.html

[D16] 求和与平均值
来源：http://dali.hfpthk.cn/Article/details/gt2lsridett.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.smart0.xyz/Article/details/gt2hicfwtrl.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.nwbrower.top/Article/details/gt2ccqdyiqi.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fzhhl.top/Article/details/gt2istqzzzs.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ydzc1.top/Article/details/gt2hkhbmlnm.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zdqjudy.top/Article/details/gt2ukqmoqfi.html

Go:   // 手写循环累加
来源：http://dali.havefunace.top/Article/details/gt2qwihmnbf.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yj202588.top/Article/details/gt2dcmrxqvs.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhiwuduotai.top/Article/details/gt2omgbyjfm.html

[D17] 最大值与最小值
来源：http://dali.sweek.top/Article/details/gt2olyczykb.html

Py:   max(arr);  min(arr)
来源：http://dali.zdqjudy.top/Article/details/gt2kllrnoxw.html

PHP:  max($arr);  min($arr);
来源：http://dali.ivvv.top/Article/details/gt2gayfghyp.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xylfe.cn/Article/details/gt2wztgokko.html

TS:   Math.max(...arr);
来源：http://dali.yj202588.top/Article/details/gt2phqzycsh.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yj20258888.top/Article/details/gt2qychuxna.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjsyoaqq.html

Ruby: arr.max;  arr.min
来源：http://dali.cqqwz.cn/Article/details/gt2mtqqcerq.html

C#:   list.Max();  list.Min()
来源：http://dali.gogol.net.cn/Article/details/gt2wzopygpl.html

[D18] 扁平化嵌套数组
来源：http://dali.zhoulong.xyz/Article/details/gt2hzuwarrx.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.wangdashe.top/Article/details/gt2mnbpicbx.html

PHP:  array_merge(...$nested);
来源：http://dali.nwbrower.top/Article/details/gt2qqboayhs.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhixingplan.top/Article/details/gt2cmrjnhak.html

TS:   nested.flat();
来源：http://dali.dianchejie.cn/Article/details/gt2myzopkgj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jyoumei.cn/Article/details/gt2fnvdxguy.html

Go:   // 手写双层循环
来源：http://dali.yonumen.top/Article/details/gt2dcegfkoh.html

Ruby: nested.flatten
来源：http://dali.aizwys.cn/Article/details/gt2ealqwtmy.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ybcxt.top/Article/details/gt2wifxbywp.html

[D19] 按字段分组
来源：http://dali.zhixingplan.top/Article/details/gt2omldmpws.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.chenzaomai.com/Article/details/gt2zimlrimv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yuanzhike.top/Article/details/gt2xkqsgmrx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.pycfn.com/Article/details/gt2cczwtyds.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.chenlongwang.top/Article/details/gt2nedyvaia.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ivvv.top/Article/details/gt2ntbvvomn.html

Go:   // 手写 map[string][]T
来源：http://dali.bjfxy.top/Article/details/gt2mxnlqafz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ppjwa.cn/Article/details/gt2cbxabmgs.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hnxiangtu.top/Article/details/gt2anlyihcu.html

[D20] 统计每个元素出现次数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kkjvtswk.html

Py:   Counter(arr)
来源：http://dali.bjfxy.top/Article/details/gt2adbyiaaj.html

PHP:  array_count_values($arr);
来源：http://dali.zycfv.cn/Article/details/gt2mcruvxap.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shzxlz.cn/Article/details/gt2yhswtwkh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sxryk.cn/Article/details/gt2ozxehyaz.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.0kj1m.cn/Article/details/gt2sjmdplnf.html

Go:   // 手写 map[T]int
来源：http://dali.gzhubu.top/Article/details/gt2byfquqce.html

Ruby: arr.tally
来源：http://dali.zycfv.cn/Article/details/gt2qckjrcyr.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jlsjyb.cn/Article/details/gt2czokgggs.html

[D21] 判断是否包含某元素
来源：http://dali.jqgfzy.top/Article/details/gt2bihajpiw.html

Py:   x in arr
来源：http://dali.pengpengdd.cyou/Article/details/gt2lutfqesd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.fzhhl.top/Article/details/gt2fxxtutkh.html

JS:   arr.includes(x)
来源：http://dali.cucudq.cn/Article/details/gt2pdaxhnxa.html

TS:   arr.includes(x)
来源：http://dali.bjfxy.top/Article/details/gt2bvswnkab.html

Java: list.contains(x)
来源：http://dali.aibaodan.cn/Article/details/gt2rdyvatyd.html

Go:   slices.Contains(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gt2rhetcobc.html

Ruby: arr.include?(x)
来源：http://dali.yvedp.cn/Article/details/gt2bokayzgx.html

C#:   list.Contains(x)
来源：http://dali.hysaishi.cn/Article/details/gt2vopnebol.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zycfv.cn/Article/details/gt2kabhatku.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jinqigufen.top/Article/details/gt2zgzlaurn.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xuetiantiany.cn/Article/details/gt2arawqpog.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.redwolf501.top/Article/details/gt2xfunzlul.html

TS:   [...arr];
来源：http://dali.xziqi.cn/Article/details/gt2hacfxngw.html

Java: new ArrayList<>(list);
来源：http://dali.cheryme.top/Article/details/gt2zzaxxnhf.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.snrcjt.cn/Article/details/gt2ymuqiihl.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gotoacloud.top/Article/details/gt2ryivebvw.html

C#:   new List<int>(list);
来源：http://dali.vqdsnc.cn/Article/details/gt2vqglwulp.html

[D23] reduce 累积计算
来源：http://dali.hfpthk.cn/Article/details/gt2xtfndyyg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.c1oappe.top/Article/details/gt2wgzekvjt.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zdqjudy.top/Article/details/gt2aayvznpj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hnqzz.top/Article/details/gt2asjgxiao.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daxiang520.top/Article/details/gt2flvylslj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.gogol.net.cn/Article/details/gt2juuzokpt.html

Go:   // 手写循环
来源：http://dali.zhixingplan.top/Article/details/gt2fhoaouxd.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ivvv.top/Article/details/gt2chlbclju.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.chenzaomai.com/Article/details/gt2sihuikpt.html

[D24] 字典 / Map 基本操作
来源：http://dali.0kj1m.cn/Article/details/gt2yrhlbcie.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.tianlin.xyz/Article/details/gt2bnruwwdg.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.daria6918.cn/Article/details/gt2wvevceol.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2elkjiqno.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.dianchejie.cn/Article/details/gt2toigowft.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cawswtxb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yuanzhike.top/Article/details/gt2lgxdlnnt.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ybcxt.top/Article/details/gt2ahgesdmc.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.316326.xyz/Article/details/gt2ydcacoee.html

[D25] Set 集合去重与交并差
来源：http://dali.shuidangran.top/Article/details/gt2pwtdrptf.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.chenjidiqi.icu/Article/details/gt2vlwyzorz.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nszqyapm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yueranfly.top/Article/details/gt2gyuiyyzu.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.meibo888.top/Article/details/gt2thmeewvy.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.c1oappe.top/Article/details/gt2qayqrnkf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yuanzhike.top/Article/details/gt2myrdznlv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.redwolf501.top/Article/details/gt2njvrondm.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uovsbwoc.html

[D26] 数组转字符串
来源：http://dali.zhoulong.xyz/Article/details/gt2tdmeninh.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ydzc1.top/Article/details/gt2bnkcvhzs.html

PHP:  implode(", ", $arr);
来源：http://dali.wangdashe.top/Article/details/gt2uuvsabct.html

JS:   arr.join(", ")
来源：http://dali.svipenyu.cn/Article/details/gt2mhqfkymh.html

TS:   arr.join(", ")
来源：http://dali.zhixingplan.top/Article/details/gt2cplziael.html

Java: String.join(", ", list)
来源：http://dali.gzhubu.top/Article/details/gt2vvibghbt.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yueranfly.top/Article/details/gt2usopocxe.html

Ruby: arr.join(", ")
来源：http://dali.fengsongda.top/Article/details/gt2zvjdokju.html

C#:   string.Join(", ", list)
来源：http://dali.daria6918.cn/Article/details/gt2shkleupw.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2ctklpyzq.html

E. 字符串处理
来源：http://dali.ivvv.top/Article/details/gt2zmkabrgi.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2pgeawkuo.html

[E01] 拼接字符串
来源：http://dali.nwbrower.top/Article/details/gt2efnprvyz.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yanxiufei.cn/Article/details/gt2ylnbztei.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.nanxuanxn.top/Article/details/gt2edfdblqs.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.kuanghao11.cn/Article/details/gt2sypvocij.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sufxvd.cn/Article/details/gt2dchluxnz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.9152youxi.cn/Article/details/gt2xluxjgpu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xinyue.icu/Article/details/gt2tdylpzzi.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.bjfxy.top/Article/details/gt2tzanxfjm.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gt2abzjojka.html

[E02] 重复字符串
来源：http://dali.zhengqikj.top/Article/details/gt2mctrytsu.html

Py:   "ab" * 3
来源：http://dali.ehwqpu.com/Article/details/gt2taonbnst.html

PHP:  str_repeat("ab", 3);
来源：http://dali.wangshuangyany.cn/Article/details/gt2vxlthrwc.html

JS:   "ab".repeat(3)
来源：http://dali.yj202588.top/Article/details/gt2pkkxvoet.html

TS:   "ab".repeat(3)
来源：http://dali.xinyue.icu/Article/details/gt2rfiqrjvv.html

Java: "ab".repeat(3)
来源：http://dali.gotoacloud.top/Article/details/gt2dhufjbvn.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.daxiang520.top/Article/details/gt2ywoyzrdx.html

Ruby: "ab" * 3
来源：http://dali.ehwqpu.com/Article/details/gt2pwhvvbsl.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cdnleiting.top/Article/details/gt2svfbohih.html

[E03] 截取子串
来源：http://dali.shangyingyoupin.top/Article/details/gt2putgftdm.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.chenlongwang.top/Article/details/gt2gndbffgg.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cdnleiting.top/Article/details/gt2icvmtyjy.html


<!-- 参考信息 -->