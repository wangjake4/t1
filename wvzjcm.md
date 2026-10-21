代发 wailian999

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gtgfhejmmk.html

[D20] 统计每个元素出现次数
来源：http://dali.redwolf501.top/Article/details/gtfvbfaakf.html

Py:   Counter(arr)
来源：http://dali.zdqjudy.top/Article/details/gtmevhqyzk.html

PHP:  array_count_values($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmqcxfdhq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnxiangtu.top/Article/details/gtxxfacmwz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.bjfxy.top/Article/details/gtkhddjrcp.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.vqdsnc.cn/Article/details/gtwkjlryno.html

Go:   // 手写 map[T]int
来源：http://dali.feifeiyinyue.top/Article/details/gtyiorytwk.html

Ruby: arr.tally
来源：http://dali.gaohongyu789.top/Article/details/gtbjlndsgn.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yongpay.top/Article/details/gtbrpsgzaw.html

[D21] 判断是否包含某元素
来源：http://dali.ehwqpu.com/Article/details/gtcydbdvbi.html

Py:   x in arr
来源：http://dali.zhaomingkeji.xyz/Article/details/gtewesxdrn.html

PHP:  in_array($x, $arr, true);
来源：http://dali.chenzaomai.com/Article/details/gtkiuydcxl.html

JS:   arr.includes(x)
来源：http://dali.dashuyun.cn/Article/details/gtlyiotevg.html

TS:   arr.includes(x)
来源：http://dali.jqgufenzy.top/Article/details/gttjdrbqun.html

Java: list.contains(x)
来源：http://dali.dianchejie.cn/Article/details/gtgawblczp.html

Go:   slices.Contains(arr, x)
来源：http://dali.daxiang520.top/Article/details/gtopbixgog.html

Ruby: arr.include?(x)
来源：http://dali.zycfv.cn/Article/details/gtrlzfmsed.html

C#:   list.Contains(x)
来源：http://dali.chenlongwang.top/Article/details/gtynfcidgs.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xziqi.cn/Article/details/gttyivfscq.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.havefunace.top/Article/details/gtodueqntx.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hongshengwenyu.top/Article/details/gthccsztrk.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yj202588.top/Article/details/gtuhjwxzyr.html

TS:   [...arr];
来源：http://dali.zhixingplan.top/Article/details/gtssnestel.html

Java: new ArrayList<>(list);
来源：http://dali.havefunace.top/Article/details/gtcakgmcew.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hywenlv.cn/Article/details/gtrdfnidwp.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yongpay.top/Article/details/gtoxmpoyfa.html

C#:   new List<int>(list);
来源：http://dali.yuanzhike.top/Article/details/gtvnlslwhh.html

[D23] reduce 累积计算
来源：http://dali.ivvv.top/Article/details/gtcfmxqtfw.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.c1oappe.top/Article/details/gtpdwwmwrb.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ydzc1.top/Article/details/gtxlfehtgk.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuxming.cn/Article/details/gtetacqaps.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yongpay.top/Article/details/gtohqqlqcm.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.guowangkeji.top/Article/details/gtpkxhvnqn.html

Go:   // 手写循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgwymjazb.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.tian-w.cn/Article/details/gtxlkagnif.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xziqi.cn/Article/details/gtivfcocwr.html

[D24] 字典 / Map 基本操作
来源：http://dali.jlsjyb.cn/Article/details/gtdtuhqums.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.guowangkeji.top/Article/details/gtwjfnrljh.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.0kj1m.cn/Article/details/gthhrpahos.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdresmnmq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yj20258888.top/Article/details/gtjpzwzpvo.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.gogol.net.cn/Article/details/gtuzkzerdn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jqgfzy.top/Article/details/gtqiivsohn.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shzxlz.cn/Article/details/gtnuflnzmo.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yj20258.top/Article/details/gtczpfdbhf.html

[D25] Set 集合去重与交并差
来源：http://dali.zhoulong.xyz/Article/details/gtgocvbhqa.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.mhx1999.top/Article/details/gtmhcuyvpu.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhixingplan.top/Article/details/gthuwkedhy.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtblhflkre.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hnxiangtu.top/Article/details/gtxvsxmdbc.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hammf.cn/Article/details/gtatxkoorb.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.sweek.top/Article/details/gtzlwiveum.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shzxlz.cn/Article/details/gtfwajgmku.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hnxiangtu.top/Article/details/gtebpdanda.html

[D26] 数组转字符串
来源：http://dali.jiagoushi.top/Article/details/gthipstivx.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jinqigufen.top/Article/details/gtgjscdqvj.html

PHP:  implode(", ", $arr);
来源：http://dali.xylfe.cn/Article/details/gtezykayvg.html

JS:   arr.join(", ")
来源：http://dali.zdqjudy.top/Article/details/gtqaddpzkh.html

TS:   arr.join(", ")
来源：http://dali.zhongyouzk.top/Article/details/gtczflxebv.html

Java: String.join(", ", list)
来源：http://dali.svipenyu.cn/Article/details/gtequaggdk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.dashuyun.cn/Article/details/gtrddielpq.html

Ruby: arr.join(", ")
来源：http://dali.pengpengdd.cyou/Article/details/gteuiyrruc.html

C#:   string.Join(", ", list)
来源：http://dali.pycfn.com/Article/details/gtvenictlm.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtoxzdmmuy.html

E. 字符串处理
来源：http://dali.yanxiufei.cn/Article/details/gtuqnxhexi.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gttupjunbl.html

[E01] 拼接字符串
来源：http://dali.sxryk.cn/Article/details/gtoehayzyz.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gogol.net.cn/Article/details/gtdqwvtyjh.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.nwbrower.top/Article/details/gtfcobdcoq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258888.top/Article/details/gtqrvdruah.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.birdmap.top/Article/details/gtptdxxqnf.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhiwuduotai.top/Article/details/gtmlgibmri.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jqgufenzy.top/Article/details/gtnaflectm.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xuanzx.com/Article/details/gtxlpwczwp.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gtokntlhny.html

[E02] 重复字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gttklaejfy.html

Py:   "ab" * 3
来源：http://dali.yuanzhike.top/Article/details/gtqpyfnscg.html

PHP:  str_repeat("ab", 3);
来源：http://dali.haohaochexian.top/Article/details/gtehwcntxc.html

JS:   "ab".repeat(3)
来源：http://dali.jqgufenzy.top/Article/details/gtaoxkvocm.html

TS:   "ab".repeat(3)
来源：http://dali.nwbrower.top/Article/details/gtpymybjff.html

Java: "ab".repeat(3)
来源：http://dali.shzxlz.cn/Article/details/gtsygioawz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yuanzhike.top/Article/details/gtbxcrrqwe.html

Ruby: "ab" * 3
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnlynexcq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ivvv.top/Article/details/gtkddcgqwn.html

[E03] 截取子串
来源：http://dali.ehwqpu.com/Article/details/gtlqmixbwo.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shzxlz.cn/Article/details/gtycjlenrl.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.316326.xyz/Article/details/gtxvbqipbl.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gaohongyu789.top/Article/details/gttshsykhz.html

TS:   s.slice(1, 4)
来源：http://dali.sysykeji.top/Article/details/gtnvqmwesy.html

Java: s.substring(1, 4)
来源：http://dali.9152youxi.cn/Article/details/gtwkjbvlgs.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.nanxinkj.top/Article/details/gthlyfwvga.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.fzhhl.top/Article/details/gtjslfuwqv.html

C#:   s.Substring(1, 3)
来源：http://dali.yanxiufei.cn/Article/details/gtesegcxwi.html

[E04] 查找子串位置
来源：http://dali.nanxinkj.top/Article/details/gtyofxaszj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jiagoushi.top/Article/details/gtfcofqxeq.html

PHP:  strpos($s, "x");
来源：http://dali.zhengqikj.top/Article/details/gtevlwqxvu.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.dashuyun.cn/Article/details/gtcdlecnvi.html

TS:   s.indexOf("x")
来源：http://dali.sweek.top/Article/details/gtgttezpng.html

Java: s.indexOf("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gtywrrzkhm.html

Go:   strings.Index(s, "x")
来源：http://dali.cheryme.top/Article/details/gtbrpbswbd.html

Ruby: s.index("x")
来源：http://dali.feifeiyinyue.top/Article/details/gtxipewyju.html

C#:   s.IndexOf("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfitywhdz.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhoulong.xyz/Article/details/gtkcasglmi.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.aibaodan.cn/Article/details/gtuzomwigv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinyuanbaomall.cn/Article/details/gttfrxhgfu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.havefunace.top/Article/details/gtptuzgnwg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yongpay.top/Article/details/gtrilcrkje.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.smart0.xyz/Article/details/gtxaleyvto.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shanyushiyangtech.top/Article/details/gtcaigltdo.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.chenjidiqi.icu/Article/details/gtiljdlekj.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.dashuyun.cn/Article/details/gttlzbgngk.html

[E06] 替换子串
来源：http://dali.gotoacloud.top/Article/details/gtgdsphaae.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbxivdxqp.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hywenlv.cn/Article/details/gtyzqewijo.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyzdqdihw.html

TS:   s.replaceAll("a", "b")
来源：http://dali.sxryk.cn/Article/details/gtypzfqrtp.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtglqeylvj.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtwwpviyvi.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtywdprxsb.html

C#:   s.Replace("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gtegmtygcg.html

[E07] 按分隔符拆分
来源：http://dali.pengpengdd.cyou/Article/details/gtmsakbwqp.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ppjwa.cn/Article/details/gtwswdrqtr.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cdnleiting.top/Article/details/gthxmzmxtr.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.pycfn.com/Article/details/gtsjgwfqwt.html

TS:   s.split(",")
来源：http://dali.nanxinkj.top/Article/details/gtmoxdawdt.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shzxlz.cn/Article/details/gtsygeupad.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xziqi.cn/Article/details/gtclfoaomq.html

Ruby: s.split(",");  s.split
来源：http://dali.yonumen.top/Article/details/gtbdwpnuly.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.snrcjt.cn/Article/details/gtbwrkbqmt.html

[E08] 数组按分隔符合并
来源：http://dali.cashguo.top/Article/details/gtthvibvjx.html

Py:   ",".join(items)
来源：http://dali.xylfe.cn/Article/details/gtdadnjoxh.html

PHP:  implode(",", $items);
来源：http://dali.tianlin.xyz/Article/details/gtjyymgeyl.html

JS:   items.join(",")
来源：http://dali.shanyushiyangtech.top/Article/details/gtxywtztnd.html

TS:   items.join(",")
来源：http://dali.ehwqpu.com/Article/details/gtutsbawdo.html

Java: String.join(",", items)
来源：http://dali.gaohongyu789.top/Article/details/gtxvavdktl.html

Go:   strings.Join(items, ",")
来源：http://dali.zhiwuduotai.top/Article/details/gtycpzqzxw.html

Ruby: items.join(",")
来源：http://dali.jyoumei.cn/Article/details/gthoamixpx.html

C#:   string.Join(",", items)
来源：http://dali.snrcjt.cn/Article/details/gtcnsdmelo.html

[E09] 去除所有空白字符
来源：http://dali.vqdsnc.cn/Article/details/gtvuwkhlbd.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yj202588.top/Article/details/gtumfztywx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtzxmtfyzd.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shangyingyoupin.top/Article/details/gthjybtshj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.316326.xyz/Article/details/gtcdhfvhaa.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.chenjidiqi.icu/Article/details/gtdtsjsvkh.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hnxiangtu.top/Article/details/gtbpyxpbxf.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xylfe.cn/Article/details/gtkoyvudnl.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xziqi.cn/Article/details/gtojccdapf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jyoumei.cn/Article/details/gtpspfoyqt.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.aibaodan.cn/Article/details/gtuuemnmvw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.chenlongwang.top/Article/details/gtddvhkdft.html

JS:   "7".padStart(3, "0")
来源：http://dali.xuanzx.com/Article/details/gtdzurpcan.html

TS:   "7".padStart(3, "0")
来源：http://dali.aizwys.cn/Article/details/gtrvfksuux.html

Java: String.format("%03d", 7)
来源：http://dali.chenjidiqi.icu/Article/details/gtuiaifwsy.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zycfv.cn/Article/details/gtjfrhkjxo.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.iojbl.cn/Article/details/gtlzkjlzoe.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.meibo888.top/Article/details/gtoohwemrx.html

[E11] 反转字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkwphdeju.html

Py:   s[::-1]
来源：http://dali.wangshuangyany.cn/Article/details/gtlmheycak.html

PHP:  strrev($s);
来源：http://dali.zhoulong.xyz/Article/details/gtnwivakcy.html

JS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gtrtjzxhwk.html

TS:   [...s].reverse().join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjgteuodl.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cheryme.top/Article/details/gtvdevlpog.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jinqigufen.top/Article/details/gtqburomdq.html

Ruby: s.reverse
来源：http://dali.zhixingplan.top/Article/details/gtmnhsjljz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.dashuyun.cn/Article/details/gtfmmrsczy.html

[E12] 统计某字符出现次数
来源：http://dali.cdnleiting.top/Article/details/gtjagmvfgf.html

Py:   s.count("a")
来源：http://dali.xuanzx.com/Article/details/gtksfoscpk.html

PHP:  substr_count($s, "a");
来源：http://dali.meibo888.top/Article/details/gtkiuwyoyk.html

JS:   s.split("a").length - 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdmugmehq.html

TS:   s.split("a").length - 1
来源：http://dali.aizwys.cn/Article/details/gtlkhcvjfm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cdnleiting.top/Article/details/gtcjkvafbu.html

Go:   strings.Count(s, "a")
来源：http://dali.ehwqpu.com/Article/details/gtmtwwbexd.html

Ruby: s.count("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthbvddinq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.pycfn.com/Article/details/gtbjtuyync.html

[E13] 逐字符遍历
来源：http://dali.fengsongda.top/Article/details/gtfivqupiq.html

Py:   for ch in s: print(ch)
来源：http://dali.yj20258888.top/Article/details/gteamwxvhf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jiagoushi.top/Article/details/gtrmxqhrcp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jiagoushi.top/Article/details/gtlehficqx.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.iojbl.cn/Article/details/gtiearwclg.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.snrcjt.cn/Article/details/gtrtaouvyf.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xuanzx.com/Article/details/gteueliqqn.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.cheryme.top/Article/details/gtpvudzknz.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.nwbrower.top/Article/details/gtizxoznxz.html

[E14] URL 编码与 Base64
来源：http://dali.shuidangran.top/Article/details/gtclnclgal.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yuanzhike.top/Article/details/gtaahcohec.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xuanzx.com/Article/details/gtwaosueso.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.0kj1m.cn/Article/details/gtakjgoqlb.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.iojbl.cn/Article/details/gtewlrrnsb.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xuanzx.com/Article/details/gtfpgxxmqv.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.0kj1m.cn/Article/details/gtgiqizepo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.aibaodan.cn/Article/details/gtjvodfwxa.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ppjwa.cn/Article/details/gtxkejswax.html

[E15] HTML 转义 / 反转义
来源：http://dali.chenjidiqi.icu/Article/details/gtsbfsgipe.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtdgokirdb.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhixingplan.top/Article/details/gtvtuvcihy.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cucudq.cn/Article/details/gtgkhnxpxm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.pengpengdd.cyou/Article/details/gtrrdetrke.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinqigufen.top/Article/details/gthkvaozhi.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.quarkkingdee.top/Article/details/gtogvdvokm.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.pycfn.com/Article/details/gtdmnwafbh.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.snrcjt.cn/Article/details/gtlvscybjz.html

[E16] 数字千分位
来源：http://dali.hammf.cn/Article/details/gtcxiccrnc.html

Py:   f"{1234567:,}"
来源：http://dali.jlsjyb.cn/Article/details/gtkryejved.html

PHP:  number_format(1234567);
来源：http://dali.jinqigfzy.top/Article/details/gturzhhzrm.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.feifeiyinyue.top/Article/details/gtvisqrwdo.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ydzc1.top/Article/details/gtntqnxqok.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ppjwa.cn/Article/details/gtwhwccpzr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cheryme.top/Article/details/gtxhiouuin.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sxryk.cn/Article/details/gtxyymolbc.html

C#:   1234567.ToString("N0")
来源：http://dali.hammf.cn/Article/details/gtwmpifrai.html

[E17] 首字母大写
来源：http://dali.tian-w.cn/Article/details/gtzsgjhweq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jqgufenzy.top/Article/details/gtzyrauufv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sweek.top/Article/details/gtnejdzlir.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.meibo888.top/Article/details/gtkuzcchpv.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sysykeji.top/Article/details/gtvdcpjjqo.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hfpthk.cn/Article/details/gtzymyrgxm.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.kuanghao11.cn/Article/details/gtaezjsmse.html

Ruby: s.capitalize
来源：http://dali.nwbrower.top/Article/details/gtwftdiqlv.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.daxiang520.top/Article/details/gtmvinldcy.html

[E18] 模板占位符替换
来源：http://dali.nwbrower.top/Article/details/gtliaieoyi.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jqgfzy.top/Article/details/gtrqwfcshh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.andypj.xyz/Article/details/gtjibsnbsq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.c1oappe.top/Article/details/gtthwvsegl.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gtqstezkup.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gtvdavcssz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xinyue.icu/Article/details/gthpsgsesq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.guannengcc.top/Article/details/gtapfjnpkg.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinqigufen.top/Article/details/gtmdpyddix.html

[E19] 多行文本按行拆分
来源：http://dali.cheryme.top/Article/details/gtljmtsguz.html

Py:   s.splitlines()
来源：http://dali.fengsongda.top/Article/details/gttpjgwklz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtkvcleofy.html

JS:   s.split(/\r?\n/)
来源：http://dali.9152youxi.cn/Article/details/gtdmqcpbxg.html

TS:   s.split(/\r?\n/)
来源：http://dali.bjfxy.top/Article/details/gttzxryazq.html

Java: s.lines().toList()
来源：http://dali.zycfv.cn/Article/details/gtdhujmfoy.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhixingplan.top/Article/details/gtwvtjsuzk.html

Ruby: s.lines
来源：http://dali.yonumen.top/Article/details/gtguoswnbc.html

C#:   s.Split('\n')
来源：http://dali.hammf.cn/Article/details/gtfiipniou.html

[E20] 判断字符串是否为空
来源：http://dali.jinyuanbaomall.cn/Article/details/gtofbhuvxm.html

Py:   if not s:
来源：http://dali.quarkkingdee.top/Article/details/gtbifgkzvq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.smart0.xyz/Article/details/gtxqrvkggm.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hywenlv.cn/Article/details/gtnvbjhrrf.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gtjrjzzagk.html

Java: if (s.isEmpty()) {}
来源：http://dali.fzhhl.top/Article/details/gtbojavxgh.html

Go:   if s == "" {}
来源：http://dali.fengsongda.top/Article/details/gtqrclhhhl.html

Ruby: if s.empty?
来源：http://dali.guowangkeji.top/Article/details/gtifcpixdx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.fengsongda.top/Article/details/gtlulaxuqu.html

[E21] 超长截断加省略号
来源：http://dali.svipenyu.cn/Article/details/gtoudqqnxl.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sxryk.cn/Article/details/gtjfdtymds.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.iojbl.cn/Article/details/gtfxiuhdey.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gtjdcfquka.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtorxqhrfe.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gtthokavhz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhixingplan.top/Article/details/gttjhxswku.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gteglwphoy.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gtqbfsycyi.html

[E22] 字节长度与字符长度
来源：http://dali.yuxming.cn/Article/details/gteewyzfqy.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.snrcjt.cn/Article/details/gtcsqhdqop.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gtdrqbcyan.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.bjfxy.top/Article/details/gtentomsme.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cqqwz.cn/Article/details/gtzibcaxwx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.iojbl.cn/Article/details/gtxzevujnt.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.chenzaomai.com/Article/details/gtemwzmziy.html

Ruby: s.bytesize;  s.length
来源：http://dali.ydzc1.top/Article/details/gtfnzyytez.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sysykeji.top/Article/details/gtxauzkhje.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtsoslrqpg.html

F. 文件与目录
来源：http://dali.hongshengwenyu.top/Article/details/gtneqwvhip.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtdbgssafs.html

[F01] 读取整个文件
来源：http://dali.haohaochexian.top/Article/details/gtqicjpfeb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.wangshuangyany.cn/Article/details/gtpmzupjot.html

PHP:  file_get_contents("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtzzmskkpi.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.pycfn.com/Article/details/gtrxqltzaw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtatwfhfbn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gtafnuxeuk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.guowangkeji.top/Article/details/gtuoeyzpwb.html

Ruby: File.read("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtwopngwas.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtfcgbcfxr.html

[F02] 逐行读取文件
来源：http://dali.wangshuangyany.cn/Article/details/gtukndxcsr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yvedp.cn/Article/details/gtnhbxmeqm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.wangshuangyany.cn/Article/details/gtzvrkruiu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj202588.top/Article/details/gtvgmxjfmu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gogol.net.cn/Article/details/gthxblvlsp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.andypj.xyz/Article/details/gtkcldeeke.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.316326.xyz/Article/details/gtgkrflnjd.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfcdvnlcy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shzxlz.cn/Article/details/gttdnlsbxx.html

[F03] 写入文件（覆盖）
来源：http://dali.chenlongwang.top/Article/details/gtesneturt.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.tanke756.top/Article/details/gtmtfhqial.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gtglbjitto.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuxming.cn/Article/details/gtzkgqighw.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigufen.top/Article/details/gtbazgdrlo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.mhx1999.top/Article/details/gtcoesebus.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jianghu66.top/Article/details/gtrtexwtae.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.quarkkingdee.top/Article/details/gtmjhnafzo.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhiwuduotai.top/Article/details/gtzlngnxhw.html

[F04] 追加写入文件
来源：http://dali.yuxming.cn/Article/details/gtwurvujyx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hysaishi.cn/Article/details/gtmltcwfrd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.nanxuanxn.top/Article/details/gtfkzqribu.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hysaishi.cn/Article/details/gtowxjarqz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gtyneeornn.html


<!-- 参考信息 -->