代发 wailian999

Py:   value = d.get("k") or default
来源：http://dali.wangshuangyany.cn/Article/details/gt2ngmrgfad.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.pengpengdd.cyou/Article/details/gt2suoljcwx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ybcxt.top/Article/details/gt2tqnpvxqb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.guannengcc.top/Article/details/gt2xbhnhnrd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cucudq.cn/Article/details/gt2ohyuvbfv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jlsjyb.cn/Article/details/gt2qzspnbfd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xuanzx.com/Article/details/gt2lbugqusb.html

C#:   obj?.A?.B ?? default
来源：http://dali.havefunace.top/Article/details/gt2rpqsdjvt.html

[H07] 断言
来源：http://dali.iojbl.cn/Article/details/gt2pxraadzi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.vqdsnc.cn/Article/details/gt2fpjeymnr.html

PHP:  assert($x > 0);
来源：http://dali.xuanzx.com/Article/details/gt2itavjyss.html

JS:   console.assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gt2jtgctchh.html

TS:   console.assert(x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2greiruxy.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jqgfzy.top/Article/details/gt2gkkpbvkg.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.vqdsnc.cn/Article/details/gt2dvmuskdq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uzxrjuan.html

C#:   Debug.Assert(x > 0);
来源：http://dali.guannengcc.top/Article/details/gt2grsxfatp.html

[H08] 获取错误信息与堆栈
来源：http://dali.svipenyu.cn/Article/details/gt2euqptnvl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yonumen.top/Article/details/gt2jxgqixvw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.9152youxi.cn/Article/details/gt2oncrtqro.html

JS:   e.message;  e.stack
来源：http://dali.wangdashe.top/Article/details/gt2ahndtflw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cucudq.cn/Article/details/gt2tmjydclr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xziqi.cn/Article/details/gt2hohbnvsc.html

Go:   err.Error()
来源：http://dali.chenjidiqi.icu/Article/details/gt2teqxdfkz.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhixingplan.top/Article/details/gt2jyxyznuv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jqgufenzy.top/Article/details/gt2iqiyxruh.html

[H09] 带错误码的异常
来源：http://dali.cqqwz.cn/Article/details/gt2lhwwjjxd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhengqikj.top/Article/details/gt2zbbfgvpy.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hfpthk.cn/Article/details/gt2lwtwidhy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ppjwa.cn/Article/details/gt2opfroafr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.nanxuanxn.top/Article/details/gt2brchswom.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ydzc1.top/Article/details/gt2kdpthkgf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.feifeiyinyue.top/Article/details/gt2acbdovlm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.gzhubu.top/Article/details/gt2gwhqtivd.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hywenlv.cn/Article/details/gt2oeiqbdgr.html

[H10] 资源自动释放
来源：http://dali.birdmap.top/Article/details/gt2ymnyjkhh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.nwbrower.top/Article/details/gt2wwucqryt.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qnsqbmqc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.meibo888.top/Article/details/gt2ohidnqoq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cheryme.top/Article/details/gt2vrzumxwq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cdnleiting.top/Article/details/gt2prykpqti.html

Go:   defer f.Close()
来源：http://dali.chenlongwang.top/Article/details/gt2ewrfigrp.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jqgufenzy.top/Article/details/gt2aaqukjgn.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.daria6918.cn/Article/details/gt2naosumuq.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2bldpisqf.html

I. 正则表达式
来源：http://dali.redwolf501.top/Article/details/gt2nnzvvuia.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2lidyvebv.html

[I01] 判断是否匹配
来源：http://dali.ppjwa.cn/Article/details/gt2swmbiztg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.aibaodan.cn/Article/details/gt2cbqfqfiv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yuxming.cn/Article/details/gt2yghfujdx.html

JS:   /\d+/.test(s)
来源：http://dali.daxiang520.top/Article/details/gt2wlhowvmo.html

TS:   /\d+/.test(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2oxcmoyow.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zdqjudy.top/Article/details/gt2thxxqild.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinqigufen.top/Article/details/gt2cfayzgxm.html

Ruby: s.match?(/\d+/)
来源：http://dali.pycfn.com/Article/details/gt2qvvophmo.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.dashuyun.cn/Article/details/gt2spryhzpm.html

[I02] 提取所有匹配
来源：http://dali.havefunace.top/Article/details/gt2xzeabakb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hnqzz.top/Article/details/gt2nmwmzixi.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xinyue.icu/Article/details/gt2sqtlblzp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.0kj1m.cn/Article/details/gt2nrhhgbxd.html

TS:   s.match(/\d+/g)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tnanvehd.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jqgufenzy.top/Article/details/gt2fbicerlv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.vqdsnc.cn/Article/details/gt2bcaydjea.html

Ruby: s.scan(/\d+/)
来源：http://dali.dianchejie.cn/Article/details/gt2rqaovtkp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2losaftzh.html

[I03] 提取捕获分组
来源：http://dali.xuanzx.com/Article/details/gt2zolhkxid.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.9152youxi.cn/Article/details/gt2klldnntc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hysaishi.cn/Article/details/gt2qisjzosq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.nanxuanxn.top/Article/details/gt2rhlfsupg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.tanke756.top/Article/details/gt2zkikpwmu.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jlsjyb.cn/Article/details/gt2gsvsymvc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sufxvd.cn/Article/details/gt2kchjriql.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.andypj.xyz/Article/details/gt2qryuybpb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gogol.net.cn/Article/details/gt2dizimfvn.html

[I04] 正则替换
来源：http://dali.hysaishi.cn/Article/details/gt2xkfnyaaz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.mhx1999.top/Article/details/gt2rqwryrel.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zycfv.cn/Article/details/gt2adxqxahj.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ybcxt.top/Article/details/gt2pbpbmtqn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jianghu66.top/Article/details/gt2gxcisije.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.quarkkingdee.top/Article/details/gt2nqvvuquu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.guowangkeji.top/Article/details/gt2ewiyswjx.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.fzhhl.top/Article/details/gt2sppkaaal.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.9152youxi.cn/Article/details/gt2wbxsylua.html

[I05] 按正则拆分
来源：http://dali.yvedp.cn/Article/details/gt2ndcslyxp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.haohaochexian.top/Article/details/gt2cfrqcpqk.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yueranfly.top/Article/details/gt2lncfmokb.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jyoumei.cn/Article/details/gt2czdyhjzj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gt2zqziodkj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.quarkkingdee.top/Article/details/gt2dadzifwn.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cucudq.cn/Article/details/gt2zuhhjjfw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.316326.xyz/Article/details/gt2bfywfdko.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sweek.top/Article/details/gt2ccxtmjub.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ucntqvpg.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gt2bijcjwaf.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shzxlz.cn/Article/details/gt2xfvwsrxf.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hywenlv.cn/Article/details/gt2lcweztuu.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ivvv.top/Article/details/gt2wwcotjbz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gogol.net.cn/Article/details/gt2nipacahf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.quarkkingdee.top/Article/details/gt2bzhosevj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gogol.net.cn/Article/details/gt2fgdlsbuw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhengqikj.top/Article/details/gt2ybhivgli.html

[I07] 忽略大小写与多行模式
来源：http://dali.vqdsnc.cn/Article/details/gt2vmsmqzlk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shuidangran.top/Article/details/gt2bygqzokn.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.316326.xyz/Article/details/gt2sozrezof.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.dianchejie.cn/Article/details/gt2ztxhvvkv.html

TS:   /error/gim
来源：http://dali.zhongyouzk.top/Article/details/gt2phcgzrkr.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.nanxuanxn.top/Article/details/gt2ejspojps.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shuidangran.top/Article/details/gt2tjcyfavq.html

Ruby: s.scan(/error/i)
来源：http://dali.cdnleiting.top/Article/details/gt2leaymwyy.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.nwbrower.top/Article/details/gt2zssanodu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fmfopceg.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.chenjidiqi.icu/Article/details/gt2faswiscx.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.feifeiyinyue.top/Article/details/gt2mqiymgii.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zycfv.cn/Article/details/gt2rtktrnyi.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.kuanghao11.cn/Article/details/gt2peddpgwl.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xinyue.icu/Article/details/gt2rygvvgsj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.aizwys.cn/Article/details/gt2xixjllmj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.c1oappe.top/Article/details/gt2rvazckxw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.aizwys.cn/Article/details/gt2aehbybsx.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2auvdlhmo.html

J. 日期与时间
来源：http://dali.shangyingyoupin.top/Article/details/gt2zqybuhtj.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2fjjhfcqr.html

[J01] 获取当前时间
来源：http://dali.nwbrower.top/Article/details/gt2afmsslwl.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xuanzx.com/Article/details/gt2cgrckgnf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhiwuduotai.top/Article/details/gt2nvwstoih.html

JS:   new Date();  Date.now()
来源：http://dali.shangyingyoupin.top/Article/details/gt2hapwswkd.html

TS:   new Date();  Date.now()
来源：http://dali.cucudq.cn/Article/details/gt2ttuwmdrp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ehwqpu.com/Article/details/gt2qogdajzu.html

Go:   time.Now()
来源：http://dali.feifeiyinyue.top/Article/details/gt2pdadvfbx.html

Ruby: Time.now
来源：http://dali.c1oappe.top/Article/details/gt2yhizmgjv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.gogol.net.cn/Article/details/gt2vltfsnht.html

[J02] 格式化输出
来源：http://dali.meibo888.top/Article/details/gt2lerxpout.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tianlin.xyz/Article/details/gt2lrfvkqzy.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gukwuytk.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nhvinols.html

TS:   d.toISOString()
来源：http://dali.wangdashe.top/Article/details/gt2qbsfyctr.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.9152youxi.cn/Article/details/gt2itriwviv.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.chenzaomai.com/Article/details/gt2jgeocixn.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.kuanghao11.cn/Article/details/gt2mmpctsjf.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cqqwz.cn/Article/details/gt2yjxgooce.html

[J03] 字符串解析为日期
来源：http://dali.nanxuanxn.top/Article/details/gt2slvykcyh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yj20258.top/Article/details/gt2iqnpxeql.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.andypj.xyz/Article/details/gt2xrrevbsw.html

JS:   new Date("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gt2xsghyqvd.html

TS:   new Date("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gt2cpzykjfh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gt2rtksrpvq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gt2pjeidwzy.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gt2pflfuorh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.vqdsnc.cn/Article/details/gt2zmodmkup.html

[J04] 时间戳与日期互转
来源：http://dali.yonumen.top/Article/details/gt2kndxnoso.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jnhzwsox.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2duxgkfst.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ybcxt.top/Article/details/gt2ovloshua.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yj202588.top/Article/details/gt2jqbjmjig.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2agdqcqpb.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gt2fykvdwrg.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yanxiufei.cn/Article/details/gt2eixirgyj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.haohaochexian.top/Article/details/gt2yzznhtuv.html

[J05] 时间加减（加 7 天）
来源：http://dali.hfpthk.cn/Article/details/gt2vwceqkjd.html

Py:   now + timedelta(days=7)
来源：http://dali.shangyingyoupin.top/Article/details/gt2nxrylbgc.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gzhubu.top/Article/details/gt2csiyyseh.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangdashe.top/Article/details/gt2dcuirvjf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhoulong.xyz/Article/details/gt2kalwcfmg.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhengqikj.top/Article/details/gt2vuqjsery.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.birdmap.top/Article/details/gt2gsgbhzrb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.dashuyun.cn/Article/details/gt2zeddlqjm.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ehwqpu.com/Article/details/gt2esuzcyhw.html

[J06] 计算两时间之差
来源：http://dali.bjfxy.top/Article/details/gt2xmtwfqnu.html

Py:   (end - start).total_seconds()
来源：http://dali.birdmap.top/Article/details/gt2codptafc.html

PHP:  $end->diff($start)->days;
来源：http://dali.tanke756.top/Article/details/gt2hygrovqd.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hongshengwenyu.top/Article/details/gt2uuywunjw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.guannengcc.top/Article/details/gt2oaylufjf.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.redwolf501.top/Article/details/gt2mgidtgcm.html

Go:   end.Sub(start).Hours()
来源：http://dali.feifeiyinyue.top/Article/details/gt2osawpjup.html

Ruby: end - start                 # 返回秒数
来源：http://dali.fengsongda.top/Article/details/gt2xysymkoo.html

C#:   (end - start).TotalSeconds
来源：http://dali.nanxuanxn.top/Article/details/gt2evsdobti.html

[J07] 比较两个日期
来源：http://dali.yongpay.top/Article/details/gt2arxqaanx.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.mhx1999.top/Article/details/gt2jgrikkog.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.quarkkingdee.top/Article/details/gt2vyjskrsq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.vqdsnc.cn/Article/details/gt2qbtushwc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.aizwys.cn/Article/details/gt2jfgegkry.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yuanzhike.top/Article/details/gt2lpfvuqan.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sppgancs.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hywenlv.cn/Article/details/gt2ptsthgwg.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.tian-w.cn/Article/details/gt2hssepyhr.html

[J08] 提取年月日与星期
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ftzysnpq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hywenlv.cn/Article/details/gt2cbbesivd.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cqqwz.cn/Article/details/gt2zchphjrk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.316326.xyz/Article/details/gt2pfnemqcd.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.chenjidiqi.icu/Article/details/gt2wrvdyaqe.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.tanke756.top/Article/details/gt2kwwhlavs.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhengqikj.top/Article/details/gt2ruifvyho.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinqigfzy.top/Article/details/gt2ljybelbr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jlsjyb.cn/Article/details/gt2qkmxdbmg.html

[J09] 时区处理
来源：http://dali.yanxiufei.cn/Article/details/gt2prpmvbsu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hywenlv.cn/Article/details/gt2orcuwtsi.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ehwqpu.com/Article/details/gt2dirrpwuo.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hammf.cn/Article/details/gt2ribtbdkt.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhongyouzk.top/Article/details/gt2qelkxweb.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yonumen.top/Article/details/gt2bkxozwmb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.nanxinkj.top/Article/details/gt2wmmsasja.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hnxiangtu.top/Article/details/gt2dykpoakq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.wangdashe.top/Article/details/gt2trshpwms.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhixingplan.top/Article/details/gt2uclirygs.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yueranfly.top/Article/details/gt2lkpashcd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gotoacloud.top/Article/details/gt2seedmqxs.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2dspxsnmk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vhygcyhw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yangfankeji.com/Article/details/gt2qagbwmju.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shangyingyoupin.top/Article/details/gt2obnbjtrd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gzhubu.top/Article/details/gt2nqwulwqj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhixingplan.top/Article/details/gt2bmqrkqtn.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2pylzvwol.html

K. JSON 与序列化
来源：http://dali.redwolf501.top/Article/details/gt2mjpadjjs.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2tioidwpd.html

[K01] 对象转 JSON 字符串
来源：http://dali.svipenyu.cn/Article/details/gt2jouqejuo.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xylfe.cn/Article/details/gt2sivbbeta.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ivvv.top/Article/details/gt2laqnbdtb.html

JS:   JSON.stringify(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2kakxjsom.html

TS:   JSON.stringify(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2kumkrwyo.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.tanke756.top/Article/details/gt2glvpajun.html

Go:   json.Marshal(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2nhkhvmcr.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.wangdashe.top/Article/details/gt2xasjogww.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ivvv.top/Article/details/gt2mistaqre.html

[K02] JSON 字符串转对象
来源：http://dali.cucudq.cn/Article/details/gt2joacwbuv.html

Py:   json.loads(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zlcyezwq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sntsqgal.html

JS:   JSON.parse(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2fjmkcrxs.html

TS:   JSON.parse(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2yxmjvjww.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yonumen.top/Article/details/gt2undiwgbs.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shzxlz.cn/Article/details/gt2loyckzve.html

Ruby: JSON.parse(s)
来源：http://dali.sxryk.cn/Article/details/gt2nasmeeur.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cucudq.cn/Article/details/gt2egnkwhzt.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yj20258.top/Article/details/gt2oinetwox.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hywenlv.cn/Article/details/gt2whqopoch.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2btrijgfr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zycfv.cn/Article/details/gt2zvmoilxq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.mhx1999.top/Article/details/gt2zvodgfwn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2xlksycvo.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jqgfzy.top/Article/details/gt2wltxrzav.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2gpzowkud.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hammf.cn/Article/details/gt2liwhkbpf.html

[K04] 读取 JSON 文件
来源：http://dali.meibo888.top/Article/details/gt2uispnugw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.chenzaomai.com/Article/details/gt2hlfyjafe.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhongyouzk.top/Article/details/gt2pqeuynyf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258.top/Article/details/gt2bikgzerx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fzhhl.top/Article/details/gt2mvqqgscl.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.wangshuangyany.cn/Article/details/gt2glseirpg.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hammf.cn/Article/details/gt2qqmtqaym.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.fzhhl.top/Article/details/gt2mnhhhigd.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jqgfzy.top/Article/details/gt2gvrssebj.html

[K05] 深拷贝对象
来源：http://dali.ybcxt.top/Article/details/gt2rxslhezr.html

Py:   copy.deepcopy(obj)
来源：http://dali.316326.xyz/Article/details/gt2wgsctdjy.html

PHP:  unserialize(serialize($obj));
来源：http://dali.nanxuanxn.top/Article/details/gt2uhqcisbi.html

JS:   structuredClone(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2dkxpcjgr.html

TS:   structuredClone(obj)
来源：http://dali.hnqzz.top/Article/details/gt2ownlbjck.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.pycfn.com/Article/details/gt2bqrpjdea.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ecmbhgga.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cucudq.cn/Article/details/gt2qavlwpsu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.nanxinkj.top/Article/details/gt2smgjkyjl.html

[K06] 解析 URL 查询串
来源：http://dali.zhoulong.xyz/Article/details/gt2pklwfuri.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.nwbrower.top/Article/details/gt2lebeyext.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.bjfxy.top/Article/details/gt2husacojp.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sysykeji.top/Article/details/gt2uvxtkvkm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hammf.cn/Article/details/gt2txhvdcak.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhixingplan.top/Article/details/gt2ehocwedn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.tianlin.xyz/Article/details/gt2hymtwswx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.daria6918.cn/Article/details/gt2bdkkqlqe.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.pycfn.com/Article/details/gt2xmgoqwdj.html

[K07] 进制转换
来源：http://dali.nanxuanxn.top/Article/details/gt2adzdyony.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gt2wxzyjgki.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zycfv.cn/Article/details/gt2xyyrkztp.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.316326.xyz/Article/details/gt2twiviahf.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gt2ktkmuxal.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gt2tutmionw.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.pycfn.com/Article/details/gt2cydmczie.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.havefunace.top/Article/details/gt2usljvjtr.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gt2jkllhryx.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xylfe.cn/Article/details/gt2ntrcduyt.html

Py:   pickle.dumps(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2osvthfjk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gzhubu.top/Article/details/gt2xefeddml.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shuidangran.top/Article/details/gt2pdmiwxsg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.daria6918.cn/Article/details/gt2vrcpikkp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hammf.cn/Article/details/gt2tsmjkwth.html

Go:   encoding/gob
来源：http://dali.shzxlz.cn/Article/details/gt2ddtdxvco.html

Ruby: Marshal.dump(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yelxdays.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xuanzx.com/Article/details/gt2cehokujp.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2vxxvhzfd.html

L. 网络请求
来源：http://dali.0kj1m.cn/Article/details/gt2lgxusnxs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hssonqxz.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2kvcshjsw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.dianchejie.cn/Article/details/gt2jrvkqmvb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qekpdanj.html

JS:   await fetch(url)
来源：http://dali.yongpay.top/Article/details/gt2tocgsvvo.html

TS:   await fetch(url)
来源：http://dali.aizwys.cn/Article/details/gt2tqsqzlly.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ycgfmckr.html

Go:   resp, err := http.Get(url)
来源：http://dali.c1oappe.top/Article/details/gt2isfcgpeh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2drovnufh.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.quarkkingdee.top/Article/details/gt2kxcwlbqp.html

[L02] 发送 POST JSON
来源：http://dali.quarkkingdee.top/Article/details/gt2qxqoyapj.html


<!-- 参考信息 -->