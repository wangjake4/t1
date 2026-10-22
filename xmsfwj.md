代发 wailian999

PHP:  max($arr);  min($arr);
来源：http://dali.gogol.net.cn/Article/details/gtrtetohhl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.9152youxi.cn/Article/details/gtiqssfvtn.html

TS:   Math.max(...arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtsstxmkqq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yanxiufei.cn/Article/details/gtyjnopafq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yuanzhike.top/Article/details/gtddhnjpgl.html

Ruby: arr.max;  arr.min
来源：http://dali.jqgfzy.top/Article/details/gtcsjjaklx.html

C#:   list.Max();  list.Min()
来源：http://dali.mhx1999.top/Article/details/gtydeykrva.html

[D18] 扁平化嵌套数组
来源：http://dali.shzxlz.cn/Article/details/gtjrggzewk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jinqigufen.top/Article/details/gtzmpguzbq.html

PHP:  array_merge(...$nested);
来源：http://dali.hywenlv.cn/Article/details/gthnzhjqhh.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhoulong.xyz/Article/details/gtutwxotfr.html

TS:   nested.flat();
来源：http://dali.xylfe.cn/Article/details/gtdgdfzcjm.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.daria6918.cn/Article/details/gtfmcakkqc.html

Go:   // 手写双层循环
来源：http://dali.sysykeji.top/Article/details/gtscenpefl.html

Ruby: nested.flatten
来源：http://dali.andypj.xyz/Article/details/gtfdsqdsrn.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.c1oappe.top/Article/details/gtryluiwjr.html

[D19] 按字段分组
来源：http://dali.xuetiantiany.cn/Article/details/gtfoiuwnxp.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.316326.xyz/Article/details/gtoujiwrje.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sysykeji.top/Article/details/gtehwanean.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yuanzhike.top/Article/details/gtrexkmoci.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yonumen.top/Article/details/gtnooudkbb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.chenjidiqi.icu/Article/details/gtlkvuotze.html

Go:   // 手写 map[string][]T
来源：http://dali.meibo888.top/Article/details/gtzlzulcmf.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.tianlin.xyz/Article/details/gtuhpebvck.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sxryk.cn/Article/details/gthofgkwtx.html

[D20] 统计每个元素出现次数
来源：http://dali.tanke756.top/Article/details/gtmlocdqat.html

Py:   Counter(arr)
来源：http://dali.nwbrower.top/Article/details/gtckbgfmiu.html

PHP:  array_count_values($arr);
来源：http://dali.9152youxi.cn/Article/details/gtdxfqtukh.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.kuanghao11.cn/Article/details/gtdoilczcl.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gogol.net.cn/Article/details/gtzbolhlgt.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zdqjudy.top/Article/details/gtqujdoldb.html

Go:   // 手写 map[T]int
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjtmumowd.html

Ruby: arr.tally
来源：http://dali.jlsjyb.cn/Article/details/gtmmkruyqx.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yonumen.top/Article/details/gtpjqvotio.html

[D21] 判断是否包含某元素
来源：http://dali.shzxlz.cn/Article/details/gthfrwmtvu.html

Py:   x in arr
来源：http://dali.zhengqikj.top/Article/details/gtctpzelry.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hywenlv.cn/Article/details/gtdrspskpg.html

JS:   arr.includes(x)
来源：http://dali.nanxinkj.top/Article/details/gtprsxjbse.html

TS:   arr.includes(x)
来源：http://dali.yanxiufei.cn/Article/details/gtuoptaezb.html

Java: list.contains(x)
来源：http://dali.aibaodan.cn/Article/details/gtvmqvgkkr.html

Go:   slices.Contains(arr, x)
来源：http://dali.yueranfly.top/Article/details/gtksoryzpk.html

Ruby: arr.include?(x)
来源：http://dali.guannengcc.top/Article/details/gtflihftju.html

C#:   list.Contains(x)
来源：http://dali.gogol.net.cn/Article/details/gtocivqvqx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.daria6918.cn/Article/details/gthbyifimk.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.daxiang520.top/Article/details/gtotzrkdep.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hysaishi.cn/Article/details/gtggakeiqe.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.wangdashe.top/Article/details/gtlrbxhfrb.html

TS:   [...arr];
来源：http://dali.haohaochexian.top/Article/details/gtlqpispdw.html

Java: new ArrayList<>(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtepsbxoll.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhongyouzk.top/Article/details/gtsftrgsja.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfyaofieq.html

C#:   new List<int>(list);
来源：http://dali.hongshengwenyu.top/Article/details/gtqtivrwcg.html

[D23] reduce 累积计算
来源：http://dali.fengsongda.top/Article/details/gtjdtcoksn.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgmqgoown.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yj20258.top/Article/details/gttvbzxnfj.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shzxlz.cn/Article/details/gtzbkxsbwd.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sufxvd.cn/Article/details/gtjvjkmevf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hysaishi.cn/Article/details/gtsdduyleo.html

Go:   // 手写循环
来源：http://dali.chenjidiqi.icu/Article/details/gtatyghbju.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhengqikj.top/Article/details/gtfbtpvjvm.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sweek.top/Article/details/gtparysypb.html

[D24] 字典 / Map 基本操作
来源：http://dali.hfpthk.cn/Article/details/gtirhjscgv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ydzc1.top/Article/details/gtqzaoleca.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zycfv.cn/Article/details/gtgaqprlqh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zycfv.cn/Article/details/gtzrsqfsny.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.pycfn.com/Article/details/gtgwdlykpj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jiagoushi.top/Article/details/gtoqbmfjky.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.gzhubu.top/Article/details/gthelubpbd.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hysaishi.cn/Article/details/gtvqaqqpms.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.chenzaomai.com/Article/details/gtovkjuwxz.html

[D25] Set 集合去重与交并差
来源：http://dali.smart0.xyz/Article/details/gtkkydfwll.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtugvuvocy.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hnqzz.top/Article/details/gthojbxugd.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.fzhhl.top/Article/details/gtgbgfoasi.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.pycfn.com/Article/details/gtrrdbmlos.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hnqzz.top/Article/details/gtncphlpse.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jqgfzy.top/Article/details/gtqsxahcyl.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.fengsongda.top/Article/details/gthxtnmapm.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtxwutpgdn.html

[D26] 数组转字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtggrfgqja.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yj20258888.top/Article/details/gtekcofdpa.html

PHP:  implode(", ", $arr);
来源：http://dali.cashguo.top/Article/details/gthjaxjans.html

JS:   arr.join(", ")
来源：http://dali.nwbrower.top/Article/details/gtrgrlbmqf.html

TS:   arr.join(", ")
来源：http://dali.sxryk.cn/Article/details/gtfuazxgsq.html

Java: String.join(", ", list)
来源：http://dali.pengpengdd.cyou/Article/details/gtlyecjebu.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jiagoushi.top/Article/details/gtdbrubreo.html

Ruby: arr.join(", ")
来源：http://dali.hywenlv.cn/Article/details/gtmmtlwvcb.html

C#:   string.Join(", ", list)
来源：http://dali.nwbrower.top/Article/details/gtztpmafkl.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtbfbblzjo.html

E. 字符串处理
来源：http://dali.kuanghao11.cn/Article/details/gtkhxtorwm.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtwvxpgvhj.html

[E01] 拼接字符串
来源：http://dali.ehwqpu.com/Article/details/gtpdduaafg.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhongyouzk.top/Article/details/gtqyoilfdd.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hfpthk.cn/Article/details/gtcbxwudje.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.0kj1m.cn/Article/details/gtxeyybvrp.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daxiang520.top/Article/details/gtamhbpkep.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zycfv.cn/Article/details/gtcnbxxjad.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yj20258888.top/Article/details/gtcwmxepgl.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhongyouzk.top/Article/details/gtweizraxx.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xziqi.cn/Article/details/gtebgayhwp.html

[E02] 重复字符串
来源：http://dali.cheryme.top/Article/details/gttsebgxxu.html

Py:   "ab" * 3
来源：http://dali.pycfn.com/Article/details/gtwzpqwvwm.html

PHP:  str_repeat("ab", 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtxrkxaawb.html

JS:   "ab".repeat(3)
来源：http://dali.tianlin.xyz/Article/details/gtpctdgtlt.html

TS:   "ab".repeat(3)
来源：http://dali.316326.xyz/Article/details/gtrbahtvkd.html

Java: "ab".repeat(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtlncrdces.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.mhx1999.top/Article/details/gtkmnascda.html

Ruby: "ab" * 3
来源：http://dali.zhaomingkeji.xyz/Article/details/gthasgfjwv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cqqwz.cn/Article/details/gtngdmiuzf.html

[E03] 截取子串
来源：http://dali.chenlongwang.top/Article/details/gtdpfiwmpi.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.meibo888.top/Article/details/gtznzlyezj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gtcxufvlsc.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.quarkkingdee.top/Article/details/gtzikxrxyb.html

TS:   s.slice(1, 4)
来源：http://dali.yvedp.cn/Article/details/gtdfxxzqvz.html

Java: s.substring(1, 4)
来源：http://dali.dashuyun.cn/Article/details/gtflbavsyu.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.chenlongwang.top/Article/details/gtqyqwmygg.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.chenjidiqi.icu/Article/details/gtqiezytei.html

C#:   s.Substring(1, 3)
来源：http://dali.chenjidiqi.icu/Article/details/gtphnsxjbk.html

[E04] 查找子串位置
来源：http://dali.iojbl.cn/Article/details/gtwgkglywt.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xylfe.cn/Article/details/gtikoxptvd.html

PHP:  strpos($s, "x");
来源：http://dali.xuetiantiany.cn/Article/details/gtkaiywakg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sweek.top/Article/details/gtikuzoaqb.html

TS:   s.indexOf("x")
来源：http://dali.snrcjt.cn/Article/details/gtrtxihips.html

Java: s.indexOf("x")
来源：http://dali.sufxvd.cn/Article/details/gtdctcyjeo.html

Go:   strings.Index(s, "x")
来源：http://dali.haohaochexian.top/Article/details/gtgfhseymh.html

Ruby: s.index("x")
来源：http://dali.zhoulong.xyz/Article/details/gtapmuhmdp.html

C#:   s.IndexOf("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvfvcvahi.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.dianchejie.cn/Article/details/gtsnistaeg.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhongyouzk.top/Article/details/gttqtfkskh.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.sufxvd.cn/Article/details/gtfditutks.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.daxiang520.top/Article/details/gtsspzpwef.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jlsjyb.cn/Article/details/gtjsljozri.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shuidangran.top/Article/details/gtefsbsbgo.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hammf.cn/Article/details/gteegnfejn.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.chenjidiqi.icu/Article/details/gtrmmiqjpq.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cdnleiting.top/Article/details/gtsbonujwi.html

[E06] 替换子串
来源：http://dali.nwbrower.top/Article/details/gtrqczebap.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtpmrbqeed.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.gogol.net.cn/Article/details/gtrqhvfyhs.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sxryk.cn/Article/details/gtrlilgtac.html

TS:   s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gthbmiebxk.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gtrmmzffaa.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xziqi.cn/Article/details/gtcxilyesl.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.mhx1999.top/Article/details/gthcioagsd.html

C#:   s.Replace("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gthjsdjoxg.html

[E07] 按分隔符拆分
来源：http://dali.zycfv.cn/Article/details/gtualfhbue.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.sysykeji.top/Article/details/gtyubrpxfu.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cucudq.cn/Article/details/gttrngdkds.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.andypj.xyz/Article/details/gtubgprrck.html

TS:   s.split(",")
来源：http://dali.yangfankeji.com/Article/details/gttnksgsou.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hammf.cn/Article/details/gtjfifnind.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.quarkkingdee.top/Article/details/gtgtldmseq.html

Ruby: s.split(",");  s.split
来源：http://dali.ivvv.top/Article/details/gthubczkyf.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.tanke756.top/Article/details/gtkhmmbgbj.html

[E08] 数组按分隔符合并
来源：http://dali.0kj1m.cn/Article/details/gtgufnfkam.html

Py:   ",".join(items)
来源：http://dali.sysykeji.top/Article/details/gtalbdmttm.html

PHP:  implode(",", $items);
来源：http://dali.haohaochexian.top/Article/details/gtpzwgxsxv.html

JS:   items.join(",")
来源：http://dali.hnxiangtu.top/Article/details/gtyqgwnwzv.html

TS:   items.join(",")
来源：http://dali.zhengqikj.top/Article/details/gtfwfmwhvz.html

Java: String.join(",", items)
来源：http://dali.ydzc1.top/Article/details/gttmkljfom.html

Go:   strings.Join(items, ",")
来源：http://dali.jqgufenzy.top/Article/details/gtezawtbhu.html

Ruby: items.join(",")
来源：http://dali.daria6918.cn/Article/details/gtdiqfyttd.html

C#:   string.Join(",", items)
来源：http://dali.shzxlz.cn/Article/details/gtvcpdtato.html

[E09] 去除所有空白字符
来源：http://dali.tanke756.top/Article/details/gtoehzopyy.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.9152youxi.cn/Article/details/gtlqeymlts.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.fzhhl.top/Article/details/gtsdgrezki.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhixingplan.top/Article/details/gtuiitzgma.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.wangshuangyany.cn/Article/details/gtgvsekauf.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.nwbrower.top/Article/details/gtjmdwelnm.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sxryk.cn/Article/details/gtexzceqkl.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cucudq.cn/Article/details/gtkphxidqn.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.tian-w.cn/Article/details/gtqagigbqx.html

[E10] 左侧补零 / 定长填充
来源：http://dali.birdmap.top/Article/details/gtxmvcrcaa.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.c1oappe.top/Article/details/gtenulklyf.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.sysykeji.top/Article/details/gttdlozmsu.html

JS:   "7".padStart(3, "0")
来源：http://dali.haohaochexian.top/Article/details/gtfayfluso.html

TS:   "7".padStart(3, "0")
来源：http://dali.316326.xyz/Article/details/gtqvkhrfoq.html

Java: String.format("%03d", 7)
来源：http://dali.hfpthk.cn/Article/details/gtwnyrliwg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yangfankeji.com/Article/details/gtmcqxzwyq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhongyouzk.top/Article/details/gtiharhkop.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.meibo888.top/Article/details/gtfyuqgfmm.html

[E11] 反转字符串
来源：http://dali.nanxinkj.top/Article/details/gtigjgfbhj.html

Py:   s[::-1]
来源：http://dali.haohaochexian.top/Article/details/gtgsconvvd.html

PHP:  strrev($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtawogijhq.html

JS:   [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gtwxsulnen.html

TS:   [...s].reverse().join("")
来源：http://dali.aizwys.cn/Article/details/gtjjyhmvql.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.havefunace.top/Article/details/gtkxzdpukb.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.dashuyun.cn/Article/details/gtaoyltklf.html

Ruby: s.reverse
来源：http://dali.jiagoushi.top/Article/details/gtanomkhrk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.gogol.net.cn/Article/details/gtdxzkwfko.html

[E12] 统计某字符出现次数
来源：http://dali.iojbl.cn/Article/details/gtyjluidzz.html

Py:   s.count("a")
来源：http://dali.sweek.top/Article/details/gtdmqzknqq.html

PHP:  substr_count($s, "a");
来源：http://dali.gotoacloud.top/Article/details/gtpwwneswi.html

JS:   s.split("a").length - 1
来源：http://dali.shzxlz.cn/Article/details/gttlpekbmz.html

TS:   s.split("a").length - 1
来源：http://dali.sysykeji.top/Article/details/gtmqzsripq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzmyggmlo.html

Go:   strings.Count(s, "a")
来源：http://dali.meibo888.top/Article/details/gtfknrdmpd.html

Ruby: s.count("a")
来源：http://dali.xylfe.cn/Article/details/gtskripfms.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zdqjudy.top/Article/details/gtoltrteog.html

[E13] 逐字符遍历
来源：http://dali.ppjwa.cn/Article/details/gtinnpxsvl.html

Py:   for ch in s: print(ch)
来源：http://dali.shangyingyoupin.top/Article/details/gtwvqhsfuv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.birdmap.top/Article/details/gtfrhensfd.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cqqwz.cn/Article/details/gtixhrkeby.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daria6918.cn/Article/details/gtsznuljcd.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.bjfxy.top/Article/details/gtecgcqsrp.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhijiandao.cn/Article/details/gtwxipjiwv.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shzxlz.cn/Article/details/gtzhhqdgpy.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gtedurfbpc.html

[E14] URL 编码与 Base64
来源：http://dali.yj20258.top/Article/details/gtueavxjqx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yj20258888.top/Article/details/gtuakcicfx.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yangfankeji.com/Article/details/gtszwnmaml.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlxjbjfph.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hnxiangtu.top/Article/details/gtwlbbdbnv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ivvv.top/Article/details/gtikncjpqa.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xuetiantiany.cn/Article/details/gtehmiremd.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zycfv.cn/Article/details/gtocdtznyc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jianghu66.top/Article/details/gtrrxddxea.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gtpbqgruvb.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.pycfn.com/Article/details/gtqfxhaziu.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtmtpaykqa.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtcecyzoer.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.iojbl.cn/Article/details/gtmqjjutrc.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.havefunace.top/Article/details/gtdmpcjquq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.tianlin.xyz/Article/details/gthmtxumhp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.fengsongda.top/Article/details/gtuzcsxvej.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sweek.top/Article/details/gtdzwqbhio.html

[E16] 数字千分位
来源：http://dali.birdmap.top/Article/details/gtyglfbxzf.html

Py:   f"{1234567:,}"
来源：http://dali.c1oappe.top/Article/details/gtafvzaatv.html

PHP:  number_format(1234567);
来源：http://dali.tanke756.top/Article/details/gttfdgtlyf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.fzhhl.top/Article/details/gththqmpxw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ydzc1.top/Article/details/gtwrdaahqf.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.guowangkeji.top/Article/details/gtajxsabhu.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.gzhubu.top/Article/details/gtjtartzre.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.fengsongda.top/Article/details/gtmovtuhnt.html

C#:   1234567.ToString("N0")
来源：http://dali.sxryk.cn/Article/details/gtbrucxcbl.html

[E17] 首字母大写
来源：http://dali.cheryme.top/Article/details/gtjpqtcsgh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.fzhhl.top/Article/details/gtiabtotpo.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hfpthk.cn/Article/details/gtouvqrfft.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zycfv.cn/Article/details/gtozgkmbnu.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigufen.top/Article/details/gtyfzvjqyw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtcegopxcv.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cheryme.top/Article/details/gtrrthxqhe.html

Ruby: s.capitalize
来源：http://dali.yanxiufei.cn/Article/details/gtsxjqwvgo.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.andypj.xyz/Article/details/gtxjsemlwi.html

[E18] 模板占位符替换
来源：http://dali.hongshengwenyu.top/Article/details/gtumxifpcn.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cashguo.top/Article/details/gtvmflfqoj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.fzhhl.top/Article/details/gtuypfyuxw.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhongyouzk.top/Article/details/gtvlponvih.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yanxiufei.cn/Article/details/gtzxvzhyos.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gtxfelragq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gtgrrxulql.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zycfv.cn/Article/details/gtzmxqpmlt.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yj202588.top/Article/details/gtaezueorr.html

[E19] 多行文本按行拆分
来源：http://dali.daxiang520.top/Article/details/gtlfowhwuk.html

Py:   s.splitlines()
来源：http://dali.xziqi.cn/Article/details/gtgrensguo.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.chenlongwang.top/Article/details/gtrvcqkwza.html

JS:   s.split(/\r?\n/)
来源：http://dali.9152youxi.cn/Article/details/gtwezdlhru.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhoulong.xyz/Article/details/gtqmmfrlfl.html

Java: s.lines().toList()
来源：http://dali.9152youxi.cn/Article/details/gtuijxccof.html

Go:   strings.Split(s, "\n")
来源：http://dali.sufxvd.cn/Article/details/gteghvooin.html

Ruby: s.lines
来源：http://dali.xuanzx.com/Article/details/gtcgrlldkf.html

C#:   s.Split('\n')
来源：http://dali.fzhhl.top/Article/details/gtzghecuzp.html

[E20] 判断字符串是否为空
来源：http://dali.mhx1999.top/Article/details/gtfsndntuz.html

Py:   if not s:
来源：http://dali.zhongyouzk.top/Article/details/gtflrbwowq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shangyingyoupin.top/Article/details/gtiekwrdvk.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcdxecgar.html

TS:   if (s === "") {}
来源：http://dali.hnqzz.top/Article/details/gtcekegpqk.html

Java: if (s.isEmpty()) {}
来源：http://dali.andypj.xyz/Article/details/gtpepqlhmf.html

Go:   if s == "" {}
来源：http://dali.zycfv.cn/Article/details/gtvrwgmymc.html

Ruby: if s.empty?
来源：http://dali.nanxinkj.top/Article/details/gtzzudwrkh.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yj20258.top/Article/details/gtfnmzynho.html

[E21] 超长截断加省略号
来源：http://dali.hfpthk.cn/Article/details/gtlqmvffrx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.andypj.xyz/Article/details/gtvkgkxorh.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinqigfzy.top/Article/details/gtufruooak.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gtwmcruqkn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtyhfzynxk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtsfxfvuao.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gogol.net.cn/Article/details/gtwaornqij.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjwujplmd.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cucudq.cn/Article/details/gtiaplyhrl.html

[E22] 字节长度与字符长度
来源：http://dali.fzhhl.top/Article/details/gtcbujyvyp.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.tianlin.xyz/Article/details/gtlvdhoyer.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gtjxahbeao.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangshuangyany.cn/Article/details/gtdayodcbx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.c1oappe.top/Article/details/gtytjdersv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hfpthk.cn/Article/details/gteoncvvap.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hnqzz.top/Article/details/gtrqgtexlx.html

Ruby: s.bytesize;  s.length
来源：http://dali.sweek.top/Article/details/gtyamsiqmp.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.chenlongwang.top/Article/details/gtdeantkvu.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtjqimhffi.html

F. 文件与目录
来源：http://dali.snrcjt.cn/Article/details/gtcqdsqhkf.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtktwfxarj.html

[F01] 读取整个文件
来源：http://dali.jqgfzy.top/Article/details/gtuuxeuojl.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhengqikj.top/Article/details/gtyxfvunae.html

PHP:  file_get_contents("a.txt");
来源：http://dali.fzhhl.top/Article/details/gthdwnzypi.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.fengsongda.top/Article/details/gtxqmkrloi.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.dashuyun.cn/Article/details/gtzotpftpw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gtngrodwll.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xziqi.cn/Article/details/gtzoxytviz.html

Ruby: File.read("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtdxafrxxo.html


<!-- 参考信息 -->