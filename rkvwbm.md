代发 wailian999

Go:   slices.Contains(arr, x)
来源：http://dali.yj20258888.top/Article/details/gtzbadeozs.html

Ruby: arr.include?(x)
来源：http://dali.gogol.net.cn/Article/details/gtxavgocnv.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gtxdsddjzf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.meibo888.top/Article/details/gtngkjhblm.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.sxryk.cn/Article/details/gtjmesmyqq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.haohaochexian.top/Article/details/gtwlpzdvyw.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.chenlongwang.top/Article/details/gtvjtpmrru.html

TS:   [...arr];
来源：http://dali.jlsjyb.cn/Article/details/gtiovbnpgj.html

Java: new ArrayList<>(list);
来源：http://dali.haohaochexian.top/Article/details/gtmsypskxh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqdyjtcto.html

Ruby: arr.dup;  arr.clone
来源：http://dali.0kj1m.cn/Article/details/gtumiqcduw.html

C#:   new List<int>(list);
来源：http://dali.hnxiangtu.top/Article/details/gtouaoigae.html

[D23] reduce 累积计算
来源：http://dali.zhixingplan.top/Article/details/gthsjncijn.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.gogol.net.cn/Article/details/gtjngijvqh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.pycfn.com/Article/details/gtmpdpinqf.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cucudq.cn/Article/details/gtkinaiott.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtusqmhpol.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xinyue.icu/Article/details/gtzbwunjfz.html

Go:   // 手写循环
来源：http://dali.ydzc1.top/Article/details/gtlhwjuykm.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.sxryk.cn/Article/details/gtiiflbvkd.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ydzc1.top/Article/details/gtttehkmfl.html

[D24] 字典 / Map 基本操作
来源：http://dali.yangfankeji.com/Article/details/gtflbnmqeg.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.pycfn.com/Article/details/gtegghiunz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hongshengwenyu.top/Article/details/gtpcwjfttc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhixingplan.top/Article/details/gtopuvujqz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gttsmbewzk.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hongshengwenyu.top/Article/details/gtjpkmdrjy.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhoulong.xyz/Article/details/gtzksbdnir.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jinqigufen.top/Article/details/gtjpwtpqxj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.andypj.xyz/Article/details/gtenulzxjx.html

[D25] Set 集合去重与交并差
来源：http://dali.zhongyouzk.top/Article/details/gtqoqloljh.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.quarkkingdee.top/Article/details/gtndjtxmnl.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.sufxvd.cn/Article/details/gterpecwfy.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtolbhbenm.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.daxiang520.top/Article/details/gtjmduqgfy.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cucudq.cn/Article/details/gtyqjvnuug.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jiagoushi.top/Article/details/gtwsbofhzy.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrmqxkujl.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jinqigfzy.top/Article/details/gtoimckrtq.html

[D26] 数组转字符串
来源：http://dali.smart0.xyz/Article/details/gthwvxezcw.html

Py:   ", ".join(map(str, arr))
来源：http://dali.smart0.xyz/Article/details/gtofqaqvxb.html

PHP:  implode(", ", $arr);
来源：http://dali.yonumen.top/Article/details/gtkejxagpg.html

JS:   arr.join(", ")
来源：http://dali.birdmap.top/Article/details/gtygkmslby.html

TS:   arr.join(", ")
来源：http://dali.cqqwz.cn/Article/details/gthrnljutt.html

Java: String.join(", ", list)
来源：http://dali.fengsongda.top/Article/details/gtythpmlfc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jqgfzy.top/Article/details/gteswbhind.html

Ruby: arr.join(", ")
来源：http://dali.xinyue.icu/Article/details/gtmtuhylxu.html

C#:   string.Join(", ", list)
来源：http://dali.jinqigufen.top/Article/details/gtagwnhaso.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtkaqidpyc.html

E. 字符串处理
来源：http://dali.shzxlz.cn/Article/details/gtjhmubevu.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtvcetzdbg.html

[E01] 拼接字符串
来源：http://dali.hywenlv.cn/Article/details/gtdzxbzgul.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.guannengcc.top/Article/details/gtfjxvbcls.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtlxtgzyng.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.haohaochexian.top/Article/details/gtxffcmwuh.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yonumen.top/Article/details/gtdbbpmyoz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyxanveqh.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cheryme.top/Article/details/gtxlcftquh.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zdqjudy.top/Article/details/gttwzicyrj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtbhnspkun.html

[E02] 重复字符串
来源：http://dali.xylfe.cn/Article/details/gtkioprhms.html

Py:   "ab" * 3
来源：http://dali.wangshuangyany.cn/Article/details/gtfgtoczho.html

PHP:  str_repeat("ab", 3);
来源：http://dali.dashuyun.cn/Article/details/gtsyzycuxz.html

JS:   "ab".repeat(3)
来源：http://dali.xuetiantiany.cn/Article/details/gtelxizmwm.html

TS:   "ab".repeat(3)
来源：http://dali.yangfankeji.com/Article/details/gtbvukbmqs.html

Java: "ab".repeat(3)
来源：http://dali.gotoacloud.top/Article/details/gtpnwottmy.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpdsgovme.html

Ruby: "ab" * 3
来源：http://dali.meibo888.top/Article/details/gtyjxunjft.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ivvv.top/Article/details/gttheqtnik.html

[E03] 截取子串
来源：http://dali.c1oappe.top/Article/details/gtzmlihyle.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhiwuduotai.top/Article/details/gtvvrdhlmw.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ehwqpu.com/Article/details/gtvuozrdge.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.havefunace.top/Article/details/gtpxwgiamb.html

TS:   s.slice(1, 4)
来源：http://dali.fengsongda.top/Article/details/gtoisusygy.html

Java: s.substring(1, 4)
来源：http://dali.guannengcc.top/Article/details/gtclznjgze.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.pengpengdd.cyou/Article/details/gtbhohgreu.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xylfe.cn/Article/details/gtafibpgte.html

C#:   s.Substring(1, 3)
来源：http://dali.zhoulong.xyz/Article/details/gteuuaxtzk.html

[E04] 查找子串位置
来源：http://dali.yanxiufei.cn/Article/details/gtsgzmgkhd.html

Py:   s.find("x");  s.index("x")
来源：http://dali.daxiang520.top/Article/details/gtvyutfxgo.html

PHP:  strpos($s, "x");
来源：http://dali.zhongyouzk.top/Article/details/gtbenekjfb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.gogol.net.cn/Article/details/gtruibbcly.html

TS:   s.indexOf("x")
来源：http://dali.vqdsnc.cn/Article/details/gtfhgoedzz.html

Java: s.indexOf("x")
来源：http://dali.kuanghao11.cn/Article/details/gteibhotjq.html

Go:   strings.Index(s, "x")
来源：http://dali.zycfv.cn/Article/details/gtdrhprubt.html

Ruby: s.index("x")
来源：http://dali.dianchejie.cn/Article/details/gtrxcxahms.html

C#:   s.IndexOf("x")
来源：http://dali.shzxlz.cn/Article/details/gtovzsikjs.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.0kj1m.cn/Article/details/gtexgiadbk.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ivvv.top/Article/details/gtftucwonp.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.fzhhl.top/Article/details/gtartdngjg.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ydzc1.top/Article/details/gtvordvmdl.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yangfankeji.com/Article/details/gtervrtgnl.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.smart0.xyz/Article/details/gtchkyxgkf.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.fengsongda.top/Article/details/gtjoqraisl.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jqgufenzy.top/Article/details/gtlzrzojue.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.meibo888.top/Article/details/gtmcifdtys.html

[E06] 替换子串
来源：http://dali.jqgfzy.top/Article/details/gtaznrhkak.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.sufxvd.cn/Article/details/gtrnqtoxvr.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yongpay.top/Article/details/gtnqmjcpqf.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtzsgtkqqo.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtmkwoyzmb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gteeqrudfz.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtqjduoirn.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gtxnqgstux.html

C#:   s.Replace("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtwhazxqtf.html

[E07] 按分隔符拆分
来源：http://dali.hongshengwenyu.top/Article/details/gtfvqjxccl.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhoulong.xyz/Article/details/gtngnnboku.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtczpahuak.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gtnpqzdxuj.html

TS:   s.split(",")
来源：http://dali.nanxuanxn.top/Article/details/gtohznuyap.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.svipenyu.cn/Article/details/gtxtmetkxb.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.svipenyu.cn/Article/details/gtajyzyrsz.html

Ruby: s.split(",");  s.split
来源：http://dali.chenjidiqi.icu/Article/details/gtufyimggh.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yj202588.top/Article/details/gtgopzqszi.html

[E08] 数组按分隔符合并
来源：http://dali.aizwys.cn/Article/details/gtvxezubco.html

Py:   ",".join(items)
来源：http://dali.shuidangran.top/Article/details/gtexxoplwp.html

PHP:  implode(",", $items);
来源：http://dali.yonumen.top/Article/details/gtupaeuoyh.html

JS:   items.join(",")
来源：http://dali.yanxiufei.cn/Article/details/gtyvvpgwkw.html

TS:   items.join(",")
来源：http://dali.nanxinkj.top/Article/details/gtpirjzcnl.html

Java: String.join(",", items)
来源：http://dali.zhengqikj.top/Article/details/gtcvnzcpnr.html

Go:   strings.Join(items, ",")
来源：http://dali.ybcxt.top/Article/details/gtlbowmxrl.html

Ruby: items.join(",")
来源：http://dali.chenlongwang.top/Article/details/gtzxzrlbaz.html

C#:   string.Join(",", items)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmbhapptt.html

[E09] 去除所有空白字符
来源：http://dali.havefunace.top/Article/details/gtyfglrdnd.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hongshengwenyu.top/Article/details/gtfcuwhnaf.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.9152youxi.cn/Article/details/gteppoqvpw.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xziqi.cn/Article/details/gtbjoajkrn.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jianghu66.top/Article/details/gtepthpdmc.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hnxiangtu.top/Article/details/gtrawgbhwa.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.chenlongwang.top/Article/details/gtkvnqdafi.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.wangshuangyany.cn/Article/details/gtsegojfmv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.pengpengdd.cyou/Article/details/gtcodxpmav.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yuxming.cn/Article/details/gtfuazyhcm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xinyue.icu/Article/details/gttxujnolr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shuidangran.top/Article/details/gtmzmbngym.html

JS:   "7".padStart(3, "0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgmvsvxib.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhongyouzk.top/Article/details/gtvxoddaeo.html

Java: String.format("%03d", 7)
来源：http://dali.yongpay.top/Article/details/gtcvqhpxlk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.daria6918.cn/Article/details/gtcuktegty.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gtzwsdxucz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ybcxt.top/Article/details/gtshrzcxny.html

[E11] 反转字符串
来源：http://dali.tian-w.cn/Article/details/gtmdvqfpxk.html

Py:   s[::-1]
来源：http://dali.shangyingyoupin.top/Article/details/gtxqgvwshn.html

PHP:  strrev($s);
来源：http://dali.yongpay.top/Article/details/gtfosmpxdt.html

JS:   [...s].reverse().join("")
来源：http://dali.wangdashe.top/Article/details/gteupannwb.html

TS:   [...s].reverse().join("")
来源：http://dali.aizwys.cn/Article/details/gtfgptwfyq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jlsjyb.cn/Article/details/gtmmxecvjn.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yj20258888.top/Article/details/gtqroidxxc.html

Ruby: s.reverse
来源：http://dali.xziqi.cn/Article/details/gtotojbjhv.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hysaishi.cn/Article/details/gtvkmjsyzp.html

[E12] 统计某字符出现次数
来源：http://dali.xinyue.icu/Article/details/gtvtgsdkxt.html

Py:   s.count("a")
来源：http://dali.zhiwuduotai.top/Article/details/gtudohdswt.html

PHP:  substr_count($s, "a");
来源：http://dali.jinghuilouyu.cn/Article/details/gtvjmdwkcr.html

JS:   s.split("a").length - 1
来源：http://dali.cheryme.top/Article/details/gtywmcxsaj.html

TS:   s.split("a").length - 1
来源：http://dali.sysykeji.top/Article/details/gtslhmoyws.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.haohaochexian.top/Article/details/gtqugiidut.html

Go:   strings.Count(s, "a")
来源：http://dali.zhengqikj.top/Article/details/gtvtcqgwta.html

Ruby: s.count("a")
来源：http://dali.jiagoushi.top/Article/details/gtzxlbgyjj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shuidangran.top/Article/details/gtthnuhaoj.html

[E13] 逐字符遍历
来源：http://dali.svipenyu.cn/Article/details/gtmsyhbgro.html

Py:   for ch in s: print(ch)
来源：http://dali.yj202588.top/Article/details/gtkzobopng.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xuetiantiany.cn/Article/details/gtkkuccldt.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hfpthk.cn/Article/details/gtouucfplz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xylfe.cn/Article/details/gtbqtcidiy.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hywenlv.cn/Article/details/gthizuyirg.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ppjwa.cn/Article/details/gtiohsbfpp.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ppjwa.cn/Article/details/gtfgjmnzgn.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hongshengwenyu.top/Article/details/gtdhnjrsln.html

[E14] URL 编码与 Base64
来源：http://dali.cheryme.top/Article/details/gtfbayupzu.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfkvumikj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhijiandao.cn/Article/details/gtvbnvvbwt.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtitkatlqu.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdcururuq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhixingplan.top/Article/details/gtqpapturh.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jqgufenzy.top/Article/details/gtmkfwckee.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.quarkkingdee.top/Article/details/gtlgojgcnw.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shzxlz.cn/Article/details/gtcluloofi.html

[E15] HTML 转义 / 反转义
来源：http://dali.yonumen.top/Article/details/gtqulzjods.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yj20258888.top/Article/details/gtajylgwdh.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.aizwys.cn/Article/details/gtbzygdjuk.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yj20258.top/Article/details/gtpunmurbx.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shzxlz.cn/Article/details/gtfwlfglet.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.pycfn.com/Article/details/gtgdrfsixj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.tanke756.top/Article/details/gtrrsjdfra.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.daxiang520.top/Article/details/gtbqwdzwkb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yangfankeji.com/Article/details/gtdaekxhpz.html

[E16] 数字千分位
来源：http://dali.haohaochexian.top/Article/details/gtqbtnomgt.html

Py:   f"{1234567:,}"
来源：http://dali.hnqzz.top/Article/details/gtvzkmcqdy.html

PHP:  number_format(1234567);
来源：http://dali.yj20258.top/Article/details/gtuuntyhhq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.fengsongda.top/Article/details/gtqtccwkvt.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jyoumei.cn/Article/details/gthzxwkexr.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.wangshuangyany.cn/Article/details/gtazkbdyft.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yueranfly.top/Article/details/gtfbcwizgb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.nwbrower.top/Article/details/gtlztfbhum.html

C#:   1234567.ToString("N0")
来源：http://dali.shanyushiyangtech.top/Article/details/gtntoszatp.html

[E17] 首字母大写
来源：http://dali.yj202588.top/Article/details/gtpfeqpljk.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhaomingkeji.xyz/Article/details/gthyxuvsgq.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xziqi.cn/Article/details/gtolrggxln.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenlongwang.top/Article/details/gtvegcdyao.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jyoumei.cn/Article/details/gtlthdnkhy.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yuanzhike.top/Article/details/gteahmdzeq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xuanzx.com/Article/details/gtcxqilbuj.html

Ruby: s.capitalize
来源：http://dali.c1oappe.top/Article/details/gtebbnhbnp.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cucudq.cn/Article/details/gtbzvtfxwe.html

[E18] 模板占位符替换
来源：http://dali.gogol.net.cn/Article/details/gtmurphesf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.fengsongda.top/Article/details/gtubxoncvf.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shuidangran.top/Article/details/gtoouurrlw.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.bjfxy.top/Article/details/gtyxfuiiyz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj20258888.top/Article/details/gtputixrse.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gtwqygvdkb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gtfcvbblvm.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jyoumei.cn/Article/details/gtfamgeoch.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ehwqpu.com/Article/details/gtngqmuiha.html

[E19] 多行文本按行拆分
来源：http://dali.wangdashe.top/Article/details/gtpdrpbgfx.html

Py:   s.splitlines()
来源：http://dali.hammf.cn/Article/details/gtygwwvgra.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.daria6918.cn/Article/details/gtcrtpshcr.html

JS:   s.split(/\r?\n/)
来源：http://dali.xuanzx.com/Article/details/gtvrqgzows.html

TS:   s.split(/\r?\n/)
来源：http://dali.birdmap.top/Article/details/gtiqdwkreb.html

Java: s.lines().toList()
来源：http://dali.pycfn.com/Article/details/gtxcirasfv.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhiwuduotai.top/Article/details/gtyqnitwkm.html

Ruby: s.lines
来源：http://dali.feifeiyinyue.top/Article/details/gtuumirqaw.html

C#:   s.Split('\n')
来源：http://dali.yonumen.top/Article/details/gtvcwwluts.html

[E20] 判断字符串是否为空
来源：http://dali.chenzaomai.com/Article/details/gtwrmpjlvp.html

Py:   if not s:
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpgfxircn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.svipenyu.cn/Article/details/gtmkuegaqu.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shangyingyoupin.top/Article/details/gthpjrwlvc.html

TS:   if (s === "") {}
来源：http://dali.wangshuangyany.cn/Article/details/gtpttiqhum.html

Java: if (s.isEmpty()) {}
来源：http://dali.haohaochexian.top/Article/details/gtavgjfjcy.html

Go:   if s == "" {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcjpqvjyi.html

Ruby: if s.empty?
来源：http://dali.smart0.xyz/Article/details/gtemiyplpd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhixingplan.top/Article/details/gtbjlpgutp.html

[E21] 超长截断加省略号
来源：http://dali.xylfe.cn/Article/details/gthjmiyvha.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ppjwa.cn/Article/details/gtodewtspe.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gtvyxyusgc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gtuwzseete.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyqekmkgy.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gtztneoznf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.daxiang520.top/Article/details/gtkujjqude.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yongpay.top/Article/details/gtyapanhoa.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gtmwgkotra.html

[E22] 字节长度与字符长度
来源：http://dali.birdmap.top/Article/details/gtudjvekwk.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.nwbrower.top/Article/details/gtibdgonah.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gaohongyu789.top/Article/details/gtgvsbukbs.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhengqikj.top/Article/details/gtsfaqooji.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.haohaochexian.top/Article/details/gtbvtdwvsn.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.aibaodan.cn/Article/details/gtbvgeujrq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.sysykeji.top/Article/details/gttspfvbmj.html

Ruby: s.bytesize;  s.length
来源：http://dali.hysaishi.cn/Article/details/gtftyipfnz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shanyushiyangtech.top/Article/details/gttucntwns.html

================================================================================
来源：http://dali.sweek.top/Article/details/gthvwxybmz.html

F. 文件与目录
来源：http://dali.chenlongwang.top/Article/details/gtsqadepcg.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtmdclxpjl.html

[F01] 读取整个文件
来源：http://dali.yj20258.top/Article/details/gtuywrdlkz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cheryme.top/Article/details/gtyxdhialw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtmjokzzlb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmrcgwfbi.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zycfv.cn/Article/details/gtocmnwrvv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gtgrsdpdfa.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yj202588.top/Article/details/gtcyoosrty.html

Ruby: File.read("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtrkuxbjbe.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtiflazmht.html

[F02] 逐行读取文件
来源：http://dali.xuanzx.com/Article/details/gtbiulzakr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shzxlz.cn/Article/details/gtnowetzqh.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hysaishi.cn/Article/details/gtmpeimeja.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cdnleiting.top/Article/details/gtxdtamzlq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnpxhcgau.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtexpyllub.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ivvv.top/Article/details/gtsircjokv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hfpthk.cn/Article/details/gtzbonbnqt.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.daria6918.cn/Article/details/gtlyqxgmni.html

[F03] 写入文件（覆盖）
来源：http://dali.zhoulong.xyz/Article/details/gtfizlcoyv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ehwqpu.com/Article/details/gtvfhqjnmx.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuhnmazvw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sysykeji.top/Article/details/gtmgjztmzf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daria6918.cn/Article/details/gttijzbctk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.daxiang520.top/Article/details/gtnzlhqhql.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.tianlin.xyz/Article/details/gtmtrvmalh.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shuidangran.top/Article/details/gtxusuybkm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yanxiufei.cn/Article/details/gtnaqgvvkq.html

[F04] 追加写入文件
来源：http://dali.guannengcc.top/Article/details/gtkzeivksf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shzxlz.cn/Article/details/gtmktdtvgy.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jiagoushi.top/Article/details/gtobdixjrb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnqzz.top/Article/details/gtzshwjfat.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258.top/Article/details/gtrwpluhmt.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sysykeji.top/Article/details/gtbsmpdday.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmmfjqskd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdvijbotc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.smart0.xyz/Article/details/gtiqilskkm.html

[F05] 判断文件或目录是否存在
来源：http://dali.feifeiyinyue.top/Article/details/gtpkegftqk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyhaeskps.html

PHP:  file_exists("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtivzvpctm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtopeutwyu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtdfjfznbe.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gtgxwmrtlh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.c1oappe.top/Article/details/gtqcjftjtv.html

Ruby: File.exist?("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtsonibjuu.html

C#:   File.Exists("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtcdokahbl.html

[F06] 删除文件
来源：http://dali.hammf.cn/Article/details/gtyeiyueug.html

Py:   os.remove("a.txt")
来源：http://dali.cashguo.top/Article/details/gtisatzllf.html

PHP:  unlink("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsildryna.html


<!-- 参考信息 -->