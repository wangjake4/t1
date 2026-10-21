代发 wailian999

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yueranfly.top/Article/details/gtmxvmpgub.html

Go:   // 手写循环
来源：http://dali.cheryme.top/Article/details/gtrngvfigt.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.nwbrower.top/Article/details/gtxvmsfasf.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hysaishi.cn/Article/details/gtsnlbfdtv.html

[D15] 去重
来源：http://dali.ehwqpu.com/Article/details/gtoyodzker.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpimtwtdp.html

PHP:  array_unique($arr);
来源：http://dali.nanxinkj.top/Article/details/gtnlpglsch.html

JS:   [...new Set(arr)]
来源：http://dali.daxiang520.top/Article/details/gtdxsfnlpu.html

TS:   [...new Set(arr)]
来源：http://dali.andypj.xyz/Article/details/gteqrzhoha.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sufxvd.cn/Article/details/gtqlqfmzxh.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xuanzx.com/Article/details/gtrwiotdve.html

Ruby: arr.uniq
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjlrigdto.html

C#:   list.Distinct().ToList()
来源：http://dali.smart0.xyz/Article/details/gtgygkcgvg.html

[D16] 求和与平均值
来源：http://dali.cucudq.cn/Article/details/gthohyuqrb.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhixingplan.top/Article/details/gtgfwlqcct.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtjmnjzsbq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtgyfiweqv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fengsongda.top/Article/details/gtjjdofkmk.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.guowangkeji.top/Article/details/gtmnaghluq.html

Go:   // 手写循环累加
来源：http://dali.zhiwuduotai.top/Article/details/gtwpopdwen.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cashguo.top/Article/details/gtmuadbqov.html

C#:   list.Sum();  list.Average()
来源：http://dali.hfpthk.cn/Article/details/gtbknlwiax.html

[D17] 最大值与最小值
来源：http://dali.nwbrower.top/Article/details/gtpvvedrln.html

Py:   max(arr);  min(arr)
来源：http://dali.andypj.xyz/Article/details/gtpqshlcmi.html

PHP:  max($arr);  min($arr);
来源：http://dali.ehwqpu.com/Article/details/gtghnztbce.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gtrlbsyndo.html

TS:   Math.max(...arr);
来源：http://dali.haohaochexian.top/Article/details/gtvlmtpwbk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.chenjidiqi.icu/Article/details/gtkhfogqzm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sufxvd.cn/Article/details/gtikgaciob.html

Ruby: arr.max;  arr.min
来源：http://dali.shuidangran.top/Article/details/gterjsdeqc.html

C#:   list.Max();  list.Min()
来源：http://dali.zhengqikj.top/Article/details/gtfhxmunul.html

[D18] 扁平化嵌套数组
来源：http://dali.jinqigufen.top/Article/details/gtnqucyqwn.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.birdmap.top/Article/details/gtnbthofgb.html

PHP:  array_merge(...$nested);
来源：http://dali.316326.xyz/Article/details/gttlipbize.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.chenzaomai.com/Article/details/gtmlfmiezg.html

TS:   nested.flat();
来源：http://dali.yvedp.cn/Article/details/gtiuhnfady.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.redwolf501.top/Article/details/gtxswdykzq.html

Go:   // 手写双层循环
来源：http://dali.jyoumei.cn/Article/details/gtcjdyhckg.html

Ruby: nested.flatten
来源：http://dali.bjfxy.top/Article/details/gtrrmcwvys.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shzxlz.cn/Article/details/gtuthekdfh.html

[D19] 按字段分组
来源：http://dali.9152youxi.cn/Article/details/gtavkrhrii.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkrfliebm.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.pengpengdd.cyou/Article/details/gttallwpda.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.chenjidiqi.icu/Article/details/gturgrqnda.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhongyouzk.top/Article/details/gtmfyzdzyd.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.wangdashe.top/Article/details/gtcfofvtmd.html

Go:   // 手写 map[string][]T
来源：http://dali.gogol.net.cn/Article/details/gtwnsjzjnk.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hfpthk.cn/Article/details/gtumgnorkh.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.smart0.xyz/Article/details/gtcfvashsf.html

[D20] 统计每个元素出现次数
来源：http://dali.9152youxi.cn/Article/details/gtbemsqdrz.html

Py:   Counter(arr)
来源：http://dali.jinqigfzy.top/Article/details/gthmlzihcm.html

PHP:  array_count_values($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtrfkshbtu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yonumen.top/Article/details/gtwnjlecyy.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gtflwtyjpd.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.tian-w.cn/Article/details/gtqenknqen.html

Go:   // 手写 map[T]int
来源：http://dali.hysaishi.cn/Article/details/gtguyglrgb.html

Ruby: arr.tally
来源：http://dali.cdnleiting.top/Article/details/gtxmcccdwm.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gtvkttjbcv.html

[D21] 判断是否包含某元素
来源：http://dali.c1oappe.top/Article/details/gttbmmekht.html

Py:   x in arr
来源：http://dali.c1oappe.top/Article/details/gtmzhcplll.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ydzc1.top/Article/details/gtaxzbefzn.html

JS:   arr.includes(x)
来源：http://dali.zdqjudy.top/Article/details/gtkjeosahn.html

TS:   arr.includes(x)
来源：http://dali.aizwys.cn/Article/details/gtjqzipmof.html

Java: list.contains(x)
来源：http://dali.hysaishi.cn/Article/details/gtspkpynsw.html

Go:   slices.Contains(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gtxupxenmn.html

Ruby: arr.include?(x)
来源：http://dali.tian-w.cn/Article/details/gtwdyvklpu.html

C#:   list.Contains(x)
来源：http://dali.shuidangran.top/Article/details/gtubojgdbf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.nanxinkj.top/Article/details/gtxvkqxmet.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jqgfzy.top/Article/details/gtjbuqwiwl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.aibaodan.cn/Article/details/gtywwemakl.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jyoumei.cn/Article/details/gtnetsckqj.html

TS:   [...arr];
来源：http://dali.svipenyu.cn/Article/details/gtmsouxvcn.html

Java: new ArrayList<>(list);
来源：http://dali.hysaishi.cn/Article/details/gtsyflmzsv.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.kuanghao11.cn/Article/details/gtdksihgtp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jlsjyb.cn/Article/details/gtrmgznfce.html

C#:   new List<int>(list);
来源：http://dali.bjfxy.top/Article/details/gtrahcrccd.html

[D23] reduce 累积计算
来源：http://dali.cdnleiting.top/Article/details/gtlxkazkfb.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.snrcjt.cn/Article/details/gtttqgfbyc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.sysykeji.top/Article/details/gtzmqcpezl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xziqi.cn/Article/details/gturbhukrs.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiwfilhvj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yuanzhike.top/Article/details/gtxtiyiqsu.html

Go:   // 手写循环
来源：http://dali.wangdashe.top/Article/details/gtndixzfho.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcrexbngh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cucudq.cn/Article/details/gtmucvfvvp.html

[D24] 字典 / Map 基本操作
来源：http://dali.jlsjyb.cn/Article/details/gtdiyrbafn.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hammf.cn/Article/details/gttfskjkmv.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xylfe.cn/Article/details/gtrfyybzmg.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cucudq.cn/Article/details/gtpvfzvmxk.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtvwclukqm.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.chenjidiqi.icu/Article/details/gtdattcdxg.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.bjfxy.top/Article/details/gtbxduogjc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jinghuilouyu.cn/Article/details/gterdirfgg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhengqikj.top/Article/details/gtchrotaqp.html

[D25] Set 集合去重与交并差
来源：http://dali.ehwqpu.com/Article/details/gtfoouswve.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zycfv.cn/Article/details/gtptcielhk.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.havefunace.top/Article/details/gtbdopzdbx.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtbzbqzndo.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.tanke756.top/Article/details/gtfzskkxjc.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdttbrrvh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.chenzaomai.com/Article/details/gtxsfojcav.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jyoumei.cn/Article/details/gtfoqycest.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jyoumei.cn/Article/details/gtdlinxqjl.html

[D26] 数组转字符串
来源：http://dali.svipenyu.cn/Article/details/gtneihulje.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hysaishi.cn/Article/details/gtxekkkcih.html

PHP:  implode(", ", $arr);
来源：http://dali.guannengcc.top/Article/details/gtrxgajyhd.html

JS:   arr.join(", ")
来源：http://dali.ehwqpu.com/Article/details/gtqyccygff.html

TS:   arr.join(", ")
来源：http://dali.aibaodan.cn/Article/details/gtgneadejk.html

Java: String.join(", ", list)
来源：http://dali.yvedp.cn/Article/details/gtbszaeqlu.html

Go:   strings.Join(strs, ", ")
来源：http://dali.gogol.net.cn/Article/details/gthemnfzgq.html

Ruby: arr.join(", ")
来源：http://dali.fengsongda.top/Article/details/gtzzrsjodq.html

C#:   string.Join(", ", list)
来源：http://dali.yj202588.top/Article/details/gtbyrhhxbp.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtuzdostps.html

E. 字符串处理
来源：http://dali.nanxuanxn.top/Article/details/gtoxspcauf.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtaeikfpsy.html

[E01] 拼接字符串
来源：http://dali.andypj.xyz/Article/details/gtzhpaosgm.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ydzc1.top/Article/details/gtqhnywpwt.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ivvv.top/Article/details/gtbmhjvmim.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.dianchejie.cn/Article/details/gtjgttdwbl.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.pycfn.com/Article/details/gtsyhmvklb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.sxryk.cn/Article/details/gtrascqvvf.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.daria6918.cn/Article/details/gtkjmytxog.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuepyoatt.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.c1oappe.top/Article/details/gtfrhakhxd.html

[E02] 重复字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtanepolci.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gtxubdwxir.html

PHP:  str_repeat("ab", 3);
来源：http://dali.nanxuanxn.top/Article/details/gtxtpjqfyw.html

JS:   "ab".repeat(3)
来源：http://dali.9152youxi.cn/Article/details/gtmdhcorhv.html

TS:   "ab".repeat(3)
来源：http://dali.meibo888.top/Article/details/gtgnfuwofk.html

Java: "ab".repeat(3)
来源：http://dali.aizwys.cn/Article/details/gtqnegolxd.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtnpbafybe.html

Ruby: "ab" * 3
来源：http://dali.aibaodan.cn/Article/details/gtpeeybgzk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.tian-w.cn/Article/details/gtcxossfmn.html

[E03] 截取子串
来源：http://dali.gogol.net.cn/Article/details/gtlhvueeir.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hongshengwenyu.top/Article/details/gtsdnovzlc.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gtrhsynrho.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.haohaochexian.top/Article/details/gtdhvbbdle.html

TS:   s.slice(1, 4)
来源：http://dali.ehwqpu.com/Article/details/gtpzamqvmz.html

Java: s.substring(1, 4)
来源：http://dali.jqgufenzy.top/Article/details/gtpbdkdqzz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.haohaochexian.top/Article/details/gtbioyqiqi.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.svipenyu.cn/Article/details/gthxhegoad.html

C#:   s.Substring(1, 3)
来源：http://dali.ppjwa.cn/Article/details/gtuvacicig.html

[E04] 查找子串位置
来源：http://dali.316326.xyz/Article/details/gtzkczkpio.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yongpay.top/Article/details/gtvhlanixj.html

PHP:  strpos($s, "x");
来源：http://dali.quarkkingdee.top/Article/details/gtxrrnjpwj.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.quarkkingdee.top/Article/details/gtuyycbjfe.html

TS:   s.indexOf("x")
来源：http://dali.cheryme.top/Article/details/gtbktbsxit.html

Java: s.indexOf("x")
来源：http://dali.feifeiyinyue.top/Article/details/gtdgrskgnm.html

Go:   strings.Index(s, "x")
来源：http://dali.hywenlv.cn/Article/details/gtujywwvpi.html

Ruby: s.index("x")
来源：http://dali.gotoacloud.top/Article/details/gtpmujrjak.html

C#:   s.IndexOf("x")
来源：http://dali.daria6918.cn/Article/details/gtesdeuedm.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cdnleiting.top/Article/details/gtnvnbweha.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.daria6918.cn/Article/details/gtsveanmzw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.bjfxy.top/Article/details/gterrnpcez.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hysaishi.cn/Article/details/gtatnlspqz.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkbayqnmt.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuxming.cn/Article/details/gtqieomvdv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.feifeiyinyue.top/Article/details/gtqaxsyqul.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gtbscyawke.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yj202588.top/Article/details/gtuirlpwjq.html

[E06] 替换子串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtetldgxmh.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.vqdsnc.cn/Article/details/gtwciczssl.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.sxryk.cn/Article/details/gtovaoogiv.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gtqgnscngp.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gtmtjtgroy.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hnqzz.top/Article/details/gtfoiruqkh.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.nanxinkj.top/Article/details/gtcedxwvgn.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yongpay.top/Article/details/gtqnhjnloz.html

C#:   s.Replace("a", "b")
来源：http://dali.ivvv.top/Article/details/gtsvbiykhe.html

[E07] 按分隔符拆分
来源：http://dali.meibo888.top/Article/details/gtzhroykmb.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yueranfly.top/Article/details/gtbgflotua.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtxubokugu.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shzxlz.cn/Article/details/gthdspmdhh.html

TS:   s.split(",")
来源：http://dali.havefunace.top/Article/details/gtrkbopqnn.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhengqikj.top/Article/details/gtexbcfrvh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.fzhhl.top/Article/details/gtdjldkbos.html

Ruby: s.split(",");  s.split
来源：http://dali.nanxinkj.top/Article/details/gtllfnimsk.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.pycfn.com/Article/details/gtlwcyroaa.html

[E08] 数组按分隔符合并
来源：http://dali.bjfxy.top/Article/details/gtpfeuqwcx.html

Py:   ",".join(items)
来源：http://dali.xuetiantiany.cn/Article/details/gtrbkfvfur.html

PHP:  implode(",", $items);
来源：http://dali.pycfn.com/Article/details/gtuhikwima.html

JS:   items.join(",")
来源：http://dali.mhx1999.top/Article/details/gtzdjzzkbd.html

TS:   items.join(",")
来源：http://dali.tian-w.cn/Article/details/gtlvmrpuxq.html

Java: String.join(",", items)
来源：http://dali.yj202588.top/Article/details/gtxummliot.html

Go:   strings.Join(items, ",")
来源：http://dali.daxiang520.top/Article/details/gtszhyuvlb.html

Ruby: items.join(",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtltwaspjw.html

C#:   string.Join(",", items)
来源：http://dali.ivvv.top/Article/details/gtbgomsayo.html

[E09] 去除所有空白字符
来源：http://dali.daxiang520.top/Article/details/gttpdasjys.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.quarkkingdee.top/Article/details/gtlfpyexra.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.havefunace.top/Article/details/gtxdxbhxyv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hysaishi.cn/Article/details/gthliihtld.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yongpay.top/Article/details/gtogndqbmp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.nwbrower.top/Article/details/gtvjntvyvn.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.redwolf501.top/Article/details/gtvnmvhxat.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.dashuyun.cn/Article/details/gtdkuczujs.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jiagoushi.top/Article/details/gtgptfqnrh.html

[E10] 左侧补零 / 定长填充
来源：http://dali.guowangkeji.top/Article/details/gtxeihjnsc.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.meibo888.top/Article/details/gtkwmwndjr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbedcpggj.html

JS:   "7".padStart(3, "0")
来源：http://dali.haohaochexian.top/Article/details/gtyogkppyl.html

TS:   "7".padStart(3, "0")
来源：http://dali.xylfe.cn/Article/details/gtggotyrdl.html

Java: String.format("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gtgmocpars.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gtfejpewdx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yj20258888.top/Article/details/gtvoaknpvn.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.tianlin.xyz/Article/details/gtnobynais.html

[E11] 反转字符串
来源：http://dali.yuxming.cn/Article/details/gtumgmersp.html

Py:   s[::-1]
来源：http://dali.haohaochexian.top/Article/details/gtzqqosych.html

PHP:  strrev($s);
来源：http://dali.guannengcc.top/Article/details/gtdiymsgki.html

JS:   [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gtwfjbgumq.html

TS:   [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gtkpiywrac.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.chenzaomai.com/Article/details/gtphiaggjt.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hongshengwenyu.top/Article/details/gtjaxhqngw.html

Ruby: s.reverse
来源：http://dali.bjfxy.top/Article/details/gtqhiojwmz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hywenlv.cn/Article/details/gtarghimtw.html

[E12] 统计某字符出现次数
来源：http://dali.cheryme.top/Article/details/gtnfrssfts.html

Py:   s.count("a")
来源：http://dali.nanxinkj.top/Article/details/gtukgsaxzt.html

PHP:  substr_count($s, "a");
来源：http://dali.jlsjyb.cn/Article/details/gtnsfhzlmq.html

JS:   s.split("a").length - 1
来源：http://dali.iojbl.cn/Article/details/gtoriytlkr.html

TS:   s.split("a").length - 1
来源：http://dali.yuanzhike.top/Article/details/gtcwmjchil.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhongyouzk.top/Article/details/gtxnwruubr.html

Go:   strings.Count(s, "a")
来源：http://dali.dianchejie.cn/Article/details/gtmzobvkfg.html

Ruby: s.count("a")
来源：http://dali.jqgfzy.top/Article/details/gtqafohcdp.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yj202588.top/Article/details/gtqizjrgcj.html

[E13] 逐字符遍历
来源：http://dali.zhijiandao.cn/Article/details/gtojfdyykn.html

Py:   for ch in s: print(ch)
来源：http://dali.birdmap.top/Article/details/gtdckqrqbl.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cdnleiting.top/Article/details/gtptkthpna.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gogol.net.cn/Article/details/gtecmsgvxp.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtipqwrkbf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gtebhfnwdy.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ivvv.top/Article/details/gttbwmkmtx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nanxuanxn.top/Article/details/gtdmavpynm.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yongpay.top/Article/details/gtqqzxryot.html

[E14] URL 编码与 Base64
来源：http://dali.xuanzx.com/Article/details/gtzvdpfsnj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sweek.top/Article/details/gtkggkqani.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hfpthk.cn/Article/details/gtgyjcdqmg.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhengqikj.top/Article/details/gtdrxniztv.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.svipenyu.cn/Article/details/gtidsilvjr.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gtttjptgyr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.nanxuanxn.top/Article/details/gtljavzljn.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.wangdashe.top/Article/details/gtvgmshpvo.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.9152youxi.cn/Article/details/gtpnezexia.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhongyouzk.top/Article/details/gtiujabjoi.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.chenzaomai.com/Article/details/gtahhxeqwc.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.chenzaomai.com/Article/details/gtssdfzdqu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sxryk.cn/Article/details/gtlxvudzfm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuyqzmqko.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xuetiantiany.cn/Article/details/gtfyfwngey.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhiwuduotai.top/Article/details/gthpcikuch.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cqqwz.cn/Article/details/gtehmpereo.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhoulong.xyz/Article/details/gtdkgjretg.html

[E16] 数字千分位
来源：http://dali.jyoumei.cn/Article/details/gtqmpdyvqk.html

Py:   f"{1234567:,}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtemwrtdsh.html

PHP:  number_format(1234567);
来源：http://dali.xuetiantiany.cn/Article/details/gtqlqwuqvb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.guowangkeji.top/Article/details/gtgujqjubt.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hfpthk.cn/Article/details/gtzulatgvu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hywenlv.cn/Article/details/gtkasoftxg.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yonumen.top/Article/details/gtygokwtim.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shuidangran.top/Article/details/gtlwckmrga.html

C#:   1234567.ToString("N0")
来源：http://dali.chenlongwang.top/Article/details/gtuoycrqju.html

[E17] 首字母大写
来源：http://dali.hysaishi.cn/Article/details/gtgemddmxv.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gotoacloud.top/Article/details/gtmlzkdhqh.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhoulong.xyz/Article/details/gthshsuobn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.kuanghao11.cn/Article/details/gtrlxvgemm.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ppjwa.cn/Article/details/gttvpaqgkv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shzxlz.cn/Article/details/gtlbedhtzi.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.quarkkingdee.top/Article/details/gtkttpjfhn.html

Ruby: s.capitalize
来源：http://dali.shzxlz.cn/Article/details/gtdgvfpaek.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shanyushiyangtech.top/Article/details/gtwhyukjum.html

[E18] 模板占位符替换
来源：http://dali.nwbrower.top/Article/details/gtanvjfmez.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yvedp.cn/Article/details/gtxwznetwc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.tanke756.top/Article/details/gtojjplkzm.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zycfv.cn/Article/details/gtnyidxsst.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gtekymnuwh.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ydzc1.top/Article/details/gtpksozixx.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.c1oappe.top/Article/details/gtbwwbuyon.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yj202588.top/Article/details/gtpshkptvw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.nanxuanxn.top/Article/details/gttbjwhnuk.html

[E19] 多行文本按行拆分
来源：http://dali.ybcxt.top/Article/details/gtkqmzcejb.html

Py:   s.splitlines()
来源：http://dali.yj20258888.top/Article/details/gtbicianpy.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.nwbrower.top/Article/details/gtqkmeeoex.html

JS:   s.split(/\r?\n/)
来源：http://dali.pengpengdd.cyou/Article/details/gttffxwczx.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhoulong.xyz/Article/details/gttxblqnds.html

Java: s.lines().toList()
来源：http://dali.chenlongwang.top/Article/details/gtjidodxfk.html

Go:   strings.Split(s, "\n")
来源：http://dali.ybcxt.top/Article/details/gthbrxbcwq.html

Ruby: s.lines
来源：http://dali.jianghu66.top/Article/details/gtvlbuoqxp.html

C#:   s.Split('\n')
来源：http://dali.sufxvd.cn/Article/details/gtzewvrdog.html

[E20] 判断字符串是否为空
来源：http://dali.ehwqpu.com/Article/details/gthqmchzno.html

Py:   if not s:
来源：http://dali.andypj.xyz/Article/details/gtmpvgeomw.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.sxryk.cn/Article/details/gtznrotbgk.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hywenlv.cn/Article/details/gtjhyrtfmv.html

TS:   if (s === "") {}
来源：http://dali.jlsjyb.cn/Article/details/gttgbxwsvt.html

Java: if (s.isEmpty()) {}
来源：http://dali.gogol.net.cn/Article/details/gtcqgqieyf.html

Go:   if s == "" {}
来源：http://dali.xinyue.icu/Article/details/gtefvlrocm.html

Ruby: if s.empty?
来源：http://dali.hfpthk.cn/Article/details/gtmsxbqgjr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sweek.top/Article/details/gthueprnym.html

[E21] 超长截断加省略号
来源：http://dali.iojbl.cn/Article/details/gtraclnbjh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cqqwz.cn/Article/details/gtolxydygc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gtbcteerxl.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hammf.cn/Article/details/gtxgfgclcq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shuidangran.top/Article/details/gtgqyokpxz.html


<!-- 参考信息 -->