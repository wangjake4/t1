代发 wailian999

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shzxlz.cn/Article/details/gtdbfuiqax.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guannengcc.top/Article/details/gtvmnejsrq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.aizwys.cn/Article/details/gtuwwslncy.html

Go:   // 手写循环累加
来源：http://dali.aibaodan.cn/Article/details/gtakmorsmk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.wangshuangyany.cn/Article/details/gtbghvqfdv.html

C#:   list.Sum();  list.Average()
来源：http://dali.chenjidiqi.icu/Article/details/gtyboikwvy.html

[D17] 最大值与最小值
来源：http://dali.meibo888.top/Article/details/gtrqdslguy.html

Py:   max(arr);  min(arr)
来源：http://dali.sxryk.cn/Article/details/gtlctkbukt.html

PHP:  max($arr);  min($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtmzyqwihy.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtqwxcbpcz.html

TS:   Math.max(...arr);
来源：http://dali.xinyue.icu/Article/details/gtudgdomva.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.daxiang520.top/Article/details/gtmylhrbcj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtfvibtzdd.html

Ruby: arr.max;  arr.min
来源：http://dali.tian-w.cn/Article/details/gtybrcjoug.html

C#:   list.Max();  list.Min()
来源：http://dali.vqdsnc.cn/Article/details/gtdxujxldv.html

[D18] 扁平化嵌套数组
来源：http://dali.yanxiufei.cn/Article/details/gtmjffnklv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ehwqpu.com/Article/details/gttoufqtis.html

PHP:  array_merge(...$nested);
来源：http://dali.yanxiufei.cn/Article/details/gtdawnckrd.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.tian-w.cn/Article/details/gtpjfkcvhw.html

TS:   nested.flat();
来源：http://dali.hywenlv.cn/Article/details/gtncgpgtwv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.haohaochexian.top/Article/details/gtfogdbuhh.html

Go:   // 手写双层循环
来源：http://dali.fzhhl.top/Article/details/gtqwqtuwxn.html

Ruby: nested.flatten
来源：http://dali.yuxming.cn/Article/details/gtvjonwlii.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.mhx1999.top/Article/details/gtmfjafvjd.html

[D19] 按字段分组
来源：http://dali.hammf.cn/Article/details/gtrrpfgsgs.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.vqdsnc.cn/Article/details/gtrvtxfdyh.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkumfszic.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xylfe.cn/Article/details/gthoovuiqh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shanyushiyangkeji.top/Article/details/gteiojevzn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ppjwa.cn/Article/details/gtlfzpncul.html

Go:   // 手写 map[string][]T
来源：http://dali.zhongyouzk.top/Article/details/gteosthbmr.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cdnleiting.top/Article/details/gtjpvuyasq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yuanzhike.top/Article/details/gtlvphfbqh.html

[D20] 统计每个元素出现次数
来源：http://dali.chenzaomai.com/Article/details/gtmnvcfqyw.html

Py:   Counter(arr)
来源：http://dali.ehwqpu.com/Article/details/gtohgvvxnh.html

PHP:  array_count_values($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtljegtiry.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.c1oappe.top/Article/details/gtqhvdlbuo.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ppjwa.cn/Article/details/gtccqifoxb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.c1oappe.top/Article/details/gtlnsjnrav.html

Go:   // 手写 map[T]int
来源：http://dali.yueranfly.top/Article/details/gtzawfurvn.html

Ruby: arr.tally
来源：http://dali.shanyushiyangtech.top/Article/details/gtoiyaoati.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.pycfn.com/Article/details/gtzyhjydlh.html

[D21] 判断是否包含某元素
来源：http://dali.bjfxy.top/Article/details/gtbknaguyd.html

Py:   x in arr
来源：http://dali.xuetiantiany.cn/Article/details/gtlxcieymh.html

PHP:  in_array($x, $arr, true);
来源：http://dali.redwolf501.top/Article/details/gtlhyzjwns.html

JS:   arr.includes(x)
来源：http://dali.wangdashe.top/Article/details/gtzdigchql.html

TS:   arr.includes(x)
来源：http://dali.yueranfly.top/Article/details/gtnothengw.html

Java: list.contains(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtqroqmfed.html

Go:   slices.Contains(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtgwxvtaee.html

Ruby: arr.include?(x)
来源：http://dali.ehwqpu.com/Article/details/gthodfofus.html

C#:   list.Contains(x)
来源：http://dali.jianghu66.top/Article/details/gtlkgkzsiy.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cucudq.cn/Article/details/gtzsbtonhj.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.sxryk.cn/Article/details/gtrwuufudt.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sweek.top/Article/details/gthtvlfjuq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xziqi.cn/Article/details/gtvivkczvq.html

TS:   [...arr];
来源：http://dali.mhx1999.top/Article/details/gtxvisrjsl.html

Java: new ArrayList<>(list);
来源：http://dali.andypj.xyz/Article/details/gtirchhnag.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinqigfzy.top/Article/details/gtrtmyrwuz.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hysaishi.cn/Article/details/gtsneehrwi.html

C#:   new List<int>(list);
来源：http://dali.hammf.cn/Article/details/gthhxecnjr.html

[D23] reduce 累积计算
来源：http://dali.nanxuanxn.top/Article/details/gteomjfsie.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtidvlfpcy.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xziqi.cn/Article/details/gtmbhdtbno.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpskrgjxg.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtvvppenei.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.kuanghao11.cn/Article/details/gtsuczxrea.html

Go:   // 手写循环
来源：http://dali.c1oappe.top/Article/details/gtcwkmzydv.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jianghu66.top/Article/details/gtmhtvnlip.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.aibaodan.cn/Article/details/gtrhypvihx.html

[D24] 字典 / Map 基本操作
来源：http://dali.andypj.xyz/Article/details/gtyymfvcyv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgwcvlhof.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.9152youxi.cn/Article/details/gtmqgzsqrk.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jyoumei.cn/Article/details/gtquukkvez.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shzxlz.cn/Article/details/gtmgvtaubk.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.chenzaomai.com/Article/details/gthsgisrer.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xziqi.cn/Article/details/gtkfhplriw.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.fengsongda.top/Article/details/gtigeuctvk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shangyingyoupin.top/Article/details/gtvxrmggac.html

[D25] Set 集合去重与交并差
来源：http://dali.shanyushiyangtech.top/Article/details/gtomecgcln.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtevqnqmtt.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhiwuduotai.top/Article/details/gtumqcsjro.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.guannengcc.top/Article/details/gtttbujbin.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hammf.cn/Article/details/gtdbzourzd.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yangfankeji.com/Article/details/gtramctbnc.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.pengpengdd.cyou/Article/details/gtfzjxjhcp.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sysykeji.top/Article/details/gtozatmpae.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.sweek.top/Article/details/gtrvlpltnm.html

[D26] 数组转字符串
来源：http://dali.birdmap.top/Article/details/gtoaajgsxl.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yuxming.cn/Article/details/gttjoiolli.html

PHP:  implode(", ", $arr);
来源：http://dali.zhoulong.xyz/Article/details/gtjrnjehmk.html

JS:   arr.join(", ")
来源：http://dali.daria6918.cn/Article/details/gtnhlsgigg.html

TS:   arr.join(", ")
来源：http://dali.wangshuangyany.cn/Article/details/gtirlziofx.html

Java: String.join(", ", list)
来源：http://dali.chenzaomai.com/Article/details/gtunqbydhk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yj20258.top/Article/details/gtppdzvqth.html

Ruby: arr.join(", ")
来源：http://dali.ehwqpu.com/Article/details/gtrtybkwla.html

C#:   string.Join(", ", list)
来源：http://dali.hnqzz.top/Article/details/gtnncpjhco.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtucoudttm.html

E. 字符串处理
来源：http://dali.jiagoushi.top/Article/details/gtibmdzbhs.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtkbcdkajo.html

[E01] 拼接字符串
来源：http://dali.redwolf501.top/Article/details/gtmnzfrshm.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yvedp.cn/Article/details/gtfaialcwz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.chenjidiqi.icu/Article/details/gtsptncvkd.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yvedp.cn/Article/details/gtlyqsnnhm.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtejxonebr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.redwolf501.top/Article/details/gtsxyjwekf.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.aizwys.cn/Article/details/gtpaxpozhs.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hongshengwenyu.top/Article/details/gtghhnloxh.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gtaolwfkzp.html

[E02] 重复字符串
来源：http://dali.andypj.xyz/Article/details/gtfoputqlm.html

Py:   "ab" * 3
来源：http://dali.zhengqikj.top/Article/details/gtdtsehjky.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ppjwa.cn/Article/details/gtshmhcheu.html

JS:   "ab".repeat(3)
来源：http://dali.sufxvd.cn/Article/details/gtqsroedqz.html

TS:   "ab".repeat(3)
来源：http://dali.shzxlz.cn/Article/details/gtvvnttqnx.html

Java: "ab".repeat(3)
来源：http://dali.dianchejie.cn/Article/details/gtbklkrsrm.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cucudq.cn/Article/details/gtzbatkwoj.html

Ruby: "ab" * 3
来源：http://dali.yangfankeji.com/Article/details/gtafsxznsz.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jianghu66.top/Article/details/gtrwepsjiw.html

[E03] 截取子串
来源：http://dali.cqqwz.cn/Article/details/gtnmwqexge.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.mhx1999.top/Article/details/gtihsxhlhk.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gtwqjmzlym.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yj202588.top/Article/details/gtknbbgypc.html

TS:   s.slice(1, 4)
来源：http://dali.hnxiangtu.top/Article/details/gtjdhmyirg.html

Java: s.substring(1, 4)
来源：http://dali.shuidangran.top/Article/details/gtketbgbfd.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtorbyzmqs.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jlsjyb.cn/Article/details/gtjmfbyany.html

C#:   s.Substring(1, 3)
来源：http://dali.redwolf501.top/Article/details/gtgexvkdhr.html

[E04] 查找子串位置
来源：http://dali.shanyushiyangkeji.top/Article/details/gtawpcrbjw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.guowangkeji.top/Article/details/gtgtkxrrqg.html

PHP:  strpos($s, "x");
来源：http://dali.pengpengdd.cyou/Article/details/gtrlcnuxgh.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqbvaxypl.html

TS:   s.indexOf("x")
来源：http://dali.shzxlz.cn/Article/details/gtsizkydpp.html

Java: s.indexOf("x")
来源：http://dali.yj20258.top/Article/details/gtpnhdpzvp.html

Go:   strings.Index(s, "x")
来源：http://dali.316326.xyz/Article/details/gtybdgqask.html

Ruby: s.index("x")
来源：http://dali.mhx1999.top/Article/details/gtghdytgzw.html

C#:   s.IndexOf("x")
来源：http://dali.dashuyun.cn/Article/details/gttjzrwcxq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ybcxt.top/Article/details/gtfmruohfi.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.nanxuanxn.top/Article/details/gtdkmilcoj.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jqgufenzy.top/Article/details/gttzvtpgjc.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhoulong.xyz/Article/details/gtzieloccw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.chenjidiqi.icu/Article/details/gtpqujzzoz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.dashuyun.cn/Article/details/gtrvldvplg.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jyoumei.cn/Article/details/gttwfvauej.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hnxiangtu.top/Article/details/gtakrmdejz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.tianlin.xyz/Article/details/gtgvauwmrh.html

[E06] 替换子串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtngmwmiqu.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.bjfxy.top/Article/details/gtcpaswaji.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.tian-w.cn/Article/details/gtfeiboykg.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gtznvlmqji.html

TS:   s.replaceAll("a", "b")
来源：http://dali.mhx1999.top/Article/details/gtoclghzrz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.mhx1999.top/Article/details/gttbwpestu.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.meibo888.top/Article/details/gteawnbamh.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zycfv.cn/Article/details/gtkvrztopb.html

C#:   s.Replace("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gtwrgeriwc.html

[E07] 按分隔符拆分
来源：http://dali.ppjwa.cn/Article/details/gtrkvosgfd.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.gzhubu.top/Article/details/gtmlhrltwg.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.fzhhl.top/Article/details/gtdbioefmi.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cqqwz.cn/Article/details/gtglbqhams.html

TS:   s.split(",")
来源：http://dali.zycfv.cn/Article/details/gtcggzhtxx.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.c1oappe.top/Article/details/gtaztuxmnh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.haohaochexian.top/Article/details/gtdeiamabi.html

Ruby: s.split(",");  s.split
来源：http://dali.jlsjyb.cn/Article/details/gtmaccmegu.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.smart0.xyz/Article/details/gtwvewcauh.html

[E08] 数组按分隔符合并
来源：http://dali.feifeiyinyue.top/Article/details/gtoskteuts.html

Py:   ",".join(items)
来源：http://dali.haohaochexian.top/Article/details/gtsccpotxn.html

PHP:  implode(",", $items);
来源：http://dali.yonumen.top/Article/details/gtxgficrgh.html

JS:   items.join(",")
来源：http://dali.fzhhl.top/Article/details/gtuetlhhor.html

TS:   items.join(",")
来源：http://dali.hongshengwenyu.top/Article/details/gtdqjdrefv.html

Java: String.join(",", items)
来源：http://dali.snrcjt.cn/Article/details/gtizgelwtx.html

Go:   strings.Join(items, ",")
来源：http://dali.yj20258.top/Article/details/gtvtetxron.html

Ruby: items.join(",")
来源：http://dali.gzhubu.top/Article/details/gtuzkyjfth.html

C#:   string.Join(",", items)
来源：http://dali.xinyue.icu/Article/details/gtqiveoqfs.html

[E09] 去除所有空白字符
来源：http://dali.jinqigufen.top/Article/details/gttgcbgufa.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.nwbrower.top/Article/details/gtauukbpfr.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.meibo888.top/Article/details/gtkkwmumjf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xylfe.cn/Article/details/gtmltvnvix.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.wangshuangyany.cn/Article/details/gtqyntdoiw.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xylfe.cn/Article/details/gtakvvlkdt.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.bjfxy.top/Article/details/gtojtmabpo.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.meibo888.top/Article/details/gtbzwbhaeh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.vqdsnc.cn/Article/details/gthtoivrxp.html

[E10] 左侧补零 / 定长填充
来源：http://dali.redwolf501.top/Article/details/gthmpfdnaw.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hongshengwenyu.top/Article/details/gtfrbtqxjs.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhiwuduotai.top/Article/details/gtlzvgyryr.html

JS:   "7".padStart(3, "0")
来源：http://dali.hywenlv.cn/Article/details/gtziovdygb.html

TS:   "7".padStart(3, "0")
来源：http://dali.aizwys.cn/Article/details/gtlezhklpl.html

Java: String.format("%03d", 7)
来源：http://dali.ppjwa.cn/Article/details/gtqtyztdct.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbrpfcagh.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.mhx1999.top/Article/details/gtaisehgmp.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.feifeiyinyue.top/Article/details/gtevnzndml.html

[E11] 反转字符串
来源：http://dali.iojbl.cn/Article/details/gtwnquboui.html

Py:   s[::-1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqiqoqzud.html

PHP:  strrev($s);
来源：http://dali.dashuyun.cn/Article/details/gtdjrvhsxh.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gtnvncudyo.html

TS:   [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gtafxbgllx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yuanzhike.top/Article/details/gtfxszzcmr.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sxryk.cn/Article/details/gtxoiwdqkt.html

Ruby: s.reverse
来源：http://dali.hnqzz.top/Article/details/gtsfoircyj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xziqi.cn/Article/details/gtyrieeylk.html

[E12] 统计某字符出现次数
来源：http://dali.zhengqikj.top/Article/details/gtgswizoia.html

Py:   s.count("a")
来源：http://dali.yj202588.top/Article/details/gtvucvgnif.html

PHP:  substr_count($s, "a");
来源：http://dali.jiagoushi.top/Article/details/gtbdeghfuu.html

JS:   s.split("a").length - 1
来源：http://dali.gogol.net.cn/Article/details/gtuvxevqjj.html

TS:   s.split("a").length - 1
来源：http://dali.daxiang520.top/Article/details/gtszedzkry.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cucudq.cn/Article/details/gtqrouqznw.html

Go:   strings.Count(s, "a")
来源：http://dali.xziqi.cn/Article/details/gtcwahdtup.html

Ruby: s.count("a")
来源：http://dali.jqgufenzy.top/Article/details/gtpklyqkkv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jianghu66.top/Article/details/gtjqijjfaz.html

[E13] 逐字符遍历
来源：http://dali.fengsongda.top/Article/details/gtnzutkaor.html

Py:   for ch in s: print(ch)
来源：http://dali.tian-w.cn/Article/details/gtxunflzeq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhengqikj.top/Article/details/gtcqnlskpm.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nwbrower.top/Article/details/gtxgskokba.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gaohongyu789.top/Article/details/gtiodyppuk.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.pycfn.com/Article/details/gtjhwiqdti.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zycfv.cn/Article/details/gtcyfnamcp.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.316326.xyz/Article/details/gtgorqhafk.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.kuanghao11.cn/Article/details/gtxjhercxz.html

[E14] URL 编码与 Base64
来源：http://dali.yueranfly.top/Article/details/gtwyboihfs.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.9152youxi.cn/Article/details/gtvopcjymm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtaiyrzubl.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cashguo.top/Article/details/gtxmymsvbd.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.9152youxi.cn/Article/details/gtiqqdvauq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sysykeji.top/Article/details/gthfjyjsdc.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xylfe.cn/Article/details/gtwbpktnkj.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.gaohongyu789.top/Article/details/gtmjceredn.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtopalptra.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhiwuduotai.top/Article/details/gtlmgouwxv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gotoacloud.top/Article/details/gtptsuvcoe.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.vqdsnc.cn/Article/details/gtjovinnkv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cucudq.cn/Article/details/gtknpkimxh.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.tianlin.xyz/Article/details/gtgpttlwow.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.smart0.xyz/Article/details/gtfksooegd.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.guowangkeji.top/Article/details/gttoukpigm.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.daxiang520.top/Article/details/gtsngaevvu.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ivvv.top/Article/details/gtwesejjub.html

[E16] 数字千分位
来源：http://dali.zycfv.cn/Article/details/gtyofduwky.html

Py:   f"{1234567:,}"
来源：http://dali.yj20258.top/Article/details/gtstkvpjyt.html

PHP:  number_format(1234567);
来源：http://dali.tanke756.top/Article/details/gtlhbnwmpj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.gogol.net.cn/Article/details/gtqlcnoxgc.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shangyingyoupin.top/Article/details/gtpvqdvtsd.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xuetiantiany.cn/Article/details/gtxjfsojki.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.birdmap.top/Article/details/gtcoiswwnt.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ppjwa.cn/Article/details/gtdfwdhxpc.html

C#:   1234567.ToString("N0")
来源：http://dali.guannengcc.top/Article/details/gtbslhokop.html

[E17] 首字母大写
来源：http://dali.ybcxt.top/Article/details/gtudafpzhe.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.nanxinkj.top/Article/details/gtuyayyjqa.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.andypj.xyz/Article/details/gtxtwgddzk.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhongyouzk.top/Article/details/gtyuwuuzwj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfkipnhgx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gaohongyu789.top/Article/details/gtycfjbbke.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.pengpengdd.cyou/Article/details/gtcmmepjyt.html

Ruby: s.capitalize
来源：http://dali.gaohongyu789.top/Article/details/gttxehwsis.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xinyue.icu/Article/details/gtyydkbprf.html

[E18] 模板占位符替换
来源：http://dali.quarkkingdee.top/Article/details/gtvuzdtxal.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinqigufen.top/Article/details/gtguhknxvi.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.feifeiyinyue.top/Article/details/gtiariwkhd.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gtdwxlttbv.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.tian-w.cn/Article/details/gtmogayyaj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsdiyjxhm.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtirtrizwp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhengqikj.top/Article/details/gtxavocjwf.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.feifeiyinyue.top/Article/details/gtobqgigyg.html

[E19] 多行文本按行拆分
来源：http://dali.zdqjudy.top/Article/details/gttqnfcnbd.html

Py:   s.splitlines()
来源：http://dali.zhoulong.xyz/Article/details/gtsannrvjw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.haohaochexian.top/Article/details/gtqmzwtyeb.html

JS:   s.split(/\r?\n/)
来源：http://dali.hfpthk.cn/Article/details/gtcyauwkao.html

TS:   s.split(/\r?\n/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcgwxllhf.html

Java: s.lines().toList()
来源：http://dali.gogol.net.cn/Article/details/gtwlsjgwzr.html

Go:   strings.Split(s, "\n")
来源：http://dali.pengpengdd.cyou/Article/details/gthbcdjaqk.html

Ruby: s.lines
来源：http://dali.yangfankeji.com/Article/details/gteqfsjpqo.html

C#:   s.Split('\n')
来源：http://dali.iojbl.cn/Article/details/gtbggdxpmk.html

[E20] 判断字符串是否为空
来源：http://dali.hnxiangtu.top/Article/details/gtnxveejuz.html

Py:   if not s:
来源：http://dali.mhx1999.top/Article/details/gtcmhcaogx.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shuidangran.top/Article/details/gtdnvkwwtw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hnqzz.top/Article/details/gtescszqmg.html

TS:   if (s === "") {}
来源：http://dali.smart0.xyz/Article/details/gtvocsjmtn.html

Java: if (s.isEmpty()) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtmrxogbtm.html

Go:   if s == "" {}
来源：http://dali.guannengcc.top/Article/details/gtabllzmiu.html

Ruby: if s.empty?
来源：http://dali.jianghu66.top/Article/details/gtbmjlqbws.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhoulong.xyz/Article/details/gtgegrqzrg.html

[E21] 超长截断加省略号
来源：http://dali.kuanghao11.cn/Article/details/gtkzbkqcdp.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.havefunace.top/Article/details/gtloesrfhu.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhiwuduotai.top/Article/details/gtrecswlam.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtbjaxmjnv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gtjnptpbxm.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yj20258888.top/Article/details/gtccynlmgd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shuidangran.top/Article/details/gtxffuxsxn.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zycfv.cn/Article/details/gtgexbddud.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.fengsongda.top/Article/details/gtztsdvwbc.html

[E22] 字节长度与字符长度
来源：http://dali.zdqjudy.top/Article/details/gtvqcyhixx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.guowangkeji.top/Article/details/gtsnezkwyy.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ydzc1.top/Article/details/gtvxzyefjr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.feifeiyinyue.top/Article/details/gtdwknjvhv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.0kj1m.cn/Article/details/gttzglyzsk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gotoacloud.top/Article/details/gtfsghlyan.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zycfv.cn/Article/details/gtfkvvosgs.html

Ruby: s.bytesize;  s.length
来源：http://dali.chenjidiqi.icu/Article/details/gtbwbyouex.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.tian-w.cn/Article/details/gttjitdsfc.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtlhhdbnkm.html

F. 文件与目录
来源：http://dali.sweek.top/Article/details/gtwvxyrdao.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtgcotvtah.html


<!-- 参考信息 -->