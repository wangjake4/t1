代发 wailian999

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.aibaodan.cn/Article/details/gtpendclqn.html

Go:   // 手写双层循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrhhuwidr.html

Ruby: nested.flatten
来源：http://dali.cucudq.cn/Article/details/gttrupmzzu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cucudq.cn/Article/details/gtacznbxru.html

[D19] 按字段分组
来源：http://dali.cheryme.top/Article/details/gtcrzjjzto.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.svipenyu.cn/Article/details/gtqcwyyjbi.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xuanzx.com/Article/details/gtldezhopm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.havefunace.top/Article/details/gtzuquukpd.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.aibaodan.cn/Article/details/gtufswwmaq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinqigfzy.top/Article/details/gtmwjtxgio.html

Go:   // 手写 map[string][]T
来源：http://dali.zhiwuduotai.top/Article/details/gtldlxbaez.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.feifeiyinyue.top/Article/details/gtkhoqejyn.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jyoumei.cn/Article/details/gtelszebmy.html

[D20] 统计每个元素出现次数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdlomgopi.html

Py:   Counter(arr)
来源：http://dali.9152youxi.cn/Article/details/gtwdpszigk.html

PHP:  array_count_values($arr);
来源：http://dali.tianlin.xyz/Article/details/gtavagfnyf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.wangdashe.top/Article/details/gteogkzydy.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgfzy.top/Article/details/gtyqtgjiow.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjweahdhu.html

Go:   // 手写 map[T]int
来源：http://dali.xuetiantiany.cn/Article/details/gtfiavmcdv.html

Ruby: arr.tally
来源：http://dali.jinqigufen.top/Article/details/gtkwliohmu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhiwuduotai.top/Article/details/gtnbacbkqm.html

[D21] 判断是否包含某元素
来源：http://dali.yj20258.top/Article/details/gtftbfjezp.html

Py:   x in arr
来源：http://dali.mhx1999.top/Article/details/gtapicrddn.html

PHP:  in_array($x, $arr, true);
来源：http://dali.bjfxy.top/Article/details/gtdidopmmp.html

JS:   arr.includes(x)
来源：http://dali.aizwys.cn/Article/details/gtuqzpljzx.html

TS:   arr.includes(x)
来源：http://dali.svipenyu.cn/Article/details/gtsteqxdqf.html

Java: list.contains(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtddsoqvjy.html

Go:   slices.Contains(arr, x)
来源：http://dali.316326.xyz/Article/details/gtbvhdqlie.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gtuiffwrjp.html

C#:   list.Contains(x)
来源：http://dali.sweek.top/Article/details/gtphpmnnuu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.fengsongda.top/Article/details/gtkalfpsaq.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jinqigufen.top/Article/details/gtcfxexoms.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.fengsongda.top/Article/details/gticztuznc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ybcxt.top/Article/details/gtoghyhlpw.html

TS:   [...arr];
来源：http://dali.xuanzx.com/Article/details/gttqkagsfw.html

Java: new ArrayList<>(list);
来源：http://dali.9152youxi.cn/Article/details/gteqauckvm.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.aizwys.cn/Article/details/gtgqczxyhy.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yongpay.top/Article/details/gtcwetvdih.html

C#:   new List<int>(list);
来源：http://dali.yongpay.top/Article/details/gtydeffhrm.html

[D23] reduce 累积计算
来源：http://dali.9152youxi.cn/Article/details/gtqnwnofqy.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yonumen.top/Article/details/gtenzpxiut.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yj202588.top/Article/details/gtfhxbnwlb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zycfv.cn/Article/details/gtjbqnjzuh.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtpyudvnti.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yanxiufei.cn/Article/details/gtttqmyyga.html

Go:   // 手写循环
来源：http://dali.fzhhl.top/Article/details/gtokqezqoa.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gotoacloud.top/Article/details/gtznjlddgq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sufxvd.cn/Article/details/gtbjoafurn.html

[D24] 字典 / Map 基本操作
来源：http://dali.sysykeji.top/Article/details/gtfbioutnv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.chenjidiqi.icu/Article/details/gtroqopajp.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhongyouzk.top/Article/details/gtjlvtekno.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.fengsongda.top/Article/details/gtmdgnmmhw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sufxvd.cn/Article/details/gtflbuplho.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jianghu66.top/Article/details/gtxicvrmzg.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yonumen.top/Article/details/gtetqebunr.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yangfankeji.com/Article/details/gtvynncqru.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jqgufenzy.top/Article/details/gtfpiwenru.html

[D25] Set 集合去重与交并差
来源：http://dali.nanxinkj.top/Article/details/gtpdvmjugu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xuetiantiany.cn/Article/details/gtoetonmfo.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.pycfn.com/Article/details/gtmpltcnqb.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.gogol.net.cn/Article/details/gtcosihjgc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.316326.xyz/Article/details/gtyccccoab.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hysaishi.cn/Article/details/gtqhitmjib.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tianlin.xyz/Article/details/gtdoqbtayv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.c1oappe.top/Article/details/gtqmjxdehe.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.smart0.xyz/Article/details/gteodnsnub.html

[D26] 数组转字符串
来源：http://dali.yj202588.top/Article/details/gtyaqstjyn.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sysykeji.top/Article/details/gtnfczvfco.html

PHP:  implode(", ", $arr);
来源：http://dali.jiagoushi.top/Article/details/gtnfzsjudz.html

JS:   arr.join(", ")
来源：http://dali.chenzaomai.com/Article/details/gtcuvsbreg.html

TS:   arr.join(", ")
来源：http://dali.tian-w.cn/Article/details/gtumjduxtl.html

Java: String.join(", ", list)
来源：http://dali.zhoulong.xyz/Article/details/gtbbqpezaq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yangfankeji.com/Article/details/gtqzllgbqg.html

Ruby: arr.join(", ")
来源：http://dali.yj20258.top/Article/details/gtisorlekz.html

C#:   string.Join(", ", list)
来源：http://dali.jianghu66.top/Article/details/gtzztspzjr.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtcxruqsqe.html

E. 字符串处理
来源：http://dali.gogol.net.cn/Article/details/gtumheftng.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtijyvmzjm.html

[E01] 拼接字符串
来源：http://dali.zhixingplan.top/Article/details/gtjekjtrvo.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cdnleiting.top/Article/details/gtztvvulri.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.cdnleiting.top/Article/details/gtbsedmaqg.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shzxlz.cn/Article/details/gtvvocxbrz.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cdnleiting.top/Article/details/gtbznlcjei.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.svipenyu.cn/Article/details/gtqkbiulsm.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.wangshuangyany.cn/Article/details/gtzcbtvzkq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yj20258888.top/Article/details/gtkjkvlxya.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ivvv.top/Article/details/gtmfgaoeuw.html

[E02] 重复字符串
来源：http://dali.yanxiufei.cn/Article/details/gtxqvbxxtk.html

Py:   "ab" * 3
来源：http://dali.yvedp.cn/Article/details/gtfozalkix.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhongyouzk.top/Article/details/gtytxfkryz.html

JS:   "ab".repeat(3)
来源：http://dali.yj20258.top/Article/details/gtdjembxpj.html

TS:   "ab".repeat(3)
来源：http://dali.hammf.cn/Article/details/gtzqkkirps.html

Java: "ab".repeat(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzqonsrmd.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hywenlv.cn/Article/details/gtsyocihil.html

Ruby: "ab" * 3
来源：http://dali.sweek.top/Article/details/gtlewifund.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xylfe.cn/Article/details/gtaypcuwtb.html

[E03] 截取子串
来源：http://dali.jinqigfzy.top/Article/details/gtwbbwvham.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.tianlin.xyz/Article/details/gtalartftk.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gtyfboabay.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xinyue.icu/Article/details/gtblkdxijz.html

TS:   s.slice(1, 4)
来源：http://dali.fengsongda.top/Article/details/gtaxfchjtg.html

Java: s.substring(1, 4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gticrcbpcx.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.quarkkingdee.top/Article/details/gthhklmwvw.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.sxryk.cn/Article/details/gtgwrrfpxa.html

C#:   s.Substring(1, 3)
来源：http://dali.gaohongyu789.top/Article/details/gtebzuvomx.html

[E04] 查找子串位置
来源：http://dali.yj20258.top/Article/details/gtzxxzsmzr.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhongyouzk.top/Article/details/gtdnemaygt.html

PHP:  strpos($s, "x");
来源：http://dali.bjfxy.top/Article/details/gtmyewftnj.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.guowangkeji.top/Article/details/gtwddtuypu.html

TS:   s.indexOf("x")
来源：http://dali.dashuyun.cn/Article/details/gtvmqvaday.html

Java: s.indexOf("x")
来源：http://dali.yuanzhike.top/Article/details/gtaxfkxsbe.html

Go:   strings.Index(s, "x")
来源：http://dali.shuidangran.top/Article/details/gthvgttkav.html

Ruby: s.index("x")
来源：http://dali.shangyingyoupin.top/Article/details/gtdveukgux.html

C#:   s.IndexOf("x")
来源：http://dali.nanxinkj.top/Article/details/gtybuluksj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cheryme.top/Article/details/gtgpwvesht.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.chenlongwang.top/Article/details/gtutmpdsvw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yanxiufei.cn/Article/details/gtjxpqjoof.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tanke756.top/Article/details/gtlwcnmfxg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.chenjidiqi.icu/Article/details/gtwjnnbhkx.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nwbrower.top/Article/details/gtgzdomloe.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cheryme.top/Article/details/gtyluvdwka.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zycfv.cn/Article/details/gtgpznogeq.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfuehiopd.html

[E06] 替换子串
来源：http://dali.daxiang520.top/Article/details/gtnbudvnrz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jianghu66.top/Article/details/gtbhiomeej.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.wangdashe.top/Article/details/gtkuvuilrm.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtkjufwqsq.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xinyue.icu/Article/details/gtovojttzl.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.316326.xyz/Article/details/gtydvenfea.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zdqjudy.top/Article/details/gteobjzitz.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gttvwlnlhm.html

C#:   s.Replace("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtnpvuwnxp.html

[E07] 按分隔符拆分
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnlmqksrh.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.wangshuangyany.cn/Article/details/gttikeqbov.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zycfv.cn/Article/details/gtecbmlsyl.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpernflwh.html

TS:   s.split(",")
来源：http://dali.yueranfly.top/Article/details/gtwjjkllfm.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhoulong.xyz/Article/details/gtjqjtzljd.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.fzhhl.top/Article/details/gtcpmbmwgn.html

Ruby: s.split(",");  s.split
来源：http://dali.zhengqikj.top/Article/details/gttfcfzzab.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.tian-w.cn/Article/details/gtinokqgtv.html

[E08] 数组按分隔符合并
来源：http://dali.zhijiandao.cn/Article/details/gtaqimvbfi.html

Py:   ",".join(items)
来源：http://dali.gogol.net.cn/Article/details/gtzjrdskwu.html

PHP:  implode(",", $items);
来源：http://dali.sxryk.cn/Article/details/gtiklxqzcj.html

JS:   items.join(",")
来源：http://dali.meibo888.top/Article/details/gtjbwglbmo.html

TS:   items.join(",")
来源：http://dali.dashuyun.cn/Article/details/gteeyjfrnt.html

Java: String.join(",", items)
来源：http://dali.gotoacloud.top/Article/details/gtlfrvixrg.html

Go:   strings.Join(items, ",")
来源：http://dali.jinqigfzy.top/Article/details/gtypschuym.html

Ruby: items.join(",")
来源：http://dali.hnqzz.top/Article/details/gtoncsngus.html

C#:   string.Join(",", items)
来源：http://dali.yuanzhike.top/Article/details/gtkugnojgj.html

[E09] 去除所有空白字符
来源：http://dali.wangdashe.top/Article/details/gtpkvbnvwv.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sweek.top/Article/details/gtjzdvbxse.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.daxiang520.top/Article/details/gtmpelsepc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.aizwys.cn/Article/details/gtyqpadbxg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xuanzx.com/Article/details/gtpanqguta.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.gogol.net.cn/Article/details/gtpccetcnz.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.vqdsnc.cn/Article/details/gtsaahzeee.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.vqdsnc.cn/Article/details/gtepmtowke.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shangyingyoupin.top/Article/details/gttclvmcxn.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhoulong.xyz/Article/details/gttgbveolf.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yj20258888.top/Article/details/gtaofmtual.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.snrcjt.cn/Article/details/gttnqrogmy.html

JS:   "7".padStart(3, "0")
来源：http://dali.gotoacloud.top/Article/details/gtcvmcmerz.html

TS:   "7".padStart(3, "0")
来源：http://dali.shuidangran.top/Article/details/gtexgoqbpa.html

Java: String.format("%03d", 7)
来源：http://dali.hfpthk.cn/Article/details/gtawjyjwzn.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sweek.top/Article/details/gtyrzufchn.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shuidangran.top/Article/details/gtcdykjjsg.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.tanke756.top/Article/details/gtvzyufdhi.html

[E11] 反转字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtngsqrolw.html

Py:   s[::-1]
来源：http://dali.guannengcc.top/Article/details/gtruelhypk.html

PHP:  strrev($s);
来源：http://dali.dianchejie.cn/Article/details/gthtoprfhr.html

JS:   [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gtpzegqhee.html

TS:   [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gtouhsvjax.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhixingplan.top/Article/details/gtovftazwt.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jiagoushi.top/Article/details/gteqcfkcce.html

Ruby: s.reverse
来源：http://dali.hfpthk.cn/Article/details/gtsdhykusg.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.iojbl.cn/Article/details/gtmcbtentg.html

[E12] 统计某字符出现次数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdmzqtbao.html

Py:   s.count("a")
来源：http://dali.hongshengwenyu.top/Article/details/gticxopvug.html

PHP:  substr_count($s, "a");
来源：http://dali.aibaodan.cn/Article/details/gtvwpldfel.html

JS:   s.split("a").length - 1
来源：http://dali.birdmap.top/Article/details/gtyrbmswcy.html

TS:   s.split("a").length - 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtwhfhjson.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zycfv.cn/Article/details/gtybdgakeo.html

Go:   strings.Count(s, "a")
来源：http://dali.yongpay.top/Article/details/gtmevgpkog.html

Ruby: s.count("a")
来源：http://dali.chenzaomai.com/Article/details/gticcktinl.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sysykeji.top/Article/details/gtgslsbafl.html

[E13] 逐字符遍历
来源：http://dali.wangdashe.top/Article/details/gtvegdxdnh.html

Py:   for ch in s: print(ch)
来源：http://dali.yj20258.top/Article/details/gtrxayovfx.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.0kj1m.cn/Article/details/gtfofxwbzk.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtagbroqsd.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shuidangran.top/Article/details/gtkzgjbfxb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yangfankeji.com/Article/details/gtepwcjxmu.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhengqikj.top/Article/details/gtqoigmjtf.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinqigufen.top/Article/details/gtjaaxjhpc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.guowangkeji.top/Article/details/gtzjnwmyqc.html

[E14] URL 编码与 Base64
来源：http://dali.ybcxt.top/Article/details/gtgrhgiceq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.chenzaomai.com/Article/details/gtphrceklm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hnxiangtu.top/Article/details/gtnsddaise.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yj202588.top/Article/details/gtbewmenrr.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cqqwz.cn/Article/details/gtlaefknvs.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shuidangran.top/Article/details/gtittccsqn.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yongpay.top/Article/details/gtdktwkmlu.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.gzhubu.top/Article/details/gttrparksl.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hongshengwenyu.top/Article/details/gtspcysqup.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhoulong.xyz/Article/details/gtyvelcncv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gotoacloud.top/Article/details/gtiyzazotb.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.guannengcc.top/Article/details/gttxohnznh.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtnnkfvtda.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hywenlv.cn/Article/details/gtsywnrkak.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.chenjidiqi.icu/Article/details/gtnogutaey.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jlsjyb.cn/Article/details/gttazfajzp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xinyue.icu/Article/details/gtkvcyhpyy.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cqqwz.cn/Article/details/gtnznebmwj.html

[E16] 数字千分位
来源：http://dali.c1oappe.top/Article/details/gtgrrmekov.html

Py:   f"{1234567:,}"
来源：http://dali.shuidangran.top/Article/details/gtbrhdfcxc.html

PHP:  number_format(1234567);
来源：http://dali.jinghuilouyu.cn/Article/details/gtfcqmwojf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.daxiang520.top/Article/details/gtawfuzwsm.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gzhubu.top/Article/details/gtaynwzmpp.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcjbldqak.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.daxiang520.top/Article/details/gtidibyuwq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yangfankeji.com/Article/details/gtxtbqrpqg.html

C#:   1234567.ToString("N0")
来源：http://dali.jqgfzy.top/Article/details/gthqlqmojd.html

[E17] 首字母大写
来源：http://dali.zhoulong.xyz/Article/details/gtkjkhzrcc.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hongshengwenyu.top/Article/details/gtfiqvjjoi.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jinqigufen.top/Article/details/gtfwxegaln.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yvedp.cn/Article/details/gtiywokvfp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shuidangran.top/Article/details/gtklxqrfey.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.birdmap.top/Article/details/gtbnlqeaus.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yj20258888.top/Article/details/gtdpyyktvx.html

Ruby: s.capitalize
来源：http://dali.jinghuilouyu.cn/Article/details/gtyhjvyyig.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hnqzz.top/Article/details/gttdgmonnp.html

[E18] 模板占位符替换
来源：http://dali.hnqzz.top/Article/details/gteznnhblo.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yonumen.top/Article/details/gtuybxepzy.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ydzc1.top/Article/details/gtaqpgzlbq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yonumen.top/Article/details/gtnebdbxvw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gtnrafeqtq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.pengpengdd.cyou/Article/details/gtnwlamqut.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gtxqloyzxn.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gtcbinnwto.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jyoumei.cn/Article/details/gtyiloglyc.html

[E19] 多行文本按行拆分
来源：http://dali.nanxuanxn.top/Article/details/gtmlyfahzp.html

Py:   s.splitlines()
来源：http://dali.hnqzz.top/Article/details/gtwutbklfh.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ehwqpu.com/Article/details/gttvlzrehf.html

JS:   s.split(/\r?\n/)
来源：http://dali.ivvv.top/Article/details/gtiqnahedv.html

TS:   s.split(/\r?\n/)
来源：http://dali.gzhubu.top/Article/details/gtfvyxhejy.html

Java: s.lines().toList()
来源：http://dali.hnxiangtu.top/Article/details/gtagvibbmr.html

Go:   strings.Split(s, "\n")
来源：http://dali.sufxvd.cn/Article/details/gtplpivnmn.html

Ruby: s.lines
来源：http://dali.shanyushiyangtech.top/Article/details/gtzihvgclr.html

C#:   s.Split('\n')
来源：http://dali.daxiang520.top/Article/details/gtaokdwjqw.html

[E20] 判断字符串是否为空
来源：http://dali.hnxiangtu.top/Article/details/gtgxzfrexj.html

Py:   if not s:
来源：http://dali.jianghu66.top/Article/details/gtulxgqfri.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.tian-w.cn/Article/details/gtnlgqvrnb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.c1oappe.top/Article/details/gtqbnlzzgg.html

TS:   if (s === "") {}
来源：http://dali.tanke756.top/Article/details/gtoekazbul.html

Java: if (s.isEmpty()) {}
来源：http://dali.birdmap.top/Article/details/gtiayplasx.html

Go:   if s == "" {}
来源：http://dali.dianchejie.cn/Article/details/gtvfxecakz.html

Ruby: if s.empty?
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdjxaeggv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.nwbrower.top/Article/details/gtwzvuhiqb.html

[E21] 超长截断加省略号
来源：http://dali.yj202588.top/Article/details/gtdwgnkssl.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hywenlv.cn/Article/details/gtacktdtuk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.birdmap.top/Article/details/gtdgnxqkkz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sweek.top/Article/details/gtnxdbvwmb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gtawqpyecw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gtwnmtmjpi.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yanxiufei.cn/Article/details/gtdsxzcmmp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xuanzx.com/Article/details/gtjmnyvlot.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.sxryk.cn/Article/details/gtvutlswvw.html

[E22] 字节长度与字符长度
来源：http://dali.fengsongda.top/Article/details/gteounpbki.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hnqzz.top/Article/details/gtacrrpqpe.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.vqdsnc.cn/Article/details/gtykygklqt.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xinyue.icu/Article/details/gtoisvojbr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.316326.xyz/Article/details/gtavzfzoec.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.dianchejie.cn/Article/details/gtvpdimznj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gaohongyu789.top/Article/details/gtmnribuox.html

Ruby: s.bytesize;  s.length
来源：http://dali.tianlin.xyz/Article/details/gtkzdgaksn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.feifeiyinyue.top/Article/details/gttjvuakco.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtpktmsiyy.html

F. 文件与目录
来源：http://dali.hywenlv.cn/Article/details/gtwcpwnprz.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtjfhrytvg.html

[F01] 读取整个文件
来源：http://dali.cashguo.top/Article/details/gtrhwkxqix.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cheryme.top/Article/details/gtiucmyins.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtlwkskide.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.smart0.xyz/Article/details/gtpufathxd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zycfv.cn/Article/details/gtreqegwnd.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gtzvtwgzgi.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.andypj.xyz/Article/details/gtybazydii.html

Ruby: File.read("a.txt")
来源：http://dali.meibo888.top/Article/details/gtzgzuvugd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtlcupwvtd.html

[F02] 逐行读取文件
来源：http://dali.chenzaomai.com/Article/details/gtyraditqx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.mhx1999.top/Article/details/gttaamhyfw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxbskhseb.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhixingplan.top/Article/details/gtlwytotjk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hfpthk.cn/Article/details/gtcaoesuxu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yj202588.top/Article/details/gtpqrynefn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.daria6918.cn/Article/details/gtivohywib.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhengqikj.top/Article/details/gtwdzrvmtm.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.mhx1999.top/Article/details/gtdukkivdn.html

[F03] 写入文件（覆盖）
来源：http://dali.ivvv.top/Article/details/gtuigmwvpv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.feifeiyinyue.top/Article/details/gtirbczchu.html


<!-- 参考信息 -->