代发 wailian999

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sxryk.cn/Article/details/gtunnswykt.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhiwuduotai.top/Article/details/gtpzvmhfdg.html

[D17] 最大值与最小值
来源：http://dali.tian-w.cn/Article/details/gtpzzcdaja.html

Py:   max(arr);  min(arr)
来源：http://dali.dianchejie.cn/Article/details/gtgqlnedzf.html

PHP:  max($arr);  min($arr);
来源：http://dali.chenlongwang.top/Article/details/gtdifkggpy.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtvipdoswz.html

TS:   Math.max(...arr);
来源：http://dali.tian-w.cn/Article/details/gtaqrklsfy.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.feifeiyinyue.top/Article/details/gtzpwbwwpg.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ydzc1.top/Article/details/gttrbqsxlh.html

Ruby: arr.max;  arr.min
来源：http://dali.wangdashe.top/Article/details/gtumzocnko.html

C#:   list.Max();  list.Min()
来源：http://dali.jinghuilouyu.cn/Article/details/gtqgzvlrmv.html

[D18] 扁平化嵌套数组
来源：http://dali.zhengqikj.top/Article/details/gtbdjdyokb.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gzhubu.top/Article/details/gtivufpwvc.html

PHP:  array_merge(...$nested);
来源：http://dali.cashguo.top/Article/details/gtgzajzktp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxbdbldui.html

TS:   nested.flat();
来源：http://dali.yj20258.top/Article/details/gtqztdbvhq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.fengsongda.top/Article/details/gthfxrrman.html

Go:   // 手写双层循环
来源：http://dali.fzhhl.top/Article/details/gthowejpuw.html

Ruby: nested.flatten
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzvvkljpr.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gthrgywjag.html

[D19] 按字段分组
来源：http://dali.yonumen.top/Article/details/gtpkstyhmg.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.mhx1999.top/Article/details/gthabqfrrs.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cheryme.top/Article/details/gtvgeuoawr.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.nwbrower.top/Article/details/gtmrccwofv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yueranfly.top/Article/details/gtguxjkeja.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.dianchejie.cn/Article/details/gtenelduvc.html

Go:   // 手写 map[string][]T
来源：http://dali.316326.xyz/Article/details/gtuzxtknas.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.aibaodan.cn/Article/details/gtnmdiovyc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.vqdsnc.cn/Article/details/gtmdszqssh.html

[D20] 统计每个元素出现次数
来源：http://dali.yuanzhike.top/Article/details/gtvpjdnkwt.html

Py:   Counter(arr)
来源：http://dali.ehwqpu.com/Article/details/gtjeueegcm.html

PHP:  array_count_values($arr);
来源：http://dali.xinyue.icu/Article/details/gtoaaarmxy.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgurdkuuc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnqzz.top/Article/details/gtcocvqrli.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gtbbuyrtfq.html

Go:   // 手写 map[T]int
来源：http://dali.zhengqikj.top/Article/details/gtbhjutosn.html

Ruby: arr.tally
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwbpbgcdr.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.0kj1m.cn/Article/details/gtvooicbaj.html

[D21] 判断是否包含某元素
来源：http://dali.vqdsnc.cn/Article/details/gthqbqsoxo.html

Py:   x in arr
来源：http://dali.fzhhl.top/Article/details/gtskzefzog.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sweek.top/Article/details/gtumpvejpq.html

JS:   arr.includes(x)
来源：http://dali.daria6918.cn/Article/details/gteoqtafiw.html

TS:   arr.includes(x)
来源：http://dali.yuxming.cn/Article/details/gtzjoczgwx.html

Java: list.contains(x)
来源：http://dali.pycfn.com/Article/details/gtijbvpnoi.html

Go:   slices.Contains(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gtvsvnyldj.html

Ruby: arr.include?(x)
来源：http://dali.tianlin.xyz/Article/details/gtslfvvctt.html

C#:   list.Contains(x)
来源：http://dali.xylfe.cn/Article/details/gtqeodbopi.html

[D22] 复制数组（避免共享引用）
来源：http://dali.pycfn.com/Article/details/gtzwsiwgqy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.mhx1999.top/Article/details/gtdqojwzpu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.daria6918.cn/Article/details/gtufudvcvh.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sufxvd.cn/Article/details/gtxkwnylub.html

TS:   [...arr];
来源：http://dali.316326.xyz/Article/details/gthnzsoizn.html

Java: new ArrayList<>(list);
来源：http://dali.yanxiufei.cn/Article/details/gtwbnamqof.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.daxiang520.top/Article/details/gtyvjskheg.html

Ruby: arr.dup;  arr.clone
来源：http://dali.nwbrower.top/Article/details/gtassiplxd.html

C#:   new List<int>(list);
来源：http://dali.yj20258.top/Article/details/gtbsfsdqik.html

[D23] reduce 累积计算
来源：http://dali.cucudq.cn/Article/details/gtjdikyuzo.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.tianlin.xyz/Article/details/gtvdieewdk.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jiagoushi.top/Article/details/gtsqfgwkdc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.haohaochexian.top/Article/details/gtroojtqao.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cashguo.top/Article/details/gtpgzypseb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hnqzz.top/Article/details/gtgxrnlyli.html

Go:   // 手写循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtphjtrrbs.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.tianlin.xyz/Article/details/gtvxvwnyul.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gaohongyu789.top/Article/details/gtgbpmvxls.html

[D24] 字典 / Map 基本操作
来源：http://dali.ehwqpu.com/Article/details/gtpgebxudb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hywenlv.cn/Article/details/gtwhrflxgv.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shzxlz.cn/Article/details/gtsaxzizew.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.fengsongda.top/Article/details/gtdljcyqrd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.316326.xyz/Article/details/gtqdwavoll.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.vqdsnc.cn/Article/details/gtsnjohhuw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.0kj1m.cn/Article/details/gtoiaylwwn.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtatuqrbzu.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jiagoushi.top/Article/details/gtmdbokoyn.html

[D25] Set 集合去重与交并差
来源：http://dali.ppjwa.cn/Article/details/gtmbdpvcfc.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hnqzz.top/Article/details/gtkeqvacpg.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.guowangkeji.top/Article/details/gtniqywekf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ydzc1.top/Article/details/gtroqocbhu.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zdqjudy.top/Article/details/gtygxvhlbt.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yvedp.cn/Article/details/gtyzysqvon.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.sufxvd.cn/Article/details/gtwrwuiumj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jinqigfzy.top/Article/details/gtihwonvza.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.chenzaomai.com/Article/details/gtbdmmigsj.html

[D26] 数组转字符串
来源：http://dali.guowangkeji.top/Article/details/gtzfwcxjsc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.fzhhl.top/Article/details/gtqrhxxvmm.html

PHP:  implode(", ", $arr);
来源：http://dali.yj20258.top/Article/details/gtgjudxizy.html

JS:   arr.join(", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtftuspwlz.html

TS:   arr.join(", ")
来源：http://dali.wangshuangyany.cn/Article/details/gtqnhkbuwh.html

Java: String.join(", ", list)
来源：http://dali.svipenyu.cn/Article/details/gteymvpnis.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhixingplan.top/Article/details/gtnwwkvgaf.html

Ruby: arr.join(", ")
来源：http://dali.havefunace.top/Article/details/gtxemgmcls.html

C#:   string.Join(", ", list)
来源：http://dali.cucudq.cn/Article/details/gtqalmlsqu.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gthiafmenq.html

E. 字符串处理
来源：http://dali.gaohongyu789.top/Article/details/gtysryafaj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtsihxwtmw.html

[E01] 拼接字符串
来源：http://dali.0kj1m.cn/Article/details/gtuxomefbn.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlxiature.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gtumksrucg.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jiagoushi.top/Article/details/gtprqdgure.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.fengsongda.top/Article/details/gtvciigmlw.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.gzhubu.top/Article/details/gtkqhxrrwb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.mhx1999.top/Article/details/gtotcebhfv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cheryme.top/Article/details/gtwqqzeekg.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gtmycfhylz.html

[E02] 重复字符串
来源：http://dali.ppjwa.cn/Article/details/gtkbwlnvrl.html

Py:   "ab" * 3
来源：http://dali.gzhubu.top/Article/details/gtiggpeucs.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zycfv.cn/Article/details/gtuchnoyoc.html

JS:   "ab".repeat(3)
来源：http://dali.svipenyu.cn/Article/details/gtcjpyukgk.html

TS:   "ab".repeat(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqyadmefr.html

Java: "ab".repeat(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqhynujdn.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.sysykeji.top/Article/details/gtwyiaqrpi.html

Ruby: "ab" * 3
来源：http://dali.hnxiangtu.top/Article/details/gtxmhmtwxw.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhongyouzk.top/Article/details/gtkxewizoz.html

[E03] 截取子串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdskieiei.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.havefunace.top/Article/details/gtsfcmlxti.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.haohaochexian.top/Article/details/gtmaxjlgwj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jyoumei.cn/Article/details/gtqntfbwbb.html

TS:   s.slice(1, 4)
来源：http://dali.yvedp.cn/Article/details/gtnqounhxm.html

Java: s.substring(1, 4)
来源：http://dali.cheryme.top/Article/details/gtvnhmenbr.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cashguo.top/Article/details/gthuxswdbk.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.c1oappe.top/Article/details/gtclghwmfi.html

C#:   s.Substring(1, 3)
来源：http://dali.fzhhl.top/Article/details/gtaorizlru.html

[E04] 查找子串位置
来源：http://dali.yangfankeji.com/Article/details/gtrurqjqjo.html

Py:   s.find("x");  s.index("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmlgcksux.html

PHP:  strpos($s, "x");
来源：http://dali.gaohongyu789.top/Article/details/gtxcboskug.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinqigfzy.top/Article/details/gtvftvahac.html

TS:   s.indexOf("x")
来源：http://dali.zhixingplan.top/Article/details/gtgrrxozex.html

Java: s.indexOf("x")
来源：http://dali.snrcjt.cn/Article/details/gtcpnfuzjb.html

Go:   strings.Index(s, "x")
来源：http://dali.zhiwuduotai.top/Article/details/gtznrotpqy.html

Ruby: s.index("x")
来源：http://dali.daxiang520.top/Article/details/gtgcnuuwhx.html

C#:   s.IndexOf("x")
来源：http://dali.ivvv.top/Article/details/gtdaejxyuh.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jqgfzy.top/Article/details/gtajedyhte.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jianghu66.top/Article/details/gtakqzoduc.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yueranfly.top/Article/details/gtfledaksy.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jqgfzy.top/Article/details/gtertgebrn.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.andypj.xyz/Article/details/gtukzifmin.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.pengpengdd.cyou/Article/details/gtkgwevpjn.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hammf.cn/Article/details/gtlsbiqwjw.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.mhx1999.top/Article/details/gtdovzfeng.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.redwolf501.top/Article/details/gtzzsorbnd.html

[E06] 替换子串
来源：http://dali.jqgufenzy.top/Article/details/gtmxqhntoi.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jqgfzy.top/Article/details/gtvxvfabys.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xylfe.cn/Article/details/gtpyvhwrea.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gtrvhrhkfz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.c1oappe.top/Article/details/gtdykvdmvl.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gtvolqswzc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ppjwa.cn/Article/details/gtpenpihuz.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gtdmhovzcn.html

C#:   s.Replace("a", "b")
来源：http://dali.ivvv.top/Article/details/gtjdrwopyc.html

[E07] 按分隔符拆分
来源：http://dali.sufxvd.cn/Article/details/gtfiwzsveg.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jqgufenzy.top/Article/details/gtzzqskvtx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.aibaodan.cn/Article/details/gtuwuwayrp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yongpay.top/Article/details/gtxwjrxyco.html

TS:   s.split(",")
来源：http://dali.xziqi.cn/Article/details/gtuzwveyhj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfvkxosiu.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sufxvd.cn/Article/details/gtxyhdqbdn.html

Ruby: s.split(",");  s.split
来源：http://dali.pycfn.com/Article/details/gtdziwdzzv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xuetiantiany.cn/Article/details/gtxlphpydc.html

[E08] 数组按分隔符合并
来源：http://dali.shzxlz.cn/Article/details/gtrukgpytv.html

Py:   ",".join(items)
来源：http://dali.jiagoushi.top/Article/details/gtlwvwmwhv.html

PHP:  implode(",", $items);
来源：http://dali.jinghuilouyu.cn/Article/details/gtwzasqjlg.html

JS:   items.join(",")
来源：http://dali.yongpay.top/Article/details/gtmbwkphyf.html

TS:   items.join(",")
来源：http://dali.chenjidiqi.icu/Article/details/gttvvrdymn.html

Java: String.join(",", items)
来源：http://dali.ehwqpu.com/Article/details/gtgwbriynt.html

Go:   strings.Join(items, ",")
来源：http://dali.guannengcc.top/Article/details/gtmyozivep.html

Ruby: items.join(",")
来源：http://dali.chenjidiqi.icu/Article/details/gtdgfwwskk.html

C#:   string.Join(",", items)
来源：http://dali.nwbrower.top/Article/details/gtotemdvnf.html

[E09] 去除所有空白字符
来源：http://dali.tianlin.xyz/Article/details/gtaijutzwz.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.aibaodan.cn/Article/details/gtvuhdwebu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtrmixgdne.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.pycfn.com/Article/details/gtkasmwjot.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xylfe.cn/Article/details/gtyuxtgjek.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.tianlin.xyz/Article/details/gthxidpgee.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.birdmap.top/Article/details/gtzjqfofhl.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtowdsavpg.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.havefunace.top/Article/details/gtapsfrbra.html

[E10] 左侧补零 / 定长填充
来源：http://dali.birdmap.top/Article/details/gtajvmnfsa.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.gaohongyu789.top/Article/details/gtqmnaerlg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gogol.net.cn/Article/details/gtgiwojnqz.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxsqfkooc.html

TS:   "7".padStart(3, "0")
来源：http://dali.guannengcc.top/Article/details/gtuwivvylo.html

Java: String.format("%03d", 7)
来源：http://dali.xylfe.cn/Article/details/gtaclyzxil.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sysykeji.top/Article/details/gtqparrryh.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shzxlz.cn/Article/details/gtcgbugyjc.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.aizwys.cn/Article/details/gtcgjgkwyd.html

[E11] 反转字符串
来源：http://dali.sxryk.cn/Article/details/gtjcqpqnkz.html

Py:   s[::-1]
来源：http://dali.cashguo.top/Article/details/gtpgfvdnrg.html

PHP:  strrev($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtgexldzqb.html

JS:   [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gtyohujrmc.html

TS:   [...s].reverse().join("")
来源：http://dali.yvedp.cn/Article/details/gtadqwmstb.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gtqgbplibi.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.pengpengdd.cyou/Article/details/gtjgdgweot.html

Ruby: s.reverse
来源：http://dali.hnxiangtu.top/Article/details/gtpkxstnvc.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ehwqpu.com/Article/details/gtlmchbgtl.html

[E12] 统计某字符出现次数
来源：http://dali.fzhhl.top/Article/details/gtrdqdfibv.html

Py:   s.count("a")
来源：http://dali.yongpay.top/Article/details/gttdluiawj.html

PHP:  substr_count($s, "a");
来源：http://dali.vqdsnc.cn/Article/details/gtojqfwisa.html

JS:   s.split("a").length - 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxdzrdwtv.html

TS:   s.split("a").length - 1
来源：http://dali.wangshuangyany.cn/Article/details/gtkgaibfaw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.316326.xyz/Article/details/gtpqtxpadx.html

Go:   strings.Count(s, "a")
来源：http://dali.jyoumei.cn/Article/details/gtybjpdrnl.html

Ruby: s.count("a")
来源：http://dali.smart0.xyz/Article/details/gtecjrcdsm.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfcsqeflb.html

[E13] 逐字符遍历
来源：http://dali.ehwqpu.com/Article/details/gtfqnrqjkx.html

Py:   for ch in s: print(ch)
来源：http://dali.sweek.top/Article/details/gtebxncyeb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.chenzaomai.com/Article/details/gtsmhkohjm.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkjhdqwbn.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinqigufen.top/Article/details/gtygblhyct.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cashguo.top/Article/details/gtkkktxayj.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.chenlongwang.top/Article/details/gtbgliyyva.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.chenjidiqi.icu/Article/details/gtbbqnthne.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.fengsongda.top/Article/details/gtkjbelozq.html

[E14] URL 编码与 Base64
来源：http://dali.yj202588.top/Article/details/gtdndvjsem.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yj202588.top/Article/details/gtylltmiic.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.tanke756.top/Article/details/gtpofqevgc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.pengpengdd.cyou/Article/details/gtnbqsibuv.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.quarkkingdee.top/Article/details/gtbjzhxorv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.nanxuanxn.top/Article/details/gtqvzemjcl.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.birdmap.top/Article/details/gtqseopilf.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.pengpengdd.cyou/Article/details/gtqnhtapay.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.dianchejie.cn/Article/details/gtnnlbazbu.html

[E15] HTML 转义 / 反转义
来源：http://dali.yangfankeji.com/Article/details/gtlgepizpj.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.tanke756.top/Article/details/gtekgyceqy.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.c1oappe.top/Article/details/gtccjeasrb.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxbvladym.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yuanzhike.top/Article/details/gtlqteajdh.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yuxming.cn/Article/details/gtdtrgqvar.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.haohaochexian.top/Article/details/gtldzioaaw.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gotoacloud.top/Article/details/gtvqzrlssd.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ppjwa.cn/Article/details/gtpelcvexh.html

[E16] 数字千分位
来源：http://dali.zhixingplan.top/Article/details/gtlhdnuavy.html

Py:   f"{1234567:,}"
来源：http://dali.cdnleiting.top/Article/details/gteufswbjv.html

PHP:  number_format(1234567);
来源：http://dali.daria6918.cn/Article/details/gtdvhyqsol.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj202588.top/Article/details/gtfthrqigl.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hywenlv.cn/Article/details/gtzijmqdsm.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.smart0.xyz/Article/details/gtymzrqugq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.wangdashe.top/Article/details/gtnwrvynag.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.haohaochexian.top/Article/details/gtrcghtvqc.html

C#:   1234567.ToString("N0")
来源：http://dali.jianghu66.top/Article/details/gtnlpptyck.html

[E17] 首字母大写
来源：http://dali.jyoumei.cn/Article/details/gtdjacfuhe.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.pengpengdd.cyou/Article/details/gtrmmiiund.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.aibaodan.cn/Article/details/gtvevshsno.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ydzc1.top/Article/details/gtndjylgxa.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hfpthk.cn/Article/details/gtlmmuoovh.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yongpay.top/Article/details/gtwrzfbjyo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cdnleiting.top/Article/details/gtdqldutye.html

Ruby: s.capitalize
来源：http://dali.svipenyu.cn/Article/details/gthpfqmdsf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yonumen.top/Article/details/gtswrjxali.html

[E18] 模板占位符替换
来源：http://dali.havefunace.top/Article/details/gtdxcnkrww.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjhtuzzdy.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yuanzhike.top/Article/details/gtnbsfavnn.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhengqikj.top/Article/details/gtzrnloeza.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gthbklzche.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gthbydzlvm.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gtdixhfcck.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jlsjyb.cn/Article/details/gtiyjdvlcz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhixingplan.top/Article/details/gtnqtgsrif.html

[E19] 多行文本按行拆分
来源：http://dali.sysykeji.top/Article/details/gtdmolehoh.html

Py:   s.splitlines()
来源：http://dali.ybcxt.top/Article/details/gtmtmlpaec.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gthqslfvyt.html

JS:   s.split(/\r?\n/)
来源：http://dali.9152youxi.cn/Article/details/gtmgdvvexz.html

TS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtaedflcqd.html

Java: s.lines().toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvgsytcyc.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhiwuduotai.top/Article/details/gtkuqtobqi.html

Ruby: s.lines
来源：http://dali.hywenlv.cn/Article/details/gtnwxzbesj.html

C#:   s.Split('\n')
来源：http://dali.shanyushiyangtech.top/Article/details/gtwladczcl.html

[E20] 判断字符串是否为空
来源：http://dali.zhiwuduotai.top/Article/details/gtsnyjjzui.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gtlhvledjp.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.tian-w.cn/Article/details/gtsfhidwqc.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gogol.net.cn/Article/details/gtrqtegpjg.html

TS:   if (s === "") {}
来源：http://dali.guowangkeji.top/Article/details/gtjbntmkip.html

Java: if (s.isEmpty()) {}
来源：http://dali.xuanzx.com/Article/details/gtuuxsxckz.html

Go:   if s == "" {}
来源：http://dali.svipenyu.cn/Article/details/gtbpdogqgx.html

Ruby: if s.empty?
来源：http://dali.hysaishi.cn/Article/details/gtwexlgjev.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.guannengcc.top/Article/details/gtacenxcfv.html

[E21] 超长截断加省略号
来源：http://dali.nwbrower.top/Article/details/gthrrjkpxt.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ppjwa.cn/Article/details/gtdjiddczv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gtyhkkfgvo.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daria6918.cn/Article/details/gtcfbaxrcc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.birdmap.top/Article/details/gtbsneexdc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.c1oappe.top/Article/details/gtwmsxcyqx.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yanxiufei.cn/Article/details/gtwwvyfyfk.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.tian-w.cn/Article/details/gtlssbsfgi.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.fzhhl.top/Article/details/gtpccakcit.html

[E22] 字节长度与字符长度
来源：http://dali.jianghu66.top/Article/details/gttftmrbvj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yuanzhike.top/Article/details/gtuinbaxxh.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gtqvzmtlha.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jlsjyb.cn/Article/details/gtsadroxep.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.316326.xyz/Article/details/gtigegxhiq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hnxiangtu.top/Article/details/gtwhlxqbty.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ppjwa.cn/Article/details/gtqnublajg.html

Ruby: s.bytesize;  s.length
来源：http://dali.vqdsnc.cn/Article/details/gthnfocaky.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xuetiantiany.cn/Article/details/gtzervuapi.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtqyqgmgrb.html

F. 文件与目录
来源：http://dali.jlsjyb.cn/Article/details/gtrbysvxbm.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtcgqrlppp.html

[F01] 读取整个文件
来源：http://dali.jiagoushi.top/Article/details/gtjckvuqkx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.316326.xyz/Article/details/gtsqqwdckp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtnrckefyf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gotoacloud.top/Article/details/gtndrnjpks.html


<!-- 参考信息 -->