代发 wailian999

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shuidangran.top/Article/details/gtwzkfkpgb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.nanxinkj.top/Article/details/gtitplzund.html

JS:   arr.map(x => x * 2)
来源：http://dali.hammf.cn/Article/details/gtwpessund.html

TS:   arr.map(x => x * 2)
来源：http://dali.shzxlz.cn/Article/details/gthdwjyuyf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.meibo888.top/Article/details/gtgtnwobxf.html

Go:   // 手写循环
来源：http://dali.aibaodan.cn/Article/details/gtikcdhudq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ydzc1.top/Article/details/gtyogesotd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.9152youxi.cn/Article/details/gttqyyhkbb.html

[D15] 去重
来源：http://dali.zhiwuduotai.top/Article/details/gtsnkobbnv.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yonumen.top/Article/details/gtciivundp.html

PHP:  array_unique($arr);
来源：http://dali.haohaochexian.top/Article/details/gtzczhystm.html

JS:   [...new Set(arr)]
来源：http://dali.jqgfzy.top/Article/details/gtfmbitksl.html

TS:   [...new Set(arr)]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtusbeihtm.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.c1oappe.top/Article/details/gtqgsqclkr.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yueranfly.top/Article/details/gtbnihcjfj.html

Ruby: arr.uniq
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtifaytrfl.html

C#:   list.Distinct().ToList()
来源：http://dali.daria6918.cn/Article/details/gtexbexcln.html

[D16] 求和与平均值
来源：http://dali.tian-w.cn/Article/details/gtqvovcddy.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xuanzx.com/Article/details/gtdlsagnnv.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.sufxvd.cn/Article/details/gtzyfxfjpn.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yonumen.top/Article/details/gtktfmzusv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jianghu66.top/Article/details/gtkqciolqt.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.sufxvd.cn/Article/details/gtzwddgfzq.html

Go:   // 手写循环累加
来源：http://dali.xuetiantiany.cn/Article/details/gtdgjqojnx.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.pengpengdd.cyou/Article/details/gtvkwcwtja.html

C#:   list.Sum();  list.Average()
来源：http://dali.vqdsnc.cn/Article/details/gtjodcgumv.html

[D17] 最大值与最小值
来源：http://dali.sweek.top/Article/details/gtmghbbcfo.html

Py:   max(arr);  min(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtmykymfpl.html

PHP:  max($arr);  min($arr);
来源：http://dali.tanke756.top/Article/details/gtkrhoauuy.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtadljyskq.html

TS:   Math.max(...arr);
来源：http://dali.daria6918.cn/Article/details/gtnthullmj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cheryme.top/Article/details/gtjspnkqtv.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtpwropouv.html

Ruby: arr.max;  arr.min
来源：http://dali.cucudq.cn/Article/details/gtjpksmpze.html

C#:   list.Max();  list.Min()
来源：http://dali.xuetiantiany.cn/Article/details/gtyidkjqfr.html

[D18] 扁平化嵌套数组
来源：http://dali.ydzc1.top/Article/details/gthgwvxkyi.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shanyushiyangtech.top/Article/details/gttxblksjb.html

PHP:  array_merge(...$nested);
来源：http://dali.aibaodan.cn/Article/details/gtmhnosnza.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cucudq.cn/Article/details/gtppsqwfbi.html

TS:   nested.flat();
来源：http://dali.nanxinkj.top/Article/details/gthwehgqgh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sufxvd.cn/Article/details/gtvdvtatyc.html

Go:   // 手写双层循环
来源：http://dali.hywenlv.cn/Article/details/gtumapctce.html

Ruby: nested.flatten
来源：http://dali.aizwys.cn/Article/details/gtaxggroex.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhixingplan.top/Article/details/gtcwpxhubb.html

[D19] 按字段分组
来源：http://dali.iojbl.cn/Article/details/gtjufoiula.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cqqwz.cn/Article/details/gtquvtwilp.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hnqzz.top/Article/details/gtxaglveyq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.tianlin.xyz/Article/details/gtduzwxvvj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cdnleiting.top/Article/details/gthmapargp.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jiagoushi.top/Article/details/gtfqlqhfde.html

Go:   // 手写 map[string][]T
来源：http://dali.c1oappe.top/Article/details/gthnrwpxpv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.9152youxi.cn/Article/details/gtxlzucpsd.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jianghu66.top/Article/details/gthzpelvdm.html

[D20] 统计每个元素出现次数
来源：http://dali.jinqigfzy.top/Article/details/gtxojurskv.html

Py:   Counter(arr)
来源：http://dali.yj202588.top/Article/details/gtufkeaucl.html

PHP:  array_count_values($arr);
来源：http://dali.gotoacloud.top/Article/details/gticepptag.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgfzy.top/Article/details/gtqykakmyi.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gzhubu.top/Article/details/gtybihpmtx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xinyue.icu/Article/details/gtlsfwzumr.html

Go:   // 手写 map[T]int
来源：http://dali.guowangkeji.top/Article/details/gtnmvbwvrg.html

Ruby: arr.tally
来源：http://dali.nwbrower.top/Article/details/gtccemabkm.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.nwbrower.top/Article/details/gtfzutxorf.html

[D21] 判断是否包含某元素
来源：http://dali.shangyingyoupin.top/Article/details/gtrmxyknog.html

Py:   x in arr
来源：http://dali.hywenlv.cn/Article/details/gtglfnjlea.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmbnxngwz.html

JS:   arr.includes(x)
来源：http://dali.tian-w.cn/Article/details/gtbopwnigx.html

TS:   arr.includes(x)
来源：http://dali.sysykeji.top/Article/details/gtztaqnixr.html

Java: list.contains(x)
来源：http://dali.iojbl.cn/Article/details/gtudhlqpme.html

Go:   slices.Contains(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gtiidlliea.html

Ruby: arr.include?(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtrwwrguai.html

C#:   list.Contains(x)
来源：http://dali.cqqwz.cn/Article/details/gtiflamsaq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.guowangkeji.top/Article/details/gthaqarejk.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.daria6918.cn/Article/details/gtizyxtswn.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sweek.top/Article/details/gtpycwrztr.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtsponivhs.html

TS:   [...arr];
来源：http://dali.yj202588.top/Article/details/gtslazlhvj.html

Java: new ArrayList<>(list);
来源：http://dali.cdnleiting.top/Article/details/gteprcxsck.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ydzc1.top/Article/details/gtpqibzavx.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gogol.net.cn/Article/details/gtlqiafgyx.html

C#:   new List<int>(list);
来源：http://dali.hongshengwenyu.top/Article/details/gtzlgfykuw.html

[D23] reduce 累积计算
来源：http://dali.andypj.xyz/Article/details/gtfawxbfsh.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hysaishi.cn/Article/details/gtcjyhoucz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jqgufenzy.top/Article/details/gtmfqaktiw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cheryme.top/Article/details/gtiocpfbyz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnlgcdjtt.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jqgufenzy.top/Article/details/gtqeziqtpo.html

Go:   // 手写循环
来源：http://dali.chenzaomai.com/Article/details/gtrfoakwzt.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jiagoushi.top/Article/details/gthhdzmigy.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ehwqpu.com/Article/details/gttkimnudt.html

[D24] 字典 / Map 基本操作
来源：http://dali.ehwqpu.com/Article/details/gtgwaprcyy.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yj20258888.top/Article/details/gthixaguen.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.svipenyu.cn/Article/details/gtwwodbvkd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.pycfn.com/Article/details/gtwzgtwukv.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jinqigfzy.top/Article/details/gtjmucadek.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yanxiufei.cn/Article/details/gtzednjlcy.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.chenjidiqi.icu/Article/details/gtnroykzbc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.dianchejie.cn/Article/details/gtjsfkykhh.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhoulong.xyz/Article/details/gtznxnsdit.html

[D25] Set 集合去重与交并差
来源：http://dali.zhixingplan.top/Article/details/gthebqugyw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.pengpengdd.cyou/Article/details/gtigqelwxh.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.fzhhl.top/Article/details/gtulowqzfh.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yongpay.top/Article/details/gtorpzgeos.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.tanke756.top/Article/details/gtrvjprhqx.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ivvv.top/Article/details/gthimyhgkr.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.bjfxy.top/Article/details/gtyegvybgx.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.chenzaomai.com/Article/details/gtdlwchldb.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.guannengcc.top/Article/details/gtkvbdssid.html

[D26] 数组转字符串
来源：http://dali.shuidangran.top/Article/details/gtrwctzity.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ppjwa.cn/Article/details/gtlcwfhfml.html

PHP:  implode(", ", $arr);
来源：http://dali.xziqi.cn/Article/details/gtpmmiglff.html

JS:   arr.join(", ")
来源：http://dali.ybcxt.top/Article/details/gtbiocfffg.html

TS:   arr.join(", ")
来源：http://dali.jyoumei.cn/Article/details/gtuzcgcnzg.html

Java: String.join(", ", list)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvgamfprj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.guannengcc.top/Article/details/gtdmtyicpr.html

Ruby: arr.join(", ")
来源：http://dali.zdqjudy.top/Article/details/gtynhhcsdl.html

C#:   string.Join(", ", list)
来源：http://dali.yangfankeji.com/Article/details/gtvszekqxk.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtxizgiunb.html

E. 字符串处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyvbosgea.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gthmbwajrs.html

[E01] 拼接字符串
来源：http://dali.daria6918.cn/Article/details/gtctgmglbl.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gotoacloud.top/Article/details/gtrprozrcg.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.chenlongwang.top/Article/details/gthehcxdtp.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.pycfn.com/Article/details/gtwsixdiag.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhoulong.xyz/Article/details/gtacwppybg.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtycoxlcaj.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shzxlz.cn/Article/details/gtnfsscmjz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xinyue.icu/Article/details/gtuwtrbqxy.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gtnhuwbise.html

[E02] 重复字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtpvielyav.html

Py:   "ab" * 3
来源：http://dali.cashguo.top/Article/details/gtmzfoskhl.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ehwqpu.com/Article/details/gtnrhvejvl.html

JS:   "ab".repeat(3)
来源：http://dali.meibo888.top/Article/details/gtavrhjuel.html

TS:   "ab".repeat(3)
来源：http://dali.iojbl.cn/Article/details/gtntodhcwh.html

Java: "ab".repeat(3)
来源：http://dali.xziqi.cn/Article/details/gtcbjjbvug.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpayqjyph.html

Ruby: "ab" * 3
来源：http://dali.chenlongwang.top/Article/details/gtfuyyepvg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.feifeiyinyue.top/Article/details/gtototcohq.html

[E03] 截取子串
来源：http://dali.tianlin.xyz/Article/details/gtegjqqamp.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.chenzaomai.com/Article/details/gtbstuginx.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shangyingyoupin.top/Article/details/gttcwmzbpu.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.bjfxy.top/Article/details/gtcujrsrmb.html

TS:   s.slice(1, 4)
来源：http://dali.ppjwa.cn/Article/details/gtyamhhefr.html

Java: s.substring(1, 4)
来源：http://dali.zhongyouzk.top/Article/details/gtbzxenxqc.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.kuanghao11.cn/Article/details/gtwuljbbjj.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yj20258888.top/Article/details/gtqpetxuzr.html

C#:   s.Substring(1, 3)
来源：http://dali.xuetiantiany.cn/Article/details/gtqitzympm.html

[E04] 查找子串位置
来源：http://dali.yonumen.top/Article/details/gtnijoboow.html

Py:   s.find("x");  s.index("x")
来源：http://dali.daxiang520.top/Article/details/gtlyxclmxb.html

PHP:  strpos($s, "x");
来源：http://dali.hongshengwenyu.top/Article/details/gtvmuklgdh.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhengqikj.top/Article/details/gtxqckfsbg.html

TS:   s.indexOf("x")
来源：http://dali.tian-w.cn/Article/details/gtmwtafyzz.html

Java: s.indexOf("x")
来源：http://dali.dianchejie.cn/Article/details/gtjusjzbxv.html

Go:   strings.Index(s, "x")
来源：http://dali.xinyue.icu/Article/details/gtbfnbaigk.html

Ruby: s.index("x")
来源：http://dali.jyoumei.cn/Article/details/gtmspqcnly.html

C#:   s.IndexOf("x")
来源：http://dali.yanxiufei.cn/Article/details/gtqrseolfl.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yangfankeji.com/Article/details/gtyffdrvqv.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.iojbl.cn/Article/details/gtughpesfz.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hammf.cn/Article/details/gtkqxjccpw.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhixingplan.top/Article/details/gtovohfaet.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.9152youxi.cn/Article/details/gtigcvbrpy.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhongyouzk.top/Article/details/gtwbhkzoup.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.nanxuanxn.top/Article/details/gthkyiolat.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yuanzhike.top/Article/details/gtnxnfdvtx.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.daxiang520.top/Article/details/gtopfjkgdl.html

[E06] 替换子串
来源：http://dali.aibaodan.cn/Article/details/gtxiktugzf.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.sxryk.cn/Article/details/gtdownkrbp.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.dianchejie.cn/Article/details/gtbaltxpbu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.birdmap.top/Article/details/gtphrtyzxz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtbxixrpqv.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.pycfn.com/Article/details/gtpctzurpi.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.tian-w.cn/Article/details/gtjzebzbtg.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtarcwpqay.html

C#:   s.Replace("a", "b")
来源：http://dali.xinyue.icu/Article/details/gtsmgwnvdk.html

[E07] 按分隔符拆分
来源：http://dali.wangdashe.top/Article/details/gtlclfulii.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hywenlv.cn/Article/details/gteebuuzew.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yueranfly.top/Article/details/gtmjlijxqf.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.gaohongyu789.top/Article/details/gtvbhbdjzm.html

TS:   s.split(",")
来源：http://dali.aizwys.cn/Article/details/gtoqghjmbz.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xziqi.cn/Article/details/gtokftuuwv.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yangfankeji.com/Article/details/gtluremenp.html

Ruby: s.split(",");  s.split
来源：http://dali.tian-w.cn/Article/details/gtkjrneiih.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.nwbrower.top/Article/details/gtkkfkicdk.html

[E08] 数组按分隔符合并
来源：http://dali.havefunace.top/Article/details/gtamujmffi.html

Py:   ",".join(items)
来源：http://dali.birdmap.top/Article/details/gtqvsvgctd.html

PHP:  implode(",", $items);
来源：http://dali.fengsongda.top/Article/details/gtfbdyvanv.html

JS:   items.join(",")
来源：http://dali.ybcxt.top/Article/details/gtxaoftgcu.html

TS:   items.join(",")
来源：http://dali.nwbrower.top/Article/details/gtvffzceiw.html

Java: String.join(",", items)
来源：http://dali.daxiang520.top/Article/details/gtiljmhizb.html

Go:   strings.Join(items, ",")
来源：http://dali.yvedp.cn/Article/details/gtdtzatbyi.html

Ruby: items.join(",")
来源：http://dali.pycfn.com/Article/details/gtlfteetrb.html

C#:   string.Join(",", items)
来源：http://dali.kuanghao11.cn/Article/details/gtiizafsxv.html

[E09] 去除所有空白字符
来源：http://dali.gogol.net.cn/Article/details/gtqhlpxtxn.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hywenlv.cn/Article/details/gtattgmqsi.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.svipenyu.cn/Article/details/gtdjoscjwy.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.sysykeji.top/Article/details/gtrugttsjl.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.dianchejie.cn/Article/details/gtlylfjoar.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.redwolf501.top/Article/details/gtsdkxurpi.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnjnihpyr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yvedp.cn/Article/details/gtheewvjat.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yongpay.top/Article/details/gtlplpsosb.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gaohongyu789.top/Article/details/gtmusmsxoe.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.snrcjt.cn/Article/details/gtgwhpvmkb.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.andypj.xyz/Article/details/gtezjizgoo.html

JS:   "7".padStart(3, "0")
来源：http://dali.fzhhl.top/Article/details/gtzsgrknws.html

TS:   "7".padStart(3, "0")
来源：http://dali.nanxuanxn.top/Article/details/gtkdlndlyg.html

Java: String.format("%03d", 7)
来源：http://dali.snrcjt.cn/Article/details/gtmecmdpzg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yanxiufei.cn/Article/details/gtnqlzbrba.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jyoumei.cn/Article/details/gtmxtwegzm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.quarkkingdee.top/Article/details/gttwavxwwi.html

[E11] 反转字符串
来源：http://dali.yuanzhike.top/Article/details/gtlcqjlbhw.html

Py:   s[::-1]
来源：http://dali.gzhubu.top/Article/details/gtcqtbsdtb.html

PHP:  strrev($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtggkyqumy.html

JS:   [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gtuddxljyy.html

TS:   [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gtmqhrpnux.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shzxlz.cn/Article/details/gtkwpaommi.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.tianlin.xyz/Article/details/gtuzckcbng.html

Ruby: s.reverse
来源：http://dali.bjfxy.top/Article/details/gtwanpfqwe.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.tian-w.cn/Article/details/gtzhpfjaex.html

[E12] 统计某字符出现次数
来源：http://dali.shzxlz.cn/Article/details/gtlrqbqgwj.html

Py:   s.count("a")
来源：http://dali.xinyue.icu/Article/details/gtlomnnwyu.html

PHP:  substr_count($s, "a");
来源：http://dali.yonumen.top/Article/details/gthjnsakov.html

JS:   s.split("a").length - 1
来源：http://dali.ivvv.top/Article/details/gtounnqtvl.html

TS:   s.split("a").length - 1
来源：http://dali.yangfankeji.com/Article/details/gttobhubgj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.mhx1999.top/Article/details/gtjwtiuoph.html

Go:   strings.Count(s, "a")
来源：http://dali.gaohongyu789.top/Article/details/gtoafcgbfa.html

Ruby: s.count("a")
来源：http://dali.haohaochexian.top/Article/details/gtfthjjhsf.html

C#:   s.Count(c => c == 'a')
来源：http://dali.0kj1m.cn/Article/details/gtlnrhulqw.html

[E13] 逐字符遍历
来源：http://dali.jiagoushi.top/Article/details/gtfhumcinl.html

Py:   for ch in s: print(ch)
来源：http://dali.c1oappe.top/Article/details/gtghdubxce.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hfpthk.cn/Article/details/gtbthgumvr.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jyoumei.cn/Article/details/gthjqdedyq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.316326.xyz/Article/details/gtraxybhny.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiptxjqrl.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gtiuqxnuhs.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhoulong.xyz/Article/details/gtcchtvgun.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zdqjudy.top/Article/details/gtsmvulguy.html

[E14] URL 编码与 Base64
来源：http://dali.havefunace.top/Article/details/gtjshhuhwt.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.tanke756.top/Article/details/gtzxndjgpn.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cheryme.top/Article/details/gtclawzmgj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtitzaaqsi.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.tanke756.top/Article/details/gtpgpublkp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xinyue.icu/Article/details/gtgqdrgkle.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.pycfn.com/Article/details/gtfcevxmuv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.pengpengdd.cyou/Article/details/gtpuhtbrui.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xuanzx.com/Article/details/gttgleegeh.html

[E15] HTML 转义 / 反转义
来源：http://dali.sysykeji.top/Article/details/gtatikcdgq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xuanzx.com/Article/details/gtuoxvnmai.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jqgfzy.top/Article/details/gtkmnluhiu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.chenlongwang.top/Article/details/gtdnwtkami.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.haohaochexian.top/Article/details/gtfpdixzyb.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.feifeiyinyue.top/Article/details/gtblrbwvwv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzeowzshl.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gtxckgmdmi.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xuanzx.com/Article/details/gtgxmphtmm.html

[E16] 数字千分位
来源：http://dali.zycfv.cn/Article/details/gtrbcdstcr.html

Py:   f"{1234567:,}"
来源：http://dali.ydzc1.top/Article/details/gtnxbonscd.html

PHP:  number_format(1234567);
来源：http://dali.cashguo.top/Article/details/gtfmvdtkho.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cqqwz.cn/Article/details/gtkylwqfky.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuetiantiany.cn/Article/details/gtdffsnqjf.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.daria6918.cn/Article/details/gtnsgxymfr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtngwirmyh.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sysykeji.top/Article/details/gtuwcfcats.html

C#:   1234567.ToString("N0")
来源：http://dali.nanxinkj.top/Article/details/gtaimdxokh.html

[E17] 首字母大写
来源：http://dali.wangdashe.top/Article/details/gteuduczqq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinqigufen.top/Article/details/gtkdhfkqmx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hfpthk.cn/Article/details/gtctuvntxc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgcceeiyc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daria6918.cn/Article/details/gtqpofwawk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ybcxt.top/Article/details/gtisthvadv.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.nanxuanxn.top/Article/details/gtrlipyfcf.html

Ruby: s.capitalize
来源：http://dali.jqgufenzy.top/Article/details/gtzehhioiz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.daria6918.cn/Article/details/gtfmhoomgf.html

[E18] 模板占位符替换
来源：http://dali.chenzaomai.com/Article/details/gtjpzenxbh.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cheryme.top/Article/details/gtyngxgulu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yanxiufei.cn/Article/details/gtmgzlupsh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gtgcmaticb.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gtyoqiniuy.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gotoacloud.top/Article/details/gthrifqcrc.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xylfe.cn/Article/details/gtjrfcbtmy.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yj20258888.top/Article/details/gtniqcycwt.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.daxiang520.top/Article/details/gtjwrmprrt.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gtfrzshpmq.html

Py:   s.splitlines()
来源：http://dali.9152youxi.cn/Article/details/gtueryrtxy.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yj202588.top/Article/details/gtbmofaxho.html

JS:   s.split(/\r?\n/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjbuozfmv.html

TS:   s.split(/\r?\n/)
来源：http://dali.hnxiangtu.top/Article/details/gtklxllbez.html

Java: s.lines().toList()
来源：http://dali.ydzc1.top/Article/details/gttewmybfn.html

Go:   strings.Split(s, "\n")
来源：http://dali.jinqigfzy.top/Article/details/gtbebdlnuy.html

Ruby: s.lines
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwolxmgfn.html

C#:   s.Split('\n')
来源：http://dali.zhengqikj.top/Article/details/gtiqlpiwnr.html

[E20] 判断字符串是否为空
来源：http://dali.hfpthk.cn/Article/details/gtxqedxtkv.html

Py:   if not s:
来源：http://dali.jqgfzy.top/Article/details/gtkmgsrbav.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.andypj.xyz/Article/details/gtgvezpjfs.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.andypj.xyz/Article/details/gtudtapkde.html

TS:   if (s === "") {}
来源：http://dali.cashguo.top/Article/details/gtzeiszujg.html

Java: if (s.isEmpty()) {}
来源：http://dali.tian-w.cn/Article/details/gtrpidbpeh.html

Go:   if s == "" {}
来源：http://dali.jlsjyb.cn/Article/details/gtgmsgzerr.html

Ruby: if s.empty?
来源：http://dali.yvedp.cn/Article/details/gtskuuiqeg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.pycfn.com/Article/details/gtuohbfigq.html

[E21] 超长截断加省略号
来源：http://dali.andypj.xyz/Article/details/gthskabupz.html


<!-- 参考信息 -->