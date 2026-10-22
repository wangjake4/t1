代发 wailian999

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jinqigfzy.top/Article/details/gtrafchauc.html

[Q75] 日期格式化
来源：http://dali.ybcxt.top/Article/details/gtipwrkggh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.smart0.xyz/Article/details/gttmdzfelh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.wangdashe.top/Article/details/gtlzhfrwoz.html

[Q76] 按天统计
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpgjmllfu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.meibo888.top/Article/details/gttphpdskr.html

[Q77] 时间加减
来源：http://dali.mhx1999.top/Article/details/gtsbivrysd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cheryme.top/Article/details/gtkcyggjbg.html

[Q78] 当前时间
来源：http://dali.zdqjudy.top/Article/details/gtmhiythmj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shanyushiyangtech.top/Article/details/gteolypscu.html

[Q79] 字符串拼接
来源：http://dali.ivvv.top/Article/details/gtmuvaasqo.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.kuanghao11.cn/Article/details/gteltyiffq.html

[Q80] 字符串截取
来源：http://dali.yongpay.top/Article/details/gtfvsiasns.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.fengsongda.top/Article/details/gtopkzucli.html

[Q81] 字符串替换
来源：http://dali.xuanzx.com/Article/details/gtesgxiuvs.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtopjplyrm.html

[Q82] 字符长度与字节长度
来源：http://dali.yonumen.top/Article/details/gtlycuggbt.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gttxttdeas.html

[Q83] 大小写转换
来源：http://dali.zhoulong.xyz/Article/details/gtdkcgvhfl.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.aizwys.cn/Article/details/gthtchxxvn.html

[Q84] 去除首尾空格
来源：http://dali.xuanzx.com/Article/details/gtmoxcjfqp.html

SELECT TRIM(name) FROM users;
来源：http://dali.sysykeji.top/Article/details/gtyxycxdir.html

[Q85] 数值取整
来源：http://dali.meibo888.top/Article/details/gtitnkixsv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ivvv.top/Article/details/gtcrithjex.html

[Q86] 读取 JSON 字段
来源：http://dali.feifeiyinyue.top/Article/details/gtruxxtywp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinqigufen.top/Article/details/gtruepagir.html

[Q87] JSON 字段做条件
来源：http://dali.zhongyouzk.top/Article/details/gtzojxrwoe.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.dashuyun.cn/Article/details/gtzrnxchox.html

[Q88] 行转列（条件聚合）
来源：http://dali.ydzc1.top/Article/details/gtdypgkivq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrvbnarmu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sysykeji.top/Article/details/gtfagrljxl.html

[Q89] 判断表是否存在
来源：http://dali.ppjwa.cn/Article/details/gtvvqdkdkc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.guowangkeji.top/Article/details/gtgzqzcbmp.html

[Q90] 生成序号列
来源：http://dali.jinqigufen.top/Article/details/gtbciajyad.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gzhubu.top/Article/details/gtosbkluwv.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtjsmauibm.html

R. Bash 专题
来源：http://dali.smart0.xyz/Article/details/gtqkhfmesv.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtzqadqhss.html

[R01] shebang 与严格模式
来源：http://dali.yj202588.top/Article/details/gthrxntldn.html

#!/usr/bin/env bash
来源：http://dali.fengsongda.top/Article/details/gtmzfazmwx.html

set -euo pipefail
来源：http://dali.zhiwuduotai.top/Article/details/gtmpdaqsbq.html

[R02] 变量赋值与使用
来源：http://dali.jqgufenzy.top/Article/details/gtfbmpcfxs.html

name="Tom"; echo "$name"
来源：http://dali.xuanzx.com/Article/details/gtvxhtvuub.html

[R03] 只读变量
来源：http://dali.ybcxt.top/Article/details/gtqciasgnr.html

readonly PI=3.14
来源：http://dali.nanxuanxn.top/Article/details/gtdaagiksq.html

[R04] 位置参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxqzaufsj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.daxiang520.top/Article/details/gtdwuojuhn.html

[R05] 参数默认值
来源：http://dali.guowangkeji.top/Article/details/gtussbqhlj.html

name="${1:-default}"
来源：http://dali.hnqzz.top/Article/details/gtrofbhylp.html

[R06] 判断命令是否存在
来源：http://dali.aibaodan.cn/Article/details/gtrdatdnhd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xziqi.cn/Article/details/gtplbqogdh.html

[R07] if 判断文件
来源：http://dali.ivvv.top/Article/details/gtgeduojih.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.feifeiyinyue.top/Article/details/gtjdhqbgyq.html

[R08] 数值比较
来源：http://dali.zdqjudy.top/Article/details/gtobxasszw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yvedp.cn/Article/details/gtvkvkzbog.html

[R09] 字符串比较
来源：http://dali.yj20258.top/Article/details/gtarbrowcx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj202588.top/Article/details/gtzsoqwzoc.html

[R10] 正则匹配
来源：http://dali.jinqigfzy.top/Article/details/gtpsmiyqec.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cucudq.cn/Article/details/gtwlvrmbvz.html

[R11] case 多分支
来源：http://dali.ivvv.top/Article/details/gtfnwmyqsi.html

case "$1" in
来源：http://dali.birdmap.top/Article/details/gtsjdypqdz.html

start) echo "启动" ;;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlbrzrpbz.html

stop)  echo "停止" ;;
来源：http://dali.gogol.net.cn/Article/details/gtbcrfmfql.html

*)     echo "未知命令" ;;
来源：http://dali.wangdashe.top/Article/details/gtxiwqpdxx.html

esac
来源：http://dali.havefunace.top/Article/details/gtgtyvahof.html

[R12] for 遍历文件
来源：http://dali.yj202588.top/Article/details/gtmccgxsof.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sweek.top/Article/details/gtlgkvpsez.html

[R13] for 计数循环
来源：http://dali.jqgufenzy.top/Article/details/gtougwznun.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jiagoushi.top/Article/details/gtxlhqzgaw.html

[R14] C 风格 for
来源：http://dali.zhoulong.xyz/Article/details/gtvhlpvree.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hfpthk.cn/Article/details/gtznobgmzn.html

[R15] while 逐行读文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtqaudtqli.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.tian-w.cn/Article/details/gttlywqmbb.html

[R16] until 等待条件
来源：http://dali.zhengqikj.top/Article/details/gtlvtijmus.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.havefunace.top/Article/details/gtclmfcazb.html

[R17] 数组定义与取值
来源：http://dali.jianghu66.top/Article/details/gtquffzkkf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.0kj1m.cn/Article/details/gtywnifrcq.html

[R18] 遍历数组
来源：http://dali.xinyue.icu/Article/details/gtcqafbqqi.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.feifeiyinyue.top/Article/details/gtxesvaexk.html

[R19] 数组长度
来源：http://dali.shuidangran.top/Article/details/gtlomanqew.html

echo "${#arr[@]}"
来源：http://dali.cheryme.top/Article/details/gtzougacic.html

[R20] 关联数组（字典）
来源：http://dali.hfpthk.cn/Article/details/gtpsrtppkk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhixingplan.top/Article/details/gtgfdzelrp.html

[R21] 字符串长度
来源：http://dali.vqdsnc.cn/Article/details/gtskzmgzad.html

echo "${#s}"
来源：http://dali.jinqigfzy.top/Article/details/gtclcouavh.html

[R22] 截取子串
来源：http://dali.cashguo.top/Article/details/gtoqrfplcc.html

echo "${s:0:5}"
来源：http://dali.jianghu66.top/Article/details/gtckimzrqf.html

[R23] 字符串替换
来源：http://dali.shangyingyoupin.top/Article/details/gtoomvjnni.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zdqjudy.top/Article/details/gtalknqzxk.html

[R24] 大小写转换
来源：http://dali.tian-w.cn/Article/details/gtomiavcme.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gthsjpyujb.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhixingplan.top/Article/details/gteyyhxepu.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jqgfzy.top/Article/details/gtclieuvtc.html

[R26] 命令替换
来源：http://dali.iojbl.cn/Article/details/gtdwglnmin.html

now=$(date +%F); echo "$now"
来源：http://dali.zhoulong.xyz/Article/details/gtrdjagihy.html

[R27] 算术展开
来源：http://dali.guowangkeji.top/Article/details/gtjddjacgs.html

echo $((1 + 2 * 3))
来源：http://dali.haohaochexian.top/Article/details/gtmsdtommv.html

[R28] 浮点运算
来源：http://dali.xylfe.cn/Article/details/gtupcktdzm.html

echo "scale=2; 10/3" | bc
来源：http://dali.shuidangran.top/Article/details/gtettvqcuo.html

[R29] 定义函数
来源：http://dali.gzhubu.top/Article/details/gtyganlvat.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ybcxt.top/Article/details/gtzvbnnkjk.html

[R30] 函数返回状态码
来源：http://dali.cqqwz.cn/Article/details/gtgcdioeyv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.haohaochexian.top/Article/details/gtduvaxucn.html

[R31] 局部变量
来源：http://dali.meibo888.top/Article/details/gtwtlubcdl.html

f() { local x=1; echo "$x"; }
来源：http://dali.havefunace.top/Article/details/gtdexkdsmb.html

[R32] 参数个数校验
来源：http://dali.fzhhl.top/Article/details/gtdtqxxabn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhengqikj.top/Article/details/gtiivpgcqn.html

[R33] 捕获错误并提示行号
来源：http://dali.yangfankeji.com/Article/details/gtzcntgzop.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cheryme.top/Article/details/gtqxrfllzl.html

[R34] 退出时清理
来源：http://dali.chenlongwang.top/Article/details/gtukdbshoa.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.gogol.net.cn/Article/details/gtxkfmllyx.html

[R35] 后台执行并等待
来源：http://dali.zycfv.cn/Article/details/gtmxheyyhg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jlsjyb.cn/Article/details/gttgpfsygt.html

[R36] 并发执行多个任务
来源：http://dali.hnxiangtu.top/Article/details/gtgtxkhaam.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhixingplan.top/Article/details/gtqclpfkeo.html

[R37] 把输出赋给变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtyozazdkx.html

files=$(ls -1)
来源：http://dali.zhongyouzk.top/Article/details/gtltbtulmq.html

[R38] 管道串联
来源：http://dali.sweek.top/Article/details/gtnlrevwsg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.9152youxi.cn/Article/details/gtwubzlrml.html

[R39] 重定向标准输出与错误
来源：http://dali.zhiwuduotai.top/Article/details/gtzyvrmgts.html

cmd > out.log 2>&1
来源：http://dali.dianchejie.cn/Article/details/gtxzkqutkt.html

[R40] 追加写日志
来源：http://dali.hysaishi.cn/Article/details/gtfefimard.html

echo "log" >> out.log
来源：http://dali.gzhubu.top/Article/details/gtxgvodpyn.html

[R41] 丢弃输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gthcemabcl.html

cmd >/dev/null 2>&1
来源：http://dali.yonumen.top/Article/details/gtlieumxok.html

[R42] 输入重定向
来源：http://dali.aizwys.cn/Article/details/gtxfihhroi.html

wc -l < a.txt
来源：http://dali.shzxlz.cn/Article/details/gtorvkxlql.html

[R43] 按名字查找文件
来源：http://dali.yanxiufei.cn/Article/details/gtkirdutwo.html

find . -name "*.log" -type f
来源：http://dali.wangshuangyany.cn/Article/details/gtjndybfbu.html

[R44] 按修改时间查找
来源：http://dali.gotoacloud.top/Article/details/gtgmdmzepm.html

find . -mtime -7 -type f
来源：http://dali.tianlin.xyz/Article/details/gtomjnubdf.html

[R45] 批量删除
来源：http://dali.dashuyun.cn/Article/details/gtharzeytf.html

find . -name "*.tmp" -delete
来源：http://dali.yvedp.cn/Article/details/gtylgtdhps.html

[R46] 递归替换文件内容
来源：http://dali.vqdsnc.cn/Article/details/gtblafrmdj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmeexlbtq.html

[R47] sed 单行替换
来源：http://dali.shangyingyoupin.top/Article/details/gtyplikbve.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinqigufen.top/Article/details/gtbpqecqdo.html

[R48] awk 取指定列
来源：http://dali.guannengcc.top/Article/details/gtpprhllly.html

awk '{print $1, $3}' a.txt
来源：http://dali.hnxiangtu.top/Article/details/gtmdraisjs.html

[R49] awk 带条件
来源：http://dali.ehwqpu.com/Article/details/gtkomfduyt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sysykeji.top/Article/details/gtgabsbdwd.html

[R50] awk 求和
来源：http://dali.wangdashe.top/Article/details/gtqpkjzcxb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yuanzhike.top/Article/details/gtrtbaxbye.html

[R51] 排序去重取前几
来源：http://dali.svipenyu.cn/Article/details/gtjqkfsfmk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.iojbl.cn/Article/details/gtqvooamuw.html

[R52] 统计行数
来源：http://dali.xinyue.icu/Article/details/gtwlluuulq.html

wc -l a.txt
来源：http://dali.daria6918.cn/Article/details/gtybvwqkpk.html

[R53] 查看文件头与实时尾
来源：http://dali.ppjwa.cn/Article/details/gtgerjhfqs.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yongpay.top/Article/details/gtjvynhnwa.html

[R54] 比较两个文件
来源：http://dali.svipenyu.cn/Article/details/gttfggtmvb.html

diff a.txt b.txt
来源：http://dali.ybcxt.top/Article/details/gtviolbiph.html

[R55] 压缩与解压
来源：http://dali.pengpengdd.cyou/Article/details/gtczuyoxhp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ydzc1.top/Article/details/gtrnbvrabu.html

[R56] 远程拷贝
来源：http://dali.jinqigfzy.top/Article/details/gtzzqibcpy.html

scp file user@host:/path/
来源：http://dali.zhongyouzk.top/Article/details/gtxrpgukkt.html

[R57] 远程执行命令
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqvyuyupt.html

ssh user@host 'uptime'
来源：http://dali.hammf.cn/Article/details/gtdzwyljkr.html

[R58] 下载文件
来源：http://dali.aizwys.cn/Article/details/gtywmeqaon.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrftpgtsq.html

[R59] 发 POST JSON
来源：http://dali.sweek.top/Article/details/gtjcbrrego.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hongshengwenyu.top/Article/details/gtohtwhzfb.html

[R60] 只看 HTTP 状态码
来源：http://dali.meibo888.top/Article/details/gtkjgpmqyz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.guowangkeji.top/Article/details/gtwhcujzcx.html

[R61] 磁盘占用
来源：http://dali.cqqwz.cn/Article/details/gtvdmpujdm.html

df -h;  du -sh *
来源：http://dali.zdqjudy.top/Article/details/gtapobcrrq.html

[R62] 找最占空间的文件
来源：http://dali.daria6918.cn/Article/details/gtcvejslvd.html

du -ah . | sort -rh | head -10
来源：http://dali.shanyushiyangtech.top/Article/details/gtsqyledla.html

[R63] 内存与进程
来源：http://dali.jlsjyb.cn/Article/details/gtezxrmnvz.html

free -h;  ps aux | grep nginx
来源：http://dali.tanke756.top/Article/details/gtrcebaxcw.html

[R64] 结束进程
来源：http://dali.nwbrower.top/Article/details/gtcsjawwmp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zdqjudy.top/Article/details/gtmrzzlqks.html

[R65] 查看端口占用
来源：http://dali.tanke756.top/Article/details/gtdognuhrx.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zycfv.cn/Article/details/gtsvdcmnta.html

[R66] 定时任务
来源：http://dali.shangyingyoupin.top/Article/details/gtbytrkqrr.html

crontab -e;  crontab -l
来源：http://dali.tianlin.xyz/Article/details/gteewabalp.html

[R67] 生成随机十六进制串
来源：http://dali.cqqwz.cn/Article/details/gtdlxyuvzd.html

openssl rand -hex 16
来源：http://dali.jqgfzy.top/Article/details/gtupnxkmea.html

[R68] 计算文件校验值
来源：http://dali.yuanzhike.top/Article/details/gtliuxvydx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gttsbyfnmi.html

[R69] 生成随机密码
来源：http://dali.havefunace.top/Article/details/gtnlxnyhcj.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gtskpcerxt.html

[R70] 时间戳与互转
来源：http://dali.wangshuangyany.cn/Article/details/gtkmmvjtsr.html

date +%s;  date -d @1700000000
来源：http://dali.jinqigufen.top/Article/details/gtomazchod.html

[R71] 日期格式化
来源：http://dali.shangyingyoupin.top/Article/details/gtypperfnj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.gogol.net.cn/Article/details/gtucsysnyw.html

[R72] 等待端口就绪
来源：http://dali.pengpengdd.cyou/Article/details/gtnmkfthqi.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.gotoacloud.top/Article/details/gtwydcvpyj.html

[R73] 分割大日志
来源：http://dali.hammf.cn/Article/details/gtvzvrtztb.html

split -l 1000 big.log part_
来源：http://dali.tianlin.xyz/Article/details/gtfokwumvl.html

[R74] 批量重命名
来源：http://dali.0kj1m.cn/Article/details/gtpqgboikl.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.mhx1999.top/Article/details/gtrjgicnwl.html

[R75] 导出环境变量
来源：http://dali.birdmap.top/Article/details/gtazeblspb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.snrcjt.cn/Article/details/gtnamymnrn.html

[R76] 使用临时文件
来源：http://dali.hysaishi.cn/Article/details/gtxdvycafu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.sysykeji.top/Article/details/gtkkyxgqrk.html

[R77] 读取用户输入
来源：http://dali.meibo888.top/Article/details/gtxrdjdced.html

read -rp "请输入: " ans
来源：http://dali.iojbl.cn/Article/details/gtubgsbivq.html

[R78] 交互式菜单
来源：http://dali.fengsongda.top/Article/details/gtvlhmrcqh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.fengsongda.top/Article/details/gthjhhhiuc.html

[R79] 解析命令行选项
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdchpngso.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.chenzaomai.com/Article/details/gtuaogztdh.html

[R80] 查看脚本执行耗时
来源：http://dali.yanxiufei.cn/Article/details/gtcszjoubu.html

time ./run.sh
来源：http://dali.hammf.cn/Article/details/gtqvljegph.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtcvwalujj.html

S. C / C++ 专题
来源：http://dali.jinghuilouyu.cn/Article/details/gtxeqvpbqi.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtnybsaopz.html

[S01] C：Hello World
来源：http://dali.c1oappe.top/Article/details/gtraesoang.html

#include <stdio.h>
来源：http://dali.ivvv.top/Article/details/gtnactdslr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.bjfxy.top/Article/details/gttlfqrdxs.html

[S02] C：变量与格式化输出
来源：http://dali.pycfn.com/Article/details/gtinpjykkw.html

int a = 10; printf("%d\n", a);
来源：http://dali.zdqjudy.top/Article/details/gthimbxxex.html

[S03] C：读入整数
来源：http://dali.cashguo.top/Article/details/gtlzzemaqp.html

int x; scanf("%d", &x);
来源：http://dali.yvedp.cn/Article/details/gtvcqiddao.html

[S04] C：字符串复制
来源：http://dali.wangshuangyany.cn/Article/details/gtsifkmdeg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhiwuduotai.top/Article/details/gtxfpenlgp.html

[S05] C：字符串长度
来源：http://dali.yanxiufei.cn/Article/details/gtxrhxelwy.html

strlen(s)
来源：http://dali.gaohongyu789.top/Article/details/gtfbtpgxwl.html

[S06] C：字符串比较
来源：http://dali.yuxming.cn/Article/details/gtxrzaolnf.html

strcmp(a, b) == 0
来源：http://dali.316326.xyz/Article/details/gtpxocwyhk.html

[S07] C：数组遍历求和
来源：http://dali.xinyue.icu/Article/details/gtumujzxzm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.snrcjt.cn/Article/details/gtwmvjqsjv.html

[S08] C：动态内存分配与释放
来源：http://dali.zhongyouzk.top/Article/details/gtkxedpaul.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zycfv.cn/Article/details/gtnxpkiyiz.html

[S09] C：结构体定义与初始化
来源：http://dali.jinghuilouyu.cn/Article/details/gtikrccpdf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jqgufenzy.top/Article/details/gtocdhipsn.html

[S10] C：指针与解引用
来源：http://dali.meibo888.top/Article/details/gtojsktiqc.html

int *p = &a;  *p = 5;
来源：http://dali.andypj.xyz/Article/details/gtlwujpcuz.html

[S11] C：逐行读文件
来源：http://dali.zycfv.cn/Article/details/gtrmgbfuto.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jinghuilouyu.cn/Article/details/gtwuvgjykq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xuanzx.com/Article/details/gtxsveghco.html

fclose(f);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoxzcyvpt.html

[S12] C：写文件
来源：http://dali.quarkkingdee.top/Article/details/gtdoqmdiyi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yangfankeji.com/Article/details/gtusnmbzdb.html

[S13] C：宏定义
来源：http://dali.jqgufenzy.top/Article/details/gtofqgtnbd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.daxiang520.top/Article/details/gtzjibfamr.html

[S14] C：枚举
来源：http://dali.vqdsnc.cn/Article/details/gtpicrninj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yangfankeji.com/Article/details/gtqjkvojfx.html

[S15] C：类型转换
来源：http://dali.svipenyu.cn/Article/details/gtugwaultn.html

(double) a / b
来源：http://dali.yonumen.top/Article/details/gtztuiecie.html

[S16] C：位操作置位
来源：http://dali.ydzc1.top/Article/details/gtstxcondt.html

x |= (1 << 3);
来源：http://dali.ehwqpu.com/Article/details/gtvslwzyzj.html

[S17] C：安全拼接字符串
来源：http://dali.ppjwa.cn/Article/details/gtcwjcwayx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinqigfzy.top/Article/details/gtijngvvcy.html

[S18] C：命令行参数
来源：http://dali.xinyue.icu/Article/details/gtisimzdsn.html

int main(int argc, char **argv)
来源：http://dali.feifeiyinyue.top/Article/details/gteskgbxca.html

[S19] C：快速排序
来源：http://dali.yueranfly.top/Article/details/gtqizyejaa.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yj202588.top/Article/details/gtotgwrehh.html

[S20] C：二分查找
来源：http://dali.birdmap.top/Article/details/gtpbnbfsup.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.nanxuanxn.top/Article/details/gtdezyaeqk.html

[S21] C：字符类别判断
来源：http://dali.yuanzhike.top/Article/details/gtpmrunmix.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ehwqpu.com/Article/details/gtkbgunvaf.html

[S22] C：字符串转数字
来源：http://dali.hfpthk.cn/Article/details/gtcpnptqcv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.tianlin.xyz/Article/details/gtbfypleav.html

[S23] C：随机数
来源：http://dali.mhx1999.top/Article/details/gthdnfrirq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gaohongyu789.top/Article/details/gtrygkrzkg.html

[S24] C：获取本地时间
来源：http://dali.316326.xyz/Article/details/gtavbtjaou.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtilluanmm.html

[S25] C：内存拷贝
来源：http://dali.gaohongyu789.top/Article/details/gtxkphwnlu.html

memcpy(dst, src, n);
来源：http://dali.yueranfly.top/Article/details/gtkvzigwwx.html

[S26] C：内存清零
来源：http://dali.zhengqikj.top/Article/details/gtqinvxxkv.html

memset(a, 0, sizeof a);
来源：http://dali.havefunace.top/Article/details/gtlkkytkea.html

[S27] C：定义常量
来源：http://dali.dianchejie.cn/Article/details/gtgmcefamh.html

const double PI = 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdmbtpscj.html

[S28] C：静态变量
来源：http://dali.chenlongwang.top/Article/details/gtqzqhbtcq.html

static int counter = 0;
来源：http://dali.ybcxt.top/Article/details/gtsoiksfvx.html

[S29] C：变参函数
来源：http://dali.iojbl.cn/Article/details/gtkccpgngw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yonumen.top/Article/details/gtkhfqukwk.html

[S30] C：头文件保护
来源：http://dali.0kj1m.cn/Article/details/gtmtpzmwna.html

#ifndef X_H
来源：http://dali.xziqi.cn/Article/details/gtggedlpcm.html

#define X_H
来源：http://dali.dianchejie.cn/Article/details/gtwlwjssfa.html

#endif
来源：http://dali.haohaochexian.top/Article/details/gtalwmvgmm.html

[S31] C++：Hello World
来源：http://dali.wangdashe.top/Article/details/gtdeaynzak.html

#include <iostream>
来源：http://dali.andypj.xyz/Article/details/gtyvldsjic.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.bjfxy.top/Article/details/gtovlrmcyj.html

[S32] C++：字符串
来源：http://dali.hysaishi.cn/Article/details/gtlibbiplq.html

std::string s = "hi";  s += "!";
来源：http://dali.guowangkeji.top/Article/details/gtalgthmzv.html

[S33] C++：vector 增删
来源：http://dali.xziqi.cn/Article/details/gtmurhmvih.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.feifeiyinyue.top/Article/details/gtpvavwlaz.html

[S34] C++：遍历 vector
来源：http://dali.xuanzx.com/Article/details/gtmortgywk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yangfankeji.com/Article/details/gtjwjehkpu.html

[S35] C++：map
来源：http://dali.xuetiantiany.cn/Article/details/gtysbgocwd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yonumen.top/Article/details/gtpkmicosl.html

[S36] C++：unordered_map
来源：http://dali.tian-w.cn/Article/details/gtwokfcpye.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hnxiangtu.top/Article/details/gtiwmsalqt.html

[S37] C++：set
来源：http://dali.jianghu66.top/Article/details/gtpfvixccg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.nwbrower.top/Article/details/gtafuhppqv.html

[S38] C++：排序
来源：http://dali.yvedp.cn/Article/details/gtomygyrqk.html

std::sort(v.begin(), v.end());
来源：http://dali.sufxvd.cn/Article/details/gtypocoqzf.html

[S39] C++：自定义比较器排序
来源：http://dali.guannengcc.top/Article/details/gttpalojii.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.quarkkingdee.top/Article/details/gtykaglsam.html

[S40] C++：查找元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfcaaxnit.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yongpay.top/Article/details/gtcnjzyfqq.html

[S41] C++：类与构造函数
来源：http://dali.zhengqikj.top/Article/details/gtvjhtzzbh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xuetiantiany.cn/Article/details/gtwqvtnaod.html

[S42] C++：继承与虚函数
来源：http://dali.jinqigufen.top/Article/details/gtsgcasuhj.html

class B : public Base { public: void f() override {} };
来源：http://dali.yvedp.cn/Article/details/gthlzxkhqy.html

[S43] C++：智能指针
来源：http://dali.c1oappe.top/Article/details/gtosmlwjsj.html

auto p = std::make_unique<int>(5);
来源：http://dali.jianghu66.top/Article/details/gtsyfcmugs.html

[S44] C++：引用传参
来源：http://dali.yj202588.top/Article/details/gtcxvnrwxd.html

void inc(int &x) { ++x; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtrouvwalt.html


<!-- 参考信息 -->