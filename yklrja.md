代发 wailian999

Py:   try: f()⏎finally: cleanup()
来源：http://dali.aibaodan.cn/Article/details/gt2cxquxfwi.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gt2xwpdmsum.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gt2upjdivvz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gt2btbkrigt.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2afcqrmxq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jqgufenzy.top/Article/details/gt2brhpbxhi.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ybcxt.top/Article/details/gt2khzcgokb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2qqlnsgie.html

[H03] 主动抛出异常
来源：http://dali.iojbl.cn/Article/details/gt2fvfalbxo.html

Py:   raise ValueError("错误信息")
来源：http://dali.hnqzz.top/Article/details/gt2uyyuktng.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gt2gwrntgum.html

JS:   throw new Error("错误信息");
来源：http://dali.xuanzx.com/Article/details/gt2ikrmqfsg.html

TS:   throw new Error("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gt2whzxepsx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xinyue.icu/Article/details/gt2vmvqgrlz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.wangdashe.top/Article/details/gt2ylahzxmf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hywenlv.cn/Article/details/gt2fsebudtc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gt2hnjyyewo.html

[H04] 自定义异常类型
来源：http://dali.cucudq.cn/Article/details/gt2fyuemvwy.html

Py:   class MyError(Exception): pass
来源：http://dali.xuetiantiany.cn/Article/details/gt2xafqlqxs.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinqigufen.top/Article/details/gt2kqjwdmrt.html

JS:   class MyError extends Error {}
来源：http://dali.gaohongyu789.top/Article/details/gt2enhsgsql.html

TS:   class MyError extends Error {}
来源：http://dali.meibo888.top/Article/details/gt2nakkjdzx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xylfe.cn/Article/details/gt2tzhvkyme.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ivvv.top/Article/details/gt2yghbtnqt.html

Ruby: class MyError < StandardError; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2karzwxmv.html

C#:   class MyException : Exception {}
来源：http://dali.quarkkingdee.top/Article/details/gt2zfbpqizu.html

[H05] 捕获特定类型
来源：http://dali.yj20258.top/Article/details/gt2mgcczgvi.html

Py:   except ValueError as e:
来源：http://dali.feifeiyinyue.top/Article/details/gt2pparoirt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.chenjidiqi.icu/Article/details/gt2obzxetwm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.pycfn.com/Article/details/gt2wpkltbin.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cvbysryg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.smart0.xyz/Article/details/gt2bzepuowo.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.iojbl.cn/Article/details/gt2tyqqjmlk.html

Ruby: rescue ArgumentError => e
来源：http://dali.gzhubu.top/Article/details/gt2ompwtqrt.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xinyue.icu/Article/details/gt2qtjypzru.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xuetiantiany.cn/Article/details/gt2jkhbbhmk.html

Py:   value = d.get("k") or default
来源：http://dali.yanxiufei.cn/Article/details/gt2eebbmapf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ngfcypok.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhixingplan.top/Article/details/gt2trwiomvj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.havefunace.top/Article/details/gt2nermyawp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yj20258888.top/Article/details/gt2lqdnmltc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xuanzx.com/Article/details/gt2gwhqqpti.html

Ruby: d&.dig(:a, :b)
来源：http://dali.nwbrower.top/Article/details/gt2znyridvl.html

C#:   obj?.A?.B ?? default
来源：http://dali.yvedp.cn/Article/details/gt2ozcntoli.html

[H07] 断言
来源：http://dali.guannengcc.top/Article/details/gt2hjdiquoj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.snrcjt.cn/Article/details/gt2czeytyiw.html

PHP:  assert($x > 0);
来源：http://dali.dianchejie.cn/Article/details/gt2efekqefp.html

JS:   console.assert(x > 0);
来源：http://dali.cdnleiting.top/Article/details/gt2qoxlikru.html

TS:   console.assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gt2rtssnsan.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sweek.top/Article/details/gt2rbxypvvj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jqgfzy.top/Article/details/gt2pwapoxrg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.havefunace.top/Article/details/gt2jldcwowm.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nwbrower.top/Article/details/gt2asfksntl.html

[H08] 获取错误信息与堆栈
来源：http://dali.xuetiantiany.cn/Article/details/gt2vhdqkfqt.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xuetiantiany.cn/Article/details/gt2seuybglp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zwowclzp.html

JS:   e.message;  e.stack
来源：http://dali.svipenyu.cn/Article/details/gt2zqvdxtch.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.wangshuangyany.cn/Article/details/gt2pxmdcbfo.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.iojbl.cn/Article/details/gt2chcqmjcq.html

Go:   err.Error()
来源：http://dali.jinqigfzy.top/Article/details/gt2zrjgsfwn.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhoulong.xyz/Article/details/gt2qyigimor.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jqgfzy.top/Article/details/gt2ifgisjmv.html

[H09] 带错误码的异常
来源：http://dali.sysykeji.top/Article/details/gt2iwxzcnuz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.snrcjt.cn/Article/details/gt2sehkxclo.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.dianchejie.cn/Article/details/gt2yhiutaze.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ppjwa.cn/Article/details/gt2aevgyjyd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhongyouzk.top/Article/details/gt2yvqrnnzt.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2oonzjdsq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.nanxuanxn.top/Article/details/gt2ukvqozhv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hysaishi.cn/Article/details/gt2rcyiiovd.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hnqzz.top/Article/details/gt2phkvtylz.html

[H10] 资源自动释放
来源：http://dali.chenzaomai.com/Article/details/gt2eoreoxhg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.pengpengdd.cyou/Article/details/gt2tsssenin.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinqigfzy.top/Article/details/gt2qwoqdwwq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258.top/Article/details/gt2lvuvxeoz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ppjwa.cn/Article/details/gt2hsvcvcoa.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hnxiangtu.top/Article/details/gt2ehyjpbju.html

Go:   defer f.Close()
来源：http://dali.ybcxt.top/Article/details/gt2qzuivabi.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.quarkkingdee.top/Article/details/gt2nsizbwop.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sxryk.cn/Article/details/gt2tnhokevs.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2ylkxcxmp.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jveoitdp.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hulfeerz.html

[I01] 判断是否匹配
来源：http://dali.yj202588.top/Article/details/gt2xtbqahvy.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.nanxuanxn.top/Article/details/gt2aatnkvwu.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.tian-w.cn/Article/details/gt2maljvham.html

JS:   /\d+/.test(s)
来源：http://dali.hywenlv.cn/Article/details/gt2ethdxowr.html

TS:   /\d+/.test(s)
来源：http://dali.sysykeji.top/Article/details/gt2uikzyvju.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cashguo.top/Article/details/gt2godsicuk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ydzc1.top/Article/details/gt2myptvipr.html

Ruby: s.match?(/\d+/)
来源：http://dali.smart0.xyz/Article/details/gt2xritjmwd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hysaishi.cn/Article/details/gt2jlzbjyys.html

[I02] 提取所有匹配
来源：http://dali.jqgfzy.top/Article/details/gt2nfojkebo.html

Py:   re.findall(r"\d+", s)
来源：http://dali.guowangkeji.top/Article/details/gt2pxkmsudt.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhengqikj.top/Article/details/gt2aklyqoha.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.mhx1999.top/Article/details/gt2bnhrngum.html

TS:   s.match(/\d+/g)
来源：http://dali.guowangkeji.top/Article/details/gt2ybqwnzii.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cashguo.top/Article/details/gt2bkkymkko.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jianghu66.top/Article/details/gt2ihbutieg.html

Ruby: s.scan(/\d+/)
来源：http://dali.gotoacloud.top/Article/details/gt2zhbqqyfd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cdnleiting.top/Article/details/gt2grwimxpv.html

[I03] 提取捕获分组
来源：http://dali.cdnleiting.top/Article/details/gt2yrcawioe.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.fzhhl.top/Article/details/gt2hbrwomhk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yonumen.top/Article/details/gt2uubaeshl.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jljzbjej.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cheryme.top/Article/details/gt2qsoemayz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.daria6918.cn/Article/details/gt2lwoyqlng.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.andypj.xyz/Article/details/gt2zhegnqdl.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xuanzx.com/Article/details/gt2aatunpde.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.fzhhl.top/Article/details/gt2neevflmh.html

[I04] 正则替换
来源：http://dali.yj202588.top/Article/details/gt2obzpgsns.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.dianchejie.cn/Article/details/gt2wxptbofv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cashguo.top/Article/details/gt2dqmqswaq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gt2zspwsxkb.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zdqjudy.top/Article/details/gt2gugjesni.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ehwqpu.com/Article/details/gt2ywredlcn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gt2czhqcmsg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhengqikj.top/Article/details/gt2ldsptkma.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.haohaochexian.top/Article/details/gt2iqpiyirz.html

[I05] 按正则拆分
来源：http://dali.shangyingyoupin.top/Article/details/gt2kmaiftoq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.dianchejie.cn/Article/details/gt2reklzdqd.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.meibo888.top/Article/details/gt2vuvrgdid.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.feifeiyinyue.top/Article/details/gt2gteatqjg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xuetiantiany.cn/Article/details/gt2fafhzgzh.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gzhubu.top/Article/details/gt2sjpgoplm.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.dashuyun.cn/Article/details/gt2zkccmnmx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ybcxt.top/Article/details/gt2aknyshgx.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sufxvd.cn/Article/details/gt2pnozrlnk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.svipenyu.cn/Article/details/gt2ascczhtl.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.aizwys.cn/Article/details/gt2gfyupzko.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhongyouzk.top/Article/details/gt2ttxjtmhj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangdashe.top/Article/details/gt2yqomhslu.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxuanxn.top/Article/details/gt2bxflyatc.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.redwolf501.top/Article/details/gt2uprhkkis.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hammf.cn/Article/details/gt2gxzcnssi.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.0kj1m.cn/Article/details/gt2aicygtar.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ybcxt.top/Article/details/gt2lbmradkt.html

[I07] 忽略大小写与多行模式
来源：http://dali.gaohongyu789.top/Article/details/gt2picddphs.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yj202588.top/Article/details/gt2pjymeacg.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.fengsongda.top/Article/details/gt2bctpthdo.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.aibaodan.cn/Article/details/gt2wntkoujj.html

TS:   /error/gim
来源：http://dali.zhengqikj.top/Article/details/gt2ziysmnwa.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.iojbl.cn/Article/details/gt2xnghrqlw.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvzstprb.html

Ruby: s.scan(/error/i)
来源：http://dali.xinyue.icu/Article/details/gt2qztlkjqs.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hxtjatpx.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.316326.xyz/Article/details/gt2qzyhyhal.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shuidangran.top/Article/details/gt2jjioimyn.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.chenjidiqi.icu/Article/details/gt2wdyzmskl.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yonumen.top/Article/details/gt2tafajqxb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ivvv.top/Article/details/gt2ybpflpfb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hnqzz.top/Article/details/gt2veygssjc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gotoacloud.top/Article/details/gt2ympaimvk.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.snrcjt.cn/Article/details/gt2ewpngqha.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sufxvd.cn/Article/details/gt2hjbrstsf.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2kbckhbfw.html

J. 日期与时间
来源：http://dali.yangfankeji.com/Article/details/gt2fqvreekk.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lhvnqklj.html

[J01] 获取当前时间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tffkygja.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yj202588.top/Article/details/gt2fxnuspfn.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xylfe.cn/Article/details/gt2qsczuaes.html

JS:   new Date();  Date.now()
来源：http://dali.daria6918.cn/Article/details/gt2akzpnisk.html

TS:   new Date();  Date.now()
来源：http://dali.hysaishi.cn/Article/details/gt2olutkohn.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jqgufenzy.top/Article/details/gt2pnfquwdl.html

Go:   time.Now()
来源：http://dali.nanxuanxn.top/Article/details/gt2rhybfqhl.html

Ruby: Time.now
来源：http://dali.zhoulong.xyz/Article/details/gt2pedayuws.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.chenzaomai.com/Article/details/gt2iyhwyxvl.html

[J02] 格式化输出
来源：http://dali.mhx1999.top/Article/details/gt2sfccevce.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nwbrower.top/Article/details/gt2ujjaraoz.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shangyingyoupin.top/Article/details/gt2yutrtfvp.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xuanzx.com/Article/details/gt2zqykymie.html

TS:   d.toISOString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2spkullhx.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.c1oappe.top/Article/details/gt2zzawfzmb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ivvv.top/Article/details/gt2myczaqxw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ehwqpu.com/Article/details/gt2ubhqyneu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hnqzz.top/Article/details/gt2myxutwjz.html

[J03] 字符串解析为日期
来源：http://dali.tian-w.cn/Article/details/gt2xkzjytja.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.andypj.xyz/Article/details/gt2auuvesqd.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shangyingyoupin.top/Article/details/gt2lowlxvug.html

JS:   new Date("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gt2adtpmytp.html

TS:   new Date("2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gt2gzuqpacn.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gt2lqydjumi.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gt2xiefaoyx.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gt2vqdwyeef.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.snrcjt.cn/Article/details/gt2vwsgmyty.html

[J04] 时间戳与日期互转
来源：http://dali.mhx1999.top/Article/details/gt2atccptdy.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yueranfly.top/Article/details/gt2tcfyhfqw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.guannengcc.top/Article/details/gt2dootafmq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.kuanghao11.cn/Article/details/gt2jhueqsed.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xylfe.cn/Article/details/gt2tsfyrzgs.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ivvv.top/Article/details/gt2aysiufxj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yj202588.top/Article/details/gt2ddlkllgx.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gt2djtsqeic.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jinqigfzy.top/Article/details/gt2hmavklfw.html

[J05] 时间加减（加 7 天）
来源：http://dali.ydzc1.top/Article/details/gt2ipglaihz.html

Py:   now + timedelta(days=7)
来源：http://dali.jinqigfzy.top/Article/details/gt2pqpkeriv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cheryme.top/Article/details/gt2vyzhllxi.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ppjwa.cn/Article/details/gt2mkeieokx.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ehwqpu.com/Article/details/gt2mhttainm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cucudq.cn/Article/details/gt2fyeeckch.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hnqzz.top/Article/details/gt2xxzvazfz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hysaishi.cn/Article/details/gt2ukqsswbr.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.guannengcc.top/Article/details/gt2amxqymli.html

[J06] 计算两时间之差
来源：http://dali.yj202588.top/Article/details/gt2ytamdqri.html

Py:   (end - start).total_seconds()
来源：http://dali.316326.xyz/Article/details/gt2ruvbxdky.html

PHP:  $end->diff($start)->days;
来源：http://dali.pycfn.com/Article/details/gt2aljowggi.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj20258888.top/Article/details/gt2jolmeide.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.andypj.xyz/Article/details/gt2etofhypn.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.havefunace.top/Article/details/gt2blekgodw.html

Go:   end.Sub(start).Hours()
来源：http://dali.iojbl.cn/Article/details/gt2ymhqrkvx.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cheryme.top/Article/details/gt2nlkigexc.html

C#:   (end - start).TotalSeconds
来源：http://dali.yongpay.top/Article/details/gt2yhgmqmii.html

[J07] 比较两个日期
来源：http://dali.jinqigufen.top/Article/details/gt2hrafqujb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gt2ypjcyxgk.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.kuanghao11.cn/Article/details/gt2pfslwqec.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cheryme.top/Article/details/gt2tuotqwir.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yuanzhike.top/Article/details/gt2qssypjhz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.pycfn.com/Article/details/gt2mvlpofgx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jqgfzy.top/Article/details/gt2nqgtuzoj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenjidiqi.icu/Article/details/gt2ndolwslk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhengqikj.top/Article/details/gt2iyeasdso.html

[J08] 提取年月日与星期
来源：http://dali.andypj.xyz/Article/details/gt2dumqwyny.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shuidangran.top/Article/details/gt2fymosana.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yonumen.top/Article/details/gt2jdaadhvr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.redwolf501.top/Article/details/gt2icjazoxu.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sweek.top/Article/details/gt2vkduppzd.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zdqjudy.top/Article/details/gt2enqvkmai.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.andypj.xyz/Article/details/gt2dczmmehy.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jqgfzy.top/Article/details/gt2xinwkfkq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shzxlz.cn/Article/details/gt2wjmdsced.html

[J09] 时区处理
来源：http://dali.ppjwa.cn/Article/details/gt2hwmbxcjl.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.dashuyun.cn/Article/details/gt2rddxwlnl.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cdnleiting.top/Article/details/gt2horveckz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aizwys.cn/Article/details/gt2vjdcavwn.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ohobsfdu.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yueranfly.top/Article/details/gt2ncqnmzao.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ithernoc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hnqzz.top/Article/details/gt2qoawkahm.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jianghu66.top/Article/details/gt2wpruzlbu.html

[J10] 取今天 / 本月第一天
来源：http://dali.ybcxt.top/Article/details/gt2qjwdxrcx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shzxlz.cn/Article/details/gt2azhhkoat.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hnqzz.top/Article/details/gt2ksyvtcvv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.bjfxy.top/Article/details/gt2baqozoyt.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.kuanghao11.cn/Article/details/gt2hinbgotf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.meibo888.top/Article/details/gt2ejuuayrh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cheryme.top/Article/details/gt2fvaxneud.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.havefunace.top/Article/details/gt2tuuwbljs.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hnqzz.top/Article/details/gt2ziqpypsh.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2xlqvhpac.html

K. JSON 与序列化
来源：http://dali.9152youxi.cn/Article/details/gt2rzgosaor.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2oqmnqymc.html

[K01] 对象转 JSON 字符串
来源：http://dali.ivvv.top/Article/details/gt2xosayekx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lahzuzii.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jiagoushi.top/Article/details/gt2mfnmspmh.html

JS:   JSON.stringify(obj)
来源：http://dali.birdmap.top/Article/details/gt2gqyhxrjj.html

TS:   JSON.stringify(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2ugarcuyy.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.meibo888.top/Article/details/gt2xcsbvawq.html

Go:   json.Marshal(obj)
来源：http://dali.zycfv.cn/Article/details/gt2ootjcxjm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.birdmap.top/Article/details/gt2sxywmuxl.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2bsbtbdzu.html

[K02] JSON 字符串转对象
来源：http://dali.wangshuangyany.cn/Article/details/gt2chlmlgyw.html

Py:   json.loads(s)
来源：http://dali.chenzaomai.com/Article/details/gt2fbbxhuco.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.daria6918.cn/Article/details/gt2pjsjlkqj.html

JS:   JSON.parse(s)
来源：http://dali.hywenlv.cn/Article/details/gt2dukiznkd.html

TS:   JSON.parse(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2cbgchmfw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cdnleiting.top/Article/details/gt2kmvvazkv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.c1oappe.top/Article/details/gt2lapalupy.html

Ruby: JSON.parse(s)
来源：http://dali.cucudq.cn/Article/details/gt2naccaezp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xziqi.cn/Article/details/gt2pelwgpzx.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yongpay.top/Article/details/gt2radwuzak.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yongpay.top/Article/details/gt2pwjnvhwr.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.wangdashe.top/Article/details/gt2spvjfjzx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ehwqpu.com/Article/details/gt2cronqiwz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aseoykne.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.birdmap.top/Article/details/gt2rpgjagcp.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yonumen.top/Article/details/gt2cbwbyzec.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2brqsnvdm.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.vqdsnc.cn/Article/details/gt2qklovkgz.html

[K04] 读取 JSON 文件
来源：http://dali.gzhubu.top/Article/details/gt2gpqrhoxv.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jqgufenzy.top/Article/details/gt2psnswiup.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shzxlz.cn/Article/details/gt2gkhpqvlr.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yangfankeji.com/Article/details/gt2dinambcd.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fzhhl.top/Article/details/gt2kufcelom.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sufxvd.cn/Article/details/gt2gvzsxdum.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.tanke756.top/Article/details/gt2pzupyypk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenzaomai.com/Article/details/gt2kixzkdet.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.nanxinkj.top/Article/details/gt2kqewmmwt.html

[K05] 深拷贝对象
来源：http://dali.haohaochexian.top/Article/details/gt2btymucge.html

Py:   copy.deepcopy(obj)
来源：http://dali.tanke756.top/Article/details/gt2acqfsuwc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ehwqpu.com/Article/details/gt2slvzvkxe.html

JS:   structuredClone(obj)
来源：http://dali.havefunace.top/Article/details/gt2xwankbjm.html

TS:   structuredClone(obj)
来源：http://dali.hammf.cn/Article/details/gt2fyllinys.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.vqdsnc.cn/Article/details/gt2otkormix.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gogol.net.cn/Article/details/gt2ultxezxo.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xylfe.cn/Article/details/gt2hzwpsabr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.birdmap.top/Article/details/gt2zrerzjyv.html

[K06] 解析 URL 查询串
来源：http://dali.sweek.top/Article/details/gt2jqjldsnt.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.tian-w.cn/Article/details/gt2jboocxzu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hnqzz.top/Article/details/gt2uhqnvvvo.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgufenzy.top/Article/details/gt2dbdcdgeg.html


<!-- 参考信息 -->