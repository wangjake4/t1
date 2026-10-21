代发 wailian999

[Q67] 设置隔离级别
来源：http://dali.c1oappe.top/Article/details/gtxwbjsceg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.guannengcc.top/Article/details/gtbyguerru.html

[Q68] 保存点
来源：http://dali.haohaochexian.top/Article/details/gtevhypswn.html

SAVEPOINT sp1;
来源：http://dali.xziqi.cn/Article/details/gtwxnfewsr.html

ROLLBACK TO sp1;
来源：http://dali.yongpay.top/Article/details/gtjxbjslds.html

[Q69] 查看执行计划
来源：http://dali.kuanghao11.cn/Article/details/gtjplkgvly.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.vqdsnc.cn/Article/details/gtktglxggs.html

[Q70] 更新统计信息
来源：http://dali.ehwqpu.com/Article/details/gtholvvmhu.html

ANALYZE TABLE users;
来源：http://dali.wangshuangyany.cn/Article/details/gtkxpodnov.html

[Q71] 查看建表语句
来源：http://dali.yvedp.cn/Article/details/gtivzhdoml.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhongyouzk.top/Article/details/gtlvwymshp.html

[Q72] 查看索引
来源：http://dali.jqgfzy.top/Article/details/gtwdpqqwgy.html

SHOW INDEX FROM users;
来源：http://dali.hnqzz.top/Article/details/gtulewqnjf.html

[Q73] 查看表状态
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbuxfqszd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gzhubu.top/Article/details/gtctjywamm.html

[Q74] 强制使用索引
来源：http://dali.zhengqikj.top/Article/details/gthcaptifz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shuidangran.top/Article/details/gtsdgzbqmb.html

[Q75] 日期格式化
来源：http://dali.aizwys.cn/Article/details/gtqmprlyaf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gtuquvolbi.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwikpwdfp.html

[Q76] 按天统计
来源：http://dali.shanyushiyangkeji.top/Article/details/gtghftwxfb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.316326.xyz/Article/details/gtgedzgsbl.html

[Q77] 时间加减
来源：http://dali.xziqi.cn/Article/details/gtuuvpwyrt.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hfpthk.cn/Article/details/gtsovzcfrm.html

[Q78] 当前时间
来源：http://dali.aizwys.cn/Article/details/gtrjsnftui.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yangfankeji.com/Article/details/gtweaiupbn.html

[Q79] 字符串拼接
来源：http://dali.fzhhl.top/Article/details/gtzdkuszlx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hysaishi.cn/Article/details/gtggiqufgk.html

[Q80] 字符串截取
来源：http://dali.jqgufenzy.top/Article/details/gtwxakfvmm.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.pycfn.com/Article/details/gtaudimfak.html

[Q81] 字符串替换
来源：http://dali.hfpthk.cn/Article/details/gtzohzrmjw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.sweek.top/Article/details/gtsnwurteq.html

[Q82] 字符长度与字节长度
来源：http://dali.zdqjudy.top/Article/details/gtkmqaudpo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtexpxfwad.html

[Q83] 大小写转换
来源：http://dali.yangfankeji.com/Article/details/gtsvrputaa.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtbffwbhfk.html

[Q84] 去除首尾空格
来源：http://dali.nanxinkj.top/Article/details/gtibnnnccf.html

SELECT TRIM(name) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtkjcackjv.html

[Q85] 数值取整
来源：http://dali.zdqjudy.top/Article/details/gtfxbtaucb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.dashuyun.cn/Article/details/gtnrzyivmy.html

[Q86] 读取 JSON 字段
来源：http://dali.guannengcc.top/Article/details/gtvqzghuaq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cqqwz.cn/Article/details/gtxqholspf.html

[Q87] JSON 字段做条件
来源：http://dali.birdmap.top/Article/details/gtiascrfvx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.316326.xyz/Article/details/gthfvpiyvl.html

[Q88] 行转列（条件聚合）
来源：http://dali.yongpay.top/Article/details/gtntiwaglm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.dianchejie.cn/Article/details/gtnnbxrbjr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtsligpwxj.html

[Q89] 判断表是否存在
来源：http://dali.jqgufenzy.top/Article/details/gtxmosjkgq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cashguo.top/Article/details/gtweeqkorv.html

[Q90] 生成序号列
来源：http://dali.chenlongwang.top/Article/details/gtkedtntup.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gogol.net.cn/Article/details/gtzletzrrj.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtbtbfiqtn.html

R. Bash 专题
来源：http://dali.redwolf501.top/Article/details/gtntjlmgin.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtslrvpcyy.html

[R01] shebang 与严格模式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtedazrxuk.html

#!/usr/bin/env bash
来源：http://dali.zhongyouzk.top/Article/details/gtwyhafenp.html

set -euo pipefail
来源：http://dali.zhiwuduotai.top/Article/details/gtjxyqpczr.html

[R02] 变量赋值与使用
来源：http://dali.quarkkingdee.top/Article/details/gtscsvskxa.html

name="Tom"; echo "$name"
来源：http://dali.316326.xyz/Article/details/gtwzlfwjnk.html

[R03] 只读变量
来源：http://dali.cqqwz.cn/Article/details/gtnpiiddti.html

readonly PI=3.14
来源：http://dali.xylfe.cn/Article/details/gtebupjhmn.html

[R04] 位置参数
来源：http://dali.jinqigufen.top/Article/details/gtthwifxbq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yj20258888.top/Article/details/gteolgoazr.html

[R05] 参数默认值
来源：http://dali.gzhubu.top/Article/details/gtvvncacwu.html

name="${1:-default}"
来源：http://dali.zhixingplan.top/Article/details/gtanyglgdl.html

[R06] 判断命令是否存在
来源：http://dali.316326.xyz/Article/details/gtnktxolsv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.birdmap.top/Article/details/gtcdbzdqbx.html

[R07] if 判断文件
来源：http://dali.ybcxt.top/Article/details/gtnfyisujy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sufxvd.cn/Article/details/gtwhziwiej.html

[R08] 数值比较
来源：http://dali.svipenyu.cn/Article/details/gtkwlfxkjn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sweek.top/Article/details/gtkaxozuws.html

[R09] 字符串比较
来源：http://dali.zhengqikj.top/Article/details/gtrmuktbkb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.nwbrower.top/Article/details/gtlwlspuvj.html

[R10] 正则匹配
来源：http://dali.svipenyu.cn/Article/details/gtacmavklg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zycfv.cn/Article/details/gtumdvylow.html

[R11] case 多分支
来源：http://dali.jqgufenzy.top/Article/details/gtawbmytot.html

case "$1" in
来源：http://dali.sysykeji.top/Article/details/gtsatlujoq.html

start) echo "启动" ;;
来源：http://dali.hysaishi.cn/Article/details/gtpttbuwkg.html

stop)  echo "停止" ;;
来源：http://dali.jianghu66.top/Article/details/gtuoqngkkc.html

*)     echo "未知命令" ;;
来源：http://dali.sysykeji.top/Article/details/gthwbelyrr.html

esac
来源：http://dali.daxiang520.top/Article/details/gtdcdyceag.html

[R12] for 遍历文件
来源：http://dali.tanke756.top/Article/details/gtznggjbrw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.nanxinkj.top/Article/details/gtldotffyi.html

[R13] for 计数循环
来源：http://dali.nanxuanxn.top/Article/details/gtolwigqpv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hfpthk.cn/Article/details/gtjenqvivw.html

[R14] C 风格 for
来源：http://dali.yj20258888.top/Article/details/gtckasuqnm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.haohaochexian.top/Article/details/gturvlvpey.html

[R15] while 逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gtsikmvivh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.tanke756.top/Article/details/gtkmwiypaw.html

[R16] until 等待条件
来源：http://dali.mhx1999.top/Article/details/gtfsdbbfzt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.nwbrower.top/Article/details/gtpmefxmqt.html

[R17] 数组定义与取值
来源：http://dali.gzhubu.top/Article/details/gttayjiqtc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.nwbrower.top/Article/details/gtxxhjhplg.html

[R18] 遍历数组
来源：http://dali.guannengcc.top/Article/details/gtgquuaglj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yangfankeji.com/Article/details/gtdxbqebhx.html

[R19] 数组长度
来源：http://dali.iojbl.cn/Article/details/gtbtmgkqsq.html

echo "${#arr[@]}"
来源：http://dali.tian-w.cn/Article/details/gtwxgqyzvq.html

[R20] 关联数组（字典）
来源：http://dali.aibaodan.cn/Article/details/gtitvmlhgl.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hnqzz.top/Article/details/gtowkoxalt.html

[R21] 字符串长度
来源：http://dali.wangshuangyany.cn/Article/details/gtvzsqdzlx.html

echo "${#s}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmrwhudzl.html

[R22] 截取子串
来源：http://dali.zhoulong.xyz/Article/details/gteoopxjxt.html

echo "${s:0:5}"
来源：http://dali.tanke756.top/Article/details/gtgqdqnjkc.html

[R23] 字符串替换
来源：http://dali.yuanzhike.top/Article/details/gtdnbluajn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jlsjyb.cn/Article/details/gtnpalaykc.html

[R24] 大小写转换
来源：http://dali.dashuyun.cn/Article/details/gtajhtgvsi.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.gogol.net.cn/Article/details/gtwtckvmse.html

[R25] 去后缀 / 去前缀
来源：http://dali.andypj.xyz/Article/details/gtgrlpukba.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinqigfzy.top/Article/details/gtqjrscikj.html

[R26] 命令替换
来源：http://dali.fzhhl.top/Article/details/gtwnyatdlh.html

now=$(date +%F); echo "$now"
来源：http://dali.smart0.xyz/Article/details/gtpzynrjzj.html

[R27] 算术展开
来源：http://dali.gotoacloud.top/Article/details/gtfdttkoni.html

echo $((1 + 2 * 3))
来源：http://dali.vqdsnc.cn/Article/details/gtjxxhakop.html

[R28] 浮点运算
来源：http://dali.feifeiyinyue.top/Article/details/gtcculvvgq.html

echo "scale=2; 10/3" | bc
来源：http://dali.xylfe.cn/Article/details/gtxodnufpd.html

[R29] 定义函数
来源：http://dali.hongshengwenyu.top/Article/details/gtvlzbnruk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.sxryk.cn/Article/details/gtpeatwxvo.html

[R30] 函数返回状态码
来源：http://dali.cheryme.top/Article/details/gtbaippxzp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtshdekzst.html

[R31] 局部变量
来源：http://dali.guannengcc.top/Article/details/gtmeqkuwni.html

f() { local x=1; echo "$x"; }
来源：http://dali.birdmap.top/Article/details/gtrengarcy.html

[R32] 参数个数校验
来源：http://dali.cheryme.top/Article/details/gthhqjemrc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.daria6918.cn/Article/details/gtxltpsneg.html

[R33] 捕获错误并提示行号
来源：http://dali.fzhhl.top/Article/details/gtuldccloo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yuxming.cn/Article/details/gtvdeqqolu.html

[R34] 退出时清理
来源：http://dali.redwolf501.top/Article/details/gtfbeowlhe.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhaomingkeji.xyz/Article/details/gtujimbdgs.html

[R35] 后台执行并等待
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtudijycvo.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.chenjidiqi.icu/Article/details/gtkaiyhlrr.html

[R36] 并发执行多个任务
来源：http://dali.cashguo.top/Article/details/gtocxazpuh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jiagoushi.top/Article/details/gtwhfxudud.html

[R37] 把输出赋给变量
来源：http://dali.zdqjudy.top/Article/details/gtjhrqkyjl.html

files=$(ls -1)
来源：http://dali.nwbrower.top/Article/details/gtbyzciatc.html

[R38] 管道串联
来源：http://dali.hysaishi.cn/Article/details/gtcwadrjsb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hongshengwenyu.top/Article/details/gtigranudv.html

[R39] 重定向标准输出与错误
来源：http://dali.cashguo.top/Article/details/gtuqcmeqgs.html

cmd > out.log 2>&1
来源：http://dali.wangdashe.top/Article/details/gtqfhdlcbh.html

[R40] 追加写日志
来源：http://dali.gotoacloud.top/Article/details/gttmqnkgqu.html

echo "log" >> out.log
来源：http://dali.gotoacloud.top/Article/details/gtdlgtiymk.html

[R41] 丢弃输出
来源：http://dali.shanyushiyangtech.top/Article/details/gtpehjckgq.html

cmd >/dev/null 2>&1
来源：http://dali.ivvv.top/Article/details/gtpxobyjpa.html

[R42] 输入重定向
来源：http://dali.fengsongda.top/Article/details/gtbjmopumd.html

wc -l < a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtcvuvhzzl.html

[R43] 按名字查找文件
来源：http://dali.hongshengwenyu.top/Article/details/gtfnykqzrb.html

find . -name "*.log" -type f
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdpdxurtm.html

[R44] 按修改时间查找
来源：http://dali.fengsongda.top/Article/details/gtdltgimso.html

find . -mtime -7 -type f
来源：http://dali.guannengcc.top/Article/details/gtzflemxwf.html

[R45] 批量删除
来源：http://dali.zycfv.cn/Article/details/gteyonggot.html

find . -name "*.tmp" -delete
来源：http://dali.ehwqpu.com/Article/details/gtquonewhn.html

[R46] 递归替换文件内容
来源：http://dali.vqdsnc.cn/Article/details/gtllzlqksw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hammf.cn/Article/details/gtsajwloyj.html

[R47] sed 单行替换
来源：http://dali.yj202588.top/Article/details/gtwpbrjsgs.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hywenlv.cn/Article/details/gtjyzgvxvx.html

[R48] awk 取指定列
来源：http://dali.zhixingplan.top/Article/details/gthdcwrfki.html

awk '{print $1, $3}' a.txt
来源：http://dali.wangdashe.top/Article/details/gthhoqyneb.html

[R49] awk 带条件
来源：http://dali.redwolf501.top/Article/details/gtjmpjuitd.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jqgufenzy.top/Article/details/gtmfrlszoj.html

[R50] awk 求和
来源：http://dali.nwbrower.top/Article/details/gtmqtokvju.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hnqzz.top/Article/details/gthtdvlwzh.html

[R51] 排序去重取前几
来源：http://dali.fengsongda.top/Article/details/gtbpinqfha.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cucudq.cn/Article/details/gtbavthmgt.html

[R52] 统计行数
来源：http://dali.daria6918.cn/Article/details/gtjwuwepgb.html

wc -l a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtgqiyjfnj.html

[R53] 查看文件头与实时尾
来源：http://dali.chenlongwang.top/Article/details/gtxvmvennt.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shanyushiyangtech.top/Article/details/gtdqduqgjq.html

[R54] 比较两个文件
来源：http://dali.zhongyouzk.top/Article/details/gtuaezjctf.html

diff a.txt b.txt
来源：http://dali.haohaochexian.top/Article/details/gtwhtafxea.html

[R55] 压缩与解压
来源：http://dali.zdqjudy.top/Article/details/gtdrbxwuxa.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zdqjudy.top/Article/details/gtfkqvtmnx.html

[R56] 远程拷贝
来源：http://dali.chenzaomai.com/Article/details/gtgqnwrsqh.html

scp file user@host:/path/
来源：http://dali.chenlongwang.top/Article/details/gtkgrflnuz.html

[R57] 远程执行命令
来源：http://dali.xziqi.cn/Article/details/gtlbeivnsv.html

ssh user@host 'uptime'
来源：http://dali.shangyingyoupin.top/Article/details/gtybnsovdh.html

[R58] 下载文件
来源：http://dali.tanke756.top/Article/details/gtbxudzxml.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sxryk.cn/Article/details/gtgkgflxvc.html

[R59] 发 POST JSON
来源：http://dali.cdnleiting.top/Article/details/gtrtzbpsdw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinqigufen.top/Article/details/gtbkhrrtxn.html

[R60] 只看 HTTP 状态码
来源：http://dali.yangfankeji.com/Article/details/gtfmoamxwn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jlsjyb.cn/Article/details/gtjrwmcdjs.html

[R61] 磁盘占用
来源：http://dali.316326.xyz/Article/details/gtemstescy.html

df -h;  du -sh *
来源：http://dali.ybcxt.top/Article/details/gtnzegvxpr.html

[R62] 找最占空间的文件
来源：http://dali.fzhhl.top/Article/details/gtsdouztiu.html

du -ah . | sort -rh | head -10
来源：http://dali.yonumen.top/Article/details/gtwfcznzue.html

[R63] 内存与进程
来源：http://dali.hysaishi.cn/Article/details/gtarqbowqn.html

free -h;  ps aux | grep nginx
来源：http://dali.jqgfzy.top/Article/details/gtaqbyehgg.html

[R64] 结束进程
来源：http://dali.mhx1999.top/Article/details/gtgvjumohm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cqqwz.cn/Article/details/gtotkmabfh.html

[R65] 查看端口占用
来源：http://dali.nwbrower.top/Article/details/gtcjyahwqt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yongpay.top/Article/details/gtlcyownud.html

[R66] 定时任务
来源：http://dali.jinqigufen.top/Article/details/gtpgpkbfop.html

crontab -e;  crontab -l
来源：http://dali.sweek.top/Article/details/gtktumobyk.html

[R67] 生成随机十六进制串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzhqqbyja.html

openssl rand -hex 16
来源：http://dali.fzhhl.top/Article/details/gtpitgimug.html

[R68] 计算文件校验值
来源：http://dali.iojbl.cn/Article/details/gtebpjqqne.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.birdmap.top/Article/details/gtthrvuvem.html

[R69] 生成随机密码
来源：http://dali.quarkkingdee.top/Article/details/gtyqemnxkk.html

head -c 16 /dev/urandom | base64
来源：http://dali.dianchejie.cn/Article/details/gtnsbhdllc.html

[R70] 时间戳与互转
来源：http://dali.jlsjyb.cn/Article/details/gtvgtpazxj.html

date +%s;  date -d @1700000000
来源：http://dali.daxiang520.top/Article/details/gtxjnqefbi.html

[R71] 日期格式化
来源：http://dali.hfpthk.cn/Article/details/gtxxejmpij.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.wangshuangyany.cn/Article/details/gtwnubnryc.html

[R72] 等待端口就绪
来源：http://dali.daria6918.cn/Article/details/gtpnohnzdi.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ppjwa.cn/Article/details/gtsukfvqdh.html

[R73] 分割大日志
来源：http://dali.wangdashe.top/Article/details/gtmpwdxhqf.html

split -l 1000 big.log part_
来源：http://dali.meibo888.top/Article/details/gtdehwovmh.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gtvjzwgowh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.chenlongwang.top/Article/details/gtjnzqieua.html

[R75] 导出环境变量
来源：http://dali.zhixingplan.top/Article/details/gttmtaznmt.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yongpay.top/Article/details/gtpdhvacqu.html

[R76] 使用临时文件
来源：http://dali.cucudq.cn/Article/details/gtgynqtolc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj20258.top/Article/details/gtjlyncdct.html

[R77] 读取用户输入
来源：http://dali.jqgufenzy.top/Article/details/gtrstdyowh.html

read -rp "请输入: " ans
来源：http://dali.cdnleiting.top/Article/details/gtmcxqwzpe.html

[R78] 交互式菜单
来源：http://dali.yj20258.top/Article/details/gtvfsleurv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hysaishi.cn/Article/details/gtsrnnujog.html

[R79] 解析命令行选项
来源：http://dali.zhoulong.xyz/Article/details/gtouhlvkug.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sweek.top/Article/details/gtfvfclfpq.html

[R80] 查看脚本执行耗时
来源：http://dali.gotoacloud.top/Article/details/gtgpuabmng.html

time ./run.sh
来源：http://dali.daria6918.cn/Article/details/gtqfxiehwp.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtfdkyxtok.html

S. C / C++ 专题
来源：http://dali.gaohongyu789.top/Article/details/gtpiskluhu.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtrdpzfjcz.html

[S01] C：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtldjnbqih.html

#include <stdio.h>
来源：http://dali.9152youxi.cn/Article/details/gtkfkffcps.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jinqigufen.top/Article/details/gtucijoqco.html

[S02] C：变量与格式化输出
来源：http://dali.meibo888.top/Article/details/gtphoxdecx.html

int a = 10; printf("%d\n", a);
来源：http://dali.jiagoushi.top/Article/details/gtqisrtgdi.html

[S03] C：读入整数
来源：http://dali.shuidangran.top/Article/details/gtlgvilxpc.html

int x; scanf("%d", &x);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjjgqcxca.html

[S04] C：字符串复制
来源：http://dali.jinqigufen.top/Article/details/gtgzoeryym.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gotoacloud.top/Article/details/gtxyolccuz.html

[S05] C：字符串长度
来源：http://dali.wangdashe.top/Article/details/gtfgmqdsrq.html

strlen(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtsaaovslq.html

[S06] C：字符串比较
来源：http://dali.xziqi.cn/Article/details/gtkczpvjwv.html

strcmp(a, b) == 0
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtawdzepfi.html

[S07] C：数组遍历求和
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwcwjydou.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xinyue.icu/Article/details/gtmsuyqyix.html

[S08] C：动态内存分配与释放
来源：http://dali.shzxlz.cn/Article/details/gthclqtahw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.0kj1m.cn/Article/details/gtccxpyrbg.html

[S09] C：结构体定义与初始化
来源：http://dali.daxiang520.top/Article/details/gtrdzyoifw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ehwqpu.com/Article/details/gtojcylokq.html

[S10] C：指针与解引用
来源：http://dali.nanxuanxn.top/Article/details/gtedcdykil.html

int *p = &a;  *p = 5;
来源：http://dali.guannengcc.top/Article/details/gtttatfjam.html

[S11] C：逐行读文件
来源：http://dali.daxiang520.top/Article/details/gtgkqpswql.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yuxming.cn/Article/details/gtnefpbrbq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.svipenyu.cn/Article/details/gtoilivpay.html

fclose(f);
来源：http://dali.ehwqpu.com/Article/details/gtzuxupxod.html

[S12] C：写文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsgygdphp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxurdimeh.html

[S13] C：宏定义
来源：http://dali.svipenyu.cn/Article/details/gtemdjqrrw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gaohongyu789.top/Article/details/gttechrdfk.html

[S14] C：枚举
来源：http://dali.fengsongda.top/Article/details/gtigvewzox.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.gzhubu.top/Article/details/gtftlkkkxv.html

[S15] C：类型转换
来源：http://dali.quarkkingdee.top/Article/details/gtwtyhmkiw.html

(double) a / b
来源：http://dali.chenjidiqi.icu/Article/details/gtdyjpbjdh.html

[S16] C：位操作置位
来源：http://dali.havefunace.top/Article/details/gtukwvpkpm.html

x |= (1 << 3);
来源：http://dali.fengsongda.top/Article/details/gthpdptlql.html

[S17] C：安全拼接字符串
来源：http://dali.guowangkeji.top/Article/details/gttnjtcetl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinqigufen.top/Article/details/gtugruifwd.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gtxzbvkgly.html

int main(int argc, char **argv)
来源：http://dali.gzhubu.top/Article/details/gteeavzvdm.html

[S19] C：快速排序
来源：http://dali.yanxiufei.cn/Article/details/gtjwrqzqrf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gtxffidhjq.html

[S20] C：二分查找
来源：http://dali.gaohongyu789.top/Article/details/gthyzspokp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jlsjyb.cn/Article/details/gtagmfrlep.html

[S21] C：字符类别判断
来源：http://dali.sysykeji.top/Article/details/gtnwuhhxoy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sweek.top/Article/details/gtnjbucrhe.html

[S22] C：字符串转数字
来源：http://dali.fzhhl.top/Article/details/gtwvxnrvot.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.snrcjt.cn/Article/details/gtpncmqmvy.html

[S23] C：随机数
来源：http://dali.aibaodan.cn/Article/details/gtnaztqbee.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.nanxinkj.top/Article/details/gtizgcthlg.html

[S24] C：获取本地时间
来源：http://dali.hongshengwenyu.top/Article/details/gtpvwylxtz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.meibo888.top/Article/details/gtgwlqhbfy.html

[S25] C：内存拷贝
来源：http://dali.zhoulong.xyz/Article/details/gtqmggvbol.html

memcpy(dst, src, n);
来源：http://dali.xuetiantiany.cn/Article/details/gtbhntuotj.html

[S26] C：内存清零
来源：http://dali.smart0.xyz/Article/details/gthmflqjvi.html

memset(a, 0, sizeof a);
来源：http://dali.shangyingyoupin.top/Article/details/gtemaznyau.html

[S27] C：定义常量
来源：http://dali.gaohongyu789.top/Article/details/gtylvvabiy.html

const double PI = 3.14159;
来源：http://dali.sysykeji.top/Article/details/gtpakikjnn.html

[S28] C：静态变量
来源：http://dali.cqqwz.cn/Article/details/gtgqchhgne.html

static int counter = 0;
来源：http://dali.jyoumei.cn/Article/details/gtwsrqelll.html

[S29] C：变参函数
来源：http://dali.gogol.net.cn/Article/details/gtggzrvgbc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.daria6918.cn/Article/details/gtizdqpycn.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gttmqnvvxi.html

#ifndef X_H
来源：http://dali.xuetiantiany.cn/Article/details/gtzgcgqnlp.html

#define X_H
来源：http://dali.fengsongda.top/Article/details/gtcwsjylli.html

#endif
来源：http://dali.cqqwz.cn/Article/details/gtrikyqkvp.html

[S31] C++：Hello World
来源：http://dali.ivvv.top/Article/details/gtiovwsppr.html

#include <iostream>
来源：http://dali.zhiwuduotai.top/Article/details/gteucwnqxf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.nwbrower.top/Article/details/gtfdyguawe.html

[S32] C++：字符串
来源：http://dali.smart0.xyz/Article/details/gtovkgneqo.html

std::string s = "hi";  s += "!";
来源：http://dali.aizwys.cn/Article/details/gtgaajgbay.html

[S33] C++：vector 增删
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmikrqvoq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hongshengwenyu.top/Article/details/gtauqownhw.html

[S34] C++：遍历 vector
来源：http://dali.zycfv.cn/Article/details/gtxtjtduep.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cucudq.cn/Article/details/gtvquhlpyg.html

[S35] C++：map
来源：http://dali.jinqigfzy.top/Article/details/gtaoavoefn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cheryme.top/Article/details/gtncvgxjqd.html

[S36] C++：unordered_map
来源：http://dali.hysaishi.cn/Article/details/gtgwxgzugi.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nwbrower.top/Article/details/gtzpfwuzmy.html


<!-- 参考信息 -->