代发 wailian999

[Q76] 按天统计
来源：http://dali.jinghuilouyu.cn/Article/details/gtoloaywhq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shanyushiyangtech.top/Article/details/gtiaxkzcsg.html

[Q77] 时间加减
来源：http://dali.jqgfzy.top/Article/details/gtpvpofjtj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.birdmap.top/Article/details/gtolpkmlpm.html

[Q78] 当前时间
来源：http://dali.yueranfly.top/Article/details/gtsexfsdva.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xylfe.cn/Article/details/gtqotrhwhu.html

[Q79] 字符串拼接
来源：http://dali.cdnleiting.top/Article/details/gtlersohdh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.daria6918.cn/Article/details/gtvceslnoy.html

[Q80] 字符串截取
来源：http://dali.sweek.top/Article/details/gtuxqsekfy.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ivvv.top/Article/details/gtsleqerhu.html

[Q81] 字符串替换
来源：http://dali.tian-w.cn/Article/details/gtdklutjaf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.316326.xyz/Article/details/gtjbtgkprv.html

[Q82] 字符长度与字节长度
来源：http://dali.yj202588.top/Article/details/gtucqkucuv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtkbwgahzp.html

[Q83] 大小写转换
来源：http://dali.chenzaomai.com/Article/details/gtkprghryc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtsjcdtuaq.html

[Q84] 去除首尾空格
来源：http://dali.quarkkingdee.top/Article/details/gttdxblzny.html

SELECT TRIM(name) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtoeyiqvdx.html

[Q85] 数值取整
来源：http://dali.wangshuangyany.cn/Article/details/gthlqaxgej.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhongyouzk.top/Article/details/gtnjjbgxlf.html

[Q86] 读取 JSON 字段
来源：http://dali.9152youxi.cn/Article/details/gtfjycjazw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ydzc1.top/Article/details/gtuybcpmih.html

[Q87] JSON 字段做条件
来源：http://dali.cucudq.cn/Article/details/gtbdbwropn.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zdqjudy.top/Article/details/gtzrtphthl.html

[Q88] 行转列（条件聚合）
来源：http://dali.jyoumei.cn/Article/details/gtgcsxoauc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shanyushiyangkeji.top/Article/details/gttqvrzsio.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtirpqoioa.html

[Q89] 判断表是否存在
来源：http://dali.9152youxi.cn/Article/details/gtxxfpryfp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zycfv.cn/Article/details/gtgehzltgh.html

[Q90] 生成序号列
来源：http://dali.pengpengdd.cyou/Article/details/gtspxffmtk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gzhubu.top/Article/details/gtvftmjwfj.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtqypgggko.html

R. Bash 专题
来源：http://dali.zhoulong.xyz/Article/details/gtbfnsrxss.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtsouvwgxs.html

[R01] shebang 与严格模式
来源：http://dali.yangfankeji.com/Article/details/gturkftetn.html

#!/usr/bin/env bash
来源：http://dali.birdmap.top/Article/details/gtnxouzxjt.html

set -euo pipefail
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxxmakwvm.html

[R02] 变量赋值与使用
来源：http://dali.jiagoushi.top/Article/details/gtzvhhrdfg.html

name="Tom"; echo "$name"
来源：http://dali.tianlin.xyz/Article/details/gtyijekgvl.html

[R03] 只读变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbailmovp.html

readonly PI=3.14
来源：http://dali.gotoacloud.top/Article/details/gtoplwgtmf.html

[R04] 位置参数
来源：http://dali.yonumen.top/Article/details/gtsruhnbnj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinqigfzy.top/Article/details/gtioclqpci.html

[R05] 参数默认值
来源：http://dali.dianchejie.cn/Article/details/gtdkacpnan.html

name="${1:-default}"
来源：http://dali.redwolf501.top/Article/details/gtnogorpja.html

[R06] 判断命令是否存在
来源：http://dali.yonumen.top/Article/details/gtpxdqaqwu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shuidangran.top/Article/details/gtjvzhnhjy.html

[R07] if 判断文件
来源：http://dali.zdqjudy.top/Article/details/gtnshykgvy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hnqzz.top/Article/details/gtxfchlvnb.html

[R08] 数值比较
来源：http://dali.ybcxt.top/Article/details/gtpifgajpc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jinyuanbaomall.cn/Article/details/gtljxnzgln.html

[R09] 字符串比较
来源：http://dali.vqdsnc.cn/Article/details/gtzuajhobo.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj20258.top/Article/details/gtbhocvttt.html

[R10] 正则匹配
来源：http://dali.xylfe.cn/Article/details/gtovktutun.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jqgfzy.top/Article/details/gtnemydzuq.html

[R11] case 多分支
来源：http://dali.xinyue.icu/Article/details/gtsfxjwpjk.html

case "$1" in
来源：http://dali.haohaochexian.top/Article/details/gtmzbjgetc.html

start) echo "启动" ;;
来源：http://dali.zhongyouzk.top/Article/details/gthacsndkc.html

stop)  echo "停止" ;;
来源：http://dali.tanke756.top/Article/details/gtebdpyujv.html

*)     echo "未知命令" ;;
来源：http://dali.jlsjyb.cn/Article/details/gtjjfpgsfu.html

esac
来源：http://dali.daria6918.cn/Article/details/gtqurfstsi.html

[R12] for 遍历文件
来源：http://dali.pengpengdd.cyou/Article/details/gtbewxlvfg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmrtazvtn.html

[R13] for 计数循环
来源：http://dali.hammf.cn/Article/details/gtjqtvdybc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.chenlongwang.top/Article/details/gtghtwafrv.html

[R14] C 风格 for
来源：http://dali.yueranfly.top/Article/details/gtxjivcmcc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yangfankeji.com/Article/details/gtdwjwtxaa.html

[R15] while 逐行读文件
来源：http://dali.sxryk.cn/Article/details/gttsumijiu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbmpbydaj.html

[R16] until 等待条件
来源：http://dali.kuanghao11.cn/Article/details/gttdapqgme.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cheryme.top/Article/details/gtnhplujaf.html

[R17] 数组定义与取值
来源：http://dali.havefunace.top/Article/details/gtlofexwgz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xuanzx.com/Article/details/gtrmqiofym.html

[R18] 遍历数组
来源：http://dali.cheryme.top/Article/details/gtxotfidut.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.nanxinkj.top/Article/details/gtjgzdgpdo.html

[R19] 数组长度
来源：http://dali.kuanghao11.cn/Article/details/gtywcwxopf.html

echo "${#arr[@]}"
来源：http://dali.jianghu66.top/Article/details/gtidmjsklj.html

[R20] 关联数组（字典）
来源：http://dali.jyoumei.cn/Article/details/gtxafrzhud.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.fzhhl.top/Article/details/gtakmoqkvy.html

[R21] 字符串长度
来源：http://dali.snrcjt.cn/Article/details/gtlxtzyrsf.html

echo "${#s}"
来源：http://dali.fzhhl.top/Article/details/gtpizxvgdk.html

[R22] 截取子串
来源：http://dali.jqgufenzy.top/Article/details/gtapcbidzm.html

echo "${s:0:5}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtohxmjsup.html

[R23] 字符串替换
来源：http://dali.haohaochexian.top/Article/details/gtgvpudike.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cucudq.cn/Article/details/gtzkegetwx.html

[R24] 大小写转换
来源：http://dali.chenlongwang.top/Article/details/gtmphbmlxh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.nwbrower.top/Article/details/gtmfdytivh.html

[R25] 去后缀 / 去前缀
来源：http://dali.xuanzx.com/Article/details/gtjclicbpp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhixingplan.top/Article/details/gtcofjtpdv.html

[R26] 命令替换
来源：http://dali.tanke756.top/Article/details/gtxurnltfp.html

now=$(date +%F); echo "$now"
来源：http://dali.shangyingyoupin.top/Article/details/gtlwscknsj.html

[R27] 算术展开
来源：http://dali.zycfv.cn/Article/details/gtqlcxyvjr.html

echo $((1 + 2 * 3))
来源：http://dali.yueranfly.top/Article/details/gtqbhpjmut.html

[R28] 浮点运算
来源：http://dali.ivvv.top/Article/details/gtzabmfdhh.html

echo "scale=2; 10/3" | bc
来源：http://dali.hnxiangtu.top/Article/details/gtxuycwkot.html

[R29] 定义函数
来源：http://dali.pycfn.com/Article/details/gtwfdxbxge.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.chenzaomai.com/Article/details/gtrukunqrn.html

[R30] 函数返回状态码
来源：http://dali.ppjwa.cn/Article/details/gtwrqufzdv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zdqjudy.top/Article/details/gtbigigbnt.html

[R31] 局部变量
来源：http://dali.mhx1999.top/Article/details/gthrfeorxw.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhengqikj.top/Article/details/gtdlqzckbv.html

[R32] 参数个数校验
来源：http://dali.ehwqpu.com/Article/details/gtwjflvwwc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.9152youxi.cn/Article/details/gtsdeitsmt.html

[R33] 捕获错误并提示行号
来源：http://dali.aibaodan.cn/Article/details/gtzzqeycfu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jinqigfzy.top/Article/details/gtchrfsbss.html

[R34] 退出时清理
来源：http://dali.jinqigufen.top/Article/details/gtckknxsjz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigufen.top/Article/details/gtauihewto.html

[R35] 后台执行并等待
来源：http://dali.sweek.top/Article/details/gtbgxrxmrw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhongyouzk.top/Article/details/gtryitqzdn.html

[R36] 并发执行多个任务
来源：http://dali.fzhhl.top/Article/details/gtthaavoig.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtprixmztx.html

[R37] 把输出赋给变量
来源：http://dali.gzhubu.top/Article/details/gtjdmkwgqt.html

files=$(ls -1)
来源：http://dali.tianlin.xyz/Article/details/gtxzqlxvhl.html

[R38] 管道串联
来源：http://dali.haohaochexian.top/Article/details/gtlllrokwu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shanyushiyangtech.top/Article/details/gtmvuwqtev.html

[R39] 重定向标准输出与错误
来源：http://dali.mhx1999.top/Article/details/gtsgmzcifu.html

cmd > out.log 2>&1
来源：http://dali.andypj.xyz/Article/details/gtuajygmua.html

[R40] 追加写日志
来源：http://dali.cheryme.top/Article/details/gtyrfvftcb.html

echo "log" >> out.log
来源：http://dali.jqgufenzy.top/Article/details/gtdqewdkjo.html

[R41] 丢弃输出
来源：http://dali.shanyushiyangtech.top/Article/details/gtfpgbyeor.html

cmd >/dev/null 2>&1
来源：http://dali.xuanzx.com/Article/details/gtdjulnqzi.html

[R42] 输入重定向
来源：http://dali.jinyuanbaomall.cn/Article/details/gtscpgfssv.html

wc -l < a.txt
来源：http://dali.nwbrower.top/Article/details/gttzasnfel.html

[R43] 按名字查找文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtamvqptaz.html

find . -name "*.log" -type f
来源：http://dali.yj20258888.top/Article/details/gthypwrdet.html

[R44] 按修改时间查找
来源：http://dali.jinqigufen.top/Article/details/gtoblpdbnu.html

find . -mtime -7 -type f
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwdosheqt.html

[R45] 批量删除
来源：http://dali.cqqwz.cn/Article/details/gtikegermb.html

find . -name "*.tmp" -delete
来源：http://dali.zdqjudy.top/Article/details/gtpmobjqnf.html

[R46] 递归替换文件内容
来源：http://dali.smart0.xyz/Article/details/gtquydzuhc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.fzhhl.top/Article/details/gtcswuyypv.html

[R47] sed 单行替换
来源：http://dali.ehwqpu.com/Article/details/gtlkleuatt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.tian-w.cn/Article/details/gtnjgzmres.html

[R48] awk 取指定列
来源：http://dali.cashguo.top/Article/details/gtrvrseitm.html

awk '{print $1, $3}' a.txt
来源：http://dali.sxryk.cn/Article/details/gtlofvtvmt.html

[R49] awk 带条件
来源：http://dali.shzxlz.cn/Article/details/gtrkiktvae.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jiagoushi.top/Article/details/gtvuwidjgp.html

[R50] awk 求和
来源：http://dali.chenjidiqi.icu/Article/details/gtbelszkhu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxqcszpab.html

[R51] 排序去重取前几
来源：http://dali.wangdashe.top/Article/details/gtllvhwjhk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.0kj1m.cn/Article/details/gtkmpwweks.html

[R52] 统计行数
来源：http://dali.aizwys.cn/Article/details/gtxrxxeajt.html

wc -l a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtawibeohk.html

[R53] 查看文件头与实时尾
来源：http://dali.ppjwa.cn/Article/details/gtsqklbyxm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cheryme.top/Article/details/gtfbbyjutw.html

[R54] 比较两个文件
来源：http://dali.cucudq.cn/Article/details/gtnmebtzev.html

diff a.txt b.txt
来源：http://dali.ppjwa.cn/Article/details/gtswugaoce.html

[R55] 压缩与解压
来源：http://dali.hnxiangtu.top/Article/details/gtwpjjbokt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.wangdashe.top/Article/details/gtusgudwam.html

[R56] 远程拷贝
来源：http://dali.jqgfzy.top/Article/details/gtnesxhwxt.html

scp file user@host:/path/
来源：http://dali.haohaochexian.top/Article/details/gtiuupgzrc.html

[R57] 远程执行命令
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqlkuowjq.html

ssh user@host 'uptime'
来源：http://dali.pengpengdd.cyou/Article/details/gtuhzzqypo.html

[R58] 下载文件
来源：http://dali.ivvv.top/Article/details/gtelvbidsi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.feifeiyinyue.top/Article/details/gtkgrugeam.html

[R59] 发 POST JSON
来源：http://dali.ybcxt.top/Article/details/gtpgyvdnln.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ivvv.top/Article/details/gteofnozzd.html

[R60] 只看 HTTP 状态码
来源：http://dali.fzhhl.top/Article/details/gtxkjjyqbe.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ydzc1.top/Article/details/gtbejjkgtk.html

[R61] 磁盘占用
来源：http://dali.gaohongyu789.top/Article/details/gtaowqpkwo.html

df -h;  du -sh *
来源：http://dali.xuanzx.com/Article/details/gtswqaqshg.html

[R62] 找最占空间的文件
来源：http://dali.zdqjudy.top/Article/details/gtjztxkpld.html

du -ah . | sort -rh | head -10
来源：http://dali.haohaochexian.top/Article/details/gtfrmbmdnc.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gtjeivxuru.html

free -h;  ps aux | grep nginx
来源：http://dali.jianghu66.top/Article/details/gtzjuqdsbv.html

[R64] 结束进程
来源：http://dali.wangshuangyany.cn/Article/details/gtwehgrilo.html

kill -9 $(pgrep -f app.py)
来源：http://dali.smart0.xyz/Article/details/gtxnhnhanh.html

[R65] 查看端口占用
来源：http://dali.shzxlz.cn/Article/details/gtuslrvzpk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.iojbl.cn/Article/details/gtucvruggg.html

[R66] 定时任务
来源：http://dali.xziqi.cn/Article/details/gtvuksiplj.html

crontab -e;  crontab -l
来源：http://dali.0kj1m.cn/Article/details/gtyfnmeort.html

[R67] 生成随机十六进制串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdadswcbd.html

openssl rand -hex 16
来源：http://dali.aibaodan.cn/Article/details/gtyafarrud.html

[R68] 计算文件校验值
来源：http://dali.shuidangran.top/Article/details/gttzqgomfr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtstbtcang.html

[R69] 生成随机密码
来源：http://dali.sweek.top/Article/details/gtlkicyghp.html

head -c 16 /dev/urandom | base64
来源：http://dali.haohaochexian.top/Article/details/gtjgotcswl.html

[R70] 时间戳与互转
来源：http://dali.ywan-chungtsiang.top/Article/details/gthxyxkhnq.html

date +%s;  date -d @1700000000
来源：http://dali.cheryme.top/Article/details/gtlvcyhpcm.html

[R71] 日期格式化
来源：http://dali.zdqjudy.top/Article/details/gttmutltns.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj20258.top/Article/details/gtkmykyblz.html

[R72] 等待端口就绪
来源：http://dali.gzhubu.top/Article/details/gtiemgwajc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ivvv.top/Article/details/gtpcfqbdkh.html

[R73] 分割大日志
来源：http://dali.fzhhl.top/Article/details/gtpbinzveo.html

split -l 1000 big.log part_
来源：http://dali.xylfe.cn/Article/details/gtwpcqlkej.html

[R74] 批量重命名
来源：http://dali.jianghu66.top/Article/details/gtgdrpgvvu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jqgufenzy.top/Article/details/gtewkwjmew.html

[R75] 导出环境变量
来源：http://dali.ybcxt.top/Article/details/gtetgpjoxt.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hnqzz.top/Article/details/gtkasbzzjo.html

[R76] 使用临时文件
来源：http://dali.zhiwuduotai.top/Article/details/gtspfsljft.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhixingplan.top/Article/details/gthfiukfln.html

[R77] 读取用户输入
来源：http://dali.fengsongda.top/Article/details/gtwcdhhqnw.html

read -rp "请输入: " ans
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkcnajyhr.html

[R78] 交互式菜单
来源：http://dali.ywan-chungtsiang.top/Article/details/gtawzglyht.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhiwuduotai.top/Article/details/gtnmmtdzvh.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gtyjbtlxki.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.aibaodan.cn/Article/details/gtqorsohzr.html

[R80] 查看脚本执行耗时
来源：http://dali.hysaishi.cn/Article/details/gtnrkwaacq.html

time ./run.sh
来源：http://dali.zhaomingkeji.xyz/Article/details/gttxkhsben.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtjyhcwuoc.html

S. C / C++ 专题
来源：http://dali.hywenlv.cn/Article/details/gteifqomwh.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtwzwbuzpd.html

[S01] C：Hello World
来源：http://dali.yangfankeji.com/Article/details/gtfabeeqti.html

#include <stdio.h>
来源：http://dali.gaohongyu789.top/Article/details/gtvqezbzal.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.chenzaomai.com/Article/details/gteyksfoim.html

[S02] C：变量与格式化输出
来源：http://dali.cucudq.cn/Article/details/gthcwhcyay.html

int a = 10; printf("%d\n", a);
来源：http://dali.tian-w.cn/Article/details/gtfoujtyjn.html

[S03] C：读入整数
来源：http://dali.ivvv.top/Article/details/gtxrmknlww.html

int x; scanf("%d", &x);
来源：http://dali.daria6918.cn/Article/details/gtfinhoaoe.html

[S04] C：字符串复制
来源：http://dali.mhx1999.top/Article/details/gtexhbqdkc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jqgfzy.top/Article/details/gtzgqrvrwi.html

[S05] C：字符串长度
来源：http://dali.chenzaomai.com/Article/details/gtvtfxkaqj.html

strlen(s)
来源：http://dali.ehwqpu.com/Article/details/gttbszibbe.html

[S06] C：字符串比较
来源：http://dali.shzxlz.cn/Article/details/gtawybnjqh.html

strcmp(a, b) == 0
来源：http://dali.zhiwuduotai.top/Article/details/gtldjbcbsp.html

[S07] C：数组遍历求和
来源：http://dali.pengpengdd.cyou/Article/details/gtqcybzuog.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.redwolf501.top/Article/details/gtkjhcaedl.html

[S08] C：动态内存分配与释放
来源：http://dali.jinqigfzy.top/Article/details/gtvrxcslfl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hnxiangtu.top/Article/details/gticehrose.html

[S09] C：结构体定义与初始化
来源：http://dali.wangshuangyany.cn/Article/details/gtxiknhavg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yangfankeji.com/Article/details/gttnsdgtfj.html

[S10] C：指针与解引用
来源：http://dali.jiagoushi.top/Article/details/gtkxlijlfj.html

int *p = &a;  *p = 5;
来源：http://dali.nanxinkj.top/Article/details/gtbbsraqyg.html

[S11] C：逐行读文件
来源：http://dali.svipenyu.cn/Article/details/gtnrqlzvfe.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cdnleiting.top/Article/details/gtikooimkz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.tianlin.xyz/Article/details/gtczuqbgvc.html

fclose(f);
来源：http://dali.jiagoushi.top/Article/details/gtwpjzlefj.html

[S12] C：写文件
来源：http://dali.chenjidiqi.icu/Article/details/gtoymmekwb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sufxvd.cn/Article/details/gtqiqgazyi.html

[S13] C：宏定义
来源：http://dali.aibaodan.cn/Article/details/gtzhyocidk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ppjwa.cn/Article/details/gtinolehqk.html

[S14] C：枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkeunkayv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgarkuxbh.html

[S15] C：类型转换
来源：http://dali.haohaochexian.top/Article/details/gtdbtzowsx.html

(double) a / b
来源：http://dali.ydzc1.top/Article/details/gtkxgdoqhx.html

[S16] C：位操作置位
来源：http://dali.feifeiyinyue.top/Article/details/gtwzttaqks.html

x |= (1 << 3);
来源：http://dali.havefunace.top/Article/details/gtosbbkwzu.html

[S17] C：安全拼接字符串
来源：http://dali.daxiang520.top/Article/details/gtfxpxgnfi.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sxryk.cn/Article/details/gtcnvwwspb.html

[S18] C：命令行参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgbbxoowu.html

int main(int argc, char **argv)
来源：http://dali.yj20258888.top/Article/details/gtkletptjh.html

[S19] C：快速排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdfrfetxr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xylfe.cn/Article/details/gtwjcmmexb.html

[S20] C：二分查找
来源：http://dali.dashuyun.cn/Article/details/gtpgqaxanv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cashguo.top/Article/details/gtdelsrmxn.html

[S21] C：字符类别判断
来源：http://dali.hfpthk.cn/Article/details/gtmomdsphk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jlsjyb.cn/Article/details/gtkzhdddrf.html

[S22] C：字符串转数字
来源：http://dali.yongpay.top/Article/details/gtzbekmpuc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yonumen.top/Article/details/gteabrlokj.html

[S23] C：随机数
来源：http://dali.havefunace.top/Article/details/gttzdtnjlf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yangfankeji.com/Article/details/gtxwjavhnz.html

[S24] C：获取本地时间
来源：http://dali.andypj.xyz/Article/details/gtchlmrayo.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbhkmqrou.html

[S25] C：内存拷贝
来源：http://dali.hnxiangtu.top/Article/details/gtwveapliz.html

memcpy(dst, src, n);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtitcsmcbn.html

[S26] C：内存清零
来源：http://dali.xuetiantiany.cn/Article/details/gtbgovxvwb.html

memset(a, 0, sizeof a);
来源：http://dali.ydzc1.top/Article/details/gtcdfvdkwi.html

[S27] C：定义常量
来源：http://dali.fzhhl.top/Article/details/gtkurtogod.html

const double PI = 3.14159;
来源：http://dali.iojbl.cn/Article/details/gtctzfowce.html

[S28] C：静态变量
来源：http://dali.cdnleiting.top/Article/details/gtwlurcmbr.html

static int counter = 0;
来源：http://dali.snrcjt.cn/Article/details/gtlbcpagwh.html

[S29] C：变参函数
来源：http://dali.cucudq.cn/Article/details/gtuzdjzmtw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.bjfxy.top/Article/details/gtteoobojc.html

[S30] C：头文件保护
来源：http://dali.birdmap.top/Article/details/gtgxbgtgvv.html

#ifndef X_H
来源：http://dali.xylfe.cn/Article/details/gthrgmaihu.html

#define X_H
来源：http://dali.gzhubu.top/Article/details/gtzhmvdaev.html

#endif
来源：http://dali.ydzc1.top/Article/details/gtrkqhvotj.html

[S31] C++：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcpqgvgiw.html

#include <iostream>
来源：http://dali.shuidangran.top/Article/details/gtukwyhziy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shangyingyoupin.top/Article/details/gttgnosxec.html

[S32] C++：字符串
来源：http://dali.xinyue.icu/Article/details/gtxctsybxt.html

std::string s = "hi";  s += "!";
来源：http://dali.hfpthk.cn/Article/details/gtcavnnzll.html

[S33] C++：vector 增删
来源：http://dali.yonumen.top/Article/details/gtynexwvoe.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.sysykeji.top/Article/details/gtvuarnale.html

[S34] C++：遍历 vector
来源：http://dali.ydzc1.top/Article/details/gtpxpvybop.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ppjwa.cn/Article/details/gtvpnfkshw.html

[S35] C++：map
来源：http://dali.hywenlv.cn/Article/details/gtcnghgscu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pycfn.com/Article/details/gtjptcgdpo.html

[S36] C++：unordered_map
来源：http://dali.sysykeji.top/Article/details/gttttllpsf.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.andypj.xyz/Article/details/gtbssosflo.html

[S37] C++：set
来源：http://dali.guannengcc.top/Article/details/gtguytwjho.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.dashuyun.cn/Article/details/gthjghiujh.html

[S38] C++：排序
来源：http://dali.0kj1m.cn/Article/details/gtvjyaveew.html

std::sort(v.begin(), v.end());
来源：http://dali.zdqjudy.top/Article/details/gtzgrpnlmb.html

[S39] C++：自定义比较器排序
来源：http://dali.pycfn.com/Article/details/gtnpjbmqbd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.chenlongwang.top/Article/details/gtdrabaqau.html

[S40] C++：查找元素
来源：http://dali.chenlongwang.top/Article/details/gthiopjiay.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.quarkkingdee.top/Article/details/gtftrtzlyd.html

[S41] C++：类与构造函数
来源：http://dali.pycfn.com/Article/details/gtcignrjid.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hywenlv.cn/Article/details/gtqfzhpcon.html

[S42] C++：继承与虚函数
来源：http://dali.svipenyu.cn/Article/details/gtyaxsvrah.html

class B : public Base { public: void f() override {} };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbjiduucm.html

[S43] C++：智能指针
来源：http://dali.shzxlz.cn/Article/details/gtakuhcoot.html

auto p = std::make_unique<int>(5);
来源：http://dali.daxiang520.top/Article/details/gtcgmzsbay.html

[S44] C++：引用传参
来源：http://dali.cucudq.cn/Article/details/gtbbtralic.html

void inc(int &x) { ++x; }
来源：http://dali.9152youxi.cn/Article/details/gtwcuvrlko.html

[S45] C++：lambda
来源：http://dali.vqdsnc.cn/Article/details/gtihvroqsk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jlsjyb.cn/Article/details/gtyvabyigl.html

[S46] C++：函数模板
来源：http://dali.hnxiangtu.top/Article/details/gtzwnfvpec.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.aibaodan.cn/Article/details/gtubtvyymt.html


<!-- 参考信息 -->