代发 wailian999

Go:   func() { fmt.Println("run") }()
来源：http://dali.hnxiangtu.top/Article/details/gt2aifktczn.html

Ruby: -> { puts "run" }.call
来源：http://dali.dianchejie.cn/Article/details/gt2xvdoxtlc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xylfe.cn/Article/details/gt2mvzcwtyn.html

[C13] 类型声明 / 类型注解
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2chzujplf.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhiwuduotai.top/Article/details/gt2zzwbnzes.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yangfankeji.com/Article/details/gt2txltantf.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.tianlin.xyz/Article/details/gt2ociaqebv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gt2ihcnycmm.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.cashguo.top/Article/details/gt2obfatxmp.html

Go:   func add(a, b int) int
来源：http://dali.guowangkeji.top/Article/details/gt2xbiylnge.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sufxvd.cn/Article/details/gt2pfkotqwt.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxtuddn.html

[C14] 泛型函数
来源：http://dali.vqdsnc.cn/Article/details/gt2kpakbuex.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.gzhubu.top/Article/details/gt2vyaaziyd.html

PHP:  // 无泛型
来源：http://dali.fzhhl.top/Article/details/gt2htsajspq.html

JS:   // 无泛型
来源：http://dali.yangfankeji.com/Article/details/gt2gkvcjpsa.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yvedp.cn/Article/details/gt2fntfqexp.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yuanzhike.top/Article/details/gt2porfgvhv.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.dashuyun.cn/Article/details/gt2jxvstofb.html

Ruby: # 无泛型
来源：http://dali.hnxiangtu.top/Article/details/gt2wqyuptya.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.chenzaomai.com/Article/details/gt2udvmzylp.html

[C15] 解构 / 展开参数
来源：http://dali.0kj1m.cn/Article/details/gt2pfrzhdup.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yanxiufei.cn/Article/details/gt2horiolvo.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cheryme.top/Article/details/gt2ilqwwgzp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zycfv.cn/Article/details/gt2mykzzcmh.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.havefunace.top/Article/details/gt2saxhrkuk.html

Java: // 无解构
来源：http://dali.xuanzx.com/Article/details/gt2hyqzlnyp.html

Go:   // 无解构
来源：http://dali.cqqwz.cn/Article/details/gt2gtgbijdd.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvvvgcy.html

C#:   var (a, b) = pair;
来源：http://dali.haohaochexian.top/Article/details/gt2lruguvhs.html

[C16] 函数 / 方法重载
来源：http://dali.daria6918.cn/Article/details/gt2iyglfjoz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hfpthk.cn/Article/details/gt2psfcfwlz.html

PHP:  // 无重载
来源：http://dali.feifeiyinyue.top/Article/details/gt2rabdrrwv.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhoulong.xyz/Article/details/gt2ssyyttay.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.sxryk.cn/Article/details/gt2jtieafqd.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hfpthk.cn/Article/details/gt2uhoxboxy.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhiwuduotai.top/Article/details/gt2ozycdvps.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gzhubu.top/Article/details/gt2ejawgrsl.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2cdigmqez.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2iyllabrs.html

D. 数组 / 列表 / 集合
来源：http://dali.sxryk.cn/Article/details/gt2brmyzdah.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2gerqunce.html

[D01] 创建数组 / 列表
来源：http://dali.xziqi.cn/Article/details/gt2jsavllkb.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.aizwys.cn/Article/details/gt2osmmmmjk.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cdnleiting.top/Article/details/gt2jboireqg.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hongshengwenyu.top/Article/details/gt2wjzlehoc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.aizwys.cn/Article/details/gt2giaxltlg.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.wangdashe.top/Article/details/gt2bcvosplw.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cheryme.top/Article/details/gt2afcdriyo.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xuetiantiany.cn/Article/details/gt2iluwxsff.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shangyingyoupin.top/Article/details/gt2ilppgrmm.html

[D02] 追加元素到末尾
来源：http://dali.shuidangran.top/Article/details/gt2fybhjxix.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2sgflkhfo.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gogol.net.cn/Article/details/gt2feglozby.html

JS:   arr.push(4);
来源：http://dali.hfpthk.cn/Article/details/gt2miwmrmrb.html

TS:   arr.push(4);
来源：http://dali.daxiang520.top/Article/details/gt2owpacwsd.html

Java: list.add(4);
来源：http://dali.jqgfzy.top/Article/details/gt2sxlxnhkt.html

Go:   arr = append(arr, 4)
来源：http://dali.gaohongyu789.top/Article/details/gt2xzsneqoi.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cashguo.top/Article/details/gt2mujnokuq.html

C#:   list.Add(4);
来源：http://dali.yvedp.cn/Article/details/gt2swrwyjgg.html

[D03] 在指定位置插入元素
来源：http://dali.guannengcc.top/Article/details/gt2ghkdbilt.html

Py:   arr.insert(0, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yvdpsirb.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xuetiantiany.cn/Article/details/gt2stqvaaoh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.smart0.xyz/Article/details/gt2wejxympy.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hnqzz.top/Article/details/gt2rlcgsebu.html

Java: list.add(0, 0);
来源：http://dali.iojbl.cn/Article/details/gt2ahdbdeeu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yonumen.top/Article/details/gt2vlixspjp.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shzxlz.cn/Article/details/gt2idhqefsy.html

C#:   list.Insert(0, 0);
来源：http://dali.yj20258888.top/Article/details/gt2qzdepvrv.html

[D04] 删除元素
来源：http://dali.jlsjyb.cn/Article/details/gt2iecmpzzo.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.aibaodan.cn/Article/details/gt2daxnxqrz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.chenlongwang.top/Article/details/gt2fiogmown.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xziqi.cn/Article/details/gt2hwoyfyms.html

TS:   arr.splice(0, 1);
来源：http://dali.shzxlz.cn/Article/details/gt2kbpfqxdu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.birdmap.top/Article/details/gt2xpapjhkt.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shzxlz.cn/Article/details/gt2kbqyxery.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.redwolf501.top/Article/details/gt2xixmzcdv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yueranfly.top/Article/details/gt2jslawama.html

[D05] 访问与修改元素
来源：http://dali.dashuyun.cn/Article/details/gt2wiuabzir.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.quarkkingdee.top/Article/details/gt2ktqiovlo.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gsivluad.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.snrcjt.cn/Article/details/gt2pvugiyru.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.9152youxi.cn/Article/details/gt2ghvwmask.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.sysykeji.top/Article/details/gt2hvpavppl.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zycfv.cn/Article/details/gt2luuvukhv.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.daxiang520.top/Article/details/gt2efecxwrw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.chenlongwang.top/Article/details/gt2uozudels.html

[D06] 数组长度
来源：http://dali.aizwys.cn/Article/details/gt2wbbblyny.html

Py:   len(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2cjhpilqb.html

PHP:  count($arr);
来源：http://dali.zdqjudy.top/Article/details/gt2txbfvhct.html

JS:   arr.length
来源：http://dali.0kj1m.cn/Article/details/gt2dmttdtwi.html

TS:   arr.length
来源：http://dali.redwolf501.top/Article/details/gt2fwjkpuha.html

Java: list.size();
来源：http://dali.quarkkingdee.top/Article/details/gt2vcknfrja.html

Go:   len(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2nonfygug.html

Ruby: arr.length; arr.size
来源：http://dali.gzhubu.top/Article/details/gt2kxmaxssf.html

C#:   list.Count;
来源：http://dali.vqdsnc.cn/Article/details/gt2slfxkqdt.html

[D07] 切片 / 取子数组
来源：http://dali.zdqjudy.top/Article/details/gt2czuwjrho.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cashguo.top/Article/details/gt2pwjndmmk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.meibo888.top/Article/details/gt2pbslhszf.html

JS:   arr.slice(1, 4);
来源：http://dali.bjfxy.top/Article/details/gt2yjbajggg.html

TS:   arr.slice(1, 4);
来源：http://dali.0kj1m.cn/Article/details/gt2mqsdaskk.html

Java: list.subList(1, 4);
来源：http://dali.ivvv.top/Article/details/gt2neeevmer.html

Go:   arr[1:4]
来源：http://dali.yanxiufei.cn/Article/details/gt2jkhmexnn.html

Ruby: arr[1, 3]
来源：http://dali.zhongyouzk.top/Article/details/gt2blvdnbhe.html

C#:   list.GetRange(1, 3);
来源：http://dali.gaohongyu789.top/Article/details/gt2wxmprsdj.html

[D08] 合并两个数组
来源：http://dali.yj20258.top/Article/details/gt2ynpeqebk.html

Py:   a + b;  a.extend(b)
来源：http://dali.havefunace.top/Article/details/gt2nrmglksd.html

PHP:  array_merge($a, $b);
来源：http://dali.guowangkeji.top/Article/details/gt2mlxgfhlz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sxryk.cn/Article/details/gt2xawenhlh.html

TS:   [...a, ...b];
来源：http://dali.tianlin.xyz/Article/details/gt2hpbcgebq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.gotoacloud.top/Article/details/gt2mbfygukd.html

Go:   append(a, b...)
来源：http://dali.hongshengwenyu.top/Article/details/gt2fwwphkxm.html

Ruby: a + b;  a.concat(b)
来源：http://dali.mhx1999.top/Article/details/gt2tcyznzod.html

C#:   a.Concat(b).ToList()
来源：http://dali.jqgfzy.top/Article/details/gt2nmtcabqw.html

[D09] 排序（升序）
来源：http://dali.shuidangran.top/Article/details/gt2oktmhkao.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ybcxt.top/Article/details/gt2rqdvpesd.html

PHP:  sort($arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2dadnhivw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yongpay.top/Article/details/gt2posljdxk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xziqi.cn/Article/details/gt2lchapfqt.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.iojbl.cn/Article/details/gt2mloprlbo.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yj20258888.top/Article/details/gt2ciwdjkqx.html

Ruby: arr.sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bwvdlxhh.html

C#:   list.Sort();
来源：http://dali.iojbl.cn/Article/details/gt2crbvflbo.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.tanke756.top/Article/details/gt2lsjtclvk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yj20258888.top/Article/details/gt2vnvxkihl.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.aizwys.cn/Article/details/gt2ttzqbcfk.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tanke756.top/Article/details/gt2ikrpahlh.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nanxinkj.top/Article/details/gt2qtdmrxhj.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.guannengcc.top/Article/details/gt2gopctmop.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jqgfzy.top/Article/details/gt2pcifiqbw.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.quarkkingdee.top/Article/details/gt2nvadbkku.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ftgvjain.html

[D11] 反转数组
来源：http://dali.jiagoushi.top/Article/details/gt2rmaxiani.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.daria6918.cn/Article/details/gt2ldhsnbir.html

PHP:  array_reverse($arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2aqrbhbsn.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yangfankeji.com/Article/details/gt2yzawisow.html

TS:   [...arr].reverse();
来源：http://dali.redwolf501.top/Article/details/gt2devjlfqk.html

Java: Collections.reverse(list);
来源：http://dali.aibaodan.cn/Article/details/gt2zatlzswe.html

Go:   slices.Reverse(arr)
来源：http://dali.tanke756.top/Article/details/gt2tvtdmquu.html

Ruby: arr.reverse
来源：http://dali.fzhhl.top/Article/details/gt2qgvaucji.html

C#:   list.Reverse();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2musfdwgq.html

[D12] 查找元素下标
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rzzcvipu.html

Py:   arr.index(x);  x in arr
来源：http://dali.vqdsnc.cn/Article/details/gt2ehokjxjj.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.aizwys.cn/Article/details/gt2wfnbjngq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.snrcjt.cn/Article/details/gt2nsfiltux.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bvfggeui.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2luieqvtt.html

Go:   slices.Index(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gt2zoqmofdd.html

Ruby: arr.index(x)
来源：http://dali.xylfe.cn/Article/details/gt2eoqodvkb.html

C#:   list.IndexOf(x);
来源：http://dali.pengpengdd.cyou/Article/details/gt2eamtrhit.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sufxvd.cn/Article/details/gt2yhdatypm.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yangfankeji.com/Article/details/gt2mvowheit.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.gotoacloud.top/Article/details/gt2xilaiqqe.html

JS:   arr.filter(x => x > 3)
来源：http://dali.pycfn.com/Article/details/gt2twyrsyfi.html

TS:   arr.filter(x => x > 3)
来源：http://dali.havefunace.top/Article/details/gt2oahziwtb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jyoumei.cn/Article/details/gt2ltiiruvb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hfpthk.cn/Article/details/gt2vamdwctt.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.pengpengdd.cyou/Article/details/gt2pjqaapnn.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yuxming.cn/Article/details/gt2ycoowepw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ppjwa.cn/Article/details/gt2gnehovax.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.aibaodan.cn/Article/details/gt2axezzzpq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.chenzaomai.com/Article/details/gt2psipnqvc.html

JS:   arr.map(x => x * 2)
来源：http://dali.yj20258888.top/Article/details/gt2mfkasmdq.html

TS:   arr.map(x => x * 2)
来源：http://dali.fengsongda.top/Article/details/gt2pvxndhbs.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.mhx1999.top/Article/details/gt2sapxiwpb.html

Go:   // 手写循环
来源：http://dali.mhx1999.top/Article/details/gt2yogteztf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.9152youxi.cn/Article/details/gt2npjxdcaw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vnhejnmu.html

[D15] 去重
来源：http://dali.chenjidiqi.icu/Article/details/gt2nndyvbtt.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jiagoushi.top/Article/details/gt2nlctlhae.html

PHP:  array_unique($arr);
来源：http://dali.tian-w.cn/Article/details/gt2zbgcmzmc.html

JS:   [...new Set(arr)]
来源：http://dali.yangfankeji.com/Article/details/gt2wdbxfacv.html

TS:   [...new Set(arr)]
来源：http://dali.316326.xyz/Article/details/gt2wrzqhmva.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.feifeiyinyue.top/Article/details/gt2fvitdosi.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.tian-w.cn/Article/details/gt2iuilpbyg.html

Ruby: arr.uniq
来源：http://dali.zdqjudy.top/Article/details/gt2vtmwxvwm.html

C#:   list.Distinct().ToList()
来源：http://dali.tanke756.top/Article/details/gt2bhsfegwn.html

[D16] 求和与平均值
来源：http://dali.yj20258888.top/Article/details/gt2knlotxxa.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2emjzrzpj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ewftpqyd.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj20258.top/Article/details/gt2xzfaugyk.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhengqikj.top/Article/details/gt2ofctwbgs.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ydzc1.top/Article/details/gt2oaagmnir.html

Go:   // 手写循环累加
来源：http://dali.iojbl.cn/Article/details/gt2umdhgvdc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cashguo.top/Article/details/gt2nxnermdl.html

C#:   list.Sum();  list.Average()
来源：http://dali.wangshuangyany.cn/Article/details/gt2fuiprkss.html

[D17] 最大值与最小值
来源：http://dali.guowangkeji.top/Article/details/gt2zkbwqcaz.html

Py:   max(arr);  min(arr)
来源：http://dali.ppjwa.cn/Article/details/gt2rhztdewo.html

PHP:  max($arr);  min($arr);
来源：http://dali.meibo888.top/Article/details/gt2xkbwnmgn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.tian-w.cn/Article/details/gt2ygmupixe.html

TS:   Math.max(...arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dqlsaxos.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gotoacloud.top/Article/details/gt2dyobwcvx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yj20258.top/Article/details/gt2ppalihiw.html

Ruby: arr.max;  arr.min
来源：http://dali.gotoacloud.top/Article/details/gt2okannati.html

C#:   list.Max();  list.Min()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ovjwlxwd.html

[D18] 扁平化嵌套数组
来源：http://dali.nanxinkj.top/Article/details/gt2hhghwhmb.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.haohaochexian.top/Article/details/gt2jbnrgwyn.html

PHP:  array_merge(...$nested);
来源：http://dali.guannengcc.top/Article/details/gt2qpfrevbn.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cashguo.top/Article/details/gt2awvedbjm.html

TS:   nested.flat();
来源：http://dali.jiagoushi.top/Article/details/gt2qsjvedrb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2jxcjmzxk.html

Go:   // 手写双层循环
来源：http://dali.chenjidiqi.icu/Article/details/gt2gftmnsmf.html

Ruby: nested.flatten
来源：http://dali.ivvv.top/Article/details/gt2ajtktbgq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.haohaochexian.top/Article/details/gt2nksfhwkd.html

[D19] 按字段分组
来源：http://dali.andypj.xyz/Article/details/gt2khedcged.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yvedp.cn/Article/details/gt2ihxhxjkx.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2brldbtme.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cqqwz.cn/Article/details/gt2jjdeqybl.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.bjfxy.top/Article/details/gt2epakssln.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.nanxinkj.top/Article/details/gt2uphfgkhi.html

Go:   // 手写 map[string][]T
来源：http://dali.hongshengwenyu.top/Article/details/gt2lzxklyps.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhongyouzk.top/Article/details/gt2ouakuots.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cqqwz.cn/Article/details/gt2kvblkuwp.html

[D20] 统计每个元素出现次数
来源：http://dali.ydzc1.top/Article/details/gt2jplfbfjd.html

Py:   Counter(arr)
来源：http://dali.ivvv.top/Article/details/gt2ietevkjm.html

PHP:  array_count_values($arr);
来源：http://dali.daxiang520.top/Article/details/gt2uhnsllou.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2jestvtht.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuxming.cn/Article/details/gt2zzmtwrwm.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jinqigufen.top/Article/details/gt2rpiskdvr.html

Go:   // 手写 map[T]int
来源：http://dali.daria6918.cn/Article/details/gt2yqcwaxig.html

Ruby: arr.tally
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pveqgsbq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.feifeiyinyue.top/Article/details/gt2puaaakxi.html

[D21] 判断是否包含某元素
来源：http://dali.birdmap.top/Article/details/gt2rmkqvfpa.html

Py:   x in arr
来源：http://dali.aizwys.cn/Article/details/gt2vsayusqa.html

PHP:  in_array($x, $arr, true);
来源：http://dali.svipenyu.cn/Article/details/gt2cjjaurlw.html

JS:   arr.includes(x)
来源：http://dali.yj20258.top/Article/details/gt2bfkfjqge.html

TS:   arr.includes(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hanckefp.html

Java: list.contains(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2arukjqul.html

Go:   slices.Contains(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gt2qcqnyydb.html

Ruby: arr.include?(x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mgctipit.html

C#:   list.Contains(x)
来源：http://dali.zhixingplan.top/Article/details/gt2dkeumcjb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bcbtxhwh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ybcxt.top/Article/details/gt2fxdnwlti.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.andypj.xyz/Article/details/gt2jvoahyjy.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yvedp.cn/Article/details/gt2hvwudbys.html

TS:   [...arr];
来源：http://dali.sweek.top/Article/details/gt2xkqxjudo.html

Java: new ArrayList<>(list);
来源：http://dali.yongpay.top/Article/details/gt2nyucfkls.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.meibo888.top/Article/details/gt2itpxrlzi.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yj202588.top/Article/details/gt2iscsuioi.html

C#:   new List<int>(list);
来源：http://dali.cdnleiting.top/Article/details/gt2ctwbmxvi.html

[D23] reduce 累积计算
来源：http://dali.shangyingyoupin.top/Article/details/gt2bwodgmji.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xinyue.icu/Article/details/gt2bedjzfbc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tpopltos.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sxryk.cn/Article/details/gt2agvstxdu.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hywenlv.cn/Article/details/gt2yksfyyki.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yj20258.top/Article/details/gt2nqdkmzal.html

Go:   // 手写循环
来源：http://dali.ehwqpu.com/Article/details/gt2gqkyxyef.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yj202588.top/Article/details/gt2ipjcwmdp.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.iojbl.cn/Article/details/gt2kgigzcee.html

[D24] 字典 / Map 基本操作
来源：http://dali.gotoacloud.top/Article/details/gt2mruilblc.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.gogol.net.cn/Article/details/gt2uadsmsxd.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.bjfxy.top/Article/details/gt2rxtxhgyc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2sljorpun.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gt2nneyyybp.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cqqwz.cn/Article/details/gt2mblauyue.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.fzhhl.top/Article/details/gt2otyrcain.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.tianlin.xyz/Article/details/gt2yqpplsrq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.316326.xyz/Article/details/gt2jfpqmpkt.html

[D25] Set 集合去重与交并差
来源：http://dali.dashuyun.cn/Article/details/gt2wtcgunsz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hnxiangtu.top/Article/details/gt2fgodoxbe.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhengqikj.top/Article/details/gt2zdjrxamn.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhixingplan.top/Article/details/gt2twvhnrzk.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.guannengcc.top/Article/details/gt2zyllfgsm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hysaishi.cn/Article/details/gt2xnsflicw.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.havefunace.top/Article/details/gt2oxamrutq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2ofwqlyvq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2gkqsxkry.html

[D26] 数组转字符串
来源：http://dali.kuanghao11.cn/Article/details/gt2abfbbjot.html

Py:   ", ".join(map(str, arr))
来源：http://dali.daxiang520.top/Article/details/gt2nkjlcyld.html

PHP:  implode(", ", $arr);
来源：http://dali.birdmap.top/Article/details/gt2bqcphzky.html

JS:   arr.join(", ")
来源：http://dali.ppjwa.cn/Article/details/gt2oevplzee.html

TS:   arr.join(", ")
来源：http://dali.daria6918.cn/Article/details/gt2dqugqiuu.html

Java: String.join(", ", list)
来源：http://dali.hnxiangtu.top/Article/details/gt2pqutyege.html

Go:   strings.Join(strs, ", ")
来源：http://dali.gogol.net.cn/Article/details/gt2cyynenwa.html

Ruby: arr.join(", ")
来源：http://dali.sufxvd.cn/Article/details/gt2nonodgva.html

C#:   string.Join(", ", list)
来源：http://dali.jlsjyb.cn/Article/details/gt2cdbsqbgc.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2dyqpgxto.html

E. 字符串处理
来源：http://dali.ybcxt.top/Article/details/gt2jsisxfgj.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2rxtxhlhc.html

[E01] 拼接字符串
来源：http://dali.guannengcc.top/Article/details/gt2ujtpxrxh.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jinqigfzy.top/Article/details/gt2rhxqvqmi.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yangfankeji.com/Article/details/gt2ywyicweg.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.vqdsnc.cn/Article/details/gt2sfkhuhma.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zdqjudy.top/Article/details/gt2bntjfusy.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhengqikj.top/Article/details/gt2tbkqkxcy.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cucudq.cn/Article/details/gt2smnctclr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ybcxt.top/Article/details/gt2fsdnmdqn.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gt2nokiuoco.html

[E02] 重复字符串
来源：http://dali.yj20258.top/Article/details/gt2prharlnf.html

Py:   "ab" * 3
来源：http://dali.nwbrower.top/Article/details/gt2oepyoxcn.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jqgufenzy.top/Article/details/gt2yqojgzlg.html

JS:   "ab".repeat(3)
来源：http://dali.9152youxi.cn/Article/details/gt2iacweaim.html

TS:   "ab".repeat(3)
来源：http://dali.yuxming.cn/Article/details/gt2mgftjder.html

Java: "ab".repeat(3)
来源：http://dali.chenlongwang.top/Article/details/gt2pmzxgghd.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.fengsongda.top/Article/details/gt2djvofwcj.html

Ruby: "ab" * 3
来源：http://dali.chenlongwang.top/Article/details/gt2rkwvmnvd.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.havefunace.top/Article/details/gt2mzvucpyw.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2gjuiswpl.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.guannengcc.top/Article/details/gt2bkbnwjtm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gt2kkskyale.html


<!-- 参考信息 -->