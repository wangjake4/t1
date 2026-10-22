代发 wailian999

Go:   arr[0]; arr[0] = 9
来源：http://dali.tian-w.cn/Article/details/gt2cminqelk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xziqi.cn/Article/details/gt2pxheuzrt.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hjcfwtuv.html

[D06] 数组长度
来源：http://dali.nanxuanxn.top/Article/details/gt2xbqiqygl.html

Py:   len(arr)
来源：http://dali.fengsongda.top/Article/details/gt2mbgjjrkb.html

PHP:  count($arr);
来源：http://dali.iojbl.cn/Article/details/gt2beqzzgdy.html

JS:   arr.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fwvlltmk.html

TS:   arr.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dihdvvfv.html

Java: list.size();
来源：http://dali.jianghu66.top/Article/details/gt2wulgphji.html

Go:   len(arr)
来源：http://dali.pycfn.com/Article/details/gt2kypzziig.html

Ruby: arr.length; arr.size
来源：http://dali.sufxvd.cn/Article/details/gt2qrxyfzjb.html

C#:   list.Count;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ptqkovkx.html

[D07] 切片 / 取子数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rpipfttl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hfpthk.cn/Article/details/gt2acxynawy.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2amyavmpw.html

JS:   arr.slice(1, 4);
来源：http://dali.tianlin.xyz/Article/details/gt2fvknlksr.html

TS:   arr.slice(1, 4);
来源：http://dali.cdnleiting.top/Article/details/gt2bexrrhaf.html

Java: list.subList(1, 4);
来源：http://dali.kuanghao11.cn/Article/details/gt2tvgliqpq.html

Go:   arr[1:4]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fycwhkpd.html

Ruby: arr[1, 3]
来源：http://dali.fengsongda.top/Article/details/gt2lsunutma.html

C#:   list.GetRange(1, 3);
来源：http://dali.yongpay.top/Article/details/gt2cpbmhwpy.html

[D08] 合并两个数组
来源：http://dali.gotoacloud.top/Article/details/gt2lxztvcpm.html

Py:   a + b;  a.extend(b)
来源：http://dali.cqqwz.cn/Article/details/gt2klhptzez.html

PHP:  array_merge($a, $b);
来源：http://dali.tianlin.xyz/Article/details/gt2qvudajvl.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jqgfzy.top/Article/details/gt2ducvlmba.html

TS:   [...a, ...b];
来源：http://dali.nanxinkj.top/Article/details/gt2urxittxe.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.guowangkeji.top/Article/details/gt2qlemtuhh.html

Go:   append(a, b...)
来源：http://dali.tian-w.cn/Article/details/gt2wokisbtk.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jinqigufen.top/Article/details/gt2carmpruw.html

C#:   a.Concat(b).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gt2jrpbfvqr.html

[D09] 排序（升序）
来源：http://dali.chenlongwang.top/Article/details/gt2lkiyqolo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigfzy.top/Article/details/gt2bmirvqye.html

PHP:  sort($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ocboavjd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ivvv.top/Article/details/gt2jrmdhcmj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ybcxt.top/Article/details/gt2fokomciw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jqgufenzy.top/Article/details/gt2xrqozeie.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tybkfoit.html

Ruby: arr.sort
来源：http://dali.cashguo.top/Article/details/gt2tuoxcvjs.html

C#:   list.Sort();
来源：http://dali.jiagoushi.top/Article/details/gt2ljnkuevi.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cashguo.top/Article/details/gt2pbumjqra.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.redwolf501.top/Article/details/gt2hylylowe.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.vqdsnc.cn/Article/details/gt2uswquzrn.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.316326.xyz/Article/details/gt2fvvmcrcp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.birdmap.top/Article/details/gt2rnughdov.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cdnleiting.top/Article/details/gt2mqyfelpy.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.guannengcc.top/Article/details/gt2jqswijmi.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2slrmlrpr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jlsjyb.cn/Article/details/gt2zmsqjdlb.html

[D11] 反转数组
来源：http://dali.quarkkingdee.top/Article/details/gt2ofvfwmpp.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.haohaochexian.top/Article/details/gt2nqxfmwop.html

PHP:  array_reverse($arr);
来源：http://dali.yvedp.cn/Article/details/gt2sodqtzdi.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.chenlongwang.top/Article/details/gt2mgtnsptr.html

TS:   [...arr].reverse();
来源：http://dali.chenlongwang.top/Article/details/gt2yzvgwzly.html

Java: Collections.reverse(list);
来源：http://dali.jiagoushi.top/Article/details/gt2xqmivvyz.html

Go:   slices.Reverse(arr)
来源：http://dali.gotoacloud.top/Article/details/gt2pjxgxauf.html

Ruby: arr.reverse
来源：http://dali.gogol.net.cn/Article/details/gt2cqrlylik.html

C#:   list.Reverse();
来源：http://dali.redwolf501.top/Article/details/gt2rccblyev.html

[D12] 查找元素下标
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2busotldy.html

Py:   arr.index(x);  x in arr
来源：http://dali.yj20258888.top/Article/details/gt2nzfecuni.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shuidangran.top/Article/details/gt2rdoqveox.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gogol.net.cn/Article/details/gt2cwpamhgz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.mhx1999.top/Article/details/gt2lbslwkwo.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ccbbazzs.html

Go:   slices.Index(arr, x)
来源：http://dali.sysykeji.top/Article/details/gt2audlieaw.html

Ruby: arr.index(x)
来源：http://dali.iojbl.cn/Article/details/gt2nkoumhlh.html

C#:   list.IndexOf(x);
来源：http://dali.xinyue.icu/Article/details/gt2nhfcmdkj.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jqgfzy.top/Article/details/gt2qhynlziw.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yj202588.top/Article/details/gt2fszhreig.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yj20258.top/Article/details/gt2iodqucdk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jinqigufen.top/Article/details/gt2xxbbijam.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cashguo.top/Article/details/gt2cbjsholo.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xziqi.cn/Article/details/gt2grxtruaz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yj20258.top/Article/details/gt2gwzarxtg.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.kuanghao11.cn/Article/details/gt2caireoql.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shzxlz.cn/Article/details/gt2japjrxal.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jinqigufen.top/Article/details/gt2gnnendcm.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.c1oappe.top/Article/details/gt2xfllvghe.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.wangdashe.top/Article/details/gt2vmmmkwjz.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhoulong.xyz/Article/details/gt2yvkodila.html

TS:   arr.map(x => x * 2)
来源：http://dali.svipenyu.cn/Article/details/gt2hsfbxidr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2xnyewvqt.html

Go:   // 手写循环
来源：http://dali.zhongyouzk.top/Article/details/gt2dtwgldic.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cokxfexk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.fengsongda.top/Article/details/gt2jszilrll.html

[D15] 去重
来源：http://dali.tianlin.xyz/Article/details/gt2sspqhnoo.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cqqwz.cn/Article/details/gt2qfbgnvpr.html

PHP:  array_unique($arr);
来源：http://dali.jiagoushi.top/Article/details/gt2qydihhbv.html

JS:   [...new Set(arr)]
来源：http://dali.nwbrower.top/Article/details/gt2xofjyyab.html

TS:   [...new Set(arr)]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cdrpakbl.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.tian-w.cn/Article/details/gt2stcnymyc.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ivvv.top/Article/details/gt2gtlydftf.html

Ruby: arr.uniq
来源：http://dali.chenlongwang.top/Article/details/gt2zifljalg.html

C#:   list.Distinct().ToList()
来源：http://dali.tian-w.cn/Article/details/gt2nwuwlmae.html

[D16] 求和与平均值
来源：http://dali.chenzaomai.com/Article/details/gt2ocjoxojd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.vqdsnc.cn/Article/details/gt2panucotz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pmteicpz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenlongwang.top/Article/details/gt2ehhfdinm.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.dianchejie.cn/Article/details/gt2gjehqaaj.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhengqikj.top/Article/details/gt2wijvuuwg.html

Go:   // 手写循环累加
来源：http://dali.zhoulong.xyz/Article/details/gt2igkgjmdw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jianghu66.top/Article/details/gt2bhxooucj.html

C#:   list.Sum();  list.Average()
来源：http://dali.cdnleiting.top/Article/details/gt2eypvghhs.html

[D17] 最大值与最小值
来源：http://dali.chenzaomai.com/Article/details/gt2jdgrkxrz.html

Py:   max(arr);  min(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2gpvrdgtk.html

PHP:  max($arr);  min($arr);
来源：http://dali.ybcxt.top/Article/details/gt2epozzzsv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jqgfzy.top/Article/details/gt2rbgnqgxo.html

TS:   Math.max(...arr);
来源：http://dali.cucudq.cn/Article/details/gt2mhherfcd.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gaohongyu789.top/Article/details/gt2pkuwvltr.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sysykeji.top/Article/details/gt2insbggbn.html

Ruby: arr.max;  arr.min
来源：http://dali.pycfn.com/Article/details/gt2amigazzf.html

C#:   list.Max();  list.Min()
来源：http://dali.gzhubu.top/Article/details/gt2oiauukwv.html

[D18] 扁平化嵌套数组
来源：http://dali.jqgufenzy.top/Article/details/gt2ckkrptus.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yanxiufei.cn/Article/details/gt2fyatrfsi.html

PHP:  array_merge(...$nested);
来源：http://dali.xuanzx.com/Article/details/gt2iwlrfyoa.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jyoumei.cn/Article/details/gt2czcrmwoa.html

TS:   nested.flat();
来源：http://dali.guannengcc.top/Article/details/gt2thjkirwq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xylfe.cn/Article/details/gt2vzwdrtnz.html

Go:   // 手写双层循环
来源：http://dali.kuanghao11.cn/Article/details/gt2anagjmyn.html

Ruby: nested.flatten
来源：http://dali.yvedp.cn/Article/details/gt2dotgcxxb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gt2sulhtaxo.html

[D19] 按字段分组
来源：http://dali.vqdsnc.cn/Article/details/gt2bouwlmst.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.iojbl.cn/Article/details/gt2mzeemham.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.nanxuanxn.top/Article/details/gt2ndvjksmv.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yj20258.top/Article/details/gt2qiznehvj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yanxiufei.cn/Article/details/gt2hlgklekz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.aibaodan.cn/Article/details/gt2zxsfifmi.html

Go:   // 手写 map[string][]T
来源：http://dali.daxiang520.top/Article/details/gt2stgrrbnl.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhoulong.xyz/Article/details/gt2yyeflwuk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yuanzhike.top/Article/details/gt2wwlekhxb.html

[D20] 统计每个元素出现次数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xbxozbvj.html

Py:   Counter(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2uyzibuxg.html

PHP:  array_count_values($arr);
来源：http://dali.svipenyu.cn/Article/details/gt2bpldqmva.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gexlksxr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ncszdmym.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.havefunace.top/Article/details/gt2hqjwonvh.html

Go:   // 手写 map[T]int
来源：http://dali.chenjidiqi.icu/Article/details/gt2dsfgogls.html

Ruby: arr.tally
来源：http://dali.hywenlv.cn/Article/details/gt2prjvfrlg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.fzhhl.top/Article/details/gt2rdmjxufo.html

[D21] 判断是否包含某元素
来源：http://dali.9152youxi.cn/Article/details/gt2xawezcli.html

Py:   x in arr
来源：http://dali.shuidangran.top/Article/details/gt2huezpqev.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jlsjyb.cn/Article/details/gt2ansgszin.html

JS:   arr.includes(x)
来源：http://dali.ppjwa.cn/Article/details/gt2hugfdfga.html

TS:   arr.includes(x)
来源：http://dali.gotoacloud.top/Article/details/gt2kqdalksi.html

Java: list.contains(x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2wcudjfox.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2trbvqgqa.html

Ruby: arr.include?(x)
来源：http://dali.daria6918.cn/Article/details/gt2afmdmdcn.html

C#:   list.Contains(x)
来源：http://dali.zycfv.cn/Article/details/gt2fhfqsrsc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.snrcjt.cn/Article/details/gt2tkzgkpzp.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jzxttfoh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yangfankeji.com/Article/details/gt2jqedfilq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.aizwys.cn/Article/details/gt2bcoirtgo.html

TS:   [...arr];
来源：http://dali.ppjwa.cn/Article/details/gt2qxpobdrz.html

Java: new ArrayList<>(list);
来源：http://dali.shangyingyoupin.top/Article/details/gt2oktmtfjq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.c1oappe.top/Article/details/gt2cowwvkfb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.dashuyun.cn/Article/details/gt2dvtylzxa.html

C#:   new List<int>(list);
来源：http://dali.cucudq.cn/Article/details/gt2mjaqcwsh.html

[D23] reduce 累积计算
来源：http://dali.ivvv.top/Article/details/gt2xmvznbpx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jyoumei.cn/Article/details/gt2etwyeumv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.chenlongwang.top/Article/details/gt2plcjjmuk.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sxryk.cn/Article/details/gt2faunpvjv.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aizwys.cn/Article/details/gt2kgtvgrau.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.fengsongda.top/Article/details/gt2paylyrdy.html

Go:   // 手写循环
来源：http://dali.yanxiufei.cn/Article/details/gt2joqmflsb.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.bjfxy.top/Article/details/gt2haphlffv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyeufkur.html

[D24] 字典 / Map 基本操作
来源：http://dali.shuidangran.top/Article/details/gt2khljkwqx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.0kj1m.cn/Article/details/gt2rkzhgaba.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shangyingyoupin.top/Article/details/gt2yohbfmtq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.guannengcc.top/Article/details/gt2welgqxkb.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sweek.top/Article/details/gt2vkawsdak.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zdqjudy.top/Article/details/gt2midywxdy.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.meibo888.top/Article/details/gt2kcanseul.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sysykeji.top/Article/details/gt2zbgshqoi.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.havefunace.top/Article/details/gt2tmewwqyt.html

[D25] Set 集合去重与交并差
来源：http://dali.9152youxi.cn/Article/details/gt2epsowyzk.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xuetiantiany.cn/Article/details/gt2eeyvggww.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.iojbl.cn/Article/details/gt2kjnoahwv.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.smart0.xyz/Article/details/gt2xdrhjrcf.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.guowangkeji.top/Article/details/gt2qeqqvulg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.bjfxy.top/Article/details/gt2yxbvyfdc.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.haohaochexian.top/Article/details/gt2inmktlcm.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yj202588.top/Article/details/gt2vrxvwghd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhixingplan.top/Article/details/gt2kcqvpxfj.html

[D26] 数组转字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2rsezaxzz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xuetiantiany.cn/Article/details/gt2ljfraztd.html

PHP:  implode(", ", $arr);
来源：http://dali.jianghu66.top/Article/details/gt2ydiwytbt.html

JS:   arr.join(", ")
来源：http://dali.yj20258888.top/Article/details/gt2mtvktewp.html

TS:   arr.join(", ")
来源：http://dali.kuanghao11.cn/Article/details/gt2pdlicdek.html

Java: String.join(", ", list)
来源：http://dali.jlsjyb.cn/Article/details/gt2wlclmzve.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shzxlz.cn/Article/details/gt2lozfnhlk.html

Ruby: arr.join(", ")
来源：http://dali.cashguo.top/Article/details/gt2uyltqeax.html

C#:   string.Join(", ", list)
来源：http://dali.dashuyun.cn/Article/details/gt2bsagywvd.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2fsxuijzp.html

E. 字符串处理
来源：http://dali.dashuyun.cn/Article/details/gt2nddgpclt.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2ycosznsx.html

[E01] 拼接字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hckoqbfx.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.0kj1m.cn/Article/details/gt2jcpmexnw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.birdmap.top/Article/details/gt2nuljnbom.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.haohaochexian.top/Article/details/gt2gfncowek.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shzxlz.cn/Article/details/gt2mskmpzcg.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.9152youxi.cn/Article/details/gt2jxoucbug.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yonumen.top/Article/details/gt2pezukgdi.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhengqikj.top/Article/details/gt2zsmjunzm.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.316326.xyz/Article/details/gt2uptochqf.html

[E02] 重复字符串
来源：http://dali.yuanzhike.top/Article/details/gt2ewnlbgxp.html

Py:   "ab" * 3
来源：http://dali.gzhubu.top/Article/details/gt2gxstepzf.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhiwuduotai.top/Article/details/gt2qmaceonj.html

JS:   "ab".repeat(3)
来源：http://dali.dashuyun.cn/Article/details/gt2bkwndgsq.html

TS:   "ab".repeat(3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ohlgvqkd.html

Java: "ab".repeat(3)
来源：http://dali.fzhhl.top/Article/details/gt2cmneojbz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yvedp.cn/Article/details/gt2gjbmfxnu.html

Ruby: "ab" * 3
来源：http://dali.yj20258888.top/Article/details/gt2fjuwhepw.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jldenqfu.html

[E03] 截取子串
来源：http://dali.tian-w.cn/Article/details/gt2fhcxelti.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hfpthk.cn/Article/details/gt2saipbkhj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.redwolf501.top/Article/details/gt2zhvgtrrk.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hongshengwenyu.top/Article/details/gt2wmfobddl.html

TS:   s.slice(1, 4)
来源：http://dali.yuanzhike.top/Article/details/gt2nyihjjyj.html

Java: s.substring(1, 4)
来源：http://dali.jlsjyb.cn/Article/details/gt2gdufqxbq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gzhubu.top/Article/details/gt2easzfawb.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.guannengcc.top/Article/details/gt2jeydftol.html

C#:   s.Substring(1, 3)
来源：http://dali.xziqi.cn/Article/details/gt2ypkvahja.html

[E04] 查找子串位置
来源：http://dali.iojbl.cn/Article/details/gt2evpfiyiu.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jlsjyb.cn/Article/details/gt2gsfegwhh.html

PHP:  strpos($s, "x");
来源：http://dali.pengpengdd.cyou/Article/details/gt2fakevaxq.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sweek.top/Article/details/gt2nfkuanxg.html

TS:   s.indexOf("x")
来源：http://dali.kuanghao11.cn/Article/details/gt2pogxnmjh.html

Java: s.indexOf("x")
来源：http://dali.pycfn.com/Article/details/gt2mlpofujj.html

Go:   strings.Index(s, "x")
来源：http://dali.yj20258.top/Article/details/gt2uiqtigmy.html

Ruby: s.index("x")
来源：http://dali.gzhubu.top/Article/details/gt2zdypbqld.html

C#:   s.IndexOf("x")
来源：http://dali.gzhubu.top/Article/details/gt2ynotzcoa.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hywenlv.cn/Article/details/gt2tqnvnxrd.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.daria6918.cn/Article/details/gt2gntodcem.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.meibo888.top/Article/details/gt2yogxzlse.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nwbrower.top/Article/details/gt2jdtztgrx.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2euosrqkb.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tanke756.top/Article/details/gt2wtwluhmb.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zycfv.cn/Article/details/gt2iqpxqyip.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uiksedmc.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.fengsongda.top/Article/details/gt2pjfkunur.html

[E06] 替换子串
来源：http://dali.guowangkeji.top/Article/details/gt2tmpnewqo.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.sysykeji.top/Article/details/gt2ktltdngk.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.dashuyun.cn/Article/details/gt2jccaefwb.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj202588.top/Article/details/gt2aczborxj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gt2ymuomhmd.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gt2fymickmr.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.quarkkingdee.top/Article/details/gt2vejkpzlv.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sysykeji.top/Article/details/gt2lopvlfnj.html

C#:   s.Replace("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gt2tvopckvh.html

[E07] 按分隔符拆分
来源：http://dali.hnxiangtu.top/Article/details/gt2jwmcmolp.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.kuanghao11.cn/Article/details/gt2lxauwnxa.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gt2entvpjhb.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhongyouzk.top/Article/details/gt2zwrvwhlj.html

TS:   s.split(",")
来源：http://dali.jiagoushi.top/Article/details/gt2plbucwld.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.gotoacloud.top/Article/details/gt2lkyxexum.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2phytvulp.html

Ruby: s.split(",");  s.split
来源：http://dali.jqgufenzy.top/Article/details/gt2edtjtoql.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhengqikj.top/Article/details/gt2bwetuvfn.html

[E08] 数组按分隔符合并
来源：http://dali.yj20258.top/Article/details/gt2krxzlbjo.html

Py:   ",".join(items)
来源：http://dali.jqgfzy.top/Article/details/gt2cqpasfio.html

PHP:  implode(",", $items);
来源：http://dali.ppjwa.cn/Article/details/gt2opsrqavd.html

JS:   items.join(",")
来源：http://dali.birdmap.top/Article/details/gt2xfracqnz.html

TS:   items.join(",")
来源：http://dali.jiagoushi.top/Article/details/gt2hvafbmkg.html

Java: String.join(",", items)
来源：http://dali.hysaishi.cn/Article/details/gt2jcgbrtoo.html

Go:   strings.Join(items, ",")
来源：http://dali.meibo888.top/Article/details/gt2fnshqphn.html

Ruby: items.join(",")
来源：http://dali.wangdashe.top/Article/details/gt2fzuvvkxk.html

C#:   string.Join(",", items)
来源：http://dali.andypj.xyz/Article/details/gt2ldpropbg.html

[E09] 去除所有空白字符
来源：http://dali.jinqigufen.top/Article/details/gt2bhiqqudm.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.smart0.xyz/Article/details/gt2jjefvqwq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.tianlin.xyz/Article/details/gt2oaozxghs.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.c1oappe.top/Article/details/gt2hdecstqw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.haohaochexian.top/Article/details/gt2sdklvwwv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cucudq.cn/Article/details/gt2cyoezkpg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xuetiantiany.cn/Article/details/gt2iqlhuiqs.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.9152youxi.cn/Article/details/gt2dtyrkmzs.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xinyue.icu/Article/details/gt2airbvypq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.vqdsnc.cn/Article/details/gt2fmloqnyn.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gt2mycoqbzd.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.nwbrower.top/Article/details/gt2minhgkii.html

JS:   "7".padStart(3, "0")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ggydlhca.html

TS:   "7".padStart(3, "0")
来源：http://dali.snrcjt.cn/Article/details/gt2czteprsc.html

Java: String.format("%03d", 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jfbbcnws.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cheryme.top/Article/details/gt2bytsgvuu.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gotoacloud.top/Article/details/gt2egdundtf.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.aibaodan.cn/Article/details/gt2jjbdatra.html

[E11] 反转字符串
来源：http://dali.daxiang520.top/Article/details/gt2jakoddlx.html

Py:   s[::-1]
来源：http://dali.guowangkeji.top/Article/details/gt2mdbfyjhe.html

PHP:  strrev($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wjwvndjp.html

JS:   [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gt2iisosrrv.html

TS:   [...s].reverse().join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cofisdqt.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhengqikj.top/Article/details/gt2wtmxsvtl.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yongpay.top/Article/details/gt2tcohopnp.html

Ruby: s.reverse
来源：http://dali.aibaodan.cn/Article/details/gt2lmlfaivt.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ppjwa.cn/Article/details/gt2kuchucsj.html

[E12] 统计某字符出现次数
来源：http://dali.xinyue.icu/Article/details/gt2tiligwip.html

Py:   s.count("a")
来源：http://dali.havefunace.top/Article/details/gt2gyguhbud.html

PHP:  substr_count($s, "a");
来源：http://dali.jqgufenzy.top/Article/details/gt2eqijsamy.html

JS:   s.split("a").length - 1
来源：http://dali.dashuyun.cn/Article/details/gt2wbipcwck.html

TS:   s.split("a").length - 1
来源：http://dali.nanxuanxn.top/Article/details/gt2owkudxwm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.c1oappe.top/Article/details/gt2rpxsdftc.html


<!-- 参考信息 -->