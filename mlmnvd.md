代发 wailian999

[Q78] 当前时间
来源：http://dali.jiagoushi.top/Article/details/gtisunfswc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.aizwys.cn/Article/details/gtvagjwcxa.html

[Q79] 字符串拼接
来源：http://dali.0kj1m.cn/Article/details/gtrcanunmi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hywenlv.cn/Article/details/gtdjoapumd.html

[Q80] 字符串截取
来源：http://dali.xziqi.cn/Article/details/gtyypwczpw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtanxuicgj.html

[Q81] 字符串替换
来源：http://dali.jianghu66.top/Article/details/gtxqfbibwc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtfhrmwevm.html

[Q82] 字符长度与字节长度
来源：http://dali.yj202588.top/Article/details/gtnjpxmnxo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.birdmap.top/Article/details/gtztfkkqep.html

[Q83] 大小写转换
来源：http://dali.yangfankeji.com/Article/details/gtivlzendn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtyxxrirwr.html

[Q84] 去除首尾空格
来源：http://dali.aizwys.cn/Article/details/gtrlviciat.html

SELECT TRIM(name) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtvzmomrzu.html

[Q85] 数值取整
来源：http://dali.cqqwz.cn/Article/details/gtutbohivv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.nanxuanxn.top/Article/details/gtbypfbxff.html

[Q86] 读取 JSON 字段
来源：http://dali.jiagoushi.top/Article/details/gtxfqzoolp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xylfe.cn/Article/details/gtwtytrxzw.html

[Q87] JSON 字段做条件
来源：http://dali.andypj.xyz/Article/details/gtfrnxsekw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xziqi.cn/Article/details/gtquukssio.html

[Q88] 行转列（条件聚合）
来源：http://dali.zdqjudy.top/Article/details/gtnwgaqddd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.guowangkeji.top/Article/details/gtjahxwbpp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zycfv.cn/Article/details/gtoaadbrbe.html

[Q89] 判断表是否存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqnnmnfbw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zdqjudy.top/Article/details/gtzbnweagi.html

[Q90] 生成序号列
来源：http://dali.xuanzx.com/Article/details/gtuiffbotm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tanke756.top/Article/details/gtheljpdku.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtcwjdrigx.html

R. Bash 专题
来源：http://dali.hysaishi.cn/Article/details/gtchkvqryp.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtcnhsbwdi.html

[R01] shebang 与严格模式
来源：http://dali.svipenyu.cn/Article/details/gtsqbtmoza.html

#!/usr/bin/env bash
来源：http://dali.nanxinkj.top/Article/details/gtpnhmwnvd.html

set -euo pipefail
来源：http://dali.jiagoushi.top/Article/details/gtxcatadws.html

[R02] 变量赋值与使用
来源：http://dali.gzhubu.top/Article/details/gtxkmfjysh.html

name="Tom"; echo "$name"
来源：http://dali.xuanzx.com/Article/details/gtuptkwidu.html

[R03] 只读变量
来源：http://dali.mhx1999.top/Article/details/gthbcouzak.html

readonly PI=3.14
来源：http://dali.nanxinkj.top/Article/details/gtmfxwknvi.html

[R04] 位置参数
来源：http://dali.jyoumei.cn/Article/details/gteefbkrnb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jlsjyb.cn/Article/details/gtgmglafpv.html

[R05] 参数默认值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtowdywakh.html

name="${1:-default}"
来源：http://dali.zhoulong.xyz/Article/details/gtknroxreo.html

[R06] 判断命令是否存在
来源：http://dali.xuanzx.com/Article/details/gtgbzjrtnk.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jiagoushi.top/Article/details/gtcgdfopkb.html

[R07] if 判断文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrceipgyt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jianghu66.top/Article/details/gtrnckcfzv.html

[R08] 数值比较
来源：http://dali.ivvv.top/Article/details/gtelyyupho.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jinqigufen.top/Article/details/gtjazurnow.html

[R09] 字符串比较
来源：http://dali.guannengcc.top/Article/details/gtfggnbutx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ydzc1.top/Article/details/gtyqrxinhb.html

[R10] 正则匹配
来源：http://dali.meibo888.top/Article/details/gtivuukmxy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zycfv.cn/Article/details/gtnxjvtnfz.html

[R11] case 多分支
来源：http://dali.tianlin.xyz/Article/details/gtvyaoxsmm.html

case "$1" in
来源：http://dali.havefunace.top/Article/details/gtkbwveoyn.html

start) echo "启动" ;;
来源：http://dali.kuanghao11.cn/Article/details/gthjbayzzp.html

stop)  echo "停止" ;;
来源：http://dali.gaohongyu789.top/Article/details/gtqckfmnij.html

*)     echo "未知命令" ;;
来源：http://dali.sweek.top/Article/details/gtpjmnnvwc.html

esac
来源：http://dali.316326.xyz/Article/details/gtcnfvvwxr.html

[R12] for 遍历文件
来源：http://dali.yonumen.top/Article/details/gtndkgjetf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.guannengcc.top/Article/details/gtlaiuatgj.html

[R13] for 计数循环
来源：http://dali.yanxiufei.cn/Article/details/gtynxkwdem.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yonumen.top/Article/details/gtoqsyspke.html

[R14] C 风格 for
来源：http://dali.chenzaomai.com/Article/details/gteksvxggw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhengqikj.top/Article/details/gtlbssrpoh.html

[R15] while 逐行读文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtnsgbrixn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hnxiangtu.top/Article/details/gtieyiequs.html

[R16] until 等待条件
来源：http://dali.dashuyun.cn/Article/details/gtfjeddrrn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.fzhhl.top/Article/details/gtgqiwnczo.html

[R17] 数组定义与取值
来源：http://dali.316326.xyz/Article/details/gtgfeqpwip.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.gzhubu.top/Article/details/gtdwgeurpf.html

[R18] 遍历数组
来源：http://dali.zhongyouzk.top/Article/details/gtzavvuadm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yueranfly.top/Article/details/gtwukzolju.html

[R19] 数组长度
来源：http://dali.zhoulong.xyz/Article/details/gtcpzxvvla.html

echo "${#arr[@]}"
来源：http://dali.svipenyu.cn/Article/details/gtynccaqux.html

[R20] 关联数组（字典）
来源：http://dali.pycfn.com/Article/details/gtqonivfez.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yj202588.top/Article/details/gtydiwahnh.html

[R21] 字符串长度
来源：http://dali.chenjidiqi.icu/Article/details/gtlxwujuwt.html

echo "${#s}"
来源：http://dali.daxiang520.top/Article/details/gtwroxswje.html

[R22] 截取子串
来源：http://dali.xinyue.icu/Article/details/gtdpdbfmir.html

echo "${s:0:5}"
来源：http://dali.gotoacloud.top/Article/details/gtjldpfcaj.html

[R23] 字符串替换
来源：http://dali.ydzc1.top/Article/details/gtjvbfqiul.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jianghu66.top/Article/details/gtwiqgjeev.html

[R24] 大小写转换
来源：http://dali.jyoumei.cn/Article/details/gttkzcxoqi.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhiwuduotai.top/Article/details/gtpvdyaepb.html

[R25] 去后缀 / 去前缀
来源：http://dali.yangfankeji.com/Article/details/gtfyaqbcsc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.sysykeji.top/Article/details/gtvnvmuedx.html

[R26] 命令替换
来源：http://dali.sweek.top/Article/details/gtdecxxqip.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gtzqkyudwd.html

[R27] 算术展开
来源：http://dali.cashguo.top/Article/details/gtfxuaxouk.html

echo $((1 + 2 * 3))
来源：http://dali.jinghuilouyu.cn/Article/details/gtrahqfsox.html

[R28] 浮点运算
来源：http://dali.snrcjt.cn/Article/details/gtwwwmcffc.html

echo "scale=2; 10/3" | bc
来源：http://dali.sysykeji.top/Article/details/gtkbkevffn.html

[R29] 定义函数
来源：http://dali.smart0.xyz/Article/details/gtarmaiujq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.nwbrower.top/Article/details/gtbnybksby.html

[R30] 函数返回状态码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtupkfmfwn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cucudq.cn/Article/details/gtxhnzqlsd.html

[R31] 局部变量
来源：http://dali.shangyingyoupin.top/Article/details/gtawternch.html

f() { local x=1; echo "$x"; }
来源：http://dali.chenlongwang.top/Article/details/gttiikmmig.html

[R32] 参数个数校验
来源：http://dali.jiagoushi.top/Article/details/gtobxrnyqt.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yj202588.top/Article/details/gtwqnjicnx.html

[R33] 捕获错误并提示行号
来源：http://dali.pycfn.com/Article/details/gtczjxyhgr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jqgfzy.top/Article/details/gtbchxijau.html

[R34] 退出时清理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqnkhblpv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sweek.top/Article/details/gtvzijpzog.html

[R35] 后台执行并等待
来源：http://dali.iojbl.cn/Article/details/gtkhjwrkqk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gogol.net.cn/Article/details/gtqwmsykod.html

[R36] 并发执行多个任务
来源：http://dali.hnqzz.top/Article/details/gtqbepbtrk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yuxming.cn/Article/details/gtxsmiurrf.html

[R37] 把输出赋给变量
来源：http://dali.nwbrower.top/Article/details/gtubtjvvni.html

files=$(ls -1)
来源：http://dali.yueranfly.top/Article/details/gtkmepzzya.html

[R38] 管道串联
来源：http://dali.pycfn.com/Article/details/gtdzqacfvo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hongshengwenyu.top/Article/details/gtoqqybinn.html

[R39] 重定向标准输出与错误
来源：http://dali.shangyingyoupin.top/Article/details/gtovlbqioy.html

cmd > out.log 2>&1
来源：http://dali.ybcxt.top/Article/details/gtnhvxqaws.html

[R40] 追加写日志
来源：http://dali.ydzc1.top/Article/details/gtcwposfec.html

echo "log" >> out.log
来源：http://dali.yongpay.top/Article/details/gtrktwbeuh.html

[R41] 丢弃输出
来源：http://dali.jianghu66.top/Article/details/gtlajejbkw.html

cmd >/dev/null 2>&1
来源：http://dali.yangfankeji.com/Article/details/gtyidpgnmd.html

[R42] 输入重定向
来源：http://dali.xuanzx.com/Article/details/gtcqudelxy.html

wc -l < a.txt
来源：http://dali.cdnleiting.top/Article/details/gtmfxvsxjq.html

[R43] 按名字查找文件
来源：http://dali.jiagoushi.top/Article/details/gtjnniiwoo.html

find . -name "*.log" -type f
来源：http://dali.zhixingplan.top/Article/details/gtuusqsufu.html

[R44] 按修改时间查找
来源：http://dali.andypj.xyz/Article/details/gtsgqfnirs.html

find . -mtime -7 -type f
来源：http://dali.havefunace.top/Article/details/gtcervwcyg.html

[R45] 批量删除
来源：http://dali.bjfxy.top/Article/details/gtmafwogue.html

find . -name "*.tmp" -delete
来源：http://dali.feifeiyinyue.top/Article/details/gtxyrrzvoj.html

[R46] 递归替换文件内容
来源：http://dali.zhaomingkeji.xyz/Article/details/gtimjqomhs.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zycfv.cn/Article/details/gtyhlmqzaa.html

[R47] sed 单行替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbvbrwvif.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hfpthk.cn/Article/details/gtfagcbjan.html

[R48] awk 取指定列
来源：http://dali.fzhhl.top/Article/details/gtkqaaqyvw.html

awk '{print $1, $3}' a.txt
来源：http://dali.cdnleiting.top/Article/details/gtxxsoztjq.html

[R49] awk 带条件
来源：http://dali.dianchejie.cn/Article/details/gtknftrbar.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cashguo.top/Article/details/gtacswlqkq.html

[R50] awk 求和
来源：http://dali.jinqigfzy.top/Article/details/gtzvefouzl.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ydzc1.top/Article/details/gtdxtixfas.html

[R51] 排序去重取前几
来源：http://dali.0kj1m.cn/Article/details/gtktzgrbpj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvcwsglqb.html

[R52] 统计行数
来源：http://dali.jyoumei.cn/Article/details/gtphfxupel.html

wc -l a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtztkppjvu.html

[R53] 查看文件头与实时尾
来源：http://dali.zdqjudy.top/Article/details/gthfdswzuj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gogol.net.cn/Article/details/gtfqsvdbia.html

[R54] 比较两个文件
来源：http://dali.gzhubu.top/Article/details/gtxcbhostv.html

diff a.txt b.txt
来源：http://dali.xinyue.icu/Article/details/gtdrmqmblk.html

[R55] 压缩与解压
来源：http://dali.cdnleiting.top/Article/details/gtrzhwnkyt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhengqikj.top/Article/details/gthqmdcazp.html

[R56] 远程拷贝
来源：http://dali.meibo888.top/Article/details/gtkuyxmvxk.html

scp file user@host:/path/
来源：http://dali.gzhubu.top/Article/details/gtyfxhonhz.html

[R57] 远程执行命令
来源：http://dali.cucudq.cn/Article/details/gtnmjizkqc.html

ssh user@host 'uptime'
来源：http://dali.jinghuilouyu.cn/Article/details/gtswrndled.html

[R58] 下载文件
来源：http://dali.yangfankeji.com/Article/details/gtodtjblem.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yj20258.top/Article/details/gtpbuiavia.html

[R59] 发 POST JSON
来源：http://dali.guowangkeji.top/Article/details/gtfivmzawq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.nwbrower.top/Article/details/gtnjmdvhxv.html

[R60] 只看 HTTP 状态码
来源：http://dali.yanxiufei.cn/Article/details/gtvjwytikx.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.havefunace.top/Article/details/gttyacykwr.html

[R61] 磁盘占用
来源：http://dali.yvedp.cn/Article/details/gtwbivorno.html

df -h;  du -sh *
来源：http://dali.yuanzhike.top/Article/details/gtieibfada.html

[R62] 找最占空间的文件
来源：http://dali.redwolf501.top/Article/details/gtomwuwadv.html

du -ah . | sort -rh | head -10
来源：http://dali.sxryk.cn/Article/details/gtnfmgutej.html

[R63] 内存与进程
来源：http://dali.quarkkingdee.top/Article/details/gtwnmbvwxu.html

free -h;  ps aux | grep nginx
来源：http://dali.yj20258888.top/Article/details/gteccppcut.html

[R64] 结束进程
来源：http://dali.wangdashe.top/Article/details/gtfkdkhazx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xinyue.icu/Article/details/gthivmdtga.html

[R65] 查看端口占用
来源：http://dali.yangfankeji.com/Article/details/gtcxvjahyw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jianghu66.top/Article/details/gtioylwojj.html

[R66] 定时任务
来源：http://dali.xinyue.icu/Article/details/gtgiokiomv.html

crontab -e;  crontab -l
来源：http://dali.yvedp.cn/Article/details/gtfactwgpi.html

[R67] 生成随机十六进制串
来源：http://dali.quarkkingdee.top/Article/details/gtjqjhznnt.html

openssl rand -hex 16
来源：http://dali.feifeiyinyue.top/Article/details/gtdrsfgbkm.html

[R68] 计算文件校验值
来源：http://dali.daxiang520.top/Article/details/gtxdtieyda.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hysaishi.cn/Article/details/gtttvlwgig.html

[R69] 生成随机密码
来源：http://dali.yonumen.top/Article/details/gtabofefzf.html

head -c 16 /dev/urandom | base64
来源：http://dali.0kj1m.cn/Article/details/gtwlpgtxjg.html

[R70] 时间戳与互转
来源：http://dali.xziqi.cn/Article/details/gtuxsuzxlc.html

date +%s;  date -d @1700000000
来源：http://dali.xziqi.cn/Article/details/gtczpuznsd.html

[R71] 日期格式化
来源：http://dali.cheryme.top/Article/details/gtqcugdwft.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yuxming.cn/Article/details/gtfciuiyve.html

[R72] 等待端口就绪
来源：http://dali.jinqigfzy.top/Article/details/gtbusroimo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.daria6918.cn/Article/details/gtjpttlmfi.html

[R73] 分割大日志
来源：http://dali.havefunace.top/Article/details/gtgrpgsvdv.html

split -l 1000 big.log part_
来源：http://dali.xuetiantiany.cn/Article/details/gtsfmxuiln.html

[R74] 批量重命名
来源：http://dali.zhongyouzk.top/Article/details/gtiuiakcla.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtccyzgvnr.html

[R75] 导出环境变量
来源：http://dali.zhengqikj.top/Article/details/gtkvsivvnw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.vqdsnc.cn/Article/details/gtwjynmjot.html

[R76] 使用临时文件
来源：http://dali.mhx1999.top/Article/details/gtrbrncgzg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj20258888.top/Article/details/gtjryttyvi.html

[R77] 读取用户输入
来源：http://dali.hywenlv.cn/Article/details/gtafrhcfbf.html

read -rp "请输入: " ans
来源：http://dali.hongshengwenyu.top/Article/details/gturskkziv.html

[R78] 交互式菜单
来源：http://dali.jiagoushi.top/Article/details/gtkwmhhgis.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.pycfn.com/Article/details/gtsidejvqh.html

[R79] 解析命令行选项
来源：http://dali.hnqzz.top/Article/details/gtzhrsjswn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jianghu66.top/Article/details/gtpnvhgqsd.html

[R80] 查看脚本执行耗时
来源：http://dali.zhengqikj.top/Article/details/gtxonzgdty.html

time ./run.sh
来源：http://dali.zhiwuduotai.top/Article/details/gtjaqzsuqc.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtitpauvfg.html

S. C / C++ 专题
来源：http://dali.mhx1999.top/Article/details/gtkkcwutib.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtigskmnqy.html

[S01] C：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdlfmvpbl.html

#include <stdio.h>
来源：http://dali.yj202588.top/Article/details/gteobmbaaj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jqgfzy.top/Article/details/gtmunvtfrs.html

[S02] C：变量与格式化输出
来源：http://dali.jinqigfzy.top/Article/details/gtfkmiqzln.html

int a = 10; printf("%d\n", a);
来源：http://dali.xuanzx.com/Article/details/gtznnspgwl.html

[S03] C：读入整数
来源：http://dali.pengpengdd.cyou/Article/details/gtvllbkmdi.html

int x; scanf("%d", &x);
来源：http://dali.birdmap.top/Article/details/gtmdkynsqg.html

[S04] C：字符串复制
来源：http://dali.shanyushiyangkeji.top/Article/details/gteuwpythq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cdnleiting.top/Article/details/gtwmezztyc.html

[S05] C：字符串长度
来源：http://dali.jqgufenzy.top/Article/details/gtlesfexaz.html

strlen(s)
来源：http://dali.zycfv.cn/Article/details/gtrbgzpluu.html

[S06] C：字符串比较
来源：http://dali.mhx1999.top/Article/details/gtljtvwhuf.html

strcmp(a, b) == 0
来源：http://dali.yuanzhike.top/Article/details/gtmtogfxbr.html

[S07] C：数组遍历求和
来源：http://dali.yangfankeji.com/Article/details/gtmhsawctf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gaohongyu789.top/Article/details/gtckcxesdq.html

[S08] C：动态内存分配与释放
来源：http://dali.sysykeji.top/Article/details/gtoamvjrjf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.svipenyu.cn/Article/details/gtuphvfkyn.html

[S09] C：结构体定义与初始化
来源：http://dali.gzhubu.top/Article/details/gtrhtutjiw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.redwolf501.top/Article/details/gttgyjdqhy.html

[S10] C：指针与解引用
来源：http://dali.xziqi.cn/Article/details/gtjhcsgrcc.html

int *p = &a;  *p = 5;
来源：http://dali.jinyuanbaomall.cn/Article/details/gttnbsgmpq.html

[S11] C：逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gtnyohmhce.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuitysyzs.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jiagoushi.top/Article/details/gtwdqxykun.html

fclose(f);
来源：http://dali.yongpay.top/Article/details/gtdqvakdes.html

[S12] C：写文件
来源：http://dali.gotoacloud.top/Article/details/gtndetapzg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jianghu66.top/Article/details/gtczjochin.html

[S13] C：宏定义
来源：http://dali.guannengcc.top/Article/details/gtvucibfhg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.svipenyu.cn/Article/details/gtpumuyqld.html

[S14] C：枚举
来源：http://dali.cdnleiting.top/Article/details/gtfjnmixem.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gtpioorcdc.html

[S15] C：类型转换
来源：http://dali.jinghuilouyu.cn/Article/details/gtlucspvle.html

(double) a / b
来源：http://dali.fzhhl.top/Article/details/gtyaqqhtvd.html

[S16] C：位操作置位
来源：http://dali.mhx1999.top/Article/details/gtakkgpana.html

x |= (1 << 3);
来源：http://dali.iojbl.cn/Article/details/gtlagfmweh.html

[S17] C：安全拼接字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtepkjpbup.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.smart0.xyz/Article/details/gtxahhoflu.html

[S18] C：命令行参数
来源：http://dali.xziqi.cn/Article/details/gtguhizpwt.html

int main(int argc, char **argv)
来源：http://dali.chenjidiqi.icu/Article/details/gtgsbpkzhv.html

[S19] C：快速排序
来源：http://dali.zhiwuduotai.top/Article/details/gtlgbyhyvd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.smart0.xyz/Article/details/gtxbupjnkg.html

[S20] C：二分查找
来源：http://dali.aibaodan.cn/Article/details/gtpymerhtg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.andypj.xyz/Article/details/gtjofcfaqk.html

[S21] C：字符类别判断
来源：http://dali.yongpay.top/Article/details/gtjdefiwik.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.aizwys.cn/Article/details/gtbspbvopg.html

[S22] C：字符串转数字
来源：http://dali.ehwqpu.com/Article/details/gtkdfvayzp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinghuilouyu.cn/Article/details/gtwnhxwmtn.html

[S23] C：随机数
来源：http://dali.chenzaomai.com/Article/details/gtqhohreti.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shanyushiyangkeji.top/Article/details/gttoqitmqn.html

[S24] C：获取本地时间
来源：http://dali.haohaochexian.top/Article/details/gtalzbwfmu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jlsjyb.cn/Article/details/gtveorjluo.html

[S25] C：内存拷贝
来源：http://dali.meibo888.top/Article/details/gtysdpnfcf.html

memcpy(dst, src, n);
来源：http://dali.fzhhl.top/Article/details/gtrrhjyqut.html

[S26] C：内存清零
来源：http://dali.meibo888.top/Article/details/gtuwqkkfbm.html

memset(a, 0, sizeof a);
来源：http://dali.xuanzx.com/Article/details/gtvuvlwdqv.html

[S27] C：定义常量
来源：http://dali.xziqi.cn/Article/details/gtvjxnaegg.html

const double PI = 3.14159;
来源：http://dali.pengpengdd.cyou/Article/details/gtqgiyyula.html

[S28] C：静态变量
来源：http://dali.jlsjyb.cn/Article/details/gtjopzoihu.html

static int counter = 0;
来源：http://dali.pengpengdd.cyou/Article/details/gtkeubqheg.html

[S29] C：变参函数
来源：http://dali.feifeiyinyue.top/Article/details/gtxtdnmshb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hysaishi.cn/Article/details/gtkxosympq.html

[S30] C：头文件保护
来源：http://dali.guowangkeji.top/Article/details/gtzpbuphoe.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gtxvbzhmda.html

#define X_H
来源：http://dali.daria6918.cn/Article/details/gtifhfkpcv.html

#endif
来源：http://dali.mhx1999.top/Article/details/gtistizlgj.html

[S31] C++：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gtgpjmsjkb.html

#include <iostream>
来源：http://dali.xziqi.cn/Article/details/gteoxhyxnz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.mhx1999.top/Article/details/gtzfdfveew.html

[S32] C++：字符串
来源：http://dali.aibaodan.cn/Article/details/gtuqmjwwog.html

std::string s = "hi";  s += "!";
来源：http://dali.jinqigufen.top/Article/details/gtkklqygxn.html

[S33] C++：vector 增删
来源：http://dali.tanke756.top/Article/details/gtxmkdihyx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ybcxt.top/Article/details/gtjlmnfexk.html

[S34] C++：遍历 vector
来源：http://dali.andypj.xyz/Article/details/gtvpqbquxv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.havefunace.top/Article/details/gtxcchssrt.html

[S35] C++：map
来源：http://dali.yj20258888.top/Article/details/gtvswbngmy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cheryme.top/Article/details/gtojlngybh.html

[S36] C++：unordered_map
来源：http://dali.guowangkeji.top/Article/details/gtyqlriuhg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yvedp.cn/Article/details/gtkexiorda.html

[S37] C++：set
来源：http://dali.zhongyouzk.top/Article/details/gtcpfruzrr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.wangshuangyany.cn/Article/details/gtelcassvk.html

[S38] C++：排序
来源：http://dali.cashguo.top/Article/details/gthmukxzfb.html

std::sort(v.begin(), v.end());
来源：http://dali.cashguo.top/Article/details/gtvkhkfatb.html

[S39] C++：自定义比较器排序
来源：http://dali.yuanzhike.top/Article/details/gtrervqfth.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.snrcjt.cn/Article/details/gtwmlhnssw.html

[S40] C++：查找元素
来源：http://dali.0kj1m.cn/Article/details/gtdjkhhixc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.quarkkingdee.top/Article/details/gtkqrnodgm.html

[S41] C++：类与构造函数
来源：http://dali.hfpthk.cn/Article/details/gtrlvioach.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.nanxuanxn.top/Article/details/gttsndeehg.html

[S42] C++：继承与虚函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaffgmgsn.html

class B : public Base { public: void f() override {} };
来源：http://dali.wangshuangyany.cn/Article/details/gtfqhvjbns.html

[S43] C++：智能指针
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbebtwlzi.html

auto p = std::make_unique<int>(5);
来源：http://dali.mhx1999.top/Article/details/gtgnxqfkbt.html

[S44] C++：引用传参
来源：http://dali.hongshengwenyu.top/Article/details/gtivxjsqlg.html

void inc(int &x) { ++x; }
来源：http://dali.guowangkeji.top/Article/details/gtbzaduqcn.html

[S45] C++：lambda
来源：http://dali.chenlongwang.top/Article/details/gtxguhkjbr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.chenzaomai.com/Article/details/gtctosbvar.html

[S46] C++：函数模板
来源：http://dali.yongpay.top/Article/details/gtprbmybmr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.meibo888.top/Article/details/gtxugbiwos.html

[S47] C++：结构化绑定遍历
来源：http://dali.pycfn.com/Article/details/gtkemjhiom.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.kuanghao11.cn/Article/details/gtmeeiaioc.html

[S48] C++：逐行读文件
来源：http://dali.cucudq.cn/Article/details/gtcxazyopt.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.daria6918.cn/Article/details/gtxmyqczxk.html


<!-- 参考信息 -->