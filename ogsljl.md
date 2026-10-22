代发 wailian999

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hammf.cn/Article/details/gt2yyiucmyp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hfpthk.cn/Article/details/gt2wiwwsdor.html

JS:   arr.map(x => x * 2)
来源：http://dali.svipenyu.cn/Article/details/gt2yaukauny.html

TS:   arr.map(x => x * 2)
来源：http://dali.jqgfzy.top/Article/details/gt2rdxagphs.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.aibaodan.cn/Article/details/gt2duchfigb.html

Go:   // 手写循环
来源：http://dali.chenzaomai.com/Article/details/gt2jghodrjw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gt2rgikgrlp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kyxohhpa.html

[D15] 去重
来源：http://dali.zhoulong.xyz/Article/details/gt2zxcepekl.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.kuanghao11.cn/Article/details/gt2lzeswokx.html

PHP:  array_unique($arr);
来源：http://dali.ydzc1.top/Article/details/gt2fyhoizgr.html

JS:   [...new Set(arr)]
来源：http://dali.hfpthk.cn/Article/details/gt2cuemewxj.html

TS:   [...new Set(arr)]
来源：http://dali.zhoulong.xyz/Article/details/gt2pvnpdpcp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ybcxt.top/Article/details/gt2zfkpzlyi.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.cqqwz.cn/Article/details/gt2fxbcqbsn.html

Ruby: arr.uniq
来源：http://dali.wangshuangyany.cn/Article/details/gt2ctvybdxh.html

C#:   list.Distinct().ToList()
来源：http://dali.ybcxt.top/Article/details/gt2rkbulerf.html

[D16] 求和与平均值
来源：http://dali.zhixingplan.top/Article/details/gt2aleitojv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.nanxinkj.top/Article/details/gt2okntlwpw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2tiwrnmrj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cdnleiting.top/Article/details/gt2uzdkuzwe.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yangfankeji.com/Article/details/gt2qbblyozk.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xziqi.cn/Article/details/gt2nageamej.html

Go:   // 手写循环累加
来源：http://dali.jinqigufen.top/Article/details/gt2symtszto.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hnqzz.top/Article/details/gt2umvlkqzs.html

C#:   list.Sum();  list.Average()
来源：http://dali.sufxvd.cn/Article/details/gt2nxmthjjo.html

[D17] 最大值与最小值
来源：http://dali.ybcxt.top/Article/details/gt2qdcsuuqe.html

Py:   max(arr);  min(arr)
来源：http://dali.yonumen.top/Article/details/gt2upmavrrp.html

PHP:  max($arr);  min($arr);
来源：http://dali.jyoumei.cn/Article/details/gt2iknbmqzp.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shuidangran.top/Article/details/gt2labfdtra.html

TS:   Math.max(...arr);
来源：http://dali.hnqzz.top/Article/details/gt2aindsqjg.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2coqygwmg.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zkvdgkmi.html

Ruby: arr.max;  arr.min
来源：http://dali.hnqzz.top/Article/details/gt2oheepeyp.html

C#:   list.Max();  list.Min()
来源：http://dali.jianghu66.top/Article/details/gt2fpoelbwb.html

[D18] 扁平化嵌套数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iwigkgka.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.dianchejie.cn/Article/details/gt2iypjyqyn.html

PHP:  array_merge(...$nested);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gbodovsx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ydzc1.top/Article/details/gt2ovzfkwph.html

TS:   nested.flat();
来源：http://dali.jqgufenzy.top/Article/details/gt2syxytlgs.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.aibaodan.cn/Article/details/gt2ifebpgne.html

Go:   // 手写双层循环
来源：http://dali.cqqwz.cn/Article/details/gt2ricpcazg.html

Ruby: nested.flatten
来源：http://dali.mhx1999.top/Article/details/gt2ycbichvu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sufxvd.cn/Article/details/gt2hkzamfrv.html

[D19] 按字段分组
来源：http://dali.316326.xyz/Article/details/gt2hbnokqyx.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cqqwz.cn/Article/details/gt2ewxdoegi.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jqgufenzy.top/Article/details/gt2olcsojow.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gzhubu.top/Article/details/gt2fzzbmhnu.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.gzhubu.top/Article/details/gt2qagugpli.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.wangdashe.top/Article/details/gt2gorfvogi.html

Go:   // 手写 map[string][]T
来源：http://dali.guowangkeji.top/Article/details/gt2zkhytbya.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ujvinxvc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhoulong.xyz/Article/details/gt2omyvufvl.html

[D20] 统计每个元素出现次数
来源：http://dali.yuxming.cn/Article/details/gt2ixrqyvxe.html

Py:   Counter(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2rjrulggh.html

PHP:  array_count_values($arr);
来源：http://dali.yvedp.cn/Article/details/gt2rdrzttuu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yanxiufei.cn/Article/details/gt2aoejiejd.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hywenlv.cn/Article/details/gt2loxmvwah.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jqgfzy.top/Article/details/gt2frrgrhiv.html

Go:   // 手写 map[T]int
来源：http://dali.pengpengdd.cyou/Article/details/gt2qruyrmuz.html

Ruby: arr.tally
来源：http://dali.hammf.cn/Article/details/gt2gdwieonz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.tanke756.top/Article/details/gt2pjpgyzcf.html

[D21] 判断是否包含某元素
来源：http://dali.nanxinkj.top/Article/details/gt2hlkrlrwe.html

Py:   x in arr
来源：http://dali.haohaochexian.top/Article/details/gt2pdehvdgb.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cqqwz.cn/Article/details/gt2fpcixefn.html

JS:   arr.includes(x)
来源：http://dali.birdmap.top/Article/details/gt2ommzitkx.html

TS:   arr.includes(x)
来源：http://dali.meibo888.top/Article/details/gt2ekastklp.html

Java: list.contains(x)
来源：http://dali.guowangkeji.top/Article/details/gt2uwqrphof.html

Go:   slices.Contains(arr, x)
来源：http://dali.hammf.cn/Article/details/gt2oqlmshzs.html

Ruby: arr.include?(x)
来源：http://dali.iojbl.cn/Article/details/gt2sblkzlca.html

C#:   list.Contains(x)
来源：http://dali.meibo888.top/Article/details/gt2xzaisoga.html

[D22] 复制数组（避免共享引用）
来源：http://dali.aibaodan.cn/Article/details/gt2ilzcfhlw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2yiqempey.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.gogol.net.cn/Article/details/gt2kalmxtlt.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2dxitdddo.html

TS:   [...arr];
来源：http://dali.hammf.cn/Article/details/gt2ytzbysja.html

Java: new ArrayList<>(list);
来源：http://dali.havefunace.top/Article/details/gt2mxowsrjt.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinqigfzy.top/Article/details/gt2vqfjvcrv.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xziqi.cn/Article/details/gt2treqjgmk.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxpfyos.html

[D23] reduce 累积计算
来源：http://dali.hysaishi.cn/Article/details/gt2uubkyxyb.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yongpay.top/Article/details/gt2snvrhcqy.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.meibo888.top/Article/details/gt2sdoebrns.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxinkj.top/Article/details/gt2vybfcrjv.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shzxlz.cn/Article/details/gt2fhoqogdl.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ystoeqob.html

Go:   // 手写循环
来源：http://dali.zhongyouzk.top/Article/details/gt2clfylzmt.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.kuanghao11.cn/Article/details/gt2dzpcevtf.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shzxlz.cn/Article/details/gt2dtbnllgo.html

[D24] 字典 / Map 基本操作
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2icmebrml.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jyoumei.cn/Article/details/gt2rvcuohcg.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yj202588.top/Article/details/gt2fpgzvllo.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xcrqhgpr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jyoumei.cn/Article/details/gt2hxyosegb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.guowangkeji.top/Article/details/gt2dpopumos.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.tianlin.xyz/Article/details/gt2cruelioy.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.smart0.xyz/Article/details/gt2jgymmsfv.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.pengpengdd.cyou/Article/details/gt2gindnfmr.html

[D25] Set 集合去重与交并差
来源：http://dali.ppjwa.cn/Article/details/gt2stbctlvf.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.mhx1999.top/Article/details/gt2ddydxjpb.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yangfankeji.com/Article/details/gt2vnniqbbl.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2rjgdbjll.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.chenjidiqi.icu/Article/details/gt2pmeelwio.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.havefunace.top/Article/details/gt2flvjbcbg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.0kj1m.cn/Article/details/gt2soluguqi.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xuanzx.com/Article/details/gt2mllwcqdp.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.daxiang520.top/Article/details/gt2skyqsiee.html

[D26] 数组转字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2dhgvukig.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shangyingyoupin.top/Article/details/gt2iiulzlpw.html

PHP:  implode(", ", $arr);
来源：http://dali.aizwys.cn/Article/details/gt2vbtyypgw.html

JS:   arr.join(", ")
来源：http://dali.xinyue.icu/Article/details/gt2wrpakbpk.html

TS:   arr.join(", ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mlqkniyh.html

Java: String.join(", ", list)
来源：http://dali.dashuyun.cn/Article/details/gt2iqozffqm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.quarkkingdee.top/Article/details/gt2wzulifjl.html

Ruby: arr.join(", ")
来源：http://dali.jiagoushi.top/Article/details/gt2wqwlgnpz.html

C#:   string.Join(", ", list)
来源：http://dali.cucudq.cn/Article/details/gt2urmxaptn.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2sachispa.html

E. 字符串处理
来源：http://dali.guowangkeji.top/Article/details/gt2mdvrkocg.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2hwmylwvn.html

[E01] 拼接字符串
来源：http://dali.nanxinkj.top/Article/details/gt2nfzvrwya.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.nwbrower.top/Article/details/gt2gvbqwoma.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.fengsongda.top/Article/details/gt2lcdufizf.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.0kj1m.cn/Article/details/gt2hanhjqwf.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.c1oappe.top/Article/details/gt2boghscdx.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ydzc1.top/Article/details/gt2rydskejp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ybcxt.top/Article/details/gt2tcdetqmy.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cqqwz.cn/Article/details/gt2zjkcytti.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vqhgpdcc.html

[E02] 重复字符串
来源：http://dali.jlsjyb.cn/Article/details/gt2jzcqmmbd.html

Py:   "ab" * 3
来源：http://dali.shuidangran.top/Article/details/gt2zbdtvjuj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hywenlv.cn/Article/details/gt2qahtedvo.html

JS:   "ab".repeat(3)
来源：http://dali.yonumen.top/Article/details/gt2dhbkjuvs.html

TS:   "ab".repeat(3)
来源：http://dali.ydzc1.top/Article/details/gt2vhsvfcwx.html

Java: "ab".repeat(3)
来源：http://dali.xziqi.cn/Article/details/gt2rdsujttj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zycfv.cn/Article/details/gt2jlwbfoxe.html

Ruby: "ab" * 3
来源：http://dali.vqdsnc.cn/Article/details/gt2zcpzuwzs.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.svipenyu.cn/Article/details/gt2xxshllsb.html

[E03] 截取子串
来源：http://dali.chenjidiqi.icu/Article/details/gt2gzadfotg.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.kuanghao11.cn/Article/details/gt2rxptlxse.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gt2oyuampxm.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xziqi.cn/Article/details/gt2qwjccnuu.html

TS:   s.slice(1, 4)
来源：http://dali.ehwqpu.com/Article/details/gt2wwkbfapt.html

Java: s.substring(1, 4)
来源：http://dali.fzhhl.top/Article/details/gt2ualnskiu.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.tianlin.xyz/Article/details/gt2qqajsant.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.dashuyun.cn/Article/details/gt2tdpjlqhv.html

C#:   s.Substring(1, 3)
来源：http://dali.yongpay.top/Article/details/gt2siguxctt.html

[E04] 查找子串位置
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pacrpzmh.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hrcubuyd.html

PHP:  strpos($s, "x");
来源：http://dali.aizwys.cn/Article/details/gt2kzxqyett.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.daxiang520.top/Article/details/gt2ffyxqaxy.html

TS:   s.indexOf("x")
来源：http://dali.aizwys.cn/Article/details/gt2xlplwbty.html

Java: s.indexOf("x")
来源：http://dali.fzhhl.top/Article/details/gt2bxunajog.html

Go:   strings.Index(s, "x")
来源：http://dali.chenlongwang.top/Article/details/gt2dsiqlnik.html

Ruby: s.index("x")
来源：http://dali.sufxvd.cn/Article/details/gt2sabdgpen.html

C#:   s.IndexOf("x")
来源：http://dali.wangdashe.top/Article/details/gt2zezhgbql.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dblpchyz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hysaishi.cn/Article/details/gt2hcyhnpcj.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.guannengcc.top/Article/details/gt2ycbbyorf.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hfpthk.cn/Article/details/gt2edpgyukc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.birdmap.top/Article/details/gt2jcbmqmcb.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.aizwys.cn/Article/details/gt2zfdmcpys.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.havefunace.top/Article/details/gt2geitaalf.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.chenjidiqi.icu/Article/details/gt2phxtsfbw.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yueranfly.top/Article/details/gt2pljgascn.html

[E06] 替换子串
来源：http://dali.xuetiantiany.cn/Article/details/gt2kqdmwtsq.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hnqzz.top/Article/details/gt2wqlnjuyh.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jinqigfzy.top/Article/details/gt2fgqpbplk.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangdashe.top/Article/details/gt2oyusjffp.html

TS:   s.replaceAll("a", "b")
来源：http://dali.316326.xyz/Article/details/gt2zsmeznpz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cashguo.top/Article/details/gt2lfocuamd.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zdqjudy.top/Article/details/gt2onucpefs.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yuxming.cn/Article/details/gt2zljyzccv.html

C#:   s.Replace("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gt2whbqqktt.html

[E07] 按分隔符拆分
来源：http://dali.havefunace.top/Article/details/gt2ykofwqhz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.nwbrower.top/Article/details/gt2xjjdmeru.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.aizwys.cn/Article/details/gt2rjtrujvo.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hnxiangtu.top/Article/details/gt2gftmpcrc.html

TS:   s.split(",")
来源：http://dali.guannengcc.top/Article/details/gt2mausgnok.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhoulong.xyz/Article/details/gt2ohqlqlqp.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gzhubu.top/Article/details/gt2ufpkrpyn.html

Ruby: s.split(",");  s.split
来源：http://dali.yangfankeji.com/Article/details/gt2qhxqfeia.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hnxiangtu.top/Article/details/gt2yoscjesz.html

[E08] 数组按分隔符合并
来源：http://dali.aizwys.cn/Article/details/gt2xjzslbka.html

Py:   ",".join(items)
来源：http://dali.ivvv.top/Article/details/gt2rehqebbl.html

PHP:  implode(",", $items);
来源：http://dali.jinqigufen.top/Article/details/gt2scpxnhrk.html

JS:   items.join(",")
来源：http://dali.ivvv.top/Article/details/gt2tlzbekha.html

TS:   items.join(",")
来源：http://dali.quarkkingdee.top/Article/details/gt2rvvykpcq.html

Java: String.join(",", items)
来源：http://dali.shuidangran.top/Article/details/gt2flcgnyem.html

Go:   strings.Join(items, ",")
来源：http://dali.fengsongda.top/Article/details/gt2esmvdoqs.html

Ruby: items.join(",")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2luvsioul.html

C#:   string.Join(",", items)
来源：http://dali.hywenlv.cn/Article/details/gt2pgfzkoyt.html

[E09] 去除所有空白字符
来源：http://dali.snrcjt.cn/Article/details/gt2alyziehh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.aibaodan.cn/Article/details/gt2ccbbpibu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yuxming.cn/Article/details/gt2jgyktfqd.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hysaishi.cn/Article/details/gt2chbrusjc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.nanxuanxn.top/Article/details/gt2jfckbqwj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.svipenyu.cn/Article/details/gt2kplxhkxp.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yj202588.top/Article/details/gt2jkgiuvdl.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yuugummd.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yj20258.top/Article/details/gt2jjatfmtc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hnxiangtu.top/Article/details/gt2bgrryubt.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xylfe.cn/Article/details/gt2pfedxbdc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ehwqpu.com/Article/details/gt2pcnmdzqa.html

JS:   "7".padStart(3, "0")
来源：http://dali.birdmap.top/Article/details/gt2dgydpzrk.html

TS:   "7".padStart(3, "0")
来源：http://dali.jqgufenzy.top/Article/details/gt2tdglwnqm.html

Java: String.format("%03d", 7)
来源：http://dali.jiagoushi.top/Article/details/gt2niodesyh.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2azqauujj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gogol.net.cn/Article/details/gt2dgyiuikk.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhengqikj.top/Article/details/gt2ageezuzr.html

[E11] 反转字符串
来源：http://dali.yuxming.cn/Article/details/gt2bkkqtsxj.html

Py:   s[::-1]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2brgrjuco.html

PHP:  strrev($s);
来源：http://dali.kuanghao11.cn/Article/details/gt2kguhepgu.html

JS:   [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gt2lhwiecal.html

TS:   [...s].reverse().join("")
来源：http://dali.hongshengwenyu.top/Article/details/gt2jwccuous.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yj20258.top/Article/details/gt2hsubmemr.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.bjfxy.top/Article/details/gt2qkmzlkmr.html

Ruby: s.reverse
来源：http://dali.dianchejie.cn/Article/details/gt2xogeiyge.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.redwolf501.top/Article/details/gt2pkynwtli.html

[E12] 统计某字符出现次数
来源：http://dali.sxryk.cn/Article/details/gt2knvwqgoo.html

Py:   s.count("a")
来源：http://dali.quarkkingdee.top/Article/details/gt2yokodzmx.html

PHP:  substr_count($s, "a");
来源：http://dali.iojbl.cn/Article/details/gt2hlnefzdy.html

JS:   s.split("a").length - 1
来源：http://dali.jqgufenzy.top/Article/details/gt2ygwhgfml.html

TS:   s.split("a").length - 1
来源：http://dali.yangfankeji.com/Article/details/gt2vfbcizrd.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yvedp.cn/Article/details/gt2jsxutkzc.html

Go:   strings.Count(s, "a")
来源：http://dali.hongshengwenyu.top/Article/details/gt2dpjtbeas.html

Ruby: s.count("a")
来源：http://dali.chenlongwang.top/Article/details/gt2adecjtxb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.iojbl.cn/Article/details/gt2aovgzjyt.html

[E13] 逐字符遍历
来源：http://dali.yj202588.top/Article/details/gt2ougztgnq.html

Py:   for ch in s: print(ch)
来源：http://dali.jinqigufen.top/Article/details/gt2ntbygxxn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xylfe.cn/Article/details/gt2usvsclas.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gaohongyu789.top/Article/details/gt2isenugaq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shzxlz.cn/Article/details/gt2qizbgyki.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yj202588.top/Article/details/gt2hwiokcki.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hysaishi.cn/Article/details/gt2nmajsdgf.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.havefunace.top/Article/details/gt2dojxctuu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.redwolf501.top/Article/details/gt2bqiysqmi.html

[E14] URL 编码与 Base64
来源：http://dali.gotoacloud.top/Article/details/gt2eamleydd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.snrcjt.cn/Article/details/gt2utpvdkzd.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yonumen.top/Article/details/gt2bmrdesqv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.smart0.xyz/Article/details/gt2uungihoy.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zycfv.cn/Article/details/gt2klslztue.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.nwbrower.top/Article/details/gt2rlglkwet.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.tanke756.top/Article/details/gt2ksreinbu.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.gaohongyu789.top/Article/details/gt2hixctxpe.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yj20258.top/Article/details/gt2dhbgdwbj.html

[E15] HTML 转义 / 反转义
来源：http://dali.fengsongda.top/Article/details/gt2ksfhhdcu.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cqqwz.cn/Article/details/gt2ixhcnsfx.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zdqjudy.top/Article/details/gt2lyeuewod.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cdnleiting.top/Article/details/gt2lsqomznz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gxtjodeq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jqgfzy.top/Article/details/gt2tcewadjr.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ivvv.top/Article/details/gt2iglpxdck.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ydzc1.top/Article/details/gt2lxldllpv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yangfankeji.com/Article/details/gt2eokfaxbl.html

[E16] 数字千分位
来源：http://dali.chenlongwang.top/Article/details/gt2ihyrobev.html

Py:   f"{1234567:,}"
来源：http://dali.xylfe.cn/Article/details/gt2jcxqvcmk.html

PHP:  number_format(1234567);
来源：http://dali.wangshuangyany.cn/Article/details/gt2kryrjmdq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.gogol.net.cn/Article/details/gt2jmipcsmo.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cucudq.cn/Article/details/gt2wyiitvbo.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.guannengcc.top/Article/details/gt2khborqzm.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.feifeiyinyue.top/Article/details/gt2zatzxpca.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cqqwz.cn/Article/details/gt2xymmhvvq.html

C#:   1234567.ToString("N0")
来源：http://dali.smart0.xyz/Article/details/gt2itxigbdy.html

[E17] 首字母大写
来源：http://dali.nanxinkj.top/Article/details/gt2csekypub.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zcxwxdkl.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.svipenyu.cn/Article/details/gt2rbtylptr.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yueranfly.top/Article/details/gt2izslazgz.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jianghu66.top/Article/details/gt2hzdabebu.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.smart0.xyz/Article/details/gt2vuaaxiha.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.nanxinkj.top/Article/details/gt2tuluwubd.html

Ruby: s.capitalize
来源：http://dali.haohaochexian.top/Article/details/gt2yfbiujce.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yongpay.top/Article/details/gt2vrywwxyi.html

[E18] 模板占位符替换
来源：http://dali.ybcxt.top/Article/details/gt2vohwekev.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fwnoginl.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gaohongyu789.top/Article/details/gt2dmfomhtk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2duhblrxa.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xziqi.cn/Article/details/gt2jkoqcgsb.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yanxiufei.cn/Article/details/gt2uvsyiqfb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ipivhhsi.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.daxiang520.top/Article/details/gt2otfiohno.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hnxiangtu.top/Article/details/gt2rplarsga.html

[E19] 多行文本按行拆分
来源：http://dali.shangyingyoupin.top/Article/details/gt2evgkeixl.html

Py:   s.splitlines()
来源：http://dali.0kj1m.cn/Article/details/gt2szqjsgzd.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cheryme.top/Article/details/gt2hbovwehy.html

JS:   s.split(/\r?\n/)
来源：http://dali.hywenlv.cn/Article/details/gt2kvmahixw.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhixingplan.top/Article/details/gt2rtrexyyj.html

Java: s.lines().toList()
来源：http://dali.birdmap.top/Article/details/gt2bkauolxm.html

Go:   strings.Split(s, "\n")
来源：http://dali.tianlin.xyz/Article/details/gt2kcvdcsgb.html

Ruby: s.lines
来源：http://dali.daria6918.cn/Article/details/gt2pdjicccu.html

C#:   s.Split('\n')
来源：http://dali.guowangkeji.top/Article/details/gt2bhhfkvaf.html

[E20] 判断字符串是否为空
来源：http://dali.0kj1m.cn/Article/details/gt2ytagvjht.html

Py:   if not s:
来源：http://dali.yueranfly.top/Article/details/gt2xnjbywkz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.haohaochexian.top/Article/details/gt2jtcwvcbo.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.pycfn.com/Article/details/gt2kwfuqkiw.html

TS:   if (s === "") {}
来源：http://dali.316326.xyz/Article/details/gt2vcnidvbr.html

Java: if (s.isEmpty()) {}
来源：http://dali.yueranfly.top/Article/details/gt2mocjyjsi.html

Go:   if s == "" {}
来源：http://dali.svipenyu.cn/Article/details/gt2dnmyyboh.html

Ruby: if s.empty?
来源：http://dali.ybcxt.top/Article/details/gt2bcwpshxd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hcgdudin.html

[E21] 超长截断加省略号
来源：http://dali.yangfankeji.com/Article/details/gt2dwgejeot.html


<!-- 参考信息 -->