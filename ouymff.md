代发 wailian999

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yj20258888.top/Article/details/gtoxoifxpx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zdqjudy.top/Article/details/gtomltekho.html

TS:   arr.filter(x => x > 3)
来源：http://dali.chenlongwang.top/Article/details/gttmcxfgha.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xylfe.cn/Article/details/gtmsvfoncy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.dianchejie.cn/Article/details/gtlttixodm.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yangfankeji.com/Article/details/gtcmocpmnf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhengqikj.top/Article/details/gtehmcwoav.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cdnleiting.top/Article/details/gtdazzygbf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.wangdashe.top/Article/details/gtxbxayhvk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xylfe.cn/Article/details/gtlkvyqakw.html

JS:   arr.map(x => x * 2)
来源：http://dali.dianchejie.cn/Article/details/gtcgidvfmb.html

TS:   arr.map(x => x * 2)
来源：http://dali.jlsjyb.cn/Article/details/gtbskneyyf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlrvmpvrw.html

Go:   // 手写循环
来源：http://dali.iojbl.cn/Article/details/gtnfmvshrr.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.gogol.net.cn/Article/details/gtbkyjqbbx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yangfankeji.com/Article/details/gtitcnwkph.html

[D15] 去重
来源：http://dali.ivvv.top/Article/details/gtvhfmtdfk.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.andypj.xyz/Article/details/gtlbbnylfe.html

PHP:  array_unique($arr);
来源：http://dali.hnqzz.top/Article/details/gtwpszsbak.html

JS:   [...new Set(arr)]
来源：http://dali.xziqi.cn/Article/details/gtruagnvyf.html

TS:   [...new Set(arr)]
来源：http://dali.jlsjyb.cn/Article/details/gtnsdfizih.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yj202588.top/Article/details/gttxczbhxe.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yj202588.top/Article/details/gtqaixuyxb.html

Ruby: arr.uniq
来源：http://dali.birdmap.top/Article/details/gtojevdplo.html

C#:   list.Distinct().ToList()
来源：http://dali.ydzc1.top/Article/details/gtajftunxu.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gtmaahhdet.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xziqi.cn/Article/details/gtbslsccwn.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.tanke756.top/Article/details/gthaxybpld.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.wangdashe.top/Article/details/gthoxrwmmk.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jiagoushi.top/Article/details/gtxeruremt.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ivvv.top/Article/details/gteahybqvk.html

Go:   // 手写循环累加
来源：http://dali.yueranfly.top/Article/details/gtrcecrwbl.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.dianchejie.cn/Article/details/gtgcoosvfr.html

C#:   list.Sum();  list.Average()
来源：http://dali.c1oappe.top/Article/details/gthhgabfvu.html

[D17] 最大值与最小值
来源：http://dali.yvedp.cn/Article/details/gtslosqfag.html

Py:   max(arr);  min(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtdpycqxyy.html

PHP:  max($arr);  min($arr);
来源：http://dali.sxryk.cn/Article/details/gtisqezsyr.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtgfxzbsic.html

TS:   Math.max(...arr);
来源：http://dali.cqqwz.cn/Article/details/gtnlcmpffu.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shzxlz.cn/Article/details/gtstpvubcq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.smart0.xyz/Article/details/gtzipduzgn.html

Ruby: arr.max;  arr.min
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlhtpmrll.html

C#:   list.Max();  list.Min()
来源：http://dali.yueranfly.top/Article/details/gtbforfctk.html

[D18] 扁平化嵌套数组
来源：http://dali.nwbrower.top/Article/details/gttsefhsxy.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ehwqpu.com/Article/details/gthxnjjfaf.html

PHP:  array_merge(...$nested);
来源：http://dali.nanxuanxn.top/Article/details/gtgpbzancg.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yangfankeji.com/Article/details/gtaiyxjmch.html

TS:   nested.flat();
来源：http://dali.gogol.net.cn/Article/details/gtrrzlcwhm.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtocohgomv.html

Go:   // 手写双层循环
来源：http://dali.birdmap.top/Article/details/gttciyjcqi.html

Ruby: nested.flatten
来源：http://dali.cqqwz.cn/Article/details/gtrlixdhah.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shuidangran.top/Article/details/gtftpeuzye.html

[D19] 按字段分组
来源：http://dali.shangyingyoupin.top/Article/details/gthmdbvojr.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cheryme.top/Article/details/gtnifdeiab.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.wangdashe.top/Article/details/gtxkfnbiod.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.smart0.xyz/Article/details/gtitqueocb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yuxming.cn/Article/details/gtvbhyorqz.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yvedp.cn/Article/details/gtrlbpccmo.html

Go:   // 手写 map[string][]T
来源：http://dali.yangfankeji.com/Article/details/gtuihpdnoh.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yangfankeji.com/Article/details/gtznlckkpr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.guannengcc.top/Article/details/gtgjlwbwjh.html

[D20] 统计每个元素出现次数
来源：http://dali.hongshengwenyu.top/Article/details/gtccnltrux.html

Py:   Counter(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnyhfjsqd.html

PHP:  array_count_values($arr);
来源：http://dali.tianlin.xyz/Article/details/gtbujvbplx.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xziqi.cn/Article/details/gtsdxelbjr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.daria6918.cn/Article/details/gtkhstyxip.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xuanzx.com/Article/details/gtyarlibzo.html

Go:   // 手写 map[T]int
来源：http://dali.xuetiantiany.cn/Article/details/gttsmdyoxm.html

Ruby: arr.tally
来源：http://dali.0kj1m.cn/Article/details/gtcoipmitm.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jlsjyb.cn/Article/details/gtjsbylaxx.html

[D21] 判断是否包含某元素
来源：http://dali.fengsongda.top/Article/details/gtckgwacxv.html

Py:   x in arr
来源：http://dali.jqgfzy.top/Article/details/gtelyvbbkr.html

PHP:  in_array($x, $arr, true);
来源：http://dali.dashuyun.cn/Article/details/gtchyeuknt.html

JS:   arr.includes(x)
来源：http://dali.cheryme.top/Article/details/gttyexitrw.html

TS:   arr.includes(x)
来源：http://dali.c1oappe.top/Article/details/gtmvxfwaec.html

Java: list.contains(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcwziytbh.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtpuudbkhg.html

Ruby: arr.include?(x)
来源：http://dali.daria6918.cn/Article/details/gtscbikpcm.html

C#:   list.Contains(x)
来源：http://dali.hnqzz.top/Article/details/gtbepwmzjb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinghuilouyu.cn/Article/details/gtfgislqnw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyfgncgjh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.mhx1999.top/Article/details/gtlyqwihed.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtkrsdwuhj.html

TS:   [...arr];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpnbrjiab.html

Java: new ArrayList<>(list);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuelbzdnr.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shuidangran.top/Article/details/gtqjgllslm.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jqgfzy.top/Article/details/gtsgbnhufv.html

C#:   new List<int>(list);
来源：http://dali.jyoumei.cn/Article/details/gtvizmpssb.html

[D23] reduce 累积计算
来源：http://dali.wangshuangyany.cn/Article/details/gtynjtyqzu.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxmqkkapz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.nwbrower.top/Article/details/gtvhemjtfp.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zycfv.cn/Article/details/gtztwuruoe.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yangfankeji.com/Article/details/gtjsczmaeg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hywenlv.cn/Article/details/gtbupkgbed.html

Go:   // 手写循环
来源：http://dali.cdnleiting.top/Article/details/gthsbecacq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ehwqpu.com/Article/details/gtwbxylzwv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.havefunace.top/Article/details/gtvemvsjya.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhongyouzk.top/Article/details/gtkvciytab.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yonumen.top/Article/details/gtmalticec.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.aibaodan.cn/Article/details/gttzekcydc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhoulong.xyz/Article/details/gtcbifrmux.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ehwqpu.com/Article/details/gtaybpbyum.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cashguo.top/Article/details/gtosylbmmm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yangfankeji.com/Article/details/gthkstnxpi.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jianghu66.top/Article/details/gtalozrzjt.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cucudq.cn/Article/details/gtxzfkgxdu.html

[D25] Set 集合去重与交并差
来源：http://dali.jinghuilouyu.cn/Article/details/gtxtdspasl.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hysaishi.cn/Article/details/gthmrsqagj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhengqikj.top/Article/details/gtgqixeawj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.guowangkeji.top/Article/details/gtdrcltjxd.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yvedp.cn/Article/details/gtdvskqlnu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.kuanghao11.cn/Article/details/gttxfvpdsd.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.guowangkeji.top/Article/details/gtysmqsqnq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.guannengcc.top/Article/details/gtxdjxtqhy.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jinqigfzy.top/Article/details/gtsjvluwua.html

[D26] 数组转字符串
来源：http://dali.cucudq.cn/Article/details/gtyipahpif.html

Py:   ", ".join(map(str, arr))
来源：http://dali.wangdashe.top/Article/details/gtiluoultg.html

PHP:  implode(", ", $arr);
来源：http://dali.yueranfly.top/Article/details/gtdfecymcm.html

JS:   arr.join(", ")
来源：http://dali.yuxming.cn/Article/details/gtvccdqxbm.html

TS:   arr.join(", ")
来源：http://dali.guannengcc.top/Article/details/gtivsvfzjp.html

Java: String.join(", ", list)
来源：http://dali.zdqjudy.top/Article/details/gtivtgbvvz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shanyushiyangtech.top/Article/details/gtybwefhbn.html

Ruby: arr.join(", ")
来源：http://dali.xylfe.cn/Article/details/gtsmykaout.html

C#:   string.Join(", ", list)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiztiyjul.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtsfkxplzp.html

E. 字符串处理
来源：http://dali.gotoacloud.top/Article/details/gtwwplzjru.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtqchmzkyp.html

[E01] 拼接字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtsbysesqu.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hfpthk.cn/Article/details/gtfvakjalv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhixingplan.top/Article/details/gtvoaqdjyg.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgprqcsjd.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhoulong.xyz/Article/details/gtjbalcihl.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhiwuduotai.top/Article/details/gtmtjbfqxp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.tian-w.cn/Article/details/gtxxlsxnsx.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.tianlin.xyz/Article/details/gtnghwtqtk.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gtcbcuxaya.html

[E02] 重复字符串
来源：http://dali.svipenyu.cn/Article/details/gttneqpdmm.html

Py:   "ab" * 3
来源：http://dali.0kj1m.cn/Article/details/gtbqroionn.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hysaishi.cn/Article/details/gteewumsyh.html

JS:   "ab".repeat(3)
来源：http://dali.sxryk.cn/Article/details/gthmayfcgn.html

TS:   "ab".repeat(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttqtoxmlh.html

Java: "ab".repeat(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtecdwhtmx.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.birdmap.top/Article/details/gtwaqoendp.html

Ruby: "ab" * 3
来源：http://dali.nanxinkj.top/Article/details/gtlqamvxan.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.chenzaomai.com/Article/details/gtfchankhi.html

[E03] 截取子串
来源：http://dali.jianghu66.top/Article/details/gtrgayvnit.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.smart0.xyz/Article/details/gtcfngoowz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jqgfzy.top/Article/details/gtcedohbuy.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yongpay.top/Article/details/gtnbklfolx.html

TS:   s.slice(1, 4)
来源：http://dali.shanyushiyangtech.top/Article/details/gtefdcgcsi.html

Java: s.substring(1, 4)
来源：http://dali.hysaishi.cn/Article/details/gtpsjmrrdx.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sysykeji.top/Article/details/gtjmbcglie.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.chenjidiqi.icu/Article/details/gtkqrmakox.html

C#:   s.Substring(1, 3)
来源：http://dali.fzhhl.top/Article/details/gtkgcvxnao.html

[E04] 查找子串位置
来源：http://dali.jinqigufen.top/Article/details/gtfvgzngum.html

Py:   s.find("x");  s.index("x")
来源：http://dali.nanxuanxn.top/Article/details/gtgnvosfoa.html

PHP:  strpos($s, "x");
来源：http://dali.jqgufenzy.top/Article/details/gtlhkvthmr.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xuanzx.com/Article/details/gtdlrvsdgq.html

TS:   s.indexOf("x")
来源：http://dali.yongpay.top/Article/details/gtnmavtxkg.html

Java: s.indexOf("x")
来源：http://dali.tian-w.cn/Article/details/gtsjilroir.html

Go:   strings.Index(s, "x")
来源：http://dali.meibo888.top/Article/details/gthksxvuhi.html

Ruby: s.index("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsrsiorfg.html

C#:   s.IndexOf("x")
来源：http://dali.zhongyouzk.top/Article/details/gthrlpldnu.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.meibo888.top/Article/details/gtowabkbbw.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.birdmap.top/Article/details/gtabocszde.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.havefunace.top/Article/details/gtnefgdkte.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gotoacloud.top/Article/details/gtllpdvxxw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.snrcjt.cn/Article/details/gtxthdrkjq.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yonumen.top/Article/details/gtkgolkpmf.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jqgufenzy.top/Article/details/gtnfoujqhp.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.meibo888.top/Article/details/gtgpittxuo.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ydzc1.top/Article/details/gtspicoigc.html

[E06] 替换子串
来源：http://dali.yueranfly.top/Article/details/gtggkitjcg.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.nanxuanxn.top/Article/details/gtofzqplna.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.smart0.xyz/Article/details/gtadjwinhq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gtytcnpnex.html

TS:   s.replaceAll("a", "b")
来源：http://dali.sysykeji.top/Article/details/gtadszfxxj.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gthlnegntx.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.fzhhl.top/Article/details/gtkgvzyynf.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gtqziwpqdt.html

C#:   s.Replace("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtivzylfwe.html

[E07] 按分隔符拆分
来源：http://dali.gaohongyu789.top/Article/details/gtdwdqdvku.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwnqphqmi.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtulxebvsw.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jianghu66.top/Article/details/gtpdnwfhgy.html

TS:   s.split(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gtacdsgiwl.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hysaishi.cn/Article/details/gtnyelipkw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yj20258.top/Article/details/gtlobfjmfx.html

Ruby: s.split(",");  s.split
来源：http://dali.meibo888.top/Article/details/gtiwccfpxk.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.gzhubu.top/Article/details/gtzxttcpfp.html

[E08] 数组按分隔符合并
来源：http://dali.jqgufenzy.top/Article/details/gtaljctqzu.html

Py:   ",".join(items)
来源：http://dali.aizwys.cn/Article/details/gtidopkarn.html

PHP:  implode(",", $items);
来源：http://dali.pengpengdd.cyou/Article/details/gtgzlxwoqu.html

JS:   items.join(",")
来源：http://dali.daria6918.cn/Article/details/gtzrdoxlph.html

TS:   items.join(",")
来源：http://dali.0kj1m.cn/Article/details/gtukyjhuip.html

Java: String.join(",", items)
来源：http://dali.shangyingyoupin.top/Article/details/gtoecjlwcw.html

Go:   strings.Join(items, ",")
来源：http://dali.guannengcc.top/Article/details/gtnbchtdnn.html

Ruby: items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gtonhhrbqm.html

C#:   string.Join(",", items)
来源：http://dali.wangshuangyany.cn/Article/details/gtvzrrvvzv.html

[E09] 去除所有空白字符
来源：http://dali.xinyue.icu/Article/details/gtltdqvqoh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.fzhhl.top/Article/details/gtthqjblvf.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ydzc1.top/Article/details/gtsfjlfkmf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.c1oappe.top/Article/details/gtausqczby.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hnxiangtu.top/Article/details/gtpecfjymd.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hnxiangtu.top/Article/details/gtazqkobxb.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.vqdsnc.cn/Article/details/gtlujmfena.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.fengsongda.top/Article/details/gtyqssdclr.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.svipenyu.cn/Article/details/gtlpczzgnz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gaohongyu789.top/Article/details/gthmwwroyk.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gtjrubylby.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xziqi.cn/Article/details/gtijoexwgu.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkpvofvjq.html

TS:   "7".padStart(3, "0")
来源：http://dali.c1oappe.top/Article/details/gtwchtkyyj.html

Java: String.format("%03d", 7)
来源：http://dali.shangyingyoupin.top/Article/details/gtqxakidjf.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cashguo.top/Article/details/gtmkqpevfl.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xziqi.cn/Article/details/gtxckybiih.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jqgufenzy.top/Article/details/gtdkalkqqz.html

[E11] 反转字符串
来源：http://dali.yvedp.cn/Article/details/gtpdeufjmi.html

Py:   s[::-1]
来源：http://dali.pycfn.com/Article/details/gtdytvtlvd.html

PHP:  strrev($s);
来源：http://dali.sweek.top/Article/details/gtjpxmylhi.html

JS:   [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gtjzeeesbu.html

TS:   [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gtulqciiqt.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jqgfzy.top/Article/details/gtkxywwcgt.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.fengsongda.top/Article/details/gtbmmsdfkm.html

Ruby: s.reverse
来源：http://dali.hywenlv.cn/Article/details/gtgqavmxcp.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jiagoushi.top/Article/details/gtgspkbvga.html

[E12] 统计某字符出现次数
来源：http://dali.vqdsnc.cn/Article/details/gtbaujyrja.html

Py:   s.count("a")
来源：http://dali.ivvv.top/Article/details/gtncnaplax.html

PHP:  substr_count($s, "a");
来源：http://dali.yj20258888.top/Article/details/gtnwsxnhbb.html

JS:   s.split("a").length - 1
来源：http://dali.xuetiantiany.cn/Article/details/gtpiqrluhk.html

TS:   s.split("a").length - 1
来源：http://dali.zycfv.cn/Article/details/gthjnizhpu.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.gotoacloud.top/Article/details/gtfklkhuhf.html

Go:   strings.Count(s, "a")
来源：http://dali.shanyushiyangtech.top/Article/details/gtpqkgmgpd.html

Ruby: s.count("a")
来源：http://dali.yongpay.top/Article/details/gtfqmffhsm.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yangfankeji.com/Article/details/gtzsvysqqg.html

[E13] 逐字符遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtehgskqvj.html

Py:   for ch in s: print(ch)
来源：http://dali.iojbl.cn/Article/details/gtrrmjqrgu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hywenlv.cn/Article/details/gtbmybgakc.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenzaomai.com/Article/details/gtwqdsetuv.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xylfe.cn/Article/details/gtingxcywi.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yj202588.top/Article/details/gtuuxhdznr.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.smart0.xyz/Article/details/gttvymvzqv.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xinyue.icu/Article/details/gtlhswrwfr.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.dianchejie.cn/Article/details/gtmtaiqxet.html

[E14] URL 编码与 Base64
来源：http://dali.aizwys.cn/Article/details/gtfhockgik.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.pengpengdd.cyou/Article/details/gttuhadoie.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.mhx1999.top/Article/details/gtmnxkhxzt.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.gzhubu.top/Article/details/gtvhblvqaa.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgfsjltnx.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.9152youxi.cn/Article/details/gtkpvryrul.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbjxvkyte.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shangyingyoupin.top/Article/details/gtkirsmunh.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.chenzaomai.com/Article/details/gthupcfuno.html

[E15] HTML 转义 / 反转义
来源：http://dali.jiagoushi.top/Article/details/gtgardtpow.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zdqjudy.top/Article/details/gtanbbubyt.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jyoumei.cn/Article/details/gtapijtvww.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ivvv.top/Article/details/gtsfmhjdnz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gtikbifnpn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cucudq.cn/Article/details/gtorsuilvx.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.c1oappe.top/Article/details/gtmzjnduzg.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtsqsxmbvy.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yuanzhike.top/Article/details/gtukemtccc.html

[E16] 数字千分位
来源：http://dali.yangfankeji.com/Article/details/gthbtwnhci.html

Py:   f"{1234567:,}"
来源：http://dali.mhx1999.top/Article/details/gtqshnfgzb.html

PHP:  number_format(1234567);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtagnkxwdy.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zycfv.cn/Article/details/gtqshtsyzg.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.9152youxi.cn/Article/details/gtomqxknrr.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdcoczhbu.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jqgufenzy.top/Article/details/gtmgaqjibm.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmgqwjlil.html

C#:   1234567.ToString("N0")
来源：http://dali.yangfankeji.com/Article/details/gtoyuisjpv.html

[E17] 首字母大写
来源：http://dali.gogol.net.cn/Article/details/gtrfososgi.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.andypj.xyz/Article/details/gtyfryyxme.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gaohongyu789.top/Article/details/gtffadelwp.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ppjwa.cn/Article/details/gthxaegrkf.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jlsjyb.cn/Article/details/gtjqnzqpdw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gotoacloud.top/Article/details/gtpwtcqevf.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hongshengwenyu.top/Article/details/gtfusubwvv.html

Ruby: s.capitalize
来源：http://dali.fengsongda.top/Article/details/gteywyyiik.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.0kj1m.cn/Article/details/gtpyxwowib.html

[E18] 模板占位符替换
来源：http://dali.yj20258.top/Article/details/gtrqlhholk.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.sweek.top/Article/details/gtjdiritxi.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.havefunace.top/Article/details/gtzmwchyfy.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwijubzdq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.guannengcc.top/Article/details/gtlwjhnhtu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gtubibaqom.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.iojbl.cn/Article/details/gtfmbzsqnv.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.smart0.xyz/Article/details/gtofcbavms.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hammf.cn/Article/details/gtijcznxal.html

[E19] 多行文本按行拆分
来源：http://dali.jinghuilouyu.cn/Article/details/gtaqsefqfz.html

Py:   s.splitlines()
来源：http://dali.sweek.top/Article/details/gtoxitehmm.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shzxlz.cn/Article/details/gtdsjjdfjz.html

JS:   s.split(/\r?\n/)
来源：http://dali.tian-w.cn/Article/details/gtlwuiirlo.html

TS:   s.split(/\r?\n/)
来源：http://dali.ppjwa.cn/Article/details/gttmlxbklp.html

Java: s.lines().toList()
来源：http://dali.daxiang520.top/Article/details/gtfencoivj.html

Go:   strings.Split(s, "\n")
来源：http://dali.svipenyu.cn/Article/details/gtzqkxbmiv.html

Ruby: s.lines
来源：http://dali.aibaodan.cn/Article/details/gttmlsagud.html

C#:   s.Split('\n')
来源：http://dali.zhixingplan.top/Article/details/gtklrkkfvg.html

[E20] 判断字符串是否为空
来源：http://dali.c1oappe.top/Article/details/gtfitjsyur.html

Py:   if not s:
来源：http://dali.havefunace.top/Article/details/gtwiotqsgu.html


<!-- 参考信息 -->