代发 wailian999

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gt2irazflvi.html

Go:   func add(a, b int) int
来源：http://dali.zhixingplan.top/Article/details/gt2mzqlbmrk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.nwbrower.top/Article/details/gt2yxknragm.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.316326.xyz/Article/details/gt2qdrhozgw.html

[C14] 泛型函数
来源：http://dali.redwolf501.top/Article/details/gt2xwcuzehe.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xylfe.cn/Article/details/gt2mzkyevsb.html

PHP:  // 无泛型
来源：http://dali.jinqigfzy.top/Article/details/gt2fuhnebbw.html

JS:   // 无泛型
来源：http://dali.yj202588.top/Article/details/gt2lgagbqge.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.0kj1m.cn/Article/details/gt2sblkuivx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2cgmvqlyk.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.nwbrower.top/Article/details/gt2jqprfqxc.html

Ruby: # 无泛型
来源：http://dali.pengpengdd.cyou/Article/details/gt2ejxvzerz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jqgufenzy.top/Article/details/gt2jmbxpfys.html

[C15] 解构 / 展开参数
来源：http://dali.pycfn.com/Article/details/gt2nnsbznyn.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.nanxuanxn.top/Article/details/gt2tcutozxd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.fengsongda.top/Article/details/gt2tbztvymk.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2uaakhkij.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.tanke756.top/Article/details/gt2fnvumrhl.html

Java: // 无解构
来源：http://dali.nanxinkj.top/Article/details/gt2qdwzcuiw.html

Go:   // 无解构
来源：http://dali.pengpengdd.cyou/Article/details/gt2fryieayk.html

Ruby: a, b = pair
来源：http://dali.nanxuanxn.top/Article/details/gt2zbardivg.html

C#:   var (a, b) = pair;
来源：http://dali.hongshengwenyu.top/Article/details/gt2pqqqbmxs.html

[C16] 函数 / 方法重载
来源：http://dali.ivvv.top/Article/details/gt2qjioynbw.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.redwolf501.top/Article/details/gt2njlspoue.html

PHP:  // 无重载
来源：http://dali.yj202588.top/Article/details/gt2dsrvavei.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xziqi.cn/Article/details/gt2whgjgmdg.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.wangdashe.top/Article/details/gt2veplqmmu.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yj20258.top/Article/details/gt2daklpeqi.html

Go:   // 无重载：用不同函数名
来源：http://dali.yangfankeji.com/Article/details/gt2nxlirprf.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hammf.cn/Article/details/gt2hsmrbdws.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2tujuhbbf.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2ijeoyrox.html

D. 数组 / 列表 / 集合
来源：http://dali.chenjidiqi.icu/Article/details/gt2ugyhogsb.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2sgbhiing.html

[D01] 创建数组 / 列表
来源：http://dali.dianchejie.cn/Article/details/gt2prfesfby.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hfpthk.cn/Article/details/gt2dpkuzxkq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.pengpengdd.cyou/Article/details/gt2rkggjnzy.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.guowangkeji.top/Article/details/gt2xnlodxxy.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zycfv.cn/Article/details/gt2pojqvici.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2masrztyj.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.vqdsnc.cn/Article/details/gt2uzeoagcv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhiwuduotai.top/Article/details/gt2kgideqef.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.pengpengdd.cyou/Article/details/gt2vbaarkby.html

[D02] 追加元素到末尾
来源：http://dali.hnqzz.top/Article/details/gt2qcdimeea.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fjjhmpex.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhiwuduotai.top/Article/details/gt2mtykafkf.html

JS:   arr.push(4);
来源：http://dali.jyoumei.cn/Article/details/gt2qqmkltna.html

TS:   arr.push(4);
来源：http://dali.redwolf501.top/Article/details/gt2frxlqffk.html

Java: list.add(4);
来源：http://dali.hnqzz.top/Article/details/gt2fjtjxvap.html

Go:   arr = append(arr, 4)
来源：http://dali.cucudq.cn/Article/details/gt2dlvhuxpb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.nwbrower.top/Article/details/gt2hqilzacg.html

C#:   list.Add(4);
来源：http://dali.fengsongda.top/Article/details/gt2cyvfgomq.html

[D03] 在指定位置插入元素
来源：http://dali.tanke756.top/Article/details/gt2dbqpjrvp.html

Py:   arr.insert(0, 0)
来源：http://dali.zdqjudy.top/Article/details/gt2atxfntvz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.nwbrower.top/Article/details/gt2zyvpfugs.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shangyingyoupin.top/Article/details/gt2fqilpuyn.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2slnkxkel.html

Java: list.add(0, 0);
来源：http://dali.xuetiantiany.cn/Article/details/gt2wdfdmuxf.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yongpay.top/Article/details/gt2stunsrpq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2klsfyfas.html

C#:   list.Insert(0, 0);
来源：http://dali.yonumen.top/Article/details/gt2mngtbxmk.html

[D04] 删除元素
来源：http://dali.cucudq.cn/Article/details/gt2cuxpigck.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jinqigfzy.top/Article/details/gt2strhbvqw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.daria6918.cn/Article/details/gt2tuvauojm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yuxming.cn/Article/details/gt2gigphwft.html

TS:   arr.splice(0, 1);
来源：http://dali.wangdashe.top/Article/details/gt2eqjvcncd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zycfv.cn/Article/details/gt2mysgooxp.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.aibaodan.cn/Article/details/gt2tciddqdv.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.pengpengdd.cyou/Article/details/gt2rnckvwyi.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sweek.top/Article/details/gt2mlqrfxot.html

[D05] 访问与修改元素
来源：http://dali.ppjwa.cn/Article/details/gt2zzebupcw.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sxryk.cn/Article/details/gt2tgvjjodk.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ivvv.top/Article/details/gt2yomutytu.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.feifeiyinyue.top/Article/details/gt2jgznirux.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zdqjudy.top/Article/details/gt2wfagmtzy.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jiagoushi.top/Article/details/gt2urfrhfae.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xylfe.cn/Article/details/gt2gxgfybqa.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.vqdsnc.cn/Article/details/gt2ucmsdvct.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cdnleiting.top/Article/details/gt2wbrvrrny.html

[D06] 数组长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pjsaglwi.html

Py:   len(arr)
来源：http://dali.yuxming.cn/Article/details/gt2fmpaorbo.html

PHP:  count($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2kqfpgavs.html

JS:   arr.length
来源：http://dali.daria6918.cn/Article/details/gt2coyohmek.html

TS:   arr.length
来源：http://dali.ivvv.top/Article/details/gt2udltgwby.html

Java: list.size();
来源：http://dali.vqdsnc.cn/Article/details/gt2qclaqptr.html

Go:   len(arr)
来源：http://dali.yangfankeji.com/Article/details/gt2eihxokhn.html

Ruby: arr.length; arr.size
来源：http://dali.shangyingyoupin.top/Article/details/gt2rulbnvsc.html

C#:   list.Count;
来源：http://dali.ivvv.top/Article/details/gt2usdojigj.html

[D07] 切片 / 取子数组
来源：http://dali.ydzc1.top/Article/details/gt2asvdcqqw.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.9152youxi.cn/Article/details/gt2tfdzzycj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dehczopm.html

JS:   arr.slice(1, 4);
来源：http://dali.aizwys.cn/Article/details/gt2ropvonxw.html

TS:   arr.slice(1, 4);
来源：http://dali.sxryk.cn/Article/details/gt2xwghvbpd.html

Java: list.subList(1, 4);
来源：http://dali.vqdsnc.cn/Article/details/gt2ifnnvuaa.html

Go:   arr[1:4]
来源：http://dali.hysaishi.cn/Article/details/gt2nzljafff.html

Ruby: arr[1, 3]
来源：http://dali.guannengcc.top/Article/details/gt2lapawgkp.html

C#:   list.GetRange(1, 3);
来源：http://dali.mhx1999.top/Article/details/gt2jvvegiwf.html

[D08] 合并两个数组
来源：http://dali.cdnleiting.top/Article/details/gt2ummzyssa.html

Py:   a + b;  a.extend(b)
来源：http://dali.pycfn.com/Article/details/gt2daxkbhjg.html

PHP:  array_merge($a, $b);
来源：http://dali.pengpengdd.cyou/Article/details/gt2rszvnnoc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.guannengcc.top/Article/details/gt2zbeqoxdj.html

TS:   [...a, ...b];
来源：http://dali.gzhubu.top/Article/details/gt2lwgnjwjc.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.cheryme.top/Article/details/gt2yrwmnzbx.html

Go:   append(a, b...)
来源：http://dali.sufxvd.cn/Article/details/gt2epkubrfg.html

Ruby: a + b;  a.concat(b)
来源：http://dali.fzhhl.top/Article/details/gt2gdnuveiz.html

C#:   a.Concat(b).ToList()
来源：http://dali.nwbrower.top/Article/details/gt2ervuqeqb.html

[D09] 排序（升序）
来源：http://dali.sufxvd.cn/Article/details/gt2wmklizcp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sweek.top/Article/details/gt2jmjvvvpc.html

PHP:  sort($arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2jcbzxyja.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ydzc1.top/Article/details/gt2rpesalvy.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vyifetdo.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.snrcjt.cn/Article/details/gt2ncsvjxml.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zycfv.cn/Article/details/gt2dplvzhek.html

Ruby: arr.sort
来源：http://dali.aizwys.cn/Article/details/gt2ahqgsbiy.html

C#:   list.Sort();
来源：http://dali.wangshuangyany.cn/Article/details/gt2qfiflked.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.guannengcc.top/Article/details/gt2odyhsass.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.fzhhl.top/Article/details/gt2fchrdfiy.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.dashuyun.cn/Article/details/gt2qaqllrlf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sxryk.cn/Article/details/gt2bilgxlsc.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenzaomai.com/Article/details/gt2plahuskk.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hywenlv.cn/Article/details/gt2vxlgepvb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pobbjhfz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xinyue.icu/Article/details/gt2eerokrxs.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shzxlz.cn/Article/details/gt2frjqqnyj.html

[D11] 反转数组
来源：http://dali.fengsongda.top/Article/details/gt2xojragaf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.pycfn.com/Article/details/gt2pbqqdjlo.html

PHP:  array_reverse($arr);
来源：http://dali.yonumen.top/Article/details/gt2epjouqed.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.kuanghao11.cn/Article/details/gt2ysmjomrd.html

TS:   [...arr].reverse();
来源：http://dali.yj202588.top/Article/details/gt2reuhabdz.html

Java: Collections.reverse(list);
来源：http://dali.pycfn.com/Article/details/gt2ziklkkkg.html

Go:   slices.Reverse(arr)
来源：http://dali.hysaishi.cn/Article/details/gt2cuuzbnvo.html

Ruby: arr.reverse
来源：http://dali.zycfv.cn/Article/details/gt2nabituhz.html

C#:   list.Reverse();
来源：http://dali.jinqigufen.top/Article/details/gt2mnpmfncw.html

[D12] 查找元素下标
来源：http://dali.vqdsnc.cn/Article/details/gt2udtjimte.html

Py:   arr.index(x);  x in arr
来源：http://dali.cashguo.top/Article/details/gt2lbyzxiwu.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yj20258.top/Article/details/gt2oqizipgu.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yvedp.cn/Article/details/gt2snpiylbs.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hfpthk.cn/Article/details/gt2vgmjarrq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2dpmtvczz.html

Go:   slices.Index(arr, x)
来源：http://dali.guannengcc.top/Article/details/gt2suuinwhv.html

Ruby: arr.index(x)
来源：http://dali.mhx1999.top/Article/details/gt2xppagiei.html

C#:   list.IndexOf(x);
来源：http://dali.wangshuangyany.cn/Article/details/gt2wosxrufe.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ybcxt.top/Article/details/gt2vkjzgprp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ybcxt.top/Article/details/gt2hohqfzlj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.sufxvd.cn/Article/details/gt2fzuhjirb.html

JS:   arr.filter(x => x > 3)
来源：http://dali.vqdsnc.cn/Article/details/gt2xudrfqre.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gzhubu.top/Article/details/gt2odkuhvbl.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cdnleiting.top/Article/details/gt2hcuherkj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.daria6918.cn/Article/details/gt2qjwlypoz.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jyoumei.cn/Article/details/gt2hdqzzpxu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.birdmap.top/Article/details/gt2dgeohodp.html

[D14] 映射转换（每个元素变形）
来源：http://dali.gotoacloud.top/Article/details/gt2tujdnkwo.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hnqzz.top/Article/details/gt2hodrthwc.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2erzhejew.html

JS:   arr.map(x => x * 2)
来源：http://dali.yongpay.top/Article/details/gt2iltqutqg.html

TS:   arr.map(x => x * 2)
来源：http://dali.c1oappe.top/Article/details/gt2xoxqncip.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sufxvd.cn/Article/details/gt2yfuxxbos.html

Go:   // 手写循环
来源：http://dali.yuxming.cn/Article/details/gt2ifcrsxvs.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yangfankeji.com/Article/details/gt2mvhfodjs.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gt2ydnvcieo.html

[D15] 去重
来源：http://dali.nanxinkj.top/Article/details/gt2njwblsdw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gogol.net.cn/Article/details/gt2iqdbbdej.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2bptllcfc.html

JS:   [...new Set(arr)]
来源：http://dali.vqdsnc.cn/Article/details/gt2ougayvdo.html

TS:   [...new Set(arr)]
来源：http://dali.cashguo.top/Article/details/gt2kksghkda.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.aibaodan.cn/Article/details/gt2ludrlscd.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.tanke756.top/Article/details/gt2tslsvtbl.html

Ruby: arr.uniq
来源：http://dali.wangdashe.top/Article/details/gt2dystzxep.html

C#:   list.Distinct().ToList()
来源：http://dali.jianghu66.top/Article/details/gt2uwwbacdt.html

[D16] 求和与平均值
来源：http://dali.chenlongwang.top/Article/details/gt2kvovotzu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2hhjgxyjs.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.tianlin.xyz/Article/details/gt2tsavnjar.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hammf.cn/Article/details/gt2wvkhztgz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jokdfzba.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.quarkkingdee.top/Article/details/gt2hklhyctd.html

Go:   // 手写循环累加
来源：http://dali.mhx1999.top/Article/details/gt2fktjclyc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zycfv.cn/Article/details/gt2gvtvonpi.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhiwuduotai.top/Article/details/gt2jplftubv.html

[D17] 最大值与最小值
来源：http://dali.ppjwa.cn/Article/details/gt2hlymwiwh.html

Py:   max(arr);  min(arr)
来源：http://dali.fzhhl.top/Article/details/gt2jkcpyari.html

PHP:  max($arr);  min($arr);
来源：http://dali.redwolf501.top/Article/details/gt2jxjridlm.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jianghu66.top/Article/details/gt2peoikvtj.html

TS:   Math.max(...arr);
来源：http://dali.316326.xyz/Article/details/gt2bapwxzzn.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.mhx1999.top/Article/details/gt2inbyyevk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2pgffvige.html

Ruby: arr.max;  arr.min
来源：http://dali.yvedp.cn/Article/details/gt2hekwhnih.html

C#:   list.Max();  list.Min()
来源：http://dali.shzxlz.cn/Article/details/gt2dfwaffbr.html

[D18] 扁平化嵌套数组
来源：http://dali.jyoumei.cn/Article/details/gt2edmpemlh.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhiwuduotai.top/Article/details/gt2kkquubwh.html

PHP:  array_merge(...$nested);
来源：http://dali.xuanzx.com/Article/details/gt2zaddxres.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hongshengwenyu.top/Article/details/gt2kchesljz.html

TS:   nested.flat();
来源：http://dali.svipenyu.cn/Article/details/gt2szdesajg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2hqzpiqfz.html

Go:   // 手写双层循环
来源：http://dali.vqdsnc.cn/Article/details/gt2rmutsxqp.html

Ruby: nested.flatten
来源：http://dali.chenjidiqi.icu/Article/details/gt2nnuxbtgv.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sweek.top/Article/details/gt2odgveuur.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2lhhnxjul.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2geuxygyr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.vqdsnc.cn/Article/details/gt2icgokjyp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhoulong.xyz/Article/details/gt2mnykvqey.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.nanxuanxn.top/Article/details/gt2jzgwheul.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cdnleiting.top/Article/details/gt2zhplgxta.html

Go:   // 手写 map[string][]T
来源：http://dali.xziqi.cn/Article/details/gt2lvrfgwyt.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cheryme.top/Article/details/gt2vmbfomrg.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.fengsongda.top/Article/details/gt2fgwrbuqe.html

[D20] 统计每个元素出现次数
来源：http://dali.shangyingyoupin.top/Article/details/gt2qncbzucc.html

Py:   Counter(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2zzpckjfu.html

PHP:  array_count_values($arr);
来源：http://dali.nanxinkj.top/Article/details/gt2tfnhncha.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fzhhl.top/Article/details/gt2lxdvtcto.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nanxuanxn.top/Article/details/gt2rbawlzvw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.haohaochexian.top/Article/details/gt2zemaneys.html

Go:   // 手写 map[T]int
来源：http://dali.birdmap.top/Article/details/gt2bwfvxctk.html

Ruby: arr.tally
来源：http://dali.cqqwz.cn/Article/details/gt2bcynzfjo.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yangfankeji.com/Article/details/gt2sqjduxtn.html

[D21] 判断是否包含某元素
来源：http://dali.vqdsnc.cn/Article/details/gt2othrcyif.html

Py:   x in arr
来源：http://dali.mhx1999.top/Article/details/gt2jhecrgxp.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shangyingyoupin.top/Article/details/gt2qabeimvb.html

JS:   arr.includes(x)
来源：http://dali.haohaochexian.top/Article/details/gt2rzjnlsuj.html

TS:   arr.includes(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wclhrjre.html

Java: list.contains(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2kntsbbyb.html

Go:   slices.Contains(arr, x)
来源：http://dali.ybcxt.top/Article/details/gt2ymdhtwlz.html

Ruby: arr.include?(x)
来源：http://dali.ivvv.top/Article/details/gt2cbswyqts.html

C#:   list.Contains(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2toppcpbl.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yueranfly.top/Article/details/gt2kwpqgtte.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.havefunace.top/Article/details/gt2gszgowom.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.pengpengdd.cyou/Article/details/gt2piwmsbwp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yvedp.cn/Article/details/gt2cejfuipo.html

TS:   [...arr];
来源：http://dali.guannengcc.top/Article/details/gt2ihcnoguj.html

Java: new ArrayList<>(list);
来源：http://dali.sweek.top/Article/details/gt2anyapdmg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.guannengcc.top/Article/details/gt2exvjydlp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.daxiang520.top/Article/details/gt2ekxwpqiz.html

C#:   new List<int>(list);
来源：http://dali.shzxlz.cn/Article/details/gt2xhdhkyya.html

[D23] reduce 累积计算
来源：http://dali.xuanzx.com/Article/details/gt2vfztscwc.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ivvv.top/Article/details/gt2gbyaepgd.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.pengpengdd.cyou/Article/details/gt2cdpwbvbh.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ybcxt.top/Article/details/gt2yuplsmbo.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenzaomai.com/Article/details/gt2nmgepkoq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sysykeji.top/Article/details/gt2xhociisc.html

Go:   // 手写循环
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vhnrjirf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yvedp.cn/Article/details/gt2nposhgyq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.tian-w.cn/Article/details/gt2uhuodmnh.html

[D24] 字典 / Map 基本操作
来源：http://dali.bjfxy.top/Article/details/gt2tqqudfgi.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xuanzx.com/Article/details/gt2wbabfcsr.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jyoumei.cn/Article/details/gt2srjzqtqa.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.snrcjt.cn/Article/details/gt2wfmcjbre.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xziqi.cn/Article/details/gt2kyvlztal.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.vqdsnc.cn/Article/details/gt2brbdzjas.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ppjwa.cn/Article/details/gt2eagsccge.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.316326.xyz/Article/details/gt2ifbczlye.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.vqdsnc.cn/Article/details/gt2dgtqxogb.html

[D25] Set 集合去重与交并差
来源：http://dali.nwbrower.top/Article/details/gt2gfglpomv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cdnleiting.top/Article/details/gt2exbmgxik.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.birdmap.top/Article/details/gt2igzmodbm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.c1oappe.top/Article/details/gt2uxtvxcpi.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yanxiufei.cn/Article/details/gt2cdnonqig.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2zrjpsltg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhengqikj.top/Article/details/gt2pjmolfeu.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zdqjudy.top/Article/details/gt2sgwbucqv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.guannengcc.top/Article/details/gt2mxshkwjy.html

[D26] 数组转字符串
来源：http://dali.gogol.net.cn/Article/details/gt2wytutetb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.gogol.net.cn/Article/details/gt2ipddxpsc.html

PHP:  implode(", ", $arr);
来源：http://dali.smart0.xyz/Article/details/gt2kfioiqkn.html

JS:   arr.join(", ")
来源：http://dali.tianlin.xyz/Article/details/gt2wepgtisi.html

TS:   arr.join(", ")
来源：http://dali.hnxiangtu.top/Article/details/gt2wsrpkyre.html

Java: String.join(", ", list)
来源：http://dali.jianghu66.top/Article/details/gt2zrlmtmup.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cdnleiting.top/Article/details/gt2kkxsypyi.html

Ruby: arr.join(", ")
来源：http://dali.xuetiantiany.cn/Article/details/gt2yyrturvc.html

C#:   string.Join(", ", list)
来源：http://dali.chenzaomai.com/Article/details/gt2fztrttpe.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2qmhzvwbl.html

E. 字符串处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aggpiuak.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2fldizobr.html

[E01] 拼接字符串
来源：http://dali.meibo888.top/Article/details/gt2dlmzkwpf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yueranfly.top/Article/details/gt2yvjvtaiw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xylfe.cn/Article/details/gt2idbpbgtg.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.haohaochexian.top/Article/details/gt2zqwkanaq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258.top/Article/details/gt2vgxxvhld.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2zaalrhuh.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cucudq.cn/Article/details/gt2kjnyuzhx.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yongpay.top/Article/details/gt2gnzmcpbs.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xuanzx.com/Article/details/gt2qltphhpk.html

[E02] 重复字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2usmdfgak.html

Py:   "ab" * 3
来源：http://dali.zhiwuduotai.top/Article/details/gt2toyskdyz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhiwuduotai.top/Article/details/gt2gwcgyufu.html

JS:   "ab".repeat(3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2rmumajcx.html

TS:   "ab".repeat(3)
来源：http://dali.yangfankeji.com/Article/details/gt2khvskcof.html

Java: "ab".repeat(3)
来源：http://dali.shuidangran.top/Article/details/gt2sycmywxv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.havefunace.top/Article/details/gt2lsejcgrj.html

Ruby: "ab" * 3
来源：http://dali.dianchejie.cn/Article/details/gt2vlwqlgzy.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yuxming.cn/Article/details/gt2yltsyxnl.html

[E03] 截取子串
来源：http://dali.redwolf501.top/Article/details/gt2mlofbuil.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.andypj.xyz/Article/details/gt2ashudvcg.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gt2psvmjyuh.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ivvv.top/Article/details/gt2qqxsfwrn.html

TS:   s.slice(1, 4)
来源：http://dali.jqgufenzy.top/Article/details/gt2npnkgoht.html

Java: s.substring(1, 4)
来源：http://dali.aibaodan.cn/Article/details/gt2ryvhryet.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zgivxyjv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yueranfly.top/Article/details/gt2dwphjrge.html

C#:   s.Substring(1, 3)
来源：http://dali.sysykeji.top/Article/details/gt2dfllrgji.html

[E04] 查找子串位置
来源：http://dali.zhoulong.xyz/Article/details/gt2tgiwiwgp.html

Py:   s.find("x");  s.index("x")
来源：http://dali.pengpengdd.cyou/Article/details/gt2qcbwarda.html


<!-- 参考信息 -->