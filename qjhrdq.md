代发 wailian999

[Q63] 开启事务
来源：http://dali.guowangkeji.top/Article/details/gtrxqkttwy.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.chenlongwang.top/Article/details/gtmqerydlx.html

[Q64] 提交事务
来源：http://dali.gzhubu.top/Article/details/gteznvilvz.html

COMMIT;
来源：http://dali.mhx1999.top/Article/details/gtydbezjry.html

[Q65] 回滚事务
来源：http://dali.zhoulong.xyz/Article/details/gtpffyyrim.html

ROLLBACK;
来源：http://dali.yj20258.top/Article/details/gtsekmmora.html

[Q66] 行锁查询
来源：http://dali.sweek.top/Article/details/gtjpwlmqqp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.nwbrower.top/Article/details/gtdwrjmdef.html

[Q67] 设置隔离级别
来源：http://dali.cheryme.top/Article/details/gtqktjwxlt.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqrelrujo.html

[Q68] 保存点
来源：http://dali.daria6918.cn/Article/details/gtjqvqugta.html

SAVEPOINT sp1;
来源：http://dali.svipenyu.cn/Article/details/gtknedbtww.html

ROLLBACK TO sp1;
来源：http://dali.guowangkeji.top/Article/details/gtdbimsvrh.html

[Q69] 查看执行计划
来源：http://dali.kuanghao11.cn/Article/details/gtxjiradvx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jlsjyb.cn/Article/details/gtwjfilcoj.html

[Q70] 更新统计信息
来源：http://dali.nwbrower.top/Article/details/gtdgglriqe.html

ANALYZE TABLE users;
来源：http://dali.xuetiantiany.cn/Article/details/gtpiownklj.html

[Q71] 查看建表语句
来源：http://dali.tian-w.cn/Article/details/gtbqwmdvnq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yuxming.cn/Article/details/gtmbmaqudv.html

[Q72] 查看索引
来源：http://dali.ybcxt.top/Article/details/gtmsjpzjcw.html

SHOW INDEX FROM users;
来源：http://dali.smart0.xyz/Article/details/gtvklltgme.html

[Q73] 查看表状态
来源：http://dali.cdnleiting.top/Article/details/gtfnfsxkjl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.aizwys.cn/Article/details/gtasggwmjz.html

[Q74] 强制使用索引
来源：http://dali.c1oappe.top/Article/details/gtnajcogwd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.sufxvd.cn/Article/details/gtcgtxkjmx.html

[Q75] 日期格式化
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrqsvltkp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hnqzz.top/Article/details/gtxepipjii.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yonumen.top/Article/details/gtuvcqjosi.html

[Q76] 按天统计
来源：http://dali.jyoumei.cn/Article/details/gtsaiqvibg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.andypj.xyz/Article/details/gtliavjhbt.html

[Q77] 时间加减
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdmskqnji.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.tian-w.cn/Article/details/gtdwrkelis.html

[Q78] 当前时间
来源：http://dali.shzxlz.cn/Article/details/gtmozdpesb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinqigfzy.top/Article/details/gtlduausox.html

[Q79] 字符串拼接
来源：http://dali.jqgfzy.top/Article/details/gtdchoqtzr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cdnleiting.top/Article/details/gtxagzikan.html

[Q80] 字符串截取
来源：http://dali.c1oappe.top/Article/details/gtjiradseb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.nwbrower.top/Article/details/gtoweqwlwi.html

[Q81] 字符串替换
来源：http://dali.xziqi.cn/Article/details/gtaxtzafnb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtgcrwkwhx.html

[Q82] 字符长度与字节长度
来源：http://dali.meibo888.top/Article/details/gtkjlctkek.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtmxurltmg.html

[Q83] 大小写转换
来源：http://dali.quarkkingdee.top/Article/details/gtigkusuky.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtycdnlsdp.html

[Q84] 去除首尾空格
来源：http://dali.nanxuanxn.top/Article/details/gttxikpvci.html

SELECT TRIM(name) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtyzjcpqva.html

[Q85] 数值取整
来源：http://dali.dianchejie.cn/Article/details/gtfsgucbxl.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ybcxt.top/Article/details/gtvensswhk.html

[Q86] 读取 JSON 字段
来源：http://dali.shuidangran.top/Article/details/gtsijqsgic.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.9152youxi.cn/Article/details/gteumcjnzo.html

[Q87] JSON 字段做条件
来源：http://dali.zhengqikj.top/Article/details/gtflnrtykk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yuxming.cn/Article/details/gtoogvsdzg.html

[Q88] 行转列（条件聚合）
来源：http://dali.zdqjudy.top/Article/details/gtkysvuqor.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.feifeiyinyue.top/Article/details/gtabzbkrvr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.tian-w.cn/Article/details/gtvcypqtts.html

[Q89] 判断表是否存在
来源：http://dali.c1oappe.top/Article/details/gtrxaqhkch.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ybcxt.top/Article/details/gtizvgpdzz.html

[Q90] 生成序号列
来源：http://dali.zdqjudy.top/Article/details/gtpvihqonr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.svipenyu.cn/Article/details/gtzxoigsfl.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtmybcmrdc.html

R. Bash 专题
来源：http://dali.xziqi.cn/Article/details/gtonjxcsie.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtsolezbfb.html

[R01] shebang 与严格模式
来源：http://dali.shzxlz.cn/Article/details/gtsbuivsek.html

#!/usr/bin/env bash
来源：http://dali.gogol.net.cn/Article/details/gtfwihgasx.html

set -euo pipefail
来源：http://dali.bjfxy.top/Article/details/gtbkezimto.html

[R02] 变量赋值与使用
来源：http://dali.daria6918.cn/Article/details/gtrzjtxbcf.html

name="Tom"; echo "$name"
来源：http://dali.redwolf501.top/Article/details/gtfddsjlkl.html

[R03] 只读变量
来源：http://dali.c1oappe.top/Article/details/gtlqdpkqqw.html

readonly PI=3.14
来源：http://dali.sweek.top/Article/details/gttbghyxxb.html

[R04] 位置参数
来源：http://dali.tian-w.cn/Article/details/gtvkbyqbfm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gtphuqwtaz.html

[R05] 参数默认值
来源：http://dali.yuanzhike.top/Article/details/gtypipjxkg.html

name="${1:-default}"
来源：http://dali.hysaishi.cn/Article/details/gtynmzvdnn.html

[R06] 判断命令是否存在
来源：http://dali.tanke756.top/Article/details/gteygmcijm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.tianlin.xyz/Article/details/gtfcuhczxl.html

[R07] if 判断文件
来源：http://dali.feifeiyinyue.top/Article/details/gtngrispxy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cucudq.cn/Article/details/gtiveuwsio.html

[R08] 数值比较
来源：http://dali.jqgfzy.top/Article/details/gtddpoekcy.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.tanke756.top/Article/details/gtggqwzacp.html

[R09] 字符串比较
来源：http://dali.hfpthk.cn/Article/details/gtudbxdvjr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhongyouzk.top/Article/details/gtaayiypoh.html

[R10] 正则匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtauvzpcny.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shangyingyoupin.top/Article/details/gtsvuetyzr.html

[R11] case 多分支
来源：http://dali.yangfankeji.com/Article/details/gtkxvyiuyu.html

case "$1" in
来源：http://dali.hongshengwenyu.top/Article/details/gtegoeqfqa.html

start) echo "启动" ;;
来源：http://dali.havefunace.top/Article/details/gtvgrwlehp.html

stop)  echo "停止" ;;
来源：http://dali.yangfankeji.com/Article/details/gtaymvglsp.html

*)     echo "未知命令" ;;
来源：http://dali.zhengqikj.top/Article/details/gtubbolezb.html

esac
来源：http://dali.yj20258888.top/Article/details/gtduskcgtz.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gtzizmkrud.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sweek.top/Article/details/gtgdwwbfvj.html

[R13] for 计数循环
来源：http://dali.gaohongyu789.top/Article/details/gtfjizflfo.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gzhubu.top/Article/details/gtkyifrxef.html

[R14] C 风格 for
来源：http://dali.jinqigfzy.top/Article/details/gtrskntgky.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jinqigfzy.top/Article/details/gtsjkmunxf.html

[R15] while 逐行读文件
来源：http://dali.wangshuangyany.cn/Article/details/gtkbkqhtlt.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sxryk.cn/Article/details/gtbzhrokcf.html

[R16] until 等待条件
来源：http://dali.smart0.xyz/Article/details/gtbhhiiwrl.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yuanzhike.top/Article/details/gtgxabhcri.html

[R17] 数组定义与取值
来源：http://dali.dianchejie.cn/Article/details/gtwjjxogqp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hnxiangtu.top/Article/details/gtlvdzbvmc.html

[R18] 遍历数组
来源：http://dali.yueranfly.top/Article/details/gtylfexfrh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sweek.top/Article/details/gtfsoridmu.html

[R19] 数组长度
来源：http://dali.daxiang520.top/Article/details/gtkagjgzcy.html

echo "${#arr[@]}"
来源：http://dali.sysykeji.top/Article/details/gtrbgphlku.html

[R20] 关联数组（字典）
来源：http://dali.shuidangran.top/Article/details/gttcykxdyk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.vqdsnc.cn/Article/details/gtzzupbxrp.html

[R21] 字符串长度
来源：http://dali.sufxvd.cn/Article/details/gtxirluxec.html

echo "${#s}"
来源：http://dali.yangfankeji.com/Article/details/gtzccvulzh.html

[R22] 截取子串
来源：http://dali.dashuyun.cn/Article/details/gtvbyxfvhg.html

echo "${s:0:5}"
来源：http://dali.quarkkingdee.top/Article/details/gtbwwrdhcj.html

[R23] 字符串替换
来源：http://dali.yj20258888.top/Article/details/gtdzwfxovc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cucudq.cn/Article/details/gtwgwtdhlk.html

[R24] 大小写转换
来源：http://dali.tianlin.xyz/Article/details/gtpovubwer.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.vqdsnc.cn/Article/details/gtadgorcip.html

[R25] 去后缀 / 去前缀
来源：http://dali.316326.xyz/Article/details/gtodwkfdix.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhixingplan.top/Article/details/gtnrygzaxy.html

[R26] 命令替换
来源：http://dali.ivvv.top/Article/details/gtbwgwdaly.html

now=$(date +%F); echo "$now"
来源：http://dali.chenlongwang.top/Article/details/gtkmgvuahx.html

[R27] 算术展开
来源：http://dali.wangshuangyany.cn/Article/details/gtcauwnayb.html

echo $((1 + 2 * 3))
来源：http://dali.jyoumei.cn/Article/details/gtollrowzx.html

[R28] 浮点运算
来源：http://dali.jyoumei.cn/Article/details/gtcnbopcpm.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhixingplan.top/Article/details/gtpkecdxqb.html

[R29] 定义函数
来源：http://dali.shzxlz.cn/Article/details/gtfjzmyydi.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xinyue.icu/Article/details/gtebzdvtro.html

[R30] 函数返回状态码
来源：http://dali.yongpay.top/Article/details/gtylohltdz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jqgfzy.top/Article/details/gtthfoxajh.html

[R31] 局部变量
来源：http://dali.sxryk.cn/Article/details/gtjqaowsxx.html

f() { local x=1; echo "$x"; }
来源：http://dali.jqgufenzy.top/Article/details/gtgrjhdfwc.html

[R32] 参数个数校验
来源：http://dali.ivvv.top/Article/details/gtyopsgzln.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.redwolf501.top/Article/details/gtyydymsfu.html

[R33] 捕获错误并提示行号
来源：http://dali.zhongyouzk.top/Article/details/gtnvmtbsmw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ehwqpu.com/Article/details/gtuyymrlkx.html

[R34] 退出时清理
来源：http://dali.zycfv.cn/Article/details/gtvvastdfd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhongyouzk.top/Article/details/gtyubrmfjr.html

[R35] 后台执行并等待
来源：http://dali.andypj.xyz/Article/details/gtgvqacrpv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.wangdashe.top/Article/details/gtbqdsutzf.html

[R36] 并发执行多个任务
来源：http://dali.mhx1999.top/Article/details/gtrflxmqvz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xinyue.icu/Article/details/gthkitjmmy.html

[R37] 把输出赋给变量
来源：http://dali.zdqjudy.top/Article/details/gtrelzwzbr.html

files=$(ls -1)
来源：http://dali.ppjwa.cn/Article/details/gthnwtnwzk.html

[R38] 管道串联
来源：http://dali.jinghuilouyu.cn/Article/details/gtpyysrwrv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.9152youxi.cn/Article/details/gtxhgezfpn.html

[R39] 重定向标准输出与错误
来源：http://dali.shanyushiyangtech.top/Article/details/gtjjcpwell.html

cmd > out.log 2>&1
来源：http://dali.gzhubu.top/Article/details/gtrralyjjh.html

[R40] 追加写日志
来源：http://dali.tianlin.xyz/Article/details/gtyodkjdnt.html

echo "log" >> out.log
来源：http://dali.hysaishi.cn/Article/details/gtiorlbhpi.html

[R41] 丢弃输出
来源：http://dali.zdqjudy.top/Article/details/gtmyvoboqr.html

cmd >/dev/null 2>&1
来源：http://dali.zycfv.cn/Article/details/gthhqrdvvp.html

[R42] 输入重定向
来源：http://dali.haohaochexian.top/Article/details/gtyhunjifp.html

wc -l < a.txt
来源：http://dali.gzhubu.top/Article/details/gtnqldrjvw.html

[R43] 按名字查找文件
来源：http://dali.kuanghao11.cn/Article/details/gtyhqhulmk.html

find . -name "*.log" -type f
来源：http://dali.tianlin.xyz/Article/details/gtcrrjkqej.html

[R44] 按修改时间查找
来源：http://dali.birdmap.top/Article/details/gtzzgwleuv.html

find . -mtime -7 -type f
来源：http://dali.zhoulong.xyz/Article/details/gtyjkgfjvl.html

[R45] 批量删除
来源：http://dali.daxiang520.top/Article/details/gtffjdlxfp.html

find . -name "*.tmp" -delete
来源：http://dali.316326.xyz/Article/details/gtndavoguy.html

[R46] 递归替换文件内容
来源：http://dali.sxryk.cn/Article/details/gtmphnklrz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.dashuyun.cn/Article/details/gtmzuttgqe.html

[R47] sed 单行替换
来源：http://dali.zhiwuduotai.top/Article/details/gtcbkiunts.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmzbpuzmm.html

[R48] awk 取指定列
来源：http://dali.dashuyun.cn/Article/details/gtqtwmsnev.html

awk '{print $1, $3}' a.txt
来源：http://dali.aibaodan.cn/Article/details/gtuvcjlukd.html

[R49] awk 带条件
来源：http://dali.jqgufenzy.top/Article/details/gtrablcqrb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zycfv.cn/Article/details/gtatldcutc.html

[R50] awk 求和
来源：http://dali.aibaodan.cn/Article/details/gtqykvbjcr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.tanke756.top/Article/details/gtqbufqesg.html

[R51] 排序去重取前几
来源：http://dali.sysykeji.top/Article/details/gtwykwcqdo.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.chenlongwang.top/Article/details/gtxaxtrmfd.html

[R52] 统计行数
来源：http://dali.jyoumei.cn/Article/details/gtyoizfsrb.html

wc -l a.txt
来源：http://dali.zhengqikj.top/Article/details/gtdhrlsjwd.html

[R53] 查看文件头与实时尾
来源：http://dali.c1oappe.top/Article/details/gtatrfdkpf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shanyushiyangtech.top/Article/details/gtztcmymlj.html

[R54] 比较两个文件
来源：http://dali.hammf.cn/Article/details/gtitdibltc.html

diff a.txt b.txt
来源：http://dali.hnqzz.top/Article/details/gtyivjpxyw.html

[R55] 压缩与解压
来源：http://dali.shanyushiyangtech.top/Article/details/gtblfnhwui.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.nanxuanxn.top/Article/details/gtkvhmmxnn.html

[R56] 远程拷贝
来源：http://dali.bjfxy.top/Article/details/gtwiegsknp.html

scp file user@host:/path/
来源：http://dali.tian-w.cn/Article/details/gtxhqyckby.html

[R57] 远程执行命令
来源：http://dali.xuetiantiany.cn/Article/details/gtlwgiyqqi.html

ssh user@host 'uptime'
来源：http://dali.nwbrower.top/Article/details/gtraemfcwj.html

[R58] 下载文件
来源：http://dali.aibaodan.cn/Article/details/gtsmuaclav.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.redwolf501.top/Article/details/gtcmwcufif.html

[R59] 发 POST JSON
来源：http://dali.yj20258.top/Article/details/gtinpocaic.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jqgfzy.top/Article/details/gtqluouhez.html

[R60] 只看 HTTP 状态码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzeljwvwr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.mhx1999.top/Article/details/gtewlfaxrk.html

[R61] 磁盘占用
来源：http://dali.cashguo.top/Article/details/gtdwyjeauw.html

df -h;  du -sh *
来源：http://dali.quarkkingdee.top/Article/details/gtdaxorcsc.html

[R62] 找最占空间的文件
来源：http://dali.smart0.xyz/Article/details/gtyhrnnxps.html

du -ah . | sort -rh | head -10
来源：http://dali.xylfe.cn/Article/details/gtdjaxcfdj.html

[R63] 内存与进程
来源：http://dali.bjfxy.top/Article/details/gtwtteovkr.html

free -h;  ps aux | grep nginx
来源：http://dali.gaohongyu789.top/Article/details/gtylzsbxkp.html

[R64] 结束进程
来源：http://dali.smart0.xyz/Article/details/gtoxpadcgf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.meibo888.top/Article/details/gtfeadqhfe.html

[R65] 查看端口占用
来源：http://dali.sufxvd.cn/Article/details/gtpjpnxlwo.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yj20258888.top/Article/details/gtiefonmyl.html

[R66] 定时任务
来源：http://dali.yueranfly.top/Article/details/gtsnuzqqog.html

crontab -e;  crontab -l
来源：http://dali.havefunace.top/Article/details/gttdpxirpu.html

[R67] 生成随机十六进制串
来源：http://dali.dianchejie.cn/Article/details/gtfqwddmwc.html

openssl rand -hex 16
来源：http://dali.zycfv.cn/Article/details/gtaigwvvpb.html

[R68] 计算文件校验值
来源：http://dali.guannengcc.top/Article/details/gthuijoepx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtnucrzgtu.html

[R69] 生成随机密码
来源：http://dali.xziqi.cn/Article/details/gtwrwsjcaf.html

head -c 16 /dev/urandom | base64
来源：http://dali.cheryme.top/Article/details/gtxpdguock.html

[R70] 时间戳与互转
来源：http://dali.redwolf501.top/Article/details/gtayijqncr.html

date +%s;  date -d @1700000000
来源：http://dali.snrcjt.cn/Article/details/gtjiehkbsc.html

[R71] 日期格式化
来源：http://dali.aibaodan.cn/Article/details/gtmjdmrixp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.birdmap.top/Article/details/gtmgnrxvlu.html

[R72] 等待端口就绪
来源：http://dali.mhx1999.top/Article/details/gtxtcwrgxp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.aibaodan.cn/Article/details/gtrhmkqoii.html

[R73] 分割大日志
来源：http://dali.fengsongda.top/Article/details/gtoqjyowhh.html

split -l 1000 big.log part_
来源：http://dali.yj202588.top/Article/details/gtzixwkoue.html

[R74] 批量重命名
来源：http://dali.gaohongyu789.top/Article/details/gtotnuknpt.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.wangdashe.top/Article/details/gttimgeuty.html

[R75] 导出环境变量
来源：http://dali.chenzaomai.com/Article/details/gthbwfrznh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.feifeiyinyue.top/Article/details/gtdhabzuol.html

[R76] 使用临时文件
来源：http://dali.hfpthk.cn/Article/details/gtdmwjwnpl.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.c1oappe.top/Article/details/gtqjwkdqvo.html

[R77] 读取用户输入
来源：http://dali.jiagoushi.top/Article/details/gtywlujmzf.html

read -rp "请输入: " ans
来源：http://dali.chenzaomai.com/Article/details/gtsmbnmssa.html

[R78] 交互式菜单
来源：http://dali.cucudq.cn/Article/details/gtpstgabkg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.aibaodan.cn/Article/details/gtcfejgogi.html

[R79] 解析命令行选项
来源：http://dali.yanxiufei.cn/Article/details/gtlhkejheg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkdjcrxod.html

[R80] 查看脚本执行耗时
来源：http://dali.pengpengdd.cyou/Article/details/gtwobdtiig.html

time ./run.sh
来源：http://dali.xziqi.cn/Article/details/gtxeeidpgx.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtfprclsdx.html

S. C / C++ 专题
来源：http://dali.gaohongyu789.top/Article/details/gtrwurbfjr.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gttlrvnucd.html

[S01] C：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtrvpcgtrc.html

#include <stdio.h>
来源：http://dali.svipenyu.cn/Article/details/gtybrrmfek.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cashguo.top/Article/details/gtuvevkzwf.html

[S02] C：变量与格式化输出
来源：http://dali.hfpthk.cn/Article/details/gtcfehpqyo.html

int a = 10; printf("%d\n", a);
来源：http://dali.tanke756.top/Article/details/gteytzzqeo.html

[S03] C：读入整数
来源：http://dali.yueranfly.top/Article/details/gtyobuduxz.html

int x; scanf("%d", &x);
来源：http://dali.dianchejie.cn/Article/details/gtwddjgiic.html

[S04] C：字符串复制
来源：http://dali.jyoumei.cn/Article/details/gtqkjgjhbc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xuanzx.com/Article/details/gtrsrqmurp.html

[S05] C：字符串长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxasxwmoi.html

strlen(s)
来源：http://dali.redwolf501.top/Article/details/gtrpkxwfbw.html

[S06] C：字符串比较
来源：http://dali.haohaochexian.top/Article/details/gtluxihtoh.html

strcmp(a, b) == 0
来源：http://dali.zhiwuduotai.top/Article/details/gtikzlkycz.html

[S07] C：数组遍历求和
来源：http://dali.0kj1m.cn/Article/details/gtwrumflwd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gtalapzoac.html

[S08] C：动态内存分配与释放
来源：http://dali.mhx1999.top/Article/details/gteeafblmd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.daxiang520.top/Article/details/gtqvpdkrww.html

[S09] C：结构体定义与初始化
来源：http://dali.haohaochexian.top/Article/details/gtkbhaklet.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jiagoushi.top/Article/details/gtmvnjitiy.html

[S10] C：指针与解引用
来源：http://dali.xziqi.cn/Article/details/gtwtokryov.html

int *p = &a;  *p = 5;
来源：http://dali.hnxiangtu.top/Article/details/gtnfcphnzk.html

[S11] C：逐行读文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpyoruizk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zdqjudy.top/Article/details/gtgpahyvec.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xziqi.cn/Article/details/gtiakcafkw.html

fclose(f);
来源：http://dali.jqgufenzy.top/Article/details/gtbkxemgvd.html

[S12] C：写文件
来源：http://dali.316326.xyz/Article/details/gtiywvqitw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.quarkkingdee.top/Article/details/gtnyywtyta.html

[S13] C：宏定义
来源：http://dali.zdqjudy.top/Article/details/gtjbchanpq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.sufxvd.cn/Article/details/gtnwjnncgc.html

[S14] C：枚举
来源：http://dali.tianlin.xyz/Article/details/gtcpuqzisw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cheryme.top/Article/details/gtwmancqax.html

[S15] C：类型转换
来源：http://dali.jinghuilouyu.cn/Article/details/gtaqrlovqy.html

(double) a / b
来源：http://dali.xuetiantiany.cn/Article/details/gtsuvwejhb.html

[S16] C：位操作置位
来源：http://dali.wangshuangyany.cn/Article/details/gtbojkubvo.html

x |= (1 << 3);
来源：http://dali.jinqigufen.top/Article/details/gtiakjdyiz.html

[S17] C：安全拼接字符串
来源：http://dali.sweek.top/Article/details/gtnbkfxvst.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hnxiangtu.top/Article/details/gtrgjtyoxz.html

[S18] C：命令行参数
来源：http://dali.hnqzz.top/Article/details/gtvyfwznlr.html

int main(int argc, char **argv)
来源：http://dali.jiagoushi.top/Article/details/gtvbgdckim.html

[S19] C：快速排序
来源：http://dali.sweek.top/Article/details/gtfpmvemmp.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ybcxt.top/Article/details/gtdaplvdbr.html

[S20] C：二分查找
来源：http://dali.daria6918.cn/Article/details/gtomoxcozd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cashguo.top/Article/details/gtxxhztfie.html

[S21] C：字符类别判断
来源：http://dali.sweek.top/Article/details/gtzzuhnirk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhoulong.xyz/Article/details/gtiwciglrx.html

[S22] C：字符串转数字
来源：http://dali.jinghuilouyu.cn/Article/details/gtbhrbwtxy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.316326.xyz/Article/details/gtjjxshxps.html

[S23] C：随机数
来源：http://dali.jqgufenzy.top/Article/details/gtjbidpkkc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.svipenyu.cn/Article/details/gtzwskekxh.html

[S24] C：获取本地时间
来源：http://dali.kuanghao11.cn/Article/details/gtexhfmxsu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.iojbl.cn/Article/details/gtciatkxho.html

[S25] C：内存拷贝
来源：http://dali.ydzc1.top/Article/details/gtqzapqqcw.html

memcpy(dst, src, n);
来源：http://dali.meibo888.top/Article/details/gtaccmdats.html

[S26] C：内存清零
来源：http://dali.jlsjyb.cn/Article/details/gtjgfwavpz.html

memset(a, 0, sizeof a);
来源：http://dali.redwolf501.top/Article/details/gtwzeqewyd.html

[S27] C：定义常量
来源：http://dali.pycfn.com/Article/details/gtqwecmvwp.html

const double PI = 3.14159;
来源：http://dali.yueranfly.top/Article/details/gtjwknqnmc.html

[S28] C：静态变量
来源：http://dali.mhx1999.top/Article/details/gtzmagbogw.html

static int counter = 0;
来源：http://dali.jqgufenzy.top/Article/details/gtzkdrndmx.html

[S29] C：变参函数
来源：http://dali.zhiwuduotai.top/Article/details/gtfgunkekd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zycfv.cn/Article/details/gthamhlspp.html

[S30] C：头文件保护
来源：http://dali.ybcxt.top/Article/details/gtbsmqzrwl.html

#ifndef X_H
来源：http://dali.0kj1m.cn/Article/details/gtsioqvzqm.html

#define X_H
来源：http://dali.guowangkeji.top/Article/details/gtqbgbunuo.html

#endif
来源：http://dali.zhixingplan.top/Article/details/gtirsiqwze.html

[S31] C++：Hello World
来源：http://dali.pycfn.com/Article/details/gtnkozfmue.html

#include <iostream>
来源：http://dali.zhixingplan.top/Article/details/gtidxbjdqg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gzhubu.top/Article/details/gtkfdpycwi.html

[S32] C++：字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtykesugck.html

std::string s = "hi";  s += "!";
来源：http://dali.jinqigufen.top/Article/details/gtjgnnpevo.html


<!-- 参考信息 -->