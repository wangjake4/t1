代发 wailian999

TS:   throw new Error("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gt2qglgojsv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.daria6918.cn/Article/details/gt2bsefsohf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.guowangkeji.top/Article/details/gt2yjadxrbj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.birdmap.top/Article/details/gt2mbtiulud.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gt2rrcclwom.html

[H04] 自定义异常类型
来源：http://dali.hammf.cn/Article/details/gt2oraeejrl.html

Py:   class MyError(Exception): pass
来源：http://dali.svipenyu.cn/Article/details/gt2bvyphrcu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.wangdashe.top/Article/details/gt2ouoemcnt.html

JS:   class MyError extends Error {}
来源：http://dali.ybcxt.top/Article/details/gt2upjcitxi.html

TS:   class MyError extends Error {}
来源：http://dali.nanxuanxn.top/Article/details/gt2azyddvto.html

Java: class MyException extends RuntimeException {}
来源：http://dali.bjfxy.top/Article/details/gt2bjkzykmu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhoulong.xyz/Article/details/gt2sptnvxtv.html

Ruby: class MyError < StandardError; end
来源：http://dali.havefunace.top/Article/details/gt2vcfczlpm.html

C#:   class MyException : Exception {}
来源：http://dali.sxryk.cn/Article/details/gt2adgliwyb.html

[H05] 捕获特定类型
来源：http://dali.hysaishi.cn/Article/details/gt2rtvfmlly.html

Py:   except ValueError as e:
来源：http://dali.svipenyu.cn/Article/details/gt2ebqkwthm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yueranfly.top/Article/details/gt2hjsvampf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.redwolf501.top/Article/details/gt2gwvantxc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.aizwys.cn/Article/details/gt2otuonyro.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jqgfzy.top/Article/details/gt2weuecuts.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sysykeji.top/Article/details/gt2bqeilytn.html

Ruby: rescue ArgumentError => e
来源：http://dali.ivvv.top/Article/details/gt2ezqqzvmg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ehwqpu.com/Article/details/gt2zocecwzy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yuanzhike.top/Article/details/gt2zmqihnzn.html

Py:   value = d.get("k") or default
来源：http://dali.zhixingplan.top/Article/details/gt2ibmqqieg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.fzhhl.top/Article/details/gt2tjudfjod.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hammf.cn/Article/details/gt2ungrlhky.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgufenzy.top/Article/details/gt2bznktalr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.pengpengdd.cyou/Article/details/gt2difhzlhv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yj202588.top/Article/details/gt2bdauqpwx.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhixingplan.top/Article/details/gt2iljjgyzz.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinqigufen.top/Article/details/gt2flqmneeo.html

[H07] 断言
来源：http://dali.hongshengwenyu.top/Article/details/gt2kskqkfcx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yueranfly.top/Article/details/gt2lgulgkrg.html

PHP:  assert($x > 0);
来源：http://dali.daxiang520.top/Article/details/gt2xwusclnm.html

JS:   console.assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gt2mhxlghuu.html

TS:   console.assert(x > 0);
来源：http://dali.sxryk.cn/Article/details/gt2brdhxajt.html

Java: assert x > 0 : "必须为正";
来源：http://dali.chenlongwang.top/Article/details/gt2puzufbax.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhiwuduotai.top/Article/details/gt2rtchclty.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.wangdashe.top/Article/details/gt2hlikubuo.html

C#:   Debug.Assert(x > 0);
来源：http://dali.guowangkeji.top/Article/details/gt2ksriuxjr.html

[H08] 获取错误信息与堆栈
来源：http://dali.hammf.cn/Article/details/gt2zlvspuxj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ivvv.top/Article/details/gt2elwzplco.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xuanzx.com/Article/details/gt2jnaqjbgs.html

JS:   e.message;  e.stack
来源：http://dali.jyoumei.cn/Article/details/gt2pywssxzr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.dashuyun.cn/Article/details/gt2cinutsvp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.meibo888.top/Article/details/gt2rwqaqnvt.html

Go:   err.Error()
来源：http://dali.gaohongyu789.top/Article/details/gt2llkzkwex.html

Ruby: e.message;  e.backtrace
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mjpwktdz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhengqikj.top/Article/details/gt2dmtvbvyq.html

[H09] 带错误码的异常
来源：http://dali.kuanghao11.cn/Article/details/gt2yvwltsae.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hywenlv.cn/Article/details/gt2paxoddsv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhengqikj.top/Article/details/gt2mjhuudnc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yuxming.cn/Article/details/gt2jswrdqgf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gzhubu.top/Article/details/gt2cdkobrya.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jqgufenzy.top/Article/details/gt2gvwwanui.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.guannengcc.top/Article/details/gt2ihswvkyu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhiwuduotai.top/Article/details/gt2cpwtljtj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenlongwang.top/Article/details/gt2xkbufkzh.html

[H10] 资源自动释放
来源：http://dali.ybcxt.top/Article/details/gt2jifnorza.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cqqwz.cn/Article/details/gt2dkdjveqa.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xziqi.cn/Article/details/gt2msdumaae.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.feifeiyinyue.top/Article/details/gt2riiajuoj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj202588.top/Article/details/gt2nyttvjcm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xuanzx.com/Article/details/gt2szmrnbsr.html

Go:   defer f.Close()
来源：http://dali.tanke756.top/Article/details/gt2jpezqkhu.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ybcxt.top/Article/details/gt2rmbowzfj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.c1oappe.top/Article/details/gt2hbopsxek.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xhrsqafx.html

I. 正则表达式
来源：http://dali.xinyue.icu/Article/details/gt2khemchgf.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2axoqbcgr.html

[I01] 判断是否匹配
来源：http://dali.aizwys.cn/Article/details/gt2moxxaymk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2alxastcq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.birdmap.top/Article/details/gt2aqqogtwb.html

JS:   /\d+/.test(s)
来源：http://dali.jqgfzy.top/Article/details/gt2omivbvjr.html

TS:   /\d+/.test(s)
来源：http://dali.gzhubu.top/Article/details/gt2yzugatit.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cdnleiting.top/Article/details/gt2omlvtvxo.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2yccxfawr.html

Ruby: s.match?(/\d+/)
来源：http://dali.mhx1999.top/Article/details/gt2nxvzdjjf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.gzhubu.top/Article/details/gt2qlhjduvr.html

[I02] 提取所有匹配
来源：http://dali.tianlin.xyz/Article/details/gt2kxbxxmqe.html

Py:   re.findall(r"\d+", s)
来源：http://dali.quarkkingdee.top/Article/details/gt2gwliokry.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinqigfzy.top/Article/details/gt2gojhxtgy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.daria6918.cn/Article/details/gt2sbdprqgc.html

TS:   s.match(/\d+/g)
来源：http://dali.ppjwa.cn/Article/details/gt2syqrabko.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.nanxinkj.top/Article/details/gt2wekvocgu.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hfpthk.cn/Article/details/gt2zeomwjvi.html

Ruby: s.scan(/\d+/)
来源：http://dali.vqdsnc.cn/Article/details/gt2injcydlz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gt2bynfwszx.html

[I03] 提取捕获分组
来源：http://dali.9152youxi.cn/Article/details/gt2dppeipro.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2dozwhhdd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.nanxuanxn.top/Article/details/gt2ectpsepj.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.316326.xyz/Article/details/gt2dfopvifn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.iojbl.cn/Article/details/gt2deqvjdjj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.9152youxi.cn/Article/details/gt2elneugjf.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.316326.xyz/Article/details/gt2rdautdyk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.mhx1999.top/Article/details/gt2duyiswlk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jqgfzy.top/Article/details/gt2ijjbxgns.html

[I04] 正则替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lyookvee.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yj20258888.top/Article/details/gt2cgwadzjp.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xziqi.cn/Article/details/gt2rycjzcnw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.havefunace.top/Article/details/gt2stklbabr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hongshengwenyu.top/Article/details/gt2pvwtqhzt.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.guowangkeji.top/Article/details/gt2cddhujdc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jiagoushi.top/Article/details/gt2qlbomohm.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yanxiufei.cn/Article/details/gt2apmkeuld.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yuxming.cn/Article/details/gt2puzseyis.html

[I05] 按正则拆分
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mmzzmpmc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.mhx1999.top/Article/details/gt2rtapksli.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sufxvd.cn/Article/details/gt2pwczhhxx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sufxvd.cn/Article/details/gt2toihqahh.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yangfankeji.com/Article/details/gt2wrabvoim.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xuetiantiany.cn/Article/details/gt2qofpbktp.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zdqjudy.top/Article/details/gt2ccmbpdrj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hnqzz.top/Article/details/gt2vwjnpgoy.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.svipenyu.cn/Article/details/gt2ubjotryz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ybcxt.top/Article/details/gt2nfeujmsy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.daria6918.cn/Article/details/gt2wfasqbpc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.tanke756.top/Article/details/gt2hmoorejn.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxuanxn.top/Article/details/gt2sdrkceij.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxuanxn.top/Article/details/gt2tuunfgcs.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xuanzx.com/Article/details/gt2uzecayzm.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.mhx1999.top/Article/details/gt2idpsdvsl.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.quarkkingdee.top/Article/details/gt2tzvmzkoq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.quarkkingdee.top/Article/details/gt2ohrnreia.html

[I07] 忽略大小写与多行模式
来源：http://dali.ybcxt.top/Article/details/gt2ezyeeuzb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cashguo.top/Article/details/gt2gwpdkasu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gaohongyu789.top/Article/details/gt2mqigfloc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zdqjudy.top/Article/details/gt2igtepurh.html

TS:   /error/gim
来源：http://dali.gaohongyu789.top/Article/details/gt2huochnyk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.nanxuanxn.top/Article/details/gt2kebdbyxo.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cucudq.cn/Article/details/gt2vhbvdbxj.html

Ruby: s.scan(/error/i)
来源：http://dali.xziqi.cn/Article/details/gt2cegvkwep.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yj20258.top/Article/details/gt2mtgrbsyn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.tanke756.top/Article/details/gt2tmlfbpqs.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yvedp.cn/Article/details/gt2ohiqgfhw.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gaohongyu789.top/Article/details/gt2xhdwzsah.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenlongwang.top/Article/details/gt2uuaezfly.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenjidiqi.icu/Article/details/gt2qlxjrzeh.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sysykeji.top/Article/details/gt2yduqijnk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.chenjidiqi.icu/Article/details/gt2qftpxlrr.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.tianlin.xyz/Article/details/gt2iblsbgkc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.birdmap.top/Article/details/gt2scsqefew.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fzsgtims.html

J. 日期与时间
来源：http://dali.sweek.top/Article/details/gt2znsxurus.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2sptxotqd.html

[J01] 获取当前时间
来源：http://dali.hfpthk.cn/Article/details/gt2yswaunnq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.fzhhl.top/Article/details/gt2nfzrcthk.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cucudq.cn/Article/details/gt2ibeobbkz.html

JS:   new Date();  Date.now()
来源：http://dali.gogol.net.cn/Article/details/gt2bfeljzmn.html

TS:   new Date();  Date.now()
来源：http://dali.iojbl.cn/Article/details/gt2lkrecpbw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.0kj1m.cn/Article/details/gt2udyalndw.html

Go:   time.Now()
来源：http://dali.yj202588.top/Article/details/gt2zvayyggr.html

Ruby: Time.now
来源：http://dali.aibaodan.cn/Article/details/gt2nqrvllge.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ybcxt.top/Article/details/gt2dkumnnox.html

[J02] 格式化输出
来源：http://dali.birdmap.top/Article/details/gt2zazjaddh.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aibaodan.cn/Article/details/gt2hpcyhopi.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uimgajyv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.wangshuangyany.cn/Article/details/gt2euzlsuhp.html

TS:   d.toISOString()
来源：http://dali.meibo888.top/Article/details/gt2fwkqpjhv.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yonumen.top/Article/details/gt2imubeevw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.wangshuangyany.cn/Article/details/gt2zbqgtoed.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuetiantiany.cn/Article/details/gt2kaxkhaow.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.daria6918.cn/Article/details/gt2ocegfyhl.html

[J03] 字符串解析为日期
来源：http://dali.yangfankeji.com/Article/details/gt2tzfxqokk.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sufxvd.cn/Article/details/gt2bxsyjbry.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shuidangran.top/Article/details/gt2aklschxt.html

JS:   new Date("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gt2pozybdck.html

TS:   new Date("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gt2nmwrfmrb.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gt2puxyedrv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gt2pgazzmym.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gt2fpdgkbya.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cheryme.top/Article/details/gt2zuzgieek.html

[J04] 时间戳与日期互转
来源：http://dali.meibo888.top/Article/details/gt2qjbxqaqq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.0kj1m.cn/Article/details/gt2hjyoqfjq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zycfv.cn/Article/details/gt2nxbrbbuq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2odepqvdh.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shzxlz.cn/Article/details/gt2qokwplkh.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ydzc1.top/Article/details/gt2cdutkdbi.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xffvtmmq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yanxiufei.cn/Article/details/gt2uqexqgod.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.wangdashe.top/Article/details/gt2lmsbgcfj.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xxannjpe.html

Py:   now + timedelta(days=7)
来源：http://dali.yueranfly.top/Article/details/gt2vskaqpjc.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sxryk.cn/Article/details/gt2gnycvuzi.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sysykeji.top/Article/details/gt2upvgkbsz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nwbrower.top/Article/details/gt2ziztmgbq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ldaermmj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sufxvd.cn/Article/details/gt2svnkptsz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yj20258.top/Article/details/gt2ynkxbigc.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shuidangran.top/Article/details/gt2bxwapvnd.html

[J06] 计算两时间之差
来源：http://dali.jlsjyb.cn/Article/details/gt2wjlruing.html

Py:   (end - start).total_seconds()
来源：http://dali.cashguo.top/Article/details/gt2xscovcnc.html

PHP:  $end->diff($start)->days;
来源：http://dali.cdnleiting.top/Article/details/gt2okfijsoz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jyoumei.cn/Article/details/gt2irbzqlup.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yonumen.top/Article/details/gt2bstfesfk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.vqdsnc.cn/Article/details/gt2jhhwmvmy.html

Go:   end.Sub(start).Hours()
来源：http://dali.ivvv.top/Article/details/gt2tckgzlvf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hnxiangtu.top/Article/details/gt2nueiiynf.html

C#:   (end - start).TotalSeconds
来源：http://dali.guannengcc.top/Article/details/gt2uduxcpsi.html

[J07] 比较两个日期
来源：http://dali.xinyue.icu/Article/details/gt2uiwtcacy.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hysaishi.cn/Article/details/gt2pabruiac.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ozpdhwbo.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shzxlz.cn/Article/details/gt2jwuygzbc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.sysykeji.top/Article/details/gt2dwtrvlsl.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zdqjudy.top/Article/details/gt2spodzwld.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.c1oappe.top/Article/details/gt2njxgfxcw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.nwbrower.top/Article/details/gt2bfwbkofi.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jqgfzy.top/Article/details/gt2cwsdyede.html

[J08] 提取年月日与星期
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mwcvhonc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhijiandao.cn/Article/details/gt2zajdxmmp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.meibo888.top/Article/details/gt2pmdoumgf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hqerdkxa.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ydzc1.top/Article/details/gt2dubymhay.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.chenzaomai.com/Article/details/gt2lupzwxbn.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shuidangran.top/Article/details/gt2xwjgqxnh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.nanxinkj.top/Article/details/gt2zhcexieb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jccgxrgr.html

[J09] 时区处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vyiloibi.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.sweek.top/Article/details/gt2ihbkpnsv.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.andypj.xyz/Article/details/gt2fjmchwvj.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shzxlz.cn/Article/details/gt2yhxsrthz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhiwuduotai.top/Article/details/gt2fdntcwvu.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gzhubu.top/Article/details/gt2cfelnoee.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ehwqpu.com/Article/details/gt2thoyjhst.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.wangdashe.top/Article/details/gt2ifbgzacc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ydzc1.top/Article/details/gt2jotmulcb.html

[J10] 取今天 / 本月第一天
来源：http://dali.9152youxi.cn/Article/details/gt2bnkndgdw.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cdnleiting.top/Article/details/gt2iyazwmso.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cashguo.top/Article/details/gt2uuccoikj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.smart0.xyz/Article/details/gt2lbqmqhid.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinqigfzy.top/Article/details/gt2uypgurzq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2wdcxtszr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.andypj.xyz/Article/details/gt2jgonmibg.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.nwbrower.top/Article/details/gt2xzosczcd.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cdnleiting.top/Article/details/gt2librbtbu.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2vjfqhmwx.html

K. JSON 与序列化
来源：http://dali.jinqigfzy.top/Article/details/gt2teezaqhc.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2mwcagirw.html

[K01] 对象转 JSON 字符串
来源：http://dali.jiagoushi.top/Article/details/gt2itywmlzk.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.dashuyun.cn/Article/details/gt2mnukexun.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hammf.cn/Article/details/gt2dqlyvnjw.html

JS:   JSON.stringify(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2xgdvamde.html

TS:   JSON.stringify(obj)
来源：http://dali.redwolf501.top/Article/details/gt2mrrjmmzz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shzxlz.cn/Article/details/gt2vtfahqfd.html

Go:   json.Marshal(obj)
来源：http://dali.nwbrower.top/Article/details/gt2vnxplreh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.iojbl.cn/Article/details/gt2yhcfvgcg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2lhfaqpdv.html

[K02] JSON 字符串转对象
来源：http://dali.ybcxt.top/Article/details/gt2jkavrahv.html

Py:   json.loads(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2irdyxbsy.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.nanxinkj.top/Article/details/gt2zwmpjbhd.html

JS:   JSON.parse(s)
来源：http://dali.sufxvd.cn/Article/details/gt2nlhgbimr.html

TS:   JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2qkdrnbvn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.tianlin.xyz/Article/details/gt2ykvzgjnz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sufxvd.cn/Article/details/gt2jrhinwta.html

Ruby: JSON.parse(s)
来源：http://dali.xziqi.cn/Article/details/gt2xbpjrzuu.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2nvykqole.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sysykeji.top/Article/details/gt2cmmxqtft.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.fzhhl.top/Article/details/gt2vedbvcfo.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.tanke756.top/Article/details/gt2yqyjozdv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xlaplukp.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.redwolf501.top/Article/details/gt2zvbmwzxn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2pavrbpce.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.nanxinkj.top/Article/details/gt2uknpbyju.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2edxysizy.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hammf.cn/Article/details/gt2aiyqpjws.html

[K04] 读取 JSON 文件
来源：http://dali.c1oappe.top/Article/details/gt2eqayrmjh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.0kj1m.cn/Article/details/gt2xjgpjonw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hnxiangtu.top/Article/details/gt2erdimytu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xylfe.cn/Article/details/gt2kleeieyh.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aibaodan.cn/Article/details/gt2vphymudq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.mhx1999.top/Article/details/gt2esrllgae.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.0kj1m.cn/Article/details/gt2ktrvbzuk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yj20258888.top/Article/details/gt2mjvqrvgn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.smart0.xyz/Article/details/gt2dsoiirny.html

[K05] 深拷贝对象
来源：http://dali.shangyingyoupin.top/Article/details/gt2motikdwh.html

Py:   copy.deepcopy(obj)
来源：http://dali.tian-w.cn/Article/details/gt2hinfffks.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yuxming.cn/Article/details/gt2dkmvxomx.html

JS:   structuredClone(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2wjugwxun.html

TS:   structuredClone(obj)
来源：http://dali.fzhhl.top/Article/details/gt2dfhklgwy.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hnqzz.top/Article/details/gt2ubtunhmp.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhixingplan.top/Article/details/gt2fvzbsgcy.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gotoacloud.top/Article/details/gt2jslnsdbl.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gotoacloud.top/Article/details/gt2rkuyjsvp.html

[K06] 解析 URL 查询串
来源：http://dali.bjfxy.top/Article/details/gt2phuoveqw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.nanxuanxn.top/Article/details/gt2btbjfaqq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhiwuduotai.top/Article/details/gt2oeieqykc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhengqikj.top/Article/details/gt2yqmnfobm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ppjwa.cn/Article/details/gt2qhcgpmia.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.aibaodan.cn/Article/details/gt2apbbvaae.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yj20258.top/Article/details/gt2djqcsndr.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.bjfxy.top/Article/details/gt2onocmmxv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.nwbrower.top/Article/details/gt2gdlriupz.html

[K07] 进制转换
来源：http://dali.yuanzhike.top/Article/details/gt2lcwuehym.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gt2abimkdpr.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hnxiangtu.top/Article/details/gt2zxirejjy.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gt2iwxqjfzc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gt2bjayezik.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gt2gygyjnuj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.vqdsnc.cn/Article/details/gt2dyqmfdww.html


<!-- 参考信息 -->