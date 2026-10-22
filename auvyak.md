代发 wailian999

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xziqi.cn/Article/details/gt2yqjtkhuc.html

PHP:  array_merge(...$nested);
来源：http://dali.jinqigfzy.top/Article/details/gt2hdcmrlgf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jianghu66.top/Article/details/gt2fcgdwjiy.html

TS:   nested.flat();
来源：http://dali.pycfn.com/Article/details/gt2ztcmmjjp.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhengqikj.top/Article/details/gt2utsgcztv.html

Go:   // 手写双层循环
来源：http://dali.ppjwa.cn/Article/details/gt2xgewvgvq.html

Ruby: nested.flatten
来源：http://dali.yvedp.cn/Article/details/gt2mfizgsnf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gt2hmsnujjm.html

[D19] 按字段分组
来源：http://dali.tianlin.xyz/Article/details/gt2sprfmilq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sufxvd.cn/Article/details/gt2vikgjkzx.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sweek.top/Article/details/gt2plcnzlvc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shangyingyoupin.top/Article/details/gt2qtczzppt.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.nwbrower.top/Article/details/gt2sdqucvnc.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.guannengcc.top/Article/details/gt2dibdidjf.html

Go:   // 手写 map[string][]T
来源：http://dali.hywenlv.cn/Article/details/gt2yogrchim.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hongshengwenyu.top/Article/details/gt2vjcpjqrh.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hywenlv.cn/Article/details/gt2updqnozy.html

[D20] 统计每个元素出现次数
来源：http://dali.jqgfzy.top/Article/details/gt2gjyfleus.html

Py:   Counter(arr)
来源：http://dali.meibo888.top/Article/details/gt2vmjbuzzp.html

PHP:  array_count_values($arr);
来源：http://dali.0kj1m.cn/Article/details/gt2dcopasmq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.dashuyun.cn/Article/details/gt2nmqznvjn.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.feifeiyinyue.top/Article/details/gt2wyataqtm.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.smart0.xyz/Article/details/gt2ltdatmml.html

Go:   // 手写 map[T]int
来源：http://dali.cheryme.top/Article/details/gt2xpzrllbf.html

Ruby: arr.tally
来源：http://dali.zhixingplan.top/Article/details/gt2wcflxbgz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.9152youxi.cn/Article/details/gt2vnyrgqyj.html

[D21] 判断是否包含某元素
来源：http://dali.gaohongyu789.top/Article/details/gt2ntdyxzaq.html

Py:   x in arr
来源：http://dali.jqgfzy.top/Article/details/gt2obcrgmpv.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sweek.top/Article/details/gt2uzkkvbbh.html

JS:   arr.includes(x)
来源：http://dali.ybcxt.top/Article/details/gt2crdfpsrj.html

TS:   arr.includes(x)
来源：http://dali.0kj1m.cn/Article/details/gt2weubymeh.html

Java: list.contains(x)
来源：http://dali.0kj1m.cn/Article/details/gt2utxbqctq.html

Go:   slices.Contains(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2oxsrgmoh.html

Ruby: arr.include?(x)
来源：http://dali.zhengqikj.top/Article/details/gt2ntqfkqmy.html

C#:   list.Contains(x)
来源：http://dali.tianlin.xyz/Article/details/gt2hvvjdwpg.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hnxiangtu.top/Article/details/gt2tvnwcmvf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rnadvcgw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jinqigufen.top/Article/details/gt2tcxkawxl.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2cwjuiqnl.html

TS:   [...arr];
来源：http://dali.hammf.cn/Article/details/gt2gzxbdmvq.html

Java: new ArrayList<>(list);
来源：http://dali.aizwys.cn/Article/details/gt2trvbqfil.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cucudq.cn/Article/details/gt2vncqaibq.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zbwbyihu.html

C#:   new List<int>(list);
来源：http://dali.guowangkeji.top/Article/details/gt2fxblazxf.html

[D23] reduce 累积计算
来源：http://dali.jqgufenzy.top/Article/details/gt2fgwfmhpj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.vqdsnc.cn/Article/details/gt2aeonciez.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dxmudymg.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2koqjtjpi.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sxryk.cn/Article/details/gt2fxwyccwf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hongshengwenyu.top/Article/details/gt2rnwzxhmg.html

Go:   // 手写循环
来源：http://dali.yuxming.cn/Article/details/gt2uoiukdtr.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.feifeiyinyue.top/Article/details/gt2pylkwgto.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yueranfly.top/Article/details/gt2cbtpaljs.html

[D24] 字典 / Map 基本操作
来源：http://dali.aizwys.cn/Article/details/gt2gzpqrjzj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.mhx1999.top/Article/details/gt2fagdlaja.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.gotoacloud.top/Article/details/gt2vktezgxa.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.gotoacloud.top/Article/details/gt2plxpflev.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yonumen.top/Article/details/gt2ltxrllpy.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xinyue.icu/Article/details/gt2jiaqehbc.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.andypj.xyz/Article/details/gt2aruvixdd.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.smart0.xyz/Article/details/gt2kckpzblw.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hnqzz.top/Article/details/gt2lphtbyjm.html

[D25] Set 集合去重与交并差
来源：http://dali.ivvv.top/Article/details/gt2lexvuhqt.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cucudq.cn/Article/details/gt2sikojzxt.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.sweek.top/Article/details/gt2kcwxskcg.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2dmwwltsj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.tianlin.xyz/Article/details/gt2kotzgwzl.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.tian-w.cn/Article/details/gt2gscqcnfs.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.chenjidiqi.icu/Article/details/gt2rnanhnjn.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cucudq.cn/Article/details/gt2kstatsmy.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yvedp.cn/Article/details/gt2dmuwfwre.html

[D26] 数组转字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tnnmoigk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ehwqpu.com/Article/details/gt2fnevoxme.html

PHP:  implode(", ", $arr);
来源：http://dali.xziqi.cn/Article/details/gt2ojzqgpys.html

JS:   arr.join(", ")
来源：http://dali.ivvv.top/Article/details/gt2dixvisbo.html

TS:   arr.join(", ")
来源：http://dali.zhongyouzk.top/Article/details/gt2kmmmfnmx.html

Java: String.join(", ", list)
来源：http://dali.jianghu66.top/Article/details/gt2hqptbypx.html

Go:   strings.Join(strs, ", ")
来源：http://dali.guowangkeji.top/Article/details/gt2lgxnpwsd.html

Ruby: arr.join(", ")
来源：http://dali.hnqzz.top/Article/details/gt2doosuzwo.html

C#:   string.Join(", ", list)
来源：http://dali.aizwys.cn/Article/details/gt2zhaisymw.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2fvbleyez.html

E. 字符串处理
来源：http://dali.zdqjudy.top/Article/details/gt2wbwuunew.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2wxiqcbwi.html

[E01] 拼接字符串
来源：http://dali.bjfxy.top/Article/details/gt2njyndwlu.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.fzhhl.top/Article/details/gt2ryrapgqw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.aizwys.cn/Article/details/gt2whwecbpi.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yanxiufei.cn/Article/details/gt2dnpwpoqk.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tian-w.cn/Article/details/gt2fccuaknc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.pycfn.com/Article/details/gt2gklbqdkn.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yvedp.cn/Article/details/gt2xrlpppwg.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xuanzx.com/Article/details/gt2wfxodfyx.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.meibo888.top/Article/details/gt2odfnbnwa.html

[E02] 重复字符串
来源：http://dali.cheryme.top/Article/details/gt2fmnsdzax.html

Py:   "ab" * 3
来源：http://dali.bjfxy.top/Article/details/gt2gsrecqng.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shzxlz.cn/Article/details/gt2rnkwxwqz.html

JS:   "ab".repeat(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tsgycfxa.html

TS:   "ab".repeat(3)
来源：http://dali.ehwqpu.com/Article/details/gt2heyphfmc.html

Java: "ab".repeat(3)
来源：http://dali.hywenlv.cn/Article/details/gt2ysyhxzzr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cqqwz.cn/Article/details/gt2uexoojvq.html

Ruby: "ab" * 3
来源：http://dali.kuanghao11.cn/Article/details/gt2yxklbzby.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xuetiantiany.cn/Article/details/gt2fsujcfwn.html

[E03] 截取子串
来源：http://dali.ybcxt.top/Article/details/gt2xopczgvt.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wivwgogp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shzxlz.cn/Article/details/gt2vkchiqdk.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wummwufx.html

TS:   s.slice(1, 4)
来源：http://dali.xylfe.cn/Article/details/gt2khqsbiyl.html

Java: s.substring(1, 4)
来源：http://dali.feifeiyinyue.top/Article/details/gt2hzxvvpyl.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.fzhhl.top/Article/details/gt2mgzbvlgl.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.nwbrower.top/Article/details/gt2tqyetayi.html

C#:   s.Substring(1, 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xxvufdba.html

[E04] 查找子串位置
来源：http://dali.yangfankeji.com/Article/details/gt2jdtgarvq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ivvv.top/Article/details/gt2oqhrzyts.html

PHP:  strpos($s, "x");
来源：http://dali.jinqigfzy.top/Article/details/gt2vdxojxvl.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.havefunace.top/Article/details/gt2hzxmgeve.html

TS:   s.indexOf("x")
来源：http://dali.yangfankeji.com/Article/details/gt2yyzufhdk.html

Java: s.indexOf("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2riwviztz.html

Go:   strings.Index(s, "x")
来源：http://dali.haohaochexian.top/Article/details/gt2sbzgtvcw.html

Ruby: s.index("x")
来源：http://dali.hysaishi.cn/Article/details/gt2etcijbrk.html

C#:   s.IndexOf("x")
来源：http://dali.nanxinkj.top/Article/details/gt2sgzehgua.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xylfe.cn/Article/details/gt2mhunadck.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.wangshuangyany.cn/Article/details/gt2osmdjqng.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.9152youxi.cn/Article/details/gt2zgxpxhxm.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fengsongda.top/Article/details/gt2ffvsfdwp.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.tianlin.xyz/Article/details/gt2ugqdfqvy.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ivvv.top/Article/details/gt2msieggis.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.sxryk.cn/Article/details/gt2lgfrkndz.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.daria6918.cn/Article/details/gt2cupmtadu.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.smart0.xyz/Article/details/gt2cccaucni.html

[E06] 替换子串
来源：http://dali.pengpengdd.cyou/Article/details/gt2xrecxmyx.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hujqukzy.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xinyue.icu/Article/details/gt2prgpnyhu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shuidangran.top/Article/details/gt2cjeudwzq.html

TS:   s.replaceAll("a", "b")
来源：http://dali.wangdashe.top/Article/details/gt2oaslydsx.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gt2vsisuith.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.dianchejie.cn/Article/details/gt2kdzwicpx.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gt2krzhalrx.html

C#:   s.Replace("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ulkjpyzv.html

[E07] 按分隔符拆分
来源：http://dali.meibo888.top/Article/details/gt2zerhyzau.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.wangdashe.top/Article/details/gt2hpmeuyem.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hnqzz.top/Article/details/gt2wrdrhgwd.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.fzhhl.top/Article/details/gt2psjfganh.html

TS:   s.split(",")
来源：http://dali.gzhubu.top/Article/details/gt2hhdxhxiu.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.guowangkeji.top/Article/details/gt2xilrugfe.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yvedp.cn/Article/details/gt2cmudneaq.html

Ruby: s.split(",");  s.split
来源：http://dali.tanke756.top/Article/details/gt2bersejrh.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ybcxt.top/Article/details/gt2dpuzebwk.html

[E08] 数组按分隔符合并
来源：http://dali.nanxuanxn.top/Article/details/gt2jsafvxre.html

Py:   ",".join(items)
来源：http://dali.fzhhl.top/Article/details/gt2dgpzmpst.html

PHP:  implode(",", $items);
来源：http://dali.chenlongwang.top/Article/details/gt2poepnnmb.html

JS:   items.join(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lclfsmzw.html

TS:   items.join(",")
来源：http://dali.zhixingplan.top/Article/details/gt2uvsmyfwq.html

Java: String.join(",", items)
来源：http://dali.vqdsnc.cn/Article/details/gt2lallshkb.html

Go:   strings.Join(items, ",")
来源：http://dali.chenzaomai.com/Article/details/gt2ocnylytp.html

Ruby: items.join(",")
来源：http://dali.daria6918.cn/Article/details/gt2bpckwtuc.html

C#:   string.Join(",", items)
来源：http://dali.xziqi.cn/Article/details/gt2qefntwvq.html

[E09] 去除所有空白字符
来源：http://dali.quarkkingdee.top/Article/details/gt2puuicstj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yonumen.top/Article/details/gt2zmebqmrw.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yanxiufei.cn/Article/details/gt2alejedwx.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ydzc1.top/Article/details/gt2dtglofsi.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.guannengcc.top/Article/details/gt2dekjhixs.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cashguo.top/Article/details/gt2rwpfqutp.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hvezqzub.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.aizwys.cn/Article/details/gt2stzivqix.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhiwuduotai.top/Article/details/gt2gstdkupb.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xinyue.icu/Article/details/gt2qvfxvdij.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.nanxinkj.top/Article/details/gt2lszxrcmx.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yuxming.cn/Article/details/gt2ezjdbbrd.html

JS:   "7".padStart(3, "0")
来源：http://dali.daxiang520.top/Article/details/gt2uhefohua.html

TS:   "7".padStart(3, "0")
来源：http://dali.yueranfly.top/Article/details/gt2rkeofxkf.html

Java: String.format("%03d", 7)
来源：http://dali.aibaodan.cn/Article/details/gt2cwqbkhui.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hnxiangtu.top/Article/details/gt2moylcmam.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fofhotel.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ehwqpu.com/Article/details/gt2owlyibht.html

[E11] 反转字符串
来源：http://dali.yj20258.top/Article/details/gt2grbhdtsc.html

Py:   s[::-1]
来源：http://dali.iojbl.cn/Article/details/gt2cryieavy.html

PHP:  strrev($s);
来源：http://dali.jinqigufen.top/Article/details/gt2ifeiegks.html

JS:   [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gt2kdhnnzrn.html

TS:   [...s].reverse().join("")
来源：http://dali.yvedp.cn/Article/details/gt2grqokupq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gzhubu.top/Article/details/gt2ifqrbdoc.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.bjfxy.top/Article/details/gt2nluukwyu.html

Ruby: s.reverse
来源：http://dali.yangfankeji.com/Article/details/gt2owkkmufx.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ivvv.top/Article/details/gt2iiaifmxv.html

[E12] 统计某字符出现次数
来源：http://dali.hammf.cn/Article/details/gt2sfhlgghh.html

Py:   s.count("a")
来源：http://dali.jinqigfzy.top/Article/details/gt2alzlirwy.html

PHP:  substr_count($s, "a");
来源：http://dali.nwbrower.top/Article/details/gt2klktzukv.html

JS:   s.split("a").length - 1
来源：http://dali.0kj1m.cn/Article/details/gt2jbetyssh.html

TS:   s.split("a").length - 1
来源：http://dali.yj202588.top/Article/details/gt2vhoxuxrj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.gzhubu.top/Article/details/gt2nhddahtl.html

Go:   strings.Count(s, "a")
来源：http://dali.jiagoushi.top/Article/details/gt2lhoybrub.html

Ruby: s.count("a")
来源：http://dali.sufxvd.cn/Article/details/gt2yrfdobsh.html

C#:   s.Count(c => c == 'a')
来源：http://dali.andypj.xyz/Article/details/gt2tbiuzuxd.html

[E13] 逐字符遍历
来源：http://dali.dashuyun.cn/Article/details/gt2wmbvhwme.html

Py:   for ch in s: print(ch)
来源：http://dali.yvedp.cn/Article/details/gt2twjxstge.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yangfankeji.com/Article/details/gt2mmgmrpcx.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hnxiangtu.top/Article/details/gt2ixdqdvxh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xinyue.icu/Article/details/gt2uyfpnagl.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jqgfzy.top/Article/details/gt2jpsvyibp.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ydzc1.top/Article/details/gt2gbufvvwn.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhengqikj.top/Article/details/gt2mhehchmc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hfpthk.cn/Article/details/gt2dyapbeli.html

[E14] URL 编码与 Base64
来源：http://dali.ppjwa.cn/Article/details/gt2suzacvte.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.tianlin.xyz/Article/details/gt2ihbaotlh.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cdnleiting.top/Article/details/gt2gwzhedxs.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.0kj1m.cn/Article/details/gt2eayzqurr.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2kqpdhace.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.nanxuanxn.top/Article/details/gt2rusdtawm.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xuetiantiany.cn/Article/details/gt2jdxjndci.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.snrcjt.cn/Article/details/gt2duqmrbxt.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ydzc1.top/Article/details/gt2pdrhghyh.html

[E15] HTML 转义 / 反转义
来源：http://dali.cheryme.top/Article/details/gt2vtpguviq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2ijoslpwv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.andypj.xyz/Article/details/gt2rewlfgqm.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.wangdashe.top/Article/details/gt2fucwrmlg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.snrcjt.cn/Article/details/gt2zeescxiu.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yangfankeji.com/Article/details/gt2jpjeqbut.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.nanxinkj.top/Article/details/gt2vlpffkru.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cucudq.cn/Article/details/gt2iexalhvo.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gotoacloud.top/Article/details/gt2enxjsqif.html

[E16] 数字千分位
来源：http://dali.shuidangran.top/Article/details/gt2lhjioufb.html

Py:   f"{1234567:,}"
来源：http://dali.daxiang520.top/Article/details/gt2fxhzemys.html

PHP:  number_format(1234567);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lvpovmwp.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.kuanghao11.cn/Article/details/gt2dirkekan.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cashguo.top/Article/details/gt2vplougxj.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.fengsongda.top/Article/details/gt2cialpgcy.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.pengpengdd.cyou/Article/details/gt2xbthxeby.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.smart0.xyz/Article/details/gt2gwzwweqy.html

C#:   1234567.ToString("N0")
来源：http://dali.yvedp.cn/Article/details/gt2fdratnds.html

[E17] 首字母大写
来源：http://dali.andypj.xyz/Article/details/gt2jhylcger.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.quarkkingdee.top/Article/details/gt2qzulyflb.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.fengsongda.top/Article/details/gt2flkmjzhb.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xziqi.cn/Article/details/gt2qypyjrkb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2oulscsnb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.guowangkeji.top/Article/details/gt2dnvgyoso.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.dianchejie.cn/Article/details/gt2uyeleytt.html

Ruby: s.capitalize
来源：http://dali.xziqi.cn/Article/details/gt2ymzliwng.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yueranfly.top/Article/details/gt2gpublztt.html

[E18] 模板占位符替换
来源：http://dali.yj20258.top/Article/details/gt2zcrhdzkw.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vozgwslk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.svipenyu.cn/Article/details/gt2hjlxnieu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gt2jbdnnqxe.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.birdmap.top/Article/details/gt2clgqxacf.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gt2qgmcwgds.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tsgryatd.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.redwolf501.top/Article/details/gt2ofcbbrhv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.chenzaomai.com/Article/details/gt2evtemzpt.html

[E19] 多行文本按行拆分
来源：http://dali.svipenyu.cn/Article/details/gt2kequkkrw.html

Py:   s.splitlines()
来源：http://dali.yj202588.top/Article/details/gt2wtezyfsn.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cqqwz.cn/Article/details/gt2gmdmdcjc.html

JS:   s.split(/\r?\n/)
来源：http://dali.jianghu66.top/Article/details/gt2efakgfqv.html

TS:   s.split(/\r?\n/)
来源：http://dali.haohaochexian.top/Article/details/gt2npgyyqkx.html

Java: s.lines().toList()
来源：http://dali.jyoumei.cn/Article/details/gt2akxwsjsv.html

Go:   strings.Split(s, "\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wviksrmq.html

Ruby: s.lines
来源：http://dali.snrcjt.cn/Article/details/gt2rbmrwdpx.html

C#:   s.Split('\n')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jugqmzdd.html

[E20] 判断字符串是否为空
来源：http://dali.jianghu66.top/Article/details/gt2bfgjoinb.html

Py:   if not s:
来源：http://dali.yuanzhike.top/Article/details/gt2feyojhxj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ehwqpu.com/Article/details/gt2sgcumxdj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ehwqpu.com/Article/details/gt2biparwhs.html

TS:   if (s === "") {}
来源：http://dali.hnxiangtu.top/Article/details/gt2lyowypbg.html

Java: if (s.isEmpty()) {}
来源：http://dali.snrcjt.cn/Article/details/gt2qbhtnzxk.html

Go:   if s == "" {}
来源：http://dali.daxiang520.top/Article/details/gt2gkokyjhr.html

Ruby: if s.empty?
来源：http://dali.feifeiyinyue.top/Article/details/gt2cwjrsoud.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cqqwz.cn/Article/details/gt2hrdfhkvp.html

[E21] 超长截断加省略号
来源：http://dali.yanxiufei.cn/Article/details/gt2mobwloxi.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jqgufenzy.top/Article/details/gt2fiqgiwsi.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zycfv.cn/Article/details/gt2tiqugwsc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xylfe.cn/Article/details/gt2qewwpvht.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xinyue.icu/Article/details/gt2ibvjezmz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gt2rbuasrpc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hnxiangtu.top/Article/details/gt2ftqheqix.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.sxryk.cn/Article/details/gt2fqimmtuy.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gt2gnyvovmz.html

[E22] 字节长度与字符长度
来源：http://dali.tian-w.cn/Article/details/gt2qwtubkck.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fqqoqygh.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenzaomai.com/Article/details/gt2fnqictgv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guowangkeji.top/Article/details/gt2qtaioeqj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.birdmap.top/Article/details/gt2wattoikb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.guannengcc.top/Article/details/gt2bwqfegwp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.aibaodan.cn/Article/details/gt2bipkfcxl.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gt2rqlfbwnh.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cheryme.top/Article/details/gt2yhjxllbi.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2zvbyixpt.html

F. 文件与目录
来源：http://dali.wangshuangyany.cn/Article/details/gt2baybjodn.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2bbadarex.html

[F01] 读取整个文件
来源：http://dali.havefunace.top/Article/details/gt2srwfigfb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yuxming.cn/Article/details/gt2uuorbfpt.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zmvgejoa.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.dashuyun.cn/Article/details/gt2ckytijsu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinqigufen.top/Article/details/gt2tccxlcts.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gt2ydxlgblb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.tanke756.top/Article/details/gt2lmqghtpz.html

Ruby: File.read("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2musgcdao.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.c1oappe.top/Article/details/gt2nicfkbes.html

[F02] 逐行读取文件
来源：http://dali.jianghu66.top/Article/details/gt2vcbbbrzk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sweek.top/Article/details/gt2fgrxemfl.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hnqzz.top/Article/details/gt2yzjqdsds.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fzhhl.top/Article/details/gt2uyrxnazu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yongpay.top/Article/details/gt2vvfosnuu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zdqjudy.top/Article/details/gt2lzzkygbc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.chenlongwang.top/Article/details/gt2hcrbddyi.html


<!-- 参考信息 -->