代发 wailian999

[D11] 反转数组
来源：http://dali.jyoumei.cn/Article/details/gt2tkltsrvd.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.aibaodan.cn/Article/details/gt2zlzpdkwm.html

PHP:  array_reverse($arr);
来源：http://dali.316326.xyz/Article/details/gt2cpwxvibd.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.0kj1m.cn/Article/details/gt2dgavbhjk.html

TS:   [...arr].reverse();
来源：http://dali.vqdsnc.cn/Article/details/gt2jvlwiiad.html

Java: Collections.reverse(list);
来源：http://dali.zdqjudy.top/Article/details/gt2qbvvdmua.html

Go:   slices.Reverse(arr)
来源：http://dali.meibo888.top/Article/details/gt2yahujzlh.html

Ruby: arr.reverse
来源：http://dali.sysykeji.top/Article/details/gt2lbcfbikg.html

C#:   list.Reverse();
来源：http://dali.hammf.cn/Article/details/gt2plbhnhra.html

[D12] 查找元素下标
来源：http://dali.xylfe.cn/Article/details/gt2scaifzaz.html

Py:   arr.index(x);  x in arr
来源：http://dali.haohaochexian.top/Article/details/gt2oxlodfgu.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2zfnyardq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gt2nfpdmjci.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aizwys.cn/Article/details/gt2quiwxtem.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.havefunace.top/Article/details/gt2jaeauxpa.html

Go:   slices.Index(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gt2vlvtnyve.html

Ruby: arr.index(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2vimimmed.html

C#:   list.IndexOf(x);
来源：http://dali.tanke756.top/Article/details/gt2swkogyob.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hywenlv.cn/Article/details/gt2kcrmdcsj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sweek.top/Article/details/gt2ntrhmrfz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xylfe.cn/Article/details/gt2eyqvcfti.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jinqigufen.top/Article/details/gt2dloqflwc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jlsjyb.cn/Article/details/gt2snnbffwu.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yangfankeji.com/Article/details/gt2otnpnwrd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xinyue.icu/Article/details/gt2myfvjjzh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hywenlv.cn/Article/details/gt2hnnkedic.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ivvv.top/Article/details/gt2jxealhlm.html

[D14] 映射转换（每个元素变形）
来源：http://dali.smart0.xyz/Article/details/gt2hqnzamiy.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.tian-w.cn/Article/details/gt2fsyfazxe.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.guannengcc.top/Article/details/gt2bdcofmic.html

JS:   arr.map(x => x * 2)
来源：http://dali.bjfxy.top/Article/details/gt2ttwmnhfx.html

TS:   arr.map(x => x * 2)
来源：http://dali.tanke756.top/Article/details/gt2noidozsn.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.nanxuanxn.top/Article/details/gt2kfudobkn.html

Go:   // 手写循环
来源：http://dali.yueranfly.top/Article/details/gt2pmtpebfx.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.c1oappe.top/Article/details/gt2tzgprvvd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jqgfzy.top/Article/details/gt2dvnchmab.html

[D15] 去重
来源：http://dali.meibo888.top/Article/details/gt2wezgtjgu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yongpay.top/Article/details/gt2hlindzpj.html

PHP:  array_unique($arr);
来源：http://dali.yj202588.top/Article/details/gt2sfjklywu.html

JS:   [...new Set(arr)]
来源：http://dali.aibaodan.cn/Article/details/gt2kijhfkcx.html

TS:   [...new Set(arr)]
来源：http://dali.dashuyun.cn/Article/details/gt2uumiysps.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.tanke756.top/Article/details/gt2sxwclfmj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shzxlz.cn/Article/details/gt2ongihpcb.html

Ruby: arr.uniq
来源：http://dali.hammf.cn/Article/details/gt2huhmuviu.html

C#:   list.Distinct().ToList()
来源：http://dali.ydzc1.top/Article/details/gt2kkkjdbds.html

[D16] 求和与平均值
来源：http://dali.hammf.cn/Article/details/gt2wjpuobcl.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2qpgjdczr.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.birdmap.top/Article/details/gt2efyumltt.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.haohaochexian.top/Article/details/gt2nrekckcu.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.iojbl.cn/Article/details/gt2dmmdigyi.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.andypj.xyz/Article/details/gt2dvtoblim.html

Go:   // 手写循环累加
来源：http://dali.birdmap.top/Article/details/gt2zcarpymh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ntvavstb.html

C#:   list.Sum();  list.Average()
来源：http://dali.hnxiangtu.top/Article/details/gt2iimleecs.html

[D17] 最大值与最小值
来源：http://dali.havefunace.top/Article/details/gt2hdtlctzq.html

Py:   max(arr);  min(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qjcrnclw.html

PHP:  max($arr);  min($arr);
来源：http://dali.chenzaomai.com/Article/details/gt2aytiapze.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.daxiang520.top/Article/details/gt2ofisbflx.html

TS:   Math.max(...arr);
来源：http://dali.hywenlv.cn/Article/details/gt2omwkwmup.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xuanzx.com/Article/details/gt2pmkzgeun.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2jcuaqill.html

Ruby: arr.max;  arr.min
来源：http://dali.xziqi.cn/Article/details/gt2xrisafcj.html

C#:   list.Max();  list.Min()
来源：http://dali.bjfxy.top/Article/details/gt2dvkjexca.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwujszf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yj20258.top/Article/details/gt2kejqvuqi.html

PHP:  array_merge(...$nested);
来源：http://dali.pycfn.com/Article/details/gt2yiwalbxw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.fzhhl.top/Article/details/gt2vrqhnvqi.html

TS:   nested.flat();
来源：http://dali.fzhhl.top/Article/details/gt2iszyapag.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.andypj.xyz/Article/details/gt2igrizvzg.html

Go:   // 手写双层循环
来源：http://dali.yonumen.top/Article/details/gt2vrsiuljc.html

Ruby: nested.flatten
来源：http://dali.jiagoushi.top/Article/details/gt2zfbytizp.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xuanzx.com/Article/details/gt2afuflrwi.html

[D19] 按字段分组
来源：http://dali.9152youxi.cn/Article/details/gt2pnesfpjv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.quarkkingdee.top/Article/details/gt2swuroddu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.iojbl.cn/Article/details/gt2mwsaoyel.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.aibaodan.cn/Article/details/gt2hdtkdsbb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xuetiantiany.cn/Article/details/gt2rhhcsefk.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.9152youxi.cn/Article/details/gt2uoxgojff.html

Go:   // 手写 map[string][]T
来源：http://dali.gzhubu.top/Article/details/gt2aoaircwj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gotoacloud.top/Article/details/gt2bzejvmtt.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yuanzhike.top/Article/details/gt2cmalvust.html

[D20] 统计每个元素出现次数
来源：http://dali.zhoulong.xyz/Article/details/gt2vcsehydr.html

Py:   Counter(arr)
来源：http://dali.yuanzhike.top/Article/details/gt2nngdglnd.html

PHP:  array_count_values($arr);
来源：http://dali.yvedp.cn/Article/details/gt2uxyikgow.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.meibo888.top/Article/details/gt2dnbhckgx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.havefunace.top/Article/details/gt2fdavbkst.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xylfe.cn/Article/details/gt2arunkhvy.html

Go:   // 手写 map[T]int
来源：http://dali.guowangkeji.top/Article/details/gt2qsojtqkj.html

Ruby: arr.tally
来源：http://dali.yj20258888.top/Article/details/gt2bumuptix.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.9152youxi.cn/Article/details/gt2ukxfrolh.html

[D21] 判断是否包含某元素
来源：http://dali.zhiwuduotai.top/Article/details/gt2ffyddfps.html

Py:   x in arr
来源：http://dali.zhixingplan.top/Article/details/gt2uahuqvhi.html

PHP:  in_array($x, $arr, true);
来源：http://dali.guowangkeji.top/Article/details/gt2zynhzvxt.html

JS:   arr.includes(x)
来源：http://dali.zhengqikj.top/Article/details/gt2ochrtbkw.html

TS:   arr.includes(x)
来源：http://dali.fengsongda.top/Article/details/gt2htrfpsqp.html

Java: list.contains(x)
来源：http://dali.yj20258.top/Article/details/gt2wraaqbar.html

Go:   slices.Contains(arr, x)
来源：http://dali.yonumen.top/Article/details/gt2pfgslwol.html

Ruby: arr.include?(x)
来源：http://dali.birdmap.top/Article/details/gt2tapybwph.html

C#:   list.Contains(x)
来源：http://dali.tanke756.top/Article/details/gt2ffydcvov.html

[D22] 复制数组（避免共享引用）
来源：http://dali.snrcjt.cn/Article/details/gt2wyssrbrr.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xuanzx.com/Article/details/gt2cixhhygi.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yangfankeji.com/Article/details/gt2fyvwsqvd.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2gzuisqtn.html

TS:   [...arr];
来源：http://dali.yongpay.top/Article/details/gt2vwsxfjtc.html

Java: new ArrayList<>(list);
来源：http://dali.jqgufenzy.top/Article/details/gt2gfuojrtg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhiwuduotai.top/Article/details/gt2fddhfedm.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hysaishi.cn/Article/details/gt2yfekaytz.html

C#:   new List<int>(list);
来源：http://dali.xinyue.icu/Article/details/gt2mosuuvgn.html

[D23] reduce 累积计算
来源：http://dali.nanxuanxn.top/Article/details/gt2nwxxinjv.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hammf.cn/Article/details/gt2sfyrepdf.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zycfv.cn/Article/details/gt2kpprlcbv.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hywenlv.cn/Article/details/gt2ygzwucnr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daria6918.cn/Article/details/gt2krorvhhh.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.c1oappe.top/Article/details/gt2iuxtwarc.html

Go:   // 手写循环
来源：http://dali.jlsjyb.cn/Article/details/gt2jycvtsqi.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yonumen.top/Article/details/gt2nnvloaam.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jqgufenzy.top/Article/details/gt2iliswcnj.html

[D24] 字典 / Map 基本操作
来源：http://dali.aibaodan.cn/Article/details/gt2raqqzrdg.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hfpthk.cn/Article/details/gt2vvwqizre.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yongpay.top/Article/details/gt2yxdjkhiq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.tianlin.xyz/Article/details/gt2rutlkwbg.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hnqzz.top/Article/details/gt2srvhhekh.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.birdmap.top/Article/details/gt2tkugxjog.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.sweek.top/Article/details/gt2clzkwcrs.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hammf.cn/Article/details/gt2lfohupcp.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jianghu66.top/Article/details/gt2beadpjqj.html

[D25] Set 集合去重与交并差
来源：http://dali.yj202588.top/Article/details/gt2pypoqoge.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.nwbrower.top/Article/details/gt2gcbrckks.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ufntabth.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.daria6918.cn/Article/details/gt2dutkyuhw.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yongpay.top/Article/details/gt2aigimcbe.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.chenzaomai.com/Article/details/gt2xhxcxaxr.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yj20258888.top/Article/details/gt2ozyrtbmh.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hysaishi.cn/Article/details/gt2roiytqub.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.nanxinkj.top/Article/details/gt2lbxpjexu.html

[D26] 数组转字符串
来源：http://dali.hnqzz.top/Article/details/gt2lakrldcf.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yj20258888.top/Article/details/gt2dvfkwvkz.html

PHP:  implode(", ", $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2tzghavlj.html

JS:   arr.join(", ")
来源：http://dali.xuetiantiany.cn/Article/details/gt2vbtpcjeb.html

TS:   arr.join(", ")
来源：http://dali.cqqwz.cn/Article/details/gt2pjgnppok.html

Java: String.join(", ", list)
来源：http://dali.snrcjt.cn/Article/details/gt2bgjfhnix.html

Go:   strings.Join(strs, ", ")
来源：http://dali.gotoacloud.top/Article/details/gt2ygkpkcal.html

Ruby: arr.join(", ")
来源：http://dali.chenlongwang.top/Article/details/gt2awrfmfoa.html

C#:   string.Join(", ", list)
来源：http://dali.pycfn.com/Article/details/gt2noiyjekp.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2tiowjxjf.html

E. 字符串处理
来源：http://dali.cashguo.top/Article/details/gt2pmogswex.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2yfneamtg.html

[E01] 拼接字符串
来源：http://dali.haohaochexian.top/Article/details/gt2pqeqaskn.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.smart0.xyz/Article/details/gt2ueormbgj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.cqqwz.cn/Article/details/gt2vxsokzqf.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nwbrower.top/Article/details/gt2ypmiuwys.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.mhx1999.top/Article/details/gt2hhcciuyo.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.haohaochexian.top/Article/details/gt2hkwhbare.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.tian-w.cn/Article/details/gt2bmwzvfcd.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.guowangkeji.top/Article/details/gt2glksivha.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.wangdashe.top/Article/details/gt2kwvizjhc.html

[E02] 重复字符串
来源：http://dali.daria6918.cn/Article/details/gt2pxboowrc.html

Py:   "ab" * 3
来源：http://dali.pycfn.com/Article/details/gt2vrifyuvj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.tian-w.cn/Article/details/gt2tlgmpfid.html

JS:   "ab".repeat(3)
来源：http://dali.andypj.xyz/Article/details/gt2iipvfcgz.html

TS:   "ab".repeat(3)
来源：http://dali.zycfv.cn/Article/details/gt2fxrszrwl.html

Java: "ab".repeat(3)
来源：http://dali.zhixingplan.top/Article/details/gt2rlifeqpj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yanxiufei.cn/Article/details/gt2afwdctcc.html

Ruby: "ab" * 3
来源：http://dali.svipenyu.cn/Article/details/gt2frkcsctw.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jianghu66.top/Article/details/gt2lkmwzghh.html

[E03] 截取子串
来源：http://dali.c1oappe.top/Article/details/gt2ujndknjo.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xinyue.icu/Article/details/gt2kkjxcsyg.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shzxlz.cn/Article/details/gt2uoumtxmh.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yuanzhike.top/Article/details/gt2rgfccbda.html

TS:   s.slice(1, 4)
来源：http://dali.sufxvd.cn/Article/details/gt2qfhtpsww.html

Java: s.substring(1, 4)
来源：http://dali.guannengcc.top/Article/details/gt2vvbsxkmj.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.birdmap.top/Article/details/gt2tujunpjl.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ybcxt.top/Article/details/gt2dqgauvwi.html

C#:   s.Substring(1, 3)
来源：http://dali.yj20258888.top/Article/details/gt2yuslpzjc.html

[E04] 查找子串位置
来源：http://dali.zycfv.cn/Article/details/gt2vruwgphj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.mhx1999.top/Article/details/gt2wvdasvyx.html

PHP:  strpos($s, "x");
来源：http://dali.jqgfzy.top/Article/details/gt2prjwdckr.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.aizwys.cn/Article/details/gt2gzgwspqh.html

TS:   s.indexOf("x")
来源：http://dali.fengsongda.top/Article/details/gt2eycawgoj.html

Java: s.indexOf("x")
来源：http://dali.cheryme.top/Article/details/gt2gdtynzud.html

Go:   strings.Index(s, "x")
来源：http://dali.cheryme.top/Article/details/gt2yxxyigym.html

Ruby: s.index("x")
来源：http://dali.ppjwa.cn/Article/details/gt2jyvufyct.html

C#:   s.IndexOf("x")
来源：http://dali.wangshuangyany.cn/Article/details/gt2rjijiyro.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hfpthk.cn/Article/details/gt2btkfffhg.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wgkxpxir.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.gzhubu.top/Article/details/gt2manyvmdj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhoulong.xyz/Article/details/gt2uyuwudfn.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2isealqio.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj20258.top/Article/details/gt2sbzyleci.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yuxming.cn/Article/details/gt2jqphkxeb.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yj20258888.top/Article/details/gt2viaoqalr.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cucudq.cn/Article/details/gt2jgwjzbfo.html

[E06] 替换子串
来源：http://dali.chenzaomai.com/Article/details/gt2shngvcwc.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2erasoajv.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yanxiufei.cn/Article/details/gt2rpipnwsz.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gt2qowfperi.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cucudq.cn/Article/details/gt2mdcccaqj.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj202588.top/Article/details/gt2gtqvwekb.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2otfduphk.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.fengsongda.top/Article/details/gt2rsqssror.html

C#:   s.Replace("a", "b")
来源：http://dali.nwbrower.top/Article/details/gt2unypmsdc.html

[E07] 按分隔符拆分
来源：http://dali.zhongyouzk.top/Article/details/gt2yybvvcuj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yongpay.top/Article/details/gt2gszdpsyk.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.dashuyun.cn/Article/details/gt2kvupfead.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hammf.cn/Article/details/gt2qjeykslu.html

TS:   s.split(",")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jitgtppo.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dypwbxkf.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2jjdnndwr.html

Ruby: s.split(",");  s.split
来源：http://dali.hongshengwenyu.top/Article/details/gt2jrobweuc.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yueranfly.top/Article/details/gt2slbvdgiy.html

[E08] 数组按分隔符合并
来源：http://dali.nwbrower.top/Article/details/gt2vujxsabv.html

Py:   ",".join(items)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ifgkwpbu.html

PHP:  implode(",", $items);
来源：http://dali.zhongyouzk.top/Article/details/gt2frbqgglq.html

JS:   items.join(",")
来源：http://dali.yj20258888.top/Article/details/gt2sldddowu.html

TS:   items.join(",")
来源：http://dali.gogol.net.cn/Article/details/gt2cdpcfpzl.html

Java: String.join(",", items)
来源：http://dali.zhixingplan.top/Article/details/gt2kyreonjj.html

Go:   strings.Join(items, ",")
来源：http://dali.hongshengwenyu.top/Article/details/gt2dlsilwns.html

Ruby: items.join(",")
来源：http://dali.fengsongda.top/Article/details/gt2isuxhrwi.html

C#:   string.Join(",", items)
来源：http://dali.zhoulong.xyz/Article/details/gt2cjsqwahf.html

[E09] 去除所有空白字符
来源：http://dali.yj202588.top/Article/details/gt2mwzdfwpg.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.tanke756.top/Article/details/gt2kjfstlzc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xuanzx.com/Article/details/gt2ndwhfwbo.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lgzmdoid.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2odqozyky.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.sufxvd.cn/Article/details/gt2kszosros.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xuanzx.com/Article/details/gt2yqxoicax.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hnxiangtu.top/Article/details/gt2bcogmxlj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ybcxt.top/Article/details/gt2rcclksrk.html

[E10] 左侧补零 / 定长填充
来源：http://dali.nanxinkj.top/Article/details/gt2qancrden.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sysykeji.top/Article/details/gt2edcxoeqi.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jiagoushi.top/Article/details/gt2bysjwscs.html

JS:   "7".padStart(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gt2fcaftdad.html

TS:   "7".padStart(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gt2xoiohrwu.html

Java: String.format("%03d", 7)
来源：http://dali.yangfankeji.com/Article/details/gt2xpjilhmc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2snrlixhj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jyoumei.cn/Article/details/gt2hxzzacjg.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.redwolf501.top/Article/details/gt2lhcxvrdx.html

[E11] 反转字符串
来源：http://dali.xylfe.cn/Article/details/gt2mmmmpzuk.html

Py:   s[::-1]
来源：http://dali.fengsongda.top/Article/details/gt2sgpgyxtx.html

PHP:  strrev($s);
来源：http://dali.birdmap.top/Article/details/gt2oiiccuww.html

JS:   [...s].reverse().join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ybqujwwk.html

TS:   [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gt2mffnurpq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hfpthk.cn/Article/details/gt2lledeyhd.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jinqigufen.top/Article/details/gt2hvrtjdbx.html

Ruby: s.reverse
来源：http://dali.zdqjudy.top/Article/details/gt2hpomeohp.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.bjfxy.top/Article/details/gt2yewjuidw.html

[E12] 统计某字符出现次数
来源：http://dali.quarkkingdee.top/Article/details/gt2lbgidjvm.html

Py:   s.count("a")
来源：http://dali.feifeiyinyue.top/Article/details/gt2hybkedws.html

PHP:  substr_count($s, "a");
来源：http://dali.hnqzz.top/Article/details/gt2wqtxbwme.html

JS:   s.split("a").length - 1
来源：http://dali.ydzc1.top/Article/details/gt2hjospaus.html

TS:   s.split("a").length - 1
来源：http://dali.nwbrower.top/Article/details/gt2hlhowlwo.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.316326.xyz/Article/details/gt2kgaivvki.html

Go:   strings.Count(s, "a")
来源：http://dali.tianlin.xyz/Article/details/gt2tjyopsda.html

Ruby: s.count("a")
来源：http://dali.jqgfzy.top/Article/details/gt2punjndou.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cucudq.cn/Article/details/gt2leqdfopq.html

[E13] 逐字符遍历
来源：http://dali.dianchejie.cn/Article/details/gt2tlfimzak.html

Py:   for ch in s: print(ch)
来源：http://dali.yongpay.top/Article/details/gt2duszivja.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jbuzpyoh.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tian-w.cn/Article/details/gt2nmtbtuyt.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shuidangran.top/Article/details/gt2xwahjrol.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cywogvbc.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kaudbxml.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.snrcjt.cn/Article/details/gt2jtrqsbqf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jianghu66.top/Article/details/gt2moieopmg.html

[E14] URL 编码与 Base64
来源：http://dali.jlsjyb.cn/Article/details/gt2gjhptkfd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ppjwa.cn/Article/details/gt2askejcaz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.daxiang520.top/Article/details/gt2dhuoqllf.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.tanke756.top/Article/details/gt2uknydsuw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yvedp.cn/Article/details/gt2qjibweal.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shzxlz.cn/Article/details/gt2prlqujpl.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nzmaumif.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sweek.top/Article/details/gt2evybyavl.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.kuanghao11.cn/Article/details/gt2cawaszld.html

[E15] HTML 转义 / 反转义
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cvfzgpek.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cashguo.top/Article/details/gt2eyqjnylt.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kzyhijmm.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhengqikj.top/Article/details/gt2tcekvgwk.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.nwbrower.top/Article/details/gt2fbtjrkgu.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hywenlv.cn/Article/details/gt2rmgdjfqu.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjssqdvr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cheryme.top/Article/details/gt2ekunoltz.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sysykeji.top/Article/details/gt2vrmsclxt.html

[E16] 数字千分位
来源：http://dali.nwbrower.top/Article/details/gt2uclvlpsp.html

Py:   f"{1234567:,}"
来源：http://dali.nanxinkj.top/Article/details/gt2rzgbnkpo.html

PHP:  number_format(1234567);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hipxizfx.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hfpthk.cn/Article/details/gt2ybyydour.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ydzc1.top/Article/details/gt2gxygziwm.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.bjfxy.top/Article/details/gt2bqzwrjij.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yueranfly.top/Article/details/gt2szcguqig.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hysaishi.cn/Article/details/gt2svjythvo.html

C#:   1234567.ToString("N0")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ocpeesid.html

[E17] 首字母大写
来源：http://dali.guannengcc.top/Article/details/gt2gghumquu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.tian-w.cn/Article/details/gt2jpnxekch.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yj20258888.top/Article/details/gt2qmnyqpwt.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daria6918.cn/Article/details/gt2uvhdpxvw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xhjbshys.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.dianchejie.cn/Article/details/gt2haimvnfz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.pycfn.com/Article/details/gt2nwsqiugm.html

Ruby: s.capitalize
来源：http://dali.ehwqpu.com/Article/details/gt2jjozpzbc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ybcxt.top/Article/details/gt2dueisacs.html


<!-- 参考信息 -->