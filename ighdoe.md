代发 wailian999

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.fzhhl.top/Article/details/gt2xjqxbewz.html

Ruby: arr.max;  arr.min
来源：http://dali.shzxlz.cn/Article/details/gt2ddfooczz.html

C#:   list.Max();  list.Min()
来源：http://dali.hnxiangtu.top/Article/details/gt2junowlkw.html

[D18] 扁平化嵌套数组
来源：http://dali.sysykeji.top/Article/details/gt2owjbrxkk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.snrcjt.cn/Article/details/gt2liqvsjga.html

PHP:  array_merge(...$nested);
来源：http://dali.jinqigufen.top/Article/details/gt2hncmigqz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yj20258.top/Article/details/gt2wytujqox.html

TS:   nested.flat();
来源：http://dali.tanke756.top/Article/details/gt2piftylfa.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2flvtonpk.html

Go:   // 手写双层循环
来源：http://dali.hongshengwenyu.top/Article/details/gt2jncuaqif.html

Ruby: nested.flatten
来源：http://dali.gzhubu.top/Article/details/gt2uhjdtede.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ivvv.top/Article/details/gt2thvtqsku.html

[D19] 按字段分组
来源：http://dali.jiagoushi.top/Article/details/gt2fwndtnpi.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2uhblwxud.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.pengpengdd.cyou/Article/details/gt2gjjfknww.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jqgfzy.top/Article/details/gt2fchvojtr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jianghu66.top/Article/details/gt2fwumbqnt.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.nanxinkj.top/Article/details/gt2zbyyhjua.html

Go:   // 手写 map[string][]T
来源：http://dali.sufxvd.cn/Article/details/gt2gaztdbgn.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.pengpengdd.cyou/Article/details/gt2pqwblxje.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cucudq.cn/Article/details/gt2ivhpdonc.html

[D20] 统计每个元素出现次数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hydtowkg.html

Py:   Counter(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jegmyqsh.html

PHP:  array_count_values($arr);
来源：http://dali.pycfn.com/Article/details/gt2luithrnm.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yonumen.top/Article/details/gt2lssgfvss.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258888.top/Article/details/gt2wstqvlly.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shangyingyoupin.top/Article/details/gt2ubvrupbp.html

Go:   // 手写 map[T]int
来源：http://dali.jinqigfzy.top/Article/details/gt2vbdqwmqv.html

Ruby: arr.tally
来源：http://dali.nanxuanxn.top/Article/details/gt2khxchanr.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sufxvd.cn/Article/details/gt2oejdbrqw.html

[D21] 判断是否包含某元素
来源：http://dali.yvedp.cn/Article/details/gt2kywxmsae.html

Py:   x in arr
来源：http://dali.gogol.net.cn/Article/details/gt2kuuimqpi.html

PHP:  in_array($x, $arr, true);
来源：http://dali.mhx1999.top/Article/details/gt2yhsgdwtt.html

JS:   arr.includes(x)
来源：http://dali.yanxiufei.cn/Article/details/gt2xucikdzl.html

TS:   arr.includes(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2busgvphz.html

Java: list.contains(x)
来源：http://dali.chenzaomai.com/Article/details/gt2nufyhtjc.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gt2lgdswrpy.html

Ruby: arr.include?(x)
来源：http://dali.ybcxt.top/Article/details/gt2lcsdhmfr.html

C#:   list.Contains(x)
来源：http://dali.daria6918.cn/Article/details/gt2legpdkks.html

[D22] 复制数组（避免共享引用）
来源：http://dali.chenjidiqi.icu/Article/details/gt2jrdziwuf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shuidangran.top/Article/details/gt2pixlcyve.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.fzhhl.top/Article/details/gt2pjnlpuch.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2rqawytwz.html

TS:   [...arr];
来源：http://dali.zhengqikj.top/Article/details/gt2iharupqd.html

Java: new ArrayList<>(list);
来源：http://dali.zhongyouzk.top/Article/details/gt2lojwihgg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.iojbl.cn/Article/details/gt2qrioameb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yj202588.top/Article/details/gt2mnirovpy.html

C#:   new List<int>(list);
来源：http://dali.aibaodan.cn/Article/details/gt2lhkulfqw.html

[D23] reduce 累积计算
来源：http://dali.nanxinkj.top/Article/details/gt2ytwuaxss.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.smart0.xyz/Article/details/gt2zgdwlwlb.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.kuanghao11.cn/Article/details/gt2iqybdwyg.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uzbgkuou.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yangfankeji.com/Article/details/gt2fxbdnzsr.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.feifeiyinyue.top/Article/details/gt2inbbckoy.html

Go:   // 手写循环
来源：http://dali.aibaodan.cn/Article/details/gt2eschcmuk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.redwolf501.top/Article/details/gt2kmjqthsk.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hnxiangtu.top/Article/details/gt2pvpfacdi.html

[D24] 字典 / Map 基本操作
来源：http://dali.redwolf501.top/Article/details/gt2plvnizxl.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.sufxvd.cn/Article/details/gt2bnymypik.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.dashuyun.cn/Article/details/gt2fzvihldh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zdqjudy.top/Article/details/gt2bfpykqks.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.daria6918.cn/Article/details/gt2isdnuoqb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xuanzx.com/Article/details/gt2kmlakatw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.sxryk.cn/Article/details/gt2fyfgbkme.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gaohongyu789.top/Article/details/gt2ryyvpmir.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.guannengcc.top/Article/details/gt2swmngsyg.html

[D25] Set 集合去重与交并差
来源：http://dali.gaohongyu789.top/Article/details/gt2crqaagod.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.gaohongyu789.top/Article/details/gt2lfilwhpk.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.mhx1999.top/Article/details/gt2hrittxcl.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.sysykeji.top/Article/details/gt2gstftysx.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.daxiang520.top/Article/details/gt2bpmibacj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gogol.net.cn/Article/details/gt2uaolmbmz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.snrcjt.cn/Article/details/gt2momrxabk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.guowangkeji.top/Article/details/gt2jupfbpse.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jvcixvhx.html

[D26] 数组转字符串
来源：http://dali.9152youxi.cn/Article/details/gt2otsmqhis.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hysaishi.cn/Article/details/gt2insfkzot.html

PHP:  implode(", ", $arr);
来源：http://dali.9152youxi.cn/Article/details/gt2jtomtour.html

JS:   arr.join(", ")
来源：http://dali.pycfn.com/Article/details/gt2nblrevlx.html

TS:   arr.join(", ")
来源：http://dali.aibaodan.cn/Article/details/gt2grfgireq.html

Java: String.join(", ", list)
来源：http://dali.xylfe.cn/Article/details/gt2vhjyrexf.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vvpgvulf.html

Ruby: arr.join(", ")
来源：http://dali.birdmap.top/Article/details/gt2ufsfajyu.html

C#:   string.Join(", ", list)
来源：http://dali.nanxuanxn.top/Article/details/gt2suejrsej.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ojadyonh.html

E. 字符串处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jlqazevm.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2sexvysdb.html

[E01] 拼接字符串
来源：http://dali.xylfe.cn/Article/details/gt2wxhikitr.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gotoacloud.top/Article/details/gt2rxntlftv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yj20258.top/Article/details/gt2irtsioqq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.pengpengdd.cyou/Article/details/gt2negsdkkc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cucudq.cn/Article/details/gt2ajlwfbxi.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.quarkkingdee.top/Article/details/gt2zgbloocb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.dianchejie.cn/Article/details/gt2extrfazy.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhoulong.xyz/Article/details/gt2akazxsru.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sweek.top/Article/details/gt2tiyttdrt.html

[E02] 重复字符串
来源：http://dali.nanxinkj.top/Article/details/gt2fbcyzrkw.html

Py:   "ab" * 3
来源：http://dali.zhengqikj.top/Article/details/gt2auwsnhli.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yueranfly.top/Article/details/gt2dlocqjst.html

JS:   "ab".repeat(3)
来源：http://dali.shzxlz.cn/Article/details/gt2qspygvmy.html

TS:   "ab".repeat(3)
来源：http://dali.ydzc1.top/Article/details/gt2rkxhzzwa.html

Java: "ab".repeat(3)
来源：http://dali.jinqigufen.top/Article/details/gt2djghwmij.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.chenlongwang.top/Article/details/gt2pkuqnwyg.html

Ruby: "ab" * 3
来源：http://dali.aizwys.cn/Article/details/gt2mbyqorga.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yj202588.top/Article/details/gt2ekueqnpq.html

[E03] 截取子串
来源：http://dali.zhiwuduotai.top/Article/details/gt2oskcenxq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ppjwa.cn/Article/details/gt2vegbskfn.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.mhx1999.top/Article/details/gt2ebbfzsij.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yuxming.cn/Article/details/gt2ddokkron.html

TS:   s.slice(1, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ofothbpd.html

Java: s.substring(1, 4)
来源：http://dali.hongshengwenyu.top/Article/details/gt2nlatqvll.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xinyue.icu/Article/details/gt2anatmpyr.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.guannengcc.top/Article/details/gt2jtqnghhc.html

C#:   s.Substring(1, 3)
来源：http://dali.gotoacloud.top/Article/details/gt2tfrknzni.html

[E04] 查找子串位置
来源：http://dali.jyoumei.cn/Article/details/gt2bwtabcpu.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2inzzegvt.html

PHP:  strpos($s, "x");
来源：http://dali.cashguo.top/Article/details/gt2grwffbax.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.pycfn.com/Article/details/gt2yomkpaci.html

TS:   s.indexOf("x")
来源：http://dali.shuidangran.top/Article/details/gt2vlfmnkzb.html

Java: s.indexOf("x")
来源：http://dali.c1oappe.top/Article/details/gt2bdgbofid.html

Go:   strings.Index(s, "x")
来源：http://dali.9152youxi.cn/Article/details/gt2utpxseqq.html

Ruby: s.index("x")
来源：http://dali.pycfn.com/Article/details/gt2nmtwetth.html

C#:   s.IndexOf("x")
来源：http://dali.zhongyouzk.top/Article/details/gt2zskuwqoo.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yvedp.cn/Article/details/gt2yxxtuvij.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.daria6918.cn/Article/details/gt2jnxypxym.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yonumen.top/Article/details/gt2rtwnqjnq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nanxuanxn.top/Article/details/gt2akxoptsc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jqgfzy.top/Article/details/gt2vksbkvsj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ehwqpu.com/Article/details/gt2ahfxwean.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yj202588.top/Article/details/gt2wvwqvsxl.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yj20258888.top/Article/details/gt2azebdfrz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yanxiufei.cn/Article/details/gt2bjndszjw.html

[E06] 替换子串
来源：http://dali.9152youxi.cn/Article/details/gt2fbcpmmzq.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jinqigufen.top/Article/details/gt2epyvabwx.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yangfankeji.com/Article/details/gt2obrivtwx.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vublmhal.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xziqi.cn/Article/details/gt2ytcifpgn.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ofrjcaiu.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2beqrxklj.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.daria6918.cn/Article/details/gt2eiwhvklg.html

C#:   s.Replace("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gt2mouyjfcw.html

[E07] 按分隔符拆分
来源：http://dali.quarkkingdee.top/Article/details/gt2qsmxawfp.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.daria6918.cn/Article/details/gt2vwyggyva.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jianghu66.top/Article/details/gt2peefjzkx.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.sysykeji.top/Article/details/gt2bxsuksov.html

TS:   s.split(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2duhqjroy.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.pycfn.com/Article/details/gt2jvdnkczr.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ybcxt.top/Article/details/gt2friinsuq.html

Ruby: s.split(",");  s.split
来源：http://dali.zhoulong.xyz/Article/details/gt2zvzsfbfj.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hywenlv.cn/Article/details/gt2uxhsbqwb.html

[E08] 数组按分隔符合并
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dhzzkvri.html

Py:   ",".join(items)
来源：http://dali.jyoumei.cn/Article/details/gt2woismyzv.html

PHP:  implode(",", $items);
来源：http://dali.zdqjudy.top/Article/details/gt2eboqsgqk.html

JS:   items.join(",")
来源：http://dali.c1oappe.top/Article/details/gt2eazewrcm.html

TS:   items.join(",")
来源：http://dali.sufxvd.cn/Article/details/gt2tvqkoqfn.html

Java: String.join(",", items)
来源：http://dali.bjfxy.top/Article/details/gt2ysvnxhcl.html

Go:   strings.Join(items, ",")
来源：http://dali.tianlin.xyz/Article/details/gt2vwkcejvz.html

Ruby: items.join(",")
来源：http://dali.yuanzhike.top/Article/details/gt2cmlagwmr.html

C#:   string.Join(",", items)
来源：http://dali.shangyingyoupin.top/Article/details/gt2amofjwrd.html

[E09] 去除所有空白字符
来源：http://dali.tian-w.cn/Article/details/gt2nrnugdug.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gaohongyu789.top/Article/details/gt2mxseqxio.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jyoumei.cn/Article/details/gt2fqlcgpxk.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.aizwys.cn/Article/details/gt2jzummfgm.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hnqzz.top/Article/details/gt2mutkkxzw.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.wangshuangyany.cn/Article/details/gt2cbsktdwc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhixingplan.top/Article/details/gt2dswvzllb.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gotoacloud.top/Article/details/gt2iarzgvby.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.vqdsnc.cn/Article/details/gt2djzdahmi.html

[E10] 左侧补零 / 定长填充
来源：http://dali.chenzaomai.com/Article/details/gt2sxjzcjyy.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yanxiufei.cn/Article/details/gt2qwazagdg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhongyouzk.top/Article/details/gt2hrvbvfec.html

JS:   "7".padStart(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gt2psjgrpde.html

TS:   "7".padStart(3, "0")
来源：http://dali.feifeiyinyue.top/Article/details/gt2qcnaccnw.html

Java: String.format("%03d", 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jsfmsxxz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yj20258.top/Article/details/gt2pskueazx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.9152youxi.cn/Article/details/gt2ezvuhafj.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hysaishi.cn/Article/details/gt2ekvztblj.html

[E11] 反转字符串
来源：http://dali.yuxming.cn/Article/details/gt2ngwmhsmj.html

Py:   s[::-1]
来源：http://dali.jqgufenzy.top/Article/details/gt2mnlgkjwt.html

PHP:  strrev($s);
来源：http://dali.nanxinkj.top/Article/details/gt2xikjirxy.html

JS:   [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gt2fnvaqgej.html

TS:   [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gt2ialhrkfp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.pengpengdd.cyou/Article/details/gt2zzyvvcdw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jazgshtb.html

Ruby: s.reverse
来源：http://dali.yj20258888.top/Article/details/gt2xrwhwxch.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.tianlin.xyz/Article/details/gt2ovddferf.html

[E12] 统计某字符出现次数
来源：http://dali.yonumen.top/Article/details/gt2psrxrcyi.html

Py:   s.count("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qpnnpbku.html

PHP:  substr_count($s, "a");
来源：http://dali.jqgfzy.top/Article/details/gt2ocpkyosm.html

JS:   s.split("a").length - 1
来源：http://dali.sxryk.cn/Article/details/gt2roxqrlvg.html

TS:   s.split("a").length - 1
来源：http://dali.ehwqpu.com/Article/details/gt2dgzyhuro.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.fengsongda.top/Article/details/gt2gswzdddi.html

Go:   strings.Count(s, "a")
来源：http://dali.cqqwz.cn/Article/details/gt2jnmfetuy.html

Ruby: s.count("a")
来源：http://dali.ydzc1.top/Article/details/gt2rwtnjllg.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yxteiuwn.html

[E13] 逐字符遍历
来源：http://dali.cucudq.cn/Article/details/gt2xgglowwq.html

Py:   for ch in s: print(ch)
来源：http://dali.guannengcc.top/Article/details/gt2vvkihzkg.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cqqwz.cn/Article/details/gt2sxyxtvwg.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj20258.top/Article/details/gt2owsikgol.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gogol.net.cn/Article/details/gt2evnstuff.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jyoumei.cn/Article/details/gt2vheuhdjp.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.chenlongwang.top/Article/details/gt2ubbxuyiz.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.snrcjt.cn/Article/details/gt2yalrbtle.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.316326.xyz/Article/details/gt2wznvhmnq.html

[E14] URL 编码与 Base64
来源：http://dali.hywenlv.cn/Article/details/gt2vzjfngmu.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.vqdsnc.cn/Article/details/gt2cwclzfgd.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2mzdwwpax.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.smart0.xyz/Article/details/gt2sncpofbt.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.0kj1m.cn/Article/details/gt2fqrvorep.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tfokhwwe.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.daxiang520.top/Article/details/gt2qrveoswl.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.wangdashe.top/Article/details/gt2xvnygbze.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.chenlongwang.top/Article/details/gt2pynqowbx.html

[E15] HTML 转义 / 反转义
来源：http://dali.quarkkingdee.top/Article/details/gt2ujdssqou.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.guannengcc.top/Article/details/gt2pzcrapvv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jianghu66.top/Article/details/gt2qilyklxo.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2bhhqfofo.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.aibaodan.cn/Article/details/gt2fordlput.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.gaohongyu789.top/Article/details/gt2wnywrzbn.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cucudq.cn/Article/details/gt2xanieusb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2nwxesvxp.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.chenzaomai.com/Article/details/gt2uadlqtev.html

[E16] 数字千分位
来源：http://dali.jqgufenzy.top/Article/details/gt2hvasqdhw.html

Py:   f"{1234567:,}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aasrcjmc.html

PHP:  number_format(1234567);
来源：http://dali.chenlongwang.top/Article/details/gt2hxxusavj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.nwbrower.top/Article/details/gt2uvwrcfir.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.sufxvd.cn/Article/details/gt2ojkfhjeg.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.svipenyu.cn/Article/details/gt2hayiykra.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.svipenyu.cn/Article/details/gt2eciqqxns.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.chenlongwang.top/Article/details/gt2zwrtjsfp.html

C#:   1234567.ToString("N0")
来源：http://dali.cucudq.cn/Article/details/gt2sqxemrdd.html

[E17] 首字母大写
来源：http://dali.svipenyu.cn/Article/details/gt2hjyqjghc.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zdqjudy.top/Article/details/gt2chnwufcx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sufxvd.cn/Article/details/gt2vxtkuggn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gugfythx.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ybcxt.top/Article/details/gt2byquiaat.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2spopctco.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cheryme.top/Article/details/gt2olcrmvkr.html

Ruby: s.capitalize
来源：http://dali.sweek.top/Article/details/gt2jtcwqhxj.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cheryme.top/Article/details/gt2rhxbddoi.html

[E18] 模板占位符替换
来源：http://dali.zhiwuduotai.top/Article/details/gt2cpnjfwhu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xuanzx.com/Article/details/gt2jraedwpk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yueranfly.top/Article/details/gt2qbppaaki.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dhxojcpg.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jianghu66.top/Article/details/gt2ryztpdtf.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gt2nyrjcuuk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gt2hsplcxqr.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hfpthk.cn/Article/details/gt2xkqiirhe.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.snrcjt.cn/Article/details/gt2ljoqqbmw.html

[E19] 多行文本按行拆分
来源：http://dali.ppjwa.cn/Article/details/gt2gygqipxr.html

Py:   s.splitlines()
来源：http://dali.zhengqikj.top/Article/details/gt2seyiuobr.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.guannengcc.top/Article/details/gt2fbrevmyh.html

JS:   s.split(/\r?\n/)
来源：http://dali.sysykeji.top/Article/details/gt2vrxlfqbg.html

TS:   s.split(/\r?\n/)
来源：http://dali.hfpthk.cn/Article/details/gt2nhfloiwi.html

Java: s.lines().toList()
来源：http://dali.sysykeji.top/Article/details/gt2pdshprdq.html

Go:   strings.Split(s, "\n")
来源：http://dali.gogol.net.cn/Article/details/gt2qufgkluu.html

Ruby: s.lines
来源：http://dali.xziqi.cn/Article/details/gt2jhozctqq.html

C#:   s.Split('\n')
来源：http://dali.daxiang520.top/Article/details/gt2jafujhnm.html

[E20] 判断字符串是否为空
来源：http://dali.hfpthk.cn/Article/details/gt2cwbxdbnr.html

Py:   if not s:
来源：http://dali.xylfe.cn/Article/details/gt2dmfdueub.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.vqdsnc.cn/Article/details/gt2vcisqbmw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yueranfly.top/Article/details/gt2afyezxpa.html

TS:   if (s === "") {}
来源：http://dali.jinqigufen.top/Article/details/gt2acmokibo.html

Java: if (s.isEmpty()) {}
来源：http://dali.sysykeji.top/Article/details/gt2byqtippn.html

Go:   if s == "" {}
来源：http://dali.dianchejie.cn/Article/details/gt2epdjfoun.html

Ruby: if s.empty?
来源：http://dali.sysykeji.top/Article/details/gt2fmktdntt.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sysykeji.top/Article/details/gt2kacvhflj.html

[E21] 超长截断加省略号
来源：http://dali.redwolf501.top/Article/details/gt2jviejmrj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinqigufen.top/Article/details/gt2yznbtlke.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.9152youxi.cn/Article/details/gt2phnfxgfj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yonumen.top/Article/details/gt2zqjiwjwp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zycfv.cn/Article/details/gt2ybsgjchc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yj20258888.top/Article/details/gt2eszxsasg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ydzc1.top/Article/details/gt2dsbevkga.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zycfv.cn/Article/details/gt2pnfschnq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cucudq.cn/Article/details/gt2ksyqsegi.html

[E22] 字节长度与字符长度
来源：http://dali.yj20258.top/Article/details/gt2eyqpgnzs.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.tianlin.xyz/Article/details/gt2juhmdokk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hysaishi.cn/Article/details/gt2kmwvbres.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgfzy.top/Article/details/gt2dyntfsqj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.andypj.xyz/Article/details/gt2wipxcfzj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.aizwys.cn/Article/details/gt2qgvhhlvy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yongpay.top/Article/details/gt2zstkvsiv.html

Ruby: s.bytesize;  s.length
来源：http://dali.hnxiangtu.top/Article/details/gt2ubtdehnt.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cheryme.top/Article/details/gt2osymdwzr.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2dhncsnnp.html

F. 文件与目录
来源：http://dali.fengsongda.top/Article/details/gt2pzgpajpk.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2vkuuflqo.html

[F01] 读取整个文件
来源：http://dali.ydzc1.top/Article/details/gt2zmeafllr.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.pycfn.com/Article/details/gt2eywyvfbz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gt2ibbtbzez.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.snrcjt.cn/Article/details/gt2vtoiyjqk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.smart0.xyz/Article/details/gt2jhinmhen.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gt2gpgbsytw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yueranfly.top/Article/details/gt2xuxsrtlb.html

Ruby: File.read("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2dzortpnr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xziqi.cn/Article/details/gt2zzoayzah.html

[F02] 逐行读取文件
来源：http://dali.9152youxi.cn/Article/details/gt2njtndcrs.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.vqdsnc.cn/Article/details/gt2cmgkwaek.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jqgfzy.top/Article/details/gt2rgpitnsv.html


<!-- 参考信息 -->