代发 wailian999

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuqkhkaju.html

PHP:  array_merge(...$nested);
来源：http://dali.chenlongwang.top/Article/details/gtznbjfkln.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xylfe.cn/Article/details/gtyvgmuxkb.html

TS:   nested.flat();
来源：http://dali.hnxiangtu.top/Article/details/gtarndonma.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhengqikj.top/Article/details/gtuaivrzeo.html

Go:   // 手写双层循环
来源：http://dali.xuanzx.com/Article/details/gtfmkfbucp.html

Ruby: nested.flatten
来源：http://dali.bjfxy.top/Article/details/gtkbtwmgig.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.nanxinkj.top/Article/details/gtadmeftbj.html

[D19] 按字段分组
来源：http://dali.chenjidiqi.icu/Article/details/gtfzqsksjf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jyoumei.cn/Article/details/gtyruoqvtb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xziqi.cn/Article/details/gtswxqaazl.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ivvv.top/Article/details/gtsaehkpty.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.havefunace.top/Article/details/gtlraufsem.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.pycfn.com/Article/details/gttletrdrw.html

Go:   // 手写 map[string][]T
来源：http://dali.ybcxt.top/Article/details/gtsngjeeqz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.nwbrower.top/Article/details/gtxjzjothi.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yueranfly.top/Article/details/gtxxpucwbi.html

[D20] 统计每个元素出现次数
来源：http://dali.nanxuanxn.top/Article/details/gtcysbrvdi.html

Py:   Counter(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtfjmuwrwk.html

PHP:  array_count_values($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtaxqupwgb.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.0kj1m.cn/Article/details/gtmntubbkr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yanxiufei.cn/Article/details/gtnjireyuz.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jlsjyb.cn/Article/details/gtiltxnerm.html

Go:   // 手写 map[T]int
来源：http://dali.hongshengwenyu.top/Article/details/gtgzbcriwo.html

Ruby: arr.tally
来源：http://dali.c1oappe.top/Article/details/gtxkfnswti.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.nwbrower.top/Article/details/gtiivzrnsl.html

[D21] 判断是否包含某元素
来源：http://dali.yueranfly.top/Article/details/gtrjbpfghn.html

Py:   x in arr
来源：http://dali.gaohongyu789.top/Article/details/gtjpdjeggl.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfyhfkczx.html

JS:   arr.includes(x)
来源：http://dali.tian-w.cn/Article/details/gteevufypq.html

TS:   arr.includes(x)
来源：http://dali.cashguo.top/Article/details/gththsxqep.html

Java: list.contains(x)
来源：http://dali.yanxiufei.cn/Article/details/gtxxpjxoxq.html

Go:   slices.Contains(arr, x)
来源：http://dali.daxiang520.top/Article/details/gtdgsqftkf.html

Ruby: arr.include?(x)
来源：http://dali.birdmap.top/Article/details/gtrxfmlqlh.html

C#:   list.Contains(x)
来源：http://dali.yvedp.cn/Article/details/gtappwrafb.html

[D22] 复制数组（避免共享引用）
来源：http://dali.tian-w.cn/Article/details/gtbbnzpbwq.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cucudq.cn/Article/details/gtutmwtzpy.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.chenlongwang.top/Article/details/gttcixfsrm.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzeorpwrx.html

TS:   [...arr];
来源：http://dali.pycfn.com/Article/details/gtnmvygsrq.html

Java: new ArrayList<>(list);
来源：http://dali.nanxuanxn.top/Article/details/gtnmtmynsa.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzqoqgzwg.html

Ruby: arr.dup;  arr.clone
来源：http://dali.shanyushiyangtech.top/Article/details/gtcvfjnuxd.html

C#:   new List<int>(list);
来源：http://dali.svipenyu.cn/Article/details/gtxgccceow.html

[D23] reduce 累积计算
来源：http://dali.c1oappe.top/Article/details/gtajdgzihi.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ehwqpu.com/Article/details/gterpdnpdb.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cqqwz.cn/Article/details/gtobkfawyu.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sweek.top/Article/details/gtzevhgrol.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ppjwa.cn/Article/details/gtigkvrlxb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ppjwa.cn/Article/details/gtkrzbhifk.html

Go:   // 手写循环
来源：http://dali.cucudq.cn/Article/details/gtexsmftbi.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.chenlongwang.top/Article/details/gtxhfiemdn.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcxejjrgq.html

[D24] 字典 / Map 基本操作
来源：http://dali.ppjwa.cn/Article/details/gtnjnzdknm.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cashguo.top/Article/details/gtsyobxrbt.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.tianlin.xyz/Article/details/gtxrcuojhg.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.dashuyun.cn/Article/details/gtxaicduhv.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ehwqpu.com/Article/details/gtyruaewbc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xziqi.cn/Article/details/gtluhvnuwj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yangfankeji.com/Article/details/gtntgmzhvy.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xinyue.icu/Article/details/gtzcngivku.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hnxiangtu.top/Article/details/gtthynetsi.html

[D25] Set 集合去重与交并差
来源：http://dali.cheryme.top/Article/details/gtqkywjlih.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.kuanghao11.cn/Article/details/gtjuwxiugm.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jqgfzy.top/Article/details/gtqebqodoi.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jiagoushi.top/Article/details/gthtivyzun.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ivvv.top/Article/details/gtfgblghiw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqtqozdqo.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ehwqpu.com/Article/details/gtonpvrntr.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtstggxpwb.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yuanzhike.top/Article/details/gtctlkiyym.html

[D26] 数组转字符串
来源：http://dali.yvedp.cn/Article/details/gtpwaupxvf.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shangyingyoupin.top/Article/details/gtntehzaem.html

PHP:  implode(", ", $arr);
来源：http://dali.yj20258888.top/Article/details/gtokqacsrc.html

JS:   arr.join(", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtozbkbiyb.html

TS:   arr.join(", ")
来源：http://dali.zhongyouzk.top/Article/details/gtfsnkwyrp.html

Java: String.join(", ", list)
来源：http://dali.havefunace.top/Article/details/gtzgbnurjs.html

Go:   strings.Join(strs, ", ")
来源：http://dali.redwolf501.top/Article/details/gtfsofyfne.html

Ruby: arr.join(", ")
来源：http://dali.hammf.cn/Article/details/gtmzzivhgo.html

C#:   string.Join(", ", list)
来源：http://dali.yvedp.cn/Article/details/gtkfahqojm.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtznafxvqz.html

E. 字符串处理
来源：http://dali.gzhubu.top/Article/details/gtmfvalkbp.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtvffkuhjz.html

[E01] 拼接字符串
来源：http://dali.havefunace.top/Article/details/gtqqhaynbh.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhixingplan.top/Article/details/gtdoklpomd.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.316326.xyz/Article/details/gttymwkimj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.kuanghao11.cn/Article/details/gtaynteffp.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jianghu66.top/Article/details/gtihykhrcc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.gaohongyu789.top/Article/details/gttorkusqy.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.pengpengdd.cyou/Article/details/gtbxuoxppx.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jianghu66.top/Article/details/gtrdyhbhva.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtxbhexein.html

[E02] 重复字符串
来源：http://dali.yueranfly.top/Article/details/gtelzpfaxi.html

Py:   "ab" * 3
来源：http://dali.nanxinkj.top/Article/details/gtdjxqabzl.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gzhubu.top/Article/details/gtlmkgpbzw.html

JS:   "ab".repeat(3)
来源：http://dali.tianlin.xyz/Article/details/gtqurtgfdr.html

TS:   "ab".repeat(3)
来源：http://dali.pengpengdd.cyou/Article/details/gtjmvwripk.html

Java: "ab".repeat(3)
来源：http://dali.tian-w.cn/Article/details/gttvmwctzh.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.gaohongyu789.top/Article/details/gtmptmurqn.html

Ruby: "ab" * 3
来源：http://dali.xuanzx.com/Article/details/gtfxtgeevs.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hfpthk.cn/Article/details/gtmbwhszpq.html

[E03] 截取子串
来源：http://dali.jinqigfzy.top/Article/details/gtvwnszrou.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.aizwys.cn/Article/details/gtyyyvwguo.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.quarkkingdee.top/Article/details/gtulxcokyf.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hongshengwenyu.top/Article/details/gtmvaenptq.html

TS:   s.slice(1, 4)
来源：http://dali.haohaochexian.top/Article/details/gtdkbcapux.html

Java: s.substring(1, 4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgzhhuxlw.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xylfe.cn/Article/details/gtlfzwited.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.wangdashe.top/Article/details/gtnxedqbys.html

C#:   s.Substring(1, 3)
来源：http://dali.kuanghao11.cn/Article/details/gtrpbzquyx.html

[E04] 查找子串位置
来源：http://dali.xuanzx.com/Article/details/gthstglvlq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jyoumei.cn/Article/details/gtnsjppsoi.html

PHP:  strpos($s, "x");
来源：http://dali.kuanghao11.cn/Article/details/gtnwiwspwd.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sufxvd.cn/Article/details/gtpgsdjixq.html

TS:   s.indexOf("x")
来源：http://dali.0kj1m.cn/Article/details/gttizpikys.html

Java: s.indexOf("x")
来源：http://dali.tianlin.xyz/Article/details/gtpqlpgtym.html

Go:   strings.Index(s, "x")
来源：http://dali.cdnleiting.top/Article/details/gtbjqoyhtj.html

Ruby: s.index("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtogcklrxe.html

C#:   s.IndexOf("x")
来源：http://dali.zhiwuduotai.top/Article/details/gtaakifvif.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gtkouzqupu.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jianghu66.top/Article/details/gteohprfyo.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.tanke756.top/Article/details/gtvrhvahrp.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nanxinkj.top/Article/details/gtapavbawa.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hnxiangtu.top/Article/details/gtvrzjotsu.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.svipenyu.cn/Article/details/gthisggksp.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.svipenyu.cn/Article/details/gtxreaeadm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yuxming.cn/Article/details/gtmteqvpqz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shzxlz.cn/Article/details/gtvmpmcayo.html

[E06] 替换子串
来源：http://dali.zhiwuduotai.top/Article/details/gthiqwfdly.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jinqigufen.top/Article/details/gttjmpifsd.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtygtucqlo.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nwbrower.top/Article/details/gterdhmdnw.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cucudq.cn/Article/details/gtotlrefnf.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gtgzymngjn.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtzwqdvhim.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.gzhubu.top/Article/details/gtnckztisn.html

C#:   s.Replace("a", "b")
来源：http://dali.andypj.xyz/Article/details/gtdpmvxocx.html

[E07] 按分隔符拆分
来源：http://dali.andypj.xyz/Article/details/gtmxzngpef.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.havefunace.top/Article/details/gtjonkavnk.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.sufxvd.cn/Article/details/gttuofsaek.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.snrcjt.cn/Article/details/gtjqvanzfm.html

TS:   s.split(",")
来源：http://dali.fzhhl.top/Article/details/gtmaowehfl.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yuxming.cn/Article/details/gtxbucmgmv.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzfakakmf.html

Ruby: s.split(",");  s.split
来源：http://dali.316326.xyz/Article/details/gtxcwkpsrv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhoulong.xyz/Article/details/gtjgrvlpck.html

[E08] 数组按分隔符合并
来源：http://dali.yonumen.top/Article/details/gtxunvbijx.html

Py:   ",".join(items)
来源：http://dali.mhx1999.top/Article/details/gttgbnatov.html

PHP:  implode(",", $items);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtstafblfv.html

JS:   items.join(",")
来源：http://dali.xziqi.cn/Article/details/gttasqqxnh.html

TS:   items.join(",")
来源：http://dali.chenzaomai.com/Article/details/gtsozromqg.html

Java: String.join(",", items)
来源：http://dali.mhx1999.top/Article/details/gtpyrxklwl.html

Go:   strings.Join(items, ",")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqbzgpruu.html

Ruby: items.join(",")
来源：http://dali.dashuyun.cn/Article/details/gtmegeamcz.html

C#:   string.Join(",", items)
来源：http://dali.c1oappe.top/Article/details/gtrrlljjye.html

[E09] 去除所有空白字符
来源：http://dali.andypj.xyz/Article/details/gtprsxpwag.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ydzc1.top/Article/details/gtbrmosvyd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfhlstnbb.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yj20258.top/Article/details/gtxgnszspe.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yongpay.top/Article/details/gtcoctvdkl.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.9152youxi.cn/Article/details/gtzkkutnxr.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yanxiufei.cn/Article/details/gthjeqhzgr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.vqdsnc.cn/Article/details/gtevjsyhqf.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.c1oappe.top/Article/details/gthczroszo.html

[E10] 左侧补零 / 定长填充
来源：http://dali.tianlin.xyz/Article/details/gtnwtxqpgu.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhengqikj.top/Article/details/gtfylndrdk.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yueranfly.top/Article/details/gtppeskriw.html

JS:   "7".padStart(3, "0")
来源：http://dali.jianghu66.top/Article/details/gtzoncevuc.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinqigufen.top/Article/details/gthyfhafde.html

Java: String.format("%03d", 7)
来源：http://dali.guannengcc.top/Article/details/gtxjhwchzr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yuanzhike.top/Article/details/gtwyrmttka.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwsmtjbac.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.andypj.xyz/Article/details/gtmsydvagg.html

[E11] 反转字符串
来源：http://dali.tian-w.cn/Article/details/gtcwtigamd.html

Py:   s[::-1]
来源：http://dali.gotoacloud.top/Article/details/gthjvqpgye.html

PHP:  strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gteovggcsa.html

JS:   [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gttoelofxs.html

TS:   [...s].reverse().join("")
来源：http://dali.snrcjt.cn/Article/details/gtmtvqfgtm.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gaohongyu789.top/Article/details/gtnrrzwqze.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yongpay.top/Article/details/gtmlqnhzck.html

Ruby: s.reverse
来源：http://dali.yanxiufei.cn/Article/details/gtcbuixdsq.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hysaishi.cn/Article/details/gttuvpggsk.html

[E12] 统计某字符出现次数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjggoahmk.html

Py:   s.count("a")
来源：http://dali.cheryme.top/Article/details/gtmjmivdby.html

PHP:  substr_count($s, "a");
来源：http://dali.nanxinkj.top/Article/details/gtshtzgeva.html

JS:   s.split("a").length - 1
来源：http://dali.jinqigufen.top/Article/details/gtqaabofho.html

TS:   s.split("a").length - 1
来源：http://dali.hnqzz.top/Article/details/gtjtemmwqk.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.dianchejie.cn/Article/details/gtvamufvct.html

Go:   strings.Count(s, "a")
来源：http://dali.zhengqikj.top/Article/details/gtjlnhgtte.html

Ruby: s.count("a")
来源：http://dali.jianghu66.top/Article/details/gtugvhmcgh.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shuidangran.top/Article/details/gttefjdkit.html

[E13] 逐字符遍历
来源：http://dali.cheryme.top/Article/details/gtysfmrcjj.html

Py:   for ch in s: print(ch)
来源：http://dali.nwbrower.top/Article/details/gttvmbfnpt.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.quarkkingdee.top/Article/details/gtmquhlkhn.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhiwuduotai.top/Article/details/gtxoddghzx.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cqqwz.cn/Article/details/gthmhgklxv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.aibaodan.cn/Article/details/gtzefesuem.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yj20258888.top/Article/details/gtfcykyclh.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shangyingyoupin.top/Article/details/gtkzdrsvqx.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jyoumei.cn/Article/details/gtnbonobup.html

[E14] URL 编码与 Base64
来源：http://dali.bjfxy.top/Article/details/gtwcxufwnw.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sufxvd.cn/Article/details/gtytnsglbz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.chenzaomai.com/Article/details/gtkrxgamni.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.andypj.xyz/Article/details/gtrkzfdwin.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.dianchejie.cn/Article/details/gtglvupuce.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.svipenyu.cn/Article/details/gtcamwqxhh.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.pycfn.com/Article/details/gtniogrgwa.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ydzc1.top/Article/details/gtxzxtalpd.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhengqikj.top/Article/details/gtvpuehosx.html

[E15] HTML 转义 / 反转义
来源：http://dali.kuanghao11.cn/Article/details/gtmwtiuspv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yj20258888.top/Article/details/gtksftggma.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.tianlin.xyz/Article/details/gtpvcwbppz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.quarkkingdee.top/Article/details/gtokfqkmms.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.havefunace.top/Article/details/gtqhzeocge.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yongpay.top/Article/details/gtzgluaoam.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ivvv.top/Article/details/gtcwbdgsan.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhengqikj.top/Article/details/gtykaawtki.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.mhx1999.top/Article/details/gtphvpfboa.html

[E16] 数字千分位
来源：http://dali.sufxvd.cn/Article/details/gttsarbltg.html

Py:   f"{1234567:,}"
来源：http://dali.hysaishi.cn/Article/details/gtbagciaoz.html

PHP:  number_format(1234567);
来源：http://dali.hfpthk.cn/Article/details/gtryjmdnmb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigfzy.top/Article/details/gtpjxtrssq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.sxryk.cn/Article/details/gtafzocfsl.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.chenjidiqi.icu/Article/details/gtvrgmzrzq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.gzhubu.top/Article/details/gtvblealfr.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yangfankeji.com/Article/details/gthbmrxlkk.html

C#:   1234567.ToString("N0")
来源：http://dali.meibo888.top/Article/details/gtklrdaevq.html

[E17] 首字母大写
来源：http://dali.meibo888.top/Article/details/gtlstbvfyp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.feifeiyinyue.top/Article/details/gtyymdbxqy.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.nanxuanxn.top/Article/details/gtkdkeqlpu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvuoughlt.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shzxlz.cn/Article/details/gtiaxbplrj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.tianlin.xyz/Article/details/gtupuyqtgo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinqigfzy.top/Article/details/gtagiscezt.html

Ruby: s.capitalize
来源：http://dali.cdnleiting.top/Article/details/gtivxfquef.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zycfv.cn/Article/details/gtntnoszkj.html

[E18] 模板占位符替换
来源：http://dali.ivvv.top/Article/details/gtlpsstcym.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shzxlz.cn/Article/details/gtiszicidn.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.havefunace.top/Article/details/gtbsovkqzr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangdashe.top/Article/details/gtydtbdbbm.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yanxiufei.cn/Article/details/gtpeijrzrl.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxxpiaeuq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xuanzx.com/Article/details/gtocnmobez.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtucgnmohd.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xinyue.icu/Article/details/gthzzsaskq.html

[E19] 多行文本按行拆分
来源：http://dali.guannengcc.top/Article/details/gtqrbnerco.html

Py:   s.splitlines()
来源：http://dali.jlsjyb.cn/Article/details/gtqwwhbyun.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.birdmap.top/Article/details/gtalrpytny.html

JS:   s.split(/\r?\n/)
来源：http://dali.jinqigfzy.top/Article/details/gtaspglwfd.html

TS:   s.split(/\r?\n/)
来源：http://dali.fzhhl.top/Article/details/gtkukhyzkc.html

Java: s.lines().toList()
来源：http://dali.xuanzx.com/Article/details/gtseiriscz.html

Go:   strings.Split(s, "\n")
来源：http://dali.yonumen.top/Article/details/gtwrpyodow.html

Ruby: s.lines
来源：http://dali.c1oappe.top/Article/details/gtesittujp.html

C#:   s.Split('\n')
来源：http://dali.birdmap.top/Article/details/gtljazmann.html

[E20] 判断字符串是否为空
来源：http://dali.hongshengwenyu.top/Article/details/gthesbgzyj.html

Py:   if not s:
来源：http://dali.jinghuilouyu.cn/Article/details/gtivatpgxy.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.birdmap.top/Article/details/gtxjxhcyfk.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jqgfzy.top/Article/details/gtowhcuwmu.html

TS:   if (s === "") {}
来源：http://dali.gzhubu.top/Article/details/gtjavuexrt.html

Java: if (s.isEmpty()) {}
来源：http://dali.snrcjt.cn/Article/details/gtsmwfnibz.html

Go:   if s == "" {}
来源：http://dali.9152youxi.cn/Article/details/gtvioytkbg.html

Ruby: if s.empty?
来源：http://dali.ehwqpu.com/Article/details/gtxgpdyjnu.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jqgufenzy.top/Article/details/gtxtznmece.html

[E21] 超长截断加省略号
来源：http://dali.daria6918.cn/Article/details/gtzjhtltxa.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.redwolf501.top/Article/details/gtltewhmao.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.aizwys.cn/Article/details/gtycypfrta.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gtryfmevgu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtpnvcrjwm.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.andypj.xyz/Article/details/gttgfncbmy.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yanxiufei.cn/Article/details/gtaummsvku.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.andypj.xyz/Article/details/gttcxpdpum.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ybcxt.top/Article/details/gtvvjkykmk.html

[E22] 字节长度与字符长度
来源：http://dali.yj20258888.top/Article/details/gtsygauaeb.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zdqjudy.top/Article/details/gtabocqrhl.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.redwolf501.top/Article/details/gtyyotxsrf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhiwuduotai.top/Article/details/gtesljoovn.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hammf.cn/Article/details/gtfrqyiuxu.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xinyue.icu/Article/details/gtxpkckvoa.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zdqjudy.top/Article/details/gtajlaszgy.html

Ruby: s.bytesize;  s.length
来源：http://dali.0kj1m.cn/Article/details/gtaorwwtwl.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hnqzz.top/Article/details/gtraebqbyk.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtmekzpjel.html

F. 文件与目录
来源：http://dali.chenjidiqi.icu/Article/details/gtahlmhjle.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtwidrogdl.html

[F01] 读取整个文件
来源：http://dali.gogol.net.cn/Article/details/gtydqjwunf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.birdmap.top/Article/details/gtwtvrztfo.html

PHP:  file_get_contents("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtzxykyvmv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.feifeiyinyue.top/Article/details/gtwossgnqu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.chenlongwang.top/Article/details/gtsopgqyws.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gtqcgseslf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.redwolf501.top/Article/details/gtcvwltses.html

Ruby: File.read("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtubqhteiq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtmiooviuw.html

[F02] 逐行读取文件
来源：http://dali.yanxiufei.cn/Article/details/gthvepgglv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yongpay.top/Article/details/gtmyapqiny.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xylfe.cn/Article/details/gticyonmbw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yanxiufei.cn/Article/details/gtumzzkdzn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nwbrower.top/Article/details/gtlynpzjsx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hfpthk.cn/Article/details/gtvfmfehmm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xuetiantiany.cn/Article/details/gtoyzkelcf.html


<!-- 参考信息 -->