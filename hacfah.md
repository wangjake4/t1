代发 wailian999

[D19] 按字段分组
来源：http://dali.yangfankeji.com/Article/details/gttduopgdq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.guannengcc.top/Article/details/gtvdsmzrkt.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zycfv.cn/Article/details/gthhgyhryd.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.quarkkingdee.top/Article/details/gtqyoecfsu.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.dashuyun.cn/Article/details/gtxaqrekth.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sweek.top/Article/details/gtjzvfucmy.html

Go:   // 手写 map[string][]T
来源：http://dali.hongshengwenyu.top/Article/details/gtdrmfoiie.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsivfvcub.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yangfankeji.com/Article/details/gtuzmbarwf.html

[D20] 统计每个元素出现次数
来源：http://dali.yangfankeji.com/Article/details/gtnmmppzte.html

Py:   Counter(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtuohhconr.html

PHP:  array_count_values($arr);
来源：http://dali.9152youxi.cn/Article/details/gtyuyeckzp.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zdqjudy.top/Article/details/gtabdxgyvd.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ehwqpu.com/Article/details/gtychwldri.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.tian-w.cn/Article/details/gtkmengths.html

Go:   // 手写 map[T]int
来源：http://dali.haohaochexian.top/Article/details/gtxxeyqruk.html

Ruby: arr.tally
来源：http://dali.havefunace.top/Article/details/gtzexuevgs.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.chenjidiqi.icu/Article/details/gtbnruasrf.html

[D21] 判断是否包含某元素
来源：http://dali.zhoulong.xyz/Article/details/gtvogjvufz.html

Py:   x in arr
来源：http://dali.dianchejie.cn/Article/details/gtociioalb.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtshvxbdri.html

JS:   arr.includes(x)
来源：http://dali.vqdsnc.cn/Article/details/gtcgvzdceh.html

TS:   arr.includes(x)
来源：http://dali.redwolf501.top/Article/details/gtiwjsvpic.html

Java: list.contains(x)
来源：http://dali.havefunace.top/Article/details/gtclqyfjav.html

Go:   slices.Contains(arr, x)
来源：http://dali.yueranfly.top/Article/details/gtwbdmagri.html

Ruby: arr.include?(x)
来源：http://dali.tian-w.cn/Article/details/gtsrmljgyr.html

C#:   list.Contains(x)
来源：http://dali.meibo888.top/Article/details/gtpcxepqig.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hfpthk.cn/Article/details/gtocrgelpg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cqqwz.cn/Article/details/gttvyjwphh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.redwolf501.top/Article/details/gtyppwyuzh.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hywenlv.cn/Article/details/gtuvdilfym.html

TS:   [...arr];
来源：http://dali.aibaodan.cn/Article/details/gtqekrteec.html

Java: new ArrayList<>(list);
来源：http://dali.redwolf501.top/Article/details/gtvidohtpo.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gthkomakly.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ivvv.top/Article/details/gtcokokzcl.html

C#:   new List<int>(list);
来源：http://dali.iojbl.cn/Article/details/gtylmoikut.html

[D23] reduce 累积计算
来源：http://dali.gaohongyu789.top/Article/details/gtdbkucgnc.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yj20258888.top/Article/details/gtunbiesdw.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hfpthk.cn/Article/details/gteunzrrxt.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cqqwz.cn/Article/details/gtzueoptwg.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yvedp.cn/Article/details/gtttfzuptr.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.tanke756.top/Article/details/gteqlrwhil.html

Go:   // 手写循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtvgvtvqfq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.vqdsnc.cn/Article/details/gtwroutqaw.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gtafhflbfk.html

[D24] 字典 / Map 基本操作
来源：http://dali.guannengcc.top/Article/details/gtwdjlqijy.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.9152youxi.cn/Article/details/gtisrxrnme.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xuetiantiany.cn/Article/details/gtgtsrxgep.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jqgufenzy.top/Article/details/gtkkbnnioe.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sweek.top/Article/details/gtypvuduzo.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.guowangkeji.top/Article/details/gtxaxdkxnk.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.guannengcc.top/Article/details/gthukmlnis.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxngllnqo.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.guannengcc.top/Article/details/gtnmmlzfws.html

[D25] Set 集合去重与交并差
来源：http://dali.yj20258888.top/Article/details/gtxnczexlu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jinqigufen.top/Article/details/gthmyxhipg.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.gogol.net.cn/Article/details/gtyxhgsjxf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.tanke756.top/Article/details/gtrpujfric.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.vqdsnc.cn/Article/details/gtscirteyf.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sweek.top/Article/details/gtbkkxhuil.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shangyingyoupin.top/Article/details/gtxjrverwe.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.haohaochexian.top/Article/details/gtxxkyewck.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hysaishi.cn/Article/details/gtntghpxbg.html

[D26] 数组转字符串
来源：http://dali.guowangkeji.top/Article/details/gtlpsagsfv.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hongshengwenyu.top/Article/details/gtowthvvvg.html

PHP:  implode(", ", $arr);
来源：http://dali.cqqwz.cn/Article/details/gtxdclcsqd.html

JS:   arr.join(", ")
来源：http://dali.xuetiantiany.cn/Article/details/gtkxfujdjp.html

TS:   arr.join(", ")
来源：http://dali.hongshengwenyu.top/Article/details/gtfpyxbapd.html

Java: String.join(", ", list)
来源：http://dali.wangshuangyany.cn/Article/details/gtndcwqqwh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cucudq.cn/Article/details/gtzcyxrkea.html

Ruby: arr.join(", ")
来源：http://dali.yonumen.top/Article/details/gttwretont.html

C#:   string.Join(", ", list)
来源：http://dali.shuidangran.top/Article/details/gthxcdilut.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtqsuzmprt.html

E. 字符串处理
来源：http://dali.guannengcc.top/Article/details/gtxxtpigsq.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtqyvotfwj.html

[E01] 拼接字符串
来源：http://dali.yj20258888.top/Article/details/gtlndmugaf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.bjfxy.top/Article/details/gtakhyjiyj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hnqzz.top/Article/details/gtfxhpzmfy.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xylfe.cn/Article/details/gthgsmlnbw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtdyyltfna.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxrbdmezp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.feifeiyinyue.top/Article/details/gttcrndgxa.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.316326.xyz/Article/details/gtrnjtwjcs.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtqzmmcxmi.html

[E02] 重复字符串
来源：http://dali.jlsjyb.cn/Article/details/gtbwhwkhwu.html

Py:   "ab" * 3
来源：http://dali.ydzc1.top/Article/details/gtfomhwhcn.html

PHP:  str_repeat("ab", 3);
来源：http://dali.aibaodan.cn/Article/details/gtbzhiskxi.html

JS:   "ab".repeat(3)
来源：http://dali.yangfankeji.com/Article/details/gtlhwzpzuv.html

TS:   "ab".repeat(3)
来源：http://dali.redwolf501.top/Article/details/gtcwyerhbg.html

Java: "ab".repeat(3)
来源：http://dali.yj20258888.top/Article/details/gtfeblmcgt.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.c1oappe.top/Article/details/gtobpkaast.html

Ruby: "ab" * 3
来源：http://dali.guannengcc.top/Article/details/gtxifdiviv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.c1oappe.top/Article/details/gtckipgqsz.html

[E03] 截取子串
来源：http://dali.zhongyouzk.top/Article/details/gtjlacypnm.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.snrcjt.cn/Article/details/gtunlukzdz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hywenlv.cn/Article/details/gtajwkwbei.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.pycfn.com/Article/details/gtnsiwmoub.html

TS:   s.slice(1, 4)
来源：http://dali.yj20258888.top/Article/details/gtozvmwcwk.html

Java: s.substring(1, 4)
来源：http://dali.cucudq.cn/Article/details/gtbglvhjqf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.smart0.xyz/Article/details/gtihekpofe.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.kuanghao11.cn/Article/details/gtjrxhvcsd.html

C#:   s.Substring(1, 3)
来源：http://dali.yanxiufei.cn/Article/details/gtmlbkzqoy.html

[E04] 查找子串位置
来源：http://dali.cashguo.top/Article/details/gtkmqjvxfs.html

Py:   s.find("x");  s.index("x")
来源：http://dali.gzhubu.top/Article/details/gtjgqplnga.html

PHP:  strpos($s, "x");
来源：http://dali.svipenyu.cn/Article/details/gtziwnkdtl.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinqigufen.top/Article/details/gtoflscjev.html

TS:   s.indexOf("x")
来源：http://dali.shangyingyoupin.top/Article/details/gtndaxxwwv.html

Java: s.indexOf("x")
来源：http://dali.cashguo.top/Article/details/gtqwzfdhef.html

Go:   strings.Index(s, "x")
来源：http://dali.yvedp.cn/Article/details/gtmqevvndg.html

Ruby: s.index("x")
来源：http://dali.iojbl.cn/Article/details/gtymdnixnx.html

C#:   s.IndexOf("x")
来源：http://dali.xuetiantiany.cn/Article/details/gtrvyfrpzz.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.nanxinkj.top/Article/details/gttkvvbskv.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.tian-w.cn/Article/details/gtwonlfkaf.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zycfv.cn/Article/details/gtqgutktoh.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cdnleiting.top/Article/details/gtddcjwzkn.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.havefunace.top/Article/details/gtotaiubkg.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sysykeji.top/Article/details/gtfllfgpdo.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.9152youxi.cn/Article/details/gtnezzwxya.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdpewsjzy.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sufxvd.cn/Article/details/gtknipmwwd.html

[E06] 替换子串
来源：http://dali.yuanzhike.top/Article/details/gtkwcocrma.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtxxamzxnc.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.dianchejie.cn/Article/details/gtknffymct.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gtqmeepviw.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtzbtkmnvv.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtizackjpy.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpfycrlwf.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtznbppiel.html

C#:   s.Replace("a", "b")
来源：http://dali.ivvv.top/Article/details/gtmxplzmlg.html

[E07] 按分隔符拆分
来源：http://dali.guowangkeji.top/Article/details/gtduvnnrtw.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.316326.xyz/Article/details/gtaptodfqr.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hammf.cn/Article/details/gtvrgeakql.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.9152youxi.cn/Article/details/gtqgkgrhoe.html

TS:   s.split(",")
来源：http://dali.yuxming.cn/Article/details/gttkxytxzi.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jinqigufen.top/Article/details/gtkyumxdit.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.meibo888.top/Article/details/gtxwikvduk.html

Ruby: s.split(",");  s.split
来源：http://dali.jlsjyb.cn/Article/details/gtvditrqat.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ppjwa.cn/Article/details/gtqqoaqmmq.html

[E08] 数组按分隔符合并
来源：http://dali.zdqjudy.top/Article/details/gtolrfhhbf.html

Py:   ",".join(items)
来源：http://dali.guowangkeji.top/Article/details/gtibqkvaso.html

PHP:  implode(",", $items);
来源：http://dali.zhongyouzk.top/Article/details/gtlcvsadct.html

JS:   items.join(",")
来源：http://dali.nwbrower.top/Article/details/gtzjfimwyd.html

TS:   items.join(",")
来源：http://dali.tanke756.top/Article/details/gttzsjrptn.html

Java: String.join(",", items)
来源：http://dali.jlsjyb.cn/Article/details/gtkqyijmyy.html

Go:   strings.Join(items, ",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gthywrdjqr.html

Ruby: items.join(",")
来源：http://dali.aibaodan.cn/Article/details/gtnqcwksmq.html

C#:   string.Join(",", items)
来源：http://dali.hfpthk.cn/Article/details/gtbhjtkleg.html

[E09] 去除所有空白字符
来源：http://dali.nanxuanxn.top/Article/details/gtkikzntsb.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shangyingyoupin.top/Article/details/gtvtesawyg.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.sufxvd.cn/Article/details/gtvggtcdpt.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hnxiangtu.top/Article/details/gtecwxryva.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sweek.top/Article/details/gtuosylmmg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhoulong.xyz/Article/details/gtnnapekej.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zycfv.cn/Article/details/gtswpnkukr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jinqigfzy.top/Article/details/gtmphelqas.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.mhx1999.top/Article/details/gtxvkurcxf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinqigufen.top/Article/details/gtqqkupccr.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gtudmwjoci.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.guannengcc.top/Article/details/gtqfnvoruj.html

JS:   "7".padStart(3, "0")
来源：http://dali.smart0.xyz/Article/details/gtuskwufla.html

TS:   "7".padStart(3, "0")
来源：http://dali.c1oappe.top/Article/details/gtytzgyatd.html

Java: String.format("%03d", 7)
来源：http://dali.cashguo.top/Article/details/gtiwalulzq.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hysaishi.cn/Article/details/gtlhddmrew.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gtsxqdbtoq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.havefunace.top/Article/details/gtsbzayodu.html

[E11] 反转字符串
来源：http://dali.fengsongda.top/Article/details/gtytxxmhcy.html

Py:   s[::-1]
来源：http://dali.mhx1999.top/Article/details/gteuyluntt.html

PHP:  strrev($s);
来源：http://dali.birdmap.top/Article/details/gtihhdskdn.html

JS:   [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gtkfqgogwt.html

TS:   [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gtvnsellwd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.daria6918.cn/Article/details/gtlagxnuhl.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.dashuyun.cn/Article/details/gthaacgghl.html

Ruby: s.reverse
来源：http://dali.quarkkingdee.top/Article/details/gtuvfnumat.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.nwbrower.top/Article/details/gtxupzxofs.html

[E12] 统计某字符出现次数
来源：http://dali.aizwys.cn/Article/details/gtojuxovms.html

Py:   s.count("a")
来源：http://dali.shangyingyoupin.top/Article/details/gthnkhswze.html

PHP:  substr_count($s, "a");
来源：http://dali.hywenlv.cn/Article/details/gtttfkfiwa.html

JS:   s.split("a").length - 1
来源：http://dali.sxryk.cn/Article/details/gtnblvlbie.html

TS:   s.split("a").length - 1
来源：http://dali.aibaodan.cn/Article/details/gtamcurqmx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hfpthk.cn/Article/details/gtolgihoqg.html

Go:   strings.Count(s, "a")
来源：http://dali.havefunace.top/Article/details/gtrjaoncsj.html

Ruby: s.count("a")
来源：http://dali.fengsongda.top/Article/details/gtcuitrazf.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xuanzx.com/Article/details/gtjcntqlgf.html

[E13] 逐字符遍历
来源：http://dali.bjfxy.top/Article/details/gteiuhxypj.html

Py:   for ch in s: print(ch)
来源：http://dali.zhengqikj.top/Article/details/gtotufvrmr.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yueranfly.top/Article/details/gtpeyzitck.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gteiptkeze.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.svipenyu.cn/Article/details/gtmuqvzoug.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zdqjudy.top/Article/details/gtaaqbqhqr.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbdskrvcy.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nanxinkj.top/Article/details/gtdviybhaw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.iojbl.cn/Article/details/gtwulkljmm.html

[E14] URL 编码与 Base64
来源：http://dali.xuetiantiany.cn/Article/details/gttkgaomjr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xylfe.cn/Article/details/gtmqonfslf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.svipenyu.cn/Article/details/gtsffkiqmg.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.feifeiyinyue.top/Article/details/gtjasjxaqc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhengqikj.top/Article/details/gtvjptufru.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.andypj.xyz/Article/details/gtxrcrylav.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.chenzaomai.com/Article/details/gtcoxhtcoi.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jyoumei.cn/Article/details/gtvfzezrls.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinqigufen.top/Article/details/gtxddnfcjk.html

[E15] HTML 转义 / 反转义
来源：http://dali.yangfankeji.com/Article/details/gtamruxoun.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.tanke756.top/Article/details/gtyffhmvtq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.pycfn.com/Article/details/gtgvowgpdk.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.quarkkingdee.top/Article/details/gtnjcrlvlm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.nwbrower.top/Article/details/gtwvvsivbl.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zycfv.cn/Article/details/gtqtfrigob.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.birdmap.top/Article/details/gtwiohohzh.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtfyoyvdly.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jinqigufen.top/Article/details/gtokfykyxi.html

[E16] 数字千分位
来源：http://dali.tianlin.xyz/Article/details/gtjaftjbnm.html

Py:   f"{1234567:,}"
来源：http://dali.gaohongyu789.top/Article/details/gtpuwegnsi.html

PHP:  number_format(1234567);
来源：http://dali.daxiang520.top/Article/details/gtrurwthbf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.fzhhl.top/Article/details/gtbrtzktay.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.kuanghao11.cn/Article/details/gtbxwtpycr.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jlsjyb.cn/Article/details/gtoeheghtb.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.guannengcc.top/Article/details/gtkdxmijku.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjyfytdft.html

C#:   1234567.ToString("N0")
来源：http://dali.daxiang520.top/Article/details/gteekqpeso.html

[E17] 首字母大写
来源：http://dali.zdqjudy.top/Article/details/gtmtaqlofp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.smart0.xyz/Article/details/gtkirtqosq.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.smart0.xyz/Article/details/gtlwgmseqe.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guowangkeji.top/Article/details/gtoqncwtbw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pycfn.com/Article/details/gtsisfptjx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.svipenyu.cn/Article/details/gtzdiopirk.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhoulong.xyz/Article/details/gtoxqgikeh.html

Ruby: s.capitalize
来源：http://dali.mhx1999.top/Article/details/gtnyocsnuw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yj20258.top/Article/details/gtnjpwtiwl.html

[E18] 模板占位符替换
来源：http://dali.quarkkingdee.top/Article/details/gtovifabzb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.9152youxi.cn/Article/details/gtmhzhefgl.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhaomingkeji.xyz/Article/details/gteagyktcy.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gteocxpeyf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.nwbrower.top/Article/details/gtneurteqz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yj202588.top/Article/details/gtdvaxlopg.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gtzgmnpiho.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.gaohongyu789.top/Article/details/gtfjczozlq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.bjfxy.top/Article/details/gtuaosowae.html

[E19] 多行文本按行拆分
来源：http://dali.yonumen.top/Article/details/gtnvdjlrpt.html

Py:   s.splitlines()
来源：http://dali.wangshuangyany.cn/Article/details/gttgdmedou.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.daxiang520.top/Article/details/gtvktwpxyk.html

JS:   s.split(/\r?\n/)
来源：http://dali.mhx1999.top/Article/details/gtyocogotu.html

TS:   s.split(/\r?\n/)
来源：http://dali.guannengcc.top/Article/details/gtmzuyzbay.html

Java: s.lines().toList()
来源：http://dali.hnxiangtu.top/Article/details/gtxqufncil.html

Go:   strings.Split(s, "\n")
来源：http://dali.sweek.top/Article/details/gtlwoqlndp.html

Ruby: s.lines
来源：http://dali.9152youxi.cn/Article/details/gtdwhwwqlk.html

C#:   s.Split('\n')
来源：http://dali.jlsjyb.cn/Article/details/gtrzytdqvt.html

[E20] 判断字符串是否为空
来源：http://dali.hammf.cn/Article/details/gtxfhnbalo.html

Py:   if not s:
来源：http://dali.tian-w.cn/Article/details/gtyfckpjux.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.dashuyun.cn/Article/details/gtroyqvgzf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jiagoushi.top/Article/details/gtwnjlbygf.html

TS:   if (s === "") {}
来源：http://dali.zhengqikj.top/Article/details/gtehzthzwh.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtujzacfdu.html

Go:   if s == "" {}
来源：http://dali.yueranfly.top/Article/details/gtqarinkyx.html

Ruby: if s.empty?
来源：http://dali.yangfankeji.com/Article/details/gtsoymoytn.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hfpthk.cn/Article/details/gtifdqkahq.html

[E21] 超长截断加省略号
来源：http://dali.yj20258888.top/Article/details/gtmpjmsxkq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xinyue.icu/Article/details/gtcbjtayry.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gtoqxliohu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gtxakzpqwh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daria6918.cn/Article/details/gtdmhkcktw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gtnfzqeijg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.316326.xyz/Article/details/gteadnazsq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gtjbznoawp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gtfjmjtdus.html

[E22] 字节长度与字符长度
来源：http://dali.xuetiantiany.cn/Article/details/gtejvlflyi.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sweek.top/Article/details/gtrrkkicay.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj202588.top/Article/details/gtghfjfyji.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xylfe.cn/Article/details/gtosesdbto.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sweek.top/Article/details/gtkzkngzoa.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jianghu66.top/Article/details/gtbbelpzbo.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.smart0.xyz/Article/details/gtkhpbzqac.html

Ruby: s.bytesize;  s.length
来源：http://dali.hnqzz.top/Article/details/gtfljlqllw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.chenlongwang.top/Article/details/gtebhazjlq.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gthblfxkvv.html

F. 文件与目录
来源：http://dali.wangshuangyany.cn/Article/details/gtfxtvpdug.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtzycxnwmu.html

[F01] 读取整个文件
来源：http://dali.aizwys.cn/Article/details/gtieyoxcci.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhiwuduotai.top/Article/details/gtglqrpvhr.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtxdtoagwd.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yueranfly.top/Article/details/gtommrsbbt.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xziqi.cn/Article/details/gtikplkmvc.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gtwpvdhywp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.guannengcc.top/Article/details/gtawnprafu.html

Ruby: File.read("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtaqeopmdv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.316326.xyz/Article/details/gtazxxcdhd.html

[F02] 逐行读取文件
来源：http://dali.jlsjyb.cn/Article/details/gtatefhnik.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.guannengcc.top/Article/details/gtnzrefpmy.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jqgfzy.top/Article/details/gtmztisigz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuanzx.com/Article/details/gtizeavqvz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tanke756.top/Article/details/gthohnpobf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.havefunace.top/Article/details/gtlhvvjnlr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.guannengcc.top/Article/details/gtsvktapko.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.tianlin.xyz/Article/details/gtpyujnfzm.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hysaishi.cn/Article/details/gthgbqbxyn.html

[F03] 写入文件（覆盖）
来源：http://dali.daria6918.cn/Article/details/gtmcbluymg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.redwolf501.top/Article/details/gtfibpotjm.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hammf.cn/Article/details/gtzlnmjcdw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guannengcc.top/Article/details/gtoiudbfgl.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zdqjudy.top/Article/details/gtecjlfqfd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hysaishi.cn/Article/details/gtirpgakxy.html


<!-- 参考信息 -->