代发 wailian999

PHP:  max($arr);  min($arr);
来源：http://dali.zhixingplan.top/Article/details/gtxmwkkbue.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtavlcdqeu.html

TS:   Math.max(...arr);
来源：http://dali.fzhhl.top/Article/details/gthbwvtztq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hnxiangtu.top/Article/details/gtffjnqcsx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ehwqpu.com/Article/details/gtmlibsvri.html

Ruby: arr.max;  arr.min
来源：http://dali.ehwqpu.com/Article/details/gtxhwjmxlm.html

C#:   list.Max();  list.Min()
来源：http://dali.jqgufenzy.top/Article/details/gtykldoitn.html

[D18] 扁平化嵌套数组
来源：http://dali.ehwqpu.com/Article/details/gtxplpxmxs.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.fengsongda.top/Article/details/gtzadbzide.html

PHP:  array_merge(...$nested);
来源：http://dali.wangshuangyany.cn/Article/details/gtnpbathqz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cqqwz.cn/Article/details/gtwuroxafo.html

TS:   nested.flat();
来源：http://dali.haohaochexian.top/Article/details/gtdyajwenr.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.birdmap.top/Article/details/gtkysgfdwf.html

Go:   // 手写双层循环
来源：http://dali.quarkkingdee.top/Article/details/gtmxkqyidu.html

Ruby: nested.flatten
来源：http://dali.yangfankeji.com/Article/details/gtfjlzdpik.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhixingplan.top/Article/details/gtmuwpaefs.html

[D19] 按字段分组
来源：http://dali.sweek.top/Article/details/gtbuyuuftj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ehwqpu.com/Article/details/gtgbwpdfsn.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zdqjudy.top/Article/details/gtsjrdceox.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jiagoushi.top/Article/details/gtpvcvpyxi.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hywenlv.cn/Article/details/gtumubvhhq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.bjfxy.top/Article/details/gtjkqxndmu.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gtzqcddxjb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jqgfzy.top/Article/details/gttclhtyqr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yonumen.top/Article/details/gthdswppdz.html

[D20] 统计每个元素出现次数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgpdksqpf.html

Py:   Counter(arr)
来源：http://dali.svipenyu.cn/Article/details/gtdxncmizv.html

PHP:  array_count_values($arr);
来源：http://dali.zhengqikj.top/Article/details/gtsbmbgprn.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jianghu66.top/Article/details/gtitivgcos.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hammf.cn/Article/details/gtpcfdeulq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.bjfxy.top/Article/details/gtoqzrtrdm.html

Go:   // 手写 map[T]int
来源：http://dali.daria6918.cn/Article/details/gtwhyqliom.html

Ruby: arr.tally
来源：http://dali.redwolf501.top/Article/details/gtmjlbqagm.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cucudq.cn/Article/details/gtwbhcvgen.html

[D21] 判断是否包含某元素
来源：http://dali.quarkkingdee.top/Article/details/gtjmpztoig.html

Py:   x in arr
来源：http://dali.yj202588.top/Article/details/gtzhefmhlv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.vqdsnc.cn/Article/details/gtgrwczmyd.html

JS:   arr.includes(x)
来源：http://dali.tanke756.top/Article/details/gtnjtonyby.html

TS:   arr.includes(x)
来源：http://dali.0kj1m.cn/Article/details/gtxzuvoyfh.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gtxvzdoxlx.html

Go:   slices.Contains(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gtizknvywu.html

Ruby: arr.include?(x)
来源：http://dali.jinqigufen.top/Article/details/gtwmccblhx.html

C#:   list.Contains(x)
来源：http://dali.tian-w.cn/Article/details/gtiynsgkjl.html

[D22] 复制数组（避免共享引用）
来源：http://dali.kuanghao11.cn/Article/details/gtjarzkwcf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.guowangkeji.top/Article/details/gthgeurwdq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.dashuyun.cn/Article/details/gthzxhnbkl.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yj20258.top/Article/details/gtluwqdlaw.html

TS:   [...arr];
来源：http://dali.gogol.net.cn/Article/details/gtynmeoupo.html

Java: new ArrayList<>(list);
来源：http://dali.yuanzhike.top/Article/details/gtflesribx.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jiagoushi.top/Article/details/gtqugibyby.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yj20258888.top/Article/details/gtnjbpsdis.html

C#:   new List<int>(list);
来源：http://dali.cashguo.top/Article/details/gtxrqbufbb.html

[D23] reduce 累积计算
来源：http://dali.nwbrower.top/Article/details/gtcsteacgh.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xuanzx.com/Article/details/gtzxwzzmkv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jyoumei.cn/Article/details/gtlyxpdhqz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.0kj1m.cn/Article/details/gtomszhgcy.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtupgcynbr.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.nanxuanxn.top/Article/details/gtzkznjpst.html

Go:   // 手写循环
来源：http://dali.hywenlv.cn/Article/details/gtqijpkxwg.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jqgufenzy.top/Article/details/gtrsgawgov.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cashguo.top/Article/details/gtrtklzrwb.html

[D24] 字典 / Map 基本操作
来源：http://dali.yvedp.cn/Article/details/gtlznwzhyh.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jlsjyb.cn/Article/details/gtwisjwyjv.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ydzc1.top/Article/details/gtmjmtiskd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yongpay.top/Article/details/gtzvfwbhdw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yuanzhike.top/Article/details/gtymjkdlfu.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.smart0.xyz/Article/details/gtkiziqhpf.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xinyue.icu/Article/details/gttariyvfg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.birdmap.top/Article/details/gtflhxbvwf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhoulong.xyz/Article/details/gtwyrkcgjs.html

[D25] Set 集合去重与交并差
来源：http://dali.chenjidiqi.icu/Article/details/gtrqjtycac.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jqgfzy.top/Article/details/gtkggaqewu.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.tanke756.top/Article/details/gtovqhrmzi.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.gotoacloud.top/Article/details/gtrhqrinmo.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.tianlin.xyz/Article/details/gtfyubvwuh.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.nwbrower.top/Article/details/gtkkqclfph.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cdnleiting.top/Article/details/gtwnliuegq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yanxiufei.cn/Article/details/gtgzdlzevz.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yj20258.top/Article/details/gtnmxwmepo.html

[D26] 数组转字符串
来源：http://dali.jinqigufen.top/Article/details/gtjowvlfho.html

Py:   ", ".join(map(str, arr))
来源：http://dali.nwbrower.top/Article/details/gtwmjwfwiy.html

PHP:  implode(", ", $arr);
来源：http://dali.jyoumei.cn/Article/details/gtybqvmrre.html

JS:   arr.join(", ")
来源：http://dali.shangyingyoupin.top/Article/details/gtzygrnnnv.html

TS:   arr.join(", ")
来源：http://dali.tanke756.top/Article/details/gtmnbkpjzv.html

Java: String.join(", ", list)
来源：http://dali.yuxming.cn/Article/details/gtwbgivuuz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zycfv.cn/Article/details/gtfkiftbis.html

Ruby: arr.join(", ")
来源：http://dali.xinyue.icu/Article/details/gtpieliasb.html

C#:   string.Join(", ", list)
来源：http://dali.svipenyu.cn/Article/details/gtwvgetoan.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtsdxmppzh.html

E. 字符串处理
来源：http://dali.shuidangran.top/Article/details/gtugtjudrh.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtidkikzwh.html

[E01] 拼接字符串
来源：http://dali.sysykeji.top/Article/details/gthazygwum.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.tanke756.top/Article/details/gtxifztryk.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xylfe.cn/Article/details/gtookdtzrt.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nanxuanxn.top/Article/details/gtempjlaby.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwdqpgbgs.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.quarkkingdee.top/Article/details/gtlmfzxtxc.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.guowangkeji.top/Article/details/gtbfwsypsx.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.chenlongwang.top/Article/details/gtejsbwpuf.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cucudq.cn/Article/details/gtgxqrnhrn.html

[E02] 重复字符串
来源：http://dali.gogol.net.cn/Article/details/gtouqdlenc.html

Py:   "ab" * 3
来源：http://dali.guannengcc.top/Article/details/gtaqotwjur.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shuidangran.top/Article/details/gtnmvekfit.html

JS:   "ab".repeat(3)
来源：http://dali.nanxinkj.top/Article/details/gtbjzvdbtx.html

TS:   "ab".repeat(3)
来源：http://dali.pengpengdd.cyou/Article/details/gtgpjbnvfe.html

Java: "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gtkuyerkrx.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.dianchejie.cn/Article/details/gtlxmmxrjj.html

Ruby: "ab" * 3
来源：http://dali.aizwys.cn/Article/details/gtfhsjfeda.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.chenzaomai.com/Article/details/gtdwxgzjgu.html

[E03] 截取子串
来源：http://dali.ywan-chungtsiang.top/Article/details/gttuiojolt.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.snrcjt.cn/Article/details/gtsbpdztaa.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gtjikqqfbj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ydzc1.top/Article/details/gtejwkvhdi.html

TS:   s.slice(1, 4)
来源：http://dali.cqqwz.cn/Article/details/gtxdmfbvfs.html

Java: s.substring(1, 4)
来源：http://dali.svipenyu.cn/Article/details/gtyiaxhmtp.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.wangshuangyany.cn/Article/details/gtyakgzjjj.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.snrcjt.cn/Article/details/gtawllcamx.html

C#:   s.Substring(1, 3)
来源：http://dali.hysaishi.cn/Article/details/gtsckixnhm.html

[E04] 查找子串位置
来源：http://dali.havefunace.top/Article/details/gtciktncqt.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yj20258.top/Article/details/gthaiybdow.html

PHP:  strpos($s, "x");
来源：http://dali.yuxming.cn/Article/details/gtcvhamuhq.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.wangdashe.top/Article/details/gtjgeelatb.html

TS:   s.indexOf("x")
来源：http://dali.fengsongda.top/Article/details/gtquhzqnym.html

Java: s.indexOf("x")
来源：http://dali.chenzaomai.com/Article/details/gtxgcziwfs.html

Go:   strings.Index(s, "x")
来源：http://dali.gzhubu.top/Article/details/gtvrnealmm.html

Ruby: s.index("x")
来源：http://dali.jianghu66.top/Article/details/gtmvtmlakn.html

C#:   s.IndexOf("x")
来源：http://dali.feifeiyinyue.top/Article/details/gtpkeugfqj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.havefunace.top/Article/details/gtassmtwdp.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yj20258888.top/Article/details/gtgmynsqgs.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.chenlongwang.top/Article/details/gttftwequs.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hongshengwenyu.top/Article/details/gtkvsvqsbg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gtngtqglzw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gtbqxiwoni.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xinyue.icu/Article/details/gtvzqmivze.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cucudq.cn/Article/details/gtzhfbxgcy.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xinyue.icu/Article/details/gtnmuygtfl.html

[E06] 替换子串
来源：http://dali.jqgufenzy.top/Article/details/gtcwwrvlrq.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.guowangkeji.top/Article/details/gtcbvypcdo.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yj20258888.top/Article/details/gtditjxmvi.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tian-w.cn/Article/details/gtucbebzqk.html

TS:   s.replaceAll("a", "b")
来源：http://dali.nwbrower.top/Article/details/gtulsckdte.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gtpdshffed.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtsqamlzqo.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtspqjxdnm.html

C#:   s.Replace("a", "b")
来源：http://dali.xylfe.cn/Article/details/gtzrlpsejc.html

[E07] 按分隔符拆分
来源：http://dali.ppjwa.cn/Article/details/gtywsxubef.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.gotoacloud.top/Article/details/gtnacaymer.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.fzhhl.top/Article/details/gtedmbvxwd.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.c1oappe.top/Article/details/gtebhgqppm.html

TS:   s.split(",")
来源：http://dali.tian-w.cn/Article/details/gttfyabgtf.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jqgfzy.top/Article/details/gtsxeobazh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yj20258.top/Article/details/gtnfisjcek.html

Ruby: s.split(",");  s.split
来源：http://dali.cqqwz.cn/Article/details/gtvfrnkuxu.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yangfankeji.com/Article/details/gtsvwemfah.html

[E08] 数组按分隔符合并
来源：http://dali.zdqjudy.top/Article/details/gtvqyxthcs.html

Py:   ",".join(items)
来源：http://dali.316326.xyz/Article/details/gtqxojmlel.html

PHP:  implode(",", $items);
来源：http://dali.gogol.net.cn/Article/details/gtllgwjixs.html

JS:   items.join(",")
来源：http://dali.zhoulong.xyz/Article/details/gtojntvehk.html

TS:   items.join(",")
来源：http://dali.meibo888.top/Article/details/gthemvplhv.html

Java: String.join(",", items)
来源：http://dali.cheryme.top/Article/details/gtnubvpqao.html

Go:   strings.Join(items, ",")
来源：http://dali.chenzaomai.com/Article/details/gtpivcezaf.html

Ruby: items.join(",")
来源：http://dali.quarkkingdee.top/Article/details/gtjjhxdwwk.html

C#:   string.Join(",", items)
来源：http://dali.jqgfzy.top/Article/details/gtmjagpafh.html

[E09] 去除所有空白字符
来源：http://dali.chenzaomai.com/Article/details/gtxosgtspb.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jlsjyb.cn/Article/details/gtbyqtbrwt.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yuxming.cn/Article/details/gtwgvezddk.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.kuanghao11.cn/Article/details/gtbzbldwbw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xylfe.cn/Article/details/gtuefrngfi.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.feifeiyinyue.top/Article/details/gtclgfedfc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.0kj1m.cn/Article/details/gtzdwczplp.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jinghuilouyu.cn/Article/details/gthkgqffps.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.pengpengdd.cyou/Article/details/gtpjwbucit.html

[E10] 左侧补零 / 定长填充
来源：http://dali.aizwys.cn/Article/details/gtksqqxitm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.smart0.xyz/Article/details/gtbqqmwdzc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.iojbl.cn/Article/details/gtvsvropiv.html

JS:   "7".padStart(3, "0")
来源：http://dali.aibaodan.cn/Article/details/gtdbymvzts.html

TS:   "7".padStart(3, "0")
来源：http://dali.smart0.xyz/Article/details/gtyvdpjcgv.html

Java: String.format("%03d", 7)
来源：http://dali.xylfe.cn/Article/details/gtustcquqe.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.iojbl.cn/Article/details/gtltmdxzdu.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.snrcjt.cn/Article/details/gtolytaogd.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfeqfdutz.html

[E11] 反转字符串
来源：http://dali.shuidangran.top/Article/details/gthhnkwalk.html

Py:   s[::-1]
来源：http://dali.yj20258888.top/Article/details/gtsmhikizr.html

PHP:  strrev($s);
来源：http://dali.birdmap.top/Article/details/gtdpkxmcct.html

JS:   [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gtoocissjr.html

TS:   [...s].reverse().join("")
来源：http://dali.hywenlv.cn/Article/details/gthxrwjmiz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.nanxuanxn.top/Article/details/gtyitlssvp.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.c1oappe.top/Article/details/gtijvagllo.html

Ruby: s.reverse
来源：http://dali.hnxiangtu.top/Article/details/gtvmvldetn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqrmyxrkk.html

[E12] 统计某字符出现次数
来源：http://dali.yuxming.cn/Article/details/gteacoihzq.html

Py:   s.count("a")
来源：http://dali.jyoumei.cn/Article/details/gtclrcvncq.html

PHP:  substr_count($s, "a");
来源：http://dali.cdnleiting.top/Article/details/gtvsnkdbmo.html

JS:   s.split("a").length - 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gthbtqquyo.html

TS:   s.split("a").length - 1
来源：http://dali.aizwys.cn/Article/details/gtkkykgksf.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.smart0.xyz/Article/details/gtnslkzlzr.html

Go:   strings.Count(s, "a")
来源：http://dali.meibo888.top/Article/details/gthqvfzffp.html

Ruby: s.count("a")
来源：http://dali.yj20258.top/Article/details/gtoqfxepfb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hnxiangtu.top/Article/details/gtklhcixlx.html

[E13] 逐字符遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtdznexgaa.html

Py:   for ch in s: print(ch)
来源：http://dali.chenjidiqi.icu/Article/details/gtxmjutblc.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.pycfn.com/Article/details/gtltujmnfo.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sysykeji.top/Article/details/gtnerdzfad.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.kuanghao11.cn/Article/details/gtuecqjlol.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shzxlz.cn/Article/details/gtcyfxiouk.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.redwolf501.top/Article/details/gtzvmwcaya.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.dianchejie.cn/Article/details/gttbkwzxqj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jyoumei.cn/Article/details/gtytnuvozd.html

[E14] URL 编码与 Base64
来源：http://dali.cdnleiting.top/Article/details/gtytmablaf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yonumen.top/Article/details/gtnjjjrvxe.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtlvqrdzsm.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.chenjidiqi.icu/Article/details/gtcuiebeuf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoywzreod.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.aibaodan.cn/Article/details/gtndfycinq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.vqdsnc.cn/Article/details/gtxpsartlt.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.aibaodan.cn/Article/details/gtvdifmozp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.quarkkingdee.top/Article/details/gtlglriafj.html

[E15] HTML 转义 / 反转义
来源：http://dali.mhx1999.top/Article/details/gtlsnmbjyr.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.0kj1m.cn/Article/details/gtklqwkzue.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yuxming.cn/Article/details/gtdhudrwoa.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sweek.top/Article/details/gtfbcrfgpw.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hfpthk.cn/Article/details/gtxwmydbvm.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcuyxtcpi.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtqaacxqud.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ydzc1.top/Article/details/gtgtqoawbu.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.birdmap.top/Article/details/gtdskojexj.html

[E16] 数字千分位
来源：http://dali.fzhhl.top/Article/details/gtjyqmjbqq.html

Py:   f"{1234567:,}"
来源：http://dali.cqqwz.cn/Article/details/gtikcyjrgo.html

PHP:  number_format(1234567);
来源：http://dali.zhixingplan.top/Article/details/gtxywxmank.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.guowangkeji.top/Article/details/gtfukmfexx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ppjwa.cn/Article/details/gtoxockgis.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj202588.top/Article/details/gtzmfupmaa.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.tanke756.top/Article/details/gtpkyrdrwe.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ybcxt.top/Article/details/gtaulinxfa.html

C#:   1234567.ToString("N0")
来源：http://dali.yvedp.cn/Article/details/gtgsglszcx.html

[E17] 首字母大写
来源：http://dali.snrcjt.cn/Article/details/gtdlnyohiw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xuanzx.com/Article/details/gtostndwbh.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.quarkkingdee.top/Article/details/gtpuvknepm.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tanke756.top/Article/details/gtxjjubius.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuanzhike.top/Article/details/gtkzldtnzt.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqzlltrtp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xuanzx.com/Article/details/gtolfdwtqu.html

Ruby: s.capitalize
来源：http://dali.ydzc1.top/Article/details/gttywynnvt.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.316326.xyz/Article/details/gtwedaeqqa.html

[E18] 模板占位符替换
来源：http://dali.tianlin.xyz/Article/details/gtqvncfcqi.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.aizwys.cn/Article/details/gtafracqho.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yj20258.top/Article/details/gtedqyinae.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gtyyauefpc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhengqikj.top/Article/details/gtiacqavdd.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhongyouzk.top/Article/details/gtououjvql.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhengqikj.top/Article/details/gtjmlidnsc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yj20258888.top/Article/details/gtehcxgghk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yvedp.cn/Article/details/gtexunegtd.html

[E19] 多行文本按行拆分
来源：http://dali.jianghu66.top/Article/details/gtxxzvdkst.html

Py:   s.splitlines()
来源：http://dali.svipenyu.cn/Article/details/gthuivgyvb.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yongpay.top/Article/details/gtiqedmbeo.html

JS:   s.split(/\r?\n/)
来源：http://dali.chenjidiqi.icu/Article/details/gtlxdjvtad.html

TS:   s.split(/\r?\n/)
来源：http://dali.cucudq.cn/Article/details/gtdfnkbkbg.html

Java: s.lines().toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtsctxuygh.html

Go:   strings.Split(s, "\n")
来源：http://dali.jinqigfzy.top/Article/details/gtigjavfxl.html

Ruby: s.lines
来源：http://dali.yangfankeji.com/Article/details/gtkcumhyif.html

C#:   s.Split('\n')
来源：http://dali.daxiang520.top/Article/details/gtqloderjb.html

[E20] 判断字符串是否为空
来源：http://dali.fengsongda.top/Article/details/gtyoaekcwd.html

Py:   if not s:
来源：http://dali.svipenyu.cn/Article/details/gtvokqytpl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zycfv.cn/Article/details/gtskszxekv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhixingplan.top/Article/details/gtylutsdfi.html

TS:   if (s === "") {}
来源：http://dali.hysaishi.cn/Article/details/gtyssgdoqt.html

Java: if (s.isEmpty()) {}
来源：http://dali.iojbl.cn/Article/details/gtoytmagog.html

Go:   if s == "" {}
来源：http://dali.shangyingyoupin.top/Article/details/gtyulrqfuy.html

Ruby: if s.empty?
来源：http://dali.redwolf501.top/Article/details/gthvergmza.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.havefunace.top/Article/details/gteepcltha.html

[E21] 超长截断加省略号
来源：http://dali.chenzaomai.com/Article/details/gttymukija.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gaohongyu789.top/Article/details/gtxnoyvuwf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.pycfn.com/Article/details/gtkbybohhe.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jianghu66.top/Article/details/gtrmzbbwrj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gtffkxdlly.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gtadkxsqgj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.smart0.xyz/Article/details/gtscnsixzc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cheryme.top/Article/details/gtxkknuqrg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.aizwys.cn/Article/details/gtyjdkqvtj.html

[E22] 字节长度与字符长度
来源：http://dali.feifeiyinyue.top/Article/details/gtjndsbnqy.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gogol.net.cn/Article/details/gtrlpdauul.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yvedp.cn/Article/details/gttzngwevz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guowangkeji.top/Article/details/gtzqezvjkc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhengqikj.top/Article/details/gtiyqdpxbl.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.andypj.xyz/Article/details/gthbrbnacn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shuidangran.top/Article/details/gtskcwwxyq.html

Ruby: s.bytesize;  s.length
来源：http://dali.chenlongwang.top/Article/details/gtfbbpsvbk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xuetiantiany.cn/Article/details/gtfvvpglpt.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtmnpnygij.html

F. 文件与目录
来源：http://dali.chenlongwang.top/Article/details/gtjvxdpimt.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtzkzwrtay.html

[F01] 读取整个文件
来源：http://dali.snrcjt.cn/Article/details/gtomqokhxb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sxryk.cn/Article/details/gtwdbhwhxr.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtjzeglwtx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.havefunace.top/Article/details/gtbrrrdifr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yj20258.top/Article/details/gtqtzuucga.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gtumtqmtsz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shanyushiyangtech.top/Article/details/gtaitvmltj.html

Ruby: File.read("a.txt")
来源：http://dali.yonumen.top/Article/details/gtrqcfpppd.html


<!-- 参考信息 -->