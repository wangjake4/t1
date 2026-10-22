代发 wailian999

Java: new ArrayList<>(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mjfngfap.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.sysykeji.top/Article/details/gt2wixjqilk.html

Ruby: arr.dup;  arr.clone
来源：http://dali.snrcjt.cn/Article/details/gt2zciyeloa.html

C#:   new List<int>(list);
来源：http://dali.yvedp.cn/Article/details/gt2chjumslg.html

[D23] reduce 累积计算
来源：http://dali.cheryme.top/Article/details/gt2jeluekxz.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.daria6918.cn/Article/details/gt2phibkvvg.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.birdmap.top/Article/details/gt2nsfrowlv.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sqqxiuxy.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dianchejie.cn/Article/details/gt2ztjaxqhb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zmaetqvg.html

Go:   // 手写循环
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nuvcpxxp.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.smart0.xyz/Article/details/gt2vbrdnahh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.guannengcc.top/Article/details/gt2eciobfgv.html

[D24] 字典 / Map 基本操作
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mbjznoyv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.fzhhl.top/Article/details/gt2jewbvklu.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.9152youxi.cn/Article/details/gt2mzmwrsdi.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.bjfxy.top/Article/details/gt2xnwdmzpf.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nnwkgtyl.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.feifeiyinyue.top/Article/details/gt2cqrxmuhy.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jjowgaob.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.dianchejie.cn/Article/details/gt2xpsexrjs.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ydzc1.top/Article/details/gt2rdafeusq.html

[D25] Set 集合去重与交并差
来源：http://dali.dianchejie.cn/Article/details/gt2nqioogtm.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yuxming.cn/Article/details/gt2yfakoifm.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.svipenyu.cn/Article/details/gt2whhmaiqm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.haohaochexian.top/Article/details/gt2wekitgyx.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yongpay.top/Article/details/gt2wevqrnma.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sweek.top/Article/details/gt2klgxdjgz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.quarkkingdee.top/Article/details/gt2olisqzaz.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.tian-w.cn/Article/details/gt2gxeogcnr.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hfpthk.cn/Article/details/gt2aumujojh.html

[D26] 数组转字符串
来源：http://dali.0kj1m.cn/Article/details/gt2gdkypwod.html

Py:   ", ".join(map(str, arr))
来源：http://dali.nanxinkj.top/Article/details/gt2wbyxcnsk.html

PHP:  implode(", ", $arr);
来源：http://dali.cqqwz.cn/Article/details/gt2gtwgilwe.html

JS:   arr.join(", ")
来源：http://dali.zhongyouzk.top/Article/details/gt2wyzhwfda.html

TS:   arr.join(", ")
来源：http://dali.cdnleiting.top/Article/details/gt2kidkbgwf.html

Java: String.join(", ", list)
来源：http://dali.hongshengwenyu.top/Article/details/gt2orearebk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xylfe.cn/Article/details/gt2jobrpphb.html

Ruby: arr.join(", ")
来源：http://dali.vqdsnc.cn/Article/details/gt2bipazdzy.html

C#:   string.Join(", ", list)
来源：http://dali.gzhubu.top/Article/details/gt2deqzfdwn.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2djbtyhek.html

E. 字符串处理
来源：http://dali.fzhhl.top/Article/details/gt2jcmvmeut.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2rtacuhoq.html

[E01] 拼接字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2hlboccnz.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xuetiantiany.cn/Article/details/gt2ucxmmdbm.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.guannengcc.top/Article/details/gt2lmsppfae.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258888.top/Article/details/gt2soclkvhv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhixingplan.top/Article/details/gt2ocrsxxzs.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ybcxt.top/Article/details/gt2oghfmend.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.birdmap.top/Article/details/gt2dxgxnhsh.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.pengpengdd.cyou/Article/details/gt2nukbsswu.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gt2qlzfvviu.html

[E02] 重复字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mhmpqhgp.html

Py:   "ab" * 3
来源：http://dali.0kj1m.cn/Article/details/gt2pbwrnbwi.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zycfv.cn/Article/details/gt2dgyqocis.html

JS:   "ab".repeat(3)
来源：http://dali.0kj1m.cn/Article/details/gt2trnbsyvu.html

TS:   "ab".repeat(3)
来源：http://dali.andypj.xyz/Article/details/gt2vgwpzbev.html

Java: "ab".repeat(3)
来源：http://dali.chenlongwang.top/Article/details/gt2lpzjayat.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sussamrq.html

Ruby: "ab" * 3
来源：http://dali.ydzc1.top/Article/details/gt2edvmbqbo.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.nanxuanxn.top/Article/details/gt2imnumazi.html

[E03] 截取子串
来源：http://dali.xuanzx.com/Article/details/gt2agzekyfh.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhoulong.xyz/Article/details/gt2dekjlpdm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.mhx1999.top/Article/details/gt2qqzsigbx.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cqqwz.cn/Article/details/gt2bmmxdpcv.html

TS:   s.slice(1, 4)
来源：http://dali.yuxming.cn/Article/details/gt2obiarlqh.html

Java: s.substring(1, 4)
来源：http://dali.xziqi.cn/Article/details/gt2fdcyxrev.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.pycfn.com/Article/details/gt2sdwqnpjx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.9152youxi.cn/Article/details/gt2wfhqzszs.html

C#:   s.Substring(1, 3)
来源：http://dali.ydzc1.top/Article/details/gt2hizcenvi.html

[E04] 查找子串位置
来源：http://dali.xylfe.cn/Article/details/gt2gdfgqwbg.html

Py:   s.find("x");  s.index("x")
来源：http://dali.svipenyu.cn/Article/details/gt2hhycoitc.html

PHP:  strpos($s, "x");
来源：http://dali.yuanzhike.top/Article/details/gt2fonbumwe.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cqqwz.cn/Article/details/gt2irtahqoy.html

TS:   s.indexOf("x")
来源：http://dali.vqdsnc.cn/Article/details/gt2stebwqzk.html

Java: s.indexOf("x")
来源：http://dali.dianchejie.cn/Article/details/gt2lcbcwvob.html

Go:   strings.Index(s, "x")
来源：http://dali.zhiwuduotai.top/Article/details/gt2chjymtvr.html

Ruby: s.index("x")
来源：http://dali.snrcjt.cn/Article/details/gt2zzkfpydn.html

C#:   s.IndexOf("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fjglanja.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.chenjidiqi.icu/Article/details/gt2bmwopdzp.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.smart0.xyz/Article/details/gt2cihlqhve.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yuxming.cn/Article/details/gt2xfxhtcqm.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shuidangran.top/Article/details/gt2hephkzrs.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yongpay.top/Article/details/gt2yujhvbig.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.guannengcc.top/Article/details/gt2zcvzgfhi.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.kuanghao11.cn/Article/details/gt2qzefratn.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.mhx1999.top/Article/details/gt2bwbksvzb.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.gaohongyu789.top/Article/details/gt2gdbdxuxn.html

[E06] 替换子串
来源：http://dali.hammf.cn/Article/details/gt2vsgtdpio.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ydzc1.top/Article/details/gt2yzkqrpit.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.sxryk.cn/Article/details/gt2bxxuavuu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xylfe.cn/Article/details/gt2bwbpmvtq.html

TS:   s.replaceAll("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gt2amzmeozk.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.guannengcc.top/Article/details/gt2aqlqzbvw.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.fengsongda.top/Article/details/gt2kfpvghrd.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.tanke756.top/Article/details/gt2mcwtquwi.html

C#:   s.Replace("a", "b")
来源：http://dali.smart0.xyz/Article/details/gt2wvdjupxe.html

[E07] 按分隔符拆分
来源：http://dali.ivvv.top/Article/details/gt2cutthush.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ythqmegv.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gt2dejhlhgy.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.nanxuanxn.top/Article/details/gt2hamnziij.html

TS:   s.split(",")
来源：http://dali.jianghu66.top/Article/details/gt2vhglndob.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yvedp.cn/Article/details/gt2gqlhsbxe.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sweek.top/Article/details/gt2bxagnzlg.html

Ruby: s.split(",");  s.split
来源：http://dali.hysaishi.cn/Article/details/gt2tdqfxemp.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cashguo.top/Article/details/gt2fqcfnfta.html

[E08] 数组按分隔符合并
来源：http://dali.havefunace.top/Article/details/gt2ykprdsjf.html

Py:   ",".join(items)
来源：http://dali.jlsjyb.cn/Article/details/gt2rzcfuzts.html

PHP:  implode(",", $items);
来源：http://dali.jlsjyb.cn/Article/details/gt2sdxgbbuu.html

JS:   items.join(",")
来源：http://dali.sysykeji.top/Article/details/gt2ssxzdyog.html

TS:   items.join(",")
来源：http://dali.cucudq.cn/Article/details/gt2wdisvvuk.html

Java: String.join(",", items)
来源：http://dali.sweek.top/Article/details/gt2ymbzsipr.html

Go:   strings.Join(items, ",")
来源：http://dali.yj202588.top/Article/details/gt2qbkrrrrp.html

Ruby: items.join(",")
来源：http://dali.zdqjudy.top/Article/details/gt2flrappxb.html

C#:   string.Join(",", items)
来源：http://dali.yvedp.cn/Article/details/gt2ezqqwhpx.html

[E09] 去除所有空白字符
来源：http://dali.jyoumei.cn/Article/details/gt2pvhksroi.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yuxming.cn/Article/details/gt2ryfishin.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hnqzz.top/Article/details/gt2kenbkazu.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xuetiantiany.cn/Article/details/gt2srljpfco.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.chenzaomai.com/Article/details/gt2ncskawhc.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.aibaodan.cn/Article/details/gt2matvdlnv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sysykeji.top/Article/details/gt2gvdalqvg.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xuetiantiany.cn/Article/details/gt2evaxnqqi.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yongpay.top/Article/details/gt2dvvfsmdw.html

[E10] 左侧补零 / 定长填充
来源：http://dali.fengsongda.top/Article/details/gt2yvnhxapx.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yuanzhike.top/Article/details/gt2dfdtjxaj.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ehwqpu.com/Article/details/gt2zlcavpge.html

JS:   "7".padStart(3, "0")
来源：http://dali.gaohongyu789.top/Article/details/gt2ekgegqxc.html

TS:   "7".padStart(3, "0")
来源：http://dali.hywenlv.cn/Article/details/gt2xomjgzfi.html

Java: String.format("%03d", 7)
来源：http://dali.hongshengwenyu.top/Article/details/gt2zxhgoemi.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.0kj1m.cn/Article/details/gt2yencdzuy.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hnqzz.top/Article/details/gt2rysctqlt.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hammf.cn/Article/details/gt2axzdgtpn.html

[E11] 反转字符串
来源：http://dali.andypj.xyz/Article/details/gt2xhurbxhq.html

Py:   s[::-1]
来源：http://dali.pycfn.com/Article/details/gt2rrzcivzf.html

PHP:  strrev($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zyzjwfpa.html

JS:   [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gt2rufuwwgl.html

TS:   [...s].reverse().join("")
来源：http://dali.feifeiyinyue.top/Article/details/gt2pwuspgal.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhixingplan.top/Article/details/gt2iawgzvyd.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhiwuduotai.top/Article/details/gt2iorizodv.html

Ruby: s.reverse
来源：http://dali.dianchejie.cn/Article/details/gt2rrnopyku.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.sysykeji.top/Article/details/gt2fgykhvom.html

[E12] 统计某字符出现次数
来源：http://dali.ivvv.top/Article/details/gt2qipuqsuy.html

Py:   s.count("a")
来源：http://dali.sysykeji.top/Article/details/gt2dseeigly.html

PHP:  substr_count($s, "a");
来源：http://dali.redwolf501.top/Article/details/gt2iymjuifl.html

JS:   s.split("a").length - 1
来源：http://dali.meibo888.top/Article/details/gt2wigoisva.html

TS:   s.split("a").length - 1
来源：http://dali.pengpengdd.cyou/Article/details/gt2oajdinvi.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xixhplzr.html

Go:   strings.Count(s, "a")
来源：http://dali.xziqi.cn/Article/details/gt2hmydakmu.html

Ruby: s.count("a")
来源：http://dali.yuxming.cn/Article/details/gt2pjhbltvt.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jiagoushi.top/Article/details/gt2fdongbvn.html

[E13] 逐字符遍历
来源：http://dali.svipenyu.cn/Article/details/gt2jfasvtqe.html

Py:   for ch in s: print(ch)
来源：http://dali.feifeiyinyue.top/Article/details/gt2onhirrrt.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhengqikj.top/Article/details/gt2nwkojicq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gt2yhkzxlug.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hammf.cn/Article/details/gt2liutvfdy.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2paucozce.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ppjwa.cn/Article/details/gt2kgfnjchr.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yueranfly.top/Article/details/gt2ziwqeyka.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.redwolf501.top/Article/details/gt2jnobqrhm.html

[E14] URL 编码与 Base64
来源：http://dali.zycfv.cn/Article/details/gt2dkompbwz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xuanzx.com/Article/details/gt2kdznvkzt.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.c1oappe.top/Article/details/gt2fpjqsfxr.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hongshengwenyu.top/Article/details/gt2xeuvywkw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2arzyumto.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yj20258888.top/Article/details/gt2qjmvhrmd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yangfankeji.com/Article/details/gt2kubrdmqv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.haohaochexian.top/Article/details/gt2kcpyyndy.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jqgufenzy.top/Article/details/gt2xtvljsei.html

[E15] HTML 转义 / 反转义
来源：http://dali.sweek.top/Article/details/gt2plmuepha.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ydzc1.top/Article/details/gt2igsnlhzu.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jqgfzy.top/Article/details/gt2jdpbuxmf.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2hclcioyc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhixingplan.top/Article/details/gt2vedwivme.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinqigufen.top/Article/details/gt2uxruhobz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2axsncszd.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2pbnbgyow.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shuidangran.top/Article/details/gt2zakdnklc.html

[E16] 数字千分位
来源：http://dali.haohaochexian.top/Article/details/gt2ryanhdlf.html

Py:   f"{1234567:,}"
来源：http://dali.chenlongwang.top/Article/details/gt2cpwefpdu.html

PHP:  number_format(1234567);
来源：http://dali.chenzaomai.com/Article/details/gt2kpbbgzle.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xinyue.icu/Article/details/gt2znzymjro.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgufenzy.top/Article/details/gt2bomwagty.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.wangshuangyany.cn/Article/details/gt2rercuhto.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jianghu66.top/Article/details/gt2osnsvpyz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.c1oappe.top/Article/details/gt2hwidqeoz.html

C#:   1234567.ToString("N0")
来源：http://dali.yanxiufei.cn/Article/details/gt2reylghts.html

[E17] 首字母大写
来源：http://dali.zhiwuduotai.top/Article/details/gt2muctjlqy.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cucudq.cn/Article/details/gt2hvbdjtwk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yuanzhike.top/Article/details/gt2hhbmtvhx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2wtjxpnvq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.aizwys.cn/Article/details/gt2puumeagk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jqgfzy.top/Article/details/gt2okejrdoe.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.wangdashe.top/Article/details/gt2grfeneru.html

Ruby: s.capitalize
来源：http://dali.yj20258888.top/Article/details/gt2cmrkcdeg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.pycfn.com/Article/details/gt2ssafzlux.html

[E18] 模板占位符替换
来源：http://dali.gotoacloud.top/Article/details/gt2wuwxclpo.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.wangshuangyany.cn/Article/details/gt2kkfujpxl.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hammf.cn/Article/details/gt2cdxguuzx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj20258888.top/Article/details/gt2yhorkmgm.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpdkurlh.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gt2sqrvhufq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gt2tqpzjftq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.fzhhl.top/Article/details/gt2vypzztbc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.dashuyun.cn/Article/details/gt2xxvmubai.html

[E19] 多行文本按行拆分
来源：http://dali.tianlin.xyz/Article/details/gt2jrzwnufc.html

Py:   s.splitlines()
来源：http://dali.smart0.xyz/Article/details/gt2pzcrpzmp.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pgwgxfep.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhiwuduotai.top/Article/details/gt2jcjfurwo.html

TS:   s.split(/\r?\n/)
来源：http://dali.aibaodan.cn/Article/details/gt2ispuqlgr.html

Java: s.lines().toList()
来源：http://dali.iojbl.cn/Article/details/gt2gbelycrk.html

Go:   strings.Split(s, "\n")
来源：http://dali.wangdashe.top/Article/details/gt2vdjawsvf.html

Ruby: s.lines
来源：http://dali.fzhhl.top/Article/details/gt2clgghnjy.html

C#:   s.Split('\n')
来源：http://dali.pycfn.com/Article/details/gt2lmmcgdzn.html

[E20] 判断字符串是否为空
来源：http://dali.pengpengdd.cyou/Article/details/gt2opksqaws.html

Py:   if not s:
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cfbefpvu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ivvv.top/Article/details/gt2bidfvlnw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.daxiang520.top/Article/details/gt2xruipqzz.html

TS:   if (s === "") {}
来源：http://dali.zhengqikj.top/Article/details/gt2fozhqmky.html

Java: if (s.isEmpty()) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2thcobqtp.html

Go:   if s == "" {}
来源：http://dali.jyoumei.cn/Article/details/gt2nyysodas.html

Ruby: if s.empty?
来源：http://dali.hysaishi.cn/Article/details/gt2ucdfctpx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2fqsrxziw.html

[E21] 超长截断加省略号
来源：http://dali.tianlin.xyz/Article/details/gt2iswzdkjl.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.svipenyu.cn/Article/details/gt2usautran.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.chenzaomai.com/Article/details/gt2zpbvjuav.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daria6918.cn/Article/details/gt2kdxnykqh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fzhhl.top/Article/details/gt2gfyonzxy.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gt2kmlgjwev.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.smart0.xyz/Article/details/gt2urilznlh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.andypj.xyz/Article/details/gt2vkjlgwhu.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gt2lzxmyhxl.html

[E22] 字节长度与字符长度
来源：http://dali.shanyushiyangtech.top/Article/details/gt2leoipbns.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yonumen.top/Article/details/gt2vgaicevp.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gt2pdrgaqrk.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnxiangtu.top/Article/details/gt2mluzmngq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.iojbl.cn/Article/details/gt2anpjnjuq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hammf.cn/Article/details/gt2vixoxjkm.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xuetiantiany.cn/Article/details/gt2ixpzsbfo.html

Ruby: s.bytesize;  s.length
来源：http://dali.zdqjudy.top/Article/details/gt2nkvdzcee.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.birdmap.top/Article/details/gt2xextrrfa.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2dloliegt.html

F. 文件与目录
来源：http://dali.0kj1m.cn/Article/details/gt2tmesnxgi.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2vbadtygo.html

[F01] 读取整个文件
来源：http://dali.gzhubu.top/Article/details/gt2zobotvpa.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yj202588.top/Article/details/gt2mumlwlrs.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zycfv.cn/Article/details/gt2cawangkw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.quarkkingdee.top/Article/details/gt2pmnejdqk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.chenjidiqi.icu/Article/details/gt2fyfakpho.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gt2fckoztrj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yanxiufei.cn/Article/details/gt2tcsjmyxt.html

Ruby: File.read("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2czxpefai.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gt2kupnnycw.html

[F02] 逐行读取文件
来源：http://dali.gogol.net.cn/Article/details/gt2pakozcio.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sufxvd.cn/Article/details/gt2giukoaal.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.chenlongwang.top/Article/details/gt2xqlbwqyh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2sqbxtkom.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ppjwa.cn/Article/details/gt2sjbfgsrk.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.c1oappe.top/Article/details/gt2dlrixhaw.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yuxming.cn/Article/details/gt2ghytkxqv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.snrcjt.cn/Article/details/gt2uzajkjhz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.birdmap.top/Article/details/gt2ijkhvrgk.html

[F03] 写入文件（覆盖）
来源：http://dali.aizwys.cn/Article/details/gt2dotkktwl.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yanxiufei.cn/Article/details/gt2ukhrkuwn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.c1oappe.top/Article/details/gt2biofuldl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenzaomai.com/Article/details/gt2teffbsir.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yueranfly.top/Article/details/gt2aqjquuxm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.havefunace.top/Article/details/gt2wfazojcp.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yuxming.cn/Article/details/gt2pyiotzum.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sufxvd.cn/Article/details/gt2qeulstrn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gzhubu.top/Article/details/gt2obxvkkmp.html

[F04] 追加写入文件
来源：http://dali.hammf.cn/Article/details/gt2gmiueybq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sweek.top/Article/details/gt2kyirskrz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ztomcucq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gt2snlgjxnd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.kuanghao11.cn/Article/details/gt2iicjajcm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.vqdsnc.cn/Article/details/gt2xjscdoso.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yj20258888.top/Article/details/gt2xsaeruwq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yuanzhike.top/Article/details/gt2dlnqtkir.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.dashuyun.cn/Article/details/gt2gjsdjwqg.html

[F05] 判断文件或目录是否存在
来源：http://dali.hysaishi.cn/Article/details/gt2kgbwtosr.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.haohaochexian.top/Article/details/gt2limlzziw.html

PHP:  file_exists("a.txt");
来源：http://dali.tanke756.top/Article/details/gt2skbxpxfr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2fzqtznld.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2repujjky.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gt2kpxizbhl.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.redwolf501.top/Article/details/gt2aqimwdvu.html

Ruby: File.exist?("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ydqiqiad.html

C#:   File.Exists("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2uympkwuk.html

[F06] 删除文件
来源：http://dali.redwolf501.top/Article/details/gt2afqdjjeb.html

Py:   os.remove("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2cokrodli.html

PHP:  unlink("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gt2gglynlxo.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2lnoyescb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2qllnytvd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gt2vyeneqdh.html

Go:   os.Remove("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2jtjntiwg.html

Ruby: File.delete("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zmsenzet.html

C#:   File.Delete("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2owgxfitg.html

[F07] 创建目录（含多级）
来源：http://dali.zhixingplan.top/Article/details/gt2mojjgrif.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.tanke756.top/Article/details/gt2hwibadoy.html


<!-- 参考信息 -->