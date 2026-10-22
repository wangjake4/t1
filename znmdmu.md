代发 wailian999

[Q67] 设置隔离级别
来源：http://dali.aizwys.cn/Article/details/gthkntxmmk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zdqjudy.top/Article/details/gtmbdolekw.html

[Q68] 保存点
来源：http://dali.hammf.cn/Article/details/gtuubncihb.html

SAVEPOINT sp1;
来源：http://dali.jlsjyb.cn/Article/details/gtmzrjtrvk.html

ROLLBACK TO sp1;
来源：http://dali.yongpay.top/Article/details/gtaarwvcth.html

[Q69] 查看执行计划
来源：http://dali.wangdashe.top/Article/details/gtzlkwtohd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthlvvotbk.html

[Q70] 更新统计信息
来源：http://dali.yueranfly.top/Article/details/gtqunhgrfv.html

ANALYZE TABLE users;
来源：http://dali.jlsjyb.cn/Article/details/gttldvmuzr.html

[Q71] 查看建表语句
来源：http://dali.haohaochexian.top/Article/details/gtrmmjoclk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jqgufenzy.top/Article/details/gtfhzwgsrj.html

[Q72] 查看索引
来源：http://dali.yj20258.top/Article/details/gtfamhfayw.html

SHOW INDEX FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtllbidijb.html

[Q73] 查看表状态
来源：http://dali.jqgfzy.top/Article/details/gtgomndeeb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zdqjudy.top/Article/details/gtxwylmzbh.html

[Q74] 强制使用索引
来源：http://dali.dianchejie.cn/Article/details/gtgrilqfxt.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zdqjudy.top/Article/details/gtxnoevwym.html

[Q75] 日期格式化
来源：http://dali.yj20258888.top/Article/details/gtjjobfabc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gtsiwueyou.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.chenzaomai.com/Article/details/gtnekkhopb.html

[Q76] 按天统计
来源：http://dali.ybcxt.top/Article/details/gttjsitrep.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.redwolf501.top/Article/details/gtyhqwjjcs.html

[Q77] 时间加减
来源：http://dali.yvedp.cn/Article/details/gtauwxqnoo.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.svipenyu.cn/Article/details/gtdtdolvaf.html

[Q78] 当前时间
来源：http://dali.hywenlv.cn/Article/details/gtpwrovhyi.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xylfe.cn/Article/details/gtbosaagpx.html

[Q79] 字符串拼接
来源：http://dali.jlsjyb.cn/Article/details/gtgdwwnawb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.0kj1m.cn/Article/details/gtqxyueyei.html

[Q80] 字符串截取
来源：http://dali.fzhhl.top/Article/details/gtdwyaqnap.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtrchpezmn.html

[Q81] 字符串替换
来源：http://dali.9152youxi.cn/Article/details/gtkjkotwve.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtwjkrhdfc.html

[Q82] 字符长度与字节长度
来源：http://dali.feifeiyinyue.top/Article/details/gtwuqfxqsq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yvedp.cn/Article/details/gthjuwrsax.html

[Q83] 大小写转换
来源：http://dali.yj20258.top/Article/details/gtgfxxvpgg.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ivvv.top/Article/details/gthomqxwks.html

[Q84] 去除首尾空格
来源：http://dali.fengsongda.top/Article/details/gtkdpnalke.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtlqxcwjts.html

[Q85] 数值取整
来源：http://dali.daria6918.cn/Article/details/gtqookhizl.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.dianchejie.cn/Article/details/gtihfmfxiy.html

[Q86] 读取 JSON 字段
来源：http://dali.pengpengdd.cyou/Article/details/gtxpqopxlm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.meibo888.top/Article/details/gtmxxbajnb.html

[Q87] JSON 字段做条件
来源：http://dali.hnxiangtu.top/Article/details/gteaspudis.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.guowangkeji.top/Article/details/gtsodwsuoi.html

[Q88] 行转列（条件聚合）
来源：http://dali.hnqzz.top/Article/details/gtqempgesb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jqgfzy.top/Article/details/gtyyvtisup.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.fengsongda.top/Article/details/gtwndcobaj.html

[Q89] 判断表是否存在
来源：http://dali.xylfe.cn/Article/details/gtjycjlcru.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.316326.xyz/Article/details/gthrkenwdy.html

[Q90] 生成序号列
来源：http://dali.redwolf501.top/Article/details/gtqwalymky.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.wangdashe.top/Article/details/gtcegnwkqv.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gttyhvjzcb.html

R. Bash 专题
来源：http://dali.316326.xyz/Article/details/gtzeziplhe.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtlsxqozae.html

[R01] shebang 与严格模式
来源：http://dali.gaohongyu789.top/Article/details/gtyszpkqac.html

#!/usr/bin/env bash
来源：http://dali.zhixingplan.top/Article/details/gtgyosvydm.html

set -euo pipefail
来源：http://dali.wangshuangyany.cn/Article/details/gtmfttiwbm.html

[R02] 变量赋值与使用
来源：http://dali.smart0.xyz/Article/details/gtacigwoyp.html

name="Tom"; echo "$name"
来源：http://dali.yongpay.top/Article/details/gtsxwggazv.html

[R03] 只读变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtwmtxpjek.html

readonly PI=3.14
来源：http://dali.shangyingyoupin.top/Article/details/gtevcnvfug.html

[R04] 位置参数
来源：http://dali.hysaishi.cn/Article/details/gtfeupbivj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hysaishi.cn/Article/details/gtntkgmoqy.html

[R05] 参数默认值
来源：http://dali.gogol.net.cn/Article/details/gtcqgobtek.html

name="${1:-default}"
来源：http://dali.jqgfzy.top/Article/details/gtyugviuih.html

[R06] 判断命令是否存在
来源：http://dali.xziqi.cn/Article/details/gtsptzbrwb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jqgufenzy.top/Article/details/gtmbwjzdnp.html

[R07] if 判断文件
来源：http://dali.jinghuilouyu.cn/Article/details/gteqhuwjci.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hfpthk.cn/Article/details/gtzsztxafn.html

[R08] 数值比较
来源：http://dali.zhoulong.xyz/Article/details/gtttaormvc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jinqigfzy.top/Article/details/gtlohaypqz.html

[R09] 字符串比较
来源：http://dali.ppjwa.cn/Article/details/gtrpvjayat.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.haohaochexian.top/Article/details/gtliwxiufx.html

[R10] 正则匹配
来源：http://dali.hywenlv.cn/Article/details/gtobifflzw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.daxiang520.top/Article/details/gtdgfybmht.html

[R11] case 多分支
来源：http://dali.chenlongwang.top/Article/details/gtfjutexvp.html

case "$1" in
来源：http://dali.nwbrower.top/Article/details/gtiyitxggj.html

start) echo "启动" ;;
来源：http://dali.feifeiyinyue.top/Article/details/gtegddjveg.html

stop)  echo "停止" ;;
来源：http://dali.jinqigfzy.top/Article/details/gtjmnodneu.html

*)     echo "未知命令" ;;
来源：http://dali.meibo888.top/Article/details/gthxnhpxkf.html

esac
来源：http://dali.yuanzhike.top/Article/details/gtzsbiafyk.html

[R12] for 遍历文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtrwkkxlyg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ehwqpu.com/Article/details/gtnawemtia.html

[R13] for 计数循环
来源：http://dali.shangyingyoupin.top/Article/details/gtanjktjzy.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hongshengwenyu.top/Article/details/gtmembvllg.html

[R14] C 风格 for
来源：http://dali.guowangkeji.top/Article/details/gtnjrolcmb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.redwolf501.top/Article/details/gtgyusunvb.html

[R15] while 逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfesiffhi.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpiekaron.html

[R16] until 等待条件
来源：http://dali.jqgfzy.top/Article/details/gtjbmnpnmm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinqigfzy.top/Article/details/gtavxbxskb.html

[R17] 数组定义与取值
来源：http://dali.9152youxi.cn/Article/details/gtdicpwlaz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shuidangran.top/Article/details/gtbznexprt.html

[R18] 遍历数组
来源：http://dali.shangyingyoupin.top/Article/details/gtqphunclv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yonumen.top/Article/details/gtjniknoyx.html

[R19] 数组长度
来源：http://dali.jianghu66.top/Article/details/gtxtlsxaut.html

echo "${#arr[@]}"
来源：http://dali.ehwqpu.com/Article/details/gtjopjrvih.html

[R20] 关联数组（字典）
来源：http://dali.hysaishi.cn/Article/details/gtvzizlrwx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.gaohongyu789.top/Article/details/gtkjfxrssx.html

[R21] 字符串长度
来源：http://dali.yj20258.top/Article/details/gtsyrizavy.html

echo "${#s}"
来源：http://dali.xylfe.cn/Article/details/gtzoucldgl.html

[R22] 截取子串
来源：http://dali.xinyue.icu/Article/details/gtgtbtwpfr.html

echo "${s:0:5}"
来源：http://dali.vqdsnc.cn/Article/details/gtuusymnfk.html

[R23] 字符串替换
来源：http://dali.hongshengwenyu.top/Article/details/gtypwkbxnf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zdqjudy.top/Article/details/gtfzdjadzp.html

[R24] 大小写转换
来源：http://dali.jiagoushi.top/Article/details/gteskxtklb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.chenzaomai.com/Article/details/gtnwurhleo.html

[R25] 去后缀 / 去前缀
来源：http://dali.jyoumei.cn/Article/details/gtraobxnkv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.fengsongda.top/Article/details/gtvepfkbdy.html

[R26] 命令替换
来源：http://dali.zdqjudy.top/Article/details/gtsaqsnijy.html

now=$(date +%F); echo "$now"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvjihllql.html

[R27] 算术展开
来源：http://dali.shangyingyoupin.top/Article/details/gtsiijqmff.html

echo $((1 + 2 * 3))
来源：http://dali.jqgufenzy.top/Article/details/gtrnoteeze.html

[R28] 浮点运算
来源：http://dali.sufxvd.cn/Article/details/gtctrkrlim.html

echo "scale=2; 10/3" | bc
来源：http://dali.shzxlz.cn/Article/details/gtltijyrpx.html

[R29] 定义函数
来源：http://dali.c1oappe.top/Article/details/gtlbcxhfpg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.dianchejie.cn/Article/details/gtqqntcdkd.html

[R30] 函数返回状态码
来源：http://dali.sufxvd.cn/Article/details/gthqmysoeg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cdnleiting.top/Article/details/gtiwxswfae.html

[R31] 局部变量
来源：http://dali.cucudq.cn/Article/details/gtwlxqqrtn.html

f() { local x=1; echo "$x"; }
来源：http://dali.cashguo.top/Article/details/gtnjjftmnv.html

[R32] 参数个数校验
来源：http://dali.shangyingyoupin.top/Article/details/gtuatmmabv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sufxvd.cn/Article/details/gtreihglld.html

[R33] 捕获错误并提示行号
来源：http://dali.bjfxy.top/Article/details/gtypfytfmc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvkhzypbh.html

[R34] 退出时清理
来源：http://dali.jianghu66.top/Article/details/gtmlirrhyu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.daxiang520.top/Article/details/gtirzaqfei.html

[R35] 后台执行并等待
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvjveplnv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hnxiangtu.top/Article/details/gtjoxqsszo.html

[R36] 并发执行多个任务
来源：http://dali.zhoulong.xyz/Article/details/gtwxsuotnf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.vqdsnc.cn/Article/details/gtufuxpycl.html

[R37] 把输出赋给变量
来源：http://dali.yj20258.top/Article/details/gtklzfhiwx.html

files=$(ls -1)
来源：http://dali.feifeiyinyue.top/Article/details/gtgobjpmkm.html

[R38] 管道串联
来源：http://dali.andypj.xyz/Article/details/gtdpayptsa.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jiagoushi.top/Article/details/gttorxtwul.html

[R39] 重定向标准输出与错误
来源：http://dali.yonumen.top/Article/details/gtkobvokuu.html

cmd > out.log 2>&1
来源：http://dali.kuanghao11.cn/Article/details/gtbkznidgg.html

[R40] 追加写日志
来源：http://dali.kuanghao11.cn/Article/details/gtweyujkqo.html

echo "log" >> out.log
来源：http://dali.quarkkingdee.top/Article/details/gtswctlpaw.html

[R41] 丢弃输出
来源：http://dali.guowangkeji.top/Article/details/gtoklhgczo.html

cmd >/dev/null 2>&1
来源：http://dali.xuetiantiany.cn/Article/details/gtiefablmz.html

[R42] 输入重定向
来源：http://dali.cheryme.top/Article/details/gttmukyklr.html

wc -l < a.txt
来源：http://dali.tianlin.xyz/Article/details/gtahatvnah.html

[R43] 按名字查找文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtptmgvcmo.html

find . -name "*.log" -type f
来源：http://dali.yangfankeji.com/Article/details/gtuiohenhd.html

[R44] 按修改时间查找
来源：http://dali.shangyingyoupin.top/Article/details/gtxejpydzq.html

find . -mtime -7 -type f
来源：http://dali.wangdashe.top/Article/details/gtlivsgjuy.html

[R45] 批量删除
来源：http://dali.hammf.cn/Article/details/gtyktxfmop.html

find . -name "*.tmp" -delete
来源：http://dali.gotoacloud.top/Article/details/gtdyglirws.html

[R46] 递归替换文件内容
来源：http://dali.zhaomingkeji.xyz/Article/details/gttorzqovt.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.dianchejie.cn/Article/details/gtkfctdkob.html

[R47] sed 单行替换
来源：http://dali.ppjwa.cn/Article/details/gtopwuoftg.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.guowangkeji.top/Article/details/gtfpoxkuyt.html

[R48] awk 取指定列
来源：http://dali.chenlongwang.top/Article/details/gtynvnmjfy.html

awk '{print $1, $3}' a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsaqehxqc.html

[R49] awk 带条件
来源：http://dali.pengpengdd.cyou/Article/details/gtwryqxdup.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jqgfzy.top/Article/details/gtdjsrzikr.html

[R50] awk 求和
来源：http://dali.jinqigfzy.top/Article/details/gttbgsbzgj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ybcxt.top/Article/details/gtxwxsemow.html

[R51] 排序去重取前几
来源：http://dali.xuanzx.com/Article/details/gtgxgdedud.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.meibo888.top/Article/details/gtlalevcsc.html

[R52] 统计行数
来源：http://dali.nwbrower.top/Article/details/gthlieumlb.html

wc -l a.txt
来源：http://dali.zhixingplan.top/Article/details/gtyjciprxc.html

[R53] 查看文件头与实时尾
来源：http://dali.xziqi.cn/Article/details/gtrrknsvzz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cqqwz.cn/Article/details/gtnjgftrii.html

[R54] 比较两个文件
来源：http://dali.pengpengdd.cyou/Article/details/gtlxhgtbet.html

diff a.txt b.txt
来源：http://dali.9152youxi.cn/Article/details/gtkbawhbar.html

[R55] 压缩与解压
来源：http://dali.shzxlz.cn/Article/details/gtaawhakto.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhoulong.xyz/Article/details/gtmqpxasgr.html

[R56] 远程拷贝
来源：http://dali.hywenlv.cn/Article/details/gtwzrzhdwd.html

scp file user@host:/path/
来源：http://dali.nanxuanxn.top/Article/details/gtgbxpghsg.html

[R57] 远程执行命令
来源：http://dali.zhoulong.xyz/Article/details/gtvlklxrvx.html

ssh user@host 'uptime'
来源：http://dali.zhengqikj.top/Article/details/gtjarwkpif.html

[R58] 下载文件
来源：http://dali.jqgufenzy.top/Article/details/gtpwsobrab.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gotoacloud.top/Article/details/gtrxlayiym.html

[R59] 发 POST JSON
来源：http://dali.gotoacloud.top/Article/details/gtrrxhbhha.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sysykeji.top/Article/details/gtgtwwpfsl.html

[R60] 只看 HTTP 状态码
来源：http://dali.0kj1m.cn/Article/details/gttaltyjud.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gzhubu.top/Article/details/gtxrcqsdon.html

[R61] 磁盘占用
来源：http://dali.guowangkeji.top/Article/details/gtotdhahbs.html

df -h;  du -sh *
来源：http://dali.jiagoushi.top/Article/details/gtsdkajxau.html

[R62] 找最占空间的文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtkrnoxhww.html

du -ah . | sort -rh | head -10
来源：http://dali.mhx1999.top/Article/details/gtjwsibbip.html

[R63] 内存与进程
来源：http://dali.yj202588.top/Article/details/gtkelimaen.html

free -h;  ps aux | grep nginx
来源：http://dali.cucudq.cn/Article/details/gtpzwkxqqw.html

[R64] 结束进程
来源：http://dali.gogol.net.cn/Article/details/gtrstalgxa.html

kill -9 $(pgrep -f app.py)
来源：http://dali.nanxuanxn.top/Article/details/gtsnscdgqm.html

[R65] 查看端口占用
来源：http://dali.yj202588.top/Article/details/gtksmvgygq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.0kj1m.cn/Article/details/gtzdbwrvgv.html

[R66] 定时任务
来源：http://dali.hywenlv.cn/Article/details/gtvhzpeapm.html

crontab -e;  crontab -l
来源：http://dali.fengsongda.top/Article/details/gtepirwdzi.html

[R67] 生成随机十六进制串
来源：http://dali.ydzc1.top/Article/details/gtnuseeatc.html

openssl rand -hex 16
来源：http://dali.yueranfly.top/Article/details/gtrwbvvbbe.html

[R68] 计算文件校验值
来源：http://dali.xinyue.icu/Article/details/gtiqmxcwue.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.daxiang520.top/Article/details/gtardogodn.html

[R69] 生成随机密码
来源：http://dali.bjfxy.top/Article/details/gtgjzfxdkp.html

head -c 16 /dev/urandom | base64
来源：http://dali.hongshengwenyu.top/Article/details/gtxkvpzzvr.html

[R70] 时间戳与互转
来源：http://dali.tianlin.xyz/Article/details/gtwzfbgoac.html

date +%s;  date -d @1700000000
来源：http://dali.zhengqikj.top/Article/details/gtbkzdstte.html

[R71] 日期格式化
来源：http://dali.jinqigfzy.top/Article/details/gthhchkgxm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenjidiqi.icu/Article/details/gtabqvngkj.html

[R72] 等待端口就绪
来源：http://dali.gzhubu.top/Article/details/gtdjiltzdo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.dashuyun.cn/Article/details/gthxgiyhsc.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gtnsyauzuk.html

split -l 1000 big.log part_
来源：http://dali.haohaochexian.top/Article/details/gtughpgmnd.html

[R74] 批量重命名
来源：http://dali.jianghu66.top/Article/details/gtwqawyejk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hnqzz.top/Article/details/gtgyldqpwf.html

[R75] 导出环境变量
来源：http://dali.dashuyun.cn/Article/details/gtwmwnqcia.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.smart0.xyz/Article/details/gtmffrscvp.html

[R76] 使用临时文件
来源：http://dali.zhoulong.xyz/Article/details/gtwdsxqowi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jiagoushi.top/Article/details/gtahihriyq.html

[R77] 读取用户输入
来源：http://dali.hysaishi.cn/Article/details/gtraexhbeg.html

read -rp "请输入: " ans
来源：http://dali.xinyue.icu/Article/details/gtjnehwzca.html

[R78] 交互式菜单
来源：http://dali.yuxming.cn/Article/details/gtmguicogn.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yangfankeji.com/Article/details/gtdxojodtv.html

[R79] 解析命令行选项
来源：http://dali.yuxming.cn/Article/details/gtqsuarlbj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ivvv.top/Article/details/gtmgmejwbr.html

[R80] 查看脚本执行耗时
来源：http://dali.haohaochexian.top/Article/details/gtxyhqgzzf.html

time ./run.sh
来源：http://dali.jinqigfzy.top/Article/details/gtnftqytht.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtuzzpgsge.html

S. C / C++ 专题
来源：http://dali.hysaishi.cn/Article/details/gtqzordxhr.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtqwhihzzg.html

[S01] C：Hello World
来源：http://dali.redwolf501.top/Article/details/gtooamisom.html

#include <stdio.h>
来源：http://dali.guannengcc.top/Article/details/gtcuuihwkm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.guowangkeji.top/Article/details/gtbrszfbqh.html

[S02] C：变量与格式化输出
来源：http://dali.iojbl.cn/Article/details/gtcsicmvuu.html

int a = 10; printf("%d\n", a);
来源：http://dali.hnqzz.top/Article/details/gtcjcmhgwq.html

[S03] C：读入整数
来源：http://dali.yj20258.top/Article/details/gtxxvghuvs.html

int x; scanf("%d", &x);
来源：http://dali.chenlongwang.top/Article/details/gtkksymmpj.html

[S04] C：字符串复制
来源：http://dali.shuidangran.top/Article/details/gtvcgxuvyh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.kuanghao11.cn/Article/details/gtnumdkqyi.html

[S05] C：字符串长度
来源：http://dali.redwolf501.top/Article/details/gthzwjkisw.html

strlen(s)
来源：http://dali.jianghu66.top/Article/details/gtkkzlkvqi.html

[S06] C：字符串比较
来源：http://dali.ydzc1.top/Article/details/gtrtmookdq.html

strcmp(a, b) == 0
来源：http://dali.quarkkingdee.top/Article/details/gtleeoumfc.html

[S07] C：数组遍历求和
来源：http://dali.pycfn.com/Article/details/gtkhcqtrak.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.daria6918.cn/Article/details/gtwacizmkg.html

[S08] C：动态内存分配与释放
来源：http://dali.shanyushiyangtech.top/Article/details/gtuxzvpxel.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhengqikj.top/Article/details/gtpmgcymbr.html

[S09] C：结构体定义与初始化
来源：http://dali.hammf.cn/Article/details/gtzihhojpc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gtcewolmlz.html

[S10] C：指针与解引用
来源：http://dali.jinqigufen.top/Article/details/gtqmigctnt.html

int *p = &a;  *p = 5;
来源：http://dali.tanke756.top/Article/details/gteacjsvlv.html

[S11] C：逐行读文件
来源：http://dali.hnqzz.top/Article/details/gtevcqgqbu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xylfe.cn/Article/details/gtlkpxxhgj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jyoumei.cn/Article/details/gtwcsyalbp.html

fclose(f);
来源：http://dali.vqdsnc.cn/Article/details/gtbhfkflvy.html

[S12] C：写文件
来源：http://dali.gzhubu.top/Article/details/gtearqvhne.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.nanxinkj.top/Article/details/gtfxwcgvou.html

[S13] C：宏定义
来源：http://dali.ydzc1.top/Article/details/gtoercdhmn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpkytezck.html

[S14] C：枚举
来源：http://dali.dashuyun.cn/Article/details/gtsniuiero.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hammf.cn/Article/details/gtshiohuwk.html

[S15] C：类型转换
来源：http://dali.dianchejie.cn/Article/details/gtdnivtozh.html

(double) a / b
来源：http://dali.wangdashe.top/Article/details/gtipniiyno.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gthincgikr.html

x |= (1 << 3);
来源：http://dali.tian-w.cn/Article/details/gtqtipfkit.html

[S17] C：安全拼接字符串
来源：http://dali.hnqzz.top/Article/details/gthszlnlpu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hfpthk.cn/Article/details/gtuwixjxqf.html

[S18] C：命令行参数
来源：http://dali.ivvv.top/Article/details/gthatadlmd.html

int main(int argc, char **argv)
来源：http://dali.zhongyouzk.top/Article/details/gtzjnhhovc.html

[S19] C：快速排序
来源：http://dali.birdmap.top/Article/details/gtohvsrftk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jinqigfzy.top/Article/details/gtawtdzkid.html

[S20] C：二分查找
来源：http://dali.vqdsnc.cn/Article/details/gtvqciiwxs.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.daxiang520.top/Article/details/gtvbjlrbba.html

[S21] C：字符类别判断
来源：http://dali.snrcjt.cn/Article/details/gttvqauqvm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ivvv.top/Article/details/gtqbipnoik.html

[S22] C：字符串转数字
来源：http://dali.jinqigufen.top/Article/details/gtkyfmiite.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cucudq.cn/Article/details/gtzcqhrngw.html

[S23] C：随机数
来源：http://dali.chenlongwang.top/Article/details/gtvaqdwwml.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jlsjyb.cn/Article/details/gtztneklcz.html

[S24] C：获取本地时间
来源：http://dali.meibo888.top/Article/details/gtoxxzpmet.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.guowangkeji.top/Article/details/gtvxmtkkru.html

[S25] C：内存拷贝
来源：http://dali.meibo888.top/Article/details/gtcgapndhs.html

memcpy(dst, src, n);
来源：http://dali.wangdashe.top/Article/details/gtabvqlbgu.html

[S26] C：内存清零
来源：http://dali.shangyingyoupin.top/Article/details/gtlhiftzpb.html

memset(a, 0, sizeof a);
来源：http://dali.cucudq.cn/Article/details/gtuiefrcra.html

[S27] C：定义常量
来源：http://dali.hnxiangtu.top/Article/details/gtdsytqmcr.html

const double PI = 3.14159;
来源：http://dali.yongpay.top/Article/details/gtmfyusabc.html

[S28] C：静态变量
来源：http://dali.0kj1m.cn/Article/details/gtpzezpdlk.html

static int counter = 0;
来源：http://dali.zhiwuduotai.top/Article/details/gtrxtpxxex.html

[S29] C：变参函数
来源：http://dali.yangfankeji.com/Article/details/gtblklksfg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.dianchejie.cn/Article/details/gtfzscxpqx.html

[S30] C：头文件保护
来源：http://dali.jqgufenzy.top/Article/details/gtredaexaq.html

#ifndef X_H
来源：http://dali.aizwys.cn/Article/details/gtapdqymuv.html

#define X_H
来源：http://dali.snrcjt.cn/Article/details/gtswrenext.html

#endif
来源：http://dali.jyoumei.cn/Article/details/gtdzpimiyp.html

[S31] C++：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtvnqpsqpw.html

#include <iostream>
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwqlrjgix.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.quarkkingdee.top/Article/details/gtrsfqxrzu.html

[S32] C++：字符串
来源：http://dali.redwolf501.top/Article/details/gttnbwoxaq.html

std::string s = "hi";  s += "!";
来源：http://dali.ydzc1.top/Article/details/gtavhymfkj.html

[S33] C++：vector 增删
来源：http://dali.pengpengdd.cyou/Article/details/gtpxqoagvh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cheryme.top/Article/details/gtpxszubcv.html

[S34] C++：遍历 vector
来源：http://dali.dashuyun.cn/Article/details/gtesffczis.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gaohongyu789.top/Article/details/gtaflxvnca.html

[S35] C++：map
来源：http://dali.ybcxt.top/Article/details/gtbpbpnfkf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yueranfly.top/Article/details/gtfpwuywkz.html

[S36] C++：unordered_map
来源：http://dali.shuidangran.top/Article/details/gtuntryxxm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtioqnebna.html


<!-- 参考信息 -->