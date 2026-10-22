代发 wailian999

C#:   list.Distinct().ToList()
来源：http://dali.cucudq.cn/Article/details/gtqjifbqml.html

[D16] 求和与平均值
来源：http://dali.daxiang520.top/Article/details/gtnomzcruk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.aizwys.cn/Article/details/gthbggzlav.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.aibaodan.cn/Article/details/gtddrtlqbs.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtgqcznddb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtefxxrdhw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yonumen.top/Article/details/gtuvjqudqb.html

Go:   // 手写循环累加
来源：http://dali.xylfe.cn/Article/details/gtlqvoakyk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zdqjudy.top/Article/details/gtsvxcxlgl.html

C#:   list.Sum();  list.Average()
来源：http://dali.hfpthk.cn/Article/details/gtkjyprgnw.html

[D17] 最大值与最小值
来源：http://dali.kuanghao11.cn/Article/details/gtvcistbaf.html

Py:   max(arr);  min(arr)
来源：http://dali.ppjwa.cn/Article/details/gtncluovby.html

PHP:  max($arr);  min($arr);
来源：http://dali.ivvv.top/Article/details/gtuirwjonm.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gaohongyu789.top/Article/details/gtknkkphsm.html

TS:   Math.max(...arr);
来源：http://dali.yuxming.cn/Article/details/gtykiltgra.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.daria6918.cn/Article/details/gtsiuxoowv.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttconexaz.html

Ruby: arr.max;  arr.min
来源：http://dali.yongpay.top/Article/details/gtrfjjsmqk.html

C#:   list.Max();  list.Min()
来源：http://dali.xuanzx.com/Article/details/gtuxkuvmvx.html

[D18] 扁平化嵌套数组
来源：http://dali.316326.xyz/Article/details/gtvpjlsxme.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.pycfn.com/Article/details/gtcbiipxuj.html

PHP:  array_merge(...$nested);
来源：http://dali.xinyue.icu/Article/details/gttuktgfrf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zycfv.cn/Article/details/gtvgygkdwz.html

TS:   nested.flat();
来源：http://dali.ehwqpu.com/Article/details/gtylhhvnjx.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yuanzhike.top/Article/details/gtgjwkvpmd.html

Go:   // 手写双层循环
来源：http://dali.sufxvd.cn/Article/details/gtrviczoxl.html

Ruby: nested.flatten
来源：http://dali.gzhubu.top/Article/details/gtfqbsryxj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhixingplan.top/Article/details/gtbotcwzwn.html

[D19] 按字段分组
来源：http://dali.yonumen.top/Article/details/gtmlehonsw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hfpthk.cn/Article/details/gtznzzmaqf.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtppjiilnk.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.guannengcc.top/Article/details/gtiblllhjr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.tian-w.cn/Article/details/gtsxbmzngw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gtsueizeyn.html

Go:   // 手写 map[string][]T
来源：http://dali.shuidangran.top/Article/details/gtcxxgcnyc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.smart0.xyz/Article/details/gtvuuazoni.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.meibo888.top/Article/details/gttmkdyckt.html

[D20] 统计每个元素出现次数
来源：http://dali.gaohongyu789.top/Article/details/gtulixtbzy.html

Py:   Counter(arr)
来源：http://dali.redwolf501.top/Article/details/gtceowcspu.html

PHP:  array_count_values($arr);
来源：http://dali.yonumen.top/Article/details/gtizjjvsws.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ydzc1.top/Article/details/gtlueaaysk.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hammf.cn/Article/details/gtzmhohmid.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ehwqpu.com/Article/details/gtfmfxntsp.html

Go:   // 手写 map[T]int
来源：http://dali.yanxiufei.cn/Article/details/gtegpifjil.html

Ruby: arr.tally
来源：http://dali.snrcjt.cn/Article/details/gtrqkkgjtw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hongshengwenyu.top/Article/details/gtyaaxmrlv.html

[D21] 判断是否包含某元素
来源：http://dali.hammf.cn/Article/details/gtjvwkxdfd.html

Py:   x in arr
来源：http://dali.pengpengdd.cyou/Article/details/gtoopolhrv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.nanxuanxn.top/Article/details/gtrohxwanm.html

JS:   arr.includes(x)
来源：http://dali.yj20258.top/Article/details/gtbkzicfym.html

TS:   arr.includes(x)
来源：http://dali.yj20258888.top/Article/details/gtzlmcatpj.html

Java: list.contains(x)
来源：http://dali.fzhhl.top/Article/details/gthvnxcnwc.html

Go:   slices.Contains(arr, x)
来源：http://dali.sysykeji.top/Article/details/gtynrptprg.html

Ruby: arr.include?(x)
来源：http://dali.sweek.top/Article/details/gtossycdlj.html

C#:   list.Contains(x)
来源：http://dali.zhengqikj.top/Article/details/gtoeyqujmx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ppjwa.cn/Article/details/gtfttzaxsx.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.wangdashe.top/Article/details/gtbzgbqsyh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.aizwys.cn/Article/details/gtliyxmitx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtnmhuwdar.html

TS:   [...arr];
来源：http://dali.svipenyu.cn/Article/details/gtarmkxund.html

Java: new ArrayList<>(list);
来源：http://dali.yuanzhike.top/Article/details/gtpuugewet.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.sxryk.cn/Article/details/gtzkzakawg.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sweek.top/Article/details/gtanwdtloy.html

C#:   new List<int>(list);
来源：http://dali.andypj.xyz/Article/details/gtvgqotwas.html

[D23] reduce 累积计算
来源：http://dali.9152youxi.cn/Article/details/gtbipnrnek.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.bjfxy.top/Article/details/gthoejaxwo.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.dianchejie.cn/Article/details/gtqdejsyuh.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.andypj.xyz/Article/details/gtqgyozuod.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.mhx1999.top/Article/details/gtlbhdmiqx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.birdmap.top/Article/details/gtfkchjnrz.html

Go:   // 手写循环
来源：http://dali.nanxuanxn.top/Article/details/gtyckeikml.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.andypj.xyz/Article/details/gtkmwfzcqc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.c1oappe.top/Article/details/gtkqzkfrur.html

[D24] 字典 / Map 基本操作
来源：http://dali.chenzaomai.com/Article/details/gtzlngxbkk.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.tianlin.xyz/Article/details/gtwmixyika.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yonumen.top/Article/details/gtflejbuqm.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.quarkkingdee.top/Article/details/gtxscuayxy.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hywenlv.cn/Article/details/gtdrdgvglf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhixingplan.top/Article/details/gttcmqgzqt.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.sxryk.cn/Article/details/gtqziggqcu.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.guannengcc.top/Article/details/gttbbugxbu.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmxfkuqcl.html

[D25] Set 集合去重与交并差
来源：http://dali.gotoacloud.top/Article/details/gtghpwlczs.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yvedp.cn/Article/details/gtkjbzpbge.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.sufxvd.cn/Article/details/gtfwjtspqc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.sysykeji.top/Article/details/gtdympawqs.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cheryme.top/Article/details/gtqdluphmc.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.iojbl.cn/Article/details/gtsgfqfkns.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cqqwz.cn/Article/details/gtpqvmerql.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.kuanghao11.cn/Article/details/gtljqcmxbk.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yanxiufei.cn/Article/details/gtqzwzhkul.html

[D26] 数组转字符串
来源：http://dali.vqdsnc.cn/Article/details/gtabarftme.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtivbyfhyp.html

PHP:  implode(", ", $arr);
来源：http://dali.yvedp.cn/Article/details/gtrryycezc.html

JS:   arr.join(", ")
来源：http://dali.9152youxi.cn/Article/details/gtgtpwrcbl.html

TS:   arr.join(", ")
来源：http://dali.havefunace.top/Article/details/gtpnmdicne.html

Java: String.join(", ", list)
来源：http://dali.jianghu66.top/Article/details/gtbptigoay.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hfpthk.cn/Article/details/gtjogmhtnw.html

Ruby: arr.join(", ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gttlqbfldx.html

C#:   string.Join(", ", list)
来源：http://dali.ppjwa.cn/Article/details/gtgfumswho.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtoruoeuib.html

E. 字符串处理
来源：http://dali.nanxuanxn.top/Article/details/gtnpeiwvyl.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtijvkmzhg.html

[E01] 拼接字符串
来源：http://dali.hnxiangtu.top/Article/details/gtvhrzptra.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sufxvd.cn/Article/details/gtjzanpwzr.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.cashguo.top/Article/details/gthojnwjvh.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjeqgyclw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shzxlz.cn/Article/details/gtidginqnw.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.haohaochexian.top/Article/details/gtvooceiws.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jqgufenzy.top/Article/details/gtkaklspwu.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cucudq.cn/Article/details/gtfzstvcfh.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xylfe.cn/Article/details/gtswlgmnoa.html

[E02] 重复字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtckompwza.html

Py:   "ab" * 3
来源：http://dali.tanke756.top/Article/details/gtcjcxxkoz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.redwolf501.top/Article/details/gtsrsujvcf.html

JS:   "ab".repeat(3)
来源：http://dali.feifeiyinyue.top/Article/details/gterkriolz.html

TS:   "ab".repeat(3)
来源：http://dali.svipenyu.cn/Article/details/gtuauasulu.html

Java: "ab".repeat(3)
来源：http://dali.svipenyu.cn/Article/details/gtyczfsuin.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.andypj.xyz/Article/details/gtdgqntpds.html

Ruby: "ab" * 3
来源：http://dali.yj20258.top/Article/details/gtgdkvwipq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.svipenyu.cn/Article/details/gtswjulkdv.html

[E03] 截取子串
来源：http://dali.jinqigfzy.top/Article/details/gtqyuzlokp.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.pengpengdd.cyou/Article/details/gtavieryzs.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gtjjavalma.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhixingplan.top/Article/details/gtsagzdmxz.html

TS:   s.slice(1, 4)
来源：http://dali.tian-w.cn/Article/details/gtujamqfkc.html

Java: s.substring(1, 4)
来源：http://dali.cashguo.top/Article/details/gtbvpggzrh.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sufxvd.cn/Article/details/gtayktjhat.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.aizwys.cn/Article/details/gtnuegiwpk.html

C#:   s.Substring(1, 3)
来源：http://dali.zhengqikj.top/Article/details/gtmcccsuyb.html

[E04] 查找子串位置
来源：http://dali.snrcjt.cn/Article/details/gtskucjbmo.html

Py:   s.find("x");  s.index("x")
来源：http://dali.mhx1999.top/Article/details/gtucsdamtp.html

PHP:  strpos($s, "x");
来源：http://dali.chenjidiqi.icu/Article/details/gtoqsrhtww.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yvedp.cn/Article/details/gtjcpsxate.html

TS:   s.indexOf("x")
来源：http://dali.hnqzz.top/Article/details/gtytometgp.html

Java: s.indexOf("x")
来源：http://dali.guowangkeji.top/Article/details/gtemebalhu.html

Go:   strings.Index(s, "x")
来源：http://dali.daria6918.cn/Article/details/gtptbbkblp.html

Ruby: s.index("x")
来源：http://dali.nanxuanxn.top/Article/details/gtawfqkrrd.html

C#:   s.IndexOf("x")
来源：http://dali.pycfn.com/Article/details/gthugocmle.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hywenlv.cn/Article/details/gtpqgbdbmo.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.pengpengdd.cyou/Article/details/gtnraeypjp.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.birdmap.top/Article/details/gttyyjfvpa.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gtmbfbjnyb.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jqgufenzy.top/Article/details/gttenjyuzj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhiwuduotai.top/Article/details/gtfvniknks.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.sweek.top/Article/details/gtrlkxlnut.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yuanzhike.top/Article/details/gtyyvvvmej.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ivvv.top/Article/details/gtbmtanhik.html

[E06] 替换子串
来源：http://dali.yanxiufei.cn/Article/details/gtiupcecoc.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyumwtdse.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ydzc1.top/Article/details/gtbsitngon.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gtrbyqghjy.html

TS:   s.replaceAll("a", "b")
来源：http://dali.meibo888.top/Article/details/gtnishrfme.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gtiddxsdtb.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.sysykeji.top/Article/details/gtwzoalprn.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gtbavbefwr.html

C#:   s.Replace("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gtajchvatk.html

[E07] 按分隔符拆分
来源：http://dali.mhx1999.top/Article/details/gtrtsmafuw.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.sufxvd.cn/Article/details/gtvpxhletm.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.meibo888.top/Article/details/gtuaalaeau.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.nanxinkj.top/Article/details/gtrkssxdjd.html

TS:   s.split(",")
来源：http://dali.shangyingyoupin.top/Article/details/gtaofrkbli.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.fzhhl.top/Article/details/gtkypwfzvc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvxlylaxm.html

Ruby: s.split(",");  s.split
来源：http://dali.ybcxt.top/Article/details/gtrrescdmk.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ppjwa.cn/Article/details/gtozfvunlv.html

[E08] 数组按分隔符合并
来源：http://dali.pengpengdd.cyou/Article/details/gtewxfovig.html

Py:   ",".join(items)
来源：http://dali.jiagoushi.top/Article/details/gtzqooguhd.html

PHP:  implode(",", $items);
来源：http://dali.chenjidiqi.icu/Article/details/gtpofiagnh.html

JS:   items.join(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gtrvtfyycz.html

TS:   items.join(",")
来源：http://dali.dashuyun.cn/Article/details/gtlindbwbp.html

Java: String.join(",", items)
来源：http://dali.yangfankeji.com/Article/details/gtsjoroulb.html

Go:   strings.Join(items, ",")
来源：http://dali.guannengcc.top/Article/details/gtejdwosjn.html

Ruby: items.join(",")
来源：http://dali.guowangkeji.top/Article/details/gtqjoazfqc.html

C#:   string.Join(",", items)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtobzujsmt.html

[E09] 去除所有空白字符
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdjahwqsw.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shangyingyoupin.top/Article/details/gtdhnllbfw.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jinqigfzy.top/Article/details/gtawaecnzv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yuanzhike.top/Article/details/gtjfxxiyui.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.feifeiyinyue.top/Article/details/gtkeiwqbzc.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.meibo888.top/Article/details/gtqzcvmtpd.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaxkcwqau.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.pycfn.com/Article/details/gtbgyfypur.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hywenlv.cn/Article/details/gtmejmoxcd.html

[E10] 左侧补零 / 定长填充
来源：http://dali.vqdsnc.cn/Article/details/gtmwykkjbg.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xinyue.icu/Article/details/gttzkcvvfl.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cashguo.top/Article/details/gtkuqsaefa.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtecaxzzqg.html

TS:   "7".padStart(3, "0")
来源：http://dali.ydzc1.top/Article/details/gtdqkxtvnc.html

Java: String.format("%03d", 7)
来源：http://dali.jqgfzy.top/Article/details/gtzqanbwjj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jqgufenzy.top/Article/details/gtscmehvtm.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.nanxinkj.top/Article/details/gtmzfqchip.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.mhx1999.top/Article/details/gtvfzelage.html

[E11] 反转字符串
来源：http://dali.tian-w.cn/Article/details/gtdegbdxwt.html

Py:   s[::-1]
来源：http://dali.wangshuangyany.cn/Article/details/gtbvlzkqzj.html

PHP:  strrev($s);
来源：http://dali.daxiang520.top/Article/details/gtdsigckol.html

JS:   [...s].reverse().join("")
来源：http://dali.zhengqikj.top/Article/details/gtucyqgyqt.html

TS:   [...s].reverse().join("")
来源：http://dali.mhx1999.top/Article/details/gtkghtqiqs.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.daria6918.cn/Article/details/gtcyejxttq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.wangshuangyany.cn/Article/details/gtuvrekowv.html

Ruby: s.reverse
来源：http://dali.yj20258888.top/Article/details/gttrehvcdh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jlsjyb.cn/Article/details/gtjxohyvgj.html

[E12] 统计某字符出现次数
来源：http://dali.nanxinkj.top/Article/details/gtccxllouk.html

Py:   s.count("a")
来源：http://dali.aizwys.cn/Article/details/gtpcrfzhau.html

PHP:  substr_count($s, "a");
来源：http://dali.hammf.cn/Article/details/gtqfnvcpjp.html

JS:   s.split("a").length - 1
来源：http://dali.jqgfzy.top/Article/details/gtnzpsmlwk.html

TS:   s.split("a").length - 1
来源：http://dali.zhongyouzk.top/Article/details/gtthlnzpwv.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.nanxinkj.top/Article/details/gtqsgyjkiq.html

Go:   strings.Count(s, "a")
来源：http://dali.andypj.xyz/Article/details/gtfqemjjnf.html

Ruby: s.count("a")
来源：http://dali.nwbrower.top/Article/details/gtqchxpuio.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shangyingyoupin.top/Article/details/gtckcwaemi.html

[E13] 逐字符遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtvgvsfsoo.html

Py:   for ch in s: print(ch)
来源：http://dali.hnxiangtu.top/Article/details/gtrmozxbho.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.iojbl.cn/Article/details/gtriskplxx.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gthqtwagmj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ybcxt.top/Article/details/gtnhcfqytw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shzxlz.cn/Article/details/gtwwtdpqii.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yonumen.top/Article/details/gttiloxdic.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.feifeiyinyue.top/Article/details/gtcsryranc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cheryme.top/Article/details/gtbbmcrylc.html

[E14] URL 编码与 Base64
来源：http://dali.feifeiyinyue.top/Article/details/gteeelpgjt.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yueranfly.top/Article/details/gtexujlkvo.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.guannengcc.top/Article/details/gtzzlbeqzd.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.pycfn.com/Article/details/gtzpswscmf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.9152youxi.cn/Article/details/gtcwzzzggp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhongyouzk.top/Article/details/gtogrbadsd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.birdmap.top/Article/details/gtnkyviikn.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.0kj1m.cn/Article/details/gtvaicsies.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.kuanghao11.cn/Article/details/gtltdrwdur.html

[E15] HTML 转义 / 反转义
来源：http://dali.snrcjt.cn/Article/details/gtjhpuwshe.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yvedp.cn/Article/details/gtoghkxwgg.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yongpay.top/Article/details/gtzomkfcha.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhoulong.xyz/Article/details/gtmufawsoz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xylfe.cn/Article/details/gttvjbahso.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.dianchejie.cn/Article/details/gtnpbfqzcx.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhoulong.xyz/Article/details/gtmeicmmkh.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtixzsjtxi.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hysaishi.cn/Article/details/gtpusprteh.html

[E16] 数字千分位
来源：http://dali.kuanghao11.cn/Article/details/gtxtgxobab.html

Py:   f"{1234567:,}"
来源：http://dali.yanxiufei.cn/Article/details/gtfujqffhn.html

PHP:  number_format(1234567);
来源：http://dali.ydzc1.top/Article/details/gtsrncrbsd.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigufen.top/Article/details/gtjfuymhtu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hywenlv.cn/Article/details/gtdstpshfy.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zdqjudy.top/Article/details/gtjcljpckz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jyoumei.cn/Article/details/gtnfesbcoz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shangyingyoupin.top/Article/details/gtluuludya.html

C#:   1234567.ToString("N0")
来源：http://dali.sysykeji.top/Article/details/gtbiriczpu.html

[E17] 首字母大写
来源：http://dali.jqgufenzy.top/Article/details/gtytpwhanq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xuanzx.com/Article/details/gtqoiwkcfd.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtsnjzalsc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnqzz.top/Article/details/gtuvkmojge.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daria6918.cn/Article/details/gtqrxfrhet.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gogol.net.cn/Article/details/gtclegylhw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.aizwys.cn/Article/details/gtocvwigbu.html

Ruby: s.capitalize
来源：http://dali.jqgufenzy.top/Article/details/gtuvwdmflv.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yj202588.top/Article/details/gtzlglgunh.html

[E18] 模板占位符替换
来源：http://dali.cheryme.top/Article/details/gtotsrjvdu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.fzhhl.top/Article/details/gtmauwrqsv.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.sweek.top/Article/details/gtyhnermkm.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.316326.xyz/Article/details/gthfnobgqa.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jqgfzy.top/Article/details/gtnjhxfmlt.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yj20258.top/Article/details/gtntgscauw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.pycfn.com/Article/details/gthdjfkpxk.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shuidangran.top/Article/details/gtpeikwrcp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.nwbrower.top/Article/details/gtkaprabwx.html

[E19] 多行文本按行拆分
来源：http://dali.shzxlz.cn/Article/details/gtuanryhcc.html

Py:   s.splitlines()
来源：http://dali.fzhhl.top/Article/details/gtfpszaexs.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yanxiufei.cn/Article/details/gtcaxhzxsy.html

JS:   s.split(/\r?\n/)
来源：http://dali.ppjwa.cn/Article/details/gtydybroql.html

TS:   s.split(/\r?\n/)
来源：http://dali.hfpthk.cn/Article/details/gtksbjjucl.html

Java: s.lines().toList()
来源：http://dali.tanke756.top/Article/details/gtgiqfxkyz.html

Go:   strings.Split(s, "\n")
来源：http://dali.yvedp.cn/Article/details/gtkptharen.html

Ruby: s.lines
来源：http://dali.dashuyun.cn/Article/details/gtncosjqye.html

C#:   s.Split('\n')
来源：http://dali.sysykeji.top/Article/details/gtbeslbved.html

[E20] 判断字符串是否为空
来源：http://dali.feifeiyinyue.top/Article/details/gtoxmyokfd.html

Py:   if not s:
来源：http://dali.zhongyouzk.top/Article/details/gtviwahykz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yonumen.top/Article/details/gthrwgkpcv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtjvwmmmnw.html

TS:   if (s === "") {}
来源：http://dali.vqdsnc.cn/Article/details/gtfbrtudva.html

Java: if (s.isEmpty()) {}
来源：http://dali.pycfn.com/Article/details/gtkichsado.html

Go:   if s == "" {}
来源：http://dali.meibo888.top/Article/details/gturuqjlkc.html

Ruby: if s.empty?
来源：http://dali.cqqwz.cn/Article/details/gtfqhjlade.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.aibaodan.cn/Article/details/gtenqmxlyc.html

[E21] 超长截断加省略号
来源：http://dali.gotoacloud.top/Article/details/gtbzzrqeur.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gogol.net.cn/Article/details/gtnmzjlzdp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gtiuwhaetb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gttjipdefi.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tian-w.cn/Article/details/gtpnucyenw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yj202588.top/Article/details/gtpqrzjsdj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sysykeji.top/Article/details/gtlzzmivyh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xziqi.cn/Article/details/gtakcqkjro.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtxftghdww.html

[E22] 字节长度与字符长度
来源：http://dali.smart0.xyz/Article/details/gtjfcojrjt.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinqigfzy.top/Article/details/gtvgkohukr.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gtcupkwess.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xinyue.icu/Article/details/gtjwnnvbqz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gtmsgczosd.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shangyingyoupin.top/Article/details/gtxlghobhp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.c1oappe.top/Article/details/gttjbyyopi.html

Ruby: s.bytesize;  s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwjxhhvyx.html


<!-- 参考信息 -->