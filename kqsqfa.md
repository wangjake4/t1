代发 wailian999

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj20258.top/Article/details/gtrkskqqpj.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtbkdrgqte.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuvxpvfys.html

Go:   // 手写循环累加
来源：http://dali.xziqi.cn/Article/details/gtzuipertd.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.nanxinkj.top/Article/details/gtgucwxopp.html

C#:   list.Sum();  list.Average()
来源：http://dali.haohaochexian.top/Article/details/gtdgwhfrej.html

[D17] 最大值与最小值
来源：http://dali.yuxming.cn/Article/details/gtsconkmtf.html

Py:   max(arr);  min(arr)
来源：http://dali.ehwqpu.com/Article/details/gtdkouixpw.html

PHP:  max($arr);  min($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtthzrqlph.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jinqigufen.top/Article/details/gtwcyxsomy.html

TS:   Math.max(...arr);
来源：http://dali.hnxiangtu.top/Article/details/gtfrnvpblx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.meibo888.top/Article/details/gtsezpakcb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ydzc1.top/Article/details/gtsymdihnk.html

Ruby: arr.max;  arr.min
来源：http://dali.zhoulong.xyz/Article/details/gtcrozjmir.html

C#:   list.Max();  list.Min()
来源：http://dali.birdmap.top/Article/details/gtzhawwmbe.html

[D18] 扁平化嵌套数组
来源：http://dali.jianghu66.top/Article/details/gtnazlqiwk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhiwuduotai.top/Article/details/gtoahzrgqz.html

PHP:  array_merge(...$nested);
来源：http://dali.daria6918.cn/Article/details/gtpkofaror.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.meibo888.top/Article/details/gtjsetzmga.html

TS:   nested.flat();
来源：http://dali.cdnleiting.top/Article/details/gtcsdfsnwp.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xuanzx.com/Article/details/gtuvfisblv.html

Go:   // 手写双层循环
来源：http://dali.zhengqikj.top/Article/details/gtrganxbsw.html

Ruby: nested.flatten
来源：http://dali.yj20258888.top/Article/details/gtzahggxdr.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.tianlin.xyz/Article/details/gtrcppoghl.html

[D19] 按字段分组
来源：http://dali.ivvv.top/Article/details/gthurtpnps.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyhsptavn.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hysaishi.cn/Article/details/gtulqrpqlz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hysaishi.cn/Article/details/gtlvyprcxt.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gththyvogw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cdnleiting.top/Article/details/gtprtzyfnu.html

Go:   // 手写 map[string][]T
来源：http://dali.yangfankeji.com/Article/details/gtmfbymkvt.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hongshengwenyu.top/Article/details/gtjunfgxxm.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zycfv.cn/Article/details/gtxjsypyuz.html

[D20] 统计每个元素出现次数
来源：http://dali.shanyushiyangtech.top/Article/details/gtjbfywhva.html

Py:   Counter(arr)
来源：http://dali.haohaochexian.top/Article/details/gtyfmpogyr.html

PHP:  array_count_values($arr);
来源：http://dali.0kj1m.cn/Article/details/gtxjjltjei.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ybcxt.top/Article/details/gtecphifrs.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sysykeji.top/Article/details/gtsacmvcxc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ivvv.top/Article/details/gtkssvusli.html

Go:   // 手写 map[T]int
来源：http://dali.cucudq.cn/Article/details/gtyacsjxwj.html

Ruby: arr.tally
来源：http://dali.hywenlv.cn/Article/details/gtxasbiaso.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.wangdashe.top/Article/details/gtkztzznyk.html

[D21] 判断是否包含某元素
来源：http://dali.yangfankeji.com/Article/details/gtfippvqdd.html

Py:   x in arr
来源：http://dali.shuidangran.top/Article/details/gtitaxxude.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ehwqpu.com/Article/details/gtlccflgll.html

JS:   arr.includes(x)
来源：http://dali.jinqigfzy.top/Article/details/gtpdmrtuej.html

TS:   arr.includes(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtecdwdgbq.html

Java: list.contains(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtitjlhdkk.html

Go:   slices.Contains(arr, x)
来源：http://dali.316326.xyz/Article/details/gtphggiuhb.html

Ruby: arr.include?(x)
来源：http://dali.mhx1999.top/Article/details/gtpmqgpjoi.html

C#:   list.Contains(x)
来源：http://dali.ppjwa.cn/Article/details/gtgssujeqr.html

[D22] 复制数组（避免共享引用）
来源：http://dali.feifeiyinyue.top/Article/details/gtxmcjfzix.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.sysykeji.top/Article/details/gtbudjqsqw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.haohaochexian.top/Article/details/gtfudgprly.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtvlrwzmnw.html

TS:   [...arr];
来源：http://dali.jianghu66.top/Article/details/gtdjdqmvwd.html

Java: new ArrayList<>(list);
来源：http://dali.svipenyu.cn/Article/details/gterezkjyd.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yj20258888.top/Article/details/gtwftmyhhg.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yangfankeji.com/Article/details/gtfwubspof.html

C#:   new List<int>(list);
来源：http://dali.havefunace.top/Article/details/gtkkecjwus.html

[D23] reduce 累积计算
来源：http://dali.wangdashe.top/Article/details/gtamltmwzc.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hnqzz.top/Article/details/gtznvsyfcv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hnqzz.top/Article/details/gtxtzyhujb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jianghu66.top/Article/details/gtpeaohrff.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlkobbguf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.9152youxi.cn/Article/details/gtsqkjzgrj.html

Go:   // 手写循环
来源：http://dali.tian-w.cn/Article/details/gtqivlaaka.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yuanzhike.top/Article/details/gtmnekwbew.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jlsjyb.cn/Article/details/gtkqytrsph.html

[D24] 字典 / Map 基本操作
来源：http://dali.smart0.xyz/Article/details/gtfrhcbnyq.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.tanke756.top/Article/details/gtovrbuybl.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.dashuyun.cn/Article/details/gtalxyiied.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.chenzaomai.com/Article/details/gtjknaanad.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.nanxuanxn.top/Article/details/gtquuawzvg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.redwolf501.top/Article/details/gtiwrlvvrd.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ppjwa.cn/Article/details/gtcvuzcyth.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ehwqpu.com/Article/details/gtkrvpyxkq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jqgfzy.top/Article/details/gtckllccxr.html

[D25] Set 集合去重与交并差
来源：http://dali.meibo888.top/Article/details/gtstnpacua.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yuxming.cn/Article/details/gtfaiyfzvt.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xuetiantiany.cn/Article/details/gtmgocimtc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.dashuyun.cn/Article/details/gtccoruuvs.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yangfankeji.com/Article/details/gtczjtwhfq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.mhx1999.top/Article/details/gtqrjiobqw.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ivvv.top/Article/details/gtkfukkvel.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ivvv.top/Article/details/gtalqadegn.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhengqikj.top/Article/details/gtzclbyrzs.html

[D26] 数组转字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtseuxcqlm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhoulong.xyz/Article/details/gtnnydapaw.html

PHP:  implode(", ", $arr);
来源：http://dali.jyoumei.cn/Article/details/gtkzekxksp.html

JS:   arr.join(", ")
来源：http://dali.nwbrower.top/Article/details/gtvgetubvh.html

TS:   arr.join(", ")
来源：http://dali.yvedp.cn/Article/details/gtpvlfeffc.html

Java: String.join(", ", list)
来源：http://dali.c1oappe.top/Article/details/gtwhqarnxg.html

Go:   strings.Join(strs, ", ")
来源：http://dali.9152youxi.cn/Article/details/gtazkxbrvj.html

Ruby: arr.join(", ")
来源：http://dali.hfpthk.cn/Article/details/gtrbdqptvf.html

C#:   string.Join(", ", list)
来源：http://dali.cheryme.top/Article/details/gttlirelkp.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtvjhllhlz.html

E. 字符串处理
来源：http://dali.jqgufenzy.top/Article/details/gtmncpxntn.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gttythrcae.html

[E01] 拼接字符串
来源：http://dali.ehwqpu.com/Article/details/gtdvdfqmyn.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yanxiufei.cn/Article/details/gtpfjzuzsn.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jqgufenzy.top/Article/details/gtsbsttqdy.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwaadqcln.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jqgufenzy.top/Article/details/gtlgbmyzfv.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.gotoacloud.top/Article/details/gttepebvvz.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhengqikj.top/Article/details/gttvgfqbwx.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yvedp.cn/Article/details/gteesyfgun.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gttwtpbptm.html

[E02] 重复字符串
来源：http://dali.xziqi.cn/Article/details/gtzgpbvieu.html

Py:   "ab" * 3
来源：http://dali.zycfv.cn/Article/details/gtqzlaojhb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtruyerwta.html

JS:   "ab".repeat(3)
来源：http://dali.svipenyu.cn/Article/details/gtjozzpxnm.html

TS:   "ab".repeat(3)
来源：http://dali.fengsongda.top/Article/details/gtnewmpwbn.html

Java: "ab".repeat(3)
来源：http://dali.nwbrower.top/Article/details/gtwbpnnqlp.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jqgufenzy.top/Article/details/gtxyzguxyl.html

Ruby: "ab" * 3
来源：http://dali.shangyingyoupin.top/Article/details/gtnbcvsiuy.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gogol.net.cn/Article/details/gtstoxsxsb.html

[E03] 截取子串
来源：http://dali.snrcjt.cn/Article/details/gtmghjhdfi.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yvedp.cn/Article/details/gtimnvsuxb.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gtunifupxp.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yj202588.top/Article/details/gtqchlpudm.html

TS:   s.slice(1, 4)
来源：http://dali.cucudq.cn/Article/details/gtpmfipods.html

Java: s.substring(1, 4)
来源：http://dali.nanxuanxn.top/Article/details/gthgjrueds.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.pengpengdd.cyou/Article/details/gtojcyefsw.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.sufxvd.cn/Article/details/gtumdmreil.html

C#:   s.Substring(1, 3)
来源：http://dali.yangfankeji.com/Article/details/gtdrfdetps.html

[E04] 查找子串位置
来源：http://dali.yvedp.cn/Article/details/gtyhkctgky.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hysaishi.cn/Article/details/gtfiykupku.html

PHP:  strpos($s, "x");
来源：http://dali.gotoacloud.top/Article/details/gtmspellfx.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shuidangran.top/Article/details/gtgmumtibe.html

TS:   s.indexOf("x")
来源：http://dali.jyoumei.cn/Article/details/gtjrkiayoo.html

Java: s.indexOf("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrwgdjsjw.html

Go:   strings.Index(s, "x")
来源：http://dali.fzhhl.top/Article/details/gthocvluhr.html

Ruby: s.index("x")
来源：http://dali.dashuyun.cn/Article/details/gtiidalldh.html

C#:   s.IndexOf("x")
来源：http://dali.cucudq.cn/Article/details/gtbjxwpnlw.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jyoumei.cn/Article/details/gtddugzmtx.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.bjfxy.top/Article/details/gtqparaxrw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hongshengwenyu.top/Article/details/gtrzgrcsxg.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ppjwa.cn/Article/details/gtwjdznxnq.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.chenzaomai.com/Article/details/gtulpkuiit.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.feifeiyinyue.top/Article/details/gtgcqrxsdy.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdcmdlhyh.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.sufxvd.cn/Article/details/gtfmmycmai.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yvedp.cn/Article/details/gtiztudgjy.html

[E06] 替换子串
来源：http://dali.kuanghao11.cn/Article/details/gtgcslryjm.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.chenzaomai.com/Article/details/gtxeqqdbvl.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtwvukwsti.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gtcfoiimno.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtdqrddimh.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gtsxyajwdh.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.snrcjt.cn/Article/details/gtwdilttzf.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxbsfeepq.html

C#:   s.Replace("a", "b")
来源：http://dali.ivvv.top/Article/details/gtbxjvoixs.html

[E07] 按分隔符拆分
来源：http://dali.nanxinkj.top/Article/details/gtuhuiurmn.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cucudq.cn/Article/details/gtygjgubjz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtptazufgs.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.iojbl.cn/Article/details/gtwcculohh.html

TS:   s.split(",")
来源：http://dali.smart0.xyz/Article/details/gtelhhxgig.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.meibo888.top/Article/details/gtmmythzko.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jqgfzy.top/Article/details/gtxagqemvu.html

Ruby: s.split(",");  s.split
来源：http://dali.gzhubu.top/Article/details/gtzsuvgpjq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.fengsongda.top/Article/details/gtymjgtoui.html

[E08] 数组按分隔符合并
来源：http://dali.ehwqpu.com/Article/details/gtwjgzguli.html

Py:   ",".join(items)
来源：http://dali.xylfe.cn/Article/details/gtuyfxpmba.html

PHP:  implode(",", $items);
来源：http://dali.zhixingplan.top/Article/details/gtfmhvfbqn.html

JS:   items.join(",")
来源：http://dali.redwolf501.top/Article/details/gtbmnlzphn.html

TS:   items.join(",")
来源：http://dali.0kj1m.cn/Article/details/gtypebbnje.html

Java: String.join(",", items)
来源：http://dali.tianlin.xyz/Article/details/gtixkxacqg.html

Go:   strings.Join(items, ",")
来源：http://dali.wangshuangyany.cn/Article/details/gtmceyjyuf.html

Ruby: items.join(",")
来源：http://dali.iojbl.cn/Article/details/gtvaiocvzp.html

C#:   string.Join(",", items)
来源：http://dali.yuanzhike.top/Article/details/gtozsrrzbi.html

[E09] 去除所有空白字符
来源：http://dali.sufxvd.cn/Article/details/gtovnpjgkh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.smart0.xyz/Article/details/gtljbqebpf.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.tanke756.top/Article/details/gtspugicux.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cdnleiting.top/Article/details/gtuskycdkg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.feifeiyinyue.top/Article/details/gtflqgehwo.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.tianlin.xyz/Article/details/gttcjkyvqy.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.aibaodan.cn/Article/details/gtdjyalwvc.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hnxiangtu.top/Article/details/gtvbuepvxh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhongyouzk.top/Article/details/gtrrqclkpb.html

[E10] 左侧补零 / 定长填充
来源：http://dali.wangshuangyany.cn/Article/details/gtxxrotili.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shanyushiyangtech.top/Article/details/gtgmxmwkrz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yj202588.top/Article/details/gtjzylsxwl.html

JS:   "7".padStart(3, "0")
来源：http://dali.redwolf501.top/Article/details/gtkgufywig.html

TS:   "7".padStart(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gtauwcrryu.html

Java: String.format("%03d", 7)
来源：http://dali.wangdashe.top/Article/details/gtwclcpzsg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hysaishi.cn/Article/details/gtxdoemicl.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.dashuyun.cn/Article/details/gtyebkaclp.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhoulong.xyz/Article/details/gtxgzxrijt.html

[E11] 反转字符串
来源：http://dali.cashguo.top/Article/details/gtrlcmoxfy.html

Py:   s[::-1]
来源：http://dali.0kj1m.cn/Article/details/gtbokrpxdd.html

PHP:  strrev($s);
来源：http://dali.cheryme.top/Article/details/gtvgjkvyqq.html

JS:   [...s].reverse().join("")
来源：http://dali.vqdsnc.cn/Article/details/gtdyaxobhv.html

TS:   [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gtdqemdozo.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.nwbrower.top/Article/details/gtduijagvi.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cdnleiting.top/Article/details/gtgiplrsrv.html

Ruby: s.reverse
来源：http://dali.yangfankeji.com/Article/details/gtfmdohmsp.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.dashuyun.cn/Article/details/gtpeikmjix.html

[E12] 统计某字符出现次数
来源：http://dali.jlsjyb.cn/Article/details/gtxjtswscy.html

Py:   s.count("a")
来源：http://dali.cashguo.top/Article/details/gtezbrfksh.html

PHP:  substr_count($s, "a");
来源：http://dali.hammf.cn/Article/details/gtfcjocdvt.html

JS:   s.split("a").length - 1
来源：http://dali.gzhubu.top/Article/details/gtnmzfgfer.html

TS:   s.split("a").length - 1
来源：http://dali.zdqjudy.top/Article/details/gthibfjnes.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.316326.xyz/Article/details/gttijbgpjf.html

Go:   strings.Count(s, "a")
来源：http://dali.chenzaomai.com/Article/details/gtzfubufff.html

Ruby: s.count("a")
来源：http://dali.ppjwa.cn/Article/details/gtxqufvvoa.html

C#:   s.Count(c => c == 'a')
来源：http://dali.aibaodan.cn/Article/details/gtlfgcsugc.html

[E13] 逐字符遍历
来源：http://dali.yj20258888.top/Article/details/gtahijoxbz.html

Py:   for ch in s: print(ch)
来源：http://dali.sxryk.cn/Article/details/gtokkkaift.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.meibo888.top/Article/details/gtvrhxcerq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gtpswqxgtt.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.svipenyu.cn/Article/details/gtrbkuudgj.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gtcqcynuvu.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ehwqpu.com/Article/details/gtuhaefrmb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nwbrower.top/Article/details/gtoiamhdff.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yuanzhike.top/Article/details/gtziazhpps.html

[E14] URL 编码与 Base64
来源：http://dali.xuanzx.com/Article/details/gtckrsrfzp.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhoulong.xyz/Article/details/gtevyqxvux.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xylfe.cn/Article/details/gtrtdlwpha.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.tanke756.top/Article/details/gtgdkounfp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hfpthk.cn/Article/details/gtwuuwgjki.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sweek.top/Article/details/gtmmtmgnuf.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shangyingyoupin.top/Article/details/gtrvlguhpa.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xylfe.cn/Article/details/gtpefselwi.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zdqjudy.top/Article/details/gtoskrkunb.html

[E15] HTML 转义 / 反转义
来源：http://dali.hfpthk.cn/Article/details/gtlzjnyufw.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhongyouzk.top/Article/details/gthlgaxocg.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqjzlumkl.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yj20258.top/Article/details/gtpbidhjiw.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hywenlv.cn/Article/details/gtyqlaifot.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.haohaochexian.top/Article/details/gtjurdcjby.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.9152youxi.cn/Article/details/gthnnptcjc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jinqigfzy.top/Article/details/gttcnsvfpq.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvryigqtj.html

[E16] 数字千分位
来源：http://dali.wangdashe.top/Article/details/gttkvrkznc.html

Py:   f"{1234567:,}"
来源：http://dali.shzxlz.cn/Article/details/gtkhzrttjl.html

PHP:  number_format(1234567);
来源：http://dali.tanke756.top/Article/details/gtzzhobeua.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.aizwys.cn/Article/details/gtqpwknvnv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yanxiufei.cn/Article/details/gtsaftxhit.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zdqjudy.top/Article/details/gtprutltbd.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.nanxinkj.top/Article/details/gtcpwwnitm.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cheryme.top/Article/details/gtefnhemso.html

C#:   1234567.ToString("N0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbfvgssom.html

[E17] 首字母大写
来源：http://dali.tanke756.top/Article/details/gtretoehmw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.guannengcc.top/Article/details/gtxmlbwhdk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkyzvpdtl.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenzaomai.com/Article/details/gtzflfluny.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dashuyun.cn/Article/details/gtjwlhcifr.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xylfe.cn/Article/details/gthnpxmfky.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sxryk.cn/Article/details/gtjamcwpah.html

Ruby: s.capitalize
来源：http://dali.jlsjyb.cn/Article/details/gtjomvvckv.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yueranfly.top/Article/details/gtnmahlkif.html

[E18] 模板占位符替换
来源：http://dali.zhoulong.xyz/Article/details/gtrsnuwrnu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.bjfxy.top/Article/details/gtvlyjpsqx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhiwuduotai.top/Article/details/gtronevfom.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.nanxuanxn.top/Article/details/gtjfntptax.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.aibaodan.cn/Article/details/gtuxrojwny.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.pengpengdd.cyou/Article/details/gtkuxdqiuc.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ydzc1.top/Article/details/gtxsmkdwyw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.svipenyu.cn/Article/details/gtgwntelhh.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.feifeiyinyue.top/Article/details/gtxflpkgac.html

[E19] 多行文本按行拆分
来源：http://dali.daxiang520.top/Article/details/gtjqaecyai.html

Py:   s.splitlines()
来源：http://dali.hnxiangtu.top/Article/details/gtjlzmzgss.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.0kj1m.cn/Article/details/gtwoyzteiq.html

JS:   s.split(/\r?\n/)
来源：http://dali.chenzaomai.com/Article/details/gtqakwbijq.html

TS:   s.split(/\r?\n/)
来源：http://dali.cheryme.top/Article/details/gtyygmdkqw.html

Java: s.lines().toList()
来源：http://dali.ydzc1.top/Article/details/gtqlwiypdv.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhoulong.xyz/Article/details/gtpvqzvzgu.html

Ruby: s.lines
来源：http://dali.c1oappe.top/Article/details/gtnozihvcu.html

C#:   s.Split('\n')
来源：http://dali.chenlongwang.top/Article/details/gtwwtczotj.html

[E20] 判断字符串是否为空
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvbqnetmc.html

Py:   if not s:
来源：http://dali.sweek.top/Article/details/gtznuhjqjt.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.fengsongda.top/Article/details/gtahelzrxg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ybcxt.top/Article/details/gtciaryucs.html

TS:   if (s === "") {}
来源：http://dali.cheryme.top/Article/details/gtaueqzvkz.html

Java: if (s.isEmpty()) {}
来源：http://dali.svipenyu.cn/Article/details/gtbdipoxjy.html

Go:   if s == "" {}
来源：http://dali.snrcjt.cn/Article/details/gtciksrftk.html

Ruby: if s.empty?
来源：http://dali.birdmap.top/Article/details/gtsytxiqdn.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.dashuyun.cn/Article/details/gthtcilvtt.html

[E21] 超长截断加省略号
来源：http://dali.sysykeji.top/Article/details/gtovtrzmfx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jiagoushi.top/Article/details/gtyqezpeaj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.tanke756.top/Article/details/gthdwvcizd.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258888.top/Article/details/gtnbvlupjd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gtmtfuoknk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hammf.cn/Article/details/gtwshkxwha.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.nanxinkj.top/Article/details/gticcubzuv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.daria6918.cn/Article/details/gtyvpdkxme.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xinyue.icu/Article/details/gtblgwuras.html

[E22] 字节长度与字符长度
来源：http://dali.yonumen.top/Article/details/gtyrbjlyjk.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.tanke756.top/Article/details/gtzmkzqagz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gtacsyrxwb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gttshzvegc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sxryk.cn/Article/details/gtfgerivbb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yvedp.cn/Article/details/gtkfippytz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jlsjyb.cn/Article/details/gtxtvyhjom.html

Ruby: s.bytesize;  s.length
来源：http://dali.jqgufenzy.top/Article/details/gtlqkrteip.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cqqwz.cn/Article/details/gtbngxohsz.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtcvzugmxq.html

F. 文件与目录
来源：http://dali.hysaishi.cn/Article/details/gtjkxvdjpp.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtljtcezya.html


<!-- 参考信息 -->