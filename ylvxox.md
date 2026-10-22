代发 wailian999

Ruby: class MyError < StandardError; end
来源：http://dali.yj202588.top/Article/details/gt2hqfuykky.html

C#:   class MyException : Exception {}
来源：http://dali.fzhhl.top/Article/details/gt2gddkfhkq.html

[H05] 捕获特定类型
来源：http://dali.shuidangran.top/Article/details/gt2vbknjskv.html

Py:   except ValueError as e:
来源：http://dali.xuetiantiany.cn/Article/details/gt2gledjkqn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.wangdashe.top/Article/details/gt2imlyufqq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sxryk.cn/Article/details/gt2clwvoyxm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2snknmavy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2atvgrkso.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.havefunace.top/Article/details/gt2orjmgzik.html

Ruby: rescue ArgumentError => e
来源：http://dali.ppjwa.cn/Article/details/gt2jkhdwmou.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cucudq.cn/Article/details/gt2qevdqwcv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cucudq.cn/Article/details/gt2opslcvfv.html

Py:   value = d.get("k") or default
来源：http://dali.quarkkingdee.top/Article/details/gt2cttitgeu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.aizwys.cn/Article/details/gt2duhmikok.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gaohongyu789.top/Article/details/gt2imluchwz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhixingplan.top/Article/details/gt2pvlkmlje.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yj20258888.top/Article/details/gt2bpfyznhu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xziqi.cn/Article/details/gt2lolsvunf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yuanzhike.top/Article/details/gt2jfxawzio.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhixingplan.top/Article/details/gt2ehszkket.html

[H07] 断言
来源：http://dali.yvedp.cn/Article/details/gt2joqdhlbq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.dianchejie.cn/Article/details/gt2jzfvmbmo.html

PHP:  assert($x > 0);
来源：http://dali.tanke756.top/Article/details/gt2gzlldzqu.html

JS:   console.assert(x > 0);
来源：http://dali.cheryme.top/Article/details/gt2uniazpwt.html

TS:   console.assert(x > 0);
来源：http://dali.sysykeji.top/Article/details/gt2pdasjgnz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sweek.top/Article/details/gt2nhivtglb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yj202588.top/Article/details/gt2zitgviis.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yuanzhike.top/Article/details/gt2rshxsumc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.smart0.xyz/Article/details/gt2obmmgzqw.html

[H08] 获取错误信息与堆栈
来源：http://dali.jqgufenzy.top/Article/details/gt2mgjxgeri.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.iojbl.cn/Article/details/gt2ymynnnco.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jalompex.html

JS:   e.message;  e.stack
来源：http://dali.zhengqikj.top/Article/details/gt2jcqricvi.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2otyzbpwk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhiwuduotai.top/Article/details/gt2enuyubfh.html

Go:   err.Error()
来源：http://dali.zycfv.cn/Article/details/gt2yncnqtua.html

Ruby: e.message;  e.backtrace
来源：http://dali.nanxuanxn.top/Article/details/gt2wbmpurhf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gotoacloud.top/Article/details/gt2lhtjztsq.html

[H09] 带错误码的异常
来源：http://dali.yangfankeji.com/Article/details/gt2fplcojpm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.wangshuangyany.cn/Article/details/gt2sabvnwrm.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.fzhhl.top/Article/details/gt2qlwijzuv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cqqwz.cn/Article/details/gt2rkkwsrkq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.wangdashe.top/Article/details/gt2orvhmvkg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xylfe.cn/Article/details/gt2kfgcnptn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yj20258888.top/Article/details/gt2vyezmpsk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.tanke756.top/Article/details/gt2hzvqtyhz.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hywenlv.cn/Article/details/gt2ujgzettp.html

[H10] 资源自动释放
来源：http://dali.snrcjt.cn/Article/details/gt2tcxbnnel.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ydzc1.top/Article/details/gt2wzpsetda.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.andypj.xyz/Article/details/gt2wmlgjbpq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxuanxn.top/Article/details/gt2vehqmbjr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.birdmap.top/Article/details/gt2nedeaggt.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhixingplan.top/Article/details/gt2egusugjf.html

Go:   defer f.Close()
来源：http://dali.pengpengdd.cyou/Article/details/gt2knpmbpdm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.fengsongda.top/Article/details/gt2zovcekhb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xziqi.cn/Article/details/gt2umlnxhet.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2lcrspvaf.html

I. 正则表达式
来源：http://dali.gotoacloud.top/Article/details/gt2kyvhcsxi.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2bymnacjx.html

[I01] 判断是否匹配
来源：http://dali.9152youxi.cn/Article/details/gt2mqcdplrh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.0kj1m.cn/Article/details/gt2meygiaea.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.pycfn.com/Article/details/gt2spdfkmxu.html

JS:   /\d+/.test(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eddzpavu.html

TS:   /\d+/.test(s)
来源：http://dali.cucudq.cn/Article/details/gt2vbnrfgot.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2scjdjshd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.bjfxy.top/Article/details/gt2tloksnvp.html

Ruby: s.match?(/\d+/)
来源：http://dali.316326.xyz/Article/details/gt2hrtcrpjj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.havefunace.top/Article/details/gt2frqsydme.html

[I02] 提取所有匹配
来源：http://dali.jqgufenzy.top/Article/details/gt2qdmskzws.html

Py:   re.findall(r"\d+", s)
来源：http://dali.andypj.xyz/Article/details/gt2awzrgktt.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hnxiangtu.top/Article/details/gt2mhxpsufh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xziqi.cn/Article/details/gt2zwefqzuy.html

TS:   s.match(/\d+/g)
来源：http://dali.wangshuangyany.cn/Article/details/gt2hhwjorxy.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ppjwa.cn/Article/details/gt2jmomwbcc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yj202588.top/Article/details/gt2eagblyou.html

Ruby: s.scan(/\d+/)
来源：http://dali.hfpthk.cn/Article/details/gt2pikgafqg.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cdnleiting.top/Article/details/gt2qseqfbkl.html

[I03] 提取捕获分组
来源：http://dali.sysykeji.top/Article/details/gt2ahhmnldx.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jianghu66.top/Article/details/gt2tnkedlcx.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.aibaodan.cn/Article/details/gt2horqgwft.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ydzc1.top/Article/details/gt2oaqkvuul.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jiagoushi.top/Article/details/gt2gjzdbmac.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yj20258888.top/Article/details/gt2ptblahmg.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jyoumei.cn/Article/details/gt2sbgfwliu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.tanke756.top/Article/details/gt2taijuumm.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yanxiufei.cn/Article/details/gt2unsbtzqq.html

[I04] 正则替换
来源：http://dali.yj20258.top/Article/details/gt2mkfviiqt.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yangfankeji.com/Article/details/gt2zwkrwyxz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zycfv.cn/Article/details/gt2vwauzzql.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hywenlv.cn/Article/details/gt2cdegrcxg.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgfzy.top/Article/details/gt2oowavlbc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.chenjidiqi.icu/Article/details/gt2djmkafoh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gt2wybmpxgz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gzhubu.top/Article/details/gt2yveqcunw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.aibaodan.cn/Article/details/gt2jvycskjl.html

[I05] 按正则拆分
来源：http://dali.yueranfly.top/Article/details/gt2lceomtyt.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2fyncvsxz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.iojbl.cn/Article/details/gt2duawyefs.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.fzhhl.top/Article/details/gt2nmznsvvl.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shangyingyoupin.top/Article/details/gt2abxrxymb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinqigufen.top/Article/details/gt2qgjcnuze.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cashguo.top/Article/details/gt2ingmwuyy.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2juzbawkn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cqqwz.cn/Article/details/gt2rophurxl.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.sxryk.cn/Article/details/gt2yequnaca.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.redwolf501.top/Article/details/gt2fojslbav.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cucudq.cn/Article/details/gt2rmijdcaj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.aizwys.cn/Article/details/gt2niizmgwf.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnqzz.top/Article/details/gt2evvgstfy.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.nanxinkj.top/Article/details/gt2iguywegj.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hammf.cn/Article/details/gt2twzylmhd.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xaxzftyt.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sysykeji.top/Article/details/gt2eqzyvgqn.html

[I07] 忽略大小写与多行模式
来源：http://dali.xylfe.cn/Article/details/gt2hxhovqcm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.cqqwz.cn/Article/details/gt2iallqxfr.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.kuanghao11.cn/Article/details/gt2lwfkpocj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.fzhhl.top/Article/details/gt2jaimgmkg.html

TS:   /error/gim
来源：http://dali.hfpthk.cn/Article/details/gt2vexcthmx.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.birdmap.top/Article/details/gt2kxllbjoz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hammf.cn/Article/details/gt2stcjjjng.html

Ruby: s.scan(/error/i)
来源：http://dali.xinyue.icu/Article/details/gt2kncpsnjd.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yvedp.cn/Article/details/gt2dldblfsl.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cheryme.top/Article/details/gt2ijobxqrg.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gxrlathj.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ijnuafoc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sxryk.cn/Article/details/gt2mwycyonq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cashguo.top/Article/details/gt2sfukyyzy.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yuxming.cn/Article/details/gt2sdipmqqr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.9152youxi.cn/Article/details/gt2bdawccdi.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hzwuhaoc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.svipenyu.cn/Article/details/gt2ghjntvql.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2beokzlds.html

J. 日期与时间
来源：http://dali.dianchejie.cn/Article/details/gt2xexphsdh.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2bgqquvwt.html

[J01] 获取当前时间
来源：http://dali.jyoumei.cn/Article/details/gt2noaacstk.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.wangdashe.top/Article/details/gt2rtnsjeqc.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.fzhhl.top/Article/details/gt2nrcvecon.html

JS:   new Date();  Date.now()
来源：http://dali.gogol.net.cn/Article/details/gt2douajioh.html

TS:   new Date();  Date.now()
来源：http://dali.shangyingyoupin.top/Article/details/gt2qjxwsirh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.dianchejie.cn/Article/details/gt2kywpjuqf.html

Go:   time.Now()
来源：http://dali.chenlongwang.top/Article/details/gt2rieqctxf.html

Ruby: Time.now
来源：http://dali.jqgufenzy.top/Article/details/gt2wfmsislr.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cheryme.top/Article/details/gt2eqausgro.html

[J02] 格式化输出
来源：http://dali.xziqi.cn/Article/details/gt2xtficgaj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dianchejie.cn/Article/details/gt2cyrzjfcm.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xinyue.icu/Article/details/gt2gknibdoz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yvedp.cn/Article/details/gt2ncvzumue.html

TS:   d.toISOString()
来源：http://dali.zdqjudy.top/Article/details/gt2nlqjgdvl.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.pycfn.com/Article/details/gt2prujazjc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yangfankeji.com/Article/details/gt2wlnhblys.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuetiantiany.cn/Article/details/gt2embezetu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cucudq.cn/Article/details/gt2xettyxbf.html

[J03] 字符串解析为日期
来源：http://dali.fzhhl.top/Article/details/gt2vjdnvlwq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.tian-w.cn/Article/details/gt2hfiadcbu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ieroricm.html

JS:   new Date("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gt2ghlsrjfw.html

TS:   new Date("2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gt2rzdkflas.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fxhkvdcm.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gt2mdjskgtf.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gt2dconmena.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhiwuduotai.top/Article/details/gt2dzylbuej.html

[J04] 时间戳与日期互转
来源：http://dali.dianchejie.cn/Article/details/gt2mdwaisbx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.nanxinkj.top/Article/details/gt2ityivpnn.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wzzmsjqe.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.haohaochexian.top/Article/details/gt2xkactdqm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.fzhhl.top/Article/details/gt2cjyrnydi.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kjulqlpg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gt2dndellcu.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.redwolf501.top/Article/details/gt2bxmwadwm.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.0kj1m.cn/Article/details/gt2vzaqvchr.html

[J05] 时间加减（加 7 天）
来源：http://dali.andypj.xyz/Article/details/gt2wxeqsyga.html

Py:   now + timedelta(days=7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zljejymz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yanxiufei.cn/Article/details/gt2gsdcurbr.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nwbrower.top/Article/details/gt2vbtrwkte.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sweek.top/Article/details/gt2asjswbkm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yj20258.top/Article/details/gt2sabafpoq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.guowangkeji.top/Article/details/gt2ybkmauxx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shzxlz.cn/Article/details/gt2btslrxys.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.feifeiyinyue.top/Article/details/gt2pnwsgius.html

[J06] 计算两时间之差
来源：http://dali.guowangkeji.top/Article/details/gt2elvjrrlz.html

Py:   (end - start).total_seconds()
来源：http://dali.gogol.net.cn/Article/details/gt2kwhaxsdl.html

PHP:  $end->diff($start)->days;
来源：http://dali.9152youxi.cn/Article/details/gt2ssfqnghk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gaohongyu789.top/Article/details/gt2hxmlyhkm.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zycfv.cn/Article/details/gt2runzbzzq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hongshengwenyu.top/Article/details/gt2zktfruja.html

Go:   end.Sub(start).Hours()
来源：http://dali.shzxlz.cn/Article/details/gt2aeewjjiw.html

Ruby: end - start                 # 返回秒数
来源：http://dali.andypj.xyz/Article/details/gt2ftioomrg.html

C#:   (end - start).TotalSeconds
来源：http://dali.yj20258888.top/Article/details/gt2dhgeegbi.html

[J07] 比较两个日期
来源：http://dali.jinqigufen.top/Article/details/gt2itmcuvsh.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yueranfly.top/Article/details/gt2lijfqybq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sysykeji.top/Article/details/gt2tuzkksqc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ivvv.top/Article/details/gt2dkvpjzbw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cvcsrmnf.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.fzhhl.top/Article/details/gt2etejtyxd.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ydzc1.top/Article/details/gt2sazshodn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yueranfly.top/Article/details/gt2afjhrvdv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhengqikj.top/Article/details/gt2hecnfxoe.html

[J08] 提取年月日与星期
来源：http://dali.yj20258888.top/Article/details/gt2sseeirbt.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.gotoacloud.top/Article/details/gt2rfeppgaz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jianghu66.top/Article/details/gt2xqlieyul.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.nanxinkj.top/Article/details/gt2weowjqvc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cheryme.top/Article/details/gt2jkoreqgj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.fengsongda.top/Article/details/gt2gsjhylpa.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.birdmap.top/Article/details/gt2fqlltedt.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hfpthk.cn/Article/details/gt2pruobkxi.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xuetiantiany.cn/Article/details/gt2wjvwccbj.html

[J09] 时区处理
来源：http://dali.0kj1m.cn/Article/details/gt2joiczktu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.svipenyu.cn/Article/details/gt2zebnsbrd.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yongpay.top/Article/details/gt2ojbirclj.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.redwolf501.top/Article/details/gt2xcvjhown.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aibaodan.cn/Article/details/gt2rkpmerqz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.guannengcc.top/Article/details/gt2yqgtozcx.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.iojbl.cn/Article/details/gt2vjwftxbj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.vqdsnc.cn/Article/details/gt2pgdfuvlw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.nanxinkj.top/Article/details/gt2lhbnrptz.html

[J10] 取今天 / 本月第一天
来源：http://dali.xylfe.cn/Article/details/gt2ywlahyqy.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nasgpmbs.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jiagoushi.top/Article/details/gt2nmjmfuob.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kdbunqka.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yanxiufei.cn/Article/details/gt2hxdjtflm.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.daxiang520.top/Article/details/gt2dgswjfkv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.aizwys.cn/Article/details/gt2msgbkcgh.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hammf.cn/Article/details/gt2cwwdbefd.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.snrcjt.cn/Article/details/gt2magdrbbp.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2awgwblui.html

K. JSON 与序列化
来源：http://dali.yonumen.top/Article/details/gt2zahgsbkf.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2chelehrk.html

[K01] 对象转 JSON 字符串
来源：http://dali.9152youxi.cn/Article/details/gt2fbcnbycv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shangyingyoupin.top/Article/details/gt2idpbwpjl.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cqqwz.cn/Article/details/gt2ihxdrmvb.html

JS:   JSON.stringify(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2pdwujcvm.html

TS:   JSON.stringify(obj)
来源：http://dali.316326.xyz/Article/details/gt2gtgrsbbn.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gaohongyu789.top/Article/details/gt2nblrhqkd.html

Go:   json.Marshal(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2pbkdzhsn.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.snrcjt.cn/Article/details/gt2wurucsxi.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.redwolf501.top/Article/details/gt2osppuazl.html

[K02] JSON 字符串转对象
来源：http://dali.svipenyu.cn/Article/details/gt2ordhoqyu.html

Py:   json.loads(s)
来源：http://dali.xylfe.cn/Article/details/gt2qimrjtop.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nhvbywos.html

JS:   JSON.parse(s)
来源：http://dali.guannengcc.top/Article/details/gt2tsvtxyga.html

TS:   JSON.parse(s)
来源：http://dali.xuanzx.com/Article/details/gt2lsarhqqj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yj202588.top/Article/details/gt2vqfkvhcb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.fengsongda.top/Article/details/gt2fntbclve.html

Ruby: JSON.parse(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jskjqgcr.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cdnleiting.top/Article/details/gt2eynkidrd.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yvedp.cn/Article/details/gt2otlebsbd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjabnrcs.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.tian-w.cn/Article/details/gt2enjverlj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.vqdsnc.cn/Article/details/gt2tygrwoca.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sweek.top/Article/details/gt2hftuyome.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.havefunace.top/Article/details/gt2dxvdnozc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.dashuyun.cn/Article/details/gt2jfcmztgf.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.meibo888.top/Article/details/gt2tqhekplw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yuanzhike.top/Article/details/gt2gkoaypob.html

[K04] 读取 JSON 文件
来源：http://dali.jianghu66.top/Article/details/gt2uwzwqfzm.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ybcxt.top/Article/details/gt2pqxsnups.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xylfe.cn/Article/details/gt2olhznmct.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sysykeji.top/Article/details/gt2eghtldzo.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shzxlz.cn/Article/details/gt2ydwfntdt.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gotoacloud.top/Article/details/gt2doksauij.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cqqwz.cn/Article/details/gt2wjdgnvau.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2eptwrkmv.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinqigfzy.top/Article/details/gt2ojxashqp.html

[K05] 深拷贝对象
来源：http://dali.jinqigufen.top/Article/details/gt2tuurgmua.html

Py:   copy.deepcopy(obj)
来源：http://dali.yuxming.cn/Article/details/gt2cguxywxl.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shanyushiyangtech.top/Article/details/gt2anyhdhes.html

JS:   structuredClone(obj)
来源：http://dali.gzhubu.top/Article/details/gt2tygfzisw.html

TS:   structuredClone(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2weoahnmx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gt2nnaubnvw.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.quarkkingdee.top/Article/details/gt2kfbdjkdr.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hnqzz.top/Article/details/gt2yqswtbjt.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shzxlz.cn/Article/details/gt2cbsjwusj.html

[K06] 解析 URL 查询串
来源：http://dali.yonumen.top/Article/details/gt2hiuikmcq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yj202588.top/Article/details/gt2sqhptdhb.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.iojbl.cn/Article/details/gt2vplymzji.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jiagoushi.top/Article/details/gt2oprkqqek.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxuanxn.top/Article/details/gt2trrxfzkb.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tpdhmfqp.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xtcgxkwi.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.andypj.xyz/Article/details/gt2odvecuws.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.nanxuanxn.top/Article/details/gt2zdqekmjk.html

[K07] 进制转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xbjnixep.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gt2kqlglszp.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.birdmap.top/Article/details/gt2mptcyvwv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hzzhvbpd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gt2oebebasp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.sweek.top/Article/details/gt2hcjpnpxx.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhoulong.xyz/Article/details/gt2zqpwfmpl.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.tianlin.xyz/Article/details/gt2cpwfpqnk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gt2pxdotxxt.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sweek.top/Article/details/gt2ndchcvuz.html

Py:   pickle.dumps(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qlkotovd.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2xetdczuk.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.kuanghao11.cn/Article/details/gt2dhbddrst.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ybcxt.top/Article/details/gt2crhthela.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gotoacloud.top/Article/details/gt2uegolqco.html

Go:   encoding/gob
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2webleknh.html

Ruby: Marshal.dump(obj)
来源：http://dali.316326.xyz/Article/details/gt2yixilimh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhengqikj.top/Article/details/gt2ebefgvei.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2bjeezjyk.html


<!-- 参考信息 -->