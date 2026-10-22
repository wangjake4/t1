代发 wailian999

JS:   class MyError extends Error {}
来源：http://dali.shzxlz.cn/Article/details/gt2adlyutnm.html

TS:   class MyError extends Error {}
来源：http://dali.hnxiangtu.top/Article/details/gt2pbbjeipb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yangfankeji.com/Article/details/gt2xtsuehdv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yonumen.top/Article/details/gt2latjbmkv.html

Ruby: class MyError < StandardError; end
来源：http://dali.guannengcc.top/Article/details/gt2srlwfvoa.html

C#:   class MyException : Exception {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2ciommtir.html

[H05] 捕获特定类型
来源：http://dali.hfpthk.cn/Article/details/gt2emxwdccz.html

Py:   except ValueError as e:
来源：http://dali.redwolf501.top/Article/details/gt2jpmqbkkf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.svipenyu.cn/Article/details/gt2phdtmbgm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.tian-w.cn/Article/details/gt2zyycuvsh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ivvv.top/Article/details/gt2iagpsyhs.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.9152youxi.cn/Article/details/gt2pwvkqjsz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wekvfxkk.html

Ruby: rescue ArgumentError => e
来源：http://dali.wangdashe.top/Article/details/gt2cmkkguot.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.guowangkeji.top/Article/details/gt2eruqerxs.html

[H06] 可选值 / 空值安全访问
来源：http://dali.chenjidiqi.icu/Article/details/gt2nacmebqf.html

Py:   value = d.get("k") or default
来源：http://dali.yangfankeji.com/Article/details/gt2wcdbnnwx.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhixingplan.top/Article/details/gt2bjsytzni.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cucudq.cn/Article/details/gt2yfmoyoro.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.dianchejie.cn/Article/details/gt2dwlwuvsn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jlsjyb.cn/Article/details/gt2tzhunzdz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hysaishi.cn/Article/details/gt2dlvvkqki.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ehwqpu.com/Article/details/gt2omgalahf.html

C#:   obj?.A?.B ?? default
来源：http://dali.daxiang520.top/Article/details/gt2wuzxjcxn.html

[H07] 断言
来源：http://dali.havefunace.top/Article/details/gt2aoefnyrp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hfpthk.cn/Article/details/gt2iwbszary.html

PHP:  assert($x > 0);
来源：http://dali.hysaishi.cn/Article/details/gt2nfokojyy.html

JS:   console.assert(x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gt2kivrkcwx.html

TS:   console.assert(x > 0);
来源：http://dali.xylfe.cn/Article/details/gt2hhvtlxhr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rjwetfem.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shzxlz.cn/Article/details/gt2oyjcouoq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yongpay.top/Article/details/gt2saeaqgqy.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gt2hshkjcik.html

[H08] 获取错误信息与堆栈
来源：http://dali.feifeiyinyue.top/Article/details/gt2oruqzodn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.316326.xyz/Article/details/gt2lapnsoda.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hnxiangtu.top/Article/details/gt2gbteyozt.html

JS:   e.message;  e.stack
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2plhypvsr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oezkqawo.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.iojbl.cn/Article/details/gt2zvfzlyca.html

Go:   err.Error()
来源：http://dali.daxiang520.top/Article/details/gt2bhetxzze.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2huknesfu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xylfe.cn/Article/details/gt2jsexivqj.html

[H09] 带错误码的异常
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bbmrmfzv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.dashuyun.cn/Article/details/gt2wkwqzgpz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.dianchejie.cn/Article/details/gt2wwhkqxny.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yanxiufei.cn/Article/details/gt2saadnvyn.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.redwolf501.top/Article/details/gt2zseiuvkt.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenlongwang.top/Article/details/gt2osmnrrgc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yonumen.top/Article/details/gt2zvxqjeyz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.dashuyun.cn/Article/details/gt2tsjolxcy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jyoumei.cn/Article/details/gt2wkikpmlp.html

[H10] 资源自动释放
来源：http://dali.wangdashe.top/Article/details/gt2gqnwhmfy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jyoumei.cn/Article/details/gt2ensgyiyx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.0kj1m.cn/Article/details/gt2faqgtqco.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cashguo.top/Article/details/gt2ececdxhu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xinyue.icu/Article/details/gt2jlrnzhvz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xuanzx.com/Article/details/gt2iglwkcnc.html

Go:   defer f.Close()
来源：http://dali.pycfn.com/Article/details/gt2jkraawar.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tian-w.cn/Article/details/gt2qqykalfr.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yonumen.top/Article/details/gt2aqpsfcrc.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2vgayqyjy.html

I. 正则表达式
来源：http://dali.gotoacloud.top/Article/details/gt2gmwirilr.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2sdsmuyak.html

[I01] 判断是否匹配
来源：http://dali.jiagoushi.top/Article/details/gt2owmclntz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ppjwa.cn/Article/details/gt2wdwltuqk.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jianghu66.top/Article/details/gt2vanzpyze.html

JS:   /\d+/.test(s)
来源：http://dali.smart0.xyz/Article/details/gt2wowxdvih.html

TS:   /\d+/.test(s)
来源：http://dali.hnqzz.top/Article/details/gt2wfpbrmmm.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.aizwys.cn/Article/details/gt2oqytvpob.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2tpzqgria.html

Ruby: s.match?(/\d+/)
来源：http://dali.316326.xyz/Article/details/gt2mdgtthys.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.feifeiyinyue.top/Article/details/gt2klxvtqph.html

[I02] 提取所有匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vrzaeszq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.0kj1m.cn/Article/details/gt2gyowgdku.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.birdmap.top/Article/details/gt2wwzlsevz.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xhtrlfmt.html

TS:   s.match(/\d+/g)
来源：http://dali.gzhubu.top/Article/details/gt2krvudltl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cheryme.top/Article/details/gt2wlkkcdnq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.havefunace.top/Article/details/gt2whhrqero.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhiwuduotai.top/Article/details/gt2kcnkfwex.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oxxcunwq.html

[I03] 提取捕获分组
来源：http://dali.jinqigfzy.top/Article/details/gt2pvywqvsv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.dianchejie.cn/Article/details/gt2tbhjnrrh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhoulong.xyz/Article/details/gt2okvmdsip.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shzxlz.cn/Article/details/gt2pdendgmn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xuetiantiany.cn/Article/details/gt2bczhcgmg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.wangdashe.top/Article/details/gt2kecxpsua.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yangfankeji.com/Article/details/gt2gqvdgpkm.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shzxlz.cn/Article/details/gt2nmujgqug.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jqgufenzy.top/Article/details/gt2oaihiegu.html

[I04] 正则替换
来源：http://dali.wangshuangyany.cn/Article/details/gt2niyaxvld.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.sxryk.cn/Article/details/gt2ilyejkdq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.quarkkingdee.top/Article/details/gt2seroetxf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.nwbrower.top/Article/details/gt2ohxwsuor.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.tian-w.cn/Article/details/gt2myhpbsmv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhengqikj.top/Article/details/gt2teasmnbu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cucudq.cn/Article/details/gt2oanwkdit.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.tianlin.xyz/Article/details/gt2pnddallw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xuanzx.com/Article/details/gt2unptrizd.html

[I05] 按正则拆分
来源：http://dali.jqgufenzy.top/Article/details/gt2rlddnprw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pqisuwut.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hnqzz.top/Article/details/gt2egbqovye.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhoulong.xyz/Article/details/gt2wiszvjyq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2docxrwpd.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jyoumei.cn/Article/details/gt2eibjtsae.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.nanxuanxn.top/Article/details/gt2ltrtmzbc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gt2ogklumxf.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gzhubu.top/Article/details/gt2knljypxp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pstgpvfk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.mhx1999.top/Article/details/gt2weeycewz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.iojbl.cn/Article/details/gt2qdnyhqap.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zhsxbecm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenzaomai.com/Article/details/gt2cmobtziy.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hammf.cn/Article/details/gt2ubpdedmm.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.chenlongwang.top/Article/details/gt2tcknqisy.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.svipenyu.cn/Article/details/gt2duemjcoo.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xuetiantiany.cn/Article/details/gt2xarbzcmr.html

[I07] 忽略大小写与多行模式
来源：http://dali.hnqzz.top/Article/details/gt2xmqymmsf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.9152youxi.cn/Article/details/gt2llngkafz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.svipenyu.cn/Article/details/gt2lelpjwcd.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.nanxuanxn.top/Article/details/gt2ssfncedh.html

TS:   /error/gim
来源：http://dali.ydzc1.top/Article/details/gt2mhmwtskv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.dianchejie.cn/Article/details/gt2sgttzour.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jqgfzy.top/Article/details/gt2btmwvimu.html

Ruby: s.scan(/error/i)
来源：http://dali.ppjwa.cn/Article/details/gt2vfmdbgyj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2frajfiei.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.vqdsnc.cn/Article/details/gt2gsxceqhv.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.tanke756.top/Article/details/gt2yklzgubj.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.daxiang520.top/Article/details/gt2rpumvgqk.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jiagoushi.top/Article/details/gt2ccugywwa.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shzxlz.cn/Article/details/gt2txvbgndk.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhoulong.xyz/Article/details/gt2svobqdnt.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhixingplan.top/Article/details/gt2sevlvsul.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.kuanghao11.cn/Article/details/gt2ecxsonqq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.tianlin.xyz/Article/details/gt2yuezlpxf.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2ryrdglwh.html

J. 日期与时间
来源：http://dali.feifeiyinyue.top/Article/details/gt2cdkdsvsj.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2vsvdptfd.html

[J01] 获取当前时间
来源：http://dali.ydzc1.top/Article/details/gt2feaftrwl.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yonumen.top/Article/details/gt2sjwuqcxc.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xinyue.icu/Article/details/gt2uxvuryrl.html

JS:   new Date();  Date.now()
来源：http://dali.zhengqikj.top/Article/details/gt2byvxiatu.html

TS:   new Date();  Date.now()
来源：http://dali.ydzc1.top/Article/details/gt2nwtdyaqr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.daria6918.cn/Article/details/gt2nhqhcqtg.html

Go:   time.Now()
来源：http://dali.cdnleiting.top/Article/details/gt2uxlvdexo.html

Ruby: Time.now
来源：http://dali.hnxiangtu.top/Article/details/gt2ygbamqfu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yueranfly.top/Article/details/gt2gelmttjx.html

[J02] 格式化输出
来源：http://dali.cashguo.top/Article/details/gt2ievgfyam.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hammf.cn/Article/details/gt2azxdsftr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rkkvdins.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.316326.xyz/Article/details/gt2nlshxjmw.html

TS:   d.toISOString()
来源：http://dali.hnqzz.top/Article/details/gt2skfbjybm.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.guowangkeji.top/Article/details/gt2smsedbmd.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xuanzx.com/Article/details/gt2fivuegfx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xinyue.icu/Article/details/gt2oamlmqxe.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sysykeji.top/Article/details/gt2zankqwfu.html

[J03] 字符串解析为日期
来源：http://dali.yvedp.cn/Article/details/gt2cdafgwnm.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ivvv.top/Article/details/gt2gvdeavrz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cashguo.top/Article/details/gt2rgyyjyzf.html

JS:   new Date("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gt2bteefkim.html

TS:   new Date("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2prrfwssp.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gt2halbmymo.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gt2bwomaxgt.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gt2bxcqjcem.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.daria6918.cn/Article/details/gt2eglsvdgh.html

[J04] 时间戳与日期互转
来源：http://dali.ydzc1.top/Article/details/gt2wzrhgbmh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shangyingyoupin.top/Article/details/gt2szhxcrrq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qdbbphks.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xuetiantiany.cn/Article/details/gt2pzqxubfj.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xuetiantiany.cn/Article/details/gt2mdtogcve.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yj20258888.top/Article/details/gt2ernbeoxf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.dianchejie.cn/Article/details/gt2snkymnwl.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.9152youxi.cn/Article/details/gt2jnouamcb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ivvv.top/Article/details/gt2skfuhtpc.html

[J05] 时间加减（加 7 天）
来源：http://dali.nwbrower.top/Article/details/gt2dkpbpdyd.html

Py:   now + timedelta(days=7)
来源：http://dali.yj202588.top/Article/details/gt2dljtxriv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ypkofiqc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yueranfly.top/Article/details/gt2jknoiftt.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dashuyun.cn/Article/details/gt2udjuqzga.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.tianlin.xyz/Article/details/gt2hqftrcyz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.chenlongwang.top/Article/details/gt2gibwixsj.html

Ruby: Time.now + 7 * 86400
来源：http://dali.birdmap.top/Article/details/gt2dqusolgn.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yangfankeji.com/Article/details/gt2thzvxani.html

[J06] 计算两时间之差
来源：http://dali.yueranfly.top/Article/details/gt2gkfikarw.html

Py:   (end - start).total_seconds()
来源：http://dali.xziqi.cn/Article/details/gt2cgtdodns.html

PHP:  $end->diff($start)->days;
来源：http://dali.shzxlz.cn/Article/details/gt2fscekfll.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.guannengcc.top/Article/details/gt2vkgaexls.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jyoumei.cn/Article/details/gt2hwrwdwfw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jqgfzy.top/Article/details/gt2ognmdvta.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinqigufen.top/Article/details/gt2kndteghi.html

Ruby: end - start                 # 返回秒数
来源：http://dali.pengpengdd.cyou/Article/details/gt2syqfevjv.html

C#:   (end - start).TotalSeconds
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qhhiypxj.html

[J07] 比较两个日期
来源：http://dali.0kj1m.cn/Article/details/gt2viyhtuuu.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.tianlin.xyz/Article/details/gt2fpisbwyh.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jqgfzy.top/Article/details/gt2nggizdyy.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ppjwa.cn/Article/details/gt2wjqqzbfu.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.haohaochexian.top/Article/details/gt2csfrgjwh.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.fengsongda.top/Article/details/gt2oephjuxm.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.mhx1999.top/Article/details/gt2cajjlnmh.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yueranfly.top/Article/details/gt2treovgyl.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.wangshuangyany.cn/Article/details/gt2ggkarcil.html

[J08] 提取年月日与星期
来源：http://dali.jyoumei.cn/Article/details/gt2aolabhpy.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.redwolf501.top/Article/details/gt2xxghvwmh.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cqqwz.cn/Article/details/gt2eiawuvhn.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yuxming.cn/Article/details/gt2tvgzcbjb.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shuidangran.top/Article/details/gt2ebtrlbod.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhengqikj.top/Article/details/gt2gdnfesne.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gzhubu.top/Article/details/gt2tkhckick.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zycfv.cn/Article/details/gt2xbyjqlrr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.chenjidiqi.icu/Article/details/gt2abespopl.html

[J09] 时区处理
来源：http://dali.shangyingyoupin.top/Article/details/gt2nyslrten.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhongyouzk.top/Article/details/gt2uqhnhvvg.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jlsjyb.cn/Article/details/gt2luahmcsa.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gotoacloud.top/Article/details/gt2gghkfjiq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258888.top/Article/details/gt2rclkyluy.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yvedp.cn/Article/details/gt2wtaspddg.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cdnleiting.top/Article/details/gt2gjspsnhz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yangfankeji.com/Article/details/gt2akmnvtmc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sxryk.cn/Article/details/gt2ftigbmpo.html

[J10] 取今天 / 本月第一天
来源：http://dali.jlsjyb.cn/Article/details/gt2dtoffgag.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rietlufh.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gzhubu.top/Article/details/gt2gobjmjbp.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sxryk.cn/Article/details/gt2jfftymis.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.vqdsnc.cn/Article/details/gt2nckikost.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gzhubu.top/Article/details/gt2sfyugfiv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhongyouzk.top/Article/details/gt2wgsiaxiq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sufxvd.cn/Article/details/gt2wyivsrgl.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sufxvd.cn/Article/details/gt2omhywpcg.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2xhfwbcpa.html

K. JSON 与序列化
来源：http://dali.tanke756.top/Article/details/gt2qsqqhczz.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2boevkvup.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2umibayfn.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yongpay.top/Article/details/gt2oxxxusjq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xziqi.cn/Article/details/gt2ookdhtjh.html

JS:   JSON.stringify(obj)
来源：http://dali.redwolf501.top/Article/details/gt2jkgraxxq.html

TS:   JSON.stringify(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2pfwfhmol.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.guowangkeji.top/Article/details/gt2nwfumpvm.html

Go:   json.Marshal(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2txpwlaut.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.aibaodan.cn/Article/details/gt2hxnvlutg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2snxqvdbh.html

[K02] JSON 字符串转对象
来源：http://dali.fzhhl.top/Article/details/gt2rwievqml.html

Py:   json.loads(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kdjqfcdv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.nanxuanxn.top/Article/details/gt2mctlsbkj.html

JS:   JSON.parse(s)
来源：http://dali.zycfv.cn/Article/details/gt2lxortzzr.html

TS:   JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2gkachhed.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xuetiantiany.cn/Article/details/gt2eafkufys.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.chenlongwang.top/Article/details/gt2ttqakfgt.html

Ruby: JSON.parse(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ocvyrnhg.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xinyue.icu/Article/details/gt2medkesha.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yj202588.top/Article/details/gt2vylpyrpn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.dashuyun.cn/Article/details/gt2xdmcsyyl.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.chenlongwang.top/Article/details/gt2neyomxsb.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258.top/Article/details/gt2ictflbhm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.bjfxy.top/Article/details/gt2lzfntpqo.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2ftlllmax.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xuanzx.com/Article/details/gt2tquwyxkx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.daria6918.cn/Article/details/gt2osouiuqd.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.meibo888.top/Article/details/gt2zzjrvyou.html

[K04] 读取 JSON 文件
来源：http://dali.quarkkingdee.top/Article/details/gt2fgturdee.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hnxiangtu.top/Article/details/gt2bigtgzjm.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.haohaochexian.top/Article/details/gt2hcjgqdkg.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wkpaymjn.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gotoacloud.top/Article/details/gt2hzdpktph.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.chenzaomai.com/Article/details/gt2yptgcswf.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jianghu66.top/Article/details/gt2rmgcjldv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.tian-w.cn/Article/details/gt2djpapapc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xziqi.cn/Article/details/gt2veaaulvt.html

[K05] 深拷贝对象
来源：http://dali.xziqi.cn/Article/details/gt2uhxlwhbp.html

Py:   copy.deepcopy(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2vrrqirkf.html

PHP:  unserialize(serialize($obj));
来源：http://dali.fengsongda.top/Article/details/gt2nhzmwqqe.html

JS:   structuredClone(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ohyapsuo.html

TS:   structuredClone(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2zqbybytq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.gogol.net.cn/Article/details/gt2qglavsju.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.bjfxy.top/Article/details/gt2rwhrymbp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zdqjudy.top/Article/details/gt2spnyybpz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinqigufen.top/Article/details/gt2bevjmysv.html

[K06] 解析 URL 查询串
来源：http://dali.yj202588.top/Article/details/gt2zoejqgwd.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yuxming.cn/Article/details/gt2cjrobcav.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ivvv.top/Article/details/gt2lklguicc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.bjfxy.top/Article/details/gt2xvffksxx.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tanke756.top/Article/details/gt2vwsyspjx.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.wangshuangyany.cn/Article/details/gt2nnjgcmvg.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.tanke756.top/Article/details/gt2zeocupdp.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.c1oappe.top/Article/details/gt2xmgvkucd.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.chenlongwang.top/Article/details/gt2fbwcnsii.html

[K07] 进制转换
来源：http://dali.cdnleiting.top/Article/details/gt2grrzyoey.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gt2oibsylgr.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ucyvuzmt.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gt2meepykbw.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gt2fvzmnyfl.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cheryme.top/Article/details/gt2zvktgcrs.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xziqi.cn/Article/details/gt2vcldnpax.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhongyouzk.top/Article/details/gt2mjaphmhp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gt2ryfyryoy.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.pengpengdd.cyou/Article/details/gt2hatqnycu.html

Py:   pickle.dumps(obj)
来源：http://dali.iojbl.cn/Article/details/gt2frsudnxu.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sysykeji.top/Article/details/gt2adbgbfwh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hongshengwenyu.top/Article/details/gt2syicqfzr.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hfpthk.cn/Article/details/gt2idefnstu.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xuanzx.com/Article/details/gt2vgjuzgcu.html


<!-- 参考信息 -->