代发 wailian999

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cucudq.cn/Article/details/gtfsutdpgf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwowqfhyl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jinqigfzy.top/Article/details/gtugxvwfpv.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.gzhubu.top/Article/details/gtyesfdunb.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.sysykeji.top/Article/details/gtdukhbanz.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ehwqpu.com/Article/details/gtdomzhgzk.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hywenlv.cn/Article/details/gtqqqaxivk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hongshengwenyu.top/Article/details/gtavsrkogx.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.nwbrower.top/Article/details/gtwrerbsgt.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yj20258.top/Article/details/gtnngwggum.html

JS:   arr.map(x => x * 2)
来源：http://dali.aizwys.cn/Article/details/gttfuqojur.html

TS:   arr.map(x => x * 2)
来源：http://dali.daria6918.cn/Article/details/gtvssvampg.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.dashuyun.cn/Article/details/gtpwxkzbnu.html

Go:   // 手写循环
来源：http://dali.chenzaomai.com/Article/details/gteprblqjh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.birdmap.top/Article/details/gtkgczqizq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtosuzxrgt.html

[D15] 去重
来源：http://dali.xuanzx.com/Article/details/gtfqsefjwm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.tanke756.top/Article/details/gthhqcpzvf.html

PHP:  array_unique($arr);
来源：http://dali.yanxiufei.cn/Article/details/gttoydzhox.html

JS:   [...new Set(arr)]
来源：http://dali.guannengcc.top/Article/details/gtpovomofd.html

TS:   [...new Set(arr)]
来源：http://dali.yangfankeji.com/Article/details/gtwyisrdke.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jiagoushi.top/Article/details/gtiwhvueos.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.havefunace.top/Article/details/gtyxstpryw.html

Ruby: arr.uniq
来源：http://dali.hnqzz.top/Article/details/gtqytgcrxu.html

C#:   list.Distinct().ToList()
来源：http://dali.yongpay.top/Article/details/gtnmdehjph.html

[D16] 求和与平均值
来源：http://dali.hysaishi.cn/Article/details/gtkytchmob.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.wangdashe.top/Article/details/gttfofwpjq.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xylfe.cn/Article/details/gtbhplthwy.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhengqikj.top/Article/details/gtmmrdkbdy.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtasmrsbsa.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.mhx1999.top/Article/details/gtriwzhqzh.html

Go:   // 手写循环累加
来源：http://dali.shzxlz.cn/Article/details/gtzwxdjkiw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sufxvd.cn/Article/details/gtfeobwgpx.html

C#:   list.Sum();  list.Average()
来源：http://dali.cucudq.cn/Article/details/gtvegjjady.html

[D17] 最大值与最小值
来源：http://dali.ybcxt.top/Article/details/gtyurnlywk.html

Py:   max(arr);  min(arr)
来源：http://dali.ehwqpu.com/Article/details/gtxxvvzybe.html

PHP:  max($arr);  min($arr);
来源：http://dali.sysykeji.top/Article/details/gtrnwbrjlv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhoulong.xyz/Article/details/gtgosonixf.html

TS:   Math.max(...arr);
来源：http://dali.tanke756.top/Article/details/gtfhpcqrnu.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jlsjyb.cn/Article/details/gtflnvgmme.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.pycfn.com/Article/details/gtaexlxqas.html

Ruby: arr.max;  arr.min
来源：http://dali.pycfn.com/Article/details/gtfshtsdnn.html

C#:   list.Max();  list.Min()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbvpcupdl.html

[D18] 扁平化嵌套数组
来源：http://dali.hammf.cn/Article/details/gterhlhsgx.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cashguo.top/Article/details/gtkgnsxtqu.html

PHP:  array_merge(...$nested);
来源：http://dali.fzhhl.top/Article/details/gtqhqiumev.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.nanxuanxn.top/Article/details/gtbtezeozy.html

TS:   nested.flat();
来源：http://dali.daria6918.cn/Article/details/gtwaowluau.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yj20258.top/Article/details/gtvqrnzpfj.html

Go:   // 手写双层循环
来源：http://dali.yueranfly.top/Article/details/gtxlgmiivr.html

Ruby: nested.flatten
来源：http://dali.nanxinkj.top/Article/details/gtxiaylxnr.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gtimijqfqo.html

[D19] 按字段分组
来源：http://dali.chenlongwang.top/Article/details/gtupbhmftq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yuanzhike.top/Article/details/gtxvzkrdju.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdwrqfozm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yongpay.top/Article/details/gtdygloibv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.wangdashe.top/Article/details/gtisgxfjla.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cdnleiting.top/Article/details/gtwefyeqgv.html

Go:   // 手写 map[string][]T
来源：http://dali.nanxinkj.top/Article/details/gtxgjarxza.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlsgcuprb.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xylfe.cn/Article/details/gtbeyacmnv.html

[D20] 统计每个元素出现次数
来源：http://dali.cashguo.top/Article/details/gtpdxfiahc.html

Py:   Counter(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtwufnjsrb.html

PHP:  array_count_values($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtujnhriza.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yueranfly.top/Article/details/gtzcoauegd.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.wangshuangyany.cn/Article/details/gtvnjtqftx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sxryk.cn/Article/details/gtapcvznup.html

Go:   // 手写 map[T]int
来源：http://dali.nanxinkj.top/Article/details/gtyauirnwo.html

Ruby: arr.tally
来源：http://dali.yongpay.top/Article/details/gtctlxtxeq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cdnleiting.top/Article/details/gtljmauzuw.html

[D21] 判断是否包含某元素
来源：http://dali.nanxinkj.top/Article/details/gtusbsniwb.html

Py:   x in arr
来源：http://dali.fzhhl.top/Article/details/gtqdnroual.html

PHP:  in_array($x, $arr, true);
来源：http://dali.c1oappe.top/Article/details/gtzymdkkwl.html

JS:   arr.includes(x)
来源：http://dali.cucudq.cn/Article/details/gtwydahmjh.html

TS:   arr.includes(x)
来源：http://dali.sysykeji.top/Article/details/gtuxisoejc.html

Java: list.contains(x)
来源：http://dali.jlsjyb.cn/Article/details/gtiotirpue.html

Go:   slices.Contains(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gthkmwuljt.html

Ruby: arr.include?(x)
来源：http://dali.aizwys.cn/Article/details/gtcyoglwze.html

C#:   list.Contains(x)
来源：http://dali.hnqzz.top/Article/details/gtvvyosczv.html

[D22] 复制数组（避免共享引用）
来源：http://dali.svipenyu.cn/Article/details/gtglakwhpn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtbuxhxqqc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yanxiufei.cn/Article/details/gtsapnfivy.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jiagoushi.top/Article/details/gtiabrfuil.html

TS:   [...arr];
来源：http://dali.0kj1m.cn/Article/details/gtjptbbmno.html

Java: new ArrayList<>(list);
来源：http://dali.feifeiyinyue.top/Article/details/gtjurjknia.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cdnleiting.top/Article/details/gtrqstbfpy.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jinghuilouyu.cn/Article/details/gtstbehopz.html

C#:   new List<int>(list);
来源：http://dali.snrcjt.cn/Article/details/gtpxlpbzdx.html

[D23] reduce 累积计算
来源：http://dali.svipenyu.cn/Article/details/gtzxjfetqm.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yueranfly.top/Article/details/gtyjzsapvv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhoulong.xyz/Article/details/gtraewrsek.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yongpay.top/Article/details/gtnusvzhek.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zdqjudy.top/Article/details/gtxjxcylgr.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.quarkkingdee.top/Article/details/gtilgjttjy.html

Go:   // 手写循环
来源：http://dali.snrcjt.cn/Article/details/gtqyjkofaw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyuokjjhb.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ppjwa.cn/Article/details/gtwxhzhzsy.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhengqikj.top/Article/details/gtkmehbbnf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.sxryk.cn/Article/details/gtlhrrbroq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhiwuduotai.top/Article/details/gtlvsbvrgx.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.fengsongda.top/Article/details/gtqakkzjmu.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtuljozxqy.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.haohaochexian.top/Article/details/gtnjlajhsa.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhiwuduotai.top/Article/details/gtsovuglwx.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.wangshuangyany.cn/Article/details/gtxsmtniqr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.svipenyu.cn/Article/details/gtwvhevqpk.html

[D25] Set 集合去重与交并差
来源：http://dali.jyoumei.cn/Article/details/gtszdpaktq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yangfankeji.com/Article/details/gtpwrkewtz.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.sxryk.cn/Article/details/gtshdlzxak.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.svipenyu.cn/Article/details/gtojqtqjnz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.dashuyun.cn/Article/details/gtowwqopys.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.meibo888.top/Article/details/gtjltmshvw.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jqgufenzy.top/Article/details/gtyneprhhl.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jinqigufen.top/Article/details/gtkwqswgpx.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.c1oappe.top/Article/details/gtoplsvdzy.html

[D26] 数组转字符串
来源：http://dali.hnxiangtu.top/Article/details/gtumfiucyj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ehwqpu.com/Article/details/gtudstghtf.html

PHP:  implode(", ", $arr);
来源：http://dali.shuidangran.top/Article/details/gtlekinzat.html

JS:   arr.join(", ")
来源：http://dali.kuanghao11.cn/Article/details/gtgomkpupv.html

TS:   arr.join(", ")
来源：http://dali.haohaochexian.top/Article/details/gtfrkmzlwi.html

Java: String.join(", ", list)
来源：http://dali.ivvv.top/Article/details/gtzxurfpdd.html

Go:   strings.Join(strs, ", ")
来源：http://dali.kuanghao11.cn/Article/details/gtemoonkca.html

Ruby: arr.join(", ")
来源：http://dali.hywenlv.cn/Article/details/gtugjqnfhj.html

C#:   string.Join(", ", list)
来源：http://dali.shuidangran.top/Article/details/gtiivbhmmy.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtayzmamfm.html

E. 字符串处理
来源：http://dali.gzhubu.top/Article/details/gtrssdnadf.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gthlbvihcl.html

[E01] 拼接字符串
来源：http://dali.zhoulong.xyz/Article/details/gtpxukfbuu.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xinyue.icu/Article/details/gtudowauxq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.pycfn.com/Article/details/gtgsthggac.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sxryk.cn/Article/details/gtsxkinkkq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.vqdsnc.cn/Article/details/gtxtyvtzgh.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.aibaodan.cn/Article/details/gtbwurnikn.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jinqigfzy.top/Article/details/gtjbelnjun.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xziqi.cn/Article/details/gtheqdjuqo.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gtfjtpxnjg.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gtpuvjjtqq.html

Py:   "ab" * 3
来源：http://dali.cashguo.top/Article/details/gtfefplleu.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yueranfly.top/Article/details/gtqgzqzxmn.html

JS:   "ab".repeat(3)
来源：http://dali.xuanzx.com/Article/details/gtceeirytv.html

TS:   "ab".repeat(3)
来源：http://dali.kuanghao11.cn/Article/details/gtmlyrropj.html

Java: "ab".repeat(3)
来源：http://dali.9152youxi.cn/Article/details/gtmvejlwpn.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hnqzz.top/Article/details/gtoxgkexxo.html

Ruby: "ab" * 3
来源：http://dali.hysaishi.cn/Article/details/gtsjondtel.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ivvv.top/Article/details/gtqkywyxzu.html

[E03] 截取子串
来源：http://dali.daria6918.cn/Article/details/gtgglybbrg.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jinqigfzy.top/Article/details/gtilfjlxqu.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gtpyjonlje.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hnqzz.top/Article/details/gtzycqbhef.html

TS:   s.slice(1, 4)
来源：http://dali.sysykeji.top/Article/details/gtzbzkrbbb.html

Java: s.substring(1, 4)
来源：http://dali.yuanzhike.top/Article/details/gtckepfvkb.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gotoacloud.top/Article/details/gtrxoauann.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.pycfn.com/Article/details/gtzntzueed.html

C#:   s.Substring(1, 3)
来源：http://dali.fzhhl.top/Article/details/gtlzsozucf.html

[E04] 查找子串位置
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgcvrazvm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sysykeji.top/Article/details/gtpxbrjlmu.html

PHP:  strpos($s, "x");
来源：http://dali.jinqigfzy.top/Article/details/gttrkkqqey.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hysaishi.cn/Article/details/gtjcpqyzai.html

TS:   s.indexOf("x")
来源：http://dali.iojbl.cn/Article/details/gtzlffrelq.html

Java: s.indexOf("x")
来源：http://dali.hfpthk.cn/Article/details/gtrrksiybj.html

Go:   strings.Index(s, "x")
来源：http://dali.gzhubu.top/Article/details/gtxvhtxfjf.html

Ruby: s.index("x")
来源：http://dali.ppjwa.cn/Article/details/gtqlcpecov.html

C#:   s.IndexOf("x")
来源：http://dali.hnxiangtu.top/Article/details/gtwmxvwgzc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jinqigufen.top/Article/details/gtwqzbvqnc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hfpthk.cn/Article/details/gtmklolrhk.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.guowangkeji.top/Article/details/gtezbtjplt.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fengsongda.top/Article/details/gttnmduupn.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.aizwys.cn/Article/details/gtdplcvzzj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.quarkkingdee.top/Article/details/gtajeqgkhp.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.sysykeji.top/Article/details/gthtjxymel.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jqgufenzy.top/Article/details/gtauanastk.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.chenlongwang.top/Article/details/gtrylftgao.html

[E06] 替换子串
来源：http://dali.smart0.xyz/Article/details/gtoibwhhlz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jiagoushi.top/Article/details/gtzdgueqdk.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.chenlongwang.top/Article/details/gtrejblbth.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gtyuiwwyot.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cheryme.top/Article/details/gtzzubmfrs.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cucudq.cn/Article/details/gtjjwomhdc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtomciholq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gtsvhtyiza.html

C#:   s.Replace("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gtwyjhqzcq.html

[E07] 按分隔符拆分
来源：http://dali.svipenyu.cn/Article/details/gtwrttfcdk.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zdqjudy.top/Article/details/gtyhjhzdiw.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.chenzaomai.com/Article/details/gtmlggaahd.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.sysykeji.top/Article/details/gtmbszcfho.html

TS:   s.split(",")
来源：http://dali.xinyue.icu/Article/details/gtsfjduzav.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhiwuduotai.top/Article/details/gtlncpgkji.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.haohaochexian.top/Article/details/gtwcbzunkf.html

Ruby: s.split(",");  s.split
来源：http://dali.zhiwuduotai.top/Article/details/gtoefjokyw.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.guannengcc.top/Article/details/gtuwezewhu.html

[E08] 数组按分隔符合并
来源：http://dali.sweek.top/Article/details/gtysrcbnpq.html

Py:   ",".join(items)
来源：http://dali.cashguo.top/Article/details/gtpnpljpvi.html

PHP:  implode(",", $items);
来源：http://dali.gotoacloud.top/Article/details/gtpxofdmak.html

JS:   items.join(",")
来源：http://dali.chenlongwang.top/Article/details/gtfrdcnlvy.html

TS:   items.join(",")
来源：http://dali.redwolf501.top/Article/details/gtnlnqutem.html

Java: String.join(",", items)
来源：http://dali.yuanzhike.top/Article/details/gtfmglsemt.html

Go:   strings.Join(items, ",")
来源：http://dali.jqgufenzy.top/Article/details/gtkddjzhzp.html

Ruby: items.join(",")
来源：http://dali.yj20258888.top/Article/details/gtpbiaedkl.html

C#:   string.Join(",", items)
来源：http://dali.jinghuilouyu.cn/Article/details/gtznwiiubz.html

[E09] 去除所有空白字符
来源：http://dali.zhixingplan.top/Article/details/gtncjfphhi.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.tian-w.cn/Article/details/gtilvcjnct.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.sufxvd.cn/Article/details/gtafmtfhwd.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.chenlongwang.top/Article/details/gtpewjcnmi.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cucudq.cn/Article/details/gtkosouufi.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.316326.xyz/Article/details/gtwoczwimv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zdqjudy.top/Article/details/gtymceohwz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.316326.xyz/Article/details/gtosoubsvp.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.iojbl.cn/Article/details/gtbqbfskda.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ybcxt.top/Article/details/gtzlelltss.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sweek.top/Article/details/gttbjtuntp.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.birdmap.top/Article/details/gtsqcakoaw.html

JS:   "7".padStart(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gtrrjibivx.html

TS:   "7".padStart(3, "0")
来源：http://dali.zdqjudy.top/Article/details/gtljraafhh.html

Java: String.format("%03d", 7)
来源：http://dali.cdnleiting.top/Article/details/gthurgainu.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.quarkkingdee.top/Article/details/gthxjrlbis.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.dianchejie.cn/Article/details/gttbbajjnb.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yongpay.top/Article/details/gtwnzrxgyt.html

[E11] 反转字符串
来源：http://dali.c1oappe.top/Article/details/gtgbwfclox.html

Py:   s[::-1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbjvcjqiq.html

PHP:  strrev($s);
来源：http://dali.cucudq.cn/Article/details/gtekrwcnll.html

JS:   [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gtepfavzco.html

TS:   [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gtabneqwic.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hywenlv.cn/Article/details/gtdsbmownt.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xinyue.icu/Article/details/gtqmjxoivt.html

Ruby: s.reverse
来源：http://dali.hongshengwenyu.top/Article/details/gthuxlzado.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xinyue.icu/Article/details/gtqxomhcpt.html

[E12] 统计某字符出现次数
来源：http://dali.shzxlz.cn/Article/details/gtahmyvrcs.html

Py:   s.count("a")
来源：http://dali.redwolf501.top/Article/details/gtylidbspb.html

PHP:  substr_count($s, "a");
来源：http://dali.cucudq.cn/Article/details/gtgrukmnrh.html

JS:   s.split("a").length - 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrroonnpk.html

TS:   s.split("a").length - 1
来源：http://dali.aibaodan.cn/Article/details/gteaaaelfr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jqgfzy.top/Article/details/gtcyzkhvmq.html

Go:   strings.Count(s, "a")
来源：http://dali.jlsjyb.cn/Article/details/gtkjzxjmpp.html

Ruby: s.count("a")
来源：http://dali.fzhhl.top/Article/details/gtkjorjrtw.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yueranfly.top/Article/details/gtqycmijiw.html

[E13] 逐字符遍历
来源：http://dali.birdmap.top/Article/details/gtoxduqcig.html

Py:   for ch in s: print(ch)
来源：http://dali.pengpengdd.cyou/Article/details/gtitbduwyg.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.bjfxy.top/Article/details/gthaygxchg.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gogol.net.cn/Article/details/gtrujmhook.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj20258888.top/Article/details/gtjvytuhvr.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.sufxvd.cn/Article/details/gtigrfkkyc.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jlsjyb.cn/Article/details/gtovbgufcr.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpnobgugn.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cucudq.cn/Article/details/gtoscaeipi.html

[E14] URL 编码与 Base64
来源：http://dali.316326.xyz/Article/details/gttgzaaieh.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ydzc1.top/Article/details/gtdykyusxs.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.dianchejie.cn/Article/details/gtwlfddnct.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yj202588.top/Article/details/gtpmwltmte.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.chenzaomai.com/Article/details/gtvagwdmka.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yuxming.cn/Article/details/gthgrheojq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cashguo.top/Article/details/gtxnmkvxuy.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sufxvd.cn/Article/details/gtphqhkirq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.aibaodan.cn/Article/details/gtzpvmuwkr.html

[E15] HTML 转义 / 反转义
来源：http://dali.nanxuanxn.top/Article/details/gtqwcyxlln.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hammf.cn/Article/details/gtzxunfljk.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hfpthk.cn/Article/details/gthqrnfccz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hywenlv.cn/Article/details/gtobantaqa.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.wangshuangyany.cn/Article/details/gtlvebpwsa.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.0kj1m.cn/Article/details/gtngwrlksi.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.mhx1999.top/Article/details/gtaajccaob.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cdnleiting.top/Article/details/gtoutdgjiz.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hywenlv.cn/Article/details/gtrmjolvvi.html

[E16] 数字千分位
来源：http://dali.fengsongda.top/Article/details/gtukpvyhus.html

Py:   f"{1234567:,}"
来源：http://dali.iojbl.cn/Article/details/gtxoylezqo.html

PHP:  number_format(1234567);
来源：http://dali.chenjidiqi.icu/Article/details/gtepdxvtwc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzrmdlxei.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgfzy.top/Article/details/gtbetksjfg.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zdqjudy.top/Article/details/gtddhzbcmv.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gtkarkubcl.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.meibo888.top/Article/details/gtvglgerbh.html

C#:   1234567.ToString("N0")
来源：http://dali.sxryk.cn/Article/details/gtuljddbyt.html

[E17] 首字母大写
来源：http://dali.xinyue.icu/Article/details/gtfxjkwoqd.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.feifeiyinyue.top/Article/details/gtrlpjoxye.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jianghu66.top/Article/details/gtftuqbuuc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.bjfxy.top/Article/details/gtgclaswek.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhengqikj.top/Article/details/gtbtffcqnc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtadvscsyc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hammf.cn/Article/details/gttthtxskc.html

Ruby: s.capitalize
来源：http://dali.zycfv.cn/Article/details/gtzpmpvyyx.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.pycfn.com/Article/details/gteyihajsz.html

[E18] 模板占位符替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtmqcaxxjt.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvikinodd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.tian-w.cn/Article/details/gtjlwnywgz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gtzytogefq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gtilwcpjvx.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gtaufsvfgs.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gtdbuofrrt.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.birdmap.top/Article/details/gtrcfjntoh.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xuetiantiany.cn/Article/details/gtszlbepgh.html

[E19] 多行文本按行拆分
来源：http://dali.guannengcc.top/Article/details/gtioflinxl.html

Py:   s.splitlines()
来源：http://dali.yuanzhike.top/Article/details/gtmcgufwxd.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yuxming.cn/Article/details/gtizpayotu.html

JS:   s.split(/\r?\n/)
来源：http://dali.gogol.net.cn/Article/details/gtiemhhkrx.html

TS:   s.split(/\r?\n/)
来源：http://dali.aizwys.cn/Article/details/gtcvrfsztc.html

Java: s.lines().toList()
来源：http://dali.xuanzx.com/Article/details/gtmvgqrazt.html

Go:   strings.Split(s, "\n")
来源：http://dali.hnxiangtu.top/Article/details/gtjkibbhvl.html

Ruby: s.lines
来源：http://dali.sweek.top/Article/details/gtydbpfbty.html

C#:   s.Split('\n')
来源：http://dali.bjfxy.top/Article/details/gtoewfrrsw.html

[E20] 判断字符串是否为空
来源：http://dali.svipenyu.cn/Article/details/gtcffqyyqo.html

Py:   if not s:
来源：http://dali.chenjidiqi.icu/Article/details/gthnmhqboo.html


<!-- 参考信息 -->