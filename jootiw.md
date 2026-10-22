代发 wailian999

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.redwolf501.top/Article/details/gtgzclmksm.html

[Q75] 日期格式化
来源：http://dali.guannengcc.top/Article/details/gtrtcllxqo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gtolrczhne.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.tianlin.xyz/Article/details/gtuhvmstny.html

[Q76] 按天统计
来源：http://dali.tanke756.top/Article/details/gtotlfezsj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yangfankeji.com/Article/details/gtsracxfyf.html

[Q77] 时间加减
来源：http://dali.jinghuilouyu.cn/Article/details/gtqrwmsjld.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.daxiang520.top/Article/details/gtxpfubvkq.html

[Q78] 当前时间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgfdlchgo.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hammf.cn/Article/details/gtwvllennp.html

[Q79] 字符串拼接
来源：http://dali.svipenyu.cn/Article/details/gtsxfwtbkn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.c1oappe.top/Article/details/gtlyiqvtaw.html

[Q80] 字符串截取
来源：http://dali.ybcxt.top/Article/details/gtfvdtpufa.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtgrvfjmvm.html

[Q81] 字符串替换
来源：http://dali.tianlin.xyz/Article/details/gtjaatbnpr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shuidangran.top/Article/details/gtvwykcxyx.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gtxozdmcde.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnvowfpba.html

[Q83] 大小写转换
来源：http://dali.hywenlv.cn/Article/details/gtwcwqhzha.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cucudq.cn/Article/details/gtjysowwmm.html

[Q84] 去除首尾空格
来源：http://dali.ybcxt.top/Article/details/gtoqfgmmrc.html

SELECT TRIM(name) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtgnytljip.html

[Q85] 数值取整
来源：http://dali.chenjidiqi.icu/Article/details/gttcukssxt.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.meibo888.top/Article/details/gtnmpaiktl.html

[Q86] 读取 JSON 字段
来源：http://dali.jqgfzy.top/Article/details/gtxsfezjig.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.feifeiyinyue.top/Article/details/gtlolrplgi.html

[Q87] JSON 字段做条件
来源：http://dali.xylfe.cn/Article/details/gtdvfokjyo.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.316326.xyz/Article/details/gtkoytutle.html

[Q88] 行转列（条件聚合）
来源：http://dali.xziqi.cn/Article/details/gtwmvcsthh.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrwxtlxiy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xylfe.cn/Article/details/gtubruyfek.html

[Q89] 判断表是否存在
来源：http://dali.gzhubu.top/Article/details/gtbpvyrfmz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hysaishi.cn/Article/details/gtestxilqo.html

[Q90] 生成序号列
来源：http://dali.wangdashe.top/Article/details/gtwbnvsrea.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jinqigufen.top/Article/details/gtfxkbrjzu.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtrdggwdzn.html

R. Bash 专题
来源：http://dali.cqqwz.cn/Article/details/gtvvyrntvl.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtyeimucne.html

[R01] shebang 与严格模式
来源：http://dali.gaohongyu789.top/Article/details/gtknufudld.html

#!/usr/bin/env bash
来源：http://dali.shzxlz.cn/Article/details/gtrqzibljt.html

set -euo pipefail
来源：http://dali.jyoumei.cn/Article/details/gtnuvoqokt.html

[R02] 变量赋值与使用
来源：http://dali.shuidangran.top/Article/details/gtfyvnlcep.html

name="Tom"; echo "$name"
来源：http://dali.hywenlv.cn/Article/details/gtcufgshdy.html

[R03] 只读变量
来源：http://dali.zycfv.cn/Article/details/gtplhbsjim.html

readonly PI=3.14
来源：http://dali.9152youxi.cn/Article/details/gtlpvylzpc.html

[R04] 位置参数
来源：http://dali.mhx1999.top/Article/details/gtvgdwjbgw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.kuanghao11.cn/Article/details/gtwdphsugu.html

[R05] 参数默认值
来源：http://dali.cucudq.cn/Article/details/gtaplghvaf.html

name="${1:-default}"
来源：http://dali.meibo888.top/Article/details/gtwfnfhnwq.html

[R06] 判断命令是否存在
来源：http://dali.jinqigufen.top/Article/details/gtjsnbudba.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.316326.xyz/Article/details/gtcuvzaxcq.html

[R07] if 判断文件
来源：http://dali.sufxvd.cn/Article/details/gtvzibncim.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sxryk.cn/Article/details/gtlbrxbona.html

[R08] 数值比较
来源：http://dali.hnqzz.top/Article/details/gtclatoghl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.svipenyu.cn/Article/details/gtkerdxdup.html

[R09] 字符串比较
来源：http://dali.birdmap.top/Article/details/gtnlgwakws.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gaohongyu789.top/Article/details/gtbjmrurhn.html

[R10] 正则匹配
来源：http://dali.chenzaomai.com/Article/details/gtrvdnumgu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.dashuyun.cn/Article/details/gtcguurchl.html

[R11] case 多分支
来源：http://dali.jinqigfzy.top/Article/details/gtcolvzgye.html

case "$1" in
来源：http://dali.feifeiyinyue.top/Article/details/gtolcdumav.html

start) echo "启动" ;;
来源：http://dali.birdmap.top/Article/details/gtvkhyoxkb.html

stop)  echo "停止" ;;
来源：http://dali.hysaishi.cn/Article/details/gtrsxwtfug.html

*)     echo "未知命令" ;;
来源：http://dali.guowangkeji.top/Article/details/gtmrawuxll.html

esac
来源：http://dali.daxiang520.top/Article/details/gtwslhjshb.html

[R12] for 遍历文件
来源：http://dali.jqgufenzy.top/Article/details/gtddgjbtbl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xuanzx.com/Article/details/gtvsuyhyuv.html

[R13] for 计数循环
来源：http://dali.xylfe.cn/Article/details/gthjfkgjrn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.nanxuanxn.top/Article/details/gtymejkqpp.html

[R14] C 风格 for
来源：http://dali.quarkkingdee.top/Article/details/gtajmcepuf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhoulong.xyz/Article/details/gtmhgpmhoi.html

[R15] while 逐行读文件
来源：http://dali.mhx1999.top/Article/details/gtysbotuwn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtioxicaid.html

[R16] until 等待条件
来源：http://dali.kuanghao11.cn/Article/details/gtvbocrcsi.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gotoacloud.top/Article/details/gtltcuzvmr.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gtwtgoyyya.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.andypj.xyz/Article/details/gtaomoqcmb.html

[R18] 遍历数组
来源：http://dali.sysykeji.top/Article/details/gtsohsezvr.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.daxiang520.top/Article/details/gtqndzfqjw.html

[R19] 数组长度
来源：http://dali.hnxiangtu.top/Article/details/gtsywfbkwn.html

echo "${#arr[@]}"
来源：http://dali.guannengcc.top/Article/details/gtqsoyzdzc.html

[R20] 关联数组（字典）
来源：http://dali.yanxiufei.cn/Article/details/gtemtxrydu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cqqwz.cn/Article/details/gtpnxtubqp.html

[R21] 字符串长度
来源：http://dali.zhongyouzk.top/Article/details/gtpuhpeobr.html

echo "${#s}"
来源：http://dali.yueranfly.top/Article/details/gtnfgtqadi.html

[R22] 截取子串
来源：http://dali.daria6918.cn/Article/details/gtsbitxppr.html

echo "${s:0:5}"
来源：http://dali.fzhhl.top/Article/details/gtiqnwutis.html

[R23] 字符串替换
来源：http://dali.yanxiufei.cn/Article/details/gtpnwaolja.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtikapipbu.html

[R24] 大小写转换
来源：http://dali.9152youxi.cn/Article/details/gtiddqayfo.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hammf.cn/Article/details/gtalctqkrc.html

[R25] 去后缀 / 去前缀
来源：http://dali.cashguo.top/Article/details/gtelrkexps.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.c1oappe.top/Article/details/gteitaopjx.html

[R26] 命令替换
来源：http://dali.hammf.cn/Article/details/gtncwwrwyd.html

now=$(date +%F); echo "$now"
来源：http://dali.jinqigufen.top/Article/details/gtqitupsqv.html

[R27] 算术展开
来源：http://dali.andypj.xyz/Article/details/gtcydkfhiz.html

echo $((1 + 2 * 3))
来源：http://dali.hfpthk.cn/Article/details/gtzlrwssot.html

[R28] 浮点运算
来源：http://dali.kuanghao11.cn/Article/details/gtbjgzbibc.html

echo "scale=2; 10/3" | bc
来源：http://dali.hnqzz.top/Article/details/gtgrjdiamj.html

[R29] 定义函数
来源：http://dali.andypj.xyz/Article/details/gtxhrzfvvw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.bjfxy.top/Article/details/gtvkxzizgp.html

[R30] 函数返回状态码
来源：http://dali.gaohongyu789.top/Article/details/gthojmfcjt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.gaohongyu789.top/Article/details/gtihgtqzcg.html

[R31] 局部变量
来源：http://dali.ehwqpu.com/Article/details/gtguxipkwp.html

f() { local x=1; echo "$x"; }
来源：http://dali.xinyue.icu/Article/details/gtgtadsyhq.html

[R32] 参数个数校验
来源：http://dali.jinghuilouyu.cn/Article/details/gtrsshtfwb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.9152youxi.cn/Article/details/gtbdopugan.html

[R33] 捕获错误并提示行号
来源：http://dali.jqgufenzy.top/Article/details/gtpxcuxjfd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yuxming.cn/Article/details/gthtgargey.html

[R34] 退出时清理
来源：http://dali.yj202588.top/Article/details/gtblouocec.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnxiangtu.top/Article/details/gtwlrzfohw.html

[R35] 后台执行并等待
来源：http://dali.guannengcc.top/Article/details/gtdssliksx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jiagoushi.top/Article/details/gtlnfwbmvk.html

[R36] 并发执行多个任务
来源：http://dali.ppjwa.cn/Article/details/gtsfhhnpub.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hywenlv.cn/Article/details/gtzzpclrms.html

[R37] 把输出赋给变量
来源：http://dali.9152youxi.cn/Article/details/gtddujimtv.html

files=$(ls -1)
来源：http://dali.yvedp.cn/Article/details/gtahfzowfn.html

[R38] 管道串联
来源：http://dali.xinyue.icu/Article/details/gtxkydpinu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cqqwz.cn/Article/details/gtcoyxfmfo.html

[R39] 重定向标准输出与错误
来源：http://dali.ybcxt.top/Article/details/gtizomityw.html

cmd > out.log 2>&1
来源：http://dali.jqgfzy.top/Article/details/gttzfxfmrv.html

[R40] 追加写日志
来源：http://dali.dianchejie.cn/Article/details/gtfnlozqju.html

echo "log" >> out.log
来源：http://dali.xinyue.icu/Article/details/gtzjkizkar.html

[R41] 丢弃输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gthtshmvnh.html

cmd >/dev/null 2>&1
来源：http://dali.pycfn.com/Article/details/gtglswkhgm.html

[R42] 输入重定向
来源：http://dali.fengsongda.top/Article/details/gtvyuyqqya.html

wc -l < a.txt
来源：http://dali.9152youxi.cn/Article/details/gtsbyxxkmz.html

[R43] 按名字查找文件
来源：http://dali.gotoacloud.top/Article/details/gtckvgkxob.html

find . -name "*.log" -type f
来源：http://dali.shangyingyoupin.top/Article/details/gtffyjbaag.html

[R44] 按修改时间查找
来源：http://dali.9152youxi.cn/Article/details/gtpnulvkkr.html

find . -mtime -7 -type f
来源：http://dali.yangfankeji.com/Article/details/gttmoafebh.html

[R45] 批量删除
来源：http://dali.snrcjt.cn/Article/details/gtdxlenynb.html

find . -name "*.tmp" -delete
来源：http://dali.aizwys.cn/Article/details/gtxkqhntfw.html

[R46] 递归替换文件内容
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqqehhmtp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jyoumei.cn/Article/details/gtttnqtdsn.html

[R47] sed 单行替换
来源：http://dali.quarkkingdee.top/Article/details/gtfqmdmhgt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.chenzaomai.com/Article/details/gtaxtxypzg.html

[R48] awk 取指定列
来源：http://dali.ppjwa.cn/Article/details/gtotoaqzvy.html

awk '{print $1, $3}' a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtctkrhdkr.html

[R49] awk 带条件
来源：http://dali.pengpengdd.cyou/Article/details/gtpehcqlsn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shzxlz.cn/Article/details/gtvcwbavxx.html

[R50] awk 求和
来源：http://dali.daxiang520.top/Article/details/gtwqkkataw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.iojbl.cn/Article/details/gtsussdaid.html

[R51] 排序去重取前几
来源：http://dali.tanke756.top/Article/details/gtjlpjwqga.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shangyingyoupin.top/Article/details/gttbptkswb.html

[R52] 统计行数
来源：http://dali.dashuyun.cn/Article/details/gtsviypovm.html

wc -l a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtvjglchti.html

[R53] 查看文件头与实时尾
来源：http://dali.jinqigufen.top/Article/details/gtfgxzinvb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yuxming.cn/Article/details/gtgzborlyx.html

[R54] 比较两个文件
来源：http://dali.gaohongyu789.top/Article/details/gtmwbqgssb.html

diff a.txt b.txt
来源：http://dali.daria6918.cn/Article/details/gtwaszkjaa.html

[R55] 压缩与解压
来源：http://dali.nanxinkj.top/Article/details/gtvtcgkgxv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.dianchejie.cn/Article/details/gtfyklecie.html

[R56] 远程拷贝
来源：http://dali.daxiang520.top/Article/details/gtbhgeutcj.html

scp file user@host:/path/
来源：http://dali.shanyushiyangtech.top/Article/details/gteukxpyie.html

[R57] 远程执行命令
来源：http://dali.hnxiangtu.top/Article/details/gtdxhkvoud.html

ssh user@host 'uptime'
来源：http://dali.chenlongwang.top/Article/details/gtrnuvhuib.html

[R58] 下载文件
来源：http://dali.shanyushiyangtech.top/Article/details/gthsjpqguo.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sysykeji.top/Article/details/gtgksgogan.html

[R59] 发 POST JSON
来源：http://dali.xuanzx.com/Article/details/gtexknbgqj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xinyue.icu/Article/details/gtulenxlsm.html

[R60] 只看 HTTP 状态码
来源：http://dali.shzxlz.cn/Article/details/gtogndsoin.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ehwqpu.com/Article/details/gtpbfudmbe.html

[R61] 磁盘占用
来源：http://dali.jyoumei.cn/Article/details/gtyzyykbeh.html

df -h;  du -sh *
来源：http://dali.tian-w.cn/Article/details/gtaangernd.html

[R62] 找最占空间的文件
来源：http://dali.gotoacloud.top/Article/details/gtidpvmuow.html

du -ah . | sort -rh | head -10
来源：http://dali.9152youxi.cn/Article/details/gtadovyhmg.html

[R63] 内存与进程
来源：http://dali.zdqjudy.top/Article/details/gtfvunlidk.html

free -h;  ps aux | grep nginx
来源：http://dali.zhoulong.xyz/Article/details/gtvxebwvsu.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gturrgrihh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sweek.top/Article/details/gttsesdtav.html

[R65] 查看端口占用
来源：http://dali.hysaishi.cn/Article/details/gtzafqdkwo.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.dianchejie.cn/Article/details/gtmvlyaudc.html

[R66] 定时任务
来源：http://dali.snrcjt.cn/Article/details/gtxgznslav.html

crontab -e;  crontab -l
来源：http://dali.yuanzhike.top/Article/details/gtwsjsurxs.html

[R67] 生成随机十六进制串
来源：http://dali.ybcxt.top/Article/details/gtqyntwyio.html

openssl rand -hex 16
来源：http://dali.sufxvd.cn/Article/details/gttsbfmwwb.html

[R68] 计算文件校验值
来源：http://dali.tian-w.cn/Article/details/gtajetovkz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xinyue.icu/Article/details/gtrxxeybfd.html

[R69] 生成随机密码
来源：http://dali.yonumen.top/Article/details/gtqpututjw.html

head -c 16 /dev/urandom | base64
来源：http://dali.jiagoushi.top/Article/details/gtumgzvsqm.html

[R70] 时间戳与互转
来源：http://dali.aizwys.cn/Article/details/gtocvybthg.html

date +%s;  date -d @1700000000
来源：http://dali.nanxinkj.top/Article/details/gtnyrjcudo.html

[R71] 日期格式化
来源：http://dali.guowangkeji.top/Article/details/gtexpkxkos.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jqgfzy.top/Article/details/gtorffrube.html

[R72] 等待端口就绪
来源：http://dali.cqqwz.cn/Article/details/gtpgexgxrb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yj20258888.top/Article/details/gtjljowwdz.html

[R73] 分割大日志
来源：http://dali.xinyue.icu/Article/details/gtmqjxelib.html

split -l 1000 big.log part_
来源：http://dali.hammf.cn/Article/details/gtixsjixzm.html

[R74] 批量重命名
来源：http://dali.yuanzhike.top/Article/details/gtecollyon.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sxryk.cn/Article/details/gtxpwpoufm.html

[R75] 导出环境变量
来源：http://dali.jinqigufen.top/Article/details/gtpczcxunl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.daxiang520.top/Article/details/gtrrbymeca.html

[R76] 使用临时文件
来源：http://dali.fengsongda.top/Article/details/gtzrpedgbg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.9152youxi.cn/Article/details/gtgtkcmfsr.html

[R77] 读取用户输入
来源：http://dali.nwbrower.top/Article/details/gtjxyfiewk.html

read -rp "请输入: " ans
来源：http://dali.316326.xyz/Article/details/gtdnxkcpxj.html

[R78] 交互式菜单
来源：http://dali.chenjidiqi.icu/Article/details/gtiinrvlgv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.havefunace.top/Article/details/gteazqfmni.html

[R79] 解析命令行选项
来源：http://dali.yonumen.top/Article/details/gtbfwxdczg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.cashguo.top/Article/details/gtbxvdqpac.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gtqpaceuse.html

time ./run.sh
来源：http://dali.dianchejie.cn/Article/details/gtclqakiyz.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtmcpoyzrf.html

S. C / C++ 专题
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpvgbrhib.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxddxkdwt.html

[S01] C：Hello World
来源：http://dali.zhengqikj.top/Article/details/gtyczbjucc.html

#include <stdio.h>
来源：http://dali.hnqzz.top/Article/details/gtfofzdjxu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hfpthk.cn/Article/details/gtkrkizovk.html

[S02] C：变量与格式化输出
来源：http://dali.pengpengdd.cyou/Article/details/gtwprfkevy.html

int a = 10; printf("%d\n", a);
来源：http://dali.yj20258.top/Article/details/gterpohhby.html

[S03] C：读入整数
来源：http://dali.gotoacloud.top/Article/details/gtbbigphsc.html

int x; scanf("%d", &x);
来源：http://dali.hfpthk.cn/Article/details/gtqnncyzxi.html

[S04] C：字符串复制
来源：http://dali.jiagoushi.top/Article/details/gtxhxxwolq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdurzfibn.html

[S05] C：字符串长度
来源：http://dali.fzhhl.top/Article/details/gtdhsjqzvi.html

strlen(s)
来源：http://dali.yonumen.top/Article/details/gtwwbupowp.html

[S06] C：字符串比较
来源：http://dali.ehwqpu.com/Article/details/gtsmuelidi.html

strcmp(a, b) == 0
来源：http://dali.yuxming.cn/Article/details/gtxccxzenz.html

[S07] C：数组遍历求和
来源：http://dali.c1oappe.top/Article/details/gtbgykeraz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yuanzhike.top/Article/details/gtkniynamx.html

[S08] C：动态内存分配与释放
来源：http://dali.cashguo.top/Article/details/gtsbzjygdr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.kuanghao11.cn/Article/details/gtmxwktlpd.html

[S09] C：结构体定义与初始化
来源：http://dali.9152youxi.cn/Article/details/gtzscnmovb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.aizwys.cn/Article/details/gtkbwveiof.html

[S10] C：指针与解引用
来源：http://dali.316326.xyz/Article/details/gtsqqtlpxh.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gtpgaxjpsf.html

[S11] C：逐行读文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtvfcxlkiq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gotoacloud.top/Article/details/gtnvhggrfx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sweek.top/Article/details/gthnvrgtcv.html

fclose(f);
来源：http://dali.aizwys.cn/Article/details/gtuwpvmvrw.html

[S12] C：写文件
来源：http://dali.smart0.xyz/Article/details/gteeoykypw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jiagoushi.top/Article/details/gtqnmhjyre.html

[S13] C：宏定义
来源：http://dali.iojbl.cn/Article/details/gtwpcrwcjn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jyoumei.cn/Article/details/gtigvxuiot.html

[S14] C：枚举
来源：http://dali.redwolf501.top/Article/details/gtqeewrcwy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.nwbrower.top/Article/details/gtcagyathy.html

[S15] C：类型转换
来源：http://dali.tanke756.top/Article/details/gtreaqvvcq.html

(double) a / b
来源：http://dali.jqgfzy.top/Article/details/gtqolfxcsv.html

[S16] C：位操作置位
来源：http://dali.tanke756.top/Article/details/gthyrmixzp.html

x |= (1 << 3);
来源：http://dali.jianghu66.top/Article/details/gtjhagxxxg.html

[S17] C：安全拼接字符串
来源：http://dali.cdnleiting.top/Article/details/gtknmkdfzq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yueranfly.top/Article/details/gtfyklheyd.html

[S18] C：命令行参数
来源：http://dali.sysykeji.top/Article/details/gtrsnqnzde.html

int main(int argc, char **argv)
来源：http://dali.mhx1999.top/Article/details/gtgyfkbxbx.html

[S19] C：快速排序
来源：http://dali.wangshuangyany.cn/Article/details/gtvwpmovfe.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiicnrjae.html

[S20] C：二分查找
来源：http://dali.ybcxt.top/Article/details/gtzafsaprw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yuxming.cn/Article/details/gtxrfbhaxj.html

[S21] C：字符类别判断
来源：http://dali.gotoacloud.top/Article/details/gtvqaqfvib.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.bjfxy.top/Article/details/gtheajcama.html

[S22] C：字符串转数字
来源：http://dali.zhiwuduotai.top/Article/details/gtfbqoclmh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.chenzaomai.com/Article/details/gtylxnvyhx.html

[S23] C：随机数
来源：http://dali.yj20258.top/Article/details/gtxlzugeck.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.9152youxi.cn/Article/details/gtizwvvefl.html

[S24] C：获取本地时间
来源：http://dali.gogol.net.cn/Article/details/gtnpevlixc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yueranfly.top/Article/details/gtcqluoqrw.html

[S25] C：内存拷贝
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcowvowgi.html

memcpy(dst, src, n);
来源：http://dali.daxiang520.top/Article/details/gtkvitmmch.html

[S26] C：内存清零
来源：http://dali.wangdashe.top/Article/details/gtkjvmsctq.html

memset(a, 0, sizeof a);
来源：http://dali.0kj1m.cn/Article/details/gtrtiiytva.html

[S27] C：定义常量
来源：http://dali.jinqigfzy.top/Article/details/gtgieiontb.html

const double PI = 3.14159;
来源：http://dali.kuanghao11.cn/Article/details/gtqzdegonj.html

[S28] C：静态变量
来源：http://dali.haohaochexian.top/Article/details/gterfjupek.html

static int counter = 0;
来源：http://dali.chenjidiqi.icu/Article/details/gtttudvofr.html

[S29] C：变参函数
来源：http://dali.tianlin.xyz/Article/details/gtqusimnmq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hammf.cn/Article/details/gtnhpihwsm.html

[S30] C：头文件保护
来源：http://dali.wangshuangyany.cn/Article/details/gtbhizonhp.html

#ifndef X_H
来源：http://dali.wangdashe.top/Article/details/gtrhjcnlgj.html

#define X_H
来源：http://dali.snrcjt.cn/Article/details/gtfvacsyqv.html

#endif
来源：http://dali.svipenyu.cn/Article/details/gtyotrwige.html

[S31] C++：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gttasfbled.html

#include <iostream>
来源：http://dali.zhiwuduotai.top/Article/details/gtbwbfxczl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.mhx1999.top/Article/details/gtrydkkyde.html

[S32] C++：字符串
来源：http://dali.zdqjudy.top/Article/details/gthltuahqm.html

std::string s = "hi";  s += "!";
来源：http://dali.havefunace.top/Article/details/gtrpuqkcrl.html

[S33] C++：vector 增删
来源：http://dali.wangdashe.top/Article/details/gthlbfmqvh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.redwolf501.top/Article/details/gtpecbyuxw.html

[S34] C++：遍历 vector
来源：http://dali.svipenyu.cn/Article/details/gtlrpmepma.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jyoumei.cn/Article/details/gtlkpsivtg.html

[S35] C++：map
来源：http://dali.smart0.xyz/Article/details/gtahsncfoq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinqigufen.top/Article/details/gthltugnuw.html

[S36] C++：unordered_map
来源：http://dali.snrcjt.cn/Article/details/gtlwgsuqne.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gaohongyu789.top/Article/details/gtbdiiyzyl.html

[S37] C++：set
来源：http://dali.pengpengdd.cyou/Article/details/gtfzwtnzwi.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yj20258888.top/Article/details/gtpwzmsnze.html

[S38] C++：排序
来源：http://dali.pycfn.com/Article/details/gtjwqmkkfr.html

std::sort(v.begin(), v.end());
来源：http://dali.daxiang520.top/Article/details/gtalvtvrar.html

[S39] C++：自定义比较器排序
来源：http://dali.fzhhl.top/Article/details/gtazsngead.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jqgfzy.top/Article/details/gthtqgutec.html

[S40] C++：查找元素
来源：http://dali.yj20258.top/Article/details/gtylumzvry.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinqigfzy.top/Article/details/gthxkqffxp.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gtrjjhsdvr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.tanke756.top/Article/details/gtntvwpbxi.html

[S42] C++：继承与虚函数
来源：http://dali.tian-w.cn/Article/details/gtfdprmxty.html

class B : public Base { public: void f() override {} };
来源：http://dali.tianlin.xyz/Article/details/gtfisafrzr.html

[S43] C++：智能指针
来源：http://dali.yangfankeji.com/Article/details/gtjlqscznw.html

auto p = std::make_unique<int>(5);
来源：http://dali.316326.xyz/Article/details/gtaqxshwdc.html

[S44] C++：引用传参
来源：http://dali.xinyue.icu/Article/details/gtvayeyibh.html

void inc(int &x) { ++x; }
来源：http://dali.guowangkeji.top/Article/details/gtjvobipwl.html


<!-- 参考信息 -->