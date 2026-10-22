代发 wailian999

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gt2xczwbqqk.html

[H04] 自定义异常类型
来源：http://dali.hnqzz.top/Article/details/gt2zgabirlv.html

Py:   class MyError(Exception): pass
来源：http://dali.guannengcc.top/Article/details/gt2dljelvwc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.daxiang520.top/Article/details/gt2ppmlipxh.html

JS:   class MyError extends Error {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2uevgqkmz.html

TS:   class MyError extends Error {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2hbqxwrqr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ybcxt.top/Article/details/gt2ztevdgxn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinqigufen.top/Article/details/gt2xnlrdqws.html

Ruby: class MyError < StandardError; end
来源：http://dali.nanxuanxn.top/Article/details/gt2yyfryajh.html

C#:   class MyException : Exception {}
来源：http://dali.havefunace.top/Article/details/gt2frpreaqg.html

[H05] 捕获特定类型
来源：http://dali.hammf.cn/Article/details/gt2hrloimzn.html

Py:   except ValueError as e:
来源：http://dali.yongpay.top/Article/details/gt2uqjctbvq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xziqi.cn/Article/details/gt2roeewqfe.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sufxvd.cn/Article/details/gt2hsvwwgbp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2haoojvry.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zycfv.cn/Article/details/gt2bnwybozz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ivvv.top/Article/details/gt2ydlszjlo.html

Ruby: rescue ArgumentError => e
来源：http://dali.cdnleiting.top/Article/details/gt2mfjxylhd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.tianlin.xyz/Article/details/gt2tircrsox.html

[H06] 可选值 / 空值安全访问
来源：http://dali.quarkkingdee.top/Article/details/gt2ojyutkvt.html

Py:   value = d.get("k") or default
来源：http://dali.yj20258888.top/Article/details/gt2aapnybpx.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yuanzhike.top/Article/details/gt2zikkvjpc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.birdmap.top/Article/details/gt2mnceftfj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.daxiang520.top/Article/details/gt2bnrkeytb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvkdytsu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xylfe.cn/Article/details/gt2ntjkaaaf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.nwbrower.top/Article/details/gt2ikcjnytv.html

C#:   obj?.A?.B ?? default
来源：http://dali.wangdashe.top/Article/details/gt2brkwfnyp.html

[H07] 断言
来源：http://dali.hysaishi.cn/Article/details/gt2auepkdkt.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xziqi.cn/Article/details/gt2budgaahh.html

PHP:  assert($x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hijogvcu.html

JS:   console.assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gt2nefcinpj.html

TS:   console.assert(x > 0);
来源：http://dali.ybcxt.top/Article/details/gt2xlakzlbu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jiagoushi.top/Article/details/gt2rklzzhfp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bpgeycip.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xziqi.cn/Article/details/gt2jlzqbupb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.havefunace.top/Article/details/gt2ucktghca.html

[H08] 获取错误信息与堆栈
来源：http://dali.hongshengwenyu.top/Article/details/gt2jlasrwku.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jlsjyb.cn/Article/details/gt2qvtqhofr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2shainmtd.html

JS:   e.message;  e.stack
来源：http://dali.guowangkeji.top/Article/details/gt2jqmsokre.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ppjwa.cn/Article/details/gt2nsniauwz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ydzc1.top/Article/details/gt2rvuetltt.html

Go:   err.Error()
来源：http://dali.yj20258.top/Article/details/gt2adcukwab.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhoulong.xyz/Article/details/gt2vrowuxmx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gotoacloud.top/Article/details/gt2qzpjodsf.html

[H09] 带错误码的异常
来源：http://dali.sxryk.cn/Article/details/gt2lriirkzy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yonumen.top/Article/details/gt2mzanzdlf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ppjwa.cn/Article/details/gt2luszykng.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.c1oappe.top/Article/details/gt2zdatvqvt.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.daria6918.cn/Article/details/gt2vjretnpr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hywenlv.cn/Article/details/gt2puwdsmxm.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.haohaochexian.top/Article/details/gt2qrrwlaff.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.nwbrower.top/Article/details/gt2gyycsdcc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cqqwz.cn/Article/details/gt2plqculwy.html

[H10] 资源自动释放
来源：http://dali.ehwqpu.com/Article/details/gt2lhserrvk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.chenzaomai.com/Article/details/gt2xpcdlxjx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gaohongyu789.top/Article/details/gt2hmnkkyrs.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenzaomai.com/Article/details/gt2knwxugyw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cqqwz.cn/Article/details/gt2vlasaksr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yj20258888.top/Article/details/gt2uwewgqzb.html

Go:   defer f.Close()
来源：http://dali.zycfv.cn/Article/details/gt2knfnmogl.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.havefunace.top/Article/details/gt2owmwmdji.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cucudq.cn/Article/details/gt2ttsygusq.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2zkxtzyta.html

I. 正则表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mlycwdak.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2ilvaqcxw.html

[I01] 判断是否匹配
来源：http://dali.zhiwuduotai.top/Article/details/gt2qpvslfvz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.dianchejie.cn/Article/details/gt2ytbqqqzg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.snrcjt.cn/Article/details/gt2firwfdsg.html

JS:   /\d+/.test(s)
来源：http://dali.jianghu66.top/Article/details/gt2yauzlbzv.html

TS:   /\d+/.test(s)
来源：http://dali.zycfv.cn/Article/details/gt2svgaemak.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hysaishi.cn/Article/details/gt2notcnzct.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.tian-w.cn/Article/details/gt2qjmqnhcs.html

Ruby: s.match?(/\d+/)
来源：http://dali.gaohongyu789.top/Article/details/gt2oyveaukz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.tian-w.cn/Article/details/gt2yhemioxw.html

[I02] 提取所有匹配
来源：http://dali.jqgufenzy.top/Article/details/gt2lmjefscm.html

Py:   re.findall(r"\d+", s)
来源：http://dali.andypj.xyz/Article/details/gt2ywnlbeqt.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xinyue.icu/Article/details/gt2jnsxcgzf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.meibo888.top/Article/details/gt2wkthzwph.html

TS:   s.match(/\d+/g)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vsubqjjt.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zycfv.cn/Article/details/gt2dgdjyntf.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.daria6918.cn/Article/details/gt2gikaasfa.html

Ruby: s.scan(/\d+/)
来源：http://dali.c1oappe.top/Article/details/gt2zpxpyoop.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gt2iuiwudgr.html

[I03] 提取捕获分组
来源：http://dali.jinqigfzy.top/Article/details/gt2rbtewjvo.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.chenzaomai.com/Article/details/gt2hvrhbifj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cheryme.top/Article/details/gt2uilfechc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yueranfly.top/Article/details/gt2nynuavrq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ehwqpu.com/Article/details/gt2wghvxnjy.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.pengpengdd.cyou/Article/details/gt2mmunryaf.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shuidangran.top/Article/details/gt2sluffdmi.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.guowangkeji.top/Article/details/gt2tzdacpea.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gplsoyrh.html

[I04] 正则替换
来源：http://dali.sxryk.cn/Article/details/gt2atmvhvft.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ybcxt.top/Article/details/gt2rxheljbn.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.ppjwa.cn/Article/details/gt2ngiqhvss.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sxryk.cn/Article/details/gt2iaujzzci.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.316326.xyz/Article/details/gt2omexzafp.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jqgfzy.top/Article/details/gt2lygtvbol.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hammf.cn/Article/details/gt2vmysvgpl.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinqigufen.top/Article/details/gt2qjocqybf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hywenlv.cn/Article/details/gt2elmfbzka.html

[I05] 按正则拆分
来源：http://dali.hnxiangtu.top/Article/details/gt2dnghxbza.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jiagoushi.top/Article/details/gt2lbmpsukg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jiagoushi.top/Article/details/gt2mlsjvwfr.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.daxiang520.top/Article/details/gt2udgfnkqx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.aizwys.cn/Article/details/gt2grcvsjrb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yuanzhike.top/Article/details/gt2zrypkvto.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yueranfly.top/Article/details/gt2atkuvjjx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.nanxuanxn.top/Article/details/gt2keelnoet.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.andypj.xyz/Article/details/gt2mkgrrvwp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gaohongyu789.top/Article/details/gt2wptxsusb.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.haohaochexian.top/Article/details/gt2crxdrfwc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oakckmkk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnxiangtu.top/Article/details/gt2qzivhzye.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yongpay.top/Article/details/gt2gpfihpyn.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.wangdashe.top/Article/details/gt2rpzyjmno.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sweek.top/Article/details/gt2trswtpvv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hywenlv.cn/Article/details/gt2teawgnor.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gt2sxihxrae.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhengqikj.top/Article/details/gt2dcnjacvk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.meibo888.top/Article/details/gt2upiahjaq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.vqdsnc.cn/Article/details/gt2gezsxgrt.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinqigfzy.top/Article/details/gt2emuipdur.html

TS:   /error/gim
来源：http://dali.9152youxi.cn/Article/details/gt2mwzsgben.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jiagoushi.top/Article/details/gt2dzalrnws.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shuidangran.top/Article/details/gt2bdvnfebh.html

Ruby: s.scan(/error/i)
来源：http://dali.feifeiyinyue.top/Article/details/gt2kcvupqbi.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shangyingyoupin.top/Article/details/gt2gistfesp.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xinyue.icu/Article/details/gt2nofjxalw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.tianlin.xyz/Article/details/gt2feeqauhg.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ydzc1.top/Article/details/gt2sbkjpxme.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aqzznnht.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenlongwang.top/Article/details/gt2kcnbbstr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xylfe.cn/Article/details/gt2ltfwjiof.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.pycfn.com/Article/details/gt2nqyzgoje.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.316326.xyz/Article/details/gt2lbpqpqhm.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.dashuyun.cn/Article/details/gt2ytbngvjp.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2kyoecrtv.html

J. 日期与时间
来源：http://dali.jianghu66.top/Article/details/gt2ctdtquhg.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2kmusgwmq.html

[J01] 获取当前时间
来源：http://dali.hywenlv.cn/Article/details/gt2dbffxwds.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yj202588.top/Article/details/gt2giwbhdew.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rkeuvxwh.html

JS:   new Date();  Date.now()
来源：http://dali.iojbl.cn/Article/details/gt2zclegaug.html

TS:   new Date();  Date.now()
来源：http://dali.sxryk.cn/Article/details/gt2ksmxgeeq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uklgjeqy.html

Go:   time.Now()
来源：http://dali.guowangkeji.top/Article/details/gt2qxsywmih.html

Ruby: Time.now
来源：http://dali.kuanghao11.cn/Article/details/gt2uddakzfh.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.gzhubu.top/Article/details/gt2dypszaxw.html

[J02] 格式化输出
来源：http://dali.hywenlv.cn/Article/details/gt2lipbfzve.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dashuyun.cn/Article/details/gt2mdcwltzx.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.quarkkingdee.top/Article/details/gt2axctaojp.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jqgfzy.top/Article/details/gt2vhnweits.html

TS:   d.toISOString()
来源：http://dali.hysaishi.cn/Article/details/gt2zojruqaz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hnqzz.top/Article/details/gt2jewujkcf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.nanxinkj.top/Article/details/gt2qjrtfrct.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhoulong.xyz/Article/details/gt2rjwfelpm.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xylfe.cn/Article/details/gt2prgvghjv.html

[J03] 字符串解析为日期
来源：http://dali.yuxming.cn/Article/details/gt2eihbsumc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jyoumei.cn/Article/details/gt2tmlunoma.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.svipenyu.cn/Article/details/gt2pmpsqkzb.html

JS:   new Date("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gt2tlsxbrnz.html

TS:   new Date("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gt2meonrkwt.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jpvbnqla.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sweek.top/Article/details/gt2lsgtokoc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yueranfly.top/Article/details/gt2neupvgvh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.nanxinkj.top/Article/details/gt2jmqdqmnp.html

[J04] 时间戳与日期互转
来源：http://dali.aizwys.cn/Article/details/gt2jwddakot.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jyoumei.cn/Article/details/gt2biifnqcg.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.c1oappe.top/Article/details/gt2iehtdlaq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pttxhwtu.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jiagoushi.top/Article/details/gt2iuhrainl.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.fzhhl.top/Article/details/gt2ajgogxqf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shuidangran.top/Article/details/gt2vvivyxlc.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.vqdsnc.cn/Article/details/gt2kwacjccy.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yongpay.top/Article/details/gt2fuertdij.html

[J05] 时间加减（加 7 天）
来源：http://dali.xuanzx.com/Article/details/gt2ovbvytye.html

Py:   now + timedelta(days=7)
来源：http://dali.hnxiangtu.top/Article/details/gt2nrfxtrmq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.nanxuanxn.top/Article/details/gt2lgqxrumx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.redwolf501.top/Article/details/gt2pcbmtqlq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shuidangran.top/Article/details/gt2ynwgptkm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.smart0.xyz/Article/details/gt2pvzoymcr.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.pycfn.com/Article/details/gt2wptjwpqp.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ivvv.top/Article/details/gt2gfulhnwl.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.svipenyu.cn/Article/details/gt2uxiaqufd.html

[J06] 计算两时间之差
来源：http://dali.guowangkeji.top/Article/details/gt2iunkhuwk.html

Py:   (end - start).total_seconds()
来源：http://dali.cashguo.top/Article/details/gt2wlgysgcp.html

PHP:  $end->diff($start)->days;
来源：http://dali.pycfn.com/Article/details/gt2ggmmedgv.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sedjnhju.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.mhx1999.top/Article/details/gt2tkwezufk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nanmodqk.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhongyouzk.top/Article/details/gt2bkaoedys.html

Ruby: end - start                 # 返回秒数
来源：http://dali.bjfxy.top/Article/details/gt2lykxuuyp.html

C#:   (end - start).TotalSeconds
来源：http://dali.xuanzx.com/Article/details/gt2ajqwpggg.html

[J07] 比较两个日期
来源：http://dali.mhx1999.top/Article/details/gt2mzuojlbw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hongshengwenyu.top/Article/details/gt2zciyeczq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhengqikj.top/Article/details/gt2xkybrxwi.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vgpvvadi.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.sysykeji.top/Article/details/gt2ztwtzvdi.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hysaishi.cn/Article/details/gt2nnxfeqds.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.smart0.xyz/Article/details/gt2ixqiaice.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.tian-w.cn/Article/details/gt2exenwenr.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.tian-w.cn/Article/details/gt2wmqckbty.html

[J08] 提取年月日与星期
来源：http://dali.cheryme.top/Article/details/gt2jgmfcpbj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yangfankeji.com/Article/details/gt2yinylxuj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cdnleiting.top/Article/details/gt2hkpgduxq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.kuanghao11.cn/Article/details/gt2ehzzwyfs.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.vqdsnc.cn/Article/details/gt2tquqcfle.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jianghu66.top/Article/details/gt2glbznzvd.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yongpay.top/Article/details/gt2hsxdxvyr.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gotoacloud.top/Article/details/gt2uckirlka.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hysaishi.cn/Article/details/gt2rbgdfdbg.html

[J09] 时区处理
来源：http://dali.tianlin.xyz/Article/details/gt2rgfgfjbo.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.sysykeji.top/Article/details/gt2fhqyacai.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinqigfzy.top/Article/details/gt2vjuwywbo.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jxvmmozb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guannengcc.top/Article/details/gt2yuirvaax.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.mhx1999.top/Article/details/gt2fnoglnti.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.svipenyu.cn/Article/details/gt2yqxxmydq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dumefdet.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sxryk.cn/Article/details/gt2qujkgzgu.html

[J10] 取今天 / 本月第一天
来源：http://dali.sweek.top/Article/details/gt2rlvuxsmd.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.tian-w.cn/Article/details/gt2klnxnpmq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yuanzhike.top/Article/details/gt2ibbkejem.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yj20258888.top/Article/details/gt2uwpwcncj.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.meibo888.top/Article/details/gt2bprwvfyx.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2clkomzno.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.0kj1m.cn/Article/details/gt2wcsrgjae.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jqgfzy.top/Article/details/gt2ltvmgyxf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zdqjudy.top/Article/details/gt2hcgbvjgp.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2cfgrppfe.html

K. JSON 与序列化
来源：http://dali.pengpengdd.cyou/Article/details/gt2lroqssyb.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2yaehyomx.html

[K01] 对象转 JSON 字符串
来源：http://dali.havefunace.top/Article/details/gt2nhoydzmu.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhengqikj.top/Article/details/gt2lokcueqn.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.c1oappe.top/Article/details/gt2ugcsnwbz.html

JS:   JSON.stringify(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2hckmqkel.html

TS:   JSON.stringify(obj)
来源：http://dali.ivvv.top/Article/details/gt2qbxqbvti.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.sufxvd.cn/Article/details/gt2xomjwciq.html

Go:   json.Marshal(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2szuxrlhf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gzhubu.top/Article/details/gt2xdumnqfu.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2fsvimbsb.html

[K02] JSON 字符串转对象
来源：http://dali.c1oappe.top/Article/details/gt2yergsqyo.html

Py:   json.loads(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yuwtjxde.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenjidiqi.icu/Article/details/gt2ldigqbyo.html

JS:   JSON.parse(s)
来源：http://dali.hywenlv.cn/Article/details/gt2ivkubbvw.html

TS:   JSON.parse(s)
来源：http://dali.sufxvd.cn/Article/details/gt2yfrdfium.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.tanke756.top/Article/details/gt2psrblfbg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.iojbl.cn/Article/details/gt2ookzpjbb.html

Ruby: JSON.parse(s)
来源：http://dali.tianlin.xyz/Article/details/gt2skfeatdw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.c1oappe.top/Article/details/gt2xzjxtqce.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xylfe.cn/Article/details/gt2grenrpby.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xinyue.icu/Article/details/gt2hxkvevou.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.kuanghao11.cn/Article/details/gt2xvdeoieq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cusltthk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuxming.cn/Article/details/gt2suazhbyb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.iojbl.cn/Article/details/gt2wyhbyvuu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ppjwa.cn/Article/details/gt2xenkdluh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.andypj.xyz/Article/details/gt2jhcddsfh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yuanzhike.top/Article/details/gt2xgculcoy.html

[K04] 读取 JSON 文件
来源：http://dali.dianchejie.cn/Article/details/gt2cqnlkgel.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sufxvd.cn/Article/details/gt2evdqvzgg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.smart0.xyz/Article/details/gt2yrxklbww.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yongpay.top/Article/details/gt2zaeopcid.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.vqdsnc.cn/Article/details/gt2gdqavxci.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hammf.cn/Article/details/gt2jcmzhfmy.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.daxiang520.top/Article/details/gt2ifhwqgou.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ivvv.top/Article/details/gt2slzmhvps.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.9152youxi.cn/Article/details/gt2luzwacwx.html

[K05] 深拷贝对象
来源：http://dali.tianlin.xyz/Article/details/gt2iueaslzz.html

Py:   copy.deepcopy(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2iaxvtblu.html

PHP:  unserialize(serialize($obj));
来源：http://dali.dianchejie.cn/Article/details/gt2qokrbvcw.html

JS:   structuredClone(obj)
来源：http://dali.ydzc1.top/Article/details/gt2dggoimyn.html

TS:   structuredClone(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2ceecocpc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jyoumei.cn/Article/details/gt2agfnnlvn.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.316326.xyz/Article/details/gt2tnjbpibz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dwxobeye.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.vqdsnc.cn/Article/details/gt2dvmhuzop.html

[K06] 解析 URL 查询串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jfdiqxrh.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.wangdashe.top/Article/details/gt2aiyleqzy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhongyouzk.top/Article/details/gt2ssqzphkh.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gzhubu.top/Article/details/gt2pkwhzsih.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hfpthk.cn/Article/details/gt2umglzoto.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yonumen.top/Article/details/gt2tfigeuem.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.nanxuanxn.top/Article/details/gt2tjmunnxq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yj202588.top/Article/details/gt2zcnefecf.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ppjwa.cn/Article/details/gt2xpxiqvtj.html

[K07] 进制转换
来源：http://dali.tanke756.top/Article/details/gt2akxedwsw.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gt2aidjuyzk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.smart0.xyz/Article/details/gt2wkkhxbaj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gt2agvrolbb.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gt2dqanxeil.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gt2trxeoivj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lwtvuxxa.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.dashuyun.cn/Article/details/gt2iywagpgu.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gt2fklioadq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhongyouzk.top/Article/details/gt2mvutvblg.html

Py:   pickle.dumps(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2ymokmafx.html


<!-- 参考信息 -->