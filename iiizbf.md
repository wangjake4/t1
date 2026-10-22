代发 wailian999

Go:   func() { fmt.Println("run") }()
来源：http://dali.nwbrower.top/Article/details/gtfhhvbnyv.html

Ruby: -> { puts "run" }.call
来源：http://dali.pycfn.com/Article/details/gtkpqdaztv.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.tanke756.top/Article/details/gtpgpetcyz.html

[C13] 类型声明 / 类型注解
来源：http://dali.yueranfly.top/Article/details/gtkujdbeva.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jqgfzy.top/Article/details/gtynnukvzv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenzaomai.com/Article/details/gtfcedaxbx.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xuanzx.com/Article/details/gtnwcncbim.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtznatvtfn.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gtctwnwaku.html

Go:   func add(a, b int) int
来源：http://dali.0kj1m.cn/Article/details/gtmatteqpe.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.tianlin.xyz/Article/details/gtaobbmdab.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.shzxlz.cn/Article/details/gtxstgwphk.html

[C14] 泛型函数
来源：http://dali.sufxvd.cn/Article/details/gtznuqyoxn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.snrcjt.cn/Article/details/gtrfnvenvs.html

PHP:  // 无泛型
来源：http://dali.jinqigufen.top/Article/details/gtbafxdeyp.html

JS:   // 无泛型
来源：http://dali.gaohongyu789.top/Article/details/gthmkoyrau.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zycfv.cn/Article/details/gtltgxpykq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.feifeiyinyue.top/Article/details/gtwhotpgth.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.tianlin.xyz/Article/details/gtabzfuxew.html

Ruby: # 无泛型
来源：http://dali.316326.xyz/Article/details/gtvsoylfor.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.aibaodan.cn/Article/details/gtnjglkmqb.html

[C15] 解构 / 展开参数
来源：http://dali.quarkkingdee.top/Article/details/gtwyaruzgq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.guowangkeji.top/Article/details/gtgsfiyqzp.html

PHP:  [$a, $b] = $pair;
来源：http://dali.havefunace.top/Article/details/gtwsibmpqf.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.sxryk.cn/Article/details/gtkratjkou.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shzxlz.cn/Article/details/gtfpcqrvnt.html

Java: // 无解构
来源：http://dali.havefunace.top/Article/details/gtdyhuuqjv.html

Go:   // 无解构
来源：http://dali.pycfn.com/Article/details/gtrylnewbg.html

Ruby: a, b = pair
来源：http://dali.hammf.cn/Article/details/gtuvvddcmo.html

C#:   var (a, b) = pair;
来源：http://dali.tian-w.cn/Article/details/gtjtzhkvqg.html

[C16] 函数 / 方法重载
来源：http://dali.jinqigufen.top/Article/details/gtbjdtqfzn.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yangfankeji.com/Article/details/gtkquwcbzo.html

PHP:  // 无重载
来源：http://dali.nwbrower.top/Article/details/gttfoacbdq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.quarkkingdee.top/Article/details/gtwoutmdms.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yvedp.cn/Article/details/gtmjmkofeg.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhengqikj.top/Article/details/gtgzcwglmb.html

Go:   // 无重载：用不同函数名
来源：http://dali.wangshuangyany.cn/Article/details/gtyhgolpox.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yongpay.top/Article/details/gtrgaflbmu.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.sxryk.cn/Article/details/gtwkgyskqw.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtlyiwdugc.html

D. 数组 / 列表 / 集合
来源：http://dali.yueranfly.top/Article/details/gtviuilphf.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtjnnvlyho.html

[D01] 创建数组 / 列表
来源：http://dali.hywenlv.cn/Article/details/gttfabsvoz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shanyushiyangtech.top/Article/details/gtuwopkrxl.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yvedp.cn/Article/details/gttglutpik.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhiwuduotai.top/Article/details/gtrsjyncnt.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yangfankeji.com/Article/details/gtjsaxstav.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.vqdsnc.cn/Article/details/gtdmsipetw.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ehwqpu.com/Article/details/gtknjjjyip.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhoulong.xyz/Article/details/gtycanyysl.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.kuanghao11.cn/Article/details/gtpcljtofp.html

[D02] 追加元素到末尾
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlbgpppmf.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hnqzz.top/Article/details/gtjgehsmum.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.pengpengdd.cyou/Article/details/gtlrcdlmnt.html

JS:   arr.push(4);
来源：http://dali.cdnleiting.top/Article/details/gtqbetrnbf.html

TS:   arr.push(4);
来源：http://dali.gotoacloud.top/Article/details/gtkrzsasac.html

Java: list.add(4);
来源：http://dali.zhixingplan.top/Article/details/gtsyueiyjd.html

Go:   arr = append(arr, 4)
来源：http://dali.zdqjudy.top/Article/details/gtrvjwzlgd.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jinghuilouyu.cn/Article/details/gtplofshky.html

C#:   list.Add(4);
来源：http://dali.svipenyu.cn/Article/details/gtjorvhznm.html

[D03] 在指定位置插入元素
来源：http://dali.birdmap.top/Article/details/gteuduwhld.html

Py:   arr.insert(0, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtudlvomtp.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cdnleiting.top/Article/details/gtkbzrachq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.dianchejie.cn/Article/details/gtjhpqtbdp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.0kj1m.cn/Article/details/gtawpbuxly.html

Java: list.add(0, 0);
来源：http://dali.hnxiangtu.top/Article/details/gtyoyiredm.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhiwuduotai.top/Article/details/gtjohsblyk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shangyingyoupin.top/Article/details/gtqokuypsk.html

C#:   list.Insert(0, 0);
来源：http://dali.guowangkeji.top/Article/details/gttlkmdyyd.html

[D04] 删除元素
来源：http://dali.guannengcc.top/Article/details/gtsabmpaba.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ybcxt.top/Article/details/gtrlktlifa.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.cdnleiting.top/Article/details/gtvtcxytfj.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.birdmap.top/Article/details/gtnpswsone.html

TS:   arr.splice(0, 1);
来源：http://dali.gzhubu.top/Article/details/gtzgatsgsz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.dianchejie.cn/Article/details/gtbljshcdh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shangyingyoupin.top/Article/details/gtxamigorg.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yuanzhike.top/Article/details/gtqhaegskb.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sxryk.cn/Article/details/gtywaaoahu.html

[D05] 访问与修改元素
来源：http://dali.yvedp.cn/Article/details/gtpoulvavz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zdqjudy.top/Article/details/gtcinruvud.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.guannengcc.top/Article/details/gtxggbtoxu.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shangyingyoupin.top/Article/details/gtjoncagmq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.kuanghao11.cn/Article/details/gtwwxbsukw.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hywenlv.cn/Article/details/gtsycprggh.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.bjfxy.top/Article/details/gtvujbwzmm.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shangyingyoupin.top/Article/details/gtidkmvvnu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ydzc1.top/Article/details/gtiqdueljx.html

[D06] 数组长度
来源：http://dali.jianghu66.top/Article/details/gtcqlxlrhg.html

Py:   len(arr)
来源：http://dali.sysykeji.top/Article/details/gtkjqsmlbo.html

PHP:  count($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtiilmozcg.html

JS:   arr.length
来源：http://dali.ybcxt.top/Article/details/gtwcsfylfc.html

TS:   arr.length
来源：http://dali.feifeiyinyue.top/Article/details/gtkqzoejto.html

Java: list.size();
来源：http://dali.ehwqpu.com/Article/details/gtibgvmizr.html

Go:   len(arr)
来源：http://dali.fzhhl.top/Article/details/gtsqmyqjkh.html

Ruby: arr.length; arr.size
来源：http://dali.jyoumei.cn/Article/details/gtycylswdr.html

C#:   list.Count;
来源：http://dali.shzxlz.cn/Article/details/gtgvxozymg.html

[D07] 切片 / 取子数组
来源：http://dali.smart0.xyz/Article/details/gtmikqmhfn.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zycfv.cn/Article/details/gttdcyfntk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhixingplan.top/Article/details/gtrbalusnu.html

JS:   arr.slice(1, 4);
来源：http://dali.316326.xyz/Article/details/gtyeucneuz.html

TS:   arr.slice(1, 4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gttitqagia.html

Java: list.subList(1, 4);
来源：http://dali.cdnleiting.top/Article/details/gtdwtxxpna.html

Go:   arr[1:4]
来源：http://dali.yj202588.top/Article/details/gtemanjssp.html

Ruby: arr[1, 3]
来源：http://dali.cheryme.top/Article/details/gtgqzkpxfi.html

C#:   list.GetRange(1, 3);
来源：http://dali.redwolf501.top/Article/details/gtikbxkgms.html

[D08] 合并两个数组
来源：http://dali.yuanzhike.top/Article/details/gtodvszbvw.html

Py:   a + b;  a.extend(b)
来源：http://dali.0kj1m.cn/Article/details/gtdprwjlcg.html

PHP:  array_merge($a, $b);
来源：http://dali.nanxuanxn.top/Article/details/gtmsjfmfce.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.svipenyu.cn/Article/details/gtxszghidf.html

TS:   [...a, ...b];
来源：http://dali.jinghuilouyu.cn/Article/details/gtuduovmjt.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.smart0.xyz/Article/details/gtunclxpxc.html

Go:   append(a, b...)
来源：http://dali.sufxvd.cn/Article/details/gtthumtxjt.html

Ruby: a + b;  a.concat(b)
来源：http://dali.feifeiyinyue.top/Article/details/gthaxwekjw.html

C#:   a.Concat(b).ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gtruatcwhj.html

[D09] 排序（升序）
来源：http://dali.hnqzz.top/Article/details/gtfampiqoc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnqzz.top/Article/details/gtkptrxqhc.html

PHP:  sort($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtzhcziior.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yuanzhike.top/Article/details/gtwbgynwmc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.svipenyu.cn/Article/details/gtcsxbserl.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ehwqpu.com/Article/details/gtvjbvsmhp.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jianghu66.top/Article/details/gtsxrhlekz.html

Ruby: arr.sort
来源：http://dali.haohaochexian.top/Article/details/gtnafvvmon.html

C#:   list.Sort();
来源：http://dali.zdqjudy.top/Article/details/gtvffdhomh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.gogol.net.cn/Article/details/gtkrhgcfbx.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtklnzzcga.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cqqwz.cn/Article/details/gtmxhxvqft.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jlsjyb.cn/Article/details/gtmiujexcm.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenlongwang.top/Article/details/gtwacudlvq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.chenlongwang.top/Article/details/gtchilkxxt.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.dashuyun.cn/Article/details/gtvvhrwkzq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zdqjudy.top/Article/details/gtvdgnfgco.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.snrcjt.cn/Article/details/gtsafjlgpn.html

[D11] 反转数组
来源：http://dali.dashuyun.cn/Article/details/gtfedgqrqj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.sufxvd.cn/Article/details/gtplcrpvrb.html

PHP:  array_reverse($arr);
来源：http://dali.daxiang520.top/Article/details/gtqzztpavb.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yangfankeji.com/Article/details/gtfxspuara.html

TS:   [...arr].reverse();
来源：http://dali.cdnleiting.top/Article/details/gttukglnpx.html

Java: Collections.reverse(list);
来源：http://dali.chenjidiqi.icu/Article/details/gtudgstadu.html

Go:   slices.Reverse(arr)
来源：http://dali.yuxming.cn/Article/details/gtcplfdgcz.html

Ruby: arr.reverse
来源：http://dali.yj202588.top/Article/details/gtmukrcyou.html

C#:   list.Reverse();
来源：http://dali.yuxming.cn/Article/details/gtgfhtbnci.html

[D12] 查找元素下标
来源：http://dali.nwbrower.top/Article/details/gtubnlwwcs.html

Py:   arr.index(x);  x in arr
来源：http://dali.chenlongwang.top/Article/details/gtxwkxlsbu.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yueranfly.top/Article/details/gtqjoleodd.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenzaomai.com/Article/details/gtbpaultbi.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.316326.xyz/Article/details/gthgqvwdri.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ydzc1.top/Article/details/gtlvewltba.html

Go:   slices.Index(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrznzxhfw.html

Ruby: arr.index(x)
来源：http://dali.xylfe.cn/Article/details/gtqpvkikkb.html

C#:   list.IndexOf(x);
来源：http://dali.vqdsnc.cn/Article/details/gtngdjuimz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.feifeiyinyue.top/Article/details/gtnnsarjyw.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ivvv.top/Article/details/gtntzomfwb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhengqikj.top/Article/details/gtzlbsnvkw.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sweek.top/Article/details/gtvlnhqyqi.html

TS:   arr.filter(x => x > 3)
来源：http://dali.snrcjt.cn/Article/details/gtegbrykdp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jlsjyb.cn/Article/details/gtijxlmuno.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.birdmap.top/Article/details/gtcqivogoa.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yanxiufei.cn/Article/details/gtdggfweqt.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.0kj1m.cn/Article/details/gtvlnelvcv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.wangshuangyany.cn/Article/details/gtotgdwgwo.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jqgufenzy.top/Article/details/gtiktdshog.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yuxming.cn/Article/details/gtcxvsbwtz.html

JS:   arr.map(x => x * 2)
来源：http://dali.hywenlv.cn/Article/details/gtinezutag.html

TS:   arr.map(x => x * 2)
来源：http://dali.yuanzhike.top/Article/details/gtajcmbdap.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.iojbl.cn/Article/details/gteooiidls.html

Go:   // 手写循环
来源：http://dali.sysykeji.top/Article/details/gtgisurojd.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.bjfxy.top/Article/details/gtkvwkcvxo.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.iojbl.cn/Article/details/gtuenmyrqc.html

[D15] 去重
来源：http://dali.pycfn.com/Article/details/gtiffyceuw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hnqzz.top/Article/details/gtoeekcpvk.html

PHP:  array_unique($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtktreemdj.html

JS:   [...new Set(arr)]
来源：http://dali.hfpthk.cn/Article/details/gtgagbhinu.html

TS:   [...new Set(arr)]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlfdgpenv.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sweek.top/Article/details/gtrsitqipo.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.wangshuangyany.cn/Article/details/gtkgxfkcje.html

Ruby: arr.uniq
来源：http://dali.nanxinkj.top/Article/details/gttxcbvsab.html

C#:   list.Distinct().ToList()
来源：http://dali.zhengqikj.top/Article/details/gtgcsnejin.html

[D16] 求和与平均值
来源：http://dali.xuetiantiany.cn/Article/details/gthfdbxhyq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xinyue.icu/Article/details/gtghrkmluf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.9152youxi.cn/Article/details/gtxwfyrzqv.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fzhhl.top/Article/details/gtxfdoelsa.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtcicvozmb.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.chenzaomai.com/Article/details/gtkxqoyxty.html

Go:   // 手写循环累加
来源：http://dali.sysykeji.top/Article/details/gtowydjuxc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hammf.cn/Article/details/gtdggxkruw.html

C#:   list.Sum();  list.Average()
来源：http://dali.pengpengdd.cyou/Article/details/gtsazetjtp.html

[D17] 最大值与最小值
来源：http://dali.gotoacloud.top/Article/details/gteeewkyxf.html

Py:   max(arr);  min(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtrgohvuvi.html

PHP:  max($arr);  min($arr);
来源：http://dali.daria6918.cn/Article/details/gthoeylajf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hnxiangtu.top/Article/details/gtpwiquyan.html

TS:   Math.max(...arr);
来源：http://dali.yj20258888.top/Article/details/gtztszstaz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shzxlz.cn/Article/details/gtblihfmyz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xinyue.icu/Article/details/gtfcofwqhs.html

Ruby: arr.max;  arr.min
来源：http://dali.zdqjudy.top/Article/details/gtoxkfrwpo.html

C#:   list.Max();  list.Min()
来源：http://dali.kuanghao11.cn/Article/details/gthinfkemp.html

[D18] 扁平化嵌套数组
来源：http://dali.zycfv.cn/Article/details/gtjahvufvt.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.kuanghao11.cn/Article/details/gtreyrhvdv.html

PHP:  array_merge(...$nested);
来源：http://dali.ivvv.top/Article/details/gtvoeitiaf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.dashuyun.cn/Article/details/gtfnqvsqgu.html

TS:   nested.flat();
来源：http://dali.yuxming.cn/Article/details/gtceycbadb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cashguo.top/Article/details/gtbgcijdrb.html

Go:   // 手写双层循环
来源：http://dali.xuetiantiany.cn/Article/details/gtiwkkedgs.html

Ruby: nested.flatten
来源：http://dali.yj202588.top/Article/details/gtpmhmsxja.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ppjwa.cn/Article/details/gtvyqcuora.html

[D19] 按字段分组
来源：http://dali.guannengcc.top/Article/details/gtuxagmopw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.wangdashe.top/Article/details/gtssnixyla.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sxryk.cn/Article/details/gtjzxpjldm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.nanxinkj.top/Article/details/gtdjcawmek.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yueranfly.top/Article/details/gtggudgmwn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ivvv.top/Article/details/gtgaypohfi.html

Go:   // 手写 map[string][]T
来源：http://dali.fengsongda.top/Article/details/gtlrxynysu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.kuanghao11.cn/Article/details/gthfwjjoeo.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yongpay.top/Article/details/gtifmcwocz.html

[D20] 统计每个元素出现次数
来源：http://dali.birdmap.top/Article/details/gtipsxqumq.html

Py:   Counter(arr)
来源：http://dali.yvedp.cn/Article/details/gtbhqfpbmw.html

PHP:  array_count_values($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtsacneula.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sxryk.cn/Article/details/gtsqxpykwx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.smart0.xyz/Article/details/gtyddaianu.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.tianlin.xyz/Article/details/gtuiaaaidw.html

Go:   // 手写 map[T]int
来源：http://dali.daxiang520.top/Article/details/gtwqafgsqk.html

Ruby: arr.tally
来源：http://dali.yanxiufei.cn/Article/details/gtwkzdcyuz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yonumen.top/Article/details/gtejukbopq.html

[D21] 判断是否包含某元素
来源：http://dali.gzhubu.top/Article/details/gtwecusdml.html

Py:   x in arr
来源：http://dali.jianghu66.top/Article/details/gttjdfrcim.html

PHP:  in_array($x, $arr, true);
来源：http://dali.nanxinkj.top/Article/details/gtfllocivt.html

JS:   arr.includes(x)
来源：http://dali.jinqigufen.top/Article/details/gteknlxqmo.html

TS:   arr.includes(x)
来源：http://dali.feifeiyinyue.top/Article/details/gttfkpdbxe.html

Java: list.contains(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmpshzghf.html

Go:   slices.Contains(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtelzytpsf.html

Ruby: arr.include?(x)
来源：http://dali.hywenlv.cn/Article/details/gtlmsduefz.html

C#:   list.Contains(x)
来源：http://dali.bjfxy.top/Article/details/gtpaqnavua.html

[D22] 复制数组（避免共享引用）
来源：http://dali.dashuyun.cn/Article/details/gtdlmwvxpg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtxkoxiwnz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jqgfzy.top/Article/details/gthgoygvqu.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yuanzhike.top/Article/details/gtbfezxann.html

TS:   [...arr];
来源：http://dali.zycfv.cn/Article/details/gtzzkzppqg.html

Java: new ArrayList<>(list);
来源：http://dali.shangyingyoupin.top/Article/details/gtlqdxlhwn.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ppjwa.cn/Article/details/gtlhpunrti.html

Ruby: arr.dup;  arr.clone
来源：http://dali.quarkkingdee.top/Article/details/gtfbxfjnir.html

C#:   new List<int>(list);
来源：http://dali.bjfxy.top/Article/details/gtuasxnjlu.html

[D23] reduce 累积计算
来源：http://dali.chenzaomai.com/Article/details/gtgbwjgzoq.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gttjmzekmy.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yj20258.top/Article/details/gtouhtrsmb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.haohaochexian.top/Article/details/gtyngqymkp.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jianghu66.top/Article/details/gtrugxwtgu.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhixingplan.top/Article/details/gtgbpngfxg.html

Go:   // 手写循环
来源：http://dali.kuanghao11.cn/Article/details/gthjjnpnif.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hammf.cn/Article/details/gtjtzsckyc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yuanzhike.top/Article/details/gtjjxuupdv.html

[D24] 字典 / Map 基本操作
来源：http://dali.guannengcc.top/Article/details/gtwizpxqdu.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yuanzhike.top/Article/details/gtxhwgtnid.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yonumen.top/Article/details/gtmhsdivoj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.fzhhl.top/Article/details/gtviayjogq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yj20258888.top/Article/details/gtxhbwnqsw.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkcmmtfcr.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.chenzaomai.com/Article/details/gtjjmxflio.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.aibaodan.cn/Article/details/gtegtoxowf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinqigfzy.top/Article/details/gtzzvddkbn.html

[D25] Set 集合去重与交并差
来源：http://dali.nanxinkj.top/Article/details/gtvkgslvav.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.snrcjt.cn/Article/details/gtnkcepjlk.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.wangshuangyany.cn/Article/details/gtygevjneb.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.nanxuanxn.top/Article/details/gttobiasrf.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yueranfly.top/Article/details/gtsasujboi.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sxryk.cn/Article/details/gtgabprfvh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yvedp.cn/Article/details/gtjtqrhqki.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.chenlongwang.top/Article/details/gtthqatjcr.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xuanzx.com/Article/details/gtsdanwkhm.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gtjtntaxmd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yuanzhike.top/Article/details/gtwzxjbyvb.html

PHP:  implode(", ", $arr);
来源：http://dali.xuanzx.com/Article/details/gtrhpylcpw.html

JS:   arr.join(", ")
来源：http://dali.9152youxi.cn/Article/details/gtykhgfilm.html

TS:   arr.join(", ")
来源：http://dali.kuanghao11.cn/Article/details/gtdxymjmbl.html

Java: String.join(", ", list)
来源：http://dali.smart0.xyz/Article/details/gtgwnlqnsx.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shuidangran.top/Article/details/gtgwjiovoe.html

Ruby: arr.join(", ")
来源：http://dali.wangdashe.top/Article/details/gtkfeduwvx.html

C#:   string.Join(", ", list)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtliblgyke.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtirsnoavq.html

E. 字符串处理
来源：http://dali.jinghuilouyu.cn/Article/details/gtmjwcuiep.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtfzekkvyc.html

[E01] 拼接字符串
来源：http://dali.hysaishi.cn/Article/details/gtrqpgipvy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmhevegfk.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.snrcjt.cn/Article/details/gtelaqwzpj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aibaodan.cn/Article/details/gtfnegvkny.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cdnleiting.top/Article/details/gtlgrobcfh.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhixingplan.top/Article/details/gtawuwnocd.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yueranfly.top/Article/details/gtlhcjfune.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cashguo.top/Article/details/gtuxkxdyki.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvsqouear.html

[E02] 重复字符串
来源：http://dali.chenlongwang.top/Article/details/gtfuxdabvb.html

Py:   "ab" * 3
来源：http://dali.yangfankeji.com/Article/details/gtdubumbcd.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xziqi.cn/Article/details/gtgprymdse.html

JS:   "ab".repeat(3)
来源：http://dali.yueranfly.top/Article/details/gtmbcspdxr.html

TS:   "ab".repeat(3)
来源：http://dali.gotoacloud.top/Article/details/gtwfzgzuqh.html

Java: "ab".repeat(3)
来源：http://dali.dashuyun.cn/Article/details/gtnkallyfd.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yongpay.top/Article/details/gtapfkupmx.html

Ruby: "ab" * 3
来源：http://dali.tianlin.xyz/Article/details/gtgkfyakdl.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.nanxinkj.top/Article/details/gtpjbuohyw.html

[E03] 截取子串
来源：http://dali.yongpay.top/Article/details/gthoiwejnb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shanyushiyangtech.top/Article/details/gtimfywdao.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gthjrituvl.html


<!-- 参考信息 -->