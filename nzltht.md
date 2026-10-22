代发 wailian999

[Q78] 当前时间
来源：http://dali.9152youxi.cn/Article/details/gtlbrkhqlm.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbwzspxhk.html

[Q79] 字符串拼接
来源：http://dali.9152youxi.cn/Article/details/gtaggwzabk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gotoacloud.top/Article/details/gtrgjxtedn.html

[Q80] 字符串截取
来源：http://dali.dianchejie.cn/Article/details/gtdxingwse.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtnyrwlxxs.html

[Q81] 字符串替换
来源：http://dali.andypj.xyz/Article/details/gtmjglahdu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gthkdiyxvl.html

[Q82] 字符长度与字节长度
来源：http://dali.fengsongda.top/Article/details/gtaybecdun.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtafatbyqr.html

[Q83] 大小写转换
来源：http://dali.shzxlz.cn/Article/details/gtkhgzyqvj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cashguo.top/Article/details/gtafkdprgr.html

[Q84] 去除首尾空格
来源：http://dali.zycfv.cn/Article/details/gtidtfelph.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gttqwbtfsc.html

[Q85] 数值取整
来源：http://dali.mhx1999.top/Article/details/gtrpkhbrle.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.quarkkingdee.top/Article/details/gtklqthfhe.html

[Q86] 读取 JSON 字段
来源：http://dali.sufxvd.cn/Article/details/gtzwswuxgk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.mhx1999.top/Article/details/gtqvsikesg.html

[Q87] JSON 字段做条件
来源：http://dali.xylfe.cn/Article/details/gtybyyslvk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.iojbl.cn/Article/details/gthdioomll.html

[Q88] 行转列（条件聚合）
来源：http://dali.jinyuanbaomall.cn/Article/details/gthjgmapsr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hongshengwenyu.top/Article/details/gtaexfnntw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.havefunace.top/Article/details/gthtxdiwgz.html

[Q89] 判断表是否存在
来源：http://dali.dashuyun.cn/Article/details/gtswioijmu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jiagoushi.top/Article/details/gtrdxwbucu.html

[Q90] 生成序号列
来源：http://dali.wangshuangyany.cn/Article/details/gtvpsswngx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jinqigfzy.top/Article/details/gtctvmqydc.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtcxwwuvmr.html

R. Bash 专题
来源：http://dali.pycfn.com/Article/details/gticuaplrb.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gteynaqkpd.html

[R01] shebang 与严格模式
来源：http://dali.zhongyouzk.top/Article/details/gteeyvdiie.html

#!/usr/bin/env bash
来源：http://dali.daria6918.cn/Article/details/gtfkqikmgi.html

set -euo pipefail
来源：http://dali.shzxlz.cn/Article/details/gtftvybkxx.html

[R02] 变量赋值与使用
来源：http://dali.c1oappe.top/Article/details/gtggsxqwcx.html

name="Tom"; echo "$name"
来源：http://dali.gotoacloud.top/Article/details/gtlsxkgufq.html

[R03] 只读变量
来源：http://dali.yj20258.top/Article/details/gtbzmpavpm.html

readonly PI=3.14
来源：http://dali.c1oappe.top/Article/details/gtzvxgokdy.html

[R04] 位置参数
来源：http://dali.fengsongda.top/Article/details/gttzhoyokq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.9152youxi.cn/Article/details/gtkqgcgfvg.html

[R05] 参数默认值
来源：http://dali.sufxvd.cn/Article/details/gtpwjvlexs.html

name="${1:-default}"
来源：http://dali.zdqjudy.top/Article/details/gtzpozigar.html

[R06] 判断命令是否存在
来源：http://dali.cashguo.top/Article/details/gtyaogerhq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.chenjidiqi.icu/Article/details/gtjfsgfjcy.html

[R07] if 判断文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtspxdiott.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinqigufen.top/Article/details/gtdguplcao.html

[R08] 数值比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfazbymdq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cashguo.top/Article/details/gtfthpzqaa.html

[R09] 字符串比较
来源：http://dali.yj20258.top/Article/details/gttsmltxbx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yongpay.top/Article/details/gtzmnvtoud.html

[R10] 正则匹配
来源：http://dali.0kj1m.cn/Article/details/gtwjwxxdpi.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.snrcjt.cn/Article/details/gtgswpxmxg.html

[R11] case 多分支
来源：http://dali.xylfe.cn/Article/details/gtsrkfcscf.html

case "$1" in
来源：http://dali.zhengqikj.top/Article/details/gtlafqhpzu.html

start) echo "启动" ;;
来源：http://dali.jlsjyb.cn/Article/details/gtynqbjxde.html

stop)  echo "停止" ;;
来源：http://dali.ivvv.top/Article/details/gtbxsumhll.html

*)     echo "未知命令" ;;
来源：http://dali.ivvv.top/Article/details/gttvhwinip.html

esac
来源：http://dali.yuxming.cn/Article/details/gtiucxadmm.html

[R12] for 遍历文件
来源：http://dali.pengpengdd.cyou/Article/details/gtaxhifguk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.tian-w.cn/Article/details/gtafudflsa.html

[R13] for 计数循环
来源：http://dali.haohaochexian.top/Article/details/gtcqmioevp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinqigfzy.top/Article/details/gtejewxtal.html

[R14] C 风格 for
来源：http://dali.aizwys.cn/Article/details/gtlxrqykyn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hongshengwenyu.top/Article/details/gtehyvukgk.html

[R15] while 逐行读文件
来源：http://dali.daria6918.cn/Article/details/gtxkmbycmu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jqgfzy.top/Article/details/gtspjcvoeh.html

[R16] until 等待条件
来源：http://dali.xziqi.cn/Article/details/gtbljjherg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.feifeiyinyue.top/Article/details/gtybvksieu.html

[R17] 数组定义与取值
来源：http://dali.feifeiyinyue.top/Article/details/gtkjyfbpzr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.smart0.xyz/Article/details/gtdnwudfrm.html

[R18] 遍历数组
来源：http://dali.snrcjt.cn/Article/details/gtkintkley.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cucudq.cn/Article/details/gtygqfvaqr.html

[R19] 数组长度
来源：http://dali.snrcjt.cn/Article/details/gtqxxaxbni.html

echo "${#arr[@]}"
来源：http://dali.yj202588.top/Article/details/gtxxpyckse.html

[R20] 关联数组（字典）
来源：http://dali.nanxuanxn.top/Article/details/gtjjwmlvtx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.pycfn.com/Article/details/gtmglonesa.html

[R21] 字符串长度
来源：http://dali.hnqzz.top/Article/details/gtxxodvpug.html

echo "${#s}"
来源：http://dali.kuanghao11.cn/Article/details/gtzfmvdvbm.html

[R22] 截取子串
来源：http://dali.c1oappe.top/Article/details/gtehkrrbvp.html

echo "${s:0:5}"
来源：http://dali.sysykeji.top/Article/details/gtlplddzwd.html

[R23] 字符串替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtaauhwdne.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.mhx1999.top/Article/details/gtlichhsoc.html

[R24] 大小写转换
来源：http://dali.yongpay.top/Article/details/gtwwfycwuy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.tanke756.top/Article/details/gtbwzymrtp.html

[R25] 去后缀 / 去前缀
来源：http://dali.hnxiangtu.top/Article/details/gtwanrpjxs.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.aibaodan.cn/Article/details/gtaddihrlf.html

[R26] 命令替换
来源：http://dali.birdmap.top/Article/details/gtesevdewv.html

now=$(date +%F); echo "$now"
来源：http://dali.xziqi.cn/Article/details/gtirgyegfy.html

[R27] 算术展开
来源：http://dali.cheryme.top/Article/details/gthyvxazkn.html

echo $((1 + 2 * 3))
来源：http://dali.shzxlz.cn/Article/details/gtpdrefxpb.html

[R28] 浮点运算
来源：http://dali.0kj1m.cn/Article/details/gtuayvrjit.html

echo "scale=2; 10/3" | bc
来源：http://dali.tianlin.xyz/Article/details/gtnacsangh.html

[R29] 定义函数
来源：http://dali.316326.xyz/Article/details/gtoaaiuagi.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.sufxvd.cn/Article/details/gtiugdhsph.html

[R30] 函数返回状态码
来源：http://dali.sysykeji.top/Article/details/gthvdlcwvd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.andypj.xyz/Article/details/gtrylfhzbk.html

[R31] 局部变量
来源：http://dali.havefunace.top/Article/details/gtkxocivev.html

f() { local x=1; echo "$x"; }
来源：http://dali.yueranfly.top/Article/details/gtsiacgpdj.html

[R32] 参数个数校验
来源：http://dali.jyoumei.cn/Article/details/gtsnbgagdr.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkrhtjzau.html

[R33] 捕获错误并提示行号
来源：http://dali.sufxvd.cn/Article/details/gtjlhjthzy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jinqigfzy.top/Article/details/gtetpblyll.html

[R34] 退出时清理
来源：http://dali.smart0.xyz/Article/details/gtpmxwumkj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhoulong.xyz/Article/details/gtqmiftxhw.html

[R35] 后台执行并等待
来源：http://dali.gzhubu.top/Article/details/gtaowvaqps.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.sysykeji.top/Article/details/gtbojyjzsq.html

[R36] 并发执行多个任务
来源：http://dali.daria6918.cn/Article/details/gtnoixextx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.quarkkingdee.top/Article/details/gtghzkqedr.html

[R37] 把输出赋给变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcimgymub.html

files=$(ls -1)
来源：http://dali.hongshengwenyu.top/Article/details/gtaluxnwpl.html

[R38] 管道串联
来源：http://dali.havefunace.top/Article/details/gtrlhiijno.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cdnleiting.top/Article/details/gtkruwkuyh.html

[R39] 重定向标准输出与错误
来源：http://dali.zhengqikj.top/Article/details/gtqdifxrla.html

cmd > out.log 2>&1
来源：http://dali.9152youxi.cn/Article/details/gtliplmthg.html

[R40] 追加写日志
来源：http://dali.hammf.cn/Article/details/gtofjqzyps.html

echo "log" >> out.log
来源：http://dali.yonumen.top/Article/details/gtzitenddq.html

[R41] 丢弃输出
来源：http://dali.kuanghao11.cn/Article/details/gtfkjmifzv.html

cmd >/dev/null 2>&1
来源：http://dali.hysaishi.cn/Article/details/gtjcxnpoox.html

[R42] 输入重定向
来源：http://dali.sufxvd.cn/Article/details/gtwgxoypew.html

wc -l < a.txt
来源：http://dali.wangdashe.top/Article/details/gtnvofwkti.html

[R43] 按名字查找文件
来源：http://dali.yanxiufei.cn/Article/details/gtdclxiiwi.html

find . -name "*.log" -type f
来源：http://dali.cdnleiting.top/Article/details/gtnmvqfvge.html

[R44] 按修改时间查找
来源：http://dali.feifeiyinyue.top/Article/details/gtihmdnjnv.html

find . -mtime -7 -type f
来源：http://dali.bjfxy.top/Article/details/gtfgenbtwm.html

[R45] 批量删除
来源：http://dali.xylfe.cn/Article/details/gtsrdwrjcl.html

find . -name "*.tmp" -delete
来源：http://dali.yj20258888.top/Article/details/gtahegzlnl.html

[R46] 递归替换文件内容
来源：http://dali.316326.xyz/Article/details/gtjhbbclqv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ppjwa.cn/Article/details/gtircsabxh.html

[R47] sed 单行替换
来源：http://dali.shangyingyoupin.top/Article/details/gtsykyauia.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.meibo888.top/Article/details/gtlswxxlpm.html

[R48] awk 取指定列
来源：http://dali.gaohongyu789.top/Article/details/gtqsdtajlz.html

awk '{print $1, $3}' a.txt
来源：http://dali.snrcjt.cn/Article/details/gtbpxfjpjb.html

[R49] awk 带条件
来源：http://dali.shangyingyoupin.top/Article/details/gtanprvvzs.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.chenlongwang.top/Article/details/gttulmlleq.html

[R50] awk 求和
来源：http://dali.feifeiyinyue.top/Article/details/gtwvecvubm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sufxvd.cn/Article/details/gtcmawbjhc.html

[R51] 排序去重取前几
来源：http://dali.gaohongyu789.top/Article/details/gtsxkqacex.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.daxiang520.top/Article/details/gtdjffiyin.html

[R52] 统计行数
来源：http://dali.xziqi.cn/Article/details/gtvgtzaevq.html

wc -l a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtajliymcn.html

[R53] 查看文件头与实时尾
来源：http://dali.ydzc1.top/Article/details/gtyejuedxv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhengqikj.top/Article/details/gtxnpzlzyj.html

[R54] 比较两个文件
来源：http://dali.jinqigufen.top/Article/details/gtitmrwdeu.html

diff a.txt b.txt
来源：http://dali.gogol.net.cn/Article/details/gtaarmaqew.html

[R55] 压缩与解压
来源：http://dali.zhengqikj.top/Article/details/gtxjryuogk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xinyue.icu/Article/details/gtihzstyhd.html

[R56] 远程拷贝
来源：http://dali.havefunace.top/Article/details/gtpmafgztx.html

scp file user@host:/path/
来源：http://dali.ybcxt.top/Article/details/gtpslwrusa.html

[R57] 远程执行命令
来源：http://dali.sysykeji.top/Article/details/gtaghwfpag.html

ssh user@host 'uptime'
来源：http://dali.guowangkeji.top/Article/details/gtuoggnutu.html

[R58] 下载文件
来源：http://dali.jqgfzy.top/Article/details/gtbieframa.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yonumen.top/Article/details/gtsbktijdp.html

[R59] 发 POST JSON
来源：http://dali.tian-w.cn/Article/details/gtmuguhfcm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.cheryme.top/Article/details/gtnahdulya.html

[R60] 只看 HTTP 状态码
来源：http://dali.yj20258888.top/Article/details/gtlohzdlfx.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ivvv.top/Article/details/gturjaoqoz.html

[R61] 磁盘占用
来源：http://dali.cqqwz.cn/Article/details/gtxxitbkfm.html

df -h;  du -sh *
来源：http://dali.yuxming.cn/Article/details/gtimmzvccg.html

[R62] 找最占空间的文件
来源：http://dali.svipenyu.cn/Article/details/gtvawzwqmd.html

du -ah . | sort -rh | head -10
来源：http://dali.hywenlv.cn/Article/details/gtvefpcazt.html

[R63] 内存与进程
来源：http://dali.zhoulong.xyz/Article/details/gtxapphbmx.html

free -h;  ps aux | grep nginx
来源：http://dali.svipenyu.cn/Article/details/gtwlnyzebg.html

[R64] 结束进程
来源：http://dali.fengsongda.top/Article/details/gtnvfouyrd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhiwuduotai.top/Article/details/gtkrlycmcp.html

[R65] 查看端口占用
来源：http://dali.shuidangran.top/Article/details/gtlsbjrauo.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jiagoushi.top/Article/details/gtriptkemg.html

[R66] 定时任务
来源：http://dali.yonumen.top/Article/details/gtaxpckkvk.html

crontab -e;  crontab -l
来源：http://dali.daxiang520.top/Article/details/gtkhxqiapw.html

[R67] 生成随机十六进制串
来源：http://dali.cucudq.cn/Article/details/gtzkjtcege.html

openssl rand -hex 16
来源：http://dali.hnqzz.top/Article/details/gtvbbebzig.html

[R68] 计算文件校验值
来源：http://dali.yuxming.cn/Article/details/gtcudjcpkh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.andypj.xyz/Article/details/gtifpowoet.html

[R69] 生成随机密码
来源：http://dali.ybcxt.top/Article/details/gtlllxnzsh.html

head -c 16 /dev/urandom | base64
来源：http://dali.quarkkingdee.top/Article/details/gtiepkxkap.html

[R70] 时间戳与互转
来源：http://dali.shuidangran.top/Article/details/gthhvfwxli.html

date +%s;  date -d @1700000000
来源：http://dali.jqgufenzy.top/Article/details/gtwdwxfqus.html

[R71] 日期格式化
来源：http://dali.zhongyouzk.top/Article/details/gthkcrkffy.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.smart0.xyz/Article/details/gtzftcfged.html

[R72] 等待端口就绪
来源：http://dali.meibo888.top/Article/details/gtzfdbdbfw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jqgfzy.top/Article/details/gtfasptkjs.html

[R73] 分割大日志
来源：http://dali.aibaodan.cn/Article/details/gtdalgmczi.html

split -l 1000 big.log part_
来源：http://dali.ehwqpu.com/Article/details/gtonjogexb.html

[R74] 批量重命名
来源：http://dali.hongshengwenyu.top/Article/details/gtzryreryf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jinqigufen.top/Article/details/gtpaekoaph.html

[R75] 导出环境变量
来源：http://dali.wangdashe.top/Article/details/gtucmvmwwk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ehwqpu.com/Article/details/gtzxeqzfpv.html

[R76] 使用临时文件
来源：http://dali.smart0.xyz/Article/details/gtaegtorkz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.wangshuangyany.cn/Article/details/gtvqtlxypb.html

[R77] 读取用户输入
来源：http://dali.fzhhl.top/Article/details/gtfzyzcdue.html

read -rp "请输入: " ans
来源：http://dali.sysykeji.top/Article/details/gtdpfievsj.html

[R78] 交互式菜单
来源：http://dali.gzhubu.top/Article/details/gtbhhvdtll.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shuidangran.top/Article/details/gtjwxxifiw.html

[R79] 解析命令行选项
来源：http://dali.hysaishi.cn/Article/details/gtgfswzhse.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zycfv.cn/Article/details/gteczwkras.html

[R80] 查看脚本执行耗时
来源：http://dali.zhixingplan.top/Article/details/gtlltdmlvn.html

time ./run.sh
来源：http://dali.daria6918.cn/Article/details/gtgjoyremm.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtrfvgcpiz.html

S. C / C++ 专题
来源：http://dali.sysykeji.top/Article/details/gtqmywriqj.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtmhdnxrfp.html

[S01] C：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtlhqtdnqd.html

#include <stdio.h>
来源：http://dali.0kj1m.cn/Article/details/gtwblmnrpw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jlsjyb.cn/Article/details/gtfwqevzca.html

[S02] C：变量与格式化输出
来源：http://dali.fengsongda.top/Article/details/gtfrcxcmap.html

int a = 10; printf("%d\n", a);
来源：http://dali.jianghu66.top/Article/details/gtkzbcxpoe.html

[S03] C：读入整数
来源：http://dali.ivvv.top/Article/details/gtrljudmny.html

int x; scanf("%d", &x);
来源：http://dali.jinghuilouyu.cn/Article/details/gtlcosjjdj.html

[S04] C：字符串复制
来源：http://dali.bjfxy.top/Article/details/gtlunnnoxd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hammf.cn/Article/details/gtmprspmtm.html

[S05] C：字符串长度
来源：http://dali.hfpthk.cn/Article/details/gtgeypggvx.html

strlen(s)
来源：http://dali.fengsongda.top/Article/details/gtoscmppzf.html

[S06] C：字符串比较
来源：http://dali.shzxlz.cn/Article/details/gtozlutrib.html

strcmp(a, b) == 0
来源：http://dali.jinqigufen.top/Article/details/gtlpmmvghu.html

[S07] C：数组遍历求和
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlovxbqoq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sysykeji.top/Article/details/gtgwsdkyfa.html

[S08] C：动态内存分配与释放
来源：http://dali.hnxiangtu.top/Article/details/gtqqfuesfz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jianghu66.top/Article/details/gtnbhutuqm.html

[S09] C：结构体定义与初始化
来源：http://dali.316326.xyz/Article/details/gtmkvutwzn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhoulong.xyz/Article/details/gtrnacbszb.html

[S10] C：指针与解引用
来源：http://dali.svipenyu.cn/Article/details/gtyfaspuuc.html

int *p = &a;  *p = 5;
来源：http://dali.fengsongda.top/Article/details/gtyxaueawf.html

[S11] C：逐行读文件
来源：http://dali.tian-w.cn/Article/details/gtacrgujid.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhiwuduotai.top/Article/details/gteordadsw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hfpthk.cn/Article/details/gtmijmpdvy.html

fclose(f);
来源：http://dali.yangfankeji.com/Article/details/gttmerzzdg.html

[S12] C：写文件
来源：http://dali.gzhubu.top/Article/details/gtwmxfvnmx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.wangdashe.top/Article/details/gtrimbanff.html

[S13] C：宏定义
来源：http://dali.svipenyu.cn/Article/details/gtwvalniwt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gogol.net.cn/Article/details/gtcpfcopjh.html

[S14] C：枚举
来源：http://dali.gaohongyu789.top/Article/details/gtwxuodmmq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yuanzhike.top/Article/details/gtbcpslnfl.html

[S15] C：类型转换
来源：http://dali.gogol.net.cn/Article/details/gtplgokqtf.html

(double) a / b
来源：http://dali.hysaishi.cn/Article/details/gtogfwmcjo.html

[S16] C：位操作置位
来源：http://dali.sweek.top/Article/details/gtfbrvjtls.html

x |= (1 << 3);
来源：http://dali.yangfankeji.com/Article/details/gtbzmclkbv.html

[S17] C：安全拼接字符串
来源：http://dali.hammf.cn/Article/details/gtrhxfbjzf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.gotoacloud.top/Article/details/gtgerfchgu.html

[S18] C：命令行参数
来源：http://dali.mhx1999.top/Article/details/gtoywbauni.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gtulenlvtr.html

[S19] C：快速排序
来源：http://dali.hongshengwenyu.top/Article/details/gtmedagujr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ywan-chungtsiang.top/Article/details/gterskyzkn.html

[S20] C：二分查找
来源：http://dali.yanxiufei.cn/Article/details/gtvbwerqoi.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cdnleiting.top/Article/details/gtbvqbczdn.html

[S21] C：字符类别判断
来源：http://dali.cashguo.top/Article/details/gtkikfbsrj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.chenjidiqi.icu/Article/details/gtmhiydtgn.html

[S22] C：字符串转数字
来源：http://dali.dianchejie.cn/Article/details/gtmdugbhwu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxsfbujcl.html

[S23] C：随机数
来源：http://dali.sweek.top/Article/details/gtuytfuggy.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.daria6918.cn/Article/details/gtqllgqkbe.html

[S24] C：获取本地时间
来源：http://dali.nwbrower.top/Article/details/gtqwwilkid.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.daria6918.cn/Article/details/gtbivgpgvx.html

[S25] C：内存拷贝
来源：http://dali.xuanzx.com/Article/details/gtcgvbsyaz.html

memcpy(dst, src, n);
来源：http://dali.hammf.cn/Article/details/gtnaiestpi.html

[S26] C：内存清零
来源：http://dali.kuanghao11.cn/Article/details/gtwwgdkmev.html

memset(a, 0, sizeof a);
来源：http://dali.iojbl.cn/Article/details/gtndwexsgk.html

[S27] C：定义常量
来源：http://dali.sysykeji.top/Article/details/gtcaeztsky.html

const double PI = 3.14159;
来源：http://dali.pengpengdd.cyou/Article/details/gtuqnidbcr.html

[S28] C：静态变量
来源：http://dali.hfpthk.cn/Article/details/gtqwavdqnd.html

static int counter = 0;
来源：http://dali.nwbrower.top/Article/details/gtuqhnmnnw.html

[S29] C：变参函数
来源：http://dali.sysykeji.top/Article/details/gtsvgprbra.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqwkqntmh.html

[S30] C：头文件保护
来源：http://dali.aizwys.cn/Article/details/gtzwguhhmb.html

#ifndef X_H
来源：http://dali.wangdashe.top/Article/details/gtghcgznby.html

#define X_H
来源：http://dali.yonumen.top/Article/details/gteibzfbvl.html

#endif
来源：http://dali.sufxvd.cn/Article/details/gtckauntts.html

[S31] C++：Hello World
来源：http://dali.andypj.xyz/Article/details/gttjrtncyb.html

#include <iostream>
来源：http://dali.cqqwz.cn/Article/details/gthjytcole.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.snrcjt.cn/Article/details/gtnauxptjq.html

[S32] C++：字符串
来源：http://dali.yanxiufei.cn/Article/details/gtmlzdgxqd.html

std::string s = "hi";  s += "!";
来源：http://dali.ydzc1.top/Article/details/gtmrworbax.html

[S33] C++：vector 增删
来源：http://dali.zhongyouzk.top/Article/details/gtlkegjdfr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yongpay.top/Article/details/gtslowjcja.html

[S34] C++：遍历 vector
来源：http://dali.kuanghao11.cn/Article/details/gtlqskbofd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xziqi.cn/Article/details/gtcmkzhdbr.html

[S35] C++：map
来源：http://dali.shzxlz.cn/Article/details/gtpzmdefwr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenzaomai.com/Article/details/gtkyvgqqrz.html

[S36] C++：unordered_map
来源：http://dali.xziqi.cn/Article/details/gtfbnwdjed.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.birdmap.top/Article/details/gtvlyaizdj.html

[S37] C++：set
来源：http://dali.pengpengdd.cyou/Article/details/gtmvwdfvwm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.tian-w.cn/Article/details/gteufjqpdr.html

[S38] C++：排序
来源：http://dali.havefunace.top/Article/details/gtyyzkgaht.html

std::sort(v.begin(), v.end());
来源：http://dali.andypj.xyz/Article/details/gtmrdrsqux.html

[S39] C++：自定义比较器排序
来源：http://dali.shzxlz.cn/Article/details/gttueuizqx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hnqzz.top/Article/details/gtrtzcgikz.html

[S40] C++：查找元素
来源：http://dali.jlsjyb.cn/Article/details/gttktpnfbc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhongyouzk.top/Article/details/gtwxiyxqik.html

[S41] C++：类与构造函数
来源：http://dali.nanxuanxn.top/Article/details/gttkyokgxe.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.wangshuangyany.cn/Article/details/gtirgoqfvt.html

[S42] C++：继承与虚函数
来源：http://dali.jqgfzy.top/Article/details/gtrmmgezft.html

class B : public Base { public: void f() override {} };
来源：http://dali.sxryk.cn/Article/details/gthybetgkg.html

[S43] C++：智能指针
来源：http://dali.daria6918.cn/Article/details/gtsgfqrwml.html

auto p = std::make_unique<int>(5);
来源：http://dali.gaohongyu789.top/Article/details/gtazqucrob.html

[S44] C++：引用传参
来源：http://dali.shuidangran.top/Article/details/gtxewrtpyt.html

void inc(int &x) { ++x; }
来源：http://dali.yuanzhike.top/Article/details/gtyxblnnli.html

[S45] C++：lambda
来源：http://dali.xuetiantiany.cn/Article/details/gterrtqnro.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gzhubu.top/Article/details/gtrraxvycp.html

[S46] C++：函数模板
来源：http://dali.aibaodan.cn/Article/details/gtgfmyacet.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhongyouzk.top/Article/details/gtopbaeeju.html

[S47] C++：结构化绑定遍历
来源：http://dali.redwolf501.top/Article/details/gtscdffvhk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jqgfzy.top/Article/details/gtjdmxyqsa.html

[S48] C++：逐行读文件
来源：http://dali.xuanzx.com/Article/details/gtnyiyncjh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jiagoushi.top/Article/details/gtaokofngc.html


<!-- 参考信息 -->