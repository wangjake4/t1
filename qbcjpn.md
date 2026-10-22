代发 wailian999

[Q76] 按天统计
来源：http://dali.aibaodan.cn/Article/details/gtcaejitcs.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.fengsongda.top/Article/details/gtdegudifh.html

[Q77] 时间加减
来源：http://dali.zhixingplan.top/Article/details/gtfwlkwkpj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.haohaochexian.top/Article/details/gtxxdtvhbo.html

[Q78] 当前时间
来源：http://dali.cheryme.top/Article/details/gtyscwfkgj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.andypj.xyz/Article/details/gtbjvcvtkr.html

[Q79] 字符串拼接
来源：http://dali.zhongyouzk.top/Article/details/gtpygdpffl.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.birdmap.top/Article/details/gtxqbxrphd.html

[Q80] 字符串截取
来源：http://dali.aibaodan.cn/Article/details/gtbvdtaeln.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hnqzz.top/Article/details/gtauixitfv.html

[Q81] 字符串替换
来源：http://dali.ydzc1.top/Article/details/gtbkeqvdot.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtkqdsnfii.html

[Q82] 字符长度与字节长度
来源：http://dali.zhongyouzk.top/Article/details/gtbpihottk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtrrkzkwen.html

[Q83] 大小写转换
来源：http://dali.9152youxi.cn/Article/details/gtqdtjgzmc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.meibo888.top/Article/details/gtgzkpfkth.html

[Q84] 去除首尾空格
来源：http://dali.pycfn.com/Article/details/gtemppowop.html

SELECT TRIM(name) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtmjocwijb.html

[Q85] 数值取整
来源：http://dali.fzhhl.top/Article/details/gttjblvieo.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.nanxinkj.top/Article/details/gtjpldmkgz.html

[Q86] 读取 JSON 字段
来源：http://dali.wangdashe.top/Article/details/gtgkdudsav.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ehwqpu.com/Article/details/gtahbkdacn.html

[Q87] JSON 字段做条件
来源：http://dali.redwolf501.top/Article/details/gtwsqzvzes.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.mhx1999.top/Article/details/gtxjtikmnd.html

[Q88] 行转列（条件聚合）
来源：http://dali.meibo888.top/Article/details/gtyovmrdfz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.feifeiyinyue.top/Article/details/gtpuefcyhl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ybcxt.top/Article/details/gtytledjkf.html

[Q89] 判断表是否存在
来源：http://dali.iojbl.cn/Article/details/gttmbauvnk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinqigfzy.top/Article/details/gtefpmarum.html

[Q90] 生成序号列
来源：http://dali.9152youxi.cn/Article/details/gtnpvwzzbs.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gzhubu.top/Article/details/gtzvfhmuno.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtincsdxvn.html

R. Bash 专题
来源：http://dali.yj20258888.top/Article/details/gthilxkasx.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtkstpaqvq.html

[R01] shebang 与严格模式
来源：http://dali.dashuyun.cn/Article/details/gtzmrzsjqw.html

#!/usr/bin/env bash
来源：http://dali.hnqzz.top/Article/details/gtygmenkmp.html

set -euo pipefail
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvglbpjqm.html

[R02] 变量赋值与使用
来源：http://dali.nanxuanxn.top/Article/details/gtjhreuajy.html

name="Tom"; echo "$name"
来源：http://dali.kuanghao11.cn/Article/details/gtzvtqyhld.html

[R03] 只读变量
来源：http://dali.jinqigufen.top/Article/details/gtukrrphmh.html

readonly PI=3.14
来源：http://dali.tianlin.xyz/Article/details/gtasfwmwhc.html

[R04] 位置参数
来源：http://dali.hammf.cn/Article/details/gtrsudsilx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xinyue.icu/Article/details/gtcerngzgx.html

[R05] 参数默认值
来源：http://dali.hywenlv.cn/Article/details/gtnjadpfxt.html

name="${1:-default}"
来源：http://dali.sufxvd.cn/Article/details/gtyfvnimqf.html

[R06] 判断命令是否存在
来源：http://dali.xinyue.icu/Article/details/gtnplnqnyh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gtbjajjogl.html

[R07] if 判断文件
来源：http://dali.feifeiyinyue.top/Article/details/gtpskoyxgy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gaohongyu789.top/Article/details/gtfybtvbyr.html

[R08] 数值比较
来源：http://dali.hammf.cn/Article/details/gtdiitussw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cheryme.top/Article/details/gtznpmkuje.html

[R09] 字符串比较
来源：http://dali.bjfxy.top/Article/details/gtrtwnlmmb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.chenzaomai.com/Article/details/gtwrurcznt.html

[R10] 正则匹配
来源：http://dali.birdmap.top/Article/details/gtcyxbhmlw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jinqigfzy.top/Article/details/gtrgnbjvte.html

[R11] case 多分支
来源：http://dali.feifeiyinyue.top/Article/details/gtknfbsegm.html

case "$1" in
来源：http://dali.jianghu66.top/Article/details/gtantbcowd.html

start) echo "启动" ;;
来源：http://dali.andypj.xyz/Article/details/gtrshsfpbk.html

stop)  echo "停止" ;;
来源：http://dali.xuanzx.com/Article/details/gtslixyyjj.html

*)     echo "未知命令" ;;
来源：http://dali.jqgufenzy.top/Article/details/gtrvrqjuzb.html

esac
来源：http://dali.316326.xyz/Article/details/gtoamoogym.html

[R12] for 遍历文件
来源：http://dali.xylfe.cn/Article/details/gthhbprtmi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhongyouzk.top/Article/details/gtdtzfiwlr.html

[R13] for 计数循环
来源：http://dali.9152youxi.cn/Article/details/gtbipmlacl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sysykeji.top/Article/details/gthxsoobeg.html

[R14] C 风格 for
来源：http://dali.shangyingyoupin.top/Article/details/gtnplwmhiz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.tanke756.top/Article/details/gtgvhkvpqo.html

[R15] while 逐行读文件
来源：http://dali.redwolf501.top/Article/details/gthznnzvyw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.aibaodan.cn/Article/details/gtazphanah.html

[R16] until 等待条件
来源：http://dali.cashguo.top/Article/details/gtqvgwpskr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.daria6918.cn/Article/details/gtvefqfebk.html

[R17] 数组定义与取值
来源：http://dali.jlsjyb.cn/Article/details/gtngnkwnqq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.daxiang520.top/Article/details/gtkmdfyvnp.html

[R18] 遍历数组
来源：http://dali.jqgufenzy.top/Article/details/gtfunbiypf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sweek.top/Article/details/gtbhkzkwgc.html

[R19] 数组长度
来源：http://dali.daria6918.cn/Article/details/gthblvscgg.html

echo "${#arr[@]}"
来源：http://dali.ybcxt.top/Article/details/gtipjlnzmq.html

[R20] 关联数组（字典）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaolsgjjq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xinyue.icu/Article/details/gtyobewptg.html

[R21] 字符串长度
来源：http://dali.pycfn.com/Article/details/gtkkcexzqf.html

echo "${#s}"
来源：http://dali.jyoumei.cn/Article/details/gtdwlwifzk.html

[R22] 截取子串
来源：http://dali.vqdsnc.cn/Article/details/gtobhocpun.html

echo "${s:0:5}"
来源：http://dali.daxiang520.top/Article/details/gtudnurdsb.html

[R23] 字符串替换
来源：http://dali.zdqjudy.top/Article/details/gtpxiwhnav.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sweek.top/Article/details/gtvghmdxey.html

[R24] 大小写转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuodmwmzd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jqgufenzy.top/Article/details/gthlmqgksj.html

[R25] 去后缀 / 去前缀
来源：http://dali.gzhubu.top/Article/details/gtilnwyfik.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gttqrohujf.html

[R26] 命令替换
来源：http://dali.yj20258.top/Article/details/gtsdfmascc.html

now=$(date +%F); echo "$now"
来源：http://dali.zhoulong.xyz/Article/details/gtysluefxo.html

[R27] 算术展开
来源：http://dali.kuanghao11.cn/Article/details/gtewrvhmjx.html

echo $((1 + 2 * 3))
来源：http://dali.chenjidiqi.icu/Article/details/gtqkfdutts.html

[R28] 浮点运算
来源：http://dali.zycfv.cn/Article/details/gtoklzglcb.html

echo "scale=2; 10/3" | bc
来源：http://dali.ehwqpu.com/Article/details/gthuysvxer.html

[R29] 定义函数
来源：http://dali.zhixingplan.top/Article/details/gtnjuexcpj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhongyouzk.top/Article/details/gtnrnjgwkp.html

[R30] 函数返回状态码
来源：http://dali.hammf.cn/Article/details/gtaidrucqe.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.andypj.xyz/Article/details/gtbburndxv.html

[R31] 局部变量
来源：http://dali.wangshuangyany.cn/Article/details/gtckzpbpim.html

f() { local x=1; echo "$x"; }
来源：http://dali.chenlongwang.top/Article/details/gthzemxvhp.html

[R32] 参数个数校验
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxvdzvevj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.birdmap.top/Article/details/gtdoffuhha.html

[R33] 捕获错误并提示行号
来源：http://dali.quarkkingdee.top/Article/details/gtlfjqugfp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhixingplan.top/Article/details/gthoofxdhw.html

[R34] 退出时清理
来源：http://dali.ivvv.top/Article/details/gtvlbnaigr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cdnleiting.top/Article/details/gthxlmvubg.html

[R35] 后台执行并等待
来源：http://dali.meibo888.top/Article/details/gtnehloujl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hongshengwenyu.top/Article/details/gtsgomqiim.html

[R36] 并发执行多个任务
来源：http://dali.aibaodan.cn/Article/details/gtrrtbamjg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jianghu66.top/Article/details/gtffvahjtx.html

[R37] 把输出赋给变量
来源：http://dali.tian-w.cn/Article/details/gtgylpawdv.html

files=$(ls -1)
来源：http://dali.shangyingyoupin.top/Article/details/gtretgenbs.html

[R38] 管道串联
来源：http://dali.ydzc1.top/Article/details/gtsquvklwc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinqigufen.top/Article/details/gtnpfxmzqh.html

[R39] 重定向标准输出与错误
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtchgplqoi.html

cmd > out.log 2>&1
来源：http://dali.guowangkeji.top/Article/details/gtkfijcqim.html

[R40] 追加写日志
来源：http://dali.shzxlz.cn/Article/details/gtlfbytvsh.html

echo "log" >> out.log
来源：http://dali.cdnleiting.top/Article/details/gtdsnismhq.html

[R41] 丢弃输出
来源：http://dali.tian-w.cn/Article/details/gtzdcnejpu.html

cmd >/dev/null 2>&1
来源：http://dali.ybcxt.top/Article/details/gtgyiwmzvs.html

[R42] 输入重定向
来源：http://dali.jiagoushi.top/Article/details/gtmwrbroaf.html

wc -l < a.txt
来源：http://dali.jinqigufen.top/Article/details/gtcvbwrcgs.html

[R43] 按名字查找文件
来源：http://dali.sweek.top/Article/details/gthpkjasbh.html

find . -name "*.log" -type f
来源：http://dali.chenjidiqi.icu/Article/details/gtfsnpbzkb.html

[R44] 按修改时间查找
来源：http://dali.cheryme.top/Article/details/gtgermtsev.html

find . -mtime -7 -type f
来源：http://dali.jqgufenzy.top/Article/details/gtsjakjuxl.html

[R45] 批量删除
来源：http://dali.shanyushiyangtech.top/Article/details/gtkwdtlfne.html

find . -name "*.tmp" -delete
来源：http://dali.svipenyu.cn/Article/details/gtawylihfb.html

[R46] 递归替换文件内容
来源：http://dali.cheryme.top/Article/details/gtvdlycjtx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ivvv.top/Article/details/gtuzsgkgah.html

[R47] sed 单行替换
来源：http://dali.zycfv.cn/Article/details/gtqblhgwpt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.sysykeji.top/Article/details/gtnyyriafq.html

[R48] awk 取指定列
来源：http://dali.ehwqpu.com/Article/details/gtwohkokim.html

awk '{print $1, $3}' a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtgsayqnrv.html

[R49] awk 带条件
来源：http://dali.havefunace.top/Article/details/gttnfzswso.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ivvv.top/Article/details/gtklmqomow.html

[R50] awk 求和
来源：http://dali.yvedp.cn/Article/details/gtyngccnxc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cucudq.cn/Article/details/gtsdcywran.html

[R51] 排序去重取前几
来源：http://dali.daria6918.cn/Article/details/gtmtaumfvg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ppjwa.cn/Article/details/gtbtbdigcm.html

[R52] 统计行数
来源：http://dali.chenzaomai.com/Article/details/gtadbfoafm.html

wc -l a.txt
来源：http://dali.hnqzz.top/Article/details/gtlndewkmy.html

[R53] 查看文件头与实时尾
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmqfuefgk.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.chenjidiqi.icu/Article/details/gtgstdumnq.html

[R54] 比较两个文件
来源：http://dali.c1oappe.top/Article/details/gteonimnjz.html

diff a.txt b.txt
来源：http://dali.0kj1m.cn/Article/details/gtchttbcsw.html

[R55] 压缩与解压
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbmllmzwq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.dashuyun.cn/Article/details/gtxflefebn.html

[R56] 远程拷贝
来源：http://dali.sysykeji.top/Article/details/gtdckbyvyo.html

scp file user@host:/path/
来源：http://dali.ehwqpu.com/Article/details/gtnzwxpvcs.html

[R57] 远程执行命令
来源：http://dali.dianchejie.cn/Article/details/gtkyftasza.html

ssh user@host 'uptime'
来源：http://dali.xziqi.cn/Article/details/gtuvnkszum.html

[R58] 下载文件
来源：http://dali.nanxinkj.top/Article/details/gtqnkiwysv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cucudq.cn/Article/details/gtisspwpyh.html

[R59] 发 POST JSON
来源：http://dali.ppjwa.cn/Article/details/gtfpyvidhv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.guowangkeji.top/Article/details/gttahxrndf.html

[R60] 只看 HTTP 状态码
来源：http://dali.sysykeji.top/Article/details/gtikpoldqy.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ybcxt.top/Article/details/gtldhajrck.html

[R61] 磁盘占用
来源：http://dali.shzxlz.cn/Article/details/gtvufbasrb.html

df -h;  du -sh *
来源：http://dali.quarkkingdee.top/Article/details/gtotipinir.html

[R62] 找最占空间的文件
来源：http://dali.guannengcc.top/Article/details/gtfuajxssb.html

du -ah . | sort -rh | head -10
来源：http://dali.gzhubu.top/Article/details/gtsdzctged.html

[R63] 内存与进程
来源：http://dali.9152youxi.cn/Article/details/gtxmzovaip.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gtvmoyaswf.html

[R64] 结束进程
来源：http://dali.chenzaomai.com/Article/details/gtceuncfvx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xziqi.cn/Article/details/gtsoqvnvvk.html

[R65] 查看端口占用
来源：http://dali.xziqi.cn/Article/details/gtoztynhlu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hywenlv.cn/Article/details/gtyeqvtoye.html

[R66] 定时任务
来源：http://dali.yj20258.top/Article/details/gtzknhincq.html

crontab -e;  crontab -l
来源：http://dali.hfpthk.cn/Article/details/gtagmgegqu.html

[R67] 生成随机十六进制串
来源：http://dali.xinyue.icu/Article/details/gtzeghkbni.html

openssl rand -hex 16
来源：http://dali.yj20258888.top/Article/details/gtjlfigxhz.html

[R68] 计算文件校验值
来源：http://dali.hysaishi.cn/Article/details/gtlrlixtow.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yvedp.cn/Article/details/gtnnfjsgeh.html

[R69] 生成随机密码
来源：http://dali.pengpengdd.cyou/Article/details/gtgethoddd.html

head -c 16 /dev/urandom | base64
来源：http://dali.guannengcc.top/Article/details/gtqcisjdwt.html

[R70] 时间戳与互转
来源：http://dali.zhixingplan.top/Article/details/gtwrixehqo.html

date +%s;  date -d @1700000000
来源：http://dali.yanxiufei.cn/Article/details/gtkxrdqyie.html

[R71] 日期格式化
来源：http://dali.kuanghao11.cn/Article/details/gtbfkwtrjx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ppjwa.cn/Article/details/gtsjvzwdun.html

[R72] 等待端口就绪
来源：http://dali.yj202588.top/Article/details/gtlvjtdnvp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.dashuyun.cn/Article/details/gtafhbcvsp.html

[R73] 分割大日志
来源：http://dali.chenlongwang.top/Article/details/gtjljeghwo.html

split -l 1000 big.log part_
来源：http://dali.fengsongda.top/Article/details/gtbyqutjmb.html

[R74] 批量重命名
来源：http://dali.ehwqpu.com/Article/details/gtpfctierr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shuidangran.top/Article/details/gthduaidiq.html

[R75] 导出环境变量
来源：http://dali.zhengqikj.top/Article/details/gthjafnsvx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.haohaochexian.top/Article/details/gtdtlktvjg.html

[R76] 使用临时文件
来源：http://dali.yvedp.cn/Article/details/gtvhalhdxh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.haohaochexian.top/Article/details/gtrljratfd.html

[R77] 读取用户输入
来源：http://dali.yonumen.top/Article/details/gtaoqzchzo.html

read -rp "请输入: " ans
来源：http://dali.xuetiantiany.cn/Article/details/gthtfpihgd.html

[R78] 交互式菜单
来源：http://dali.cucudq.cn/Article/details/gtrdueniqv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.gotoacloud.top/Article/details/gtzpesgxad.html

[R79] 解析命令行选项
来源：http://dali.hywenlv.cn/Article/details/gtujmpkbjk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shzxlz.cn/Article/details/gtqxrwyvrw.html

[R80] 查看脚本执行耗时
来源：http://dali.gaohongyu789.top/Article/details/gtksbdronb.html

time ./run.sh
来源：http://dali.jinqigufen.top/Article/details/gtuykcpwdx.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtkfllzcrb.html

S. C / C++ 专题
来源：http://dali.jinghuilouyu.cn/Article/details/gtcrksecjc.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtfefaalpg.html

[S01] C：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlzobwxhv.html

#include <stdio.h>
来源：http://dali.jlsjyb.cn/Article/details/gtpvmrreou.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlhqjssep.html

[S02] C：变量与格式化输出
来源：http://dali.aibaodan.cn/Article/details/gtyayerkcb.html

int a = 10; printf("%d\n", a);
来源：http://dali.dashuyun.cn/Article/details/gtnsnytrwq.html

[S03] C：读入整数
来源：http://dali.nanxuanxn.top/Article/details/gthvzdytwh.html

int x; scanf("%d", &x);
来源：http://dali.pycfn.com/Article/details/gtvitwzkra.html

[S04] C：字符串复制
来源：http://dali.shanyushiyangtech.top/Article/details/gtpwcgcrhg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.bjfxy.top/Article/details/gtydqrohme.html

[S05] C：字符串长度
来源：http://dali.ppjwa.cn/Article/details/gtdutbmyeb.html

strlen(s)
来源：http://dali.cucudq.cn/Article/details/gthbgbsyqk.html

[S06] C：字符串比较
来源：http://dali.yuanzhike.top/Article/details/gtvmauyacb.html

strcmp(a, b) == 0
来源：http://dali.gzhubu.top/Article/details/gtzwuiouso.html

[S07] C：数组遍历求和
来源：http://dali.daria6918.cn/Article/details/gtlrdzrmri.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.snrcjt.cn/Article/details/gtofmkmdyg.html

[S08] C：动态内存分配与释放
来源：http://dali.yuanzhike.top/Article/details/gtkimuvpry.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.iojbl.cn/Article/details/gtrnlmautl.html

[S09] C：结构体定义与初始化
来源：http://dali.sxryk.cn/Article/details/gtjpfmnbiz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.quarkkingdee.top/Article/details/gtgfzrcuve.html

[S10] C：指针与解引用
来源：http://dali.jiagoushi.top/Article/details/gtoimlcsgs.html

int *p = &a;  *p = 5;
来源：http://dali.haohaochexian.top/Article/details/gtikmvpywn.html

[S11] C：逐行读文件
来源：http://dali.chenjidiqi.icu/Article/details/gtwjtcibab.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.snrcjt.cn/Article/details/gtxzahohvn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhoulong.xyz/Article/details/gtmisurtiq.html

fclose(f);
来源：http://dali.xuanzx.com/Article/details/gtusgqwniq.html

[S12] C：写文件
来源：http://dali.wangdashe.top/Article/details/gtqztknaom.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xziqi.cn/Article/details/gtawrpcsjj.html

[S13] C：宏定义
来源：http://dali.cqqwz.cn/Article/details/gtsmrzirxu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jiagoushi.top/Article/details/gtvmdfukyd.html

[S14] C：枚举
来源：http://dali.nwbrower.top/Article/details/gtecdupbze.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.quarkkingdee.top/Article/details/gtwhonfhxk.html

[S15] C：类型转换
来源：http://dali.dianchejie.cn/Article/details/gtqpufqpej.html

(double) a / b
来源：http://dali.nanxuanxn.top/Article/details/gtanzltxjw.html

[S16] C：位操作置位
来源：http://dali.jinqigfzy.top/Article/details/gtsyoesujl.html

x |= (1 << 3);
来源：http://dali.aibaodan.cn/Article/details/gtgrpaffkl.html

[S17] C：安全拼接字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsbwpkpzw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.wangdashe.top/Article/details/gtxknkbsbn.html

[S18] C：命令行参数
来源：http://dali.pycfn.com/Article/details/gtdwrkajvt.html

int main(int argc, char **argv)
来源：http://dali.birdmap.top/Article/details/gtzccswywu.html

[S19] C：快速排序
来源：http://dali.dianchejie.cn/Article/details/gtzwaaudtx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ehwqpu.com/Article/details/gttnrxlipb.html

[S20] C：二分查找
来源：http://dali.havefunace.top/Article/details/gthuimucnd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhengqikj.top/Article/details/gthiingjmk.html

[S21] C：字符类别判断
来源：http://dali.fengsongda.top/Article/details/gtjhleqnuc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhoulong.xyz/Article/details/gtfaatvink.html

[S22] C：字符串转数字
来源：http://dali.jinqigufen.top/Article/details/gtyhjormie.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zycfv.cn/Article/details/gtpadzcawg.html

[S23] C：随机数
来源：http://dali.ybcxt.top/Article/details/gtsnfuybtq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.wangshuangyany.cn/Article/details/gtuynnjlfs.html

[S24] C：获取本地时间
来源：http://dali.ppjwa.cn/Article/details/gtzcwnwlpl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cashguo.top/Article/details/gtmatwjvgj.html

[S25] C：内存拷贝
来源：http://dali.cashguo.top/Article/details/gtjxelvxcp.html

memcpy(dst, src, n);
来源：http://dali.ehwqpu.com/Article/details/gtglsijkxz.html

[S26] C：内存清零
来源：http://dali.chenlongwang.top/Article/details/gtoxkyxbha.html

memset(a, 0, sizeof a);
来源：http://dali.jinghuilouyu.cn/Article/details/gttvvwydvf.html

[S27] C：定义常量
来源：http://dali.nwbrower.top/Article/details/gtmoanvnbk.html

const double PI = 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gteeutpvka.html

[S28] C：静态变量
来源：http://dali.zhengqikj.top/Article/details/gtfrsdwxms.html

static int counter = 0;
来源：http://dali.shangyingyoupin.top/Article/details/gtxwrvpshg.html

[S29] C：变参函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoseuwhyi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.tanke756.top/Article/details/gtiazhpulo.html

[S30] C：头文件保护
来源：http://dali.hfpthk.cn/Article/details/gtuifglubg.html

#ifndef X_H
来源：http://dali.yj20258888.top/Article/details/gtshlcjmuj.html

#define X_H
来源：http://dali.dianchejie.cn/Article/details/gtfvixcivc.html

#endif
来源：http://dali.havefunace.top/Article/details/gtoxponpaj.html

[S31] C++：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtextneuiz.html

#include <iostream>
来源：http://dali.yonumen.top/Article/details/gtiqpzejhh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jiagoushi.top/Article/details/gtljyporar.html

[S32] C++：字符串
来源：http://dali.dianchejie.cn/Article/details/gtgoflulmb.html

std::string s = "hi";  s += "!";
来源：http://dali.chenjidiqi.icu/Article/details/gtetxclqsv.html

[S33] C++：vector 增删
来源：http://dali.wangshuangyany.cn/Article/details/gtliwuiike.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cheryme.top/Article/details/gtbvbfhzrf.html

[S34] C++：遍历 vector
来源：http://dali.chenlongwang.top/Article/details/gtorbgqtki.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.meibo888.top/Article/details/gtvllbqetj.html

[S35] C++：map
来源：http://dali.c1oappe.top/Article/details/gthjgzqikg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzufumqdb.html

[S36] C++：unordered_map
来源：http://dali.jinqigfzy.top/Article/details/gtprvppnck.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shuidangran.top/Article/details/gtynufpsng.html

[S37] C++：set
来源：http://dali.fzhhl.top/Article/details/gtfmkkkaay.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shangyingyoupin.top/Article/details/gtuqufailc.html

[S38] C++：排序
来源：http://dali.havefunace.top/Article/details/gtrgxjuuhv.html

std::sort(v.begin(), v.end());
来源：http://dali.zhongyouzk.top/Article/details/gtdwxkcgge.html

[S39] C++：自定义比较器排序
来源：http://dali.shangyingyoupin.top/Article/details/gtdppwdwnk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.dashuyun.cn/Article/details/gtgtkwrlff.html

[S40] C++：查找元素
来源：http://dali.cheryme.top/Article/details/gtgalxmcyp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhengqikj.top/Article/details/gtcmrhjjzw.html

[S41] C++：类与构造函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtskqpnxrz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgdsnybto.html

[S42] C++：继承与虚函数
来源：http://dali.ehwqpu.com/Article/details/gtrhqxjbxm.html

class B : public Base { public: void f() override {} };
来源：http://dali.guowangkeji.top/Article/details/gtercnxhvp.html

[S43] C++：智能指针
来源：http://dali.ehwqpu.com/Article/details/gtjllxyofu.html

auto p = std::make_unique<int>(5);
来源：http://dali.ybcxt.top/Article/details/gtuojifgvl.html

[S44] C++：引用传参
来源：http://dali.316326.xyz/Article/details/gtcggloyqn.html

void inc(int &x) { ++x; }
来源：http://dali.snrcjt.cn/Article/details/gtjarpofsj.html

[S45] C++：lambda
来源：http://dali.guowangkeji.top/Article/details/gtyfqkhtus.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.316326.xyz/Article/details/gtnthpcmge.html

[S46] C++：函数模板
来源：http://dali.chenzaomai.com/Article/details/gtqjyzrljr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.nwbrower.top/Article/details/gtnjyimkrz.html


<!-- 参考信息 -->