代发 wailian999

[D19] 按字段分组
来源：http://dali.birdmap.top/Article/details/gt2nzsdozae.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sufxvd.cn/Article/details/gt2qnanbsav.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yuxming.cn/Article/details/gt2suwfplch.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.tian-w.cn/Article/details/gt2aypniotl.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.pengpengdd.cyou/Article/details/gt2emwwnnqd.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xziqi.cn/Article/details/gt2sbcyoumx.html

Go:   // 手写 map[string][]T
来源：http://dali.bjfxy.top/Article/details/gt2nwdgdwsi.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.birdmap.top/Article/details/gt2lhifddxh.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cheryme.top/Article/details/gt2iacblpxd.html

[D20] 统计每个元素出现次数
来源：http://dali.vqdsnc.cn/Article/details/gt2ugzhaypo.html

Py:   Counter(arr)
来源：http://dali.redwolf501.top/Article/details/gt2goaribjp.html

PHP:  array_count_values($arr);
来源：http://dali.hnxiangtu.top/Article/details/gt2edmkgzog.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jiagoushi.top/Article/details/gt2gcvzxchc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yvedp.cn/Article/details/gt2whzcqhbw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jyoumei.cn/Article/details/gt2jlfhlgnm.html

Go:   // 手写 map[T]int
来源：http://dali.chenlongwang.top/Article/details/gt2xgfrjlsn.html

Ruby: arr.tally
来源：http://dali.bjfxy.top/Article/details/gt2kcsugfka.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sxryk.cn/Article/details/gt2pnirmuxk.html

[D21] 判断是否包含某元素
来源：http://dali.gaohongyu789.top/Article/details/gt2zdozbhed.html

Py:   x in arr
来源：http://dali.cheryme.top/Article/details/gt2nvjvfndb.html

PHP:  in_array($x, $arr, true);
来源：http://dali.0kj1m.cn/Article/details/gt2kbhnmtjy.html

JS:   arr.includes(x)
来源：http://dali.gaohongyu789.top/Article/details/gt2ogofkydb.html

TS:   arr.includes(x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2mcnoimop.html

Java: list.contains(x)
来源：http://dali.zhengqikj.top/Article/details/gt2bcjkplto.html

Go:   slices.Contains(arr, x)
来源：http://dali.sxryk.cn/Article/details/gt2vqdjxfrx.html

Ruby: arr.include?(x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2iyzonosp.html

C#:   list.Contains(x)
来源：http://dali.hfpthk.cn/Article/details/gt2wfltmpqc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.feifeiyinyue.top/Article/details/gt2vljjowci.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yonumen.top/Article/details/gt2tkchsgeb.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jinqigfzy.top/Article/details/gt2noselfjq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hysaishi.cn/Article/details/gt2bpyxitzq.html

TS:   [...arr];
来源：http://dali.shuidangran.top/Article/details/gt2tghuydqv.html

Java: new ArrayList<>(list);
来源：http://dali.nwbrower.top/Article/details/gt2ecptsjxs.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pgkxdqax.html

Ruby: arr.dup;  arr.clone
来源：http://dali.316326.xyz/Article/details/gt2rgjusdgu.html

C#:   new List<int>(list);
来源：http://dali.jyoumei.cn/Article/details/gt2lhyyhgmy.html

[D23] reduce 累积计算
来源：http://dali.iojbl.cn/Article/details/gt2tvxspjxn.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xinyue.icu/Article/details/gt2evhjeopp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.pengpengdd.cyou/Article/details/gt2fpnbmxqi.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jiagoushi.top/Article/details/gt2ojzxruay.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhengqikj.top/Article/details/gt2vvfnrejw.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.andypj.xyz/Article/details/gt2gkphzlro.html

Go:   // 手写循环
来源：http://dali.ydzc1.top/Article/details/gt2gnbymwfp.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.9152youxi.cn/Article/details/gt2ialkattv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2qmbfpbtt.html

[D24] 字典 / Map 基本操作
来源：http://dali.sufxvd.cn/Article/details/gt2byojdykg.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2laltnqsd.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.dianchejie.cn/Article/details/gt2nvlclyhh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yj20258.top/Article/details/gt2prbgggzq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.gogol.net.cn/Article/details/gt2duqlycjc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xylfe.cn/Article/details/gt2wiivxobz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2iyuvbsdq.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sysykeji.top/Article/details/gt2zolkubxr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hnxiangtu.top/Article/details/gt2qiixfsni.html

[D25] Set 集合去重与交并差
来源：http://dali.gzhubu.top/Article/details/gt2gxljelfj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.fengsongda.top/Article/details/gt2vttpwfbw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pcrufslh.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.gogol.net.cn/Article/details/gt2ootxnxrk.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhixingplan.top/Article/details/gt2tmqtbrit.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2fmyogswr.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.gzhubu.top/Article/details/gt2oavoyuia.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jiagoushi.top/Article/details/gt2pxosqjef.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.guowangkeji.top/Article/details/gt2ddnjgdjl.html

[D26] 数组转字符串
来源：http://dali.xuanzx.com/Article/details/gt2vyxvklle.html

Py:   ", ".join(map(str, arr))
来源：http://dali.fzhhl.top/Article/details/gt2uwvwhhzd.html

PHP:  implode(", ", $arr);
来源：http://dali.shuidangran.top/Article/details/gt2jyszicrd.html

JS:   arr.join(", ")
来源：http://dali.sysykeji.top/Article/details/gt2igwetoon.html

TS:   arr.join(", ")
来源：http://dali.jqgufenzy.top/Article/details/gt2vimlggmw.html

Java: String.join(", ", list)
来源：http://dali.gaohongyu789.top/Article/details/gt2jatbhwvt.html

Go:   strings.Join(strs, ", ")
来源：http://dali.quarkkingdee.top/Article/details/gt2iekgykcl.html

Ruby: arr.join(", ")
来源：http://dali.dashuyun.cn/Article/details/gt2ylvdmupe.html

C#:   string.Join(", ", list)
来源：http://dali.quarkkingdee.top/Article/details/gt2oyzrdujn.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2psmtzujn.html

E. 字符串处理
来源：http://dali.yuanzhike.top/Article/details/gt2vmfddhlv.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2xgndkwdx.html

[E01] 拼接字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2nxoeltdi.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hywenlv.cn/Article/details/gt2pfpbcjrp.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.wangdashe.top/Article/details/gt2xfpytvff.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gaohongyu789.top/Article/details/gt2rqiqkuiw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shuidangran.top/Article/details/gt2nsfswgbi.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yvedp.cn/Article/details/gt2kmaacttu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhiwuduotai.top/Article/details/gt2knqkgusl.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yuanzhike.top/Article/details/gt2fnjkpcym.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gt2reocdqac.html

[E02] 重复字符串
来源：http://dali.fengsongda.top/Article/details/gt2deigmimx.html

Py:   "ab" * 3
来源：http://dali.ehwqpu.com/Article/details/gt2acydciyq.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqshxymu.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkspelyx.html

TS:   "ab".repeat(3)
来源：http://dali.hnqzz.top/Article/details/gt2oeahuelt.html

Java: "ab".repeat(3)
来源：http://dali.nanxuanxn.top/Article/details/gt2cjkofpcy.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.tanke756.top/Article/details/gt2ydqoxngh.html

Ruby: "ab" * 3
来源：http://dali.quarkkingdee.top/Article/details/gt2phbvkmqt.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.daria6918.cn/Article/details/gt2owxrjxaf.html

[E03] 截取子串
来源：http://dali.c1oappe.top/Article/details/gt2mrwkwjmh.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yuanzhike.top/Article/details/gt2kaijcnfk.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jinqigufen.top/Article/details/gt2fwebscis.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hnqzz.top/Article/details/gt2faxmwrpe.html

TS:   s.slice(1, 4)
来源：http://dali.xuanzx.com/Article/details/gt2oagfikac.html

Java: s.substring(1, 4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rjdujkvp.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hfpthk.cn/Article/details/gt2onlavduk.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cucudq.cn/Article/details/gt2hqoojbie.html

C#:   s.Substring(1, 3)
来源：http://dali.jinqigfzy.top/Article/details/gt2kfjlqfzw.html

[E04] 查找子串位置
来源：http://dali.jianghu66.top/Article/details/gt2znhgelhr.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hfpthk.cn/Article/details/gt2tybjxeit.html

PHP:  strpos($s, "x");
来源：http://dali.yvedp.cn/Article/details/gt2impckjrj.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cqqwz.cn/Article/details/gt2dvhmrmwj.html

TS:   s.indexOf("x")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ydrajlft.html

Java: s.indexOf("x")
来源：http://dali.feifeiyinyue.top/Article/details/gt2zdpzytvv.html

Go:   strings.Index(s, "x")
来源：http://dali.jyoumei.cn/Article/details/gt2zdbvucyl.html

Ruby: s.index("x")
来源：http://dali.jlsjyb.cn/Article/details/gt2xdfjxvgd.html

C#:   s.IndexOf("x")
来源：http://dali.guowangkeji.top/Article/details/gt2sqcmqwtc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hongshengwenyu.top/Article/details/gt2tzgxsqmf.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.dashuyun.cn/Article/details/gt2mwahtsmm.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cucudq.cn/Article/details/gt2mswwheae.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ryrgxqss.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cheryme.top/Article/details/gt2sfphtqou.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.vqdsnc.cn/Article/details/gt2tmqnpdyi.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hdrddsot.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cashguo.top/Article/details/gt2rxmlydyl.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jiagoushi.top/Article/details/gt2qdfheyrl.html

[E06] 替换子串
来源：http://dali.nanxinkj.top/Article/details/gt2mcegeyjh.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hysaishi.cn/Article/details/gt2olpwnkjj.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.snrcjt.cn/Article/details/gt2ushxqraa.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gt2hvngysiy.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ivvv.top/Article/details/gt2kpipozmi.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gdyraaas.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tpmjflrm.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gt2zgmgbbbj.html

C#:   s.Replace("a", "b")
来源：http://dali.fengsongda.top/Article/details/gt2toietkuv.html

[E07] 按分隔符拆分
来源：http://dali.tianlin.xyz/Article/details/gt2vjqldfmq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.shanyushiyangtech.top/Article/details/gt2upojhtle.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zycfv.cn/Article/details/gt2qsbvvnlf.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.gotoacloud.top/Article/details/gt2gnzxseiy.html

TS:   s.split(",")
来源：http://dali.hfpthk.cn/Article/details/gt2zpudfqbv.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.quarkkingdee.top/Article/details/gt2bgnxbdoi.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xziqi.cn/Article/details/gt2qktnqzze.html

Ruby: s.split(",");  s.split
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dphfyqaw.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yvedp.cn/Article/details/gt2swsrrwky.html

[E08] 数组按分隔符合并
来源：http://dali.jqgufenzy.top/Article/details/gt2mljshbhi.html

Py:   ",".join(items)
来源：http://dali.tianlin.xyz/Article/details/gt2ttneumni.html

PHP:  implode(",", $items);
来源：http://dali.hywenlv.cn/Article/details/gt2hiwxmilr.html

JS:   items.join(",")
来源：http://dali.yvedp.cn/Article/details/gt2qevndvtv.html

TS:   items.join(",")
来源：http://dali.tian-w.cn/Article/details/gt2vwvvsdhi.html

Java: String.join(",", items)
来源：http://dali.jiagoushi.top/Article/details/gt2onblnssu.html

Go:   strings.Join(items, ",")
来源：http://dali.aibaodan.cn/Article/details/gt2awiddcqf.html

Ruby: items.join(",")
来源：http://dali.yj20258888.top/Article/details/gt2ycmmjqnx.html

C#:   string.Join(",", items)
来源：http://dali.birdmap.top/Article/details/gt2gujmohbt.html

[E09] 去除所有空白字符
来源：http://dali.hywenlv.cn/Article/details/gt2vromrhog.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xylfe.cn/Article/details/gt2pgyoujkj.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.0kj1m.cn/Article/details/gt2jjqirhfo.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xylfe.cn/Article/details/gt2cgapgbch.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dxvodtcn.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.mhx1999.top/Article/details/gt2jiutlilo.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shuidangran.top/Article/details/gt2yvwutpiq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sweek.top/Article/details/gt2cpqngouu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jyoumei.cn/Article/details/gt2jccscatg.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yvofkmwh.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xziqi.cn/Article/details/gt2einyjbhc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ybcxt.top/Article/details/gt2dpgjxpxm.html

JS:   "7".padStart(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gt2tfrykniy.html

TS:   "7".padStart(3, "0")
来源：http://dali.aibaodan.cn/Article/details/gt2habkwoqp.html

Java: String.format("%03d", 7)
来源：http://dali.nanxuanxn.top/Article/details/gt2igrfnudu.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uucilqxw.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shangyingyoupin.top/Article/details/gt2fvcnvcwv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinqigfzy.top/Article/details/gt2yooderge.html

[E11] 反转字符串
来源：http://dali.0kj1m.cn/Article/details/gt2usyfinbk.html

Py:   s[::-1]
来源：http://dali.jiagoushi.top/Article/details/gt2jwdxavqj.html

PHP:  strrev($s);
来源：http://dali.yj20258.top/Article/details/gt2lzznbjcq.html

JS:   [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gt2wiswnvei.html

TS:   [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gt2paebwesc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.pycfn.com/Article/details/gt2kfyrcxae.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.chenzaomai.com/Article/details/gt2edernlwp.html

Ruby: s.reverse
来源：http://dali.guowangkeji.top/Article/details/gt2lgwpwvoc.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.wangdashe.top/Article/details/gt2hiutieok.html

[E12] 统计某字符出现次数
来源：http://dali.hfpthk.cn/Article/details/gt2qjnhthqu.html

Py:   s.count("a")
来源：http://dali.kuanghao11.cn/Article/details/gt2xhqvgcws.html

PHP:  substr_count($s, "a");
来源：http://dali.pycfn.com/Article/details/gt2zprfwbqb.html

JS:   s.split("a").length - 1
来源：http://dali.nanxinkj.top/Article/details/gt2jtdszzta.html

TS:   s.split("a").length - 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2giwerwdx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.nanxuanxn.top/Article/details/gt2ifbeiosk.html

Go:   strings.Count(s, "a")
来源：http://dali.gaohongyu789.top/Article/details/gt2hevfoydj.html

Ruby: s.count("a")
来源：http://dali.snrcjt.cn/Article/details/gt2bvhahqoh.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yuanzhike.top/Article/details/gt2amywfnmi.html

[E13] 逐字符遍历
来源：http://dali.yj20258888.top/Article/details/gt2qqrmzfwe.html

Py:   for ch in s: print(ch)
来源：http://dali.havefunace.top/Article/details/gt2emqvynil.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gotoacloud.top/Article/details/gt2htindemx.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guannengcc.top/Article/details/gt2tnmmzpdz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhoulong.xyz/Article/details/gt2nyznjmhf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yongpay.top/Article/details/gt2udhmcaxq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.fengsongda.top/Article/details/gt2kexqbsjd.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yongpay.top/Article/details/gt2strueoat.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.havefunace.top/Article/details/gt2tdoptiat.html

[E14] URL 编码与 Base64
来源：http://dali.nwbrower.top/Article/details/gt2qbieilaa.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.pycfn.com/Article/details/gt2xplrvuom.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hammf.cn/Article/details/gt2zmvxtrqy.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cashguo.top/Article/details/gt2mjkxvkay.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ebbizbja.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.tanke756.top/Article/details/gt2ydwkycer.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ihkdiwxg.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.aibaodan.cn/Article/details/gt2lmdlvuhv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sufxvd.cn/Article/details/gt2riusyglg.html

[E15] HTML 转义 / 反转义
来源：http://dali.cashguo.top/Article/details/gt2amfeeafc.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.smart0.xyz/Article/details/gt2woimikns.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.andypj.xyz/Article/details/gt2wjhrfrhi.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tofgdiyb.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xjmeufbo.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xylfe.cn/Article/details/gt2vwgfjqac.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2edpjxudq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jyoumei.cn/Article/details/gt2ewuqtqrp.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhengqikj.top/Article/details/gt2ncrmjppm.html

[E16] 数字千分位
来源：http://dali.ppjwa.cn/Article/details/gt2cjtjjpnf.html

Py:   f"{1234567:,}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hauhgzjg.html

PHP:  number_format(1234567);
来源：http://dali.jianghu66.top/Article/details/gt2vimoiqll.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.wangdashe.top/Article/details/gt2ktlnvgkq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.iojbl.cn/Article/details/gt2ndpztnbh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mzqopcrr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2agzcqvcc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cqqwz.cn/Article/details/gt2anrrdgca.html

C#:   1234567.ToString("N0")
来源：http://dali.shuidangran.top/Article/details/gt2jvynkbkk.html

[E17] 首字母大写
来源：http://dali.jqgufenzy.top/Article/details/gt2ozkhkrmx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xuanzx.com/Article/details/gt2exoedpsg.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.pycfn.com/Article/details/gt2yviboejn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.wangdashe.top/Article/details/gt2vqccnzuv.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cashguo.top/Article/details/gt2lbdjyifn.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.andypj.xyz/Article/details/gt2riaasmqt.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.chenzaomai.com/Article/details/gt2kmklpgpx.html

Ruby: s.capitalize
来源：http://dali.tanke756.top/Article/details/gt2qnwsufaz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xanxmbak.html

[E18] 模板占位符替换
来源：http://dali.316326.xyz/Article/details/gt2nnuakkox.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.pycfn.com/Article/details/gt2odyneego.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.fengsongda.top/Article/details/gt2kjqvgbar.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2itgucauk.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.tian-w.cn/Article/details/gt2xyjmygmz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ppjwa.cn/Article/details/gt2hzvopqgk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gt2qymmwhfu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jyoumei.cn/Article/details/gt2yuwalkdz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.guowangkeji.top/Article/details/gt2fzsqpeku.html

[E19] 多行文本按行拆分
来源：http://dali.yuxming.cn/Article/details/gt2yjxsclvz.html

Py:   s.splitlines()
来源：http://dali.jqgfzy.top/Article/details/gt2zpjdncfi.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gt2vgqqyqho.html

JS:   s.split(/\r?\n/)
来源：http://dali.kuanghao11.cn/Article/details/gt2sjscdwhz.html

TS:   s.split(/\r?\n/)
来源：http://dali.hnxiangtu.top/Article/details/gt2nsoobcpd.html

Java: s.lines().toList()
来源：http://dali.jinqigfzy.top/Article/details/gt2mlubahlo.html

Go:   strings.Split(s, "\n")
来源：http://dali.shuidangran.top/Article/details/gt2vjjqwizt.html

Ruby: s.lines
来源：http://dali.snrcjt.cn/Article/details/gt2cguilrca.html

C#:   s.Split('\n')
来源：http://dali.dianchejie.cn/Article/details/gt2tquftsou.html

[E20] 判断字符串是否为空
来源：http://dali.yueranfly.top/Article/details/gt2wxocvzik.html

Py:   if not s:
来源：http://dali.jqgfzy.top/Article/details/gt2pyqemimd.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hnqzz.top/Article/details/gt2rhudwdom.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.andypj.xyz/Article/details/gt2ouzbeaqr.html

TS:   if (s === "") {}
来源：http://dali.fzhhl.top/Article/details/gt2eiqhwrvz.html

Java: if (s.isEmpty()) {}
来源：http://dali.9152youxi.cn/Article/details/gt2yvmdyujr.html

Go:   if s == "" {}
来源：http://dali.fzhhl.top/Article/details/gt2wikfbgak.html

Ruby: if s.empty?
来源：http://dali.smart0.xyz/Article/details/gt2nwosudhm.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2evhaexin.html

[E21] 超长截断加省略号
来源：http://dali.jlsjyb.cn/Article/details/gt2pcsxcsrs.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cheryme.top/Article/details/gt2bmiqrjkg.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinqigufen.top/Article/details/gt2gkietotf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xziqi.cn/Article/details/gt2vgqwqdfk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258.top/Article/details/gt2wzxbpcll.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sweek.top/Article/details/gt2pmrxtukk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.andypj.xyz/Article/details/gt2stcqvuom.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gt2zculoyhs.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.sweek.top/Article/details/gt2sidqexqi.html

[E22] 字节长度与字符长度
来源：http://dali.zhengqikj.top/Article/details/gt2vdhfqrop.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2dqrlsjqu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gt2vmudmsuf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jiagoushi.top/Article/details/gt2jtbnkggp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.kuanghao11.cn/Article/details/gt2yklyggpo.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gogol.net.cn/Article/details/gt2xyfzsfsw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.tian-w.cn/Article/details/gt2zuxdymge.html

Ruby: s.bytesize;  s.length
来源：http://dali.tanke756.top/Article/details/gt2ahczbkuq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sweek.top/Article/details/gt2ohisjryu.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2hxqarite.html

F. 文件与目录
来源：http://dali.tanke756.top/Article/details/gt2lcdpuhaa.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uopadspp.html

[F01] 读取整个文件
来源：http://dali.yuanzhike.top/Article/details/gt2tpvtblcx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shangyingyoupin.top/Article/details/gt2xpmafubu.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gt2dbenmqil.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sxryk.cn/Article/details/gt2yihnjyet.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gotoacloud.top/Article/details/gt2cgxwwwyt.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gt2dyvjqoas.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.9152youxi.cn/Article/details/gt2eskdcxcs.html

Ruby: File.read("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jmwhnbdc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.meibo888.top/Article/details/gt2jymahqjo.html

[F02] 逐行读取文件
来源：http://dali.hfpthk.cn/Article/details/gt2aauhihbu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.mhx1999.top/Article/details/gt2cpypjskz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zycfv.cn/Article/details/gt2ekvmxsgi.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xylfe.cn/Article/details/gt2rvjppolk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pycfn.com/Article/details/gt2hkpsgsft.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.redwolf501.top/Article/details/gt2qkdpvtlm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.dianchejie.cn/Article/details/gt2ovhuvlfn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.sxryk.cn/Article/details/gt2hxpuayii.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ydzc1.top/Article/details/gt2mzusmwvh.html

[F03] 写入文件（覆盖）
来源：http://dali.guannengcc.top/Article/details/gt2uqyxvfdz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.dashuyun.cn/Article/details/gt2abhcldwo.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jqgfzy.top/Article/details/gt2giclhrox.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tanke756.top/Article/details/gt2awspxpcr.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yueranfly.top/Article/details/gt2uvlartnv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.bjfxy.top/Article/details/gt2quepbome.html


<!-- 参考信息 -->