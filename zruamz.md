代发 wailian999

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.tianlin.xyz/Article/details/gtqpumdgvd.html

Ruby: arr.max;  arr.min
来源：http://dali.ehwqpu.com/Article/details/gtqtfqnxgi.html

C#:   list.Max();  list.Min()
来源：http://dali.dianchejie.cn/Article/details/gtosreqanb.html

[D18] 扁平化嵌套数组
来源：http://dali.kuanghao11.cn/Article/details/gtzrsiswjj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ehwqpu.com/Article/details/gtndhoydwd.html

PHP:  array_merge(...$nested);
来源：http://dali.yuanzhike.top/Article/details/gtsqqfymmo.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yuxming.cn/Article/details/gtxcecalur.html

TS:   nested.flat();
来源：http://dali.jinghuilouyu.cn/Article/details/gtnsceoint.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jlsjyb.cn/Article/details/gtjxidgvbi.html

Go:   // 手写双层循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxramyxxn.html

Ruby: nested.flatten
来源：http://dali.yuanzhike.top/Article/details/gtapfbfryu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yangfankeji.com/Article/details/gtkolmpjma.html

[D19] 按字段分组
来源：http://dali.meibo888.top/Article/details/gtpkdafckx.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.nanxinkj.top/Article/details/gtmcvcuwyt.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sxryk.cn/Article/details/gtfwsmmfjr.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.tianlin.xyz/Article/details/gtqutncwgo.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.nanxuanxn.top/Article/details/gtxdokkprx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hammf.cn/Article/details/gtmblegqpm.html

Go:   // 手写 map[string][]T
来源：http://dali.zhengqikj.top/Article/details/gtjsaiphmz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hammf.cn/Article/details/gtjtddigdb.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yuanzhike.top/Article/details/gtitekfjwx.html

[D20] 统计每个元素出现次数
来源：http://dali.daria6918.cn/Article/details/gtexpmbjvg.html

Py:   Counter(arr)
来源：http://dali.snrcjt.cn/Article/details/gtibuxbvkh.html

PHP:  array_count_values($arr);
来源：http://dali.haohaochexian.top/Article/details/gtixamjuhx.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.snrcjt.cn/Article/details/gtcbhxuxmj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.bjfxy.top/Article/details/gtxguscfqd.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.nanxinkj.top/Article/details/gtwigvyhxh.html

Go:   // 手写 map[T]int
来源：http://dali.cdnleiting.top/Article/details/gtavhcynqs.html

Ruby: arr.tally
来源：http://dali.wangdashe.top/Article/details/gtzgrrvapt.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cucudq.cn/Article/details/gtvpjrmgei.html

[D21] 判断是否包含某元素
来源：http://dali.feifeiyinyue.top/Article/details/gtqvprrtpl.html

Py:   x in arr
来源：http://dali.nanxuanxn.top/Article/details/gtgmtdafot.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhengqikj.top/Article/details/gtfwdhngxm.html

JS:   arr.includes(x)
来源：http://dali.haohaochexian.top/Article/details/gtxikxlzrs.html

TS:   arr.includes(x)
来源：http://dali.shzxlz.cn/Article/details/gtaciieegv.html

Java: list.contains(x)
来源：http://dali.dashuyun.cn/Article/details/gtaclvnons.html

Go:   slices.Contains(arr, x)
来源：http://dali.tian-w.cn/Article/details/gtwmdeymkw.html

Ruby: arr.include?(x)
来源：http://dali.ivvv.top/Article/details/gtlbtylddy.html

C#:   list.Contains(x)
来源：http://dali.iojbl.cn/Article/details/gtmraqkkcw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.sysykeji.top/Article/details/gtpjerwstw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtiocjnzpk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqevdvznx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.daria6918.cn/Article/details/gttthtzhxc.html

TS:   [...arr];
来源：http://dali.yuanzhike.top/Article/details/gtpbvfcnps.html

Java: new ArrayList<>(list);
来源：http://dali.zycfv.cn/Article/details/gtvphofaat.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.9152youxi.cn/Article/details/gtqbwlwkez.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ehwqpu.com/Article/details/gtuosaqoeh.html

C#:   new List<int>(list);
来源：http://dali.wangshuangyany.cn/Article/details/gtxajrwvpq.html

[D23] reduce 累积计算
来源：http://dali.xuanzx.com/Article/details/gtbksxdyad.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xziqi.cn/Article/details/gtghesgbax.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.tianlin.xyz/Article/details/gtyykimjrf.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cheryme.top/Article/details/gtpageduyr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtrlzsqzyf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.andypj.xyz/Article/details/gtxbwdrsyj.html

Go:   // 手写循环
来源：http://dali.yvedp.cn/Article/details/gtmbrgfbum.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yanxiufei.cn/Article/details/gtprwptewe.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.wangdashe.top/Article/details/gtcofctcyg.html

[D24] 字典 / Map 基本操作
来源：http://dali.smart0.xyz/Article/details/gtmqqzxszo.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.tian-w.cn/Article/details/gtsxujlcst.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.smart0.xyz/Article/details/gtaaojzdbo.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.0kj1m.cn/Article/details/gtpyzsbaqz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hnxiangtu.top/Article/details/gtuiqivcpg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.gzhubu.top/Article/details/gtvphdwwms.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jqgufenzy.top/Article/details/gtuguhbrie.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.guowangkeji.top/Article/details/gtxwywgvcu.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gaohongyu789.top/Article/details/gtadaguley.html

[D25] Set 集合去重与交并差
来源：http://dali.haohaochexian.top/Article/details/gtustjshgq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.guowangkeji.top/Article/details/gtczhlpgzj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xziqi.cn/Article/details/gtupnizinu.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.sufxvd.cn/Article/details/gtsqmwrero.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaybprlse.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sysykeji.top/Article/details/gtvafhhgka.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.smart0.xyz/Article/details/gtuwuopkjh.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwunnttzt.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hysaishi.cn/Article/details/gtfufteroa.html

[D26] 数组转字符串
来源：http://dali.mhx1999.top/Article/details/gtqtvnskbw.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cqqwz.cn/Article/details/gtiwzaijnp.html

PHP:  implode(", ", $arr);
来源：http://dali.jlsjyb.cn/Article/details/gtgzqrgqkm.html

JS:   arr.join(", ")
来源：http://dali.gzhubu.top/Article/details/gtheoxfdlh.html

TS:   arr.join(", ")
来源：http://dali.cucudq.cn/Article/details/gtlmhwdika.html

Java: String.join(", ", list)
来源：http://dali.iojbl.cn/Article/details/gtapkvhjxr.html

Go:   strings.Join(strs, ", ")
来源：http://dali.sysykeji.top/Article/details/gtozoxyxmo.html

Ruby: arr.join(", ")
来源：http://dali.xylfe.cn/Article/details/gtxuncybkm.html

C#:   string.Join(", ", list)
来源：http://dali.smart0.xyz/Article/details/gtugmxufvw.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtbexblbkl.html

E. 字符串处理
来源：http://dali.cqqwz.cn/Article/details/gtbzkhztpf.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtfuikangv.html

[E01] 拼接字符串
来源：http://dali.jinqigufen.top/Article/details/gtmbilkdkl.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.fengsongda.top/Article/details/gtmvtomuyo.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.gaohongyu789.top/Article/details/gtwvdateap.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sweek.top/Article/details/gtchoonknm.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.andypj.xyz/Article/details/gtljnhkacp.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.316326.xyz/Article/details/gttxbshetw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.nanxinkj.top/Article/details/gtdvbxwzbf.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ppjwa.cn/Article/details/gtdpxtxmte.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gtalvibnrh.html

[E02] 重复字符串
来源：http://dali.316326.xyz/Article/details/gtlmztiiec.html

Py:   "ab" * 3
来源：http://dali.shzxlz.cn/Article/details/gtvbfgphjr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.daxiang520.top/Article/details/gtchyajudw.html

JS:   "ab".repeat(3)
来源：http://dali.birdmap.top/Article/details/gtdhgsbibt.html

TS:   "ab".repeat(3)
来源：http://dali.zycfv.cn/Article/details/gteueekhts.html

Java: "ab".repeat(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtmawtkqyr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtscnjleia.html

Ruby: "ab" * 3
来源：http://dali.xuetiantiany.cn/Article/details/gtgqfhcrwv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jinghuilouyu.cn/Article/details/gttiejpihq.html

[E03] 截取子串
来源：http://dali.jqgufenzy.top/Article/details/gtlvutfugl.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shuidangran.top/Article/details/gtkemrpavo.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ehwqpu.com/Article/details/gtvseijnws.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.chenzaomai.com/Article/details/gtivrtclwk.html

TS:   s.slice(1, 4)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlulurmam.html

Java: s.substring(1, 4)
来源：http://dali.jinqigufen.top/Article/details/gtyzbizvvs.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.daxiang520.top/Article/details/gtgqjaawyr.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.wangshuangyany.cn/Article/details/gtpedwbywv.html

C#:   s.Substring(1, 3)
来源：http://dali.jiagoushi.top/Article/details/gtlsknjavv.html

[E04] 查找子串位置
来源：http://dali.yonumen.top/Article/details/gtywitmvoa.html

Py:   s.find("x");  s.index("x")
来源：http://dali.bjfxy.top/Article/details/gtnxfvehoq.html

PHP:  strpos($s, "x");
来源：http://dali.c1oappe.top/Article/details/gtebzensgs.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cqqwz.cn/Article/details/gtwgzbmtnu.html

TS:   s.indexOf("x")
来源：http://dali.fzhhl.top/Article/details/gtbewtvfux.html

Java: s.indexOf("x")
来源：http://dali.vqdsnc.cn/Article/details/gtjqmugbsp.html

Go:   strings.Index(s, "x")
来源：http://dali.ydzc1.top/Article/details/gtujsifkyj.html

Ruby: s.index("x")
来源：http://dali.gotoacloud.top/Article/details/gtniqzcqwm.html

C#:   s.IndexOf("x")
来源：http://dali.yanxiufei.cn/Article/details/gtnenqcosg.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.andypj.xyz/Article/details/gtvncqszyb.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.pycfn.com/Article/details/gtldjmqhil.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhongyouzk.top/Article/details/gtmwjvhxpl.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhongyouzk.top/Article/details/gtlcqxlfcm.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xziqi.cn/Article/details/gtqbyqmeya.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.haohaochexian.top/Article/details/gtpodeuwta.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yvedp.cn/Article/details/gtkawxecai.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.tian-w.cn/Article/details/gtzikyytdr.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ppjwa.cn/Article/details/gtllluisgn.html

[E06] 替换子串
来源：http://dali.tianlin.xyz/Article/details/gtrszsnmlt.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.aizwys.cn/Article/details/gtvlvouamt.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.gogol.net.cn/Article/details/gtazksnqxd.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gtfijopsza.html

TS:   s.replaceAll("a", "b")
来源：http://dali.meibo888.top/Article/details/gtkdauwcso.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ivvv.top/Article/details/gtfuknjpsi.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.nwbrower.top/Article/details/gtihfaijlx.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sweek.top/Article/details/gthnoarfbu.html

C#:   s.Replace("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gtzjumsdts.html

[E07] 按分隔符拆分
来源：http://dali.shanyushiyangtech.top/Article/details/gtrtkogrnz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.shangyingyoupin.top/Article/details/gtkvswkiyi.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zycfv.cn/Article/details/gtbwovszbs.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj202588.top/Article/details/gtyliyzlvd.html

TS:   s.split(",")
来源：http://dali.9152youxi.cn/Article/details/gtunikgpcs.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.9152youxi.cn/Article/details/gtsehrtdoo.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yangfankeji.com/Article/details/gtuiviynvv.html

Ruby: s.split(",");  s.split
来源：http://dali.snrcjt.cn/Article/details/gtbigxxtkg.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.meibo888.top/Article/details/gtrxcbzteg.html

[E08] 数组按分隔符合并
来源：http://dali.andypj.xyz/Article/details/gtnizbsvga.html

Py:   ",".join(items)
来源：http://dali.iojbl.cn/Article/details/gtjlqhxaim.html

PHP:  implode(",", $items);
来源：http://dali.bjfxy.top/Article/details/gtayseaexd.html

JS:   items.join(",")
来源：http://dali.sysykeji.top/Article/details/gtcpjegjim.html

TS:   items.join(",")
来源：http://dali.yangfankeji.com/Article/details/gtnzpjzhrq.html

Java: String.join(",", items)
来源：http://dali.guannengcc.top/Article/details/gtkhwekduo.html

Go:   strings.Join(items, ",")
来源：http://dali.sweek.top/Article/details/gttoduvyju.html

Ruby: items.join(",")
来源：http://dali.ydzc1.top/Article/details/gtqjsecung.html

C#:   string.Join(",", items)
来源：http://dali.redwolf501.top/Article/details/gthhupedpt.html

[E09] 去除所有空白字符
来源：http://dali.ehwqpu.com/Article/details/gtpxlfwzhf.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sweek.top/Article/details/gtbzmzjwuh.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtcokhnzbl.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jqgufenzy.top/Article/details/gtwkoxdnnz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkgbdpnyf.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj20258888.top/Article/details/gtklecfmho.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sxryk.cn/Article/details/gtdzwusaiw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.smart0.xyz/Article/details/gtnjvgbxgf.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cashguo.top/Article/details/gthzwuzqug.html

[E10] 左侧补零 / 定长填充
来源：http://dali.fzhhl.top/Article/details/gterwaevox.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ydzc1.top/Article/details/gtzqjigtpw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.snrcjt.cn/Article/details/gttjnyybqd.html

JS:   "7".padStart(3, "0")
来源：http://dali.shanyushiyangtech.top/Article/details/gttnfrrppe.html

TS:   "7".padStart(3, "0")
来源：http://dali.meibo888.top/Article/details/gtpfuhmxtm.html

Java: String.format("%03d", 7)
来源：http://dali.zhongyouzk.top/Article/details/gtwyhabsdk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jiagoushi.top/Article/details/gtigattske.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.dianchejie.cn/Article/details/gtqpgrjexm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shuidangran.top/Article/details/gthdthtfub.html

[E11] 反转字符串
来源：http://dali.yuanzhike.top/Article/details/gtbyxhrfbw.html

Py:   s[::-1]
来源：http://dali.shangyingyoupin.top/Article/details/gtrdicnhfm.html

PHP:  strrev($s);
来源：http://dali.shzxlz.cn/Article/details/gteictcqex.html

JS:   [...s].reverse().join("")
来源：http://dali.zdqjudy.top/Article/details/gtkrtmnlvf.html

TS:   [...s].reverse().join("")
来源：http://dali.ppjwa.cn/Article/details/gthlwvquhn.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xuetiantiany.cn/Article/details/gtzlphztpu.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhoulong.xyz/Article/details/gtqtpzysej.html

Ruby: s.reverse
来源：http://dali.c1oappe.top/Article/details/gtifszsxig.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.guannengcc.top/Article/details/gtdopddmzt.html

[E12] 统计某字符出现次数
来源：http://dali.chenlongwang.top/Article/details/gtionmjbva.html

Py:   s.count("a")
来源：http://dali.chenzaomai.com/Article/details/gtukidbqks.html

PHP:  substr_count($s, "a");
来源：http://dali.xuanzx.com/Article/details/gtkheznmzo.html

JS:   s.split("a").length - 1
来源：http://dali.yanxiufei.cn/Article/details/gtxlntkqpr.html

TS:   s.split("a").length - 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtqcclfvam.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jinqigfzy.top/Article/details/gtgwkjlwnx.html

Go:   strings.Count(s, "a")
来源：http://dali.chenzaomai.com/Article/details/gttntxfmre.html

Ruby: s.count("a")
来源：http://dali.tanke756.top/Article/details/gtvolpghmn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.nwbrower.top/Article/details/gthshqebgy.html

[E13] 逐字符遍历
来源：http://dali.dianchejie.cn/Article/details/gtldncojws.html

Py:   for ch in s: print(ch)
来源：http://dali.316326.xyz/Article/details/gtzjytkgvr.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yj20258.top/Article/details/gtdoedcmqv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.havefunace.top/Article/details/gtmyeirxsk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zycfv.cn/Article/details/gtmwqmwggh.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jinqigfzy.top/Article/details/gtakpnxqgb.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinqigfzy.top/Article/details/gtybcsrvay.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.pengpengdd.cyou/Article/details/gtowmtjvwe.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sufxvd.cn/Article/details/gtyjpyyqqv.html

[E14] URL 编码与 Base64
来源：http://dali.cucudq.cn/Article/details/gtyhyyzmpo.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sweek.top/Article/details/gtxkowqgdy.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.havefunace.top/Article/details/gthipgkigk.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.havefunace.top/Article/details/gtrfnievuz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.316326.xyz/Article/details/gtquegvbtc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jiagoushi.top/Article/details/gtaeqkvefj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hysaishi.cn/Article/details/gtiqomkyaw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jianghu66.top/Article/details/gtjqnffwjp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yueranfly.top/Article/details/gtlqrzyfsx.html

[E15] HTML 转义 / 反转义
来源：http://dali.nanxinkj.top/Article/details/gtcvfkozkl.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yuanzhike.top/Article/details/gttfjygguf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.pengpengdd.cyou/Article/details/gttpzfhqxl.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.fzhhl.top/Article/details/gtrwkfqmml.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sweek.top/Article/details/gtebwfziic.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cdnleiting.top/Article/details/gtrmhiydvj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shzxlz.cn/Article/details/gtmuhiifvw.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yj20258.top/Article/details/gtyddjwbyy.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yueranfly.top/Article/details/gtlymwolfb.html

[E16] 数字千分位
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbdvvmsms.html

Py:   f"{1234567:,}"
来源：http://dali.0kj1m.cn/Article/details/gtjvxxsjww.html

PHP:  number_format(1234567);
来源：http://dali.jlsjyb.cn/Article/details/gtpslqahmc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgfzy.top/Article/details/gtxwinduux.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ppjwa.cn/Article/details/gtbdxvtiht.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.aibaodan.cn/Article/details/gtddwjueyw.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yuxming.cn/Article/details/gtmpbwktrc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jqgfzy.top/Article/details/gtupzhielc.html

C#:   1234567.ToString("N0")
来源：http://dali.mhx1999.top/Article/details/gtceenrqxv.html

[E17] 首字母大写
来源：http://dali.feifeiyinyue.top/Article/details/gtsgoedhuu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.feifeiyinyue.top/Article/details/gtdumsiqun.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gzhubu.top/Article/details/gtindgltfw.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jlsjyb.cn/Article/details/gtkwegpvoz.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xziqi.cn/Article/details/gtmrkflvns.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.guowangkeji.top/Article/details/gtvhymyplm.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.aizwys.cn/Article/details/gtmjxxzvqo.html

Ruby: s.capitalize
来源：http://dali.yueranfly.top/Article/details/gtykmtdzwt.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yuanzhike.top/Article/details/gtfrqwfytf.html

[E18] 模板占位符替换
来源：http://dali.chenlongwang.top/Article/details/gtqvbjppah.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.chenzaomai.com/Article/details/gtigtbuzxh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.haohaochexian.top/Article/details/gtytruqjkg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gtqxhcamev.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cucudq.cn/Article/details/gtdjuicqmp.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.nwbrower.top/Article/details/gtudckacoz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gzhubu.top/Article/details/gtkccybdpd.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.meibo888.top/Article/details/gtfwdxrkpg.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.birdmap.top/Article/details/gtxqgnjgmt.html

[E19] 多行文本按行拆分
来源：http://dali.fzhhl.top/Article/details/gtnsxbqpzd.html

Py:   s.splitlines()
来源：http://dali.nanxinkj.top/Article/details/gtqguktopi.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtcswomhss.html

JS:   s.split(/\r?\n/)
来源：http://dali.xziqi.cn/Article/details/gtrkxqzrvy.html

TS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkidvrmsq.html

Java: s.lines().toList()
来源：http://dali.shangyingyoupin.top/Article/details/gtgxmskqvs.html

Go:   strings.Split(s, "\n")
来源：http://dali.fzhhl.top/Article/details/gtxupcavcj.html

Ruby: s.lines
来源：http://dali.0kj1m.cn/Article/details/gtibonuzdn.html

C#:   s.Split('\n')
来源：http://dali.xuanzx.com/Article/details/gtnqzzupow.html

[E20] 判断字符串是否为空
来源：http://dali.c1oappe.top/Article/details/gtqokodtcg.html

Py:   if not s:
来源：http://dali.jqgfzy.top/Article/details/gtozmmkgxi.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhixingplan.top/Article/details/gtxowyxoij.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.guowangkeji.top/Article/details/gtizzkcsmh.html

TS:   if (s === "") {}
来源：http://dali.zhongyouzk.top/Article/details/gtkthksdyu.html

Java: if (s.isEmpty()) {}
来源：http://dali.hnqzz.top/Article/details/gtxgubfaiy.html

Go:   if s == "" {}
来源：http://dali.dianchejie.cn/Article/details/gtlvswfaik.html

Ruby: if s.empty?
来源：http://dali.nanxinkj.top/Article/details/gtxbvkzmkd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.dianchejie.cn/Article/details/gttdgbejki.html

[E21] 超长截断加省略号
来源：http://dali.zhoulong.xyz/Article/details/gtfznbhbwn.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sufxvd.cn/Article/details/gtoymqojfs.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gtptyavpok.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gtkcwhbgiw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tian-w.cn/Article/details/gtbergealn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gtbjiwbpoi.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.fengsongda.top/Article/details/gtraobaaez.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gtdltmueel.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtprmmnkoc.html

[E22] 字节长度与字符长度
来源：http://dali.dianchejie.cn/Article/details/gtngjkverk.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shuidangran.top/Article/details/gtjbxemnqp.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hnqzz.top/Article/details/gtwcmywxzj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tianlin.xyz/Article/details/gtkjvsddzu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhoulong.xyz/Article/details/gtnkeyiebr.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shanyushiyangtech.top/Article/details/gtnxecjnqm.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.svipenyu.cn/Article/details/gtjauuaszr.html

Ruby: s.bytesize;  s.length
来源：http://dali.cqqwz.cn/Article/details/gtzacwarzl.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xylfe.cn/Article/details/gtmkhccqom.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtxdmxxjzb.html

F. 文件与目录
来源：http://dali.gogol.net.cn/Article/details/gtlwxrumhm.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtwbsilqla.html

[F01] 读取整个文件
来源：http://dali.0kj1m.cn/Article/details/gtgttnmwex.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gzhubu.top/Article/details/gtbdueudjg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtpcqmzyhf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.guannengcc.top/Article/details/gtthepbdgw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yuanzhike.top/Article/details/gtmyvabiqu.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.tianlin.xyz/Article/details/gtbpxgdoev.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.meibo888.top/Article/details/gtgtuwrktq.html

Ruby: File.read("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gthzetkfqh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtzbvxyyye.html

[F02] 逐行读取文件
来源：http://dali.yongpay.top/Article/details/gtmvslvrek.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.daria6918.cn/Article/details/gtpiqufojb.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfueznryp.html


<!-- 参考信息 -->