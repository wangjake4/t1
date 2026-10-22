代发 wailian999

TS:   [...new Set(arr)]
来源：http://dali.jqgfzy.top/Article/details/gt2unrnshnz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xuanzx.com/Article/details/gt2vqjjuqzu.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yj202588.top/Article/details/gt2htxbnlbw.html

Ruby: arr.uniq
来源：http://dali.yj20258888.top/Article/details/gt2kyqnmtnh.html

C#:   list.Distinct().ToList()
来源：http://dali.tanke756.top/Article/details/gt2aegaaaet.html

[D16] 求和与平均值
来源：http://dali.iojbl.cn/Article/details/gt2ekdwtbjr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ydavctpr.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mnpxjkky.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj20258.top/Article/details/gt2kwmdmadq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.c1oappe.top/Article/details/gt2qdwxwlxx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rytabovl.html

Go:   // 手写循环累加
来源：http://dali.hnxiangtu.top/Article/details/gt2lnxlsbtr.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.havefunace.top/Article/details/gt2dpqpllru.html

C#:   list.Sum();  list.Average()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rciqvqgt.html

[D17] 最大值与最小值
来源：http://dali.zhixingplan.top/Article/details/gt2oibqxhzp.html

Py:   max(arr);  min(arr)
来源：http://dali.tanke756.top/Article/details/gt2pqkelmkb.html

PHP:  max($arr);  min($arr);
来源：http://dali.gzhubu.top/Article/details/gt2lprhaujm.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.fzhhl.top/Article/details/gt2micblatu.html

TS:   Math.max(...arr);
来源：http://dali.ehwqpu.com/Article/details/gt2xkittvdc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.vqdsnc.cn/Article/details/gt2mefzfwpw.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xylfe.cn/Article/details/gt2nzpszfnh.html

Ruby: arr.max;  arr.min
来源：http://dali.9152youxi.cn/Article/details/gt2voekzcxo.html

C#:   list.Max();  list.Min()
来源：http://dali.fzhhl.top/Article/details/gt2cdfjhiov.html

[D18] 扁平化嵌套数组
来源：http://dali.aizwys.cn/Article/details/gt2voextzme.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.aibaodan.cn/Article/details/gt2ezcbhmpy.html

PHP:  array_merge(...$nested);
来源：http://dali.xuetiantiany.cn/Article/details/gt2owzezouo.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jinqigfzy.top/Article/details/gt2tmncpbwl.html

TS:   nested.flat();
来源：http://dali.hywenlv.cn/Article/details/gt2trcktoys.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.smart0.xyz/Article/details/gt2pfmjfexl.html

Go:   // 手写双层循环
来源：http://dali.gotoacloud.top/Article/details/gt2bbafscgb.html

Ruby: nested.flatten
来源：http://dali.jinqigfzy.top/Article/details/gt2hfcjyccs.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zycfv.cn/Article/details/gt2norhurlh.html

[D19] 按字段分组
来源：http://dali.jinqigfzy.top/Article/details/gt2rlaardsn.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zdqjudy.top/Article/details/gt2sivymlyb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.vqdsnc.cn/Article/details/gt2njhyzgdw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.andypj.xyz/Article/details/gt2zyqevyip.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.guowangkeji.top/Article/details/gt2gpqtdxhs.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.pycfn.com/Article/details/gt2ystfdtxf.html

Go:   // 手写 map[string][]T
来源：http://dali.jqgufenzy.top/Article/details/gt2cxkcsapw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.feifeiyinyue.top/Article/details/gt2nhgsikle.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yangfankeji.com/Article/details/gt2usbyopgh.html

[D20] 统计每个元素出现次数
来源：http://dali.jiagoushi.top/Article/details/gt2yucbhnre.html

Py:   Counter(arr)
来源：http://dali.iojbl.cn/Article/details/gt2iqgahami.html

PHP:  array_count_values($arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2epzleqoc.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xuetiantiany.cn/Article/details/gt2ahultfay.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenzaomai.com/Article/details/gt2gtzxpqor.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.nanxuanxn.top/Article/details/gt2psmxtudt.html

Go:   // 手写 map[T]int
来源：http://dali.jianghu66.top/Article/details/gt2blawdmhw.html

Ruby: arr.tally
来源：http://dali.ivvv.top/Article/details/gt2cgteqpbq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.haohaochexian.top/Article/details/gt2qobbuoqw.html

[D21] 判断是否包含某元素
来源：http://dali.vqdsnc.cn/Article/details/gt2rgkvzkrq.html

Py:   x in arr
来源：http://dali.cdnleiting.top/Article/details/gt2blpfdmln.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gogol.net.cn/Article/details/gt2lfayqhuo.html

JS:   arr.includes(x)
来源：http://dali.haohaochexian.top/Article/details/gt2mmcltghv.html

TS:   arr.includes(x)
来源：http://dali.c1oappe.top/Article/details/gt2dlzqmjwo.html

Java: list.contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2kndzkwnh.html

Go:   slices.Contains(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gt2khfemkjv.html

Ruby: arr.include?(x)
来源：http://dali.sysykeji.top/Article/details/gt2fxqgdcjg.html

C#:   list.Contains(x)
来源：http://dali.tian-w.cn/Article/details/gt2hoigwbea.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yonumen.top/Article/details/gt2ygikssyj.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jpcobkcp.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hysaishi.cn/Article/details/gt2kvsdcvna.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jjecphah.html

TS:   [...arr];
来源：http://dali.nanxuanxn.top/Article/details/gt2zlfqlgpf.html

Java: new ArrayList<>(list);
来源：http://dali.guowangkeji.top/Article/details/gt2xobiuoyc.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.haohaochexian.top/Article/details/gt2mceydipw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yj20258.top/Article/details/gt2vktcggdn.html

C#:   new List<int>(list);
来源：http://dali.jqgufenzy.top/Article/details/gt2xtkcctqd.html

[D23] reduce 累积计算
来源：http://dali.jqgufenzy.top/Article/details/gt2bvfqvuzh.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hnxiangtu.top/Article/details/gt2rrcrzuxs.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhengqikj.top/Article/details/gt2ecqhtruk.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shzxlz.cn/Article/details/gt2ztcmaatk.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hfpthk.cn/Article/details/gt2koctpiav.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shangyingyoupin.top/Article/details/gt2cjdoowqk.html

Go:   // 手写循环
来源：http://dali.zhoulong.xyz/Article/details/gt2ltnghidz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.c1oappe.top/Article/details/gt2xiagbjsk.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.kuanghao11.cn/Article/details/gt2azksmbus.html

[D24] 字典 / Map 基本操作
来源：http://dali.dianchejie.cn/Article/details/gt2mpfjaiwp.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uscplbxw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.bjfxy.top/Article/details/gt2kqrivmmx.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rdbpkslv.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hfpthk.cn/Article/details/gt2iigtmigw.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yonumen.top/Article/details/gt2vqknaduo.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.smart0.xyz/Article/details/gt2mlazccvj.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.vqdsnc.cn/Article/details/gt2wjwohfyk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bwdotidq.html

[D25] Set 集合去重与交并差
来源：http://dali.iojbl.cn/Article/details/gt2uougtrgw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hnqzz.top/Article/details/gt2mfodpeur.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.wangdashe.top/Article/details/gt2tjpcvjjh.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hysaishi.cn/Article/details/gt2jwlzbltg.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.nanxuanxn.top/Article/details/gt2znswwjao.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yongpay.top/Article/details/gt2qaikbnfx.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.gogol.net.cn/Article/details/gt2xtntrzyy.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.tian-w.cn/Article/details/gt2xxxkksny.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.havefunace.top/Article/details/gt2uokollva.html

[D26] 数组转字符串
来源：http://dali.nwbrower.top/Article/details/gt2yqgberrb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yvedp.cn/Article/details/gt2oyqrhogd.html

PHP:  implode(", ", $arr);
来源：http://dali.hammf.cn/Article/details/gt2pvpomdun.html

JS:   arr.join(", ")
来源：http://dali.sxryk.cn/Article/details/gt2tebbawhb.html

TS:   arr.join(", ")
来源：http://dali.shuidangran.top/Article/details/gt2juxirwas.html

Java: String.join(", ", list)
来源：http://dali.zhongyouzk.top/Article/details/gt2tjlzlkso.html

Go:   strings.Join(strs, ", ")
来源：http://dali.iojbl.cn/Article/details/gt2klhuiddf.html

Ruby: arr.join(", ")
来源：http://dali.shuidangran.top/Article/details/gt2hsrpcaco.html

C#:   string.Join(", ", list)
来源：http://dali.snrcjt.cn/Article/details/gt2ysgpxgmn.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2dchghqzg.html

E. 字符串处理
来源：http://dali.smart0.xyz/Article/details/gt2vohcqxac.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2fekxfbng.html

[E01] 拼接字符串
来源：http://dali.yj20258888.top/Article/details/gt2ddkxonrg.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.meibo888.top/Article/details/gt2krharysi.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.tianlin.xyz/Article/details/gt2fqppbjru.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ubefmvjh.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.fengsongda.top/Article/details/gt2kbbwqgyr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xuanzx.com/Article/details/gt2lbtzvdns.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.aibaodan.cn/Article/details/gt2hmqofkpb.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xuanzx.com/Article/details/gt2ohjcrpar.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gt2obnkiwlp.html

[E02] 重复字符串
来源：http://dali.daxiang520.top/Article/details/gt2xjnzobgh.html

Py:   "ab" * 3
来源：http://dali.ehwqpu.com/Article/details/gt2cawxlbqn.html

PHP:  str_repeat("ab", 3);
来源：http://dali.kuanghao11.cn/Article/details/gt2qtctsrrw.html

JS:   "ab".repeat(3)
来源：http://dali.zhongyouzk.top/Article/details/gt2tlnonyli.html

TS:   "ab".repeat(3)
来源：http://dali.guowangkeji.top/Article/details/gt2racsznij.html

Java: "ab".repeat(3)
来源：http://dali.chenlongwang.top/Article/details/gt2mxwgqmjj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jqgufenzy.top/Article/details/gt2ajzxegtp.html

Ruby: "ab" * 3
来源：http://dali.zhengqikj.top/Article/details/gt2eqluefof.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xylfe.cn/Article/details/gt2xtmjkygn.html

[E03] 截取子串
来源：http://dali.meibo888.top/Article/details/gt2vbermxso.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.dianchejie.cn/Article/details/gt2cxmbjqpp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gt2edfxwfwz.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ehwqpu.com/Article/details/gt2yryndsek.html

TS:   s.slice(1, 4)
来源：http://dali.hfpthk.cn/Article/details/gt2kcbnijgz.html

Java: s.substring(1, 4)
来源：http://dali.hfpthk.cn/Article/details/gt2jvsetqim.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yongpay.top/Article/details/gt2ilrljowf.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xylfe.cn/Article/details/gt2reoeyqrq.html

C#:   s.Substring(1, 3)
来源：http://dali.yueranfly.top/Article/details/gt2qjsobpfy.html

[E04] 查找子串位置
来源：http://dali.jyoumei.cn/Article/details/gt2zszrxftw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.andypj.xyz/Article/details/gt2czexbtht.html

PHP:  strpos($s, "x");
来源：http://dali.gzhubu.top/Article/details/gt2jqmfklgg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.gogol.net.cn/Article/details/gt2yqcpcrgx.html

TS:   s.indexOf("x")
来源：http://dali.havefunace.top/Article/details/gt2peqgqhlu.html

Java: s.indexOf("x")
来源：http://dali.fengsongda.top/Article/details/gt2wgkbgwew.html

Go:   strings.Index(s, "x")
来源：http://dali.xylfe.cn/Article/details/gt2cnmpmrao.html

Ruby: s.index("x")
来源：http://dali.iojbl.cn/Article/details/gt2tslnujkf.html

C#:   s.IndexOf("x")
来源：http://dali.zhiwuduotai.top/Article/details/gt2xccukhrh.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.fengsongda.top/Article/details/gt2zbzzficw.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.aibaodan.cn/Article/details/gt2dvybvrnw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinqigfzy.top/Article/details/gt2csxouolr.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nwbrower.top/Article/details/gt2jardjiig.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shuidangran.top/Article/details/gt2galgjigd.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj202588.top/Article/details/gt2zrmskwur.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.chenjidiqi.icu/Article/details/gt2kirnbvao.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.dianchejie.cn/Article/details/gt2gctxfcjq.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.tian-w.cn/Article/details/gt2qwzzqizl.html

[E06] 替换子串
来源：http://dali.yongpay.top/Article/details/gt2cbwvcgjs.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yueranfly.top/Article/details/gt2kwrikroi.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.snrcjt.cn/Article/details/gt2uswqbhzh.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yonumen.top/Article/details/gt2fpgrmbul.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gt2cpkppjkr.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.birdmap.top/Article/details/gt2eylyobtp.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zycfv.cn/Article/details/gt2qgqxjpqf.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gt2whyuwuma.html

C#:   s.Replace("a", "b")
来源：http://dali.c1oappe.top/Article/details/gt2zddlljzb.html

[E07] 按分隔符拆分
来源：http://dali.hnxiangtu.top/Article/details/gt2jpxwugdi.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xuetiantiany.cn/Article/details/gt2ebwajmms.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shuidangran.top/Article/details/gt2eiknyihd.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.fengsongda.top/Article/details/gt2cphanggy.html

TS:   s.split(",")
来源：http://dali.tian-w.cn/Article/details/gt2qdxhuulc.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.sysykeji.top/Article/details/gt2oxadhdce.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.dianchejie.cn/Article/details/gt2fuonqhos.html

Ruby: s.split(",");  s.split
来源：http://dali.quarkkingdee.top/Article/details/gt2twgslklw.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.pycfn.com/Article/details/gt2rftzogvt.html

[E08] 数组按分隔符合并
来源：http://dali.guannengcc.top/Article/details/gt2lchyjets.html

Py:   ",".join(items)
来源：http://dali.fengsongda.top/Article/details/gt2uufidhxz.html

PHP:  implode(",", $items);
来源：http://dali.sxryk.cn/Article/details/gt2qunvhlmm.html

JS:   items.join(",")
来源：http://dali.sysykeji.top/Article/details/gt2khcjules.html

TS:   items.join(",")
来源：http://dali.shangyingyoupin.top/Article/details/gt2rodcmsoc.html

Java: String.join(",", items)
来源：http://dali.vqdsnc.cn/Article/details/gt2slvmgmqm.html

Go:   strings.Join(items, ",")
来源：http://dali.chenjidiqi.icu/Article/details/gt2khmqueso.html

Ruby: items.join(",")
来源：http://dali.svipenyu.cn/Article/details/gt2ecuvqcke.html

C#:   string.Join(",", items)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2htichmxn.html

[E09] 去除所有空白字符
来源：http://dali.cucudq.cn/Article/details/gt2wimvvhhh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jqgufenzy.top/Article/details/gt2aviiyzeo.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xziqi.cn/Article/details/gt2equluwwl.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.havefunace.top/Article/details/gt2govfmtev.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.0kj1m.cn/Article/details/gt2oxeamdrg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhiwuduotai.top/Article/details/gt2aechzuut.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zycfv.cn/Article/details/gt2epjpljmp.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ewikefud.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.sysykeji.top/Article/details/gt2mlgalyuh.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhoulong.xyz/Article/details/gt2uabtnevm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.birdmap.top/Article/details/gt2vxacdylj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ivvv.top/Article/details/gt2ntsyvbou.html

JS:   "7".padStart(3, "0")
来源：http://dali.jyoumei.cn/Article/details/gt2ekdnauoh.html

TS:   "7".padStart(3, "0")
来源：http://dali.jqgfzy.top/Article/details/gt2adcihbpw.html

Java: String.format("%03d", 7)
来源：http://dali.c1oappe.top/Article/details/gt2nsaneevb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hammf.cn/Article/details/gt2alrcijpy.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.chenzaomai.com/Article/details/gt2sbgehiwa.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ydzc1.top/Article/details/gt2aewqxeun.html

[E11] 反转字符串
来源：http://dali.daria6918.cn/Article/details/gt2kfwwapmr.html

Py:   s[::-1]
来源：http://dali.smart0.xyz/Article/details/gt2xmrjrbmg.html

PHP:  strrev($s);
来源：http://dali.xziqi.cn/Article/details/gt2fpvtzqsr.html

JS:   [...s].reverse().join("")
来源：http://dali.cheryme.top/Article/details/gt2yuxycpet.html

TS:   [...s].reverse().join("")
来源：http://dali.zhiwuduotai.top/Article/details/gt2wbkofyqo.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xziqi.cn/Article/details/gt2ajbqywvt.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.dianchejie.cn/Article/details/gt2ktiomxjh.html

Ruby: s.reverse
来源：http://dali.zhongyouzk.top/Article/details/gt2wbbargec.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yanxiufei.cn/Article/details/gt2bdtahdtr.html

[E12] 统计某字符出现次数
来源：http://dali.gotoacloud.top/Article/details/gt2pvxvskko.html

Py:   s.count("a")
来源：http://dali.jyoumei.cn/Article/details/gt2vxoasdyl.html

PHP:  substr_count($s, "a");
来源：http://dali.gotoacloud.top/Article/details/gt2rsaflsrz.html

JS:   s.split("a").length - 1
来源：http://dali.hnxiangtu.top/Article/details/gt2rogrielu.html

TS:   s.split("a").length - 1
来源：http://dali.xylfe.cn/Article/details/gt2nrbecwqp.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhiwuduotai.top/Article/details/gt2kvnnglbq.html

Go:   strings.Count(s, "a")
来源：http://dali.tanke756.top/Article/details/gt2uewklmtx.html

Ruby: s.count("a")
来源：http://dali.havefunace.top/Article/details/gt2xitrujve.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yongpay.top/Article/details/gt2avkcuvqv.html

[E13] 逐字符遍历
来源：http://dali.yvedp.cn/Article/details/gt2zixyjvgn.html

Py:   for ch in s: print(ch)
来源：http://dali.xuetiantiany.cn/Article/details/gt2htwtocyl.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yuxming.cn/Article/details/gt2zflcqzms.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lxkrtehz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sxryk.cn/Article/details/gt2qvaflwci.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jyoumei.cn/Article/details/gt2lkmpzixp.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xuetiantiany.cn/Article/details/gt2gftrnlcs.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ludcgboh.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.wangdashe.top/Article/details/gt2emzxarwu.html

[E14] URL 编码与 Base64
来源：http://dali.xuanzx.com/Article/details/gt2ldihckqc.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.nwbrower.top/Article/details/gt2xtqjxqes.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.havefunace.top/Article/details/gt2idzlyxll.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ybcxt.top/Article/details/gt2wjhahvdo.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2xnozcpah.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jyoumei.cn/Article/details/gt2dnaneraw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ehwqpu.com/Article/details/gt2vluoajji.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wjzaettf.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.snrcjt.cn/Article/details/gt2pmwiifgd.html

[E15] HTML 转义 / 反转义
来源：http://dali.smart0.xyz/Article/details/gt2aeubygyp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gzubgtpl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ehwqpu.com/Article/details/gt2afgfxmwx.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.chenlongwang.top/Article/details/gt2jlancpvn.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cashguo.top/Article/details/gt2caktblur.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.gotoacloud.top/Article/details/gt2swoxqnkx.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.haohaochexian.top/Article/details/gt2rugbeskk.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.dianchejie.cn/Article/details/gt2exjefeje.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2npwyhfxj.html

[E16] 数字千分位
来源：http://dali.tianlin.xyz/Article/details/gt2fiewsddz.html

Py:   f"{1234567:,}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cdekrqyf.html

PHP:  number_format(1234567);
来源：http://dali.svipenyu.cn/Article/details/gt2fpdoktmo.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ydzc1.top/Article/details/gt2nwroculj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yueranfly.top/Article/details/gt2lubymexh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.sxryk.cn/Article/details/gt2lwqnbkdm.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.wangshuangyany.cn/Article/details/gt2ycrvhcpv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jlsjyb.cn/Article/details/gt2qiebhfwi.html

C#:   1234567.ToString("N0")
来源：http://dali.smart0.xyz/Article/details/gt2pkqlfmvq.html

[E17] 首字母大写
来源：http://dali.gogol.net.cn/Article/details/gt2dahnhfdj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hfpthk.cn/Article/details/gt2wulnqzyr.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yanxiufei.cn/Article/details/gt2mbabnhbd.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zcbnnclb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.haohaochexian.top/Article/details/gt2nvenbczv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2akoeslrg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jyoumei.cn/Article/details/gt2zlyftmxk.html

Ruby: s.capitalize
来源：http://dali.ivvv.top/Article/details/gt2pzoqhaza.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cbrzbxqj.html

[E18] 模板占位符替换
来源：http://dali.redwolf501.top/Article/details/gt2atafiemb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.tanke756.top/Article/details/gt2kebcpaqn.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.vqdsnc.cn/Article/details/gt2crctrvsq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhoulong.xyz/Article/details/gt2ljihgkrx.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gt2smfhjhnm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yueranfly.top/Article/details/gt2ttxzmkdw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gt2vweyabef.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.gotoacloud.top/Article/details/gt2hbtqgfsk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jlsjyb.cn/Article/details/gt2dzdxyzzh.html

[E19] 多行文本按行拆分
来源：http://dali.zhixingplan.top/Article/details/gt2qliartuk.html

Py:   s.splitlines()
来源：http://dali.jianghu66.top/Article/details/gt2ssrqmrlg.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2czhbeqpn.html

JS:   s.split(/\r?\n/)
来源：http://dali.ehwqpu.com/Article/details/gt2gokuulbh.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2howosvny.html

Java: s.lines().toList()
来源：http://dali.nwbrower.top/Article/details/gt2mmyxdryo.html

Go:   strings.Split(s, "\n")
来源：http://dali.jqgfzy.top/Article/details/gt2jhrjrjxz.html

Ruby: s.lines
来源：http://dali.shuidangran.top/Article/details/gt2skemdwcx.html

C#:   s.Split('\n')
来源：http://dali.ppjwa.cn/Article/details/gt2emometmx.html

[E20] 判断字符串是否为空
来源：http://dali.sweek.top/Article/details/gt2mqtgzdni.html

Py:   if not s:
来源：http://dali.hnqzz.top/Article/details/gt2gsnmwesc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.tianlin.xyz/Article/details/gt2uzxowlvr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ydzc1.top/Article/details/gt2gcduoogc.html

TS:   if (s === "") {}
来源：http://dali.pycfn.com/Article/details/gt2pmugtbgi.html

Java: if (s.isEmpty()) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2skznesnd.html

Go:   if s == "" {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ytwfcote.html

Ruby: if s.empty?
来源：http://dali.yongpay.top/Article/details/gt2ymnidesw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yj202588.top/Article/details/gt2eucsbaez.html

[E21] 超长截断加省略号
来源：http://dali.yonumen.top/Article/details/gt2wjlrosua.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.kuanghao11.cn/Article/details/gt2ycfbyzdr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hywenlv.cn/Article/details/gt2qkykygxo.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hnqzz.top/Article/details/gt2twhjzbie.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daria6918.cn/Article/details/gt2ivwdlrfp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gt2yjpgebgo.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xziqi.cn/Article/details/gt2tpgsapml.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gt2sjegqryv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uugnjwfm.html

[E22] 字节长度与字符长度
来源：http://dali.yongpay.top/Article/details/gt2ghkgjnee.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.haohaochexian.top/Article/details/gt2otecrbzm.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangdashe.top/Article/details/gt2jevqdyzm.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xinyue.icu/Article/details/gt2dnnvhflv.html


<!-- 参考信息 -->