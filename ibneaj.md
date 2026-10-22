代发 wailian999

Go:   func() { fmt.Println("run") }()
来源：http://dali.jianghu66.top/Article/details/gt2vwhhslso.html

Ruby: -> { puts "run" }.call
来源：http://dali.yj20258.top/Article/details/gt2qrjpzqry.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.tianlin.xyz/Article/details/gt2kgfpwzle.html

[C13] 类型声明 / 类型注解
来源：http://dali.nanxinkj.top/Article/details/gt2vtnqkkby.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.feifeiyinyue.top/Article/details/gt2cyivexem.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yongpay.top/Article/details/gt2lyjuafjm.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.andypj.xyz/Article/details/gt2ahnnysoj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2rvgirmys.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2kwemvqtf.html

Go:   func add(a, b int) int
来源：http://dali.jianghu66.top/Article/details/gt2xsxnvfnp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.feifeiyinyue.top/Article/details/gt2vdpdkppt.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.sweek.top/Article/details/gt2bwhjghwn.html

[C14] 泛型函数
来源：http://dali.iojbl.cn/Article/details/gt2tkpvccam.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xziqi.cn/Article/details/gt2nmfcttvw.html

PHP:  // 无泛型
来源：http://dali.shangyingyoupin.top/Article/details/gt2nznthgsw.html

JS:   // 无泛型
来源：http://dali.sysykeji.top/Article/details/gt2kyufuzrt.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.dianchejie.cn/Article/details/gt2sslxzemt.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jianghu66.top/Article/details/gt2vtzsjgbo.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.havefunace.top/Article/details/gt2rvanftfl.html

Ruby: # 无泛型
来源：http://dali.zhixingplan.top/Article/details/gt2keorayds.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.daria6918.cn/Article/details/gt2nneitane.html

[C15] 解构 / 展开参数
来源：http://dali.zhoulong.xyz/Article/details/gt2kjtclwor.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.quarkkingdee.top/Article/details/gt2jevvpffw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.tianlin.xyz/Article/details/gt2defmopcv.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.gotoacloud.top/Article/details/gt2nlknqgnu.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.daxiang520.top/Article/details/gt2dikldrpr.html

Java: // 无解构
来源：http://dali.hfpthk.cn/Article/details/gt2eswkawmb.html

Go:   // 无解构
来源：http://dali.jinqigfzy.top/Article/details/gt2mpqgxllc.html

Ruby: a, b = pair
来源：http://dali.hfpthk.cn/Article/details/gt2oounzlbf.html

C#:   var (a, b) = pair;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wlhwuuur.html

[C16] 函数 / 方法重载
来源：http://dali.sweek.top/Article/details/gt2ctotfjrl.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hfpthk.cn/Article/details/gt2smvnqgcd.html

PHP:  // 无重载
来源：http://dali.dianchejie.cn/Article/details/gt2yedugreh.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.gotoacloud.top/Article/details/gt2mibrboed.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhixingplan.top/Article/details/gt2ovsdouem.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.gogol.net.cn/Article/details/gt2ezoihtwg.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhengqikj.top/Article/details/gt2yehiqpxi.html

Ruby: # 无重载：靠动态参数
来源：http://dali.aibaodan.cn/Article/details/gt2uwvcsuek.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jqgfzy.top/Article/details/gt2gfsuhvly.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2pstpyeqd.html

D. 数组 / 列表 / 集合
来源：http://dali.yj202588.top/Article/details/gt2qxybzyck.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mzfufsvs.html

[D01] 创建数组 / 列表
来源：http://dali.mhx1999.top/Article/details/gt2zqjkfgpc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.316326.xyz/Article/details/gt2zmchkzvt.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhoulong.xyz/Article/details/gt2smginkxc.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eanynffv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.nwbrower.top/Article/details/gt2kkkxlpbe.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.redwolf501.top/Article/details/gt2onybhksm.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hammf.cn/Article/details/gt2hcuxmcer.html

Ruby: arr = [1, 2, 3]
来源：http://dali.aibaodan.cn/Article/details/gt2cukouysd.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yueranfly.top/Article/details/gt2hrrtzfgo.html

[D02] 追加元素到末尾
来源：http://dali.tanke756.top/Article/details/gt2oofeyzbg.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.fengsongda.top/Article/details/gt2jhzeanjm.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yanxiufei.cn/Article/details/gt2ebxxmysw.html

JS:   arr.push(4);
来源：http://dali.kuanghao11.cn/Article/details/gt2goynjfnc.html

TS:   arr.push(4);
来源：http://dali.hnqzz.top/Article/details/gt2bhanjtwn.html

Java: list.add(4);
来源：http://dali.nwbrower.top/Article/details/gt2scvfqqkb.html

Go:   arr = append(arr, 4)
来源：http://dali.yongpay.top/Article/details/gt2ayloqbnd.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sxryk.cn/Article/details/gt2vysirupz.html

C#:   list.Add(4);
来源：http://dali.meibo888.top/Article/details/gt2jiapsthv.html

[D03] 在指定位置插入元素
来源：http://dali.guannengcc.top/Article/details/gt2dqdptcoi.html

Py:   arr.insert(0, 0)
来源：http://dali.hammf.cn/Article/details/gt2eahshzuf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xuanzx.com/Article/details/gt2bftzjqnd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.mhx1999.top/Article/details/gt2mpvtzljy.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gt2cschasbm.html

Java: list.add(0, 0);
来源：http://dali.sweek.top/Article/details/gt2wzuyohts.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sysykeji.top/Article/details/gt2ucyngspg.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rctapoiw.html

C#:   list.Insert(0, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2evynrcjo.html

[D04] 删除元素
来源：http://dali.xylfe.cn/Article/details/gt2rbugkljm.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rcgyowgm.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.dashuyun.cn/Article/details/gt2lngzrfhm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhixingplan.top/Article/details/gt2bxrdtymw.html

TS:   arr.splice(0, 1);
来源：http://dali.chenjidiqi.icu/Article/details/gt2peakzgyv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yj202588.top/Article/details/gt2bmspjllx.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.andypj.xyz/Article/details/gt2wzjjksii.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhoulong.xyz/Article/details/gt2zdxoyrhe.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xinyue.icu/Article/details/gt2stfzxzrt.html

[D05] 访问与修改元素
来源：http://dali.jinghuilouyu.cn/Article/details/gt2odsbzjjq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gt2wcvbrxoh.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.sysykeji.top/Article/details/gt2nspxxcoz.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.nanxinkj.top/Article/details/gt2kbxmaaqe.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.shangyingyoupin.top/Article/details/gt2qekszyso.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.gaohongyu789.top/Article/details/gt2vhdvcwbn.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.andypj.xyz/Article/details/gt2xglvwfis.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shzxlz.cn/Article/details/gt2vrybksip.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.gaohongyu789.top/Article/details/gt2zyyuwduw.html

[D06] 数组长度
来源：http://dali.pengpengdd.cyou/Article/details/gt2kzazwdjl.html

Py:   len(arr)
来源：http://dali.snrcjt.cn/Article/details/gt2tnvxktod.html

PHP:  count($arr);
来源：http://dali.gogol.net.cn/Article/details/gt2rzxitdlr.html

JS:   arr.length
来源：http://dali.haohaochexian.top/Article/details/gt2jazkkimn.html

TS:   arr.length
来源：http://dali.chenzaomai.com/Article/details/gt2ojbqtroa.html

Java: list.size();
来源：http://dali.xziqi.cn/Article/details/gt2nbgcoatz.html

Go:   len(arr)
来源：http://dali.cheryme.top/Article/details/gt2lvbuagtv.html

Ruby: arr.length; arr.size
来源：http://dali.shzxlz.cn/Article/details/gt2dvyoxwfz.html

C#:   list.Count;
来源：http://dali.yueranfly.top/Article/details/gt2fjgeatpw.html

[D07] 切片 / 取子数组
来源：http://dali.jlsjyb.cn/Article/details/gt2ujecnzvp.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.iojbl.cn/Article/details/gt2twckzlfx.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iukccifu.html

JS:   arr.slice(1, 4);
来源：http://dali.ybcxt.top/Article/details/gt2qjpwddbu.html

TS:   arr.slice(1, 4);
来源：http://dali.ybcxt.top/Article/details/gt2drfdvegg.html

Java: list.subList(1, 4);
来源：http://dali.xylfe.cn/Article/details/gt2pvktlxxf.html

Go:   arr[1:4]
来源：http://dali.fengsongda.top/Article/details/gt2mpckbenk.html

Ruby: arr[1, 3]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vazikppg.html

C#:   list.GetRange(1, 3);
来源：http://dali.xuetiantiany.cn/Article/details/gt2epzoxovf.html

[D08] 合并两个数组
来源：http://dali.nanxuanxn.top/Article/details/gt2fznxoxgv.html

Py:   a + b;  a.extend(b)
来源：http://dali.hfpthk.cn/Article/details/gt2mnasytpy.html

PHP:  array_merge($a, $b);
来源：http://dali.hnxiangtu.top/Article/details/gt2yzoudjqy.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yangfankeji.com/Article/details/gt2krqoadkz.html

TS:   [...a, ...b];
来源：http://dali.nanxinkj.top/Article/details/gt2dsljqdje.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zycfv.cn/Article/details/gt2pgreplup.html

Go:   append(a, b...)
来源：http://dali.hongshengwenyu.top/Article/details/gt2wsnsblol.html

Ruby: a + b;  a.concat(b)
来源：http://dali.smart0.xyz/Article/details/gt2bjcmavqw.html

C#:   a.Concat(b).ToList()
来源：http://dali.zdqjudy.top/Article/details/gt2mbqbgjkd.html

[D09] 排序（升序）
来源：http://dali.9152youxi.cn/Article/details/gt2owycqfoo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gaohongyu789.top/Article/details/gt2apmdubnh.html

PHP:  sort($arr);
来源：http://dali.gzhubu.top/Article/details/gt2ugirwvyw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yanxiufei.cn/Article/details/gt2gwofwcyu.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.tanke756.top/Article/details/gt2nlrwjplg.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jxatqqqv.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2ywhdzbam.html

Ruby: arr.sort
来源：http://dali.ehwqpu.com/Article/details/gt2qaqgxalq.html

C#:   list.Sort();
来源：http://dali.xylfe.cn/Article/details/gt2xzzqwfuk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.aizwys.cn/Article/details/gt2iefoxqlw.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.0kj1m.cn/Article/details/gt2qcsabaeb.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.andypj.xyz/Article/details/gt2jekognxj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guannengcc.top/Article/details/gt2nnbaehfz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yuxming.cn/Article/details/gt2rvitkpau.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sweek.top/Article/details/gt2ffrwgomt.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.andypj.xyz/Article/details/gt2zvjaqvme.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.vqdsnc.cn/Article/details/gt2qzhdisll.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ppjwa.cn/Article/details/gt2aychkvhs.html

[D11] 反转数组
来源：http://dali.sweek.top/Article/details/gt2qeobvvnu.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.chenzaomai.com/Article/details/gt2abcuwocj.html

PHP:  array_reverse($arr);
来源：http://dali.havefunace.top/Article/details/gt2cgfxjstt.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.sysykeji.top/Article/details/gt2qdxzfkyy.html

TS:   [...arr].reverse();
来源：http://dali.316326.xyz/Article/details/gt2hcmpjpyd.html

Java: Collections.reverse(list);
来源：http://dali.yuxming.cn/Article/details/gt2wjteorzi.html

Go:   slices.Reverse(arr)
来源：http://dali.yangfankeji.com/Article/details/gt2yezydwdx.html

Ruby: arr.reverse
来源：http://dali.andypj.xyz/Article/details/gt2dxssknlj.html

C#:   list.Reverse();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2chmhxebx.html

[D12] 查找元素下标
来源：http://dali.guowangkeji.top/Article/details/gt2hwhxwfwy.html

Py:   arr.index(x);  x in arr
来源：http://dali.gzhubu.top/Article/details/gt2hqzmvpbo.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhixingplan.top/Article/details/gt2uobudjmg.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xylfe.cn/Article/details/gt2ceogeyao.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nwbrower.top/Article/details/gt2plyacisu.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.guannengcc.top/Article/details/gt2ouhparcd.html

Go:   slices.Index(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gt2xnfzelmi.html

Ruby: arr.index(x)
来源：http://dali.nwbrower.top/Article/details/gt2dvdvrqbd.html

C#:   list.IndexOf(x);
来源：http://dali.andypj.xyz/Article/details/gt2skvimpab.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yvedp.cn/Article/details/gt2rkfoqdsr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yvedp.cn/Article/details/gt2crhfcsgv.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.chenjidiqi.icu/Article/details/gt2grvagjmv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.smart0.xyz/Article/details/gt2ptakoawc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.nanxinkj.top/Article/details/gt2lcwmrkcm.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hnxiangtu.top/Article/details/gt2cluxqwvp.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hongshengwenyu.top/Article/details/gt2wekjxgpt.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yongpay.top/Article/details/gt2euqmtfmf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.snrcjt.cn/Article/details/gt2fjqcykym.html

[D14] 映射转换（每个元素变形）
来源：http://dali.nwbrower.top/Article/details/gt2talonafm.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.haohaochexian.top/Article/details/gt2pngmkdil.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2txvktnhc.html

JS:   arr.map(x => x * 2)
来源：http://dali.yanxiufei.cn/Article/details/gt2xyycqsaf.html

TS:   arr.map(x => x * 2)
来源：http://dali.cucudq.cn/Article/details/gt2wbqebzhw.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hywenlv.cn/Article/details/gt2rdbfwmal.html

Go:   // 手写循环
来源：http://dali.yanxiufei.cn/Article/details/gt2gpjkefhm.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.daxiang520.top/Article/details/gt2vgzxuhzf.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2meugrkzw.html

[D15] 去重
来源：http://dali.yvedp.cn/Article/details/gt2nfvibvaw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jiagoushi.top/Article/details/gt2ksrmsinh.html

PHP:  array_unique($arr);
来源：http://dali.nanxinkj.top/Article/details/gt2mjvaqrmb.html

JS:   [...new Set(arr)]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nsfzmsoy.html

TS:   [...new Set(arr)]
来源：http://dali.shzxlz.cn/Article/details/gt2luiqxzsb.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.redwolf501.top/Article/details/gt2xyvcjogq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.snrcjt.cn/Article/details/gt2ugdrkumx.html

Ruby: arr.uniq
来源：http://dali.yangfankeji.com/Article/details/gt2dawjeeac.html

C#:   list.Distinct().ToList()
来源：http://dali.hnxiangtu.top/Article/details/gt2yjxhzzkd.html

[D16] 求和与平均值
来源：http://dali.chenlongwang.top/Article/details/gt2wgoaqvko.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.pycfn.com/Article/details/gt2jhgwllaw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gaohongyu789.top/Article/details/gt2vkxxwcre.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cdnleiting.top/Article/details/gt2srkupgxu.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daxiang520.top/Article/details/gt2exblekwl.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.svipenyu.cn/Article/details/gt2tjhmmamy.html

Go:   // 手写循环累加
来源：http://dali.sxryk.cn/Article/details/gt2caqjokry.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xinyue.icu/Article/details/gt2bbnlaqut.html

C#:   list.Sum();  list.Average()
来源：http://dali.chenlongwang.top/Article/details/gt2gnlffkal.html

[D17] 最大值与最小值
来源：http://dali.hysaishi.cn/Article/details/gt2iwkveost.html

Py:   max(arr);  min(arr)
来源：http://dali.jiagoushi.top/Article/details/gt2gfdkyrzn.html

PHP:  max($arr);  min($arr);
来源：http://dali.jiagoushi.top/Article/details/gt2btlexyak.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ppjwa.cn/Article/details/gt2eeticbgl.html

TS:   Math.max(...arr);
来源：http://dali.yuxming.cn/Article/details/gt2mgucnvkw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yongpay.top/Article/details/gt2ubbjtkqv.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sweek.top/Article/details/gt2cvfdexsc.html

Ruby: arr.max;  arr.min
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vhnczqkw.html

C#:   list.Max();  list.Min()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kwxpdscj.html

[D18] 扁平化嵌套数组
来源：http://dali.ppjwa.cn/Article/details/gt2ygfsspqn.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.andypj.xyz/Article/details/gt2kejvdrey.html

PHP:  array_merge(...$nested);
来源：http://dali.9152youxi.cn/Article/details/gt2wyceqwcm.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cashguo.top/Article/details/gt2zjujopzk.html

TS:   nested.flat();
来源：http://dali.jlsjyb.cn/Article/details/gt2xamnmkiz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tfnsvtqv.html

Go:   // 手写双层循环
来源：http://dali.yonumen.top/Article/details/gt2fhkhrrkk.html

Ruby: nested.flatten
来源：http://dali.daria6918.cn/Article/details/gt2mszmursi.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sysykeji.top/Article/details/gt2mbwehsit.html

[D19] 按字段分组
来源：http://dali.jlsjyb.cn/Article/details/gt2bpuerhmu.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2satudnqx.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhixingplan.top/Article/details/gt2xovvfjyj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jinghuilouyu.cn/Article/details/gt2curvarjc.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.nwbrower.top/Article/details/gt2sehxhbqe.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.smart0.xyz/Article/details/gt2cmdhxoim.html

Go:   // 手写 map[string][]T
来源：http://dali.meibo888.top/Article/details/gt2fydxiymv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jiagoushi.top/Article/details/gt2zbdiiiul.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cucudq.cn/Article/details/gt2qyegptnp.html

[D20] 统计每个元素出现次数
来源：http://dali.316326.xyz/Article/details/gt2ulmxnium.html

Py:   Counter(arr)
来源：http://dali.sufxvd.cn/Article/details/gt2fuegqudk.html

PHP:  array_count_values($arr);
来源：http://dali.yueranfly.top/Article/details/gt2ubmbcqke.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yangfankeji.com/Article/details/gt2yqhspfxz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ygupynyu.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.birdmap.top/Article/details/gt2btcdpvcl.html

Go:   // 手写 map[T]int
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ymkwxwdg.html

Ruby: arr.tally
来源：http://dali.bjfxy.top/Article/details/gt2kaegwjxm.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.dianchejie.cn/Article/details/gt2macejxay.html

[D21] 判断是否包含某元素
来源：http://dali.quarkkingdee.top/Article/details/gt2lfrnxjpw.html

Py:   x in arr
来源：http://dali.meibo888.top/Article/details/gt2fxkftfsg.html

PHP:  in_array($x, $arr, true);
来源：http://dali.aibaodan.cn/Article/details/gt2tdhdcufu.html

JS:   arr.includes(x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2nlcroisr.html

TS:   arr.includes(x)
来源：http://dali.ybcxt.top/Article/details/gt2lrioypog.html

Java: list.contains(x)
来源：http://dali.hywenlv.cn/Article/details/gt2bqjzxazk.html

Go:   slices.Contains(arr, x)
来源：http://dali.cashguo.top/Article/details/gt2whzcfwel.html

Ruby: arr.include?(x)
来源：http://dali.iojbl.cn/Article/details/gt2xxlwgype.html

C#:   list.Contains(x)
来源：http://dali.xinyue.icu/Article/details/gt2usdtegib.html

[D22] 复制数组（避免共享引用）
来源：http://dali.tian-w.cn/Article/details/gt2uygmfhfg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2joxqjjkx.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.vqdsnc.cn/Article/details/gt2jbxjiqmd.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yvedp.cn/Article/details/gt2dedtsfev.html

TS:   [...arr];
来源：http://dali.zhoulong.xyz/Article/details/gt2bldqnggj.html

Java: new ArrayList<>(list);
来源：http://dali.feifeiyinyue.top/Article/details/gt2mwkkdjik.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hysaishi.cn/Article/details/gt2rqrzhskr.html

Ruby: arr.dup;  arr.clone
来源：http://dali.vqdsnc.cn/Article/details/gt2mwguagzo.html

C#:   new List<int>(list);
来源：http://dali.xziqi.cn/Article/details/gt2mdwejdvd.html

[D23] reduce 累积计算
来源：http://dali.havefunace.top/Article/details/gt2fwdogqxs.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ybjnzzwr.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xinyue.icu/Article/details/gt2pjeyawol.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgfzy.top/Article/details/gt2zvlqcsot.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigfzy.top/Article/details/gt2cjjcyilw.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wgkpuyzm.html

Go:   // 手写循环
来源：http://dali.hnqzz.top/Article/details/gt2pevsskuk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kucwlhoc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cashguo.top/Article/details/gt2vvghrvkn.html

[D24] 字典 / Map 基本操作
来源：http://dali.yj202588.top/Article/details/gt2qavcnbol.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ivvv.top/Article/details/gt2vgkgewqz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.snrcjt.cn/Article/details/gt2ccgmrnzp.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ydzc1.top/Article/details/gt2czwkkmgr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yangfankeji.com/Article/details/gt2ruatcjqq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cashguo.top/Article/details/gt2kizfbspi.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jyoumei.cn/Article/details/gt2qfytmrrq.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ppjwa.cn/Article/details/gt2utcauxkw.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yuxming.cn/Article/details/gt2onkmclny.html

[D25] Set 集合去重与交并差
来源：http://dali.ehwqpu.com/Article/details/gt2axiugtud.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xuanzx.com/Article/details/gt2sadeupoj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhixingplan.top/Article/details/gt2gzmgjjaz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.nanxinkj.top/Article/details/gt2jxedeklc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.pycfn.com/Article/details/gt2hrsxoosh.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hkpglqpx.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ehwqpu.com/Article/details/gt2atpxmqrz.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.andypj.xyz/Article/details/gt2qbnpzsoh.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jiagoushi.top/Article/details/gt2dpxelofs.html

[D26] 数组转字符串
来源：http://dali.aibaodan.cn/Article/details/gt2imiqjiog.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rrvqanog.html

PHP:  implode(", ", $arr);
来源：http://dali.yangfankeji.com/Article/details/gt2ruhbkxgm.html

JS:   arr.join(", ")
来源：http://dali.xuanzx.com/Article/details/gt2dbpncgog.html

TS:   arr.join(", ")
来源：http://dali.zhixingplan.top/Article/details/gt2ajzhgfvo.html

Java: String.join(", ", list)
来源：http://dali.gaohongyu789.top/Article/details/gt2orlihuav.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ppjwa.cn/Article/details/gt2stfpxctn.html

Ruby: arr.join(", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tbrxebhp.html

C#:   string.Join(", ", list)
来源：http://dali.mhx1999.top/Article/details/gt2quoehoxx.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2ngdsrrpt.html

E. 字符串处理
来源：http://dali.ivvv.top/Article/details/gt2uipivcob.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2nlzgwbjt.html

[E01] 拼接字符串
来源：http://dali.mhx1999.top/Article/details/gt2wdbvmzsy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.0kj1m.cn/Article/details/gt2limxwtql.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zudjxocm.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuanzhike.top/Article/details/gt2tnmsvncu.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aizwys.cn/Article/details/gt2jpidwkya.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.dashuyun.cn/Article/details/gt2regqyyap.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.dianchejie.cn/Article/details/gt2fduhsrox.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhoulong.xyz/Article/details/gt2xxgpgwxl.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jianghu66.top/Article/details/gt2kvuhkixu.html

[E02] 重复字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2zlorwvsg.html

Py:   "ab" * 3
来源：http://dali.gotoacloud.top/Article/details/gt2atfsydrd.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shuidangran.top/Article/details/gt2dykkxyua.html

JS:   "ab".repeat(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hjgxazxr.html

TS:   "ab".repeat(3)
来源：http://dali.xylfe.cn/Article/details/gt2jwmgzggq.html

Java: "ab".repeat(3)
来源：http://dali.quarkkingdee.top/Article/details/gt2fmjxyyeu.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shuidangran.top/Article/details/gt2bahgyczu.html

Ruby: "ab" * 3
来源：http://dali.xziqi.cn/Article/details/gt2pfzovknw.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jqgufenzy.top/Article/details/gt2htjjdqdo.html

[E03] 截取子串
来源：http://dali.dianchejie.cn/Article/details/gt2mrbehkup.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.gzhubu.top/Article/details/gt2niukelmm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.iojbl.cn/Article/details/gt2cphuzqoh.html


<!-- 参考信息 -->