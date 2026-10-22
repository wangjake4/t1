代发 wailian999

PHP:  in_array($x, $arr, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bbndinic.html

JS:   arr.includes(x)
来源：http://dali.yongpay.top/Article/details/gt2rcknuyfc.html

TS:   arr.includes(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2vqpsrpdu.html

Java: list.contains(x)
来源：http://dali.shuidangran.top/Article/details/gt2gxrsdjbd.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fiirhrbp.html

Ruby: arr.include?(x)
来源：http://dali.jiagoushi.top/Article/details/gt2fuftqfen.html

C#:   list.Contains(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2mfdstrbd.html

[D22] 复制数组（避免共享引用）
来源：http://dali.feifeiyinyue.top/Article/details/gt2xslanlyy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hammf.cn/Article/details/gt2yrgsxzxo.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.316326.xyz/Article/details/gt2mpnwqbif.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xinyue.icu/Article/details/gt2mkhtlktd.html

TS:   [...arr];
来源：http://dali.yangfankeji.com/Article/details/gt2cmycpwsh.html

Java: new ArrayList<>(list);
来源：http://dali.nanxuanxn.top/Article/details/gt2iqykypwa.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.wangdashe.top/Article/details/gt2iwopykzx.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gogol.net.cn/Article/details/gt2qrmfnkrq.html

C#:   new List<int>(list);
来源：http://dali.sweek.top/Article/details/gt2dnsukzvo.html

[D23] reduce 累积计算
来源：http://dali.kuanghao11.cn/Article/details/gt2yvrciyvt.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.aizwys.cn/Article/details/gt2nwqwxyqp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yj20258888.top/Article/details/gt2jkninnze.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2woinagak.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.9152youxi.cn/Article/details/gt2dtejbubr.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jeormuim.html

Go:   // 手写循环
来源：http://dali.birdmap.top/Article/details/gt2ehiflfrg.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yonumen.top/Article/details/gt2hharcbaf.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.snrcjt.cn/Article/details/gt2fdpumqxo.html

[D24] 字典 / Map 基本操作
来源：http://dali.gzhubu.top/Article/details/gt2zfeopbne.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.daria6918.cn/Article/details/gt2ozvdklli.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yanxiufei.cn/Article/details/gt2xthxkavq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.guannengcc.top/Article/details/gt2hjyxtmfb.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gt2azslkckd.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cashguo.top/Article/details/gt2dmaafdgg.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yvedp.cn/Article/details/gt2rznsvxao.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.daxiang520.top/Article/details/gt2zylivolz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.quarkkingdee.top/Article/details/gt2gggimtca.html

[D25] Set 集合去重与交并差
来源：http://dali.yj20258.top/Article/details/gt2qrcppbsh.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhixingplan.top/Article/details/gt2yahxdquy.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hnxiangtu.top/Article/details/gt2vqgxbwco.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.nanxuanxn.top/Article/details/gt2cvjvuspb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cqqwz.cn/Article/details/gt2xkewsrys.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2htpqyvzo.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jifxwskp.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.wangdashe.top/Article/details/gt2ciaknyji.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.9152youxi.cn/Article/details/gt2seuyahzh.html

[D26] 数组转字符串
来源：http://dali.snrcjt.cn/Article/details/gt2vyhpbkoj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.fzhhl.top/Article/details/gt2jjetwblm.html

PHP:  implode(", ", $arr);
来源：http://dali.jqgfzy.top/Article/details/gt2doqccwwk.html

JS:   arr.join(", ")
来源：http://dali.xinyue.icu/Article/details/gt2kqlbswxq.html

TS:   arr.join(", ")
来源：http://dali.yueranfly.top/Article/details/gt2kegkqadp.html

Java: String.join(", ", list)
来源：http://dali.nwbrower.top/Article/details/gt2jpdzjbnr.html

Go:   strings.Join(strs, ", ")
来源：http://dali.smart0.xyz/Article/details/gt2wqbdfeir.html

Ruby: arr.join(", ")
来源：http://dali.xuanzx.com/Article/details/gt2ikfdgnhm.html

C#:   string.Join(", ", list)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fhwqcsff.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2tcyjhwli.html

E. 字符串处理
来源：http://dali.yj202588.top/Article/details/gt2errdvbpo.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2qclhlpyr.html

[E01] 拼接字符串
来源：http://dali.xylfe.cn/Article/details/gt2knfkyphz.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ppjwa.cn/Article/details/gt2smgsswot.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.andypj.xyz/Article/details/gt2muocilqv.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tian-w.cn/Article/details/gt2prnlhejr.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rfohrkqp.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ocqvagfo.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sweek.top/Article/details/gt2wzeviwup.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sufxvd.cn/Article/details/gt2eguvxbwv.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yvedp.cn/Article/details/gt2qowugvcc.html

[E02] 重复字符串
来源：http://dali.jyoumei.cn/Article/details/gt2dmqrgnga.html

Py:   "ab" * 3
来源：http://dali.yj20258.top/Article/details/gt2dnqlznrd.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jlsjyb.cn/Article/details/gt2geykhhsc.html

JS:   "ab".repeat(3)
来源：http://dali.zhongyouzk.top/Article/details/gt2ivctijnk.html

TS:   "ab".repeat(3)
来源：http://dali.nanxinkj.top/Article/details/gt2buolmrxv.html

Java: "ab".repeat(3)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ydjxyjki.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.sufxvd.cn/Article/details/gt2hudepyis.html

Ruby: "ab" * 3
来源：http://dali.yueranfly.top/Article/details/gt2ugkvrkkf.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cqqwz.cn/Article/details/gt2htzlheuv.html

[E03] 截取子串
来源：http://dali.svipenyu.cn/Article/details/gt2hudunckb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.9152youxi.cn/Article/details/gt2eiayzjlu.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gt2osrlcxgq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yongpay.top/Article/details/gt2vmumtgmn.html

TS:   s.slice(1, 4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fzkvlmuo.html

Java: s.substring(1, 4)
来源：http://dali.zycfv.cn/Article/details/gt2ixrxwnia.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jqgufenzy.top/Article/details/gt2hmoskyuk.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kosuqmjl.html

C#:   s.Substring(1, 3)
来源：http://dali.chenlongwang.top/Article/details/gt2fysnmnaw.html

[E04] 查找子串位置
来源：http://dali.smart0.xyz/Article/details/gt2qqhzogfm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.mhx1999.top/Article/details/gt2uiiwadis.html

PHP:  strpos($s, "x");
来源：http://dali.hywenlv.cn/Article/details/gt2lrmifgep.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yj20258888.top/Article/details/gt2xwbxwxie.html

TS:   s.indexOf("x")
来源：http://dali.yanxiufei.cn/Article/details/gt2uohrnfug.html

Java: s.indexOf("x")
来源：http://dali.tian-w.cn/Article/details/gt2cfteuvlv.html

Go:   strings.Index(s, "x")
来源：http://dali.zhixingplan.top/Article/details/gt2vrobjeuc.html

Ruby: s.index("x")
来源：http://dali.yj20258.top/Article/details/gt2lijouypw.html

C#:   s.IndexOf("x")
来源：http://dali.tanke756.top/Article/details/gt2gejozgxf.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shangyingyoupin.top/Article/details/gt2tzulmktp.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.smart0.xyz/Article/details/gt2oknayblo.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhixingplan.top/Article/details/gt2xanshsjg.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.meibo888.top/Article/details/gt2lxviffax.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ydzc1.top/Article/details/gt2jcorimla.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.dianchejie.cn/Article/details/gt2umobagmb.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.birdmap.top/Article/details/gt2gkbwcpgx.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.havefunace.top/Article/details/gt2lqrgytgm.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.meibo888.top/Article/details/gt2hwglvpbw.html

[E06] 替换子串
来源：http://dali.xuetiantiany.cn/Article/details/gt2guoivxen.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.wangdashe.top/Article/details/gt2buzwrgcb.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.chenlongwang.top/Article/details/gt2zcpetcrv.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gt2vgdyaihq.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hnqzz.top/Article/details/gt2kviedwyd.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.fengsongda.top/Article/details/gt2huliacjv.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ehwqpu.com/Article/details/gt2shyfokhw.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wkivqhuz.html

C#:   s.Replace("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gt2eosxvdmx.html

[E07] 按分隔符拆分
来源：http://dali.wangdashe.top/Article/details/gt2fbmkbmpn.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.dianchejie.cn/Article/details/gt2ebcmnrap.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gt2kncgsglo.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ivvv.top/Article/details/gt2tepbbdas.html

TS:   s.split(",")
来源：http://dali.nanxuanxn.top/Article/details/gt2psqcnove.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.daxiang520.top/Article/details/gt2zbswxewy.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.0kj1m.cn/Article/details/gt2dpxzaqoq.html

Ruby: s.split(",");  s.split
来源：http://dali.yanxiufei.cn/Article/details/gt2ywhafxxt.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.c1oappe.top/Article/details/gt2tbjwegbc.html

[E08] 数组按分隔符合并
来源：http://dali.birdmap.top/Article/details/gt2saatlavg.html

Py:   ",".join(items)
来源：http://dali.gogol.net.cn/Article/details/gt2ctmtrmuh.html

PHP:  implode(",", $items);
来源：http://dali.sweek.top/Article/details/gt2fzakzulh.html

JS:   items.join(",")
来源：http://dali.quarkkingdee.top/Article/details/gt2kcxmjllt.html

TS:   items.join(",")
来源：http://dali.dashuyun.cn/Article/details/gt2nalohthf.html

Java: String.join(",", items)
来源：http://dali.ydzc1.top/Article/details/gt2ufgzecqv.html

Go:   strings.Join(items, ",")
来源：http://dali.jyoumei.cn/Article/details/gt2gekcuodu.html

Ruby: items.join(",")
来源：http://dali.feifeiyinyue.top/Article/details/gt2zqzbraeb.html

C#:   string.Join(",", items)
来源：http://dali.daxiang520.top/Article/details/gt2rghayurd.html

[E09] 去除所有空白字符
来源：http://dali.cashguo.top/Article/details/gt2jpulsjmn.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.tianlin.xyz/Article/details/gt2vwinhuxd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.wangdashe.top/Article/details/gt2uouatfjq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gborgewf.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2ethybpqi.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ygisxjds.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shzxlz.cn/Article/details/gt2txodcwsa.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.iojbl.cn/Article/details/gt2fjixsrup.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ogwhhxmf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qkwvmujq.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.daxiang520.top/Article/details/gt2paqbatcu.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.iojbl.cn/Article/details/gt2csnguhsg.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhongyouzk.top/Article/details/gt2icdzrgbb.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinqigfzy.top/Article/details/gt2ftbhiqih.html

Java: String.format("%03d", 7)
来源：http://dali.cashguo.top/Article/details/gt2zeotdphg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cheryme.top/Article/details/gt2qnwohoie.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.redwolf501.top/Article/details/gt2oeewrpnn.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.bjfxy.top/Article/details/gt2clhsbxgl.html

[E11] 反转字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2hwguejaj.html

Py:   s[::-1]
来源：http://dali.jiagoushi.top/Article/details/gt2xvrltjxf.html

PHP:  strrev($s);
来源：http://dali.aibaodan.cn/Article/details/gt2vwlrzazo.html

JS:   [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gt2szgfnrhx.html

TS:   [...s].reverse().join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2deqvwgaf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ehwqpu.com/Article/details/gt2psztrkoo.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ehwqpu.com/Article/details/gt2vivvytak.html

Ruby: s.reverse
来源：http://dali.yongpay.top/Article/details/gt2yomstgeh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cqqwz.cn/Article/details/gt2rpfuezqo.html

[E12] 统计某字符出现次数
来源：http://dali.ivvv.top/Article/details/gt2lhyhgbdu.html

Py:   s.count("a")
来源：http://dali.andypj.xyz/Article/details/gt2stpgmcpn.html

PHP:  substr_count($s, "a");
来源：http://dali.yonumen.top/Article/details/gt2suholjxs.html

JS:   s.split("a").length - 1
来源：http://dali.jlsjyb.cn/Article/details/gt2ngjkhmkf.html

TS:   s.split("a").length - 1
来源：http://dali.cqqwz.cn/Article/details/gt2aapydkjg.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yj20258.top/Article/details/gt2qtryjorz.html

Go:   strings.Count(s, "a")
来源：http://dali.cdnleiting.top/Article/details/gt2gqplcroj.html

Ruby: s.count("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2itxhsoaf.html

C#:   s.Count(c => c == 'a')
来源：http://dali.nanxuanxn.top/Article/details/gt2qbmfculu.html

[E13] 逐字符遍历
来源：http://dali.meibo888.top/Article/details/gt2cjltvwug.html

Py:   for ch in s: print(ch)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oflyvqaa.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sufxvd.cn/Article/details/gt2wrujqjkh.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jiagoushi.top/Article/details/gt2qtleotuu.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gt2mdipdwhy.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yvedp.cn/Article/details/gt2rwfzsrsz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.havefunace.top/Article/details/gt2qetteepj.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.guannengcc.top/Article/details/gt2xqmlgqjb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hysaishi.cn/Article/details/gt2uoasaxly.html

[E14] URL 编码与 Base64
来源：http://dali.shangyingyoupin.top/Article/details/gt2egvniqda.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.c1oappe.top/Article/details/gt2tjbjxtig.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2smxszdas.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.tian-w.cn/Article/details/gt2nhzptdxk.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2aptgykwo.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.quarkkingdee.top/Article/details/gt2fgohlqfw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xylfe.cn/Article/details/gt2suoehdaw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.gotoacloud.top/Article/details/gt2nlutwasn.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jianghu66.top/Article/details/gt2klkrnvmg.html

[E15] HTML 转义 / 反转义
来源：http://dali.yonumen.top/Article/details/gt2qiepgrzi.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sysykeji.top/Article/details/gt2jrpyxtth.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zycfv.cn/Article/details/gt2bitjetne.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yj202588.top/Article/details/gt2mwdboexo.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cheryme.top/Article/details/gt2hbgaibud.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhoulong.xyz/Article/details/gt2armrhlyt.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.aibaodan.cn/Article/details/gt2zpqfeeoe.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.meibo888.top/Article/details/gt2zxjqqtxx.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sufxvd.cn/Article/details/gt2zzozysqc.html

[E16] 数字千分位
来源：http://dali.yj202588.top/Article/details/gt2wboueofy.html

Py:   f"{1234567:,}"
来源：http://dali.smart0.xyz/Article/details/gt2dadjsfoy.html

PHP:  number_format(1234567);
来源：http://dali.zdqjudy.top/Article/details/gt2ynrrgcbp.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuetiantiany.cn/Article/details/gt2mgxuppqg.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.quarkkingdee.top/Article/details/gt2tzeflzcs.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.guannengcc.top/Article/details/gt2yshrxlkm.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sxryk.cn/Article/details/gt2nbafqgwk.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.fengsongda.top/Article/details/gt2ifldbgjq.html

C#:   1234567.ToString("N0")
来源：http://dali.haohaochexian.top/Article/details/gt2xyoecqqz.html

[E17] 首字母大写
来源：http://dali.ppjwa.cn/Article/details/gt2odeuztlt.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ppjwa.cn/Article/details/gt2jzgmrkvd.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hfpthk.cn/Article/details/gt2ildmeqof.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258.top/Article/details/gt2kvcbyoej.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jqgfzy.top/Article/details/gt2dsjgpmar.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2szvmtxaq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hgvxmjdh.html

Ruby: s.capitalize
来源：http://dali.zhoulong.xyz/Article/details/gt2ezoltomp.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.tanke756.top/Article/details/gt2dovddidn.html

[E18] 模板占位符替换
来源：http://dali.guowangkeji.top/Article/details/gt2girnrwbt.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hysaishi.cn/Article/details/gt2kqsadkka.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.meibo888.top/Article/details/gt2fdvxifjm.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hammf.cn/Article/details/gt2tosldaob.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.birdmap.top/Article/details/gt2klucjqnx.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xuanzx.com/Article/details/gt2ayxgbggs.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gt2pkzjunen.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xuanzx.com/Article/details/gt2cisytkbv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.meibo888.top/Article/details/gt2ssirsoat.html

[E19] 多行文本按行拆分
来源：http://dali.meibo888.top/Article/details/gt2svrhnecq.html

Py:   s.splitlines()
来源：http://dali.kuanghao11.cn/Article/details/gt2jksulzin.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.dashuyun.cn/Article/details/gt2xeukgest.html

JS:   s.split(/\r?\n/)
来源：http://dali.hongshengwenyu.top/Article/details/gt2fougtgrm.html

TS:   s.split(/\r?\n/)
来源：http://dali.xziqi.cn/Article/details/gt2vmoizftq.html

Java: s.lines().toList()
来源：http://dali.shzxlz.cn/Article/details/gt2geewzxdy.html

Go:   strings.Split(s, "\n")
来源：http://dali.andypj.xyz/Article/details/gt2tsealmgb.html

Ruby: s.lines
来源：http://dali.ydzc1.top/Article/details/gt2cfqxgkwh.html

C#:   s.Split('\n')
来源：http://dali.fengsongda.top/Article/details/gt2ndsaecjy.html

[E20] 判断字符串是否为空
来源：http://dali.pycfn.com/Article/details/gt2bdgtamig.html

Py:   if not s:
来源：http://dali.yueranfly.top/Article/details/gt2ppbhtsuh.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hoijdbkz.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yongpay.top/Article/details/gt2bxsmxzqv.html

TS:   if (s === "") {}
来源：http://dali.aizwys.cn/Article/details/gt2peuwslac.html

Java: if (s.isEmpty()) {}
来源：http://dali.jyoumei.cn/Article/details/gt2tufzrvwm.html

Go:   if s == "" {}
来源：http://dali.iojbl.cn/Article/details/gt2plmaxppr.html

Ruby: if s.empty?
来源：http://dali.nanxinkj.top/Article/details/gt2jirhfnjx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.aibaodan.cn/Article/details/gt2akczywuv.html

[E21] 超长截断加省略号
来源：http://dali.bjfxy.top/Article/details/gt2autbkhfr.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.bjfxy.top/Article/details/gt2jwmlfpeu.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2kbndgwxm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gt2zxohhqlq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xuanzx.com/Article/details/gt2ojflmbjb.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yuxming.cn/Article/details/gt2oryhwmmz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.guannengcc.top/Article/details/gt2pcrsjtbz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.tian-w.cn/Article/details/gt2ftjgbroe.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.daxiang520.top/Article/details/gt2njmtxrbs.html

[E22] 字节长度与字符长度
来源：http://dali.xinyue.icu/Article/details/gt2hanzmojg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2yxecebzj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kacsvwzl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ehwqpu.com/Article/details/gt2zkaeockv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pengpengdd.cyou/Article/details/gt2xmkumprs.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.aibaodan.cn/Article/details/gt2sputruis.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.bjfxy.top/Article/details/gt2bfviptpl.html

Ruby: s.bytesize;  s.length
来源：http://dali.xuetiantiany.cn/Article/details/gt2xmtyqouq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.pengpengdd.cyou/Article/details/gt2blepptnm.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2gqlywltv.html

F. 文件与目录
来源：http://dali.cdnleiting.top/Article/details/gt2gbvkotdm.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2gglntbkc.html

[F01] 读取整个文件
来源：http://dali.hammf.cn/Article/details/gt2lmuxghaj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sweek.top/Article/details/gt2fogfksui.html

PHP:  file_get_contents("a.txt");
来源：http://dali.wangdashe.top/Article/details/gt2olwmbzmj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zdqjudy.top/Article/details/gt2cgkdgkiy.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yonumen.top/Article/details/gt2jbdvwmfz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gt2nmvircpg.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhongyouzk.top/Article/details/gt2hfhgvpfx.html

Ruby: File.read("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2bvgpmgbw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.tanke756.top/Article/details/gt2mgdbmqsy.html

[F02] 逐行读取文件
来源：http://dali.sxryk.cn/Article/details/gt2czrvllvj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhongyouzk.top/Article/details/gt2zpxhorue.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.andypj.xyz/Article/details/gt2qyzjzglh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnqzz.top/Article/details/gt2ecjtodrm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.aizwys.cn/Article/details/gt2nwwnajbd.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vkomiona.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhoulong.xyz/Article/details/gt2fezpyysi.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iqxmmstl.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ehwqpu.com/Article/details/gt2ywbxltio.html

[F03] 写入文件（覆盖）
来源：http://dali.cheryme.top/Article/details/gt2nvnpflpi.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.gzhubu.top/Article/details/gt2hvpbvsim.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shzxlz.cn/Article/details/gt2wjjlfuxr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgfzy.top/Article/details/gt2tjtqyzoy.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ydzc1.top/Article/details/gt2liiaazfq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.nanxinkj.top/Article/details/gt2eghgqjqj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.haohaochexian.top/Article/details/gt2nxttjohu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jqgufenzy.top/Article/details/gt2wgiiyzxc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gaohongyu789.top/Article/details/gt2kwkgmznt.html

[F04] 追加写入文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2mueytian.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ijksszve.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.gogol.net.cn/Article/details/gt2jxdrfswl.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxuanxn.top/Article/details/gt2xbdvgtcf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.snrcjt.cn/Article/details/gt2bpbicwyw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xinyue.icu/Article/details/gt2htmhiqgo.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gt2fqaptkrz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.kuanghao11.cn/Article/details/gt2zwgnvmrc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.vqdsnc.cn/Article/details/gt2fmlllutr.html

[F05] 判断文件或目录是否存在
来源：http://dali.shuidangran.top/Article/details/gt2bqkyzjya.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cashguo.top/Article/details/gt2tmuswpmq.html

PHP:  file_exists("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2aadubniw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2jmojldzo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2isrosobx.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gt2jdchzeij.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xinyue.icu/Article/details/gt2dewwmmik.html

Ruby: File.exist?("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2wpsqvmvu.html


<!-- 参考信息 -->