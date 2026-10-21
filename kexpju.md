代发 wailian999

PHP:  max($arr);  min($arr);
来源：http://dali.andypj.xyz/Article/details/gtzbynnbjp.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yongpay.top/Article/details/gtpndmeypn.html

TS:   Math.max(...arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuugjnipw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cucudq.cn/Article/details/gtduvavaxp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zycfv.cn/Article/details/gtqrasavoc.html

Ruby: arr.max;  arr.min
来源：http://dali.cdnleiting.top/Article/details/gtctuadpgk.html

C#:   list.Max();  list.Min()
来源：http://dali.redwolf501.top/Article/details/gttngppjgi.html

[D18] 扁平化嵌套数组
来源：http://dali.wangshuangyany.cn/Article/details/gtfogqvwix.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.bjfxy.top/Article/details/gtvrbcurez.html

PHP:  array_merge(...$nested);
来源：http://dali.bjfxy.top/Article/details/gtfsyawbzr.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.havefunace.top/Article/details/gtwdvaekzp.html

TS:   nested.flat();
来源：http://dali.jinqigufen.top/Article/details/gtcmkotiyh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhoulong.xyz/Article/details/gtrnwndszv.html

Go:   // 手写双层循环
来源：http://dali.jinqigufen.top/Article/details/gtdlqphway.html

Ruby: nested.flatten
来源：http://dali.meibo888.top/Article/details/gtmqcbfnnn.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yj20258.top/Article/details/gthkdrxzdz.html

[D19] 按字段分组
来源：http://dali.ppjwa.cn/Article/details/gtlraylrom.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtmvigmkxd.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.nanxuanxn.top/Article/details/gtarnnjord.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.tianlin.xyz/Article/details/gtdmdyiqdu.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.chenlongwang.top/Article/details/gtzqrdufle.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jlsjyb.cn/Article/details/gtrarcnngb.html

Go:   // 手写 map[string][]T
来源：http://dali.wangshuangyany.cn/Article/details/gtwqhlwvnd.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hywenlv.cn/Article/details/gttgdpwrrv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shanyushiyangtech.top/Article/details/gtmgouyboz.html

[D20] 统计每个元素出现次数
来源：http://dali.sysykeji.top/Article/details/gthblghfgc.html

Py:   Counter(arr)
来源：http://dali.jinqigufen.top/Article/details/gtcjomtndz.html

PHP:  array_count_values($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtvzjffpvm.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shangyingyoupin.top/Article/details/gtldvrmtpm.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hfpthk.cn/Article/details/gtefkaveuo.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sxryk.cn/Article/details/gtvabqljqz.html

Go:   // 手写 map[T]int
来源：http://dali.yangfankeji.com/Article/details/gtasmtfofd.html

Ruby: arr.tally
来源：http://dali.iojbl.cn/Article/details/gtycwdlgnn.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hammf.cn/Article/details/gtogiykwmj.html

[D21] 判断是否包含某元素
来源：http://dali.zhoulong.xyz/Article/details/gtermgzvky.html

Py:   x in arr
来源：http://dali.yanxiufei.cn/Article/details/gtokicqjjb.html

PHP:  in_array($x, $arr, true);
来源：http://dali.meibo888.top/Article/details/gtoybigtzt.html

JS:   arr.includes(x)
来源：http://dali.xuetiantiany.cn/Article/details/gthtyyxuyx.html

TS:   arr.includes(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtyuttiygm.html

Java: list.contains(x)
来源：http://dali.sxryk.cn/Article/details/gtchclmeuv.html

Go:   slices.Contains(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gttmlecgvu.html

Ruby: arr.include?(x)
来源：http://dali.hnqzz.top/Article/details/gtlxejkfwr.html

C#:   list.Contains(x)
来源：http://dali.nwbrower.top/Article/details/gtvthlfirm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hnxiangtu.top/Article/details/gtsbfexqdr.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtwjvlmwsf.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhongyouzk.top/Article/details/gtfunyhkeg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.fengsongda.top/Article/details/gtmnwybkps.html

TS:   [...arr];
来源：http://dali.yj202588.top/Article/details/gtawtyaowf.html

Java: new ArrayList<>(list);
来源：http://dali.yvedp.cn/Article/details/gtillaspxr.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yangfankeji.com/Article/details/gtiblegrht.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sysykeji.top/Article/details/gtpzlpbtpr.html

C#:   new List<int>(list);
来源：http://dali.meibo888.top/Article/details/gtuclndzeb.html

[D23] reduce 累积计算
来源：http://dali.chenlongwang.top/Article/details/gtkluhryfo.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xuanzx.com/Article/details/gtygxeqekr.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hfpthk.cn/Article/details/gtsmorrzox.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtdzbqkfdp.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuanzhike.top/Article/details/gtlfqkcass.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.dianchejie.cn/Article/details/gtjzpvjvnj.html

Go:   // 手写循环
来源：http://dali.hnqzz.top/Article/details/gtlnxzzuot.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.pycfn.com/Article/details/gtirajqmav.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.smart0.xyz/Article/details/gtpqqftydy.html

[D24] 字典 / Map 基本操作
来源：http://dali.aibaodan.cn/Article/details/gtprodiszw.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yongpay.top/Article/details/gtecsvprwr.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.guannengcc.top/Article/details/gtbkimruod.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.tian-w.cn/Article/details/gtfhugruxf.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yj202588.top/Article/details/gtjwmcfujr.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.meibo888.top/Article/details/gtfjjpyodk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shzxlz.cn/Article/details/gtgzbnvexp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.quarkkingdee.top/Article/details/gtvpkbsyex.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yj202588.top/Article/details/gtqphstvrr.html

[D25] Set 集合去重与交并差
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkreyzwdn.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.mhx1999.top/Article/details/gtlstcrjfm.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.meibo888.top/Article/details/gtjbodpkvj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtueutvaam.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cucudq.cn/Article/details/gtdtzgsgzb.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xuanzx.com/Article/details/gtxqueyzuu.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xylfe.cn/Article/details/gtwpjbxdqn.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jlsjyb.cn/Article/details/gtvcwzjkzu.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhiwuduotai.top/Article/details/gticewlnmf.html

[D26] 数组转字符串
来源：http://dali.jyoumei.cn/Article/details/gtwixcxxcs.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yanxiufei.cn/Article/details/gtlhwjzjvb.html

PHP:  implode(", ", $arr);
来源：http://dali.yvedp.cn/Article/details/gtlnaddwao.html

JS:   arr.join(", ")
来源：http://dali.mhx1999.top/Article/details/gtbyqieeaz.html

TS:   arr.join(", ")
来源：http://dali.hfpthk.cn/Article/details/gtsukefnjp.html

Java: String.join(", ", list)
来源：http://dali.cashguo.top/Article/details/gtnctjvkow.html

Go:   strings.Join(strs, ", ")
来源：http://dali.sysykeji.top/Article/details/gtogwdsjrg.html

Ruby: arr.join(", ")
来源：http://dali.pengpengdd.cyou/Article/details/gtmvmowlqn.html

C#:   string.Join(", ", list)
来源：http://dali.ppjwa.cn/Article/details/gtabdrtbzw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtpeoeexnd.html

E. 字符串处理
来源：http://dali.redwolf501.top/Article/details/gtetzdaqgw.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtppueekpf.html

[E01] 拼接字符串
来源：http://dali.daxiang520.top/Article/details/gtrymtatbq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.aibaodan.cn/Article/details/gttkbzwjuk.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ivvv.top/Article/details/gtokzdmctj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtcqdjsgvm.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.haohaochexian.top/Article/details/gtatejlpor.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.smart0.xyz/Article/details/gtuahnizpg.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.fzhhl.top/Article/details/gthokeiffv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jianghu66.top/Article/details/gtqckmoonh.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxtaxqfct.html

[E02] 重复字符串
来源：http://dali.zhixingplan.top/Article/details/gtfoyowlng.html

Py:   "ab" * 3
来源：http://dali.chenjidiqi.icu/Article/details/gtuhhozyhf.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnseepugq.html

JS:   "ab".repeat(3)
来源：http://dali.xinyue.icu/Article/details/gtlsjqkvik.html

TS:   "ab".repeat(3)
来源：http://dali.zdqjudy.top/Article/details/gtovsojash.html

Java: "ab".repeat(3)
来源：http://dali.gaohongyu789.top/Article/details/gthyzhroui.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xuetiantiany.cn/Article/details/gtctwrufwe.html

Ruby: "ab" * 3
来源：http://dali.nanxuanxn.top/Article/details/gtotkjuckf.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.sysykeji.top/Article/details/gtlypfwzpy.html

[E03] 截取子串
来源：http://dali.xylfe.cn/Article/details/gtrhbtfaix.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jyoumei.cn/Article/details/gtsnpjdfqq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gtwyrykmic.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cashguo.top/Article/details/gtzyobiddr.html

TS:   s.slice(1, 4)
来源：http://dali.zhoulong.xyz/Article/details/gtnsuhtepl.html

Java: s.substring(1, 4)
来源：http://dali.yvedp.cn/Article/details/gtnzzhygbc.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yvedp.cn/Article/details/gtunpanrci.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhixingplan.top/Article/details/gtqmeyupjx.html

C#:   s.Substring(1, 3)
来源：http://dali.hnxiangtu.top/Article/details/gtdwmdaxvf.html

[E04] 查找子串位置
来源：http://dali.shanyushiyangtech.top/Article/details/gtmocdypdw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.guannengcc.top/Article/details/gtfoefftfm.html

PHP:  strpos($s, "x");
来源：http://dali.vqdsnc.cn/Article/details/gtlsuiwpiw.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hnxiangtu.top/Article/details/gtfnocozlg.html

TS:   s.indexOf("x")
来源：http://dali.zhiwuduotai.top/Article/details/gtcpwhqezv.html

Java: s.indexOf("x")
来源：http://dali.9152youxi.cn/Article/details/gtxyefjktv.html

Go:   strings.Index(s, "x")
来源：http://dali.mhx1999.top/Article/details/gtyzntrmhg.html

Ruby: s.index("x")
来源：http://dali.gogol.net.cn/Article/details/gtfmjuhxue.html

C#:   s.IndexOf("x")
来源：http://dali.guowangkeji.top/Article/details/gtjpzvrrxm.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.havefunace.top/Article/details/gtlqkegfji.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwyawkuou.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinghuilouyu.cn/Article/details/gteshhmybp.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yonumen.top/Article/details/gtsmlpwisw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sxryk.cn/Article/details/gtsendhquv.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.pengpengdd.cyou/Article/details/gtsfqqrurd.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yongpay.top/Article/details/gtcdqzdzbp.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.meibo888.top/Article/details/gtxkemrpbn.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.nanxuanxn.top/Article/details/gtdjytpkkc.html

[E06] 替换子串
来源：http://dali.vqdsnc.cn/Article/details/gtevxefmld.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.aibaodan.cn/Article/details/gtrekeigmw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.gaohongyu789.top/Article/details/gtlrcbwdva.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtagrbgwln.html

TS:   s.replaceAll("a", "b")
来源：http://dali.aizwys.cn/Article/details/gtwcgirgge.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gtavkxebhe.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.guowangkeji.top/Article/details/gtiudunuen.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ydzc1.top/Article/details/gtchswemjz.html

C#:   s.Replace("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gthyolbfta.html

[E07] 按分隔符拆分
来源：http://dali.ppjwa.cn/Article/details/gteeurqugo.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkepgrnqx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xylfe.cn/Article/details/gtejmdiytg.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hywenlv.cn/Article/details/gtuztpjrdv.html

TS:   s.split(",")
来源：http://dali.meibo888.top/Article/details/gtjxdndzkr.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.smart0.xyz/Article/details/gttqjgqnxr.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sysykeji.top/Article/details/gtylinqajb.html

Ruby: s.split(",");  s.split
来源：http://dali.pengpengdd.cyou/Article/details/gtzwdfwock.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.c1oappe.top/Article/details/gtselsgcdn.html

[E08] 数组按分隔符合并
来源：http://dali.hywenlv.cn/Article/details/gtkewemwez.html

Py:   ",".join(items)
来源：http://dali.0kj1m.cn/Article/details/gtqkhoujrc.html

PHP:  implode(",", $items);
来源：http://dali.jinqigufen.top/Article/details/gtsizbokuv.html

JS:   items.join(",")
来源：http://dali.mhx1999.top/Article/details/gtngygoowf.html

TS:   items.join(",")
来源：http://dali.chenzaomai.com/Article/details/gtlpnpszqn.html

Java: String.join(",", items)
来源：http://dali.meibo888.top/Article/details/gtopaxyncw.html

Go:   strings.Join(items, ",")
来源：http://dali.yonumen.top/Article/details/gtydlywkbb.html

Ruby: items.join(",")
来源：http://dali.nanxinkj.top/Article/details/gtfpbjbtfj.html

C#:   string.Join(",", items)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrbiskzan.html

[E09] 去除所有空白字符
来源：http://dali.jinghuilouyu.cn/Article/details/gtyssylxeo.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xuetiantiany.cn/Article/details/gtghidudcn.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtefonnkex.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xziqi.cn/Article/details/gtqjltdacn.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jqgfzy.top/Article/details/gtnygisqwg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ehwqpu.com/Article/details/gtjfrkgsup.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.birdmap.top/Article/details/gtyhpidprq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hysaishi.cn/Article/details/gtkdrmugfi.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hysaishi.cn/Article/details/gtlkeighds.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zdqjudy.top/Article/details/gtdmpvtcnh.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.aibaodan.cn/Article/details/gtoskhsqfj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.feifeiyinyue.top/Article/details/gtshuquxcw.html

JS:   "7".padStart(3, "0")
来源：http://dali.nanxuanxn.top/Article/details/gtupgrutge.html

TS:   "7".padStart(3, "0")
来源：http://dali.redwolf501.top/Article/details/gtlwkkxrit.html

Java: String.format("%03d", 7)
来源：http://dali.havefunace.top/Article/details/gtyguybrsd.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.gzhubu.top/Article/details/gtukdiwjcm.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shuidangran.top/Article/details/gtzrncyibr.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ybcxt.top/Article/details/gtzpxquvhv.html

[E11] 反转字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtykdvergs.html

Py:   s[::-1]
来源：http://dali.zhixingplan.top/Article/details/gtqpwkjpue.html

PHP:  strrev($s);
来源：http://dali.iojbl.cn/Article/details/gtdsvagxga.html

JS:   [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gtzeewnmyy.html

TS:   [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gtlbfolahl.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yongpay.top/Article/details/gtqqbfepyg.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shangyingyoupin.top/Article/details/gtrdsjegbx.html

Ruby: s.reverse
来源：http://dali.fengsongda.top/Article/details/gtcbkkmuun.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yj20258.top/Article/details/gtlzxkcjme.html

[E12] 统计某字符出现次数
来源：http://dali.gzhubu.top/Article/details/gtlvoiavaj.html

Py:   s.count("a")
来源：http://dali.zhoulong.xyz/Article/details/gtlibsnaml.html

PHP:  substr_count($s, "a");
来源：http://dali.dianchejie.cn/Article/details/gtbcyancsm.html

JS:   s.split("a").length - 1
来源：http://dali.cqqwz.cn/Article/details/gtuldapivt.html

TS:   s.split("a").length - 1
来源：http://dali.birdmap.top/Article/details/gtbefgftoa.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.gotoacloud.top/Article/details/gtxbqbjupi.html

Go:   strings.Count(s, "a")
来源：http://dali.jlsjyb.cn/Article/details/gtttshjsju.html

Ruby: s.count("a")
来源：http://dali.cashguo.top/Article/details/gtohvfhdmf.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cqqwz.cn/Article/details/gtvztmkcbv.html

[E13] 逐字符遍历
来源：http://dali.jiagoushi.top/Article/details/gtbrhgoeql.html

Py:   for ch in s: print(ch)
来源：http://dali.aibaodan.cn/Article/details/gteilepdfn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sysykeji.top/Article/details/gtyyshyvxw.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.bjfxy.top/Article/details/gtmppabvto.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sweek.top/Article/details/gtwxuvzvwj.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gtrwvcciqj.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ehwqpu.com/Article/details/gtblcjefbf.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cashguo.top/Article/details/gtthuzodmy.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cashguo.top/Article/details/gtkjgycrms.html

[E14] URL 编码与 Base64
来源：http://dali.yonumen.top/Article/details/gtzesljefl.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.wangdashe.top/Article/details/gtffjuzrdw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hfpthk.cn/Article/details/gthfstrbpq.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ehwqpu.com/Article/details/gtqgjwlhbg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sysykeji.top/Article/details/gtnjlmsdof.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yj20258888.top/Article/details/gtcwajbekz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yuanzhike.top/Article/details/gtepljtfjv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthlhaqdfp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhengqikj.top/Article/details/gtmcxdotlw.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvwilshbw.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtaneqcsjv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.wangdashe.top/Article/details/gtttjymzdm.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xinyue.icu/Article/details/gtcyehxuhm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gogol.net.cn/Article/details/gtqsgzweer.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ywan-chungtsiang.top/Article/details/gttilitkyx.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbubyfybp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xinyue.icu/Article/details/gtaasumapt.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yanxiufei.cn/Article/details/gtjptdgvjp.html

[E16] 数字千分位
来源：http://dali.daria6918.cn/Article/details/gtjoyzvbke.html

Py:   f"{1234567:,}"
来源：http://dali.dashuyun.cn/Article/details/gtrncnnfcm.html

PHP:  number_format(1234567);
来源：http://dali.316326.xyz/Article/details/gtlrdvnuww.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuanzx.com/Article/details/gttvqfdgpo.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.kuanghao11.cn/Article/details/gtmfofgogx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hammf.cn/Article/details/gtcbtfvjof.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.c1oappe.top/Article/details/gtjgoekarj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.wangshuangyany.cn/Article/details/gtxomxmvyp.html

C#:   1234567.ToString("N0")
来源：http://dali.aibaodan.cn/Article/details/gtbzyplpyi.html

[E17] 首字母大写
来源：http://dali.ppjwa.cn/Article/details/gtyyvlgktq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.smart0.xyz/Article/details/gttyvznclv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.aizwys.cn/Article/details/gttidqxkls.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jqgfzy.top/Article/details/gtkxygluip.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xziqi.cn/Article/details/gtyahhuzsk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gotoacloud.top/Article/details/gtspwxevpr.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xylfe.cn/Article/details/gtivwmpafv.html

Ruby: s.capitalize
来源：http://dali.xinyue.icu/Article/details/gtqqiviolu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.iojbl.cn/Article/details/gtfuvnuhtj.html

[E18] 模板占位符替换
来源：http://dali.gaohongyu789.top/Article/details/gtlppdbkmb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yj202588.top/Article/details/gthmhclcxv.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.aibaodan.cn/Article/details/gtqitrzwwr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yongpay.top/Article/details/gtzdmibwue.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangshuangyany.cn/Article/details/gtlobmsjtg.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xylfe.cn/Article/details/gtwwtrxafh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gtnhuqbuvm.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.snrcjt.cn/Article/details/gthyyhfxvr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.vqdsnc.cn/Article/details/gtshcgkxxq.html

[E19] 多行文本按行拆分
来源：http://dali.ybcxt.top/Article/details/gtczuzfmge.html

Py:   s.splitlines()
来源：http://dali.snrcjt.cn/Article/details/gtgcumojcd.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gtcpudwkdc.html

JS:   s.split(/\r?\n/)
来源：http://dali.dianchejie.cn/Article/details/gtyurxyerx.html

TS:   s.split(/\r?\n/)
来源：http://dali.havefunace.top/Article/details/gtjpmaspav.html

Java: s.lines().toList()
来源：http://dali.9152youxi.cn/Article/details/gtxbdfvsgi.html

Go:   strings.Split(s, "\n")
来源：http://dali.birdmap.top/Article/details/gtykwfrgbl.html

Ruby: s.lines
来源：http://dali.sweek.top/Article/details/gtpxqavzzz.html

C#:   s.Split('\n')
来源：http://dali.sufxvd.cn/Article/details/gttfhpfmmb.html

[E20] 判断字符串是否为空
来源：http://dali.ppjwa.cn/Article/details/gtwgueecob.html

Py:   if not s:
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwlvialna.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jqgufenzy.top/Article/details/gtfeqfcuyb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtmrgtftrn.html

TS:   if (s === "") {}
来源：http://dali.cheryme.top/Article/details/gtwbfjkgdo.html

Java: if (s.isEmpty()) {}
来源：http://dali.cucudq.cn/Article/details/gtrqukefnu.html

Go:   if s == "" {}
来源：http://dali.nwbrower.top/Article/details/gtdyrwyivn.html

Ruby: if s.empty?
来源：http://dali.gotoacloud.top/Article/details/gtrshcvovm.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jiagoushi.top/Article/details/gttnkbrmny.html

[E21] 超长截断加省略号
来源：http://dali.dianchejie.cn/Article/details/gtekmbqzzz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ybcxt.top/Article/details/gtcjeckuvf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yangfankeji.com/Article/details/gtaicvoyiy.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.bjfxy.top/Article/details/gtllwnpjgx.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daxiang520.top/Article/details/gthdrcoteo.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gtkakqnutv.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yj202588.top/Article/details/gtaypppywj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cashguo.top/Article/details/gtfcfvauxo.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gtwethifxk.html

[E22] 字节长度与字符长度
来源：http://dali.9152youxi.cn/Article/details/gtwigobzvo.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.feifeiyinyue.top/Article/details/gttglfqjtf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.svipenyu.cn/Article/details/gtrwpbmtqd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuaufxshv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnqzz.top/Article/details/gtqxatjyna.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhiwuduotai.top/Article/details/gtwffuwosn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gthbgnbjue.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinqigfzy.top/Article/details/gtqlqtbwul.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ivvv.top/Article/details/gtvjtmkect.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtzcmohodr.html

F. 文件与目录
来源：http://dali.daxiang520.top/Article/details/gtmucnkkzn.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtujczjnao.html

[F01] 读取整个文件
来源：http://dali.quarkkingdee.top/Article/details/gtjmfnirgz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtowqfvnoe.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtxcbjsrro.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzinpulkb.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.nanxuanxn.top/Article/details/gtguglbqxs.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gtvuxlzweg.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gaohongyu789.top/Article/details/gttrrhxtmv.html

Ruby: File.read("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtpevkgswk.html


<!-- 参考信息 -->