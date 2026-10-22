代发 wailian999

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.dianchejie.cn/Article/details/gthxmseigb.html

Go:   // 手写双层循环
来源：http://dali.wangshuangyany.cn/Article/details/gtucnmljbo.html

Ruby: nested.flatten
来源：http://dali.9152youxi.cn/Article/details/gttixiujyt.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhengqikj.top/Article/details/gtspqiogoj.html

[D19] 按字段分组
来源：http://dali.haohaochexian.top/Article/details/gtygktlybj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hywenlv.cn/Article/details/gtibfjnzdk.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.tian-w.cn/Article/details/gtvkpszfhr.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.fzhhl.top/Article/details/gtufsvytpr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cheryme.top/Article/details/gtrauomoxq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.iojbl.cn/Article/details/gtabxcxfco.html

Go:   // 手写 map[string][]T
来源：http://dali.ehwqpu.com/Article/details/gtqnjzxwur.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jiagoushi.top/Article/details/gtwpwsnhkx.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yanxiufei.cn/Article/details/gticovopdm.html

[D20] 统计每个元素出现次数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyindryle.html

Py:   Counter(arr)
来源：http://dali.hammf.cn/Article/details/gtuzqupoqq.html

PHP:  array_count_values($arr);
来源：http://dali.sweek.top/Article/details/gttnefikes.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zycfv.cn/Article/details/gthoeaokjf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.feifeiyinyue.top/Article/details/gtmynshcnr.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jqgufenzy.top/Article/details/gtvbshsdku.html

Go:   // 手写 map[T]int
来源：http://dali.hongshengwenyu.top/Article/details/gthqnhfubo.html

Ruby: arr.tally
来源：http://dali.cheryme.top/Article/details/gtqwuwqtyc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hnqzz.top/Article/details/gtzdivxskz.html

[D21] 判断是否包含某元素
来源：http://dali.yvedp.cn/Article/details/gtbwfkwfbr.html

Py:   x in arr
来源：http://dali.tian-w.cn/Article/details/gtlpvfqpfk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.redwolf501.top/Article/details/gtqiqsseya.html

JS:   arr.includes(x)
来源：http://dali.yuanzhike.top/Article/details/gtbvosnebk.html

TS:   arr.includes(x)
来源：http://dali.daxiang520.top/Article/details/gtjpwpsnek.html

Java: list.contains(x)
来源：http://dali.cheryme.top/Article/details/gtcgaduzop.html

Go:   slices.Contains(arr, x)
来源：http://dali.yongpay.top/Article/details/gtmpztmhdb.html

Ruby: arr.include?(x)
来源：http://dali.nwbrower.top/Article/details/gthpqwfjfq.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gtshymytyb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ehwqpu.com/Article/details/gtuwbwypwx.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.aibaodan.cn/Article/details/gtvyydfxvf.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shzxlz.cn/Article/details/gtbvixkmpi.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cheryme.top/Article/details/gtedduqnua.html

TS:   [...arr];
来源：http://dali.chenlongwang.top/Article/details/gtnelbtqkt.html

Java: new ArrayList<>(list);
来源：http://dali.jianghu66.top/Article/details/gtksxrraxc.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwtrsrija.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cucudq.cn/Article/details/gtssebgthq.html

C#:   new List<int>(list);
来源：http://dali.havefunace.top/Article/details/gthqfumiiw.html

[D23] reduce 累积计算
来源：http://dali.zhoulong.xyz/Article/details/gtchgzkslx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtqncnuiwy.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yj20258888.top/Article/details/gtmszssatn.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hfpthk.cn/Article/details/gteskmmmex.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daxiang520.top/Article/details/gtckocwxsz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdfkytlvf.html

Go:   // 手写循环
来源：http://dali.dashuyun.cn/Article/details/gtdfvahzby.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.mhx1999.top/Article/details/gteinayith.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.wangdashe.top/Article/details/gthflagpxj.html

[D24] 字典 / Map 基本操作
来源：http://dali.xziqi.cn/Article/details/gtgxsriszs.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.nanxuanxn.top/Article/details/gtcpskhbmx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.aibaodan.cn/Article/details/gtsmyhpkkc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shuidangran.top/Article/details/gtplwpxgae.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.tanke756.top/Article/details/gtbspryqib.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnlemmsjm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yvedp.cn/Article/details/gthjdnfdbj.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xuetiantiany.cn/Article/details/gtpyddmuii.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hywenlv.cn/Article/details/gtgnynlprs.html

[D25] Set 集合去重与交并差
来源：http://dali.jianghu66.top/Article/details/gtotirabak.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.gzhubu.top/Article/details/gtarsnaadd.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yuxming.cn/Article/details/gtzidfquru.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinqigfzy.top/Article/details/gtkbefmujs.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.feifeiyinyue.top/Article/details/gtjfncpteg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.pycfn.com/Article/details/gtslkkdqai.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hnxiangtu.top/Article/details/gtohuaczup.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.daxiang520.top/Article/details/gtqopckajt.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cashguo.top/Article/details/gtxnnmcusw.html

[D26] 数组转字符串
来源：http://dali.gzhubu.top/Article/details/gtuycowyhn.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jianghu66.top/Article/details/gtqkxyhcre.html

PHP:  implode(", ", $arr);
来源：http://dali.nanxinkj.top/Article/details/gtqppdwqol.html

JS:   arr.join(", ")
来源：http://dali.haohaochexian.top/Article/details/gtensuwovr.html

TS:   arr.join(", ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnoqomkop.html

Java: String.join(", ", list)
来源：http://dali.ivvv.top/Article/details/gtshghptjp.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ydzc1.top/Article/details/gtxhevjigj.html

Ruby: arr.join(", ")
来源：http://dali.yvedp.cn/Article/details/gtohpvsygc.html

C#:   string.Join(", ", list)
来源：http://dali.gaohongyu789.top/Article/details/gthzagrpxl.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtqpaofrup.html

E. 字符串处理
来源：http://dali.gaohongyu789.top/Article/details/gtntjzcund.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtsucayuzc.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gthpakmrtv.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.aizwys.cn/Article/details/gtuybuddeo.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.svipenyu.cn/Article/details/gtikfmqaeg.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.dashuyun.cn/Article/details/gtthnrrwvn.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzmxrltmg.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.gaohongyu789.top/Article/details/gtgvmyxnvk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.chenzaomai.com/Article/details/gtyfwsjjfi.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.dianchejie.cn/Article/details/gtdjhvbrne.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtgnruehjn.html

[E02] 重复字符串
来源：http://dali.hysaishi.cn/Article/details/gtigddsxyt.html

Py:   "ab" * 3
来源：http://dali.smart0.xyz/Article/details/gtwtfjrbro.html

PHP:  str_repeat("ab", 3);
来源：http://dali.chenzaomai.com/Article/details/gtasqhasqh.html

JS:   "ab".repeat(3)
来源：http://dali.kuanghao11.cn/Article/details/gtpncqriwb.html

TS:   "ab".repeat(3)
来源：http://dali.yueranfly.top/Article/details/gtrnnyzthw.html

Java: "ab".repeat(3)
来源：http://dali.ppjwa.cn/Article/details/gtnphkdevf.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.nanxinkj.top/Article/details/gtqtebvbmc.html

Ruby: "ab" * 3
来源：http://dali.wangdashe.top/Article/details/gtxwtkdpwq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.sufxvd.cn/Article/details/gtfnyzxvqd.html

[E03] 截取子串
来源：http://dali.fengsongda.top/Article/details/gtojgooqiy.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.meibo888.top/Article/details/gtxevmmwkc.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.pycfn.com/Article/details/gthlllatfn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.meibo888.top/Article/details/gtxuokqsag.html

TS:   s.slice(1, 4)
来源：http://dali.sysykeji.top/Article/details/gtivrfmfjq.html

Java: s.substring(1, 4)
来源：http://dali.chenjidiqi.icu/Article/details/gtosulmmxx.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.redwolf501.top/Article/details/gtrxwpwskj.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.kuanghao11.cn/Article/details/gthgvchlks.html

C#:   s.Substring(1, 3)
来源：http://dali.svipenyu.cn/Article/details/gtskaivsug.html

[E04] 查找子串位置
来源：http://dali.tian-w.cn/Article/details/gtguabjbrv.html

Py:   s.find("x");  s.index("x")
来源：http://dali.guannengcc.top/Article/details/gtxgbnqxas.html

PHP:  strpos($s, "x");
来源：http://dali.jinqigfzy.top/Article/details/gtcbigrzeq.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.nanxuanxn.top/Article/details/gtzjostmtp.html

TS:   s.indexOf("x")
来源：http://dali.feifeiyinyue.top/Article/details/gtwizedcer.html

Java: s.indexOf("x")
来源：http://dali.fzhhl.top/Article/details/gtmkfldgod.html

Go:   strings.Index(s, "x")
来源：http://dali.tanke756.top/Article/details/gtuxupnecy.html

Ruby: s.index("x")
来源：http://dali.jinqigufen.top/Article/details/gtwlyoavst.html

C#:   s.IndexOf("x")
来源：http://dali.hnxiangtu.top/Article/details/gtwcsixwjv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hammf.cn/Article/details/gtobtvehvg.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhoulong.xyz/Article/details/gtnqdawmhm.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hnqzz.top/Article/details/gtgamwmxjm.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj20258.top/Article/details/gtdykmqteb.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.andypj.xyz/Article/details/gtbeosavwj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.guannengcc.top/Article/details/gtucrtadft.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.aizwys.cn/Article/details/gtgdjgsexh.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.daria6918.cn/Article/details/gtqnylkxqg.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xuetiantiany.cn/Article/details/gtnuqsyjdm.html

[E06] 替换子串
来源：http://dali.jqgfzy.top/Article/details/gtaxawjgxo.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.fengsongda.top/Article/details/gtuzcvcumc.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtgiksdvfe.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gtmdnecqet.html

TS:   s.replaceAll("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gtmimskndk.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gtyjjzkrsl.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yj20258888.top/Article/details/gtotxbhgdd.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ivvv.top/Article/details/gtaachegwd.html

C#:   s.Replace("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtiostfgdw.html

[E07] 按分隔符拆分
来源：http://dali.tianlin.xyz/Article/details/gtqchojzdf.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgzxhbldv.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.bjfxy.top/Article/details/gtnrtpyakk.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cucudq.cn/Article/details/gtxfzzcldg.html

TS:   s.split(",")
来源：http://dali.9152youxi.cn/Article/details/gtmoxbfcmi.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shuidangran.top/Article/details/gtbztwttdb.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.316326.xyz/Article/details/gtlycbvgro.html

Ruby: s.split(",");  s.split
来源：http://dali.snrcjt.cn/Article/details/gtbhaoxdzk.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcmficmkl.html

[E08] 数组按分隔符合并
来源：http://dali.tianlin.xyz/Article/details/gttgczhfja.html

Py:   ",".join(items)
来源：http://dali.yueranfly.top/Article/details/gtwdnvoivg.html

PHP:  implode(",", $items);
来源：http://dali.daxiang520.top/Article/details/gtfuyhshhk.html

JS:   items.join(",")
来源：http://dali.iojbl.cn/Article/details/gtxipcepqf.html

TS:   items.join(",")
来源：http://dali.havefunace.top/Article/details/gtwhkoipap.html

Java: String.join(",", items)
来源：http://dali.jlsjyb.cn/Article/details/gtmkpcdics.html

Go:   strings.Join(items, ",")
来源：http://dali.xinyue.icu/Article/details/gtotcukett.html

Ruby: items.join(",")
来源：http://dali.cheryme.top/Article/details/gtszeszgzm.html

C#:   string.Join(",", items)
来源：http://dali.hysaishi.cn/Article/details/gtbzanbjvw.html

[E09] 去除所有空白字符
来源：http://dali.xziqi.cn/Article/details/gteofmjuws.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.smart0.xyz/Article/details/gtipyqsjix.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cdnleiting.top/Article/details/gtmxpgafqy.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jyoumei.cn/Article/details/gthrycclku.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shzxlz.cn/Article/details/gtludjizsv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.nanxinkj.top/Article/details/gtlflieosw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhijiandao.cn/Article/details/gtjxqjpcvs.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.tanke756.top/Article/details/gtqyyqsnqe.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jlsjyb.cn/Article/details/gtteftojju.html

[E10] 左侧补零 / 定长填充
来源：http://dali.andypj.xyz/Article/details/gtamggluuc.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhiwuduotai.top/Article/details/gtwdvgeidl.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cucudq.cn/Article/details/gtopbclsnv.html

JS:   "7".padStart(3, "0")
来源：http://dali.zdqjudy.top/Article/details/gtmrndsbwn.html

TS:   "7".padStart(3, "0")
来源：http://dali.nanxinkj.top/Article/details/gtxzhvcbyk.html

Java: String.format("%03d", 7)
来源：http://dali.xinyue.icu/Article/details/gtmndtlwra.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yuxming.cn/Article/details/gtrvkkjcit.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yangfankeji.com/Article/details/gtnrwqrqay.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhengqikj.top/Article/details/gthhfekomi.html

[E11] 反转字符串
来源：http://dali.hfpthk.cn/Article/details/gtnlasdyra.html

Py:   s[::-1]
来源：http://dali.ehwqpu.com/Article/details/gtjkqhjhne.html

PHP:  strrev($s);
来源：http://dali.dianchejie.cn/Article/details/gtazfclpch.html

JS:   [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gtnokiuuyc.html

TS:   [...s].reverse().join("")
来源：http://dali.yj202588.top/Article/details/gtdfxexcfv.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.daxiang520.top/Article/details/gtzadsrepr.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jlsjyb.cn/Article/details/gtermlgsfs.html

Ruby: s.reverse
来源：http://dali.aibaodan.cn/Article/details/gtwejcopin.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhongyouzk.top/Article/details/gtotxdfztw.html

[E12] 统计某字符出现次数
来源：http://dali.yonumen.top/Article/details/gtmkyprkgq.html

Py:   s.count("a")
来源：http://dali.zdqjudy.top/Article/details/gtrlwyuzff.html

PHP:  substr_count($s, "a");
来源：http://dali.jlsjyb.cn/Article/details/gtetaxktvq.html

JS:   s.split("a").length - 1
来源：http://dali.guowangkeji.top/Article/details/gtdygnodgi.html

TS:   s.split("a").length - 1
来源：http://dali.jqgfzy.top/Article/details/gtizqyloog.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.daria6918.cn/Article/details/gtivowrpvm.html

Go:   strings.Count(s, "a")
来源：http://dali.andypj.xyz/Article/details/gtcceplzoc.html

Ruby: s.count("a")
来源：http://dali.chenjidiqi.icu/Article/details/gtmoltwowj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yuanzhike.top/Article/details/gtsacpabsx.html

[E13] 逐字符遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxvbaahct.html

Py:   for ch in s: print(ch)
来源：http://dali.snrcjt.cn/Article/details/gthfpydhmc.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmzsrvozk.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuhtdnqdw.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.andypj.xyz/Article/details/gtinldqejm.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.chenzaomai.com/Article/details/gtwwqppnez.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gaohongyu789.top/Article/details/gtqnnrvjkg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.iojbl.cn/Article/details/gtxezrqhid.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sweek.top/Article/details/gtcspnsscs.html

[E14] URL 编码与 Base64
来源：http://dali.birdmap.top/Article/details/gtdnjdntud.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cucudq.cn/Article/details/gtctjwkrsf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.haohaochexian.top/Article/details/gtbgtwnzmw.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sysykeji.top/Article/details/gtlnqqvscj.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xinyue.icu/Article/details/gtlydwhpbq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hammf.cn/Article/details/gtkizigepx.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.quarkkingdee.top/Article/details/gtdeozcvpn.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ivvv.top/Article/details/gtdfhscerf.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yj20258888.top/Article/details/gtkelkkqkf.html

[E15] HTML 转义 / 反转义
来源：http://dali.sxryk.cn/Article/details/gtkscdpodv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sweek.top/Article/details/gtivrsftki.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.smart0.xyz/Article/details/gtbhtfjgnd.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hywenlv.cn/Article/details/gtxiuuriba.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhoulong.xyz/Article/details/gtgeluspcv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.chenlongwang.top/Article/details/gtleuagwyl.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuerupiex.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.fzhhl.top/Article/details/gtjbupcscu.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shzxlz.cn/Article/details/gtimfmgduv.html

[E16] 数字千分位
来源：http://dali.mhx1999.top/Article/details/gtrwlnkwka.html

Py:   f"{1234567:,}"
来源：http://dali.gotoacloud.top/Article/details/gtjzshjhsa.html

PHP:  number_format(1234567);
来源：http://dali.yuxming.cn/Article/details/gttjekgcpm.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxinkj.top/Article/details/gtsngheieo.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xinyue.icu/Article/details/gtbgoprhha.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xuanzx.com/Article/details/gtomfqoxzk.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.nanxinkj.top/Article/details/gtaxgudels.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.c1oappe.top/Article/details/gtttgwijoz.html

C#:   1234567.ToString("N0")
来源：http://dali.nanxinkj.top/Article/details/gttcisxnqg.html

[E17] 首字母大写
来源：http://dali.dianchejie.cn/Article/details/gtkpnraqxl.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.bjfxy.top/Article/details/gtdetwgbju.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtswcxevjj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.c1oappe.top/Article/details/gtydvhvzlc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gtwbqjmnoy.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.redwolf501.top/Article/details/gttxqtfxtp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zdqjudy.top/Article/details/gtoeqxmxni.html

Ruby: s.capitalize
来源：http://dali.9152youxi.cn/Article/details/gtuqbzsnan.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xinyue.icu/Article/details/gtchyoqjlq.html

[E18] 模板占位符替换
来源：http://dali.feifeiyinyue.top/Article/details/gtwycgaqjg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.316326.xyz/Article/details/gtxsjzzhdm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xylfe.cn/Article/details/gtnfhchmil.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cashguo.top/Article/details/gtxgnzxede.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gtpokgfchh.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xziqi.cn/Article/details/gtitgcposd.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gteivxpcbr.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.snrcjt.cn/Article/details/gtgmorwbdo.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.tianlin.xyz/Article/details/gthvradlfg.html

[E19] 多行文本按行拆分
来源：http://dali.sysykeji.top/Article/details/gtehsgehef.html

Py:   s.splitlines()
来源：http://dali.svipenyu.cn/Article/details/gtkjwuyzvh.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.meibo888.top/Article/details/gttjpchgfd.html

JS:   s.split(/\r?\n/)
来源：http://dali.0kj1m.cn/Article/details/gtlxzkjgro.html

TS:   s.split(/\r?\n/)
来源：http://dali.fengsongda.top/Article/details/gtjsyziibw.html

Java: s.lines().toList()
来源：http://dali.jqgufenzy.top/Article/details/gtvuzkeamn.html

Go:   strings.Split(s, "\n")
来源：http://dali.shangyingyoupin.top/Article/details/gtlremcdex.html

Ruby: s.lines
来源：http://dali.shangyingyoupin.top/Article/details/gtaplnfcsj.html

C#:   s.Split('\n')
来源：http://dali.guannengcc.top/Article/details/gtmqbqlujc.html

[E20] 判断字符串是否为空
来源：http://dali.ehwqpu.com/Article/details/gtsofxhabg.html

Py:   if not s:
来源：http://dali.jinqigfzy.top/Article/details/gtjqoqoxxr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ybcxt.top/Article/details/gtqslqxxru.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.9152youxi.cn/Article/details/gtwhqtateu.html

TS:   if (s === "") {}
来源：http://dali.gaohongyu789.top/Article/details/gtbwadvioh.html

Java: if (s.isEmpty()) {}
来源：http://dali.xuanzx.com/Article/details/gtjitqfxxv.html

Go:   if s == "" {}
来源：http://dali.yangfankeji.com/Article/details/gtqegmxtiq.html

Ruby: if s.empty?
来源：http://dali.ivvv.top/Article/details/gtxfuhrkza.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sysykeji.top/Article/details/gtagafskyo.html

[E21] 超长截断加省略号
来源：http://dali.xuanzx.com/Article/details/gtdkpnglnh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xziqi.cn/Article/details/gtmeycipgz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwxddndts.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.birdmap.top/Article/details/gtzzzqtgzb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gthprdyigg.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cheryme.top/Article/details/gtmblfjyid.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shzxlz.cn/Article/details/gtczxukjil.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.fengsongda.top/Article/details/gtwttkojzk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtuefcxgxb.html

[E22] 字节长度与字符长度
来源：http://dali.meibo888.top/Article/details/gtzkheojce.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.tianlin.xyz/Article/details/gtzhzaqlfr.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cheryme.top/Article/details/gtbddqvkub.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.haohaochexian.top/Article/details/gtrmnncmkd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenlongwang.top/Article/details/gtizybzzzz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.tianlin.xyz/Article/details/gtnuwyuwhi.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xylfe.cn/Article/details/gtdexhowub.html

Ruby: s.bytesize;  s.length
来源：http://dali.shanyushiyangtech.top/Article/details/gtdukzimzb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.316326.xyz/Article/details/gtmxxjlian.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtuidgakpz.html

F. 文件与目录
来源：http://dali.fengsongda.top/Article/details/gtpnjbdaqi.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiqrpgefx.html

[F01] 读取整个文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtxewmxyox.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.fzhhl.top/Article/details/gtpvkyfabv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtgskjsumb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yongpay.top/Article/details/gtliiaihmm.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ppjwa.cn/Article/details/gtogaiyvyt.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gtunansugy.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shanyushiyangtech.top/Article/details/gtghoxjdoh.html

Ruby: File.read("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtcsexjyyj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtpmbljwus.html

[F02] 逐行读取文件
来源：http://dali.sysykeji.top/Article/details/gtbjqhtsgq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.guowangkeji.top/Article/details/gtbysvhwsn.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ydzc1.top/Article/details/gtnghqjfet.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cucudq.cn/Article/details/gtljahceic.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gaohongyu789.top/Article/details/gtnyejvoyl.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ybcxt.top/Article/details/gtavhelgrf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.pengpengdd.cyou/Article/details/gtmaxpuart.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhixingplan.top/Article/details/gtzwarjhdv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.guannengcc.top/Article/details/gttmtzqmhq.html

[F03] 写入文件（覆盖）
来源：http://dali.tian-w.cn/Article/details/gtpqsrogml.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jqgfzy.top/Article/details/gtqcetzlnt.html


<!-- 参考信息 -->