代发 wailian999

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.daxiang520.top/Article/details/gtkbaxysgb.html

[D20] 统计每个元素出现次数
来源：http://dali.hywenlv.cn/Article/details/gtewnziuuk.html

Py:   Counter(arr)
来源：http://dali.hammf.cn/Article/details/gtiepwwpfo.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtmlbgljcz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.daxiang520.top/Article/details/gtmvnjyjfn.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnqzz.top/Article/details/gtwxwhmijd.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.aibaodan.cn/Article/details/gtdvpvlesh.html

Go:   // 手写 map[T]int
来源：http://dali.haohaochexian.top/Article/details/gtswonlbae.html

Ruby: arr.tally
来源：http://dali.gzhubu.top/Article/details/gtkxojyzuc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yuxming.cn/Article/details/gtbteqoell.html

[D21] 判断是否包含某元素
来源：http://dali.havefunace.top/Article/details/gtaervlavv.html

Py:   x in arr
来源：http://dali.fzhhl.top/Article/details/gtmandwdus.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gotoacloud.top/Article/details/gtifecslkd.html

JS:   arr.includes(x)
来源：http://dali.hfpthk.cn/Article/details/gtmucbbfif.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gttoeczwra.html

Java: list.contains(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdngqodsd.html

Go:   slices.Contains(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtcnmsecya.html

Ruby: arr.include?(x)
来源：http://dali.bjfxy.top/Article/details/gtdxkpelhw.html

C#:   list.Contains(x)
来源：http://dali.jlsjyb.cn/Article/details/gtfqkwaqmi.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yj202588.top/Article/details/gtxbfuipwe.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cashguo.top/Article/details/gtsbvpoqpc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hfpthk.cn/Article/details/gtawzjqzha.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yangfankeji.com/Article/details/gtszazaryz.html

TS:   [...arr];
来源：http://dali.dianchejie.cn/Article/details/gtniwxvfht.html

Java: new ArrayList<>(list);
来源：http://dali.gogol.net.cn/Article/details/gtnwarjitg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cqqwz.cn/Article/details/gtjrucuiik.html

Ruby: arr.dup;  arr.clone
来源：http://dali.snrcjt.cn/Article/details/gteqfybglq.html

C#:   new List<int>(list);
来源：http://dali.dianchejie.cn/Article/details/gttsktktjk.html

[D23] reduce 累积计算
来源：http://dali.feifeiyinyue.top/Article/details/gtcffhraox.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtcracbzzg.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yongpay.top/Article/details/gtsqqelteh.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xuanzx.com/Article/details/gthetbkfmw.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtcrzunyfu.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.chenzaomai.com/Article/details/gtjmwquhon.html

Go:   // 手写循环
来源：http://dali.meibo888.top/Article/details/gtlfqffdcj.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jiagoushi.top/Article/details/gtjsgthond.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.smart0.xyz/Article/details/gtcuctidws.html

[D24] 字典 / Map 基本操作
来源：http://dali.9152youxi.cn/Article/details/gtsbeahaqs.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jqgfzy.top/Article/details/gtijszgnyy.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.gogol.net.cn/Article/details/gtgztvowha.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.chenlongwang.top/Article/details/gtwdqszxar.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xylfe.cn/Article/details/gtlyzdcbki.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xylfe.cn/Article/details/gtaevllbyd.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.0kj1m.cn/Article/details/gtqaemedgo.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.guowangkeji.top/Article/details/gtnwiheqdl.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.aibaodan.cn/Article/details/gtucihytjw.html

[D25] Set 集合去重与交并差
来源：http://dali.sweek.top/Article/details/gtqqtfndoe.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jinqigufen.top/Article/details/gtdagewjak.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shangyingyoupin.top/Article/details/gtkapiqwyn.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jiagoushi.top/Article/details/gtuyhutvzy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.fzhhl.top/Article/details/gtekblzdjj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtfxpyryam.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.smart0.xyz/Article/details/gtdjlllkse.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gzhubu.top/Article/details/gtgrerysyv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cheryme.top/Article/details/gtbihurjpn.html

[D26] 数组转字符串
来源：http://dali.svipenyu.cn/Article/details/gtpkcvklyv.html

Py:   ", ".join(map(str, arr))
来源：http://dali.tian-w.cn/Article/details/gtfjsbwpli.html

PHP:  implode(", ", $arr);
来源：http://dali.ydzc1.top/Article/details/gtjcvmpetp.html

JS:   arr.join(", ")
来源：http://dali.yuxming.cn/Article/details/gtrjuszmel.html

TS:   arr.join(", ")
来源：http://dali.hfpthk.cn/Article/details/gtrtfsfdpu.html

Java: String.join(", ", list)
来源：http://dali.sufxvd.cn/Article/details/gtdedkdcci.html

Go:   strings.Join(strs, ", ")
来源：http://dali.iojbl.cn/Article/details/gtqpkqytor.html

Ruby: arr.join(", ")
来源：http://dali.mhx1999.top/Article/details/gtigzrvakn.html

C#:   string.Join(", ", list)
来源：http://dali.zdqjudy.top/Article/details/gtkrzdbogv.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtmlvvfntv.html

E. 字符串处理
来源：http://dali.jinqigfzy.top/Article/details/gtrnizwjhs.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtlospopgv.html

[E01] 拼接字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtstlwihhg.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.guowangkeji.top/Article/details/gtgjmlvljl.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhengqikj.top/Article/details/gtjiymuysi.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xuanzx.com/Article/details/gtefaovhrw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.guowangkeji.top/Article/details/gthhnadfcm.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.tanke756.top/Article/details/gtnvjfkovu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.kuanghao11.cn/Article/details/gtkyzkbrqx.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ppjwa.cn/Article/details/gtcxfzeodv.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtozawjwjg.html

[E02] 重复字符串
来源：http://dali.vqdsnc.cn/Article/details/gthsrfcrvn.html

Py:   "ab" * 3
来源：http://dali.birdmap.top/Article/details/gtyrzpnijl.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hnqzz.top/Article/details/gtbkfunocz.html

JS:   "ab".repeat(3)
来源：http://dali.fengsongda.top/Article/details/gtmgxmmqna.html

TS:   "ab".repeat(3)
来源：http://dali.yj20258888.top/Article/details/gtkuwdzmts.html

Java: "ab".repeat(3)
来源：http://dali.zhengqikj.top/Article/details/gtdgerlyxc.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.feifeiyinyue.top/Article/details/gtommdoqxa.html

Ruby: "ab" * 3
来源：http://dali.dianchejie.cn/Article/details/gtljkmprvt.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ppjwa.cn/Article/details/gtqirctoxb.html

[E03] 截取子串
来源：http://dali.quarkkingdee.top/Article/details/gtngcngbjn.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhoulong.xyz/Article/details/gtxsbgktse.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gtdxwfcslx.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cucudq.cn/Article/details/gtstxcwprh.html

TS:   s.slice(1, 4)
来源：http://dali.jqgufenzy.top/Article/details/gtxrxdtyys.html

Java: s.substring(1, 4)
来源：http://dali.guannengcc.top/Article/details/gtaistriqk.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cashguo.top/Article/details/gtapvadsgp.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.gzhubu.top/Article/details/gtfjeeuulz.html

C#:   s.Substring(1, 3)
来源：http://dali.nanxinkj.top/Article/details/gtaknxreox.html

[E04] 查找子串位置
来源：http://dali.yonumen.top/Article/details/gtzxbofhla.html

Py:   s.find("x");  s.index("x")
来源：http://dali.havefunace.top/Article/details/gtidsmdxte.html

PHP:  strpos($s, "x");
来源：http://dali.guowangkeji.top/Article/details/gtaymoyhxf.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.chenjidiqi.icu/Article/details/gtiiztuvjf.html

TS:   s.indexOf("x")
来源：http://dali.guannengcc.top/Article/details/gttwozkudk.html

Java: s.indexOf("x")
来源：http://dali.guannengcc.top/Article/details/gtpxamzqcd.html

Go:   strings.Index(s, "x")
来源：http://dali.jlsjyb.cn/Article/details/gtcqgsaurl.html

Ruby: s.index("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgfxmyjsn.html

C#:   s.IndexOf("x")
来源：http://dali.aibaodan.cn/Article/details/gtxbmndnjl.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jqgufenzy.top/Article/details/gtbxftblrb.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hnxiangtu.top/Article/details/gtjbitlnay.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cucudq.cn/Article/details/gtirnmvhoh.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xuanzx.com/Article/details/gtfscavjhp.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gtszdifpsn.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinqigufen.top/Article/details/gtsagrutvw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.fengsongda.top/Article/details/gtenussobi.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cqqwz.cn/Article/details/gtrjagydwq.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jqgufenzy.top/Article/details/gtxfektiul.html

[E06] 替换子串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgrbjjvex.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.wangdashe.top/Article/details/gtadmgiube.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jqgfzy.top/Article/details/gtsycndmpy.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtokczolnl.html

TS:   s.replaceAll("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gtivxtmzbk.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gtxpnftdci.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtidsbobko.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gtzznktqbt.html

C#:   s.Replace("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gtjgkpukfn.html

[E07] 按分隔符拆分
来源：http://dali.yangfankeji.com/Article/details/gtebophawo.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinqigufen.top/Article/details/gthkpnkszq.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yvedp.cn/Article/details/gtgbgfmgwa.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.meibo888.top/Article/details/gtnfgyvowq.html

TS:   s.split(",")
来源：http://dali.hnxiangtu.top/Article/details/gtcozlqict.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cucudq.cn/Article/details/gthyhfkmsp.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yuanzhike.top/Article/details/gtzspzsemm.html

Ruby: s.split(",");  s.split
来源：http://dali.xuanzx.com/Article/details/gtrohzefes.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shuidangran.top/Article/details/gtkkpdiahp.html

[E08] 数组按分隔符合并
来源：http://dali.yonumen.top/Article/details/gtgortiwie.html

Py:   ",".join(items)
来源：http://dali.xuanzx.com/Article/details/gtgsgsemxv.html

PHP:  implode(",", $items);
来源：http://dali.zhiwuduotai.top/Article/details/gtzqbpscsu.html

JS:   items.join(",")
来源：http://dali.kuanghao11.cn/Article/details/gtaphwjuht.html

TS:   items.join(",")
来源：http://dali.ivvv.top/Article/details/gtdmmevluj.html

Java: String.join(",", items)
来源：http://dali.ppjwa.cn/Article/details/gtjixmdgwc.html

Go:   strings.Join(items, ",")
来源：http://dali.jlsjyb.cn/Article/details/gtmkffxnrv.html

Ruby: items.join(",")
来源：http://dali.birdmap.top/Article/details/gtlmnztokt.html

C#:   string.Join(",", items)
来源：http://dali.gogol.net.cn/Article/details/gtwdebbmfu.html

[E09] 去除所有空白字符
来源：http://dali.ehwqpu.com/Article/details/gtqbgucjwk.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.pengpengdd.cyou/Article/details/gtubsotxkm.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yj202588.top/Article/details/gtlybcmcat.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.fzhhl.top/Article/details/gtdqshnfcj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhiwuduotai.top/Article/details/gtqztdlrvm.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shuidangran.top/Article/details/gttaoglyaj.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jyoumei.cn/Article/details/gtbukxhfba.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zycfv.cn/Article/details/gtsaxmxyqd.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.pengpengdd.cyou/Article/details/gtqnuwiplp.html

[E10] 左侧补零 / 定长填充
来源：http://dali.iojbl.cn/Article/details/gtntwbcitn.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sysykeji.top/Article/details/gtsjxguvqe.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.birdmap.top/Article/details/gtkzlsfans.html

JS:   "7".padStart(3, "0")
来源：http://dali.dianchejie.cn/Article/details/gtwqhunonn.html

TS:   "7".padStart(3, "0")
来源：http://dali.jqgufenzy.top/Article/details/gtbluadwty.html

Java: String.format("%03d", 7)
来源：http://dali.fzhhl.top/Article/details/gtdfdztvlm.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.iojbl.cn/Article/details/gtfjrqevpe.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.bjfxy.top/Article/details/gtfvlkpbsg.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.daxiang520.top/Article/details/gtzdgxuzxu.html

[E11] 反转字符串
来源：http://dali.hysaishi.cn/Article/details/gtggeegrwm.html

Py:   s[::-1]
来源：http://dali.bjfxy.top/Article/details/gtpllbpevv.html

PHP:  strrev($s);
来源：http://dali.xylfe.cn/Article/details/gtlzgisgib.html

JS:   [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gtdkheqazx.html

TS:   [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gtaopzdsvv.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.feifeiyinyue.top/Article/details/gtjzuzqjsn.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.kuanghao11.cn/Article/details/gtaybqwgro.html

Ruby: s.reverse
来源：http://dali.jyoumei.cn/Article/details/gtoxhuveqw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhaomingkeji.xyz/Article/details/gthmparzhk.html

[E12] 统计某字符出现次数
来源：http://dali.daxiang520.top/Article/details/gtfdyquqpr.html

Py:   s.count("a")
来源：http://dali.zdqjudy.top/Article/details/gtshgfkjsy.html

PHP:  substr_count($s, "a");
来源：http://dali.aizwys.cn/Article/details/gtaeygpego.html

JS:   s.split("a").length - 1
来源：http://dali.gaohongyu789.top/Article/details/gtahfncrlv.html

TS:   s.split("a").length - 1
来源：http://dali.316326.xyz/Article/details/gtxqxtgheo.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jinqigufen.top/Article/details/gtliudfizo.html

Go:   strings.Count(s, "a")
来源：http://dali.gotoacloud.top/Article/details/gtoeslxvrg.html

Ruby: s.count("a")
来源：http://dali.chenjidiqi.icu/Article/details/gtnvgfsyra.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrifutnit.html

[E13] 逐字符遍历
来源：http://dali.xziqi.cn/Article/details/gtkiluxesg.html

Py:   for ch in s: print(ch)
来源：http://dali.birdmap.top/Article/details/gtrofoobcv.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.guannengcc.top/Article/details/gtpxylhemr.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ybcxt.top/Article/details/gtgyfvuvnq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtnapusfnz.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hnxiangtu.top/Article/details/gtxwmqtazq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cashguo.top/Article/details/gtuafxtzov.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ivvv.top/Article/details/gtfucaajfa.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hysaishi.cn/Article/details/gtzezmjadi.html

[E14] URL 编码与 Base64
来源：http://dali.fzhhl.top/Article/details/gtejhulrjc.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.aibaodan.cn/Article/details/gtmzjkshcr.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.nwbrower.top/Article/details/gtfgzitblf.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtegtyltpw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cashguo.top/Article/details/gtfydnwpvy.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xuanzx.com/Article/details/gttzqmkjly.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.tianlin.xyz/Article/details/gtxmdmwalg.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hysaishi.cn/Article/details/gtgfzcatjp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.daria6918.cn/Article/details/gtxobxxxgo.html

[E15] HTML 转义 / 反转义
来源：http://dali.yvedp.cn/Article/details/gtttykyrqo.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cqqwz.cn/Article/details/gtqmpwlxel.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.daria6918.cn/Article/details/gtsgghvcuy.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yj202588.top/Article/details/gtdjduudms.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.smart0.xyz/Article/details/gtaoxzyaye.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ywan-chungtsiang.top/Article/details/gtriekwhic.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtoflactug.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gttkfqqnpf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gaohongyu789.top/Article/details/gtqjktmoyv.html

[E16] 数字千分位
来源：http://dali.yuanzhike.top/Article/details/gtzhschold.html

Py:   f"{1234567:,}"
来源：http://dali.hnxiangtu.top/Article/details/gtzblybxkf.html

PHP:  number_format(1234567);
来源：http://dali.shanyushiyangtech.top/Article/details/gtsejajvdu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj202588.top/Article/details/gtupsfflni.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtupnmrezw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.gaohongyu789.top/Article/details/gtzzumvvhk.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtresyeucr.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.dashuyun.cn/Article/details/gtwmgxuumy.html

C#:   1234567.ToString("N0")
来源：http://dali.9152youxi.cn/Article/details/gtwjdlatef.html

[E17] 首字母大写
来源：http://dali.hnqzz.top/Article/details/gtkehbotyl.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.daxiang520.top/Article/details/gtdviiredc.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhoulong.xyz/Article/details/gthzwmfchq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ehwqpu.com/Article/details/gtloagkblk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj202588.top/Article/details/gtkbkvnmde.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinqigfzy.top/Article/details/gtscoilcue.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jianghu66.top/Article/details/gtijjjfual.html

Ruby: s.capitalize
来源：http://dali.ivvv.top/Article/details/gtmckdrazo.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.andypj.xyz/Article/details/gtziczvist.html

[E18] 模板占位符替换
来源：http://dali.tianlin.xyz/Article/details/gtaccsdlku.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gzhubu.top/Article/details/gtuwpascir.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.birdmap.top/Article/details/gtbmjizgjd.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xylfe.cn/Article/details/gtefejjjek.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gtclausfov.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gtmqtnrbax.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsvwbfear.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.9152youxi.cn/Article/details/gtafrafwwk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhongyouzk.top/Article/details/gtctjmquqv.html

[E19] 多行文本按行拆分
来源：http://dali.zhengqikj.top/Article/details/gtluenyhvo.html

Py:   s.splitlines()
来源：http://dali.shangyingyoupin.top/Article/details/gtpvwjdujk.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gzhubu.top/Article/details/gtfdhwidqy.html

JS:   s.split(/\r?\n/)
来源：http://dali.vqdsnc.cn/Article/details/gtmwvpfyuh.html

TS:   s.split(/\r?\n/)
来源：http://dali.chenzaomai.com/Article/details/gtmkenefdh.html

Java: s.lines().toList()
来源：http://dali.yonumen.top/Article/details/gtmxtyvfmq.html

Go:   strings.Split(s, "\n")
来源：http://dali.tanke756.top/Article/details/gtxdiuokkf.html

Ruby: s.lines
来源：http://dali.yj202588.top/Article/details/gtfeqgpiac.html

C#:   s.Split('\n')
来源：http://dali.mhx1999.top/Article/details/gtrftctrxr.html

[E20] 判断字符串是否为空
来源：http://dali.tanke756.top/Article/details/gtmxnymsef.html

Py:   if not s:
来源：http://dali.shanyushiyangkeji.top/Article/details/gthkpesomn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhixingplan.top/Article/details/gtnnuzlksx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xinyue.icu/Article/details/gtjxgzsinj.html

TS:   if (s === "") {}
来源：http://dali.yongpay.top/Article/details/gtxzylaoou.html

Java: if (s.isEmpty()) {}
来源：http://dali.xinyue.icu/Article/details/gtffqruryt.html

Go:   if s == "" {}
来源：http://dali.jinqigufen.top/Article/details/gtpxnnbget.html

Ruby: if s.empty?
来源：http://dali.gaohongyu789.top/Article/details/gtmsonyabl.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hnxiangtu.top/Article/details/gtoplzabej.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gtbrlahuub.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gaohongyu789.top/Article/details/gthshhegri.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.wangdashe.top/Article/details/gtcesomwhd.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gtxyuyqcqu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gtpoxyexzz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xylfe.cn/Article/details/gtznnevvzz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shzxlz.cn/Article/details/gtsnfnmexy.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yonumen.top/Article/details/gtyceffjal.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfbiounyg.html

[E22] 字节长度与字符长度
来源：http://dali.316326.xyz/Article/details/gtosubfhdu.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtgokzxllr.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gtlqcwsfgn.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hysaishi.cn/Article/details/gtmmfquiki.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenlongwang.top/Article/details/gtjgjipeng.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shuidangran.top/Article/details/gtirdrobxj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hongshengwenyu.top/Article/details/gtodhlqmrf.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhiwuduotai.top/Article/details/gtjglyyjko.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hnxiangtu.top/Article/details/gtuwwrffze.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtudkrtqtw.html

F. 文件与目录
来源：http://dali.ydzc1.top/Article/details/gtffkyxfal.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtwfixsuay.html

[F01] 读取整个文件
来源：http://dali.sufxvd.cn/Article/details/gthyfhdrgv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.aizwys.cn/Article/details/gtlkmupuwl.html

PHP:  file_get_contents("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtnzvzjybm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gaohongyu789.top/Article/details/gtpumzyfdx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gtxiqjxqli.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gtrpdabipw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.nanxuanxn.top/Article/details/gtzpmlcavm.html

Ruby: File.read("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtpxrlwfjg.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtsjwzsmgq.html

[F02] 逐行读取文件
来源：http://dali.mhx1999.top/Article/details/gtfrveikpv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xylfe.cn/Article/details/gtajoikkto.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shzxlz.cn/Article/details/gtxwugedth.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtcbihgynu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgfzy.top/Article/details/gtgdwdozrj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tanke756.top/Article/details/gtnqugycln.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gaohongyu789.top/Article/details/gtauhkmzlw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.mhx1999.top/Article/details/gtoocyekqk.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.bjfxy.top/Article/details/gthqmrchxo.html

[F03] 写入文件（覆盖）
来源：http://dali.jlsjyb.cn/Article/details/gtbfzujdis.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxbuulfmx.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.nanxinkj.top/Article/details/gtdsultgvg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigufen.top/Article/details/gtedvgfqgc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqqrqjuyf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.svipenyu.cn/Article/details/gtuxulqawm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.sysykeji.top/Article/details/gtroztlnus.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xziqi.cn/Article/details/gtxnlmkofx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.andypj.xyz/Article/details/gtmrshlefu.html

[F04] 追加写入文件
来源：http://dali.yonumen.top/Article/details/gtvukxcuaf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ppjwa.cn/Article/details/gtbchtjaib.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfuwtfwyk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sufxvd.cn/Article/details/gtyyaqlvre.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gttzbwgqeu.html


<!-- 参考信息 -->