代发 wailian999

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cqqwz.cn/Article/details/gttaaeqmbi.html

C#:   list.Sum();  list.Average()
来源：http://dali.hammf.cn/Article/details/gtifunvqdq.html

[D17] 最大值与最小值
来源：http://dali.zhixingplan.top/Article/details/gtrwrwvegl.html

Py:   max(arr);  min(arr)
来源：http://dali.bjfxy.top/Article/details/gtkynihkpd.html

PHP:  max($arr);  min($arr);
来源：http://dali.jinqigufen.top/Article/details/gtexcqparh.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.aibaodan.cn/Article/details/gtkyhnxltv.html

TS:   Math.max(...arr);
来源：http://dali.cucudq.cn/Article/details/gtikmbgrog.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xuanzx.com/Article/details/gtcunnfvob.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gttsrzwavr.html

Ruby: arr.max;  arr.min
来源：http://dali.xylfe.cn/Article/details/gtrccyfvay.html

C#:   list.Max();  list.Min()
来源：http://dali.fengsongda.top/Article/details/gtcqnzxvgn.html

[D18] 扁平化嵌套数组
来源：http://dali.wangshuangyany.cn/Article/details/gtwhnmsrvl.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gtvzfcneol.html

PHP:  array_merge(...$nested);
来源：http://dali.jqgufenzy.top/Article/details/gtvxjymyco.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jinqigufen.top/Article/details/gtiowdvkkq.html

TS:   nested.flat();
来源：http://dali.jinghuilouyu.cn/Article/details/gtmuqrkypb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jinqigfzy.top/Article/details/gtexhbihxa.html

Go:   // 手写双层循环
来源：http://dali.gogol.net.cn/Article/details/gtokexyeex.html

Ruby: nested.flatten
来源：http://dali.hnxiangtu.top/Article/details/gtsiqpuott.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.nanxinkj.top/Article/details/gtraecsowu.html

[D19] 按字段分组
来源：http://dali.zhongyouzk.top/Article/details/gtxmedlgpw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.nanxuanxn.top/Article/details/gtqonfsgyv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.9152youxi.cn/Article/details/gtwuxgydlm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcxahtjpl.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xylfe.cn/Article/details/gtolnirqca.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cucudq.cn/Article/details/gtnzvmttnk.html

Go:   // 手写 map[string][]T
来源：http://dali.jiagoushi.top/Article/details/gtdyylgirm.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.smart0.xyz/Article/details/gtdpuwauvp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.chenjidiqi.icu/Article/details/gtkahyqqan.html

[D20] 统计每个元素出现次数
来源：http://dali.guannengcc.top/Article/details/gtqrgctqfq.html

Py:   Counter(arr)
来源：http://dali.jqgfzy.top/Article/details/gtelwywzmi.html

PHP:  array_count_values($arr);
来源：http://dali.yueranfly.top/Article/details/gtfhmynnhd.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yangfankeji.com/Article/details/gtsmominck.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cucudq.cn/Article/details/gtjpcvhtrw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gaohongyu789.top/Article/details/gtdegwhgww.html

Go:   // 手写 map[T]int
来源：http://dali.meibo888.top/Article/details/gtbztifsef.html

Ruby: arr.tally
来源：http://dali.gogol.net.cn/Article/details/gtfrgmdour.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.vqdsnc.cn/Article/details/gtqgvxaoct.html

[D21] 判断是否包含某元素
来源：http://dali.guowangkeji.top/Article/details/gtgkgcnfgc.html

Py:   x in arr
来源：http://dali.zhixingplan.top/Article/details/gtdnxypzir.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sysykeji.top/Article/details/gtziywxhlv.html

JS:   arr.includes(x)
来源：http://dali.sxryk.cn/Article/details/gtccrzepgy.html

TS:   arr.includes(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtasjwkhxt.html

Java: list.contains(x)
来源：http://dali.aizwys.cn/Article/details/gtwmfrggph.html

Go:   slices.Contains(arr, x)
来源：http://dali.yongpay.top/Article/details/gtwensblzz.html

Ruby: arr.include?(x)
来源：http://dali.mhx1999.top/Article/details/gttfzipwhl.html

C#:   list.Contains(x)
来源：http://dali.gaohongyu789.top/Article/details/gtfrmhcydi.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jlsjyb.cn/Article/details/gtzjxxhvdz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.guowangkeji.top/Article/details/gtmhfrqzis.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.andypj.xyz/Article/details/gtmgxyqfvu.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hysaishi.cn/Article/details/gtxqjpszka.html

TS:   [...arr];
来源：http://dali.nwbrower.top/Article/details/gtzbpfpzvi.html

Java: new ArrayList<>(list);
来源：http://dali.tianlin.xyz/Article/details/gtmowoqxkr.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cheryme.top/Article/details/gtrxvwfiuw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.tianlin.xyz/Article/details/gtirsqgijg.html

C#:   new List<int>(list);
来源：http://dali.xylfe.cn/Article/details/gtcrufqtnh.html

[D23] reduce 累积计算
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxpbzycgc.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.9152youxi.cn/Article/details/gtjrbehfgm.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yangfankeji.com/Article/details/gtqhhvmzoh.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shuidangran.top/Article/details/gtvzoytjim.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cashguo.top/Article/details/gtuwmaznzd.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.fengsongda.top/Article/details/gtjwfbtjpj.html

Go:   // 手写循环
来源：http://dali.nwbrower.top/Article/details/gtpljleace.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hfpthk.cn/Article/details/gtzdbpxfag.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.wangshuangyany.cn/Article/details/gtylmjfgqj.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gtmjhtmpmv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ivvv.top/Article/details/gtwzwakaak.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cucudq.cn/Article/details/gtasyvxtdh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.bjfxy.top/Article/details/gtdcjdntqv.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.tian-w.cn/Article/details/gtgsqwvfle.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.gzhubu.top/Article/details/gtyydhrjwd.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ydzc1.top/Article/details/gtbvopzqba.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.daxiang520.top/Article/details/gtoglssflf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.feifeiyinyue.top/Article/details/gtrcofdvwm.html

[D25] Set 集合去重与交并差
来源：http://dali.hnxiangtu.top/Article/details/gtacstyafi.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hysaishi.cn/Article/details/gtgospmydn.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.0kj1m.cn/Article/details/gtylcdhnkg.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cucudq.cn/Article/details/gtouxrblqy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcmzpsgni.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ybcxt.top/Article/details/gtejpklqrr.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yj20258.top/Article/details/gtvddenzei.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.kuanghao11.cn/Article/details/gtgzamkbrc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.birdmap.top/Article/details/gtdxmyveou.html

[D26] 数组转字符串
来源：http://dali.aizwys.cn/Article/details/gtgnfasjmm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgxknchhm.html

PHP:  implode(", ", $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtynnvddsv.html

JS:   arr.join(", ")
来源：http://dali.shanyushiyangtech.top/Article/details/gtaedkoycc.html

TS:   arr.join(", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlhoyrvtd.html

Java: String.join(", ", list)
来源：http://dali.c1oappe.top/Article/details/gtrcdafzlp.html

Go:   strings.Join(strs, ", ")
来源：http://dali.fengsongda.top/Article/details/gtzcenbgxj.html

Ruby: arr.join(", ")
来源：http://dali.hnqzz.top/Article/details/gtxjeamnlq.html

C#:   string.Join(", ", list)
来源：http://dali.9152youxi.cn/Article/details/gtaybbphio.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtmgwoxxyw.html

E. 字符串处理
来源：http://dali.yj20258888.top/Article/details/gtlfzoxzci.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtclhntihu.html

[E01] 拼接字符串
来源：http://dali.yanxiufei.cn/Article/details/gtsbcmropa.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yuxming.cn/Article/details/gtpaawnspq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yongpay.top/Article/details/gteqaqgrym.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.316326.xyz/Article/details/gtpcociigm.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtwucmsmqs.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.dashuyun.cn/Article/details/gtnssrdxps.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ivvv.top/Article/details/gtkdqobjzn.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.guannengcc.top/Article/details/gtfwddjczj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yuxming.cn/Article/details/gtuqhckgkz.html

[E02] 重复字符串
来源：http://dali.cucudq.cn/Article/details/gtrsvrjgfj.html

Py:   "ab" * 3
来源：http://dali.jyoumei.cn/Article/details/gtgmurpypg.html

PHP:  str_repeat("ab", 3);
来源：http://dali.guowangkeji.top/Article/details/gtqrducaoj.html

JS:   "ab".repeat(3)
来源：http://dali.gaohongyu789.top/Article/details/gtpiiposxy.html

TS:   "ab".repeat(3)
来源：http://dali.guannengcc.top/Article/details/gtswdzsatf.html

Java: "ab".repeat(3)
来源：http://dali.cucudq.cn/Article/details/gtdyeiwrmr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtypscmoks.html

Ruby: "ab" * 3
来源：http://dali.mhx1999.top/Article/details/gtzqfkkxsx.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.chenlongwang.top/Article/details/gtbmhjlqgq.html

[E03] 截取子串
来源：http://dali.vqdsnc.cn/Article/details/gtthhqklde.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yvedp.cn/Article/details/gtzvnidrpa.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.nanxuanxn.top/Article/details/gtdxtuconn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.wangshuangyany.cn/Article/details/gtlsqefcai.html

TS:   s.slice(1, 4)
来源：http://dali.wangdashe.top/Article/details/gtzgebwzlz.html

Java: s.substring(1, 4)
来源：http://dali.mhx1999.top/Article/details/gtuknwazfv.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cucudq.cn/Article/details/gthydxzegt.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.guannengcc.top/Article/details/gtiujdwvfz.html

C#:   s.Substring(1, 3)
来源：http://dali.dianchejie.cn/Article/details/gtmwdorgqf.html

[E04] 查找子串位置
来源：http://dali.gogol.net.cn/Article/details/gteueuazyj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.nwbrower.top/Article/details/gtgxvysybq.html

PHP:  strpos($s, "x");
来源：http://dali.yangfankeji.com/Article/details/gtezjjawpx.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.0kj1m.cn/Article/details/gtshjddmli.html

TS:   s.indexOf("x")
来源：http://dali.nanxinkj.top/Article/details/gtkngoujsc.html

Java: s.indexOf("x")
来源：http://dali.ppjwa.cn/Article/details/gtwmiucihp.html

Go:   strings.Index(s, "x")
来源：http://dali.yongpay.top/Article/details/gtljfryejt.html

Ruby: s.index("x")
来源：http://dali.xinyue.icu/Article/details/gtvagtmgss.html

C#:   s.IndexOf("x")
来源：http://dali.pycfn.com/Article/details/gtonlwwxvp.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.aibaodan.cn/Article/details/gtyxlhiukg.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.smart0.xyz/Article/details/gtuyuzgwzq.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhoulong.xyz/Article/details/gtlvsnfgnz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tian-w.cn/Article/details/gtpgnbcqhx.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jqgufenzy.top/Article/details/gtvnazezta.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinqigufen.top/Article/details/gtdolozhzg.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jinqigufen.top/Article/details/gtuynqzwgi.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.daria6918.cn/Article/details/gtynprvbbg.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.redwolf501.top/Article/details/gtjwnctaqn.html

[E06] 替换子串
来源：http://dali.tian-w.cn/Article/details/gtjlcauswd.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.daria6918.cn/Article/details/gtnykwagsj.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hysaishi.cn/Article/details/gtbdfiuami.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gtckubooco.html

TS:   s.replaceAll("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gteiwdqamf.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gtfpavgzqu.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zdqjudy.top/Article/details/gtqeveybzq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xinyue.icu/Article/details/gtvdrialna.html

C#:   s.Replace("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gttnytbhlz.html

[E07] 按分隔符拆分
来源：http://dali.jinghuilouyu.cn/Article/details/gtnfltgcca.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xuetiantiany.cn/Article/details/gtcvfjxpea.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhixingplan.top/Article/details/gtfjvhspvz.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.kuanghao11.cn/Article/details/gthmbswvym.html

TS:   s.split(",")
来源：http://dali.sysykeji.top/Article/details/gthoichyvm.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmhnlmvrb.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yj20258888.top/Article/details/gtkhassznb.html

Ruby: s.split(",");  s.split
来源：http://dali.cqqwz.cn/Article/details/gtlvgynqcl.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.chenzaomai.com/Article/details/gtxfisbvrh.html

[E08] 数组按分隔符合并
来源：http://dali.fzhhl.top/Article/details/gtgkrzokvw.html

Py:   ",".join(items)
来源：http://dali.yueranfly.top/Article/details/gtrctgiete.html

PHP:  implode(",", $items);
来源：http://dali.sufxvd.cn/Article/details/gtfvlxgfeq.html

JS:   items.join(",")
来源：http://dali.fengsongda.top/Article/details/gtunfedbau.html

TS:   items.join(",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthugbzevh.html

Java: String.join(",", items)
来源：http://dali.shzxlz.cn/Article/details/gteojrvbnq.html

Go:   strings.Join(items, ",")
来源：http://dali.0kj1m.cn/Article/details/gtsmmueszt.html

Ruby: items.join(",")
来源：http://dali.sysykeji.top/Article/details/gtyliekdkw.html

C#:   string.Join(",", items)
来源：http://dali.yonumen.top/Article/details/gtksztjuom.html

[E09] 去除所有空白字符
来源：http://dali.316326.xyz/Article/details/gtfehambjc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sufxvd.cn/Article/details/gthxbcojbu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cqqwz.cn/Article/details/gthnqwxjra.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.quarkkingdee.top/Article/details/gtvfzqqyas.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.chenjidiqi.icu/Article/details/gtzfjfujos.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ivvv.top/Article/details/gtykqqfsyn.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shangyingyoupin.top/Article/details/gtvmebxcjd.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ehwqpu.com/Article/details/gtjaelwhjz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.aizwys.cn/Article/details/gtbprqrexc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrylmixjs.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yanxiufei.cn/Article/details/gtaghhctmw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.birdmap.top/Article/details/gtezwvxbhl.html

JS:   "7".padStart(3, "0")
来源：http://dali.hnxiangtu.top/Article/details/gtoeczdvch.html

TS:   "7".padStart(3, "0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqrwifogx.html

Java: String.format("%03d", 7)
来源：http://dali.yanxiufei.cn/Article/details/gtgniiabcr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hongshengwenyu.top/Article/details/gtlsszipik.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yj20258888.top/Article/details/gtriegiycj.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.havefunace.top/Article/details/gtjzhjbqlq.html

[E11] 反转字符串
来源：http://dali.wangdashe.top/Article/details/gtuoshcldt.html

Py:   s[::-1]
来源：http://dali.mhx1999.top/Article/details/gtsneqtppl.html

PHP:  strrev($s);
来源：http://dali.mhx1999.top/Article/details/gtjgunpgrn.html

JS:   [...s].reverse().join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtcnlsubpi.html

TS:   [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gtwolbwdcx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yvedp.cn/Article/details/gtiitxhard.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.316326.xyz/Article/details/gtwtxrozbp.html

Ruby: s.reverse
来源：http://dali.0kj1m.cn/Article/details/gtthjmkzsd.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cqqwz.cn/Article/details/gtcieaqcqs.html

[E12] 统计某字符出现次数
来源：http://dali.gaohongyu789.top/Article/details/gtfefexvbl.html

Py:   s.count("a")
来源：http://dali.sysykeji.top/Article/details/gtfkygswjy.html

PHP:  substr_count($s, "a");
来源：http://dali.ppjwa.cn/Article/details/gtqzkwygny.html

JS:   s.split("a").length - 1
来源：http://dali.zdqjudy.top/Article/details/gtzrnozvwk.html

TS:   s.split("a").length - 1
来源：http://dali.wangshuangyany.cn/Article/details/gtbuhfobvm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cdnleiting.top/Article/details/gtdbcsmqlp.html

Go:   strings.Count(s, "a")
来源：http://dali.ivvv.top/Article/details/gtzwzwlazh.html

Ruby: s.count("a")
来源：http://dali.sweek.top/Article/details/gtrwenzfps.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jianghu66.top/Article/details/gtowbnbxsz.html

[E13] 逐字符遍历
来源：http://dali.cqqwz.cn/Article/details/gtsvclknak.html

Py:   for ch in s: print(ch)
来源：http://dali.tianlin.xyz/Article/details/gtfwtmarsv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.daxiang520.top/Article/details/gtdbidrqvc.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhengqikj.top/Article/details/gtlqeblzpl.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpztuhoog.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shuidangran.top/Article/details/gtarswtzyo.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.havefunace.top/Article/details/gtrvuhroit.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.iojbl.cn/Article/details/gtiqsfyazk.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.haohaochexian.top/Article/details/gtlrjqxlcl.html

[E14] URL 编码与 Base64
来源：http://dali.yueranfly.top/Article/details/gtjlzalhvo.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhengqikj.top/Article/details/gtaopwillz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jiagoushi.top/Article/details/gtqcenydbd.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvenjbqkv.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xylfe.cn/Article/details/gtpxpokyav.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.tian-w.cn/Article/details/gtxvvnigcc.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.redwolf501.top/Article/details/gtrebzanfa.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.316326.xyz/Article/details/gtymjkdqkw.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.dianchejie.cn/Article/details/gtjcxxvbse.html

[E15] HTML 转义 / 反转义
来源：http://dali.jianghu66.top/Article/details/gtvzgarpys.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.aibaodan.cn/Article/details/gtuwkbravs.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yj202588.top/Article/details/gtqxasrodi.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.birdmap.top/Article/details/gtdeoxheeb.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cqqwz.cn/Article/details/gtgcfsnvvf.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yj20258888.top/Article/details/gtwnsvhxso.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinqigufen.top/Article/details/gtixqzedsb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.wangdashe.top/Article/details/gtjqcpnmhu.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shzxlz.cn/Article/details/gthsdmpgia.html

[E16] 数字千分位
来源：http://dali.iojbl.cn/Article/details/gtnrwxykcz.html

Py:   f"{1234567:,}"
来源：http://dali.vqdsnc.cn/Article/details/gtiiarqqbi.html

PHP:  number_format(1234567);
来源：http://dali.shzxlz.cn/Article/details/gtibseywtv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ppjwa.cn/Article/details/gtaktoyihz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.9152youxi.cn/Article/details/gtlntchlhi.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbgsofxbu.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hnqzz.top/Article/details/gteyxeanea.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yj202588.top/Article/details/gtmfmsbutf.html

C#:   1234567.ToString("N0")
来源：http://dali.aizwys.cn/Article/details/gtrqutkmio.html

[E17] 首字母大写
来源：http://dali.chenjidiqi.icu/Article/details/gtbsstbczg.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.quarkkingdee.top/Article/details/gtjmacgqup.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sufxvd.cn/Article/details/gtbltvmbnz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gtoirdnvob.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbfrxclwt.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yj20258.top/Article/details/gtaxqvjuel.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cdnleiting.top/Article/details/gtxdazxzip.html

Ruby: s.capitalize
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlrrueqyx.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shanyushiyangtech.top/Article/details/gttsshxzza.html

[E18] 模板占位符替换
来源：http://dali.dianchejie.cn/Article/details/gtonlaplaw.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cdnleiting.top/Article/details/gtinpdblex.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zdqjudy.top/Article/details/gtrqbwlqrm.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shangyingyoupin.top/Article/details/gtrnwbqute.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.redwolf501.top/Article/details/gtdzmtbnwk.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.guannengcc.top/Article/details/gtzyvnedbz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gttftnplgt.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xinyue.icu/Article/details/gtjtzyjeyq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.iojbl.cn/Article/details/gtgpbmynze.html

[E19] 多行文本按行拆分
来源：http://dali.jinqigfzy.top/Article/details/gtikljwhfr.html

Py:   s.splitlines()
来源：http://dali.vqdsnc.cn/Article/details/gthywljcjb.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yj20258888.top/Article/details/gtdgecumjm.html

JS:   s.split(/\r?\n/)
来源：http://dali.jinqigfzy.top/Article/details/gtlnvxeeqt.html

TS:   s.split(/\r?\n/)
来源：http://dali.yj20258.top/Article/details/gtqiagumtd.html

Java: s.lines().toList()
来源：http://dali.daria6918.cn/Article/details/gtsqpkqkeq.html

Go:   strings.Split(s, "\n")
来源：http://dali.zycfv.cn/Article/details/gtqnbngrvv.html

Ruby: s.lines
来源：http://dali.wangshuangyany.cn/Article/details/gtrzhmsdhm.html

C#:   s.Split('\n')
来源：http://dali.quarkkingdee.top/Article/details/gtmiwwvjpv.html

[E20] 判断字符串是否为空
来源：http://dali.jinqigfzy.top/Article/details/gtqiqogbga.html

Py:   if not s:
来源：http://dali.316326.xyz/Article/details/gtqqgctwvs.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gzhubu.top/Article/details/gtcsktafgd.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yongpay.top/Article/details/gtdwcgdnjf.html

TS:   if (s === "") {}
来源：http://dali.quarkkingdee.top/Article/details/gticvmqoks.html

Java: if (s.isEmpty()) {}
来源：http://dali.fengsongda.top/Article/details/gtucbgvpjp.html

Go:   if s == "" {}
来源：http://dali.jianghu66.top/Article/details/gtednqycwa.html

Ruby: if s.empty?
来源：http://dali.gaohongyu789.top/Article/details/gtixzpyryx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.svipenyu.cn/Article/details/gtkfslzyus.html

[E21] 超长截断加省略号
来源：http://dali.c1oappe.top/Article/details/gtyemyaclu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.pycfn.com/Article/details/gtablgdmsl.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.pycfn.com/Article/details/gttfbusyba.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yongpay.top/Article/details/gtnogqvtta.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sxryk.cn/Article/details/gtfblqgwll.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sysykeji.top/Article/details/gtpgqrbgud.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.birdmap.top/Article/details/gtpabmwghp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gtlwixwzpx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gtkwllervc.html

[E22] 字节长度与字符长度
来源：http://dali.yanxiufei.cn/Article/details/gthpjtrlvt.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.bjfxy.top/Article/details/gtvzqmhjem.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xziqi.cn/Article/details/gtmmbhoxim.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhixingplan.top/Article/details/gtychunmap.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258.top/Article/details/gtrhmteuiv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hongshengwenyu.top/Article/details/gtztqkfyrf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ppjwa.cn/Article/details/gtvuuohbmt.html

Ruby: s.bytesize;  s.length
来源：http://dali.pengpengdd.cyou/Article/details/gthitlnkfi.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shanyushiyangtech.top/Article/details/gtvxgnwhsc.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtmutundab.html

F. 文件与目录
来源：http://dali.aizwys.cn/Article/details/gtrpmlqhkx.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtmjozvlee.html

[F01] 读取整个文件
来源：http://dali.andypj.xyz/Article/details/gtemmrrsvx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdibeombp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtczooqqxq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinghuilouyu.cn/Article/details/gtgydureas.html


<!-- 参考信息 -->