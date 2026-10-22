代发 wailian999

[Q65] 回滚事务
来源：http://dali.zhixingplan.top/Article/details/gtyaxzwfgf.html

ROLLBACK;
来源：http://dali.cheryme.top/Article/details/gtkozbmgpo.html

[Q66] 行锁查询
来源：http://dali.shangyingyoupin.top/Article/details/gtjucgdwfm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.pycfn.com/Article/details/gtctxfakkg.html

[Q67] 设置隔离级别
来源：http://dali.zdqjudy.top/Article/details/gtegebndte.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.gaohongyu789.top/Article/details/gtwvqtiwee.html

[Q68] 保存点
来源：http://dali.yvedp.cn/Article/details/gtbzdixrcb.html

SAVEPOINT sp1;
来源：http://dali.vqdsnc.cn/Article/details/gthwkwgzxm.html

ROLLBACK TO sp1;
来源：http://dali.cheryme.top/Article/details/gtimupkgwj.html

[Q69] 查看执行计划
来源：http://dali.yuanzhike.top/Article/details/gtapzmgoux.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.316326.xyz/Article/details/gtwmhatubw.html

[Q70] 更新统计信息
来源：http://dali.chenlongwang.top/Article/details/gtsjpnkmmv.html

ANALYZE TABLE users;
来源：http://dali.zhiwuduotai.top/Article/details/gtknquplre.html

[Q71] 查看建表语句
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtibqrbyru.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.havefunace.top/Article/details/gtocgvquhq.html

[Q72] 查看索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwrymupzo.html

SHOW INDEX FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gttjbndfmx.html

[Q73] 查看表状态
来源：http://dali.xinyue.icu/Article/details/gtlxvgkcao.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.cashguo.top/Article/details/gtmjiyxmvm.html

[Q74] 强制使用索引
来源：http://dali.xinyue.icu/Article/details/gtlzllpgwf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shuidangran.top/Article/details/gtiqyixsti.html

[Q75] 日期格式化
来源：http://dali.zhiwuduotai.top/Article/details/gtblkhzits.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gtpjwlrdln.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.316326.xyz/Article/details/gtyppjyvcu.html

[Q76] 按天统计
来源：http://dali.cashguo.top/Article/details/gttuinoiin.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yongpay.top/Article/details/gtrhcuaupm.html

[Q77] 时间加减
来源：http://dali.yj20258.top/Article/details/gtbdjcxcea.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhiwuduotai.top/Article/details/gtgogqegtc.html

[Q78] 当前时间
来源：http://dali.iojbl.cn/Article/details/gtjtlrojko.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.wangshuangyany.cn/Article/details/gticldoyhn.html

[Q79] 字符串拼接
来源：http://dali.zhengqikj.top/Article/details/gtorokwzza.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.9152youxi.cn/Article/details/gttkjntfta.html

[Q80] 字符串截取
来源：http://dali.yj202588.top/Article/details/gtwxwgmppx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yj202588.top/Article/details/gtxoxuhijo.html

[Q81] 字符串替换
来源：http://dali.zhongyouzk.top/Article/details/gtpkjkbnvh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtxveujzrc.html

[Q82] 字符长度与字节长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtyegmfnct.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtckorfmvf.html

[Q83] 大小写转换
来源：http://dali.guowangkeji.top/Article/details/gtrolcudge.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtsggfjfgs.html

[Q84] 去除首尾空格
来源：http://dali.cashguo.top/Article/details/gtbweabonp.html

SELECT TRIM(name) FROM users;
来源：http://dali.sysykeji.top/Article/details/gtirdysvhw.html

[Q85] 数值取整
来源：http://dali.yueranfly.top/Article/details/gtdayxvare.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cucudq.cn/Article/details/gtuoruknis.html

[Q86] 读取 JSON 字段
来源：http://dali.jiagoushi.top/Article/details/gtdzuhcxdl.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.dianchejie.cn/Article/details/gtehblxcaw.html

[Q87] JSON 字段做条件
来源：http://dali.chenzaomai.com/Article/details/gtiidamybg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hnxiangtu.top/Article/details/gtzztqvftm.html

[Q88] 行转列（条件聚合）
来源：http://dali.jiagoushi.top/Article/details/gtbssuputb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.feifeiyinyue.top/Article/details/gtqtacdsuh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xylfe.cn/Article/details/gtqwciflwh.html

[Q89] 判断表是否存在
来源：http://dali.xuetiantiany.cn/Article/details/gtqhmtiked.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hfpthk.cn/Article/details/gtrtmxpcld.html

[Q90] 生成序号列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnfrryfne.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xylfe.cn/Article/details/gtnhbjzuex.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gteenwpiko.html

R. Bash 专题
来源：http://dali.hongshengwenyu.top/Article/details/gtzqtzilga.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtsuyltnjb.html

[R01] shebang 与严格模式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtobtfwkfb.html

#!/usr/bin/env bash
来源：http://dali.nwbrower.top/Article/details/gthpnlooqb.html

set -euo pipefail
来源：http://dali.jinqigfzy.top/Article/details/gtxymsfpzm.html

[R02] 变量赋值与使用
来源：http://dali.cdnleiting.top/Article/details/gtjdrbjano.html

name="Tom"; echo "$name"
来源：http://dali.gzhubu.top/Article/details/gtshmbwame.html

[R03] 只读变量
来源：http://dali.ppjwa.cn/Article/details/gtvstlfmfd.html

readonly PI=3.14
来源：http://dali.xylfe.cn/Article/details/gtauaisykx.html

[R04] 位置参数
来源：http://dali.xinyue.icu/Article/details/gtahflpxqi.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ehwqpu.com/Article/details/gtgdyemptx.html

[R05] 参数默认值
来源：http://dali.ppjwa.cn/Article/details/gtipqjrjwq.html

name="${1:-default}"
来源：http://dali.haohaochexian.top/Article/details/gtzvsnyjmy.html

[R06] 判断命令是否存在
来源：http://dali.zhoulong.xyz/Article/details/gtgupwlqzg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yj20258.top/Article/details/gtfrcmnmus.html

[R07] if 判断文件
来源：http://dali.havefunace.top/Article/details/gtvjzhhdlj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jyoumei.cn/Article/details/gtutauvmcv.html

[R08] 数值比较
来源：http://dali.ppjwa.cn/Article/details/gtpavgcjyw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hnqzz.top/Article/details/gtqqobwlms.html

[R09] 字符串比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtbjuluzvr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtknsqrpwu.html

[R10] 正则匹配
来源：http://dali.jinqigfzy.top/Article/details/gttpffvdpt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.haohaochexian.top/Article/details/gthtdsbkob.html

[R11] case 多分支
来源：http://dali.daria6918.cn/Article/details/gtsrjiaqfv.html

case "$1" in
来源：http://dali.fengsongda.top/Article/details/gtjzitrsjv.html

start) echo "启动" ;;
来源：http://dali.pengpengdd.cyou/Article/details/gtckquwmoe.html

stop)  echo "停止" ;;
来源：http://dali.shanyushiyangtech.top/Article/details/gtkmqvzzpl.html

*)     echo "未知命令" ;;
来源：http://dali.yueranfly.top/Article/details/gtmlqlojeq.html

esac
来源：http://dali.andypj.xyz/Article/details/gtnikhvwiz.html

[R12] for 遍历文件
来源：http://dali.cqqwz.cn/Article/details/gtcluhlkvp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.snrcjt.cn/Article/details/gtdxwnpins.html

[R13] for 计数循环
来源：http://dali.quarkkingdee.top/Article/details/gtiodqsrca.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.chenzaomai.com/Article/details/gtwrghjnbq.html

[R14] C 风格 for
来源：http://dali.havefunace.top/Article/details/gtotsuwukg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwawgejkc.html

[R15] while 逐行读文件
来源：http://dali.shangyingyoupin.top/Article/details/gtvkzydzqc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shuidangran.top/Article/details/gtznvkplsa.html

[R16] until 等待条件
来源：http://dali.yj202588.top/Article/details/gttmsjigcp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.c1oappe.top/Article/details/gtslzuzayd.html

[R17] 数组定义与取值
来源：http://dali.daria6918.cn/Article/details/gtwnuwaupy.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.nanxinkj.top/Article/details/gtuviomzey.html

[R18] 遍历数组
来源：http://dali.jiagoushi.top/Article/details/gtzdatiybu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jiagoushi.top/Article/details/gteymkdxxj.html

[R19] 数组长度
来源：http://dali.cqqwz.cn/Article/details/gtrinjqzdn.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gtivyaknbe.html

[R20] 关联数组（字典）
来源：http://dali.yueranfly.top/Article/details/gtkkkrayta.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.gaohongyu789.top/Article/details/gtzkikagyz.html

[R21] 字符串长度
来源：http://dali.jqgfzy.top/Article/details/gthtkjdpbu.html

echo "${#s}"
来源：http://dali.gotoacloud.top/Article/details/gtjeriaqno.html

[R22] 截取子串
来源：http://dali.jinqigfzy.top/Article/details/gtxfsabsda.html

echo "${s:0:5}"
来源：http://dali.haohaochexian.top/Article/details/gtxvuwxvjn.html

[R23] 字符串替换
来源：http://dali.c1oappe.top/Article/details/gtxwurrnyx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.chenjidiqi.icu/Article/details/gtkhflvncm.html

[R24] 大小写转换
来源：http://dali.havefunace.top/Article/details/gttpnsjfap.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yonumen.top/Article/details/gtlkckolhh.html

[R25] 去后缀 / 去前缀
来源：http://dali.guannengcc.top/Article/details/gtayxgysrc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yuxming.cn/Article/details/gtgajnwtee.html

[R26] 命令替换
来源：http://dali.yongpay.top/Article/details/gtwnvgygup.html

now=$(date +%F); echo "$now"
来源：http://dali.shanyushiyangtech.top/Article/details/gtbczkfvzb.html

[R27] 算术展开
来源：http://dali.yueranfly.top/Article/details/gtzrobzagu.html

echo $((1 + 2 * 3))
来源：http://dali.ybcxt.top/Article/details/gtynapgjmj.html

[R28] 浮点运算
来源：http://dali.jqgfzy.top/Article/details/gtqmisgyfz.html

echo "scale=2; 10/3" | bc
来源：http://dali.hnxiangtu.top/Article/details/gtfbkcgdvu.html

[R29] 定义函数
来源：http://dali.shangyingyoupin.top/Article/details/gtoceitwdj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.sysykeji.top/Article/details/gtkpvxzwsf.html

[R30] 函数返回状态码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvmtokjpo.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfhfqqoau.html

[R31] 局部变量
来源：http://dali.nwbrower.top/Article/details/gtpjamlznu.html

f() { local x=1; echo "$x"; }
来源：http://dali.sufxvd.cn/Article/details/gtgoihypvt.html

[R32] 参数个数校验
来源：http://dali.yueranfly.top/Article/details/gtbicedvri.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hysaishi.cn/Article/details/gtcuoncoib.html

[R33] 捕获错误并提示行号
来源：http://dali.hnqzz.top/Article/details/gtzkosfizf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.quarkkingdee.top/Article/details/gtpsoyqbiv.html

[R34] 退出时清理
来源：http://dali.sufxvd.cn/Article/details/gtasfawkpb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hammf.cn/Article/details/gtcvdlbref.html

[R35] 后台执行并等待
来源：http://dali.chenjidiqi.icu/Article/details/gtefglpwij.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.feifeiyinyue.top/Article/details/gtxnwbdntt.html

[R36] 并发执行多个任务
来源：http://dali.tian-w.cn/Article/details/gttptdwhzx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ivvv.top/Article/details/gtyaberguc.html

[R37] 把输出赋给变量
来源：http://dali.chenjidiqi.icu/Article/details/gtjajqfkle.html

files=$(ls -1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfejvjfoh.html

[R38] 管道串联
来源：http://dali.jyoumei.cn/Article/details/gttmwzvvff.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhaomingkeji.xyz/Article/details/gthxuinjou.html

[R39] 重定向标准输出与错误
来源：http://dali.ybcxt.top/Article/details/gtysnbituh.html

cmd > out.log 2>&1
来源：http://dali.nanxuanxn.top/Article/details/gtkwsmoaed.html

[R40] 追加写日志
来源：http://dali.zdqjudy.top/Article/details/gttqofygat.html

echo "log" >> out.log
来源：http://dali.cheryme.top/Article/details/gtnyqadsww.html

[R41] 丢弃输出
来源：http://dali.yj20258888.top/Article/details/gtbcvoyeir.html

cmd >/dev/null 2>&1
来源：http://dali.gaohongyu789.top/Article/details/gtkcuvxgwb.html

[R42] 输入重定向
来源：http://dali.jinqigufen.top/Article/details/gtbqnpohhh.html

wc -l < a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoytdamsc.html

[R43] 按名字查找文件
来源：http://dali.sxryk.cn/Article/details/gtoldnxftc.html

find . -name "*.log" -type f
来源：http://dali.cashguo.top/Article/details/gtibulkebp.html

[R44] 按修改时间查找
来源：http://dali.havefunace.top/Article/details/gtrliitmlz.html

find . -mtime -7 -type f
来源：http://dali.316326.xyz/Article/details/gtopxtesoa.html

[R45] 批量删除
来源：http://dali.shangyingyoupin.top/Article/details/gtxpsuwbwp.html

find . -name "*.tmp" -delete
来源：http://dali.daxiang520.top/Article/details/gtubccoqee.html

[R46] 递归替换文件内容
来源：http://dali.zhongyouzk.top/Article/details/gteqcyndvh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xziqi.cn/Article/details/gtlczmowtv.html

[R47] sed 单行替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiebmbipk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.guannengcc.top/Article/details/gtqakkbaws.html

[R48] awk 取指定列
来源：http://dali.hnqzz.top/Article/details/gtedqbfmzv.html

awk '{print $1, $3}' a.txt
来源：http://dali.yueranfly.top/Article/details/gtznnmqipj.html

[R49] awk 带条件
来源：http://dali.jianghu66.top/Article/details/gtyfdayxsu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yangfankeji.com/Article/details/gtwdkkylrt.html

[R50] awk 求和
来源：http://dali.jinghuilouyu.cn/Article/details/gtotpfckip.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.tian-w.cn/Article/details/gtsmserais.html

[R51] 排序去重取前几
来源：http://dali.ybcxt.top/Article/details/gtxgewhhfy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhaomingkeji.xyz/Article/details/gtykogagpe.html

[R52] 统计行数
来源：http://dali.jinghuilouyu.cn/Article/details/gtrjkpprvk.html

wc -l a.txt
来源：http://dali.sweek.top/Article/details/gtznothikb.html

[R53] 查看文件头与实时尾
来源：http://dali.wangdashe.top/Article/details/gtukljbxrk.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yuxming.cn/Article/details/gtscsygjha.html

[R54] 比较两个文件
来源：http://dali.ehwqpu.com/Article/details/gtdetsexai.html

diff a.txt b.txt
来源：http://dali.cqqwz.cn/Article/details/gtueidtdsa.html

[R55] 压缩与解压
来源：http://dali.dianchejie.cn/Article/details/gtpovwupbu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.haohaochexian.top/Article/details/gtcrolbaoz.html

[R56] 远程拷贝
来源：http://dali.yj202588.top/Article/details/gtgzwajenz.html

scp file user@host:/path/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttdzamyor.html

[R57] 远程执行命令
来源：http://dali.dashuyun.cn/Article/details/gtnseegxad.html

ssh user@host 'uptime'
来源：http://dali.hysaishi.cn/Article/details/gtimgrzfho.html

[R58] 下载文件
来源：http://dali.ppjwa.cn/Article/details/gtrepidoqy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hammf.cn/Article/details/gtofvdpluf.html

[R59] 发 POST JSON
来源：http://dali.vqdsnc.cn/Article/details/gtnkwzfawy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.gaohongyu789.top/Article/details/gtrqcximhd.html

[R60] 只看 HTTP 状态码
来源：http://dali.mhx1999.top/Article/details/gtcoqmiyvl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.nwbrower.top/Article/details/gtexugqlzi.html

[R61] 磁盘占用
来源：http://dali.cdnleiting.top/Article/details/gtltymaayj.html

df -h;  du -sh *
来源：http://dali.kuanghao11.cn/Article/details/gtsejzgcza.html

[R62] 找最占空间的文件
来源：http://dali.wangshuangyany.cn/Article/details/gtzheggdvf.html

du -ah . | sort -rh | head -10
来源：http://dali.iojbl.cn/Article/details/gtgjddsjrx.html

[R63] 内存与进程
来源：http://dali.andypj.xyz/Article/details/gtlnsjaaye.html

free -h;  ps aux | grep nginx
来源：http://dali.yangfankeji.com/Article/details/gtcxucnhfd.html

[R64] 结束进程
来源：http://dali.zhoulong.xyz/Article/details/gtjehcvolp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shzxlz.cn/Article/details/gtqlyfgjji.html

[R65] 查看端口占用
来源：http://dali.guowangkeji.top/Article/details/gthihcneqf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.feifeiyinyue.top/Article/details/gteyevfefv.html

[R66] 定时任务
来源：http://dali.yonumen.top/Article/details/gtpievsztk.html

crontab -e;  crontab -l
来源：http://dali.guannengcc.top/Article/details/gtrkzcuebl.html

[R67] 生成随机十六进制串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwjrlqlxb.html

openssl rand -hex 16
来源：http://dali.yangfankeji.com/Article/details/gtxavmncbl.html

[R68] 计算文件校验值
来源：http://dali.wangshuangyany.cn/Article/details/gtnkpfblme.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.0kj1m.cn/Article/details/gtnmrhxeha.html

[R69] 生成随机密码
来源：http://dali.gotoacloud.top/Article/details/gtzdixgbgf.html

head -c 16 /dev/urandom | base64
来源：http://dali.yuxming.cn/Article/details/gtwyouucma.html

[R70] 时间戳与互转
来源：http://dali.ivvv.top/Article/details/gtwdsymdgr.html

date +%s;  date -d @1700000000
来源：http://dali.yangfankeji.com/Article/details/gtgkjltjea.html

[R71] 日期格式化
来源：http://dali.chenjidiqi.icu/Article/details/gtobhzvfol.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenlongwang.top/Article/details/gtowmellzu.html

[R72] 等待端口就绪
来源：http://dali.shzxlz.cn/Article/details/gtmitydmou.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.pengpengdd.cyou/Article/details/gtlocodxcx.html

[R73] 分割大日志
来源：http://dali.hongshengwenyu.top/Article/details/gtdffcqwbd.html

split -l 1000 big.log part_
来源：http://dali.zhengqikj.top/Article/details/gtgidfsjeo.html

[R74] 批量重命名
来源：http://dali.zdqjudy.top/Article/details/gtyoylcglg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ivvv.top/Article/details/gtbsfxlrgd.html

[R75] 导出环境变量
来源：http://dali.feifeiyinyue.top/Article/details/gtfdwntqwf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.dianchejie.cn/Article/details/gtclncehej.html

[R76] 使用临时文件
来源：http://dali.yvedp.cn/Article/details/gttpidkybl.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.sweek.top/Article/details/gtopwofcim.html

[R77] 读取用户输入
来源：http://dali.zhoulong.xyz/Article/details/gtcdjjqmby.html

read -rp "请输入: " ans
来源：http://dali.yonumen.top/Article/details/gtvzxksiov.html

[R78] 交互式菜单
来源：http://dali.nanxinkj.top/Article/details/gtoixpxgab.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.gzhubu.top/Article/details/gtzmdtgzwg.html

[R79] 解析命令行选项
来源：http://dali.nanxuanxn.top/Article/details/gtpdpmovzc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yj20258888.top/Article/details/gtekeazrir.html

[R80] 查看脚本执行耗时
来源：http://dali.jianghu66.top/Article/details/gtemfwcrye.html

time ./run.sh
来源：http://dali.9152youxi.cn/Article/details/gtzbcbuswj.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gthcpppisk.html

S. C / C++ 专题
来源：http://dali.aibaodan.cn/Article/details/gtltgtbedt.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gteidxqvlr.html

[S01] C：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gtgnwtceog.html

#include <stdio.h>
来源：http://dali.yangfankeji.com/Article/details/gtteotcfto.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shuidangran.top/Article/details/gtobexhhqe.html

[S02] C：变量与格式化输出
来源：http://dali.svipenyu.cn/Article/details/gtcagqpmcm.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gtrjqxgwkg.html

[S03] C：读入整数
来源：http://dali.jianghu66.top/Article/details/gtfmhqikjt.html

int x; scanf("%d", &x);
来源：http://dali.iojbl.cn/Article/details/gtzkvaesar.html

[S04] C：字符串复制
来源：http://dali.chenjidiqi.icu/Article/details/gtqflpjlow.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gtvtxsltpb.html

[S05] C：字符串长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmvrvftrw.html

strlen(s)
来源：http://dali.yangfankeji.com/Article/details/gthhiupdbg.html

[S06] C：字符串比较
来源：http://dali.ehwqpu.com/Article/details/gtmljgdvvw.html

strcmp(a, b) == 0
来源：http://dali.cdnleiting.top/Article/details/gtleouxzvx.html

[S07] C：数组遍历求和
来源：http://dali.birdmap.top/Article/details/gtpzpasfqj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zdqjudy.top/Article/details/gtaaoaqbiz.html

[S08] C：动态内存分配与释放
来源：http://dali.fengsongda.top/Article/details/gtlwbdbimq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cucudq.cn/Article/details/gtbmutlilw.html

[S09] C：结构体定义与初始化
来源：http://dali.shzxlz.cn/Article/details/gtsswfazhg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ppjwa.cn/Article/details/gtaacmsnkg.html

[S10] C：指针与解引用
来源：http://dali.guowangkeji.top/Article/details/gtkwjibixp.html

int *p = &a;  *p = 5;
来源：http://dali.jqgufenzy.top/Article/details/gtjvpouhqa.html

[S11] C：逐行读文件
来源：http://dali.hnxiangtu.top/Article/details/gtuirmlbku.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yuanzhike.top/Article/details/gtmbkfczus.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.fengsongda.top/Article/details/gtopvjeaph.html

fclose(f);
来源：http://dali.xuetiantiany.cn/Article/details/gtdqfwymev.html

[S12] C：写文件
来源：http://dali.havefunace.top/Article/details/gtzmlgloxw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.nanxinkj.top/Article/details/gtykdnlrzr.html

[S13] C：宏定义
来源：http://dali.iojbl.cn/Article/details/gtnekjsxah.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yanxiufei.cn/Article/details/gthutdrwef.html

[S14] C：枚举
来源：http://dali.shangyingyoupin.top/Article/details/gtqjujtnhi.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.guowangkeji.top/Article/details/gtwvphjcda.html

[S15] C：类型转换
来源：http://dali.hnqzz.top/Article/details/gtoswvctru.html

(double) a / b
来源：http://dali.nwbrower.top/Article/details/gtldbchyjd.html

[S16] C：位操作置位
来源：http://dali.yj20258888.top/Article/details/gtfbqsobyz.html

x |= (1 << 3);
来源：http://dali.chenzaomai.com/Article/details/gtjkzgtxjs.html

[S17] C：安全拼接字符串
来源：http://dali.quarkkingdee.top/Article/details/gtaeqbzslc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yonumen.top/Article/details/gtvkzkglnb.html

[S18] C：命令行参数
来源：http://dali.cdnleiting.top/Article/details/gtyypzsxtt.html

int main(int argc, char **argv)
来源：http://dali.yj20258.top/Article/details/gtewebjzow.html

[S19] C：快速排序
来源：http://dali.yuxming.cn/Article/details/gtjhatkmfb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.fengsongda.top/Article/details/gtbqsibiwe.html

[S20] C：二分查找
来源：http://dali.pengpengdd.cyou/Article/details/gtuvnwdwkm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yueranfly.top/Article/details/gtclzemtge.html

[S21] C：字符类别判断
来源：http://dali.zhoulong.xyz/Article/details/gtvcorsxlb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtigwqpjed.html

[S22] C：字符串转数字
来源：http://dali.zhongyouzk.top/Article/details/gtawddouhz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cdnleiting.top/Article/details/gttlyoqxnc.html

[S23] C：随机数
来源：http://dali.jyoumei.cn/Article/details/gturrniudz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yangfankeji.com/Article/details/gtawdceasx.html

[S24] C：获取本地时间
来源：http://dali.cheryme.top/Article/details/gtbylfzchm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdediayyv.html

[S25] C：内存拷贝
来源：http://dali.yonumen.top/Article/details/gtatinndkf.html

memcpy(dst, src, n);
来源：http://dali.iojbl.cn/Article/details/gtdawkwkyg.html

[S26] C：内存清零
来源：http://dali.gaohongyu789.top/Article/details/gtfstwhwvk.html

memset(a, 0, sizeof a);
来源：http://dali.sysykeji.top/Article/details/gtsewczbrk.html

[S27] C：定义常量
来源：http://dali.feifeiyinyue.top/Article/details/gtuhudjalz.html

const double PI = 3.14159;
来源：http://dali.jyoumei.cn/Article/details/gtbkcbbivs.html

[S28] C：静态变量
来源：http://dali.redwolf501.top/Article/details/gtlpvesdyr.html

static int counter = 0;
来源：http://dali.gaohongyu789.top/Article/details/gttubaqikt.html

[S29] C：变参函数
来源：http://dali.hysaishi.cn/Article/details/gtsudnpajl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.sufxvd.cn/Article/details/gtgfiwjaug.html

[S30] C：头文件保护
来源：http://dali.yj20258888.top/Article/details/gthvxihtcc.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gtscndoahb.html

#define X_H
来源：http://dali.xylfe.cn/Article/details/gtfkoydowy.html

#endif
来源：http://dali.jqgfzy.top/Article/details/gtuuxfcspv.html

[S31] C++：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtqfdkhsdo.html

#include <iostream>
来源：http://dali.zhiwuduotai.top/Article/details/gtzrtdljva.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtybiqrcgo.html

[S32] C++：字符串
来源：http://dali.yj20258888.top/Article/details/gtxhliffbk.html

std::string s = "hi";  s += "!";
来源：http://dali.hongshengwenyu.top/Article/details/gtjkmrbvso.html

[S33] C++：vector 增删
来源：http://dali.9152youxi.cn/Article/details/gtfxgwkbnq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.chenlongwang.top/Article/details/gtrrkqrfoi.html

[S34] C++：遍历 vector
来源：http://dali.jinqigufen.top/Article/details/gtbfslbxww.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shangyingyoupin.top/Article/details/gtljbfiuze.html


<!-- 参考信息 -->