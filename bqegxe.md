代发 wailian999

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.0kj1m.cn/Article/details/gttesgytgv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cdnleiting.top/Article/details/gtljmqwjly.html

Go:   // 手写 map[string][]T
来源：http://dali.guowangkeji.top/Article/details/gtlbrovceu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.aibaodan.cn/Article/details/gtlobjzbbf.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmhefewrh.html

[D20] 统计每个元素出现次数
来源：http://dali.wangshuangyany.cn/Article/details/gtuqdseimo.html

Py:   Counter(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtlotzfgti.html

PHP:  array_count_values($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtfdktshtk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.snrcjt.cn/Article/details/gtbnysrmex.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jlsjyb.cn/Article/details/gtsbaueguh.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.chenzaomai.com/Article/details/gtbtopmkpn.html

Go:   // 手写 map[T]int
来源：http://dali.jinghuilouyu.cn/Article/details/gtvoyiqjgi.html

Ruby: arr.tally
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlskuepba.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zdqjudy.top/Article/details/gtjuvattjl.html

[D21] 判断是否包含某元素
来源：http://dali.c1oappe.top/Article/details/gtkaemkysk.html

Py:   x in arr
来源：http://dali.feifeiyinyue.top/Article/details/gtnnmeyqmw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ppjwa.cn/Article/details/gtisrdlzmw.html

JS:   arr.includes(x)
来源：http://dali.guannengcc.top/Article/details/gtjxaalizd.html

TS:   arr.includes(x)
来源：http://dali.jianghu66.top/Article/details/gtkvwdaveo.html

Java: list.contains(x)
来源：http://dali.sxryk.cn/Article/details/gttyoddkqo.html

Go:   slices.Contains(arr, x)
来源：http://dali.ivvv.top/Article/details/gtqwykgrpj.html

Ruby: arr.include?(x)
来源：http://dali.jyoumei.cn/Article/details/gtwbckpyez.html

C#:   list.Contains(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtsqdchryg.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yj20258888.top/Article/details/gthpmfjvjg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gogol.net.cn/Article/details/gthioumrcp.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yongpay.top/Article/details/gtmveziaeb.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtiniikwxa.html

TS:   [...arr];
来源：http://dali.yj202588.top/Article/details/gthlquhubk.html

Java: new ArrayList<>(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwnphtyyw.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.nanxinkj.top/Article/details/gtovtdsglq.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cqqwz.cn/Article/details/gtxnrwurqu.html

C#:   new List<int>(list);
来源：http://dali.sxryk.cn/Article/details/gtkcpvkozx.html

[D23] reduce 累积计算
来源：http://dali.yueranfly.top/Article/details/gtddkbpvbt.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yvedp.cn/Article/details/gtliryuaye.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdmgdhnyc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenlongwang.top/Article/details/gtyibamwmc.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxinkj.top/Article/details/gtcxvjevum.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhiwuduotai.top/Article/details/gtezjkesnw.html

Go:   // 手写循环
来源：http://dali.gogol.net.cn/Article/details/gtswlfxwqk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xylfe.cn/Article/details/gtbbptmlgp.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.fzhhl.top/Article/details/gtrcqxmsax.html

[D24] 字典 / Map 基本操作
来源：http://dali.sxryk.cn/Article/details/gtjiioxyee.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xuetiantiany.cn/Article/details/gtqfjqyloo.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hysaishi.cn/Article/details/gtqcubvfiu.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtooixzbab.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gtpkoxxbml.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.daxiang520.top/Article/details/gtmigdlkjl.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinqigfzy.top/Article/details/gtfxqynqgb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhixingplan.top/Article/details/gtbedxfzxr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.chenlongwang.top/Article/details/gttcqlgjau.html

[D25] Set 集合去重与交并差
来源：http://dali.gotoacloud.top/Article/details/gtuzvzjwbn.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xuanzx.com/Article/details/gtuarkzktc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.birdmap.top/Article/details/gtocuafudz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yj202588.top/Article/details/gtiabqxgbu.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoienpxuc.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ybcxt.top/Article/details/gtpgwfiucs.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hysaishi.cn/Article/details/gtxjofixsg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ydzc1.top/Article/details/gtojadjftp.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yuanzhike.top/Article/details/gtdclrnsmz.html

[D26] 数组转字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtribzijje.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhoulong.xyz/Article/details/gtbqzxhijy.html

PHP:  implode(", ", $arr);
来源：http://dali.yangfankeji.com/Article/details/gtfqogxosm.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gtfovrlfzu.html

TS:   arr.join(", ")
来源：http://dali.yuanzhike.top/Article/details/gtjdzexzvw.html

Java: String.join(", ", list)
来源：http://dali.vqdsnc.cn/Article/details/gtupzgocwe.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cucudq.cn/Article/details/gtawsjxhno.html

Ruby: arr.join(", ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoemujlsl.html

C#:   string.Join(", ", list)
来源：http://dali.jqgufenzy.top/Article/details/gtyvvnjqco.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtuycpdrib.html

E. 字符串处理
来源：http://dali.fengsongda.top/Article/details/gtgfexnbae.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtqcifukas.html

[E01] 拼接字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtiowwaqsv.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jqgufenzy.top/Article/details/gtocvyftzt.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinqigfzy.top/Article/details/gtxgykonlf.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jqgufenzy.top/Article/details/gtgabeltoe.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhongyouzk.top/Article/details/gttkfbprxr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jqgufenzy.top/Article/details/gtjfsdqhfw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sweek.top/Article/details/gtrwajhmrn.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jqgufenzy.top/Article/details/gtgpzrepjv.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gtvsvqczjj.html

[E02] 重复字符串
来源：http://dali.nanxuanxn.top/Article/details/gtzwylxxap.html

Py:   "ab" * 3
来源：http://dali.jinqigfzy.top/Article/details/gtukkkbuqh.html

PHP:  str_repeat("ab", 3);
来源：http://dali.chenzaomai.com/Article/details/gtiqhfmtqi.html

JS:   "ab".repeat(3)
来源：http://dali.jyoumei.cn/Article/details/gttgrasivx.html

TS:   "ab".repeat(3)
来源：http://dali.xziqi.cn/Article/details/gtefemylxi.html

Java: "ab".repeat(3)
来源：http://dali.nwbrower.top/Article/details/gtalkidmdc.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xuanzx.com/Article/details/gtxjdxvxpx.html

Ruby: "ab" * 3
来源：http://dali.vqdsnc.cn/Article/details/gtzcwsccld.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hongshengwenyu.top/Article/details/gttneovbni.html

[E03] 截取子串
来源：http://dali.hywenlv.cn/Article/details/gttwqnaged.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shanyushiyangtech.top/Article/details/gtjtypeapy.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gtyexoquye.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.sysykeji.top/Article/details/gtichlfyko.html

TS:   s.slice(1, 4)
来源：http://dali.dashuyun.cn/Article/details/gtxjzofgzw.html

Java: s.substring(1, 4)
来源：http://dali.xziqi.cn/Article/details/gtdybqmwuw.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.daxiang520.top/Article/details/gtdwrxbbla.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.meibo888.top/Article/details/gtgniheiyz.html

C#:   s.Substring(1, 3)
来源：http://dali.chenlongwang.top/Article/details/gthmtaqrrz.html

[E04] 查找子串位置
来源：http://dali.pycfn.com/Article/details/gtgwmulptn.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ppjwa.cn/Article/details/gtgdaeiarj.html

PHP:  strpos($s, "x");
来源：http://dali.jlsjyb.cn/Article/details/gtombzfjtc.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ydzc1.top/Article/details/gtottoeear.html

TS:   s.indexOf("x")
来源：http://dali.zycfv.cn/Article/details/gtunazrjju.html

Java: s.indexOf("x")
来源：http://dali.gotoacloud.top/Article/details/gtcmjwrwvv.html

Go:   strings.Index(s, "x")
来源：http://dali.jinqigfzy.top/Article/details/gtyxcbxbqw.html

Ruby: s.index("x")
来源：http://dali.yueranfly.top/Article/details/gtcgldgvmg.html

C#:   s.IndexOf("x")
来源：http://dali.shzxlz.cn/Article/details/gtiwmwqivl.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.316326.xyz/Article/details/gtezdpaucw.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.wangshuangyany.cn/Article/details/gtnaavgiwt.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.chenzaomai.com/Article/details/gtubfbwhsj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.wangshuangyany.cn/Article/details/gtnxfdwgic.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.andypj.xyz/Article/details/gtzfoafkth.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gogol.net.cn/Article/details/gthdnzouuv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.bjfxy.top/Article/details/gtmkidyqry.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.9152youxi.cn/Article/details/gtzosrennu.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.nwbrower.top/Article/details/gtzdxeknsg.html

[E06] 替换子串
来源：http://dali.quarkkingdee.top/Article/details/gtzyuaoiyw.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.wangdashe.top/Article/details/gtysddmgby.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jinqigfzy.top/Article/details/gtkgbvjepj.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gteqxqubls.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gtfedbjvky.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yonumen.top/Article/details/gtcpqadnet.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hammf.cn/Article/details/gtdsqucneb.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtuugsnbxe.html

C#:   s.Replace("a", "b")
来源：http://dali.fzhhl.top/Article/details/gtfgqxiinu.html

[E07] 按分隔符拆分
来源：http://dali.wangshuangyany.cn/Article/details/gtfvymmwzo.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.kuanghao11.cn/Article/details/gtccyuuchp.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hfpthk.cn/Article/details/gthvffiska.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ehwqpu.com/Article/details/gtkeptnmyu.html

TS:   s.split(",")
来源：http://dali.hnqzz.top/Article/details/gtwaxzuoyt.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xziqi.cn/Article/details/gtjayimhxq.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sufxvd.cn/Article/details/gtutbtmibb.html

Ruby: s.split(",");  s.split
来源：http://dali.nanxuanxn.top/Article/details/gtzpajsjba.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.nwbrower.top/Article/details/gttyxjymkv.html

[E08] 数组按分隔符合并
来源：http://dali.chenlongwang.top/Article/details/gtrjqegyjg.html

Py:   ",".join(items)
来源：http://dali.xuetiantiany.cn/Article/details/gtxstnyqff.html

PHP:  implode(",", $items);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwsuhqtlx.html

JS:   items.join(",")
来源：http://dali.shuidangran.top/Article/details/gtyaefbeay.html

TS:   items.join(",")
来源：http://dali.wangshuangyany.cn/Article/details/gtnefdsysr.html

Java: String.join(",", items)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpqufgfvi.html

Go:   strings.Join(items, ",")
来源：http://dali.nanxuanxn.top/Article/details/gtimidsnvy.html

Ruby: items.join(",")
来源：http://dali.jinqigufen.top/Article/details/gtdiagftxf.html

C#:   string.Join(",", items)
来源：http://dali.sysykeji.top/Article/details/gtwzhjinur.html

[E09] 去除所有空白字符
来源：http://dali.yangfankeji.com/Article/details/gtkemjcmrg.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.havefunace.top/Article/details/gtnquipcev.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hnqzz.top/Article/details/gtgvszfnpf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.redwolf501.top/Article/details/gtvhajiqqu.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ydzc1.top/Article/details/gtsgiyzovy.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xuanzx.com/Article/details/gtypzbfydh.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zdqjudy.top/Article/details/gtfosbvrjy.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.mhx1999.top/Article/details/gtkvmuokve.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.iojbl.cn/Article/details/gtqzgegldd.html

[E10] 左侧补零 / 定长填充
来源：http://dali.shuidangran.top/Article/details/gtifetwzgn.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.haohaochexian.top/Article/details/gtxxlaqqwk.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.dianchejie.cn/Article/details/gtexxzpyre.html

JS:   "7".padStart(3, "0")
来源：http://dali.yueranfly.top/Article/details/gtqtderovg.html

TS:   "7".padStart(3, "0")
来源：http://dali.tianlin.xyz/Article/details/gtzprweztx.html

Java: String.format("%03d", 7)
来源：http://dali.sweek.top/Article/details/gtzyiynjrk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.iojbl.cn/Article/details/gtkgupcuti.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.pengpengdd.cyou/Article/details/gthlvhyulc.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.redwolf501.top/Article/details/gtciibwnft.html

[E11] 反转字符串
来源：http://dali.xuanzx.com/Article/details/gtvuhqafxi.html

Py:   s[::-1]
来源：http://dali.snrcjt.cn/Article/details/gtunesqskf.html

PHP:  strrev($s);
来源：http://dali.jqgufenzy.top/Article/details/gtnpwogbdp.html

JS:   [...s].reverse().join("")
来源：http://dali.snrcjt.cn/Article/details/gtqmyhdwxk.html

TS:   [...s].reverse().join("")
来源：http://dali.yuxming.cn/Article/details/gtfbmecjxr.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinqigufen.top/Article/details/gthehzvsuh.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.pycfn.com/Article/details/gtazkhmczb.html

Ruby: s.reverse
来源：http://dali.0kj1m.cn/Article/details/gthccyuvwo.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinqigufen.top/Article/details/gtdtkdktzd.html

[E12] 统计某字符出现次数
来源：http://dali.shzxlz.cn/Article/details/gtidcoakor.html

Py:   s.count("a")
来源：http://dali.cucudq.cn/Article/details/gtqdfbhqyj.html

PHP:  substr_count($s, "a");
来源：http://dali.hongshengwenyu.top/Article/details/gtzazsrvxo.html

JS:   s.split("a").length - 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfqfjybzp.html

TS:   s.split("a").length - 1
来源：http://dali.meibo888.top/Article/details/gtserdlkep.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.fzhhl.top/Article/details/gtjjxtuqtl.html

Go:   strings.Count(s, "a")
来源：http://dali.kuanghao11.cn/Article/details/gttehzcjwk.html

Ruby: s.count("a")
来源：http://dali.yonumen.top/Article/details/gttdansyuk.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhiwuduotai.top/Article/details/gtuomazjzq.html

[E13] 逐字符遍历
来源：http://dali.shuidangran.top/Article/details/gtzfkyczkz.html

Py:   for ch in s: print(ch)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtirymnxby.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.guowangkeji.top/Article/details/gtcredlcun.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtieirtwzx.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenlongwang.top/Article/details/gtbwlwtuco.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.redwolf501.top/Article/details/gtofbhiznm.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.chenzaomai.com/Article/details/gtshvvkzxi.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhaomingkeji.xyz/Article/details/gteqwsjjri.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.aibaodan.cn/Article/details/gtinpbffdc.html

[E14] URL 编码与 Base64
来源：http://dali.yongpay.top/Article/details/gtruuddswa.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.aizwys.cn/Article/details/gtisxkmgjt.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.wangdashe.top/Article/details/gtmwcuxoyt.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sxryk.cn/Article/details/gtxhblatrv.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfqowdsxw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xinyue.icu/Article/details/gtkkqypkld.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ybcxt.top/Article/details/gtjzdamvxy.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cqqwz.cn/Article/details/gthexhjwyv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ehwqpu.com/Article/details/gtqoyxgslf.html

[E15] HTML 转义 / 反转义
来源：http://dali.feifeiyinyue.top/Article/details/gtdlupwkoh.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hfpthk.cn/Article/details/gtvbheeefi.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gzhubu.top/Article/details/gtjmbixiid.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.aibaodan.cn/Article/details/gtrsluikkj.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.nwbrower.top/Article/details/gtugyqphhn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.birdmap.top/Article/details/gtwwjxlrnh.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.snrcjt.cn/Article/details/gtkukhqwjl.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxoznpaou.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gotoacloud.top/Article/details/gtvqbipnhf.html

[E16] 数字千分位
来源：http://dali.feifeiyinyue.top/Article/details/gtkszpwfmi.html

Py:   f"{1234567:,}"
来源：http://dali.cashguo.top/Article/details/gtsbjodhgr.html

PHP:  number_format(1234567);
来源：http://dali.tianlin.xyz/Article/details/gtfstupauv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hywenlv.cn/Article/details/gtziqtxxov.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuanzx.com/Article/details/gtnmukbiuq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shangyingyoupin.top/Article/details/gtrbvjjzvx.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.wangshuangyany.cn/Article/details/gtyrzlxvqj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.smart0.xyz/Article/details/gtdiikqhzl.html

C#:   1234567.ToString("N0")
来源：http://dali.gogol.net.cn/Article/details/gtpapxlieu.html

[E17] 首字母大写
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkktrvwmu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.feifeiyinyue.top/Article/details/gtptdroouk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yongpay.top/Article/details/gttmuchykq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.fzhhl.top/Article/details/gtsnqmjida.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jyoumei.cn/Article/details/gtjmamqqbm.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zycfv.cn/Article/details/gtshinpdkk.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hysaishi.cn/Article/details/gtjsukcxws.html

Ruby: s.capitalize
来源：http://dali.yj20258888.top/Article/details/gtnyyevico.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnmpvibda.html

[E18] 模板占位符替换
来源：http://dali.wangdashe.top/Article/details/gtqashjepk.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.chenjidiqi.icu/Article/details/gtoaamsost.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinqigfzy.top/Article/details/gteqezvald.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnxiangtu.top/Article/details/gtrcvcrfvr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shuidangran.top/Article/details/gtcmquonqy.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gtwngxxnrm.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gotoacloud.top/Article/details/gtrreisqfw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yueranfly.top/Article/details/gtbrzysqll.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hfpthk.cn/Article/details/gtmcpwtnde.html

[E19] 多行文本按行拆分
来源：http://dali.yueranfly.top/Article/details/gtwbuzcvjb.html

Py:   s.splitlines()
来源：http://dali.vqdsnc.cn/Article/details/gttyjixfbz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cashguo.top/Article/details/gtyyvocpfp.html

JS:   s.split(/\r?\n/)
来源：http://dali.xuetiantiany.cn/Article/details/gtvgtgoiri.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhiwuduotai.top/Article/details/gtbmaoqwig.html

Java: s.lines().toList()
来源：http://dali.iojbl.cn/Article/details/gtnillrskx.html

Go:   strings.Split(s, "\n")
来源：http://dali.yj20258.top/Article/details/gtbzzadwlc.html

Ruby: s.lines
来源：http://dali.jinghuilouyu.cn/Article/details/gtymzbnqsj.html

C#:   s.Split('\n')
来源：http://dali.ywan-chungtsiang.top/Article/details/gtghmpifky.html

[E20] 判断字符串是否为空
来源：http://dali.9152youxi.cn/Article/details/gttsnnkezr.html

Py:   if not s:
来源：http://dali.zycfv.cn/Article/details/gtrladjlmq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmwjyjogo.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.0kj1m.cn/Article/details/gtdyulmdec.html

TS:   if (s === "") {}
来源：http://dali.yanxiufei.cn/Article/details/gthefxrdfd.html

Java: if (s.isEmpty()) {}
来源：http://dali.xuanzx.com/Article/details/gtfvtfdhps.html

Go:   if s == "" {}
来源：http://dali.hfpthk.cn/Article/details/gtzmftsivc.html

Ruby: if s.empty?
来源：http://dali.jinqigfzy.top/Article/details/gtwuurdbgp.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sufxvd.cn/Article/details/gtbxwzkqur.html

[E21] 超长截断加省略号
来源：http://dali.pycfn.com/Article/details/gtgvenyrvo.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gotoacloud.top/Article/details/gtuzyeibrg.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gtizqqywrp.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gtbcwgkzhn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.birdmap.top/Article/details/gtckhdlins.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yj20258888.top/Article/details/gthnqupukg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cheryme.top/Article/details/gtcyngdnkh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yj20258.top/Article/details/gtaxzbvutz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gtbydsxfjf.html

[E22] 字节长度与字符长度
来源：http://dali.xuetiantiany.cn/Article/details/gteivrynpn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.wangdashe.top/Article/details/gtuwmzsdmi.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gtywmfxzvu.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.feifeiyinyue.top/Article/details/gtdtochnkr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cqqwz.cn/Article/details/gtbjsqfqzf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.smart0.xyz/Article/details/gtiwlolybn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xinyue.icu/Article/details/gtuyrwblid.html

Ruby: s.bytesize;  s.length
来源：http://dali.jianghu66.top/Article/details/gtqimnxocs.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.mhx1999.top/Article/details/gttnynfkki.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtpvowacby.html

F. 文件与目录
来源：http://dali.xylfe.cn/Article/details/gtutwyoyaw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gttbmqlxgq.html

[F01] 读取整个文件
来源：http://dali.jiagoushi.top/Article/details/gtsxgapjas.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.tian-w.cn/Article/details/gtastahhsx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtxefflpps.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hnqzz.top/Article/details/gthnuyegrk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zdqjudy.top/Article/details/gtrqrjfmkm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gtmrnstkus.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jiagoushi.top/Article/details/gtkgbezbkm.html

Ruby: File.read("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtozcmghrt.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtyphriezs.html

[F02] 逐行读取文件
来源：http://dali.xuanzx.com/Article/details/gtyidmgery.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.tianlin.xyz/Article/details/gtoazykyqc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwwbptcky.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.aibaodan.cn/Article/details/gtmdutepjt.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyuifhdev.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yongpay.top/Article/details/gtsriiinyo.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.meibo888.top/Article/details/gtldexvowz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hnqzz.top/Article/details/gtosuegwxk.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhoulong.xyz/Article/details/gtkdknedfc.html

[F03] 写入文件（覆盖）
来源：http://dali.sweek.top/Article/details/gtzyuqxoxh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhongyouzk.top/Article/details/gtlonhbgmi.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hfpthk.cn/Article/details/gtbvlzypwv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.haohaochexian.top/Article/details/gtusnxowlu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.9152youxi.cn/Article/details/gtlgluwfpx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.nanxuanxn.top/Article/details/gtnkokjdcg.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.tanke756.top/Article/details/gtoqvrkwzc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.dianchejie.cn/Article/details/gtthluvnlv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zdqjudy.top/Article/details/gtklejohpz.html

[F04] 追加写入文件
来源：http://dali.yj20258888.top/Article/details/gtkjmdcqpd.html


<!-- 参考信息 -->