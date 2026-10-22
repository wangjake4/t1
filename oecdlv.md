代发 wailian999

Go:   slices.Contains(arr, x)
来源：http://dali.hnqzz.top/Article/details/gtkpwggbxl.html

Ruby: arr.include?(x)
来源：http://dali.yj20258888.top/Article/details/gttimveeht.html

C#:   list.Contains(x)
来源：http://dali.quarkkingdee.top/Article/details/gtoxbewypr.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ydzc1.top/Article/details/gtebuouwyf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yangfankeji.com/Article/details/gthrxcbqbv.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xuetiantiany.cn/Article/details/gtjldpgotq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtcjrlkmto.html

TS:   [...arr];
来源：http://dali.wangshuangyany.cn/Article/details/gtjgcbiopi.html

Java: new ArrayList<>(list);
来源：http://dali.zhoulong.xyz/Article/details/gtbubdglns.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hysaishi.cn/Article/details/gtajpxxzbs.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xuetiantiany.cn/Article/details/gtdhhfjqqo.html

C#:   new List<int>(list);
来源：http://dali.9152youxi.cn/Article/details/gtzdmcxfpu.html

[D23] reduce 累积计算
来源：http://dali.tianlin.xyz/Article/details/gtvvayltbb.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xylfe.cn/Article/details/gtivhdceol.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfjvxexti.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cucudq.cn/Article/details/gtvibmauvm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gzhubu.top/Article/details/gtfqpgngqv.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hfpthk.cn/Article/details/gtbpbfpozh.html

Go:   // 手写循环
来源：http://dali.yongpay.top/Article/details/gtxfapphug.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hfpthk.cn/Article/details/gtgsiwcfbf.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhengqikj.top/Article/details/gtyqllotet.html

[D24] 字典 / Map 基本操作
来源：http://dali.jinghuilouyu.cn/Article/details/gtpapqzsvf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcncxhjfk.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xinyue.icu/Article/details/gtnxtbwyve.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jlsjyb.cn/Article/details/gtblvjepbo.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xinyue.icu/Article/details/gtfwzddagl.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yanxiufei.cn/Article/details/gtupynzkpc.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinqigufen.top/Article/details/gtgxlheckz.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yangfankeji.com/Article/details/gtzogarnls.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinghuilouyu.cn/Article/details/gtfrjticdn.html

[D25] Set 集合去重与交并差
来源：http://dali.daria6918.cn/Article/details/gtfkqqyrvn.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cucudq.cn/Article/details/gtqpjkdugr.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yanxiufei.cn/Article/details/gtzrswpuwr.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfbhmgizp.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.feifeiyinyue.top/Article/details/gtkqdnbfzt.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ybcxt.top/Article/details/gtzaumopsa.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.pycfn.com/Article/details/gtopetqdxo.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sxryk.cn/Article/details/gtfpafucze.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.gogol.net.cn/Article/details/gtsvdryqdf.html

[D26] 数组转字符串
来源：http://dali.hysaishi.cn/Article/details/gteikatjbd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.tianlin.xyz/Article/details/gtdesnjycb.html

PHP:  implode(", ", $arr);
来源：http://dali.tian-w.cn/Article/details/gtulzujsby.html

JS:   arr.join(", ")
来源：http://dali.shanyushiyangtech.top/Article/details/gtefjwfrxa.html

TS:   arr.join(", ")
来源：http://dali.haohaochexian.top/Article/details/gtqzpurafj.html

Java: String.join(", ", list)
来源：http://dali.wangshuangyany.cn/Article/details/gtuojpewoq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jqgfzy.top/Article/details/gtmsnbdiig.html

Ruby: arr.join(", ")
来源：http://dali.yj20258888.top/Article/details/gtegdancdb.html

C#:   string.Join(", ", list)
来源：http://dali.jinqigufen.top/Article/details/gtwwjovmoa.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtfamutohb.html

E. 字符串处理
来源：http://dali.cashguo.top/Article/details/gtakhywggy.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtqtgmhdqf.html

[E01] 拼接字符串
来源：http://dali.cqqwz.cn/Article/details/gtwtfifioh.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jianghu66.top/Article/details/gtxgoldaxd.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ehwqpu.com/Article/details/gtbrinlvtf.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxafbkdfp.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shangyingyoupin.top/Article/details/gtqcajaxjf.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxgcudsnj.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.guowangkeji.top/Article/details/gtpaaioxug.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hammf.cn/Article/details/gtyfsxjljv.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gttakmapls.html

[E02] 重复字符串
来源：http://dali.zhengqikj.top/Article/details/gtloatgeof.html

Py:   "ab" * 3
来源：http://dali.daxiang520.top/Article/details/gtwwqjosdl.html

PHP:  str_repeat("ab", 3);
来源：http://dali.quarkkingdee.top/Article/details/gtaydgfehr.html

JS:   "ab".repeat(3)
来源：http://dali.hnxiangtu.top/Article/details/gtpjsmfamt.html

TS:   "ab".repeat(3)
来源：http://dali.yj20258.top/Article/details/gtahephcww.html

Java: "ab".repeat(3)
来源：http://dali.tanke756.top/Article/details/gtlqgvvtia.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hnqzz.top/Article/details/gtqlufozxb.html

Ruby: "ab" * 3
来源：http://dali.meibo888.top/Article/details/gtxcgnxwqg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.vqdsnc.cn/Article/details/gtxokxansh.html

[E03] 截取子串
来源：http://dali.sxryk.cn/Article/details/gtcylazvic.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.daxiang520.top/Article/details/gtdsbuvisl.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gtuchaakju.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.sysykeji.top/Article/details/gtkdfznvid.html

TS:   s.slice(1, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxwwgepej.html

Java: s.substring(1, 4)
来源：http://dali.9152youxi.cn/Article/details/gtudedgxco.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hongshengwenyu.top/Article/details/gtihmjsfsf.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xylfe.cn/Article/details/gtdlzhhywj.html

C#:   s.Substring(1, 3)
来源：http://dali.cheryme.top/Article/details/gthjzgzhhg.html

[E04] 查找子串位置
来源：http://dali.jiagoushi.top/Article/details/gtdficvbhu.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gtyvivvcvc.html

PHP:  strpos($s, "x");
来源：http://dali.sweek.top/Article/details/gteisteybo.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hnqzz.top/Article/details/gtwxxkrrva.html

TS:   s.indexOf("x")
来源：http://dali.ppjwa.cn/Article/details/gthfpmvxgv.html

Java: s.indexOf("x")
来源：http://dali.nanxuanxn.top/Article/details/gtbcdkklge.html

Go:   strings.Index(s, "x")
来源：http://dali.sweek.top/Article/details/gtazvwdoem.html

Ruby: s.index("x")
来源：http://dali.jianghu66.top/Article/details/gtlmdnqxyv.html

C#:   s.IndexOf("x")
来源：http://dali.yongpay.top/Article/details/gthjwzvqoh.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hywenlv.cn/Article/details/gtskvrcfzs.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yj202588.top/Article/details/gtbhmqlyth.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.chenzaomai.com/Article/details/gtvyuscmfv.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jlsjyb.cn/Article/details/gtraczcvio.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hfpthk.cn/Article/details/gtisopineu.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.iojbl.cn/Article/details/gtfllouveq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jinqigfzy.top/Article/details/gtxtudgcqi.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgdimcihi.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.bjfxy.top/Article/details/gtgmeqdstr.html

[E06] 替换子串
来源：http://dali.yj20258888.top/Article/details/gtkvhrkilt.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwlojndjh.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhixingplan.top/Article/details/gtpbzriuyr.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gthjdkxfwt.html

TS:   s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtpunfpkzz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gttaymdtae.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.aibaodan.cn/Article/details/gtitfdkugi.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtvypgnpom.html

C#:   s.Replace("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gttjqrxibf.html

[E07] 按分隔符拆分
来源：http://dali.nanxinkj.top/Article/details/gtaplwpvdu.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.redwolf501.top/Article/details/gtklpyblzf.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.0kj1m.cn/Article/details/gtyhpoixjj.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.aibaodan.cn/Article/details/gtpihqbbjr.html

TS:   s.split(",")
来源：http://dali.ivvv.top/Article/details/gtnniklpmj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.pycfn.com/Article/details/gtqteqonbx.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.birdmap.top/Article/details/gtfmknlgss.html

Ruby: s.split(",");  s.split
来源：http://dali.jinqigufen.top/Article/details/gtrmcqormt.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shanyushiyangtech.top/Article/details/gtumucdtim.html

[E08] 数组按分隔符合并
来源：http://dali.gogol.net.cn/Article/details/gtoqwvcfmn.html

Py:   ",".join(items)
来源：http://dali.haohaochexian.top/Article/details/gtvawzihne.html

PHP:  implode(",", $items);
来源：http://dali.ybcxt.top/Article/details/gtrhpftdpn.html

JS:   items.join(",")
来源：http://dali.smart0.xyz/Article/details/gtnmxxpvqj.html

TS:   items.join(",")
来源：http://dali.sxryk.cn/Article/details/gtqsoqthxy.html

Java: String.join(",", items)
来源：http://dali.quarkkingdee.top/Article/details/gttppcxcdi.html

Go:   strings.Join(items, ",")
来源：http://dali.jlsjyb.cn/Article/details/gterlrtoij.html

Ruby: items.join(",")
来源：http://dali.jyoumei.cn/Article/details/gtbkkpzkbr.html

C#:   string.Join(",", items)
来源：http://dali.jinqigufen.top/Article/details/gtngpwzqpn.html

[E09] 去除所有空白字符
来源：http://dali.yonumen.top/Article/details/gtpdleraev.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cucudq.cn/Article/details/gtfygnjlao.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhongyouzk.top/Article/details/gttxvoqlmf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.smart0.xyz/Article/details/gtnriyzpff.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shuidangran.top/Article/details/gtpxkyktmm.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cucudq.cn/Article/details/gtkgpmpqbk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xziqi.cn/Article/details/gtcdtckfwa.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhijiandao.cn/Article/details/gtmlmxxjrj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.0kj1m.cn/Article/details/gtdaccbfnz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jiagoushi.top/Article/details/gtxjnvmvti.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xylfe.cn/Article/details/gtbwnymtot.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yanxiufei.cn/Article/details/gtzqsadqtf.html

JS:   "7".padStart(3, "0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpxwfyzru.html

TS:   "7".padStart(3, "0")
来源：http://dali.cucudq.cn/Article/details/gtuaihugmm.html

Java: String.format("%03d", 7)
来源：http://dali.ybcxt.top/Article/details/gtlqwkfmgy.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.kuanghao11.cn/Article/details/gtuafuopmq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.kuanghao11.cn/Article/details/gthqmidwgh.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xuanzx.com/Article/details/gtpxtlyttp.html

[E11] 反转字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtiprttbhw.html

Py:   s[::-1]
来源：http://dali.c1oappe.top/Article/details/gtvytsczvk.html

PHP:  strrev($s);
来源：http://dali.chenzaomai.com/Article/details/gtbgdpafcf.html

JS:   [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gtdkgtxsxg.html

TS:   [...s].reverse().join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtlrzxktvr.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xinyue.icu/Article/details/gtbiuxalzc.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yj202588.top/Article/details/gtajitstzd.html

Ruby: s.reverse
来源：http://dali.hammf.cn/Article/details/gtcavcmezk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.daxiang520.top/Article/details/gtfdpbmwsj.html

[E12] 统计某字符出现次数
来源：http://dali.aizwys.cn/Article/details/gtfhpcgdal.html

Py:   s.count("a")
来源：http://dali.yj202588.top/Article/details/gtlhiiitrl.html

PHP:  substr_count($s, "a");
来源：http://dali.cashguo.top/Article/details/gtqtcelera.html

JS:   s.split("a").length - 1
来源：http://dali.quarkkingdee.top/Article/details/gtisehrrqo.html

TS:   s.split("a").length - 1
来源：http://dali.feifeiyinyue.top/Article/details/gthmvnqcck.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yongpay.top/Article/details/gtalenpqdq.html

Go:   strings.Count(s, "a")
来源：http://dali.shanyushiyangtech.top/Article/details/gturkmygdg.html

Ruby: s.count("a")
来源：http://dali.wangdashe.top/Article/details/gtoinrwwmj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shanyushiyangtech.top/Article/details/gtqyvlegww.html

[E13] 逐字符遍历
来源：http://dali.cheryme.top/Article/details/gtssnfqyel.html

Py:   for ch in s: print(ch)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgyssnzht.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.smart0.xyz/Article/details/gtycgfprbo.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nanxinkj.top/Article/details/gtwjlvuafk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.havefunace.top/Article/details/gtjdfmlwcl.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gtjjwnlcga.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jianghu66.top/Article/details/gtbzwkjthg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiuprfoio.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gtccavthce.html

[E14] URL 编码与 Base64
来源：http://dali.birdmap.top/Article/details/gtnvfoxful.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.nwbrower.top/Article/details/gtrsswgohx.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jqgfzy.top/Article/details/gtstsezpxv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.redwolf501.top/Article/details/gtyltmlwqr.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.quarkkingdee.top/Article/details/gtfdusnoch.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ydzc1.top/Article/details/gtqaemquqn.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhixingplan.top/Article/details/gtywkjqcnf.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xylfe.cn/Article/details/gtqqukbaff.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ydzc1.top/Article/details/gtdbxotykq.html

[E15] HTML 转义 / 反转义
来源：http://dali.shanyushiyangtech.top/Article/details/gtpixstubl.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.iojbl.cn/Article/details/gtvuxzxlop.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hnqzz.top/Article/details/gtyrbcavkk.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zdqjudy.top/Article/details/gtfwfijibe.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.c1oappe.top/Article/details/gtvjwdldhp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.dashuyun.cn/Article/details/gtzouhquav.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.guowangkeji.top/Article/details/gtxdunruls.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.nanxinkj.top/Article/details/gtdpqooqzb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.guowangkeji.top/Article/details/gtctdxqhya.html

[E16] 数字千分位
来源：http://dali.ppjwa.cn/Article/details/gtldvruigs.html

Py:   f"{1234567:,}"
来源：http://dali.hongshengwenyu.top/Article/details/gtaxqkphwy.html

PHP:  number_format(1234567);
来源：http://dali.nanxinkj.top/Article/details/gtthpyakyn.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnyyvvjrv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hywenlv.cn/Article/details/gtjpyiknon.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hnxiangtu.top/Article/details/gtkmolpkhd.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ivvv.top/Article/details/gthacxsczy.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.quarkkingdee.top/Article/details/gtlnczjrxy.html

C#:   1234567.ToString("N0")
来源：http://dali.nwbrower.top/Article/details/gtbnjtutpz.html

[E17] 首字母大写
来源：http://dali.jinqigufen.top/Article/details/gtjqrfedit.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.havefunace.top/Article/details/gtjihdqbkx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jianghu66.top/Article/details/gtrdixltwr.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cqqwz.cn/Article/details/gthakbigmc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.meibo888.top/Article/details/gtvlxydifn.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shuidangran.top/Article/details/gtszjinmuy.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.aizwys.cn/Article/details/gtwwymhqwi.html

Ruby: s.capitalize
来源：http://dali.jiagoushi.top/Article/details/gtvblsdigq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.kuanghao11.cn/Article/details/gtzccgxknn.html

[E18] 模板占位符替换
来源：http://dali.yonumen.top/Article/details/gtoggkqthy.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.daxiang520.top/Article/details/gtctwkzevf.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.cdnleiting.top/Article/details/gtpckgibcq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.daria6918.cn/Article/details/gtowztapku.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gtpusuihcq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hnxiangtu.top/Article/details/gtapfnimfg.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jianghu66.top/Article/details/gtkiyhtfiy.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hywenlv.cn/Article/details/gthqujrhvj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.vqdsnc.cn/Article/details/gtukiupebl.html

[E19] 多行文本按行拆分
来源：http://dali.birdmap.top/Article/details/gtnckogrmx.html

Py:   s.splitlines()
来源：http://dali.yj20258.top/Article/details/gtxduikzzi.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.wangdashe.top/Article/details/gtzclnbmws.html

JS:   s.split(/\r?\n/)
来源：http://dali.wangdashe.top/Article/details/gtkphkmyot.html

TS:   s.split(/\r?\n/)
来源：http://dali.cdnleiting.top/Article/details/gtrrawqmxr.html

Java: s.lines().toList()
来源：http://dali.cashguo.top/Article/details/gtdljdunsu.html

Go:   strings.Split(s, "\n")
来源：http://dali.jlsjyb.cn/Article/details/gtumnraztf.html

Ruby: s.lines
来源：http://dali.smart0.xyz/Article/details/gtzxfflrzl.html

C#:   s.Split('\n')
来源：http://dali.zycfv.cn/Article/details/gtunqdvjgs.html

[E20] 判断字符串是否为空
来源：http://dali.zycfv.cn/Article/details/gtajhfwlit.html

Py:   if not s:
来源：http://dali.ydzc1.top/Article/details/gtncywabov.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.havefunace.top/Article/details/gtewvemqst.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jinqigfzy.top/Article/details/gtrsehbudu.html

TS:   if (s === "") {}
来源：http://dali.redwolf501.top/Article/details/gtunwyarkt.html

Java: if (s.isEmpty()) {}
来源：http://dali.ivvv.top/Article/details/gttvbgtqbj.html

Go:   if s == "" {}
来源：http://dali.chenzaomai.com/Article/details/gtpbtpcbov.html

Ruby: if s.empty?
来源：http://dali.tanke756.top/Article/details/gtounicxil.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnhmjtafy.html

[E21] 超长截断加省略号
来源：http://dali.xuetiantiany.cn/Article/details/gtidnotbbx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jqgufenzy.top/Article/details/gtekukussn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.aizwys.cn/Article/details/gtdgdnbygd.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gtznejowcq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ivvv.top/Article/details/gtyszpnein.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gtrccjibpk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhengqikj.top/Article/details/gtvqhraiah.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yueranfly.top/Article/details/gtjmkmqula.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yvedp.cn/Article/details/gtkatqecpd.html

[E22] 字节长度与字符长度
来源：http://dali.yj202588.top/Article/details/gtralcrooz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gaohongyu789.top/Article/details/gtnwttgple.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pycfn.com/Article/details/gtnhqybthu.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hysaishi.cn/Article/details/gtxtlyhawx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fengsongda.top/Article/details/gtfzavwxji.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cheryme.top/Article/details/gtozbuwuuo.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ivvv.top/Article/details/gtolzpnrzw.html

Ruby: s.bytesize;  s.length
来源：http://dali.birdmap.top/Article/details/gthbblokoj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.tianlin.xyz/Article/details/gttgmthhbj.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtedraxzxw.html

F. 文件与目录
来源：http://dali.jinghuilouyu.cn/Article/details/gtitwoziiu.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtzvabqxbg.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gtdqwartms.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhixingplan.top/Article/details/gttdnvthip.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtpxfzgtwp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.kuanghao11.cn/Article/details/gtfbochzbx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ybcxt.top/Article/details/gtxvocyavh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gtsgginhih.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmamrnwgc.html

Ruby: File.read("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtaquyzvca.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtkndpxmkj.html

[F02] 逐行读取文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwvnncpqy.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xziqi.cn/Article/details/gtkstlxexn.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xuanzx.com/Article/details/gtjvupoteq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.havefunace.top/Article/details/gtbobjtovd.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtppfzuhhb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.kuanghao11.cn/Article/details/gtqcbyiwdj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.meibo888.top/Article/details/gtwtkymvlb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhixingplan.top/Article/details/gtdnuxlrfk.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yongpay.top/Article/details/gtlkilqmpz.html

[F03] 写入文件（覆盖）
来源：http://dali.yj202588.top/Article/details/gtaitfczal.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhongyouzk.top/Article/details/gtlmofskol.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.tianlin.xyz/Article/details/gtzckztake.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258888.top/Article/details/gtqplolnyv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258.top/Article/details/gtfnenutpp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.bjfxy.top/Article/details/gtcuymwhup.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtashooiex.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.wangdashe.top/Article/details/gtcnryskon.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yuanzhike.top/Article/details/gtnuccixrg.html

[F04] 追加写入文件
来源：http://dali.ehwqpu.com/Article/details/gteqmhlrdp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.fzhhl.top/Article/details/gttzwbyvfz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zdqjudy.top/Article/details/gtaspsxiwy.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.vqdsnc.cn/Article/details/gtvtcaeapx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tanke756.top/Article/details/gtfwcqkdan.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaclnnrwr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ydzc1.top/Article/details/gtbgoelzun.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj20258888.top/Article/details/gtfyhrihle.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zycfv.cn/Article/details/gtqytrcxka.html

[F05] 判断文件或目录是否存在
来源：http://dali.yuanzhike.top/Article/details/gtlgvffpur.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.chenzaomai.com/Article/details/gtizocegsm.html

PHP:  file_exists("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtifyzexny.html

JS:   fs.existsSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtdtzzlckd.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtqdzkdkeb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gtgtfjennu.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwsyboswv.html

Ruby: File.exist?("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtisopzmnf.html

C#:   File.Exists("a.txt")
来源：http://dali.316326.xyz/Article/details/gtxnpuplcr.html

[F06] 删除文件
来源：http://dali.shuidangran.top/Article/details/gtioyiulpq.html

Py:   os.remove("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtivdogxhv.html

PHP:  unlink("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtrryzstiv.html


<!-- 参考信息 -->