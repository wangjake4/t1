代发 wailian999

C#:   list.Reverse();
来源：http://dali.cdnleiting.top/Article/details/gt2ztlulmkj.html

[D12] 查找元素下标
来源：http://dali.feifeiyinyue.top/Article/details/gt2grlnigmm.html

Py:   arr.index(x);  x in arr
来源：http://dali.xuetiantiany.cn/Article/details/gt2tthmohbn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.fengsongda.top/Article/details/gt2fdyqiukd.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.snrcjt.cn/Article/details/gt2llafkkpz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jqgufenzy.top/Article/details/gt2emgfjahc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ybcxt.top/Article/details/gt2ozpdcqkv.html

Go:   slices.Index(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gt2evlbmwfj.html

Ruby: arr.index(x)
来源：http://dali.hfpthk.cn/Article/details/gt2mowgitbe.html

C#:   list.IndexOf(x);
来源：http://dali.redwolf501.top/Article/details/gt2pjkozqei.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shuidangran.top/Article/details/gt2peuektib.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gcdfravw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.chenjidiqi.icu/Article/details/gt2eegjdatg.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yanxiufei.cn/Article/details/gt2fxpkmcdq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gotoacloud.top/Article/details/gt2ygbzpuec.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhoulong.xyz/Article/details/gt2bprkvyxg.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lyfmbqeo.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cheryme.top/Article/details/gt2wipjphyw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.birdmap.top/Article/details/gt2xjkngpfm.html

[D14] 映射转换（每个元素变形）
来源：http://dali.gaohongyu789.top/Article/details/gt2scytfoek.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.nwbrower.top/Article/details/gt2wffacvhm.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.mhx1999.top/Article/details/gt2tjfsofpv.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhongyouzk.top/Article/details/gt2cmrqxwqt.html

TS:   arr.map(x => x * 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ibsmkjqp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.0kj1m.cn/Article/details/gt2ybajfjxq.html

Go:   // 手写循环
来源：http://dali.ybcxt.top/Article/details/gt2azyrrvhd.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.guannengcc.top/Article/details/gt2tlwtexjx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.pycfn.com/Article/details/gt2sudljplp.html

[D15] 去重
来源：http://dali.c1oappe.top/Article/details/gt2vjnvxwbg.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yongpay.top/Article/details/gt2xrutxcoc.html

PHP:  array_unique($arr);
来源：http://dali.wangdashe.top/Article/details/gt2wqfqzvav.html

JS:   [...new Set(arr)]
来源：http://dali.jqgufenzy.top/Article/details/gt2mopzeyhe.html

TS:   [...new Set(arr)]
来源：http://dali.gaohongyu789.top/Article/details/gt2cwmtbsnr.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jlsjyb.cn/Article/details/gt2faphiejv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hongshengwenyu.top/Article/details/gt2dsqlwrjo.html

Ruby: arr.uniq
来源：http://dali.guowangkeji.top/Article/details/gt2xgsbuzfe.html

C#:   list.Distinct().ToList()
来源：http://dali.yvedp.cn/Article/details/gt2dzbknyyb.html

[D16] 求和与平均值
来源：http://dali.vqdsnc.cn/Article/details/gt2hclemdkn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yj20258888.top/Article/details/gt2hbmlkzry.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hfpthk.cn/Article/details/gt2svmaxdhu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.iojbl.cn/Article/details/gt2fzkkasml.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nwbrower.top/Article/details/gt2oenmaxzy.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yanxiufei.cn/Article/details/gt2oivwycuy.html

Go:   // 手写循环累加
来源：http://dali.hnxiangtu.top/Article/details/gt2kqdrguuf.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ivvv.top/Article/details/gt2wgfhknwj.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhixingplan.top/Article/details/gt2smifbsng.html

[D17] 最大值与最小值
来源：http://dali.shangyingyoupin.top/Article/details/gt2grbkwxkq.html

Py:   max(arr);  min(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hmqvfgvm.html

PHP:  max($arr);  min($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2jnsyywml.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yangfankeji.com/Article/details/gt2penxpyeh.html

TS:   Math.max(...arr);
来源：http://dali.daria6918.cn/Article/details/gt2fbbdadsx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.chenlongwang.top/Article/details/gt2knzasors.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2aarltraj.html

Ruby: arr.max;  arr.min
来源：http://dali.zycfv.cn/Article/details/gt2zpoordiz.html

C#:   list.Max();  list.Min()
来源：http://dali.yanxiufei.cn/Article/details/gt2sksriciv.html

[D18] 扁平化嵌套数组
来源：http://dali.yvedp.cn/Article/details/gt2invasamn.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.tanke756.top/Article/details/gt2cqujpjhf.html

PHP:  array_merge(...$nested);
来源：http://dali.daria6918.cn/Article/details/gt2mirralku.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cashguo.top/Article/details/gt2gmrbhdvc.html

TS:   nested.flat();
来源：http://dali.gogol.net.cn/Article/details/gt2duulnyyg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.pycfn.com/Article/details/gt2wxibsmiq.html

Go:   // 手写双层循环
来源：http://dali.tianlin.xyz/Article/details/gt2cyzjmkiw.html

Ruby: nested.flatten
来源：http://dali.ivvv.top/Article/details/gt2mnpnfdie.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zdqjudy.top/Article/details/gt2iodphprk.html

[D19] 按字段分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eqrnfcoc.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sweek.top/Article/details/gt2xbkpevgc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yj202588.top/Article/details/gt2lngfgogx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.tian-w.cn/Article/details/gt2jawsnrun.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yongpay.top/Article/details/gt2pvbxdxbg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hongshengwenyu.top/Article/details/gt2ixjdgmry.html

Go:   // 手写 map[string][]T
来源：http://dali.redwolf501.top/Article/details/gt2zweexmpi.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.haohaochexian.top/Article/details/gt2gzfggxjh.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zycfv.cn/Article/details/gt2ihcqihav.html

[D20] 统计每个元素出现次数
来源：http://dali.yj20258.top/Article/details/gt2yvcgewgv.html

Py:   Counter(arr)
来源：http://dali.yj20258888.top/Article/details/gt2wruxxqxb.html

PHP:  array_count_values($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2taghxtbr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhixingplan.top/Article/details/gt2dudyelco.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinqigufen.top/Article/details/gt2qnipagip.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.pengpengdd.cyou/Article/details/gt2wkeocoie.html

Go:   // 手写 map[T]int
来源：http://dali.cheryme.top/Article/details/gt2ltsysvqb.html

Ruby: arr.tally
来源：http://dali.nwbrower.top/Article/details/gt2uyykcdgr.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.aibaodan.cn/Article/details/gt2lsxhmmzl.html

[D21] 判断是否包含某元素
来源：http://dali.yj20258888.top/Article/details/gt2cvkmfmrn.html

Py:   x in arr
来源：http://dali.daria6918.cn/Article/details/gt2fnsknxrq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yj20258888.top/Article/details/gt2lxozdftf.html

JS:   arr.includes(x)
来源：http://dali.cheryme.top/Article/details/gt2ygaedmmc.html

TS:   arr.includes(x)
来源：http://dali.ydzc1.top/Article/details/gt2lldthkmj.html

Java: list.contains(x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2xcteuiht.html

Go:   slices.Contains(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2llhbbvom.html

Ruby: arr.include?(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2kdhohaca.html

C#:   list.Contains(x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2adfjtvgs.html

[D22] 复制数组（避免共享引用）
来源：http://dali.wangdashe.top/Article/details/gt2uhqzughu.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2lrdjhorg.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jinqigufen.top/Article/details/gt2ozhizzcc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2nkdkggul.html

TS:   [...arr];
来源：http://dali.andypj.xyz/Article/details/gt2gsgiqxhe.html

Java: new ArrayList<>(list);
来源：http://dali.sysykeji.top/Article/details/gt2ptvjkwgq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.vqdsnc.cn/Article/details/gt2cdmrpnjn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cheryme.top/Article/details/gt2kacvstxq.html

C#:   new List<int>(list);
来源：http://dali.vqdsnc.cn/Article/details/gt2qluuccar.html

[D23] reduce 累积计算
来源：http://dali.zhengqikj.top/Article/details/gt2vyjuvplf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.snrcjt.cn/Article/details/gt2tvhrzlkj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.nwbrower.top/Article/details/gt2vphzsbvu.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhoulong.xyz/Article/details/gt2lxqsprwh.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dashuyun.cn/Article/details/gt2dvfpahci.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yrmwgdbe.html

Go:   // 手写循环
来源：http://dali.zhiwuduotai.top/Article/details/gt2dvucfkxp.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.316326.xyz/Article/details/gt2tmxolpgv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cdnleiting.top/Article/details/gt2ditvjqke.html

[D24] 字典 / Map 基本操作
来源：http://dali.nanxinkj.top/Article/details/gt2pnuerjpu.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.gotoacloud.top/Article/details/gt2bcawxcih.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhoulong.xyz/Article/details/gt2zlylmwep.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yanxiufei.cn/Article/details/gt2mzlzrpat.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xziqi.cn/Article/details/gt2phfcjgig.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nafwmkwk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.guannengcc.top/Article/details/gt2xpjbflid.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ddurdeno.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.fengsongda.top/Article/details/gt2cikadqhd.html

[D25] Set 集合去重与交并差
来源：http://dali.haohaochexian.top/Article/details/gt2stuzblgm.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hnqzz.top/Article/details/gt2raazvxkj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yongpay.top/Article/details/gt2omyscipl.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.meibo888.top/Article/details/gt2uegyczty.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.wangshuangyany.cn/Article/details/gt2bmdxcdtz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jqwnavtl.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.iojbl.cn/Article/details/gt2xuxixjvl.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pucdvqrx.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hfpthk.cn/Article/details/gt2nedgpphb.html

[D26] 数组转字符串
来源：http://dali.daxiang520.top/Article/details/gt2cvlpirhs.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yvedp.cn/Article/details/gt2fphmtokk.html

PHP:  implode(", ", $arr);
来源：http://dali.hammf.cn/Article/details/gt2nhcoirov.html

JS:   arr.join(", ")
来源：http://dali.aizwys.cn/Article/details/gt2oeluwqiu.html

TS:   arr.join(", ")
来源：http://dali.tian-w.cn/Article/details/gt2vqphxzol.html

Java: String.join(", ", list)
来源：http://dali.xziqi.cn/Article/details/gt2ohabtvzf.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yxrcldhz.html

Ruby: arr.join(", ")
来源：http://dali.guowangkeji.top/Article/details/gt2vgjtlpjt.html

C#:   string.Join(", ", list)
来源：http://dali.gogol.net.cn/Article/details/gt2lldkyuff.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2wuabgvru.html

E. 字符串处理
来源：http://dali.zhoulong.xyz/Article/details/gt2grqvpukf.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mbwjsyzl.html

[E01] 拼接字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2txlsknpv.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sufxvd.cn/Article/details/gt2sftdtygi.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ehwqpu.com/Article/details/gt2rgffnkid.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hywenlv.cn/Article/details/gt2zmepyeqf.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zycfv.cn/Article/details/gt2lxbwcyea.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yj20258888.top/Article/details/gt2hxmosila.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2yyipiaqm.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.dashuyun.cn/Article/details/gt2lbvijius.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gt2vobdldmq.html

[E02] 重复字符串
来源：http://dali.gotoacloud.top/Article/details/gt2glaqynna.html

Py:   "ab" * 3
来源：http://dali.andypj.xyz/Article/details/gt2btgcjpri.html

PHP:  str_repeat("ab", 3);
来源：http://dali.havefunace.top/Article/details/gt2rjxucnkl.html

JS:   "ab".repeat(3)
来源：http://dali.iojbl.cn/Article/details/gt2ezgxdrew.html

TS:   "ab".repeat(3)
来源：http://dali.jqgfzy.top/Article/details/gt2oqbdifpt.html

Java: "ab".repeat(3)
来源：http://dali.zhongyouzk.top/Article/details/gt2shsqgdmw.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.redwolf501.top/Article/details/gt2hhgmhrgv.html

Ruby: "ab" * 3
来源：http://dali.pengpengdd.cyou/Article/details/gt2pkhttkkx.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cashguo.top/Article/details/gt2qhrejqyd.html

[E03] 截取子串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2upwmdwav.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hyffhlzy.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gt2nwwwsjxd.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wkgnleip.html

TS:   s.slice(1, 4)
来源：http://dali.yvedp.cn/Article/details/gt2csoygdwe.html

Java: s.substring(1, 4)
来源：http://dali.xuanzx.com/Article/details/gt2qlxfhmod.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.iojbl.cn/Article/details/gt2pnbdnvvh.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.sxryk.cn/Article/details/gt2smezgywu.html

C#:   s.Substring(1, 3)
来源：http://dali.kuanghao11.cn/Article/details/gt2ofkemnjz.html

[E04] 查找子串位置
来源：http://dali.hnxiangtu.top/Article/details/gt2walvijzd.html

Py:   s.find("x");  s.index("x")
来源：http://dali.gotoacloud.top/Article/details/gt2upkakctc.html

PHP:  strpos($s, "x");
来源：http://dali.chenjidiqi.icu/Article/details/gt2gwljqvyy.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.pengpengdd.cyou/Article/details/gt2yhdzcnwc.html

TS:   s.indexOf("x")
来源：http://dali.aibaodan.cn/Article/details/gt2ubjovokz.html

Java: s.indexOf("x")
来源：http://dali.chenzaomai.com/Article/details/gt2xrirqknh.html

Go:   strings.Index(s, "x")
来源：http://dali.dianchejie.cn/Article/details/gt2nvsbxuju.html

Ruby: s.index("x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uvfewzaw.html

C#:   s.IndexOf("x")
来源：http://dali.xylfe.cn/Article/details/gt2xobtiofx.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhixingplan.top/Article/details/gt2wdsomeyx.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhoulong.xyz/Article/details/gt2gdioykgr.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yvedp.cn/Article/details/gt2yfxtlhuj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.pycfn.com/Article/details/gt2cjruujbh.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhengqikj.top/Article/details/gt2nvgkngzz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhengqikj.top/Article/details/gt2iyoskyqy.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.daxiang520.top/Article/details/gt2akfmeaaf.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ehwqpu.com/Article/details/gt2eegydgft.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhiwuduotai.top/Article/details/gt2atbveyqb.html

[E06] 替换子串
来源：http://dali.jyoumei.cn/Article/details/gt2fihhpbqn.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jlsjyb.cn/Article/details/gt2dhcuvxyk.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.gogol.net.cn/Article/details/gt2jmmpuumm.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tian-w.cn/Article/details/gt2aixidrek.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cheryme.top/Article/details/gt2ywgdcqfx.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.andypj.xyz/Article/details/gt2nrgkuubr.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.iojbl.cn/Article/details/gt2mssqolpd.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hnqzz.top/Article/details/gt2nnmoqodz.html

C#:   s.Replace("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gt2xuerggmz.html

[E07] 按分隔符拆分
来源：http://dali.jinqigufen.top/Article/details/gt2okdxyges.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yanxiufei.cn/Article/details/gt2tziiizbp.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.havefunace.top/Article/details/gt2tlahdpfn.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cdnleiting.top/Article/details/gt2mhoustpl.html

TS:   s.split(",")
来源：http://dali.yongpay.top/Article/details/gt2tyyygesa.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.wangshuangyany.cn/Article/details/gt2bqtofdcp.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yonumen.top/Article/details/gt2jybyrrtn.html

Ruby: s.split(",");  s.split
来源：http://dali.316326.xyz/Article/details/gt2huckzkwo.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jqgufenzy.top/Article/details/gt2cupwucwc.html

[E08] 数组按分隔符合并
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wllwpshb.html

Py:   ",".join(items)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rypewncr.html

PHP:  implode(",", $items);
来源：http://dali.aibaodan.cn/Article/details/gt2jwfzjnft.html

JS:   items.join(",")
来源：http://dali.hnqzz.top/Article/details/gt2wgwllkyh.html

TS:   items.join(",")
来源：http://dali.ivvv.top/Article/details/gt2ommaelmu.html

Java: String.join(",", items)
来源：http://dali.pycfn.com/Article/details/gt2sepghvks.html

Go:   strings.Join(items, ",")
来源：http://dali.mhx1999.top/Article/details/gt2zbyctfvk.html

Ruby: items.join(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lbtpidpn.html

C#:   string.Join(",", items)
来源：http://dali.ppjwa.cn/Article/details/gt2cqefmmgf.html

[E09] 去除所有空白字符
来源：http://dali.jinqigufen.top/Article/details/gt2yqqfdsox.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yonumen.top/Article/details/gt2kdbcaqwy.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jqgfzy.top/Article/details/gt2jrbogbcv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xziqi.cn/Article/details/gt2ewhlsidt.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yvedp.cn/Article/details/gt2ekzbbfwh.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.tanke756.top/Article/details/gt2lnpaggzp.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shuidangran.top/Article/details/gt2dfauqnfx.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.aizwys.cn/Article/details/gt2seicliwo.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.chenlongwang.top/Article/details/gt2tralfrpr.html

[E10] 左侧补零 / 定长填充
来源：http://dali.wangdashe.top/Article/details/gt2jzaudkoh.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.vqdsnc.cn/Article/details/gt2schedaql.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.havefunace.top/Article/details/gt2tnmihgpn.html

JS:   "7".padStart(3, "0")
来源：http://dali.ydzc1.top/Article/details/gt2lcrhwrqc.html

TS:   "7".padStart(3, "0")
来源：http://dali.shzxlz.cn/Article/details/gt2gerefpyt.html

Java: String.format("%03d", 7)
来源：http://dali.gotoacloud.top/Article/details/gt2zqayotnn.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhongyouzk.top/Article/details/gt2fhaockyk.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hykbsmmy.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jianghu66.top/Article/details/gt2fnafublu.html

[E11] 反转字符串
来源：http://dali.hammf.cn/Article/details/gt2yttlines.html

Py:   s[::-1]
来源：http://dali.yj202588.top/Article/details/gt2pvdxgmng.html

PHP:  strrev($s);
来源：http://dali.tanke756.top/Article/details/gt2jigijvgb.html

JS:   [...s].reverse().join("")
来源：http://dali.zhongyouzk.top/Article/details/gt2ypyetnfq.html

TS:   [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gt2kasulcfv.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.havefunace.top/Article/details/gt2tyhjisrn.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.c1oappe.top/Article/details/gt2nlplxqxy.html

Ruby: s.reverse
来源：http://dali.pycfn.com/Article/details/gt2uzrsvjwo.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cucudq.cn/Article/details/gt2qqyvftmy.html

[E12] 统计某字符出现次数
来源：http://dali.yongpay.top/Article/details/gt2gdewfydu.html

Py:   s.count("a")
来源：http://dali.xziqi.cn/Article/details/gt2fcdrixpq.html

PHP:  substr_count($s, "a");
来源：http://dali.zycfv.cn/Article/details/gt2sslttuvr.html

JS:   s.split("a").length - 1
来源：http://dali.snrcjt.cn/Article/details/gt2odnofurt.html

TS:   s.split("a").length - 1
来源：http://dali.shzxlz.cn/Article/details/gt2sxpifsmg.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yuanzhike.top/Article/details/gt2eetpebtf.html

Go:   strings.Count(s, "a")
来源：http://dali.9152youxi.cn/Article/details/gt2bonsigii.html

Ruby: s.count("a")
来源：http://dali.wangshuangyany.cn/Article/details/gt2bsvotocg.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sweek.top/Article/details/gt2mnlpfiil.html

[E13] 逐字符遍历
来源：http://dali.guowangkeji.top/Article/details/gt2jebpnhcs.html

Py:   for ch in s: print(ch)
来源：http://dali.nwbrower.top/Article/details/gt2cowtwfuu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jinqigufen.top/Article/details/gt2gxrkpwyy.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenlongwang.top/Article/details/gt2xdlcpxdg.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wghmxvgg.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.0kj1m.cn/Article/details/gt2fylgdrxm.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.svipenyu.cn/Article/details/gt2elpnimch.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yvedp.cn/Article/details/gt2swublxkl.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.snrcjt.cn/Article/details/gt2ugcyvgrl.html

[E14] URL 编码与 Base64
来源：http://dali.nanxinkj.top/Article/details/gt2dtacffpw.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cucudq.cn/Article/details/gt2gidpsald.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xziqi.cn/Article/details/gt2tlkfpmum.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gfgqssra.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ppjwa.cn/Article/details/gt2ugutxfhk.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jianghu66.top/Article/details/gt2yznpnmld.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhoulong.xyz/Article/details/gt2qdntmliv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.fengsongda.top/Article/details/gt2tnsfuhuv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yangfankeji.com/Article/details/gt2zpdklhls.html

[E15] HTML 转义 / 反转义
来源：http://dali.yueranfly.top/Article/details/gt2waioshkd.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.tian-w.cn/Article/details/gt2pdmqrusd.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.smart0.xyz/Article/details/gt2jcqdlaae.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jyoumei.cn/Article/details/gt2hnmblqlv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ivvv.top/Article/details/gt2jutpmmyl.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.wangshuangyany.cn/Article/details/gt2etbykahx.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.sweek.top/Article/details/gt2cxkzdlom.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xuanzx.com/Article/details/gt2tnrzdaza.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ybcxt.top/Article/details/gt2hywbvojv.html

[E16] 数字千分位
来源：http://dali.birdmap.top/Article/details/gt2ahiiravd.html

Py:   f"{1234567:,}"
来源：http://dali.jqgufenzy.top/Article/details/gt2gixeuors.html

PHP:  number_format(1234567);
来源：http://dali.bjfxy.top/Article/details/gt2ljahqfje.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zycfv.cn/Article/details/gt2mcqzmrbs.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2faswjnur.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.iojbl.cn/Article/details/gt2dbpnntym.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xuetiantiany.cn/Article/details/gt2okejikzm.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hongshengwenyu.top/Article/details/gt2rrrfxwhf.html

C#:   1234567.ToString("N0")
来源：http://dali.guowangkeji.top/Article/details/gt2adjyncmw.html

[E17] 首字母大写
来源：http://dali.sxryk.cn/Article/details/gt2hcqjwahp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yongpay.top/Article/details/gt2downjcao.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gzhubu.top/Article/details/gt2nuohfnph.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2thcioayb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2ejaiduwn.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.mhx1999.top/Article/details/gt2ygwkmsol.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cdnleiting.top/Article/details/gt2ssylfizi.html

Ruby: s.capitalize
来源：http://dali.shzxlz.cn/Article/details/gt2ujfnhnic.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jiagoushi.top/Article/details/gt2roctekak.html

[E18] 模板占位符替换
来源：http://dali.cashguo.top/Article/details/gt2wefnjuhc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.tanke756.top/Article/details/gt2izzkiccx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yuanzhike.top/Article/details/gt2wgupxwxx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.daxiang520.top/Article/details/gt2qufecxwb.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.daxiang520.top/Article/details/gt2ziwvfsnj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gt2bcoqtzqe.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jianghu66.top/Article/details/gt2jwfvukpz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cqqwz.cn/Article/details/gt2hbtosxly.html


<!-- 参考信息 -->