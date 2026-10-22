代发 wailian999

PHP:  max($arr);  min($arr);
来源：http://dali.9152youxi.cn/Article/details/gtrqylvfpx.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yanxiufei.cn/Article/details/gtlendzvyc.html

TS:   Math.max(...arr);
来源：http://dali.daxiang520.top/Article/details/gtljbjiqjg.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ehwqpu.com/Article/details/gtpjjpybja.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gotoacloud.top/Article/details/gtwwibjdil.html

Ruby: arr.max;  arr.min
来源：http://dali.ivvv.top/Article/details/gtypvrlfih.html

C#:   list.Max();  list.Min()
来源：http://dali.ehwqpu.com/Article/details/gttnfzygni.html

[D18] 扁平化嵌套数组
来源：http://dali.andypj.xyz/Article/details/gtxudfpnbh.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.feifeiyinyue.top/Article/details/gtjeripqxm.html

PHP:  array_merge(...$nested);
来源：http://dali.shzxlz.cn/Article/details/gtqioyydyz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jyoumei.cn/Article/details/gttxocyibj.html

TS:   nested.flat();
来源：http://dali.gzhubu.top/Article/details/gtvprgihhk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cdnleiting.top/Article/details/gthtsxfrgl.html

Go:   // 手写双层循环
来源：http://dali.zhixingplan.top/Article/details/gtqouqqgyj.html

Ruby: nested.flatten
来源：http://dali.gzhubu.top/Article/details/gtzloohtvj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.aizwys.cn/Article/details/gtghwyyrui.html

[D19] 按字段分组
来源：http://dali.guowangkeji.top/Article/details/gtwkthaofg.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hywenlv.cn/Article/details/gtuetkgvja.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.bjfxy.top/Article/details/gtfrrkkdmp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jlsjyb.cn/Article/details/gtyywqbmes.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xylfe.cn/Article/details/gtlmzffbht.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.birdmap.top/Article/details/gttmgmmjnr.html

Go:   // 手写 map[string][]T
来源：http://dali.jqgufenzy.top/Article/details/gtnmztkxpy.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.smart0.xyz/Article/details/gtzfpkupea.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hywenlv.cn/Article/details/gtdxxliwfd.html

[D20] 统计每个元素出现次数
来源：http://dali.jqgfzy.top/Article/details/gtzzlcabaa.html

Py:   Counter(arr)
来源：http://dali.c1oappe.top/Article/details/gtzyhysfpu.html

PHP:  array_count_values($arr);
来源：http://dali.dianchejie.cn/Article/details/gthrxglfgi.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guannengcc.top/Article/details/gtnahsefqd.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gaohongyu789.top/Article/details/gtfbnuoalo.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.guowangkeji.top/Article/details/gtliuzagjf.html

Go:   // 手写 map[T]int
来源：http://dali.jinghuilouyu.cn/Article/details/gtmxkjeenp.html

Ruby: arr.tally
来源：http://dali.jyoumei.cn/Article/details/gtzbzjibed.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zdqjudy.top/Article/details/gtmzqizedf.html

[D21] 判断是否包含某元素
来源：http://dali.sufxvd.cn/Article/details/gtoiplxusj.html

Py:   x in arr
来源：http://dali.chenzaomai.com/Article/details/gtvdphlles.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhengqikj.top/Article/details/gtzzpufbds.html

JS:   arr.includes(x)
来源：http://dali.gaohongyu789.top/Article/details/gttdrcwjhv.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gtnqbcsscd.html

Java: list.contains(x)
来源：http://dali.yanxiufei.cn/Article/details/gtbighhryn.html

Go:   slices.Contains(arr, x)
来源：http://dali.yuxming.cn/Article/details/gtnefuoltc.html

Ruby: arr.include?(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjxabrnhq.html

C#:   list.Contains(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjxqzrkpi.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinqigufen.top/Article/details/gtlxnegnrk.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hfpthk.cn/Article/details/gtdkqbiwev.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gtmwvqvdbc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.nwbrower.top/Article/details/gtfcsfetpv.html

TS:   [...arr];
来源：http://dali.cheryme.top/Article/details/gttjqbucyf.html

Java: new ArrayList<>(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsgoqjlbk.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.meibo888.top/Article/details/gtujxowihr.html

Ruby: arr.dup;  arr.clone
来源：http://dali.chenjidiqi.icu/Article/details/gtgxjxwlae.html

C#:   new List<int>(list);
来源：http://dali.chenlongwang.top/Article/details/gtuchjgnjx.html

[D23] reduce 累积计算
来源：http://dali.jianghu66.top/Article/details/gtqbcuwkkm.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yvedp.cn/Article/details/gtevlcglvj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jlsjyb.cn/Article/details/gtfynuybei.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtlhrnudgt.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zycfv.cn/Article/details/gtgkmntred.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yuxming.cn/Article/details/gtxeqchmqf.html

Go:   // 手写循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gttnjytzcp.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yongpay.top/Article/details/gthxwjoidv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xinyue.icu/Article/details/gtmydcvcur.html

[D24] 字典 / Map 基本操作
来源：http://dali.cheryme.top/Article/details/gtmsnimelh.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.svipenyu.cn/Article/details/gthlzrgelq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.gotoacloud.top/Article/details/gtuhtpbpqr.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ybcxt.top/Article/details/gtokivvaaf.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtrjmiwlnj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyivcbumy.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.sweek.top/Article/details/gtshqadysm.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shuidangran.top/Article/details/gtghjqficc.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinqigfzy.top/Article/details/gtreqbqwso.html

[D25] Set 集合去重与交并差
来源：http://dali.hfpthk.cn/Article/details/gtcgcgiioo.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.feifeiyinyue.top/Article/details/gtqndmjnuh.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yvedp.cn/Article/details/gtxvhylwsk.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shzxlz.cn/Article/details/gtwkywmzly.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.mhx1999.top/Article/details/gtprxphjez.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yuxming.cn/Article/details/gtcaexcmqu.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.nanxinkj.top/Article/details/gtwybmfxci.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hysaishi.cn/Article/details/gtviotibae.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.birdmap.top/Article/details/gteghbylva.html

[D26] 数组转字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtsndfqqun.html

Py:   ", ".join(map(str, arr))
来源：http://dali.smart0.xyz/Article/details/gtnmkgbosv.html

PHP:  implode(", ", $arr);
来源：http://dali.zhoulong.xyz/Article/details/gtkcemdrxt.html

JS:   arr.join(", ")
来源：http://dali.ybcxt.top/Article/details/gtndaupmga.html

TS:   arr.join(", ")
来源：http://dali.haohaochexian.top/Article/details/gtdmgkwhjv.html

Java: String.join(", ", list)
来源：http://dali.birdmap.top/Article/details/gtdubjmgdf.html

Go:   strings.Join(strs, ", ")
来源：http://dali.gzhubu.top/Article/details/gtvddvejkz.html

Ruby: arr.join(", ")
来源：http://dali.daxiang520.top/Article/details/gtcnrnxsol.html

C#:   string.Join(", ", list)
来源：http://dali.zhengqikj.top/Article/details/gttkvcrcex.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtmeutscum.html

E. 字符串处理
来源：http://dali.feifeiyinyue.top/Article/details/gtixsjdnau.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtxbhdrjhw.html

[E01] 拼接字符串
来源：http://dali.cucudq.cn/Article/details/gtojedzhet.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hywenlv.cn/Article/details/gtonrbykgb.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.vqdsnc.cn/Article/details/gtymchbwrl.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.snrcjt.cn/Article/details/gtymcokhwb.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gtqdswwdwb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtchdwbrac.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.birdmap.top/Article/details/gtvrjhzbxg.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.daxiang520.top/Article/details/gtbmxtskuw.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gtporbgfjp.html

[E02] 重复字符串
来源：http://dali.jiagoushi.top/Article/details/gtawpzqyqp.html

Py:   "ab" * 3
来源：http://dali.hnxiangtu.top/Article/details/gtnedessvb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.daria6918.cn/Article/details/gtrhjryfap.html

JS:   "ab".repeat(3)
来源：http://dali.daxiang520.top/Article/details/gtyrtddely.html

TS:   "ab".repeat(3)
来源：http://dali.fengsongda.top/Article/details/gtjcirqexw.html

Java: "ab".repeat(3)
来源：http://dali.cdnleiting.top/Article/details/gtrivqdikg.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shzxlz.cn/Article/details/gtbnjqdfnj.html

Ruby: "ab" * 3
来源：http://dali.gotoacloud.top/Article/details/gtigcvjflm.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzatpxvej.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gtpyqpzfrh.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jinghuilouyu.cn/Article/details/gtjfvgzgss.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gtxijjnqxv.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.mhx1999.top/Article/details/gthfzwiers.html

TS:   s.slice(1, 4)
来源：http://dali.c1oappe.top/Article/details/gtnsanaukf.html

Java: s.substring(1, 4)
来源：http://dali.sysykeji.top/Article/details/gthghuwzww.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sufxvd.cn/Article/details/gtgllbmbwp.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cdnleiting.top/Article/details/gtucotxfsg.html

C#:   s.Substring(1, 3)
来源：http://dali.sxryk.cn/Article/details/gtsrjegqea.html

[E04] 查找子串位置
来源：http://dali.ywan-chungtsiang.top/Article/details/gtowrzxnkm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jyoumei.cn/Article/details/gtwpvumqug.html

PHP:  strpos($s, "x");
来源：http://dali.havefunace.top/Article/details/gtbmkzvnux.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.nanxinkj.top/Article/details/gtxbyhkkww.html

TS:   s.indexOf("x")
来源：http://dali.gaohongyu789.top/Article/details/gtgxixqogy.html

Java: s.indexOf("x")
来源：http://dali.yongpay.top/Article/details/gtdzjegvie.html

Go:   strings.Index(s, "x")
来源：http://dali.zdqjudy.top/Article/details/gtpadfmtcj.html

Ruby: s.index("x")
来源：http://dali.sufxvd.cn/Article/details/gtwrzqxnci.html

C#:   s.IndexOf("x")
来源：http://dali.zhoulong.xyz/Article/details/gtvjowelyg.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.chenjidiqi.icu/Article/details/gtuxlsebxa.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.gotoacloud.top/Article/details/gtjewsgwak.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ybcxt.top/Article/details/gttxnzlfry.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.0kj1m.cn/Article/details/gtlrubuhvf.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.daxiang520.top/Article/details/gtqsioktbf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.daxiang520.top/Article/details/gtmnqznmaw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shzxlz.cn/Article/details/gtuwndptgh.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yongpay.top/Article/details/gtsiqxictg.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jiagoushi.top/Article/details/gttkgaqlys.html

[E06] 替换子串
来源：http://dali.yanxiufei.cn/Article/details/gtjsceaqsb.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.aizwys.cn/Article/details/gtnigyouio.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.daxiang520.top/Article/details/gtpgarffbe.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.fengsongda.top/Article/details/gtpxdpivnh.html

TS:   s.replaceAll("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gtzhgpjtse.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.meibo888.top/Article/details/gtwzukgsin.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.cdnleiting.top/Article/details/gtmxehasuv.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtcohxusfn.html

C#:   s.Replace("a", "b")
来源：http://dali.cheryme.top/Article/details/gtnohedsjv.html

[E07] 按分隔符拆分
来源：http://dali.chenlongwang.top/Article/details/gtlfzhypky.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ydzc1.top/Article/details/gteuqyxdlk.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.daria6918.cn/Article/details/gtjdmlvyki.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.mhx1999.top/Article/details/gtfdomddub.html

TS:   s.split(",")
来源：http://dali.hammf.cn/Article/details/gtlykqzxhw.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.pengpengdd.cyou/Article/details/gtpgynpcel.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shzxlz.cn/Article/details/gtqnjfejgd.html

Ruby: s.split(",");  s.split
来源：http://dali.jlsjyb.cn/Article/details/gtzrlyuhqw.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.nanxuanxn.top/Article/details/gtvzqfnilg.html

[E08] 数组按分隔符合并
来源：http://dali.fzhhl.top/Article/details/gtuqppupii.html

Py:   ",".join(items)
来源：http://dali.shzxlz.cn/Article/details/gtzskodhmc.html

PHP:  implode(",", $items);
来源：http://dali.yuxming.cn/Article/details/gtrrpsdhie.html

JS:   items.join(",")
来源：http://dali.sxryk.cn/Article/details/gtgefghajt.html

TS:   items.join(",")
来源：http://dali.daria6918.cn/Article/details/gtoftcxlrz.html

Java: String.join(",", items)
来源：http://dali.jqgfzy.top/Article/details/gtnnvcacvw.html

Go:   strings.Join(items, ",")
来源：http://dali.jqgfzy.top/Article/details/gtnjpxbedh.html

Ruby: items.join(",")
来源：http://dali.havefunace.top/Article/details/gtwdudchky.html

C#:   string.Join(",", items)
来源：http://dali.yanxiufei.cn/Article/details/gtgediiwwp.html

[E09] 去除所有空白字符
来源：http://dali.yj20258888.top/Article/details/gtkuptufve.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtupovtbfr.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtrfnhmugm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.nanxinkj.top/Article/details/gtsedbipui.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.tian-w.cn/Article/details/gtwjceicpu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj20258.top/Article/details/gtgxtsnzrn.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.9152youxi.cn/Article/details/gtozhholsn.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.9152youxi.cn/Article/details/gtllsomlvz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.smart0.xyz/Article/details/gtmssebbnm.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jyoumei.cn/Article/details/gtaikcqqxs.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.316326.xyz/Article/details/gtdxpaepej.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ivvv.top/Article/details/gtwkxxprel.html

JS:   "7".padStart(3, "0")
来源：http://dali.hywenlv.cn/Article/details/gtoafdfboq.html

TS:   "7".padStart(3, "0")
来源：http://dali.wangdashe.top/Article/details/gttptpixzw.html

Java: String.format("%03d", 7)
来源：http://dali.jqgfzy.top/Article/details/gtyogshzvr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shzxlz.cn/Article/details/gtpvcmzpvv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yuanzhike.top/Article/details/gtcdgmriml.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shanyushiyangtech.top/Article/details/gthkwlgxbo.html

[E11] 反转字符串
来源：http://dali.jiagoushi.top/Article/details/gtbdfntojt.html

Py:   s[::-1]
来源：http://dali.jinqigfzy.top/Article/details/gtswpybidr.html

PHP:  strrev($s);
来源：http://dali.yj202588.top/Article/details/gtxzktipng.html

JS:   [...s].reverse().join("")
来源：http://dali.yvedp.cn/Article/details/gtbxlxubex.html

TS:   [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gtamzoxnmf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.nanxinkj.top/Article/details/gtxajcxtjz.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.aizwys.cn/Article/details/gtacybjgku.html

Ruby: s.reverse
来源：http://dali.ehwqpu.com/Article/details/gtivamvhmd.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yueranfly.top/Article/details/gtqetxqfih.html

[E12] 统计某字符出现次数
来源：http://dali.cashguo.top/Article/details/gtbabvrogr.html

Py:   s.count("a")
来源：http://dali.zdqjudy.top/Article/details/gtkmutzens.html

PHP:  substr_count($s, "a");
来源：http://dali.yj202588.top/Article/details/gtjtxipeeu.html

JS:   s.split("a").length - 1
来源：http://dali.zhixingplan.top/Article/details/gtijnatmsu.html

TS:   s.split("a").length - 1
来源：http://dali.chenzaomai.com/Article/details/gtykcbeatj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cashguo.top/Article/details/gtmcoelnpe.html

Go:   strings.Count(s, "a")
来源：http://dali.tianlin.xyz/Article/details/gtsiaumqcg.html

Ruby: s.count("a")
来源：http://dali.ivvv.top/Article/details/gtzzeubnpf.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cheryme.top/Article/details/gtosqmrdcr.html

[E13] 逐字符遍历
来源：http://dali.yj20258.top/Article/details/gtlrpywzzj.html

Py:   for ch in s: print(ch)
来源：http://dali.pengpengdd.cyou/Article/details/gtyzdpjtuo.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jianghu66.top/Article/details/gtemswjbpi.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guowangkeji.top/Article/details/gtrhtsxfpf.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zdqjudy.top/Article/details/gtugcgpiqg.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.meibo888.top/Article/details/gtyltlewgk.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfsrgyxan.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.bjfxy.top/Article/details/gtvoqogmxk.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yj20258.top/Article/details/gtxendahvq.html

[E14] URL 编码与 Base64
来源：http://dali.snrcjt.cn/Article/details/gtcwxxnpwu.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinyuanbaomall.cn/Article/details/gteyyitzyq.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yj20258888.top/Article/details/gttcflwozj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtomyzioye.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yongpay.top/Article/details/gtopyydzsm.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hysaishi.cn/Article/details/gtyqhgzlsm.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gogol.net.cn/Article/details/gtaclcnkxk.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xinyue.icu/Article/details/gtivxhuewo.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sweek.top/Article/details/gtvkktyree.html

[E15] HTML 转义 / 反转义
来源：http://dali.sweek.top/Article/details/gtfqjeahld.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xziqi.cn/Article/details/gtexttssto.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gotoacloud.top/Article/details/gtxjlzfxqh.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xylfe.cn/Article/details/gtjpkcudmy.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shuidangran.top/Article/details/gtfisccfpp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinqigfzy.top/Article/details/gtswgcersq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.nanxinkj.top/Article/details/gtsdjgufxj.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jyoumei.cn/Article/details/gtyrxcvhae.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gogol.net.cn/Article/details/gttxprscoa.html

[E16] 数字千分位
来源：http://dali.tianlin.xyz/Article/details/gtlxllejyx.html

Py:   f"{1234567:,}"
来源：http://dali.sweek.top/Article/details/gthqekuzci.html

PHP:  number_format(1234567);
来源：http://dali.yuanzhike.top/Article/details/gtixjnbajy.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.gogol.net.cn/Article/details/gthqhcedyo.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.tanke756.top/Article/details/gtzrtnnnrn.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jyoumei.cn/Article/details/gtmtgrnhbe.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.snrcjt.cn/Article/details/gtihueexzn.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.iojbl.cn/Article/details/gtljkvtbwf.html

C#:   1234567.ToString("N0")
来源：http://dali.aibaodan.cn/Article/details/gtvhpskbsq.html

[E17] 首字母大写
来源：http://dali.yj202588.top/Article/details/gtbjykqspp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinqigufen.top/Article/details/gtcwatgaeg.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jianghu66.top/Article/details/gtadbytsww.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.aibaodan.cn/Article/details/gtchtwmsfy.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtudnhuufo.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yj20258.top/Article/details/gtycddiqnm.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xuetiantiany.cn/Article/details/gtvexdvkhf.html

Ruby: s.capitalize
来源：http://dali.bjfxy.top/Article/details/gtkrjryapv.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.sufxvd.cn/Article/details/gtrkkyoajb.html

[E18] 模板占位符替换
来源：http://dali.shzxlz.cn/Article/details/gtpvwaorpr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.daria6918.cn/Article/details/gtuhvjyajk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.sufxvd.cn/Article/details/gtxesfrvvj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.pycfn.com/Article/details/gtaxybbtpr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gtknjzjpgi.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.pengpengdd.cyou/Article/details/gtlewsqhii.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.mhx1999.top/Article/details/gtobyclmkq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtlniimuvg.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zycfv.cn/Article/details/gtjmgstlos.html

[E19] 多行文本按行拆分
来源：http://dali.hnqzz.top/Article/details/gtubdlioyb.html

Py:   s.splitlines()
来源：http://dali.dashuyun.cn/Article/details/gthhaaafzv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.birdmap.top/Article/details/gtsfoezgrt.html

JS:   s.split(/\r?\n/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlhlupwri.html

TS:   s.split(/\r?\n/)
来源：http://dali.yj20258888.top/Article/details/gtzprjjlxh.html

Java: s.lines().toList()
来源：http://dali.gzhubu.top/Article/details/gtubxuwkgd.html

Go:   strings.Split(s, "\n")
来源：http://dali.nanxinkj.top/Article/details/gtvnotlgtq.html

Ruby: s.lines
来源：http://dali.feifeiyinyue.top/Article/details/gtrxebrzwj.html

C#:   s.Split('\n')
来源：http://dali.ybcxt.top/Article/details/gthzbjkpbd.html

[E20] 判断字符串是否为空
来源：http://dali.zhaomingkeji.xyz/Article/details/gtarjvksid.html

Py:   if not s:
来源：http://dali.wangdashe.top/Article/details/gtmyruqtto.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.sysykeji.top/Article/details/gteqbxiflf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jlsjyb.cn/Article/details/gtfkaksyux.html

TS:   if (s === "") {}
来源：http://dali.jianghu66.top/Article/details/gtqjbfabid.html

Java: if (s.isEmpty()) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtzuzyhkbq.html

Go:   if s == "" {}
来源：http://dali.birdmap.top/Article/details/gtcrwcspjl.html

Ruby: if s.empty?
来源：http://dali.9152youxi.cn/Article/details/gtcdubppyz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.dianchejie.cn/Article/details/gtljvatdva.html

[E21] 超长截断加省略号
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvebeuvzx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.wangshuangyany.cn/Article/details/gthycuhrfn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yj20258.top/Article/details/gtnntxzbqd.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttdfikwsm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gtoufluzmz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gtcfcjmolu.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gaohongyu789.top/Article/details/gttlsysxeq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gtqvhaqjtz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jianghu66.top/Article/details/gtcoadisjz.html

[E22] 字节长度与字符长度
来源：http://dali.sufxvd.cn/Article/details/gtctelxzio.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.aibaodan.cn/Article/details/gtuyniniwi.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gtjacrxetb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sweek.top/Article/details/gtscyccryk.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fzhhl.top/Article/details/gtprqmfdlk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jqgufenzy.top/Article/details/gtjtygzefl.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.wangshuangyany.cn/Article/details/gtjienmhzy.html

Ruby: s.bytesize;  s.length
来源：http://dali.nwbrower.top/Article/details/gtlnyaxsdx.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinqigufen.top/Article/details/gtbkewsnfc.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtouizfpwd.html

F. 文件与目录
来源：http://dali.hysaishi.cn/Article/details/gtenxyjrvs.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtquvlzsio.html

[F01] 读取整个文件
来源：http://dali.feifeiyinyue.top/Article/details/gtytokmhws.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yanxiufei.cn/Article/details/gtbmypzueg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtkvpkwgci.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xylfe.cn/Article/details/gtmqhqtmvr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gotoacloud.top/Article/details/gtihgeqzmv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gtmbcnicqi.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jiagoushi.top/Article/details/gtfirlagpa.html

Ruby: File.read("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtdvcamoph.html


<!-- 参考信息 -->