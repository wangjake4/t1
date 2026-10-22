代发 wailian999

PHP:  max($arr);  min($arr);
来源：http://dali.havefunace.top/Article/details/gtnehlsrsy.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.nanxinkj.top/Article/details/gtciglfdwa.html

TS:   Math.max(...arr);
来源：http://dali.jqgufenzy.top/Article/details/gtseaockpi.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.kuanghao11.cn/Article/details/gtetrfgwlw.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjwooveqs.html

Ruby: arr.max;  arr.min
来源：http://dali.ppjwa.cn/Article/details/gthcthiofu.html

C#:   list.Max();  list.Min()
来源：http://dali.chenzaomai.com/Article/details/gtkhkchdrk.html

[D18] 扁平化嵌套数组
来源：http://dali.gzhubu.top/Article/details/gtmmhlgysm.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhongyouzk.top/Article/details/gtjuozyube.html

PHP:  array_merge(...$nested);
来源：http://dali.chenlongwang.top/Article/details/gtvnwalpkf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sweek.top/Article/details/gtvsmgnvfl.html

TS:   nested.flat();
来源：http://dali.cheryme.top/Article/details/gtyrqlyorg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jqgufenzy.top/Article/details/gtskdopwnd.html

Go:   // 手写双层循环
来源：http://dali.guannengcc.top/Article/details/gtsvqbicfl.html

Ruby: nested.flatten
来源：http://dali.gogol.net.cn/Article/details/gtfnmivrnp.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.redwolf501.top/Article/details/gtlddqfcbu.html

[D19] 按字段分组
来源：http://dali.chenlongwang.top/Article/details/gtsyggwcqw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sufxvd.cn/Article/details/gtwtyjzzrg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.c1oappe.top/Article/details/gtopwyufbb.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.dashuyun.cn/Article/details/gtqrgograv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.quarkkingdee.top/Article/details/gtyivlnhcv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jqgfzy.top/Article/details/gtarkmjyii.html

Go:   // 手写 map[string][]T
来源：http://dali.ivvv.top/Article/details/gtyrvlzhmn.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shanyushiyangtech.top/Article/details/gtrqiflvum.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ehwqpu.com/Article/details/gtkrxiwjuq.html

[D20] 统计每个元素出现次数
来源：http://dali.zhiwuduotai.top/Article/details/gtuvbwcpae.html

Py:   Counter(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtkldvnjyg.html

PHP:  array_count_values($arr);
来源：http://dali.hysaishi.cn/Article/details/gtbiziktkj.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nwbrower.top/Article/details/gtquvdgytb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cdnleiting.top/Article/details/gtwglkpygq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ydzc1.top/Article/details/gtdzawouwd.html

Go:   // 手写 map[T]int
来源：http://dali.xziqi.cn/Article/details/gtzdggtgug.html

Ruby: arr.tally
来源：http://dali.xziqi.cn/Article/details/gtmsmqpezs.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jiagoushi.top/Article/details/gtkjdbjpes.html

[D21] 判断是否包含某元素
来源：http://dali.kuanghao11.cn/Article/details/gtznskuafl.html

Py:   x in arr
来源：http://dali.iojbl.cn/Article/details/gtdwkdcgib.html

PHP:  in_array($x, $arr, true);
来源：http://dali.tianlin.xyz/Article/details/gtphsqlder.html

JS:   arr.includes(x)
来源：http://dali.hnqzz.top/Article/details/gtxgkegetd.html

TS:   arr.includes(x)
来源：http://dali.dashuyun.cn/Article/details/gtlehptavd.html

Java: list.contains(x)
来源：http://dali.sufxvd.cn/Article/details/gtjksumphp.html

Go:   slices.Contains(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtzywjhpmp.html

Ruby: arr.include?(x)
来源：http://dali.yueranfly.top/Article/details/gtlbgrtxhx.html

C#:   list.Contains(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqaxfnngx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.mhx1999.top/Article/details/gtgczyquwl.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtxhfmpjpi.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.nanxuanxn.top/Article/details/gtftzkblot.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jyoumei.cn/Article/details/gteklvyzks.html

TS:   [...arr];
来源：http://dali.hywenlv.cn/Article/details/gthtyaajis.html

Java: new ArrayList<>(list);
来源：http://dali.zdqjudy.top/Article/details/gtwcqjivhz.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.havefunace.top/Article/details/gtvauudngr.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hnxiangtu.top/Article/details/gtqjcgwksm.html

C#:   new List<int>(list);
来源：http://dali.xuanzx.com/Article/details/gtycopjebs.html

[D23] reduce 累积计算
来源：http://dali.nanxuanxn.top/Article/details/gttqmelyac.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.tianlin.xyz/Article/details/gtpnmlnnok.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yongpay.top/Article/details/gtiucyvciq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gogol.net.cn/Article/details/gtqbkrgpwx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yongpay.top/Article/details/gtfvzjdlzx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yanxiufei.cn/Article/details/gtewmjzdqv.html

Go:   // 手写循环
来源：http://dali.zhixingplan.top/Article/details/gtizderuxp.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.sxryk.cn/Article/details/gtdonlggqe.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.dianchejie.cn/Article/details/gtspfrjwbc.html

[D24] 字典 / Map 基本操作
来源：http://dali.mhx1999.top/Article/details/gtvavufljn.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.gaohongyu789.top/Article/details/gtqihndgnb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtciozglyk.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtzetgxgge.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.bjfxy.top/Article/details/gtatqrwmcs.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yj202588.top/Article/details/gtvooavkcj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cucudq.cn/Article/details/gtnlhsyetb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.pycfn.com/Article/details/gtkbgbulea.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jqgfzy.top/Article/details/gtsvehhkpo.html

[D25] Set 集合去重与交并差
来源：http://dali.yongpay.top/Article/details/gtkmrrsmtm.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zycfv.cn/Article/details/gttgctnkxw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hongshengwenyu.top/Article/details/gtihplpyen.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.aibaodan.cn/Article/details/gttgdmjiqt.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yueranfly.top/Article/details/gtqdtlrxnu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yvedp.cn/Article/details/gtlmhfgjsy.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.fzhhl.top/Article/details/gtblleswvv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cashguo.top/Article/details/gtwbzsqfmw.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.mhx1999.top/Article/details/gtrjctlaaw.html

[D26] 数组转字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtysjumuxy.html

Py:   ", ".join(map(str, arr))
来源：http://dali.gogol.net.cn/Article/details/gtgcjalzvc.html

PHP:  implode(", ", $arr);
来源：http://dali.zhongyouzk.top/Article/details/gtvwoyklmf.html

JS:   arr.join(", ")
来源：http://dali.kuanghao11.cn/Article/details/gtzaeiwzaq.html

TS:   arr.join(", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrbxexewm.html

Java: String.join(", ", list)
来源：http://dali.sysykeji.top/Article/details/gtlvuckwgy.html

Go:   strings.Join(strs, ", ")
来源：http://dali.gogol.net.cn/Article/details/gtacvzpnin.html

Ruby: arr.join(", ")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvzgewhbh.html

C#:   string.Join(", ", list)
来源：http://dali.zhoulong.xyz/Article/details/gtevgmjwko.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtopfshpeb.html

E. 字符串处理
来源：http://dali.nanxinkj.top/Article/details/gtpustdluz.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtbafveodn.html

[E01] 拼接字符串
来源：http://dali.zhongyouzk.top/Article/details/gtsoeregcu.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xylfe.cn/Article/details/gtqyddorem.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.quarkkingdee.top/Article/details/gtebubyien.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.haohaochexian.top/Article/details/gtygtsytzv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hfpthk.cn/Article/details/gtfrcdpuej.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ydzc1.top/Article/details/gtomwblscs.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.dianchejie.cn/Article/details/gtlajfxzkq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.andypj.xyz/Article/details/gtnkiucvpy.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.havefunace.top/Article/details/gttzbsijai.html

[E02] 重复字符串
来源：http://dali.yj202588.top/Article/details/gtfvfdwmiy.html

Py:   "ab" * 3
来源：http://dali.andypj.xyz/Article/details/gtseikelwi.html

PHP:  str_repeat("ab", 3);
来源：http://dali.dashuyun.cn/Article/details/gtayjoagec.html

JS:   "ab".repeat(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtchwtjbiz.html

TS:   "ab".repeat(3)
来源：http://dali.cashguo.top/Article/details/gttjinobdj.html

Java: "ab".repeat(3)
来源：http://dali.ybcxt.top/Article/details/gtbvlberxu.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.fzhhl.top/Article/details/gtdeslztik.html

Ruby: "ab" * 3
来源：http://dali.shanyushiyangtech.top/Article/details/gtjvvmekyk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jinyuanbaomall.cn/Article/details/gthkfowlij.html

[E03] 截取子串
来源：http://dali.chenzaomai.com/Article/details/gtyhdataoq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.gogol.net.cn/Article/details/gthuuqxpkn.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.smart0.xyz/Article/details/gtiptttxfx.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yj20258.top/Article/details/gtqenxrmfl.html

TS:   s.slice(1, 4)
来源：http://dali.jlsjyb.cn/Article/details/gtwwgvfbuc.html

Java: s.substring(1, 4)
来源：http://dali.cashguo.top/Article/details/gthpulmagp.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.haohaochexian.top/Article/details/gtnflkvfdm.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xylfe.cn/Article/details/gtkchwrrmt.html

C#:   s.Substring(1, 3)
来源：http://dali.ppjwa.cn/Article/details/gthwglbkwd.html

[E04] 查找子串位置
来源：http://dali.dashuyun.cn/Article/details/gtbnbeymij.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhongyouzk.top/Article/details/gtnjvzysnw.html

PHP:  strpos($s, "x");
来源：http://dali.feifeiyinyue.top/Article/details/gtfgbhimqg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yangfankeji.com/Article/details/gtvssclheb.html

TS:   s.indexOf("x")
来源：http://dali.gzhubu.top/Article/details/gtfnvqzros.html

Java: s.indexOf("x")
来源：http://dali.nanxinkj.top/Article/details/gtlcguoexq.html

Go:   strings.Index(s, "x")
来源：http://dali.jianghu66.top/Article/details/gtdiyyphcj.html

Ruby: s.index("x")
来源：http://dali.hnqzz.top/Article/details/gtakydltle.html

C#:   s.IndexOf("x")
来源：http://dali.xuanzx.com/Article/details/gtjdwstxgq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhiwuduotai.top/Article/details/gtxhoqguup.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.tanke756.top/Article/details/gtnjgidomc.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.quarkkingdee.top/Article/details/gtznnvruys.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhoulong.xyz/Article/details/gtnbwledrt.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.nwbrower.top/Article/details/gtnofxvdye.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cucudq.cn/Article/details/gtfzccywqh.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shuidangran.top/Article/details/gtfiminzlb.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbvwtrxze.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yueranfly.top/Article/details/gtgjltyuvv.html

[E06] 替换子串
来源：http://dali.sysykeji.top/Article/details/gtbxphjske.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhengqikj.top/Article/details/gtpofzdynk.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.dashuyun.cn/Article/details/gtdnryxvrz.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xinyue.icu/Article/details/gtaunvzdzs.html

TS:   s.replaceAll("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gtrtkajpoi.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gttrgoufnk.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ppjwa.cn/Article/details/gtrdoyjgye.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gtggrlhijh.html

C#:   s.Replace("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtlhdqgyjf.html

[E07] 按分隔符拆分
来源：http://dali.chenzaomai.com/Article/details/gtwddpgrsw.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.guannengcc.top/Article/details/gtbfjbfbbi.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtaflckfkr.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.316326.xyz/Article/details/gtyijifhyi.html

TS:   s.split(",")
来源：http://dali.yangfankeji.com/Article/details/gtcsozyfqi.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.iojbl.cn/Article/details/gtwlimzjqg.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.daxiang520.top/Article/details/gtwwticiqk.html

Ruby: s.split(",");  s.split
来源：http://dali.pycfn.com/Article/details/gtbtuxapxo.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xziqi.cn/Article/details/gtdtbthihr.html

[E08] 数组按分隔符合并
来源：http://dali.hnxiangtu.top/Article/details/gtxooqwslv.html

Py:   ",".join(items)
来源：http://dali.xuetiantiany.cn/Article/details/gtjgvypcok.html

PHP:  implode(",", $items);
来源：http://dali.sweek.top/Article/details/gtyclstldk.html

JS:   items.join(",")
来源：http://dali.9152youxi.cn/Article/details/gtsapifljl.html

TS:   items.join(",")
来源：http://dali.pengpengdd.cyou/Article/details/gtpisqhags.html

Java: String.join(",", items)
来源：http://dali.andypj.xyz/Article/details/gtcbjrkihn.html

Go:   strings.Join(items, ",")
来源：http://dali.feifeiyinyue.top/Article/details/gtwslbbsmu.html

Ruby: items.join(",")
来源：http://dali.chenjidiqi.icu/Article/details/gtzmslltcp.html

C#:   string.Join(",", items)
来源：http://dali.jiagoushi.top/Article/details/gtssdbpxvp.html

[E09] 去除所有空白字符
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzmxakhed.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yangfankeji.com/Article/details/gtmvmacdnt.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.wangdashe.top/Article/details/gtwgufzknj.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cdnleiting.top/Article/details/gteuwpcsqe.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ehwqpu.com/Article/details/gtuyophvbj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj202588.top/Article/details/gtwwfmyrel.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.wangshuangyany.cn/Article/details/gtachvwzwt.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.redwolf501.top/Article/details/gtttvdwilp.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.wangdashe.top/Article/details/gthpgcdtir.html

[E10] 左侧补零 / 定长填充
来源：http://dali.birdmap.top/Article/details/gtreqxhrff.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xinyue.icu/Article/details/gtwzbypsjc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yvedp.cn/Article/details/gtjzosemsf.html

JS:   "7".padStart(3, "0")
来源：http://dali.fzhhl.top/Article/details/gtapmnlwwp.html

TS:   "7".padStart(3, "0")
来源：http://dali.jqgfzy.top/Article/details/gtpidwdgwr.html

Java: String.format("%03d", 7)
来源：http://dali.yj202588.top/Article/details/gtjwayfpgn.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xinyue.icu/Article/details/gtjnarnnhi.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hnqzz.top/Article/details/gteulpisnj.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yongpay.top/Article/details/gtjmuojzcu.html

[E11] 反转字符串
来源：http://dali.birdmap.top/Article/details/gtqqadxyvv.html

Py:   s[::-1]
来源：http://dali.birdmap.top/Article/details/gtrzuglztp.html

PHP:  strrev($s);
来源：http://dali.wangdashe.top/Article/details/gtdlwxderl.html

JS:   [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gtiovicrpw.html

TS:   [...s].reverse().join("")
来源：http://dali.zhengqikj.top/Article/details/gtnuqwggcx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.pengpengdd.cyou/Article/details/gtxvrrbxdl.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yangfankeji.com/Article/details/gtoguiglnv.html

Ruby: s.reverse
来源：http://dali.yonumen.top/Article/details/gtjlkawzvs.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jyoumei.cn/Article/details/gtpglecmbr.html

[E12] 统计某字符出现次数
来源：http://dali.yj20258888.top/Article/details/gtwvgopmhf.html

Py:   s.count("a")
来源：http://dali.guowangkeji.top/Article/details/gtfcvyezaw.html

PHP:  substr_count($s, "a");
来源：http://dali.mhx1999.top/Article/details/gtdusiqoeo.html

JS:   s.split("a").length - 1
来源：http://dali.zhoulong.xyz/Article/details/gtsetqxbbv.html

TS:   s.split("a").length - 1
来源：http://dali.gogol.net.cn/Article/details/gtmbopqzbd.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sufxvd.cn/Article/details/gtffejcoaq.html

Go:   strings.Count(s, "a")
来源：http://dali.aizwys.cn/Article/details/gtrecracxi.html

Ruby: s.count("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrccxawqj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.havefunace.top/Article/details/gtepoleeee.html

[E13] 逐字符遍历
来源：http://dali.fengsongda.top/Article/details/gtyqqgamfd.html

Py:   for ch in s: print(ch)
来源：http://dali.shuidangran.top/Article/details/gtayaocaal.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhiwuduotai.top/Article/details/gtrlqzveaw.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sufxvd.cn/Article/details/gtizqfxkks.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hysaishi.cn/Article/details/gtnsxwjtzp.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.guowangkeji.top/Article/details/gtufczmpas.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jqgfzy.top/Article/details/gtojczbptf.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hywenlv.cn/Article/details/gtemzgvpnp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.birdmap.top/Article/details/gtsrbsvnon.html

[E14] URL 编码与 Base64
来源：http://dali.zhengqikj.top/Article/details/gtzpupurob.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sweek.top/Article/details/gtvjjgaeje.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.nwbrower.top/Article/details/gtfagrmcly.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zdqjudy.top/Article/details/gtewlrhflp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hammf.cn/Article/details/gtvcgorbis.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jianghu66.top/Article/details/gtvdpdhjxf.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hfpthk.cn/Article/details/gtibgribxc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.316326.xyz/Article/details/gtusnpinmx.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ehwqpu.com/Article/details/gtpdstjghv.html

[E15] HTML 转义 / 反转义
来源：http://dali.havefunace.top/Article/details/gtzoithapc.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.fengsongda.top/Article/details/gtqrlvinnf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxhdlhehz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yueranfly.top/Article/details/gtkqnbaegh.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.nanxinkj.top/Article/details/gtbecnmmvm.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ybcxt.top/Article/details/gtkkqopixs.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gotoacloud.top/Article/details/gtccwqfalv.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jqgfzy.top/Article/details/gtuyvwkvlx.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jqgufenzy.top/Article/details/gtwjepqagc.html

[E16] 数字千分位
来源：http://dali.cashguo.top/Article/details/gtuuyoaoic.html

Py:   f"{1234567:,}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtagrtxmmv.html

PHP:  number_format(1234567);
来源：http://dali.fengsongda.top/Article/details/gtjniltsby.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhengqikj.top/Article/details/gtzbdjzqmi.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shanyushiyangtech.top/Article/details/gtansauuok.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.kuanghao11.cn/Article/details/gtjkrbtvxz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.vqdsnc.cn/Article/details/gtdumfmokf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jianghu66.top/Article/details/gtizopclbm.html

C#:   1234567.ToString("N0")
来源：http://dali.yangfankeji.com/Article/details/gtkljmacvu.html

[E17] 首字母大写
来源：http://dali.jiagoushi.top/Article/details/gthuncpeec.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.guannengcc.top/Article/details/gtjdlmqavy.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.guannengcc.top/Article/details/gtuwcjpead.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jianghu66.top/Article/details/gtkykslfoi.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigufen.top/Article/details/gtfgoakkwt.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.daria6918.cn/Article/details/gtqmexrwhb.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yangfankeji.com/Article/details/gthfvqmhqs.html

Ruby: s.capitalize
来源：http://dali.guannengcc.top/Article/details/gtzushfcwz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.iojbl.cn/Article/details/gtajemzjnw.html

[E18] 模板占位符替换
来源：http://dali.hnxiangtu.top/Article/details/gtndzdchxv.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shanyushiyangtech.top/Article/details/gtnpwbolft.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.smart0.xyz/Article/details/gtmywysgnr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcysbkxtm.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gtzsgboqfd.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gthabsinai.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gtehvfnkbb.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.andypj.xyz/Article/details/gtaureiouq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.pengpengdd.cyou/Article/details/gttbwvxzgi.html

[E19] 多行文本按行拆分
来源：http://dali.mhx1999.top/Article/details/gtefvqyktv.html

Py:   s.splitlines()
来源：http://dali.c1oappe.top/Article/details/gtzswovwur.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yueranfly.top/Article/details/gtzpktnbxw.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhongyouzk.top/Article/details/gtmdrfqvqx.html

TS:   s.split(/\r?\n/)
来源：http://dali.gogol.net.cn/Article/details/gtarnoohsc.html

Java: s.lines().toList()
来源：http://dali.vqdsnc.cn/Article/details/gtdijqfyoh.html

Go:   strings.Split(s, "\n")
来源：http://dali.mhx1999.top/Article/details/gtpjwhpavc.html

Ruby: s.lines
来源：http://dali.chenjidiqi.icu/Article/details/gtlmptfjuf.html

C#:   s.Split('\n')
来源：http://dali.kuanghao11.cn/Article/details/gtpbmzwgub.html

[E20] 判断字符串是否为空
来源：http://dali.sxryk.cn/Article/details/gtfajlabqc.html

Py:   if not s:
来源：http://dali.c1oappe.top/Article/details/gthevbdjsu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.daria6918.cn/Article/details/gttwmiioyw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhongyouzk.top/Article/details/gtvgmvjprk.html

TS:   if (s === "") {}
来源：http://dali.hammf.cn/Article/details/gtvcordzgv.html

Java: if (s.isEmpty()) {}
来源：http://dali.sufxvd.cn/Article/details/gtqqlmaikb.html

Go:   if s == "" {}
来源：http://dali.havefunace.top/Article/details/gtzrzovhft.html

Ruby: if s.empty?
来源：http://dali.9152youxi.cn/Article/details/gtzfqkocyh.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.bjfxy.top/Article/details/gtgnvtkocm.html

[E21] 超长截断加省略号
来源：http://dali.316326.xyz/Article/details/gtbvnoopzv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinqigufen.top/Article/details/gtkzigoazh.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gtvikchkij.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgzziugkb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ydzc1.top/Article/details/gtexzuwcux.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmkdmllnm.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xuetiantiany.cn/Article/details/gtievgkqfv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gtkhmkwqvt.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtwducjroc.html

[E22] 字节长度与字符长度
来源：http://dali.chenjidiqi.icu/Article/details/gthhjtslsg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cucudq.cn/Article/details/gtdlxkfiry.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gtbjfqklvt.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnnuzsegp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hywenlv.cn/Article/details/gtoezilchx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.smart0.xyz/Article/details/gtybgelusu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yj20258.top/Article/details/gtyafaygqg.html

Ruby: s.bytesize;  s.length
来源：http://dali.guannengcc.top/Article/details/gtftvsbrni.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.tianlin.xyz/Article/details/gtwtabegmh.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtuwblyezo.html

F. 文件与目录
来源：http://dali.hywenlv.cn/Article/details/gtrajjtlrv.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxplunfsk.html

[F01] 读取整个文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtrbfxlrau.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hywenlv.cn/Article/details/gtiotmopxj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtlmpzclii.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xuetiantiany.cn/Article/details/gtuyzsrfqd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhiwuduotai.top/Article/details/gtuwzqyvxo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.gotoacloud.top/Article/details/gtaahsigbd.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.tianlin.xyz/Article/details/gttgxzapeu.html

Ruby: File.read("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtblquwwmt.html


<!-- 参考信息 -->