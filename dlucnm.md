代发 wailian999

Go:   func() { fmt.Println("run") }()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dixmfnff.html

Ruby: -> { puts "run" }.call
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zljugjir.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zycfv.cn/Article/details/gt2kwexnhqn.html

[C13] 类型声明 / 类型注解
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lzrsytuw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.wangshuangyany.cn/Article/details/gt2jjhqcnre.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxuanxn.top/Article/details/gt2kcxlqlwg.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jyoumei.cn/Article/details/gt2uecnpnoo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2kalxfsdg.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gt2esjlhgci.html

Go:   func add(a, b int) int
来源：http://dali.hfpthk.cn/Article/details/gt2yenlkcsx.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.nanxuanxn.top/Article/details/gt2loweffoe.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.smart0.xyz/Article/details/gt2tnvfjjvd.html

[C14] 泛型函数
来源：http://dali.shzxlz.cn/Article/details/gt2lagbrkkh.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.chenzaomai.com/Article/details/gt2txkgnmnv.html

PHP:  // 无泛型
来源：http://dali.chenjidiqi.icu/Article/details/gt2oenpwxhl.html

JS:   // 无泛型
来源：http://dali.gogol.net.cn/Article/details/gt2hygrbxbf.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.haohaochexian.top/Article/details/gt2uduzefhi.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.nwbrower.top/Article/details/gt2mcydmauk.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhengqikj.top/Article/details/gt2lrxumrgc.html

Ruby: # 无泛型
来源：http://dali.jlsjyb.cn/Article/details/gt2lanwgkag.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.chenlongwang.top/Article/details/gt2eehpsyoa.html

[C15] 解构 / 展开参数
来源：http://dali.zhongyouzk.top/Article/details/gt2dhefybkq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.cdnleiting.top/Article/details/gt2gkyeuokz.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ysdhwhnn.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ybcxt.top/Article/details/gt2ickidwrf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.nanxinkj.top/Article/details/gt2pvwrcbmc.html

Java: // 无解构
来源：http://dali.aizwys.cn/Article/details/gt2dmmmegeg.html

Go:   // 无解构
来源：http://dali.shuidangran.top/Article/details/gt2diinezzw.html

Ruby: a, b = pair
来源：http://dali.zhongyouzk.top/Article/details/gt2xmhdbbil.html

C#:   var (a, b) = pair;
来源：http://dali.zhongyouzk.top/Article/details/gt2wmnpyrwd.html

[C16] 函数 / 方法重载
来源：http://dali.haohaochexian.top/Article/details/gt2nrhpiefb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.andypj.xyz/Article/details/gt2sgsutrrr.html

PHP:  // 无重载
来源：http://dali.birdmap.top/Article/details/gt2qpkcnnhb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.andypj.xyz/Article/details/gt2fdyxtbrj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hammf.cn/Article/details/gt2mlwjchlr.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jianghu66.top/Article/details/gt2abasnaex.html

Go:   // 无重载：用不同函数名
来源：http://dali.0kj1m.cn/Article/details/gt2xzsvxhii.html

Ruby: # 无重载：靠动态参数
来源：http://dali.quarkkingdee.top/Article/details/gt2iosxhcdg.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2bxibpioq.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2zorqpgis.html

D. 数组 / 列表 / 集合
来源：http://dali.zycfv.cn/Article/details/gt2ovdqtiaq.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2pqkpihyu.html

[D01] 创建数组 / 列表
来源：http://dali.zhiwuduotai.top/Article/details/gt2yrzbnzgd.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.nanxinkj.top/Article/details/gt2nmddhpow.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hammf.cn/Article/details/gt2ijrsmtpt.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.svipenyu.cn/Article/details/gt2razhifkd.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.tanke756.top/Article/details/gt2ndajmopx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jlsjyb.cn/Article/details/gt2zokuuukx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xylfe.cn/Article/details/gt2fblqusvv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.c1oappe.top/Article/details/gt2xrviwatl.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.smart0.xyz/Article/details/gt2tdbrwqws.html

[D02] 追加元素到末尾
来源：http://dali.birdmap.top/Article/details/gt2jmdnihmu.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.guannengcc.top/Article/details/gt2aimjhmfd.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhengqikj.top/Article/details/gt2bxjacbzb.html

JS:   arr.push(4);
来源：http://dali.ydzc1.top/Article/details/gt2gychqayw.html

TS:   arr.push(4);
来源：http://dali.haohaochexian.top/Article/details/gt2hgijfcbu.html

Java: list.add(4);
来源：http://dali.zdqjudy.top/Article/details/gt2cskvdgmo.html

Go:   arr = append(arr, 4)
来源：http://dali.hywenlv.cn/Article/details/gt2kwbcvcgm.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.bjfxy.top/Article/details/gt2bjdmgnko.html

C#:   list.Add(4);
来源：http://dali.yueranfly.top/Article/details/gt2tygdmyiv.html

[D03] 在指定位置插入元素
来源：http://dali.jqgufenzy.top/Article/details/gt2pybsgwov.html

Py:   arr.insert(0, 0)
来源：http://dali.quarkkingdee.top/Article/details/gt2wyacccul.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.snrcjt.cn/Article/details/gt2hrynnhpd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cashguo.top/Article/details/gt2vjfnhxmq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yvedp.cn/Article/details/gt2yfcunnir.html

Java: list.add(0, 0);
来源：http://dali.yj20258.top/Article/details/gt2ljjwbttd.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yanxiufei.cn/Article/details/gt2ndoesscd.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shuidangran.top/Article/details/gt2jqahatnp.html

C#:   list.Insert(0, 0);
来源：http://dali.meibo888.top/Article/details/gt2hvmbvmpx.html

[D04] 删除元素
来源：http://dali.hysaishi.cn/Article/details/gt2eghrnazt.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.daxiang520.top/Article/details/gt2mvszzlhz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yj202588.top/Article/details/gt2jqyifhei.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.haohaochexian.top/Article/details/gt2kkwvuffy.html

TS:   arr.splice(0, 1);
来源：http://dali.yj20258.top/Article/details/gt2riqjbtwl.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hfpthk.cn/Article/details/gt2ipfgbewm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yongpay.top/Article/details/gt2slmebcxo.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cashguo.top/Article/details/gt2vhadapbh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ewxsncqd.html

[D05] 访问与修改元素
来源：http://dali.bjfxy.top/Article/details/gt2imstonqb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yuanzhike.top/Article/details/gt2whobbcez.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenlongwang.top/Article/details/gt2iwtamvbv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.tianlin.xyz/Article/details/gt2fzvqbkyx.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jiagoushi.top/Article/details/gt2bjceznhs.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yuanzhike.top/Article/details/gt2iocetzal.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.9152youxi.cn/Article/details/gt2sfrwdioh.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tanke756.top/Article/details/gt2iowresdp.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.sweek.top/Article/details/gt2vizmubiq.html

[D06] 数组长度
来源：http://dali.zhoulong.xyz/Article/details/gt2esxymjqe.html

Py:   len(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2hayfrqkc.html

PHP:  count($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zxeyzupb.html

JS:   arr.length
来源：http://dali.xuetiantiany.cn/Article/details/gt2qoidrdcg.html

TS:   arr.length
来源：http://dali.guowangkeji.top/Article/details/gt2hdnyiymg.html

Java: list.size();
来源：http://dali.chenlongwang.top/Article/details/gt2ncmbbbsv.html

Go:   len(arr)
来源：http://dali.yueranfly.top/Article/details/gt2iywppjac.html

Ruby: arr.length; arr.size
来源：http://dali.feifeiyinyue.top/Article/details/gt2nixaitja.html

C#:   list.Count;
来源：http://dali.cqqwz.cn/Article/details/gt2ljaoqibc.html

[D07] 切片 / 取子数组
来源：http://dali.xuetiantiany.cn/Article/details/gt2mgvndmye.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.aizwys.cn/Article/details/gt2guvjipmq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.aizwys.cn/Article/details/gt2tsdbdmvb.html

JS:   arr.slice(1, 4);
来源：http://dali.yueranfly.top/Article/details/gt2hlomdzjw.html

TS:   arr.slice(1, 4);
来源：http://dali.sxryk.cn/Article/details/gt2soppubxj.html

Java: list.subList(1, 4);
来源：http://dali.nanxinkj.top/Article/details/gt2upkayovo.html

Go:   arr[1:4]
来源：http://dali.sxryk.cn/Article/details/gt2jhzbmjrv.html

Ruby: arr[1, 3]
来源：http://dali.daxiang520.top/Article/details/gt2csekunlm.html

C#:   list.GetRange(1, 3);
来源：http://dali.gogol.net.cn/Article/details/gt2tcsyxgdu.html

[D08] 合并两个数组
来源：http://dali.sxryk.cn/Article/details/gt2dkpjsrcb.html

Py:   a + b;  a.extend(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gmelyqfr.html

PHP:  array_merge($a, $b);
来源：http://dali.zhiwuduotai.top/Article/details/gt2xbsozscx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.feifeiyinyue.top/Article/details/gt2hjixhroj.html

TS:   [...a, ...b];
来源：http://dali.kuanghao11.cn/Article/details/gt2yvecadlm.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.havefunace.top/Article/details/gt2aouizzxm.html

Go:   append(a, b...)
来源：http://dali.jqgfzy.top/Article/details/gt2nzjsfxhd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.guowangkeji.top/Article/details/gt2ingvmlkz.html

C#:   a.Concat(b).ToList()
来源：http://dali.gogol.net.cn/Article/details/gt2haoxlgqe.html

[D09] 排序（升序）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kwxktawk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cucudq.cn/Article/details/gt2cztipekz.html

PHP:  sort($arr);
来源：http://dali.hysaishi.cn/Article/details/gt2igzrjeyy.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ydzc1.top/Article/details/gt2hhcfaoxv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cucudq.cn/Article/details/gt2tkndiomw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.chenlongwang.top/Article/details/gt2lmbuwxdw.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ivvv.top/Article/details/gt2gwhxgmgw.html

Ruby: arr.sort
来源：http://dali.9152youxi.cn/Article/details/gt2ocjaaqwy.html

C#:   list.Sort();
来源：http://dali.jianghu66.top/Article/details/gt2kqyoiafp.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.9152youxi.cn/Article/details/gt2eooawdpz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.sufxvd.cn/Article/details/gt2newiwlwz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zdqjudy.top/Article/details/gt2gzjgeueq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yongpay.top/Article/details/gt2danqmmbm.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.haohaochexian.top/Article/details/gt2yblfpfmt.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.kuanghao11.cn/Article/details/gt2ybikflmr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yj202588.top/Article/details/gt2tsbstqlu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.dashuyun.cn/Article/details/gt2usykmkoq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.fengsongda.top/Article/details/gt2zdqaqnvl.html

[D11] 反转数组
来源：http://dali.xziqi.cn/Article/details/gt2raetiyop.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shzxlz.cn/Article/details/gt2mrnskprt.html

PHP:  array_reverse($arr);
来源：http://dali.dianchejie.cn/Article/details/gt2wxqsxnkf.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhengqikj.top/Article/details/gt2uwxchglg.html

TS:   [...arr].reverse();
来源：http://dali.ybcxt.top/Article/details/gt2kbbnkzwe.html

Java: Collections.reverse(list);
来源：http://dali.gaohongyu789.top/Article/details/gt2yqacfnpj.html

Go:   slices.Reverse(arr)
来源：http://dali.redwolf501.top/Article/details/gt2ihadapeh.html

Ruby: arr.reverse
来源：http://dali.cheryme.top/Article/details/gt2hssdqghl.html

C#:   list.Reverse();
来源：http://dali.feifeiyinyue.top/Article/details/gt2bydzarvp.html

[D12] 查找元素下标
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tkeoxkrq.html

Py:   arr.index(x);  x in arr
来源：http://dali.redwolf501.top/Article/details/gt2illmrapr.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.mhx1999.top/Article/details/gt2edixlwni.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zycfv.cn/Article/details/gt2oevwizxe.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj202588.top/Article/details/gt2ybvcqwkr.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ihgkdksh.html

Go:   slices.Index(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gt2zbvxselu.html

Ruby: arr.index(x)
来源：http://dali.chenzaomai.com/Article/details/gt2qshxswzr.html

C#:   list.IndexOf(x);
来源：http://dali.xuetiantiany.cn/Article/details/gt2lvdkboce.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xziqi.cn/Article/details/gt2ncbqkbbg.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cucudq.cn/Article/details/gt2zwhzqpvl.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.wangshuangyany.cn/Article/details/gt2iqedpacr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.havefunace.top/Article/details/gt2fvvsqvki.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hywenlv.cn/Article/details/gt2tyetnpul.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shzxlz.cn/Article/details/gt2bwsmhptt.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yangfankeji.com/Article/details/gt2gocxtipe.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.wangshuangyany.cn/Article/details/gt2alskthnm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.nwbrower.top/Article/details/gt2enopmdth.html

[D14] 映射转换（每个元素变形）
来源：http://dali.tian-w.cn/Article/details/gt2ozgicfta.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.iojbl.cn/Article/details/gt2tszlrxow.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.tanke756.top/Article/details/gt2mohwkmii.html

JS:   arr.map(x => x * 2)
来源：http://dali.316326.xyz/Article/details/gt2rtwehsmb.html

TS:   arr.map(x => x * 2)
来源：http://dali.0kj1m.cn/Article/details/gt2pdguqfgi.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zycfv.cn/Article/details/gt2zyejlfwk.html

Go:   // 手写循环
来源：http://dali.316326.xyz/Article/details/gt2kolnezhz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hnqzz.top/Article/details/gt2hhepuxwy.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hysaishi.cn/Article/details/gt2okwatmuj.html

[D15] 去重
来源：http://dali.yuanzhike.top/Article/details/gt2dqtcwgsv.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shangyingyoupin.top/Article/details/gt2xeyjxukc.html

PHP:  array_unique($arr);
来源：http://dali.havefunace.top/Article/details/gt2jumyxpvh.html

JS:   [...new Set(arr)]
来源：http://dali.jqgufenzy.top/Article/details/gt2jxeaotrf.html

TS:   [...new Set(arr)]
来源：http://dali.hysaishi.cn/Article/details/gt2ltejhsns.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hnxiangtu.top/Article/details/gt2gcwsitdp.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.c1oappe.top/Article/details/gt2clhvrmia.html

Ruby: arr.uniq
来源：http://dali.ppjwa.cn/Article/details/gt2alfbbwvu.html

C#:   list.Distinct().ToList()
来源：http://dali.zhengqikj.top/Article/details/gt2ouvjhsks.html

[D16] 求和与平均值
来源：http://dali.yangfankeji.com/Article/details/gt2vqnjjwtt.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cqqwz.cn/Article/details/gt2oozokfsw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yanxiufei.cn/Article/details/gt2mqljbuls.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hysaishi.cn/Article/details/gt2dgfogfik.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gt2qqzmjlwd.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hfpthk.cn/Article/details/gt2ueclamfw.html

Go:   // 手写循环累加
来源：http://dali.hongshengwenyu.top/Article/details/gt2nmfrhbvr.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jiagoushi.top/Article/details/gt2bxruvrzp.html

C#:   list.Sum();  list.Average()
来源：http://dali.xylfe.cn/Article/details/gt2hzlgxtsg.html

[D17] 最大值与最小值
来源：http://dali.9152youxi.cn/Article/details/gt2adhdicik.html

Py:   max(arr);  min(arr)
来源：http://dali.tanke756.top/Article/details/gt2ixldkpqy.html

PHP:  max($arr);  min($arr);
来源：http://dali.ivvv.top/Article/details/gt2sdtxzbnl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hysaishi.cn/Article/details/gt2byecxgkf.html

TS:   Math.max(...arr);
来源：http://dali.xylfe.cn/Article/details/gt2jipznjjl.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhiwuduotai.top/Article/details/gt2voeexzkd.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.meibo888.top/Article/details/gt2ycmnqduf.html

Ruby: arr.max;  arr.min
来源：http://dali.zhengqikj.top/Article/details/gt2frduejej.html

C#:   list.Max();  list.Min()
来源：http://dali.yj20258888.top/Article/details/gt2tdynobpb.html

[D18] 扁平化嵌套数组
来源：http://dali.jianghu66.top/Article/details/gt2fbuhtgyg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kaqjvwzn.html

PHP:  array_merge(...$nested);
来源：http://dali.xylfe.cn/Article/details/gt2ezeeutsa.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shuidangran.top/Article/details/gt2gpbdrycm.html

TS:   nested.flat();
来源：http://dali.gaohongyu789.top/Article/details/gt2smwwuuak.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cheryme.top/Article/details/gt2ryhzgjlh.html

Go:   // 手写双层循环
来源：http://dali.xziqi.cn/Article/details/gt2iyteftro.html

Ruby: nested.flatten
来源：http://dali.jianghu66.top/Article/details/gt2mdhldcyw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xylfe.cn/Article/details/gt2fzrpmscy.html

[D19] 按字段分组
来源：http://dali.aizwys.cn/Article/details/gt2adhuqora.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.pycfn.com/Article/details/gt2gyeuzugu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yongpay.top/Article/details/gt2uyhwcfjb.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ehwqpu.com/Article/details/gt2ixfvlrvq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sufxvd.cn/Article/details/gt2qsfjvjml.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yongpay.top/Article/details/gt2vfshbrqd.html

Go:   // 手写 map[string][]T
来源：http://dali.aibaodan.cn/Article/details/gt2gikmgscx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jqgfzy.top/Article/details/gt2xclmhpch.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ybcxt.top/Article/details/gt2mithzzws.html

[D20] 统计每个元素出现次数
来源：http://dali.yj202588.top/Article/details/gt2rtrafqol.html

Py:   Counter(arr)
来源：http://dali.cashguo.top/Article/details/gt2vipwaljj.html

PHP:  array_count_values($arr);
来源：http://dali.xinyue.icu/Article/details/gt2pbpavebx.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258.top/Article/details/gt2gttmtsjs.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2tfarcnmk.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sxryk.cn/Article/details/gt2kjxjhdcr.html

Go:   // 手写 map[T]int
来源：http://dali.daria6918.cn/Article/details/gt2imwbuzzg.html

Ruby: arr.tally
来源：http://dali.redwolf501.top/Article/details/gt2ldkysuzo.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hvppoyqs.html

[D21] 判断是否包含某元素
来源：http://dali.ehwqpu.com/Article/details/gt2xnsmcusi.html

Py:   x in arr
来源：http://dali.pycfn.com/Article/details/gt2nlzhltjh.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yj20258.top/Article/details/gt2ecmgfcch.html

JS:   arr.includes(x)
来源：http://dali.sysykeji.top/Article/details/gt2srzbuyjc.html

TS:   arr.includes(x)
来源：http://dali.fengsongda.top/Article/details/gt2rqvvzrtk.html

Java: list.contains(x)
来源：http://dali.yuxming.cn/Article/details/gt2mczobghp.html

Go:   slices.Contains(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gt2fwywdgua.html

Ruby: arr.include?(x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2tazadtcg.html

C#:   list.Contains(x)
来源：http://dali.guowangkeji.top/Article/details/gt2grtrvsfc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pqzubuii.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yangfankeji.com/Article/details/gt2sllowwvh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xinyue.icu/Article/details/gt2itxxjfkc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.daxiang520.top/Article/details/gt2jcuuqswm.html

TS:   [...arr];
来源：http://dali.yongpay.top/Article/details/gt2twzzhjwn.html

Java: new ArrayList<>(list);
来源：http://dali.ybcxt.top/Article/details/gt2xcsvfvtu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.chenlongwang.top/Article/details/gt2xwlljxay.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zdqjudy.top/Article/details/gt2mhhrjhtg.html

C#:   new List<int>(list);
来源：http://dali.ybcxt.top/Article/details/gt2xytzynbk.html

[D23] reduce 累积计算
来源：http://dali.shzxlz.cn/Article/details/gt2lktoznnu.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ivvv.top/Article/details/gt2ddaosnay.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.nanxuanxn.top/Article/details/gt2dalxgzgp.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zycfv.cn/Article/details/gt2mtefevfu.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.kuanghao11.cn/Article/details/gt2sktiiayo.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.feifeiyinyue.top/Article/details/gt2dvcyxsnj.html

Go:   // 手写循环
来源：http://dali.pycfn.com/Article/details/gt2qbwpolsj.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.sweek.top/Article/details/gt2gudvdycz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sakokfhd.html

[D24] 字典 / Map 基本操作
来源：http://dali.vqdsnc.cn/Article/details/gt2fnpmaojt.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jdzjmpbu.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yuanzhike.top/Article/details/gt2ftqrynnw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xuanzx.com/Article/details/gt2ppdeulsp.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gt2ypxolqoh.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zycfv.cn/Article/details/gt2isouexkt.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ehwqpu.com/Article/details/gt2stiknfpa.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hywenlv.cn/Article/details/gt2tbqkywdg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hnxiangtu.top/Article/details/gt2gxurfufa.html

[D25] Set 集合去重与交并差
来源：http://dali.nanxuanxn.top/Article/details/gt2gmhhffpr.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.daria6918.cn/Article/details/gt2ofjkkmqj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jianghu66.top/Article/details/gt2xvobdmgr.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.havefunace.top/Article/details/gt2laktipce.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.daxiang520.top/Article/details/gt2fpljrwes.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sufxvd.cn/Article/details/gt2ychbcqad.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pajymnws.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hammf.cn/Article/details/gt2wpdbnhbb.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xziqi.cn/Article/details/gt2dzauzldq.html

[D26] 数组转字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2ceupxluw.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yj20258.top/Article/details/gt2bzmtdfwi.html

PHP:  implode(", ", $arr);
来源：http://dali.hfpthk.cn/Article/details/gt2wetrkqeh.html

JS:   arr.join(", ")
来源：http://dali.yangfankeji.com/Article/details/gt2dkabqmhu.html

TS:   arr.join(", ")
来源：http://dali.hnxiangtu.top/Article/details/gt2shnortts.html

Java: String.join(", ", list)
来源：http://dali.wangshuangyany.cn/Article/details/gt2unwaipdc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cucudq.cn/Article/details/gt2htyktzau.html

Ruby: arr.join(", ")
来源：http://dali.yvedp.cn/Article/details/gt2qikfpscp.html

C#:   string.Join(", ", list)
来源：http://dali.hongshengwenyu.top/Article/details/gt2schjzhnw.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2fhajnbsf.html

E. 字符串处理
来源：http://dali.aibaodan.cn/Article/details/gt2fryjnexh.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2nfovjuzx.html

[E01] 拼接字符串
来源：http://dali.kuanghao11.cn/Article/details/gt2ojcpvefh.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.pycfn.com/Article/details/gt2gaclkjjx.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.wangshuangyany.cn/Article/details/gt2mrtnqtnx.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.smart0.xyz/Article/details/gt2lfiadvzu.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aibaodan.cn/Article/details/gt2fqoctvvs.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hnxiangtu.top/Article/details/gt2pjmqnyoy.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.9152youxi.cn/Article/details/gt2pgebhwyg.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.redwolf501.top/Article/details/gt2tblhdygh.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yongpay.top/Article/details/gt2iklopcyy.html

[E02] 重复字符串
来源：http://dali.andypj.xyz/Article/details/gt2hoomejye.html

Py:   "ab" * 3
来源：http://dali.jianghu66.top/Article/details/gt2tatqbbby.html

PHP:  str_repeat("ab", 3);
来源：http://dali.redwolf501.top/Article/details/gt2eennrxns.html

JS:   "ab".repeat(3)
来源：http://dali.jyoumei.cn/Article/details/gt2muacwiqh.html

TS:   "ab".repeat(3)
来源：http://dali.zhengqikj.top/Article/details/gt2tkibjhty.html

Java: "ab".repeat(3)
来源：http://dali.hnqzz.top/Article/details/gt2sgcyxwuf.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2poxxeirb.html

Ruby: "ab" * 3
来源：http://dali.shangyingyoupin.top/Article/details/gt2bjsfhiuk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2gagqvdir.html

[E03] 截取子串
来源：http://dali.316326.xyz/Article/details/gt2ecnqapbn.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.andypj.xyz/Article/details/gt2iwwkzwlw.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gt2bpvflxov.html


<!-- 参考信息 -->