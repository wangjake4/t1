代发 wailian999

Ruby: class MyError < StandardError; end
来源：http://dali.jqgfzy.top/Article/details/gt2ylvebafe.html

C#:   class MyException : Exception {}
来源：http://dali.yuanzhike.top/Article/details/gt2azvkhuhs.html

[H05] 捕获特定类型
来源：http://dali.mhx1999.top/Article/details/gt2yjkormpc.html

Py:   except ValueError as e:
来源：http://dali.yueranfly.top/Article/details/gt2qyjdvojv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.tianlin.xyz/Article/details/gt2zctrumhg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2eimwkfcu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2hljxtzxw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yonumen.top/Article/details/gt2ikjntchy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sweek.top/Article/details/gt2eguaityn.html

Ruby: rescue ArgumentError => e
来源：http://dali.aizwys.cn/Article/details/gt2ronazkfu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.fengsongda.top/Article/details/gt2prjbxciz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhengqikj.top/Article/details/gt2pvjpsicj.html

Py:   value = d.get("k") or default
来源：http://dali.kuanghao11.cn/Article/details/gt2yxsdrfqb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.fengsongda.top/Article/details/gt2ggtfnoos.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.feifeiyinyue.top/Article/details/gt2qmwhprhp.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.bjfxy.top/Article/details/gt2jywjejal.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hongshengwenyu.top/Article/details/gt2arjmaslr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.kuanghao11.cn/Article/details/gt2yoispqsn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.0kj1m.cn/Article/details/gt2tleiqcxs.html

C#:   obj?.A?.B ?? default
来源：http://dali.nanxuanxn.top/Article/details/gt2gtlcnmdd.html

[H07] 断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vljimrcl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.9152youxi.cn/Article/details/gt2jinshtkj.html

PHP:  assert($x > 0);
来源：http://dali.daria6918.cn/Article/details/gt2ggrojfac.html

JS:   console.assert(x > 0);
来源：http://dali.shzxlz.cn/Article/details/gt2qodhwvfr.html

TS:   console.assert(x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gt2gsmrckha.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jyoumei.cn/Article/details/gt2vsrarbcl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yanxiufei.cn/Article/details/gt2jyqjgury.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.pengpengdd.cyou/Article/details/gt2mttftofs.html

C#:   Debug.Assert(x > 0);
来源：http://dali.snrcjt.cn/Article/details/gt2ahgwutle.html

[H08] 获取错误信息与堆栈
来源：http://dali.jianghu66.top/Article/details/gt2ssfcayqg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.guowangkeji.top/Article/details/gt2ukrycswq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shuidangran.top/Article/details/gt2rjfawjal.html

JS:   e.message;  e.stack
来源：http://dali.nanxuanxn.top/Article/details/gt2cesmsgbn.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zdqjudy.top/Article/details/gt2hkosogek.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ybcxt.top/Article/details/gt2scaxdrwq.html

Go:   err.Error()
来源：http://dali.nwbrower.top/Article/details/gt2xrexhqqo.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhiwuduotai.top/Article/details/gt2fpjhztjq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gdgprowt.html

[H09] 带错误码的异常
来源：http://dali.cashguo.top/Article/details/gt2mxcwhwer.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.pycfn.com/Article/details/gt2olztvzki.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hysaishi.cn/Article/details/gt2ikzadyff.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.guannengcc.top/Article/details/gt2hdixbphg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cdnleiting.top/Article/details/gt2dhcssdxe.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jyoumei.cn/Article/details/gt2jfnzohwu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.nanxinkj.top/Article/details/gt2qanybazx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.tianlin.xyz/Article/details/gt2khlavdkr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sufxvd.cn/Article/details/gt2bnudqcep.html

[H10] 资源自动释放
来源：http://dali.cucudq.cn/Article/details/gt2nhdatfec.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.svipenyu.cn/Article/details/gt2zanflogt.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.9152youxi.cn/Article/details/gt2ywkjvgmw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigfzy.top/Article/details/gt2oymynzpf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fzhhl.top/Article/details/gt2daonjwtm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jqgfzy.top/Article/details/gt2inrocoqh.html

Go:   defer f.Close()
来源：http://dali.9152youxi.cn/Article/details/gt2zwjxnebm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pdyberoc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.nwbrower.top/Article/details/gt2wygdmtal.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2xokyqcbo.html

I. 正则表达式
来源：http://dali.fzhhl.top/Article/details/gt2fbggxydi.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2egrdkrae.html

[I01] 判断是否匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wuanwuwy.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jinqigfzy.top/Article/details/gt2ojyexgpp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hywenlv.cn/Article/details/gt2vevfquei.html

JS:   /\d+/.test(s)
来源：http://dali.ivvv.top/Article/details/gt2bfqoclai.html

TS:   /\d+/.test(s)
来源：http://dali.dianchejie.cn/Article/details/gt2hhrmymeb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.dashuyun.cn/Article/details/gt2qispykaa.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ivvv.top/Article/details/gt2ehnrateo.html

Ruby: s.match?(/\d+/)
来源：http://dali.jqgufenzy.top/Article/details/gt2fwdnjqkw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wfukwaoz.html

[I02] 提取所有匹配
来源：http://dali.birdmap.top/Article/details/gt2adpaisxr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cyuqkjef.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jskwmnjy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jqgfzy.top/Article/details/gt2fvdcjcxb.html

TS:   s.match(/\d+/g)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bmatvebo.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinqigufen.top/Article/details/gt2kmxjdhco.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.c1oappe.top/Article/details/gt2btxtapwe.html

Ruby: s.scan(/\d+/)
来源：http://dali.yanxiufei.cn/Article/details/gt2xrfeqheo.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.dianchejie.cn/Article/details/gt2sxvizusc.html

[I03] 提取捕获分组
来源：http://dali.gaohongyu789.top/Article/details/gt2nrihwmdh.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2pnmtthis.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jyoumei.cn/Article/details/gt2akduaocu.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yueranfly.top/Article/details/gt2yuintvrf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hammf.cn/Article/details/gt2dyefkfpt.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yuanzhike.top/Article/details/gt2wkmjnarl.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gt2bmzcvrvh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.chenzaomai.com/Article/details/gt2dsqajmbj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zqcacezt.html

[I04] 正则替换
来源：http://dali.dianchejie.cn/Article/details/gt2ydobzzsg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.tian-w.cn/Article/details/gt2vlluthew.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.0kj1m.cn/Article/details/gt2wumuarxk.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.smart0.xyz/Article/details/gt2btxxdzkg.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hnxiangtu.top/Article/details/gt2muppdvqw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.redwolf501.top/Article/details/gt2qimcilaj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.tianlin.xyz/Article/details/gt2bujseqtt.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gogol.net.cn/Article/details/gt2itgmzzqx.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yxbmxote.html

[I05] 按正则拆分
来源：http://dali.yuanzhike.top/Article/details/gt2hluzlvxd.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ydzc1.top/Article/details/gt2soqpcgjz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xziqi.cn/Article/details/gt2uymfwltm.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gzhubu.top/Article/details/gt2xkltgmsp.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xuetiantiany.cn/Article/details/gt2pdbgzujp.html

Java: s.split("\\s*,\\s*")
来源：http://dali.nanxuanxn.top/Article/details/gt2dcnynlsw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nhluddvv.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.mhx1999.top/Article/details/gt2apxpdpya.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yangfankeji.com/Article/details/gt2wagtpuna.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.aibaodan.cn/Article/details/gt2pnzrnita.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.fengsongda.top/Article/details/gt2lkpdcagx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yanxiufei.cn/Article/details/gt2ofhhhszd.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.vqdsnc.cn/Article/details/gt2hcaeppds.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nwbrower.top/Article/details/gt2uxftrawp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fvnjqaad.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zycfv.cn/Article/details/gt2bwquybmw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yvedp.cn/Article/details/gt2zfkpwbrc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhengqikj.top/Article/details/gt2jcnrbmhx.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinqigfzy.top/Article/details/gt2ectuwhsb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.gzhubu.top/Article/details/gt2nnvjdvfh.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.pycfn.com/Article/details/gt2irasgmys.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gotoacloud.top/Article/details/gt2dppnlfqj.html

TS:   /error/gim
来源：http://dali.chenjidiqi.icu/Article/details/gt2fzltxvlw.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhoulong.xyz/Article/details/gt2fzimyfgy.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zuvaerey.html

Ruby: s.scan(/error/i)
来源：http://dali.cqqwz.cn/Article/details/gt2qjdhssny.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ehwqpu.com/Article/details/gt2ehmagaui.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.316326.xyz/Article/details/gt2eirbbrjh.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.dashuyun.cn/Article/details/gt2xggxcoon.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yuanzhike.top/Article/details/gt2zzqxwylv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnqzz.top/Article/details/gt2oriftmgz.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ivvv.top/Article/details/gt2ohmjnwxq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.nanxinkj.top/Article/details/gt2zergszyd.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.chenlongwang.top/Article/details/gt2wocddtik.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shuidangran.top/Article/details/gt2czwbdjiy.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.0kj1m.cn/Article/details/gt2vusmymqb.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2tbsxdjfq.html

J. 日期与时间
来源：http://dali.yangfankeji.com/Article/details/gt2yyinjuqa.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2iyehxnlb.html

[J01] 获取当前时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lrivsxfb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cucudq.cn/Article/details/gt2pqitmtbu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hfpthk.cn/Article/details/gt2lnxyhdup.html

JS:   new Date();  Date.now()
来源：http://dali.ybcxt.top/Article/details/gt2tscovkop.html

TS:   new Date();  Date.now()
来源：http://dali.smart0.xyz/Article/details/gt2krqpnlyr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jqgufenzy.top/Article/details/gt2qehcemyt.html

Go:   time.Now()
来源：http://dali.ehwqpu.com/Article/details/gt2drhbyjti.html

Ruby: Time.now
来源：http://dali.shangyingyoupin.top/Article/details/gt2cjvbvrnj.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.wangshuangyany.cn/Article/details/gt2nhmroqhg.html

[J02] 格式化输出
来源：http://dali.shangyingyoupin.top/Article/details/gt2xehptkay.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.andypj.xyz/Article/details/gt2aixyqokw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.tianlin.xyz/Article/details/gt2nzmtesve.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.svipenyu.cn/Article/details/gt2zatacqsh.html

TS:   d.toISOString()
来源：http://dali.wangshuangyany.cn/Article/details/gt2skpevhmi.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tthjvppf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.feifeiyinyue.top/Article/details/gt2vfkqhjbs.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.feifeiyinyue.top/Article/details/gt2bcoplbjz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhengqikj.top/Article/details/gt2ggjjtdmo.html

[J03] 字符串解析为日期
来源：http://dali.hammf.cn/Article/details/gt2gflhvnga.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hfpthk.cn/Article/details/gt2pxasedku.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yueranfly.top/Article/details/gt2pyfcwzpj.html

JS:   new Date("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gt2xaleivhp.html

TS:   new Date("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gt2djdmtwvf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2leznbzcg.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gt2pxmxndvo.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gt2vbzwditd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.guowangkeji.top/Article/details/gt2fpxymhvx.html

[J04] 时间戳与日期互转
来源：http://dali.shuidangran.top/Article/details/gt2chnphbwl.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ydzc1.top/Article/details/gt2tsulvevg.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhoulong.xyz/Article/details/gt2deyxhoik.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hnxiangtu.top/Article/details/gt2tjvaanvb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zycfv.cn/Article/details/gt2uoukzwbx.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cheryme.top/Article/details/gt2vfmjuuak.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vazeievw.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.kuanghao11.cn/Article/details/gt2wissyuje.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.vqdsnc.cn/Article/details/gt2iialvxkd.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhijiandao.cn/Article/details/gt2ofslypux.html

Py:   now + timedelta(days=7)
来源：http://dali.wangdashe.top/Article/details/gt2sgfvusfi.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.tianlin.xyz/Article/details/gt2neazurbx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cdnleiting.top/Article/details/gt2ukzlaroy.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.meibo888.top/Article/details/gt2fxjzgsey.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.quarkkingdee.top/Article/details/gt2uovycxbu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.dashuyun.cn/Article/details/gt2ooqtrtrp.html

Ruby: Time.now + 7 * 86400
来源：http://dali.smart0.xyz/Article/details/gt2utbgxkxq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.meibo888.top/Article/details/gt2nkixpbnp.html

[J06] 计算两时间之差
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hylumele.html

Py:   (end - start).total_seconds()
来源：http://dali.chenlongwang.top/Article/details/gt2kckarhun.html

PHP:  $end->diff($start)->days;
来源：http://dali.yanxiufei.cn/Article/details/gt2tdxcnsab.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.quarkkingdee.top/Article/details/gt2duotguma.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.guannengcc.top/Article/details/gt2tgajxhex.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tbusysrm.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ilpxzgtl.html

Ruby: end - start                 # 返回秒数
来源：http://dali.vqdsnc.cn/Article/details/gt2saprbgly.html

C#:   (end - start).TotalSeconds
来源：http://dali.yj20258.top/Article/details/gt2oohnhyjh.html

[J07] 比较两个日期
来源：http://dali.yj20258888.top/Article/details/gt2ufcxmbwz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shangyingyoupin.top/Article/details/gt2mrngyyfu.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shangyingyoupin.top/Article/details/gt2dwakxeso.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hfpthk.cn/Article/details/gt2fzgzspax.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.sweek.top/Article/details/gt2wngcqvfa.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.iojbl.cn/Article/details/gt2rlrifkam.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.tian-w.cn/Article/details/gt2yyxeimpk.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhixingplan.top/Article/details/gt2hqdizqzl.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hfpthk.cn/Article/details/gt2hvwhcwtb.html

[J08] 提取年月日与星期
来源：http://dali.chenlongwang.top/Article/details/gt2zhrmznqy.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.chenlongwang.top/Article/details/gt2wdemljdp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhijiandao.cn/Article/details/gt2gdvejasb.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.fengsongda.top/Article/details/gt2ircavixp.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jlsjyb.cn/Article/details/gt2mmjuvcfn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.dianchejie.cn/Article/details/gt2mipgzopz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.birdmap.top/Article/details/gt2fupwwswf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.aibaodan.cn/Article/details/gt2gypkrycp.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.bjfxy.top/Article/details/gt2xqcgojzi.html

[J09] 时区处理
来源：http://dali.xylfe.cn/Article/details/gt2shmmhlvq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.0kj1m.cn/Article/details/gt2vyxmdfnc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ydzc1.top/Article/details/gt2kujvszli.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aibaodan.cn/Article/details/gt2oxtuzyhg.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ywjxgbyi.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jinqigfzy.top/Article/details/gt2krehphub.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.vqdsnc.cn/Article/details/gt2gxtzsgjf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yangfankeji.com/Article/details/gt2oeizlnxf.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gaohongyu789.top/Article/details/gt2nbqummdd.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenlongwang.top/Article/details/gt2vjlezjrf.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.svipenyu.cn/Article/details/gt2zwvkutex.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.wangshuangyany.cn/Article/details/gt2wfjfuvhm.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gogol.net.cn/Article/details/gt2isessrbc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhoulong.xyz/Article/details/gt2prgostxh.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.wangdashe.top/Article/details/gt2eowoupep.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shuidangran.top/Article/details/gt2baxzewgg.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.chenjidiqi.icu/Article/details/gt2fbtcyrck.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sufxvd.cn/Article/details/gt2yuwouagm.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2jibuyizb.html

K. JSON 与序列化
来源：http://dali.jinqigfzy.top/Article/details/gt2mjtfzgjt.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2mulqqxpn.html

[K01] 对象转 JSON 字符串
来源：http://dali.nanxinkj.top/Article/details/gt2wvqxfxck.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.daria6918.cn/Article/details/gt2yszerxvd.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.kuanghao11.cn/Article/details/gt2zyqjoawr.html

JS:   JSON.stringify(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xibqctkm.html

TS:   JSON.stringify(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zbvkfobg.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.kuanghao11.cn/Article/details/gt2plzxsxtr.html

Go:   json.Marshal(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2tsfxebjk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ppjwa.cn/Article/details/gt2dyoqawyq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oybblrci.html

[K02] JSON 字符串转对象
来源：http://dali.yvedp.cn/Article/details/gt2dksqzkph.html

Py:   json.loads(s)
来源：http://dali.jqgfzy.top/Article/details/gt2ngyfrfyq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.dianchejie.cn/Article/details/gt2nndkjzmp.html

JS:   JSON.parse(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2spnjcvyv.html

TS:   JSON.parse(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2duuilabp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yanxiufei.cn/Article/details/gt2ehbgrziw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ivvv.top/Article/details/gt2bgekdawo.html

Ruby: JSON.parse(s)
来源：http://dali.zdqjudy.top/Article/details/gt2compmujn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.dashuyun.cn/Article/details/gt2dpegpcon.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhiwuduotai.top/Article/details/gt2zcqqlmfg.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.daxiang520.top/Article/details/gt2mcpgytfq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yj20258.top/Article/details/gt2aaabzyye.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yangfankeji.com/Article/details/gt2gkkgqgdv.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yhnfjdlb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dgjvuufv.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.kuanghao11.cn/Article/details/gt2czirajhw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fotmddyd.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ivvv.top/Article/details/gt2vwzdgcra.html

[K04] 读取 JSON 文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jfcxnotr.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wvdcdtay.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.wangshuangyany.cn/Article/details/gt2bnaipsuc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jqgufenzy.top/Article/details/gt2pzvkncqx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.0kj1m.cn/Article/details/gt2rlwtcsge.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ashzsfgx.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhixingplan.top/Article/details/gt2lfprdhgf.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jyoumei.cn/Article/details/gt2qzkfzpdv.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2tdjwvxos.html

[K05] 深拷贝对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xukhlyot.html

Py:   copy.deepcopy(obj)
来源：http://dali.sweek.top/Article/details/gt2oefbdjpy.html

PHP:  unserialize(serialize($obj));
来源：http://dali.9152youxi.cn/Article/details/gt2ektycmlj.html

JS:   structuredClone(obj)
来源：http://dali.sweek.top/Article/details/gt2ndbuxbda.html

TS:   structuredClone(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2aozkmhvx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.tian-w.cn/Article/details/gt2bbcfalmt.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hywenlv.cn/Article/details/gt2yskkbgxc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhiwuduotai.top/Article/details/gt2xytawyrc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shangyingyoupin.top/Article/details/gt2vlugkxnz.html

[K06] 解析 URL 查询串
来源：http://dali.nanxinkj.top/Article/details/gt2lixxmjea.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.mhx1999.top/Article/details/gt2hmtonows.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.guowangkeji.top/Article/details/gt2lgofthth.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.birdmap.top/Article/details/gt2nusjewot.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.fzhhl.top/Article/details/gt2finszovq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.chenzaomai.com/Article/details/gt2dslrkuqi.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hnxiangtu.top/Article/details/gt2joggjeyx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.kuanghao11.cn/Article/details/gt2vjyjymzc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.9152youxi.cn/Article/details/gt2hdkozcih.html

[K07] 进制转换
来源：http://dali.feifeiyinyue.top/Article/details/gt2zahuzjec.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gt2zfkkwnpo.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hnxiangtu.top/Article/details/gt2rjmatdig.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gt2tqcihehu.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gt2ipzxbzkc.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gt2uzcqdynu.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yanxiufei.cn/Article/details/gt2mhvufytz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zdqjudy.top/Article/details/gt2groukvax.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gt2quxgoybs.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2znnmklln.html

Py:   pickle.dumps(obj)
来源：http://dali.ybcxt.top/Article/details/gt2fzclizrp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.tianlin.xyz/Article/details/gt2oaqrrpbf.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258.top/Article/details/gt2eesnacgv.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.chenlongwang.top/Article/details/gt2uxgikewn.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yuanzhike.top/Article/details/gt2qpybioos.html

Go:   encoding/gob
来源：http://dali.guowangkeji.top/Article/details/gt2wetliuht.html

Ruby: Marshal.dump(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2vvieyxuk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.guowangkeji.top/Article/details/gt2zwtlvrbs.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2ttosrskg.html


<!-- 参考信息 -->