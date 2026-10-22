代发 wailian999

PHP:  max($arr);  min($arr);
来源：http://dali.guowangkeji.top/Article/details/gtvqnvgpgj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cashguo.top/Article/details/gtymmwsjqx.html

TS:   Math.max(...arr);
来源：http://dali.mhx1999.top/Article/details/gtjlmqfyzw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shzxlz.cn/Article/details/gtgrkwqckq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gttoldopdj.html

Ruby: arr.max;  arr.min
来源：http://dali.jyoumei.cn/Article/details/gtitkupbaz.html

C#:   list.Max();  list.Min()
来源：http://dali.tianlin.xyz/Article/details/gtunmcvhic.html

[D18] 扁平化嵌套数组
来源：http://dali.bjfxy.top/Article/details/gtfkizonmq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.meibo888.top/Article/details/gtpifpuxhd.html

PHP:  array_merge(...$nested);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtatwghwnz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jinqigfzy.top/Article/details/gtseoahusa.html

TS:   nested.flat();
来源：http://dali.chenjidiqi.icu/Article/details/gtepifvrtn.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.9152youxi.cn/Article/details/gthhgtalxt.html

Go:   // 手写双层循环
来源：http://dali.tanke756.top/Article/details/gtiwdkbayl.html

Ruby: nested.flatten
来源：http://dali.hfpthk.cn/Article/details/gtrrvauhla.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtdvwsyqxj.html

[D19] 按字段分组
来源：http://dali.jinqigufen.top/Article/details/gtympjitdv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jqgufenzy.top/Article/details/gthgvhfmgc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.wangdashe.top/Article/details/gtgpcgwfhy.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cucudq.cn/Article/details/gttshjfibd.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.andypj.xyz/Article/details/gtndgivdvg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yangfankeji.com/Article/details/gtwvlrbdch.html

Go:   // 手写 map[string][]T
来源：http://dali.hfpthk.cn/Article/details/gtibautdfr.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yonumen.top/Article/details/gtkpbdzaxi.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.meibo888.top/Article/details/gtmieicnfd.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gthjreivvk.html

Py:   Counter(arr)
来源：http://dali.sufxvd.cn/Article/details/gtyesnvcna.html

PHP:  array_count_values($arr);
来源：http://dali.yj20258.top/Article/details/gtuzcwcznb.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinqigfzy.top/Article/details/gtwjoprjou.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cheryme.top/Article/details/gtiwetteav.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yuxming.cn/Article/details/gtczsgpwfi.html

Go:   // 手写 map[T]int
来源：http://dali.hammf.cn/Article/details/gtblzkrmpj.html

Ruby: arr.tally
来源：http://dali.sxryk.cn/Article/details/gtwkihfihx.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.wangshuangyany.cn/Article/details/gtouvxesyc.html

[D21] 判断是否包含某元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtoteuhfbb.html

Py:   x in arr
来源：http://dali.daria6918.cn/Article/details/gtgvuvmcwa.html

PHP:  in_array($x, $arr, true);
来源：http://dali.nanxuanxn.top/Article/details/gtvkrucaqq.html

JS:   arr.includes(x)
来源：http://dali.daxiang520.top/Article/details/gtjxrqmzhn.html

TS:   arr.includes(x)
来源：http://dali.sufxvd.cn/Article/details/gtvjwxcklo.html

Java: list.contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gtorpjotra.html

Go:   slices.Contains(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gtrlcskuky.html

Ruby: arr.include?(x)
来源：http://dali.0kj1m.cn/Article/details/gtwbgkddmw.html

C#:   list.Contains(x)
来源：http://dali.9152youxi.cn/Article/details/gttpaqczwd.html

[D22] 复制数组（避免共享引用）
来源：http://dali.gogol.net.cn/Article/details/gtzflhmdvy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.vqdsnc.cn/Article/details/gthnnoikeb.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xinyue.icu/Article/details/gtpqrksbcq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.redwolf501.top/Article/details/gttmimeadb.html

TS:   [...arr];
来源：http://dali.jinqigufen.top/Article/details/gtdbhanpgd.html

Java: new ArrayList<>(list);
来源：http://dali.zhiwuduotai.top/Article/details/gtfmsvemdd.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhongyouzk.top/Article/details/gtaoagzdum.html

Ruby: arr.dup;  arr.clone
来源：http://dali.feifeiyinyue.top/Article/details/gtzidsymsy.html

C#:   new List<int>(list);
来源：http://dali.aibaodan.cn/Article/details/gtaeqaqygm.html

[D23] reduce 累积计算
来源：http://dali.redwolf501.top/Article/details/gtttcaqlij.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.dashuyun.cn/Article/details/gtbpzaeetl.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.fengsongda.top/Article/details/gtlrjvyhcl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tianlin.xyz/Article/details/gtklcrswbw.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtfwmwkvbe.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shuidangran.top/Article/details/gtzzlbywot.html

Go:   // 手写循环
来源：http://dali.jqgufenzy.top/Article/details/gtwikjmaxa.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.feifeiyinyue.top/Article/details/gtlsllmbar.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.smart0.xyz/Article/details/gtoerfxbww.html

[D24] 字典 / Map 基本操作
来源：http://dali.bjfxy.top/Article/details/gtqeynnuui.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.snrcjt.cn/Article/details/gthqmkxzpk.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.aizwys.cn/Article/details/gtndxzqsfl.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvgmxgcki.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.chenzaomai.com/Article/details/gtrapypqtb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.daxiang520.top/Article/details/gtrjssvrsg.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.bjfxy.top/Article/details/gtbnnkfuna.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shanyushiyangtech.top/Article/details/gtycektrsv.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinghuilouyu.cn/Article/details/gtooufkzik.html

[D25] Set 集合去重与交并差
来源：http://dali.zhongyouzk.top/Article/details/gtgqdbuwia.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.snrcjt.cn/Article/details/gtgpmffxui.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ybcxt.top/Article/details/gtpchfuzrw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhixingplan.top/Article/details/gtzkquxejs.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xziqi.cn/Article/details/gtdejigafa.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.guowangkeji.top/Article/details/gtsxymbvmn.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.vqdsnc.cn/Article/details/gtboyeaxcr.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gteuzinoum.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.bjfxy.top/Article/details/gtlsmtyemi.html

[D26] 数组转字符串
来源：http://dali.9152youxi.cn/Article/details/gtblbmejeu.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shuidangran.top/Article/details/gtbfsoexoq.html

PHP:  implode(", ", $arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtsfhlgazx.html

JS:   arr.join(", ")
来源：http://dali.zycfv.cn/Article/details/gtcwuipiwq.html

TS:   arr.join(", ")
来源：http://dali.jinqigufen.top/Article/details/gtizbjxogx.html

Java: String.join(", ", list)
来源：http://dali.hfpthk.cn/Article/details/gtxqjmzupy.html

Go:   strings.Join(strs, ", ")
来源：http://dali.guannengcc.top/Article/details/gttyravquq.html

Ruby: arr.join(", ")
来源：http://dali.pengpengdd.cyou/Article/details/gtlzcfccse.html

C#:   string.Join(", ", list)
来源：http://dali.yueranfly.top/Article/details/gtsvemjgdx.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtzmlkvkbs.html

E. 字符串处理
来源：http://dali.gaohongyu789.top/Article/details/gtaqvlzpbd.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtdnhsqybh.html

[E01] 拼接字符串
来源：http://dali.sysykeji.top/Article/details/gtgahexblf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gogol.net.cn/Article/details/gtqpemzezi.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.cashguo.top/Article/details/gtzcwwskuz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.mhx1999.top/Article/details/gtdncbpozj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gteknobcjo.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.feifeiyinyue.top/Article/details/gtnqejprdz.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.pengpengdd.cyou/Article/details/gtixamrhsa.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yvedp.cn/Article/details/gtynnxfzhm.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cheryme.top/Article/details/gtvrmwjhno.html

[E02] 重复字符串
来源：http://dali.quarkkingdee.top/Article/details/gtnspaayju.html

Py:   "ab" * 3
来源：http://dali.gogol.net.cn/Article/details/gturzqvszq.html

PHP:  str_repeat("ab", 3);
来源：http://dali.nwbrower.top/Article/details/gtyjooidkm.html

JS:   "ab".repeat(3)
来源：http://dali.nanxinkj.top/Article/details/gtgzqpupbo.html

TS:   "ab".repeat(3)
来源：http://dali.zhongyouzk.top/Article/details/gtmapmjitb.html

Java: "ab".repeat(3)
来源：http://dali.feifeiyinyue.top/Article/details/gtfwwmggpv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvnbjymxo.html

Ruby: "ab" * 3
来源：http://dali.shanyushiyangkeji.top/Article/details/gtklctiwit.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hnqzz.top/Article/details/gtezcaruit.html

[E03] 截取子串
来源：http://dali.cqqwz.cn/Article/details/gtbgijnjjj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhiwuduotai.top/Article/details/gtmzjwouee.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.fzhhl.top/Article/details/gtvfmhsvai.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gaohongyu789.top/Article/details/gtqbfznchs.html

TS:   s.slice(1, 4)
来源：http://dali.bjfxy.top/Article/details/gtamgyethz.html

Java: s.substring(1, 4)
来源：http://dali.gotoacloud.top/Article/details/gtigoviqcs.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cqqwz.cn/Article/details/gthqntgrdf.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.feifeiyinyue.top/Article/details/gtszbzlaxm.html

C#:   s.Substring(1, 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtchmwhnnu.html

[E04] 查找子串位置
来源：http://dali.cqqwz.cn/Article/details/gtgopgfpbo.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ybcxt.top/Article/details/gtsywbfkiy.html

PHP:  strpos($s, "x");
来源：http://dali.snrcjt.cn/Article/details/gtojxljypx.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.fengsongda.top/Article/details/gtjelcthkz.html

TS:   s.indexOf("x")
来源：http://dali.iojbl.cn/Article/details/gtlngerlnt.html

Java: s.indexOf("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnjtodcyb.html

Go:   strings.Index(s, "x")
来源：http://dali.dianchejie.cn/Article/details/gtjssppiyq.html

Ruby: s.index("x")
来源：http://dali.yj202588.top/Article/details/gtscsmjkbm.html

C#:   s.IndexOf("x")
来源：http://dali.fengsongda.top/Article/details/gtjfsttgpc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xinyue.icu/Article/details/gtjxixqffy.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.sweek.top/Article/details/gtubdkkenf.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yonumen.top/Article/details/gthfvfzcpe.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gzhubu.top/Article/details/gtbxgbfcbx.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.gzhubu.top/Article/details/gtrhdpzjsh.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.daxiang520.top/Article/details/gtrbfxdmjr.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.fzhhl.top/Article/details/gthdptuyrf.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xinyue.icu/Article/details/gteaoftjed.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jiagoushi.top/Article/details/gticyxxend.html

[E06] 替换子串
来源：http://dali.xinyue.icu/Article/details/gtycyxofev.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yanxiufei.cn/Article/details/gtyjmlzmvq.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhengqikj.top/Article/details/gtoeddbrfj.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zycfv.cn/Article/details/gtzkdaizsr.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtwvrqvjvs.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtoiqwyzrn.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtqrxxipfz.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvriwxlva.html

C#:   s.Replace("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gttfftkhzs.html

[E07] 按分隔符拆分
来源：http://dali.jyoumei.cn/Article/details/gtcxrngigb.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xuanzx.com/Article/details/gtgcdpqdnw.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzjhulfhs.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdavjttzx.html

TS:   s.split(",")
来源：http://dali.birdmap.top/Article/details/gtbysccsle.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.9152youxi.cn/Article/details/gtvfxwxsum.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gotoacloud.top/Article/details/gtbndcgxeg.html

Ruby: s.split(",");  s.split
来源：http://dali.dianchejie.cn/Article/details/gtjqojivsq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.tianlin.xyz/Article/details/gtjldqanck.html

[E08] 数组按分隔符合并
来源：http://dali.shzxlz.cn/Article/details/gtpahckhfw.html

Py:   ",".join(items)
来源：http://dali.hywenlv.cn/Article/details/gtzptynybj.html

PHP:  implode(",", $items);
来源：http://dali.cdnleiting.top/Article/details/gtfeqzeqmc.html

JS:   items.join(",")
来源：http://dali.jianghu66.top/Article/details/gtnnegjsji.html

TS:   items.join(",")
来源：http://dali.xuetiantiany.cn/Article/details/gtqjpuyppv.html

Java: String.join(",", items)
来源：http://dali.0kj1m.cn/Article/details/gtqrlfaefx.html

Go:   strings.Join(items, ",")
来源：http://dali.jqgufenzy.top/Article/details/gtexlmkyiq.html

Ruby: items.join(",")
来源：http://dali.gaohongyu789.top/Article/details/gtkmllrtil.html

C#:   string.Join(",", items)
来源：http://dali.xuanzx.com/Article/details/gtoehpidkv.html

[E09] 去除所有空白字符
来源：http://dali.cqqwz.cn/Article/details/gtzjmuhbiu.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cdnleiting.top/Article/details/gtlfxnrfxy.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.aibaodan.cn/Article/details/gtqdbyjdbc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shangyingyoupin.top/Article/details/gtumvhwejo.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigufen.top/Article/details/gtasqvnkli.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.chenlongwang.top/Article/details/gtdhbxogri.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.svipenyu.cn/Article/details/gtpremmmzu.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhiwuduotai.top/Article/details/gteflyyyes.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.fzhhl.top/Article/details/gthzwlvexo.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ppjwa.cn/Article/details/gtocfqcton.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jqgfzy.top/Article/details/gtsyjfmvod.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.birdmap.top/Article/details/gtvrhyxzqj.html

JS:   "7".padStart(3, "0")
来源：http://dali.jlsjyb.cn/Article/details/gtxlzyxxxu.html

TS:   "7".padStart(3, "0")
来源：http://dali.andypj.xyz/Article/details/gttxkzahhv.html

Java: String.format("%03d", 7)
来源：http://dali.yongpay.top/Article/details/gtdhvnxrjy.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.mhx1999.top/Article/details/gtcmqsubxe.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.haohaochexian.top/Article/details/gtfmsvjbiq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.smart0.xyz/Article/details/gtqymbcrrf.html

[E11] 反转字符串
来源：http://dali.cucudq.cn/Article/details/gtnnijhxsr.html

Py:   s[::-1]
来源：http://dali.svipenyu.cn/Article/details/gtpbkslkwn.html

PHP:  strrev($s);
来源：http://dali.chenlongwang.top/Article/details/gtprtlkjer.html

JS:   [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gtuxgfzkbe.html

TS:   [...s].reverse().join("")
来源：http://dali.sysykeji.top/Article/details/gtqzbfboqc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.sxryk.cn/Article/details/gtlxfsdcrc.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jinyuanbaomall.cn/Article/details/gtamixstvy.html

Ruby: s.reverse
来源：http://dali.sxryk.cn/Article/details/gtszlhfchv.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hnqzz.top/Article/details/gtmddtwgrn.html

[E12] 统计某字符出现次数
来源：http://dali.vqdsnc.cn/Article/details/gtjswqtqgn.html

Py:   s.count("a")
来源：http://dali.hywenlv.cn/Article/details/gtdbaaaskb.html

PHP:  substr_count($s, "a");
来源：http://dali.jinqigfzy.top/Article/details/gtmztpzlov.html

JS:   s.split("a").length - 1
来源：http://dali.ivvv.top/Article/details/gtymehpkyo.html

TS:   s.split("a").length - 1
来源：http://dali.iojbl.cn/Article/details/gtkbsehnds.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hysaishi.cn/Article/details/gteigsuqay.html

Go:   strings.Count(s, "a")
来源：http://dali.chenlongwang.top/Article/details/gtwdevxlje.html

Ruby: s.count("a")
来源：http://dali.ehwqpu.com/Article/details/gttuwmgbow.html

C#:   s.Count(c => c == 'a')
来源：http://dali.kuanghao11.cn/Article/details/gtduupktvf.html

[E13] 逐字符遍历
来源：http://dali.sxryk.cn/Article/details/gtdtuuccio.html

Py:   for ch in s: print(ch)
来源：http://dali.smart0.xyz/Article/details/gtudauaavb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhixingplan.top/Article/details/gtaxtqnhhg.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aibaodan.cn/Article/details/gtzubsyfwe.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gtglrjirpd.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.c1oappe.top/Article/details/gtwkapkblk.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.chenzaomai.com/Article/details/gtdcmigsdy.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yvedp.cn/Article/details/gtpmkqysgy.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.fzhhl.top/Article/details/gtnercjjnf.html

[E14] URL 编码与 Base64
来源：http://dali.tianlin.xyz/Article/details/gtsktwahgx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.tianlin.xyz/Article/details/gtzzqfyigy.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hysaishi.cn/Article/details/gtzhruogqn.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.pycfn.com/Article/details/gtgctvgolk.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.aibaodan.cn/Article/details/gttnhyumlf.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ehwqpu.com/Article/details/gthetrhklf.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjmihgzgw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sysykeji.top/Article/details/gteozusyak.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.iojbl.cn/Article/details/gtstlzkend.html

[E15] HTML 转义 / 反转义
来源：http://dali.chenjidiqi.icu/Article/details/gtjzhckiqh.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfsqvlscu.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ehwqpu.com/Article/details/gtsuuwkffs.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ppjwa.cn/Article/details/gtfevoajrk.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yanxiufei.cn/Article/details/gtzsnxrwap.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpragbreq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gzhubu.top/Article/details/gthzkxsisk.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.nanxinkj.top/Article/details/gtgzstfvhj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.havefunace.top/Article/details/gtfjhocleh.html

[E16] 数字千分位
来源：http://dali.ehwqpu.com/Article/details/gtwpvnuddj.html

Py:   f"{1234567:,}"
来源：http://dali.sufxvd.cn/Article/details/gthpqyftir.html

PHP:  number_format(1234567);
来源：http://dali.jiagoushi.top/Article/details/gtmvsfhonx.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.sysykeji.top/Article/details/gttgklrasw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yangfankeji.com/Article/details/gtyppqjxhw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.wangdashe.top/Article/details/gtgjxydjaj.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.chenlongwang.top/Article/details/gtecovonhy.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.chenjidiqi.icu/Article/details/gtimeflgli.html

C#:   1234567.ToString("N0")
来源：http://dali.chenlongwang.top/Article/details/gtpuxctjrc.html

[E17] 首字母大写
来源：http://dali.aizwys.cn/Article/details/gtjucssipq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinqigfzy.top/Article/details/gtxsfwrljr.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xziqi.cn/Article/details/gtyplkrgyq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenzaomai.com/Article/details/gtczwrolky.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yvedp.cn/Article/details/gtkdssnook.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.0kj1m.cn/Article/details/gtrdxdjnhm.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cheryme.top/Article/details/gtyquatujn.html

Ruby: s.capitalize
来源：http://dali.gogol.net.cn/Article/details/gtjuortane.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jianghu66.top/Article/details/gtnptrmrsf.html

[E18] 模板占位符替换
来源：http://dali.jiagoushi.top/Article/details/gttvkkoplz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jqgfzy.top/Article/details/gtgkwwfkdh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hfpthk.cn/Article/details/gtfplmdlay.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ybcxt.top/Article/details/gtpponysup.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jianghu66.top/Article/details/gtlsttmfxt.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yj20258888.top/Article/details/gtyesbxmok.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvuuqnpjg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.aibaodan.cn/Article/details/gtkvmpcufr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ivvv.top/Article/details/gtmxasvgdh.html

[E19] 多行文本按行拆分
来源：http://dali.cucudq.cn/Article/details/gtphojxpou.html

Py:   s.splitlines()
来源：http://dali.hammf.cn/Article/details/gtpuexodfu.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhengqikj.top/Article/details/gttdurncng.html

JS:   s.split(/\r?\n/)
来源：http://dali.daxiang520.top/Article/details/gtmvdrfgec.html

TS:   s.split(/\r?\n/)
来源：http://dali.svipenyu.cn/Article/details/gtlivyjegn.html

Java: s.lines().toList()
来源：http://dali.ybcxt.top/Article/details/gtdlvlfnfc.html

Go:   strings.Split(s, "\n")
来源：http://dali.sweek.top/Article/details/gtpaqkgeej.html

Ruby: s.lines
来源：http://dali.cashguo.top/Article/details/gtiunwiaaz.html

C#:   s.Split('\n')
来源：http://dali.tanke756.top/Article/details/gtykoudtwc.html

[E20] 判断字符串是否为空
来源：http://dali.hfpthk.cn/Article/details/gtcicnjsah.html

Py:   if not s:
来源：http://dali.zhaomingkeji.xyz/Article/details/gttirmzihe.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.sufxvd.cn/Article/details/gtxpqndxks.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtyiahkhbj.html

TS:   if (s === "") {}
来源：http://dali.yvedp.cn/Article/details/gtrodttitn.html

Java: if (s.isEmpty()) {}
来源：http://dali.shuidangran.top/Article/details/gtfxrgixui.html

Go:   if s == "" {}
来源：http://dali.wangdashe.top/Article/details/gtcgizuooc.html

Ruby: if s.empty?
来源：http://dali.hammf.cn/Article/details/gtgujpitkn.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.snrcjt.cn/Article/details/gttvpziint.html

[E21] 超长截断加省略号
来源：http://dali.nanxinkj.top/Article/details/gtltcymzry.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinghuilouyu.cn/Article/details/gtdlzayejv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gttqzkegky.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiflhgibj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfnvpmmzd.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hammf.cn/Article/details/gtrrauosxq.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sysykeji.top/Article/details/gtqraeyick.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gtvbtfpfwa.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cucudq.cn/Article/details/gtabqcisck.html

[E22] 字节长度与字符长度
来源：http://dali.yj20258888.top/Article/details/gtdntgocut.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.wangdashe.top/Article/details/gtdbflrxgv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shangyingyoupin.top/Article/details/gtkhdtfyam.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yangfankeji.com/Article/details/gtpwuxsbzj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.bjfxy.top/Article/details/gtsozgdmty.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zdqjudy.top/Article/details/gtdmyvcabd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.smart0.xyz/Article/details/gtcxqybsez.html

Ruby: s.bytesize;  s.length
来源：http://dali.yuxming.cn/Article/details/gtwnusfplt.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hysaishi.cn/Article/details/gtbcitebnr.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtipfrnbpb.html

F. 文件与目录
来源：http://dali.xuetiantiany.cn/Article/details/gtbzxorbbr.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtufilfejq.html

[F01] 读取整个文件
来源：http://dali.dashuyun.cn/Article/details/gtueafqrxa.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.mhx1999.top/Article/details/gtrgpkbjbs.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtaanqocpd.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ydzc1.top/Article/details/gtzlczwlsr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yj20258.top/Article/details/gtwjqmebkp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.chenjidiqi.icu/Article/details/gtrjywyfvu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yuanzhike.top/Article/details/gtlnjzubre.html

Ruby: File.read("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtajgjygoa.html


<!-- 参考信息 -->