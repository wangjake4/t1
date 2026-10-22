代发 wailian999

Ruby: a + b;  a.concat(b)
来源：http://dali.smart0.xyz/Article/details/gt2yqujqwcb.html

C#:   a.Concat(b).ToList()
来源：http://dali.meibo888.top/Article/details/gt2bonvfslp.html

[D09] 排序（升序）
来源：http://dali.gzhubu.top/Article/details/gt2yzfsjlwz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kgortpag.html

PHP:  sort($arr);
来源：http://dali.xziqi.cn/Article/details/gt2frgfuatn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cqqwz.cn/Article/details/gt2efahbiyc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ipliszit.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.redwolf501.top/Article/details/gt2jwzwtdby.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xinyue.icu/Article/details/gt2xwvjlpdi.html

Ruby: arr.sort
来源：http://dali.wangdashe.top/Article/details/gt2qifpxkml.html

C#:   list.Sort();
来源：http://dali.hammf.cn/Article/details/gt2ievxftpe.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.gogol.net.cn/Article/details/gt2olteapjs.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.fengsongda.top/Article/details/gt2axqlyobl.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.mhx1999.top/Article/details/gt2adzceldu.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yuxming.cn/Article/details/gt2qmzahxec.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sysykeji.top/Article/details/gt2jumyifzd.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.snrcjt.cn/Article/details/gt2bkfleztp.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xuanzx.com/Article/details/gt2bttrjhwj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.snrcjt.cn/Article/details/gt2clelemyf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.meibo888.top/Article/details/gt2hbbyrggq.html

[D11] 反转数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vtvafqzb.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jinqigfzy.top/Article/details/gt2bdardpbc.html

PHP:  array_reverse($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2eecnbvks.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.sysykeji.top/Article/details/gt2dizjotmu.html

TS:   [...arr].reverse();
来源：http://dali.fzhhl.top/Article/details/gt2cshzyysj.html

Java: Collections.reverse(list);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2msbmjyoi.html

Go:   slices.Reverse(arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2oqqmtjnl.html

Ruby: arr.reverse
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ywecachd.html

C#:   list.Reverse();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kbfksodl.html

[D12] 查找元素下标
来源：http://dali.9152youxi.cn/Article/details/gt2krjdpnuv.html

Py:   arr.index(x);  x in arr
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wcgcuvki.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ejxyjjml.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.daria6918.cn/Article/details/gt2jrwmvqno.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yecjfcwo.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sysykeji.top/Article/details/gt2idxpuwqu.html

Go:   slices.Index(arr, x)
来源：http://dali.daxiang520.top/Article/details/gt2zfaagqsj.html

Ruby: arr.index(x)
来源：http://dali.cucudq.cn/Article/details/gt2dsdprscd.html

C#:   list.IndexOf(x);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ghhrjbuz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jiagoushi.top/Article/details/gt2nipicwnz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cdnleiting.top/Article/details/gt2ewjungmf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.mhx1999.top/Article/details/gt2xxxqevfh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lnmnmpvy.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hnqzz.top/Article/details/gt2xxqqmhow.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jqgfzy.top/Article/details/gt2rungosbi.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.fengsongda.top/Article/details/gt2uztvbwep.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.chenjidiqi.icu/Article/details/gt2pzxhceyz.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ybcxt.top/Article/details/gt2lhtspwbx.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yj202588.top/Article/details/gt2cgjdufeg.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.bjfxy.top/Article/details/gt2ehbtowwd.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xylfe.cn/Article/details/gt2vznpyodb.html

JS:   arr.map(x => x * 2)
来源：http://dali.dashuyun.cn/Article/details/gt2zyzkfmee.html

TS:   arr.map(x => x * 2)
来源：http://dali.aibaodan.cn/Article/details/gt2fppcdspa.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hnxiangtu.top/Article/details/gt2mtaqutex.html

Go:   // 手写循环
来源：http://dali.aibaodan.cn/Article/details/gt2wibbnuud.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ydzc1.top/Article/details/gt2ikeurkol.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.gogol.net.cn/Article/details/gt2ruwxnynv.html

[D15] 去重
来源：http://dali.hnqzz.top/Article/details/gt2rqbxuqso.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jqgfzy.top/Article/details/gt2wgvxilpk.html

PHP:  array_unique($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2wdvioyoo.html

JS:   [...new Set(arr)]
来源：http://dali.jyoumei.cn/Article/details/gt2cguwsonb.html

TS:   [...new Set(arr)]
来源：http://dali.sysykeji.top/Article/details/gt2ddxqomxr.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jqgfzy.top/Article/details/gt2cmvcrdic.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jyoumei.cn/Article/details/gt2lrcovbqr.html

Ruby: arr.uniq
来源：http://dali.shuidangran.top/Article/details/gt2eckfuohz.html

C#:   list.Distinct().ToList()
来源：http://dali.hysaishi.cn/Article/details/gt2ddzdsxeo.html

[D16] 求和与平均值
来源：http://dali.hywenlv.cn/Article/details/gt2scnbcwrl.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fybcvqfv.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2alswvfey.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gt2hzgznwpc.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhengqikj.top/Article/details/gt2klbnbzjk.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.sufxvd.cn/Article/details/gt2kgcpkdye.html

Go:   // 手写循环累加
来源：http://dali.cdnleiting.top/Article/details/gt2tlliiwkk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.redwolf501.top/Article/details/gt2dhduonxz.html

C#:   list.Sum();  list.Average()
来源：http://dali.jqgfzy.top/Article/details/gt2yunseoes.html

[D17] 最大值与最小值
来源：http://dali.tian-w.cn/Article/details/gt2bispgqvm.html

Py:   max(arr);  min(arr)
来源：http://dali.hnqzz.top/Article/details/gt2xphtqwrp.html

PHP:  max($arr);  min($arr);
来源：http://dali.yuanzhike.top/Article/details/gt2tbvdkrht.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xziqi.cn/Article/details/gt2kwijuobc.html

TS:   Math.max(...arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ztvrhybd.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cqqwz.cn/Article/details/gt2jbumnoua.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yj202588.top/Article/details/gt2cvfvnqvj.html

Ruby: arr.max;  arr.min
来源：http://dali.guowangkeji.top/Article/details/gt2lznkmmzj.html

C#:   list.Max();  list.Min()
来源：http://dali.zhongyouzk.top/Article/details/gt2okafzcyz.html

[D18] 扁平化嵌套数组
来源：http://dali.xylfe.cn/Article/details/gt2vvheureu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.aibaodan.cn/Article/details/gt2unnujkfq.html

PHP:  array_merge(...$nested);
来源：http://dali.mhx1999.top/Article/details/gt2ktfhsxtj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hywenlv.cn/Article/details/gt2krqhinkr.html

TS:   nested.flat();
来源：http://dali.nanxinkj.top/Article/details/gt2ujurxmtm.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jzgejbvp.html

Go:   // 手写双层循环
来源：http://dali.yangfankeji.com/Article/details/gt2gfitapdt.html

Ruby: nested.flatten
来源：http://dali.ehwqpu.com/Article/details/gt2pvljclop.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gt2rhdqphyx.html

[D19] 按字段分组
来源：http://dali.yj20258888.top/Article/details/gt2italaice.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ydzc1.top/Article/details/gt2xnbwwipd.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.kuanghao11.cn/Article/details/gt2bvnqiwxg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.chenlongwang.top/Article/details/gt2srhrtknd.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.bjfxy.top/Article/details/gt2lhclrhzo.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.pengpengdd.cyou/Article/details/gt2qlhrotto.html

Go:   // 手写 map[string][]T
来源：http://dali.shzxlz.cn/Article/details/gt2isdkceau.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.feifeiyinyue.top/Article/details/gt2jobfnvdk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.daria6918.cn/Article/details/gt2npqzfjus.html

[D20] 统计每个元素出现次数
来源：http://dali.nwbrower.top/Article/details/gt2whvikbsb.html

Py:   Counter(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2rwzkfamu.html

PHP:  array_count_values($arr);
来源：http://dali.0kj1m.cn/Article/details/gt2gqqzmbfu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinqigfzy.top/Article/details/gt2hqgvqkkf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.dashuyun.cn/Article/details/gt2mraymhmg.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yvedp.cn/Article/details/gt2hvlkmdbv.html

Go:   // 手写 map[T]int
来源：http://dali.snrcjt.cn/Article/details/gt2tbmimdhq.html

Ruby: arr.tally
来源：http://dali.hongshengwenyu.top/Article/details/gt2wyhpytyd.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhoulong.xyz/Article/details/gt2hqgdfvek.html

[D21] 判断是否包含某元素
来源：http://dali.xuetiantiany.cn/Article/details/gt2udpzwvjp.html

Py:   x in arr
来源：http://dali.daxiang520.top/Article/details/gt2mjsoqtrb.html

PHP:  in_array($x, $arr, true);
来源：http://dali.dianchejie.cn/Article/details/gt2vnhpnori.html

JS:   arr.includes(x)
来源：http://dali.shzxlz.cn/Article/details/gt2ykkwctlp.html

TS:   arr.includes(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2kqbieaap.html

Java: list.contains(x)
来源：http://dali.smart0.xyz/Article/details/gt2kxdvmhpc.html

Go:   slices.Contains(arr, x)
来源：http://dali.zycfv.cn/Article/details/gt2aztlhnyw.html

Ruby: arr.include?(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2hvjhdqqv.html

C#:   list.Contains(x)
来源：http://dali.jyoumei.cn/Article/details/gt2ovzcmshw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xuetiantiany.cn/Article/details/gt2zxiorlry.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2zsltidri.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jqgfzy.top/Article/details/gt2eguslllb.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.c1oappe.top/Article/details/gt2pdyauxbj.html

TS:   [...arr];
来源：http://dali.pengpengdd.cyou/Article/details/gt2yibtwlgm.html

Java: new ArrayList<>(list);
来源：http://dali.havefunace.top/Article/details/gt2ajuwxeoe.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cheryme.top/Article/details/gt2penxkrrd.html

Ruby: arr.dup;  arr.clone
来源：http://dali.guannengcc.top/Article/details/gt2qoqlmhul.html

C#:   new List<int>(list);
来源：http://dali.gogol.net.cn/Article/details/gt2jhncqtfv.html

[D23] reduce 累积计算
来源：http://dali.wangdashe.top/Article/details/gt2baffwury.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.gogol.net.cn/Article/details/gt2hyspnihz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yj20258.top/Article/details/gt2cqkzekxp.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yanxiufei.cn/Article/details/gt2zdeojvbb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.redwolf501.top/Article/details/gt2bfgtsady.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.snrcjt.cn/Article/details/gt2bcbegfph.html

Go:   // 手写循环
来源：http://dali.sweek.top/Article/details/gt2gnohqjxb.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xylfe.cn/Article/details/gt2wjcdtnrg.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gaohongyu789.top/Article/details/gt2mjsotgcv.html

[D24] 字典 / Map 基本操作
来源：http://dali.ydzc1.top/Article/details/gt2omdtjyuk.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhoulong.xyz/Article/details/gt2neeyvrtc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.tian-w.cn/Article/details/gt2ocutysdu.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.316326.xyz/Article/details/gt2mgbsyvjf.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yj202588.top/Article/details/gt2mtfhfhix.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hnxiangtu.top/Article/details/gt2jjqybtht.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ydzc1.top/Article/details/gt2bpkxgccc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ivvv.top/Article/details/gt2lwaqlmdv.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinqigufen.top/Article/details/gt2euqniwzj.html

[D25] Set 集合去重与交并差
来源：http://dali.dianchejie.cn/Article/details/gt2ccvfzuwr.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.fengsongda.top/Article/details/gt2tgtwviwd.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.daxiang520.top/Article/details/gt2rcrmzuuv.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.tanke756.top/Article/details/gt2gvlcmaot.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cheryme.top/Article/details/gt2sirogdsk.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.chenzaomai.com/Article/details/gt2ncpehjft.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.meibo888.top/Article/details/gt2kjhyqvch.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.aizwys.cn/Article/details/gt2hzpamnpi.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rbwseffk.html

[D26] 数组转字符串
来源：http://dali.chenlongwang.top/Article/details/gt2ylhdjcxk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yj20258888.top/Article/details/gt2civyrxqw.html

PHP:  implode(", ", $arr);
来源：http://dali.redwolf501.top/Article/details/gt2lqcluxtc.html

JS:   arr.join(", ")
来源：http://dali.iojbl.cn/Article/details/gt2dyulxjsi.html

TS:   arr.join(", ")
来源：http://dali.iojbl.cn/Article/details/gt2aiqedsaj.html

Java: String.join(", ", list)
来源：http://dali.andypj.xyz/Article/details/gt2ufwnyeuz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.sufxvd.cn/Article/details/gt2kivdqdog.html

Ruby: arr.join(", ")
来源：http://dali.gogol.net.cn/Article/details/gt2qukkwviy.html

C#:   string.Join(", ", list)
来源：http://dali.feifeiyinyue.top/Article/details/gt2qkwittuh.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2sfubvfwg.html

E. 字符串处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2knzivqqu.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2kwljjecd.html

[E01] 拼接字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2ovvhapzz.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kjgqcuwx.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.wangshuangyany.cn/Article/details/gt2gkmredqa.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ppjwa.cn/Article/details/gt2mqwjvnkb.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.bjfxy.top/Article/details/gt2gkkquehz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yuanzhike.top/Article/details/gt2wqrrajjw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yueranfly.top/Article/details/gt2emouehuj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ybcxt.top/Article/details/gt2gdknrfvn.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gt2pmfuzblc.html

[E02] 重复字符串
来源：http://dali.316326.xyz/Article/details/gt2bkxddrgv.html

Py:   "ab" * 3
来源：http://dali.yongpay.top/Article/details/gt2bvqrvavd.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cabryxsm.html

JS:   "ab".repeat(3)
来源：http://dali.yonumen.top/Article/details/gt2szjpcwry.html

TS:   "ab".repeat(3)
来源：http://dali.fzhhl.top/Article/details/gt2dcqsgbhz.html

Java: "ab".repeat(3)
来源：http://dali.chenzaomai.com/Article/details/gt2akbhjqqe.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yj20258.top/Article/details/gt2kzylejxc.html

Ruby: "ab" * 3
来源：http://dali.0kj1m.cn/Article/details/gt2eqoehkay.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.birdmap.top/Article/details/gt2nobfvhjm.html

[E03] 截取子串
来源：http://dali.zhongyouzk.top/Article/details/gt2eloketqu.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jiagoushi.top/Article/details/gt2dbnwnfja.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iassmntp.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhoulong.xyz/Article/details/gt2gcfkpwov.html

TS:   s.slice(1, 4)
来源：http://dali.gzhubu.top/Article/details/gt2vpgtmwji.html

Java: s.substring(1, 4)
来源：http://dali.quarkkingdee.top/Article/details/gt2tuwawsme.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jyoumei.cn/Article/details/gt2kzjqddvu.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yj20258.top/Article/details/gt2mpcxfdgr.html

C#:   s.Substring(1, 3)
来源：http://dali.hywenlv.cn/Article/details/gt2amxkurnr.html

[E04] 查找子串位置
来源：http://dali.316326.xyz/Article/details/gt2eoghstvx.html

Py:   s.find("x");  s.index("x")
来源：http://dali.haohaochexian.top/Article/details/gt2dafcqnhy.html

PHP:  strpos($s, "x");
来源：http://dali.ybcxt.top/Article/details/gt2kcwwupuv.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.0kj1m.cn/Article/details/gt2qiqqrwmg.html

TS:   s.indexOf("x")
来源：http://dali.hammf.cn/Article/details/gt2vgtvtibp.html

Java: s.indexOf("x")
来源：http://dali.redwolf501.top/Article/details/gt2zyejzgfa.html

Go:   strings.Index(s, "x")
来源：http://dali.chenlongwang.top/Article/details/gt2uojvhnwp.html

Ruby: s.index("x")
来源：http://dali.zhoulong.xyz/Article/details/gt2aohbyzlu.html

C#:   s.IndexOf("x")
来源：http://dali.jianghu66.top/Article/details/gt2zslxqnkx.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ydzc1.top/Article/details/gt2nztbhspo.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yueranfly.top/Article/details/gt2aoiafxtr.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cheryme.top/Article/details/gt2fzzoircj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.havefunace.top/Article/details/gt2oyvaautr.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.svipenyu.cn/Article/details/gt2ycqvbgtg.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fengsongda.top/Article/details/gt2ralzqhtt.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xojikbwr.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xuetiantiany.cn/Article/details/gt2qvbvpqsh.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jyoumei.cn/Article/details/gt2obustfii.html

[E06] 替换子串
来源：http://dali.cheryme.top/Article/details/gt2asbflemc.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.nanxinkj.top/Article/details/gt2blilzrxs.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hnqzz.top/Article/details/gt2hkkgrhgr.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gt2ugfcjzkg.html

TS:   s.replaceAll("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gt2ealivpyo.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj20258.top/Article/details/gt2eqiqfnub.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ehwqpu.com/Article/details/gt2zlwsefds.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gt2aeibrwfc.html

C#:   s.Replace("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gt2veoizcef.html

[E07] 按分隔符拆分
来源：http://dali.yvedp.cn/Article/details/gt2qvjunufn.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.tanke756.top/Article/details/gt2cethuisy.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.fengsongda.top/Article/details/gt2pqmepswz.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ehwqpu.com/Article/details/gt2tratkjpb.html

TS:   s.split(",")
来源：http://dali.ydzc1.top/Article/details/gt2fykcdrzq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.aizwys.cn/Article/details/gt2bykdkwzw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2dsybmsxl.html

Ruby: s.split(",");  s.split
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lcqmqmuh.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sufxvd.cn/Article/details/gt2lmszzuwo.html

[E08] 数组按分隔符合并
来源：http://dali.aizwys.cn/Article/details/gt2wzlcgggy.html

Py:   ",".join(items)
来源：http://dali.jqgfzy.top/Article/details/gt2hohxqocg.html

PHP:  implode(",", $items);
来源：http://dali.hongshengwenyu.top/Article/details/gt2lwydmpxs.html

JS:   items.join(",")
来源：http://dali.yongpay.top/Article/details/gt2lvribfdv.html

TS:   items.join(",")
来源：http://dali.wangshuangyany.cn/Article/details/gt2xfvjerxk.html

Java: String.join(",", items)
来源：http://dali.vqdsnc.cn/Article/details/gt2pxqtqkzt.html

Go:   strings.Join(items, ",")
来源：http://dali.jlsjyb.cn/Article/details/gt2jpwxswzd.html

Ruby: items.join(",")
来源：http://dali.redwolf501.top/Article/details/gt2jqpshfdb.html

C#:   string.Join(",", items)
来源：http://dali.jianghu66.top/Article/details/gt2ekbutjpx.html

[E09] 去除所有空白字符
来源：http://dali.yuxming.cn/Article/details/gt2wiswjarc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.kuanghao11.cn/Article/details/gt2phwviicq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.aibaodan.cn/Article/details/gt2aiaosefx.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2umgwpexw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shzxlz.cn/Article/details/gt2djeokpzk.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.andypj.xyz/Article/details/gt2ntujpyer.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.aibaodan.cn/Article/details/gt2aulwbioa.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.9152youxi.cn/Article/details/gt2glgmnryy.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.mhx1999.top/Article/details/gt2jvuxipye.html

[E10] 左侧补零 / 定长填充
来源：http://dali.nanxinkj.top/Article/details/gt2bzuwjglt.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hywenlv.cn/Article/details/gt2hpwszsee.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.meibo888.top/Article/details/gt2jlluqspq.html

JS:   "7".padStart(3, "0")
来源：http://dali.xziqi.cn/Article/details/gt2qewiojgy.html

TS:   "7".padStart(3, "0")
来源：http://dali.shuidangran.top/Article/details/gt2rfrdpwnz.html

Java: String.format("%03d", 7)
来源：http://dali.yanxiufei.cn/Article/details/gt2ztaxyoqs.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cheryme.top/Article/details/gt2vhabnser.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.nanxuanxn.top/Article/details/gt2lqmriplq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.tian-w.cn/Article/details/gt2bhwtuuvm.html

[E11] 反转字符串
来源：http://dali.wangshuangyany.cn/Article/details/gt2hhzvlfwi.html

Py:   s[::-1]
来源：http://dali.haohaochexian.top/Article/details/gt2etzvzcea.html

PHP:  strrev($s);
来源：http://dali.hnxiangtu.top/Article/details/gt2jqajivqj.html

JS:   [...s].reverse().join("")
来源：http://dali.yangfankeji.com/Article/details/gt2cxrofemb.html

TS:   [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qibymaab.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.sysykeji.top/Article/details/gt2ffcnwfro.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cashguo.top/Article/details/gt2ydosdbxr.html

Ruby: s.reverse
来源：http://dali.aizwys.cn/Article/details/gt2gtglfaik.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.sxryk.cn/Article/details/gt2tjqrltyo.html

[E12] 统计某字符出现次数
来源：http://dali.cqqwz.cn/Article/details/gt2cscuhkzt.html

Py:   s.count("a")
来源：http://dali.pengpengdd.cyou/Article/details/gt2rmwysxuh.html

PHP:  substr_count($s, "a");
来源：http://dali.ivvv.top/Article/details/gt2crnbohua.html

JS:   s.split("a").length - 1
来源：http://dali.cheryme.top/Article/details/gt2vgayftpc.html

TS:   s.split("a").length - 1
来源：http://dali.fzhhl.top/Article/details/gt2tpzrzaex.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hywenlv.cn/Article/details/gt2wevpherv.html

Go:   strings.Count(s, "a")
来源：http://dali.gogol.net.cn/Article/details/gt2nbwwjcig.html

Ruby: s.count("a")
来源：http://dali.zycfv.cn/Article/details/gt2roxfdbyd.html

C#:   s.Count(c => c == 'a')
来源：http://dali.vqdsnc.cn/Article/details/gt2zlpevpyw.html

[E13] 逐字符遍历
来源：http://dali.tianlin.xyz/Article/details/gt2nkzwpejo.html

Py:   for ch in s: print(ch)
来源：http://dali.shangyingyoupin.top/Article/details/gt2poozxwro.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ehwqpu.com/Article/details/gt2ngjqwpau.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgfzy.top/Article/details/gt2duwbkcdz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nwbrower.top/Article/details/gt2xnupfoeo.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2khcjjabl.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zdqjudy.top/Article/details/gt2tvlqdroj.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yj20258888.top/Article/details/gt2nhfxhzbn.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lwwfdypc.html

[E14] URL 编码与 Base64
来源：http://dali.gaohongyu789.top/Article/details/gt2msucalgx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gt2ndbpcrff.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jqgfzy.top/Article/details/gt2wtetiwug.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.gzhubu.top/Article/details/gt2wgykbwxk.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.haohaochexian.top/Article/details/gt2novcvljp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.quarkkingdee.top/Article/details/gt2yqksjmmr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.fzhhl.top/Article/details/gt2opqzwojo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj20258888.top/Article/details/gt2evuqlurg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.0kj1m.cn/Article/details/gt2qlimeexa.html

[E15] HTML 转义 / 反转义
来源：http://dali.xuetiantiany.cn/Article/details/gt2wvcgaege.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jinqigufen.top/Article/details/gt2udetoopl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sweek.top/Article/details/gt2xdimquji.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yvedp.cn/Article/details/gt2ztzthzak.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.tanke756.top/Article/details/gt2uduueekx.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qvlzqwfq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhixingplan.top/Article/details/gt2qeondfwf.html


<!-- 参考信息 -->