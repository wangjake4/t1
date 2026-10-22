代发 wailian999

Go:   arr[0]; arr[0] = 9
来源：http://dali.0kj1m.cn/Article/details/gt2hhxghhbf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jianghu66.top/Article/details/gt2nazxttef.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.aibaodan.cn/Article/details/gt2wwcrcxuw.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sbzucgds.html

Py:   len(arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2ndrrnazz.html

PHP:  count($arr);
来源：http://dali.jinqigufen.top/Article/details/gt2xwjuaxoy.html

JS:   arr.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kmudrlfl.html

TS:   arr.length
来源：http://dali.chenlongwang.top/Article/details/gt2saccynom.html

Java: list.size();
来源：http://dali.9152youxi.cn/Article/details/gt2mexfjppr.html

Go:   len(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gt2kezxtcpa.html

Ruby: arr.length; arr.size
来源：http://dali.haohaochexian.top/Article/details/gt2boxpmpwg.html

C#:   list.Count;
来源：http://dali.xuanzx.com/Article/details/gt2rbilnusq.html

[D07] 切片 / 取子数组
来源：http://dali.shuidangran.top/Article/details/gt2bkpkxmbr.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yj20258.top/Article/details/gt2nmmjltae.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.tanke756.top/Article/details/gt2xdgcaune.html

JS:   arr.slice(1, 4);
来源：http://dali.0kj1m.cn/Article/details/gt2gaoxdeuk.html

TS:   arr.slice(1, 4);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2umjyfxij.html

Java: list.subList(1, 4);
来源：http://dali.chenjidiqi.icu/Article/details/gt2iihlxoit.html

Go:   arr[1:4]
来源：http://dali.yvedp.cn/Article/details/gt2lqlyxkxx.html

Ruby: arr[1, 3]
来源：http://dali.meibo888.top/Article/details/gt2lnxunsat.html

C#:   list.GetRange(1, 3);
来源：http://dali.jqgufenzy.top/Article/details/gt2fsshowiw.html

[D08] 合并两个数组
来源：http://dali.c1oappe.top/Article/details/gt2canthusj.html

Py:   a + b;  a.extend(b)
来源：http://dali.sweek.top/Article/details/gt2eebvrmzl.html

PHP:  array_merge($a, $b);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zwbcihlf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhongyouzk.top/Article/details/gt2edmrthcd.html

TS:   [...a, ...b];
来源：http://dali.9152youxi.cn/Article/details/gt2jagbqxrp.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2jkfdzwjq.html

Go:   append(a, b...)
来源：http://dali.iojbl.cn/Article/details/gt2grmjmrvf.html

Ruby: a + b;  a.concat(b)
来源：http://dali.iojbl.cn/Article/details/gt2jqzphrzp.html

C#:   a.Concat(b).ToList()
来源：http://dali.sxryk.cn/Article/details/gt2mtreglgm.html

[D09] 排序（升序）
来源：http://dali.andypj.xyz/Article/details/gt2avwaogrq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fengsongda.top/Article/details/gt2ggijhqjj.html

PHP:  sort($arr);
来源：http://dali.meibo888.top/Article/details/gt2heefxlrq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.chenzaomai.com/Article/details/gt2mjqswxlu.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.kuanghao11.cn/Article/details/gt2hvjardal.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sufxvd.cn/Article/details/gt2cuqcgtpf.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.nwbrower.top/Article/details/gt2iaekumoi.html

Ruby: arr.sort
来源：http://dali.hfpthk.cn/Article/details/gt2fpnjayln.html

C#:   list.Sort();
来源：http://dali.aizwys.cn/Article/details/gt2zdimgsvw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jqgufenzy.top/Article/details/gt2vfiylsri.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.gzhubu.top/Article/details/gt2omioxafb.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ppjwa.cn/Article/details/gt2gdcrotaa.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shangyingyoupin.top/Article/details/gt2grepoimh.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zdqjudy.top/Article/details/gt2dthzitrn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.havefunace.top/Article/details/gt2dadsetwr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.svipenyu.cn/Article/details/gt2kbgzwtrx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.c1oappe.top/Article/details/gt2gfxjxxmy.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pyzqdcfh.html

[D11] 反转数组
来源：http://dali.vqdsnc.cn/Article/details/gt2ptdemvug.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.c1oappe.top/Article/details/gt2cfhxwazz.html

PHP:  array_reverse($arr);
来源：http://dali.c1oappe.top/Article/details/gt2uiaeukty.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yueranfly.top/Article/details/gt2efenqkvl.html

TS:   [...arr].reverse();
来源：http://dali.ydzc1.top/Article/details/gt2dckraigc.html

Java: Collections.reverse(list);
来源：http://dali.quarkkingdee.top/Article/details/gt2ighvrjlp.html

Go:   slices.Reverse(arr)
来源：http://dali.hfpthk.cn/Article/details/gt2hfbsjspl.html

Ruby: arr.reverse
来源：http://dali.ppjwa.cn/Article/details/gt2kyaphsxl.html

C#:   list.Reverse();
来源：http://dali.hnxiangtu.top/Article/details/gt2cxzmzyik.html

[D12] 查找元素下标
来源：http://dali.zhiwuduotai.top/Article/details/gt2toavtiuc.html

Py:   arr.index(x);  x in arr
来源：http://dali.kuanghao11.cn/Article/details/gt2qylysxur.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qijoysnx.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tian-w.cn/Article/details/gt2rsjecqie.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.wangdashe.top/Article/details/gt2cptyiyfv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhiwuduotai.top/Article/details/gt2dibevejg.html

Go:   slices.Index(arr, x)
来源：http://dali.yueranfly.top/Article/details/gt2fldbwnxu.html

Ruby: arr.index(x)
来源：http://dali.hywenlv.cn/Article/details/gt2ekfmcaov.html

C#:   list.IndexOf(x);
来源：http://dali.yj20258.top/Article/details/gt2mdoaujsl.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sysykeji.top/Article/details/gt2rglblqgx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yanxiufei.cn/Article/details/gt2iplokfhz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.tianlin.xyz/Article/details/gt2ifpmlsab.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cheryme.top/Article/details/gt2gwtgcivp.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jianghu66.top/Article/details/gt2xmespsnu.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.sweek.top/Article/details/gt2uiepngum.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.nanxinkj.top/Article/details/gt2gotibiam.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.birdmap.top/Article/details/gt2opounojn.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mdsmsiom.html

[D14] 映射转换（每个元素变形）
来源：http://dali.aibaodan.cn/Article/details/gt2snukeczk.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mdejqetn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.gaohongyu789.top/Article/details/gt2adxwrwmn.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhixingplan.top/Article/details/gt2mqxudkta.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhongyouzk.top/Article/details/gt2bqehkukw.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.redwolf501.top/Article/details/gt2qcjkxugl.html

Go:   // 手写循环
来源：http://dali.daria6918.cn/Article/details/gt2jllixayd.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.nanxuanxn.top/Article/details/gt2snmhalpp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yuxming.cn/Article/details/gt2wnwnvxhu.html

[D15] 去重
来源：http://dali.feifeiyinyue.top/Article/details/gt2phcfruhp.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.pycfn.com/Article/details/gt2sqsxddwa.html

PHP:  array_unique($arr);
来源：http://dali.ivvv.top/Article/details/gt2snysxhxn.html

JS:   [...new Set(arr)]
来源：http://dali.yangfankeji.com/Article/details/gt2efmgxmmy.html

TS:   [...new Set(arr)]
来源：http://dali.jqgufenzy.top/Article/details/gt2jprsdhix.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cdnleiting.top/Article/details/gt2wvtcwcfi.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.vqdsnc.cn/Article/details/gt2gebnqpwe.html

Ruby: arr.uniq
来源：http://dali.hammf.cn/Article/details/gt2bilbtzde.html

C#:   list.Distinct().ToList()
来源：http://dali.yj20258888.top/Article/details/gt2vphcsiry.html

[D16] 求和与平均值
来源：http://dali.shuidangran.top/Article/details/gt2lfctqlzh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2tmuguxnq.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jinqigufen.top/Article/details/gt2fxntizcd.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guannengcc.top/Article/details/gt2ioejashh.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sxryk.cn/Article/details/gt2ylofczys.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hnxiangtu.top/Article/details/gt2mrrvljuy.html

Go:   // 手写循环累加
来源：http://dali.chenlongwang.top/Article/details/gt2rdowsnka.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.nwbrower.top/Article/details/gt2krdrizvq.html

C#:   list.Sum();  list.Average()
来源：http://dali.nanxinkj.top/Article/details/gt2idohbhqn.html

[D17] 最大值与最小值
来源：http://dali.havefunace.top/Article/details/gt2xbjgdmjv.html

Py:   max(arr);  min(arr)
来源：http://dali.smart0.xyz/Article/details/gt2hznpxcaa.html

PHP:  max($arr);  min($arr);
来源：http://dali.hammf.cn/Article/details/gt2pjvxztnr.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.mhx1999.top/Article/details/gt2fmmyszth.html

TS:   Math.max(...arr);
来源：http://dali.ehwqpu.com/Article/details/gt2hhpqxztp.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hysaishi.cn/Article/details/gt2svckmlow.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yj20258.top/Article/details/gt2qefxvkpo.html

Ruby: arr.max;  arr.min
来源：http://dali.havefunace.top/Article/details/gt2rdimfcvu.html

C#:   list.Max();  list.Min()
来源：http://dali.yuxming.cn/Article/details/gt2bchkuteh.html

[D18] 扁平化嵌套数组
来源：http://dali.feifeiyinyue.top/Article/details/gt2sacbrrpl.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cqqwz.cn/Article/details/gt2avrwiswf.html

PHP:  array_merge(...$nested);
来源：http://dali.hnqzz.top/Article/details/gt2iddllnnv.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.birdmap.top/Article/details/gt2xfwksiig.html

TS:   nested.flat();
来源：http://dali.yangfankeji.com/Article/details/gt2mozapsem.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zycfv.cn/Article/details/gt2ubyejhxu.html

Go:   // 手写双层循环
来源：http://dali.sxryk.cn/Article/details/gt2gcxnvbvd.html

Ruby: nested.flatten
来源：http://dali.guannengcc.top/Article/details/gt2jalkawsw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.wangdashe.top/Article/details/gt2cviwmdfr.html

[D19] 按字段分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eoblykai.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.bjfxy.top/Article/details/gt2epmxkkfa.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yvedp.cn/Article/details/gt2hasijenx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jlsjyb.cn/Article/details/gt2nsdwwkly.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jiagoushi.top/Article/details/gt2qkosijad.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yangfankeji.com/Article/details/gt2wsdtowxz.html

Go:   // 手写 map[string][]T
来源：http://dali.yueranfly.top/Article/details/gt2lsedoccd.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.redwolf501.top/Article/details/gt2msythtcr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jlsjyb.cn/Article/details/gt2abhlmuur.html

[D20] 统计每个元素出现次数
来源：http://dali.ehwqpu.com/Article/details/gt2jmmdxhvw.html

Py:   Counter(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2exwekhwf.html

PHP:  array_count_values($arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2wgmljlah.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgfzy.top/Article/details/gt2txzdzkiv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hammf.cn/Article/details/gt2rvfndqnn.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.bjfxy.top/Article/details/gt2oxfbumhm.html

Go:   // 手写 map[T]int
来源：http://dali.yj202588.top/Article/details/gt2xabueuos.html

Ruby: arr.tally
来源：http://dali.nanxinkj.top/Article/details/gt2lezfmenz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.meibo888.top/Article/details/gt2ckedkhre.html

[D21] 判断是否包含某元素
来源：http://dali.gogol.net.cn/Article/details/gt2bpzcvfkg.html

Py:   x in arr
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2anpbykmh.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yangfankeji.com/Article/details/gt2goeuwzgi.html

JS:   arr.includes(x)
来源：http://dali.zhoulong.xyz/Article/details/gt2ttplnpns.html

TS:   arr.includes(x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gsyrkltv.html

Java: list.contains(x)
来源：http://dali.dashuyun.cn/Article/details/gt2iujwamnm.html

Go:   slices.Contains(arr, x)
来源：http://dali.andypj.xyz/Article/details/gt2eiyyycbt.html

Ruby: arr.include?(x)
来源：http://dali.chenzaomai.com/Article/details/gt2tbpafrfx.html

C#:   list.Contains(x)
来源：http://dali.zhoulong.xyz/Article/details/gt2zhsajypn.html

[D22] 复制数组（避免共享引用）
来源：http://dali.gotoacloud.top/Article/details/gt2ytkfdspc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.fengsongda.top/Article/details/gt2xwedygqg.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yongpay.top/Article/details/gt2zwwqehih.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2dlmzrnqh.html

TS:   [...arr];
来源：http://dali.wangdashe.top/Article/details/gt2ppwwreow.html

Java: new ArrayList<>(list);
来源：http://dali.iojbl.cn/Article/details/gt2amdkfecc.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.bjfxy.top/Article/details/gt2vfjoblkz.html

Ruby: arr.dup;  arr.clone
来源：http://dali.dashuyun.cn/Article/details/gt2npqxhcxc.html

C#:   new List<int>(list);
来源：http://dali.chenjidiqi.icu/Article/details/gt2sbipjmne.html

[D23] reduce 累积计算
来源：http://dali.tanke756.top/Article/details/gt2klnsvygs.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qrqrllqq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fqsfrcol.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hammf.cn/Article/details/gt2hhlpsbxq.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.fzhhl.top/Article/details/gt2fgalzoty.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.kuanghao11.cn/Article/details/gt2itxtbzwn.html

Go:   // 手写循环
来源：http://dali.tanke756.top/Article/details/gt2bhefrysi.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhixingplan.top/Article/details/gt2brbjuzrs.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2fdikdwxy.html

[D24] 字典 / Map 基本操作
来源：http://dali.shuidangran.top/Article/details/gt2qvgfczpk.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.birdmap.top/Article/details/gt2vkdrairs.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hywenlv.cn/Article/details/gt2bbfxkmpe.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yj202588.top/Article/details/gt2uroqxemn.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jianghu66.top/Article/details/gt2pdnxpzoi.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.quarkkingdee.top/Article/details/gt2vbvikbvb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.gotoacloud.top/Article/details/gt2wukthbqr.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yj202588.top/Article/details/gt2rmgykrrt.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gzhubu.top/Article/details/gt2dtzedhra.html

[D25] Set 集合去重与交并差
来源：http://dali.yj202588.top/Article/details/gt2lywlhfta.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhixingplan.top/Article/details/gt2bqptzeka.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2odswvszs.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2kkwiemwk.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eksyhoka.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yuxming.cn/Article/details/gt2yahdxdjp.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shangyingyoupin.top/Article/details/gt2ndfobrer.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gzhubu.top/Article/details/gt2kinlmltp.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yj20258888.top/Article/details/gt2gxvjyyob.html

[D26] 数组转字符串
来源：http://dali.hongshengwenyu.top/Article/details/gt2cfzrcvhl.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zycfv.cn/Article/details/gt2dfzpktkh.html

PHP:  implode(", ", $arr);
来源：http://dali.dashuyun.cn/Article/details/gt2pelofeed.html

JS:   arr.join(", ")
来源：http://dali.yangfankeji.com/Article/details/gt2dmsgdilx.html

TS:   arr.join(", ")
来源：http://dali.fengsongda.top/Article/details/gt2ibejptuv.html

Java: String.join(", ", list)
来源：http://dali.haohaochexian.top/Article/details/gt2eqdfetfb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinqigfzy.top/Article/details/gt2ibgbsguy.html

Ruby: arr.join(", ")
来源：http://dali.chenlongwang.top/Article/details/gt2rjsfpasx.html

C#:   string.Join(", ", list)
来源：http://dali.zhoulong.xyz/Article/details/gt2qvcdzwut.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2xeqcuiau.html

E. 字符串处理
来源：http://dali.xuetiantiany.cn/Article/details/gt2oygsrafo.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2gxfzelcz.html

[E01] 拼接字符串
来源：http://dali.meibo888.top/Article/details/gt2zehbmcxh.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dkqiqppf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.feifeiyinyue.top/Article/details/gt2hndwgpkz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.iojbl.cn/Article/details/gt2menprjff.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.wangshuangyany.cn/Article/details/gt2qnfaplbi.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jqgfzy.top/Article/details/gt2fbquzuvw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.tianlin.xyz/Article/details/gt2zqucmezs.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhengqikj.top/Article/details/gt2qateisnr.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xziqi.cn/Article/details/gt2jgnskcux.html

[E02] 重复字符串
来源：http://dali.kuanghao11.cn/Article/details/gt2slmeuurl.html

Py:   "ab" * 3
来源：http://dali.haohaochexian.top/Article/details/gt2hnyhzqfs.html

PHP:  str_repeat("ab", 3);
来源：http://dali.vqdsnc.cn/Article/details/gt2pzvrnxjn.html

JS:   "ab".repeat(3)
来源：http://dali.ydzc1.top/Article/details/gt2ivsmesjf.html

TS:   "ab".repeat(3)
来源：http://dali.wangshuangyany.cn/Article/details/gt2udxzlkvk.html

Java: "ab".repeat(3)
来源：http://dali.iojbl.cn/Article/details/gt2zwcxgfyz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xziqi.cn/Article/details/gt2bmjazarx.html

Ruby: "ab" * 3
来源：http://dali.fzhhl.top/Article/details/gt2wwsfxyux.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cashguo.top/Article/details/gt2arvaiqhv.html

[E03] 截取子串
来源：http://dali.shzxlz.cn/Article/details/gt2hrmkwcyg.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jqgufenzy.top/Article/details/gt2mudawocj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gt2kluvtfro.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.nanxinkj.top/Article/details/gt2nezpfabe.html

TS:   s.slice(1, 4)
来源：http://dali.cashguo.top/Article/details/gt2hdhuqlqj.html

Java: s.substring(1, 4)
来源：http://dali.zhixingplan.top/Article/details/gt2epzdeegd.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yj202588.top/Article/details/gt2xqjsucvj.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.mhx1999.top/Article/details/gt2visdzggb.html

C#:   s.Substring(1, 3)
来源：http://dali.daria6918.cn/Article/details/gt2ttejtbey.html

[E04] 查找子串位置
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oagxeylh.html

Py:   s.find("x");  s.index("x")
来源：http://dali.nanxuanxn.top/Article/details/gt2llantpun.html

PHP:  strpos($s, "x");
来源：http://dali.cqqwz.cn/Article/details/gt2skbykoyd.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2edhocuzo.html

TS:   s.indexOf("x")
来源：http://dali.shangyingyoupin.top/Article/details/gt2revcctnn.html

Java: s.indexOf("x")
来源：http://dali.zhixingplan.top/Article/details/gt2xesflbqo.html

Go:   strings.Index(s, "x")
来源：http://dali.yj20258.top/Article/details/gt2fuacvrtp.html

Ruby: s.index("x")
来源：http://dali.hnqzz.top/Article/details/gt2byxoukhb.html

C#:   s.IndexOf("x")
来源：http://dali.sufxvd.cn/Article/details/gt2bvccgyha.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shangyingyoupin.top/Article/details/gt2cfewjdau.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhixingplan.top/Article/details/gt2jtbwhdcu.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.fzhhl.top/Article/details/gt2waiyyznu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ivvv.top/Article/details/gt2zmnbrptf.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.aibaodan.cn/Article/details/gt2cxyudtha.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuxming.cn/Article/details/gt2dxdbitjc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.sufxvd.cn/Article/details/gt2rqdemgsp.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jinqigufen.top/Article/details/gt2xesrbdtn.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yuanzhike.top/Article/details/gt2wseypavz.html

[E06] 替换子串
来源：http://dali.ehwqpu.com/Article/details/gt2rxmvlawb.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.gotoacloud.top/Article/details/gt2yegwizyh.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shuidangran.top/Article/details/gt2xdczlvcy.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gt2kjmitloi.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yonumen.top/Article/details/gt2jdfjssdv.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sysykeji.top/Article/details/gt2nopihknd.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lohbcmmr.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gt2qfflzfgc.html

C#:   s.Replace("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gt2hisplgrv.html

[E07] 按分隔符拆分
来源：http://dali.c1oappe.top/Article/details/gt2yuehhxih.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yangfankeji.com/Article/details/gt2rzerhgqp.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.dianchejie.cn/Article/details/gt2orhxrnmm.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.tanke756.top/Article/details/gt2iengpcyo.html

TS:   s.split(",")
来源：http://dali.shuidangran.top/Article/details/gt2ekjzrulv.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.andypj.xyz/Article/details/gt2fglkrywo.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.daria6918.cn/Article/details/gt2hbhkajxd.html

Ruby: s.split(",");  s.split
来源：http://dali.zhongyouzk.top/Article/details/gt2wempuozv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yj20258888.top/Article/details/gt2auvkmxqp.html

[E08] 数组按分隔符合并
来源：http://dali.sufxvd.cn/Article/details/gt2zirlmmik.html

Py:   ",".join(items)
来源：http://dali.aibaodan.cn/Article/details/gt2usmqcobq.html

PHP:  implode(",", $items);
来源：http://dali.316326.xyz/Article/details/gt2tedhugms.html

JS:   items.join(",")
来源：http://dali.smart0.xyz/Article/details/gt2nuwfgrcj.html

TS:   items.join(",")
来源：http://dali.shangyingyoupin.top/Article/details/gt2msfmhuvf.html

Java: String.join(",", items)
来源：http://dali.jinqigfzy.top/Article/details/gt2mttdvpde.html

Go:   strings.Join(items, ",")
来源：http://dali.chenjidiqi.icu/Article/details/gt2zarxggnt.html

Ruby: items.join(",")
来源：http://dali.chenlongwang.top/Article/details/gt2xtrqkvkt.html

C#:   string.Join(",", items)
来源：http://dali.haohaochexian.top/Article/details/gt2qvidptda.html

[E09] 去除所有空白字符
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tjroqtku.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yonumen.top/Article/details/gt2twyjlgpe.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.c1oappe.top/Article/details/gt2qkgrassj.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhoulong.xyz/Article/details/gt2xekknnsm.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhiwuduotai.top/Article/details/gt2zrhblmtt.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.havefunace.top/Article/details/gt2aamnutuu.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gzhubu.top/Article/details/gt2fkchfnpx.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.pengpengdd.cyou/Article/details/gt2hpojuqfz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xinyue.icu/Article/details/gt2ynfcdxvm.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zycfv.cn/Article/details/gt2lpwehyil.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.havefunace.top/Article/details/gt2buvvkgso.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.bjfxy.top/Article/details/gt2bobycicb.html

JS:   "7".padStart(3, "0")
来源：http://dali.aibaodan.cn/Article/details/gt2unfclobs.html

TS:   "7".padStart(3, "0")
来源：http://dali.hammf.cn/Article/details/gt2xwkkzfsc.html

Java: String.format("%03d", 7)
来源：http://dali.haohaochexian.top/Article/details/gt2tvyxfwcv.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhssikz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jinqigufen.top/Article/details/gt2gqswodmf.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.birdmap.top/Article/details/gt2dbatkiwd.html

[E11] 反转字符串
来源：http://dali.zdqjudy.top/Article/details/gt2pogmlqmp.html

Py:   s[::-1]
来源：http://dali.hnxiangtu.top/Article/details/gt2mxaveokq.html

PHP:  strrev($s);
来源：http://dali.tanke756.top/Article/details/gt2nosmnkfg.html

JS:   [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gt2cbkbujta.html

TS:   [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gt2qssqudjv.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.redwolf501.top/Article/details/gt2npzlujgy.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.wangdashe.top/Article/details/gt2mhrnhewc.html

Ruby: s.reverse
来源：http://dali.redwolf501.top/Article/details/gt2qfqeoacf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.wangshuangyany.cn/Article/details/gt2wwhkczpo.html

[E12] 统计某字符出现次数
来源：http://dali.yj20258888.top/Article/details/gt2hwyfxcbd.html

Py:   s.count("a")
来源：http://dali.yvedp.cn/Article/details/gt2rsjtriyt.html

PHP:  substr_count($s, "a");
来源：http://dali.wangshuangyany.cn/Article/details/gt2fnkovkpo.html

JS:   s.split("a").length - 1
来源：http://dali.guowangkeji.top/Article/details/gt2jmgiiria.html

TS:   s.split("a").length - 1
来源：http://dali.jinqigufen.top/Article/details/gt2fxiyozsz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yvtabfxc.html


<!-- 参考信息 -->