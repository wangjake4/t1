代发 wailian999

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rmndgqsq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.vqdsnc.cn/Article/details/gt2hcvvgeji.html

Go:   // 手写 map[string][]T
来源：http://dali.c1oappe.top/Article/details/gt2ubgpkiac.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gaohongyu789.top/Article/details/gt2hfxojgex.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.nanxuanxn.top/Article/details/gt2ljbhgwoe.html

[D20] 统计每个元素出现次数
来源：http://dali.sysykeji.top/Article/details/gt2rdisyhrm.html

Py:   Counter(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2lemwbgnu.html

PHP:  array_count_values($arr);
来源：http://dali.gogol.net.cn/Article/details/gt2bnsxttsq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.9152youxi.cn/Article/details/gt2nsqhjjjg.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.smart0.xyz/Article/details/gt2bmphhgnv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xszuzzsd.html

Go:   // 手写 map[T]int
来源：http://dali.hongshengwenyu.top/Article/details/gt2pnzjvcoy.html

Ruby: arr.tally
来源：http://dali.yanxiufei.cn/Article/details/gt2ridypqvx.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.aibaodan.cn/Article/details/gt2shfgtpsg.html

[D21] 判断是否包含某元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rdfknxfy.html

Py:   x in arr
来源：http://dali.yuanzhike.top/Article/details/gt2pfohwtfa.html

PHP:  in_array($x, $arr, true);
来源：http://dali.redwolf501.top/Article/details/gt2bmxlwjhw.html

JS:   arr.includes(x)
来源：http://dali.xziqi.cn/Article/details/gt2tvavhrzz.html

TS:   arr.includes(x)
来源：http://dali.cdnleiting.top/Article/details/gt2jnlknwof.html

Java: list.contains(x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ocnpfsgs.html

Go:   slices.Contains(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gt2aufvljam.html

Ruby: arr.include?(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2bhioihly.html

C#:   list.Contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2fpityxox.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yvedp.cn/Article/details/gt2xmvdffob.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cheryme.top/Article/details/gt2clwowglb.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.cqqwz.cn/Article/details/gt2isastmya.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cqqwz.cn/Article/details/gt2lgjgzpky.html

TS:   [...arr];
来源：http://dali.gaohongyu789.top/Article/details/gt2rekbllvq.html

Java: new ArrayList<>(list);
来源：http://dali.pengpengdd.cyou/Article/details/gt2iymdwtfa.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ydzc1.top/Article/details/gt2mhmniopp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.0kj1m.cn/Article/details/gt2nuukliaj.html

C#:   new List<int>(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bcvgcxlo.html

[D23] reduce 累积计算
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mlgrxwzc.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ehwqpu.com/Article/details/gt2orfikvqy.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yj20258.top/Article/details/gt2volsgunm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhixingplan.top/Article/details/gt2xbjjpakt.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.iojbl.cn/Article/details/gt2xcnuihzz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ehwqpu.com/Article/details/gt2ysbeogsu.html

Go:   // 手写循环
来源：http://dali.316326.xyz/Article/details/gt2dstvkozh.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.nanxuanxn.top/Article/details/gt2ewbwtryt.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovclokep.html

[D24] 字典 / Map 基本操作
来源：http://dali.cqqwz.cn/Article/details/gt2qodpjjmo.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xziqi.cn/Article/details/gt2rgrbhrnx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.9152youxi.cn/Article/details/gt2pogcosxr.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.gogol.net.cn/Article/details/gt2chtrmkth.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jxqnhtjn.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.quarkkingdee.top/Article/details/gt2bevwfyma.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jianghu66.top/Article/details/gt2fzswuljo.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.birdmap.top/Article/details/gt2lngwkrlg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yanxiufei.cn/Article/details/gt2esvpfnzy.html

[D25] Set 集合去重与交并差
来源：http://dali.cucudq.cn/Article/details/gt2xosumlii.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.vqdsnc.cn/Article/details/gt2drzpxwax.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.sweek.top/Article/details/gt2kghycpcd.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.smart0.xyz/Article/details/gt2wcsdvodt.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hywenlv.cn/Article/details/gt2axhxowpj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.tianlin.xyz/Article/details/gt2scarvytw.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.snrcjt.cn/Article/details/gt2yefjiszg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.nanxuanxn.top/Article/details/gt2ljiwwwzh.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cqqwz.cn/Article/details/gt2fnplnicd.html

[D26] 数组转字符串
来源：http://dali.zhoulong.xyz/Article/details/gt2jkybfsgd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhongyouzk.top/Article/details/gt2opcrtvlo.html

PHP:  implode(", ", $arr);
来源：http://dali.nanxuanxn.top/Article/details/gt2drtbfkfa.html

JS:   arr.join(", ")
来源：http://dali.cashguo.top/Article/details/gt2wailtwpq.html

TS:   arr.join(", ")
来源：http://dali.cqqwz.cn/Article/details/gt2bheocyhw.html

Java: String.join(", ", list)
来源：http://dali.jlsjyb.cn/Article/details/gt2oiwibfrp.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sfmeuwgy.html

Ruby: arr.join(", ")
来源：http://dali.iojbl.cn/Article/details/gt2uawmwtiu.html

C#:   string.Join(", ", list)
来源：http://dali.jlsjyb.cn/Article/details/gt2iyyhqtnq.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2azlkmrti.html

E. 字符串处理
来源：http://dali.9152youxi.cn/Article/details/gt2vzajbvrh.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2qjmgajzj.html

[E01] 拼接字符串
来源：http://dali.ydzc1.top/Article/details/gt2yshjhdnq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2outocwoo.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yj20258888.top/Article/details/gt2zfgjryud.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.meibo888.top/Article/details/gt2ljnuxivq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.0kj1m.cn/Article/details/gt2gjmdiiak.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yangfankeji.com/Article/details/gt2fcwhxzvr.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.tianlin.xyz/Article/details/gt2crsojkjg.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ybcxt.top/Article/details/gt2bzdlaitg.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gt2vxffylue.html

[E02] 重复字符串
来源：http://dali.yangfankeji.com/Article/details/gt2xredljlk.html

Py:   "ab" * 3
来源：http://dali.zhengqikj.top/Article/details/gt2ldqmgzft.html

PHP:  str_repeat("ab", 3);
来源：http://dali.chenjidiqi.icu/Article/details/gt2oxqzrwyi.html

JS:   "ab".repeat(3)
来源：http://dali.dashuyun.cn/Article/details/gt2iufsjyhc.html

TS:   "ab".repeat(3)
来源：http://dali.nwbrower.top/Article/details/gt2jvuqloee.html

Java: "ab".repeat(3)
来源：http://dali.jlsjyb.cn/Article/details/gt2smqpqaru.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mdfzlgsz.html

Ruby: "ab" * 3
来源：http://dali.xinyue.icu/Article/details/gt2nfqjstfm.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.birdmap.top/Article/details/gt2iwyxxafa.html

[E03] 截取子串
来源：http://dali.gogol.net.cn/Article/details/gt2epvsntnq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.andypj.xyz/Article/details/gt2vyxvnuxp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.dianchejie.cn/Article/details/gt2jkbrbvzw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2uduqnxwo.html

TS:   s.slice(1, 4)
来源：http://dali.smart0.xyz/Article/details/gt2pkyshiyh.html

Java: s.substring(1, 4)
来源：http://dali.cashguo.top/Article/details/gt2wowojfgr.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gotoacloud.top/Article/details/gt2feyqueyh.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jinqigufen.top/Article/details/gt2gtbzabvd.html

C#:   s.Substring(1, 3)
来源：http://dali.xylfe.cn/Article/details/gt2gwhwkvpo.html

[E04] 查找子串位置
来源：http://dali.smart0.xyz/Article/details/gt2dndnlnid.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2mytddrsp.html

PHP:  strpos($s, "x");
来源：http://dali.jqgufenzy.top/Article/details/gt2ltxqioim.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jqgufenzy.top/Article/details/gt2phwkwxhe.html

TS:   s.indexOf("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uzqhfkvr.html

Java: s.indexOf("x")
来源：http://dali.vqdsnc.cn/Article/details/gt2gnlhfvlf.html

Go:   strings.Index(s, "x")
来源：http://dali.nwbrower.top/Article/details/gt2ztnvtnef.html

Ruby: s.index("x")
来源：http://dali.feifeiyinyue.top/Article/details/gt2dxfwgpku.html

C#:   s.IndexOf("x")
来源：http://dali.mhx1999.top/Article/details/gt2ihxsqqwv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lrunbhaz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.snrcjt.cn/Article/details/gt2zonhhlmv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shuidangran.top/Article/details/gt2juyozzoh.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hongshengwenyu.top/Article/details/gt2fjmmuzlp.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.dashuyun.cn/Article/details/gt2qpbqtcuh.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jiagoushi.top/Article/details/gt2uzorhmhx.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.daxiang520.top/Article/details/gt2psfiepdd.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hywenlv.cn/Article/details/gt2zidmzgyh.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yanxiufei.cn/Article/details/gt2nmowcyxo.html

[E06] 替换子串
来源：http://dali.tanke756.top/Article/details/gt2akvlhhnr.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yj202588.top/Article/details/gt2oxxbnhox.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.9152youxi.cn/Article/details/gt2utvfoxkq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2cvfzgfpg.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gt2nbnauvxj.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gt2ppqtkmyn.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.havefunace.top/Article/details/gt2hpeezdus.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gt2ckbtwdwy.html

C#:   s.Replace("a", "b")
来源：http://dali.gzhubu.top/Article/details/gt2cooefwcl.html

[E07] 按分隔符拆分
来源：http://dali.wangshuangyany.cn/Article/details/gt2liqpuszx.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.bjfxy.top/Article/details/gt2jgopzajz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.daxiang520.top/Article/details/gt2hmlazsza.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.redwolf501.top/Article/details/gt2ctgmanyz.html

TS:   s.split(",")
来源：http://dali.sysykeji.top/Article/details/gt2wsvewfxn.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.bjfxy.top/Article/details/gt2tdhiezuf.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shuidangran.top/Article/details/gt2mehzldnd.html

Ruby: s.split(",");  s.split
来源：http://dali.zhixingplan.top/Article/details/gt2xjnuvmpp.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.birdmap.top/Article/details/gt2rwztregi.html

[E08] 数组按分隔符合并
来源：http://dali.sweek.top/Article/details/gt2pxhreovr.html

Py:   ",".join(items)
来源：http://dali.fzhhl.top/Article/details/gt2yysrrbvw.html

PHP:  implode(",", $items);
来源：http://dali.gotoacloud.top/Article/details/gt2pybumfwn.html

JS:   items.join(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2slvhevze.html

TS:   items.join(",")
来源：http://dali.316326.xyz/Article/details/gt2zrvmnqri.html

Java: String.join(",", items)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ulgouobp.html

Go:   strings.Join(items, ",")
来源：http://dali.aibaodan.cn/Article/details/gt2kobjjbmf.html

Ruby: items.join(",")
来源：http://dali.yuanzhike.top/Article/details/gt2velrsvwz.html

C#:   string.Join(",", items)
来源：http://dali.birdmap.top/Article/details/gt2rknyfsfq.html

[E09] 去除所有空白字符
来源：http://dali.cdnleiting.top/Article/details/gt2wbvzfdfd.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ehwqpu.com/Article/details/gt2upfpulko.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.nanxinkj.top/Article/details/gt2oaznhjbn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.andypj.xyz/Article/details/gt2azbjwdzz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.chenzaomai.com/Article/details/gt2zbkuttgs.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhijiandao.cn/Article/details/gt2rcechjab.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhiwuduotai.top/Article/details/gt2zlmzrwvb.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gzhubu.top/Article/details/gt2rmnqlwod.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xuetiantiany.cn/Article/details/gt2wpozrtnv.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xuanzx.com/Article/details/gt2txdkrtgg.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yanxiufei.cn/Article/details/gt2phxmdntl.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yanxiufei.cn/Article/details/gt2parvspzp.html

JS:   "7".padStart(3, "0")
来源：http://dali.tian-w.cn/Article/details/gt2qgxsdpgv.html

TS:   "7".padStart(3, "0")
来源：http://dali.iojbl.cn/Article/details/gt2pkfstucu.html

Java: String.format("%03d", 7)
来源：http://dali.ydzc1.top/Article/details/gt2cuuboisq.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.bjfxy.top/Article/details/gt2qllpgpfa.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.dianchejie.cn/Article/details/gt2aiyfvfzw.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xylfe.cn/Article/details/gt2wxiixehw.html

[E11] 反转字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mwrmyqzw.html

Py:   s[::-1]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uixqfcwd.html

PHP:  strrev($s);
来源：http://dali.jianghu66.top/Article/details/gt2xgjfmgjn.html

JS:   [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gt2eqaqyakp.html

TS:   [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gt2mqjjqblw.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.birdmap.top/Article/details/gt2xrpknaaz.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhongyouzk.top/Article/details/gt2llqsdrno.html

Ruby: s.reverse
来源：http://dali.redwolf501.top/Article/details/gt2bewbqmll.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.guowangkeji.top/Article/details/gt2qnxbfazr.html

[E12] 统计某字符出现次数
来源：http://dali.hywenlv.cn/Article/details/gt2pfogxjuy.html

Py:   s.count("a")
来源：http://dali.daria6918.cn/Article/details/gt2aspandks.html

PHP:  substr_count($s, "a");
来源：http://dali.smart0.xyz/Article/details/gt2hlbacnln.html

JS:   s.split("a").length - 1
来源：http://dali.gogol.net.cn/Article/details/gt2enzpdvjy.html

TS:   s.split("a").length - 1
来源：http://dali.vqdsnc.cn/Article/details/gt2rtblxiws.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2nlkwkrcd.html

Go:   strings.Count(s, "a")
来源：http://dali.jqgufenzy.top/Article/details/gt2lekdfygz.html

Ruby: s.count("a")
来源：http://dali.wangshuangyany.cn/Article/details/gt2fwpbkcni.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cashguo.top/Article/details/gt2xgzufwrt.html

[E13] 逐字符遍历
来源：http://dali.pengpengdd.cyou/Article/details/gt2vmakhfpk.html

Py:   for ch in s: print(ch)
来源：http://dali.andypj.xyz/Article/details/gt2prdwlmey.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gotoacloud.top/Article/details/gt2dxcqwoik.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj20258888.top/Article/details/gt2smaonmts.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.birdmap.top/Article/details/gt2crlhwqrs.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2conrzaai.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.svipenyu.cn/Article/details/gt2lwaozmqc.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.andypj.xyz/Article/details/gt2wckryvuk.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gotoacloud.top/Article/details/gt2ldeqbqcy.html

[E14] URL 编码与 Base64
来源：http://dali.redwolf501.top/Article/details/gt2tyqqeyfm.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.chenzaomai.com/Article/details/gt2ombtaqza.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.sysykeji.top/Article/details/gt2tgjowbpl.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jianghu66.top/Article/details/gt2awjdxlqt.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xuanzx.com/Article/details/gt2skqglbni.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zdqjudy.top/Article/details/gt2ykwcqurv.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jqgufenzy.top/Article/details/gt2kcluimea.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cqqwz.cn/Article/details/gt2dzzkpvww.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.snrcjt.cn/Article/details/gt2ckjvpdkp.html

[E15] HTML 转义 / 反转义
来源：http://dali.yj202588.top/Article/details/gt2zxpfrnft.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ydzc1.top/Article/details/gt2wxyxwjtf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.havefunace.top/Article/details/gt2yadsvhtb.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.chenlongwang.top/Article/details/gt2uhrcwbgm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jqgufenzy.top/Article/details/gt2dkgbmebd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.gzhubu.top/Article/details/gt2kpgynfyf.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ppjwa.cn/Article/details/gt2hzfhgvow.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jianghu66.top/Article/details/gt2nmqshapj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gzhubu.top/Article/details/gt2ymussqrb.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2lbeslzug.html

Py:   f"{1234567:,}"
来源：http://dali.havefunace.top/Article/details/gt2nhoxgknq.html

PHP:  number_format(1234567);
来源：http://dali.smart0.xyz/Article/details/gt2afbbcqtt.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.gogol.net.cn/Article/details/gt2pzlbykyv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hammf.cn/Article/details/gt2zaxpsxac.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.gzhubu.top/Article/details/gt2ilnidfln.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yonumen.top/Article/details/gt2zmhtzkfy.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sysykeji.top/Article/details/gt2ctuthmlu.html

C#:   1234567.ToString("N0")
来源：http://dali.hongshengwenyu.top/Article/details/gt2nloqnblo.html

[E17] 首字母大写
来源：http://dali.aizwys.cn/Article/details/gt2zgilxzex.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.sweek.top/Article/details/gt2iabwmbos.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.andypj.xyz/Article/details/gt2jtuzirhe.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jlmmryud.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ehwqpu.com/Article/details/gt2ijlqdccj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jyoumei.cn/Article/details/gt2kkcpvyvx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yj20258888.top/Article/details/gt2ckgfojvp.html

Ruby: s.capitalize
来源：http://dali.fzhhl.top/Article/details/gt2jbexmkyu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hammf.cn/Article/details/gt2xzrwvyzl.html

[E18] 模板占位符替换
来源：http://dali.smart0.xyz/Article/details/gt2widwjiea.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gzhubu.top/Article/details/gt2pfrvdnjy.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hfpthk.cn/Article/details/gt2ynbqtllp.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.redwolf501.top/Article/details/gt2bpwwvmyx.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.pycfn.com/Article/details/gt2gooxeoom.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gt2fzweyjtd.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gt2lwkzdapg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hysaishi.cn/Article/details/gt2uiaayqsn.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gaohongyu789.top/Article/details/gt2mjfvdozs.html

[E19] 多行文本按行拆分
来源：http://dali.yangfankeji.com/Article/details/gt2thessavz.html

Py:   s.splitlines()
来源：http://dali.jianghu66.top/Article/details/gt2qmpcdbzc.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.dashuyun.cn/Article/details/gt2isblmewf.html

JS:   s.split(/\r?\n/)
来源：http://dali.cqqwz.cn/Article/details/gt2utfhuyzq.html

TS:   s.split(/\r?\n/)
来源：http://dali.yangfankeji.com/Article/details/gt2cmojtnhe.html

Java: s.lines().toList()
来源：http://dali.haohaochexian.top/Article/details/gt2pbnbxecy.html

Go:   strings.Split(s, "\n")
来源：http://dali.nanxinkj.top/Article/details/gt2yjpdftwr.html

Ruby: s.lines
来源：http://dali.haohaochexian.top/Article/details/gt2iwogfvsn.html

C#:   s.Split('\n')
来源：http://dali.pengpengdd.cyou/Article/details/gt2jrsqzfim.html

[E20] 判断字符串是否为空
来源：http://dali.aizwys.cn/Article/details/gt2vzmgeyop.html

Py:   if not s:
来源：http://dali.chenjidiqi.icu/Article/details/gt2qajepmxd.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shzxlz.cn/Article/details/gt2emhycunu.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.mhx1999.top/Article/details/gt2gicjlagc.html

TS:   if (s === "") {}
来源：http://dali.fengsongda.top/Article/details/gt2ylppxtmz.html

Java: if (s.isEmpty()) {}
来源：http://dali.daria6918.cn/Article/details/gt2jzwvjmcn.html

Go:   if s == "" {}
来源：http://dali.kuanghao11.cn/Article/details/gt2okotxwbu.html

Ruby: if s.empty?
来源：http://dali.cdnleiting.top/Article/details/gt2iglgnpfc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.birdmap.top/Article/details/gt2ymbnrlaj.html

[E21] 超长截断加省略号
来源：http://dali.vqdsnc.cn/Article/details/gt2cukhgllx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.feifeiyinyue.top/Article/details/gt2pqhjkdul.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gt2ivxrfrnu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gt2sirtirgw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gt2qbemdzxu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gt2ofiyxfgr.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.quarkkingdee.top/Article/details/gt2mjnjpwsv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gt2nqpeqsso.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nhzifoim.html

[E22] 字节长度与字符长度
来源：http://dali.yonumen.top/Article/details/gt2ztlaokqa.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.haohaochexian.top/Article/details/gt2jwilxzte.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hnxiangtu.top/Article/details/gt2axabgimh.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tpdjowqu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tianlin.xyz/Article/details/gt2njtupfkr.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yangfankeji.com/Article/details/gt2inxoqkwi.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.chenzaomai.com/Article/details/gt2suzixcma.html

Ruby: s.bytesize;  s.length
来源：http://dali.xziqi.cn/Article/details/gt2qsaejmel.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.aizwys.cn/Article/details/gt2jgcoeeow.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2fitptike.html

F. 文件与目录
来源：http://dali.hnqzz.top/Article/details/gt2krbiebqi.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sfqufgag.html

[F01] 读取整个文件
来源：http://dali.shuidangran.top/Article/details/gt2lflopetu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.bjfxy.top/Article/details/gt2pjbpswkg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yongpay.top/Article/details/gt2qvaqwtkh.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhixingplan.top/Article/details/gt2jiukzumu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gaohongyu789.top/Article/details/gt2viiqanis.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gt2irupipln.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.mhx1999.top/Article/details/gt2hlnaxtnx.html

Ruby: File.read("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2ljvmlocz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yj20258888.top/Article/details/gt2pofniwdk.html

[F02] 逐行读取文件
来源：http://dali.jqgufenzy.top/Article/details/gt2idysrilh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wghhrhna.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yuanzhike.top/Article/details/gt2jqtsjtux.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2qcozgjne.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fengsongda.top/Article/details/gt2otkjrixh.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.sxryk.cn/Article/details/gt2cgfnqcrj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.9152youxi.cn/Article/details/gt2bjqnzrdp.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shuidangran.top/Article/details/gt2zeosuvwn.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xinyue.icu/Article/details/gt2vaysvgpm.html

[F03] 写入文件（覆盖）
来源：http://dali.jlsjyb.cn/Article/details/gt2ssfuhgxc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cashguo.top/Article/details/gt2wrwdxyaq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.meibo888.top/Article/details/gt2ybuwhaxn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xurklsqn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jyoumei.cn/Article/details/gt2oimjwwuo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhixingplan.top/Article/details/gt2jwvbwdjc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shuidangran.top/Article/details/gt2kkjbgosm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.aibaodan.cn/Article/details/gt2bgngpubb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.tanke756.top/Article/details/gt2prxhcsrg.html

[F04] 追加写入文件
来源：http://dali.yuxming.cn/Article/details/gt2oooqumlf.html


<!-- 参考信息 -->