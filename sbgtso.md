代发 wailian999

SHOW INDEX FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2mqqnkgsp.html

[Q73] 查看表状态
来源：http://dali.hammf.cn/Article/details/gt2lehrnesd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ugbrrdgx.html

[Q74] 强制使用索引
来源：http://dali.tanke756.top/Article/details/gt2oyewuhme.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yonumen.top/Article/details/gt2rbhyontm.html

[Q75] 日期格式化
来源：http://dali.zdqjudy.top/Article/details/gt2cfofzwxq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.smart0.xyz/Article/details/gt2laxqipkt.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cheryme.top/Article/details/gt2rzpkdhdn.html

[Q76] 按天统计
来源：http://dali.jinqigufen.top/Article/details/gt2ogeypzzg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xziqi.cn/Article/details/gt2vbybkinc.html

[Q77] 时间加减
来源：http://dali.9152youxi.cn/Article/details/gt2whtubrmy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.aibaodan.cn/Article/details/gt2wtbktegu.html

[Q78] 当前时间
来源：http://dali.dashuyun.cn/Article/details/gt2svtrmelg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhongyouzk.top/Article/details/gt2xscrancg.html

[Q79] 字符串拼接
来源：http://dali.yj20258888.top/Article/details/gt2jruilcgj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hnxiangtu.top/Article/details/gt2zmisvxly.html

[Q80] 字符串截取
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bjxuqzwg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2qhahnfxg.html

[Q81] 字符串替换
来源：http://dali.haohaochexian.top/Article/details/gt2eydbteyc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2yvuswjaz.html

[Q82] 字符长度与字节长度
来源：http://dali.wangdashe.top/Article/details/gt2xiohihnt.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.sysykeji.top/Article/details/gt2sgvchpso.html

[Q83] 大小写转换
来源：http://dali.ehwqpu.com/Article/details/gt2luwmmgiv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yj20258.top/Article/details/gt2vvrxxhll.html

[Q84] 去除首尾空格
来源：http://dali.sweek.top/Article/details/gt2xuloujmv.html

SELECT TRIM(name) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2dxvogrpo.html

[Q85] 数值取整
来源：http://dali.yongpay.top/Article/details/gt2znvyuagv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hnxiangtu.top/Article/details/gt2bzdqamwm.html

[Q86] 读取 JSON 字段
来源：http://dali.meibo888.top/Article/details/gt2avxossty.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhongyouzk.top/Article/details/gt2xkhjcjfk.html

[Q87] JSON 字段做条件
来源：http://dali.gogol.net.cn/Article/details/gt2xgpxekkg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cdnleiting.top/Article/details/gt2golqdfod.html

[Q88] 行转列（条件聚合）
来源：http://dali.fengsongda.top/Article/details/gt2vywqnqvs.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.andypj.xyz/Article/details/gt2hiocinfb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2nrtrisob.html

[Q89] 判断表是否存在
来源：http://dali.zhoulong.xyz/Article/details/gt2pdlotoqq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhiwuduotai.top/Article/details/gt2lgtldjtp.html

[Q90] 生成序号列
来源：http://dali.pycfn.com/Article/details/gt2weenciti.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shzxlz.cn/Article/details/gt2juhfmrma.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2fdhtlmkc.html

R. Bash 专题
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cqmqxauf.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2wpaqheaf.html

[R01] shebang 与严格模式
来源：http://dali.gzhubu.top/Article/details/gt2eellyomu.html

#!/usr/bin/env bash
来源：http://dali.cqqwz.cn/Article/details/gt2ksujoqlk.html

set -euo pipefail
来源：http://dali.yangfankeji.com/Article/details/gt2lywlhxga.html

[R02] 变量赋值与使用
来源：http://dali.hongshengwenyu.top/Article/details/gt2plznoevv.html

name="Tom"; echo "$name"
来源：http://dali.c1oappe.top/Article/details/gt2gssbndud.html

[R03] 只读变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dnftfvuj.html

readonly PI=3.14
来源：http://dali.chenlongwang.top/Article/details/gt2ncgxrqld.html

[R04] 位置参数
来源：http://dali.yj20258888.top/Article/details/gt2yuzqldkf.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2crazevdp.html

[R05] 参数默认值
来源：http://dali.guannengcc.top/Article/details/gt2qsitppen.html

name="${1:-default}"
来源：http://dali.zhongyouzk.top/Article/details/gt2ocjdlmhk.html

[R06] 判断命令是否存在
来源：http://dali.jianghu66.top/Article/details/gt2kdcwdgiw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xinyue.icu/Article/details/gt2gyvaalke.html

[R07] if 判断文件
来源：http://dali.zhoulong.xyz/Article/details/gt2rbztfhyw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinqigfzy.top/Article/details/gt2yvdonfpk.html

[R08] 数值比较
来源：http://dali.hongshengwenyu.top/Article/details/gt2hthbogqc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zdqjudy.top/Article/details/gt2hmpmpibv.html

[R09] 字符串比较
来源：http://dali.316326.xyz/Article/details/gt2xhboctxk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yuxming.cn/Article/details/gt2obzntsng.html

[R10] 正则匹配
来源：http://dali.yangfankeji.com/Article/details/gt2liadagft.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.meibo888.top/Article/details/gt2iarlhzma.html

[R11] case 多分支
来源：http://dali.shanyushiyangtech.top/Article/details/gt2miinrbbl.html

case "$1" in
来源：http://dali.dashuyun.cn/Article/details/gt2fjlzqrhd.html

start) echo "启动" ;;
来源：http://dali.jqgfzy.top/Article/details/gt2qihdamwg.html

stop)  echo "停止" ;;
来源：http://dali.yanxiufei.cn/Article/details/gt2zbjwiush.html

*)     echo "未知命令" ;;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dhulgtct.html

esac
来源：http://dali.gogol.net.cn/Article/details/gt2toeqvdyc.html

[R12] for 遍历文件
来源：http://dali.hnqzz.top/Article/details/gt2kntehjha.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yj20258888.top/Article/details/gt2wdrsbdpq.html

[R13] for 计数循环
来源：http://dali.pengpengdd.cyou/Article/details/gt2qknpwozp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.daxiang520.top/Article/details/gt2mqsjvdlx.html

[R14] C 风格 for
来源：http://dali.jinqigfzy.top/Article/details/gt2eowbeamc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.daria6918.cn/Article/details/gt2asdkeqgg.html

[R15] while 逐行读文件
来源：http://dali.jqgfzy.top/Article/details/gt2sieruyvj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jlsjyb.cn/Article/details/gt2dvlgwtji.html

[R16] until 等待条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cvufrlzw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.fzhhl.top/Article/details/gt2fggtoncj.html

[R17] 数组定义与取值
来源：http://dali.ehwqpu.com/Article/details/gt2luzyivuf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yuanzhike.top/Article/details/gt2frzmqytx.html

[R18] 遍历数组
来源：http://dali.sweek.top/Article/details/gt2uhkrgetn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.meibo888.top/Article/details/gt2mcubiejy.html

[R19] 数组长度
来源：http://dali.chenlongwang.top/Article/details/gt2jlknovnv.html

echo "${#arr[@]}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jtwiqqmn.html

[R20] 关联数组（字典）
来源：http://dali.aibaodan.cn/Article/details/gt2dzufdxpo.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jyoumei.cn/Article/details/gt2cljlucbv.html

[R21] 字符串长度
来源：http://dali.jqgufenzy.top/Article/details/gt2dsmehhzw.html

echo "${#s}"
来源：http://dali.fzhhl.top/Article/details/gt2cdikfvjh.html

[R22] 截取子串
来源：http://dali.nanxinkj.top/Article/details/gt2dfruveej.html

echo "${s:0:5}"
来源：http://dali.hysaishi.cn/Article/details/gt2wtxptiyo.html

[R23] 字符串替换
来源：http://dali.0kj1m.cn/Article/details/gt2mlppflry.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hammf.cn/Article/details/gt2anksuqkf.html

[R24] 大小写转换
来源：http://dali.chenjidiqi.icu/Article/details/gt2zhdibqeu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.c1oappe.top/Article/details/gt2ccxtsktz.html

[R25] 去后缀 / 去前缀
来源：http://dali.yj20258888.top/Article/details/gt2dujmeqkz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.sysykeji.top/Article/details/gt2wxvvbuye.html

[R26] 命令替换
来源：http://dali.hysaishi.cn/Article/details/gt2cyrpqkck.html

now=$(date +%F); echo "$now"
来源：http://dali.fzhhl.top/Article/details/gt2qsecghln.html

[R27] 算术展开
来源：http://dali.svipenyu.cn/Article/details/gt2ibyafrhw.html

echo $((1 + 2 * 3))
来源：http://dali.shzxlz.cn/Article/details/gt2mvxuanfd.html

[R28] 浮点运算
来源：http://dali.9152youxi.cn/Article/details/gt2ylvxktge.html

echo "scale=2; 10/3" | bc
来源：http://dali.chenlongwang.top/Article/details/gt2rossemcg.html

[R29] 定义函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lwkhwxen.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.chenzaomai.com/Article/details/gt2xhggbplf.html

[R30] 函数返回状态码
来源：http://dali.fzhhl.top/Article/details/gt2pwkybtat.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.smart0.xyz/Article/details/gt2gypiualj.html

[R31] 局部变量
来源：http://dali.hnqzz.top/Article/details/gt2uifuwikh.html

f() { local x=1; echo "$x"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xunkfdvt.html

[R32] 参数个数校验
来源：http://dali.nanxinkj.top/Article/details/gt2vuknyodc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xziqi.cn/Article/details/gt2ppbsmzam.html

[R33] 捕获错误并提示行号
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2frawrlmm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhixingplan.top/Article/details/gt2ddgnplaz.html

[R34] 退出时清理
来源：http://dali.yangfankeji.com/Article/details/gt2jdwpezge.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zdqjudy.top/Article/details/gt2auqrqnak.html

[R35] 后台执行并等待
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fdfrxfmm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.tian-w.cn/Article/details/gt2gvqnnxzf.html

[R36] 并发执行多个任务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2abpthiau.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hfpthk.cn/Article/details/gt2djhnwlql.html

[R37] 把输出赋给变量
来源：http://dali.pycfn.com/Article/details/gt2zrswpqho.html

files=$(ls -1)
来源：http://dali.aizwys.cn/Article/details/gt2bwbzofwe.html

[R38] 管道串联
来源：http://dali.316326.xyz/Article/details/gt2uypfagwn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.quarkkingdee.top/Article/details/gt2hhwmopjc.html

[R39] 重定向标准输出与错误
来源：http://dali.svipenyu.cn/Article/details/gt2qivfyfjz.html

cmd > out.log 2>&1
来源：http://dali.gaohongyu789.top/Article/details/gt2qyapxnoz.html

[R40] 追加写日志
来源：http://dali.cashguo.top/Article/details/gt2thkjojqy.html

echo "log" >> out.log
来源：http://dali.yanxiufei.cn/Article/details/gt2zypfybvg.html

[R41] 丢弃输出
来源：http://dali.zhongyouzk.top/Article/details/gt2xhrjvtdf.html

cmd >/dev/null 2>&1
来源：http://dali.cashguo.top/Article/details/gt2cwdoasow.html

[R42] 输入重定向
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cqqzvekc.html

wc -l < a.txt
来源：http://dali.sysykeji.top/Article/details/gt2xkdudhul.html

[R43] 按名字查找文件
来源：http://dali.zycfv.cn/Article/details/gt2okblgfsp.html

find . -name "*.log" -type f
来源：http://dali.snrcjt.cn/Article/details/gt2qbtddpof.html

[R44] 按修改时间查找
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2noynrmcl.html

find . -mtime -7 -type f
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2osjeacco.html

[R45] 批量删除
来源：http://dali.xziqi.cn/Article/details/gt2zwljrmvf.html

find . -name "*.tmp" -delete
来源：http://dali.cheryme.top/Article/details/gt2lfvcwlae.html

[R46] 递归替换文件内容
来源：http://dali.haohaochexian.top/Article/details/gt2tvvbgsvx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.quarkkingdee.top/Article/details/gt2oifeyhrp.html

[R47] sed 单行替换
来源：http://dali.jinqigfzy.top/Article/details/gt2bjsabulu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jianghu66.top/Article/details/gt2zkzzwtpa.html

[R48] awk 取指定列
来源：http://dali.ybcxt.top/Article/details/gt2jhhouewd.html

awk '{print $1, $3}' a.txt
来源：http://dali.nanxuanxn.top/Article/details/gt2pnetneir.html

[R49] awk 带条件
来源：http://dali.guannengcc.top/Article/details/gt2bqfgwxhg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yongpay.top/Article/details/gt2fnqwfvby.html

[R50] awk 求和
来源：http://dali.iojbl.cn/Article/details/gt2rifbwqyo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zycfv.cn/Article/details/gt2yhfrhpje.html

[R51] 排序去重取前几
来源：http://dali.smart0.xyz/Article/details/gt2zulmmuxj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2hbblktdj.html

[R52] 统计行数
来源：http://dali.shzxlz.cn/Article/details/gt2xqtimuoo.html

wc -l a.txt
来源：http://dali.xinyue.icu/Article/details/gt2hmpzkmqn.html

[R53] 查看文件头与实时尾
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rqvlygby.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yueranfly.top/Article/details/gt2ufpgeynv.html

[R54] 比较两个文件
来源：http://dali.vqdsnc.cn/Article/details/gt2ksvopuir.html

diff a.txt b.txt
来源：http://dali.fzhhl.top/Article/details/gt2mqkomtin.html

[R55] 压缩与解压
来源：http://dali.snrcjt.cn/Article/details/gt2xnxyxqle.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhoulong.xyz/Article/details/gt2ueohwkov.html

[R56] 远程拷贝
来源：http://dali.wangshuangyany.cn/Article/details/gt2tmpcklhg.html

scp file user@host:/path/
来源：http://dali.jinqigufen.top/Article/details/gt2duydobff.html

[R57] 远程执行命令
来源：http://dali.316326.xyz/Article/details/gt2wyaooxtx.html

ssh user@host 'uptime'
来源：http://dali.andypj.xyz/Article/details/gt2hzdvmlhs.html

[R58] 下载文件
来源：http://dali.nanxinkj.top/Article/details/gt2vwfsbsiw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.pengpengdd.cyou/Article/details/gt2dllxaaqm.html

[R59] 发 POST JSON
来源：http://dali.hongshengwenyu.top/Article/details/gt2eggjkvoj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jqgufenzy.top/Article/details/gt2ukanhcsz.html

[R60] 只看 HTTP 状态码
来源：http://dali.yueranfly.top/Article/details/gt2izpbddqf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hysaishi.cn/Article/details/gt2olegshnd.html

[R61] 磁盘占用
来源：http://dali.redwolf501.top/Article/details/gt2ovlocdcd.html

df -h;  du -sh *
来源：http://dali.sxryk.cn/Article/details/gt2dwrrozgb.html

[R62] 找最占空间的文件
来源：http://dali.gaohongyu789.top/Article/details/gt2cffjobgw.html

du -ah . | sort -rh | head -10
来源：http://dali.cashguo.top/Article/details/gt2evgvieea.html

[R63] 内存与进程
来源：http://dali.zhongyouzk.top/Article/details/gt2ddjlqrwh.html

free -h;  ps aux | grep nginx
来源：http://dali.yj202588.top/Article/details/gt2tmhrzjeu.html

[R64] 结束进程
来源：http://dali.smart0.xyz/Article/details/gt2qksrevgf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sxryk.cn/Article/details/gt2nesrgwzv.html

[R65] 查看端口占用
来源：http://dali.dianchejie.cn/Article/details/gt2jdkeqrpo.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.9152youxi.cn/Article/details/gt2kipucqnu.html

[R66] 定时任务
来源：http://dali.yuanzhike.top/Article/details/gt2ynqmvsgg.html

crontab -e;  crontab -l
来源：http://dali.yuxming.cn/Article/details/gt2rclwhskl.html

[R67] 生成随机十六进制串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vrdivefw.html

openssl rand -hex 16
来源：http://dali.mhx1999.top/Article/details/gt2bckpzmzy.html

[R68] 计算文件校验值
来源：http://dali.tian-w.cn/Article/details/gt2xlnedhjs.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.svipenyu.cn/Article/details/gt2zpdcfrhx.html

[R69] 生成随机密码
来源：http://dali.haohaochexian.top/Article/details/gt2bhyuqvai.html

head -c 16 /dev/urandom | base64
来源：http://dali.jqgufenzy.top/Article/details/gt2lliccfpd.html

[R70] 时间戳与互转
来源：http://dali.hywenlv.cn/Article/details/gt2atsmiely.html

date +%s;  date -d @1700000000
来源：http://dali.chenlongwang.top/Article/details/gt2gaegklxn.html

[R71] 日期格式化
来源：http://dali.nanxuanxn.top/Article/details/gt2giukbpck.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xinyue.icu/Article/details/gt2eexulwod.html

[R72] 等待端口就绪
来源：http://dali.yuxming.cn/Article/details/gt2towfdbti.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.sufxvd.cn/Article/details/gt2wikgzglf.html

[R73] 分割大日志
来源：http://dali.0kj1m.cn/Article/details/gt2jmiaboyt.html

split -l 1000 big.log part_
来源：http://dali.fzhhl.top/Article/details/gt2mcshompw.html

[R74] 批量重命名
来源：http://dali.havefunace.top/Article/details/gt2zfvgcxsn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yanxiufei.cn/Article/details/gt2tcprtzpj.html

[R75] 导出环境变量
来源：http://dali.yj20258888.top/Article/details/gt2wuvrzytj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.c1oappe.top/Article/details/gt2vztrqafc.html

[R76] 使用临时文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2jweevpso.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.haohaochexian.top/Article/details/gt2wqnjimvg.html

[R77] 读取用户输入
来源：http://dali.xuanzx.com/Article/details/gt2bknzromm.html

read -rp "请输入: " ans
来源：http://dali.svipenyu.cn/Article/details/gt2rfaiwqzx.html

[R78] 交互式菜单
来源：http://dali.hnxiangtu.top/Article/details/gt2recfxsvs.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.gaohongyu789.top/Article/details/gt2hysipvdp.html

[R79] 解析命令行选项
来源：http://dali.dashuyun.cn/Article/details/gt2ykxihiaf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.dashuyun.cn/Article/details/gt2mflsqzjs.html

[R80] 查看脚本执行耗时
来源：http://dali.jiagoushi.top/Article/details/gt2rcyyntyq.html

time ./run.sh
来源：http://dali.jianghu66.top/Article/details/gt2haltafoz.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2wahvyody.html

S. C / C++ 专题
来源：http://dali.cashguo.top/Article/details/gt2yahzsnrt.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lmeiovcg.html

[S01] C：Hello World
来源：http://dali.bjfxy.top/Article/details/gt2ekankjld.html

#include <stdio.h>
来源：http://dali.aibaodan.cn/Article/details/gt2sgukcchp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hysaishi.cn/Article/details/gt2zvqrepcb.html

[S02] C：变量与格式化输出
来源：http://dali.jinqigufen.top/Article/details/gt2ywafgwgv.html

int a = 10; printf("%d\n", a);
来源：http://dali.xziqi.cn/Article/details/gt2qpsmazbi.html

[S03] C：读入整数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uvmczajv.html

int x; scanf("%d", &x);
来源：http://dali.316326.xyz/Article/details/gt2redmkxxh.html

[S04] C：字符串复制
来源：http://dali.yangfankeji.com/Article/details/gt2ygljqetb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yj202588.top/Article/details/gt2yylcimpe.html

[S05] C：字符串长度
来源：http://dali.cdnleiting.top/Article/details/gt2xajvkieu.html

strlen(s)
来源：http://dali.snrcjt.cn/Article/details/gt2mnfyzlyk.html

[S06] C：字符串比较
来源：http://dali.zdqjudy.top/Article/details/gt2dxwzaqkz.html

strcmp(a, b) == 0
来源：http://dali.xuanzx.com/Article/details/gt2nngnnguy.html

[S07] C：数组遍历求和
来源：http://dali.nwbrower.top/Article/details/gt2nrybtgao.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.kuanghao11.cn/Article/details/gt2tzpexxod.html

[S08] C：动态内存分配与释放
来源：http://dali.yueranfly.top/Article/details/gt2vrmkjnge.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yueranfly.top/Article/details/gt2lhhljaav.html

[S09] C：结构体定义与初始化
来源：http://dali.jinqigfzy.top/Article/details/gt2secutcfr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jlsjyb.cn/Article/details/gt2czmexbfi.html

[S10] C：指针与解引用
来源：http://dali.cucudq.cn/Article/details/gt2iidbgrcn.html

int *p = &a;  *p = 5;
来源：http://dali.daxiang520.top/Article/details/gt2euqwqowy.html

[S11] C：逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gt2suexgsjx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.guowangkeji.top/Article/details/gt2leyswhad.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.quarkkingdee.top/Article/details/gt2fhrshbrl.html

fclose(f);
来源：http://dali.shangyingyoupin.top/Article/details/gt2frlppbwx.html

[S12] C：写文件
来源：http://dali.cqqwz.cn/Article/details/gt2qdasuhdb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.nanxuanxn.top/Article/details/gt2twsqwwrk.html

[S13] C：宏定义
来源：http://dali.chenzaomai.com/Article/details/gt2latoglwl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.tianlin.xyz/Article/details/gt2cqruunpp.html

[S14] C：枚举
来源：http://dali.yangfankeji.com/Article/details/gt2hsgefqxu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ivvv.top/Article/details/gt2awbcpzxa.html

[S15] C：类型转换
来源：http://dali.daxiang520.top/Article/details/gt2fdtnyznc.html

(double) a / b
来源：http://dali.meibo888.top/Article/details/gt2roywioaj.html

[S16] C：位操作置位
来源：http://dali.shuidangran.top/Article/details/gt2fgkyocfk.html

x |= (1 << 3);
来源：http://dali.zhixingplan.top/Article/details/gt2zjtgbfsr.html

[S17] C：安全拼接字符串
来源：http://dali.yuanzhike.top/Article/details/gt2ypaysgkl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shzxlz.cn/Article/details/gt2qyqguqhc.html

[S18] C：命令行参数
来源：http://dali.aibaodan.cn/Article/details/gt2frppprog.html

int main(int argc, char **argv)
来源：http://dali.nwbrower.top/Article/details/gt2dpmqdidq.html

[S19] C：快速排序
来源：http://dali.dianchejie.cn/Article/details/gt2haxcxftx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ivvv.top/Article/details/gt2sopncmzw.html

[S20] C：二分查找
来源：http://dali.yj202588.top/Article/details/gt2xetqklxb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yueranfly.top/Article/details/gt2msnyvfae.html

[S21] C：字符类别判断
来源：http://dali.nwbrower.top/Article/details/gt2ducgnivz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jlsjyb.cn/Article/details/gt2epgkqkzv.html

[S22] C：字符串转数字
来源：http://dali.daxiang520.top/Article/details/gt2isvcigvy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinqigufen.top/Article/details/gt2yispybmx.html

[S23] C：随机数
来源：http://dali.fzhhl.top/Article/details/gt2dbmegwve.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhoulong.xyz/Article/details/gt2qpebckyb.html

[S24] C：获取本地时间
来源：http://dali.9152youxi.cn/Article/details/gt2jvupkoja.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.gaohongyu789.top/Article/details/gt2ywovcorr.html

[S25] C：内存拷贝
来源：http://dali.cdnleiting.top/Article/details/gt2nhzfkrrp.html

memcpy(dst, src, n);
来源：http://dali.nwbrower.top/Article/details/gt2richisxy.html

[S26] C：内存清零
来源：http://dali.cqqwz.cn/Article/details/gt2olcpgitj.html

memset(a, 0, sizeof a);
来源：http://dali.fzhhl.top/Article/details/gt2dfduufrc.html

[S27] C：定义常量
来源：http://dali.zhengqikj.top/Article/details/gt2zvtnpinj.html

const double PI = 3.14159;
来源：http://dali.zycfv.cn/Article/details/gt2wwivmyyb.html

[S28] C：静态变量
来源：http://dali.ivvv.top/Article/details/gt2mskudkan.html

static int counter = 0;
来源：http://dali.xinyue.icu/Article/details/gt2slvrrslo.html

[S29] C：变参函数
来源：http://dali.birdmap.top/Article/details/gt2zyytkmoq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmsduizp.html

[S30] C：头文件保护
来源：http://dali.feifeiyinyue.top/Article/details/gt2tjlifgkt.html

#ifndef X_H
来源：http://dali.guannengcc.top/Article/details/gt2barjpbto.html

#define X_H
来源：http://dali.snrcjt.cn/Article/details/gt2nepmxdcr.html

#endif
来源：http://dali.9152youxi.cn/Article/details/gt2nhhvtdoh.html

[S31] C++：Hello World
来源：http://dali.chenlongwang.top/Article/details/gt2icqgdeqq.html

#include <iostream>
来源：http://dali.tian-w.cn/Article/details/gt2guzhtkzf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.bjfxy.top/Article/details/gt2hlxbmoit.html

[S32] C++：字符串
来源：http://dali.ehwqpu.com/Article/details/gt2njurwwda.html

std::string s = "hi";  s += "!";
来源：http://dali.cheryme.top/Article/details/gt2gulufivi.html

[S33] C++：vector 增删
来源：http://dali.birdmap.top/Article/details/gt2niogxkjf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.snrcjt.cn/Article/details/gt2tjwsyazv.html

[S34] C++：遍历 vector
来源：http://dali.gotoacloud.top/Article/details/gt2gyrhlrfa.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.aibaodan.cn/Article/details/gt2nushfnyn.html

[S35] C++：map
来源：http://dali.fzhhl.top/Article/details/gt2lixduamu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ivmdkwxr.html

[S36] C++：unordered_map
来源：http://dali.yvedp.cn/Article/details/gt2nlonmdka.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gt2pvxpzfgt.html

[S37] C++：set
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eolmusdo.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.aibaodan.cn/Article/details/gt2wksdczvx.html

[S38] C++：排序
来源：http://dali.cucudq.cn/Article/details/gt2laldfzoz.html

std::sort(v.begin(), v.end());
来源：http://dali.aizwys.cn/Article/details/gt2nhdtjjel.html

[S39] C++：自定义比较器排序
来源：http://dali.ehwqpu.com/Article/details/gt2sizzikqo.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.svipenyu.cn/Article/details/gt2glvijrms.html

[S40] C++：查找元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ybqwhpqb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.vqdsnc.cn/Article/details/gt2aueilmam.html

[S41] C++：类与构造函数
来源：http://dali.sufxvd.cn/Article/details/gt2zbfagwif.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.bjfxy.top/Article/details/gt2hvqebdid.html

[S42] C++：继承与虚函数
来源：http://dali.guowangkeji.top/Article/details/gt2yevcnhif.html

class B : public Base { public: void f() override {} };
来源：http://dali.fzhhl.top/Article/details/gt2xhovbfbr.html


<!-- 参考信息 -->