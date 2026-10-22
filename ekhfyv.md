代发 wailian999

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.chenzaomai.com/Article/details/gt2eolrucjt.html

[C15] 解构 / 展开参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2xxraixdy.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.nwbrower.top/Article/details/gt2enfqcmvr.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hnxiangtu.top/Article/details/gt2flwwhkmd.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2dmglrfim.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ivvv.top/Article/details/gt2uedryjly.html

Java: // 无解构
来源：http://dali.cqqwz.cn/Article/details/gt2tyyhclti.html

Go:   // 无解构
来源：http://dali.cdnleiting.top/Article/details/gt2gjrzcdwo.html

Ruby: a, b = pair
来源：http://dali.sufxvd.cn/Article/details/gt2pbwzqcrs.html

C#:   var (a, b) = pair;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wwgyqkev.html

[C16] 函数 / 方法重载
来源：http://dali.hfpthk.cn/Article/details/gt2wpgplwrk.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.meibo888.top/Article/details/gt2tbzlyvoy.html

PHP:  // 无重载
来源：http://dali.yanxiufei.cn/Article/details/gt2nezyrlfg.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yvedp.cn/Article/details/gt2dbujtcpx.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jqgfzy.top/Article/details/gt2xoxnpfkr.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.aibaodan.cn/Article/details/gt2frjhtgtn.html

Go:   // 无重载：用不同函数名
来源：http://dali.yj20258888.top/Article/details/gt2aweznhcb.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhengqikj.top/Article/details/gt2vsruypad.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.sysykeji.top/Article/details/gt2aeonrecz.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2snejamzx.html

D. 数组 / 列表 / 集合
来源：http://dali.yangfankeji.com/Article/details/gt2fhprjthq.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2ufalidxb.html

[D01] 创建数组 / 列表
来源：http://dali.hfpthk.cn/Article/details/gt2apbwflsp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hysaishi.cn/Article/details/gt2xnbgldjp.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hywenlv.cn/Article/details/gt2htqjbcaq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eygvzlgq.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xuetiantiany.cn/Article/details/gt2ggyjzqcr.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hywenlv.cn/Article/details/gt2nidhlvzr.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.feifeiyinyue.top/Article/details/gt2zqzmwfcs.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cucudq.cn/Article/details/gt2xiduizgk.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.gogol.net.cn/Article/details/gt2imyaaqdl.html

[D02] 追加元素到末尾
来源：http://dali.ehwqpu.com/Article/details/gt2rtceqrpu.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yeqgxxtx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.dianchejie.cn/Article/details/gt2jqkphqwm.html

JS:   arr.push(4);
来源：http://dali.sysykeji.top/Article/details/gt2zukajoff.html

TS:   arr.push(4);
来源：http://dali.cqqwz.cn/Article/details/gt2fqgkdgtf.html

Java: list.add(4);
来源：http://dali.yanxiufei.cn/Article/details/gt2enhbqzpg.html

Go:   arr = append(arr, 4)
来源：http://dali.smart0.xyz/Article/details/gt2btfmsvup.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ehwqpu.com/Article/details/gt2ajdyfxmn.html

C#:   list.Add(4);
来源：http://dali.jqgufenzy.top/Article/details/gt2chvipzbj.html

[D03] 在指定位置插入元素
来源：http://dali.xuetiantiany.cn/Article/details/gt2wuwletxa.html

Py:   arr.insert(0, 0)
来源：http://dali.guowangkeji.top/Article/details/gt2kggajihj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.bjfxy.top/Article/details/gt2jrgfyyfi.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhixingplan.top/Article/details/gt2qdgamhwl.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jceinxam.html

Java: list.add(0, 0);
来源：http://dali.xuanzx.com/Article/details/gt2qlkdjymg.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.gzhubu.top/Article/details/gt2nwyolxob.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.sweek.top/Article/details/gt2ttdqwxes.html

C#:   list.Insert(0, 0);
来源：http://dali.jqgufenzy.top/Article/details/gt2ftlrlpbx.html

[D04] 删除元素
来源：http://dali.yuxming.cn/Article/details/gt2jwrbdaxg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.kuanghao11.cn/Article/details/gt2csoernan.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.dianchejie.cn/Article/details/gt2wtznymeu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ppjwa.cn/Article/details/gt2nkczznkx.html

TS:   arr.splice(0, 1);
来源：http://dali.gzhubu.top/Article/details/gt2rgwydyzg.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.aizwys.cn/Article/details/gt2eddpgcni.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.9152youxi.cn/Article/details/gt2mzbqlqir.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hnqzz.top/Article/details/gt2jvfudwcd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.chenlongwang.top/Article/details/gt2tvsrgrze.html

[D05] 访问与修改元素
来源：http://dali.mhx1999.top/Article/details/gt2rgidtopp.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.dianchejie.cn/Article/details/gt2punpatjr.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yuanzhike.top/Article/details/gt2lqzfpkbx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zycfv.cn/Article/details/gt2bajhzmfb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.quarkkingdee.top/Article/details/gt2qyiufrso.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2izmiakrd.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.birdmap.top/Article/details/gt2ltqzqhxm.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ppjwa.cn/Article/details/gt2xvyqvzmn.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.wangshuangyany.cn/Article/details/gt2olwdvzfg.html

[D06] 数组长度
来源：http://dali.yongpay.top/Article/details/gt2dluwehhg.html

Py:   len(arr)
来源：http://dali.yongpay.top/Article/details/gt2zskbforz.html

PHP:  count($arr);
来源：http://dali.zhixingplan.top/Article/details/gt2gzsyapte.html

JS:   arr.length
来源：http://dali.shuidangran.top/Article/details/gt2pipvkzqt.html

TS:   arr.length
来源：http://dali.yonumen.top/Article/details/gt2ythgnend.html

Java: list.size();
来源：http://dali.meibo888.top/Article/details/gt2zywxwbws.html

Go:   len(arr)
来源：http://dali.xuanzx.com/Article/details/gt2gxfiwftk.html

Ruby: arr.length; arr.size
来源：http://dali.zhiwuduotai.top/Article/details/gt2jjejawtt.html

C#:   list.Count;
来源：http://dali.yuanzhike.top/Article/details/gt2bqrhdkmf.html

[D07] 切片 / 取子数组
来源：http://dali.haohaochexian.top/Article/details/gt2xdrmfdqw.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.gotoacloud.top/Article/details/gt2opndzzsf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yj202588.top/Article/details/gt2aouaodsw.html

JS:   arr.slice(1, 4);
来源：http://dali.aibaodan.cn/Article/details/gt2bttolazc.html

TS:   arr.slice(1, 4);
来源：http://dali.chenjidiqi.icu/Article/details/gt2taadnnev.html

Java: list.subList(1, 4);
来源：http://dali.yangfankeji.com/Article/details/gt2dkhctgyw.html

Go:   arr[1:4]
来源：http://dali.dianchejie.cn/Article/details/gt2evdsgmcl.html

Ruby: arr[1, 3]
来源：http://dali.cdnleiting.top/Article/details/gt2mhhoptvy.html

C#:   list.GetRange(1, 3);
来源：http://dali.meibo888.top/Article/details/gt2kdetuovr.html

[D08] 合并两个数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uxopqvop.html

Py:   a + b;  a.extend(b)
来源：http://dali.quarkkingdee.top/Article/details/gt2mcbmyrwk.html

PHP:  array_merge($a, $b);
来源：http://dali.0kj1m.cn/Article/details/gt2qyawxmya.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhixingplan.top/Article/details/gt2zmiotmlt.html

TS:   [...a, ...b];
来源：http://dali.ppjwa.cn/Article/details/gt2impoaazj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yvedp.cn/Article/details/gt2vrpfgyhn.html

Go:   append(a, b...)
来源：http://dali.cqqwz.cn/Article/details/gt2rgbpxpsx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhongyouzk.top/Article/details/gt2awueqogw.html

C#:   a.Concat(b).ToList()
来源：http://dali.mhx1999.top/Article/details/gt2qafxozni.html

[D09] 排序（升序）
来源：http://dali.zhoulong.xyz/Article/details/gt2mzahqkjf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shangyingyoupin.top/Article/details/gt2cgagdcdh.html

PHP:  sort($arr);
来源：http://dali.aibaodan.cn/Article/details/gt2jzhtbvmz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.9152youxi.cn/Article/details/gt2xzygxzwb.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.haohaochexian.top/Article/details/gt2tthhcygq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dqgsfjmt.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2bipwzeup.html

Ruby: arr.sort
来源：http://dali.ppjwa.cn/Article/details/gt2yhlsgwoq.html

C#:   list.Sort();
来源：http://dali.zycfv.cn/Article/details/gt2tdueapum.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.fzhhl.top/Article/details/gt2ulnphydb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yueranfly.top/Article/details/gt2qabliemc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sysykeji.top/Article/details/gt2trbyzzkt.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shangyingyoupin.top/Article/details/gt2iereetce.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hywenlv.cn/Article/details/gt2jlesuvmk.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yueranfly.top/Article/details/gt2irvlsgbn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.bjfxy.top/Article/details/gt2ndxmwmiw.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.andypj.xyz/Article/details/gt2zgbpxsli.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.meibo888.top/Article/details/gt2lqjhvdcr.html

[D11] 反转数组
来源：http://dali.chenzaomai.com/Article/details/gt2szifywka.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.pengpengdd.cyou/Article/details/gt2stmtxiom.html

PHP:  array_reverse($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2xgdeiohr.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.mhx1999.top/Article/details/gt2yikyzdtf.html

TS:   [...arr].reverse();
来源：http://dali.zhongyouzk.top/Article/details/gt2vqjwvmhq.html

Java: Collections.reverse(list);
来源：http://dali.yj20258.top/Article/details/gt2mgwegict.html

Go:   slices.Reverse(arr)
来源：http://dali.xylfe.cn/Article/details/gt2cgcqrtpx.html

Ruby: arr.reverse
来源：http://dali.chenjidiqi.icu/Article/details/gt2xbvxzbsv.html

C#:   list.Reverse();
来源：http://dali.cdnleiting.top/Article/details/gt2jphfvnqy.html

[D12] 查找元素下标
来源：http://dali.ivvv.top/Article/details/gt2rrovjabx.html

Py:   arr.index(x);  x in arr
来源：http://dali.pycfn.com/Article/details/gt2bcwssmhk.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.chenzaomai.com/Article/details/gt2vxfcsyar.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nanxinkj.top/Article/details/gt2ddujodyo.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cucudq.cn/Article/details/gt2swaxfcdt.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.gzhubu.top/Article/details/gt2zhrmiksr.html

Go:   slices.Index(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gt2fqcsudsy.html

Ruby: arr.index(x)
来源：http://dali.yueranfly.top/Article/details/gt2jdmulccf.html

C#:   list.IndexOf(x);
来源：http://dali.zycfv.cn/Article/details/gt2mnizhxkp.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cqqwz.cn/Article/details/gt2cskqxtvw.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.wangdashe.top/Article/details/gt2xbagswvo.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.wangshuangyany.cn/Article/details/gt2vofkurpv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.gaohongyu789.top/Article/details/gt2yvficunr.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvgblaht.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.meibo888.top/Article/details/gt2vscnplka.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.redwolf501.top/Article/details/gt2wdgwhuxe.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shuidangran.top/Article/details/gt2uupjzlqm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gt2kwpixiec.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shuidangran.top/Article/details/gt2xzoydjgr.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cdnleiting.top/Article/details/gt2vjwkggpf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.tianlin.xyz/Article/details/gt2zstliubg.html

JS:   arr.map(x => x * 2)
来源：http://dali.cheryme.top/Article/details/gt2wlpmidgt.html

TS:   arr.map(x => x * 2)
来源：http://dali.cheryme.top/Article/details/gt2bcxxrpex.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zokstqvm.html

Go:   // 手写循环
来源：http://dali.yuanzhike.top/Article/details/gt2jqfasntn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jqgufenzy.top/Article/details/gt2otbpheeh.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sufxvd.cn/Article/details/gt2vgseowog.html

[D15] 去重
来源：http://dali.9152youxi.cn/Article/details/gt2ysieobly.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhiwuduotai.top/Article/details/gt2elaqyvma.html

PHP:  array_unique($arr);
来源：http://dali.jiagoushi.top/Article/details/gt2kwjryfnn.html

JS:   [...new Set(arr)]
来源：http://dali.chenjidiqi.icu/Article/details/gt2pqfiulcp.html

TS:   [...new Set(arr)]
来源：http://dali.316326.xyz/Article/details/gt2ixdninat.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.bjfxy.top/Article/details/gt2vuihbhni.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.nanxinkj.top/Article/details/gt2xckscxyu.html

Ruby: arr.uniq
来源：http://dali.cqqwz.cn/Article/details/gt2gqmoklco.html

C#:   list.Distinct().ToList()
来源：http://dali.ehwqpu.com/Article/details/gt2bzawlilk.html

[D16] 求和与平均值
来源：http://dali.shzxlz.cn/Article/details/gt2opordcbo.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.guannengcc.top/Article/details/gt2wdpfljmg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.meibo888.top/Article/details/gt2npqzvquu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.c1oappe.top/Article/details/gt2ttihyvuo.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yuxming.cn/Article/details/gt2jijfidns.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hnqzz.top/Article/details/gt2raobcogn.html

Go:   // 手写循环累加
来源：http://dali.jyoumei.cn/Article/details/gt2jlyfxhcc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yuanzhike.top/Article/details/gt2byhrnwad.html

C#:   list.Sum();  list.Average()
来源：http://dali.aibaodan.cn/Article/details/gt2geyhqbdx.html

[D17] 最大值与最小值
来源：http://dali.cucudq.cn/Article/details/gt2kvboqmat.html

Py:   max(arr);  min(arr)
来源：http://dali.gzhubu.top/Article/details/gt2yhhxkgoe.html

PHP:  max($arr);  min($arr);
来源：http://dali.fzhhl.top/Article/details/gt2vgjgqobb.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jianghu66.top/Article/details/gt2tmqajene.html

TS:   Math.max(...arr);
来源：http://dali.snrcjt.cn/Article/details/gt2oohmkrun.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.sweek.top/Article/details/gt2fyarrdga.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yj20258.top/Article/details/gt2bpvpjdgc.html

Ruby: arr.max;  arr.min
来源：http://dali.birdmap.top/Article/details/gt2yuoqthic.html

C#:   list.Max();  list.Min()
来源：http://dali.shzxlz.cn/Article/details/gt2tgdzzcjc.html

[D18] 扁平化嵌套数组
来源：http://dali.9152youxi.cn/Article/details/gt2butcexjp.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hammf.cn/Article/details/gt2cmvvmldz.html

PHP:  array_merge(...$nested);
来源：http://dali.0kj1m.cn/Article/details/gt2jzirgyia.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xziqi.cn/Article/details/gt2bfapiqxd.html

TS:   nested.flat();
来源：http://dali.aibaodan.cn/Article/details/gt2polaaboz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.aibaodan.cn/Article/details/gt2iacilneg.html

Go:   // 手写双层循环
来源：http://dali.chenlongwang.top/Article/details/gt2xsdydiph.html

Ruby: nested.flatten
来源：http://dali.jyoumei.cn/Article/details/gt2cezhcwkw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hnqzz.top/Article/details/gt2ioilhcjq.html

[D19] 按字段分组
来源：http://dali.c1oappe.top/Article/details/gt2atvevykw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2xowoojln.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jiagoushi.top/Article/details/gt2jtnsoyir.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.meibo888.top/Article/details/gt2behqubcc.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yonumen.top/Article/details/gt2ehbgekbh.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.chenzaomai.com/Article/details/gt2qczqhmdv.html

Go:   // 手写 map[string][]T
来源：http://dali.nwbrower.top/Article/details/gt2djxzcnte.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ppjwa.cn/Article/details/gt2uzfhzzbt.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.daria6918.cn/Article/details/gt2ibghpltg.html

[D20] 统计每个元素出现次数
来源：http://dali.daria6918.cn/Article/details/gt2ngcnafxr.html

Py:   Counter(arr)
来源：http://dali.cdnleiting.top/Article/details/gt2zrnbvxra.html

PHP:  array_count_values($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2wpwqpsof.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shzxlz.cn/Article/details/gt2oijytlcx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yvedp.cn/Article/details/gt2hybxndsd.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.meibo888.top/Article/details/gt2opqyqqys.html

Go:   // 手写 map[T]int
来源：http://dali.jinqigfzy.top/Article/details/gt2lqepiecf.html

Ruby: arr.tally
来源：http://dali.bjfxy.top/Article/details/gt2ppvoklem.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hywenlv.cn/Article/details/gt2obkvzkyv.html

[D21] 判断是否包含某元素
来源：http://dali.shangyingyoupin.top/Article/details/gt2fppgdjhi.html

Py:   x in arr
来源：http://dali.sxryk.cn/Article/details/gt2seclexlq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hysaishi.cn/Article/details/gt2hxnqfoql.html

JS:   arr.includes(x)
来源：http://dali.cqqwz.cn/Article/details/gt2nghqeied.html

TS:   arr.includes(x)
来源：http://dali.yongpay.top/Article/details/gt2dhykhchm.html

Java: list.contains(x)
来源：http://dali.hfpthk.cn/Article/details/gt2ashfvfou.html

Go:   slices.Contains(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fhofntcs.html

Ruby: arr.include?(x)
来源：http://dali.shuidangran.top/Article/details/gt2tebjeyru.html

C#:   list.Contains(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2eewjokni.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xegjqqqa.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xziqi.cn/Article/details/gt2hrtvonso.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hongshengwenyu.top/Article/details/gt2kziqeygi.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hnqzz.top/Article/details/gt2zuainnwv.html

TS:   [...arr];
来源：http://dali.daxiang520.top/Article/details/gt2hvprqzpu.html

Java: new ArrayList<>(list);
来源：http://dali.zhixingplan.top/Article/details/gt2zsyqxcwx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ompluiua.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ehwqpu.com/Article/details/gt2vlvenztz.html

C#:   new List<int>(list);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ajpjghis.html

[D23] reduce 累积计算
来源：http://dali.nanxuanxn.top/Article/details/gt2bputrjid.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.redwolf501.top/Article/details/gt2acldcatf.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yonumen.top/Article/details/gt2xgmmzfjr.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aizwys.cn/Article/details/gt2gzmsjlgb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenlongwang.top/Article/details/gt2xuafzoay.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.wangdashe.top/Article/details/gt2oatkdmor.html

Go:   // 手写循环
来源：http://dali.iojbl.cn/Article/details/gt2ojxiktyo.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.andypj.xyz/Article/details/gt2xtedwyft.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2aoxzpowk.html

[D24] 字典 / Map 基本操作
来源：http://dali.svipenyu.cn/Article/details/gt2aweplslh.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yongpay.top/Article/details/gt2adqefpeg.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yvedp.cn/Article/details/gt2kajahtoh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.gaohongyu789.top/Article/details/gt2xuhsipla.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gt2xqdqzdoj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.nanxuanxn.top/Article/details/gt2xttqtprm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.svipenyu.cn/Article/details/gt2pxtjvvhb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.guannengcc.top/Article/details/gt2xlrgqkal.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jqgfzy.top/Article/details/gt2lmzxnujw.html

[D25] Set 集合去重与交并差
来源：http://dali.xziqi.cn/Article/details/gt2rtofqwhz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.9152youxi.cn/Article/details/gt2xnrmuzjs.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.gotoacloud.top/Article/details/gt2vuxjvywx.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2okihxriq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yangfankeji.com/Article/details/gt2qtdoegwt.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2imvfkddr.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.c1oappe.top/Article/details/gt2ddfitwov.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2vgbwhrvh.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.redwolf501.top/Article/details/gt2vuahwwpt.html

[D26] 数组转字符串
来源：http://dali.gogol.net.cn/Article/details/gt2ntoankvu.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hongshengwenyu.top/Article/details/gt2csxshnpu.html

PHP:  implode(", ", $arr);
来源：http://dali.svipenyu.cn/Article/details/gt2fnqhnrbg.html

JS:   arr.join(", ")
来源：http://dali.ivvv.top/Article/details/gt2xlvfzcsh.html

TS:   arr.join(", ")
来源：http://dali.xuanzx.com/Article/details/gt2rtoshbnu.html

Java: String.join(", ", list)
来源：http://dali.sufxvd.cn/Article/details/gt2dxcpoisz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.nwbrower.top/Article/details/gt2fjbwnmbr.html

Ruby: arr.join(", ")
来源：http://dali.aizwys.cn/Article/details/gt2qkfhdnsw.html

C#:   string.Join(", ", list)
来源：http://dali.cashguo.top/Article/details/gt2tadfeyft.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sxjlydkx.html

E. 字符串处理
来源：http://dali.yuanzhike.top/Article/details/gt2ntafzqyr.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2affecddf.html

[E01] 拼接字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xwpjbdao.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.snrcjt.cn/Article/details/gt2lkgwotds.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xylfe.cn/Article/details/gt2bagvttvo.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.andypj.xyz/Article/details/gt2jtnthrng.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nanxuanxn.top/Article/details/gt2hwhmtqdg.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2jdcrzmid.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zdqjudy.top/Article/details/gt2nbzxvmrl.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sufxvd.cn/Article/details/gt2gzpaayzk.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gt2phfhskru.html

[E02] 重复字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2cucwurcn.html

Py:   "ab" * 3
来源：http://dali.chenzaomai.com/Article/details/gt2bzjxvpup.html

PHP:  str_repeat("ab", 3);
来源：http://dali.tian-w.cn/Article/details/gt2heyuhjvv.html

JS:   "ab".repeat(3)
来源：http://dali.andypj.xyz/Article/details/gt2arijeqoc.html

TS:   "ab".repeat(3)
来源：http://dali.guannengcc.top/Article/details/gt2cwgfqqmx.html

Java: "ab".repeat(3)
来源：http://dali.zhixingplan.top/Article/details/gt2hlfjlpqu.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhixingplan.top/Article/details/gt2veavmqha.html

Ruby: "ab" * 3
来源：http://dali.andypj.xyz/Article/details/gt2jtavdlna.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xylfe.cn/Article/details/gt2ajaqupmr.html

[E03] 截取子串
来源：http://dali.gotoacloud.top/Article/details/gt2riedzqqs.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.havefunace.top/Article/details/gt2pkodvxey.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cxhdthuv.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.0kj1m.cn/Article/details/gt2pgbxwdrx.html

TS:   s.slice(1, 4)
来源：http://dali.guowangkeji.top/Article/details/gt2gtsmapgh.html

Java: s.substring(1, 4)
来源：http://dali.ydzc1.top/Article/details/gt2shadpcxt.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yj202588.top/Article/details/gt2egfnwkmv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.chenlongwang.top/Article/details/gt2juyhyktg.html

C#:   s.Substring(1, 3)
来源：http://dali.hammf.cn/Article/details/gt2vvecczuw.html

[E04] 查找子串位置
来源：http://dali.bjfxy.top/Article/details/gt2sqpsxewg.html

Py:   s.find("x");  s.index("x")
来源：http://dali.andypj.xyz/Article/details/gt2vsfhhgbq.html

PHP:  strpos($s, "x");
来源：http://dali.pengpengdd.cyou/Article/details/gt2aypryqvh.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jiagoushi.top/Article/details/gt2fcujhjmj.html

TS:   s.indexOf("x")
来源：http://dali.pengpengdd.cyou/Article/details/gt2hubwdpca.html

Java: s.indexOf("x")
来源：http://dali.guowangkeji.top/Article/details/gt2slfengfa.html

Go:   strings.Index(s, "x")
来源：http://dali.fzhhl.top/Article/details/gt2nkhefduq.html

Ruby: s.index("x")
来源：http://dali.daria6918.cn/Article/details/gt2omiqsurd.html

C#:   s.IndexOf("x")
来源：http://dali.sysykeji.top/Article/details/gt2cnidquwt.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2piexrcqd.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.9152youxi.cn/Article/details/gt2wxfwakzg.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shangyingyoupin.top/Article/details/gt2txwumikx.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuanzhike.top/Article/details/gt2dgqkqrks.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yanxiufei.cn/Article/details/gt2riicnjup.html


<!-- 参考信息 -->