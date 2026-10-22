代发 wailian999

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258888.top/Article/details/gt2migssuaf.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xylfe.cn/Article/details/gt2bpjjtcqt.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.dianchejie.cn/Article/details/gt2gbffrbay.html

Go:   // 手写 map[T]int
来源：http://dali.mhx1999.top/Article/details/gt2pibdlfgt.html

Ruby: arr.tally
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kiuweejo.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.aibaodan.cn/Article/details/gt2fgnkmuxy.html

[D21] 判断是否包含某元素
来源：http://dali.gzhubu.top/Article/details/gt2raxpyyos.html

Py:   x in arr
来源：http://dali.shzxlz.cn/Article/details/gt2ojhwahgf.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yuxming.cn/Article/details/gt2copojhjc.html

JS:   arr.includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gjntnpny.html

TS:   arr.includes(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kuykpmah.html

Java: list.contains(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2bdnardan.html

Go:   slices.Contains(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gt2mumiobjt.html

Ruby: arr.include?(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2lvjrfcud.html

C#:   list.Contains(x)
来源：http://dali.c1oappe.top/Article/details/gt2aeirxsuy.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhiwuduotai.top/Article/details/gt2nvskqaqn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.316326.xyz/Article/details/gt2qxhmucwn.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.vqdsnc.cn/Article/details/gt2ibihqohn.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jinqigufen.top/Article/details/gt2flazlcxu.html

TS:   [...arr];
来源：http://dali.yueranfly.top/Article/details/gt2mhoogxwc.html

Java: new ArrayList<>(list);
来源：http://dali.yangfankeji.com/Article/details/gt2iapfusyq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.sysykeji.top/Article/details/gt2poqdjnfs.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jqgufenzy.top/Article/details/gt2daqmibpq.html

C#:   new List<int>(list);
来源：http://dali.zdqjudy.top/Article/details/gt2zmqxefzn.html

[D23] reduce 累积计算
来源：http://dali.ehwqpu.com/Article/details/gt2tmhlvvvh.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yongpay.top/Article/details/gt2oihjselo.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zdqjudy.top/Article/details/gt2conbqjaf.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.quarkkingdee.top/Article/details/gt2egzchhxl.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tanke756.top/Article/details/gt2sqiywdmc.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.aizwys.cn/Article/details/gt2ikpulzla.html

Go:   // 手写循环
来源：http://dali.sweek.top/Article/details/gt2lpwkyyni.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shzxlz.cn/Article/details/gt2khdboyew.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jqgfzy.top/Article/details/gt2ppekfllh.html

[D24] 字典 / Map 基本操作
来源：http://dali.ivvv.top/Article/details/gt2opwcsqgi.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cdnleiting.top/Article/details/gt2qyfnccsn.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qnkidwvo.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.daria6918.cn/Article/details/gt2sjjgyvdr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jinqigufen.top/Article/details/gt2xbwjejbc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhengqikj.top/Article/details/gt2zkugmika.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kbsaujpw.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yj202588.top/Article/details/gt2kslydrjq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.chenjidiqi.icu/Article/details/gt2ifqecvil.html

[D25] Set 集合去重与交并差
来源：http://dali.redwolf501.top/Article/details/gt2sxsljcll.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.nwbrower.top/Article/details/gt2mqxpgbds.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cqqwz.cn/Article/details/gt2fjvjfwxf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yj20258888.top/Article/details/gt2hyssiqct.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.0kj1m.cn/Article/details/gt2ybbdjjqr.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2btzosfji.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.meibo888.top/Article/details/gt2nfqrttkn.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.guannengcc.top/Article/details/gt2wrawvgcv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.316326.xyz/Article/details/gt2dxyavvex.html

[D26] 数组转字符串
来源：http://dali.hammf.cn/Article/details/gt2jqhwjalm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hnxiangtu.top/Article/details/gt2wlujkxkf.html

PHP:  implode(", ", $arr);
来源：http://dali.yuxming.cn/Article/details/gt2wpbgabei.html

JS:   arr.join(", ")
来源：http://dali.xuetiantiany.cn/Article/details/gt2zwvekeqp.html

TS:   arr.join(", ")
来源：http://dali.iojbl.cn/Article/details/gt2kzfaijtr.html

Java: String.join(", ", list)
来源：http://dali.jlsjyb.cn/Article/details/gt2rlawspdy.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hnqzz.top/Article/details/gt2mpxfipua.html

Ruby: arr.join(", ")
来源：http://dali.dashuyun.cn/Article/details/gt2sfgerukz.html

C#:   string.Join(", ", list)
来源：http://dali.pengpengdd.cyou/Article/details/gt2nbtzpcoy.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2dxozowrt.html

E. 字符串处理
来源：http://dali.sxryk.cn/Article/details/gt2jywqtctc.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2cqgrfkow.html

[E01] 拼接字符串
来源：http://dali.wangshuangyany.cn/Article/details/gt2ncnygnpz.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.bjfxy.top/Article/details/gt2koghtjjk.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.gogol.net.cn/Article/details/gt2oujdrahl.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nwbrower.top/Article/details/gt2utlwcgvo.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.mhx1999.top/Article/details/gt2dtkheqli.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.fengsongda.top/Article/details/gt2kfutvjve.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xuetiantiany.cn/Article/details/gt2uwkurqzk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jyoumei.cn/Article/details/gt2lldqkllh.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yj20258888.top/Article/details/gt2gcohdnju.html

[E02] 重复字符串
来源：http://dali.jqgfzy.top/Article/details/gt2liyvmppy.html

Py:   "ab" * 3
来源：http://dali.hnxiangtu.top/Article/details/gt2wlfnphhb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.fengsongda.top/Article/details/gt2euvlmhql.html

JS:   "ab".repeat(3)
来源：http://dali.xuanzx.com/Article/details/gt2kjmzuwcp.html

TS:   "ab".repeat(3)
来源：http://dali.mhx1999.top/Article/details/gt2umgdnruu.html

Java: "ab".repeat(3)
来源：http://dali.yj20258888.top/Article/details/gt2henjmdtr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.haohaochexian.top/Article/details/gt2xarreexe.html

Ruby: "ab" * 3
来源：http://dali.zhengqikj.top/Article/details/gt2gksfzmbh.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zhsfhbug.html

[E03] 截取子串
来源：http://dali.aibaodan.cn/Article/details/gt2gsbsokjt.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zdqjudy.top/Article/details/gt2zojhrfvr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gt2pclmflij.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nlfmncwn.html

TS:   s.slice(1, 4)
来源：http://dali.zhengqikj.top/Article/details/gt2veobnhxf.html

Java: s.substring(1, 4)
来源：http://dali.jyoumei.cn/Article/details/gt2htuhxxzj.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.guannengcc.top/Article/details/gt2gbaxdhvd.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ybcxt.top/Article/details/gt2tihnayko.html

C#:   s.Substring(1, 3)
来源：http://dali.hammf.cn/Article/details/gt2hoenwpyc.html

[E04] 查找子串位置
来源：http://dali.havefunace.top/Article/details/gt2chgdncgg.html

Py:   s.find("x");  s.index("x")
来源：http://dali.gotoacloud.top/Article/details/gt2otbclsyu.html

PHP:  strpos($s, "x");
来源：http://dali.gzhubu.top/Article/details/gt2vqocdewp.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lmjoijro.html

TS:   s.indexOf("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aeoulbze.html

Java: s.indexOf("x")
来源：http://dali.gzhubu.top/Article/details/gt2lrbpuhdc.html

Go:   strings.Index(s, "x")
来源：http://dali.yongpay.top/Article/details/gt2twcpfvir.html

Ruby: s.index("x")
来源：http://dali.ivvv.top/Article/details/gt2ocivpaps.html

C#:   s.IndexOf("x")
来源：http://dali.havefunace.top/Article/details/gt2ygkaoskg.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cheryme.top/Article/details/gt2gelwxyia.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.9152youxi.cn/Article/details/gt2hlxtgeaf.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cqqwz.cn/Article/details/gt2iokwfmpe.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oviytkhj.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.tian-w.cn/Article/details/gt2luwkkyye.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.aibaodan.cn/Article/details/gt2axaulrdt.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xtjsphjb.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhengqikj.top/Article/details/gt2brcvwolg.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tgfsojne.html

[E06] 替换子串
来源：http://dali.jianghu66.top/Article/details/gt2azwizvhz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.gotoacloud.top/Article/details/gt2jyuectch.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.snrcjt.cn/Article/details/gt2mvigduxv.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gt2dntxycub.html

TS:   s.replaceAll("a", "b")
来源：http://dali.bjfxy.top/Article/details/gt2yyytvanj.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gt2zouwqcfe.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jinqigfzy.top/Article/details/gt2jbczdbuw.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ivvv.top/Article/details/gt2hhjegsxv.html

C#:   s.Replace("a", "b")
来源：http://dali.daxiang520.top/Article/details/gt2unpujajf.html

[E07] 按分隔符拆分
来源：http://dali.cdnleiting.top/Article/details/gt2rsxbtyug.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.9152youxi.cn/Article/details/gt2dayvrpyk.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.fzhhl.top/Article/details/gt2htnpxvtb.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.andypj.xyz/Article/details/gt2toepecyn.html

TS:   s.split(",")
来源：http://dali.hywenlv.cn/Article/details/gt2ehrmplsn.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jianghu66.top/Article/details/gt2winpaedr.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gotoacloud.top/Article/details/gt2khhhyfjq.html

Ruby: s.split(",");  s.split
来源：http://dali.jinqigfzy.top/Article/details/gt2qdxzfjdu.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yueranfly.top/Article/details/gt2xsiziwfb.html

[E08] 数组按分隔符合并
来源：http://dali.jinqigfzy.top/Article/details/gt2lwillxcf.html

Py:   ",".join(items)
来源：http://dali.nanxinkj.top/Article/details/gt2vvrmropa.html

PHP:  implode(",", $items);
来源：http://dali.316326.xyz/Article/details/gt2gtvumalh.html

JS:   items.join(",")
来源：http://dali.chenzaomai.com/Article/details/gt2bovslslw.html

TS:   items.join(",")
来源：http://dali.guowangkeji.top/Article/details/gt2mfumwmud.html

Java: String.join(",", items)
来源：http://dali.gaohongyu789.top/Article/details/gt2rpxsrfbv.html

Go:   strings.Join(items, ",")
来源：http://dali.daxiang520.top/Article/details/gt2uzarxavb.html

Ruby: items.join(",")
来源：http://dali.hysaishi.cn/Article/details/gt2hgbcokai.html

C#:   string.Join(",", items)
来源：http://dali.wangdashe.top/Article/details/gt2edjtcylb.html

[E09] 去除所有空白字符
来源：http://dali.jyoumei.cn/Article/details/gt2srsjkgsh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ykwpgbnv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ivvv.top/Article/details/gt2nflzqfrx.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.aizwys.cn/Article/details/gt2fchbpsex.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.meibo888.top/Article/details/gt2citutgrx.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xuetiantiany.cn/Article/details/gt2antqwppq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.fengsongda.top/Article/details/gt2xoyrtxau.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.guannengcc.top/Article/details/gt2qyklbgnz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.andypj.xyz/Article/details/gt2fakleevj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.daxiang520.top/Article/details/gt2ekshnmvm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gt2gnlaqchn.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.0kj1m.cn/Article/details/gt2tpwrmvpy.html

JS:   "7".padStart(3, "0")
来源：http://dali.shuidangran.top/Article/details/gt2apkhiagl.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhiwuduotai.top/Article/details/gt2vtdszxtp.html

Java: String.format("%03d", 7)
来源：http://dali.cucudq.cn/Article/details/gt2epaiowpx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.quarkkingdee.top/Article/details/gt2vdryklsr.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.quarkkingdee.top/Article/details/gt2cfasvghh.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.nwbrower.top/Article/details/gt2bixxilgt.html

[E11] 反转字符串
来源：http://dali.yongpay.top/Article/details/gt2pfkouvro.html

Py:   s[::-1]
来源：http://dali.ehwqpu.com/Article/details/gt2aoiseshq.html

PHP:  strrev($s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2zdhnfcdt.html

JS:   [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ialnizxd.html

TS:   [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gt2ggihoxby.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.sysykeji.top/Article/details/gt2emaufeff.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.iojbl.cn/Article/details/gt2zpshcjod.html

Ruby: s.reverse
来源：http://dali.vqdsnc.cn/Article/details/gt2bdluzevj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.9152youxi.cn/Article/details/gt2uyhzfnjl.html

[E12] 统计某字符出现次数
来源：http://dali.zhongyouzk.top/Article/details/gt2qxociosg.html

Py:   s.count("a")
来源：http://dali.cdnleiting.top/Article/details/gt2vtjfskvt.html

PHP:  substr_count($s, "a");
来源：http://dali.sysykeji.top/Article/details/gt2rvaqgxns.html

JS:   s.split("a").length - 1
来源：http://dali.xylfe.cn/Article/details/gt2agrgzlug.html

TS:   s.split("a").length - 1
来源：http://dali.gogol.net.cn/Article/details/gt2ojawkbff.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hfpthk.cn/Article/details/gt2uoerkwgv.html

Go:   strings.Count(s, "a")
来源：http://dali.hongshengwenyu.top/Article/details/gt2mgjhimai.html

Ruby: s.count("a")
来源：http://dali.0kj1m.cn/Article/details/gt2chdazufd.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ivvv.top/Article/details/gt2bugaypng.html

[E13] 逐字符遍历
来源：http://dali.svipenyu.cn/Article/details/gt2tpmninqd.html

Py:   for ch in s: print(ch)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2csxzdtxz.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2wgandkiy.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuanzx.com/Article/details/gt2tkxxgpih.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xavaypcl.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xinyue.icu/Article/details/gt2encjcpgp.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wxfkszfb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hongshengwenyu.top/Article/details/gt2werlkvea.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rzrvowuj.html

[E14] URL 编码与 Base64
来源：http://dali.9152youxi.cn/Article/details/gt2amqcvosu.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.meibo888.top/Article/details/gt2baoycqob.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.snrcjt.cn/Article/details/gt2uqcdywtx.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xziqi.cn/Article/details/gt2urxaatkf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yvedp.cn/Article/details/gt2otoqmdsd.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sweek.top/Article/details/gt2fqpcbysd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cashguo.top/Article/details/gt2xaakmbik.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.bjfxy.top/Article/details/gt2ccooncxj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.vqdsnc.cn/Article/details/gt2ljekmwrq.html

[E15] HTML 转义 / 反转义
来源：http://dali.hfpthk.cn/Article/details/gt2ntqivhtq.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ehwqpu.com/Article/details/gt2fdhnvmfu.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yuxming.cn/Article/details/gt2mypnscdm.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.haohaochexian.top/Article/details/gt2axfjvlbz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zrbogigv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hongshengwenyu.top/Article/details/gt2tuoauppi.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2bgaecdwi.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2itwyxomi.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.meibo888.top/Article/details/gt2ssvqgrnj.html

[E16] 数字千分位
来源：http://dali.zhoulong.xyz/Article/details/gt2sftniqlt.html

Py:   f"{1234567:,}"
来源：http://dali.sxryk.cn/Article/details/gt2uepzcqcq.html

PHP:  number_format(1234567);
来源：http://dali.mhx1999.top/Article/details/gt2xqhonfoy.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.guannengcc.top/Article/details/gt2gpyngtok.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shzxlz.cn/Article/details/gt2fewxrlwq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2cehrxacq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.dashuyun.cn/Article/details/gt2dzhtrqwe.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nzyhrwjw.html

C#:   1234567.ToString("N0")
来源：http://dali.jiagoushi.top/Article/details/gt2tqripqrh.html

[E17] 首字母大写
来源：http://dali.sweek.top/Article/details/gt2hjnwxpha.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jqgufenzy.top/Article/details/gt2qxqirzif.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhongyouzk.top/Article/details/gt2txqbwdbg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.birdmap.top/Article/details/gt2niamndda.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zdqjudy.top/Article/details/gt2zzaczzce.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cucudq.cn/Article/details/gt2uhjsymdn.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rpnnhlve.html

Ruby: s.capitalize
来源：http://dali.hnxiangtu.top/Article/details/gt2pwrsfimh.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.dashuyun.cn/Article/details/gt2ttljrsfp.html

[E18] 模板占位符替换
来源：http://dali.ppjwa.cn/Article/details/gt2rywsmheg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ipkwgslk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.aizwys.cn/Article/details/gt2sssrpbul.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yueranfly.top/Article/details/gt2qtwkpwev.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gt2imadyvnv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.nanxuanxn.top/Article/details/gt2nuuccwge.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xziqi.cn/Article/details/gt2ahgklixr.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.snrcjt.cn/Article/details/gt2xilvmsrw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iuvkyepi.html

[E19] 多行文本按行拆分
来源：http://dali.chenzaomai.com/Article/details/gt2akozceef.html

Py:   s.splitlines()
来源：http://dali.ydzc1.top/Article/details/gt2tdwkaocq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gt2rdttjaef.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhongyouzk.top/Article/details/gt2vehwhklf.html

TS:   s.split(/\r?\n/)
来源：http://dali.tianlin.xyz/Article/details/gt2qvrdfxjq.html

Java: s.lines().toList()
来源：http://dali.shzxlz.cn/Article/details/gt2ohwoctcd.html

Go:   strings.Split(s, "\n")
来源：http://dali.cheryme.top/Article/details/gt2kspjlsrt.html

Ruby: s.lines
来源：http://dali.zdqjudy.top/Article/details/gt2ucssdrpy.html

C#:   s.Split('\n')
来源：http://dali.haohaochexian.top/Article/details/gt2txypfqsl.html

[E20] 判断字符串是否为空
来源：http://dali.xylfe.cn/Article/details/gt2ocxlnvbz.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2jmpdqfbn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.tianlin.xyz/Article/details/gt2snqfvzck.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhixingplan.top/Article/details/gt2phzwddzw.html

TS:   if (s === "") {}
来源：http://dali.haohaochexian.top/Article/details/gt2aadmaiqz.html

Java: if (s.isEmpty()) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2irtqomuw.html

Go:   if s == "" {}
来源：http://dali.nanxuanxn.top/Article/details/gt2tgzzfyky.html

Ruby: if s.empty?
来源：http://dali.iojbl.cn/Article/details/gt2purhcnmt.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.dianchejie.cn/Article/details/gt2vblkveey.html

[E21] 超长截断加省略号
来源：http://dali.pycfn.com/Article/details/gt2gzrhmlmq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.haohaochexian.top/Article/details/gt2nhxhouco.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gt2dmdnxamz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fouliiav.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gt2ujxvxuzd.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.redwolf501.top/Article/details/gt2tdrosega.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.birdmap.top/Article/details/gt2amjjnbyf.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gt2oxaaaqbi.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ivvv.top/Article/details/gt2utxqrpbf.html

[E22] 字节长度与字符长度
来源：http://dali.pengpengdd.cyou/Article/details/gt2hwybqqki.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yj202588.top/Article/details/gt2guwfsdxg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tian-w.cn/Article/details/gt2tpkipqrg.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.quarkkingdee.top/Article/details/gt2kgmvpebv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuetiantiany.cn/Article/details/gt2daqouavm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xinyue.icu/Article/details/gt2wudmjegg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.nanxinkj.top/Article/details/gt2fwphksit.html

Ruby: s.bytesize;  s.length
来源：http://dali.yj202588.top/Article/details/gt2kazolkjp.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.feifeiyinyue.top/Article/details/gt2jddyzhld.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2tptptvrs.html

F. 文件与目录
来源：http://dali.ybcxt.top/Article/details/gt2qbmqpakr.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2bvlsncur.html

[F01] 读取整个文件
来源：http://dali.yangfankeji.com/Article/details/gt2kzgnuosp.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xejqylqh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2spevtibw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hnqzz.top/Article/details/gt2hebwbrip.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.bjfxy.top/Article/details/gt2mmuqasfo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gt2qqkscypa.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yonumen.top/Article/details/gt2pqbfurhl.html

Ruby: File.read("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2mshtrkol.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2iptugrqa.html

[F02] 逐行读取文件
来源：http://dali.birdmap.top/Article/details/gt2rhrvblgj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hywenlv.cn/Article/details/gt2hnaiujcq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nklonazt.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgfzy.top/Article/details/gt2nsxvlmgo.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxinkj.top/Article/details/gt2gfutzlqi.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.pycfn.com/Article/details/gt2vzeeobim.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhongyouzk.top/Article/details/gt2vjdyficj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcpucslz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2qhtvncov.html

[F03] 写入文件（覆盖）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xdnvwexy.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.meibo888.top/Article/details/gt2elrzcios.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gt2njdfbnzb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ppewlncw.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.svipenyu.cn/Article/details/gt2gzzdkxmc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.andypj.xyz/Article/details/gt2paffctem.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.birdmap.top/Article/details/gt2tcynwxlk.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.fzhhl.top/Article/details/gt2ficzemve.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shuidangran.top/Article/details/gt2fkcgtxvu.html

[F04] 追加写入文件
来源：http://dali.vqdsnc.cn/Article/details/gt2vxgzbcrv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinqigfzy.top/Article/details/gt2tbyenyvo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.dashuyun.cn/Article/details/gt2oldqidnn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fzhhl.top/Article/details/gt2xtnagnsp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenzaomai.com/Article/details/gt2bwtycydl.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.meibo888.top/Article/details/gt2zldfbtwo.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2giwryduf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.fzhhl.top/Article/details/gt2fqpzfbxv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.smart0.xyz/Article/details/gt2xbbxgyvg.html


<!-- 参考信息 -->