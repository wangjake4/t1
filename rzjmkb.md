代发 wailian999

ROLLBACK TO sp1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqnntvvie.html

[Q69] 查看执行计划
来源：http://dali.dashuyun.cn/Article/details/gtrglhljkn.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.mhx1999.top/Article/details/gtcqihfium.html

[Q70] 更新统计信息
来源：http://dali.quarkkingdee.top/Article/details/gtiwwyacqk.html

ANALYZE TABLE users;
来源：http://dali.jlsjyb.cn/Article/details/gtennfjkmv.html

[Q71] 查看建表语句
来源：http://dali.hfpthk.cn/Article/details/gtkpgzapkp.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shanyushiyangtech.top/Article/details/gtwbalhiik.html

[Q72] 查看索引
来源：http://dali.sxryk.cn/Article/details/gtszvatnix.html

SHOW INDEX FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtrwomggmx.html

[Q73] 查看表状态
来源：http://dali.yangfankeji.com/Article/details/gtfibjfexm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shanyushiyangtech.top/Article/details/gtxjtkidqr.html

[Q74] 强制使用索引
来源：http://dali.jyoumei.cn/Article/details/gtxsblcfnr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.dianchejie.cn/Article/details/gttblznowr.html

[Q75] 日期格式化
来源：http://dali.shanyushiyangtech.top/Article/details/gtmeejusdo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hnqzz.top/Article/details/gtybygltbi.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.aibaodan.cn/Article/details/gtehshmyhu.html

[Q76] 按天统计
来源：http://dali.gzhubu.top/Article/details/gtxnuyrcuy.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.daria6918.cn/Article/details/gtpvcrxspx.html

[Q77] 时间加减
来源：http://dali.fengsongda.top/Article/details/gtpnxugvmh.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zycfv.cn/Article/details/gtuzynzsrw.html

[Q78] 当前时间
来源：http://dali.cqqwz.cn/Article/details/gtdlrkhtlp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.9152youxi.cn/Article/details/gtsmujzvjg.html

[Q79] 字符串拼接
来源：http://dali.yuxming.cn/Article/details/gtgkjavdrw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhongyouzk.top/Article/details/gtrksxvuyg.html

[Q80] 字符串截取
来源：http://dali.shanyushiyangkeji.top/Article/details/gtskpdyupt.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtfzjkjjcf.html

[Q81] 字符串替换
来源：http://dali.yuanzhike.top/Article/details/gtopgiqwjb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtnxelfvmh.html

[Q82] 字符长度与字节长度
来源：http://dali.ppjwa.cn/Article/details/gtukkzoctc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.smart0.xyz/Article/details/gthcoexywf.html

[Q83] 大小写转换
来源：http://dali.aizwys.cn/Article/details/gtgpxrtnaq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gttasotukh.html

[Q84] 去除首尾空格
来源：http://dali.jinqigfzy.top/Article/details/gthbrgcunk.html

SELECT TRIM(name) FROM users;
来源：http://dali.yuxming.cn/Article/details/gtzrrybqnz.html

[Q85] 数值取整
来源：http://dali.ybcxt.top/Article/details/gtuazobzqm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.redwolf501.top/Article/details/gtzfuzhulm.html

[Q86] 读取 JSON 字段
来源：http://dali.nanxuanxn.top/Article/details/gtjhlxkaye.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.pengpengdd.cyou/Article/details/gtaebxdujq.html

[Q87] JSON 字段做条件
来源：http://dali.9152youxi.cn/Article/details/gtvqsfidcw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ivvv.top/Article/details/gtordcwqji.html

[Q88] 行转列（条件聚合）
来源：http://dali.shuidangran.top/Article/details/gthettsifs.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.havefunace.top/Article/details/gtjfteqvus.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtdxvibjkf.html

[Q89] 判断表是否存在
来源：http://dali.sysykeji.top/Article/details/gthtthjpbj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yj20258.top/Article/details/gtwgfawila.html

[Q90] 生成序号列
来源：http://dali.fengsongda.top/Article/details/gtvjnikojc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xinyue.icu/Article/details/gtbpqqjeeh.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzuzezsrr.html

R. Bash 专题
来源：http://dali.jlsjyb.cn/Article/details/gtrongyomg.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtpsegsluk.html

[R01] shebang 与严格模式
来源：http://dali.gogol.net.cn/Article/details/gthnicuctx.html

#!/usr/bin/env bash
来源：http://dali.yueranfly.top/Article/details/gtbowlfsaz.html

set -euo pipefail
来源：http://dali.yj202588.top/Article/details/gtklmhdbgq.html

[R02] 变量赋值与使用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnlqdyzds.html

name="Tom"; echo "$name"
来源：http://dali.bjfxy.top/Article/details/gtpmynzmbr.html

[R03] 只读变量
来源：http://dali.daria6918.cn/Article/details/gtuaeoaoqn.html

readonly PI=3.14
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvbbpczxc.html

[R04] 位置参数
来源：http://dali.shzxlz.cn/Article/details/gtemsenxaa.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.fengsongda.top/Article/details/gtiyqxojdu.html

[R05] 参数默认值
来源：http://dali.ppjwa.cn/Article/details/gtgowmgaxx.html

name="${1:-default}"
来源：http://dali.pengpengdd.cyou/Article/details/gtjatknbcr.html

[R06] 判断命令是否存在
来源：http://dali.ivvv.top/Article/details/gtdbastmpx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hysaishi.cn/Article/details/gtkwzdgqnh.html

[R07] if 判断文件
来源：http://dali.xinyue.icu/Article/details/gtcittarnt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinqigfzy.top/Article/details/gtpztojhue.html

[R08] 数值比较
来源：http://dali.gzhubu.top/Article/details/gtdimuinis.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.nanxinkj.top/Article/details/gteefoqkjj.html

[R09] 字符串比较
来源：http://dali.hywenlv.cn/Article/details/gtnfgkovpv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xinyue.icu/Article/details/gtqqvexcgd.html

[R10] 正则匹配
来源：http://dali.9152youxi.cn/Article/details/gthbvpzrea.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zycfv.cn/Article/details/gtzmmwoyeq.html

[R11] case 多分支
来源：http://dali.nanxinkj.top/Article/details/gtpyvxfhby.html

case "$1" in
来源：http://dali.aizwys.cn/Article/details/gtpphsjmty.html

start) echo "启动" ;;
来源：http://dali.c1oappe.top/Article/details/gtnrvsynxt.html

stop)  echo "停止" ;;
来源：http://dali.ehwqpu.com/Article/details/gtkkgaqoyh.html

*)     echo "未知命令" ;;
来源：http://dali.tianlin.xyz/Article/details/gtlliblwxn.html

esac
来源：http://dali.wangshuangyany.cn/Article/details/gtrtftxqko.html

[R12] for 遍历文件
来源：http://dali.feifeiyinyue.top/Article/details/gtbisppiwe.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gogol.net.cn/Article/details/gtnudmhwqq.html

[R13] for 计数循环
来源：http://dali.jianghu66.top/Article/details/gtgiprjrqw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.bjfxy.top/Article/details/gtqxjwujci.html

[R14] C 风格 for
来源：http://dali.zdqjudy.top/Article/details/gtpyydafiu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.chenjidiqi.icu/Article/details/gtjdmlyvxc.html

[R15] while 逐行读文件
来源：http://dali.cucudq.cn/Article/details/gtwbmtmjfz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.fzhhl.top/Article/details/gtwtourlbo.html

[R16] until 等待条件
来源：http://dali.jlsjyb.cn/Article/details/gthcwaehfp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.quarkkingdee.top/Article/details/gtsytnhshh.html

[R17] 数组定义与取值
来源：http://dali.iojbl.cn/Article/details/gtcepjdpah.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ybcxt.top/Article/details/gtuwedszlg.html

[R18] 遍历数组
来源：http://dali.yonumen.top/Article/details/gtyxxhmmjz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.nanxuanxn.top/Article/details/gtjmgodpth.html

[R19] 数组长度
来源：http://dali.sxryk.cn/Article/details/gtlzhledak.html

echo "${#arr[@]}"
来源：http://dali.redwolf501.top/Article/details/gtxhhpdylh.html

[R20] 关联数组（字典）
来源：http://dali.ehwqpu.com/Article/details/gtvwqgrazr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.nanxinkj.top/Article/details/gtvkbvjbqb.html

[R21] 字符串长度
来源：http://dali.zycfv.cn/Article/details/gtzelvgcwl.html

echo "${#s}"
来源：http://dali.mhx1999.top/Article/details/gtwsdpkhsy.html

[R22] 截取子串
来源：http://dali.hongshengwenyu.top/Article/details/gtjmgzcfka.html

echo "${s:0:5}"
来源：http://dali.yuanzhike.top/Article/details/gtposfjiiu.html

[R23] 字符串替换
来源：http://dali.hysaishi.cn/Article/details/gtzlkffkat.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yanxiufei.cn/Article/details/gtsjdscrys.html

[R24] 大小写转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrztdylpe.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.gotoacloud.top/Article/details/gtrgsmsjwm.html

[R25] 去后缀 / 去前缀
来源：http://dali.jianghu66.top/Article/details/gttwvjbhkz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xuetiantiany.cn/Article/details/gtctcznynb.html

[R26] 命令替换
来源：http://dali.guowangkeji.top/Article/details/gtegyeelcg.html

now=$(date +%F); echo "$now"
来源：http://dali.jiagoushi.top/Article/details/gtfhlitpyv.html

[R27] 算术展开
来源：http://dali.shanyushiyangtech.top/Article/details/gtavxfbfdl.html

echo $((1 + 2 * 3))
来源：http://dali.tanke756.top/Article/details/gtfxcihdso.html

[R28] 浮点运算
来源：http://dali.0kj1m.cn/Article/details/gtewzutlzc.html

echo "scale=2; 10/3" | bc
来源：http://dali.feifeiyinyue.top/Article/details/gtzakhlvtk.html

[R29] 定义函数
来源：http://dali.zdqjudy.top/Article/details/gtsqxlqrff.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.guowangkeji.top/Article/details/gtabfuexjy.html

[R30] 函数返回状态码
来源：http://dali.jqgufenzy.top/Article/details/gtzcjhhksz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.dashuyun.cn/Article/details/gtcbrkbfhg.html

[R31] 局部变量
来源：http://dali.wangdashe.top/Article/details/gtvgtvuzdh.html

f() { local x=1; echo "$x"; }
来源：http://dali.yj20258888.top/Article/details/gtiezvbgvj.html

[R32] 参数个数校验
来源：http://dali.sweek.top/Article/details/gtyftzkmcp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yangfankeji.com/Article/details/gtlhmyrrol.html

[R33] 捕获错误并提示行号
来源：http://dali.xuetiantiany.cn/Article/details/gtxiwtwqod.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.vqdsnc.cn/Article/details/gtzxfpefgm.html

[R34] 退出时清理
来源：http://dali.aibaodan.cn/Article/details/gtsspzjhjl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.gzhubu.top/Article/details/gtzrxekmxc.html

[R35] 后台执行并等待
来源：http://dali.shangyingyoupin.top/Article/details/gtricjisbq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.guowangkeji.top/Article/details/gtffavedbm.html

[R36] 并发执行多个任务
来源：http://dali.cucudq.cn/Article/details/gtveqrjcob.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.fzhhl.top/Article/details/gtfdedzkun.html

[R37] 把输出赋给变量
来源：http://dali.ydzc1.top/Article/details/gtekagorhp.html

files=$(ls -1)
来源：http://dali.jianghu66.top/Article/details/gtmyfcedyh.html

[R38] 管道串联
来源：http://dali.ywan-chungtsiang.top/Article/details/gthzupvobk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrdqbcsqx.html

[R39] 重定向标准输出与错误
来源：http://dali.daxiang520.top/Article/details/gtxtxkphzr.html

cmd > out.log 2>&1
来源：http://dali.chenzaomai.com/Article/details/gtjuvfngsr.html

[R40] 追加写日志
来源：http://dali.mhx1999.top/Article/details/gtjzlvcrqg.html

echo "log" >> out.log
来源：http://dali.hammf.cn/Article/details/gtvuaotfyq.html

[R41] 丢弃输出
来源：http://dali.smart0.xyz/Article/details/gtcfyljuas.html

cmd >/dev/null 2>&1
来源：http://dali.fzhhl.top/Article/details/gtrkteaomr.html

[R42] 输入重定向
来源：http://dali.xinyue.icu/Article/details/gtruabrvbb.html

wc -l < a.txt
来源：http://dali.0kj1m.cn/Article/details/gttmhrsdia.html

[R43] 按名字查找文件
来源：http://dali.andypj.xyz/Article/details/gtrzpapvrr.html

find . -name "*.log" -type f
来源：http://dali.cqqwz.cn/Article/details/gtnnlttiex.html

[R44] 按修改时间查找
来源：http://dali.jlsjyb.cn/Article/details/gtelqluaer.html

find . -mtime -7 -type f
来源：http://dali.cashguo.top/Article/details/gtppkwfujb.html

[R45] 批量删除
来源：http://dali.cheryme.top/Article/details/gtakmioqpq.html

find . -name "*.tmp" -delete
来源：http://dali.jiagoushi.top/Article/details/gtrpvmuytk.html

[R46] 递归替换文件内容
来源：http://dali.yj202588.top/Article/details/gtkmcfradk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cqqwz.cn/Article/details/gtosptuies.html

[R47] sed 单行替换
来源：http://dali.nanxuanxn.top/Article/details/gtgproizba.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yueranfly.top/Article/details/gtygojcnjj.html

[R48] awk 取指定列
来源：http://dali.ivvv.top/Article/details/gthailfuac.html

awk '{print $1, $3}' a.txt
来源：http://dali.smart0.xyz/Article/details/gtnrjzkgxj.html

[R49] awk 带条件
来源：http://dali.zhongyouzk.top/Article/details/gtmwaaicqm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yuxming.cn/Article/details/gtaxbjuhwi.html

[R50] awk 求和
来源：http://dali.smart0.xyz/Article/details/gtvfgsbbxt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.pycfn.com/Article/details/gtnjoaxanb.html

[R51] 排序去重取前几
来源：http://dali.wangshuangyany.cn/Article/details/gtwskaozrk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.fzhhl.top/Article/details/gtbvimhlaw.html

[R52] 统计行数
来源：http://dali.wangdashe.top/Article/details/gtwuneqqjp.html

wc -l a.txt
来源：http://dali.cheryme.top/Article/details/gtodsvzbxk.html

[R53] 查看文件头与实时尾
来源：http://dali.dianchejie.cn/Article/details/gtqvzpxygf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.haohaochexian.top/Article/details/gtnjiqtsgr.html

[R54] 比较两个文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtvecmrayz.html

diff a.txt b.txt
来源：http://dali.ydzc1.top/Article/details/gtqxdpfomc.html

[R55] 压缩与解压
来源：http://dali.yuxming.cn/Article/details/gtdwlhoosi.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.tianlin.xyz/Article/details/gtzwmdclgq.html

[R56] 远程拷贝
来源：http://dali.xuanzx.com/Article/details/gtowibxgam.html

scp file user@host:/path/
来源：http://dali.cdnleiting.top/Article/details/gtjtzyveuc.html

[R57] 远程执行命令
来源：http://dali.shanyushiyangtech.top/Article/details/gtxgdhlsrm.html

ssh user@host 'uptime'
来源：http://dali.mhx1999.top/Article/details/gtuzstwdcl.html

[R58] 下载文件
来源：http://dali.ivvv.top/Article/details/gtlzstkcbk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ppjwa.cn/Article/details/gtwpkjontw.html

[R59] 发 POST JSON
来源：http://dali.jlsjyb.cn/Article/details/gtwhdrmlid.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.nwbrower.top/Article/details/gtkhmdlidt.html

[R60] 只看 HTTP 状态码
来源：http://dali.gzhubu.top/Article/details/gtaxwbmdxr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shuidangran.top/Article/details/gtqodbucbu.html

[R61] 磁盘占用
来源：http://dali.vqdsnc.cn/Article/details/gtyeerzinn.html

df -h;  du -sh *
来源：http://dali.yanxiufei.cn/Article/details/gtjzwoclcw.html

[R62] 找最占空间的文件
来源：http://dali.daxiang520.top/Article/details/gtqjqlrobk.html

du -ah . | sort -rh | head -10
来源：http://dali.gzhubu.top/Article/details/gtlokldebo.html

[R63] 内存与进程
来源：http://dali.birdmap.top/Article/details/gtxrggjnec.html

free -h;  ps aux | grep nginx
来源：http://dali.aibaodan.cn/Article/details/gthgiwkbfr.html

[R64] 结束进程
来源：http://dali.shanyushiyangkeji.top/Article/details/gtexuucxbw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.chenzaomai.com/Article/details/gtjyiklpre.html

[R65] 查看端口占用
来源：http://dali.yonumen.top/Article/details/gtzffrcalz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.nanxuanxn.top/Article/details/gtmzzoovne.html

[R66] 定时任务
来源：http://dali.xuanzx.com/Article/details/gtwiliybgn.html

crontab -e;  crontab -l
来源：http://dali.aibaodan.cn/Article/details/gtfhwpnnks.html

[R67] 生成随机十六进制串
来源：http://dali.gotoacloud.top/Article/details/gttjievbpl.html

openssl rand -hex 16
来源：http://dali.hnqzz.top/Article/details/gtpjbeomqh.html

[R68] 计算文件校验值
来源：http://dali.nwbrower.top/Article/details/gtrtceweyd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sweek.top/Article/details/gtuyooicdd.html

[R69] 生成随机密码
来源：http://dali.dashuyun.cn/Article/details/gtjmvaixks.html

head -c 16 /dev/urandom | base64
来源：http://dali.jinqigufen.top/Article/details/gtqpssynfv.html

[R70] 时间戳与互转
来源：http://dali.dashuyun.cn/Article/details/gtcdyfqiio.html

date +%s;  date -d @1700000000
来源：http://dali.yangfankeji.com/Article/details/gtradszgdc.html

[R71] 日期格式化
来源：http://dali.sxryk.cn/Article/details/gthgcrzebj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.dashuyun.cn/Article/details/gttkyhytuc.html

[R72] 等待端口就绪
来源：http://dali.yj20258.top/Article/details/gtlwxyfuum.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtguzttvwd.html

[R73] 分割大日志
来源：http://dali.shanyushiyangtech.top/Article/details/gtzttwycpr.html

split -l 1000 big.log part_
来源：http://dali.kuanghao11.cn/Article/details/gtmerfmllk.html

[R74] 批量重命名
来源：http://dali.hfpthk.cn/Article/details/gtuytzwsun.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cashguo.top/Article/details/gtmhvugibx.html

[R75] 导出环境变量
来源：http://dali.dianchejie.cn/Article/details/gtuolpahxu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.dianchejie.cn/Article/details/gtwwkcnkdf.html

[R76] 使用临时文件
来源：http://dali.nanxinkj.top/Article/details/gtqgnsyvqw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.nanxinkj.top/Article/details/gtggtzfqxy.html

[R77] 读取用户输入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtitjeevqf.html

read -rp "请输入: " ans
来源：http://dali.redwolf501.top/Article/details/gtvyurhauq.html

[R78] 交互式菜单
来源：http://dali.ehwqpu.com/Article/details/gtfkulajxi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shangyingyoupin.top/Article/details/gtvzvaumgu.html

[R79] 解析命令行选项
来源：http://dali.nanxuanxn.top/Article/details/gteldbrtmf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xziqi.cn/Article/details/gtubnppbsf.html

[R80] 查看脚本执行耗时
来源：http://dali.iojbl.cn/Article/details/gtoxqojvep.html

time ./run.sh
来源：http://dali.yanxiufei.cn/Article/details/gtaypvjxkk.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gthlulbgwz.html

S. C / C++ 专题
来源：http://dali.jinghuilouyu.cn/Article/details/gtootowkut.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtrvibewtv.html

[S01] C：Hello World
来源：http://dali.yj20258888.top/Article/details/gtwphxiegh.html

#include <stdio.h>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtntoiclgc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.sysykeji.top/Article/details/gtbclgcven.html

[S02] C：变量与格式化输出
来源：http://dali.hnxiangtu.top/Article/details/gtguomfvah.html

int a = 10; printf("%d\n", a);
来源：http://dali.jyoumei.cn/Article/details/gtnwowyejq.html

[S03] C：读入整数
来源：http://dali.xinyue.icu/Article/details/gtsuodkxas.html

int x; scanf("%d", &x);
来源：http://dali.zhengqikj.top/Article/details/gtqokuyxyr.html

[S04] C：字符串复制
来源：http://dali.hywenlv.cn/Article/details/gtaxsseuyd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xuanzx.com/Article/details/gtzecoeotm.html

[S05] C：字符串长度
来源：http://dali.haohaochexian.top/Article/details/gtdfdrjtsf.html

strlen(s)
来源：http://dali.jqgufenzy.top/Article/details/gtvfbyeyzk.html

[S06] C：字符串比较
来源：http://dali.jinqigfzy.top/Article/details/gtqfhyzmzy.html

strcmp(a, b) == 0
来源：http://dali.svipenyu.cn/Article/details/gtsyxiesev.html

[S07] C：数组遍历求和
来源：http://dali.ivvv.top/Article/details/gtymoqudaa.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shuidangran.top/Article/details/gtokdrkzqm.html

[S08] C：动态内存分配与释放
来源：http://dali.xylfe.cn/Article/details/gtcvipyhhd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jqgufenzy.top/Article/details/gtiwvmqbmf.html

[S09] C：结构体定义与初始化
来源：http://dali.chenzaomai.com/Article/details/gtjksqgdcz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.redwolf501.top/Article/details/gtpksfbadn.html

[S10] C：指针与解引用
来源：http://dali.chenlongwang.top/Article/details/gtanexskhh.html

int *p = &a;  *p = 5;
来源：http://dali.fengsongda.top/Article/details/gtxpopnbid.html

[S11] C：逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gtgvpegygw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthjbwoieb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yj202588.top/Article/details/gtrxovernu.html

fclose(f);
来源：http://dali.tanke756.top/Article/details/gtikeqmcvm.html

[S12] C：写文件
来源：http://dali.nanxinkj.top/Article/details/gtdhgpcjle.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinqigufen.top/Article/details/gtfspwzney.html

[S13] C：宏定义
来源：http://dali.guowangkeji.top/Article/details/gtfzbdqrqq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhongyouzk.top/Article/details/gtykriaosa.html

[S14] C：枚举
来源：http://dali.daria6918.cn/Article/details/gtzkbqyidu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yuanzhike.top/Article/details/gtvxhpduqj.html

[S15] C：类型转换
来源：http://dali.yongpay.top/Article/details/gtdnagammx.html

(double) a / b
来源：http://dali.jqgufenzy.top/Article/details/gtsmdgrtnk.html

[S16] C：位操作置位
来源：http://dali.vqdsnc.cn/Article/details/gtpstwmjjc.html

x |= (1 << 3);
来源：http://dali.hnqzz.top/Article/details/gtiatxajak.html

[S17] C：安全拼接字符串
来源：http://dali.chenlongwang.top/Article/details/gtpaoqtmfg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yanxiufei.cn/Article/details/gtfrtzvxjf.html

[S18] C：命令行参数
来源：http://dali.yanxiufei.cn/Article/details/gtxrscarvu.html

int main(int argc, char **argv)
来源：http://dali.hongshengwenyu.top/Article/details/gtbapmleni.html

[S19] C：快速排序
来源：http://dali.hywenlv.cn/Article/details/gtnwalabck.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yongpay.top/Article/details/gthoyzljxv.html

[S20] C：二分查找
来源：http://dali.yvedp.cn/Article/details/gtxsikffqa.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cheryme.top/Article/details/gtuepxowak.html

[S21] C：字符类别判断
来源：http://dali.c1oappe.top/Article/details/gtntfitqyp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jiagoushi.top/Article/details/gtdcjixwxc.html

[S22] C：字符串转数字
来源：http://dali.dianchejie.cn/Article/details/gtatzpyyoq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ybcxt.top/Article/details/gtfgldewyu.html

[S23] C：随机数
来源：http://dali.tianlin.xyz/Article/details/gtrytcbvgb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.sysykeji.top/Article/details/gttkixqvmf.html

[S24] C：获取本地时间
来源：http://dali.xuetiantiany.cn/Article/details/gtvehkxqxp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.guowangkeji.top/Article/details/gtlkgciwlp.html

[S25] C：内存拷贝
来源：http://dali.hammf.cn/Article/details/gtwawuwmfe.html

memcpy(dst, src, n);
来源：http://dali.iojbl.cn/Article/details/gtrwdlptxx.html

[S26] C：内存清零
来源：http://dali.sysykeji.top/Article/details/gtmynwpfsp.html

memset(a, 0, sizeof a);
来源：http://dali.daria6918.cn/Article/details/gtvqusnvjp.html

[S27] C：定义常量
来源：http://dali.yonumen.top/Article/details/gtfjgavnpi.html

const double PI = 3.14159;
来源：http://dali.wangdashe.top/Article/details/gtgegtcfps.html

[S28] C：静态变量
来源：http://dali.yuanzhike.top/Article/details/gtmtfswvpq.html

static int counter = 0;
来源：http://dali.dashuyun.cn/Article/details/gtzlogtikf.html

[S29] C：变参函数
来源：http://dali.snrcjt.cn/Article/details/gtleutkzvc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.bjfxy.top/Article/details/gtcpdyefrb.html

[S30] C：头文件保护
来源：http://dali.shzxlz.cn/Article/details/gtcsxxfxts.html

#ifndef X_H
来源：http://dali.shzxlz.cn/Article/details/gtjmkhnkqh.html

#define X_H
来源：http://dali.chenjidiqi.icu/Article/details/gtizpwylzd.html

#endif
来源：http://dali.ppjwa.cn/Article/details/gtzdapnvzg.html

[S31] C++：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtczmlreee.html

#include <iostream>
来源：http://dali.daria6918.cn/Article/details/gtnguldvnr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jinqigufen.top/Article/details/gtysxlbjze.html

[S32] C++：字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtfocrowgy.html

std::string s = "hi";  s += "!";
来源：http://dali.yj20258888.top/Article/details/gtgmzmyrfz.html

[S33] C++：vector 增删
来源：http://dali.jlsjyb.cn/Article/details/gtuefyryzs.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyqmeyoei.html

[S34] C++：遍历 vector
来源：http://dali.xylfe.cn/Article/details/gtwauudkhi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmxjkxbqz.html

[S35] C++：map
来源：http://dali.pengpengdd.cyou/Article/details/gtjfnluict.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cqqwz.cn/Article/details/gtevakdsiq.html

[S36] C++：unordered_map
来源：http://dali.shuidangran.top/Article/details/gtlconfudf.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hnqzz.top/Article/details/gtpdssoycr.html

[S37] C++：set
来源：http://dali.yueranfly.top/Article/details/gtfgztgvfk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.dianchejie.cn/Article/details/gtsrgrtkcw.html

[S38] C++：排序
来源：http://dali.pengpengdd.cyou/Article/details/gtwkalnoxi.html

std::sort(v.begin(), v.end());
来源：http://dali.dianchejie.cn/Article/details/gtjzjobrbl.html


<!-- 参考信息 -->