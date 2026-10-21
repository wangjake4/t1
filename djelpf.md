代发 wailian999

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gogol.net.cn/Article/details/gtuutqfudm.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yongpay.top/Article/details/gtmorgzgkk.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.aibaodan.cn/Article/details/gtutswafwx.html

TS:   [...arr];
来源：http://dali.jqgfzy.top/Article/details/gtstiymhpj.html

Java: new ArrayList<>(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gticnzokao.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gotoacloud.top/Article/details/gtkmmwiyyc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.dianchejie.cn/Article/details/gtzyioxppp.html

C#:   new List<int>(list);
来源：http://dali.hnxiangtu.top/Article/details/gtpqkkcppj.html

[D23] reduce 累积计算
来源：http://dali.dianchejie.cn/Article/details/gtgzcvenef.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hysaishi.cn/Article/details/gtvifhtfez.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.fengsongda.top/Article/details/gtbakklywe.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.andypj.xyz/Article/details/gtbghosezr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gotoacloud.top/Article/details/gtakcuethf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sxryk.cn/Article/details/gtctzlxzpd.html

Go:   // 手写循环
来源：http://dali.zhixingplan.top/Article/details/gtbnacfgbg.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.aibaodan.cn/Article/details/gtivxpxamv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jiagoushi.top/Article/details/gtbhftyaoi.html

[D24] 字典 / Map 基本操作
来源：http://dali.guowangkeji.top/Article/details/gtgldusdqw.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhixingplan.top/Article/details/gtbegnmjpp.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.daria6918.cn/Article/details/gtvyunmytm.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yuanzhike.top/Article/details/gtbrfszeou.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.guowangkeji.top/Article/details/gtieapspwy.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.vqdsnc.cn/Article/details/gtgqzmwtnp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.nanxinkj.top/Article/details/gtemfuczzb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jianghu66.top/Article/details/gtyvixlipw.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinqigufen.top/Article/details/gtzmnfjmko.html

[D25] Set 集合去重与交并差
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsroowjqd.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ivvv.top/Article/details/gtscarapzi.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfkfpndnp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.wangdashe.top/Article/details/gtosjbpslg.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ehwqpu.com/Article/details/gtymajvdfw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.chenzaomai.com/Article/details/gtiisbqsgd.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tian-w.cn/Article/details/gtxdjjinjh.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhixingplan.top/Article/details/gtsqpwrkvg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.sufxvd.cn/Article/details/gtfbitsirh.html

[D26] 数组转字符串
来源：http://dali.ydzc1.top/Article/details/gtfjgpnppi.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jqgfzy.top/Article/details/gtihcxipuq.html

PHP:  implode(", ", $arr);
来源：http://dali.xylfe.cn/Article/details/gtvigvfvuf.html

JS:   arr.join(", ")
来源：http://dali.sxryk.cn/Article/details/gtwzuservn.html

TS:   arr.join(", ")
来源：http://dali.jlsjyb.cn/Article/details/gtpsnorrkp.html

Java: String.join(", ", list)
来源：http://dali.cheryme.top/Article/details/gtufeaphsf.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jqgufenzy.top/Article/details/gtdctuyuop.html

Ruby: arr.join(", ")
来源：http://dali.cashguo.top/Article/details/gtykrzafsb.html

C#:   string.Join(", ", list)
来源：http://dali.svipenyu.cn/Article/details/gtijjltjxr.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtgotgozkw.html

E. 字符串处理
来源：http://dali.zhongyouzk.top/Article/details/gtdfxyavmd.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtytnuhyua.html

[E01] 拼接字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbyyopsiy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yvedp.cn/Article/details/gtjeyeytge.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yj20258.top/Article/details/gtwemffadl.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.iojbl.cn/Article/details/gtjdxffxzi.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.guowangkeji.top/Article/details/gtyhbymrbm.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yangfankeji.com/Article/details/gtjuxexzrz.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.iojbl.cn/Article/details/gtqyiyqbqd.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.wangshuangyany.cn/Article/details/gtmkvauznj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.birdmap.top/Article/details/gtlwmspskx.html

[E02] 重复字符串
来源：http://dali.daxiang520.top/Article/details/gtzifugbwl.html

Py:   "ab" * 3
来源：http://dali.chenlongwang.top/Article/details/gtcehxbqec.html

PHP:  str_repeat("ab", 3);
来源：http://dali.guannengcc.top/Article/details/gtmydqrlnw.html

JS:   "ab".repeat(3)
来源：http://dali.316326.xyz/Article/details/gtlpilsnmt.html

TS:   "ab".repeat(3)
来源：http://dali.shuidangran.top/Article/details/gtyeiefrqe.html

Java: "ab".repeat(3)
来源：http://dali.vqdsnc.cn/Article/details/gtsqnqnhwe.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.wangdashe.top/Article/details/gtahdalghm.html

Ruby: "ab" * 3
来源：http://dali.quarkkingdee.top/Article/details/gtlwnnimfa.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.nanxinkj.top/Article/details/gtncxhqnin.html

[E03] 截取子串
来源：http://dali.cdnleiting.top/Article/details/gtunnyddkr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.svipenyu.cn/Article/details/gtawrsfnla.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gtxybyeckn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.vqdsnc.cn/Article/details/gtltzuvbvi.html

TS:   s.slice(1, 4)
来源：http://dali.jiagoushi.top/Article/details/gtslevcenw.html

Java: s.substring(1, 4)
来源：http://dali.0kj1m.cn/Article/details/gtbdnotuar.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yj202588.top/Article/details/gtcxntgbge.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtayavbohd.html

C#:   s.Substring(1, 3)
来源：http://dali.kuanghao11.cn/Article/details/gtnaqmmhwu.html

[E04] 查找子串位置
来源：http://dali.jianghu66.top/Article/details/gtaxvxzfei.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jyoumei.cn/Article/details/gtyqxembbs.html

PHP:  strpos($s, "x");
来源：http://dali.c1oappe.top/Article/details/gtgdnwtcnv.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xuetiantiany.cn/Article/details/gtjmnmficx.html

TS:   s.indexOf("x")
来源：http://dali.xziqi.cn/Article/details/gtosthjfru.html

Java: s.indexOf("x")
来源：http://dali.mhx1999.top/Article/details/gthjkthesz.html

Go:   strings.Index(s, "x")
来源：http://dali.xziqi.cn/Article/details/gtwapzxrcu.html

Ruby: s.index("x")
来源：http://dali.tianlin.xyz/Article/details/gtyctrmwxr.html

C#:   s.IndexOf("x")
来源：http://dali.yj202588.top/Article/details/gtsuhutmos.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.c1oappe.top/Article/details/gtqkpfgnio.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.wangshuangyany.cn/Article/details/gtcfbojvob.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shzxlz.cn/Article/details/gtjpiwczum.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ydzc1.top/Article/details/gtrwuyrdel.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.wangshuangyany.cn/Article/details/gtrpkuwzfv.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yvedp.cn/Article/details/gtbatwbefe.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.316326.xyz/Article/details/gtofqehevq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhoulong.xyz/Article/details/gtwlxvsxyu.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jqgfzy.top/Article/details/gtfkowoxlc.html

[E06] 替换子串
来源：http://dali.nanxuanxn.top/Article/details/gtmefqssri.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.0kj1m.cn/Article/details/gtpijthwwk.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtujzfvrqe.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtbruxaqtw.html

TS:   s.replaceAll("a", "b")
来源：http://dali.aizwys.cn/Article/details/gtdaslpqhd.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtbqwzyalk.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.tanke756.top/Article/details/gtsitcsgks.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gtnlhfyxup.html

C#:   s.Replace("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gtlivappmx.html

[E07] 按分隔符拆分
来源：http://dali.zhijiandao.cn/Article/details/gtagaldetd.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.sysykeji.top/Article/details/gtyfvkxzxp.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtcdonyrrh.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj20258888.top/Article/details/gtxhxmufuc.html

TS:   s.split(",")
来源：http://dali.ehwqpu.com/Article/details/gtinrvpxve.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.gotoacloud.top/Article/details/gtbtpkkzti.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.bjfxy.top/Article/details/gtogjezdtg.html

Ruby: s.split(",");  s.split
来源：http://dali.c1oappe.top/Article/details/gtozadmvlu.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sysykeji.top/Article/details/gtnoivuvfg.html

[E08] 数组按分隔符合并
来源：http://dali.yonumen.top/Article/details/gthcntpdra.html

Py:   ",".join(items)
来源：http://dali.ydzc1.top/Article/details/gtotpehpmv.html

PHP:  implode(",", $items);
来源：http://dali.nanxuanxn.top/Article/details/gtppgnvqnl.html

JS:   items.join(",")
来源：http://dali.yj20258888.top/Article/details/gtcjajbyte.html

TS:   items.join(",")
来源：http://dali.yongpay.top/Article/details/gtssioetax.html

Java: String.join(",", items)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxhznrtgv.html

Go:   strings.Join(items, ",")
来源：http://dali.aibaodan.cn/Article/details/gtxvwbuwpn.html

Ruby: items.join(",")
来源：http://dali.ivvv.top/Article/details/gtgleumdpw.html

C#:   string.Join(",", items)
来源：http://dali.aibaodan.cn/Article/details/gtlylufafo.html

[E09] 去除所有空白字符
来源：http://dali.0kj1m.cn/Article/details/gtnzuhxzhm.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnwlrnfdw.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdgfxhpsn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xylfe.cn/Article/details/gtftbcccwg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuwsqrwtu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.guowangkeji.top/Article/details/gtyyooyaaq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sxryk.cn/Article/details/gtgvdgomtp.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yanxiufei.cn/Article/details/gtocplpgli.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.chenjidiqi.icu/Article/details/gtfgcslbju.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinqigfzy.top/Article/details/gtkcosiwyd.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvgjnkzyb.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ydzc1.top/Article/details/gtoeasfckd.html

JS:   "7".padStart(3, "0")
来源：http://dali.nanxinkj.top/Article/details/gtsofsuwwb.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzueabuzh.html

Java: String.format("%03d", 7)
来源：http://dali.daria6918.cn/Article/details/gtfrevijqa.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ybcxt.top/Article/details/gtkfxszhlg.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.daxiang520.top/Article/details/gtrgvowbhc.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.guowangkeji.top/Article/details/gtfbsmhqrq.html

[E11] 反转字符串
来源：http://dali.zhongyouzk.top/Article/details/gtdfunpkaa.html

Py:   s[::-1]
来源：http://dali.aibaodan.cn/Article/details/gttudltmon.html

PHP:  strrev($s);
来源：http://dali.pycfn.com/Article/details/gtkiykcwcq.html

JS:   [...s].reverse().join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtkgkrxptv.html

TS:   [...s].reverse().join("")
来源：http://dali.ivvv.top/Article/details/gtkkamidzi.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jyoumei.cn/Article/details/gtyvamxygh.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ppjwa.cn/Article/details/gtfmdlqlfg.html

Ruby: s.reverse
来源：http://dali.cucudq.cn/Article/details/gtyfzqalll.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yj202588.top/Article/details/gtpdcpobky.html

[E12] 统计某字符出现次数
来源：http://dali.yuxming.cn/Article/details/gtpusrginf.html

Py:   s.count("a")
来源：http://dali.0kj1m.cn/Article/details/gtweudlbzi.html

PHP:  substr_count($s, "a");
来源：http://dali.havefunace.top/Article/details/gtdozduruy.html

JS:   s.split("a").length - 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpnwpokgy.html

TS:   s.split("a").length - 1
来源：http://dali.yongpay.top/Article/details/gtcuuyqesv.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sysykeji.top/Article/details/gtujnualvt.html

Go:   strings.Count(s, "a")
来源：http://dali.zhongyouzk.top/Article/details/gtczarwpdr.html

Ruby: s.count("a")
来源：http://dali.yonumen.top/Article/details/gtzmrhysut.html

C#:   s.Count(c => c == 'a')
来源：http://dali.quarkkingdee.top/Article/details/gtldjtfjri.html

[E13] 逐字符遍历
来源：http://dali.ehwqpu.com/Article/details/gtdbhkinaa.html

Py:   for ch in s: print(ch)
来源：http://dali.ybcxt.top/Article/details/gtrpejyebq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gaohongyu789.top/Article/details/gtpivyxduh.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sweek.top/Article/details/gtmjgoaplk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaulnqwpx.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hywenlv.cn/Article/details/gtpxqorxxd.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.redwolf501.top/Article/details/gtexvudiwm.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgsawwgxa.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.chenzaomai.com/Article/details/gtcewfqhvd.html

[E14] URL 编码与 Base64
来源：http://dali.tian-w.cn/Article/details/gtnbmbkbbx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sufxvd.cn/Article/details/gtvrjqorlm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.smart0.xyz/Article/details/gtybyuknmi.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.svipenyu.cn/Article/details/gtuvwcpvzd.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.daxiang520.top/Article/details/gtqsvhecox.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhiwuduotai.top/Article/details/gtndbdsoci.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.pengpengdd.cyou/Article/details/gtvweumxmp.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xylfe.cn/Article/details/gtzjgwfxgk.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhongyouzk.top/Article/details/gtugtczysk.html

[E15] HTML 转义 / 反转义
来源：http://dali.jiagoushi.top/Article/details/gtjtukfbad.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.0kj1m.cn/Article/details/gtcxcszioq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gaohongyu789.top/Article/details/gtvxqyzsqe.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xylfe.cn/Article/details/gtdfadlhzc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gaohongyu789.top/Article/details/gtjgpjdgst.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.redwolf501.top/Article/details/gtkoubcfdy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jlsjyb.cn/Article/details/gtaoevbjwq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hywenlv.cn/Article/details/gtwnodfvzy.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.feifeiyinyue.top/Article/details/gttjedcqdz.html

[E16] 数字千分位
来源：http://dali.chenzaomai.com/Article/details/gtwwdxpiql.html

Py:   f"{1234567:,}"
来源：http://dali.jyoumei.cn/Article/details/gtdjtlxolo.html

PHP:  number_format(1234567);
来源：http://dali.xuetiantiany.cn/Article/details/gtrlqksgtx.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.tian-w.cn/Article/details/gtiukutagl.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj20258.top/Article/details/gtaiijdxio.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.nanxinkj.top/Article/details/gtneskzkyu.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.tian-w.cn/Article/details/gtyazthztk.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyitiskjg.html

C#:   1234567.ToString("N0")
来源：http://dali.jinqigufen.top/Article/details/gtooxxqpdb.html

[E17] 首字母大写
来源：http://dali.mhx1999.top/Article/details/gtpvsbqlhb.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hfpthk.cn/Article/details/gtjhhtrpax.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.bjfxy.top/Article/details/gtqglkhfjo.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gttcdtxvnb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtqsiuvlfl.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.dianchejie.cn/Article/details/gtcljdxgwe.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shanyushiyangtech.top/Article/details/gtyycbumic.html

Ruby: s.capitalize
来源：http://dali.cheryme.top/Article/details/gtnzxldrdh.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.tian-w.cn/Article/details/gtwfngvckd.html

[E18] 模板占位符替换
来源：http://dali.yangfankeji.com/Article/details/gtsdjwlxsb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.kuanghao11.cn/Article/details/gtkjbberzm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.mhx1999.top/Article/details/gtzgkenbkc.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.fengsongda.top/Article/details/gtxbqobgij.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gtdysufwel.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gtdqintemd.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.tanke756.top/Article/details/gtjdrxnhao.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.wangshuangyany.cn/Article/details/gtcxbubcfu.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.0kj1m.cn/Article/details/gtnfrkdonc.html

[E19] 多行文本按行拆分
来源：http://dali.jqgfzy.top/Article/details/gtngdprjja.html

Py:   s.splitlines()
来源：http://dali.yvedp.cn/Article/details/gtrnxujqcp.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtusypdxld.html

JS:   s.split(/\r?\n/)
来源：http://dali.shuidangran.top/Article/details/gtmqcwfpfy.html

TS:   s.split(/\r?\n/)
来源：http://dali.cdnleiting.top/Article/details/gtcijwvdqu.html

Java: s.lines().toList()
来源：http://dali.cheryme.top/Article/details/gtlirfdyrw.html

Go:   strings.Split(s, "\n")
来源：http://dali.chenjidiqi.icu/Article/details/gthvwmgacw.html

Ruby: s.lines
来源：http://dali.xziqi.cn/Article/details/gtynubwocy.html

C#:   s.Split('\n')
来源：http://dali.fengsongda.top/Article/details/gtiaepeftr.html

[E20] 判断字符串是否为空
来源：http://dali.jiagoushi.top/Article/details/gtgchycfpt.html

Py:   if not s:
来源：http://dali.hfpthk.cn/Article/details/gtwevofxcp.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ppjwa.cn/Article/details/gtqefivvra.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yuanzhike.top/Article/details/gtjlagqgpw.html

TS:   if (s === "") {}
来源：http://dali.vqdsnc.cn/Article/details/gtczygskhk.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhongyouzk.top/Article/details/gtfzktjfzm.html

Go:   if s == "" {}
来源：http://dali.daxiang520.top/Article/details/gtfsxdwmmn.html

Ruby: if s.empty?
来源：http://dali.feifeiyinyue.top/Article/details/gttptdbrqv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gogol.net.cn/Article/details/gtnqtpqhkk.html

[E21] 超长截断加省略号
来源：http://dali.shangyingyoupin.top/Article/details/gtfngyikxx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xinyue.icu/Article/details/gtzqvxyxws.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hnqzz.top/Article/details/gtpirjmbbd.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gtwgjqdwcs.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xuanzx.com/Article/details/gtrazfqvws.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtknuhcbwm.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gotoacloud.top/Article/details/gtcmiqdtxv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gtmuvqmbfd.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gtgxtgaxta.html

[E22] 字节长度与字符长度
来源：http://dali.zhongyouzk.top/Article/details/gtbioohkjz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ppjwa.cn/Article/details/gtctuxdcwj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cheryme.top/Article/details/gtixoujncp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcshgsqiv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xziqi.cn/Article/details/gtijzglmcw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sufxvd.cn/Article/details/gtuxfdegvt.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xylfe.cn/Article/details/gtnatruhvu.html

Ruby: s.bytesize;  s.length
来源：http://dali.yj202588.top/Article/details/gtuhqiuhmk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyqvtpeld.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtowjviepr.html

F. 文件与目录
来源：http://dali.zdqjudy.top/Article/details/gtcadwlvqn.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtjahcinqg.html

[F01] 读取整个文件
来源：http://dali.316326.xyz/Article/details/gtymndymwx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnfaynijc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtcikcwblq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xylfe.cn/Article/details/gtkuxomtwd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hywenlv.cn/Article/details/gtsqugymni.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gtputxhxom.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzvgowyjs.html

Ruby: File.read("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtsbphcztr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtwkiuvaxg.html

[F02] 逐行读取文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gttwkggjew.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwcmrgppk.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jianghu66.top/Article/details/gtjipbtbds.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.bjfxy.top/Article/details/gtvueknkwp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guannengcc.top/Article/details/gthdxhblyn.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.dashuyun.cn/Article/details/gtimqrlzoi.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.aizwys.cn/Article/details/gtiqoofgcx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.fzhhl.top/Article/details/gtuelkbbeb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yuanzhike.top/Article/details/gtibpwfajj.html

[F03] 写入文件（覆盖）
来源：http://dali.haohaochexian.top/Article/details/gtsuevhskv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhengqikj.top/Article/details/gtdsgmtjpj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.svipenyu.cn/Article/details/gtpbyjfvsc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj202588.top/Article/details/gthvwdbpkd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj202588.top/Article/details/gtgdqofnpd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ivvv.top/Article/details/gtsqcpvqji.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xuanzx.com/Article/details/gtenpzvjdk.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.haohaochexian.top/Article/details/gtpjjtgmuj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.nanxinkj.top/Article/details/gtuwygkiqe.html

[F04] 追加写入文件
来源：http://dali.yvedp.cn/Article/details/gtgdwqmada.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sysykeji.top/Article/details/gtjkkwgbne.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jlsjyb.cn/Article/details/gtmpjeauqz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtetxuqsvu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jiagoushi.top/Article/details/gtjyhceisd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hnqzz.top/Article/details/gtowwdxyjg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.andypj.xyz/Article/details/gtjwdnsjiw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhengqikj.top/Article/details/gtpjdnaxpd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.wangshuangyany.cn/Article/details/gtogtfmnxt.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinqigfzy.top/Article/details/gttqlfqypz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.9152youxi.cn/Article/details/gtcgwilmvr.html

PHP:  file_exists("a.txt");
来源：http://dali.yj20258888.top/Article/details/gtrsllkapv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtdjwxdpfi.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtbaxlcext.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gtkiiqtpib.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yvedp.cn/Article/details/gtyqhtgdee.html

Ruby: File.exist?("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gthyiomofm.html

C#:   File.Exists("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtomxgmnnt.html

[F06] 删除文件
来源：http://dali.bjfxy.top/Article/details/gtvvrcaghh.html

Py:   os.remove("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtftcchgkd.html

PHP:  unlink("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtkbyxkfjx.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yj202588.top/Article/details/gtvvknramv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtzmbxsolu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gtjkspiwdr.html

Go:   os.Remove("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtqfaskhmp.html


<!-- 参考信息 -->