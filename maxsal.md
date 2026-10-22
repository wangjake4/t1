代发 wailian999

PHP:  in_array($x, $arr, true);
来源：http://dali.yanxiufei.cn/Article/details/gtawchdfzo.html

JS:   arr.includes(x)
来源：http://dali.meibo888.top/Article/details/gtruhijzym.html

TS:   arr.includes(x)
来源：http://dali.iojbl.cn/Article/details/gtlrsvfftt.html

Java: list.contains(x)
来源：http://dali.xuanzx.com/Article/details/gthegvqzwc.html

Go:   slices.Contains(arr, x)
来源：http://dali.jianghu66.top/Article/details/gtukgevqct.html

Ruby: arr.include?(x)
来源：http://dali.zhongyouzk.top/Article/details/gtceyqoaqt.html

C#:   list.Contains(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtubazyjqr.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cdnleiting.top/Article/details/gtllnxjkzz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.guowangkeji.top/Article/details/gttppctkez.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.aizwys.cn/Article/details/gtaejeokhv.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cdnleiting.top/Article/details/gtrmkqmrdk.html

TS:   [...arr];
来源：http://dali.cqqwz.cn/Article/details/gtzwqobqrw.html

Java: new ArrayList<>(list);
来源：http://dali.sweek.top/Article/details/gtzdsrjzax.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cdnleiting.top/Article/details/gtdrcmglka.html

Ruby: arr.dup;  arr.clone
来源：http://dali.fengsongda.top/Article/details/gtfxhtnroe.html

C#:   new List<int>(list);
来源：http://dali.tian-w.cn/Article/details/gtzgatwsfs.html

[D23] reduce 累积计算
来源：http://dali.tianlin.xyz/Article/details/gtuzxocmrj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwznzltbr.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hfpthk.cn/Article/details/gtpafjbnir.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nwbrower.top/Article/details/gthjxwxvtb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cdnleiting.top/Article/details/gtulluwnkb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shzxlz.cn/Article/details/gtgvtbvqqg.html

Go:   // 手写循环
来源：http://dali.jiagoushi.top/Article/details/gtaqnumisj.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yuanzhike.top/Article/details/gtnambbfgh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yj20258888.top/Article/details/gtreqlcnmo.html

[D24] 字典 / Map 基本操作
来源：http://dali.pycfn.com/Article/details/gtiigfduqn.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xziqi.cn/Article/details/gtysfheafp.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.iojbl.cn/Article/details/gtnjhsaogz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.haohaochexian.top/Article/details/gtrpnvqfga.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.pycfn.com/Article/details/gtyyyglehi.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hywenlv.cn/Article/details/gtjyftsjyy.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.chenjidiqi.icu/Article/details/gtkoumfnqi.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhoulong.xyz/Article/details/gtuicobidd.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cdnleiting.top/Article/details/gteqgffoat.html

[D25] Set 集合去重与交并差
来源：http://dali.gzhubu.top/Article/details/gtjcclklkm.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.birdmap.top/Article/details/gtgfbekifr.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.birdmap.top/Article/details/gtizbtheke.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.gotoacloud.top/Article/details/gtoxsuhapj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.sufxvd.cn/Article/details/gtfwgyzcds.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.chenzaomai.com/Article/details/gtwjlngcef.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hywenlv.cn/Article/details/gtiifjlveg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hywenlv.cn/Article/details/gtogolwwpa.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hysaishi.cn/Article/details/gtxilyvjbz.html

[D26] 数组转字符串
来源：http://dali.nanxuanxn.top/Article/details/gtjhxhhtlf.html

Py:   ", ".join(map(str, arr))
来源：http://dali.meibo888.top/Article/details/gtfmzcvajc.html

PHP:  implode(", ", $arr);
来源：http://dali.vqdsnc.cn/Article/details/gtqctmpxte.html

JS:   arr.join(", ")
来源：http://dali.hongshengwenyu.top/Article/details/gtotrauyct.html

TS:   arr.join(", ")
来源：http://dali.tanke756.top/Article/details/gtmgrccmlo.html

Java: String.join(", ", list)
来源：http://dali.sysykeji.top/Article/details/gtnllbgnec.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhongyouzk.top/Article/details/gthtxrvces.html

Ruby: arr.join(", ")
来源：http://dali.shangyingyoupin.top/Article/details/gttlmatytp.html

C#:   string.Join(", ", list)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtohiallwy.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtplbvgcqo.html

E. 字符串处理
来源：http://dali.jqgfzy.top/Article/details/gtvwdzdeeb.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtxnbsbfmq.html

[E01] 拼接字符串
来源：http://dali.cheryme.top/Article/details/gtrjritkbt.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.dashuyun.cn/Article/details/gtcigjwbhb.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.cqqwz.cn/Article/details/gtmjsbmztr.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnqzz.top/Article/details/gtldlnpocy.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gtfdcjgahl.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.redwolf501.top/Article/details/gtvqunrlkj.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jqgfzy.top/Article/details/gtuvzsxmsh.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gtadszflop.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gttlilqqpg.html

[E02] 重复字符串
来源：http://dali.nwbrower.top/Article/details/gtwxuevaga.html

Py:   "ab" * 3
来源：http://dali.shanyushiyangkeji.top/Article/details/gtncvwgjjs.html

PHP:  str_repeat("ab", 3);
来源：http://dali.dashuyun.cn/Article/details/gtfetlriee.html

JS:   "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gtsifsdzza.html

TS:   "ab".repeat(3)
来源：http://dali.tanke756.top/Article/details/gtczevhday.html

Java: "ab".repeat(3)
来源：http://dali.yuanzhike.top/Article/details/gtotqsyprf.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.guowangkeji.top/Article/details/gtfrslbqlj.html

Ruby: "ab" * 3
来源：http://dali.chenzaomai.com/Article/details/gtoofsjdjc.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtliejixuz.html

[E03] 截取子串
来源：http://dali.zhengqikj.top/Article/details/gtancvnqvg.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.fzhhl.top/Article/details/gtmigoqzov.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gtghibnfnv.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.snrcjt.cn/Article/details/gtcvgaildm.html

TS:   s.slice(1, 4)
来源：http://dali.yj20258.top/Article/details/gtcyejspwo.html

Java: s.substring(1, 4)
来源：http://dali.ehwqpu.com/Article/details/gtewpmydzq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.aibaodan.cn/Article/details/gtxznaylpr.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cucudq.cn/Article/details/gttfbjkmqg.html

C#:   s.Substring(1, 3)
来源：http://dali.yueranfly.top/Article/details/gtrvbtkcwt.html

[E04] 查找子串位置
来源：http://dali.hysaishi.cn/Article/details/gtqadsuhft.html

Py:   s.find("x");  s.index("x")
来源：http://dali.svipenyu.cn/Article/details/gtmdxbarvi.html

PHP:  strpos($s, "x");
来源：http://dali.jyoumei.cn/Article/details/gtpfjhmija.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthybmeapi.html

TS:   s.indexOf("x")
来源：http://dali.shzxlz.cn/Article/details/gtsgleejkl.html

Java: s.indexOf("x")
来源：http://dali.yj202588.top/Article/details/gtaujyufnk.html

Go:   strings.Index(s, "x")
来源：http://dali.sxryk.cn/Article/details/gtuezxnvus.html

Ruby: s.index("x")
来源：http://dali.yanxiufei.cn/Article/details/gtaautjifr.html

C#:   s.IndexOf("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrkfmzhat.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.aizwys.cn/Article/details/gtjmehmhim.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.havefunace.top/Article/details/gthehbyfxw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xinyue.icu/Article/details/gtotslxdao.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yangfankeji.com/Article/details/gttamelavt.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.havefunace.top/Article/details/gtvmkifzby.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gtvhayrunw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.wangdashe.top/Article/details/gtveqgsunv.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhijiandao.cn/Article/details/gtcwsnbkmg.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.dashuyun.cn/Article/details/gtxilqekcq.html

[E06] 替换子串
来源：http://dali.gogol.net.cn/Article/details/gtmbpxbnyl.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtutnbvrjy.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cheryme.top/Article/details/gtcxokkrwt.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tian-w.cn/Article/details/gtrjakudvf.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gtfshqnysa.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gzhubu.top/Article/details/gtdyodqvkp.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zdqjudy.top/Article/details/gtrwkhbtga.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.birdmap.top/Article/details/gtewzlfcrq.html

C#:   s.Replace("a", "b")
来源：http://dali.sweek.top/Article/details/gtmwunuidy.html

[E07] 按分隔符拆分
来源：http://dali.meibo888.top/Article/details/gtdoumkywt.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yueranfly.top/Article/details/gtuxlgwscs.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.birdmap.top/Article/details/gtxlbhhkfz.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhengqikj.top/Article/details/gtiqhmiiqb.html

TS:   s.split(",")
来源：http://dali.daxiang520.top/Article/details/gtpzwrxxrz.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.daria6918.cn/Article/details/gthqcstphq.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yonumen.top/Article/details/gtoxerccaa.html

Ruby: s.split(",");  s.split
来源：http://dali.jyoumei.cn/Article/details/gttgiwawoq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtanibsxmt.html

[E08] 数组按分隔符合并
来源：http://dali.andypj.xyz/Article/details/gtpkehwuxi.html

Py:   ",".join(items)
来源：http://dali.xinyue.icu/Article/details/gtlahvwgod.html

PHP:  implode(",", $items);
来源：http://dali.yj20258888.top/Article/details/gtbagvnskx.html

JS:   items.join(",")
来源：http://dali.gzhubu.top/Article/details/gtjqvilaan.html

TS:   items.join(",")
来源：http://dali.fzhhl.top/Article/details/gtnkzeoerx.html

Java: String.join(",", items)
来源：http://dali.yangfankeji.com/Article/details/gtfmachnjv.html

Go:   strings.Join(items, ",")
来源：http://dali.pycfn.com/Article/details/gtdydfqmii.html

Ruby: items.join(",")
来源：http://dali.zhongyouzk.top/Article/details/gtagmlgmtm.html

C#:   string.Join(",", items)
来源：http://dali.dianchejie.cn/Article/details/gtdiazcsig.html

[E09] 去除所有空白字符
来源：http://dali.gaohongyu789.top/Article/details/gtmqmfdsoj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jqgfzy.top/Article/details/gtjixsjccv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtwmluznsh.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.0kj1m.cn/Article/details/gtduucznyc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yueranfly.top/Article/details/gtxugteyey.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.kuanghao11.cn/Article/details/gtwurysjrj.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sufxvd.cn/Article/details/gtccocljij.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyvrewywd.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xinyue.icu/Article/details/gtsotcrpbe.html

[E10] 左侧补零 / 定长填充
来源：http://dali.pengpengdd.cyou/Article/details/gtqglzwuqb.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.gaohongyu789.top/Article/details/gtklnvxkmv.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yangfankeji.com/Article/details/gtcwhnvkam.html

JS:   "7".padStart(3, "0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdeyagimc.html

TS:   "7".padStart(3, "0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpoltfjzz.html

Java: String.format("%03d", 7)
来源：http://dali.yuanzhike.top/Article/details/gthbgnchwe.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yueranfly.top/Article/details/gtgrcvccsm.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.wangshuangyany.cn/Article/details/gtwhqslkti.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yonumen.top/Article/details/gtbczugpyf.html

[E11] 反转字符串
来源：http://dali.ydzc1.top/Article/details/gtjqdotdhv.html

Py:   s[::-1]
来源：http://dali.0kj1m.cn/Article/details/gtsnhzguvu.html

PHP:  strrev($s);
来源：http://dali.yonumen.top/Article/details/gtoxqftrje.html

JS:   [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gtskzaexhg.html

TS:   [...s].reverse().join("")
来源：http://dali.cheryme.top/Article/details/gtbzuzuvpe.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbpmtslgm.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yj20258.top/Article/details/gtlddmnkhv.html

Ruby: s.reverse
来源：http://dali.xuanzx.com/Article/details/gtaiazrqld.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhengqikj.top/Article/details/gtllgwrifg.html

[E12] 统计某字符出现次数
来源：http://dali.svipenyu.cn/Article/details/gtwrznqikw.html

Py:   s.count("a")
来源：http://dali.shangyingyoupin.top/Article/details/gtfupmydwj.html

PHP:  substr_count($s, "a");
来源：http://dali.ybcxt.top/Article/details/gtxduwxfrz.html

JS:   s.split("a").length - 1
来源：http://dali.jqgfzy.top/Article/details/gteiulxpgk.html

TS:   s.split("a").length - 1
来源：http://dali.xinyue.icu/Article/details/gtuslwdamn.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yangfankeji.com/Article/details/gtldganpty.html

Go:   strings.Count(s, "a")
来源：http://dali.guannengcc.top/Article/details/gtwwxgbbeb.html

Ruby: s.count("a")
来源：http://dali.mhx1999.top/Article/details/gtkqagkyxy.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hywenlv.cn/Article/details/gtpeunexzh.html

[E13] 逐字符遍历
来源：http://dali.tianlin.xyz/Article/details/gtkozbnffm.html

Py:   for ch in s: print(ch)
来源：http://dali.zycfv.cn/Article/details/gtfkrmfrje.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xylfe.cn/Article/details/gtoulxfawl.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daxiang520.top/Article/details/gtortgkyek.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daxiang520.top/Article/details/gtgekpsvzv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.c1oappe.top/Article/details/gtqyjcypex.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hysaishi.cn/Article/details/gtprsusfei.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gtsdrgsxks.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hysaishi.cn/Article/details/gtkykzhkgp.html

[E14] URL 编码与 Base64
来源：http://dali.ybcxt.top/Article/details/gtiyggiscg.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yuanzhike.top/Article/details/gtjiajtmms.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.iojbl.cn/Article/details/gtmyjqwyro.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.chenlongwang.top/Article/details/gtmxdxewqj.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hywenlv.cn/Article/details/gtnslikmmg.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.guannengcc.top/Article/details/gtamavbvcz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zdqjudy.top/Article/details/gtacijujol.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.nanxuanxn.top/Article/details/gtnmgfcmbk.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cdnleiting.top/Article/details/gtoxeyrghz.html

[E15] HTML 转义 / 反转义
来源：http://dali.sweek.top/Article/details/gtgbilaida.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.havefunace.top/Article/details/gtlgwezogw.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yueranfly.top/Article/details/gtetymhmpf.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xylfe.cn/Article/details/gtcjimwoxb.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.tianlin.xyz/Article/details/gtznonlsma.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.nanxuanxn.top/Article/details/gtgmquzlaq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cashguo.top/Article/details/gtnoydzwom.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yonumen.top/Article/details/gtyztrczra.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.gogol.net.cn/Article/details/gtfokxikjo.html

[E16] 数字千分位
来源：http://dali.tianlin.xyz/Article/details/gtszjcypoi.html

Py:   f"{1234567:,}"
来源：http://dali.chenzaomai.com/Article/details/gtdmbtommi.html

PHP:  number_format(1234567);
来源：http://dali.dianchejie.cn/Article/details/gtelfklihx.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jyoumei.cn/Article/details/gtbvwhlqev.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.vqdsnc.cn/Article/details/gtdnnrpauw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhengqikj.top/Article/details/gtfntzvcfx.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hywenlv.cn/Article/details/gtircjfelw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cdnleiting.top/Article/details/gttcaykpap.html

C#:   1234567.ToString("N0")
来源：http://dali.xylfe.cn/Article/details/gtxsrvousn.html

[E17] 首字母大写
来源：http://dali.jlsjyb.cn/Article/details/gtndwtyqlq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.tanke756.top/Article/details/gtpcenqzib.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.aibaodan.cn/Article/details/gtdkllbqpp.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pycfn.com/Article/details/gtsmxrmeln.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.bjfxy.top/Article/details/gtmrlbuoep.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttbtuobhf.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.guowangkeji.top/Article/details/gtbqtnfoyc.html

Ruby: s.capitalize
来源：http://dali.sysykeji.top/Article/details/gtcmkcfuap.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hysaishi.cn/Article/details/gthprxswrj.html

[E18] 模板占位符替换
来源：http://dali.hammf.cn/Article/details/gtgozrvrmm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.chenzaomai.com/Article/details/gtwnxvxopz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yj202588.top/Article/details/gtcyfpdqdk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjcdbmczu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.birdmap.top/Article/details/gtqmktsdsa.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gtpxllhqdu.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gtarstbflz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yueranfly.top/Article/details/gtwzhczigp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfvoacmfo.html

[E19] 多行文本按行拆分
来源：http://dali.yj20258888.top/Article/details/gtfkbvjhmt.html

Py:   s.splitlines()
来源：http://dali.chenzaomai.com/Article/details/gtbkegtbee.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinqigufen.top/Article/details/gtfgswtogs.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhengqikj.top/Article/details/gtspqpodaf.html

TS:   s.split(/\r?\n/)
来源：http://dali.c1oappe.top/Article/details/gtcscvyban.html

Java: s.lines().toList()
来源：http://dali.quarkkingdee.top/Article/details/gtixqyhlpg.html

Go:   strings.Split(s, "\n")
来源：http://dali.iojbl.cn/Article/details/gtotrehdws.html

Ruby: s.lines
来源：http://dali.hnxiangtu.top/Article/details/gtmldjllnt.html

C#:   s.Split('\n')
来源：http://dali.ivvv.top/Article/details/gtfqctjnrl.html

[E20] 判断字符串是否为空
来源：http://dali.snrcjt.cn/Article/details/gtdipzkype.html

Py:   if not s:
来源：http://dali.yonumen.top/Article/details/gtytrkrvqn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.vqdsnc.cn/Article/details/gtgjmjjagx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmbiuejta.html

TS:   if (s === "") {}
来源：http://dali.9152youxi.cn/Article/details/gtcrdkoztw.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gtknvufizn.html

Go:   if s == "" {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtitnpngxc.html

Ruby: if s.empty?
来源：http://dali.zycfv.cn/Article/details/gtqjligkpk.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xuanzx.com/Article/details/gtudjadehs.html

[E21] 超长截断加省略号
来源：http://dali.ivvv.top/Article/details/gtthlrpiqt.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvslblygx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.birdmap.top/Article/details/gtdkagaeph.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xziqi.cn/Article/details/gtpyrlvzol.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gtknyqpfst.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.smart0.xyz/Article/details/gtczpsiahw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cqqwz.cn/Article/details/gtumlhrdhh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xinyue.icu/Article/details/gtalajcmrj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtvekfwyqb.html

[E22] 字节长度与字符长度
来源：http://dali.vqdsnc.cn/Article/details/gtivhrppod.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yangfankeji.com/Article/details/gtwecogooz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.redwolf501.top/Article/details/gtipbmkqds.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cheryme.top/Article/details/gtienxhesh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.snrcjt.cn/Article/details/gtkzuipcif.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.daxiang520.top/Article/details/gtcgwfhutd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.daria6918.cn/Article/details/gtvyqqxtxo.html

Ruby: s.bytesize;  s.length
来源：http://dali.ydzc1.top/Article/details/gtlflncbdu.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinqigfzy.top/Article/details/gtychwimal.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtfkmijuin.html

F. 文件与目录
来源：http://dali.wangshuangyany.cn/Article/details/gtjwjnwjgf.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtzfwpvvdd.html

[F01] 读取整个文件
来源：http://dali.haohaochexian.top/Article/details/gtzkhnnsga.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sufxvd.cn/Article/details/gtrwmnmvdp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.daria6918.cn/Article/details/gtiqkaqflz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yvedp.cn/Article/details/gtyljpkoue.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yj20258.top/Article/details/gtibqzybbm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtsftwlyty.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hnqzz.top/Article/details/gtroovkhuw.html

Ruby: File.read("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtrabirnah.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtqjiljvbw.html

[F02] 逐行读取文件
来源：http://dali.fzhhl.top/Article/details/gtjitzcxly.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.gotoacloud.top/Article/details/gtnwiffrui.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zycfv.cn/Article/details/gtofrwcsvj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xylfe.cn/Article/details/gtnnouknlv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yueranfly.top/Article/details/gtcrpewdbk.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.aibaodan.cn/Article/details/gtmllrdxpm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.havefunace.top/Article/details/gtrfjzchbp.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkhvwkutb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hnxiangtu.top/Article/details/gtaqrvhwwn.html

[F03] 写入文件（覆盖）
来源：http://dali.ivvv.top/Article/details/gttyojjmfj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.gzhubu.top/Article/details/gtebrygcdl.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yangfankeji.com/Article/details/gtiuhxgacg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.quarkkingdee.top/Article/details/gtbwxlpvta.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sxryk.cn/Article/details/gtjjxmmtgb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jyoumei.cn/Article/details/gtqlmwdyzk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cqqwz.cn/Article/details/gtfgvpgwva.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hnxiangtu.top/Article/details/gthvfbngao.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ydzc1.top/Article/details/gtjlzvussr.html

[F04] 追加写入文件
来源：http://dali.sweek.top/Article/details/gtbpdquscy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.andypj.xyz/Article/details/gttwnsvvix.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yanxiufei.cn/Article/details/gtwxcqpunl.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenlongwang.top/Article/details/gtiejqulnl.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dashuyun.cn/Article/details/gtaxtuzncs.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cqqwz.cn/Article/details/gtzllghrka.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cqqwz.cn/Article/details/gtpfovyppc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hysaishi.cn/Article/details/gthkfbscle.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xylfe.cn/Article/details/gturyyzwjb.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhengqikj.top/Article/details/gtbvududtb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhongyouzk.top/Article/details/gtyyduaewg.html

PHP:  file_exists("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtxbgfikkn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtjtllxrks.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtliudlqeg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gtprcnuwfs.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdksfwzir.html

Ruby: File.exist?("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gthazaytnr.html


<!-- 参考信息 -->