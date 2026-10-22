代发 wailian999

[Q65] 回滚事务
来源：http://dali.jinyuanbaomall.cn/Article/details/gtypcragwn.html

ROLLBACK;
来源：http://dali.nanxinkj.top/Article/details/gtfbwwkegn.html

[Q66] 行锁查询
来源：http://dali.hammf.cn/Article/details/gtzxtaiyjy.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hongshengwenyu.top/Article/details/gtijnfasji.html

[Q67] 设置隔离级别
来源：http://dali.dianchejie.cn/Article/details/gtgazzmteq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.meibo888.top/Article/details/gtpglmjzbh.html

[Q68] 保存点
来源：http://dali.yuanzhike.top/Article/details/gtnuwcrteb.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gtomgcbkfu.html

ROLLBACK TO sp1;
来源：http://dali.jiagoushi.top/Article/details/gtnhkvstin.html

[Q69] 查看执行计划
来源：http://dali.nwbrower.top/Article/details/gtistndrte.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cheryme.top/Article/details/gtgzipinfw.html

[Q70] 更新统计信息
来源：http://dali.jyoumei.cn/Article/details/gtyfujytid.html

ANALYZE TABLE users;
来源：http://dali.jqgfzy.top/Article/details/gtnamxluqd.html

[Q71] 查看建表语句
来源：http://dali.fengsongda.top/Article/details/gtcwqjykfc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cqqwz.cn/Article/details/gteecukein.html

[Q72] 查看索引
来源：http://dali.hammf.cn/Article/details/gtpubnbivy.html

SHOW INDEX FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtihdgerwm.html

[Q73] 查看表状态
来源：http://dali.xuetiantiany.cn/Article/details/gtstmdibyw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlnenhhbm.html

[Q74] 强制使用索引
来源：http://dali.jqgufenzy.top/Article/details/gtnsjgqlro.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.vqdsnc.cn/Article/details/gtmzkrprsz.html

[Q75] 日期格式化
来源：http://dali.snrcjt.cn/Article/details/gtfajccfwy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtaqibnork.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.pengpengdd.cyou/Article/details/gtdsjswbtl.html

[Q76] 按天统计
来源：http://dali.yanxiufei.cn/Article/details/gtlclvskea.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.pycfn.com/Article/details/gthespluln.html

[Q77] 时间加减
来源：http://dali.vqdsnc.cn/Article/details/gtvsavgojg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hnqzz.top/Article/details/gtdqfyqtws.html

[Q78] 当前时间
来源：http://dali.zhixingplan.top/Article/details/gtzuivamay.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinqigufen.top/Article/details/gtkwhfsakv.html

[Q79] 字符串拼接
来源：http://dali.nanxuanxn.top/Article/details/gthhboyadi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.c1oappe.top/Article/details/gtzhsrmcna.html

[Q80] 字符串截取
来源：http://dali.wangdashe.top/Article/details/gtfiohzhzp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gthwckzfjo.html

[Q81] 字符串替换
来源：http://dali.9152youxi.cn/Article/details/gtvawntygn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtuxpjuygi.html

[Q82] 字符长度与字节长度
来源：http://dali.daxiang520.top/Article/details/gtssiaahgt.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtbrznuorc.html

[Q83] 大小写转换
来源：http://dali.meibo888.top/Article/details/gtnkfnsspw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtuapftoar.html

[Q84] 去除首尾空格
来源：http://dali.sufxvd.cn/Article/details/gtigkcduyf.html

SELECT TRIM(name) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtfcmpgref.html

[Q85] 数值取整
来源：http://dali.redwolf501.top/Article/details/gtvhwfbhbt.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zycfv.cn/Article/details/gtveoioekk.html

[Q86] 读取 JSON 字段
来源：http://dali.xziqi.cn/Article/details/gtifqdbzvo.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.svipenyu.cn/Article/details/gtxqvkwmsm.html

[Q87] JSON 字段做条件
来源：http://dali.meibo888.top/Article/details/gtqomjnzbs.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cucudq.cn/Article/details/gtkettwotj.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhongyouzk.top/Article/details/gtehgbayld.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jiagoushi.top/Article/details/gtghbxtcqe.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtwagzvptz.html

[Q89] 判断表是否存在
来源：http://dali.0kj1m.cn/Article/details/gtxkxiiqav.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xylfe.cn/Article/details/gtmopmawir.html

[Q90] 生成序号列
来源：http://dali.meibo888.top/Article/details/gttsnxyxfv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.aizwys.cn/Article/details/gtbddbxjrb.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtketqyhmf.html

R. Bash 专题
来源：http://dali.hnqzz.top/Article/details/gttafzgffk.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtflhageom.html

[R01] shebang 与严格模式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtntycdctt.html

#!/usr/bin/env bash
来源：http://dali.ivvv.top/Article/details/gtnakoypxs.html

set -euo pipefail
来源：http://dali.iojbl.cn/Article/details/gtqmimhjni.html

[R02] 变量赋值与使用
来源：http://dali.tian-w.cn/Article/details/gtrbhvpkvc.html

name="Tom"; echo "$name"
来源：http://dali.ivvv.top/Article/details/gtepwznknj.html

[R03] 只读变量
来源：http://dali.0kj1m.cn/Article/details/gtamwocapj.html

readonly PI=3.14
来源：http://dali.cdnleiting.top/Article/details/gtyckfyefa.html

[R04] 位置参数
来源：http://dali.yongpay.top/Article/details/gtnodmwgzs.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.vqdsnc.cn/Article/details/gtiscmsmdd.html

[R05] 参数默认值
来源：http://dali.havefunace.top/Article/details/gtwclgdksb.html

name="${1:-default}"
来源：http://dali.jinqigfzy.top/Article/details/gtbwkfqgbe.html

[R06] 判断命令是否存在
来源：http://dali.aizwys.cn/Article/details/gtivhicqqa.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sufxvd.cn/Article/details/gtneyfphnm.html

[R07] if 判断文件
来源：http://dali.xylfe.cn/Article/details/gtuvfmuuml.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.mhx1999.top/Article/details/gtqsazvjdf.html

[R08] 数值比较
来源：http://dali.zdqjudy.top/Article/details/gtqjtbpamh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.smart0.xyz/Article/details/gthuguzxxw.html

[R09] 字符串比较
来源：http://dali.jianghu66.top/Article/details/gtundddfsl.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.smart0.xyz/Article/details/gttgxdqtna.html

[R10] 正则匹配
来源：http://dali.meibo888.top/Article/details/gtyopqvkgc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.9152youxi.cn/Article/details/gtcrdiyysl.html

[R11] case 多分支
来源：http://dali.c1oappe.top/Article/details/gtakxdvijr.html

case "$1" in
来源：http://dali.hfpthk.cn/Article/details/gtocfunqhm.html

start) echo "启动" ;;
来源：http://dali.gogol.net.cn/Article/details/gttuycinxd.html

stop)  echo "停止" ;;
来源：http://dali.jlsjyb.cn/Article/details/gtzfcdvwqj.html

*)     echo "未知命令" ;;
来源：http://dali.jlsjyb.cn/Article/details/gtkhxwjyvh.html

esac
来源：http://dali.sweek.top/Article/details/gtodkxzazx.html

[R12] for 遍历文件
来源：http://dali.daria6918.cn/Article/details/gtlllgnqgr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yuxming.cn/Article/details/gtpjagruuh.html

[R13] for 计数循环
来源：http://dali.zhoulong.xyz/Article/details/gtvyogiurp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sxryk.cn/Article/details/gtgfedhmbz.html

[R14] C 风格 for
来源：http://dali.tanke756.top/Article/details/gtrtromvru.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shuidangran.top/Article/details/gtyxogmivn.html

[R15] while 逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gtonyiwobb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.redwolf501.top/Article/details/gtjmzehrew.html

[R16] until 等待条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgpdhmxpy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhengqikj.top/Article/details/gtillcekmt.html

[R17] 数组定义与取值
来源：http://dali.gzhubu.top/Article/details/gtwdxcnwka.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.chenlongwang.top/Article/details/gtlncczxxj.html

[R18] 遍历数组
来源：http://dali.aizwys.cn/Article/details/gtmuhfubby.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sufxvd.cn/Article/details/gtnfjptrxx.html

[R19] 数组长度
来源：http://dali.jianghu66.top/Article/details/gtmghsfpbp.html

echo "${#arr[@]}"
来源：http://dali.hongshengwenyu.top/Article/details/gtzvdrqihw.html

[R20] 关联数组（字典）
来源：http://dali.hammf.cn/Article/details/gtcwacldsz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.316326.xyz/Article/details/gtyhugjvkm.html

[R21] 字符串长度
来源：http://dali.yueranfly.top/Article/details/gtnbybvefo.html

echo "${#s}"
来源：http://dali.ppjwa.cn/Article/details/gtyblebzhg.html

[R22] 截取子串
来源：http://dali.meibo888.top/Article/details/gtqryuqpej.html

echo "${s:0:5}"
来源：http://dali.snrcjt.cn/Article/details/gtjnfwvwev.html

[R23] 字符串替换
来源：http://dali.xylfe.cn/Article/details/gtqeafisou.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.vqdsnc.cn/Article/details/gttkicowlk.html

[R24] 大小写转换
来源：http://dali.c1oappe.top/Article/details/gtqmrbybwr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sufxvd.cn/Article/details/gtbcpgsdsj.html

[R25] 去后缀 / 去前缀
来源：http://dali.pycfn.com/Article/details/gtbdrugznr.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jqgufenzy.top/Article/details/gtblszvdyg.html

[R26] 命令替换
来源：http://dali.yanxiufei.cn/Article/details/gtwkotzegu.html

now=$(date +%F); echo "$now"
来源：http://dali.sweek.top/Article/details/gtazpqyxvb.html

[R27] 算术展开
来源：http://dali.yj20258.top/Article/details/gtirdhehui.html

echo $((1 + 2 * 3))
来源：http://dali.yj20258.top/Article/details/gtrblwvvuz.html

[R28] 浮点运算
来源：http://dali.shangyingyoupin.top/Article/details/gtgpibivuu.html

echo "scale=2; 10/3" | bc
来源：http://dali.zdqjudy.top/Article/details/gtqycyvowl.html

[R29] 定义函数
来源：http://dali.ppjwa.cn/Article/details/gtnrifqnci.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhongyouzk.top/Article/details/gtznuxhuoh.html

[R30] 函数返回状态码
来源：http://dali.redwolf501.top/Article/details/gtrekhggnl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hammf.cn/Article/details/gtqeyrsnrm.html

[R31] 局部变量
来源：http://dali.tian-w.cn/Article/details/gtduexeqem.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhengqikj.top/Article/details/gtzqqedovw.html

[R32] 参数个数校验
来源：http://dali.gzhubu.top/Article/details/gtqsrnfqnu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cqqwz.cn/Article/details/gtzxaasbhg.html

[R33] 捕获错误并提示行号
来源：http://dali.tanke756.top/Article/details/gthcalxcqh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cheryme.top/Article/details/gtjrazlwfw.html

[R34] 退出时清理
来源：http://dali.wangshuangyany.cn/Article/details/gtdemlheeq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgfzy.top/Article/details/gtsauonbbw.html

[R35] 后台执行并等待
来源：http://dali.pengpengdd.cyou/Article/details/gtophwpydq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhiwuduotai.top/Article/details/gtgvxoohok.html

[R36] 并发执行多个任务
来源：http://dali.xuetiantiany.cn/Article/details/gtzdtvcout.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hnxiangtu.top/Article/details/gtvmeoaqfr.html

[R37] 把输出赋给变量
来源：http://dali.aibaodan.cn/Article/details/gtuxabxsgx.html

files=$(ls -1)
来源：http://dali.zycfv.cn/Article/details/gtkhzgcgyn.html

[R38] 管道串联
来源：http://dali.wangdashe.top/Article/details/gtgrvugiie.html

cat a.txt | grep -i error | wc -l
来源：http://dali.chenzaomai.com/Article/details/gtrntxrdsz.html

[R39] 重定向标准输出与错误
来源：http://dali.jinghuilouyu.cn/Article/details/gtwtxesxrk.html

cmd > out.log 2>&1
来源：http://dali.hnqzz.top/Article/details/gtigylkbwt.html

[R40] 追加写日志
来源：http://dali.jinghuilouyu.cn/Article/details/gtpqhukhmu.html

echo "log" >> out.log
来源：http://dali.nwbrower.top/Article/details/gtvkzlrcse.html

[R41] 丢弃输出
来源：http://dali.haohaochexian.top/Article/details/gtfxrqbddt.html

cmd >/dev/null 2>&1
来源：http://dali.daxiang520.top/Article/details/gtihijeyfl.html

[R42] 输入重定向
来源：http://dali.gotoacloud.top/Article/details/gtramdcfur.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gttxjrenad.html

[R43] 按名字查找文件
来源：http://dali.shangyingyoupin.top/Article/details/gthijelvoo.html

find . -name "*.log" -type f
来源：http://dali.9152youxi.cn/Article/details/gtaotiwxxo.html

[R44] 按修改时间查找
来源：http://dali.jlsjyb.cn/Article/details/gtmsxgyezh.html

find . -mtime -7 -type f
来源：http://dali.zhaomingkeji.xyz/Article/details/gtedvhzyts.html

[R45] 批量删除
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmbtobfmn.html

find . -name "*.tmp" -delete
来源：http://dali.yonumen.top/Article/details/gtxwlyqzzv.html

[R46] 递归替换文件内容
来源：http://dali.kuanghao11.cn/Article/details/gtyqcfeosc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.mhx1999.top/Article/details/gtbtoooyiy.html

[R47] sed 单行替换
来源：http://dali.sxryk.cn/Article/details/gtmqjhubxa.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.nwbrower.top/Article/details/gtzggmsewe.html

[R48] awk 取指定列
来源：http://dali.aibaodan.cn/Article/details/gtrqnhqree.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhongyouzk.top/Article/details/gtlnnpyedi.html

[R49] awk 带条件
来源：http://dali.jinghuilouyu.cn/Article/details/gtfrocwlgj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hnqzz.top/Article/details/gtqcwbxeme.html

[R50] awk 求和
来源：http://dali.guannengcc.top/Article/details/gtumntfgog.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtdiyyfxtx.html

[R51] 排序去重取前几
来源：http://dali.ybcxt.top/Article/details/gtyzlvjmbt.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zycfv.cn/Article/details/gtvbirpsos.html

[R52] 统计行数
来源：http://dali.ppjwa.cn/Article/details/gtzfcdapvk.html

wc -l a.txt
来源：http://dali.yangfankeji.com/Article/details/gtykjkrfyh.html

[R53] 查看文件头与实时尾
来源：http://dali.cheryme.top/Article/details/gtzaqconra.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jlsjyb.cn/Article/details/gtmvxpynam.html

[R54] 比较两个文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsruqvxca.html

diff a.txt b.txt
来源：http://dali.cheryme.top/Article/details/gtgrmwoaka.html

[R55] 压缩与解压
来源：http://dali.hysaishi.cn/Article/details/gtmevtfpjh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.havefunace.top/Article/details/gtrryasyrt.html

[R56] 远程拷贝
来源：http://dali.sxryk.cn/Article/details/gtscufhxzq.html

scp file user@host:/path/
来源：http://dali.guowangkeji.top/Article/details/gtbqmwehah.html

[R57] 远程执行命令
来源：http://dali.jiagoushi.top/Article/details/gtlzgwnctv.html

ssh user@host 'uptime'
来源：http://dali.chenlongwang.top/Article/details/gtfedpzmdf.html

[R58] 下载文件
来源：http://dali.quarkkingdee.top/Article/details/gtmbmplwcd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shzxlz.cn/Article/details/gtvmxomgjg.html

[R59] 发 POST JSON
来源：http://dali.ppjwa.cn/Article/details/gtqgoyjrzh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yonumen.top/Article/details/gthfonbeqb.html

[R60] 只看 HTTP 状态码
来源：http://dali.cucudq.cn/Article/details/gtharifbtd.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yuxming.cn/Article/details/gtpkaemdqh.html

[R61] 磁盘占用
来源：http://dali.tian-w.cn/Article/details/gtajbunhqk.html

df -h;  du -sh *
来源：http://dali.nanxinkj.top/Article/details/gtvmmybvts.html

[R62] 找最占空间的文件
来源：http://dali.havefunace.top/Article/details/gtcimhprqw.html

du -ah . | sort -rh | head -10
来源：http://dali.gotoacloud.top/Article/details/gtdyqegror.html

[R63] 内存与进程
来源：http://dali.yvedp.cn/Article/details/gtlnrmbpzz.html

free -h;  ps aux | grep nginx
来源：http://dali.jianghu66.top/Article/details/gteebhcnpr.html

[R64] 结束进程
来源：http://dali.shanyushiyangkeji.top/Article/details/gtclnybtns.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yangfankeji.com/Article/details/gtlgyhfmsq.html

[R65] 查看端口占用
来源：http://dali.hywenlv.cn/Article/details/gtvljnjcib.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.c1oappe.top/Article/details/gtoaipmjyd.html

[R66] 定时任务
来源：http://dali.quarkkingdee.top/Article/details/gtdwmldkbm.html

crontab -e;  crontab -l
来源：http://dali.wangshuangyany.cn/Article/details/gtezfohdau.html

[R67] 生成随机十六进制串
来源：http://dali.jinqigfzy.top/Article/details/gtdwbnvmrg.html

openssl rand -hex 16
来源：http://dali.smart0.xyz/Article/details/gtrtxsgyro.html

[R68] 计算文件校验值
来源：http://dali.yj20258.top/Article/details/gtjzosyssa.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ppjwa.cn/Article/details/gtxjiyklvr.html

[R69] 生成随机密码
来源：http://dali.jlsjyb.cn/Article/details/gtqddjwxja.html

head -c 16 /dev/urandom | base64
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwdpufxfc.html

[R70] 时间戳与互转
来源：http://dali.birdmap.top/Article/details/gtkniqxogv.html

date +%s;  date -d @1700000000
来源：http://dali.ydzc1.top/Article/details/gtuacxjdii.html

[R71] 日期格式化
来源：http://dali.mhx1999.top/Article/details/gtqpsqmkvt.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yuxming.cn/Article/details/gteskomcov.html

[R72] 等待端口就绪
来源：http://dali.jianghu66.top/Article/details/gtityygrxz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xylfe.cn/Article/details/gtziyupjor.html

[R73] 分割大日志
来源：http://dali.gaohongyu789.top/Article/details/gtzgveqvai.html

split -l 1000 big.log part_
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqxpulyyf.html

[R74] 批量重命名
来源：http://dali.redwolf501.top/Article/details/gthcrlsfxp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.fengsongda.top/Article/details/gtdpoellvl.html

[R75] 导出环境变量
来源：http://dali.hongshengwenyu.top/Article/details/gtutdvwuzm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.fengsongda.top/Article/details/gtuscxqvwo.html

[R76] 使用临时文件
来源：http://dali.iojbl.cn/Article/details/gtxvbexspw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ydzc1.top/Article/details/gtrapftyml.html

[R77] 读取用户输入
来源：http://dali.jyoumei.cn/Article/details/gtarjawqvt.html

read -rp "请输入: " ans
来源：http://dali.mhx1999.top/Article/details/gtheuwieas.html

[R78] 交互式菜单
来源：http://dali.jiagoushi.top/Article/details/gtolvfgaci.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhoulong.xyz/Article/details/gtgiryrkqt.html

[R79] 解析命令行选项
来源：http://dali.yvedp.cn/Article/details/gtcozcpepc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ybcxt.top/Article/details/gtfvwzifdj.html

[R80] 查看脚本执行耗时
来源：http://dali.gotoacloud.top/Article/details/gtzoinlzkl.html

time ./run.sh
来源：http://dali.chenzaomai.com/Article/details/gtpwawnmld.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtlhwvaxiw.html

S. C / C++ 专题
来源：http://dali.smart0.xyz/Article/details/gtayczfbwf.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtppzmqrsb.html

[S01] C：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtzzmnwron.html

#include <stdio.h>
来源：http://dali.cqqwz.cn/Article/details/gtdozulowa.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.sysykeji.top/Article/details/gtprvknkst.html

[S02] C：变量与格式化输出
来源：http://dali.yj20258.top/Article/details/gtahezqhgn.html

int a = 10; printf("%d\n", a);
来源：http://dali.ehwqpu.com/Article/details/gtrlblbxjv.html

[S03] C：读入整数
来源：http://dali.yuanzhike.top/Article/details/gtzbwozdvg.html

int x; scanf("%d", &x);
来源：http://dali.xylfe.cn/Article/details/gtsqjtfaus.html

[S04] C：字符串复制
来源：http://dali.xinyue.icu/Article/details/gtyyomiqei.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gtnreglodf.html

[S05] C：字符串长度
来源：http://dali.chenjidiqi.icu/Article/details/gtldqoldqo.html

strlen(s)
来源：http://dali.aizwys.cn/Article/details/gtmgvoalpb.html

[S06] C：字符串比较
来源：http://dali.chenzaomai.com/Article/details/gtrnudfhmw.html

strcmp(a, b) == 0
来源：http://dali.jyoumei.cn/Article/details/gtnzxwxfgy.html

[S07] C：数组遍历求和
来源：http://dali.hysaishi.cn/Article/details/gtessbknqt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jinqigufen.top/Article/details/gtsvppgnns.html

[S08] C：动态内存分配与释放
来源：http://dali.chenzaomai.com/Article/details/gtolmqvcyb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xuetiantiany.cn/Article/details/gtnpzromht.html

[S09] C：结构体定义与初始化
来源：http://dali.hysaishi.cn/Article/details/gtvkopfwbb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.fengsongda.top/Article/details/gttsplscgn.html

[S10] C：指针与解引用
来源：http://dali.hnqzz.top/Article/details/gtzrlcterj.html

int *p = &a;  *p = 5;
来源：http://dali.cdnleiting.top/Article/details/gttpaxeiga.html

[S11] C：逐行读文件
来源：http://dali.yuanzhike.top/Article/details/gtxoykovqx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxohwhzyy.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yj20258.top/Article/details/gtnfvzurzg.html

fclose(f);
来源：http://dali.xziqi.cn/Article/details/gtmyseuztl.html

[S12] C：写文件
来源：http://dali.aizwys.cn/Article/details/gtsuyzrefp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xuanzx.com/Article/details/gtwqzolkag.html

[S13] C：宏定义
来源：http://dali.yueranfly.top/Article/details/gtlzxmeeoz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yongpay.top/Article/details/gtamdnehri.html

[S14] C：枚举
来源：http://dali.ppjwa.cn/Article/details/gtoeirouzh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jyoumei.cn/Article/details/gtmxupvpgu.html

[S15] C：类型转换
来源：http://dali.9152youxi.cn/Article/details/gtemfijdfr.html

(double) a / b
来源：http://dali.cheryme.top/Article/details/gtsximujis.html

[S16] C：位操作置位
来源：http://dali.c1oappe.top/Article/details/gtwzuvnffz.html

x |= (1 << 3);
来源：http://dali.aizwys.cn/Article/details/gttbadmglw.html

[S17] C：安全拼接字符串
来源：http://dali.ydzc1.top/Article/details/gtepnhyabp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.dianchejie.cn/Article/details/gtxmcpnpgw.html

[S18] C：命令行参数
来源：http://dali.sufxvd.cn/Article/details/gtcwshqarh.html

int main(int argc, char **argv)
来源：http://dali.cqqwz.cn/Article/details/gtcppzonxt.html

[S19] C：快速排序
来源：http://dali.dianchejie.cn/Article/details/gtylejxhhk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shzxlz.cn/Article/details/gtlnkausey.html

[S20] C：二分查找
来源：http://dali.ppjwa.cn/Article/details/gtrtgptaca.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinyuanbaomall.cn/Article/details/gthascybau.html

[S21] C：字符类别判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjpwlvxle.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhiwuduotai.top/Article/details/gtmjcaupjg.html

[S22] C：字符串转数字
来源：http://dali.sysykeji.top/Article/details/gteqhvrwyq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gtmykueoev.html

[S23] C：随机数
来源：http://dali.mhx1999.top/Article/details/gtsrdyuujj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cheryme.top/Article/details/gtywzhvedd.html

[S24] C：获取本地时间
来源：http://dali.vqdsnc.cn/Article/details/gtwubfkfmh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.chenlongwang.top/Article/details/gtvmvfyoma.html

[S25] C：内存拷贝
来源：http://dali.guannengcc.top/Article/details/gtsucczcrd.html

memcpy(dst, src, n);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzzpxdayc.html

[S26] C：内存清零
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmqefdxjk.html

memset(a, 0, sizeof a);
来源：http://dali.jqgufenzy.top/Article/details/gtngambpgj.html

[S27] C：定义常量
来源：http://dali.dashuyun.cn/Article/details/gttjoaxadp.html

const double PI = 3.14159;
来源：http://dali.ybcxt.top/Article/details/gtvngneypg.html

[S28] C：静态变量
来源：http://dali.cashguo.top/Article/details/gtpwpfrejn.html

static int counter = 0;
来源：http://dali.0kj1m.cn/Article/details/gttclcslvz.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gtshgczwuw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.aizwys.cn/Article/details/gtdtcfvpgk.html

[S30] C：头文件保护
来源：http://dali.xziqi.cn/Article/details/gtunfzskcp.html

#ifndef X_H
来源：http://dali.zhixingplan.top/Article/details/gtnglxbwoq.html

#define X_H
来源：http://dali.cdnleiting.top/Article/details/gthxczkfkv.html

#endif
来源：http://dali.zdqjudy.top/Article/details/gtddprznhq.html

[S31] C++：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtendomlrl.html

#include <iostream>
来源：http://dali.cucudq.cn/Article/details/gtrnbuhjdd.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.aizwys.cn/Article/details/gtxwwebosv.html

[S32] C++：字符串
来源：http://dali.xziqi.cn/Article/details/gtsssktmfh.html

std::string s = "hi";  s += "!";
来源：http://dali.wangshuangyany.cn/Article/details/gthdnfiosd.html

[S33] C++：vector 增删
来源：http://dali.kuanghao11.cn/Article/details/gtznzjwgqb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.pycfn.com/Article/details/gtjbqftwsm.html

[S34] C++：遍历 vector
来源：http://dali.guowangkeji.top/Article/details/gtjzrsehoa.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yvedp.cn/Article/details/gtbfpgxffq.html


<!-- 参考信息 -->