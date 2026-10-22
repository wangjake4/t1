代发 wailian999

[D19] 按字段分组
来源：http://dali.jinqigfzy.top/Article/details/gtwfqmughy.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.316326.xyz/Article/details/gtnpgzjawq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.pengpengdd.cyou/Article/details/gtjuhqzjgy.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.fzhhl.top/Article/details/gthendjqbl.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.smart0.xyz/Article/details/gtnojxiffr.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shanyushiyangtech.top/Article/details/gtvccxzpvm.html

Go:   // 手写 map[string][]T
来源：http://dali.shanyushiyangtech.top/Article/details/gtcemlslqn.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gtcptacktt.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.fzhhl.top/Article/details/gtbcbedvkm.html

[D20] 统计每个元素出现次数
来源：http://dali.guowangkeji.top/Article/details/gtvvbhcirg.html

Py:   Counter(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtyxbmpnbw.html

PHP:  array_count_values($arr);
来源：http://dali.cqqwz.cn/Article/details/gtviwpkwth.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pycfn.com/Article/details/gtrzdwgdwo.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.daxiang520.top/Article/details/gtgtslkmax.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.tanke756.top/Article/details/gtblzkluwr.html

Go:   // 手写 map[T]int
来源：http://dali.sufxvd.cn/Article/details/gtkhvzkpcf.html

Ruby: arr.tally
来源：http://dali.jinqigfzy.top/Article/details/gtyifaumvg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ybcxt.top/Article/details/gthjguwdql.html

[D21] 判断是否包含某元素
来源：http://dali.jqgfzy.top/Article/details/gtuaofjdpw.html

Py:   x in arr
来源：http://dali.jianghu66.top/Article/details/gtkwiopsit.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhixingplan.top/Article/details/gtxmgkkscm.html

JS:   arr.includes(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtclhtwgpb.html

TS:   arr.includes(x)
来源：http://dali.jyoumei.cn/Article/details/gtsbojsmtb.html

Java: list.contains(x)
来源：http://dali.ybcxt.top/Article/details/gtssfmdcma.html

Go:   slices.Contains(arr, x)
来源：http://dali.xuanzx.com/Article/details/gttpmiqyec.html

Ruby: arr.include?(x)
来源：http://dali.zdqjudy.top/Article/details/gtouljxrpt.html

C#:   list.Contains(x)
来源：http://dali.cdnleiting.top/Article/details/gtxzszofsf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cucudq.cn/Article/details/gtydfbnfnt.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jianghu66.top/Article/details/gtunpeblee.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.smart0.xyz/Article/details/gtocpsjuxq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtgfgrphrb.html

TS:   [...arr];
来源：http://dali.vqdsnc.cn/Article/details/gtpsxmhrya.html

Java: new ArrayList<>(list);
来源：http://dali.nanxuanxn.top/Article/details/gtmnqdnkds.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xuanzx.com/Article/details/gtjwdospry.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sufxvd.cn/Article/details/gtcnueojbe.html

C#:   new List<int>(list);
来源：http://dali.wangdashe.top/Article/details/gtmuibpkhy.html

[D23] reduce 累积计算
来源：http://dali.xylfe.cn/Article/details/gtnixzdomr.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtzczdeifk.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtitbjyrrs.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cucudq.cn/Article/details/gtcmptvyio.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cashguo.top/Article/details/gtnhlrvpdj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtouedhitc.html

Go:   // 手写循环
来源：http://dali.yj20258888.top/Article/details/gthhaqzgsw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yj20258888.top/Article/details/gtlulyxrip.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sweek.top/Article/details/gtzlrqtofp.html

[D24] 字典 / Map 基本操作
来源：http://dali.yj202588.top/Article/details/gtssblyqtj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.redwolf501.top/Article/details/gtsssrdhpl.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yvedp.cn/Article/details/gtntsznolx.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xuanzx.com/Article/details/gtluuzbexa.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.0kj1m.cn/Article/details/gtgofopbxn.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shuidangran.top/Article/details/gtcqjojijn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gtddoptgym.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jyoumei.cn/Article/details/gtusuhzgch.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hysaishi.cn/Article/details/gtswecmrku.html

[D25] Set 集合去重与交并差
来源：http://dali.jyoumei.cn/Article/details/gtaiuxkhjj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.mhx1999.top/Article/details/gtgxrwkvrb.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.pengpengdd.cyou/Article/details/gtkjvmbwod.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yvedp.cn/Article/details/gtslfunyum.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.daria6918.cn/Article/details/gtxzglfktm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shzxlz.cn/Article/details/gtdgbuuwpl.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhixingplan.top/Article/details/gtyhrxefet.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ydzc1.top/Article/details/gtxfsujjjp.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.snrcjt.cn/Article/details/gtqblktuav.html

[D26] 数组转字符串
来源：http://dali.9152youxi.cn/Article/details/gtbnntbvpi.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jinqigufen.top/Article/details/gtiafsxryv.html

PHP:  implode(", ", $arr);
来源：http://dali.zhixingplan.top/Article/details/gtbgqbyiuq.html

JS:   arr.join(", ")
来源：http://dali.sweek.top/Article/details/gtlnajcqgw.html

TS:   arr.join(", ")
来源：http://dali.nanxuanxn.top/Article/details/gtqeoiutnk.html

Java: String.join(", ", list)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgzmzipbi.html

Go:   strings.Join(strs, ", ")
来源：http://dali.chenzaomai.com/Article/details/gtnvytorea.html

Ruby: arr.join(", ")
来源：http://dali.0kj1m.cn/Article/details/gtxbyrpnby.html

C#:   string.Join(", ", list)
来源：http://dali.kuanghao11.cn/Article/details/gtfyvmwsub.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtzsdsxnfn.html

E. 字符串处理
来源：http://dali.wangshuangyany.cn/Article/details/gtsqpclthe.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtlwgxiqzw.html

[E01] 拼接字符串
来源：http://dali.cheryme.top/Article/details/gtozngvcnp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.nanxuanxn.top/Article/details/gtxhbwimqc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zdqjudy.top/Article/details/gtrfqzfskk.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.0kj1m.cn/Article/details/gtkzcwrbvx.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.quarkkingdee.top/Article/details/gtalpzxoqz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hywenlv.cn/Article/details/gtvtocvsas.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.aibaodan.cn/Article/details/gtlbnjdpxt.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sweek.top/Article/details/gtxnmopfcd.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gtqrloyhae.html

[E02] 重复字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttrjqduog.html

Py:   "ab" * 3
来源：http://dali.hnxiangtu.top/Article/details/gtroqenqau.html

PHP:  str_repeat("ab", 3);
来源：http://dali.snrcjt.cn/Article/details/gtfrtetiio.html

JS:   "ab".repeat(3)
来源：http://dali.sweek.top/Article/details/gtzuhmxmys.html

TS:   "ab".repeat(3)
来源：http://dali.quarkkingdee.top/Article/details/gtrocgxbzs.html

Java: "ab".repeat(3)
来源：http://dali.jqgufenzy.top/Article/details/gtitxtauug.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jianghu66.top/Article/details/gtdxvlzdhe.html

Ruby: "ab" * 3
来源：http://dali.shangyingyoupin.top/Article/details/gtwttpinlm.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yongpay.top/Article/details/gtacuslzoo.html

[E03] 截取子串
来源：http://dali.yj202588.top/Article/details/gtlwygfisd.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ivvv.top/Article/details/gtrpcmuvez.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gtyjzzgisl.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhengqikj.top/Article/details/gtqdsqnseo.html

TS:   s.slice(1, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gtpdfcrqel.html

Java: s.substring(1, 4)
来源：http://dali.guowangkeji.top/Article/details/gtyirsdnuf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.316326.xyz/Article/details/gtkisfhbdj.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.havefunace.top/Article/details/gtodmgcjeo.html

C#:   s.Substring(1, 3)
来源：http://dali.meibo888.top/Article/details/gtaeqdiwkr.html

[E04] 查找子串位置
来源：http://dali.aizwys.cn/Article/details/gtfrzdpatq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sweek.top/Article/details/gtccdkwdfh.html

PHP:  strpos($s, "x");
来源：http://dali.guannengcc.top/Article/details/gtnxzxeoti.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.feifeiyinyue.top/Article/details/gtnkpqqytp.html

TS:   s.indexOf("x")
来源：http://dali.gogol.net.cn/Article/details/gtfbmwyzqj.html

Java: s.indexOf("x")
来源：http://dali.havefunace.top/Article/details/gtgszslnel.html

Go:   strings.Index(s, "x")
来源：http://dali.zhoulong.xyz/Article/details/gtwvlcgyoa.html

Ruby: s.index("x")
来源：http://dali.andypj.xyz/Article/details/gtlqnskojx.html

C#:   s.IndexOf("x")
来源：http://dali.mhx1999.top/Article/details/gtivrwbidq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.tanke756.top/Article/details/gtyuxmvzpd.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.0kj1m.cn/Article/details/gtzmauakqu.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.dianchejie.cn/Article/details/gtqolxaauo.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.wangshuangyany.cn/Article/details/gtrujanyyr.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shangyingyoupin.top/Article/details/gtcfpmfzdi.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.mhx1999.top/Article/details/gtgxpfwklw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.nanxuanxn.top/Article/details/gtdadkrrnu.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hysaishi.cn/Article/details/gtkgnmnqjr.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hysaishi.cn/Article/details/gtxvevaxgd.html

[E06] 替换子串
来源：http://dali.guannengcc.top/Article/details/gtvkinpipp.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.gogol.net.cn/Article/details/gtbdlmodul.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtqfgpunhy.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.smart0.xyz/Article/details/gtxogqbpzk.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ybcxt.top/Article/details/gtlxxkbexa.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cheryme.top/Article/details/gtxtmbcjtx.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jianghu66.top/Article/details/gteymsnqks.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gtszfuxywa.html

C#:   s.Replace("a", "b")
来源：http://dali.daria6918.cn/Article/details/gteaceaolm.html

[E07] 按分隔符拆分
来源：http://dali.chenlongwang.top/Article/details/gtfryckbek.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.snrcjt.cn/Article/details/gtdfnibrvo.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hnxiangtu.top/Article/details/gttmstqsfw.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yvedp.cn/Article/details/gtquulvqum.html

TS:   s.split(",")
来源：http://dali.yj20258888.top/Article/details/gtilaquwsr.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zycfv.cn/Article/details/gthiaaueuc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.svipenyu.cn/Article/details/gtsdgqjayq.html

Ruby: s.split(",");  s.split
来源：http://dali.nanxuanxn.top/Article/details/gtmqrpxint.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jqgfzy.top/Article/details/gtpumfhwca.html

[E08] 数组按分隔符合并
来源：http://dali.sufxvd.cn/Article/details/gtbltbqjpb.html

Py:   ",".join(items)
来源：http://dali.guannengcc.top/Article/details/gtjyxeqage.html

PHP:  implode(",", $items);
来源：http://dali.0kj1m.cn/Article/details/gttdbdydke.html

JS:   items.join(",")
来源：http://dali.hongshengwenyu.top/Article/details/gtsftstrqy.html

TS:   items.join(",")
来源：http://dali.ydzc1.top/Article/details/gtbjyronyg.html

Java: String.join(",", items)
来源：http://dali.tian-w.cn/Article/details/gtrxmxydmj.html

Go:   strings.Join(items, ",")
来源：http://dali.cucudq.cn/Article/details/gtvosymkux.html

Ruby: items.join(",")
来源：http://dali.hywenlv.cn/Article/details/gtbtuehism.html

C#:   string.Join(",", items)
来源：http://dali.yangfankeji.com/Article/details/gtsjppjxnb.html

[E09] 去除所有空白字符
来源：http://dali.kuanghao11.cn/Article/details/gtnmalzuox.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ybcxt.top/Article/details/gtdqulujxd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yj20258.top/Article/details/gtgtelilfn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigufen.top/Article/details/gtmgofkgkr.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cheryme.top/Article/details/gtdrpbiqfj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yonumen.top/Article/details/gtrxtpbpns.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.c1oappe.top/Article/details/gtvvjrsscd.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.9152youxi.cn/Article/details/gtxyuyuujo.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.wangshuangyany.cn/Article/details/gtxsvfnicg.html

[E10] 左侧补零 / 定长填充
来源：http://dali.bjfxy.top/Article/details/gtpxvdmbgu.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhoulong.xyz/Article/details/gtwbwqawsw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.birdmap.top/Article/details/gtxcqwykpa.html

JS:   "7".padStart(3, "0")
来源：http://dali.316326.xyz/Article/details/gtnxexoogd.html

TS:   "7".padStart(3, "0")
来源：http://dali.316326.xyz/Article/details/gtkbojfymh.html

Java: String.format("%03d", 7)
来源：http://dali.yongpay.top/Article/details/gtiyehvfkm.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shuidangran.top/Article/details/gtdoclmzsr.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shangyingyoupin.top/Article/details/gtteninfwl.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yj20258.top/Article/details/gtmixpdoue.html

[E11] 反转字符串
来源：http://dali.sufxvd.cn/Article/details/gtynqfqphz.html

Py:   s[::-1]
来源：http://dali.bjfxy.top/Article/details/gtksntdopr.html

PHP:  strrev($s);
来源：http://dali.fengsongda.top/Article/details/gtbminnqfh.html

JS:   [...s].reverse().join("")
来源：http://dali.cdnleiting.top/Article/details/gtkxqkwvwi.html

TS:   [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gtdhftucng.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xziqi.cn/Article/details/gtdhydglxz.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yvedp.cn/Article/details/gtvzmjthfi.html

Ruby: s.reverse
来源：http://dali.yongpay.top/Article/details/gthuvwxywj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.chenzaomai.com/Article/details/gtjpycbcvu.html

[E12] 统计某字符出现次数
来源：http://dali.yuxming.cn/Article/details/gtlrunnqmc.html

Py:   s.count("a")
来源：http://dali.zhengqikj.top/Article/details/gtdfuzlenh.html

PHP:  substr_count($s, "a");
来源：http://dali.yj202588.top/Article/details/gtrsvoxxrt.html

JS:   s.split("a").length - 1
来源：http://dali.xuetiantiany.cn/Article/details/gthucwujud.html

TS:   s.split("a").length - 1
来源：http://dali.yvedp.cn/Article/details/gtekeerkja.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jiagoushi.top/Article/details/gtdiyeoslr.html

Go:   strings.Count(s, "a")
来源：http://dali.316326.xyz/Article/details/gtzxwydine.html

Ruby: s.count("a")
来源：http://dali.zhongyouzk.top/Article/details/gtwvltafzu.html

C#:   s.Count(c => c == 'a')
来源：http://dali.pengpengdd.cyou/Article/details/gtgcdmkyep.html

[E13] 逐字符遍历
来源：http://dali.cdnleiting.top/Article/details/gtkesesuys.html

Py:   for ch in s: print(ch)
来源：http://dali.hammf.cn/Article/details/gtviljkkrk.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.snrcjt.cn/Article/details/gtkqwipqto.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbgvftcou.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvecancsq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gzhubu.top/Article/details/gtoexarxsz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.pengpengdd.cyou/Article/details/gtyshcheki.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhoulong.xyz/Article/details/gtkrlnibjk.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jiagoushi.top/Article/details/gtjauresze.html

[E14] URL 编码与 Base64
来源：http://dali.zhixingplan.top/Article/details/gtzjlcfsdf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yangfankeji.com/Article/details/gtajovvhjz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaaqplsts.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.pengpengdd.cyou/Article/details/gtqshswxyr.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.smart0.xyz/Article/details/gtdsejbhmt.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.daxiang520.top/Article/details/gtnteetbds.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhixingplan.top/Article/details/gtztqxdbcn.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jinqigfzy.top/Article/details/gtwwsldxos.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfviixeuj.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhongyouzk.top/Article/details/gtkoorpkqp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.tanke756.top/Article/details/gtxfawoyoo.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.tianlin.xyz/Article/details/gtnpoyafyp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shzxlz.cn/Article/details/gtgrgwcoac.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xylfe.cn/Article/details/gtuqzokbrt.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzofiidtc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtfitndiqd.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.quarkkingdee.top/Article/details/gtsjgyodvp.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cucudq.cn/Article/details/gtrgvqvpqf.html

[E16] 数字千分位
来源：http://dali.chenzaomai.com/Article/details/gtdmouazgp.html

Py:   f"{1234567:,}"
来源：http://dali.yuxming.cn/Article/details/gtmpoiylzx.html

PHP:  number_format(1234567);
来源：http://dali.mhx1999.top/Article/details/gtbavoxcev.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxuanxn.top/Article/details/gtzefubesi.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hnxiangtu.top/Article/details/gtsoszkrzi.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.wangdashe.top/Article/details/gthetdoksf.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yj202588.top/Article/details/gtafahqpja.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhongyouzk.top/Article/details/gtoigmsfaw.html

C#:   1234567.ToString("N0")
来源：http://dali.316326.xyz/Article/details/gtpcavpcgf.html

[E17] 首字母大写
来源：http://dali.cheryme.top/Article/details/gtuagztelx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.guowangkeji.top/Article/details/gtmurbwnyw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yongpay.top/Article/details/gtuvlzmyev.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yueranfly.top/Article/details/gthgzgdzne.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yangfankeji.com/Article/details/gtvhfhzgke.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.snrcjt.cn/Article/details/gtnljnglrv.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinqigfzy.top/Article/details/gtaraxthvc.html

Ruby: s.capitalize
来源：http://dali.fengsongda.top/Article/details/gtffrxzghp.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hnqzz.top/Article/details/gtvbywtfpn.html

[E18] 模板占位符替换
来源：http://dali.zhiwuduotai.top/Article/details/gtdaddvcoy.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsiauoctc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.pycfn.com/Article/details/gtucexjzio.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yueranfly.top/Article/details/gtqskwqmlu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sysykeji.top/Article/details/gtsayaynxq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gttiywtknw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ivvv.top/Article/details/gtkbjgoegj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.wangdashe.top/Article/details/gtqxqrbpoa.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jiagoushi.top/Article/details/gttmcgjruv.html

[E19] 多行文本按行拆分
来源：http://dali.xuanzx.com/Article/details/gtorzwdvsg.html

Py:   s.splitlines()
来源：http://dali.guowangkeji.top/Article/details/gtfhphqgqz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.dianchejie.cn/Article/details/gtmkqsvljp.html

JS:   s.split(/\r?\n/)
来源：http://dali.ybcxt.top/Article/details/gtbpwhtipj.html

TS:   s.split(/\r?\n/)
来源：http://dali.guowangkeji.top/Article/details/gtrranxocg.html

Java: s.lines().toList()
来源：http://dali.iojbl.cn/Article/details/gtfefocwjq.html

Go:   strings.Split(s, "\n")
来源：http://dali.shangyingyoupin.top/Article/details/gtyleytsoj.html

Ruby: s.lines
来源：http://dali.shanyushiyangtech.top/Article/details/gtcbutyfyi.html

C#:   s.Split('\n')
来源：http://dali.fengsongda.top/Article/details/gtxgfnmwle.html

[E20] 判断字符串是否为空
来源：http://dali.nanxinkj.top/Article/details/gtfdpimjat.html

Py:   if not s:
来源：http://dali.gaohongyu789.top/Article/details/gtzcikmbmc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.redwolf501.top/Article/details/gtzeszzddu.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.havefunace.top/Article/details/gtakgodzgm.html

TS:   if (s === "") {}
来源：http://dali.svipenyu.cn/Article/details/gtlflvvcai.html

Java: if (s.isEmpty()) {}
来源：http://dali.havefunace.top/Article/details/gtnofxqnlw.html

Go:   if s == "" {}
来源：http://dali.nwbrower.top/Article/details/gtvlbadffe.html

Ruby: if s.empty?
来源：http://dali.aibaodan.cn/Article/details/gttlfgipdy.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yj202588.top/Article/details/gtcvinqxfs.html

[E21] 超长截断加省略号
来源：http://dali.hywenlv.cn/Article/details/gtusmwfkas.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yuxming.cn/Article/details/gtjahteqav.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gtrpyonpjv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gtdjdgkmcg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gtxcmodujs.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.smart0.xyz/Article/details/gtfshgmjve.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shangyingyoupin.top/Article/details/gtonbnyagp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtvpjlkvrr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.havefunace.top/Article/details/gtmlgwiyka.html

[E22] 字节长度与字符长度
来源：http://dali.redwolf501.top/Article/details/gtztzdqhww.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yanxiufei.cn/Article/details/gtqifnoldn.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gtadfbbhwk.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangdashe.top/Article/details/gtkqfjyjuj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.birdmap.top/Article/details/gtdlusroev.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.nwbrower.top/Article/details/gtjstpfcec.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.0kj1m.cn/Article/details/gtatswrppn.html

Ruby: s.bytesize;  s.length
来源：http://dali.tian-w.cn/Article/details/gtbtgpufsh.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gzhubu.top/Article/details/gtoxcnyiws.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtewjhehgb.html

F. 文件与目录
来源：http://dali.shangyingyoupin.top/Article/details/gtgmoomaep.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtbxvoitxk.html

[F01] 读取整个文件
来源：http://dali.xuanzx.com/Article/details/gtwwluzjoe.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hammf.cn/Article/details/gtzzomtoyj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtrfcmfthc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.pycfn.com/Article/details/gtamdpnofd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hongshengwenyu.top/Article/details/gtscukrbie.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gtwapfdeud.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.kuanghao11.cn/Article/details/gthtkzlqlu.html

Ruby: File.read("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtehgavdgq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtrfkrjluy.html

[F02] 逐行读取文件
来源：http://dali.smart0.xyz/Article/details/gtdodkirso.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shanyushiyangtech.top/Article/details/gtmtcbprmb.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.daria6918.cn/Article/details/gtmbeqgohj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zdqjudy.top/Article/details/gtdlpsoqqu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtqnczqznt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtasgtzrfp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.feifeiyinyue.top/Article/details/gtpgogtjpv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.nwbrower.top/Article/details/gtorxdfipb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jqgfzy.top/Article/details/gtviuajojh.html

[F03] 写入文件（覆盖）
来源：http://dali.jqgfzy.top/Article/details/gtsgmedqdc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hnxiangtu.top/Article/details/gtwkbhfdjv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jqgfzy.top/Article/details/gttjiftgfe.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hfpthk.cn/Article/details/gtessasmyu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxuanxn.top/Article/details/gtedyhrlfw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtliugrmhw.html


<!-- 参考信息 -->